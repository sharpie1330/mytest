# mytest

1. 포크
2. 브랜치 생성 -> sharpie - feature1
3. commit 후 원본저장소 sharpie브랜치로 pr
4. merge 후 sharpie 브랜치로 이동, 작업 브랜치 feature1 삭제
5. 원본 저장소 upstream 등록 git remote add -t sharpie1330 upstream gitUrl, git remote -v
6. git fetch upstream sharpie1330으로 자기 브랜치 정보 가져오기
7. 내 브랜치 동기화 git rebase upstream/sharpie1330
8. git push origin sharpie1330
9. 반복

테스트용 텍스트 추가
-> feature2 PR후 머지 전에 feature2에서 파생된 브랜치 feature3를 이어서 작업한 경우

git rebase feature1 main
-> feature1에 main을 이어붙이겠다는 소리...