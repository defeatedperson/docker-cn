# docker-cn大陆服务器安装docker的脚本+自己改的脚本
【阿里云一键安装脚本】curl -sSL http://acs-public-mirror.oss-cn-hangzhou.aliyuncs.com/docker-engine/internet | sh -

【DaoCloud 的安装脚本】curl -sSL https://get.daocloud.io/docker | sh

# 自己改的脚本
使用方法：（将”docker-install“文件放入web服务器当中，绑定一个域名）
#  安装
（需要安装docker的服务器使用后面的命令安装）  curl https://绑定的域名/docker-install -o docker-install && sudo bash ./docker-install && rm -f ./docker-install
#  提示
如果web服务器没有ssl，那么只需要把https改成http即可。“绑定域名”记得替换！。自己改的脚本，只是把下载源改成了中科大镜像地址：http://mirrors.ustc.edu.cn/  （只测试过debian和Ubuntu系统，其他系统可能装不上）
