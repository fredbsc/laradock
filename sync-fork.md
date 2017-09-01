### Keeping the fork in sync with laradock

$git remote -v

$git remote add upstream https://github.com/laradock/laradock.git

$git remote -v

$git fetch upstream

$git merge upstream/master

$git push origin/master
