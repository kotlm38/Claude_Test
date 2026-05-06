# Commit Convention

## 형식

```
[<type>(<scope>)] : <subject>

<body>

<footer>
```

---

## Type

| 타입 | 설명 |
|------|------|
| `Feat` | 새로운 기능 추가 |
| `Fix` | 버그 수정 |
| `Docs` | 문서 수정 |
| `Style` | 코드 포맷 변경 (기능 변경 없음) |
| `Refactor` | 코드 리팩토링 |
| `Test` | 테스트 추가 또는 수정 |
| `Chore` | 빌드 설정, 패키지 관리 등 기타 변경 |

---

## 규칙

- `subject`는 50자 이내로 작성
- 마침표(`.`) 사용 금지
- 명령문 형태로 작성 (예: "Add feature" not "Added feature")
- `body`는 선택 사항이며 72자 줄바꿈 권장
- `footer`에는 관련 이슈 번호 기재 (예: `Closes #123`)

---

## 예시

```
[Feat(auth)] : Add login with Google OAuth

사용자가 Google 계정으로 로그인할 수 있도록 OAuth 2.0 연동 추가.

Closes #42
```

```
[Fix(api)] : Handle null response from user endpoint
```

```
[Docs] : Update COMMIT_CONVENTION.md with examples
```
