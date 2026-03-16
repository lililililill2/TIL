# CSS 기초 스타일링

css 기초 스타일링엔 글꼴,색상,배경등이 있습니다.

먼저 글꼴은 텍스트의 모양을 바꾸는 속성들입니다.

`font-family`는 글꼴지정,

`font-size`는 글자 크기,

`font-weight`는 글자 굵기,

`font-style`은 글자 스타일을 바꿉니다.

예시

```css
p {
  font-family: Arial, sans-serif; /* 글꼴 지정*/
  font-size: 16px; /* 글자 크기 */
  font-weight: bold; /* 글자 굵기 */
  font-style: normal; /* 글자 스타일 */
}
```

다음으로 색상은 텍스트나 요소의 색상을 지정할 수 있습니다.

색상을 지정하는 방법으로

```css
h1 {
  color: red; /* 색상 이름 */
  color: #ff0000; /* HEX 코드 */
  color: rgb(255, 0, 0); /* RGB 값 */
}
```

이렇게 대표적인 3가지 방식이 있습니다.

마지막으로 배경은 요소의 배경을 꾸밀 수 있습니다.

`background-color`로 배경의 색상을 바꿀수 있습니다.
예시

```css
div {
  background-color: red;
}
```

이렇게 css 기초 스타일링에 대해 알아보았습니다.
