# docker-jenkins

默认使用的是blueocean的镜像，也可以替换成build那个镜像(jenkins/jenkins)，可以安装python环境

[jenkins使用文档](https://jenkins.io/zh/doc/book/installing/)

默认端口是2080，修改yml的映射端口即可

已经配置了加速，在nginx/conf.d里面，使用的清华源，不喜欢可以替换成其他源，改proxy_pass即可