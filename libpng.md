# libpng

- [官网](http://www.libpng.org/pub/png/libpng.html)
- [文档](http://www.libpng.org/pub/png/libpng.html)

## 1.6 下载解压

```bash
curl -O https://download.sourceforge.net/libpng/lpng1647.zip
7z x lpng1647.zip
```

## 编译

- 去 zlib 的 build 目录将 zconf.h 复制到 zlib 根目录
- 使用 cmake-gui 打开 libpng 根目录
- 设置 ZLIB

- 使用 CMakeLists.txt 直接编译即可
