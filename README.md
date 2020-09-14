git checkout --orphan images
git rm -rf
git add 20111226-a1.gif
git commit -m "カレンダーを追加しました"
git push origin images
git checkout master
vim README.md
![20111226-a1](https://user-images.githubusercontent.com/70795804/93086339-f52a2880-f6d1-11ea-89dd-cf0a75ef1484.gif)
git add README.md
git commit -m "画像を表示"
git push origin master
