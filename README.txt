- buat modul
- buat modul di repository github
=================================================

local proj :

go mod init github.com/missthecode/go-say-hello

git init
git add .
git commit -m 'membuat module say hello'
git remote add origin git@github.com/missthecode/go-say-hello
git push origin master

echo "# go-say-hello" >> README.md
git init
git add .
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/missthecode/go-say-hello.git
git push -u origin master


git tag v1.0.0
git push origin v1.0.0



