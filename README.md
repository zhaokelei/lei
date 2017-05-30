脚本进度

用户、端口密码增加，修改，删除功能。（已完成）
自动添加，删除相关防火墙政策。（已完成）
流量统计，流量限制功能。（已完成）
支持开机自启（已完成）
支持SSR混淆模式（已完成）
一键搭建脚本（已完成）
简单的控制脚本（已完成）
周期性清空用户已使用流量（即将更新
注意事项

为了防止 SSR 程序被滥用来免流，已经禁止各类非正常 Host 以及 ML 有关端口，愿 SSR 能够继续担当为用户打开通往世界的大门的工具~
只支持统计 IPV4 流量
程序路径已写死，只能通过此脚本进行管理
系统支持

Ubuntu 14.04
Ubuntu 16.10
Debian 7
Debian 8
 
安装命令


wget -N --no-check-certificate https://raw.githubusercontent.com/zhaokelei/lei/master/install.sh && bash install.sh
 
 
 
卸载命令


wget -N --no-check-certificate https://raw.githubusercontent.com/zhaokelei/lei/master/uninstall.sh && bash uninstall.sh
