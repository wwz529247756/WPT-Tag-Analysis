| WPT测试文件路径（相对WPT工程目录） | 对应样式标签被测试内容描述 |
| ----------- | ----------- |
| dom\events\Event-cancelBubble.html | Event.cancelBubble |
| dom\events\Event-defaultPrevented-after-dispatch.html | Event.defaultPrevented is not reset after dispatchEvent() |
| dom\events\Event-dispatch-bubbles-false.html | Event.bubbles attribute is set to false |
| dom\events\Event-dispatch-bubbles-true.html | Event.bubbles attribute is set to false |
| dom\events\Event-dispatch-detached-input-and-change.html | input and change events for detached checkbox and radio elements |
| dom\events\Event-dispatch-handlers-changed.html | Dispatch additional events inside an event listener |
| dom\events\Event-dispatch-omitted-capture.html | EventTarget.addEventListener: capture argument omitted |
| dom\events\Event-dispatch-on-disabled-elements.html | Events must dispatch on disabled elements |
| dom\events\Event-dispatch-order-at-target.html | Listeners are invoked in correct order (AT_TARGET phase) |
| dom\events\Event-dispatch-redispatch.html | EventTarget#dispatchEvent(): redispatching a native event |
| dom\events\Event-dispatch-reenter.html | Dispatch additional events inside an event listener |
| dom\events\Event-dispatch-single-activation-behavior.html | Only one activation behavior is executed during dispatch |
| dom\events\Event-dispatch-target-moved.html | Determined event propagation path - target moved |
| dom\events\Event-dispatch-target-removed.html | Determined event propagation path - target removed |
| dom\events\Event-dispatch-throwing.html | Throwing in event listeners |
| dom\events\Event-init-while-dispatching.html | Re-initializing events while dispatching them |
| dom\events\Event-returnValue.html | Event.returnValue |
| dom\events\Event-stopImmediatePropagation.html | Event's stopImmediatePropagation |
| dom\events\Event-stopPropagation-cancel-bubbling.html | 测试Event-stopPropagation-cancel-bubbling中相关HTML元素的行为 |
| dom\events\Event-subclasses-constructors.html | Event constructors |
| dom\events\Event-timestamp-cross-realm-getter.html | event.timeStamp is initialized using event's relevant global object |
| dom\events\EventListener-handleEvent-cross-realm.html | Cross-realm EventListener throws TypeError of its associated Realm |
| dom\events\EventListener-handleEvent.html | EventListener::handleEvent() |
| dom\events\EventListener-incumbent-global-1.sub.html | 测试meta元素的事件处理或行为 |
| dom\events\EventListener-incumbent-global-2.sub.html | 测试meta元素的事件处理或行为 |
| dom\events\EventListener-invoke-legacy.html | Invoke legacy event listener |
| dom\events\EventListenerOptions-capture.html | EventListenerOptions.capture |
| dom\events\EventTarget-add-listener-platform-object.html | addEventListener with a platform object |
| dom\events\EventTarget-dispatchEvent-returnvalue.html | EventTarget.dispatchEvent: return value |
| dom\events\EventTarget-dispatchEvent.html | EventTarget.dispatchEvent |
| dom\events\EventTarget-this-of-listener.html | EventTarget listeners this value |
| dom\events\KeyEvent-initKeyEvent.html | KeyEvent.initKeyEvent |
| dom\events\event-disabled-dynamic.html | Test that disabled is honored immediately in presence of dynamic changes |
| dom\events\event-global-is-still-set-when-coercing-beforeunload-result.html | window.event is still set when 'beforeunload' result is coerced to string |
| dom\events\event-global-is-still-set-when-reporting-exception-onerror.html | window.onerror handler restores window.event after it reports an exception |
| dom\events\event-src-element-nullable.html | Event srcElement should be nullable |
| dom\events\handler-count.html | dom.spec.whatwg.org/#add-an-event-listener"> |
| dom\events\no-focus-events-at-clicking-editable-content-in-link.html | Clicking editable content in link shouldn't cause redundant focus related events |
| dom\events\non-cancelable-when-passive\generic-events-stay-cancelable.html | 测试meta元素的事件处理或行为 |
| dom\events\replace-event-listener-null-browsing-context-crash.html | Event listeners: replace listener after moving between documents |
| dom\events\resources\empty-document.html | 测试empty-document中相关HTML元素的行为 |
| dom\events\resources\event-global-is-still-set-when-coercing-beforeunload-result-frame.html | 测试event-global-is-still-set-when-coercing-beforeunload-result-frame中相关HTML元素的行为 |
| dom\events\resources\large-dimension-document.sub.html | 测试large-dimension-document.sub中相关HTML元素的行为 |
| dom\events\scrolling\iframe-chains.html | Allow the possibility the scroll is not fully synchronous |
| dom\events\scrolling\save-iframe-scroll-offset-when-display-none.html | Ensure that the scroll position isn't lost when the iframe is set to display:none and shown again |
| dom\events\scrolling\scroll-cross-origin-iframes.html | Verify that two sibling cross-origin iframes both correctly scroll on MouseWheel events, as per https://crbug.com/675695. |
| dom\events\scrolling\scroll-event-fired-to-element.html | Scroll event should behave correctly for Element.offsetTop and Element.offsetLeft |
| dom\events\scrolling\scroll-event-fired-to-iframe.html | Scroll event should behave correctly for Element.ScrollX and Element.ScrollLeft |
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
| dom\events\scrolling\scrollend-event-fires-to-iframe-window.html | Tests for scrollend events on an element within an iframe. |
| dom\events\scrolling\scrollend-event-for-user-scroll.html | Same issue as previous test. |
| dom\events\scrolling\scrollend-event-handler-content-attributes.html | The document body onscrollend event handler content attribute will fail |
| dom\events\scrolling\scrollend-event-not-fired-after-removing-scroller.tentative.html | Remove the element after reached half of the scroll offset, |
| dom\events\scrolling\scrollend-event-not-fired-on-no-scroll.html | 测试scrollend-event-not-fired-on-no-scroll中相关HTML元素的行为 |
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