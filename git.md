git status

git merge
ssh develop@123.56.107.8
git checkout d

fab deploy_dev:web
evelop
redis-server

./localserver.sh web 5001

./localserver.sh api 5000

ps -ef | grep redis

service mongod restart

python manager.py db downgrade

python manager.py db upgrade

git status

git branch 
sudo pip install -r requirements.txt

fab deploy_dev:web
git reset --hard
git pull
<img class="gei_height_for_head_pic" src="{{ static_file('img/web/live/head.png') }}" />



git checkout master
git pull origin master

git flow hotfix start test
 
git checkout develop
git pull origin develop

git checkout hotfix/test
git flow finish -n test


git add .
git commit -m  ‘test'

git flow hotfix finish -n test

git push origin develop
git checkout master

git push origin master


1、创建分支
```
git branch <分支名>
```
2、切换分支
```
git checkout <分支名>
```
     该语句和上一个语句可以和起来用一个语句表示：git checkout -b <分支名>
3、分支合并
     比如，如果要将开发中的分支（develop），合并到稳定分支（master），
```
git checkout master
```
然后执行合并操作：
```
git merge develop
```
     如果有冲突，会提示你，调用git status查看冲突文件。
     解决冲突，然后调用git add或git rm将解决后的文件暂存。
     所有冲突解决后，git commit 提交更改。
4、分支衍合
     分支衍合和分支合并的差别在于，分支衍合不会保留合并的日志，不留痕迹，而 分支合并则会保留合并的日志。
     要将开发中的分支（develop），衍合到稳定分支（master）。
     首先切换的master分支：
```
git checkout master
```
     然后执行衍和操作：
```
git rebase develop
```
     如果有冲突，会提示你，调用git status查看冲突文件。
     解决冲突，然后调用git add或git rm将解决后的文件暂存。
     所有冲突解决后，git rebase --continue 提交更改。
5、删除分支
```
git branch -d <分支名>
```
     如果该分支没有合并到主分支会报错，可以用以下命令强制删除git branch -D <分支名>
