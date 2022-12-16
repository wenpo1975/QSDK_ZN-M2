## ZN-M2 openwrt云编译

复制 `.config` 文件

```bash
make menuconfig
```

选择需要的插件，然后

```bash
./scripts/diffconfig.sh > diff.config
```

拿到配置文件，云编译
