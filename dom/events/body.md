| WPT测试文件路径（相对WPT工程目录） | 对应样式标签被测试内容描述 |
| ----------- | ----------- |
| dom\events\Body-FrameSet-Event-Handlers.html | HTMLBodyElement and HTMLFrameSetElement Event Handler Tests |
| dom\events\Event-cancelBubble.html | Event.cancelBubble |
| dom\events\Event-defaultPrevented-after-dispatch.html | Event.defaultPrevented is not reset after dispatchEvent() |
| dom\events\Event-dispatch-bubble-canceled.html | Setting cancelBubble=true prior to dispatchEvent() |
| dom\events\Event-dispatch-detached-input-and-change.html | input and change events for detached checkbox and radio elements |
| dom\events\Event-dispatch-multiple-cancelBubble.html | Multiple dispatchEvent() and cancelBubble |
| dom\events\Event-dispatch-multiple-stopPropagation.html | Multiple dispatchEvent() and stopPropagation() |
| dom\events\Event-dispatch-on-disabled-elements.html | Events must dispatch on disabled elements |
| dom\events\Event-dispatch-propagation-stopped.html | Calling stopPropagation() prior to dispatchEvent() |
| dom\events\Event-dispatch-throwing-multiple-globals.html | Returns a promise which will resolve with the next error event fired at any |
| dom\events\Event-returnValue.html | Event.returnValue |
| dom\events\Event-stopPropagation-cancel-bubbling.html | 测试Event-stopPropagation-cancel-bubbling中相关HTML元素的行为 |
| dom\events\Event-timestamp-cross-realm-getter.html | event.timeStamp is initialized using event's relevant global object |
| dom\events\event-global-is-still-set-when-coercing-beforeunload-result.html | window.event is still set when 'beforeunload' result is coerced to string |
| dom\events\event-global-is-still-set-when-reporting-exception-onerror.html | window.onerror handler restores window.event after it reports an exception |
| dom\events\event-src-element-nullable.html | Event srcElement should be nullable |
| dom\events\handler-count.html | dom.spec.whatwg.org/#add-an-event-listener"> |
| dom\events\no-focus-events-at-clicking-editable-content-in-link.html | Clicking editable content in link shouldn't cause redundant focus related events |
| dom\events\passive-by-default.html | Default passive event listeners on window, document, document element, body |
| dom\events\pointer-event-document-move.html | crbug.com/341104769"> |
| dom\events\preventDefault-during-activation-behavior.html | preventDefault during activation behavior |
| dom\events\resources\empty-document.html | 测试empty-document中相关HTML元素的行为 |
| dom\events\resources\event-global-is-still-set-when-coercing-beforeunload-result-frame.html | 测试event-global-is-still-set-when-coercing-beforeunload-result-frame中相关HTML元素的行为 |
| dom\events\resources\large-dimension-document.sub.html | 测试large-dimension-document.sub中相关HTML元素的行为 |
| dom\events\scrolling\iframe-chains.html | Allow the possibility the scroll is not fully synchronous |
| dom\events\scrolling\input-text-scroll-event-when-using-arrow-keys.html | move cursor to the right until the text scrolls |
| dom\events\scrolling\overscroll-deltas.tentative.html | Even though we request 300 extra pixels of scroll, the API above doesn't |
| dom\events\scrolling\overscroll-event-fired-to-document.tentative.html | overscroll events are bubbled when the target node is document. |
| dom\events\scrolling\overscroll-event-fired-to-element-with-overscroll-behavior.tentative.html | Test that both "onoverscroll" and addEventListener("overscroll"... work. |
| dom\events\scrolling\overscroll-event-fired-to-scrolled-element.tentative.html | Make sure that no overscroll event is sent to document. |
| dom\events\scrolling\overscroll-event-fired-to-window.tentative.html | overscroll events targetting document are bubbled to the window. |
| dom\events\scrolling\scroll-cross-origin-iframes.html | Verify that two sibling cross-origin iframes both correctly scroll on MouseWheel events, as per https://crbug.com/675695. |
| dom\events\scrolling\scrollend-event-fired-after-sequence-of-scrolls.tentative.html | Skip the test on a Mac as they do not support touch screens. |
| dom\events\scrolling\scrollend-event-fired-after-snap.html | Wait for the scroll snap animation to finish. |
| dom\events\scrolling\scrollend-event-fired-for-mandatory-snap-point-after-load.html | scrollend + mandatory scroll snap test |
| dom\events\scrolling\scrollend-event-fired-for-programmatic-scroll.html | 测试scrollend-event-fired-for-programmatic-scroll中相关HTML元素的行为 |
| dom\events\scrolling\scrollend-event-fired-for-scroll-attr-change.html | 测试scrollend-event-fired-for-scroll-attr-change中相关HTML元素的行为 |
| dom\events\scrolling\scrollend-event-fired-for-scrollIntoView.html | scrollend events are bubbled when the target node is document. |
| dom\events\scrolling\scrollend-event-fired-to-document.html | Scroll up on target div and wait for the doc to get scrollend event. |
| dom\events\scrolling\scrollend-event-fired-to-element-with-overscroll-behavior.html | Test that both "onscrollend" and addEventListener("scrollend"... work. |
| dom\events\scrolling\scrollend-event-fired-to-window.html | Scroll up on target div and wait for the doc to get scrollend event. |
| dom\events\scrolling\scrollend-event-fires-on-visual-viewport.html | No need to undo scroll; subsequent test has room to scroll further. |
| dom\events\scrolling\scrollend-event-fires-to-iframe-inner-frame.html | 测试scrollend-event-fires-to-iframe-inner-frame中相关HTML元素的行为 |
| dom\events\scrolling\scrollend-event-fires-to-iframe-window.html | Tests for scrollend events on an element within an iframe. |
| dom\events\scrolling\scrollend-event-for-user-scroll.html | Same issue as previous test. |
| dom\events\scrolling\scrollend-event-handler-content-attributes.html | The document body onscrollend event handler content attribute will fail |
| dom\events\scrolling\scrollend-event-not-fired-after-removing-scroller.tentative.html | Remove the element after reached half of the scroll offset, |
| dom\events\scrolling\scrollend-event-not-fired-on-no-scroll.html | 测试scrollend-event-not-fired-on-no-scroll中相关HTML元素的行为 |
| dom\events\scrolling\scrollend-fires-to-text-input.html | 测试scrollend-fires-to-text-input中相关HTML元素的行为 |
| dom\events\scrolling\scrollend-with-snap-on-fractional-offset.html | This test aims to verify that scrollend fires correctly (i.e. once) |
| dom\events\scrolling\wheel-event-no-scroll-after-prevent-default.html | Ensure that the calling `preventDefault` on a wheel event prevents a scroll from happening |
| dom\events\scrolling\wheel-event-transactions-basic.html | Ensure that the wheel transaction fires all wheel events to the initial |
| dom\events\scrolling\wheel-event-transactions-multiple-action-chains.html | The first action chain should target the initial element |
| dom\events\scrolling\wheel-event-transactions-target-display-change.html | Modify the initial element the wheel event is targetted at to |
| dom\events\scrolling\wheel-event-transactions-target-elements.html | Wheel event transactions target elements, not nodes. A wheel event |
| dom\events\scrolling\wheel-event-transactions-target-move.html | Move the initial element the wheel event is targetted at once we fire the |
| dom\events\scrolling\wheel-event-transactions-target-removal.html | Remove the initial element the wheel event is targetted at once we fire the |
| dom\events\scrolling\wheel-event-transactions-target-resize.html | Resize the initial element the wheel event is targetted at once we fire the |
| dom\events\webkit-animation-end-event.html | Prefixed CSS Animation end events |
| dom\events\webkit-animation-iteration-event.html | Prefixed CSS Animation iteration events |
| dom\events\webkit-animation-start-event.html | Prefixed CSS Animation start events |
| dom\events\webkit-transition-end-event.html | Prefixed CSS Transition End event |
| dom\events\window-composed-path.html | Window: Event.composedPath() |