# Git Tutorial
-----------------------
## install
`$sudo apt-get install git`

## configure
`$git config --global user.name "Xieyingying"`
`$git config --global user.email "xyynku@163.com"`

## initialize a directory as a repository
`$git init`

## add files to git repository
`$git add <file>`
`$git commit -m "..."`


## generate ssh key
`$ssh-keygen -t rsa -C "xyynku@163.com"`

## add ssh key to GitHub


## associate with a remote Github repository
`git remote add origin git@github.com:seawood/repo-name.git`

## first push
`$git push -u origin master  `

## second and afterwords push
`$git push origin master`

## clone remote repository
`$git clone git://g.csail.mit.edu/6.824-golabs-2018  //use ssh`
`$git clone https://github.com/michaelliao/gitskills.git  //use https`

## show git status
`$git status`

## show difference
`$git diff`

## show commit log 
`$git log`
`$git log --pretty=oneline`
`$git reflog`

# branch
`$git checkout -b dev`
`$git checkout master`
`$git branch`
`$git merge dev`
`$git branch -d dev`
