# index.html


Main Branch: update_upgrade_config_cr with one PR 1
Another small Branch: updating_MUO_doc with another PR 2

Task: Now if you want to merge the changes from PR 2 to PR 1 

(base) ~git checkout update_upgrade_config_cr
Switched to branch 'update_upgrade_config_cr'
Your branch is up to date with 'origin/update_upgrade_config_cr'.

(base) ~git rebase updating_MUO_doc
First, rewinding head to replay your work on top of it...

(base) ~git commit --amend --no-edit
[update_upgrade_config_cr 05532d1] Updated the design doc and crds by removing the unused objects - OSD-4780
 Date: Thu Aug 20 10:25:43 2020 +0530
 3 files changed, 8 deletions(-)

(base) ~git push origin update_upgrade_config_cr
Enumerating objects: 15, done.
Counting objects: 100% (15/15), done.
Delta compression using up to 12 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 703 bytes | 703.00 KiB/s, done.
Total 8 (delta 7), reused 0 (delta 0)
remote: Resolving deltas: 100% (7/7), completed with 7 local objects.
To https://github.com/himanshudogra/managed-upgrade-operator.git
   872cb56..05532d1  update_upgrade_config_cr -> update_upgrade_config_cr
