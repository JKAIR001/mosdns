# mosdns
## 简介

在`Linux`上运行`mosdns`所需的配置文件及所有数据文件。

## 说明

+ 路径：`/etc/mosdns/`
+ `GEOIP`、`GEOSITE`相关数据文件每日从上游拉取，自动更新，详见`Actions`
+ 更新脚本配合linux计划任务实现配置更新：`/etc/mosdns/mosdns.sh`
+ 项目不包括`mosdns`程序本身

---
