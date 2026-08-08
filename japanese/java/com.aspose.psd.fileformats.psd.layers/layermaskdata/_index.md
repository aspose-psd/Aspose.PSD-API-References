---
title: "LayerMaskData"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "PSD ファイル内のレイヤーマスクデータに関する情報を含む基本 LayerMaskData クラスを定義します。"
type: docs
weight: 21
url: /ja/java/com.aspose.psd.fileformats.psd.layers/layermaskdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public abstract class LayerMaskData implements Cloneable
```

PSD ファイル内のレイヤーマスクデータに関する情報を含む基底 LayerMaskData クラスを定義します。これにより、Adobe\ufffd Photoshop\ufffd ファイルをプログラムで変更したり、PSD フォーマットの編集を自動化したりできます。レイヤーがラスターマスクのみを持つ場合、ImageData はラスターマスクデータバイトを含みます。レイヤーがベクターマスクのみを持つ場合、ImageData はベクターマスクをラスタライズ（キャッシュ）したデータバイトを含みます。レイヤーがラスターマスクとベクターマスクの両方を持つ場合、ImageData はラスターマスクとラスタライズされたベクターマスクを結合したものを含みます。ImageData ([getImageData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getImageData)/[setImageData(byte[])](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setImageData-byte---)) バイト長は、MaskRectangle の Width \* Height と等しくなる必要があります ([getMaskRectangle](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#getMaskRectangle)/[setMaskRectangle(Rectangle)](../../com.aspose.psd.fileformats.psd.layers/layermaskdata\#setMaskRectangle-Rectangle-)) プロパティです。単に LayerMaskData を削除/追加/更新するだけでは、チャネルが更新されないため正しく保存できませんが、正しいレンダリングを提供する場合があります。その場合は [Layer.addLayerMask(LayerMaskData)](../../com.aspose.psd.fileformats.psd.layers/layer\#addLayerMask-LayerMaskData-) メソッドを使用すべきです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | このインスタンスをクローンします。 |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | レイヤーマスクをクローンします。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBottom()](#getBottom--) | 下部レイヤーマスクの位置を取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | レイヤーマスクデータのサイズを取得します。 |
| [getDefaultColor()](#getDefaultColor--) | デフォルトカラーを取得または設定します。 |
| [getFlags()](#getFlags--) | レイヤーマスクフラグを取得または設定します。 |
| [getHeight_internalized()](#getHeight-internalized--) | マスクの高さを取得します。 |
| [getImageData()](#getImageData--) | PSD ファイル内のレイヤーマスク データ（ベクターマスクがある場合は結合/最終マスク）を取得または設定します。 |
| [getLeft()](#getLeft--) | 左側のレイヤーマスク位置を取得または設定します。 |
| [getMaskRectangle()](#getMaskRectangle--) | PSD ファイル内のレイヤーマスクのマスク Rectangle を取得または設定します。 |
| [getRight()](#getRight--) | 右側のレイヤーマスク位置を取得または設定します。 |
| [getTop()](#getTop--) | 上側のレイヤーマスク位置を取得または設定します。 |
| [getWidth_internalized()](#getWidth-internalized--) | マスクの幅を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | 指定された StreamContainer に [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) を保存します。 |
| [setBottom(int value)](#setBottom-int-) | 下部レイヤーマスクの位置を取得または設定します。 |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | デフォルトカラーを取得または設定します。 |
| [setFlags(byte value)](#setFlags-byte-) | レイヤーマスクフラグを取得または設定します。 |
| [setImageData(byte[] value)](#setImageData-byte---) | PSD ファイル内のレイヤーマスク データ（ベクターマスクがある場合は結合/最終マスク）を取得または設定します。 |
| [setLeft(int value)](#setLeft-int-) | 左側のレイヤーマスク位置を取得または設定します。 |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | PSD ファイル内のレイヤーマスクのマスク Rectangle を取得または設定します。 |
| [setRight(int value)](#setRight-int-) | 右側のレイヤーマスク位置を取得または設定します。 |
| [setTop(int value)](#setTop-int-) | 上側のレイヤーマスク位置を取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
public abstract void save_internalized(StreamContainer streamContainer)
```


指定された StreamContainer に [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) を保存します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | データを保存するストリーム コンテナです。 |

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

