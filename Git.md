init 初始化一个git仓库  
add 将文件送入暂存区  
commit -m "修改记录" 将文件提交到仓库  
status 查看仓库现状  
log 显示最近到最远的提交日志:  
        --pertty=oneline单行显示  
reset 将工作区文件回退到各个版本:  
        前一个版本 git reset --hard HEAD^  
        前前一个版本 git reset --hard HEAD^^  
        前第一百个版本 git reset --hard HEAD~100  
        指定commit id的版本 git reset --hard commit_id  
reflog 查看命令历史  
checkout:  
        -- targetFileName 将工作区文件回退到版本库版本  
rm 在版本库将文件删除  