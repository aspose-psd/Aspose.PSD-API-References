---
title: "LiFeDataSource"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "外部リンクファイルに関する情報を含む LnkeDataSource クラスを定義します。"
type: docs
weight: 11
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource/
---

**Inheritance:**
java.lang.Object、[com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource)
```
public class LiFeDataSource extends LinkDataSource
```

外部リンクファイルに関する情報を含む LnkeDataSource クラスを定義します。これは Adobe® Photoshop® ファイルの変更を支援する PSD ファイル形式操作 API の一部です。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [LiFeDataSource()](#LiFeDataSource--) | [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) クラスの新しいインスタンスを初期化します。 |
| [LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)](#LiFeDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-) | [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [DescriptorVersion_internalized](#DescriptorVersion-internalized) | 記述子のバージョン。 |
| [LatestVersion_internalized](#LatestVersion-internalized) | リンクデータソースの利用可能な最新バージョン |
| [UnexpectedLinkDataSourceTypeValue_internalized](#UnexpectedLinkDataSourceTypeValue-internalized) | 予期しないリンクデータソースのタイプ値 |
| [ZeroChar_internalized](#ZeroChar-internalized) | ゼロ文字 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator)](#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeStockId()](#getAdobeStockId--) | Adobe® Photoshop® CC ライブラリ用のグラフィックライブラリ AdobeStockId を取得または設定します。 |
| [getAdobeStockLicenseState()](#getAdobeStockLicenseState--) | 利用可能な場合、Adobe® Photoshop® CC ライブラリ用の Adobe Stock ライセンスの状態を取得します。 |
| [getAssetLockedState()](#getAssetLockedState--) | PSD アセットがロックされているかどうかを示す値を取得または設定します。 |
| [getAssetModTime()](#getAssetModTime--) | Adobe® Photoshop® \\u0421\\u0421 ライブラリ資産用のアセットの変更時刻を取得または設定します。 |
| [getChildDocId()](#getChildDocId--) | Lnk2 / LnkE Adobe® Photoshop® リソースの liFE または liFD データ ソースにおける子ドキュメント識別子を取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | リソース クラス ID を取得または設定します。 |
| [getClassName_internalized()](#getClassName-internalized--) | リソース クラス名を取得または設定します。 |
| [getCompId()](#getCompId--) | 子ドキュメント用に現在選択されているコンプの ID を取得または設定します。選択されていない場合は -1 になります。 |
| [getCompInfoKeyName()](#getCompInfoKeyName--) |  |
| [getContentID_internalized()](#getContentID-internalized--) | ContentID プロパティを取得または設定します。 |
| [getDataLength_Property_internalized()](#getDataLength-Property-internalized--) | 追加データの長さを取得します。 |
| [getDataLength_internalized()](#getDataLength-internalized--) | リンク ソース データの長さを取得します。 |
| [getDate()](#getDate--) | PSD LnkE リソースの LiFE データ ソースにある外部ファイルの最終書き込み日時を取得または設定します。 |
| [getDate_internalized()](#getDate-internalized--) |  |
| [getElementName()](#getElementName--) | Adobe® Photoshop® CC ライブラリ用のグラフィックス ライブラリ要素名を取得または設定します。 |
| [getElementRef()](#getElementRef--) | Adobe® Photoshop® CC ライブラリ用のグラフィックス ライブラリ要素参照を取得または設定します。 |
| [getFileCreator()](#getFileCreator--) | PSD 形式の LnkE / Lnk2 リソースにおけるファイル作成者を取得または設定します。 |
| [getFileName()](#getFileName--) | PSD リンク リソース内の外部または埋め込みファイルの名前を取得または設定します。 |
| [getFileSize()](#getFileSize--) | PSD LnkE リソースの LiFE データ ソースにある外部ファイルのサイズを取得または設定します。 |
| [getFileType()](#getFileType--) | Adobe® Photoshop® Lnk2 / LnkE リソースが含むまたはリンクする埋め込みまたは外部ファイルのタイプを取得または設定します。 |
| [getFullPath()](#getFullPath--) | PSD LnkE リソースの LiFE データ ソースにある外部ファイルのフルパスを取得または設定します。 |
| [getItems_internalized()](#getItems-internalized--) | リソース プロパティを定義する OSTypeStructure 配列を取得または設定します。 |
| [getLength()](#getLength--) | リンク データ ソースの長さ（バイト単位）を取得します。 |
| [getOriginalCompId()](#getOriginalCompId--) | 子ドキュメント用に現在選択されているコンプの元の ID を取得します。選択されていない場合は -1 になります。 |
| [getOriginalFileName()](#getOriginalFileName--) | Adobe® Photoshop® グローバルリンク リソース内のデータ ソースの元のファイル名を取得します。 |
| [getRelativePath()](#getRelativePath--) | PSD LnkE リソースの LiFE データ ソースにある外部ファイルの相対パスを取得または設定します。 |
| [getType()](#getType--) | Adobe® Photoshop® グローバルリンク データ ソースのタイプを取得します。以下のいずれか、またはなしになる可能性があります: PSD Lnk2Resource に対応する埋め込みリンクファイル liFD、PSD LnkeResource に対応する外部リンクファイル liFE、リンクファイルエイリアス liFA |
| [getUniqueId()](#getUniqueId--) | PSD リンク リソース内のデータ ソースのグローバル一意識別子を取得します。 |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getUnknownBytes_internalized()](#getUnknownBytes-internalized--) | Items OSTypeStructures プロパティの前にある不明データを取得または設定します。 |
| [getVersion()](#getVersion--) | PSD LnkE / Lnk2 リソース内のデータ ソースのバージョンを取得します。 |
| [hasFileOpenDescriptor()](#hasFileOpenDescriptor--) | このリンク データ ソースがファイルオープン ディスクリプタ（CompId と OriginalCompId）を持つかどうかを示す値を取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [isLibraryLink()](#isLibraryLink--) | この PSD リンク データ ソースが Adobe® Photoshop® \u0421\u0421 ライブラリ アイテムにリンクしているかどうかを示す値を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | リンク データ ソース ブロック データを保存します。 |
| [setAdobeStockId(String value)](#setAdobeStockId-java.lang.String-) | Adobe® Photoshop® CC ライブラリ用のグラフィックライブラリ AdobeStockId を取得または設定します。 |
| [setAssetLockedState(boolean value)](#setAssetLockedState-boolean-) | PSD アセットがロックされているかどうかを示す値を取得または設定します。 |
| [setAssetModTime(double value)](#setAssetModTime-double-) | Adobe® Photoshop® \\u0421\\u0421 ライブラリ資産用のアセットの変更時刻を取得または設定します。 |
| [setChildDocId(String value)](#setChildDocId-java.lang.String-) | Lnk2 / LnkE Adobe® Photoshop® リソースの liFE または liFD データ ソースにおける子ドキュメント識別子を取得または設定します。 |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | リソース クラス ID を取得または設定します。 |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | リソース クラス名を取得または設定します。 |
| [setCompId(int value)](#setCompId-int-) | 子ドキュメント用に現在選択されているコンプの ID を取得または設定します。選択されていない場合は -1 になります。 |
| [setContentID_internalized(String value)](#setContentID-internalized-java.lang.String-) | ContentID プロパティを取得または設定します。 |
| [setDate(Date value)](#setDate-java.util.Date-) | PSD LnkE リソースの LiFE データ ソースにある外部ファイルの最終書き込み日時を取得または設定します。 |
| [setDate_internalized(System.DateTime value)](#setDate-internalized-com.aspose.ms.System.DateTime-) |  |
| [setElementName(String value)](#setElementName-java.lang.String-) | Adobe® Photoshop® CC ライブラリ用のグラフィックス ライブラリ要素名を取得または設定します。 |
| [setElementRef(String value)](#setElementRef-java.lang.String-) | Adobe® Photoshop® CC ライブラリ用のグラフィックス ライブラリ要素参照を取得または設定します。 |
| [setFileCreator(String value)](#setFileCreator-java.lang.String-) | PSD 形式の LnkE / Lnk2 リソースにおけるファイル作成者を取得または設定します。 |
| [setFileName(String value)](#setFileName-java.lang.String-) | PSD リンク リソース内の外部または埋め込みファイルの名前を取得または設定します。 |
| [setFileOpenDescriptor(boolean value)](#setFileOpenDescriptor-boolean-) | このリンク データ ソースがファイルオープン ディスクリプタ（CompId と OriginalCompId）を持つかどうかを示す値を取得または設定します。 |
| [setFileSize(long value)](#setFileSize-long-) | PSD LnkE リソースの LiFE データ ソースにある外部ファイルのサイズを取得または設定します。 |
| [setFileType(String value)](#setFileType-java.lang.String-) | Adobe® Photoshop® Lnk2 / LnkE リソースが含むまたはリンクする埋め込みまたは外部ファイルのタイプを取得または設定します。 |
| [setFullPath(String value)](#setFullPath-java.lang.String-) | PSD LnkE リソースの LiFE データ ソースにある外部ファイルのフルパスを取得または設定します。 |
| [setItems_internalized(OSTypeStructure[] value)](#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | リソース プロパティを定義する OSTypeStructure 配列を取得または設定します。 |
| [setLibraryLink(boolean value)](#setLibraryLink-boolean-) | この PSD リンク データ ソースが Adobe® Photoshop® \u0421\u0421 ライブラリ アイテムにリンクしているかどうかを示す値を取得します。 |
| [setOriginalCompId(int value)](#setOriginalCompId-int-) | 子ドキュメント用に現在選択されているコンプの元の ID を取得します。選択されていない場合は -1 になります。 |
| [setOriginalFileName(String value)](#setOriginalFileName-java.lang.String-) | Adobe® Photoshop® グローバルリンク リソース内のデータ ソースの元のファイル名を取得します。 |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | 型構造でプロパティ値を設定します。 |
| [setRelativePath(String value)](#setRelativePath-java.lang.String-) | PSD LnkE リソースの LiFE データ ソースにある外部ファイルの相対パスを取得または設定します。 |
| [setUniqueId(UUID uuid)](#setUniqueId-java.util.UUID-) | PSD リンク リソース内のデータ ソースのグローバル一意識別子を取得します。 |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setUnknownBytes_internalized(byte[] value)](#setUnknownBytes-internalized-byte---) | Items OSTypeStructures プロパティの前にある不明データを取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LiFeDataSource() {#LiFeDataSource--}
```
public LiFeDataSource()
```


[LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) クラスの新しいインスタンスを初期化します。

### LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator) {#LiFeDataSource-int-java.util.UUID-java.lang.String-java.lang.String-java.lang.String-}
```
public LiFeDataSource(int version, UUID uniqueId, String originalFileName, String fileType, String fileCreator)
```


[LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource) クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| version | int | バージョン。 |
| uniqueId | java.util.UUID | 一意の識別子です。 |
| originalFileName | java.lang.String | 元のファイルの名前。 |
| fileType | java.lang.String | ファイルのタイプ。 |
| fileCreator | java.lang.String | ファイルの作成者。 |

### DescriptorVersion_internalized {#DescriptorVersion-internalized}
```
public static final int DescriptorVersion_internalized
```


記述子のバージョン。

### LatestVersion_internalized {#LatestVersion-internalized}
```
public static final int LatestVersion_internalized
```


リンクデータソースの利用可能な最新バージョン

### UnexpectedLinkDataSourceTypeValue_internalized {#UnexpectedLinkDataSourceTypeValue-internalized}
```
public static final String UnexpectedLinkDataSourceTypeValue_internalized
```


予期しないリンクデータソースのタイプ値

### ZeroChar_internalized {#ZeroChar-internalized}
```
public static final char ZeroChar_internalized
```


ゼロ文字

### create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator) {#create-internalized-int-com.aspose.ms.System.Guid-java.lang.String-java.lang.String-java.lang.String-}
```
public static LiFeDataSource create_internalized(int version, System.Guid uniqueId, String originalFileName, String fileType, String fileCreator)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| version | int |  |
| uniqueId | com.aspose.ms.System.Guid |  |
| originalFileName | java.lang.String |  |
| fileType | java.lang.String |  |
| fileCreator | java.lang.String |  |

**Returns:**
[LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAdobeStockId() {#getAdobeStockId--}
```
public final String getAdobeStockId()
```


Adobe® Photoshop® CC ライブラリ用のグラフィックライブラリ AdobeStockId を取得または設定します。

**Returns:**
java.lang.String
### getAdobeStockLicenseState() {#getAdobeStockLicenseState--}
```
public final String getAdobeStockLicenseState()
```


利用可能な場合、Adobe® Photoshop® CC ライブラリ用の Adobe Stock ライセンスの状態を取得します。

値: Adobe Stock ライセンスの状態、または利用できない場合は空文字列。

**Returns:**
java.lang.String
### getAssetLockedState() {#getAssetLockedState--}
```
public final boolean getAssetLockedState()
```


PSD アセットがロックされているかどうかを示す値を取得または設定します。Adobe® Photoshop® \u0421\u0421 ライブラリ資産のロック状態です。

**Returns:**
boolean
### getAssetModTime() {#getAssetModTime--}
```
public final double getAssetModTime()
```


Adobe® Photoshop® \\u0421\\u0421 ライブラリ資産用のアセットの変更時刻を取得または設定します。

**Returns:**
double
### getChildDocId() {#getChildDocId--}
```
public final String getChildDocId()
```


Lnk2 / LnkE Adobe® Photoshop® リソースの liFE または liFD データ ソースにおける子ドキュメント識別子を取得または設定します。

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


リソース クラス ID を取得または設定します。

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


リソース クラス名を取得または設定します。

**Returns:**
java.lang.String
### getCompId() {#getCompId--}
```
public final int getCompId()
```


子ドキュメントの現在選択されているコンプの ID を取得または設定します。選択されていない場合は -1 になります。コンプはデザイナーが作成できるページレイアウトの構成です。レイヤーコンプを使用すると、単一の Adobe® Photoshop® ファイル内でレイアウトの複数バージョンを作成、管理、表示できます。レイヤーコンプはレイヤーパネルの状態のスナップショットです。レイヤーコンプは 3 種類のレイヤーオプションを保存しますが、このプロパティはスマートオブジェクト用のレイヤーコンプ選択識別子を取得します。スマートオブジェクトのレイヤーコンプ

**Returns:**
int
### getCompInfoKeyName() {#getCompInfoKeyName--}
```
public static String getCompInfoKeyName()
```




**Returns:**
java.lang.String
### getContentID_internalized() {#getContentID-internalized--}
```
public final String getContentID_internalized()
```


ContentID プロパティを取得または設定します。このプロパティの値は Version が 8 以上の場合にのみ読み取りおよび保存されます。

**Returns:**
java.lang.String
### getDataLength_Property_internalized() {#getDataLength-Property-internalized--}
```
public int getDataLength_Property_internalized()
```


追加データの長さを取得します。

値: データの長さ。

**Returns:**
int
### getDataLength_internalized() {#getDataLength-internalized--}
```
public final long getDataLength_internalized()
```


リンク ソース データの長さを取得します。

**Returns:**
long - ソースデータの長さ。
### getDate() {#getDate--}
```
public final Date getDate()
```


PSD LnkE リソースの LiFE データ ソースにある外部ファイルの最終書き込み日時を取得または設定します。

**Returns:**
java.util.Date
### getDate_internalized() {#getDate-internalized--}
```
public final System.DateTime getDate_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getElementName() {#getElementName--}
```
public final String getElementName()
```


Adobe® Photoshop® CC ライブラリ用のグラフィックス ライブラリ要素名を取得または設定します。

**Returns:**
java.lang.String
### getElementRef() {#getElementRef--}
```
public final String getElementRef()
```


Adobe® Photoshop® CC ライブラリ用のグラフィックス ライブラリ要素参照を取得または設定します。

**Returns:**
java.lang.String
### getFileCreator() {#getFileCreator--}
```
public final String getFileCreator()
```


PSD 形式の LnkE / Lnk2 リソースにおけるファイル作成者を取得または設定します。

**Returns:**
java.lang.String
### getFileName() {#getFileName--}
```
public final String getFileName()
```


PSD リンク リソース内の外部または埋め込みファイルの名前を取得または設定します。

値: 外部または埋め込みファイルの名前。

**Returns:**
java.lang.String
### getFileSize() {#getFileSize--}
```
public final long getFileSize()
```


PSD LnkE リソースの LiFE データ ソースにある外部ファイルのサイズを取得または設定します。

**Returns:**
long
### getFileType() {#getFileType--}
```
public final String getFileType()
```


Adobe® Photoshop® Lnk2 / LnkE リソースが含むまたはリンクする埋め込みまたは外部ファイルのタイプを取得または設定します。

**Returns:**
java.lang.String
### getFullPath() {#getFullPath--}
```
public final String getFullPath()
```


PSD LnkE リソースの LiFE データ ソースにある外部ファイルのフルパスを取得または設定します。

**Returns:**
java.lang.String
### getItems_internalized() {#getItems-internalized--}
```
public final OSTypeStructure[] getItems_internalized()
```


リソース プロパティを定義する OSTypeStructure 配列を取得または設定します。

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLength() {#getLength--}
```
public final long getLength()
```


リンク データ ソースの長さ（バイト単位）を取得します。

**Returns:**
long
### getOriginalCompId() {#getOriginalCompId--}
```
public final int getOriginalCompId()
```


子ドキュメントの現在選択されているコンプの元の ID を取得します。選択されていない場合は -1 になります。このプロパティはスマートオブジェクト用の元のレイヤーコンプ選択識別子を取得します。スマートオブジェクトのレイヤーコンプ

**Returns:**
int
### getOriginalFileName() {#getOriginalFileName--}
```
public final String getOriginalFileName()
```


Adobe® Photoshop® グローバルリンク リソース内のデータ ソースの元のファイル名を取得します。

**Returns:**
java.lang.String
### getRelativePath() {#getRelativePath--}
```
public final String getRelativePath()
```


PSD LnkE リソースの LiFE データ ソースにある外部ファイルの相対パスを取得または設定します。

**Returns:**
java.lang.String
### getType() {#getType--}
```
public final int getType()
```


Adobe® Photoshop® グローバルリンク データ ソースのタイプを取得します。以下のいずれか、またはなしになる可能性があります: PSD Lnk2Resource に対応する埋め込みリンクファイル liFD、PSD LnkeResource に対応する外部リンクファイル liFE、リンクファイルエイリアス liFA

値: PSD リンク データ ソースのタイプ。

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public final UUID getUniqueId()
```


PSD リンク リソース内のデータ ソースのグローバル一意識別子を取得します。

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public final System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getUnknownBytes_internalized() {#getUnknownBytes-internalized--}
```
public final byte[] getUnknownBytes_internalized()
```


Items OSTypeStructures プロパティの前にある不明データを取得または設定します。

**Returns:**
byte[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


PSD LnkE / Lnk2 リソース内のデータ ソースのバージョンを取得します。

**Returns:**
int
### hasFileOpenDescriptor() {#hasFileOpenDescriptor--}
```
public final boolean hasFileOpenDescriptor()
```


このリンク データ ソースがファイルオープン ディスクリプタ（CompId と OriginalCompId）を持つかどうかを示す値を取得または設定します。

値: このインスタンスにファイルオープン ディスクリプタがある場合は true、そうでない場合は false。

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isLibraryLink() {#isLibraryLink--}
```
public final boolean isLibraryLink()
```


この PSD リンク データ ソースが Adobe® Photoshop® \u0421\u0421 ライブラリ アイテムにリンクしているかどうかを示す値を取得します。

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public final void save_internalized(StreamContainer streamContainer)
```


リンク データ ソース ブロック データを保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 保存先のストリームコンテナです。 |

### setAdobeStockId(String value) {#setAdobeStockId-java.lang.String-}
```
public final void setAdobeStockId(String value)
```


Adobe® Photoshop® CC ライブラリ用のグラフィックライブラリ AdobeStockId を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setAssetLockedState(boolean value) {#setAssetLockedState-boolean-}
```
public final void setAssetLockedState(boolean value)
```


PSD アセットがロックされているかどうかを示す値を取得または設定します。Adobe® Photoshop® \u0421\u0421 ライブラリ資産のロック状態です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setAssetModTime(double value) {#setAssetModTime-double-}
```
public final void setAssetModTime(double value)
```


Adobe® Photoshop® \\u0421\\u0421 ライブラリ資産用のアセットの変更時刻を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### setChildDocId(String value) {#setChildDocId-java.lang.String-}
```
public final void setChildDocId(String value)
```


Lnk2 / LnkE Adobe® Photoshop® リソースの liFE または liFD データ ソースにおける子ドキュメント識別子を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


リソース クラス ID を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


リソース クラス名を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setCompId(int value) {#setCompId-int-}
```
public final void setCompId(int value)
```


子ドキュメントの現在選択されているコンプの ID を取得または設定します。選択されていない場合は -1 になります。コンプはデザイナーが作成できるページレイアウトの構成です。レイヤーコンプを使用すると、単一の Adobe® Photoshop® ファイル内でレイアウトの複数バージョンを作成、管理、表示できます。レイヤーコンプはレイヤーパネルの状態のスナップショットです。レイヤーコンプは 3 種類のレイヤーオプションを保存しますが、このプロパティはスマートオブジェクト用のレイヤーコンプ選択識別子を取得します。スマートオブジェクトのレイヤーコンプ

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setContentID_internalized(String value) {#setContentID-internalized-java.lang.String-}
```
public final void setContentID_internalized(String value)
```


ContentID プロパティを取得または設定します。このプロパティの値は Version が 8 以上の場合にのみ読み取りおよび保存されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setDate(Date value) {#setDate-java.util.Date-}
```
public final void setDate(Date value)
```


PSD LnkE リソースの LiFE データ ソースにある外部ファイルの最終書き込み日時を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.Date |  |

### setDate_internalized(System.DateTime value) {#setDate-internalized-com.aspose.ms.System.DateTime-}
```
public final void setDate_internalized(System.DateTime value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | com.aspose.ms.System.DateTime |  |

### setElementName(String value) {#setElementName-java.lang.String-}
```
public final void setElementName(String value)
```


Adobe® Photoshop® CC ライブラリ用のグラフィックス ライブラリ要素名を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setElementRef(String value) {#setElementRef-java.lang.String-}
```
public final void setElementRef(String value)
```


Adobe® Photoshop® CC ライブラリ用のグラフィックス ライブラリ要素参照を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setFileCreator(String value) {#setFileCreator-java.lang.String-}
```
public final void setFileCreator(String value)
```


PSD 形式の LnkE / Lnk2 リソースにおけるファイル作成者を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public final void setFileName(String value)
```


PSD リンク リソース内の外部または埋め込みファイルの名前を取得または設定します。

値: 外部または埋め込みファイルの名前。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setFileOpenDescriptor(boolean value) {#setFileOpenDescriptor-boolean-}
```
public final void setFileOpenDescriptor(boolean value)
```


このリンク データ ソースがファイルオープン ディスクリプタ（CompId と OriginalCompId）を持つかどうかを示す値を取得または設定します。

値: このインスタンスにファイルオープン ディスクリプタがある場合は true、そうでない場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setFileSize(long value) {#setFileSize-long-}
```
public final void setFileSize(long value)
```


PSD LnkE リソースの LiFE データ ソースにある外部ファイルのサイズを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### setFileType(String value) {#setFileType-java.lang.String-}
```
public final void setFileType(String value)
```


Adobe® Photoshop® Lnk2 / LnkE リソースが含むまたはリンクする埋め込みまたは外部ファイルのタイプを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setFullPath(String value) {#setFullPath-java.lang.String-}
```
public final void setFullPath(String value)
```


PSD LnkE リソースの LiFE データ ソースにある外部ファイルのフルパスを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setItems_internalized(OSTypeStructure[] value) {#setItems-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems_internalized(OSTypeStructure[] value)
```


リソース プロパティを定義する OSTypeStructure 配列を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLibraryLink(boolean value) {#setLibraryLink-boolean-}
```
public final void setLibraryLink(boolean value)
```


この PSD リンク データ ソースが Adobe® Photoshop® \u0421\u0421 ライブラリ アイテムにリンクしているかどうかを示す値を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setOriginalCompId(int value) {#setOriginalCompId-int-}
```
public final void setOriginalCompId(int value)
```


子ドキュメントの現在選択されているコンプの元の ID を取得します。選択されていない場合は -1 になります。このプロパティはスマートオブジェクト用の元のレイヤーコンプ選択識別子を取得します。スマートオブジェクトのレイヤーコンプ

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setOriginalFileName(String value) {#setOriginalFileName-java.lang.String-}
```
public final void setOriginalFileName(String value)
```


Adobe® Photoshop® グローバルリンク リソース内のデータ ソースの元のファイル名を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


型構造でプロパティ値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | 構造体。 |

### setRelativePath(String value) {#setRelativePath-java.lang.String-}
```
public final void setRelativePath(String value)
```


PSD LnkE リソースの LiFE データ ソースにある外部ファイルの相対パスを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setUniqueId(UUID uuid) {#setUniqueId-java.util.UUID-}
```
public final void setUniqueId(UUID uuid)
```


PSD リンク リソース内のデータ ソースのグローバル一意識別子を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| uuid | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public final void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | com.aspose.ms.System.Guid |  |

### setUnknownBytes_internalized(byte[] value) {#setUnknownBytes-internalized-byte---}
```
public final void setUnknownBytes_internalized(byte[] value)
```


Items OSTypeStructures プロパティの前にある不明データを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

