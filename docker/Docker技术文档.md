# Docker技术文档

## 常用指令

```sh
# 显示当前容器的在线流式资源信息
docker stats --no-stream

# 设置当前容器的CPU共享核数 --cpu-shares
docker run -d --name c768 --cpuset-cpus 0 --cpu-shares 768 benhall/stress
```

