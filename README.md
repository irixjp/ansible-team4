Ansible Team 4 Repository.

How to Add/Change

$ git add . # 新規ファイル作成時のみ実行
$ git commit -am "added"
[master (root-commit) 9b83d71] added
 Committer: Hirofumi Kojima <hkojima@fedora.redhat.kk>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)
 create mode 100644 README.md
$ git push
Username for 'https://github.com': h-kojima
Password for 'https://h-kojima@github.com': 
Counting objects: 3, done.
Writing objects: 100% (3/3), 240 bytes | 240.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/irixjp/ansible-team4
 * [new branch]      master -> master
$ 
