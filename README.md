# subject-230623

```sql
CREATE TABLE `アニメマスタ` (
  `アニメコード` varchar(4) NOT NULL,
  `アニメ名` varchar(50) DEFAULT NULL,
  `参照` varchar(4) DEFAULT NULL,
  `アニメ区分` int DEFAULT NULL,
  `数値` int DEFAULT NULL,
  `日付` datetime DEFAULT NULL,
  PRIMARY KEY (`アニメコード`)
)
```

```sql
CREATE TABLE `所属マスタ` (
  `所属コード` varchar(4) NOT NULL,
  `所属名称` varchar(50) DEFAULT NULL,
  PRIMARY KEY (`所属コード`)
)
```

![image](https://github.com/winofsql/subject-230623/assets/1501327/ee33844e-9d19-41f3-9fbb-d43154098f91)
