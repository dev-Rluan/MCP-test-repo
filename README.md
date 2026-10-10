# MCP-test-repo

MCP Studio용으로 자동 생성된 프로젝트 구조 템플릿입니다. Tool 정의, Context 구성, Claude 호출 테스트 화면에 해당하는 파일 경로가 마련되어 있습니다.

## 템플릿 탐색

| 위치 | 구성 |
|---|---|
| [src/app](src/app/) | 페이지·대시보드·Tool·Context·Test 화면 경로 |
| [src/features/toolBuilder](src/features/toolBuilder/) | Tool 폼·파라미터·응답 예시 파일 |
| [src/features/contextBuilder](src/features/contextBuilder/) | Context 폼·유형·상태 파일 |
| [src/features/claudeTester](src/features/claudeTester/) | 키 입력·프롬프트·결과·호출 로그 파일 |
| [src/lib](src/lib/) | Claude 클라이언트·JSON 구성 파일 |

## 현재 상태

확인한 대표 페이지·폼·클라이언트 파일과 `package.json`은 자동 생성 주석만 담고 있습니다. 파일 경로는 구현을 위한 틀이며, 동작하는 MCP 도구나 Claude 연동 앱을 의미하지 않습니다.

현재 설치·실행에 필요한 패키지 설정도 구현된 상태가 아니므로 실행 명령은 제공하지 않습니다. 라이선스는 [LICENSE](LICENSE)를 참고합니다.

