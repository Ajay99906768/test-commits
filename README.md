git clone https://github.com/username/test-commits.git
cd test-commits
echo "line 1" >> file.txt
git add .
git commit -m "Commit 1"

echo "line 2" >> file.txt
git add .
git commit -m "Commit 2"
