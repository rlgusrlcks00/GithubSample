
1. 브랜치 관리
   - 새로운 브랜치 생성:
     ```markdown
     git branch <branch_name>
     ```
     새로운 브랜치를 생성합니다. `<branch_name>`에는 새로 생성할 브랜치의 이름을 입력합니다.

   - 브랜치 전환:
     ```markdown
     git checkout <branch_name>
     ```
     기존 브랜치에서 다른 브랜치로 전환합니다. `<branch_name>`에는 전환할 브랜치의 이름을 입력합니다.

   - 브랜치 생성 및 전환:
     ```markdown
     git checkout -b <branch_name>
     ```
     새로운 브랜치를 생성하고, 해당 브랜치로 전환합니다. `<branch_name>`에는 생성 및 전환할 브랜치의 이름을 입력합니다.

   - 브랜치 목록 확인:
     ```markdown
     git branch
     ```
     현재 저장소의 브랜치 목록을 확인합니다.

   - 브랜치 병합:
     ```markdown
     git merge <branch_name>
     ```
     다른 브랜치의 변경 내용을 현재 브랜치로 병합합니다. `<branch_name>`에는 병합할 브랜치의 이름을 입력합니다.

2. 원격 저장소 관리
   - 원격 저장소 추가:
     ```markdown
     git remote add <remote_name> <remote_url>
     ```
     새로운 원격 저장소를 로컬 저장소에 추가합니다. `<remote_name>`에는 원격 저장소의 이름을, `<remote_url>`에는 원격 저장소의 URL을 입력합니다.

   - 원격 저장소 목록 확인:
     ```markdown
     git remote -v
     ```
     현재 저장소에 연결된 원격 저장소의 목록과 URL을 확인합니다.

   - 원격 저장소에서 변경 내용 가져오기:
     ```markdown
     git pull <remote_name> <branch_name>
     ```
     원격 저장소로부터 변경된 내용을 가져와서 현재 브랜치에 병합합니다. `<remote_name>`에는 원격 저장소의 이름을, `<branch_name>`에는 가져올 브랜치의 이름을 입력합니다.

   - 원격 저장소로 변경 내용 푸시:
     ```markdown
     git push <remote_name> <branch_name>
     ```
     변경된 내용을 로컬 저장소에서 원격 저장소로 푸시합니다. `<remote_name>`에는 원격 저장소의 이름을, `<branch_name>`에는 푸시할 브랜치의 이름을 입력합니다.

3. 변경 내용 관리
   - 변경 내용 스테이징:
     ```markdown


     git add <file>
     ```
     변경된 파일을 스테이징 영역에 추가하여 커밋할 준비를 합니다. `<file>`에는 스테이징할 파일의 경로와 이름을 입력합니다.

   - 변경 내용 커밋:
     ```markdown
     git commit -m "<commit_message>"
     ```
     스테이징 영역에 있는 파일들을 커밋합니다. `<commit_message>`에는 커밋 메시지를 입력합니다.

   - 변경 내용 로그 확인:
     ```markdown
     git log
     ```
     저장소의 커밋 로그를 확인합니다.

   - 변경된 파일 상태 확인:
     ```markdown
     git status
     ```
     저장소의 변경된 파일의 상태를 확인합니다.

   - 변경 내용 비교:
     ```markdown
     git diff
     ```
     스테이징 영역과 현재 작업 트리 사이의 변경 내용을 비교합니다.

4. 기타 명령어
   - 이전 커밋으로 돌아가기:
     ```markdown
     git reset <commit_hash>
     ```
     특정 커밋으로 이동하여 이전 상태로 되돌립니다. `<commit_hash>`에는 이동할 커밋의 해시 값을 입력합니다.

   - 원격 저장소의 변경 내용 가져오기:
     ```markdown
     git fetch
     ```
     원격 저장소에서 변경된 내용을 가져옵니다.

   - 변경 내용 되돌리기:
     ```markdown
     git revert <commit_hash>
     ```
     특정 커밋의 변경 내용을 되돌립니다. `<commit_hash>`에는 되돌릴 커밋의 해시 값을 입력합니다.

