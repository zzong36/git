# Git에 관하여<br>

## 1. Git과 GitHub
Git은 파일을 쉽게 관리하도록 도와주는 프로그램입니다. <br>
특히 여러 버젼의 파일을 한 번에 관리하거나, 다른 사람들과 협업할 때 용이하게 사용할 수 있습니다.<br>
반면 GitHub는 쉽게 말해 웹 클라우드입니다. GitHub에 있는 내용을 fork하여 여러 개발자와 함꼐 협업할 수 있습니다. <br>

### GitHub 기본 사용 방법
GitHub를 이용하기 위해 알아야 하는 정보를 유튜브 영상으로 만들었습니다.
<iframe width="640" height="360" src="https://www.youtube.com/embed/fCC2SRMziJQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>


## 2. GitBash 사용법
### Git 초기 설정
저장소 초기화: >> git init <br>
사용자에 설정: >>git config --global user.name,  >>git config --global user.email <br>
저장소 상태 확인: >> git status<br>
저장소에 저장: >> git add 와 >> git commit -m<br>
#### !!TIP!!
Git 저장소를 잘못 설정한 경우(이상한 파일 git init) 차분하게 숨겨진 .git 폴더를 다 지우면 해결됩니다.<br>


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
다른 Branch clone 하기: >> git checkout -t origin/브랜치 이름<br>

### Push와 Pull
Push는 Local에서 원격저장소로 보냅니다.<br>
커밋 한 후 Push: >> git push<br>
Pull은 원격 저장소에서 Local로 데이터를 가져오기: >> git pull<br>



## Sourcetree 사용법
Sourcetree를 사용하면 직관적으로 Git을 관리할 수 있습니다.<br>
사용방법은 아래 영상에 자세히 설명하였습니다.<br>
<iframe width="640" height="360" src="https://www.youtube.com/embed/km2_F3--S6U" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe><br>

* Sourcetree에서 깃허브(Github)로 로그인할 때 비밀번호를 잘못 설정해 Push나 Pull이 안 되는 경우<br>
다음 [링크](https://stackoverflow.com/questions/45690641/sourcetree-wont-let-me-delete-password)를 참고해주세요.

## 공부하며 느낀 점
Git과 Github 사용 방법을 처음 익힐 때는 약간 난해했지만 연습을 통해 익숙해지니 향후 파일관리에 적극적으로 사용할 수 있다는 자신감이 생겼습니다.<br>
문제를 하나씩 해결해 나갈 때마다 실력이 쌓이는 것 같아 학습 동기부여가 됩니다. 




