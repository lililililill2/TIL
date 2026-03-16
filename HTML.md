# HTML 기본 구조

HTML 기본 구조는 <!DOCTYPE html>, <html>, <head>, <body>으로 구성됩니다.

먼저 <!DOCTYPE html>은 문서가 HTML5문법을 따른다는 선언문입니다.
항상 문서 가장 위에 작성됩니다.

다음으로 <html>은 문서의 전체 영역을 감싸는 태그입니다.
모든 콘텐츠는 이 태그 안에 들어가야 합니다.

<head>는 웹페이지의 정보를 담는 부분입니다.
화면에 보이는게 아닌, 검색엔진이 이해하는 정보들이 들어갑니다.
예를 들면 <title>,<meta>,<link>등이 있습니다.

마지막으로 <body>는 실제로 화면에 표시되는 콘텐츠가 들어가는 부분입니다.
여기에 사용자가 보는 모든 요소가 작성됩니다.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body></body>
</html>
```

이렇게 html 기본구조가 구성됩니다.
