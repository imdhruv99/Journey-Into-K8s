<!DOCTYPE html>
<!-- saved from url=(0021)https://dillinger.io/ -->
<html lang="en" ng-strict-di=""><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><style type="text/css">@charset "UTF-8";[ng\:cloak],[ng-cloak],[data-ng-cloak],[x-ng-cloak],.ng-cloak,.x-ng-cloak,.ng-hide:not(.ng-hide-animate){display:none !important;}ng\:form{display:block;}.ng-animate-shim{visibility:hidden;}.ng-anchor{position:absolute;}</style>

<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
<title>Online Markdown Editor - Dillinger, the Last Markdown Editor ever.</title>
<meta name="description" content="Dillinger is an online cloud based HTML5 filled
  Markdown Editor. Sync with Dropbox, Github, Google Drive or OneDrive.
  Convert HTML to Markdown. 100% Open Source!">
<meta name="keywords" content="Markdown, Dillinger, Editor, ACE, Github, Open Source, Node.js">
<meta name="author" content="Joe McCann and Martin Broder">
<link rel="apple-touch-icon" href="https://dillinger.io/apple-touch-icon.png">


<meta name="robots" content="noodp, noydir">

<meta name="google-site-verification" content="DAyGOgtsg8rJpq9VVktKzDkQ1UhXm1FYl8SD47hPkjA">

<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no, maximum-scale=1, minimum-scale=1">
<meta name="HandheldFriendly" content="true">
<meta name="MobileOptimized" content="320">
<meta http-equiv="cleartype" content="on">
<link href="./README_files/css" rel="stylesheet" type="text/css">
<link href="./README_files/css(1)" rel="stylesheet" type="text/css">
<link href="./README_files/app.css" rel="stylesheet">
<script type="text/javascript">
   var trackOutboundLink = function(url) {
    ga('send', 'event', 'outbound', 'click', url, {
      'transport': 'beacon',
      'hitCallback': function(){window.open(url);}
    });
    }
  </script>
