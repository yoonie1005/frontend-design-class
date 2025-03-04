[[TOC]]
<br><br>

# PC 사용자 이름 변경

<br>

## Windows PC 이름 변경
| 한글로 PC 이름 설정 된 경우 명령어 사용 시 오류 이슈 문제가 많아 영문으로 변경이 필요 합니다.

1. Windows 아이콘을 우클릭 후 설정 열기
  ![](https://imgsh-net.s3.amazonaws.com/32483115788642f99012703c71d0a917.png)

2. PC 이름 바꾸기 클릭 후 띄어쓰기 없이 영문으로 작성하고 다음
  ![](https://imgsh-net.s3.amazonaws.com/77220e8a68e3f2cff71e5e7d4f324ec5.png)

3. 다시 시작 (재부팅 하기)
  ![](https://imgsh-net.s3.amazonaws.com/1346fd8d9095f7345cc6640cb65aa811.png)

4. `C:\Users\영문이름` 폴더명 확인

## PC 이름 변경되지 않는 경우
1. Windows(아이콘)+R 실행 창 열고 `lusrmgr.msc` 입력 후 확인
  ![](https://imgsh-net.s3.amazonaws.com/605467c2520242dac830dae3806bf5f4.png)

2. 한글 사용자 계정 이름을 찾아 영문이름으로 변경
    - Windows 11일 경우 [사용자 계정](https://journeying.tistory.com/118#:~:text=Windows%2011%20%EC%82%AC%EC%9A%A9%EC%9E%90%20%EA%B3%84%EC%A0%95%20%EC%82%AC%EB%9D%BC%EC%A7%90%20%ED%95%B4%EA%B2%B0%EB%B0%A9%EB%B2%95%201%201.,...%204%204.%20%EC%95%88%EC%A0%84%20%EB%AA%A8%EB%93%9C%20%ED%95%B4%EC%A0%9C%ED%95%98%EB%8A%94%20%EB%B2%95%20) 실행 파일 다운로드 설치 후 진행
    - [명령어로 변경하는 방법](https://fivem.tistory.com/84) 참고

3. PC 이름 변경 완료 후 재부팅

<br><br>

# git 설치

![](https://velog.velcdn.com/images/b1uesoda/post/b3a456b4-071b-4a9b-9c87-e759d36cfcb9/image.png)

- Git - 소스 이력 추적을 위한 버전 관리 시스템
- Github - git 프로젝트를 관리하는 저장소 제공

<br><br>

## Mac 설치 방법

1. [Homebrew](https://brew.sh/) 명령어로 설치
    ````bash
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ````
    or
    ````bash
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    (echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/example/.profile
    eval "$(/opt/homebrew/bin/brew shellenv)"
    ````

   - [`zsh: command not found: brew`](https://miracleground.tistory.com/entry/Mac%EC%97%90%EC%84%9C-Homebrew-%EC%84%A4%EC%B9%98-%ED%9B%84-zsh-command-not-found-brew-%EC%98%A4%EB%A5%98%ED%95%B4%EA%B2%B0) 오류 발생 시 해결 방법 참고

2. [Download for macOS](https://git-scm.com/downloads/mac) 접속
   - brew 명령어로 git 설치
      ````bash
      brew install git
      ````
   - [macOS에서 Git 설치하기](https://velog.io/@seoxuni/%EB%A7%A5%EC%97%90%EC%84%9C-%EA%B9%83%ED%97%88%EB%B8%8C-%EC%97%B0%EB%8F%99%ED%95%98%EA%B8%B0) 참고

3. 설치 완료 후 git 버전 확인
    - 명령 프롬프트git 버전 확인
      ````bash
      git --version
      ````

<br><br>

## Windows 설치 방법

1. [Download for Windows](https://git-scm.com/downloads/win) 접속

2. 64-bit Git for Windows Setup으로 설치

3. 설치 파일 실행 후 Next 진행
![](https://imgsh-net.s3.amazonaws.com/fbb2a1a42927982aa204eb15005faf3d.png)

4. 윈도우 터미널 활용을 위해 Add a Git Bash Profile to Windows Terminal 항목 체크 후 Next 진행
![](https://imgsh-net.s3.amazonaws.com/3e07db2e92099bc0552baa7d3de16be4.png)

5. VS Cose에 Git을 Default로 설정하기 위해 Use Visual Studio Code as Git's default editor을 선택 후 Next 진행
![](https://imgsh-net.s3.amazonaws.com/031b789cc301f69ee21a9a5e35f41b25.png)

6. Let Git decide 선택 후 이후 과정은 모두 Next 진행 (기본 설정)

7. Install 진행 (설치 완료 후 git 버전 확인)
![](https://imgsh-net.s3.amazonaws.com/ff84340d2bed39d1866c9a64865216f1.png)