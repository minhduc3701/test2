Twice - One In A Million

git init //tao mot git moi cho 1 project
git status //kiem tra status xem co thay doi nao k
git add // add thay doi vao staged
git commit // add thay doi vao head(day la ban luu cuoi cung)

git log // dua ra danh sach tat ca commit
git show //dia ra thong tin commit chi dinh
git diff diffirence // hien thi cac thay di trong file

working directory //thu muc dang lam viec
staging area  //khu vuc cho commit
git responsitory

git checkout  git restore <file> //xoa thay doi cua file
git reset     git restore --staged <file> //dua file tu staged ve working directory

git checkout -b <branch> (branching) //tao 1 branch moi de lam viec
git checkout <branch> //kiem tra branch hien tai dang lam viec
git merge //add branch vao master

gitk //bang dieu khien

git branch -d <branch> //xoa di 1 brand

git add . //them tat ca file, thay doi vao stage

(git reset se xoa, thay doi tu commit gan nhan den commit duoc chi dinh)
git reset --sort <to_commit> // dua thay doi tu HEAD ve lai staged
git reset --mixed <to_commit> // dua thay doi tu HEAD ve lai working directory
git reset --hard <to_commit> // xoa han thay doi

git revert <commit> //tra lai trang thai cua duy nhat commit duoc chi dinh

gitignore
npm init //tao file package.json chua thong tin ve project
git remote add origin <link github> //set link project github mac dinh cho project
git push //cap nhat project len github da tai len
git remote -v // check link github dang lam viec
git remote set-url origin <link github> // thay doi link project github
git push -u origin master //tai len github project (lan dau)


//cach luu ten dang nhap mat khau khi push
//luu ten dang nhap trong 5 tieng hoac toi khi tat may
git config --global credential.helper "cache --timeout=18000"

cd //chon thu muc de lam viec
git clone <link github> //tao ra 1 ban clone giong het project tren github ve may
git pull //update thay doi tu project github vao ban clone tren may

//quy trinh lam viec nhom vs git pull request
1.git checkout -b <feature_branch>
2.git push origin <branch>
3.create a pull request on github
4.review code
5.merge to master
