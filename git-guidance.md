# generate ssh key
ssh-keygen

# clone project
git clone git@git.augmentum.com.cn:eriksson.luo/exam.git

# set user name
git config --global user.name 'Kevin Sun'

# set user email
git config --global user.email 'kevinsun@augmentum.com.cn'

# set file mode
git config --global core.filemode false

# set content editor
git config --global core.editor vim

# set diff tool
git config --global merge.tool vimdiff

# set ui color
git config --global color.ui auto

# create or delete branch
git branch kevin.sun

# check repository status
git status

# add modified/untracked file[s]
git add -u/-A

# commit changes
git commit -m "comment..."

# push new commits to remote
git push origin kevin.sun

# check out code from remote 
git pull -r

