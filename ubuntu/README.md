## 文件说明

* pip.conf - 参考: https://pip.pypa.io/en/stable/user_guide/#config-file

## 安装其他软件

**安装 Python 3.6**

```
sudo add-apt-repository -y ppa:deadsnakes/ppa
# 或: sudo add-apt-repository -y ppa:jonathonf/python-3.6
sudo apt-get update
sudo apt-get install -y python3.6 python3.6-venv
```

**安装 Dokcer**

最快的方法，分分钟装好最新版的 docker-ce：

```
$ curl -fsSL get.docker.com -o get-docker.sh
$ sudo sh get-docker.sh --mirror Aliyun

# 然后按照提示添加用户到 docker 组，注意：重新登录才生效
$ sudo usermod -aG docker $(whoami)
```
