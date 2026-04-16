# 반응형

반응형 웹 디자인은 다양한 화면 해상도에서도 편리하도록 만드는
웹 디자인 방식입니다.

먼저 `@media`는 css에서 화면크기나 해상도에 따라 다른 스타일을 적용 할수 있게
해줍니다.

예시

```css
@media (max-width: 500px) {
  body {
    background-color: red;
  }
}
/*화면 너비가 500px 이하일 때 배경색을 빨강으로 바꿉니다*/
```

다음으로 `max-width`와`min-width`는 화면 너비가 지정한 값 이하나 이상일떄
스타일을 적용하려고 사용합니다.

`max-width`는 화면 너비가 지정한 값 이하일 때 적용,
`min-width`는 반대로 이상일때 적용합니다.

예시

```css
@media (max-width: 500px) {
  body {
    background-color: red;
  }
}
/*화면 너비가 500px 이하일 때 배경색을 빨강으로 바꿉니다*/
@media (min-width: 500px) {
  body {
    background-color: red;
  }
}
/*화면 너비가 500px 이상일 때 배경색을 빨강으로 바꿉니다*/
```

반응형 단위는 고정된 `px`같은 단위가 아닌 기준 요소에 따라 크기가 변하는
단위입니다.

종류에는 부모 요소 크기를 기준으로 비율을 계산하는 `%`

화면 전체 너비를 기준으로 계산하는 `vw`

화면 전체 높이를 기준으로 계산하는 `vh`

루트의 폰트 크기를 기준으로 계산하는 `rem`이 있습니다.

# Flexbox

`Flexbox`는 요소를 Flex 컨테이너로 만들어줍니다.
Flex 컨테이너는 안에 있는 요소들이 자동으로 가로 또는 세로 방향으로 배치되게 합니다.

예시

```css
.Flexbox {
  display: flex;
}
```

Flexbox요소에는
`justify-content`,`align-items` 등이 있습니다.

먼저 `justify-content`는 주축 정렬을 제어합니다.
주요 값으로

<ul>
    <li>왼쪽 정렬하는 flex-start </li>
    <li>오른쪽 정렬하는 flex-end</li>
    <li>가운데 정렬하는 center</li>
    <li>양 끝에 붙이고, 사이를 균등 분배하는 space-between</li>
    <li>요소 사이만 동일한 여백으로 설정하는 space-around</li>
</ul>
등이 있습니다.

`align-itmes`는 반대로 교차축 방향 정렬을 제어합니다.
주요 값으로

<ul>
    <li>왼쪽 정렬하는 flex-start </li>
    <li>오른쪽 정렬하는 flex-end</li>
    <li>가운데 정렬하는 center</li>
</ul>
등이 있습니다.
