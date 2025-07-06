# Vue.js

## 개요

- 프로그레시브 자바스크립트 프레임워크
- 웹 사용자 인터페이스를 만들기 위한 쉽고 강력하며 다재다능한 프레임워크

## 내용

### 코드 형태

Vue(발음: /vjuː/, view와 비슷함)는 사용자 인터페이스를 구축하기 위한 자바스크립트 프레임워크입니다. 표준 HTML, CSS, JavaScript 위에 구축되며, 선언적이고 컴포넌트 기반의 프로그래밍 모델을 제공하여 복잡도에 상관없이 효율적으로 사용자 인터페이스를 개발할 수 있도록 도와줍니다.

다음은 최소한의 예시:

```js
import { createApp, ref } from 'vue';

createApp({
  setup() {
    return {
      count: ref(0),
    };
  },
}).mount('#app');
```

```template
<div id="app">
  <button @click="count++">
    Count is: {{ count }}
  </button>
</div>
```

### 특징

싱글 파일 컴포넌트​

```js
<script setup>
import { ref } from 'vue'
const count = ref(0)
</script>

<template>
  <button @click="count++">Count is: {{ count }}</button>
</template>

<style scoped>
button {
  font-weight: bold;
}
</style>
```

## 링크

https://ko.vuejs.org/
