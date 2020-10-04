# V2Ray一键脚本Ubuntu版

网上收集的一键脚本，所有权利归原作者，本人不是程序员，也不懂代码。

一键脚本：

bash <(curl -sL https://raw.githubusercontent.com/artzh0755/shared/main/v2ray.sh)


# V2ray一键脚本包括：

1.更新系统到最新版；

2.安装bbr加速模块；

3.安装v2ray并设置开机启动。



# 其它

1. 查看配置运行状态/参数：

bash <(curl -sL https://raw.githubusercontent.com/hijkpw/scripts/master/ubuntu_install_v2ray.sh) info

2. v2ray管理命令：

启动：systemctl start v2ray

停止：systemctl stop v2ray

重启：systemctl restart v2ray


3. 更改端口、alterid最简单的办法：重新运行一键脚本

4. 更新v2ray到最新版：

bash <(curl -sL https://raw.githubusercontent.com/hijkpw/scripts/master/goV2.sh)

（提示“装不上daemon”不用管，systemctl restart v2ray重新启动v2ray）

5. 卸载命令：

bash <(curl -sL https://raw.githubusercontent.com/hijkpw/scripts/master/ubuntu_install_v2ray.sh) uninstall
