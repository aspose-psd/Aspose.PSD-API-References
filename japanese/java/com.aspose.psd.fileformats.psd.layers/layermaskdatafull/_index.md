---
title: "LayerMaskDataFull"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "LayerMaskDataFull クラスを定義します。このクラスは、レイヤーがレイヤーマスクとベクトルマスクの両方を持つ場合の PSD ファイルレイヤー内のマスクデータに関する情報を含みます。"
type: docs
weight: 22
url: /ja/java/com.aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataFull extends LayerMaskData
```

LayerMaskDataFull クラスを定義します。このクラスは、レイヤーがレイヤーマスクとベクターマスクの両方を持つ場合の PSD ファイルレイヤー内のマスクデータに関する情報を含みます。そうでない場合は、[LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort) が使用されます。ImageData にはラスターマスクとラスタライズされたベクターマスクが結合されて含まれます。ImageData のバイト長は MaskRectangle.Width \\* MaskRectangle.Height プロパティと等しくなる必要があります。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [LayerMaskDataFull()](#LayerMaskDataFull--) | 新しい [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull) クラスのインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | このインスタンスをクローンします。 |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | レイヤーマスクをクローンします。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | 背景色を取得または設定します。 |
| [getBottom()](#getBottom--) | 下部レイヤーマスクの位置を取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | レイヤーマスクデータのサイズを取得します。 |
| [getDefaultColor()](#getDefaultColor--) | デフォルトカラーを取得または設定します。 |
| [getEnclosingBottom()](#getEnclosingBottom--) | PSD 画像レイヤー内の囲む下部ラスターマスク位置を取得または設定します。 |
| [getEnclosingLeft()](#getEnclosingLeft--) | PSD ファイルレイヤー内の囲む左側ラスターマスク位置を取得または設定します。 |
| [getEnclosingRight()](#getEnclosingRight--) | PSD ファイルレイヤー内の囲む右側ラスターマスク位置を取得または設定します。 |
| [getEnclosingTop()](#getEnclosingTop--) | PSD 画像レイヤー内のラスターマスクの囲む上部位置を取得または設定します。 |
| [getFlags()](#getFlags--) | レイヤーマスクフラグを取得または設定します。 |
| [getHeight_internalized()](#getHeight-internalized--) | マスクの高さを取得します。 |
| [getImageData()](#getImageData--) | PSD ファイル内のレイヤーマスク データ（ベクターマスクがある場合は結合/最終マスク）を取得または設定します。 |
| [getLeft()](#getLeft--) | 左側のレイヤーマスク位置を取得または設定します。 |
| [getMaskRectangle()](#getMaskRectangle--) | PSD ファイル内のレイヤーマスクのマスク Rectangle を取得または設定します。 |
| [getRealFlags()](#getRealFlags--) | ユーザー/ラスターマスクに使用されるレイヤーマスクフラグを取得または設定します。 |
| [getRight()](#getRight--) | 右側のレイヤーマスク位置を取得または設定します。 |
| [getTop()](#getTop--) | 上側のレイヤーマスク位置を取得または設定します。 |
| [getUserMaskData()](#getUserMaskData--) | PSD ファイル内のレイヤーのユーザー（ラスタ）マスクデータを取得または設定します。 |
| [getUserMaskRectangle()](#getUserMaskRectangle--) | PSD 画像レイヤー内のユーザーマスク（囲む）矩形を取得または設定します。 |
| [getWidth_internalized()](#getWidth-internalized--) | マスクの幅を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | 指定された StreamContainer に [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) を保存します。 |
| [setBackgroundColor(byte value)](#setBackgroundColor-byte-) | 背景色を取得または設定します。 |
| [setBottom(int value)](#setBottom-int-) | 下部レイヤーマスクの位置を取得または設定します。 |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | デフォルトカラーを取得または設定します。 |
| [setEnclosingBottom(int value)](#setEnclosingBottom-int-) | PSD 画像レイヤー内の囲む下部ラスターマスク位置を取得または設定します。 |
| [setEnclosingLeft(int value)](#setEnclosingLeft-int-) | PSD ファイルレイヤー内の囲む左側ラスターマスク位置を取得または設定します。 |
| [setEnclosingRight(int value)](#setEnclosingRight-int-) | PSD ファイルレイヤー内の囲む右側ラスターマスク位置を取得または設定します。 |
| [setEnclosingTop(int value)](#setEnclosingTop-int-) | PSD 画像レイヤー内のラスターマスクの囲む上部位置を取得または設定します。 |
| [setFlags(byte value)](#setFlags-byte-) | レイヤーマスクフラグを取得または設定します。 |
| [setImageData(byte[] value)](#setImageData-byte---) | PSD ファイル内のレイヤーマスク データ（ベクターマスクがある場合は結合/最終マスク）を取得または設定します。 |
| [setLeft(int value)](#setLeft-int-) | 左側のレイヤーマスク位置を取得または設定します。 |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | PSD ファイル内のレイヤーマスクのマスク Rectangle を取得または設定します。 |
| [setRealFlags(byte value)](#setRealFlags-byte-) | ユーザー/ラスターマスクに使用されるレイヤーマスクフラグを取得または設定します。 |
| [setRight(int value)](#setRight-int-) | 右側のレイヤーマスク位置を取得または設定します。 |
| [setTop(int value)](#setTop-int-) | 上側のレイヤーマスク位置を取得または設定します。 |
| [setUserMaskData(byte[] value)](#setUserMaskData-byte---) | PSD ファイル内のレイヤーのユーザー（ラスタ）マスクデータを取得または設定します。 |
| [setUserMaskRectangle(Rectangle value)](#setUserMaskRectangle-com.aspose.psd.Rectangle-) | PSD 画像レイヤー内のユーザーマスク（囲む）矩形を取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataFull() {#LayerMaskDataFull--}
```
public LayerMaskDataFull()
```


新しい [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull) クラスのインスタンスを初期化します。

### deepClone_internalized() {#deepClone-internalized--}
```
public LayerMaskData deepClone_internalized()
```


このインスタンスをクローンします。

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
### deepClone_internalized(LayerMaskData mask) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public static LayerMaskData deepClone_internalized(LayerMaskData mask)
```


