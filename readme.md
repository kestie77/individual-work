Last login: Tue Jun 12 11:48:49 on ttys000
Jessicas-MacBook-Air:~ jmcmahon$ git init
Initialized empty Git repository in /Users/jmcmahon/.git/
Jessicas-MacBook-Air:~ jmcmahon$ git init demo
Reinitialized existing Git repository in /Users/jmcmahon/demo/.git/
Jessicas-MacBook-Air:~ jmcmahon$ cd
Jessicas-MacBook-Air:~ jmcmahon$ cd demo
Jessicas-MacBook-Air:demo jmcmahon$ git add readme.md
fatal: pathspec 'readme.md' did not match any files
Jessicas-MacBook-Air:demo jmcmahon$ touch readme.md
Jessicas-MacBook-Air:demo jmcmahon$ add readme.md
-bash: add: command not found
Jessicas-MacBook-Air:demo jmcmahon$ git add readme.md
Jessicas-MacBook-Air:demo jmcmahon$ git reset readme.md
Jessicas-MacBook-Air:demo jmcmahon$ git add readme.md
Jessicas-MacBook-Air:demo jmcmahon$ git commit -m'commit empty readme'
[master (root-commit) 6bff685] commit empty readme
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 readme.md
Jessicas-MacBook-Air:demo jmcmahon$ 


