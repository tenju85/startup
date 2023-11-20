# startup
ここから始めましょう。
なかなかうまくいかないね！

いろんなことがあって…
2023年 11月20日 月曜日 19時49分26秒 JST

$ git push origin main
Username for 'https://github.com': tenju85@gmail.com
Password for 'https://tenju85@gmail.com@github.com':
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/tenju85/startup.git/'
128<honda@venus114>~/work/git/tenju85/startup on main

$ git remote set-url origin https://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@github.com/tenju85/startup.git
0<honda@venus114>~/work/git/tenju85/startup on main

$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 320 bytes | 320.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/tenju85/startup.git
   dbbc11b..9377d0c  main -> main
0<honda@venus114>~/work/git/tenju85/startup on main
$ emacs README.md
0<honda@venus114>~/work/git/tenju85/startup on main
$ git push --set-upstream origin main
branch 'main' set up to track 'origin/main'.
Everything up-to-date
0<honda@venus114>~/work/git/tenju85/startup on main
$ git commit -a -m "2nd commit ...."
[main 7877c80] 2nd commit ....
 Committer: 本田実 <honda@venus114.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 4 insertions(+)

0<honda@venus114>~/work/git/tenju85/startup on main
$ git push --set-upstream origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 396 bytes | 396.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/tenju85/startup.git
   9377d0c..7877c80  main -> main
branch 'main' set up to track 'origin/main'.

0<honda@venus114>~/work/git/tenju85/startup on main


