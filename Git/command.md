- Git 설정 및 초기화

```
#깃허브 원격 저장소 로컬로 복사하기
$ git clone 레포지토리
$ git clone ssh / https 주소
#깃 설정 관리
$ git config
```

- Git 기본 작업 명령어

```
#변경된 파일 스테이징 영역에 추가
$ git add 파일명
#변경된 모든 파일 스테이징 영역에 추가
$ git add . 
#스테이징 영역에 추가된 파일들을 커밋
$ git commit -m "작성할 커밋 메세지"
```

- Git 변경 내역 확인

```
#작업 디렉토리 상태 확인
$ git status
#현재 변경 내역을 확인
$ git diff
#전체 커밋 히스토리 확인
$ git log
#모든 커밋에 대한 내용 그래프로 나타내기
$ git log --graph
```

- 원격 저장소

```
#원격 저장소와 연결
$ git remote add origin <원격저장소 주소>
#현재 연결된 원격 저장소 확인
$ git remote -v
# git remote 취소 (원격저장소 연결 해제)
$ git remote rm origin
# 현재 연결된 원격 저장소 삭제
$ git remote remove <origin>
# 연결하고 있던 원격저장소의 '이름'이 변경되었을 때 재설정
$ git remote set-url origin <원격저장소 주소>
```

 - 브랜치

```
#브랜치 목록 확인
$ git branch
#새로운 브랜치 생성
$ git branch <브랜치이름>
#브랜치가 없으면 새로운 브랜치를 생성하고 이동 동시에
$ git checkout -b <브랜치이름>
#특정 브랜치로 전환
$ git checkout <브랜치이름>
$ git switch <브랜치이름>
#다른 브랜치를 현재 브랜치로 병합함
$ git merge <브랜치이름>
```
