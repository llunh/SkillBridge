
# Git Convention

## 1. Commit Convention

### 기본 형식
type: 작업 내용

### Commit Type

| Type | 설명 |
|---|---|
| feat | 새로운 기능 추가 |
| fix | 버그 및 오류 수정 |
| data | 데이터 수집 및 전처리 |
| refactor | 코드 리팩토링 |
| docs | 문서 작성 및 수정 |
| test | 테스트 코드 작성 |
| chore | 환경 설정 및 기타 작업 |

### 작성 규칙
- type은 영어 소문자로 작성합니다.
- 작업 내용은 한글로 간결하게 작성합니다.
- 하나의 커밋에는 하나의 작업 단위를 포함합니다.
- 문장 끝에 마침표를 사용하지 않습니다.

### 예시
feat: 뉴스 크롤러 구현
fix: 데이터 수집 오류 수정
data: 결측치 처리
docs: README 작성
chore: requirements.txt 수정

## 2. Branch Convention

### 기본 형식
type/이슈번호-작업명

### 예시
feat/12-news-crawler
data/13-preprocessing
fix/14-crawling-error

## 3. Issue / PR Convention

### 제목 형식
[Type] 작업 내용

### 예시
[Feat] 뉴스 크롤러 구현
[Data] 수집 데이터 전처리
[Fix] 크롤링 오류 수정
[Docs] README 작성

## 4. 협업 규칙

1. 작업 전 Issue를 생성합니다.
2. Issue 번호를 포함한 브랜치를 생성합니다.
3. 개인 브랜치에서 작업 후 Commit 및 Push합니다.
4. PR을 생성하고 관련 Issue를 연결합니다.
5. 팀원 리뷰 후 기본 브랜치에 Merge합니다.
