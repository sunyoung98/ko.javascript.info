importance: 5

---

# 알림 만들기

 주어진 예제에서 `<div class="notification">` 알림을 만드는 `showNotification(options)` 함수를 작성해봅시다. 알림은 1.5초 후에 자동으로 사라집니다.

옵션은 다음과 같습니다.

```js
// shows an element with the text "Hello" near the right-top of the window
showNotification({
  top: 10, // 10px from the top of the window (by default 0px)
  right: 10, // 10px from the right edge of the window (by default 0px)
  html: "Hello!", // the HTML of notification
  className: "welcome" // an additional class for the div (optional)
});
```

[demo src="solution"]


CSS 포지셔닝을 사용하여 top/right 좌표에 알림을 표시하세요. 소스 문서에 필요한 스타일들이 있습니다.
