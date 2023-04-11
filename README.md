# undiasinluismi
git commit -am "commit inicial"
git push
code . 
mkdir privada
touch 1.txt
touch .gitignore
privada/
privado.txt

git tag -a v0.1 -m "Versión 0.1"
git push origin v0.1
git commit -am "segundo commit"
git push

git checkout -b v0.2
touch 2.txt
git commit -am "commit rama v0.2"
git push --all
git merge v0.2

git branch --help
git branch --merged
git branch --no-merged



git branch -d v0.2