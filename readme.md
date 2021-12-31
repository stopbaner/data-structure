### mysql笔记

---

1. binlog文件以二进制格式保存所有的修改操作
- binlog有三种格式：
  –基于SQL语句的复制(statement-based replication,SBR)，
  –基于行的复制(row-based replication,RBR)，
  –混合模式复制(mixed-based replication,MBR)。