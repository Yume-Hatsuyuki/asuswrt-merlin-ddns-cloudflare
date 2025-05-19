完全的支持ipv6和ipv4的更新。

参考了代码 <https://github.com/alphabt/asuswrt-merlin-ddns-cloudflare/blob/master/ddns-start> 并进行一些增强型修改。

主要修改部分：
添加了更加丰富的日志显示。以及更多的容错处理。
去除了对于 Python 的依赖，即使未安装任何额外插件也能正常的使用。

使用方式：将脚本下载到 /jffs/script 目录后编辑配置。
         chmod +x ddns-start
         bash ddns-start
