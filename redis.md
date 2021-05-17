> mac下安装redis
## 查看可以安装的版本
```
brew search redis
```
### 安装redis
```
brew install redis

brew install redis@3.2
```
##  卸载 redis

```
brew uninstall redis
```
##启动
```
brew services start redis
```
## 关闭
```
brew services stop redis
```

### 重启
```
brew service restart redis
```
## 配置开机启动
```
ln -sfv /usr/local/opt/redis/*plist ~/Library/LaunchAgents
```