レイヤーマスクをクローンします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | マスク。 |

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
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
### getBackgroundColor() {#getBackgroundColor--}
```
public final byte getBackgroundColor()
```


背景色を取得または設定します。

値: 背景色。

**Returns:**
byte
### getBottom() {#getBottom--}
```
public final int getBottom()
```


下部レイヤーマスクの位置を取得または設定します。

値: 下側のレイヤーマスク位置。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public final int getDataSize()
```


レイヤーマスクデータのサイズを取得します。

値: レイヤーマスク データのサイズ。

**Returns:**
int
### getDefaultColor() {#getDefaultColor--}
```
public final byte getDefaultColor()
```


デフォルトカラーを取得または設定します。

値: デフォルトの色。

**Returns:**
byte
### getEnclosingBottom() {#getEnclosingBottom--}
```
public final int getEnclosingBottom()
```


PSD 画像レイヤー内の囲む下部ラスターマスク位置を取得または設定します。

値: 下側のレイヤーマスク位置。

**Returns:**
int
### getEnclosingLeft() {#getEnclosingLeft--}
```
public final int getEnclosingLeft()
```


PSD ファイルレイヤー内の囲む左側ラスターマスク位置を取得または設定します。

値: 左側のレイヤーマスク位置。

**Returns:**
int
### getEnclosingRight() {#getEnclosingRight--}
```
public final int getEnclosingRight()
```


PSD ファイルレイヤー内の囲む右側ラスターマスク位置を取得または設定します。

値: 右側のレイヤーマスク位置。

**Returns:**
int
### getEnclosingTop() {#getEnclosingTop--}
```
public final int getEnclosingTop()
```


PSD 画像レイヤー内のラスターマスクの囲む上部位置を取得または設定します。

値: 上側のレイヤーマスク位置。

**Returns:**
int
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


レイヤーマスクフラグを取得または設定します。

値: レイヤーマスク フラグ。

**Returns:**
byte
### getHeight_internalized() {#getHeight-internalized--}
```
public final int getHeight_internalized()
```


マスクの高さを取得します。

値: 高さ。

**Returns:**
int
### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


PSD ファイル内のレイヤーマスク データ（ベクターマスクがある場合は結合/最終マスク）を取得または設定します。

値: 画像データ。

**Returns:**
byte[]
### getLeft() {#getLeft--}
```
public final int getLeft()
```


左側のレイヤーマスク位置を取得または設定します。

値: 左側のレイヤーマスク位置。

**Returns:**
int
### getMaskRectangle() {#getMaskRectangle--}
```
public final Rectangle getMaskRectangle()
```


PSD ファイル内のレイヤーマスクのマスク Rectangle を取得または設定します。left、right、top、bottom プロパティを受け取り、Rectangle を作成します。

値: マスク矩形。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getRealFlags() {#getRealFlags--}
```
public final byte getRealFlags()
```


ユーザー/ラスターマスクに使用されるレイヤーマスクフラグを取得または設定します。ベクターマスクの場合は Flags プロパティが使用されます。

値: 実際のレイヤーマスクフラグ。

**Returns:**
byte
### getRight() {#getRight--}
```
public final int getRight()
```


右側のレイヤーマスク位置を取得または設定します。

値: 右側のレイヤーマスク位置。

**Returns:**
int
### getTop() {#getTop--}
```
public final int getTop()
```


上側のレイヤーマスク位置を取得または設定します。

値: 上側のレイヤーマスク位置。

**Returns:**
int
### getUserMaskData() {#getUserMaskData--}
```
public final byte[] getUserMaskData()
```


PSD ファイル内のレイヤーのユーザー（ラスタ）マスクデータを取得または設定します。（MaskData プロパティにラスタライズされたベクターマスクがあります）。

値: PSD 画像内のレイヤー画像データ。

**Returns:**
byte[]
### getUserMaskRectangle() {#getUserMaskRectangle--}
```
public final Rectangle getUserMaskRectangle()
```


PSD 画像レイヤー内のユーザーマスク（囲む）矩形を取得または設定します。

値: ユーザーマスク矩形。

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getWidth_internalized() {#getWidth-internalized--}
```
public final int getWidth_internalized()
```


マスクの幅を取得します。

値: 幅。

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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
public void save_internalized(StreamContainer streamContainer)
```


