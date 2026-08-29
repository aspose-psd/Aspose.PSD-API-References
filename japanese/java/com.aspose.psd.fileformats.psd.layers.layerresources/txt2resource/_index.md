---
title: "Txt2Resource"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "Txt2 リソースクラス"
type: docs
weight: 76
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layerresources/txt2resource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class Txt2Resource extends LayerResource
```

Txt2 リソースクラス
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Txt2Resource()](#Txt2Resource--) | [Txt2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/txt2resource) クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB ヘッダー バージョン |
| [PsbResourceSignature](#PsbResourceSignature) | PSB 固有のリソース署名。 |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD ヘッダー バージョン |
| [ResourceSignature](#ResourceSignature) | 共通リソース署名。 |
| [TypeToolKey](#TypeToolKey) | タイプツール情報キー。 |
| [ventureLicense_internalized](#ventureLicense-internalized) | ベンチャー ライセンス。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addTextRecord(String text, RectangleF bounds)](#addTextRecord-java.lang.String-com.aspose.psd.RectangleF-) | テキストレコードを Resource に追加し、テキストレコードの ID を返します。 |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | リソースが PSB 固有かどうかをチェックし、設定します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | データを取得または設定します。 |
| [getHeader_internalized()](#getHeader-internalized--) | ヘッダーを取得または設定します。 |
| [getKey()](#getKey--) | レイヤーリソースキーを取得します。 |
| [getKeys_internalized(System.Collections.Generic.Dictionary<String,Object> tree)](#getKeys-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--) | リソースが圧縮されているか取得します。 |
| [getLength()](#getLength--) | レイヤーリソースの長さ（バイト単位）を取得します。 |
| [getParsedTxt2Model_internalized()](#getParsedTxt2Model-internalized--) | txt2 データを Txt2DataRoot クラスのインスタンスに解析します。 |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | プレフィックスの長さを取得します。 |
| [getPsdVersion()](#getPsdVersion--) | レイヤーリソースに必要な最小の psd バージョンを取得します。 |
| [getSignature()](#getSignature--) | レイヤーリソースのシグネチャを取得します。 |
| [getTextData()](#getTextData--) | リソースデータからテキストレコードを取得します。 |
| [getText_internalized()](#getText-internalized--) | 名前を取得または設定します。 |
| [getTxt2FromParsedTree_internalized(System.Collections.Generic.Dictionary<String,Object> tree)](#getTxt2FromParsedTree-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--) | 解析されたツリーから TXT2 を取得します。 |
| [getTxt2ParsedTree_internalized()](#getTxt2ParsedTree-internalized--) | TXT2 の解析ツリーを取得します。 |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | リソースが PSB 固有かどうかを判定します。 |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | このインスタンスがリソース PSB 固有かどうかを示す値を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeTextRecord_internalized(int textIndex)](#removeTextRecord-internalized-int-) | リソースからテキストレコードを削除します。 |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 指定されたストリームコンテナを保存します。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | カスタムリソースヘッダーを保存します。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | ヘッダーのシグネチャ、識別子、長さを保存します。 |
| [setData(byte[] value)](#setData-byte---) | データを取得または設定します。 |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | ヘッダーを取得または設定します。 |
| [setText_internalized(String value)](#setText-internalized-java.lang.String-) | 名前を取得または設定します。 |
| [toString()](#toString--) | このインスタンスを表す String を返します。 |
| [updateTextData_internalized(int textIndex, String newText, double fontSize, Color color)](#updateTextData-internalized-int-java.lang.String-double-com.aspose.psd.Color-) | テキスト Index でテキストレコードを、新しいデフォルトテキストデータと新しいテキスト、フォントサイズ、カラーで更新します。 |
| [updateTxt2DataFromModel_internalized(Txt2DataRoot txt2DataRoot)](#updateTxt2DataFromModel-internalized-com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot-) | Txt2DataRoot モデルから txt2 データを更新します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Txt2Resource() {#Txt2Resource--}
```
public Txt2Resource()
```


[Txt2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources/txt2resource) クラスの新しいインスタンスを初期化します。

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


PSB ヘッダー バージョン

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


PSB 固有のリソース署名。

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


PSD ヘッダー バージョン

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


共通リソース署名。

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


タイプツール情報キー。

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


ベンチャー ライセンス。

### addTextRecord(String text, RectangleF bounds) {#addTextRecord-java.lang.String-com.aspose.psd.RectangleF-}
```
public final int addTextRecord(String text, RectangleF bounds)
```


テキストレコードを Resource に追加し、テキストレコードの ID を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | レコードテキスト。 |
| bounds | [RectangleF](../../com.aspose.psd/rectanglef) | 境界。 |

**Returns:**
int - リソースのテキストレコードの Id を返します
### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


リソースが PSB 固有かどうかをチェックし、設定します。現在、一部のリソースは認識されていませんが、保存時の動作を変更する PSB 固有リソースの完全なリストがあります。そのため、少なくとも UnknownResource でこれをチェックする必要があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | int | キーです。 |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public final byte[] getData()
```


データを取得または設定します。

値: データ。

**Returns:**
byte[]
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


ヘッダーを取得または設定します。

