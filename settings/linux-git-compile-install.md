## linux下编译安装git

---

```
tar -zxf git-2.17.0.tar.gz
cd git-2.17.0
make prefix=/usr/local all
sudo make prefix=/usr/local install
```

最终是安装到了目录：/usr/local/bin/