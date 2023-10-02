## 점메추 기능구현
### 입력
- [ ] 코치 명단 입력받기(2-5명)
- [ ] 각 코치가 못 먹는 메뉴 입력(0-2가지)
### 메뉴 정하기
- [ ] 메뉴 카테고리 선정
  - [ ] 한 카테고리는 최대 한 주에 2회
- [ ] 메뉴 정하기
  - [ ] 못 먹는 메뉴인지
  - [ ] 매일 다른 메뉴인지
### 결과 출력
- [ ] 메뉴 추천 결과 출력


---

## commit message convention
```
<type>: <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```
### Subject line
Subject line 에는 변경 사항에 대한 간결한 설명이 포함되어 있어야 함

#### Allowed `<type>`
* feat (feature)
* fix (bug fix)
* docs (documentation)
* style (formatting, missing semicolons, …)
* refactor
* test (when adding missing tests)
* chore (maintain)

#### `<subject>` text
* 현재형으로 쓰기 : “바꿈” not “바꿨음”
* 끝에 마침표 (.) 쓰지 않기

### Message body
* 현재형으로 쓰기 : “바꿈” not “바꿨음”
* 변화에 대한 동기와 이전과의 차이점 포함하기

### Message footer

#### Referencing issues

Closed bugs 는 Closes로 #(issue 번호)로 마지막 줄에 명시해야 함:
```
Closes #234
```

여러 issue에 대해선 나열하여 명시:
```
Closes #123, #245, #992
```

예시
--------

```
feat: ng:disabled, ng:checked, ng:multiple, ng:readonly, ng:selected

New directives for proper binding these attributes in older browsers (IE).
Added coresponding description, live examples and e2e tests.

Closes #351
```

```
style: add couple of missing semi colons
```

```
docs: updated fixed docs from Google Docs

Couple of typos fixed:
- indentation
- batchLogbatchLog -> batchLog
- start periodic checking
- missing brace
```