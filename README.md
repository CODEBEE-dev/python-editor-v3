# Python Editor v3
이 프로젝트는 https://github.com/microbit-foundation/python-editor-v3 를 fork 하여 생성한 프로젝트입니다.

python-editor-v3 를 CodeBridge 에 맞게 커스터마이징 하는 프로젝트 입니다.

<br />

# 원본 프로젝트 변경사항 적용하기
`git remote`
- `origin` ➡️ fork 한 저장소
- `upstream` ➡️ 원본 저장소

1. 원본 저장소 변경사항 가져오기
    ```bash
    git fetch upstream
    ```
2. 브렌치에 합치기
    ```bash
    git merge upstream/main

    # or

    git rebase upstream/main
    ```

<br />

# 프로젝트 실행
1. 저장소 clone
    ```bash
    git clone https://github.com/CODEBEE-dev/python-editor-v3.git
    ```
2. 의존성 설치
    ```bash
    npm install
    ```
3. 개발 실행
    ```bash
    npm start
    ```

<br />

# 프로젝트 Build
```bash
npm run build
```