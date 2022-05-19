# Pull Request 실습 - N행시 짓기

1. 현재 강사의 원격 저장소를 Fork 합니다.  
```
오른쪽 상단 Fork 누르기
```

<br>

2. Fork한 자신의 원격 저장소를 로컬에 Clone 합니다.  
```bash
git clone https://~~~
```

<br>

3. 자신의 이름으로 브랜치를 생성하고 해당 브랜치로 이동합니다.  
```bash
git branch edukyle
git switch edukyle
```

<br>

4. `acrostic-poem.md` 파일에 N행시를 작성하고 커밋을 남긴 후, 자신의 원격 저장소에 Push 합니다.
```bash
git add .
git commit -m "Update acrostic-poem.md"
git push origin edukyle
```

<br>

5. 자신의 원격 저장소에서 Pull Request를 보냅니다.
```
자신 이름 브랜치 -> 강사의 master 브랜치
```

<br>

6. 강사의 원격 저장소의 Pull Request 목록에서 자신의 PR을 찾아봅니다.
