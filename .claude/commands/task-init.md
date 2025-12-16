---
description: 새 업무를 시작할 때 Task ID와 업무 설명을 설정하는 커맨드
---

# Task ID 설정

## 워크플로우

1. 사용자에게 질문: "어떤 작업을 하실 건가요? (분석, 정리, 개발 등)"
2. 사용자의 설명을 바탕으로 Task ID 3개 추천
   - 간결하고 명확한 식별자
   - 예: "user-data-analysis", "monthly-report", "api-integration"
3. 사용자가 추천 중 선택하거나 직접 입력
4. 선택된 Task ID를 파일로 저장

## 파일 생성

- 폴더: `_task/`
- 파일명: `L1_INIT.md`
- 내용: Task ID + 업무 설명

예시:
```markdown
# Task Init

## Task ID
user-data-analysis

## 업무 설명
사용자 데이터를 분석하여 월별 사용 패턴을 파악하고 리포트를 생성하는 작업
```

## Task ID 추천 가이드라인

- 소문자 + 하이픈 형식 (kebab-case)
- 작업 유형 + 대상/목적
- 예시:
  - 분석: `sales-data-analysis`, `user-behavior-report`
  - 정리: `document-cleanup`, `code-refactor`
  - 개발: `login-feature`, `api-endpoint`
