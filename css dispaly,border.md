# css display 속성과 border 속성

display 속성은 요소를 블록 레벨요소와 인라인 요소 중
어느 쪽으로 처리할지 정의합니다

만약 블록 레벨 요소를 인라인으로 처리하고 싶다면

```css
div {
  display: inline;
}
```

인라인 요소인 a 요소를 블록 레벨로 처리하고 싶다면

```css
a {
  display: block;
}
```

이렇게 정의할 수 있습니다.

또 인라인으로 배치하되, 블록 레벨 요소의 속성을 추가하고 싶다면

```css
div {
  display: inline-block;
}
```

표시하지 않으려면

```css
div {
  display: none;
}
```

이렇게 정의할 수 있습니다.

border 속성은 테두리의 두께, 모양,색상 등을 한번에 지정할 수 있는 단축속성입니다.

```css
span {
  border: 2px solid green;
}
```

이렇게 쓰면 두께가 2px인 직선 모양의 초록 테두리를 만들라는 뜻과 같습니다.

border 속성의 하위 속성으로

색을 지정하는 border-color

두께를 지정하는 border-width

테두리의 선을 지정하는 border-style이 있습니다.