値: ヘッダー。

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getKey() {#getKey--}
```
public final int getKey()
```


レイヤーリソースキーを取得します。

**Returns:**
int
### getKeys_internalized(System.Collections.Generic.Dictionary<String,Object> tree) {#getKeys-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--}
```
public static ITextEngineKeys getKeys_internalized(System.Collections.Generic.Dictionary<String,Object> tree)
```


リソースが圧縮されているか取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ツリー | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.Object> | ツリーです。 |

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.ITextEngineKeys - キーを含むオブジェクトを返します。
### getLength() {#getLength--}
```
public int getLength()
```


レイヤーリソースの長さ（バイト単位）を取得します。

**Returns:**
int
### getParsedTxt2Model_internalized() {#getParsedTxt2Model-internalized--}
```
public final Txt2DataRoot getParsedTxt2Model_internalized()
```


txt2 データを Txt2DataRoot クラスのインスタンスに解析します。

**Returns:**
com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot - Txt2DataRoot クラスのインスタンスとしての txt2 データです。
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


プレフィックスの長さを取得します。8BIM リソースの場合はデフォルト値が 12、8B64 の場合は 16 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| psdVersion | int | PSD バージョン。 |

**Returns:**
int - プレフィックスの長さ。
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


レイヤーリソースに必要な最小の psd バージョンを取得します。0 は制限がないことを示します。

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


レイヤーリソースのシグネチャを取得します。

**Returns:**
int
### getTextData() {#getTextData--}
```
public final String[] getTextData()
```


リソースデータからテキストレコードを取得します。

**Returns:**
java.lang.String[] - テキストレコードの配列
### getText_internalized() {#getText-internalized--}
```
public final String getText_internalized()
```


名前を取得または設定します。

値: 名前です。

**Returns:**
java.lang.String
### getTxt2FromParsedTree_internalized(System.Collections.Generic.Dictionary<String,Object> tree) {#getTxt2FromParsedTree-internalized-com.aspose.ms.System.Collections.Generic.Dictionary-java.lang.String-java.lang.Object--}
```
public final String getTxt2FromParsedTree_internalized(System.Collections.Generic.Dictionary<String,Object> tree)
```


解析されたツリーから TXT2 を取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ツリー | com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.Object> | データツリーです。 |

**Returns:**
java.lang.String - Txt2 データです。
### getTxt2ParsedTree_internalized() {#getTxt2ParsedTree-internalized--}
```
public final System.Collections.Generic.Dictionary<String,Object> getTxt2ParsedTree_internalized()
```


TXT2 の解析ツリーを取得します。

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.Object> - 解析されたツリー
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


リソースが PSB 固有かどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| キー | int | リソースキーです。 |

**Returns:**
boolean - リソースが PSB 固有の場合は true、そうでない場合は false。
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


このインスタンスがリソース PSB 固有かどうかを示す値を取得します。

値: このインスタンスがリソース PSB 固有の場合は true、そうでない場合は false。

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




### removeTextRecord_internalized(int textIndex) {#removeTextRecord-internalized-int-}
```
public final void removeTextRecord_internalized(int textIndex)
```


リソースからテキストレコードを削除します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| textIndex | int | 削除するテキストレコードのインデックスです。 |

### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


指定されたストリームコンテナを保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | ストリームコンテナです。 |
| psdVersion | int | PSD バージョン。 |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


カスタムリソースヘッダーを保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | ストリームコンテナです。 |
| 署名 | int | シグネチャです。 |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


ヘッダーのシグネチャ、識別子、長さを保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | ストリームコンテナです。 |
| 署名 | int | シグネチャです。 |
| isLengthLong | boolean | true に設定すると、長さは長くなります。 |

### setData(byte[] value) {#setData-byte---}
```
public final void setData(byte[] value)
```


データを取得または設定します。

値: データ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


ヘッダーを取得または設定します。

値: ヘッダー。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setText_internalized(String value) {#setText-internalized-java.lang.String-}
```
public final void setText_internalized(String value)
```


名前を取得または設定します。

値: 名前です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


このインスタンスを表す String を返します。

**Returns:**
java.lang.String - このインスタンスを表す文字列です。
### updateTextData_internalized(int textIndex, String newText, double fontSize, Color color) {#updateTextData-internalized-int-java.lang.String-double-com.aspose.psd.Color-}
```
public final void updateTextData_internalized(int textIndex, String newText, double fontSize, Color color)
```


テキスト Index でテキストレコードを、新しいデフォルトテキストデータと新しいテキスト、フォントサイズ、カラーで更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| textIndex | int | txt2 リソースデータ内のテキストレコードのインデックスです。 |
| newText | java.lang.String | 新しいテキストです。 |
| fontSize | double | 新しいフォントサイズです。 |
| color | [Color](../../com.aspose.psd/color) | 新しいテキストの色です。 |

### updateTxt2DataFromModel_internalized(Txt2DataRoot txt2DataRoot) {#updateTxt2DataFromModel-internalized-com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot-}
```
public final void updateTxt2DataFromModel_internalized(Txt2DataRoot txt2DataRoot)
```


Txt2DataRoot モデルから txt2 データを更新します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| txt2DataRoot | com.aspose.internal.fileformats.psd.layers.text.txt2data.Txt2DataRoot | txt2 データモデルです。 |

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

