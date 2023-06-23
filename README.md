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
