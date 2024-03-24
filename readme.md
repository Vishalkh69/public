git tag v1.0
git tag -d v1.0
git tag v1.0 "commmit id"

git show "commit id"
git log -n 4 "commit id"

git log --author="vishal" -since="2024-02-01" --until="2024-02-06"

git lg -n 5

git cherry-pick "start id"^.."end id"
