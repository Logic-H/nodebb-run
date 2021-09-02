# nodebb-run
# Now we support English 
此脚本用于自动化安装nodebb程序
仅适用于ubuntu



原项目由我和gaein共同维护，适用于centos&ubuntu （centos停止支持，已放弃）
nodebb经不断迭代，旧版脚本年久失修已不再能正常运行，现全面升级至全新环境下
编写旧版脚本时本人还在初中，英语翻译还有些许不通顺 现一并改进（狗头

支持ubuntu16.04，18.04，20.04 LTS，默认安装nodebb 1.17.x （最近发布了1.18版本 如有需要请手动升级

不推荐用本脚本安装mongoDB 需要手动配置
redis支持一条龙安装

# 注意
 
- nginx配置文件在/etc/nginx下 nginx.conf按照官方文档配置 如有需要自行修改
- 如需公网访问example.com:4567，请手动开端口

# 食用方法

Ubuntu使用代码：

```
wget https://github.com/nidbCN/nodeBBrun/blob/Ubuntu/run-latest.sh && chmod u+x run-latest.sh && ./run-latest.sh
```
# 当前功能（Ubuntu）

- 根据用户输入选择下载源（大陆为阿里、中科大镜像）未测试 建议默认
- 根据用户输入选择数据库（Redis/MongoDB）
- 根据用户输入为数据库进行安全设置（仅限Redis）
- 自动判断系统版本添加合适的源（MongoDB，nginx）
- 自动判断是否存在必须软件，没有则自动安装（编译安装过的软件无法实现）
- 高亮信息提示

# 最后
本人Linux菜鸟，如果有错误或者改正建议还请指正

# Buy me a coffee

![4DA6A5B9A3155EFB943023FB082E56AF](https://user-images.githubusercontent.com/42613665/131843816-3b2016ad-a15f-49c8-a3f1-995527f962a7.jpg)







