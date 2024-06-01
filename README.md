# demo_git
"Hello world"
PS D:\study_da\Home work lv3\ven_demo\venv\Git_repository> cd demo_git
PS D:\study_da\Home work lv3\ven_demo\venv\Git_repository\demo_git> ls


    Directory: D:\study_da\Home work lv3\ven_demo\venv\Git_repository\demo_git


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----          6/1/2024   8:50 PM             23 README.md


PS D:\study_da\Home work lv3\ven_demo\venv\Git_repository\demo_git> git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
PS D:\study_da\Home work lv3\ven_demo\venv\Git_repository\demo_git> git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Disable this message with "git config advice.addEmptyPathspec false"
PS D:\study_da\Home work lv3\ven_demo\venv\Git_repository\demo_git> git add .
PS D:\study_da\Home work lv3\ven_demo\venv\Git_repository\demo_git> git commit - m "this is a first commit from huongpham"
error: pathspec '-' did not match any file(s) known to git
error: pathspec 'm' did not match any file(s) known to git
error: pathspec 'this is a first commit from huongpham' did not match any file(s) known to git
PS D:\study_da\Home work lv3\ven_demo\venv\Git_repository\demo_git> git commit -m "this is a first commit from huongph"  
[main a8fb74e] this is a first commit from huongph
 1 file changed, 1 insertion(+), 1 deletion(-)
PS D:\study_da\Home work lv3\ven_demo\venv\Git_repository\demo_git> git push
info: please complete authentication in your browser...
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 286 bytes | 286.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Huongpham950/demo_git.git
   f76f304..a8fb74e  main -> main
PS D:\study_da\Home work lv3\ven_demo\venv\Git_repository\demo_git> 