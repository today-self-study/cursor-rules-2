# MCP Rules - 프론트엔드 규칙 요약 (Frontend)

## 폴더/파일 구조
- 기능 단위로 폴더 구성 (예: components, pages, hooks)
- 파일명은 소문자, kebab-case 또는 camelCase

## 코드 스타일
- Prettier, ESLint 등 도구로 코드 스타일 통일
- 함수형 컴포넌트, Hooks 우선 사용
- CSS-in-JS 또는 모듈화된 CSS 권장

## 커밋/PR
- 커밋 메시지, PR 규칙은 공통 규칙과 동일
- UI/UX 변경은 스크린샷 첨부

## 테스트
- 단위 테스트(Jest, React Testing Library 등) 필수
- 주요 로직/컴포넌트 테스트 코드 작성

## 기타
- API 통신은 axios, fetch 등 일관성 있게 사용
- 환경변수(.env) 관리, 민감정보 노출 금지

---

> 자세한 내용은 MCP rules 유튜브 영상을 참고하세요: https://youtu.be/5rCk0tjkvNM?si=RqOxkq-iMcFd9ryK
