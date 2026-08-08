---
title: "Pen"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "線や曲線、図形の描画に使用されるオブジェクトを定義します。"
type: docs
weight: 77
url: /ja/java/com.aspose.psd/pen/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.TransparencySupporter](../../com.aspose.psd/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

線、曲線、図形の描画に使用されるオブジェクトを定義します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.psd.Color-) | 指定された色で  Pen  クラスの新しいインスタンスを初期化します。 |
| [Pen(Color color, float width)](#Pen-com.aspose.psd.Color-float-) | 指定された  Color  と  Pen.Width  プロパティで  Pen  クラスの新しいインスタンスを初期化します。 |
| [Pen(Brush brush)](#Pen-com.aspose.psd.Brush-) | 指定された  Brush  で  Pen  クラスの新しいインスタンスを初期化します。 |
| [Pen(Brush brush, float width)](#Pen-com.aspose.psd.Brush-float-) | 指定された  Brush  と  Pen.Width  で  Pen  クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | この  Pen  の配置を取得します。 |
| [getBrush()](#getBrush--) | この  Pen  の属性を決定する  Brush  を取得します。 |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | この  Pen  の色を取得します。 |
| [getCompoundArray()](#getCompoundArray--) | 複合ペンを指定する値の配列を取得します。 |
| [getCustomEndCap()](#getCustomEndCap--) | この  Pen  で描画された線の終端で使用するカスタムキャップを取得します。 |
| [getCustomStartCap()](#getCustomStartCap--) | この  Pen  で描画された線の開始部で使用するカスタムキャップを取得します。 |
| [getDashCap()](#getDashCap--) | この  Pen  で描画された破線を構成するダッシュの終端で使用されるキャップスタイルを取得します。 |
| [getDashOffset()](#getDashOffset--) | 線の開始点からダッシュパターンの開始までの距離を取得します。 |
| [getDashPattern()](#getDashPattern--) | カスタムダッシュとスペースの配列を取得します。 |
| [getDashStyle()](#getDashStyle--) | この  Pen  で描画された破線に使用されるスタイルを取得します。 |
| [getEndCap()](#getEndCap--) | この  Pen  で描画された線の終端で使用されるキャップスタイルを取得します。 |
| [getLineJoin()](#getLineJoin--) | この  Pen  で描画された連続する2本の線の端部の結合スタイルを取得します。 |
| [getMiterLimit()](#getMiterLimit--) | 斜め角の結合部の厚さの上限を取得します。 |
| [getOpacity()](#getOpacity--) | オブジェクトの不透明度を取得します。 |
| [getPenType()](#getPenType--) | この  Pen  で描画された線のスタイルを取得します。 |
| [getStartCap()](#getStartCap--) | この  Pen  で描画された線の開始部で使用されるキャップスタイルを取得します。 |
| [getTransform()](#getTransform--) | この  Pen  の幾何変換のコピーを取得します。 |
| [getWidth()](#getWidth--) | 描画に使用される Graphics オブジェクトの単位で、この  Pen  の幅を取得します。 |
| [hashCode()](#hashCode--) |  |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | この  Pen  の変換行列を指定された  Matrix  で乗算します。 |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | この  Pen  の変換行列を指定された  Matrix  で、指定された順序で乗算します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | この  Pen  の幾何変換行列を単位行列にリセットします。 |
| [rotateTransform(float angle)](#rotateTransform-float-) | ローカルの幾何変換を指定された角度で回転させます。 |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | ローカルの幾何変換を指定された角度で、指定された順序で回転させます。 |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | ローカルの幾何変換を指定された係数で拡大縮小します。 |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | ローカルの幾何変換を指定された係数で、指定された順序で拡大縮小します。 |
| [setAlignment(int value)](#setAlignment-int-) | この  Pen  の配置を設定します。 |
| [setBrush(Brush value)](#setBrush-com.aspose.psd.Brush-) | この  Pen  の属性を決定する  Brush  を設定します。 |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | この  Pen  の色を設定します。 |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | 複合ペンを指定する値の配列を設定します。 |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.psd.CustomLineCap-) | この  Pen  で描画された線の末端に使用するカスタムキャップを設定します。 |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.psd.CustomLineCap-) | この  Pen  で描画された線の開始点に使用するカスタムキャップを設定します。 |
| [setDashCap(int value)](#setDashCap-int-) | この  Pen  で描画された破線を構成するダッシュの末端に使用されるキャップスタイルを設定します。 |
| [setDashOffset(float value)](#setDashOffset-float-) | 線の開始点からダッシュパターンの開始までの距離を設定します。 |
| [setDashPattern(float[] value)](#setDashPattern-float---) | カスタムダッシュとスペースの配列を設定します。 |
| [setDashStyle(int value)](#setDashStyle-int-) | この  Pen  で描画された破線に使用されるスタイルを設定します。 |
| [setEndCap(int value)](#setEndCap-int-) | この  Pen  で描画された線の末端に使用されるキャップスタイルを設定します。 |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | この  Pen  が描画する線の末端に使用されるキャップのスタイルを決定する値を設定します。 |
| [setLineJoin(int value)](#setLineJoin-int-) | この  Pen  で描画された連続する2本の線の端部に使用される結合スタイルを設定します。 |
| [setMiterLimit(float value)](#setMiterLimit-float-) | 斜め角の結合部の厚さの上限を設定します。 |
| [setOpacity(float value)](#setOpacity-float-) | オブジェクトの不透明度を設定します。 |
| [setStartCap(int value)](#setStartCap-int-) | この  Pen  で描画された線の開始点に使用されるキャップスタイルを設定します。 |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | この  Pen  の幾何変換のコピーを設定します。 |
| [setWidth(float value)](#setWidth-float-) | 描画に使用される Graphics オブジェクトの単位で、この  Pen  の幅を設定します。 |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | ローカルの幾何変換を指定された寸法で平行移動します。 |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | 指定された次元で、指定された順序に従ってローカルの幾何変換を平行移動します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Pen(Color color) {#Pen-com.aspose.psd.Color-}
```
public Pen(Color color)
```


指定された色で  Pen  クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | この Pen の色を示す Color 構造体です。 |

### Pen(Color color, float width) {#Pen-com.aspose.psd.Color-float-}
```
public Pen(Color color, float width)
```


指定された  Color  と  Pen.Width  プロパティで  Pen  クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | この Pen の色を示す Color 構造体です。 |
| 幅 | float | この Pen の幅を示す値です。 |

### Pen(Brush brush) {#Pen-com.aspose.psd.Brush-}
```
public Pen(Brush brush)
```


指定された  Brush  で  Pen  クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | この Pen の塗りプロパティを決定する Brush です。 |

### Pen(Brush brush, float width) {#Pen-com.aspose.psd.Brush-float-}
```
public Pen(Brush brush, float width)
```


指定された  Brush  と  Pen.Width  で  Pen  クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.psd/brush) | この Pen の特性を決定する Brush です。 |
| 幅 | float | 新しい Pen の幅です。 |

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


この  Pen  の配置を取得します。

**Returns:**
int - この Pen の配置を表す PenAlignment です。
### getBrush() {#getBrush--}
```
public Brush getBrush()
```


この  Pen  の属性を決定する  Brush  を取得します。

**Returns:**
[Brush](../../com.aspose.psd/brush) - A  Brush  that determines attributes of this  Pen .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


この  Pen  の色を取得します。

**Returns:**
[Color](../../com.aspose.psd/color) - A  Color  structure that represents the color of this  Pen .
### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


複合ペンを指定する値の配列を取得します。複合ペンは平行線と間隔で構成された複合線を描画します。

**Returns:**
float[] - 複合配列を指定する実数の配列です。配列の要素は昇順で、0 未満でも 1 超過でもいけません。
### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


この  Pen  で描画された線の終端で使用するカスタムキャップを取得します。

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the end of lines drawn with this  Pen .
### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


この  Pen  で描画された線の開始部で使用するカスタムキャップを取得します。

**Returns:**
[CustomLineCap](../../com.aspose.psd/customlinecap) - A  CustomLineCap  that represents the cap used at the beginning of lines drawn with this  Pen .
### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


この  Pen  で描画された破線を構成するダッシュの終端で使用されるキャップスタイルを取得します。

**Returns:**
int - この Pen で描画される破線の開始と終了に使用されるダッシュのキャップスタイルを表す DashCap のいずれかです。
### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


線の開始点からダッシュパターンの開始までの距離を取得します。

**Returns:**
float - 線の開始点からダッシュパターンの開始までの距離です。
### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


カスタムダッシュとスペースの配列を取得します。

**Returns:**
float[] - 破線における交互のダッシュとスペースの長さを指定する実数の配列です。
### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


この  Pen  で描画された破線に使用されるスタイルを取得します。

**Returns:**
int - この Pen で描画される破線に使用されるスタイルを表す DashStyle です。
### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


この  Pen  で描画された線の終端で使用されるキャップスタイルを取得します。

**Returns:**
int - この Pen で描画される線の終端に使用されるキャップスタイルを表す LineCap のいずれかです。
### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


この  Pen  で描画された連続する2本の線の端部の結合スタイルを取得します。

**Returns:**
int - この Pen で描画される連続する二本の線の端部の結合スタイルを表す LineJoin です。
### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


斜め角の結合部の厚さの上限を取得します。

**Returns:**
float - 斜め角の結合部の厚さの上限です。
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


オブジェクトの不透明度を取得します。値は 0 から 1 の間である必要があります。0 の値はオブジェクトが完全に可視であることを意味し、1 の値はオブジェクトが完全に不透明であることを意味します。

**Returns:**
float - 不透明度の値。
### getPenType() {#getPenType--}
```
public int getPenType()
```


この  Pen  で描画された線のスタイルを取得します。

**Returns:**
int - この Pen で描画される線のスタイルを指定する PenType 列挙体です。
### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


この  Pen  で描画された線の開始部で使用されるキャップスタイルを取得します。

**Returns:**
int - この Pen で描画される線の開始に使用されるキャップスタイルを表す LineCap のいずれかです。
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


この  Pen  の幾何変換のコピーを取得します。

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Matrix  that represents the geometric transformation for this  Pen .
### getWidth() {#getWidth--}
```
public float getWidth()
```


描画に使用される Graphics オブジェクトの単位で、この  Pen  の幅を取得します。

**Returns:**
float - この Pen の幅です。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


この  Pen  の変換行列を指定された  Matrix  で乗算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 変換行列に掛け合わせる Matrix オブジェクトです。 |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


この  Pen  の変換行列を指定された  Matrix  で、指定された順序で乗算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | 変換行列に掛け合わせる Matrix です。 |
| order | int | 乗算操作を実行する順序です。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


この  Pen  の幾何変換行列を単位行列にリセットします。

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


指定された角度でローカルの幾何変換を回転させます。このメソッドは回転を変換の先頭に追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転角度です。 |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


ローカルの幾何変換を指定された角度で、指定された順序で回転させます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転角度です。 |
| order | int | 回転行列を末尾に追加するか先頭に追加するかを指定する MatrixOrder です。 |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


指定された係数でローカルの幾何変換を拡大縮小します。このメソッドは拡大縮小行列を変換の先頭に追加します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sx | float | 変換を x 軸方向に拡大する係数。 |
| sy | float | 変換を y 軸方向に拡大する係数。 |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


ローカルの幾何変換を指定された係数で、指定された順序で拡大縮小します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sx | float | 変換を x 軸方向に拡大する係数。 |
| sy | float | 変換を y 軸方向に拡大する係数。 |
| order | int | 拡大行列を追加するか前置するかを指定する MatrixOrder。 |

### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


この  Pen  の配置を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | この Pen の配置を表す PenAlignment。 |

### setBrush(Brush value) {#setBrush-com.aspose.psd.Brush-}
```
public void setBrush(Brush value)
```


この  Pen  の属性を決定する  Brush  を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Brush](../../com.aspose.psd/brush) | この Pen の属性を決定する Brush。 |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```


この  Pen  の色を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | この Pen の色を表す Color 構造体。 |

### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


複合ペンを指定する値の配列を設定します。複合ペンは平行線と間隔で構成された複合線を描画します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float[] | 複合配列を指定する実数の配列です。配列の要素は昇順で、0 未満でも 1 超過でもいけません。 |

### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


この  Pen  で描画された線の末端に使用するカスタムキャップを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | この Pen で描画された線の終端に使用されるキャップを表す CustomLineCap。 |

### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.psd.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


この  Pen  で描画された線の開始点に使用するカスタムキャップを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.psd/customlinecap) | この Pen で描画された線の開始点に使用されるキャップを表す CustomLineCap。 |

### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


この  Pen  で描画された破線を構成するダッシュの末端に使用されるキャップスタイルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | この Pen で描画された破線を構成するダッシュの開始点と終了点で使用されるキャップスタイルを表す DashCap のいずれかの値。 |

### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


線の開始点からダッシュパターンの開始までの距離を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | 線の開始点からダッシュパターンの開始までの距離。 |

### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


カスタムダッシュとスペースの配列を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float[] | 破線における交互のダッシュとスペースの長さを指定する実数の配列。 |

### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


この  Pen  で描画された破線に使用されるスタイルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | この Pen で描画された破線に使用されるスタイルを表す DashStyle。 |

### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


この  Pen  で描画された線の末端に使用されるキャップスタイルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | この Pen で描画された線の終端で使用されるキャップスタイルを表す LineCap のいずれかの値。 |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


この  Pen  が描画する線の末端に使用されるキャップのスタイルを決定する値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| startCap | int | この Pen で描画された線の開始点で使用するキャップスタイルを表す LineCap。 |
| endCap | int | この Pen で描画された線の終端で使用するキャップスタイルを表す LineCap。 |
| dashCap | int | この Pen で描画された破線の開始点または終端で使用するキャップスタイルを表す LineCap。 |

### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


この  Pen  で描画された連続する2本の線の端部に使用される結合スタイルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | この Pen で描画された連続する二本の線の端部で使用される結合スタイルを表す LineJoin。 |

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


斜め角の結合部の厚さの上限を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | 斜め角の結合部の厚さの上限。 |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


オブジェクトの不透明度を設定します。値は 0 から 1 の間である必要があります。0 の値はオブジェクトが完全に可視であることを意味し、1 の値はオブジェクトが完全に不透明であることを意味します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | 不透明度の値。 |

### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


この  Pen  で描画された線の開始点に使用されるキャップスタイルを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int | この Pen で描画された線の開始点で使用されるキャップスタイルを表す LineCap のいずれかの値。 |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


この  Pen  の幾何変換のコピーを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) | この Pen の幾何変換を表す Matrix のコピー。 |

### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


描画に使用される Graphics オブジェクトの単位で、この  Pen  の幅を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float | この Pen の幅。 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


指定された寸法でローカルの幾何変換を平行移動します。このメソッドは変換の先頭に平行移動を前置します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dx | float | x 方向の平行移動量です。 |
| dy | float | y 方向の平行移動量です。 |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


指定された次元で、指定された順序に従ってローカルの幾何変換を平行移動します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| dx | float | x 方向の平行移動量です。 |
| dy | float | y 方向の平行移動量です。 |
| order | int | 平行移動を適用する順序（先頭に付加するか末尾に追加するか）です。 |

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

