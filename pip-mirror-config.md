vi ~/.config/pip/pip.conf

这里使用了阿里云镜像，添加以下内容

```
[global]
timeout = 60
index-url = https://mirrors.aliyun.com/pypi/simple

[install]
trusted-host=mirrors.aliyun.com
```
