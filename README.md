# SSD 自用

## Basic Project - 基础项目

[shadowsocks-android](https://github.com/shadowsocks/shadowsocks-android)

ShadowsocksD会跟随Shadowsocks更新代码。
```
  *  ShadowsocksD中的广告收入依然归Shadowsocks项目作者所有，ShadowsocksD不会分取此收入
```

## Shared Wiki - 共享Wiki

[ShadowsocksD项目共享Wiki](https://github.com/TheCGDF/SSD-Windows/wiki)

## 编译方法

```
git clone https://github.com/Sorata/SSD.git
cd SSD/
git add .
git commit -m commit
git submodule update --init --recursive
Android Studio编译
```

## Environment - 环境

Android 5.0+


## Development - 开发

\[Windows/Linux/MacOS\]

需使用`git clone --recurse-submodules <repo>`或 `git submodule update --init --recursive`进行初始化

## Open Source References - 开源引用
```
shadowsocks-android (GPLv3) https://github.com/shadowsocks/shadowsocks-android
redsocks (APL 2.0)          https://github.com/shadowsocks/redsocks
mbed TLS (APL 2.0)          https://github.com/ARMmbed/mbedtls
libevent (BSD)              https://github.com/shadowsocks/libevent
tun2socks (BSD)             https://github.com/shadowsocks/badvpn
pcre (BSD)                  https://android.googlesource.com/platform/external/pcre/+/master/dist2
libancillary (BSD)          https://github.com/shadowsocks/libancillary
shadowsocks-libev (GPLv3)   https://github.com/shadowsocks/shadowsocks-libev
libev (GPLv2)               https://github.com/shadowsocks/libev
libsodium (ISC)             https://github.com/jedisct1/libsodium
```
