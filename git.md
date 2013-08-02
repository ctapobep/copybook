git rev-parse symbolic 
git cat-file -p sha1
git reflog, git log -g
 Reflog items in log format
git rev-list --objects --all 
  Shows all the objects inside of .git that are referenceable
git update-index --add file
git update-index --remove file
git update-index --really-remove file
git write-tree
echo 'hello' |git commit-tree treesha -p ParentCommitSha1
