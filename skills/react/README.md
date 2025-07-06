# Vue.js

## 개요

- 웹 및 사용자 인터페이스를 위한 라이브러리

## 내용

Vue(발음: /vjuː/, view와 비슷함)는 사용자 인터페이스를 구축하기 위한 자바스크립트 프레임워크입니다. 표준 HTML, CSS, JavaScript 위에 구축되며, 선언적이고 컴포넌트 기반의 프로그래밍 모델을 제공하여 복잡도에 상관없이 효율적으로 사용자 인터페이스를 개발할 수 있도록 도와줍니다.

### 코드 형태

다음은 최소한의 예시:

```js
import { useState } from 'react';

function MyButton() {
  const [count, setCount] = useState(0);

  function handleClick() {
    setCount(count + 1);
  }

  return <button onClick={handleClick}>Clicked {count} times</button>;
}
```

## 링크

https://ko.react.dev/
