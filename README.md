# HTML
### 20250804 HTML시작
* 비주얼 스튜디오 코드 설치, 깃허브 회원가입, 깃 설치
* 비주얼 스튜디오 환경설정 및 플러그인 설치
### 주의사항
1. 영문 대소문자 사용하기(소문자 권장) 예) subTitle, sub_title
2. 숫자는 영문 뒤로 배치하기 예) sub1, main002
3. 공백 + 한글 사용금지
4. 특수문자 사용금지(#,$,%,^,&,*,(,+,\,~,★ 등..) *언더바(`_`) 하이픈(`-`) 가능
5. 이름은 의미있게 사용하기 예) images, fonts, mail, cafe 등..
6. 비주얼 스튜디오 코드 실행 시 작업 폴더 연결되어 있는지 확인하기
7. (위) 작업폴더 연결이 안되어 잇다면 ->File -> Close Folfer 후 다시 File -> Open Folder
### 깃(Git) 설치 확인
* Vscode에서 단축키 `Ctrl + J` 터미널 실행
* `git -v` 깃설치 버전 확인 (버전결과가 나온다면 설치 ok)
### 터미널 기본 설정
* 윈도우 기본 터미널 powershell을 git Bash로 변경하기
* (위 gitBash는 갓설치 후 사용 가능)
## git 설정과 gitHub 업로드까지 순서
1. `git config --list` : 현재 깃 설정 정보 확인
2. 새로운 입력창이 입력 안될때 터미널에서 `Ctrl+C` 또는 `Q` 입력
3. 위 1번에서 깃 설정 정보에 name, email이 내 정보가 아닐때
4. `git config --global user.email "a01099186626@gmail.com"` 이메일 설정 
5. `git config --global user.name "kimsuyeon1231"` 이름 설정 (메일 아이디와 동일)
6. `git config --list` 위 4~5번 설정 올바르게 됐는지 확인
---
7. `git init` 현재 폴더를 작업 디렉터리 폴더로 연결, 폴더 경로 옆에 **master** 표시 생기면 성공!
8. `git branch -M main` 깃 디렉터리명칭을 브랜치라고 부름. 해당 브랜치 명을 개인에 맞게 변경. 기본이 **main**
---
9. `git add .` **.**이란 작업수정한 모든 파일을 대기소(스테이지)에 올린다는 뜻. 만약 REDME.md만 올리고 싶을 경우 `git add REDME.md` 라고 명령어 입력하면 된다.
10. `git status` 현재 스테이지 확인 명령
11. `git commit -m ‘메세지기록’` 
12. `git remote add origin ‘깃허브 저장소 주소’`
13. git push origin main