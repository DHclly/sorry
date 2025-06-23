# sorry-v1.0.tar.gz

基于项目源文件直接打包的镜像，有bug，但是底包已经安装好了。

# sorry-v2.0.tar.gz

基于 1.0 优化调整后的版本，没有重头打包。

操作命令：

```
# 导入镜像
tar -xzvf sorry-v2.0.tar.gz
docker load -i sorry-v2.0.tar

# 直接运行
docker run -d -p 4567:4567 --name sorry01 dhclly/sorry:v2.0
```