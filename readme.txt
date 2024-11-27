
ashok@Animo MINGW64 /d/demoproject
$ git init
Initialized empty Git repository in D:/demoproject/.git/

ashok@Animo MINGW64 /d/demoproject (master)
$ git add README.md
fatal: pathspec 'README.md' did not match any files

ashok@Animo MINGW64 /d/demoproject (master)
$ git add readme.txt

ashok@Animo MINGW64 /d/demoproject (master)
$ git commit -m "first commit"
[master (root-commit) f8708e9] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 readme.txt

ashok@Animo MINGW64 /d/demoproject (master)
$ git branch -M master

ashok@Animo MINGW64 /d/demoproject (master)
$ git remote add origin https://github.com/ashoksethy/Demo-Project.git

ashok@Animo MINGW64 /d/demoproject (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/ashoksethy/Demo-Project.git'

ashok@Animo MINGW64 /d/demoproject (master)
$ git push origin master
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 225 bytes | 225.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/ashoksethy/Demo-Project.git
 * [new branch]      master -> master

ashok@Animo MINGW64 /d/demoproject (master)
$ git push origin master
Everything up-to-date

ashok@Animo MINGW64 /d/demoproject (master)
$


once above steps done do bellow
    : do changes on code and left go to 3rd opetion
    : add that file and write a message
    : press commit and push
    : it ll update on live server
    : 
