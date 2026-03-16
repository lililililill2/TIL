# CSS 기본 문법

CSS는 HTML 요소에 스타일을 적용합니다.
기본 구조는 선택자,속성,값으로 구성됩니다.
예시

```css
p/*선택자*/ {
  color/*속성*/: blue /*값*/;
  font-size: 16px;
}
```

# CSS Selector 사용법

선택자는 HTML요소를 지정하는 방법입니다.
대표적으로 태그를 선택하는 종류는

태그 선택자

```css
p {
  color: red;
}
```

클래스 선택자

```css
.highlight {
  color: red;
}
```

아이디 선택자

```css
#title {
  color: red;
}
```

전체 선택자

```css
* {
  color: red;
}
```

등이 있습니다.
