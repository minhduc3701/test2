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
git remote add origin <link github>
git push