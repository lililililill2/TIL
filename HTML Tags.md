# HTML의 주요 태그

html의 주요 태그로 `<div>, <span>, <p>, <a>, <img>, <form>, <input>,<button>` 이 있습니다.

먼저 `<div>`는 웹 페이지를 블록으로 나눌 때 사용합니다.
주로 스타일을 적용할 때 자주 사용됩니다.
예시

```html
<div id="sing">
  <p>노래</p>
</div>
```

다음으로 `<span>`은 인라인 요소로, 글자나 문장 일부에 스타일을 적용할 때 자주 씁니다.
예시

```html
<p><span>예시</span>문구</p>
```

`<p>`는 문단을 나타냅니다.
텍스트를 문단 단위로 구분할 때 사용합니다.
예시

```html
<p>안녕하세요</p>
```

`<form>`은 사용자 입력을 받을 수 있는 양식을 정의합니다.
로그인,회원가입 등에 활용할 수 있습니다.
예시

```html
<form action="test.php" method="post">
  <input type="text" placeholder="아이디" />
  <br />
  <input type="text" placeholder="비밀번호" />
  <br />
  <input type="submit" value="로그인" />
</form>
```

`<input>`은 form 안에서 실제 입력 필드를 만드는 태그입니다.

마지막으로 `<button>`은 클릭 가능한 버튼을 생성합니다.
폼 제출 등에 사용합니다.

예시

```html
<button>버튼</button>
```

이렇게 html의 주요 태그들을 알아보았습니다.