<div id="_bsa_srv-CVADP53W_0"></div><style id="ace_editor.css">.ace_editor {position: relative;overflow: hidden;font: 12px/normal 'Monaco', 'Menlo', 'Ubuntu Mono', 'Consolas', 'source-code-pro', monospace;direction: ltr;text-align: left;-webkit-tap-highlight-color: rgba(0, 0, 0, 0);}.ace_scroller {position: absolute;overflow: hidden;top: 0;bottom: 0;background-color: inherit;-ms-user-select: none;-moz-user-select: none;-webkit-user-select: none;user-select: none;cursor: text;}.ace_content {position: absolute;-moz-box-sizing: border-box;-webkit-box-sizing: border-box;box-sizing: border-box;min-width: 100%;}.ace_dragging .ace_scroller:before{position: absolute;top: 0;left: 0;right: 0;bottom: 0;content: '';background: rgba(250, 250, 250, 0.01);z-index: 1000;}.ace_dragging.ace_dark .ace_scroller:before{background: rgba(0, 0, 0, 0.01);}.ace_selecting, .ace_selecting * {cursor: text !important;}.ace_gutter {position: absolute;overflow : hidden;width: auto;top: 0;bottom: 0;left: 0;cursor: default;z-index: 4;-ms-user-select: none;-moz-user-select: none;-webkit-user-select: none;user-select: none;}.ace_gutter-active-line {position: absolute;left: 0;right: 0;}.ace_scroller.ace_scroll-left {box-shadow: 17px 0 16px -16px rgba(0, 0, 0, 0.4) inset;}.ace_gutter-cell {padding-left: 19px;padding-right: 6px;background-repeat: no-repeat;}.ace_gutter-cell.ace_error {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAABOFBMVEX/////////QRswFAb/Ui4wFAYwFAYwFAaWGAfDRymzOSH/PxswFAb/SiUwFAYwFAbUPRvjQiDllog5HhHdRybsTi3/Tyv9Tir+Syj/UC3////XurebMBIwFAb/RSHbPx/gUzfdwL3kzMivKBAwFAbbvbnhPx66NhowFAYwFAaZJg8wFAaxKBDZurf/RB6mMxb/SCMwFAYwFAbxQB3+RB4wFAb/Qhy4Oh+4QifbNRcwFAYwFAYwFAb/QRzdNhgwFAYwFAbav7v/Uy7oaE68MBK5LxLewr/r2NXewLswFAaxJw4wFAbkPRy2PyYwFAaxKhLm1tMwFAazPiQwFAaUGAb/QBrfOx3bvrv/VC/maE4wFAbRPBq6MRO8Qynew8Dp2tjfwb0wFAbx6eju5+by6uns4uH9/f36+vr/GkHjAAAAYnRSTlMAGt+64rnWu/bo8eAA4InH3+DwoN7j4eLi4xP99Nfg4+b+/u9B/eDs1MD1mO7+4PHg2MXa347g7vDizMLN4eG+Pv7i5evs/v79yu7S3/DV7/498Yv24eH+4ufQ3Ozu/v7+y13sRqwAAADLSURBVHjaZc/XDsFgGIBhtDrshlitmk2IrbHFqL2pvXf/+78DPokj7+Fz9qpU/9UXJIlhmPaTaQ6QPaz0mm+5gwkgovcV6GZzd5JtCQwgsxoHOvJO15kleRLAnMgHFIESUEPmawB9ngmelTtipwwfASilxOLyiV5UVUyVAfbG0cCPHig+GBkzAENHS0AstVF6bacZIOzgLmxsHbt2OecNgJC83JERmePUYq8ARGkJx6XtFsdddBQgZE2nPR6CICZhawjA4Fb/chv+399kfR+MMMDGOQAAAABJRU5ErkJggg==");background-repeat: no-repeat;background-position: 2px center;}.ace_gutter-cell.ace_warning {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAAAmVBMVEX///8AAAD///8AAAAAAABPSzb/5sAAAAB/blH/73z/ulkAAAAAAAD85pkAAAAAAAACAgP/vGz/rkDerGbGrV7/pkQICAf////e0IsAAAD/oED/qTvhrnUAAAD/yHD/njcAAADuv2r/nz//oTj/p064oGf/zHAAAAA9Nir/tFIAAAD/tlTiuWf/tkIAAACynXEAAAAAAAAtIRW7zBpBAAAAM3RSTlMAABR1m7RXO8Ln31Z36zT+neXe5OzooRDfn+TZ4p3h2hTf4t3k3ucyrN1K5+Xaks52Sfs9CXgrAAAAjklEQVR42o3PbQ+CIBQFYEwboPhSYgoYunIqqLn6/z8uYdH8Vmdnu9vz4WwXgN/xTPRD2+sgOcZjsge/whXZgUaYYvT8QnuJaUrjrHUQreGczuEafQCO/SJTufTbroWsPgsllVhq3wJEk2jUSzX3CUEDJC84707djRc5MTAQxoLgupWRwW6UB5fS++NV8AbOZgnsC7BpEAAAAABJRU5ErkJggg==");background-position: 2px center;}.ace_gutter-cell.ace_info {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAAAAAA6mKC9AAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAAJ0Uk5TAAB2k804AAAAPklEQVQY02NgIB68QuO3tiLznjAwpKTgNyDbMegwisCHZUETUZV0ZqOquBpXj2rtnpSJT1AEnnRmL2OgGgAAIKkRQap2htgAAAAASUVORK5CYII=");background-position: 2px center;}.ace_dark .ace_gutter-cell.ace_info {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQBAMAAADt3eJSAAAAJFBMVEUAAAChoaGAgIAqKiq+vr6tra1ZWVmUlJSbm5s8PDxubm56enrdgzg3AAAAAXRSTlMAQObYZgAAAClJREFUeNpjYMAPdsMYHegyJZFQBlsUlMFVCWUYKkAZMxZAGdxlDMQBAG+TBP4B6RyJAAAAAElFTkSuQmCC");}.ace_scrollbar {position: absolute;right: 0;bottom: 0;z-index: 6;}.ace_scrollbar-inner {position: absolute;cursor: text;left: 0;top: 0;}.ace_scrollbar-v{overflow-x: hidden;overflow-y: scroll;top: 0;}.ace_scrollbar-h {overflow-x: scroll;overflow-y: hidden;left: 0;}.ace_print-margin {position: absolute;height: 100%;}.ace_text-input {position: absolute;z-index: 0;width: 0.5em;height: 1em;opacity: 0;background: transparent;-moz-appearance: none;appearance: none;border: none;resize: none;outline: none;overflow: hidden;font: inherit;padding: 0 1px;margin: 0 -1px;text-indent: -1em;-ms-user-select: text;-moz-user-select: text;-webkit-user-select: text;user-select: text;white-space: pre!important;}.ace_text-input.ace_composition {background: inherit;color: inherit;z-index: 1000;opacity: 1;text-indent: 0;}.ace_layer {z-index: 1;position: absolute;overflow: hidden;word-wrap: normal;white-space: pre;height: 100%;width: 100%;-moz-box-sizing: border-box;-webkit-box-sizing: border-box;box-sizing: border-box;pointer-events: none;}.ace_gutter-layer {position: relative;width: auto;text-align: right;pointer-events: auto;}.ace_text-layer {font: inherit !important;}.ace_cjk {display: inline-block;text-align: center;}.ace_cursor-layer {z-index: 4;}.ace_cursor {z-index: 4;position: absolute;-moz-box-sizing: border-box;-webkit-box-sizing: border-box;box-sizing: border-box;border-left: 2px solid;transform: translatez(0);}.ace_multiselect .ace_cursor {border-left-width: 1px;}.ace_slim-cursors .ace_cursor {border-left-width: 1px;}.ace_overwrite-cursors .ace_cursor {border-left-width: 0;border-bottom: 1px solid;}.ace_hidden-cursors .ace_cursor {opacity: 0.2;}.ace_smooth-blinking .ace_cursor {-webkit-transition: opacity 0.18s;transition: opacity 0.18s;}.ace_marker-layer .ace_step, .ace_marker-layer .ace_stack {position: absolute;z-index: 3;}.ace_marker-layer .ace_selection {position: absolute;z-index: 5;}.ace_marker-layer .ace_bracket {position: absolute;z-index: 6;}.ace_marker-layer .ace_active-line {position: absolute;z-index: 2;}.ace_marker-layer .ace_selected-word {position: absolute;z-index: 4;-moz-box-sizing: border-box;-webkit-box-sizing: border-box;box-sizing: border-box;}.ace_line .ace_fold {-moz-box-sizing: border-box;-webkit-box-sizing: border-box;box-sizing: border-box;display: inline-block;height: 11px;margin-top: -2px;vertical-align: middle;background-image:url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABEAAAAJCAYAAADU6McMAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAJpJREFUeNpi/P//PwOlgAXGYGRklAVSokD8GmjwY1wasKljQpYACtpCFeADcHVQfQyMQAwzwAZI3wJKvCLkfKBaMSClBlR7BOQikCFGQEErIH0VqkabiGCAqwUadAzZJRxQr/0gwiXIal8zQQPnNVTgJ1TdawL0T5gBIP1MUJNhBv2HKoQHHjqNrA4WO4zY0glyNKLT2KIfIMAAQsdgGiXvgnYAAAAASUVORK5CYII="),url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAA3CAYAAADNNiA5AAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAACJJREFUeNpi+P//fxgTAwPDBxDxD078RSX+YeEyDFMCIMAAI3INmXiwf2YAAAAASUVORK5CYII=");background-repeat: no-repeat, repeat-x;background-position: center center, top left;color: transparent;border: 1px solid black;border-radius: 2px;cursor: pointer;pointer-events: auto;}.ace_dark .ace_fold {}.ace_fold:hover{background-image:url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABEAAAAJCAYAAADU6McMAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAJpJREFUeNpi/P//PwOlgAXGYGRklAVSokD8GmjwY1wasKljQpYACtpCFeADcHVQfQyMQAwzwAZI3wJKvCLkfKBaMSClBlR7BOQikCFGQEErIH0VqkabiGCAqwUadAzZJRxQr/0gwiXIal8zQQPnNVTgJ1TdawL0T5gBIP1MUJNhBv2HKoQHHjqNrA4WO4zY0glyNKLT2KIfIMAAQsdgGiXvgnYAAAAASUVORK5CYII="),url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAA3CAYAAADNNiA5AAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAACBJREFUeNpi+P//fz4TAwPDZxDxD5X4i5fLMEwJgAADAEPVDbjNw87ZAAAAAElFTkSuQmCC");}.ace_tooltip {background-color: #FFF;background-image: -webkit-linear-gradient(top, transparent, rgba(0, 0, 0, 0.1));background-image: linear-gradient(to bottom, transparent, rgba(0, 0, 0, 0.1));border: 1px solid gray;border-radius: 1px;box-shadow: 0 1px 2px rgba(0, 0, 0, 0.3);color: black;max-width: 100%;padding: 3px 4px;position: fixed;z-index: 999999;-moz-box-sizing: border-box;-webkit-box-sizing: border-box;box-sizing: border-box;cursor: default;white-space: pre;word-wrap: break-word;line-height: normal;font-style: normal;font-weight: normal;letter-spacing: normal;pointer-events: none;}.ace_folding-enabled > .ace_gutter-cell {padding-right: 13px;}.ace_fold-widget {-moz-box-sizing: border-box;-webkit-box-sizing: border-box;box-sizing: border-box;margin: 0 -12px 0 1px;display: none;width: 11px;vertical-align: top;background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAUAAAAFCAYAAACNbyblAAAANElEQVR42mWKsQ0AMAzC8ixLlrzQjzmBiEjp0A6WwBCSPgKAXoLkqSot7nN3yMwR7pZ32NzpKkVoDBUxKAAAAABJRU5ErkJggg==");background-repeat: no-repeat;background-position: center;border-radius: 3px;border: 1px solid transparent;cursor: pointer;}.ace_folding-enabled .ace_fold-widget {display: inline-block;   }.ace_fold-widget.ace_end {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAUAAAAFCAYAAACNbyblAAAANElEQVR42m3HwQkAMAhD0YzsRchFKI7sAikeWkrxwScEB0nh5e7KTPWimZki4tYfVbX+MNl4pyZXejUO1QAAAABJRU5ErkJggg==");}.ace_fold-widget.ace_closed {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAMAAAAGCAYAAAAG5SQMAAAAOUlEQVR42jXKwQkAMAgDwKwqKD4EwQ26sSOkVWjgIIHAzPiCgaqiqnJHZnKICBERHN194O5b9vbLuAVRL+l0YWnZAAAAAElFTkSuQmCCXA==");}.ace_fold-widget:hover {border: 1px solid rgba(0, 0, 0, 0.3);background-color: rgba(255, 255, 255, 0.2);box-shadow: 0 1px 1px rgba(255, 255, 255, 0.7);}.ace_fold-widget:active {border: 1px solid rgba(0, 0, 0, 0.4);background-color: rgba(0, 0, 0, 0.05);box-shadow: 0 1px 1px rgba(255, 255, 255, 0.8);}.ace_dark .ace_fold-widget {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAUAAAAFCAYAAACNbyblAAAAHklEQVQIW2P4//8/AzoGEQ7oGCaLLAhWiSwB146BAQCSTPYocqT0AAAAAElFTkSuQmCC");}.ace_dark .ace_fold-widget.ace_end {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAUAAAAFCAYAAACNbyblAAAAH0lEQVQIW2P4//8/AxQ7wNjIAjDMgC4AxjCVKBirIAAF0kz2rlhxpAAAAABJRU5ErkJggg==");}.ace_dark .ace_fold-widget.ace_closed {background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAMAAAAFCAYAAACAcVaiAAAAHElEQVQIW2P4//+/AxAzgDADlOOAznHAKgPWAwARji8UIDTfQQAAAABJRU5ErkJggg==");}.ace_dark .ace_fold-widget:hover {box-shadow: 0 1px 1px rgba(255, 255, 255, 0.2);background-color: rgba(255, 255, 255, 0.1);}.ace_dark .ace_fold-widget:active {box-shadow: 0 1px 1px rgba(255, 255, 255, 0.2);}.ace_fold-widget.ace_invalid {background-color: #FFB4B4;border-color: #DE5555;}.ace_fade-fold-widgets .ace_fold-widget {-webkit-transition: opacity 0.4s ease 0.05s;transition: opacity 0.4s ease 0.05s;opacity: 0;}.ace_fade-fold-widgets:hover .ace_fold-widget {-webkit-transition: opacity 0.05s ease 0.05s;transition: opacity 0.05s ease 0.05s;opacity:1;}.ace_underline {text-decoration: underline;}.ace_bold {font-weight: bold;}.ace_nobold .ace_bold {font-weight: normal;}.ace_italic {font-style: italic;}.ace_error-marker {background-color: rgba(255, 0, 0,0.2);position: absolute;z-index: 9;}.ace_highlight-marker {background-color: rgba(255, 255, 0,0.2);position: absolute;z-index: 8;}.ace_br1 {border-top-left-radius    : 3px;}.ace_br2 {border-top-right-radius   : 3px;}.ace_br3 {border-top-left-radius    : 3px; border-top-right-radius:    3px;}.ace_br4 {border-bottom-right-radius: 3px;}.ace_br5 {border-top-left-radius    : 3px; border-bottom-right-radius: 3px;}.ace_br6 {border-top-right-radius   : 3px; border-bottom-right-radius: 3px;}.ace_br7 {border-top-left-radius    : 3px; border-top-right-radius:    3px; border-bottom-right-radius: 3px;}.ace_br8 {border-bottom-left-radius : 3px;}.ace_br9 {border-top-left-radius    : 3px; border-bottom-left-radius:  3px;}.ace_br10{border-top-right-radius   : 3px; border-bottom-left-radius:  3px;}.ace_br11{border-top-left-radius    : 3px; border-top-right-radius:    3px; border-bottom-left-radius:  3px;}.ace_br12{border-bottom-right-radius: 3px; border-bottom-left-radius:  3px;}.ace_br13{border-top-left-radius    : 3px; border-bottom-right-radius: 3px; border-bottom-left-radius:  3px;}.ace_br14{border-top-right-radius   : 3px; border-bottom-right-radius: 3px; border-bottom-left-radius:  3px;}.ace_br15{border-top-left-radius    : 3px; border-top-right-radius:    3px; border-bottom-right-radius: 3px; border-bottom-left-radius: 3px;}.ace_text-input-ios {position: absolute !important;top: -100000px !important;left: -100000px !important;}
/*# sourceURL=ace/css/ace_editor.css */</style><style id="ace-tm">.ace-tm .ace_gutter {background: #f0f0f0;color: #333;}.ace-tm .ace_print-margin {width: 1px;background: #e8e8e8;}.ace-tm .ace_fold {background-color: #6B72E6;}.ace-tm {background-color: #FFFFFF;color: black;}.ace-tm .ace_cursor {color: black;}.ace-tm .ace_invisible {color: rgb(191, 191, 191);}.ace-tm .ace_storage,.ace-tm .ace_keyword {color: blue;}.ace-tm .ace_constant {color: rgb(197, 6, 11);}.ace-tm .ace_constant.ace_buildin {color: rgb(88, 72, 246);}.ace-tm .ace_constant.ace_language {color: rgb(88, 92, 246);}.ace-tm .ace_constant.ace_library {color: rgb(6, 150, 14);}.ace-tm .ace_invalid {background-color: rgba(255, 0, 0, 0.1);color: red;}.ace-tm .ace_support.ace_function {color: rgb(60, 76, 114);}.ace-tm .ace_support.ace_constant {color: rgb(6, 150, 14);}.ace-tm .ace_support.ace_type,.ace-tm .ace_support.ace_class {color: rgb(109, 121, 222);}.ace-tm .ace_keyword.ace_operator {color: rgb(104, 118, 135);}.ace-tm .ace_string {color: rgb(3, 106, 7);}.ace-tm .ace_comment {color: rgb(76, 136, 107);}.ace-tm .ace_comment.ace_doc {color: rgb(0, 102, 255);}.ace-tm .ace_comment.ace_doc.ace_tag {color: rgb(128, 159, 191);}.ace-tm .ace_constant.ace_numeric {color: rgb(0, 0, 205);}.ace-tm .ace_variable {color: rgb(49, 132, 149);}.ace-tm .ace_xml-pe {color: rgb(104, 104, 91);}.ace-tm .ace_entity.ace_name.ace_function {color: #0000A2;}.ace-tm .ace_heading {color: rgb(12, 7, 255);}.ace-tm .ace_list {color:rgb(185, 6, 144);}.ace-tm .ace_meta.ace_tag {color:rgb(0, 22, 142);}.ace-tm .ace_string.ace_regex {color: rgb(255, 0, 0)}.ace-tm .ace_marker-layer .ace_selection {background: rgb(181, 213, 255);}.ace-tm.ace_multiselect .ace_selection.ace_start {box-shadow: 0 0 3px 0px white;}.ace-tm .ace_marker-layer .ace_step {background: rgb(252, 255, 0);}.ace-tm .ace_marker-layer .ace_stack {background: rgb(164, 229, 101);}.ace-tm .ace_marker-layer .ace_bracket {margin: -1px 0 0 -1px;border: 1px solid rgb(192, 192, 192);}.ace-tm .ace_marker-layer .ace_active-line {background: rgba(0, 0, 0, 0.07);}.ace-tm .ace_gutter-active-line {background-color : #dcdcdc;}.ace-tm .ace_marker-layer .ace_selected-word {background: rgb(250, 250, 255);border: 1px solid rgb(200, 200, 250);}.ace-tm .ace_indent-guide {background: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAEAAAACCAYAAACZgbYnAAAAE0lEQVQImWP4////f4bLly//BwAmVgd1/w11/gAAAABJRU5ErkJggg==") right repeat-y;}
/*# sourceURL=ace/css/ace-tm */</style><style>    .error_widget_wrapper {        background: inherit;        color: inherit;        border:none    }    .error_widget {        border-top: solid 2px;        border-bottom: solid 2px;        margin: 5px 0;        padding: 10px 40px;        white-space: pre-wrap;    }    .error_widget.ace_error, .error_widget_arrow.ace_error{        border-color: #ff5a5a    }    .error_widget.ace_warning, .error_widget_arrow.ace_warning{        border-color: #F1D817    }    .error_widget.ace_info, .error_widget_arrow.ace_info{        border-color: #5a5a5a    }    .error_widget.ace_ok, .error_widget_arrow.ace_ok{        border-color: #5aaa5a    }    .error_widget_arrow {        position: absolute;        border: solid 5px;        border-top-color: transparent!important;        border-right-color: transparent!important;        border-left-color: transparent!important;        top: -5px;    }</style><script src="./README_files/theme-github.js.download"></script></head>
<body ng-controller="Base" file-import-drop-target="" class="ng-scope" data-new-gr-c-s-check-loaded="14.1026.0" data-gr-ext-installed="" style="overflow: hidden;" data-new-gr-c-s-loaded="14.1026.0">
<input type="file" accept=".md,.markdown,text/html" file-import-choose-file="" style="display: none;">
<form method="POST" id="downloader" class="ng-pristine ng-valid">
<input type="hidden" name="name" autocomplete="off">
<input type="hidden" name="unmd" autocomplete="off">
<input type="hidden" name="formatting" autocomplete="off">
<input type="hidden" name="preview" autocomplete="off">
</form>

<ul class="settings ng-scope" role="menu" ng-controller="User as user">
<li>
<a ng-click="user.toggleAutoSave($event)">
<span class="has-checkbox">Auto Save</span>
<span class="toggle-auto-save switch ng-isolate-scope checked" ng-class="{checked: toggleValue}" value="user.profile.enableAutoSave">
  <input type="checkbox" ng-model="toggleValue" class="ng-pristine ng-untouched ng-valid ng-not-empty">
  <small></small>
</span>
</a>
</li>
<li>
<a ng-click="user.toggleWordsCount($event)">
<span class="has-checkbox">Word Count</span>
<span class="toggle-word-count switch ng-isolate-scope checked" ng-class="{checked: toggleValue}" value="user.profile.enableWordsCount">
  <input type="checkbox" ng-model="toggleValue" class="ng-pristine ng-untouched ng-valid ng-not-empty">
  <small></small>
</span>
</a>
</li>
<li>
<a ng-click="user.toggleCharactersCount($event)">
<span class="has-checkbox">Character Count</span>
<span class="toggle-character-count switch ng-isolate-scope checked" ng-class="{checked: toggleValue}" value="user.profile.enableCharactersCount">
  <input type="checkbox" ng-model="toggleValue" class="ng-pristine ng-untouched ng-valid ng-not-empty">
  <small></small>
</span>
</a>
</li>
<li>
<a ng-click="user.toggleScrollSync($event)">
<span class="has-checkbox">Scroll Sync</span>
<span class="toggle-scroll-sync switch ng-isolate-scope" ng-class="{checked: toggleValue}" value="user.profile.enableScrollSync">
  <input type="checkbox" ng-model="toggleValue" class="ng-pristine ng-untouched ng-valid ng-empty">
  <small></small>
</span>
</a>
</li>
<li>
<a><form class="ng-pristine ng-valid ng-valid-min">
<span>Tab Size</span>
<input type="number" ng-model="tabsize" min="1" ng-change="user.storeTabSize()" class="ng-pristine ng-untouched ng-valid ng-not-empty ng-valid-min">
</form></a>
</li>
<li>
<a><form class="ng-pristine ng-valid">
<span>Keybindings</span>
<select ng-model="keybindings" ng-change="user.storeKeybindings()" class="ng-pristine ng-untouched ng-valid ng-not-empty">
<!-- ngRepeat: (key, value) in allKeybindings --><option ng-repeat="(key, value) in allKeybindings" value="Ace" class="ng-binding ng-scope" selected="selected">Ace</option><!-- end ngRepeat: (key, value) in allKeybindings --><option ng-repeat="(key, value) in allKeybindings" value="Vim" class="ng-binding ng-scope">Vim</option><!-- end ngRepeat: (key, value) in allKeybindings --><option ng-repeat="(key, value) in allKeybindings" value="Emacs" class="ng-binding ng-scope">Emacs</option><!-- end ngRepeat: (key, value) in allKeybindings -->
</select>
</form></a>
</li>

<li>
<a target="_blank" href="https://www.markdownguide.org/">
<span>Markdown Help</span>
</a>
</li>
<li>
<a class="toggle-wtf" ng-click="user.showAbout($event)">
<span>WTF is Dillinger?</span>
</a>
</li>
<li>
<a class="toggle-reset" ng-click="user.resetProfile($event)">
<span>Reset Profile</span>
</a>
</li>
</ul>
<div class="wrapper">
<div class="sidebar-wrapper">
<div class="sidebar ng-scope" ng-controller="Documents as document">
<h2 class="sidebar-branding">
<svg viewBox="0 0 85 11" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g id="Desktop---Save-to" sketch:type="MSArtboardGroup" transform="translate(-92.000000, -58.000000)" fill="#FFFFFF">
<g id="Navigation" sketch:type="MSLayerGroup" transform="translate(0.000000, 38.000000)">
<g id="Menu-Item:-Branding" transform="translate(91.000000, 17.000000)" sketch:type="MSShapeGroup">
<path d="M1.17,13 L4.563,13 C7.423,13 9.399,11.011 9.399,8.45 L9.399,8.424 C9.399,5.863 7.423,3.9 4.563,3.9 L1.17,3.9 L1.17,13 Z M2.769,11.544 L2.769,5.356 L4.563,5.356 C6.474,5.356 7.722,6.669 7.722,8.45 L7.722,8.476 C7.722,10.257 6.474,11.544 4.563,11.544 L2.769,11.544 Z M13.047,13 L14.646,13 L14.646,3.9 L13.047,3.9 L13.047,13 Z M18.697,13 L25.08,13 L25.08,11.544 L20.296,11.544 L20.296,3.9 L18.697,3.9 L18.697,13 Z M28.364,13 L34.747,13 L34.747,11.544 L29.963,11.544 L29.963,3.9 L28.364,3.9 L28.364,13 Z M38.122,13 L39.721,13 L39.721,3.9 L38.122,3.9 L38.122,13 Z M43.772,13 L45.345,13 L45.345,6.526 L50.363,13 L51.702,13 L51.702,3.9 L50.129,3.9 L50.129,10.192 L45.254,3.9 L43.772,3.9 L43.772,13 Z M59.978,13.156 C61.59,13.156 62.877,12.506 63.774,11.739 L63.774,7.917 L59.9,7.917 L59.9,9.308 L62.227,9.308 L62.227,11.011 C61.668,11.427 60.888,11.7 60.03,11.7 C58.171,11.7 56.936,10.322 56.936,8.45 L56.936,8.424 C56.936,6.682 58.21,5.213 59.887,5.213 C61.044,5.213 61.733,5.59 62.435,6.188 L63.449,4.979 C62.513,4.186 61.538,3.744 59.952,3.744 C57.209,3.744 55.259,5.902 55.259,8.45 L55.259,8.476 C55.259,11.128 57.131,13.156 59.978,13.156 Z M67.474,13 L74.286,13 L74.286,11.57 L69.073,11.57 L69.073,9.126 L73.636,9.126 L73.636,7.696 L69.073,7.696 L69.073,5.33 L74.221,5.33 L74.221,3.9 L67.474,3.9 L67.474,13 Z M77.804,13 L79.403,13 L79.403,9.828 L81.405,9.828 L83.641,13 L85.526,13 L83.069,9.555 C84.343,9.191 85.24,8.294 85.24,6.799 L85.24,6.773 C85.24,5.98 84.967,5.304 84.486,4.81 C83.901,4.238 83.004,3.9 81.86,3.9 L77.804,3.9 L77.804,13 Z M79.403,8.411 L79.403,5.356 L81.73,5.356 C82.913,5.356 83.615,5.889 83.615,6.864 L83.615,6.89 C83.615,7.813 82.887,8.411 81.743,8.411 L79.403,8.411 Z" id="DILLINGER-2"></path>
</g>
</g>
</g>
</g>
</svg>
</h2>
<nav class="nav nav-sidebar">
<ul class="menu menu-sidebar">
<li class="menu-item menu-item--link-unlink in-sidebar">
<a class="menu-link" ng-click="document.status.linkUnlink = !document.status.linkUnlink">
<span>Services</span> <span class="caret"></span></a>
<ul class="sidebar-list collapse" collapse="document.status.linkUnlink" style="height: 0px;">
<li>
<a href="https://dillinger.io/redirect/dropbox" class="import-dropbox unlinked">Link with
<span>Dropbox</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Bitbucket as bitbucket" class="ng-scope">
<a class="import-bitbucket unlinked" href="https://dillinger.io/redirect/bitbucket">Link with
<span>Bitbucket</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Github as github" class="ng-scope">
<a class="import-github unlinked" ng-click="github.chooseScope()">Link with
<span>Github</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li>
<a href="https://dillinger.io/redirect/medium" class="import-medium unlinked">Link with
<span>Medium</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li>
<a href="https://dillinger.io/redirect/googledrive" class="import-google-drive unlinked">Link with
<span>Google Drive</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li>
<a href="https://dillinger.io/redirect/onedrive" class="import-one-drive unlinked">Link with
<span>One Drive</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
 <path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
</ul>
</li>
<li class="menu-item menu-item--save-to in-sidebar">
<a class="menu-link" ng-click="document.status.save = !document.status.save">
<span>Save to</span> <span class="caret"></span></a>
<ul class="sidebar-list collapse" collapse="document.status.save" style="height: 0px;">
<li ng-controller="Dropbox as dropbox" class="ng-scope">
<a href="https://dillinger.io/redirect/dropbox" class="import-dropbox unlinked">
<span>Dropbox</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>

<li ng-controller="Github as github" class="ng-scope">
<a class="import-github unlinked" ng-click="github.chooseScope()">
<span>Github</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Medium as medium" class="ng-scope">
<a href="https://dillinger.io/redirect/medium" class="import-medium unlinked">
<span>Medium</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Googledrive as googledrive" class="ng-scope">
<a href="https://dillinger.io/redirect/googledrive" class="import-google-drive unlinked">
<span>Google Drive</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Onedrive as onedrive" class="ng-scope">
<a href="https://dillinger.io/redirect/onedrive" class="import-one-drive unlinked">
<span>One Drive</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
</ul>
</li>
<li class="menu-item menu-item--import-from in-sidebar">
<a class="menu-link" ng-click="document.status.import = !document.status.import">
<span>Import from</span> <span class="caret"></span></a>
<ul class="sidebar-list collapse" collapse="document.status.import" style="height: 0px;">
<li ng-controller="Dropbox as dropbox" class="ng-scope">
<a href="https://dillinger.io/redirect/dropbox" class="import-dropbox unlinked">
<span>Dropbox</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Bitbucket as bitbucket" class="ng-scope">
<a class="import-bitbucket unlinked" href="https://dillinger.io/redirect/bitbucket">
<span>Bitbucket</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Github as github" class="ng-scope">
<a class="import-github unlinked" ng-click="github.chooseScope()">
<span>Github</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Googledrive as googledrive" class="ng-scope">
<a href="https://dillinger.io/redirect/googledrive" class="import-google-drive unlinked">
<span>Google Drive</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Onedrive as onedrive" class="ng-scope">
<a href="https://dillinger.io/redirect/onedrive" class="import-one-drive unlinked">
<span>One Drive</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="ImportFile as importFile" class="ng-scope">
<a class="linked" ng-click="choose()">
<span>Markdown File</span>
</a>
</li>
<li ng-controller="ImportFile as importFile" class="ng-scope">
<a class="linked" ng-click="choose(&#39;html&#39;)">
<span>HTML File</span>
</a>
</li>
</ul>
</li>
<li class="menu-item menu-item--documents in-sidebar">
<a class="menu-link" ng-click="document.status.document = !document.status.document">
<span>Documents</span> <span class="caret"></span></a>
<ul class="documents sidebar-list collapse in" collapse="document.status.document" role="menu" style="height: auto;">
<!-- ngRepeat: document in documents track by document.id --><li ng-repeat="document in documents track by document.id" ng-class="{
    &#39;active&#39;: currentDocument.id === document.id,
    &#39;octocat&#39;: document.isGithubFile
    }" class="ng-scope active">
<a ng-click="selectDocument(document)" class="ng-binding">Core Architecture.md</a>
</li><!-- end ngRepeat: document in documents track by document.id -->
</ul>
</li>
</ul>
</nav>
<a class="btn btn--new" ng-click="createDocument()">New Document</a>
<a class="btn btn--save" ng-click="saveDocument(true)">Save Session</a>
<!-- ngIf: documents.length > 1 -->
</div>
</div>
<div class="notification-container">
<div class="notification"></div>
</div>
<div class="page">
<div class="navbar">
<a class="toggle">
  <span></span>
</a>
<h1 class="navbar-brand">
<a class="brand" href="https://dillinger.io/"><svg viewBox="0 0 85 11" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g id="Desktop---Save-to" sketch:type="MSArtboardGroup" transform="translate(-92.000000, -58.000000)" fill="#FFFFFF">
<g id="Navigation" sketch:type="MSLayerGroup" transform="translate(0.000000, 38.000000)">
<g id="Menu-Item:-Branding" transform="translate(91.000000, 17.000000)" sketch:type="MSShapeGroup">
<path d="M1.17,13 L4.563,13 C7.423,13 9.399,11.011 9.399,8.45 L9.399,8.424 C9.399,5.863 7.423,3.9 4.563,3.9 L1.17,3.9 L1.17,13 Z M2.769,11.544 L2.769,5.356 L4.563,5.356 C6.474,5.356 7.722,6.669 7.722,8.45 L7.722,8.476 C7.722,10.257 6.474,11.544 4.563,11.544 L2.769,11.544 Z M13.047,13 L14.646,13 L14.646,3.9 L13.047,3.9 L13.047,13 Z M18.697,13 L25.08,13 L25.08,11.544 L20.296,11.544 L20.296,3.9 L18.697,3.9 L18.697,13 Z M28.364,13 L34.747,13 L34.747,11.544 L29.963,11.544 L29.963,3.9 L28.364,3.9 L28.364,13 Z M38.122,13 L39.721,13 L39.721,3.9 L38.122,3.9 L38.122,13 Z M43.772,13 L45.345,13 L45.345,6.526 L50.363,13 L51.702,13 L51.702,3.9 L50.129,3.9 L50.129,10.192 L45.254,3.9 L43.772,3.9 L43.772,13 Z M59.978,13.156 C61.59,13.156 62.877,12.506 63.774,11.739 L63.774,7.917 L59.9,7.917 L59.9,9.308 L62.227,9.308 L62.227,11.011 C61.668,11.427 60.888,11.7 60.03,11.7 C58.171,11.7 56.936,10.322 56.936,8.45 L56.936,8.424 C56.936,6.682 58.21,5.213 59.887,5.213 C61.044,5.213 61.733,5.59 62.435,6.188 L63.449,4.979 C62.513,4.186 61.538,3.744 59.952,3.744 C57.209,3.744 55.259,5.902 55.259,8.45 L55.259,8.476 C55.259,11.128 57.131,13.156 59.978,13.156 Z M67.474,13 L74.286,13 L74.286,11.57 L69.073,11.57 L69.073,9.126 L73.636,9.126 L73.636,7.696 L69.073,7.696 L69.073,5.33 L74.221,5.33 L74.221,3.9 L67.474,3.9 L67.474,13 Z M77.804,13 L79.403,13 L79.403,9.828 L81.405,9.828 L83.641,13 L85.526,13 L83.069,9.555 C84.343,9.191 85.24,8.294 85.24,6.799 L85.24,6.773 C85.24,5.98 84.967,5.304 84.486,4.81 C83.901,4.238 83.004,3.9 81.86,3.9 L77.804,3.9 L77.804,13 Z M79.403,8.411 L79.403,5.356 L81.73,5.356 C82.913,5.356 83.615,5.889 83.615,6.864 L83.615,6.89 C83.615,7.813 82.887,8.411 81.743,8.411 L79.403,8.411 Z" id="DILLINGER-2"></path>
</g>
</g>
</g>
</g>
</svg>
</a>
</h1>
<div class="ad-container">
</div>
<nav class="nav nav-right">
<ul class="menu menu-utilities">
<li class="menu-item menu-item--export-as has-dropdown" dropdown="">
<a class="dropdown-toggle" dropdown-toggle="" aria-haspopup="true" aria-expanded="false">Preview as <span class="caret"></span></a>
<ul class="dropdown dropdown-menu ng-scope" role="menu" ng-controller="DocumentsExport as export" di-target="preview">
<li>
<a ng-click="export.asHTML()" class="export-html">HTML</a>
</li>
<li>
<a ng-click="export.asStyledHTML()" class="export-styled_html">Styled HTML</a>
</li>
<li>
<a ng-click="export.asMarkdown()" class="export-md">Markdown</a>
</li>
<li>
<a ng-click="export.asPDF()" class="export-pdf">PDF</a>
</li>
</ul>
</li>
<li class="menu-item menu-item--export-as has-dropdown" dropdown="">
<a class="dropdown-toggle" dropdown-toggle="" aria-haspopup="true" aria-expanded="false">Export as <span class="caret"></span></a>
<ul class="dropdown dropdown-menu ng-scope" role="menu" ng-controller="DocumentsExport as export" di-target="_top">
<li>
<a ng-click="export.asHTML()" class="export-html">HTML</a>
</li>
<li>
<a ng-click="export.asStyledHTML()" class="export-styled_html">Styled HTML</a>
</li>
<li>
<a ng-click="export.asMarkdown()" class="export-md">Markdown</a>
</li>
<li>
<a ng-click="export.asPDF()" class="export-pdf">PDF</a>
</li>
</ul>
</li>
<li class="menu-item menu-item--save-to has-dropdown" dropdown="">
<a class="dropdown-toggle" dropdown-toggle="" aria-haspopup="true" aria-expanded="false">Save to <span class="caret"></span></a>
<ul class="dropdown dropdown-menu" role="menu">
<li ng-controller="Dropbox as dropbox" class="ng-scope">
<a href="https://dillinger.io/redirect/dropbox" class="import-dropbox unlinked">
<span>Dropbox</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>

<li ng-controller="Github as github" class="ng-scope">
<a class="import-github unlinked" ng-click="github.chooseScope()">
<span>Github</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Medium as medium" class="ng-scope">
<a href="https://dillinger.io/redirect/medium" class="import-medium unlinked">
<span>Medium</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Googledrive as googledrive" class="ng-scope">
<a href="https://dillinger.io/redirect/googledrive" class="import-google-drive unlinked">
<span>Google Drive</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Onedrive as onedrive" class="ng-scope">
<a href="https://dillinger.io/redirect/onedrive" class="import-one-drive unlinked">
<span>One Drive</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
</ul>
</li>
<li class="menu-item menu-item--import-from has-dropdown" dropdown="">
<a class="dropdown-toggle" dropdown-toggle="" aria-haspopup="true" aria-expanded="false">Import from <span class="caret"></span></a>
<ul class="dropdown dropdown-menu" role="menu">
<li ng-controller="Dropbox as dropbox" class="ng-scope">
<a href="https://dillinger.io/redirect/dropbox" class="import-dropbox unlinked">
<span>Dropbox</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Bitbucket as bitbucket" class="ng-scope">
<a class="import-bitbucket unlinked" href="https://dillinger.io/redirect/bitbucket">
<span>Bitbucket</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Github as github" class="ng-scope">
<a class="import-github unlinked" ng-click="github.chooseScope()">
<span>Github</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Googledrive as googledrive" class="ng-scope">
<a href="https://dillinger.io/redirect/googledrive" class="import-google-drive unlinked">
<span>Google Drive</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="Onedrive as onedrive" class="ng-scope">
<a href="https://dillinger.io/redirect/onedrive" class="import-one-drive unlinked">
<span>One Drive</span>
<span class="icon icon-link"><svg viewBox="0 0 16 16" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g sketch:type="MSArtboardGroup" transform="translate(-238.000000, -212.000000)" fill="#FFFFFF">
<g sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g transform="translate(0.000000, 75.000000)" sketch:type="MSShapeGroup">
<g transform="translate(32.000000, 72.000000)">
<g transform="translate(206.000000, 0.000000)">
<path d="M15.0962672,6.56194892 L10.8290766,10.8291395 C9.6502947,12.0079214 7.74066798,12.0079214 6.56188605,10.8291395 L5.13948919,9.40674263 L6.56188605,7.98434578 L7.98428291,9.40674263 C8.37721022,9.79869548 9.01472692,9.79966994 9.40667976,9.40674263 L13.6738703,5.13955206 C14.0658232,4.7471277 14.0658232,4.10910806 13.6738703,3.71665226 L12.2514735,2.2942554 C11.8595206,1.90230255 11.2210295,1.90230255 10.8290766,2.2942554 L9.30549312,3.8178389 C8.59919843,3.40231041 7.79665226,3.22401572 7.00196464,3.27754813 L9.40667976,0.871858546 C10.5854617,-0.306420432 12.4960629,-0.306420432 13.6738703,0.871858546 L15.0962672,2.2942554 C16.2750491,3.47256582 16.2750491,5.38366994 15.0962672,6.56194892 L15.0962672,6.56194892 Z M6.66209823,12.1513242 L5.13948919,13.6739332 C4.74656189,14.0668605 4.10904519,14.0658861 3.71709234,13.6739332 L2.29469548,12.2515363 C1.90176817,11.8595835 1.90176817,11.2220668 2.29469548,10.8291395 L6.56188605,6.56194892 C6.9538389,6.16999607 7.59233006,6.16999607 7.98428291,6.56194892 L9.40667976,7.98434578 L10.8290766,6.56194892 L9.40667976,5.13955206 C8.22789784,3.96127308 6.31827112,3.96127308 5.13948919,5.13955206 L0.872298625,9.40674263 C-0.306483301,10.5855246 -0.306483301,12.4961257 0.872298625,13.6739332 L2.29469548,15.0963301 C3.47250295,16.275112 5.38310413,16.275112 6.56188605,15.0963301 L8.96660118,12.6916149 C8.17191356,12.7446444 7.37131631,12.5658782 6.66209823,12.1513242 L6.66209823,12.1513242 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</g>
</svg>
</span>
</a>
</li>
<li ng-controller="ImportFile as importFile" class="ng-scope">
<a class="linked" ng-click="choose()">
<span>Markdown File</span>
</a>
</li>
<li ng-controller="ImportFile as importFile" class="ng-scope">
<a class="linked" ng-click="choose(&#39;html&#39;)">
<span>HTML File</span>
</a>
</li>
</ul>
</li>
<li class="menu-item menu-item-icon menu-item--preview">
<a class="menu-link menu-link-preview" preview-toggle="">
<i class="icon icon-preview"><svg viewBox="0 0 19 12" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g id="Mobile---Home" sketch:type="MSArtboardGroup" transform="translate(-234.000000, -85.000000)" fill="#D3DBEB">
<g id="Navigation" sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g id="Menu-Item:-Preview" transform="translate(218.000000, 0.000000)" sketch:type="MSShapeGroup">
<g id="Icon:-Preview" transform="translate(17.000000, 20.000000)">
<path d="M8.90526316,0.0311320755 C3.00069474,0.0311320755 -0.0947368421,4.79641509 -0.0947368421,5.55188679 C-0.0947368421,6.30756604 3.00069474,11.0726415 8.90526316,11.0726415 C14.8094526,11.0726415 17.9052632,6.30756604 17.9052632,5.55188679 C17.9052632,4.79641509 14.8094526,0.0311320755 8.90526316,0.0311320755 L8.90526316,0.0311320755 Z M8.90526316,9.79871698 C6.69618947,9.79871698 4.90509474,7.89737736 4.90509474,5.55188679 C4.90509474,3.20639623 6.69618947,1.3050566 8.90526316,1.3050566 C11.1143368,1.3050566 12.9052421,3.20639623 12.9052421,5.55188679 C12.9052421,7.89737736 11.1143368,9.79871698 8.90526316,9.79871698 L8.90526316,9.79871698 Z M10.9051579,5.55188679 C10.9051579,6.7245283 10.0095158,7.67550943 8.90526316,7.67550943 C7.80063158,7.67550943 6.90536842,6.7245283 6.90536842,5.55188679 C6.90536842,4.37924528 7.80063158,3.4284717 8.90526316,3.4284717 C9.50210526,3.4284717 8.53901053,5.11126415 8.90526316,5.55188679 C9.21656842,5.92609434 10.9051579,5.01330189 10.9051579,5.55188679 L10.9051579,5.55188679 Z" id="Shape"></path>
</g>
</g>
</g>
</g>
</g>
</svg>
</i>
<span class="sr-only">Preview</span>
</a>
</li>
<li class="menu-item menu-item-icon menu-item--settings">
<a class="menu-link menu-link-settings" settings-toggle="">
<i class="icon icon-settings"><svg viewBox="0 0 18 18" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns:sketch="http://www.bohemiancoding.com/sketch/ns">
<g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
<g id="Mobile---Home" sketch:type="MSArtboardGroup" transform="translate(-286.000000, -81.000000)" fill="#D3DBEB">
<g id="Navigation" sketch:type="MSLayerGroup" transform="translate(0.000000, 65.000000)">
<g id="Menu-Item:-Settings" transform="translate(269.000000, 0.000000)" sketch:type="MSShapeGroup">
<g id="Icon:-Settings" transform="translate(17.000000, 16.000000)">
<path d="M17.341654,7.68935491 L15.5585491,7.39189286 C15.4289531,6.86205804 15.2399933,6.35558705 14.9938996,5.88320759 L16.1353929,4.46787723 C16.3781719,4.16876786 16.3671429,3.73839509 16.1111853,3.44971205 L15.4020134,2.65156473 C15.1449509,2.36318304 14.7186763,2.30219196 14.3934911,2.507625 L12.8685937,3.46620536 C12.1978929,2.99760268 11.4381562,2.65156473 10.6185937,2.45077232 L10.3202679,0.658104911 C10.2576696,0.278517857 9.92918973,0 9.54359598,0 L8.47488616,0 C8.09007589,0 7.76049107,0.278517857 7.69925893,0.658104911 L7.39932589,2.45133482 C6.72173437,2.61723214 6.0864308,2.88502232 5.50665402,3.23770982 L4.05644866,2.20275 C3.74389955,1.97945759 3.31461161,2.01437277 3.04185937,2.28654241 L2.28684375,3.04210045 C2.01467411,3.31485268 1.97975893,3.74414062 2.20363393,4.05668973 L3.24100446,5.50966741 C2.8916317,6.08506473 2.62659375,6.71675223 2.46071652,7.38829687 L0.65784375,7.68935491 C0.278839286,7.75195312 -0.000220982143,8.08047321 -0.000220982143,8.46606696 L-0.000220982143,9.53393304 C-0.000220982143,9.91952679 0.278839286,10.2480469 0.65784375,10.3106451 L2.46071652,10.6117031 C2.59694196,11.1642991 2.79470089,11.6921853 3.05754911,12.1816205 L1.92125893,13.5889554 C1.67930357,13.8877835 1.68946875,14.3184375 1.94542634,14.6068594 L2.6540558,15.4050067 C2.91113839,15.6939308 3.33765402,15.753817 3.66285937,15.5489063 L5.20973437,14.5771875 C5.86426339,15.0248772 6.60473437,15.3539196 7.39932589,15.5489063 L7.69925893,17.341875 C7.76049107,17.7215022 8.09007589,18 8.47488616,18 L9.54359598,18 C9.92918973,18 10.2576696,17.7215022 10.3202679,17.3418951 L10.619096,15.5489263 C11.2882299,15.3852589 11.9154777,15.1221295 12.4900915,14.7754888 L14.0007254,15.8543839 C14.3127321,16.0785 14.7423214,16.0433437 15.0147924,15.7703103 L15.7700893,15.0150134 C16.0419576,14.7430848 16.0787812,14.3140379 15.8529978,14.0009464 L14.7774978,12.4930647 C15.1278951,11.9157388 15.3943192,11.2829263 15.5591518,10.6083683 L17.3422366,10.310625 C17.722346,10.2480268 18.0002812,9.9195067 18.0002812,9.53391295 L18.0002812,8.46604688 C17.9997388,8.08047321 17.7218036,7.75195312 17.341654,7.68935491 L17.341654,7.68935491 Z M9.0283058,12.375 C7.1647433,12.375 5.6533058,10.8632812 5.6533058,9 C5.6533058,7.1364375 7.1647433,5.625 9.0283058,5.625 C10.8915469,5.625 12.4032656,7.1364375 12.4032656,9 C12.4032656,10.8632812 10.8915469,12.375 9.0283058,12.375 L9.0283058,12.375 Z" id="settings_1_"></path>
</g>
</g>
</g>
</g>
</g>
</svg>
</i>
<span class="sr-only">Settings</span>
</a>
</li>
</ul>
</nav>
</div>
<div class="overlay"></div>
<div class="header">
<h2 class="title">Document Name</h2>
<document-title><input class="title-document ng-pristine ng-untouched ng-valid ng-not-empty" type="text" name="documentTitle" ng-change="updateDocument()" ng-model-options="{ debounce: 500 }" ng-model="currentDocument.title">
</document-title>
<!-- ngIf: profile.enableWordsCount && !viewSrcMode --><p ng-if="profile.enableWordsCount &amp;&amp; !viewSrcMode" class="words ng-scope">
<span class="mr10">Reading Time: <span class="counter ng-binding" ng-bind="readingTime">9 min read</span></span>
<span>Words: <span class="counter ng-binding" ng-bind="words">1709</span></span>
</p><!-- end ngIf: profile.enableWordsCount && !viewSrcMode -->
<!-- ngIf: profile.enableCharactersCount && !viewSrcMode --><p ng-if="profile.enableCharactersCount &amp;&amp; !viewSrcMode" class="characters ng-scope">Characters: <span class="counter ng-binding" ng-bind="characters">10431</span></p><!-- end ngIf: profile.enableCharactersCount && !viewSrcMode -->
</div>
<div class="g mnone">
<div class="editor-header editor-header--first">
<h3 class="title">Markdown</h3>
<!-- ngIf: !$root.viewSrcMode --><a class="enter-zen-mode ng-scope" ng-click="zenmode.toggle()" ng-if="!$root.viewSrcMode">Toggle Zen Mode</a><!-- end ngIf: !$root.viewSrcMode -->
</div>
<div class="editor-header">
<h3 class="title">Preview</h3>
<a ng-class="{&#39;preview-mode-toggle-html&#39; : $root.viewSrcMode, &#39;preview-mode-toggle-src&#39; : !$root.viewSrcMode}" ng-click="toggleView()" class="preview-mode-toggle-src">Toggle Mode</a>
</div>
<div id="editor1" class="g-b g-b--t1of2 split split-editor" style="height: 616px;">
<div id="editor" class="ui-resizable-e ace_editor ace-tm ace_focus" style="height: 6111.11px;" draggable="false"><textarea class="ace_text-input" wrap="off" autocorrect="off" autocapitalize="off" spellcheck="false" style="opacity: 0; left: 739px; top: 5944.44px; height: 27.7778px; width: 7px;"></textarea><div class="ace_gutter" aria-hidden="true"><div class="ace_layer ace_gutter-layer ace_folding-enabled" style="margin-top: 0px; height: 6166.67px; width: 55px;"><div class="ace_gutter-cell " style="height: 27.7778px;">1<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">2</div><div class="ace_gutter-cell " style="height: 27.7778px;">3</div><div class="ace_gutter-cell " style="height: 27.7778px;">4<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">5</div><div class="ace_gutter-cell " style="height: 27.7778px;">6</div><div class="ace_gutter-cell " style="height: 27.7778px;">7</div><div class="ace_gutter-cell " style="height: 27.7778px;">8</div><div class="ace_gutter-cell " style="height: 27.7778px;">9</div><div class="ace_gutter-cell " style="height: 27.7778px;">10</div><div class="ace_gutter-cell " style="height: 27.7778px;">11</div><div class="ace_gutter-cell " style="height: 27.7778px;">12</div><div class="ace_gutter-cell " style="height: 55.5556px;">13</div><div class="ace_gutter-cell " style="height: 27.7778px;">14</div><div class="ace_gutter-cell " style="height: 27.7778px;">15</div><div class="ace_gutter-cell " style="height: 27.7778px;">16</div><div class="ace_gutter-cell " style="height: 27.7778px;">17</div><div class="ace_gutter-cell " style="height: 55.5556px;">18</div><div class="ace_gutter-cell " style="height: 27.7778px;">19</div><div class="ace_gutter-cell " style="height: 27.7778px;">20</div><div class="ace_gutter-cell " style="height: 27.7778px;">21</div><div class="ace_gutter-cell " style="height: 27.7778px;">22</div><div class="ace_gutter-cell " style="height: 27.7778px;">23</div><div class="ace_gutter-cell " style="height: 83.3333px;">24</div><div class="ace_gutter-cell " style="height: 27.7778px;">25</div><div class="ace_gutter-cell " style="height: 27.7778px;">26<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">27</div><div class="ace_gutter-cell " style="height: 27.7778px;">28</div><div class="ace_gutter-cell " style="height: 55.5556px;">29</div><div class="ace_gutter-cell " style="height: 27.7778px;">30</div><div class="ace_gutter-cell " style="height: 27.7778px;">31</div><div class="ace_gutter-cell " style="height: 55.5556px;">32</div><div class="ace_gutter-cell " style="height: 27.7778px;">33<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">34<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">35</div><div class="ace_gutter-cell " style="height: 27.7778px;">36</div><div class="ace_gutter-cell " style="height: 27.7778px;">37<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">38</div><div class="ace_gutter-cell " style="height: 27.7778px;">39</div><div class="ace_gutter-cell " style="height: 27.7778px;">40</div><div class="ace_gutter-cell " style="height: 27.7778px;">41</div><div class="ace_gutter-cell " style="height: 27.7778px;">42<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">43</div><div class="ace_gutter-cell " style="height: 27.7778px;">44</div><div class="ace_gutter-cell " style="height: 27.7778px;">45</div><div class="ace_gutter-cell " style="height: 27.7778px;">46</div><div class="ace_gutter-cell " style="height: 27.7778px;">47</div><div class="ace_gutter-cell " style="height: 27.7778px;">48</div><div class="ace_gutter-cell " style="height: 27.7778px;">49</div><div class="ace_gutter-cell " style="height: 27.7778px;">50</div><div class="ace_gutter-cell " style="height: 27.7778px;">51</div><div class="ace_gutter-cell " style="height: 27.7778px;">52</div><div class="ace_gutter-cell " style="height: 27.7778px;">53</div><div class="ace_gutter-cell " style="height: 27.7778px;">54<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 55.5556px;">55</div><div class="ace_gutter-cell " style="height: 55.5556px;">56</div><div class="ace_gutter-cell " style="height: 27.7778px;">57</div><div class="ace_gutter-cell " style="height: 27.7778px;">58</div><div class="ace_gutter-cell " style="height: 27.7778px;">59<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 55.5556px;">60</div><div class="ace_gutter-cell " style="height: 27.7778px;">61<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">62<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">63</div><div class="ace_gutter-cell " style="height: 83.3333px;">64</div><div class="ace_gutter-cell " style="height: 27.7778px;">65</div><div class="ace_gutter-cell " style="height: 27.7778px;">66</div><div class="ace_gutter-cell " style="height: 27.7778px;">67<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 55.5556px;">68</div><div class="ace_gutter-cell " style="height: 55.5556px;">69</div><div class="ace_gutter-cell " style="height: 55.5556px;">70</div><div class="ace_gutter-cell " style="height: 55.5556px;">71</div><div class="ace_gutter-cell " style="height: 55.5556px;">72</div><div class="ace_gutter-cell " style="height: 27.7778px;">73</div><div class="ace_gutter-cell " style="height: 27.7778px;">74</div><div class="ace_gutter-cell " style="height: 27.7778px;">75<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">76</div><div class="ace_gutter-cell " style="height: 27.7778px;">77</div><div class="ace_gutter-cell " style="height: 27.7778px;">78</div><div class="ace_gutter-cell " style="height: 27.7778px;">79</div><div class="ace_gutter-cell " style="height: 27.7778px;">80</div><div class="ace_gutter-cell " style="height: 27.7778px;">81</div><div class="ace_gutter-cell " style="height: 27.7778px;">82<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">83<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">84</div><div class="ace_gutter-cell " style="height: 55.5556px;">85</div><div class="ace_gutter-cell " style="height: 27.7778px;">86</div><div class="ace_gutter-cell " style="height: 27.7778px;">87<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 55.5556px;">88</div><div class="ace_gutter-cell " style="height: 27.7778px;">89</div><div class="ace_gutter-cell " style="height: 27.7778px;">90</div><div class="ace_gutter-cell " style="height: 27.7778px;">91</div><div class="ace_gutter-cell " style="height: 55.5556px;">92</div><div class="ace_gutter-cell " style="height: 27.7778px;">93</div><div class="ace_gutter-cell " style="height: 27.7778px;">94<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 55.5556px;">95</div><div class="ace_gutter-cell " style="height: 27.7778px;">96</div><div class="ace_gutter-cell " style="height: 27.7778px;">97</div><div class="ace_gutter-cell " style="height: 27.7778px;">98<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">99</div><div class="ace_gutter-cell " style="height: 27.7778px;">100</div><div class="ace_gutter-cell " style="height: 27.7778px;">101</div><div class="ace_gutter-cell " style="height: 27.7778px;">102</div><div class="ace_gutter-cell " style="height: 27.7778px;">103</div><div class="ace_gutter-cell " style="height: 27.7778px;">104</div><div class="ace_gutter-cell " style="height: 27.7778px;">105</div><div class="ace_gutter-cell " style="height: 27.7778px;">106</div><div class="ace_gutter-cell " style="height: 27.7778px;">107</div><div class="ace_gutter-cell " style="height: 27.7778px;">108</div><div class="ace_gutter-cell " style="height: 27.7778px;">109</div><div class="ace_gutter-cell " style="height: 27.7778px;">110</div><div class="ace_gutter-cell " style="height: 27.7778px;">111<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">112<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">113</div><div class="ace_gutter-cell " style="height: 55.5556px;">114</div><div class="ace_gutter-cell " style="height: 27.7778px;">115</div><div class="ace_gutter-cell " style="height: 27.7778px;">116</div><div class="ace_gutter-cell " style="height: 27.7778px;">117<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 55.5556px;">118</div><div class="ace_gutter-cell " style="height: 27.7778px;">119</div><div class="ace_gutter-cell " style="height: 55.5556px;">120</div><div class="ace_gutter-cell " style="height: 27.7778px;">121<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">122<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">123</div><div class="ace_gutter-cell " style="height: 55.5556px;">124</div><div class="ace_gutter-cell " style="height: 55.5556px;">125</div><div class="ace_gutter-cell " style="height: 27.7778px;">126<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">127<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 55.5556px;">128</div><div class="ace_gutter-cell " style="height: 55.5556px;">129</div><div class="ace_gutter-cell " style="height: 83.3333px;">130</div><div class="ace_gutter-cell " style="height: 27.7778px;">131<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">132<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 55.5556px;">133</div><div class="ace_gutter-cell " style="height: 55.5556px;">134</div><div class="ace_gutter-cell " style="height: 55.5556px;">135</div><div class="ace_gutter-cell " style="height: 55.5556px;">136</div><div class="ace_gutter-cell " style="height: 27.7778px;">137<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">138<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">139</div><div class="ace_gutter-cell " style="height: 55.5556px;">140</div><div class="ace_gutter-cell " style="height: 83.3333px;">141</div><div class="ace_gutter-cell " style="height: 27.7778px;">142</div><div class="ace_gutter-cell " style="height: 27.7778px;">143</div><div class="ace_gutter-cell " style="height: 55.5556px;">144</div><div class="ace_gutter-cell " style="height: 27.7778px;">145</div><div class="ace_gutter-cell " style="height: 55.5556px;">146</div><div class="ace_gutter-cell " style="height: 27.7778px;">147<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">148<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 55.5556px;">149</div><div class="ace_gutter-cell " style="height: 83.3333px;">150</div><div class="ace_gutter-cell " style="height: 83.3333px;">151</div><div class="ace_gutter-cell " style="height: 27.7778px;">152</div><div class="ace_gutter-cell " style="height: 55.5556px;">153</div><div class="ace_gutter-cell " style="height: 27.7778px;">154<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">155<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 83.3333px;">156</div><div class="ace_gutter-cell " style="height: 27.7778px;">157</div><div class="ace_gutter-cell " style="height: 55.5556px;">158</div><div class="ace_gutter-cell " style="height: 55.5556px;">159</div><div class="ace_gutter-cell " style="height: 27.7778px;">160<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">161<span class="ace_fold-widget ace_start ace_open" style="height: 27.7778px;"></span></div><div class="ace_gutter-cell " style="height: 27.7778px;">162</div><div class="ace_gutter-cell " style="height: 27.7778px;">163</div><div class="ace_gutter-cell " style="height: 27.7778px;">164</div><div class="ace_gutter-cell " style="height: 27.7778px;">165</div><div class="ace_gutter-cell " style="height: 55.5556px;">166</div><div class="ace_gutter-cell " style="height: 27.7778px;">167</div><div class="ace_gutter-cell " style="height: 55.5556px;">168</div><div class="ace_gutter-cell " style="height: 27.7778px;">169</div><div class="ace_gutter-cell " style="height: 27.7778px;">170</div></div><div class="ace_gutter-active-line" style="top: 5916.67px; height: 55.5556px;"></div></div><div class="ace_scroller" style="left: 56px; right: 0px; bottom: 0px;"><div class="ace_content" style="margin-top: 0px; width: 804px; height: 6166.67px; margin-left: 0px;"><div class="ace_layer ace_print-margin-layer"><div class="ace_print-margin" style="left: 564px; visibility: hidden;"></div></div><div class="ace_layer ace_marker-layer"><div class="ace_active-line" style="height:27.77777862548828px;top:5944.444625854492px;left:0;right:0;"></div></div><div class="ace_layer ace_text-layer" style="padding: 0px 4px;"><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_heading ace_1">#</span><span class="ace_heading"> Core Architecture</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">This is the highlevel overview of the each components in K8s core architecture.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_heading ace_2">##</span><span class="ace_heading"> Master Node Component</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">### Master</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">    - Manage, Plan, Schedule and Monitor slave nodes</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">### ETCD</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">    - Database that stores information in a Key-Value format.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">### Kube-Scheduler</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">    - Identifies the right node to place a container based on the containers resource requirements, the worker </span></div><div class="ace_line" style="height:27.77777862548828px">&nbsp;&nbsp;&nbsp;&nbsp;<span class="ace_list">nodes capacity or any other policies &amp; constraints such as tents and tolerations or node affinity rules.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">### Controllers and Controller Manager</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_text ace_xml">    - </span><span class="ace_string ace_strong">**Node-Controller**</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_indent-guide">    </span><span class="ace_text ace_xml">    - Takes care of Nodes, responsible for onboarding new nodes to the cluster, handling situations where </span></div><div class="ace_line" style="height:27.77777862548828px">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="ace_text ace_xml">nodes become unavailable or gets destroyed.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_indent-guide">    </span><span class="ace_text ace_xml">    </span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_text ace_xml">    - </span><span class="ace_string ace_strong">**Replication Controller**</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_indent-guide">    </span><span class="ace_text ace_xml">    - Ensures that desired number of containers are running all times in replication group.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">### Kube-API Server</span></div></div><div class="ace_line_group" style="height:83.33333587646484px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">    - Primary management component of K8s, Responsible of orchestrating all operations within the cluster, </span></div><div class="ace_line" style="height:27.77777862548828px">&nbsp;&nbsp;&nbsp;&nbsp;<span class="ace_list">Exposes the K8s API which is used by external users to perform management operations on cluster and Kube-API </span></div><div class="ace_line" style="height:27.77777862548828px">&nbsp;&nbsp;&nbsp;&nbsp;<span class="ace_list">Server also perform many other works.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_heading ace_2">##</span><span class="ace_heading"> Slave Node Component</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">### Kubelet</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">    - It's an agent runs on each node in a cluster. It listens for instructions from the kube-api server and </span></div><div class="ace_line" style="height:27.77777862548828px">&nbsp;&nbsp;&nbsp;&nbsp;<span class="ace_list">deploys or destroys containers on the nodes as required.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">### Kube-Proxy</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">    - Ensures that the necessary rules are in place on the worker nodes to allow the containers running on them </span></div><div class="ace_line" style="height:27.77777862548828px">&nbsp;&nbsp;&nbsp;&nbsp;<span class="ace_list">to reach each other.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">----</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">## ETCD</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">It is Distributed, reliable key-value database that is simple, secure and fast.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_heading ace_3">###</span><span class="ace_heading"> Key-Values Store</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Stores information in Documents or pages.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Changing one document does not affect other.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Easy to convert into JSON.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_heading ace_3">###</span><span class="ace_heading"> ETCD Control Client</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Default Client</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">It is a command line client for etcd and we can use it to store and retrive key-value pair.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Store the value</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_support ace_function">    ```</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_support ace_function">    ./etcdctl set key1 value1</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_support ace_function">    ```</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Retrive the value</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_support ace_function">    ```</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_support ace_function">    ./etcdctl get key1</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_support ace_function">    ```</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_heading ace_3">###</span><span class="ace_heading"> ETCD Role in K8s</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Stores information regarding The Clusters, Such as nodes, pods, configs, secrets, accounts, roles, bindings and </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">others.</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Every additional changes and information such as adding nodes, deploying pods or replica sets are updated in </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">etcd server.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Default port on which etcd listens is </span><span class="ace_support ace_function">`2379`</span><span class="ace_list">.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_heading ace_3">###</span><span class="ace_heading"> Explore ETCD</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">K8s stores data in specific directory structre. Root directory is registery and under that we have various K8s </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">constructs such as minions or nodes, pods, replicasets, deployments etc.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">----</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">## Kube-API Server</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Primary Management component in K8s.</span></div></div><div class="ace_line_group" style="height:83.33333587646484px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">When we run any </span><span class="ace_support ace_function">`kubectl`</span><span class="ace_list"> command, it infact reaching to the Kube-API Server. Kube-Api server first </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">authenticate and validate the request. It then retrives the data from ETCD cluster and responds back with the </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">requested information.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">We can also invoke api directly by sending post request.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_heading ace_3">###</span><span class="ace_heading"> Working Process</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">When user make request to create new node, Kube-API server first authenticate and validates the request. Then </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">it register the pod into ETCD cluster and give feedback to user that pod is created.</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Kube-Scheduler continuously monitors the API Server and realize that there is a new pod with no node assigned. </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">The scheduler identifies right node to place the new pod on and communicates that back to the Kube-API Server.</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">The API server update the information into ETCD Cluster and then passes these informations to Kubelet in </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">appropriate worker node.</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">The Kubelet then creates the Pod on the node and instructes the container runtime engine to deploy the </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">application image.</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Once done, The kubelets update the status back to the API Server and API Server then updates the data into ETCD </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">Cluster.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">A similar pattern follows everytime changes reflected.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_heading ace_4">####</span><span class="ace_heading"> Summary</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Authenticate User</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Validate Request</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Retrive Data</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Update ETCD</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Scheduler</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Kubelet</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">----</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">## Kube Controller Manager</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">It manages various contollers in K8s.</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">It continuously monitors te state of various components within the system and works towards bringing the whole </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">system to the desired functioning state.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_heading ace_3">###</span><span class="ace_heading"> Node Controller</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">It is responsible for monitoring the status of the nodes and taking necessary actions to keep the application </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">running.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">it does that through the Kube-API Server.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">it checks the status of the nodes every 5 seconds.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">If node fails it wait for 40 seconds to mark it as unreachable.</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">After marking unreachable it waits for 5 mins for node to come back up, if does not then it removes the pod </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">assigned to that node and provisioned them to the healthy one.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_heading ace_3">###</span><span class="ace_heading"> Replication Controller</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">It is responsible for monitoring the status of the Replica Sets and Ensuring that desired number of pods are </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">available at all times within the set.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">if pod dies it creates another one.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_heading ace_4">####</span><span class="ace_heading"> Other K8s controller are as below...</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Deployment Controller</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Namespace Controller</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Job Controller</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">EndPoint Controller</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Service Account Controller</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">PV Binder Controller</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">PV Protection Controller</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Stateful Set</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Replica Set</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Cron Job</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">and much more...</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">This all controllers are packaged into single process called </span><span class="ace_string ace_strong">**Kube-Controller Manager**</span><span class="ace_list">. </span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">----</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">## Kube Scheduler</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">It responsible for scheduling the pods on nodes.</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">It only responsible for deciding which pod goes on which node. It does not actually place the pod on the node. </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">That is the job of the kubelet</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Scheduler only decides which pod goes where.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_heading ace_3">###</span><span class="ace_heading"> Why need scheduler?</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">In K8s The Scheduler decides which nodes the pods are placed on depending on certain criteria. We may have Pods </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">with different resource requirements, we can have nodes in the cluster dedicated to certain applications.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">The Scheduler looks at each Pods and tries to find best node for it.</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">If one Pod require 10 CPU then there is possible that all the nodes in cluster does not have 10 or more than 10 </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">CPUs, some of them have or some of them do not have.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">----</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">## Kubelet</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Kubelet is like captain on the ship, It leads all the activity on Nodes.</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">It registers the node with te Kubernetes Cluster. When It receives the instructions to load a container or POD </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">on the node it requests the container runtime engine to pull the required image and run on the node.</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Kubelets then continues to monitor the state of the POD and the containers in it and reports to the Kube-API </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">Server on a timely basis.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">----</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">## Kube Proxy</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Within the K8s Cluster, every POD can reach every other pod, this is accomplished by deploying POD Netorking </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">solution to the cluster.</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">A Pod Network is an internal virtual network that spans across all the nodes in the cluster to which all the </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">pods connect to.</span></div></div><div class="ace_line_group" style="height:83.33333587646484px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Kube-Proxy is a process that runs on the each node of the cluster. It's job is to look for new services and </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">every time a new service is created it creates the appropriate rules on each nodes to forward traffic to those </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">services to the backend Pods. One way it does this is using IPTABLES rules.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">----</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">## PODs</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">The containers are encapsulated into the K8s Object knows as Pods. A Pods is a single instance of an </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">application and it's the smallest object in K8s.</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">If we want to scale up we can create new Pods or New Nodes with Pods and to scale down we can delete Pods or </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">Nodes as per the requiements.</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">A single pod can ave multiple containers except for the fact that they are usually not multiple containers of </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">the same kind.</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Multi Container are rare use case scenario and best practice suggest that we should run single container per </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">Pod.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">----</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">## Replication Controller and Replica Set</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">What if for some reason our application crashes and users will no longer be able to access our application.</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">To Prevent this we would like to run more than single instance at a time. So if one fails we still have other </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">containers on which our app is running.</span></div></div><div class="ace_line_group" style="height:83.33333587646484px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">The Replication Controller help us to run multiple Pods of single part thus providing High Availability. So </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">even if we have single pod and if it crashes the replication controller can help by automatically bringing up the </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">new pod.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Replication Controller ensures that the specified number of pods are running at all times.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">It also help us to share load across the Pods.</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Replication Controller and Replica Set both are similar terms. Both have same Purpose but they are not the </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">same.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Replication Controller is the older technology that is being replaced by Replica Set.</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Replica Set monitors the Pods using Lable, Lable works as a filter for Replica Sets when there is 100s of Pods </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">are running.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">----</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">## Deployments</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Suppose we might want to deploy our app in production environment. We want to deploy multiple instances for web </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">servers running.</span></div></div><div class="ace_line_group" style="height:83.33333587646484px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">In addition to whenever newer version of app comes we also want to roll update on each instances one by one, </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">and if one of the update results in unexpected error and we need to undo the recent change we would like to be </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">able to roll back the changes that were recently carried out.</span></div></div><div class="ace_line_group" style="height:83.33333587646484px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Also we would like to do multiple changes in our production environment, such as modifying resources, scaling </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">the environment etc... We do not want to apply the changes immediately after the command is run, instead we would </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">like to pause the environment, make the changes and resumes the environment so all the changes roll-out together.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">All of these capabilities are available in K8s Deployments.</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">The Deployments provides us with the capabilities to upgrade the underlying instaces, rolling updates, undo </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">changes and Pause and Resume changes as required.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">----</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">## NameSpaces</span></div></div><div class="ace_line_group" style="height:83.33333587646484px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">K8s creates </span><span class="ace_support ace_function">`Default`</span><span class="ace_list"> namespace automatically when the cluster is first setup. K8s also creates </span><span class="ace_support ace_function">`Kube-System`</span><span class="ace_list"> </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">namespace for it's internal purpose and the third namespace is called </span><span class="ace_support ace_function">`kube-public`</span><span class="ace_list"> this is where resources that </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">should be made available to all users are created.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">We can create our own NameSpaces as well.</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Each namespace can have it's own set of policies.We can also assign quota or resources to each of these </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">resources.</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">- Resources within same namespace can refer each other using Names. If require resource can reach another </span></div><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">namesapce as well.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">----</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">## Services</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">K8s services enables te communications between various components within and outside of the application.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">Services enables the loose coupling between microservices in our applications.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_markup ace_list">- </span><span class="ace_list">K8s Service is the an object. There are multiple type of service available.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">    - </span><span class="ace_string ace_strong">**NodePort Service**</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_indent-guide">    </span><span class="ace_list">   -    It's use case is to listen to a port on the Node and Forward requests on that Port to a Port on the </span></div><div class="ace_line" style="height:27.77777862548828px">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="ace_list">POD running Web Application. Valid Port range for NodePort service is from 30000 to 32767.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">    - </span><span class="ace_string ace_strong">**Cluster IP Service**</span></div></div><div class="ace_line_group" style="height:55.55555725097656px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_indent-guide">    </span><span class="ace_list">    - Service creates a Virtual IP inside the cluster to enable communication between diffrent services. </span></div><div class="ace_line" style="height:27.77777862548828px">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span class="ace_list">Example set of frontend servers services to set of backend servers services.</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_list">    - </span><span class="ace_string ace_strong">**LoadBalancer Service**</span></div></div><div class="ace_line_group" style="height:27.77777862548828px"><div class="ace_line" style="height:27.77777862548828px"><span class="ace_indent-guide">    </span><span class="ace_list">    - It provisions a Load Balancer for our application in supported cloud providers. </span></div></div></div><div class="ace_layer ace_marker-layer"></div><div class="ace_layer ace_cursor-layer"><div class="ace_cursor" style="left: 683px; top: 5944.44px; width: 7px; height: 27.7778px;"></div></div></div></div><div class="ace_scrollbar ace_scrollbar-v" style="display: none; width: 24px; bottom: 0px;"><div class="ace_scrollbar-inner" style="width: 24px; height: 6111.11px;"></div></div><div class="ace_scrollbar ace_scrollbar-h" style="display: none; height: 24px; left: 56px; right: 0px;"><div class="ace_scrollbar-inner" style="height: 24px; width: 819px;"></div></div><div style="height: auto; width: auto; top: 0px; left: 0px; visibility: hidden; position: absolute; white-space: pre; font: inherit; overflow: hidden;"><div style="height: auto; width: auto; top: 0px; left: 0px; visibility: hidden; position: absolute; white-space: pre; font: inherit; overflow: visible;"></div><div style="height: auto; width: auto; top: 0px; left: 0px; visibility: hidden; position: absolute; white-space: pre; font-style: inherit; font-variant: inherit; font-stretch: inherit; font-size: inherit; line-height: inherit; font-family: inherit; overflow: visible;">XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX</div></div></div>
</div>
<div id="preview1" class="g-b g-b--t1of2 split split-preview" style="height: 616px;">
<div id="preview" class="preview-html" preview="" debounce="150"><h1 class="code-line" data-line-start="0" data-line-end="1"><a id="Core_Architecture_0"></a>Core Architecture</h1>
<ul>
<li class="has-line-data" data-line-start="1" data-line-end="3">This is the highlevel overview of the each components in K8s core architecture.</li>
</ul>
<h2 class="code-line" data-line-start="3" data-line-end="4"><a id="Master_Node_Component_3"></a>Master Node Component</h2>
<ul>
<li class="has-line-data" data-line-start="5" data-line-end="8">
<h3 class="code-line" data-line-start="5" data-line-end="6"><a id="Master_5"></a>Master</h3>
<ul>
<li class="has-line-data" data-line-start="6" data-line-end="8">Manage, Plan, Schedule and Monitor slave nodes</li>
</ul>
</li>
<li class="has-line-data" data-line-start="8" data-line-end="11">
<h3 class="code-line" data-line-start="8" data-line-end="9"><a id="ETCD_8"></a>ETCD</h3>
<ul>
<li class="has-line-data" data-line-start="9" data-line-end="11">Database that stores information in a Key-Value format.</li>
</ul>
</li>
<li class="has-line-data" data-line-start="11" data-line-end="14">
<h3 class="code-line" data-line-start="11" data-line-end="12"><a id="KubeScheduler_11"></a>Kube-Scheduler</h3>
<ul>
<li class="has-line-data" data-line-start="12" data-line-end="14">Identifies the right node to place a container based on the containers resource requirements, the worker nodes capacity or any other policies &amp; constraints such as tents and tolerations or node affinity rules.</li>
</ul>
</li>
<li class="has-line-data" data-line-start="14" data-line-end="22">
<h3 class="code-line" data-line-start="14" data-line-end="15"><a id="Controllers_and_Controller_Manager_14"></a>Controllers and Controller Manager</h3>
<ul>
<li class="has-line-data" data-line-start="16" data-line-end="19">
<p class="has-line-data" data-line-start="16" data-line-end="17"><strong>Node-Controller</strong></p>
<ul>
<li class="has-line-data" data-line-start="17" data-line-end="19">Takes care of Nodes, responsible for onboarding new nodes to the cluster, handling situations where nodes become unavailable or gets destroyed.</li>
</ul>
</li>
<li class="has-line-data" data-line-start="19" data-line-end="22">
<p class="has-line-data" data-line-start="19" data-line-end="20"><strong>Replication Controller</strong></p>
<ul>
<li class="has-line-data" data-line-start="20" data-line-end="22">Ensures that desired number of containers are running all times in replication group.</li>
</ul>
</li>
</ul>
</li>
<li class="has-line-data" data-line-start="22" data-line-end="25">
<h3 class="code-line" data-line-start="22" data-line-end="23"><a id="KubeAPI_Server_22"></a>Kube-API Server</h3>
<ul>
<li class="has-line-data" data-line-start="23" data-line-end="25">Primary management component of K8s, Responsible of orchestrating all operations within the cluster, Exposes the K8s API which is used by external users to perform management operations on cluster and Kube-API Server also perform many other works.</li>
</ul>
</li>
</ul>
<h2 class="code-line" data-line-start="25" data-line-end="26"><a id="Slave_Node_Component_25"></a>Slave Node Component</h2>
<ul>
<li class="has-line-data" data-line-start="27" data-line-end="30">
<h3 class="code-line" data-line-start="27" data-line-end="28"><a id="Kubelet_27"></a>Kubelet</h3>
<ul>
<li class="has-line-data" data-line-start="28" data-line-end="30">It’s an agent runs on each node in a cluster. It listens for instructions from the kube-api server and deploys or destroys containers on the nodes as required.</li>
</ul>
</li>
<li class="has-line-data" data-line-start="30" data-line-end="32">
<h3 class="code-line" data-line-start="30" data-line-end="31"><a id="KubeProxy_30"></a>Kube-Proxy</h3>
<ul>
<li class="has-line-data" data-line-start="31" data-line-end="32">Ensures that the necessary rules are in place on the worker nodes to allow the containers running on them to reach each other.</li>
</ul>
</li>
</ul>
<hr>
<h2 class="code-line" data-line-start="33" data-line-end="34"><a id="ETCD_33"></a>ETCD</h2>
<ul>
<li class="has-line-data" data-line-start="34" data-line-end="36">It is Distributed, reliable key-value database that is simple, secure and fast.</li>
</ul>
<h3 class="code-line" data-line-start="36" data-line-end="37"><a id="KeyValues_Store_36"></a>Key-Values Store</h3>
<ul>
<li class="has-line-data" data-line-start="37" data-line-end="38">Stores information in Documents or pages.</li>
<li class="has-line-data" data-line-start="38" data-line-end="39">Changing one document does not affect other.</li>
<li class="has-line-data" data-line-start="39" data-line-end="41">Easy to convert into JSON.</li>
</ul>
<h3 class="code-line" data-line-start="41" data-line-end="42"><a id="ETCD_Control_Client_41"></a>ETCD Control Client</h3>
<ul>
<li class="has-line-data" data-line-start="42" data-line-end="43">Default Client</li>
<li class="has-line-data" data-line-start="43" data-line-end="44">It is a command line client for etcd and we can use it to store and retrive key-value pair.</li>
<li class="has-line-data" data-line-start="44" data-line-end="48">Store the value<pre><code class="has-line-data" data-line-start="46" data-line-end="48">./etcdctl set key1 value1
</code></pre>
</li>
<li class="has-line-data" data-line-start="48" data-line-end="53">Retrive the value<pre><code class="has-line-data" data-line-start="50" data-line-end="52">./etcdctl get key1
</code></pre>
</li>
</ul>
<h3 class="code-line" data-line-start="53" data-line-end="54"><a id="ETCD_Role_in_K8s_53"></a>ETCD Role in K8s</h3>
<ul>
<li class="has-line-data" data-line-start="54" data-line-end="55">Stores information regarding The Clusters, Such as nodes, pods, configs, secrets, accounts, roles, bindings and others.</li>
<li class="has-line-data" data-line-start="55" data-line-end="56">Every additional changes and information such as adding nodes, deploying pods or replica sets are updated in etcd server.</li>
<li class="has-line-data" data-line-start="56" data-line-end="58">Default port on which etcd listens is <code>2379</code>.</li>
</ul>
<h3 class="code-line" data-line-start="58" data-line-end="59"><a id="Explore_ETCD_58"></a>Explore ETCD</h3>
<ul>
<li class="has-line-data" data-line-start="59" data-line-end="60">K8s stores data in specific directory structre. Root directory is registery and under that we have various K8s constructs such as minions or nodes, pods, replicasets, deployments etc.</li>
</ul>
<hr>
<h2 class="code-line" data-line-start="61" data-line-end="62"><a id="KubeAPI_Server_61"></a>Kube-API Server</h2>
<ul>
<li class="has-line-data" data-line-start="62" data-line-end="63">Primary Management component in K8s.</li>
<li class="has-line-data" data-line-start="63" data-line-end="64">When we run any <code>kubectl</code> command, it infact reaching to the Kube-API Server. Kube-Api server first authenticate and validate the request. It then retrives the data from ETCD cluster and responds back with the requested information.</li>
<li class="has-line-data" data-line-start="64" data-line-end="66">We can also invoke api directly by sending post request.</li>
</ul>
<h3 class="code-line" data-line-start="66" data-line-end="67"><a id="Working_Process_66"></a>Working Process</h3>
<ul>
<li class="has-line-data" data-line-start="67" data-line-end="68">When user make request to create new node, Kube-API server first authenticate and validates the request. Then it register the pod into ETCD cluster and give feedback to user that pod is created.</li>
<li class="has-line-data" data-line-start="68" data-line-end="69">Kube-Scheduler continuously monitors the API Server and realize that there is a new pod with no node assigned. The scheduler identifies right node to place the new pod on and communicates that back to the Kube-API Server.</li>
<li class="has-line-data" data-line-start="69" data-line-end="70">The API server update the information into ETCD Cluster and then passes these informations to Kubelet in appropriate worker node.</li>
<li class="has-line-data" data-line-start="70" data-line-end="71">The Kubelet then creates the Pod on the node and instructes the container runtime engine to deploy the application image.</li>
<li class="has-line-data" data-line-start="71" data-line-end="72">Once done, The kubelets update the status back to the API Server and API Server then updates the data into ETCD Cluster.</li>
<li class="has-line-data" data-line-start="72" data-line-end="74">A similar pattern follows everytime changes reflected.</li>
</ul>
<h4 class="code-line" data-line-start="74" data-line-end="75"><a id="Summary_74"></a>Summary</h4>
<ul>
<li class="has-line-data" data-line-start="75" data-line-end="76">Authenticate User</li>
<li class="has-line-data" data-line-start="76" data-line-end="77">Validate Request</li>
<li class="has-line-data" data-line-start="77" data-line-end="78">Retrive Data</li>
<li class="has-line-data" data-line-start="78" data-line-end="79">Update ETCD</li>
<li class="has-line-data" data-line-start="79" data-line-end="80">Scheduler</li>
<li class="has-line-data" data-line-start="80" data-line-end="81">Kubelet</li>
</ul>
<hr>
<h2 class="code-line" data-line-start="82" data-line-end="83"><a id="Kube_Controller_Manager_82"></a>Kube Controller Manager</h2>
<ul>
<li class="has-line-data" data-line-start="83" data-line-end="84">It manages various contollers in K8s.</li>
<li class="has-line-data" data-line-start="84" data-line-end="86">It continuously monitors te state of various components within the system and works towards bringing the whole system to the desired functioning state.</li>
</ul>
<h3 class="code-line" data-line-start="86" data-line-end="87"><a id="Node_Controller_86"></a>Node Controller</h3>
<ul>
<li class="has-line-data" data-line-start="87" data-line-end="88">It is responsible for monitoring the status of the nodes and taking necessary actions to keep the application running.</li>
<li class="has-line-data" data-line-start="88" data-line-end="89">it does that through the Kube-API Server.</li>
<li class="has-line-data" data-line-start="89" data-line-end="90">it checks the status of the nodes every 5 seconds.</li>
<li class="has-line-data" data-line-start="90" data-line-end="91">If node fails it wait for 40 seconds to mark it as unreachable.</li>
<li class="has-line-data" data-line-start="91" data-line-end="93">After marking unreachable it waits for 5 mins for node to come back up, if does not then it removes the pod assigned to that node and provisioned them to the healthy one.</li>
</ul>
<h3 class="code-line" data-line-start="93" data-line-end="94"><a id="Replication_Controller_93"></a>Replication Controller</h3>
<ul>
<li class="has-line-data" data-line-start="94" data-line-end="95">It is responsible for monitoring the status of the Replica Sets and Ensuring that desired number of pods are available at all times within the set.</li>
<li class="has-line-data" data-line-start="95" data-line-end="97">if pod dies it creates another one.</li>
</ul>
<h4 class="code-line" data-line-start="97" data-line-end="98"><a id="Other_K8s_controller_are_as_below_97"></a>Other K8s controller are as below…</h4>
<ul>
<li class="has-line-data" data-line-start="98" data-line-end="99">Deployment Controller</li>
<li class="has-line-data" data-line-start="99" data-line-end="100">Namespace Controller</li>
<li class="has-line-data" data-line-start="100" data-line-end="101">Job Controller</li>
<li class="has-line-data" data-line-start="101" data-line-end="102">EndPoint Controller</li>
<li class="has-line-data" data-line-start="102" data-line-end="103">Service Account Controller</li>
<li class="has-line-data" data-line-start="103" data-line-end="104">PV Binder Controller</li>
<li class="has-line-data" data-line-start="104" data-line-end="105">PV Protection Controller</li>
<li class="has-line-data" data-line-start="105" data-line-end="106">Stateful Set</li>
<li class="has-line-data" data-line-start="106" data-line-end="107">Replica Set</li>
<li class="has-line-data" data-line-start="107" data-line-end="108">Cron Job</li>
<li class="has-line-data" data-line-start="108" data-line-end="109">and much more…</li>
<li class="has-line-data" data-line-start="109" data-line-end="110">This all controllers are packaged into single process called <strong>Kube-Controller Manager</strong>.</li>
</ul>
<hr>
<h2 class="code-line" data-line-start="111" data-line-end="112"><a id="Kube_Scheduler_111"></a>Kube Scheduler</h2>
<ul>
<li class="has-line-data" data-line-start="112" data-line-end="113">It responsible for scheduling the pods on nodes.</li>
<li class="has-line-data" data-line-start="113" data-line-end="114">It only responsible for deciding which pod goes on which node. It does not actually place the pod on the node. That is the job of the kubelet</li>
<li class="has-line-data" data-line-start="114" data-line-end="116">Scheduler only decides which pod goes where.</li>
</ul>
<h3 class="code-line" data-line-start="116" data-line-end="117"><a id="Why_need_scheduler_116"></a>Why need scheduler?</h3>
<ul>
<li class="has-line-data" data-line-start="117" data-line-end="118">In K8s The Scheduler decides which nodes the pods are placed on depending on certain criteria. We may have Pods with different resource requirements, we can have nodes in the cluster dedicated to certain applications.</li>
<li class="has-line-data" data-line-start="118" data-line-end="119">The Scheduler looks at each Pods and tries to find best node for it.</li>
<li class="has-line-data" data-line-start="119" data-line-end="120">If one Pod require 10 CPU then there is possible that all the nodes in cluster does not have 10 or more than 10 CPUs, some of them have or some of them do not have.</li>
</ul>
<hr>
<h2 class="code-line" data-line-start="121" data-line-end="122"><a id="Kubelet_121"></a>Kubelet</h2>
<ul>
<li class="has-line-data" data-line-start="122" data-line-end="123">Kubelet is like captain on the ship, It leads all the activity on Nodes.</li>
<li class="has-line-data" data-line-start="123" data-line-end="124">It registers the node with te Kubernetes Cluster. When It receives the instructions to load a container or POD on the node it requests the container runtime engine to pull the required image and run on the node.</li>
<li class="has-line-data" data-line-start="124" data-line-end="125">Kubelets then continues to monitor the state of the POD and the containers in it and reports to the Kube-API Server on a timely basis.</li>
</ul>
<hr>
<h2 class="code-line" data-line-start="126" data-line-end="127"><a id="Kube_Proxy_126"></a>Kube Proxy</h2>
<ul>
<li class="has-line-data" data-line-start="127" data-line-end="128">Within the K8s Cluster, every POD can reach every other pod, this is accomplished by deploying POD Netorking solution to the cluster.</li>
<li class="has-line-data" data-line-start="128" data-line-end="129">A Pod Network is an internal virtual network that spans across all the nodes in the cluster to which all the pods connect to.</li>
<li class="has-line-data" data-line-start="129" data-line-end="130">Kube-Proxy is a process that runs on the each node of the cluster. It’s job is to look for new services and every time a new service is created it creates the appropriate rules on each nodes to forward traffic to those services to the backend Pods. One way it does this is using IPTABLES rules.</li>
</ul>
<hr>
<h2 class="code-line" data-line-start="131" data-line-end="132"><a id="PODs_131"></a>PODs</h2>
<ul>
<li class="has-line-data" data-line-start="132" data-line-end="133">The containers are encapsulated into the K8s Object knows as Pods. A Pods is a single instance of an application and it’s the smallest object in K8s.</li>
<li class="has-line-data" data-line-start="133" data-line-end="134">If we want to scale up we can create new Pods or New Nodes with Pods and to scale down we can delete Pods or Nodes as per the requiements.</li>
<li class="has-line-data" data-line-start="134" data-line-end="135">A single pod can ave multiple containers except for the fact that they are usually not multiple containers of the same kind.</li>
<li class="has-line-data" data-line-start="135" data-line-end="136">Multi Container are rare use case scenario and best practice suggest that we should run single container per Pod.</li>
</ul>
<hr>
<h2 class="code-line" data-line-start="137" data-line-end="138"><a id="Replication_Controller_and_Replica_Set_137"></a>Replication Controller and Replica Set</h2>
<ul>
<li class="has-line-data" data-line-start="138" data-line-end="139">What if for some reason our application crashes and users will no longer be able to access our application.</li>
<li class="has-line-data" data-line-start="139" data-line-end="140">To Prevent this we would like to run more than single instance at a time. So if one fails we still have other containers on which our app is running.</li>
<li class="has-line-data" data-line-start="140" data-line-end="141">The Replication Controller help us to run multiple Pods of single part thus providing High Availability. So even if we have single pod and if it crashes the replication controller can help by automatically bringing up the new pod.</li>
<li class="has-line-data" data-line-start="141" data-line-end="142">Replication Controller ensures that the specified number of pods are running at all times.</li>
<li class="has-line-data" data-line-start="142" data-line-end="143">It also help us to share load across the Pods.</li>
<li class="has-line-data" data-line-start="143" data-line-end="144">Replication Controller and Replica Set both are similar terms. Both have same Purpose but they are not the same.</li>
<li class="has-line-data" data-line-start="144" data-line-end="145">Replication Controller is the older technology that is being replaced by Replica Set.</li>
<li class="has-line-data" data-line-start="145" data-line-end="146">Replica Set monitors the Pods using Lable, Lable works as a filter for Replica Sets when there is 100s of Pods are running.</li>
</ul>
<hr>
<h2 class="code-line" data-line-start="147" data-line-end="148"><a id="Deployments_147"></a>Deployments</h2>
<ul>
<li class="has-line-data" data-line-start="148" data-line-end="149">Suppose we might want to deploy our app in production environment. We want to deploy multiple instances for web servers running.</li>
<li class="has-line-data" data-line-start="149" data-line-end="150">In addition to whenever newer version of app comes we also want to roll update on each instances one by one, and if one of the update results in unexpected error and we need to undo the recent change we would like to be able to roll back the changes that were recently carried out.</li>
<li class="has-line-data" data-line-start="150" data-line-end="151">Also we would like to do multiple changes in our production environment, such as modifying resources, scaling the environment etc… We do not want to apply the changes immediately after the command is run, instead we would like to pause the environment, make the changes and resumes the environment so all the changes roll-out together.</li>
<li class="has-line-data" data-line-start="151" data-line-end="152">All of these capabilities are available in K8s Deployments.</li>
<li class="has-line-data" data-line-start="152" data-line-end="153">The Deployments provides us with the capabilities to upgrade the underlying instaces, rolling updates, undo changes and Pause and Resume changes as required.</li>
</ul>
<hr>
<h2 class="code-line" data-line-start="154" data-line-end="155"><a id="NameSpaces_154"></a>NameSpaces</h2>
<ul>
<li class="has-line-data" data-line-start="155" data-line-end="156">K8s creates <code>Default</code> namespace automatically when the cluster is first setup. K8s also creates <code>Kube-System</code> namespace for it’s internal purpose and the third namespace is called <code>kube-public</code> this is where resources that should be made available to all users are created.</li>
<li class="has-line-data" data-line-start="156" data-line-end="157">We can create our own NameSpaces as well.</li>
<li class="has-line-data" data-line-start="157" data-line-end="158">Each namespace can have it’s own set of policies.We can also assign quota or resources to each of these resources.</li>
<li class="has-line-data" data-line-start="158" data-line-end="159">
<ul>
<li class="has-line-data" data-line-start="158" data-line-end="159">Resources within same namespace can refer each other using Names. If require resource can reach another namesapce as well.</li>
</ul>
</li>
</ul>
<hr>
<h2 class="code-line" data-line-start="160" data-line-end="161"><a id="Services_160"></a>Services</h2>
<ul>
<li class="has-line-data" data-line-start="161" data-line-end="162">K8s services enables te communications between various components within and outside of the application.</li>
<li class="has-line-data" data-line-start="162" data-line-end="163">Services enables the loose coupling between microservices in our applications.</li>
<li class="has-line-data" data-line-start="163" data-line-end="170">K8s Service is the an object. There are multiple type of service available.
<ul>
<li class="has-line-data" data-line-start="164" data-line-end="166"><strong>NodePort Service</strong>
<ul>
<li class="has-line-data" data-line-start="165" data-line-end="166">It’s use case is to listen to a port on the Node and Forward requests on that Port to a Port on the POD running Web Application. Valid Port range for NodePort service is from 30000 to 32767.</li>
</ul>
</li>
<li class="has-line-data" data-line-start="166" data-line-end="168"><strong>Cluster IP Service</strong>
<ul>
<li class="has-line-data" data-line-start="167" data-line-end="168">Service creates a Virtual IP inside the cluster to enable communication between diffrent services. Example set of frontend servers services to set of backend servers services.</li>
</ul>
</li>
<li class="has-line-data" data-line-start="168" data-line-end="170"><strong>LoadBalancer Service</strong>
<ul>
<li class="has-line-data" data-line-start="169" data-line-end="170">It provisions a Load Balancer for our application in supported cloud providers.</li>
</ul>
</li>
</ul>
</li>
</ul>
</div>
</div>
</div>
</div>
</div>
<script src="./README_files/monetization.js.download" type="text/javascript"></script>
<script>
  (function () {
    if (typeof _bsa !== 'undefined' && _bsa) {
      _bsa.init('default', 'CVADP53W', 'placement:dillingerio', {
        target: '.ad-container',
        align: 'horizontal',
        disable_css: 'true'
      });
    }
  })();
</script>
<script src="./README_files/main.bundle.js.download" type="text/javascript" async=""></script>


</body><grammarly-desktop-integration data-grammarly-shadow-root="true"></grammarly-desktop-integration></html>