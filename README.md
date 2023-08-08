<b>vanillaJS</b><br>
HTML을 먼저 만들고 그걸 JavaScript로 가져와서 HTML을 수정<br>

<b>ReactJS</b><br>
JavaScript를 이용해 element를 만들고 React JS가 그걸 HTML로 번역<br>
(모든 것이 JavaScript로 시작. 그 다음에 HTML이 된다.)<br>
***여러가지 요소들을 리렌더링하려고 해도 전부 다 새로 생성되지 않고 바뀐 부분만 생성된다.<br>


<i>createElement</i><br>
-
ReactJS의 기초이고 어려운 방식이다.<br>

<i>JSX & babel</i><br>
-
JavaScript를 확장한 문법이다.<br>
HTML에서 사용한 문법과 흡사한 문법을 사용해서 React 요소를 만든다.<br>

브라우저가 JSX를 이해할 수 있도록 babel을 사용한다.<br>
babel: JSX로 적은 코드를 브라우저가 이해할 수 있는 형태로 바꿔준다.<br>
(⇒createElement 형태로 바뀐다. / script 태그에 type 필요)<br>

React element를 함수 내에 담으면 컴포넌트로 사용 가능하다.<br>
***컴포넌트의 첫 글자는 반드시 대문자여야 한다.<br>
소문자면 그냥 HTML tag로 인식된다.<br>
