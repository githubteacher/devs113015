# devs113015

Command Line History for Day 1:
523  git clone https://github.com/githubteacher/devs113015.git
  524  git branch
  525  cd devs113015
  526  git branch
  527  git branch --all
  528  git branch githubteacher-hometown origin/githubteacher-hometown
  529  git branch
  530  git checkout githubteacher-hometown
  531  git remote
  532  git remote -v
  533  atom .
  534  git checkout master
  535  git checkout githubteacher-hometown
  536  git add ocala-fl.md
  537  git status
  538  git reset HEAD ocala-fl.md
  539  git status
  540  git add ocala-fl.md
  541  git status
  542  git commit
  543  git checkout master
  544  git checkout githubteacher-hometown
  545  git push
  546  git checkout master
  547  git pull
  548  git branch
  549  git branch --merged
  550  git branch -d githubteacher-hometown
  551  git branch --all
  552  git pull --prune
  553  git branch
  554  atom .
  555  git status
  556  git add -A
  557  git status
  558  atom .
  559  git status
  560  git diff
  561  git diff --staged
  562  git diff HEAD
  563  ls -la
  564  clear
  565  atom .
  566  git diff
  567  git status
  568  git diff --stat
  569  git diff ocala-fl.md
  570  git log
  571  git log --oneline
  572  git log --oneline --graph
  573  git log --oneline --graph --decorate
  574  git log --oneline --graph --decorate --all
  - 575  git log --help
  - 576  git config --global alias.lol "log --oneline --graph --decorate --all"
  - 577  git lol
  - 578  git config --global alias.lol "log --oneline --graph --decorate --all"
  - 579  history

### Command Line History for Day 2

  501  cd documents/scratch
  502  git clone https://github.com/githubteacher/github-games.git
  503  git branch --all
  504  cd github-games
  505  git branch --all
  506  atom .
  507  git checkout -b readme-updates
  508  atom .
  509  git status
  510  git add .
  511  git status
  512  git commit -m "update README to correct URL"
  513  git push -u origin readme-updates
  514  git checkout gh-pages
  515  git pull
  516  git branch --all
  517  git pull --prune
  518  git branch --merged
  519  git branch -d readme-updates
  520  git branch --all
  521  git log --oneline
  522  ls -la
  523  git revert 2710
  524  ls -la
  525  git status
  526  git log --oneline
  527  git push
  528  git log --oneline
  529  git branch --all
  530  git checkout -b stats-update origin/stats-update
  531  git checkout origin/game-instructions
  532  git checkout stats-update
  533  git diff gh-pages..stats-update
  534  git diff gh-pages..stats-update README.md
  535  git diff --color-words gh-pages..stats-update
  536  git checkout gh-pages
  537  git merge stats-update
  538  git status
  539  atom index.html
  540  git status
  541  git add index.html
  542  git commit -m "fixing conflict in score color"
  543  git branch --merged
  544  git branch -d stats-update
  545  git push
  546  git branch --all
  547  git pull --prune
  548  git checkout -b shape-colors origin/shape-colors
  549  atom .
  550  git status
  551  git commit -a -m "changing the colors of the shapes"
  552  git push
  553  git checkout gh-pages
  554  git fetch origin
  555  git checkout shape-colors
  556  git merge gh-pages
  557  atom .
  558  git status
  559  git add index.html
  560  git commit -m "fixing merge conflict in shape colors"
  561  git status
  562  git push
  563  git checkout gh-pages
  564  git pull --prune
  565  git branch --merged
  566  git branch -d shape-colors
  567  git branch --al
  568  git checkout -b slow-down
  569  atom .
  570  ls -al
  571  mkdir images
  572  git mv texture.jpg images/texture.jpg
  573  git status
  574  git add -p
  575  git status
  576  git commit -m "moving texture file to directory"
  577  git status
  578  git commit -a -m "slow down game"
  579  git commit --amend
  580  git log --oneline
  581  git push -u origin slow-down
  582  cd ..
  583  git init practice-repo
  584  cd practice-repo
  585  touch README.md
  586  git add README.md
  587  git commit -m "creating README file"
  588  git status
  589  git log --oneline
  590  touch file1.md file2.md file3.md file4.md
  591  git add file1.md
  592  git commit -m "adding file 1"
  593  git add file2.md
  594  git commit -m "adding file 2"
  595  git add file3.md
  596  git commit -m "adding file3"
  597  git add file4.md
  598  git commit -m "adding file 4"
  599  git status
  600  git log --oneline
  601  git lol
  602  git log --oneline --decorate --all
  603  git config --list
  604  clear
  605  git lol
  606  git reset --soft a233
  607  git lol
  608  git status
  609  git commit -m "adding file 3 and 4"
  610  git status
  611  ls -al
  612  git lol
  613  git reset c5a9
  614  git lol
  615  git status
  616  ls -al
  617  git commit -m "adding files 1 thru 4"
  618  git status
  619  git add .
  620  git commit -m "adding files 1 thru 4"
  621  git status
  622  git lol
  623  ls -al
  624  git lol
  625  git reset --hard HEAD~
  626  git lol
  627  git status
  628  git reflog
  629  ls -al
  630  git reflog
  631  git cherry-pick a233
  632  git reflog
  633  ls -al
  634  git cherry-pick e9b8
  635  git status
  636  git lol
  637  echo "some content" >> file2.md
  638  git status
  639  git add .
  640  git status
  641  git checkout -b rebase-me
  642  ls -al
  643  touch rebase1.md rebase2.md
  644  git add rebase1.md
  645  git commit -m "add rebase1"
  646  git add .
  647  git commit -m "add rebase2 and tagalong"
  648  git status
  649  git checkout master
  650  echo "some more content" >> file4.md
  651  git add .
  652  git commit -m "more content for file 4"
  653  git lol
  654  git checkout rebase-me
  655  git rebase -i master
  656  git lol
  657  git checkout master
  658  git merge rebase-me
  659  echo "I need more content to stash" >> file2.md
  660  git checkout rebase-me
  661  git stash
  662  git lol
  663  git stash --list
  664  git stash list
  665  git stash pop
  666  git checkout master
  667  echo "more content" >> file3.md
  668  git status
  669  git add file2.md
  670  git commit -m "adding some changes"
  671  git status
  672  git checkout -b more-changes
  673  git status
  674  git add .
  675  git commit -m "adding more changes to file 3"
  676  git lol
