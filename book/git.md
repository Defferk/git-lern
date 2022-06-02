* git init //start
* git status --short [git s] //for show file list
* git add file.name/. //add file/all for traking git
* git rm --cached file.name //remov track file
* git commit -m 'commit text' //create commit
* git log [git l/g] //show commit
* git merge name //add name to now br
* git push //push to github
* git pull //scan git
- git fetch //uppdate github


{branch}
* git branch [git br] //add �����
* git branch -D(delet) name //delet
* git checkout name [git co] //switched br 
	git checkout -b name //add branch


[alias]
s = status --short
st = status
ad = add .
l = log --oneline --graph --decorate --all
g = log --graph --abbrev-commit --decorate --all --format=format:'%C(bold blue)%h%C(reset) - %C(bold cyan)%aD%C(dim white) - %an%C(reset) %C(bold green)(%ar)%C(reset)%C(bold yellow)%d%C(reset)%n %C(white)%s%C(reset)'
br = branch
co = checkout
com = commit -m