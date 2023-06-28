
1. 브랜치 관리
   - 새로운 브랜치 생성: 
     ```markdown
     git branch <branch_name>
     ```
   - 브랜치 전환:
     ```markdown
     git checkout <branch_name>
     ```
   - 브랜치 생성 및 전환:
     ```markdown
     git checkout -b <branch_name>
     ```
   - 브랜치 목록 확인:
     ```markdown
     git branch
     ```
   - 브랜치 병합:
     ```markdown
     git merge <branch_name>
     ```

2. 원격 저장소 관리
   - 원격 저장소 추가:
     ```markdown
     git remote add <remote_name> <remote_url>
     ```
   - 원격 저장소 목록 확인:
     ```markdown
     git remote -v
     ```
   - 원격 저장소에서 변경 내용 가져오기:
     ```markdown
     git pull <remote_name> <branch_name>
     ```
   - 원격 저장소로 변경 내용 푸시:
     ```markdown
     git push <remote_name> <branch_name>
     ```

3. 변경 내용 관리
   - 변경 내용 스테이징:
     ```markdown
     git add <file>
     ```
   - 변경 내용 커밋:
     ```markdown
     git commit -m "<commit_message>"
     ```
   - 변경 내용 로그 확인:
     ```markdown
     git log
     ```
   - 변경된 파일 상태 확인:
     ```markdown
     git status
     ```
   - 변경 내용 비교:
     ```markdown
     git diff
     ```

4. 기타 명령어
   - 이전 커밋으로 돌아가기:
     ```markdown
     git reset <commit_hash>
     ```
   - 원격 저장소의 변경 내용 가져오기:
     ```markdown
     git fetch
     ```
   - 변경 내용 되돌리기:
     ```markdown
     git revert <commit_hash>
     ```
