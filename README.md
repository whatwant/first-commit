# first-commit
첫 번째 commit 공부를 위한 저장소

파일을 업데이트 했어요!

## Git 설치

[Git 공식 홈페이지](https://git-scm.com/)에서 Git 소개와 사용 설명서를 확인할 수 있습니다. 설치 파일은 [공식 다운로드 페이지](https://git-scm.com/downloads)에서 운영체제에 맞게 받을 수 있습니다.

### Windows

1. [Windows용 Git 다운로드 페이지](https://git-scm.com/download/win)에서 설치 파일을 받습니다.
2. 받은 설치 파일을 실행하고 안내에 따라 설치합니다.
3. 설치가 끝나면 Git Bash 또는 새 터미널을 엽니다.

### macOS

터미널에서 아래 명령을 실행해 Xcode Command Line Tools와 함께 Git을 설치합니다.

```sh
xcode-select --install
```

Homebrew를 사용 중이라면 `brew install git`으로도 설치할 수 있습니다.

### Linux

배포판에 맞는 패키지 관리자로 설치합니다.

Ubuntu / Debian:

```sh
sudo apt update
sudo apt install git
```

Fedora:

```sh
sudo dnf install git
```

### 설치 확인

설치 후 새 터미널에서 다음 명령을 실행합니다. Git 버전이 표시되면 설치가 완료된 것입니다.

```sh
git --version
```