指定された StreamContainer に [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) を保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | データを保存するストリーム コンテナです。 |

### setBackgroundColor(byte value) {#setBackgroundColor-byte-}
```
public final void setBackgroundColor(byte value)
```


背景色を取得または設定します。

値: 背景色。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte |  |

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


下部レイヤーマスクの位置を取得または設定します。

値: 下側のレイヤーマスク位置。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setDefaultColor(byte value) {#setDefaultColor-byte-}
```
public final void setDefaultColor(byte value)
```


デフォルトカラーを取得または設定します。

値: デフォルトの色。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte |  |

### setEnclosingBottom(int value) {#setEnclosingBottom-int-}
```
public final void setEnclosingBottom(int value)
```


PSD 画像レイヤー内の囲む下部ラスターマスク位置を取得または設定します。

値: 下側のレイヤーマスク位置。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setEnclosingLeft(int value) {#setEnclosingLeft-int-}
```
public final void setEnclosingLeft(int value)
```


PSD ファイルレイヤー内の囲む左側ラスターマスク位置を取得または設定します。

値: 左側のレイヤーマスク位置。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setEnclosingRight(int value) {#setEnclosingRight-int-}
```
public final void setEnclosingRight(int value)
```


PSD ファイルレイヤー内の囲む右側ラスターマスク位置を取得または設定します。

値: 右側のレイヤーマスク位置。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setEnclosingTop(int value) {#setEnclosingTop-int-}
```
public final void setEnclosingTop(int value)
```


PSD 画像レイヤー内のラスターマスクの囲む上部位置を取得または設定します。

値: 上側のレイヤーマスク位置。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


レイヤーマスクフラグを取得または設定します。

値: レイヤーマスク フラグ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```


PSD ファイル内のレイヤーマスク データ（ベクターマスクがある場合は結合/最終マスク）を取得または設定します。

値: 画像データ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


左側のレイヤーマスク位置を取得または設定します。

値: 左側のレイヤーマスク位置。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setMaskRectangle(Rectangle value) {#setMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setMaskRectangle(Rectangle value)
```


PSD ファイル内のレイヤーマスクのマスク Rectangle を取得または設定します。left、right、top、bottom プロパティを受け取り、Rectangle を作成します。

値: マスク矩形。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setRealFlags(byte value) {#setRealFlags-byte-}
```
public final void setRealFlags(byte value)
```


ユーザー/ラスターマスクに使用されるレイヤーマスクフラグを取得または設定します。ベクターマスクの場合は Flags プロパティが使用されます。

値: 実際のレイヤーマスクフラグ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


右側のレイヤーマスク位置を取得または設定します。

値: 右側のレイヤーマスク位置。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


上側のレイヤーマスク位置を取得または設定します。

値: 上側のレイヤーマスク位置。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setUserMaskData(byte[] value) {#setUserMaskData-byte---}
```
public final void setUserMaskData(byte[] value)
```


PSD ファイル内のレイヤーのユーザー（ラスタ）マスクデータを取得または設定します。（MaskData プロパティにラスタライズされたベクターマスクがあります）。

値: PSD 画像内のレイヤー画像データ。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte[] |  |

### setUserMaskRectangle(Rectangle value) {#setUserMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setUserMaskRectangle(Rectangle value)
```


PSD 画像レイヤー内のユーザーマスク（囲む）矩形を取得または設定します。

値: ユーザーマスク矩形。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

