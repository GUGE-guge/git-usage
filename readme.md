Git学习
git init
git config --global user.name "Edsion"
git config --global user.email "745180624@qq.com"
git add ./readme.md
git commit -m "这是一点说明"
(commit 环境如何退出)Esc->:q
(强制退出)Esc->:q!
(查看工作状态)git status
(将所有修改的文件放置缓存区)git add ./
(一步将所有修改的文件放置版本库中)git commit --all -m"说明"
(查看提交记录)git log
(简洁提交记录)git log --oneline