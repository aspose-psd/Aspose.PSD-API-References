---
title: "InfxResource"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "クラス InfxResource."
type: docs
weight: 39
url: /ja/java/com.aspose.psd.fileformats.psd.layers.layerresources/infxresource/
---

**Inheritance:**
java.lang.Object、[com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)、[com.aspose.psd.fileformats.psd.layers.layerresources.BooleanResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/booleanresource)
```
public class InfxResource extends BooleanResource
```

クラス InfxResource。このリソースはクリップされた要素のブレンドに関する情報を含みます。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [InfxResource(boolean blendInteriorElements)](#InfxResource-boolean-) | 新しい [InfxResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/infxresource) クラスのインスタンスを初期化します。 |
| [InfxResource()](#InfxResource--) | 新しい [InfxResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/infxresource) クラスのインスタンスを初期化します。 |
| [InfxResource(byte[] data)](#InfxResource-byte---) | 新しい [InfxResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/infxresource) クラスのインスタンスを初期化します。 |
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
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | リソースが PSB 固有かどうかをチェックし、設定します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendInteriorElements()](#getBlendInteriorElements--) | [blend interior elements] かどうかを示す値を取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | ヘッダーを取得または設定します。 |
| [getKey()](#getKey--) | レイヤーリソースキーを取得します。 |
| [getLength()](#getLength--) | レイヤーリソースの長さ（バイト単位）を取得します。 |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | プレフィックスの長さを取得します。 |
| [getPsdVersion()](#getPsdVersion--) | レイヤーリソースに必要な最小の psd バージョンを取得します。 |
| [getSignature()](#getSignature--) | レイヤーリソースのシグネチャを取得します。 |
| [getValue()](#getValue--) | 値 [BooleanResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/booleanresource) が true か false かを示す値を取得または設定します |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | リソースが PSB 固有かどうかを判定します。 |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | このインスタンスがリソース PSB 固有かどうかを示す値を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | 指定されたストリームコンテナを保存します。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | カスタムリソースヘッダーを保存します。 |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | ヘッダーのシグネチャ、識別子、長さを保存します。 |
| [setBlendInteriorElements(boolean value)](#setBlendInteriorElements-boolean-) | [blend interior elements] かどうかを示す値を取得または設定します。 |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | ヘッダーを取得または設定します。 |
| [setValue(boolean value)](#setValue-boolean-) | 値 [BooleanResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/booleanresource) が true か false かを示す値を取得または設定します |
| [toString()](#toString--) | このインスタンスを表す String を返します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### InfxResource(boolean blendInteriorElements) {#InfxResource-boolean-}
```
public InfxResource(boolean blendInteriorElements)
```


新しい [InfxResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/infxresource) クラスのインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| blendInteriorElements | boolean | true に設定された場合、[blend interior elements]。 |

### InfxResource() {#InfxResource--}
```
public InfxResource()
```


新しい [InfxResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/infxresource) クラスのインスタンスを初期化します。

### InfxResource(byte[] data) {#InfxResource-byte---}
```
public InfxResource(byte[] data)
```


新しい [InfxResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/infxresource) クラスのインスタンスを初期化します。カスタムまたは不明な値を使用します

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| データ | byte[] | リソース データ。 |

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
### getBlendInteriorElements() {#getBlendInteriorElements--}
```
public final boolean getBlendInteriorElements()
```


[blend interior elements] かどうかを示す値を取得または設定します。

値: [blend interior elements] の場合は true、そうでない場合は false。

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getLength() {#getLength--}
```
public int getLength()
```


レイヤーリソースの長さ（バイト単位）を取得します。

**Returns:**
int
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
### getValue() {#getValue--}
```
public final boolean getValue()
```


値 [BooleanResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/booleanresource) が true か false かを示す値を取得または設定します

値: 値が true の場合は true、そうでない場合は false。

**Returns:**
boolean
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

### setBlendInteriorElements(boolean value) {#setBlendInteriorElements-boolean-}
```
public final void setBlendInteriorElements(boolean value)
```


[blend interior elements] かどうかを示す値を取得または設定します。

値: [blend interior elements] の場合は true、そうでない場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

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

### setValue(boolean value) {#setValue-boolean-}
```
public final void setValue(boolean value)
```


値 [BooleanResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/booleanresource) が true か false かを示す値を取得または設定します

値: 値が true の場合は true、そうでない場合は false。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### toString() {#toString--}
```
public String toString()
```


このインスタンスを表す String を返します。

**Returns:**
java.lang.String - このインスタンスを表す文字列です。
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

