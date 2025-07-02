# MCP Rules - 공통 규칙 요약 (Common)

## MCP란?
- MCP(Meta Cursor Protocol)는 대규모 협업, 코드 품질, 일관성 유지를 위한 규칙 집합입니다.
- 코드 리뷰, 커밋, 브랜치 전략, 협업 커뮤니케이션 등 개발 전반에 적용됩니다.

## 공통 규칙

### 1. 커밋 메시지
- 명확하고 일관된 커밋 메시지 작성
- 예시: `[타입] 기능/수정 요약 (이슈번호)`
- 타입 예시: feat, fix, docs, style, refactor, test, chore

### 2. 브랜치 전략
- main/master: 배포용
- develop: 개발 통합
- feature/이름: 기능 개발
- hotfix/이름: 긴급 수정

### 3. PR(Pull Request) 규칙
- PR 템플릿 사용, 제목/설명/이슈 연결 필수
- 리뷰어 지정, 셀프 머지 금지
- CI 통과 후 머지

### 4. 코드 리뷰
- 리뷰어는 코드 품질, 일관성, 보안, 성능 등 체크
- 리뷰어/작성자 모두 적극적 커뮤니케이션

### 5. 문서화
- 주요 기능/설정/사용법은 README, Wiki 등으로 문서화

---

> 자세한 내용은 MCP rules 유튜브 영상을 참고하세요: https://youtu.be/5rCk0tjkvNM?si=RqOxkq-iMcFd9ryK
