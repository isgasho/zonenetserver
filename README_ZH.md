# ZoneNet Server

[English](README.md)

全球局域网络. 对任何地点, 任何设备, 建立点对点和端到端加密的局域网

这是 ZoneNet Server, 这是可选的, 因为 ZoneNet 会有官方 Server. 更多信息 https://zonenet.io

### 通过 [nami](https://github.com/txthinking/nami) 安装

```
$ nami install github.com/zonenetio/zonenetserver
```

或直接下载二进制文件 [releases](https://github.com/zonenetio/zonenetserver/releases)

### 说明

- 确保你的域名已经解析到你的服务器
- TCP 端口 80/443/8443, TCP&UDP 端口 4438/30000-60000 将会被使用
- 用 root 或 sudo 运行

### 使用

```
$ zonenetserver --domain yourdomain.com
```
> 更多参数: $ zonenetserver --help

### 守护进程

你可能喜欢 [joker](https://github.com/txthinking/joker)
