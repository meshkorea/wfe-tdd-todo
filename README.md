# Todo app 요구사항

## todo 추가하기

1. 입력창이 있어야 한다.
2. todo 추가를 실행하면 입력한 내용이 목록에 추가된다.
3. todo 추가를 실행하면 입력창이 비워져야 한다.
4. todo 추가 실행 시 입력창이 비어있는 경우 오류메시지를 띄운다.

cf) todo 추가는 입력 버튼, 입력창에서 엔터키 누르기 등으로 실행 가능

## todo 목록

1. 처음 접속시 지금까지 입력한 todo 중 완료되지 않은 todo가 목록으로 출력된다.
2. 입력한 todo는 삭제할 수 있으며, 삭제한 경우 목록에서 제거된다.
3. 입력한 todo는 완료처리 할 수 있으며, 완료처리된 경우 목록에서 숨겨진다.
4. 완료된 todo는 별도로 정의된 방법으로 불러오거나 다시 숨길 수 있다.
5. 모두 완료되거나 입력한 것이 없어 목록이 비어있을 경우 목록이 비어있다는 메시지를 출력해야 한다.
6. 완료된 todo는 미완료처리 할 수 있으며, 미완료처리된 경우 목록에서 다시 보여진다.

cf) 삭제의 경우 다음 중 여러 개의 방식을 지원할 수 있다.

* 편집 모드 -> 선택 -> 삭제
* 삭제 버튼 상시 표시
* (모바일) 스와이프시 삭제 버튼 표시

cf) 완료된 todo의 경우 다음 중 하나의 방식을 지원할 수 있다.

* 미완료 / 완료 탭
* 목록 상단 또는 하단에 완료된 todo 보기 버튼

