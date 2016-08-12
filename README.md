# raspberry

# 解决外接硬盘一直高速转动发热问题:
使用hdparm 设置硬盘超时自动睡眠：
```java
sudo aptitude install hdparm
sudo hdparm -S120 /dev/sdc1
```
参考文档：https://www.chiphell.com/thread-914770-1-1.html

---
