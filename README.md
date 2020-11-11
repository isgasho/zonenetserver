# ZoneNet Server

[中文](README_ZH.md)

Global Area Networking. Peer-to-Peer & End-to-End Encryption for every device, anywhere

This is ZoneNet Server, this is optional, because zonenet has official servers. more https://zonenet.io

### Install via [nami](https://github.com/txthinking/nami)

```
$ nami install github.com/zonenetio/zonenetserver
```

or download binary from [releases](https://github.com/zonenetio/zonenetserver/releases)

### Requirements

- Make sure your domain name has been successfully resolved
- TCP ports 80/443/8443, TCP&UDP ports 4438/30000-60000 will be used
- Run command with root or sudo 

### Usage

```
$ zonenetserver --domain yourdomain.com
```
> more parameters: $ zonenetserver --help

### Daemon

You may like [joker](https://github.com/txthinking/joker)
