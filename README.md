# PLPBasicGitAssignment
The basic workflow of creating a GitHub repository, connecting it to a local folder, and making commits and pushes.

Documentation of steps:


C:\Users\PC>cd PLPBasicGitAssignment

C:\Users\PC\PLPBasicGitAssignment>git init
Initialized empty Git repository in C:/Users/PC/PLPBasicGitAssignment/.git/

C:\Users\PC\PLPBasicGitAssignment>git remote add origin https://github.com/Mesh-code1/PLPBasicGitAssignment

C:\Users\PC\PLPBasicGitAssignment>git add hello.txt

C:\Users\PC\PLPBasicGitAssignment>git commit -m "Add hello.txt with a greeting"
[master (root-commit) 8da0d07] Add hello.txt with a greeting
 1 file changed, 1 insertion(+)
 create mode 100644 hello.txt

C:\Users\PC\PLPBasicGitAssignment>git push -u origin main