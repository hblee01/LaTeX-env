# LaTeX env

도커와 vscode가 있다면 LaTeX을 쓸 수 있도록 세팅한 작업환경.

## How to use

1. 리눅스 환경(WSL 가능)에서 docker가 설치되어있어야 한다. docker를 설치할 때는 터미널에 다음과 같이 입력하면 된다. (Docker desktop 설치는 비추.)
    ```bash
    curl -fsSL https://get.docker.com -o get-docker.sh
    sudo sh get-docker.sh
    ```
    뭐라 하면서 뜸을 들인 후에 설치해서 시간이 좀 걸리지만 1분 내에 끝난다.    
    [출처 링크](https://docs.docker.com/engine/install/ubuntu/#install-using-the-convenience-script)  
2. vscode 설치. 
3. vscode 내에서 Dev Containers 확장을 설치한다.  
    `Ctrl + shift + X` 를 누르고 검색창에 Dev Containers를 검색하면 나온다.
4. 이 레포지토리를 `git clone`한다.
5. clone한 레포지토리를 vscode에서 연다. (`$ code .`)
6. `Ctrl + shift + P` 를 누르고 `Rebuild and Reopen in Container` 검색 후 `Enter`
7. .tex 파일과 .bib 파일을 만들고 사용하면 된다. 컴파일 결과는 `out` 디렉토리에 생성된다.

## 기능들
1. 자동 포멧팅
2. 오탈자 지적
3. LaTeX Workshop의 여러 기능들.. 
    1. 자동 컴파일 지원
    2. 수식 미리보기 지원
    등등..
