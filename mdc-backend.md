# MCP Rules - 백엔드(Java Spring) 규칙 요약 (Backend)

## 프로젝트 구조
- multi-module 구조 권장 (core, api, batch 등)
- 패키지 네이밍: 기능/계층별로 구분 (controller, service, repository)

## 코드 스타일
- Java Code Convention, Checkstyle 적용
- 클래스/메서드/변수명은 명확하게
- Lombok 등 보조 라이브러리 사용 시 일관성 유지

## 커밋/PR
- 커밋 메시지, PR 규칙은 공통 규칙과 동일
- API 변경 시 Swagger 등 문서화 필수

## 테스트
- 단위/통합 테스트(JUnit, Mockito 등) 작성
- 테스트 커버리지 목표 설정

## 기타
- DB 마이그레이션 도구(Flyway, Liquibase 등) 사용
- 환경별 설정 분리(application.yml)

---

> 자세한 내용은 MCP rules 유튜브 영상을 참고하세요: https://youtu.be/5rCk0tjkvNM?si=RqOxkq-iMcFd9ryK
