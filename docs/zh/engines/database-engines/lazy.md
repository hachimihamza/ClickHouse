---
machine_translated: true
machine_translated_rev: b111334d6614a02564cf32f379679e9ff970d9b1
toc_priority: 31
toc_title: "\u61D2\u60F0"
---

# 懒惰 {#lazy}

仅将表保留在RAM中 `expiration_time_in_seconds` 上次访问后几秒钟。 只能与\*日志表一起使用。

它针对存储许多小\*日志表进行了优化，访问之间存在较长的时间间隔。

## 创建数据库 {#creating-a-database}

    CREATE DATABASE testlazy ENGINE = Lazy(expiration_time_in_seconds);

[原始文章](https://clickhouse.tech/docs/en/database_engines/lazy/) <!--hide-->
