# repository
## remote
remote add 关联本地与远程
**push** to remote
git clone 克隆到本地
## 版本回退
log, reset HEAD^, reflog
# working directory
**add** to stage
**stash** to hide temporary(list, apply, drop, pop)
**checkout -- ** to back
# stage
**commit** to repository

**reset HEAD** to back

**rm** and **commit** to delete file in repository
# branch
**checkout -b** or **switch -c** create and switch

**branch** list all and point now

**branch -d** del

**chechout** or **switch**

## merge:
**冲突** 手动修改并add

--no-ff

## fix bug for multi branches:

make sure one commit id

**git cherry-pick** do more one time

## multiplayer:
**push**

### about get:

**clone** only master default

**pull** can pull current branch(before this, use **checkout -b b-name origin/b-name** to track local and remote)

# tag
tag on a commit

**-a**:name

**-m**:description

**-d**:del locally

**push origin --tags**

**push origin :refs/tags/\<tagname>** del remotely