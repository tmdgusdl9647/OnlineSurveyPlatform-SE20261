# Use Case Descriptions - 로그인, 로그아웃, 설문 수정

## Use case description: 로그인

| Actor Action | System Response |
| --- | --- |
|  | 1. 시스템은 로그인 화면을 표시한다. |
| 2. 사용자가 ID, 비밀번호를 입력한다. |  |
| 3. 사용자가 로그인 버튼을 선택한다. | 4. 시스템은 사용자에게 메인 화면을 제공한다. |

**Alternative Courses**

- 2a. 사용자가 입력한 ID 또는 비밀번호가 일치하지 않는 경우, 시스템은 ID와 비밀번호를 사용자에게 다시 입력받는다.

---

## Use case description: 로그아웃

| Actor Action | System Response |
| --- | --- |
|  | 1. 시스템은 로그아웃 화면을 표시한다. |
| 2. 사용자가 로그아웃 버튼을 선택한다. | 3. 시스템은 로그인 화면을 출력한다. |

**Alternative Courses**

- None.

---

## Use case description: 설문 수정

| Actor Action | System Response |
| --- | --- |
|  | 1. 시스템은 응답한 설문 화면을 표시한다. |
| 2. 회원이 현재 진행 중인 설문 중 수정하고 싶은 설문을 선택한다. | 3. 시스템은 기존 응답과 최근 수정 날짜가 포함된 설문 수정 화면을 표시한다. |
| 4. 회원이 응답 내용을 수정한다. |  |
| 5. 회원이 수정 버튼을 선택한다. | 6. 시스템은 수정 완료 메시지를 출력한다. |

**Alternative Courses**

- 2a. 설문이 종료된 경우, 수정 버튼을 비활성화한다. 
