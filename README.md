# subject-230623

### 前提条件としてインターネット可

### スマホ不可

### イヤホン不可

<br><br>

![image](https://github.com/winofsql/subject-230623/assets/1501327/c6066125-80ff-4573-9fe2-9fef87e25eef)

プログラム作成中を Zoom で録画したデータ( mp4 / C:\Users\lightbox\Documents\Zoom )


```sql
CREATE TABLE `アニメマスタ` (
  `アニメコード` varchar(4) NOT NULL,
  `アニメ作品タイトル` varchar(50) DEFAULT NULL,
  `制作会社` varchar(4) DEFAULT NULL,
  `アニメ分類` int DEFAULT NULL,
  `放映回数` int DEFAULT NULL,
  `初回放映開始日` datetime DEFAULT NULL,
  PRIMARY KEY (`アニメコード`)
)
```

```sql
CREATE TABLE `所属マスタ` (
  `制作会社コード` varchar(4) NOT NULL,
  `制作会社名称` varchar(50) DEFAULT NULL,
  PRIMARY KEY (`制作会社コード`)
)
```

![image](https://github.com/winofsql/subject-230623/assets/1501327/ee33844e-9d19-41f3-9fbb-d43154098f91)

上記のような csv を提出
