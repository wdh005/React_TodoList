# ToDOList

---

## 사용 언어(framework)

---

1. javascript
2. css
3. react(framework)

## 사용 라이브러리

---

1. react-icons
2. styled-components

## 설명

---

- React framework를 이용하여 TodoList를 만들었습니다.
- 스타일은 CSS in Js 방식으로 구성하여 따로 css파일을 분리하지 않고 styled-components라이브러리를 사용해 js파일에 직접 스타일을 적용하였습니다.
- checkbox, 휴지통 icon은 react-icons 라이브러리로 가져와 사용했습나다.

  > import { MdDone, MdDelete } from 'react-icons/md';

- TodoTemplate = TodoList layout 설정
- TodoHead = 오늘의 날짜와 요일, 남은 Todo를 보여준다
- TodoList = TodoItem component를 랜더링
- TodoItem = 할 일에 대한 정보를 렌더링 & 완료여부 체크기능 & 삭제 기능
- TodoCreate = 새로운 할 일을 등록
