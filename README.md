1. 下载 https://html5test.co/ 站点
1. 将所有的链接改成相对链接，包括 css 对 fonts 对下载
1. 移除所有 a 链接，或者对它进行改进，将必要的链接用文本直接显示
1. 移除 header
1. 移除一些无用的 html 内容，在 base.js 里
1. base.js 同时加载本地的 detect.js 和[原版](api.whichbrowser.net)的，两次下载，执行两次 callback。每次执行 callback 需要清空 #results
1. 加入 messagechannel 的监听，用它来对外发送数据
