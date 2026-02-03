| WPT测试文件路径（相对WPT工程目录） | 对应样式标签被测试内容描述 |
| ----------- | ----------- |
| dom\events\non-cancelable-when-passive\resources\scrolling.js | rAF twice. |
| dom\events\scrolling\scroll_support.js | Waits until a rAF callback with no "scroll" event in the last 200ms. |
| dom\events\scrolling\scrollend-user-scroll-common.js | Skip the test on a Mac as they do not support touch screens. |