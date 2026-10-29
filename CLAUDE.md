# 라커룸

플랩풋볼형 풋살 소셜 매치 플랫폼. 열린 매치에 개인이 한 자리씩 참가한다.
학습과 포트폴리오용 프로젝트이며 실운영은 하지 않는다 (샘플 데이터로 시연).

## 현재 단계
- 설계 단계 (~2026-11-14): `docs/` 문서만 작업한다. 코드는 만들지 않는다.
- 개발은 2026-11-15부터 시작한다.

## 구조 (예정)
- `backend/`: Java 21, Spring Boot 4.1, Spring Data JPA, MySQL 8.4
- `frontend/`: React, Vite, TypeScript, TanStack Query, Tailwind CSS, PWA
- `infra/`: Docker Compose, Nginx
- `docs/`: 기획, 설계 문서

## 문서 지도 (작업 전에 해당 문서를 먼저 읽는다)
| 작업 | 문서 |
|---|---|
| 서비스 범위, 정책 확인 | `docs/PRD.md` |
| 기능 구현 | `docs/spec/` 의 해당 기능 명세 |
| DB, API 설계 | `docs/design/` |
| 기술 선택, 단계별 도입, 테스트 방식 | `docs/tech-design.md` |
| 기술 결정의 이유 | `docs/adr/` |
| 작업 방식, 기록 규칙 | `docs/dev-process.md` |

## 작업 규칙
- 한국어로 답한다.
- 문서에 없는 정책이나 범위는 추측하지 말고 묻는다.
- `docs/PRD.md` 의 "하지 않을 것"에 있는 기능은 만들지 않는다.
- 여러 파일을 바꾸는 작업은 계획을 먼저 보여주고 확인받는다.
- 완료했다고 말할 때는 테스트, 빌드 결과를 근거로 보여준다.
- 커밋에 Claude 공동작성자(Co-Authored-By) 표시를 붙이지 않는다.
- `.env`, 키 같은 비밀값은 읽거나 커밋하지 않는다. `docs/private/` 는 커밋하지 않는다.

## 명령어
개발을 시작하면 빌드, 테스트, 실행 명령을 여기에 추가한다.
