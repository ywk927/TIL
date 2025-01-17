# 이것은 나의 TIL시작
# 트랙 특화 DAY3

GitHub: 1. 프로젝트 협업 2. 개인 포트폴리오

개발자들의 SNS가 GitHub

**문서화**의 중요성

- 신입 개발자에게 요구되는 가장 중요한 덕목 - 꾸준히 스스로 학습해 성장할 수 있고 문서화를 통해 내 생각을 정리하고 팀에게 공유할 수 있는 능력

[기사](https://d2.naver.com/news/3435170)

TIL (Today I learned) repo생성함

로컬 저장소에서 push하는 과정 (복습)

vi [README.md](http://README.md) → 안에 들어가서 내용 수정 가능

i 눌러서 insert하고 끝나면 esc 누르고 shift column, w q 누르면 저장하고 나감

cat [READ.md](http://READ.md) → 내가 수정내용 확인 가능

git remote -v: 현재 로컬 저장소에 등록된 원격 저장소 목록 보는 것

git remote rm 원격저장소이름:     “   삭제

clone해오면 remote 연결안해도 됨

안했으면 (pull했으면) **git remote add origin 주소** (로컬 저장소에 원격 저장소를 추가하는 것) 를 통해  해야됨

git push origin master

지금의 테스트: README.md는 하나만 있을 수 있는가?

1. 우리의 Repo: TIL
2. TIL/ README.md
    - [README.md](http://README.md) ← README.md의 역할은 Repo의 대문 역할
3. TIL/ALGO/디렉토리 생성
4. TIL/ALGO/README.md 새로 생성
5. TIL/ALGO/README.md에 내용 기입
6. 커밋 함

## 커밋 수정

- 커밋을 잘못하고 잘못된 점을 알았으면 ammend를 통해서 바로 수정할 수 있음
- 커밋을 삭제하는 방법
    1. 삭제를 했다고 기록을 남기는 법
    2. 아예 흔적도 안남게 지우는 법 (근데 이게 History를 남기는 관점에서 올바른 접근 방법인가? 에 대한 고찰이 필요)
    3. staging area로 내리는 방법
    4. WD로 내리는 방법