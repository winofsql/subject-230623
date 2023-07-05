# subject-230623

### ✅ 前提条件としてインターネット可
### ✅ 各自手順書を作成して、当日インターネット経由で参照してかまいません

<hr>

## ⛔ 試験当日、試験に関する質問(内容・手順)は受け付けない。当日までに自分で準備する事

### ⛔ Zoomアカウントが無い場合は参加不可


### ⛔ スマホ不可

### ⛔ イヤホン不可

### ⛔ 不正は即退場

<hr>

### 🔴 [cs-form-mtn-012-vs2022](https://github.com/winofsql/cs-form-mtn-012-vs2022) と [cs-form-mtn-011-vs2022](https://github.com/winofsql/cs-form-mtn-011-vs2022) は必ず当日ダウンロードする事(当日マーキングします)

### 🔴 Visual Studio 2022 で .sln を開いたらすぐに、入れ子の設定をすること(WEB)

<hr>

### 🔴 まず最初に自分のアカウントで Zoom にログインして、録画を開始する( 以下の作業は全て録画する事 )

### 🔴 こちらの指定した画像をデスクトップに設定する
"G:\共有ドライブ\SE-WORK-DOWNLOAD\_windows-software\DESKTOP-WALLPAPER-settings.vbs"
### 🔴 デスクトップのアイコンを非表示にする
同上
### 🔴 タスクバーを常に表示する設定で行う
同上
### 🔴 Visual Sttudio 2022 のウインドウの大きさをこちらの指定通りにする(プログラムを用意しています)
"G:\共有ドライブ\SE-WORK-DOWNLOAD\_windows-software\WINDOW-SIZE-settings.vbs" <br> 
( window-size-Visual-Studio-2022.bat )

[cs-form-mtn-012-vs2022](https://github.com/winofsql/cs-form-mtn-012-vs2022) と [cs-form-mtn-011-vs2022](https://github.com/winofsql/cs-form-mtn-011-vs2022) で作成可能
<br><br>

### 🔵 プロジェクト名は pg学籍番号 > namespace がその名前になります

### 提出物

🔴 Visual Studio 2022 で開く事が可能な以下のファイルを zip 圧縮して、**a学籍番号.zip** で提出
![image](https://github.com/winofsql/subject-230623/assets/1501327/c6066125-80ff-4573-9fe2-9fef87e25eef)

🔴 プログラム作成中を Zoom で録画したデータ( mp4 / C:\Users\lightbox\Documents\Zoom ) を **b学籍番号.mp4** で提出

🔴 使用したテーブルの Create 文二つと参照データの CSV ファイルを圧縮して、**c学籍番号.zip** で提出
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
CREATE TABLE `制作会社マスタ` (
  `制作会社コード` varchar(4) NOT NULL,
  `制作会社名称` varchar(50) DEFAULT NULL,
  PRIMARY KEY (`制作会社コード`)
)
```

```csv
0001,アクタス
0002,バンダイ
0003,スタジオジブリ
```


