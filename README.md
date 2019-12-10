# ubuntu_qq

## 1. Docker

本脚本依赖Docker，需要提前安装好Docker环境。参考<https://yeasy.gitbooks.io/docker_practice/install/ubuntu.html>安装




## 2. 使用

```sh
#Install qq
bash <(curl -L -s https://raw.githubusercontent.com/ygcaicn/ubuntu_qq/master/qq.sh)

qq -h
  -h, --help            Show help
  -i, --install         Install this script to system
  -f, --force           Force install or reinstall
  -c, --clean           Clean all qq container
      --start           Start qq
      --update          Update script
      --remove          Remove this script
      --instance        Create a instance qq container, you can create more than one using this option

#Install wechat
bash <(curl -L -s https://raw.githubusercontent.com/ygcaicn/ubuntu_qq/master/wechat.sh)
wechat -h
  -h, --help            Show help
  -i, --install         Install this script to system
  -f, --force           Force install or reinstall
  -c, --clean           Clean all wechat container
      --start           Start wechat
      --update          Update script
      --remove          Remove this script
      --instance        Create a instance wechat container, you can create more than one using this option
```

## 感谢

<https://github.com/bestwu/docker-qq>