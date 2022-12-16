# Github
upload code to github

git-init - Create an empty Git repository or reinitialize an existing one

cd /path/to/your/existing/code 
git init
git init <project directory>

Cloning an existing repository: git clone
git clone <repo url>

Saving changes to the repository: git add and git commit
cd /path/to/project 
echo "test content for git tutorial" >> CommitTest.txt 
git add CommitTest.txt 
git commit -m "added CommitTest.txt to the repo"

Configuration & set up: git config
git remote add <remote_name> <remote_repo_url>
git push -u <remote_name> <local_branch_name>

git config --global user.name <name>
git config --local user.email <email>
git config --global alias.<alias-name> <git-command>
git config --global alias.ci commit
git config --system core.editor <editor>
git config --global --edit
