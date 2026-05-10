# Use Case Descriptions - 회원 가입, 회원 탈퇴, 설문 검색

## Use case description: 회원 가입

| Actor Action | System Response |
| --- | --- |
|  | 1. 시스템은 회원 가입 화면을 표시한다. |
| 2. 사용자가 ID, 비밀번호, 이름, 전화번호, 이메일을 입력한다. |  |
| 3. 사용자가 회원 가입 버튼을 선택한다. | 4. 시스템은 회원 가입을 완료한다. |

**Alternative Courses**

- 2a. 사용자가 필수 정보를 입력하지 않은 경우, 시스템은 회원 가입을 완료하지 않는다.

---

## Use case description: 회원 탈퇴

| Actor Action | System Response |
| --- | --- |
|  | 1. 시스템은 회원 탈퇴 화면을 표시한다. |
| 2. 회원이 회원 탈퇴 버튼을 선택한다. | 3. 시스템은 회원 탈퇴를 완료한다. |
|  | 4. 시스템은 해당 회원의 모든 이용 권한과 데이터를 삭제한다. |

**Alternative Courses**

- None.

---

## Use case description: 설문 검색

| Actor Action | System Response |
| --- | --- |
|  | 1. 시스템은 설문 검색 화면을 표시한다. |
| 2. 회원이 현재 진행 중인 설문 리스트, 향후 진행 예정인 설문 리스트, 종료된 설문 리스트 중 하나를 선택한다. |  |
| 3. 회원이 키워드를 입력한다. |  |
| 4. 회원이 검색 버튼을 선택한다. | 5. 시스템은 검색 조건에 맞는 설문 리스트를 출력한다. |

**Alternative Courses**

- None.
