# docker-cn大陆服务器安装docker的脚本+自己改的脚本
【阿里云一键安装脚本】curl -sSL http://acs-public-mirror.oss-cn-hangzhou.aliyuncs.com/docker-engine/internet | sh -

【DaoCloud 的安装脚本】curl -sSL https://get.daocloud.io/docker | sh

# 自己改的脚本，安装
（需要安装docker的服务器使用后面的命令安装,预计需要10分钟）  curl https://install.1panel.live/docker-install -o docker-install && sudo bash ./docker-install && rm -f ./docker-install
#  或者使用2命令
curl https://install.1panel.live/docker2-install -o docker2-install && sudo bash ./docker2-install && rm -f ./docker2-install
#  提示
只是把下载源改成了阿里地址：https://mirrors.aliyun.com/docker-ce （只测试过debian和Ubuntu系统，其他系统可能装不上）（原来是中科大，不可用了，改成阿里了
