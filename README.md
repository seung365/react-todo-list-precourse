# react-todo-list-precourse

## 기능 구현 사항

- [x] 할 일을 추가하고 삭제할 수 있다.
- [x] 할 일을 추가할 때 사용자는 Enter 키나 추가 버튼을 사용하여 할 일을 목록에 추가할 수 있어야 한다.
- [x] 사용자가 아무것도 입력하지 않은 경우에는 할 일을 추가할 수 없다.
- [x] 할 일의 목록을 볼 수 있다.
- [x] 할 일의 완료 상태를 전환할 수 있다.

- [x] 현재 진행 중인 할 일, 완료된 할 일, 모든 할 일을 필터링할 수 있다.
- [x] 해야 할 일의 총개수를 확인할 수 있다.

## 구현 순서


- 먼저 List.js를 생성한다. 여기에서 TodoListItem을 담아준다.
- TodoListItem을 담아줄 TodoInsert를 구현한다.
- 여기서 TodoListItem의 checked 값에 따라 보여줄 Active 컴포넌트와 Completed 컴포넌트를 구현한다.
- 각 컴포넌트 별로 버튼을 만들어 각각의 페이지로 이동할 수 있게 한다.
- UI를 보여줄 화면을 구현한다. 여기서 각각의 페이지로 이동 가능하다.
- UI를 render해줄 UIRender을 구현해 준다.
- UI의 state를 관리해 줄 useToDoState를 구현한다.

