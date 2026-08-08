---
title: "CustomLineCap"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "カスタムのユーザー定義ラインキャップをカプセル化します。"
type: docs
weight: 34
url: /ja/java/com.aspose.psd/customlinecap/
---

**Inheritance:**
java.lang.Object
```
public class CustomLineCap
```

カスタムのユーザー定義ラインキャップをカプセル化します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-) | 指定された輪郭と塗りつぶしで  CustomLineCap  クラスの新しいインスタンスを初期化します。 |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-) | 指定された既存の  LineCap  列挙体から、指定された輪郭と塗りつぶしで  CustomLineCap  クラスの新しいインスタンスを初期化します。 |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-) | 指定された既存の  LineCap  列挙体から、指定された輪郭、塗りつぶし、およびインセットで  CustomLineCap  クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaseCap()](#getBaseCap--) | この  CustomLineCap  が基づく  LineCap  列挙体を取得します。 |
| [getBaseInset()](#getBaseInset--) | キャップと線との間の距離を取得します。 |
| [getClass()](#getClass--) |  |
| [getFillPath()](#getFillPath--) | カスタムキャップの塗りつぶしを定義するオブジェクトを取得します。 |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | このカスタムキャップを構成する線の開始と終了に使用されるキャップを取得します。 |
| [getStrokeJoin()](#getStrokeJoin--) | この  CustomLineCap  オブジェクトを構成する線がどのように結合されるかを決定する  LineJoin  列挙体を取得します。 |
| [getStrokePath()](#getStrokePath--) | カスタムキャップの輪郭を定義するオブジェクトを取得します。 |
| [getWidthScale()](#getWidthScale--) | この  CustomLineCap  クラスオブジェクトを、  System.Drawing.Pen  オブジェクトの幅に対してどれだけスケールするかの量を取得します。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBaseCap(int value)](#setBaseCap-int-) | この  CustomLineCap  が基づく  LineCap  列挙体を設定します。 |
| [setBaseInset(float value)](#setBaseInset-float-) | キャップと線との間の距離を設定します。 |
| [setFillPath(GraphicsPath value)](#setFillPath-com.aspose.psd.GraphicsPath-) | カスタムキャップの塗りつぶしを定義するオブジェクトを設定します。 |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | このカスタムキャップを構成する線の開始と終了に使用されるキャップを設定します。 |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | この  CustomLineCap  オブジェクトを構成する線がどのように結合されるかを決定する  LineJoin  列挙体を設定します。 |
| [setStrokePath(GraphicsPath value)](#setStrokePath-com.aspose.psd.GraphicsPath-) | カスタムキャップの輪郭を定義するオブジェクトを設定します。 |
| [setWidthScale(float value)](#setWidthScale-float-) | この  CustomLineCap  クラスオブジェクトを、  System.Drawing.Pen  オブジェクトの幅に対してどれだけスケールするかの量を設定します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


指定された輪郭と塗りつぶしで  CustomLineCap  クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | カスタムキャップの塗りつぶしを定義する  GraphicsPath  オブジェクトです。 |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | カスタムキャップの輪郭を定義する GraphicsPath オブジェクト。 |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


指定された既存の  LineCap  列挙体から、指定された輪郭と塗りつぶしで  CustomLineCap  クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | カスタムキャップの塗りつぶしを定義する  GraphicsPath  オブジェクトです。 |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | カスタムキャップの輪郭を定義する GraphicsPath オブジェクト。 |
| baseCap | int | カスタムキャップを作成する元となるラインキャップ。 |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


指定された既存の  LineCap  列挙体から、指定された輪郭、塗りつぶし、およびインセットで  CustomLineCap  クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | カスタムキャップの塗りつぶしを定義する  GraphicsPath  オブジェクトです。 |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | カスタムキャップの輪郭を定義する GraphicsPath オブジェクト。 |
| baseCap | int | カスタムキャップを作成する元となるラインキャップ。 |
| baseInset | float | キャップとラインの間の距離。 |

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
### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


この  CustomLineCap  が基づく  LineCap  列挙体を取得します。

**Returns:**
int - この CustomLineCap が基づく LineCap 列挙体。
### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


キャップと線との間の距離を取得します。

**Returns:**
float - キャップの開始点とラインの終点間の距離。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```


カスタムキャップの塗りつぶしを定義するオブジェクトを取得します。

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the fill for the custom cap.
### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public void getStrokeCaps(int[] startCap, int[] endCap)
```


このカスタムキャップを構成する線の開始と終了に使用されるキャップを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startCap | int[] | このキャップ内のラインの開始時に使用される LineCap 列挙体。 |
| endCap | int[] | このキャップ内のラインの終了時に使用される LineCap 列挙体。 |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


この  CustomLineCap  オブジェクトを構成する線がどのように結合されるかを決定する  LineJoin  列挙体を取得します。

**Returns:**
int - この CustomLineCap オブジェクトがラインを結合するために使用する LineJoin 列挙体。
### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


カスタムキャップの輪郭を定義するオブジェクトを取得します。

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the outline of the custom cap.
### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


この  CustomLineCap  クラスオブジェクトを、  System.Drawing.Pen  オブジェクトの幅に対してどれだけスケールするかの量を取得します。

**Returns:**
float - キャップを拡大縮小する量。
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




### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


この  CustomLineCap  が基づく  LineCap  列挙体を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | この CustomLineCap が基づく LineCap 列挙体。 |

### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


キャップと線との間の距離を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | キャップの開始点とラインの終点間の距離。 |

### setFillPath(GraphicsPath value) {#setFillPath-com.aspose.psd.GraphicsPath-}
```
public void setFillPath(GraphicsPath value)
```


カスタムキャップの塗りつぶしを定義するオブジェクトを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | カスタムキャップの塗りを定義するオブジェクト。 |

### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public void setStrokeCaps(int startCap, int endCap)
```


このカスタムキャップを構成する線の開始と終了に使用されるキャップを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startCap | int | このキャップ内のラインの開始時に使用される LineCap 列挙体。 |
| endCap | int | このキャップ内のラインの終了時に使用される LineCap 列挙体。 |

### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


この  CustomLineCap  オブジェクトを構成する線がどのように結合されるかを決定する  LineJoin  列挙体を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | この CustomLineCap オブジェクトがラインを結合するために使用する LineJoin 列挙体。 |

### setStrokePath(GraphicsPath value) {#setStrokePath-com.aspose.psd.GraphicsPath-}
```
public void setStrokePath(GraphicsPath value)
```


カスタムキャップの輪郭を定義するオブジェクトを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | カスタムキャップの輪郭を定義するオブジェクト。 |

### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


この  CustomLineCap  クラスオブジェクトを、  System.Drawing.Pen  オブジェクトの幅に対してどれだけスケールするかの量を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | キャップを拡大縮小する量。 |

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

