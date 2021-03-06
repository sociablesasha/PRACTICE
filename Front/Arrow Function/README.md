# Arrow Function (=화살표 함수)

## 정의
기존의 함수 선언을 => (화살표)로 나타낸 것을 말한다. 기존의 함수와 표기법만 다르다.

## 사용
```javascript
() => {
    console.log("Arrow");
}
```

간단하게 함수를 선언한 것이다. 함수 이름도 없어서 헷갈리고 쓸모가 없을 것 같은 함수로 보일 수도 있다. 하지만 그것은 크나큰 오산이다.

자바스크립트로 프로젝트를 진행해봤다면 가장 많이 사용하는 패턴이 아마 아래와 같은 콜백 패턴이다.

```javascript
let arr = ["a", "b", "c", "d", "e"];
arr.forEach(function () {});
```

콜백 함수를 더욱 간략하게 표기해주는 것이 이 화살표 함수가 될 수 있겠다.

```javascript
let arr = ["a", "b", "c", "d", "e"];
arr.forEach(() => {});
```

만약에 인자값을 받아야 한다면 어떻게 해야 할까?

```javascript
let arr = ["a", "b", "c", "d", "e"];
arr.forEach((elem) => {});
```

인자값을 받으면 된다. 어렵지 않으니 익숙해져 보자.