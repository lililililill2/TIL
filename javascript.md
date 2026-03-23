# javascript 기본 문법

javascript에서 변수를 선언할때는 `let`을 쓰고

상수를 선언할 떄는 `const`를 사용합니다.

예시

```js
let a = 20;
const b = 20; //변경이 불가능합니다.
```

조건문은 `if`나 `else`등을 사용합니다.

각각 조건이 참, 거짓일때 실행합니다.

사용 방법은 거의 파이썬과 비슷하지만 약간 다른 점들이 있습니다.

파이썬은 `elif`를 쓰지만 자바스크립트는 `else if`를 쓰는 점 등이 있습니다.

예시

```js
if (s > 15) {
  console.log("15보다 크다");
} else {
  console.log("15보다 같거나 작다");
}
```

반복문은 `for`이나 `while`등을 사용합니다.

for은 정해진 횟수만큼 반복할 때 사용하고

while은 조건이 참인 동안 계속 반복합니다.

예시

```js
for (let i = 0; i < 5; i++) {
  console.log(i);
}

let count = 0;
while (count < 5) {
  console.log(count);
  count++;
}
```

일반적으로 함수는 선언할 떄 `function`을 사용합니다.

하지만 더 간단하게 표현할 때는 화살표 함수를 사용합니다.

```js
function greet(name) {
  return "Hello " + name;
}

const greetArrow = (name) => "Hello " + name; // 화살표 함수
```

자료구조에는 배열과 객체가 있습니다.

배열은 여러 값을 순서대로 저장하고 []를 사용합니다.

객체는 키와 값으로 구성해 저장하고 {}를 사용합니다.

예시

```js
let en = ["a", "b", "c"]; // 배열

let me = { color: "red", age: 15 }; // 객체
```
