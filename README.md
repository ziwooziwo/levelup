원격저장소 만들기<br>
로컬에서 만든 것을 원격저장소 push (내 로컬, 내 원격)<br>
로컬은 이렇게 생김<br>
<img src="https://user-images.githubusercontent.com/121791920/213123605-f6d8c971-23e3-4cc0-8a95-524efaaebe86.jpg"><br>
로컬에서 mkdir 폴더명 > git init<br>
git remote add origin [원격저장소주소]<br>
git remote 엔터 (origin 이라고 나온다)<br>
예시<br>
<img src="https://user-images.githubusercontent.com/121791920/213122423-9c02dc80-b96c-409e-ac99-ac48e17f85eb.jpg"><br>
파일만들고 > git add . > git commit -m "커밋메세지"<br>
git branch -M main <br>
git push -u origin main <br>
원격저장소에서 README.md 파일 보여지는지 확인<br>
로컬에서 다른 파일 만들고 > git add . > git commit -m "커밋메세지"<br>
git push

끝!
