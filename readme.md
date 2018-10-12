
一、安装脚本
1. 确保安装了Chrome
2. 确保安装python2.X
3. 确保安装pip
4. 安装SDP工具： pip install SDPPublishTool
5. 移动执行脚本： mv  /usr/local/lib/python2.7/site-packages/SDP.*  ~/

二、发布命令：
python ~/sdp.py
（确保 podspec 文件内 s.homepage 为对应组件 gitlab 地址，且s.version为要发布的版本号）

userName : gitlab用户名（工号）
password : 工号密码
project dir ： 要发布的组件目录
code-branch(dev or test or release)：发布分支分别对应开发、测试、正式环境
publish content：发布内容（可为空）
