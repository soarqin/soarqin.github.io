+++
title = '【直播工具】直播时用foobar2000 64位版播放音乐实时同步显示当前播放歌曲教程'
date = 2024-01-15T15:24:04+08:00
draft = false
+++
# 前言
#### foobar2000 2.0发布后增加了64位版本，导致以前32位版本的now playing simple组件无法使用。
#### 本文介绍一个新的解决方案。
<!--more-->
# 安装JScript Panel 3
1. 从[这里](https://github.com/jscript-panel/release/releases)下载最新版JScript Panel 3
2. 启动foobar2000后从File->Preferences->Components里点击Install...按钮安装此组件(也可以直接把这个组件拖到组件列表框里)
# 添加一个JScript Panel
1. View->Layout->Enable layout editing mode 启用界面编辑模式
2. 右键点击播放列表->Replace UI Element...，从两个Splitter里随便选择一个
3. 左键单击新出现的空白部分，选择JScript Panel 3
# 在JScript Panel组件上编写脚本
1. 左键单击JScript Panel 3组件部分(如果要再次修改需要在右键菜单选择Configure)，复制以下脚本替换默认脚本：
```javascript
// ==PREPROCESSOR==
// @import "%fb2k_component_path%samples\js\lodash.min.js"
// ==/PREPROCESSOR==

var tfo = fb.TitleFormat("[%artist% - ]%title%");
var path = "D:\\fb2k_music.txt";

/////////////////////////////////////////////////////////////////////////////////////////////////////////

function on_playback_new_track() {
    log_it();
}

function on_playback_dynamic_info_track(type) {
    if (type == 0) {
        log_it();
    }
}

function on_playback_stop(reason) {
    if (reason == 0 || reason == 1) {
        log_it();
    }
}

function on_playback_pause(state) {
    log_it();
}

function log_it() {
    utils.WriteTextFile(path, !fb.IsPlaying ? "[已停止]" : (fb.IsPaused ? "[已暂停]" : "[播放中]")
        + " " + tfo.Eval());
}
```
2. 你可以修改tfo, path以及log_it的函数体来改变输出格式和输出文件路径
3. 在OBS或者你用的对应直播工具里添加一个文本控件，选择读取这个输出的txt文件，然后编辑文本格式等，即可完成直播时的当前播放歌曲实时显示

以上就是本教程的全部内容，希望能帮到还在坚持用foobar2000的播主！
