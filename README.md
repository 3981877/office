
# 免费获取Office软件
1.office 软件部署工具：https://www.microsoft.com/en-us/download/details.aspx?id=49117


2.office 版本自定义工具：https://config.office.com/deploymentsettings

3.基于KMS的 GVLK：https://learn.microsoft.com/zh-cn/deployoffice/vlactivation/gvlks

4.通过官方下载安装批量授权版：

下载命令：
```
setup /download config.xml
 ```

安装命令:
```
setup /configure config.xml
```
激活命令（以管理员身份打开命令提示符）
```
cd\
cd C:\Program Files\Microsoft Office\Office16
cscript ospp.vbs /sethst:kms.03k.org
cscript ospp.vbs /act
```
