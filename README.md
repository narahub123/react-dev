<meta charset="UTF-8">

# react-dev 정리

### [참고자료](https://react-ko.dev/)

## Describing the UI

<details>
<summary>Your First Component(첫번째 컴포넌트)</summary>

### Components: UI building blocking

#### 컴포넌트 : 리액트가 제공하는 마크업, CSS, 자바스크립트를 합친 재사용 가능한 UI 엘리먼트

### Defining a compenent

#### 리액트 컴포넌트는 마크업을 반환하는 자바스크립트 함수이다

#### 컴포넌트를 만드는 법

##### 컴포넌트 내보내기 : export default

##### 함수 정의 하기 : 함수명은 대문자로 시작되어햐 함

##### 마크업 추가하기 : 반환문이 두 줄이상인 경우에는 소괄호로 둘러싸여야 한다

### Using a component

#### 컴포넌트는 다른 컴포넌트에 중첩되어 사용 가능하다

### Nesting and organizing components

</details>

<details>
<summary>Importing and Exporting Component(컴포넌트 import 및 export)</summary>

### The root component file(루트 컴포넌트)

루트 컴포넌트 : ReactDOM.render() 메서드를 사용하여 DOM에 렌더링되는 최상위 컴포넌트

### Exporting and importing a component(컴포넌트 import 및 export 하기)

- 루트 컴포넌트 안에 있는 컴포넌트들을 루트 컴포넌트 파일 밖으로 옮기게 되면 모듈성이 강화되고 다른 파일에서 재사용이 가능해짐

- 컴포넌트를 export하고 import 하기

  - 컴포넌트를 넣을 js 파일 생성
  - 새로 만든 파일에서 함수 컴포넌트를 export함(default or named export 사용 )
  - 컴포넌트를 사용할 파일에서 import함

  <details>
    <summary>default export vs named export </summary>

  ![i_import-export.svg](https://prod-files-secure.s3.us-west-2.amazonaws.com/d7788950-4a28-47f3-841e-58e428d740a1/252a75f9-a492-4834-aa4a-1bfcbaf88b3c/i_import-export.svg)

  export 방식에 따라 import 방식이 정해짐

  | Syntax  | Export statement                    | Import statement                      |
  | ------- | ----------------------------------- | ------------------------------------- |
  | Default | export default function Button() {} | import Button from './Button.js';     |
  | Named   | export function Button() {}         | import { Button } from './Button.js'; |

  default import : import 후에 다른 이름으로 값을 가져올 수 있음

  ```jsx
  import Banana from "./Button.js";
  ```

  named import : 양쪽 파일에서 사용하고자 하는 값의 이름이 같아야 함

  ```jsx
  import { Button } from "./Button.js";
  ```

  </details>

### Exporting and importing multiple components from the same file (동일한 파일에서 컴포넌트 import 및 export 하기)

</details>

<details>
<summary>Writing Markup with JSX(JSX로 마크업 작성하기)</summary>

</details>

<details>
<summary>JavaScript in JSX with Curly Braces(JSX에서 JavaScript 사용하기)</summary>

</details>

<details>
<summary>Passing Props to a Component(컴포넌트에 props 전달하기)</summary>

</details>

<details>
<summary>Conditional Rendering(조건부 랜더링)</summary>

</details>

<details>
<summary>Rendering Lists(목록 랜더링)</summary>

</details>

<details>
<summary>Keeping Components Pure(컴포넌트 순수성 유지)</summary>

</details>

<details>
<summary>Your UI as a Tree(트리로 보는 UI)</summary>

</details>
