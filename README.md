# code-
first git prgm

 1) prg
mkdir ---
ls
cd ---
git init
git config --list
git config --global user.name "Ansariamaan786"
git config --global user.email "amankingamanking89729@gmail.com"
git clone https://github.com/Ansariamaan786/3VC24CS400.git
cd 3VC--
git status
echo "hello git and git Hub" >> lab1.txt
ls
git add lab1.txt
git status
git commit -m "first msg"
git push origin main

2)prg
vi one.c
git add one.c
git commit -m "create one.c"
git add two.c
git commit -m "create two.c"
vi two.c
ls
git add two.c
git commit -m "create two.c"
git log
git status
git branch b1
git branch b2
git branch
git checkout b1
git status
echo " in branch b1 hello world " >> lab3.c
echo " in branch b1 branching world " >> lab4.c
git add lab3.c
git add lab4.c
git commit -m " lab3 for b1"
git checkout b2
git branch
echo " in branch b2 hello world" >> lab5.c
echo " in branch b2 branching world" >> lab6.c
git add lab5.c
git add lab6.c
git commit -m " lab5 and lab 6 in branch b2"
echo " in branch b2 hello world" >> lab5.c
echo " in branch b2 branching world" >> lab6.c
git add lab5.c
git add lab6.c
git commit -m " lab5 and lab 6 in branch b2"
git checkout master
git diff main..b1
git checkout main
git diff main..b1
git merge b1
git branch –merged
git branch -d b1
git branch -d b2
git status
git merge b2
git branch –- merged
git branch –-merged
git branch -d b2

3)prg

vi index.txt
git add .
git commit -m "create indes file"
git branch feature
git checkout feature
vi feature.txt
git add . 
git commit -m "work in progress"
git add .
git commit -m "work in progress"
git index.txt
git checkout main
git stash
git stash list
git checkout main
git checkout feature
git stash pop
git stash list
git add .
git commit -m "create indes file changed in feature"

4) prg
Add file → create new file
commit changes →commit changes
go to git bash
Git  clone https://github.com/lingarajpower/3VC15CS065.git

5)prg
 Step 1:
//vi index.txt
//git add .
//$ git commit -m "create indes file"
//git pull https://github.com/lingarajpower/3VC15CS065
//ls
setting-developer setting-personal access tokens-personal access token(classic)-genetrate new token
:  name →mytoken
Expiration → customize to 6 months
Select all box and submit
Copy token in 
Step 4: go to git bash paste 
//git  remote set-url origin https://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@github.com/lingarajpower/3VC15CS065
//git push

6)prg
//vi pgm6.c
#include<stdio.h>
void main()
{
    printf("inside master branch");
}
//Git add pgm6.c
//Git commit –m “program 6”
//Git branch feature-branch
//Git checkout feature-branch
//Vi pgm6b.c
//Git add pgm6b.c
//Git commit –m “pgm 6b feature branch”
//git checkout master
//git merge --no-ff feature-branch -m "Your custom merge commit message"

7)prg
git tag v1.0
git tag
git tag -a v1.1 -m "tag for release ver 1.1"
git tag
git show v1.0

8)prg
git checkout master
$ echo "I am in 8a" >> lab8a.txt
git add .
$ git commit -m " I am in 8a branch master "
$ git log
$ git show f7b46493e18b1dd58703830637ae9d3e615adbde

9)prg
git checkout master
$ echo "I am in 9a" >> lab9a.txt
git add .
$ git commit -m " I am in 9a branch master "
$ git branch cherry
$ git log
git checkout cheery
$ echo "I am in 9b" >> lab9b.txt
git add .
$ git commit -m " I am in 9b branch cheery "
$ echo "I am in 9c" >> lab9c.txt
git add .
$ git commit -m " I am in 9c branch cheery "
git checkout master
$ git log
$ git cherry-pick f7b46493e18b1dd58703830637ae9d3e615adbde
$ git log
git tag -a v1.1 -m "tag for release ver 1.1"
git tag
git shoe v1.0
git push origin v1.0

10)prg
echo "I am in 10a" >> lab10a.txt
git add .
$ git commit -m " I am in 10a "
$ echo "I am in 10b" >> lab10b.txt
git add .
$ git commit -m " I am in 10b "
$ echo "I am in 10c" >> lab10c.txt
git add .
$ git commit -m " I am in 10c " $ git log --author="lingarajpower" --since="2024-01-01" --until="2024-02-07"

11)prg
echo "I am in 11a" >> lab11a.txt
$ echo " I am in 11b " >> lab11b.txt
$ echo " I am in 11c " >> lab11c.txt
$ echo " I am in 11d " >> lab11d.txt
$ echo " I am in 11e " >> lab11e.txt
git add .
$ git commit -m "create indes file"
$ git log –n 5

12)prg
git checkout master
$ vi 12a.txt
git add .
$ git commit -m " I am in 12a branch master "
$ vi 12b.txt
git add .
$ git commit -m " I am in 12b branch master "
$ vi 12a.txt
git add .
$ git commit -m " I am in 12a branch master changes 1"
$ vi 12b.txt
git add .
$ git commit -m " I am in 12b branch master changes 1 "
$ git log --oneline
git revert ec9d05e
