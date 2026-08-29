---
title: "AiLayerSection"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "Ai フォーマットのレイヤーセクションです"
type: docs
weight: 15
url: /ja/java/com.aspose.psd.fileformats.ai/ailayersection/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.fileformats.ai.AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
```
public final class AiLayerSection extends AiDataSection
```

Ai フォーマットのレイヤーセクションです
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addRasterImage(AiRasterImageSection rasterImage)](#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-) | ラスター画像を追加します。 |
| [close()](#close--) | Closable インターフェイスを実装しており、JDK 1.7 以降の try-with-resources 文で使用できます。 |
| [create_internalized(StreamContainer stream)](#create-internalized-com.aspose.psd.StreamContainer-) |  |
| [create_internalized(String name, String[] properties, StreamContainer stream)](#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-) |  |
| [dispose()](#dispose--) | 現在のインスタンスを破棄します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlue()](#getBlue--) | 青色コンポーネントを取得または設定します。 |
| [getClass()](#getClass--) |  |
| [getColorIndex()](#getColorIndex--) | 色のインデックスを取得または設定します。 |
| [getColorNumber()](#getColorNumber--) | カラー番号を取得または設定します。 |
| [getData()](#getData--) | 文字列データを取得します。 |
| [getDimValue()](#getDimValue--) | ディム値をパーセンテージで取得または設定します。 |
| [getDisposed()](#getDisposed--) | このインスタンスが破棄されているかどうかを示す値を取得します。 |
| [getGreen()](#getGreen--) | 緑色コンポーネントを取得または設定します。 |
| [getName()](#getName--) | レイヤー名を取得または設定します。 |
| [getRasterImages()](#getRasterImages--) | ラスター画像を取得します。 |
| [getRed()](#getRed--) | 赤色コンポーネントを取得または設定します。 |
| [getStream_internalized()](#getStream-internalized--) | 内部ストリームを取得します。 |
| [hasMultiLayerMasks()](#hasMultiLayerMasks--) | このインスタンスがマルチレイヤーマスクを持つかどうかを示す値を取得または設定します。 |
| [hashCode()](#hashCode--) |  |
| [isImagesDimmed()](#isImagesDimmed--) | このレイヤーが暗くされているかどうかを示す値を取得または設定します。 |
| [isLocked()](#isLocked--) | このレイヤーがロックされているかどうかを示す値を取得または設定します。 |
| [isPreview()](#isPreview--) | このレイヤーがプレビューであるかどうかを示す値を取得または設定します。 |
| [isPrinted()](#isPrinted--) | このレイヤーが印刷されるかどうかを示す値を取得または設定します。 |
| [isShown()](#isShown--) | このレイヤーが表示されるかどうかを示す値を取得または設定します。 |
| [isTemplate()](#isTemplate--) | このレイヤーがテンプレートレイヤーであるかどうかを示す値を取得または設定します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlue(int value)](#setBlue-int-) | 青色コンポーネントを取得または設定します。 |
| [setColorIndex(int value)](#setColorIndex-int-) | 色のインデックスを取得または設定します。 |
| [setColorNumber(int value)](#setColorNumber-int-) | カラー番号を取得または設定します。 |
| [setDimValue(int value)](#setDimValue-int-) | ディム値をパーセンテージで取得または設定します。 |
| [setGreen(int value)](#setGreen-int-) | 緑色コンポーネントを取得または設定します。 |
| [setImagesDimmed(boolean value)](#setImagesDimmed-boolean-) | このレイヤーが暗くされているかどうかを示す値を取得または設定します。 |
| [setLocked(boolean value)](#setLocked-boolean-) | このレイヤーがロックされているかどうかを示す値を取得または設定します。 |
| [setMultiLayerMasks(boolean value)](#setMultiLayerMasks-boolean-) | このインスタンスがマルチレイヤーマスクを持つかどうかを示す値を取得または設定します。 |
| [setName(String value)](#setName-java.lang.String-) | レイヤー名を取得または設定します。 |
| [setPreview(boolean value)](#setPreview-boolean-) | このレイヤーがプレビューであるかどうかを示す値を取得または設定します。 |
| [setPrinted(boolean value)](#setPrinted-boolean-) | このレイヤーが印刷されるかどうかを示す値を取得または設定します。 |
| [setRed(int value)](#setRed-int-) | 赤色コンポーネントを取得または設定します。 |
| [setShown(boolean value)](#setShown-boolean-) | このレイヤーが表示されるかどうかを示す値を取得または設定します。 |
| [setTemplate(boolean value)](#setTemplate-boolean-) | このレイヤーがテンプレートレイヤーであるかどうかを示す値を取得または設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addRasterImage(AiRasterImageSection rasterImage) {#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-}
```
public final void addRasterImage(AiRasterImageSection rasterImage)
```


ラスター画像を追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rasterImage | [AiRasterImageSection](../../com.aspose.psd.fileformats.ai/airasterimagesection) | ラスタ画像です。 |

### close() {#close--}
```
public void close()
```


Closable インターフェイスを実装し、JDK 1.7 以降の try-with-resources 文で使用できます。このメソッドは単に dispose メソッドを呼び出すだけです。

### create_internalized(StreamContainer stream) {#create-internalized-com.aspose.psd.StreamContainer-}
```
public static AiDataSection create_internalized(StreamContainer stream)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
### create_internalized(String name, String[] properties, StreamContainer stream) {#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-}
```
public static AiLayerSection create_internalized(String name, String[] properties, StreamContainer stream)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String |  |
| プロパティ | java.lang.String[] |  |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiLayerSection](../../com.aspose.psd.fileformats.ai/ailayersection)
### dispose() {#dispose--}
```
public final void dispose()
```


現在のインスタンスを破棄します。

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
### getBlue() {#getBlue--}
```
public final int getBlue()
```


青色コンポーネントを取得または設定します。

Value: 青色成分。

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorIndex() {#getColorIndex--}
```
public final int getColorIndex()
```


色のインデックスを取得または設定します。この引数は \\u20131 から 26 の間の値を取ることができます。各整数は、ユーザー識別のためにレイヤーに割り当て可能な色を表します。

Value: 色のインデックス。

**Returns:**
int
### getColorNumber() {#getColorNumber--}
```
public final int getColorNumber()
```


色番号を取得または設定します。-1 は、Red、Green、Blue プロパティからのカスタムカラー値です。レイヤー\\u2019のカラー設定を指定します。

Value: カラー番号。

**Returns:**
int
### getData() {#getData--}
```
public final String getData()
```


文字列データを取得します。

**Returns:**
java.lang.String - セクションの文字列データ
### getDimValue() {#getDimValue--}
```
public final int getDimValue()
```


ディム値（パーセンテージ）を取得または設定します。レイヤーに含まれるリンク画像およびビットマップ画像の強度を指定されたパーセンテージに減少させます。

Value: ディム値（パーセンテージ）。

**Returns:**
int
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


このインスタンスが破棄されているかどうかを示す値を取得します。

**Returns:**
boolean - 破棄されている場合は true、そうでなければ false 。
### getGreen() {#getGreen--}
```
public final int getGreen()
```


緑色コンポーネントを取得または設定します。

Value: 緑色成分。

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


レイヤー名を取得または設定します。Layers パネルに表示されるアイテムの名前を指定します。

値: レイヤー名。

**Returns:**
java.lang.String
### getRasterImages() {#getRasterImages--}
```
public final AiRasterImageSection[] getRasterImages()
```


ラスター画像を取得します。

Value: ラスタ画像。

**Returns:**
com.aspose.psd.fileformats.ai.AiRasterImageSection[]
### getRed() {#getRed--}
```
public final int getRed()
```


赤色コンポーネントを取得または設定します。

Value: 赤色成分。

**Returns:**
int
### getStream_internalized() {#getStream-internalized--}
```
public final StreamContainer getStream_internalized()
```


内部ストリームを取得します。

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  instance.
### hasMultiLayerMasks() {#hasMultiLayerMasks--}
```
public final boolean hasMultiLayerMasks()
```


このインスタンスがマルチレイヤーマスクを持つかどうかを示す値を取得または設定します。

Value:  true  このインスタンスにマルチレイヤーマスクがある場合; それ以外の場合は  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isImagesDimmed() {#isImagesDimmed--}
```
public final boolean isImagesDimmed()
```


このレイヤーが暗くなるかどうかを示す値を取得または設定します。レイヤーに含まれるリンク画像およびビットマップ画像の強度を減少させます。

Value:  true  このレイヤーが暗くなる場合; それ以外の場合は  false .

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


このレイヤーがロックされているかどうかを示す値を取得または設定します。アイテムへの変更を防止します。

Value:  true  このレイヤーがロックされている場合; それ以外の場合は  false .

**Returns:**
boolean
### isPreview() {#isPreview--}
```
public final boolean isPreview()
```


このレイヤーがプレビューかどうかを示す値を取得または設定します。レイヤーに含まれるアートワークをアウトラインではなくカラーで表示します。

Value:  true  このレイヤーがプレビューの場合; それ以外の場合は  false .

**Returns:**
boolean
### isPrinted() {#isPrinted--}
```
public final boolean isPrinted()
```


このレイヤーが印刷されるかどうかを示す値を取得または設定します。true の場合、レイヤーに含まれるアートワークを印刷可能にします。

Value:  true  このレイヤーが印刷される場合; それ以外の場合は  false .

**Returns:**
boolean
### isShown() {#isShown--}
```
public final boolean isShown()
```


このレイヤーが表示されるかどうかを示す値を取得または設定します。true の場合、レイヤーに含まれるすべてのアートワークをアートボードに表示します。

Value:  true  このレイヤーが表示される場合; それ以外の場合は  false .

**Returns:**
boolean
### isTemplate() {#isTemplate--}
```
public final boolean isTemplate()
```


このレイヤーがテンプレートレイヤーであるかどうかを示す値を取得または設定します。

Value:  true  このレイヤーがテンプレートの場合; それ以外の場合は  false .

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




### setBlue(int value) {#setBlue-int-}
```
public final void setBlue(int value)
```


青色コンポーネントを取得または設定します。

Value: 青色成分。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setColorIndex(int value) {#setColorIndex-int-}
```
public final void setColorIndex(int value)
```


色のインデックスを取得または設定します。この引数は \\u20131 から 26 の間の値を取ることができます。各整数は、ユーザー識別のためにレイヤーに割り当て可能な色を表します。

Value: 色のインデックス。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setColorNumber(int value) {#setColorNumber-int-}
```
public final void setColorNumber(int value)
```


色番号を取得または設定します。-1 は、Red、Green、Blue プロパティからのカスタムカラー値です。レイヤー\\u2019のカラー設定を指定します。

Value: カラー番号。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setDimValue(int value) {#setDimValue-int-}
```
public final void setDimValue(int value)
```


ディム値（パーセンテージ）を取得または設定します。レイヤーに含まれるリンク画像およびビットマップ画像の強度を指定されたパーセンテージに減少させます。

Value: ディム値（パーセンテージ）。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setGreen(int value) {#setGreen-int-}
```
public final void setGreen(int value)
```


緑色コンポーネントを取得または設定します。

Value: 緑色成分。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setImagesDimmed(boolean value) {#setImagesDimmed-boolean-}
```
public final void setImagesDimmed(boolean value)
```


このレイヤーが暗くなるかどうかを示す値を取得または設定します。レイヤーに含まれるリンク画像およびビットマップ画像の強度を減少させます。

Value:  true  このレイヤーが暗くなる場合; それ以外の場合は  false .

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


このレイヤーがロックされているかどうかを示す値を取得または設定します。アイテムへの変更を防止します。

Value:  true  このレイヤーがロックされている場合; それ以外の場合は  false .

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setMultiLayerMasks(boolean value) {#setMultiLayerMasks-boolean-}
```
public final void setMultiLayerMasks(boolean value)
```


このインスタンスがマルチレイヤーマスクを持つかどうかを示す値を取得または設定します。

Value:  true  このインスタンスにマルチレイヤーマスクがある場合; それ以外の場合は  false .

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


レイヤー名を取得または設定します。Layers パネルに表示されるアイテムの名前を指定します。

値: レイヤー名。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### setPreview(boolean value) {#setPreview-boolean-}
```
public final void setPreview(boolean value)
```


このレイヤーがプレビューかどうかを示す値を取得または設定します。レイヤーに含まれるアートワークをアウトラインではなくカラーで表示します。

Value:  true  このレイヤーがプレビューの場合; それ以外の場合は  false .

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setPrinted(boolean value) {#setPrinted-boolean-}
```
public final void setPrinted(boolean value)
```


このレイヤーが印刷されるかどうかを示す値を取得または設定します。true の場合、レイヤーに含まれるアートワークを印刷可能にします。

Value:  true  このレイヤーが印刷される場合; それ以外の場合は  false .

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setRed(int value) {#setRed-int-}
```
public final void setRed(int value)
```


赤色コンポーネントを取得または設定します。

Value: 赤色成分。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setShown(boolean value) {#setShown-boolean-}
```
public final void setShown(boolean value)
```


このレイヤーが表示されるかどうかを示す値を取得または設定します。true の場合、レイヤーに含まれるすべてのアートワークをアートボードに表示します。

Value:  true  このレイヤーが表示される場合; それ以外の場合は  false .

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### setTemplate(boolean value) {#setTemplate-boolean-}
```
public final void setTemplate(boolean value)
```


このレイヤーがテンプレートレイヤーであるかどうかを示す値を取得または設定します。

Value:  true  このレイヤーがテンプレートの場合; それ以外の場合は  false .

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

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

