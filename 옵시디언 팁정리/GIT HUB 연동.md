

##### GIT HUB 연동

원본 : https://alive-wong.tistory.com/65

  
만약, 깃이 설치되어 있지 않으면 운영체제와 CPU 아키텍처에 맞는 Git을 설치해야한다.
[Git git-scm.com](https://git-scm.com/)


```
echo "# lcc_team_obsidan" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/82wewego/lcc_team_obsidan.git
git push -u origin main
```


일련의 명령어를 터미널 창에 입력하여 기존 옵시디언 디렉토리에 생성한 깃허브 리포지토리와의 연결이 가능해진다.


---

#####  Obsidian Git 구성 및 연동

우선 커뮤니티 플러그인에서 Obsidian Git을 검색하여 설치한다.

기본적인 구성을 위해서 아래의 공식 문서를 참고했다.

 [Start here - Git Documentation - Obsidian Publish

Obsidian-Git Documentation Topics Installation Getting Started Authentication Features Tips-and-Tricks Common Issues Line Authoring Obsidian installation on LinuxPlease don't use Flatpak or Snap to i…

publish.obsidian.md](https://publish.obsidian.md/git-doc/Start+here)

  
  
이후 설정 창을 들어오면 하단의 설정 가능한 요소들을 알 수 있다. 이제 간단한 설정들을 수행하면, 아래와 같다.

![etc-image-4](https://blog.kakaocdn.net/dn/dqdwEz/btsBCYFUtyT/KPVsSuHcStp727y9ydyAsK/img.png)

해당 플러그인이 동작하는 과정을 설명하면 다음과 같다.

우선, 커밋이 생성되는 조건아래와 같다.

1. 새로운 파일 또는 파일을 포함한 디렉토리 생성되고 나서 1분

2. 파일을 변경하고 변경이 멈춘 지 1분

따라서, 파일을 처음 생성하고 나면 1분 뒤에 한번 커밋이 되고, 수정을 마무리하고(더 이상 변경이 없을 때) 1분 뒤에 커밋이 일어난다.

이후 이게 마무리 되면 5분 뒤에 Push가 진행되어 로컬 환경에서 커밋된 사항이 Github에 반영된다.

아래와 같이 기존 옵시디언 파일의 내용들이 Github에 Push되었음을 확인할 수 있다.

![Pasted image 20231208015940.png](https://blog.kakaocdn.net/dn/sd6UZ/btsBCoESxkB/784vxKVKV3ByhTB1ebkGXk/img.png)

자동으로 Push하는 것만 사용하게 된다면, 옵시디언을 닫아버리면 깃허브에 푸시가 일어나지 않을 것이다.

따라서, "Ctrl + P"를 눌러 빠른 명령 창을 연 다음 Git을 검색해보면 여러 명령이 존재하는데, 수동으로 Commit을 수행하고 Push를 진행하면 바로 변경 사항이 반영된다.

![etc-image-6](https://blog.kakaocdn.net/dn/M7AJC/btsBCnMQMAe/7kxby0Kf0Kkr5uNcoLyBFK/img.png)

또한, History View를 이용하여 변경 사항이 어떻게 진행되고 있는지를 한 눈에 확인이 가능하다. 이를 확인하기 위해선 마찬가지로 빠른 명령 창에서 아래처럼 확인이 가능하다.

![etc-image-7](https://blog.kakaocdn.net/dn/ZTwRn/btsBFePahUR/s1P9d15Jav0kddZ8FIKXT0/img.png)

![etc-image-8](https://blog.kakaocdn.net/dn/wtuz9/btsBB8bhu8R/L9IvGU6aec463biTCASOM1/img.png)

