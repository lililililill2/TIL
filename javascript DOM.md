# DOM 조작

DOM은 html 문서를 트리 구조로 표현한 것 입니다 그래서 DOM을 통해 html 요소 수정이 가능합니다.

## 요소 선택

그러기 위해 먼저 수정할 요소를 선택해야하는데 이때 쓰는 것이

`document.querySelector`와`document.querySelectorAll`입니다.

먼저 `document.querySelector`는 문서 전체에서 조건에 맞는 첫 번쨰 요소 단 하나만 찾아옵니다.

예시

```js
// class가 'title'인 요소를 찾아서 title이라는 변수에 저장
const title = document.querySelector(".title");
```

`document.querySelectorAll`는 문서 전체에서 조건에 맞는 모든 요소를 다 찾고 리스트 형태로 가져옵니다.

예시

```js
// class가 'name'인 모든 요소를 찾아서 names라는 변수에 저장.
const names = document.querySelectorAll(".name");
```

## 요소 내용 수정

이제 대상을 정했다면 이제 수정 할 수 있습니다.

여기에도 종류가 있는데 `textContent`와 `innerHTML`이 있습니다.

`textContent`는 요소의 텍스트만 바꿔서 HTML 태그를 적어도 그냥 일반 글자로 취급합니다

예시

```js
const en = document.querySelector(".a");
en.textContent = "<strong>apple</strong>"; // 화면에 '<strong>안녕</strong>' 이라고 태그째로 보임
```

`innerHTML`는 요소 안에 있는 내용을 HTML 태그까지 포함해서 가져오거나 바꿉니다.

예시

```js
// 실제 글씨가 굵어지는 <strong> 태그가 화면에 적용되어 보여짐
box.innerHTML = "<strong>안녕하세요!</strong>";
```

## 요소 생성과 추가

기존의 것을 바꾸는 것만 아니라 새로운 태그를 만들고 추가 할 수 있습니다.

추가 할 떄는 `createElement`를 사용합니다.
하지만 여기선 만들기만 한 상태라 아직 화면에 보이진 않습니다.

예시

```js
// <div> 태그를 하나 생성
const new = document.createElement('div');
new.textContent = "새로운 박스";
```

이제 추가하려면 `appendChild`를 사용합니다.
이 작업을 해야 새롭게 만든 태그가 화면에 나타납니다.

예시

```js
// 이미 문서에 있는 <body> 태그를 찾는다
const body = document.querySelector('body');

// 아까 만들어둔 new를 <body> 안의 맨 끝에 붙인다
body.appendChild(new);
```
