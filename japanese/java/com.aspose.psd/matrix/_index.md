---
title: "Matrix"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "GDI Matrix を置き換えます。"
type: docs
weight: 69
url: /ja/java/com.aspose.psd/matrix/
---

**Inheritance:**
java.lang.Object
```
public class Matrix
```

GDI+ Matrix を置き換えます。

ほとんどのアルゴリズムは Sun の AffineTransform.java から取得されています。内部で使用される行列要素の Java 名です。java 名から .net 名へのマッピングと説明: m00 M11 Scale X m10 M12 Shear Y m01 M21 Shear X m11 M22 Scale Y m02 M31 Translate X m12 M32 Translate Y
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Matrix()](#Matrix--) | Matrix クラスの新しいインスタンスを単位行列として初期化します。 |
| [Matrix(float m11, float m12, float m21, float m22, float m31, float m32)](#Matrix-float-float-float-float-float-float-) | Matrix クラスの新しいインスタンスを初期化します。 |
| [Matrix(Matrix origin)](#Matrix-com.aspose.psd.Matrix-) | Matrix クラスのコピーを作成します。 |
| [Matrix(RectangleF rect, PointF[] plgpts)](#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---) | 指定された矩形と点の配列で定義された幾何変換に対して、Aspose.Imaging.Matrix クラスの新しいインスタンスを初期化します。 |
| [Matrix(Rectangle rect, Point[] plgpts)](#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---) | 指定された矩形と点の配列で定義された幾何変換に対して、Aspose.Imaging.Matrix クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [TYPE_FLIP](#TYPE-FLIP) | このフラグビットは、このオブジェクトで定義された変換が、他のフラグビットが示す変換に加えて、通常の右手座標系を左手座標系に変更する軸についての鏡像反転を行うことを示します。 |
| [TYPE_GENERAL_ROTATION](#TYPE-GENERAL-ROTATION) | このフラグビットは、このオブジェクトで定義された変換が、他のフラグビットで示される変換に加えて、任意の角度による回転を行うことを示します。 |
| [TYPE_GENERAL_SCALE](#TYPE-GENERAL-SCALE) | 一般的なスケールは、直交ベクトル間の角度を変えずに、x方向と y方向で異なる量だけベクトルの長さを乗算します。 |
| [TYPE_GENERAL_TRANSFORM](#TYPE-GENERAL-TRANSFORM) | この定数は、このオブジェクトで定義された変換が入力座標の任意の変換を行うことを示します。 |
| [TYPE_IDENTITY](#TYPE-IDENTITY) | 単位変換とは、出力座標が常に入力座標と同じになる変換です。 |
| [TYPE_MASK_ROTATION](#TYPE-MASK-ROTATION) | この定数は、回転フラグビットのいずれかのビットマスクです。 |
| [TYPE_MASK_SCALE](#TYPE-MASK-SCALE) | この定数は、スケールフラグビットのいずれかのビットマスクです。 |
| [TYPE_QUADRANT_ROTATION](#TYPE-QUADRANT-ROTATION) | このフラグビットは、このオブジェクトで定義された変換が、他のフラグビットで示される変換に加えて、90度の倍数による象限回転を行うことを示します。 |
| [TYPE_TRANSLATION](#TYPE-TRANSLATION) | 平行移動は、ベクトルの長さや角度を変えずに、x と y 方向に一定量だけ座標を移動させます。 |
| [TYPE_UNIFORM_SCALE](#TYPE-UNIFORM-SCALE) | 均一スケールは、ベクトル間の角度を変えずに、x と y の両方向で同じ量だけベクトルの長さを乗算します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 指定された  System.Object  がこのインスタンスと等しいかどうかを判断します。 |
| [getClass()](#getClass--) |  |
| [getElements()](#getElements--) | 行列要素のコピーを取得します。 |
| [getM11()](#getM11--) | 第1行第1列の行列要素を取得します。 |
| [getM12()](#getM12--) | 第1行第2列の行列要素を取得します。 |
| [getM21()](#getM21--) | 第2行第1列の行列要素を取得します。 |
| [getM22()](#getM22--) | 第2行第2列の行列要素を取得します。 |
| [getM31()](#getM31--) | 第3行第1列の行列要素を取得します。 |
| [getM32()](#getM32--) | 第3行第1列の行列要素を取得します。 |
| [hashCode()](#hashCode--) | このインスタンスのハッシュコードを返します。 |
| [isEquals(Matrix a, Matrix b)](#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-) | 2つの行列が等しいかどうかを判定します。 |
| [isIdentity()](#isIdentity--) | `AffineTransform` が単位変換である場合、`true` を返します。 |
| [multiply(Matrix Tx)](#multiply-com.aspose.psd.Matrix-) | この Matrix を、matrix パラメーターで指定された行列で、（デフォルトの）Prepend 順序を使用して乗算します。 |
| [multiply(Matrix Tx, int order)](#multiply-com.aspose.psd.Matrix-int-) | この Matrix を、matrix パラメーターで指定された行列で、order パラメーターで指定された順序で乗算します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | この Matrix を単位行列の要素にリセットします。 |
| [rotate(float angle)](#rotate-float-) | この Matrix に対して、角度パラメーターで指定された量の時計回り回転を、原点（x と y が 0 の座標）を中心に、デフォルト（Prepend）順序で適用します。 |
| [rotate(float angle, int order)](#rotate-float-int-) | この Matrix に対して、角度パラメーターで指定された量の時計回り回転を、原点（x と y が 0 の座標）を中心に、指定された順序で適用します。 |
| [rotateAt(float angle, PointF point)](#rotateAt-float-com.aspose.psd.PointF-) | 指定された点を中心に時計回り回転を、この Matrix に対してデフォルト（Prepend）順序で適用します。 |
| [rotateAt(float angle, PointF point, int order)](#rotateAt-float-com.aspose.psd.PointF-int-) | 指定された点を中心に時計回り回転を、この Matrix に対して指定された順序で適用します。 |
| [scale(float sx, float sy)](#scale-float-float-) | 指定されたスケールベクトル（scaleX と scaleY）を、この Matrix に対して（デフォルトの）Prepend 順序で適用します。 |
| [scale(float scaleX, float scaleY, int order)](#scale-float-float-int-) | 指定されたスケールベクトル（scaleX と scaleY）をこの Matrix に、指定された順序で適用します。 |
| [toString()](#toString--) | このインスタンスを表す  System.String  を返します。 |
| [transformPoints(PointF[] points)](#transformPoints-com.aspose.psd.PointF---) | この Matrix が表す幾何変換を、指定された点の配列に適用します。 |
| [translate(float tx, float ty)](#translate-float-float-) | 指定された平行移動ベクトルを、この Matrix に (デフォルト) Prepend 順序で適用します。 |
| [translate(float offsetX, float offsetY, int order)](#translate-float-float-int-) | 指定された平行移動ベクトルを、この Matrix に指定された順序で適用します。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Matrix() {#Matrix--}
```
public Matrix()
```


Matrix クラスの新しいインスタンスを単位行列として初期化します。

### Matrix(float m11, float m12, float m21, float m22, float m31, float m32) {#Matrix-float-float-float-float-float-float-}
```
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```


Matrix クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| m11 | float | m00 M11 Scale X |
| m12 | float | m10 M12 Shear Y |
| m21 | float | m01 M21 Shear X |
| m22 | float | m11 M22 Scale Y |
| m31 | float | m02 M31 Translate X |
| m32 | float | m12 M32 Translate Y |

### Matrix(Matrix origin) {#Matrix-com.aspose.psd.Matrix-}
```
public Matrix(Matrix origin)
```


Matrix クラスのコピーを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| origin | [Matrix](../../com.aspose.psd/matrix) | コーピング用の基本行列 |

### Matrix(RectangleF rect, PointF[] plgpts) {#Matrix-com.aspose.psd.RectangleF-com.aspose.psd.PointF---}
```
public Matrix(RectangleF rect, PointF[] plgpts)
```


指定された矩形と点の配列で定義された幾何変換に対して、Aspose.Imaging.Matrix クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.psd/rectanglef) | 変換される矩形を表す Aspose.Imaging.RectangleF 構造体です。 |
| plgpts | [PointF\[\]](../../com.aspose.psd/pointf) | 矩形の左上、右上、左下の各コーナーが変換される平行四辺形の点を表す、3 つの Aspose.Imaging.PointF 構造体の配列です。平行四辺形の右下コーナーは、最初の 3 つのコーナーから暗黙的に決定されます。 |

### Matrix(Rectangle rect, Point[] plgpts) {#Matrix-com.aspose.psd.Rectangle-com.aspose.psd.Point---}
```
public Matrix(Rectangle rect, Point[] plgpts)
```


指定された矩形と点の配列で定義された幾何変換に対して、Aspose.Imaging.Matrix クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | 変換される矩形を表す Aspose.Imaging.Rectangle 構造体です。 |
| plgpts | [Point\[\]](../../com.aspose.psd/point) | 矩形の左上、右上、左下の各コーナーが変換される平行四辺形の点を表す、3 つの Aspose.Imaging.Point 構造体の配列です。平行四辺形の右下コーナーは、最初の 3 つのコーナーから暗黙的に決定されます。 |

### TYPE_FLIP {#TYPE-FLIP}
```
public static final int TYPE_FLIP
```


このフラグビットは、このオブジェクトで定義された変換が、他のフラグビットが示す変換に加えて、ある軸を中心とした鏡像反転を行い、通常の右手系座標系を左手系に変換することを示します。右手系座標系とは、正の X 軸が反時計回りに回転して正の Y 軸上に重なる系で、右手の親指を前に向けたときに指が巻きつく方向に相当します。左手系座標系とは、正の X 軸が時計回りに回転して正の Y 軸上に重なる系で、左手の親指を前に向けたときに指が巻きつく方向に相当します。適切な調整回転があれば、すべての反転角度は同一になるため、元の反転または鏡像変換の角度を数学的に求める方法はありません。NOTE: TypeFlip は GENERAL\_TRANSFORM が公開された後に追加されたため、フラグビットを外部コードとのバイナリ互換性を損なうことなく便利に番号付けし直すことができなくなりました。

### TYPE_GENERAL_ROTATION {#TYPE-GENERAL-ROTATION}
```
public static final int TYPE_GENERAL_ROTATION
```


このフラグビットは、このオブジェクトで定義された変換が、他のフラグビットが示す変換に加えて、任意の角度で回転を行うことを示します。回転はベクトルの元の方向に関係なく、ベクトルの長さを変えずに同じ量だけ角度を変えます。このフラグビットは、

### TYPE_GENERAL_SCALE {#TYPE-GENERAL-SCALE}
```
public static final int TYPE_GENERAL_SCALE
```


一般的なスケールは、ベクトルの長さを x 方向と y 方向で異なる倍率で拡大・縮小し、垂直ベクトル間の角度は変えません。このフラグビットは TypeUniformScale フラグと相互に排他的です。

### TYPE_GENERAL_TRANSFORM {#TYPE-GENERAL-TRANSFORM}
```
public static final int TYPE_GENERAL_TRANSFORM
```


この定数は、このオブジェクトで定義された変換が入力座標の任意の変換を行うことを示します。上記の定数のいずれかでこの変換を分類できる場合、タイプは定数 TypeIdentity になるか、またはこの変換が実行するさまざまな座標変換に対応するフラグビットの組み合わせになります。

### TYPE_IDENTITY {#TYPE-IDENTITY}
```
public static final int TYPE_IDENTITY
```


恒等変換とは、出力座標が常に入力座標と同じである変換です。この変換が恒等変換以外の場合、タイプは定数 GENERAL\_TRANSFORM になるか、またはこの変換が実行するさまざまな座標変換のための適切なフラグビットの組み合わせになります。

### TYPE_MASK_ROTATION {#TYPE-MASK-ROTATION}
```
public static final int TYPE_MASK_ROTATION
```


この定数は、回転フラグビットのいずれかのビットマスクです。

### TYPE_MASK_SCALE {#TYPE-MASK-SCALE}
```
public static final int TYPE_MASK_SCALE
```


この定数は、スケールフラグビットのいずれかのビットマスクです。

### TYPE_QUADRANT_ROTATION {#TYPE-QUADRANT-ROTATION}
```
public static final int TYPE_QUADRANT_ROTATION
```


このフラグビットは、このオブジェクトで定義された変換が、他のフラグビットで示される変換に加えて、90度の倍数による象限回転を行うことを示します。回転はベクトルの元の方向に関係なく、ベクトルの長さを変えずに同じ量だけベクトルの角度を変えます。このフラグビットは TypeGeneralRotation フラグと相互に排他的です。

### TYPE_TRANSLATION {#TYPE-TRANSLATION}
```
public static final int TYPE_TRANSLATION
```


平行移動は、ベクトルの長さや角度を変えずに、x と y 方向に一定量だけ座標を移動させます。

### TYPE_UNIFORM_SCALE {#TYPE-UNIFORM-SCALE}
```
public static final int TYPE_UNIFORM_SCALE
```


一様スケールは、ベクトル間の角度を変えずに、x方向と y方向の両方でベクトルの長さを同じ量だけ乗算します。このフラグビットは TypeGeneralScale フラグと相互に排他的です。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指定された  System.Object  がこのインスタンスと等しいかどうかを判断します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object | このインスタンスと比較する System.Object。 |

**Returns:**
boolean - この指定された System.Object がこのインスタンスと等しい場合は true、そうでない場合は false。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getElements() {#getElements--}
```
public float[] getElements()
```


行列要素のコピーを取得します。

**Returns:**
float[] - 行列要素のコピー。
### getM11() {#getM11--}
```
public float getM11()
```


最初の行最初の列の行列要素を取得します。X 軸方向のスケールを表します。

**Returns:**
float
### getM12() {#getM12--}
```
public float getM12()
```


最初の行第2列の行列要素を取得します。Y 軸方向のせん断を表します。

**Returns:**
float
### getM21() {#getM21--}
```
public float getM21()
```


第2行第1列の行列要素を取得します。X 軸方向のせん断を表します。

**Returns:**
float
### getM22() {#getM22--}
```
public float getM22()
```


第2行第2列の行列要素を取得します。Y 軸方向のスケールを表します。

**Returns:**
float
### getM31() {#getM31--}
```
public float getM31()
```


第3行第1列の行列要素を取得します。X 軸方向の平行移動を表します。

**Returns:**
float
### getM32() {#getM32--}
```
public float getM32()
```


第3行第1列の行列要素を取得します。Y 軸方向の平行移動を表します。

**Returns:**
float
### hashCode() {#hashCode--}
```
public int hashCode()
```


このインスタンスのハッシュコードを返します。

**Returns:**
int - このインスタンスのハッシュコード。ハッシュアルゴリズムやハッシュテーブルのようなデータ構造での使用に適しています。
### isEquals(Matrix a, Matrix b) {#isEquals-com.aspose.psd.Matrix-com.aspose.psd.Matrix-}
```
public static boolean isEquals(Matrix a, Matrix b)
```


2つの行列が等しいかどうかを判定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| a | [Matrix](../../com.aspose.psd/matrix) | 比較対象の最初の行列。 |
| b | [Matrix](../../com.aspose.psd/matrix) | 比較対象の2番目の行列。 |

**Returns:**
boolean - 行列が等しい場合は True。
### isIdentity() {#isIdentity--}
```
public boolean isIdentity()
```


`AffineTransform` が単位変換である場合、`true` を返します。

**Returns:**
boolean - `true` この `AffineTransform` が恒等変換の場合; それ以外は `false`。
### multiply(Matrix Tx) {#multiply-com.aspose.psd.Matrix-}
```
public void multiply(Matrix Tx)
```


この Matrix を、matrix パラメーターで指定された行列で、（デフォルトの）Prepend 順序を使用して乗算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | 掛け合わせる行列。 |

### multiply(Matrix Tx, int order) {#multiply-com.aspose.psd.Matrix-int-}
```
public void multiply(Matrix Tx, int order)
```


この Matrix を、matrix パラメーターで指定された行列で、order パラメーターで指定された順序で乗算します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| Tx | [Matrix](../../com.aspose.psd/matrix) | tx。 tx。 tx。 |
| order | int | 順序。 順序。 順序。 |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public void reset()
```


この Matrix を単位行列の要素にリセットします。

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


この Matrix に対して、角度パラメーターで指定された量の時計回り回転を、原点（x と y が 0 の座標）を中心に、デフォルト（Prepend）順序で適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転角度。 |

### rotate(float angle, int order) {#rotate-float-int-}
```
public void rotate(float angle, int order)
```


この Matrix に対して、角度パラメーターで指定された量の時計回り回転を、原点（x と y が 0 の座標）を中心に、指定された順序で適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 回転角度。 |
| order | int | 行列の順序。 |

### rotateAt(float angle, PointF point) {#rotateAt-float-com.aspose.psd.PointF-}
```
public void rotateAt(float angle, PointF point)
```


指定された点を中心に時計回り回転を、この Matrix に対してデフォルト（Prepend）順序で適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 角度。 |
| point | [PointF](../../com.aspose.psd/pointf) | ポイントです。 |

### rotateAt(float angle, PointF point, int order) {#rotateAt-float-com.aspose.psd.PointF-int-}
```
public void rotateAt(float angle, PointF point, int order)
```


指定された点を中心に時計回り回転を、この Matrix に対して指定された順序で適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 角度 | float | 角度。 |
| point | [PointF](../../com.aspose.psd/pointf) | ポイントです。 |
| order | int | 順序。 |

### scale(float sx, float sy) {#scale-float-float-}
```
public void scale(float sx, float sy)
```


指定されたスケールベクトル（scaleX と scaleY）を、この Matrix に対して（デフォルトの）Prepend 順序で適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sx | float | sx。 sx。 sx。 |
| sy | float | sy。 sy。 sy。 |

### scale(float scaleX, float scaleY, int order) {#scale-float-float-int-}
```
public void scale(float scaleX, float scaleY, int order)
```


指定されたスケールベクトル（scaleX と scaleY）をこの Matrix に、指定された順序で適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| scaleX | float | X スケール。 |
| scaleY | float | Y スケール。 |
| order | int | 順序。 |

### toString() {#toString--}
```
public String toString()
```


このインスタンスを表す  System.String  を返します。

**Returns:**
java.lang.String - このインスタンスを表す System.String。
### transformPoints(PointF[] points) {#transformPoints-com.aspose.psd.PointF---}
```
public void transformPoints(PointF[] points)
```


この Matrix が表す幾何変換を、指定された点の配列に適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.psd/pointf) | 点。 |

### translate(float tx, float ty) {#translate-float-float-}
```
public void translate(float tx, float ty)
```


指定された平行移動ベクトルを、この Matrix に (デフォルト) Prepend 順序で適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| tx | float | tx。 tx。 tx。 |
| ty | float | その ty. その ty. その ty. |

### translate(float offsetX, float offsetY, int order) {#translate-float-float-int-}
```
public void translate(float offsetX, float offsetY, int order)
```


指定された平行移動ベクトルを、この Matrix に指定された順序で適用します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| offsetX | float | オフセット Xです。 |
| offsetY | float | オフセット Yです。 |
| order | int | 順序。 |

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

