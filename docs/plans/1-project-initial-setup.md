# [chore] 프로젝트 초기 세팅

- 이슈: #1
- 마일스톤: `00-setup`

## 목표

이슈·PR·기록이 [작업 프로세스 규칙](../process.md)대로 쌓이도록 GitHub 저장소를 세팅한다.

## 할 일

| 항목 | 방법 | 담당 |
| --- | --- | --- |
| 라벨 | GitHub 기본 라벨 삭제, `type:` / `problem:` / `record:` / `epic` 생성 | Claude (API) |
| 마일스톤 | `00-setup` ~ `08-resume` 생성 | Claude (API) |
| 이슈 템플릿 | 작업 / Epic, 빈 이슈 막기 | 이 PR |
| PR 템플릿 | 이슈·계획·기록 링크, 리뷰 관점 체크, 머지 전 점검 | 이 PR |
| 문서 구조 | `docs/process.md`, `docs/plans/`, `docs/records/` | 이 PR |
| 기존 문서 이관 | Claude 문서 3건 → `docs/process.md`, `docs/records/1-design-*.md` | 이 PR |
| CLAUDE.md | 로컬 Claude Code가 규칙 문서를 먼저 읽도록 안내 | 이 PR |
| 브랜치 보호 | `main` 직접 push 금지, PR 필수, 승인 0명, 관리자도 적용 | WU (웹 UI, 이 환경에서는 API 쓰기 불가) |
| Projects 보드 | Todo / In Progress / Review / Done | WU (웹 UI, API로 생성 불가) |

## 결정한 것

- PR 템플릿에 "면접 질문 답변 여부"는 넣지 않는다.
- 브랜치 보호의 승인 수는 0명으로 둔다. 혼자 진행해 승인할 사람이 없기 때문이다.
- 세팅 작업용 마일스톤 `00-setup`을 추가했다. 로드맵 단계(01~08)에 속하지 않는 준비 작업을 담는다.

## 완료 조건

- 작업 템플릿으로 새 이슈를 만들 수 있다.
- `main`에 직접 push하면 거부된다.
- Projects 보드에 이슈가 보인다.
