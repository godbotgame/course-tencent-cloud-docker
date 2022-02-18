### 项目介绍

为酷瓜云课堂（腾讯云版） [course-tencent-cloud](https://gitee.com/koogua/course-tencent-cloud) 提供环境支持

### 安装指南

下载安装脚本

```
cd ~ && curl http://download.koogua.com/ctc/install.sh -o install.sh
```

增加执行权限

```
chmod +x install.sh
```

根据实际情况修改配置

```
nano install.sh
```

执行安装，快慢取决于网络，当有错误或者超时请再次重试安装

```
bash install.sh
```

### 访问网站

* 管理账号：10000@163.com / 123456
* 前台地址：http://{your-domain}.com
* 后台地址：http://{your-domain}.com/admin

后续设置： [系统设置](https://koogua.com/page/wiki)

   
### 测试数据

管理账号：100015@163.com / 123456

### 结束安装

安装完成，请删除安装脚本

```
rm install.sh
```