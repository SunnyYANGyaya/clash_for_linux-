# clash_for_linux-
自用的clash_for_linux备份文件
# 参考链接
https://github.com/clash-hub/clash_for_windows_pkg/releases/tag/Latest

# 处理运行Clash
·  将下载的包提取解压，然后修改下名字，例如 Clash,然后将Clash移动到opt/下

sudo mv Clash/   /opt

· 转到新的路径下

cd  /opt/Clash

·运行Clash,打开界面（根目录下的cfw文件就是执行入口）

./cfw

界面打开后，配置Clash
主界面 Start with Linux 可以打开，即开机启动
配置机场，选择订阅Url的形式（输入url,点击Download），直接配置文件也可以(Import) 

端口配置
这一步千万别忘记了！！！
这里注意端口就是前面主界面Port项的端口，有修改要同步修改
在设置--网络里面，修改为手动
HTTP和HTTPS都修改为127.0.0.1 7890
重启clash就可以了
