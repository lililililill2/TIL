# 이벤트 처리

## 이벤트 리스너

이벤트 처리란 사용자의 행동에 웹 페이지가 반응하도록 만드는 과정입니다.

이벤트 처리를 하기 위해 먼저 `addEventListener`를 사용합니다.

이 메소드는 이벤트를 감지하는 역할을 하고 이벤트가 발생하면 설정한 내용을 실행합니다.

```js
const button = document.querySelector("button");

function handler(event) {
  console.log("버튼 클릭");
}

button.addEventListener("click" /*이벤트 종류*/, handler);
```

## 주요 이벤트

이벤트에도 종류가 있습니다. 대표적으로 `click`, `input`, `change` 등이 있습니다.

`click`은 말 그대로 마우스로 요소를 클릭했을 떄 발생합니다.

`input`은 입력창에 글자를 타이핑할 때마다 실시간으로 발생합니다.

`change`는 입력창에서 내용이 바뀐 상태로 나갈 때 발생합니다.

## 이벤트 객체

이벤트가 발생하면 정보가 생기는데 이걸 정리한 것을 이벤트 객체라고 합니다.
주로 알아보기 쉽게 `event` 나 `e`로 사용합니다.

`event.target`은 이벤트에서 가장 중요한 정보입니다.
이벤트가 일어난 태그를 가리킵니다.
