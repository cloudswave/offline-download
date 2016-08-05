# offline-download
docker版离线下载服务器
- 免配置，一行代码即可安装完成。
- 使用Aria2+Yaaw作为离线工具，支持BT、U链、HTTP、百度云下载。
- 使用KODExplorer作为桌面工具，提供WebOS级别的文件管理体验

### 安装
```
sudo docker run -d -p 80:80 -p 6800:6800 -v /tmp/modata/comic:/var/www/html/comic index.tenxcloud.com/ethanzhu/offline-download
```
###Dockerfile
```
FROM easychen/modo.moe
```
### docker加速器
```
curl https://coding.net/u/ethanzhu/p/shell/git/raw/master/docker-new-setmirror.sh | sh
```
