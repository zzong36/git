# Git이란 무엇인가?
## 1. Git과 GitHub의 차이는?
Git은 파일을 쉽게 관리하게 도와주는 프로그램입니다. <br>
여러 버젼의 파일을 한 번에 관리하거나, 다른 사람들과 협업할 때 용이하게 사용할 수 있습니다.<br>
GitHub는 쉽게 말해 웹 클라우드입니다. GitHub에 있는 내용을 fork하여 여러 개발자와 함꼐 협업할 수 있습니다. <br>

## 2. GitBash 사용법
### Git 초기 설정
Git 저장소를 초기화: >> git init <br>
사용자에 설정: >>git config --global user.name,  >>git config --global user.email <br>
Git 저장소의 상태 확인: >> git status<br>
Git 저장소에 저장: >> git add 와 >> git commit -m<br>

### Branch 관리
Branch는 새로운 기능을 추가하거나 버그 수정을 할 때 사용할 수 있는데, GitBash에서는 다음의 명령어를 이용합니다.<br>
현재 브랜치 확인 >> git branch<br>
브랜치 생성 >> git branch 새로운 브랜치 이름<br>
브랜치 변경 >> git checkout 브랜치 이름<br>
브랜치 합치기 >> git merge 브랜치 이름 (병합될 브랜치로 가서 명령어를 입력해야 합니다)<br>

### Remote 저장소 연동하기
원격 저장소와 연동하기 위해서는 다음 단계를 따르면 됩니다.<br>
원격 저장소 저장: >> git remote add origin GitHub 원격 저장소 주소<br>
저장이 잘 되었는지 확인: >> git remote 또는 >> git remote -v<br>
원격 저장소 Branch 가져오기(default가 clone 됨): >> git clone 깃허브 Repository 주소<br>



