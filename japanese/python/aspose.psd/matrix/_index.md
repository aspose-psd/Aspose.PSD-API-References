---
title: "Matrix クラス"
type: docs
weight: 3000
url: /ja/python-net/aspose.psd/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Matrix

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [Matrix()](#Matrix__1) | Matrix クラスの新しいインスタンスを単位行列として初期化します。 |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | [Matrix](/psd/python-net/aspose.psd/matrix/) クラスの新しいインスタンスを初期化します。 |
| [Matrix(origin)](#Matrix_origin_3) | [Matrix](/psd/python-net/aspose.psd/matrix/) クラスのコピーを作成します。 |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | [Matrix](/psd/python-net/aspose.psd/matrix/) クラスの新しいインスタンスを、指定された矩形と点の配列で定義された幾何変換に初期化します。 |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | [Matrix](/psd/python-net/aspose.psd/matrix/) クラスの新しいインスタンスを、指定された矩形と点の配列で定義された幾何変換に初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| TYPE_FLIP [static] | int | r | このフラグビットは、このオブジェクトで定義された変換が<br/>            ある軸について鏡像反転を行い、通常の右手系座標系を左手系に<br/>            変換すると同時に、他のフラグビットで示される変換も行うことを示します。<br/>            右手系座標系とは、正の X 軸が反時計回りに回転して正の Y 軸に重なる系で、<br/>            右手の親指を正面から見たときに指がカールする方向に似ています。<br/>            左手系座標系とは、正の X 軸が時計回りに回転して正の Y 軸に重なる系で、<br/>            左手の親指を正面から見たときに指がカールする方向に似ています。<br/>            適切な調整回転があれば、すべての反転角度は同一になるため、元の反転または鏡像変換の角度を数学的に求める方法はありません。<br/>            注: TypeFlip は GENERAL_TRANSFORM が公開された後に追加されたため、フラグビットを便利に再番号付けすることができず、外部コードとのバイナリ互換性が失われました。 |
| TYPE_GENERAL_ROTATION [static] | int | r | このフラグビットは、このオブジェクトで定義された変換が<br/>            任意の角度で回転を行い、他のフラグビットで示される変換も併せて行うことを示します。<br/>            回転はベクトルの元の方向に関係なく、ベクトルの角度を同じ量だけ変え、ベクトルの長さは変えません。<br/>            このフラグビットは、 |
| TYPE_GENERAL_SCALE [static] | int | r | 一般的なスケールは、ベクトルの長さを x 方向と y 方向で異なる量だけ乗算し、直交ベクトル間の角度は変えません。<br/>            このフラグビットは、TypeUniformScale フラグと相互排他的です。 |
| TYPE_GENERAL_TRANSFORM [static] | int | r | この定数は、このオブジェクトで定義された変換が入力座標の任意の変換を行うことを示します。<br/>            この変換が上記のいずれかの定数で分類できる場合、タイプは定数 TypeIdentity になるか、またはこの変換が実行するさまざまな座標変換に対応する適切なフラグビットの組み合わせになります。 |
| TYPE_IDENTITY [static] | int | r | 恒等変換とは、出力座標が常に入力座標と同じである変換です。<br/>            この変換が恒等変換以外である場合、タイプは定数 GENERAL_TRANSFORM になるか、またはこの変換が実行するさまざまな座標変換に対応する適切なフラグビットの組み合わせになります。 |
| TYPE_MASK_ROTATION [static] | int | r | この定数は、回転フラグビットのいずれかに対するビットマスクです。 |
| TYPE_MASK_SCALE [static] | int | r | この定数は、スケールフラグビットのいずれかに対するビットマスクです。 |
| TYPE_QUADRANT_ROTATION [static] | int | r | このフラグビットは、このオブジェクトで定義された変換が<br/>            他のフラグビットで示される変換に加えて、90 度の倍数による象限回転を行うことを示します。<br/>            回転はベクトルの元の方向に関係なく、ベクトルの角度を同じ量だけ変え、ベクトルの長さは変えません。<br/>            このフラグビットは、TypeGeneralRotation フラグと相互排他的です。 |
| TYPE_TRANSLATION [static] | int | r | 平行移動は、ベクトルの長さや角度を変えずに、x と y の方向に一定量だけ座標を移動させます。 |
| TYPE_UNIFORM_SCALE [static] | int | r | 均一スケールは、ベクトルの長さを x 方向と y 方向の両方で同じ量だけ乗算し、ベクトル間の角度は変えません。<br/>            このフラグビットは、TypeGeneralScale フラグと相互排他的です。 |
| elements | float | r | この [Matrix](/psd/python-net/aspose.psd/matrix/) の要素を表す浮動小数点値の配列を取得します。 |
| m11 | float | r | 第一行第一列の行列要素を取得します。X 軸方向のスケールを表します。 |
| m12 | float | r | 第一行第二列の行列要素を取得します。Y 軸方向のせん断を表します。 |
| m21 | float | r | 第2行第1列の行列要素を取得します。X 軸に沿ったせん断を表します。 |
| m22 | float | r | 第2行第2列の行列要素を取得します。Y 軸に沿ったスケールを表します。 |
| m31 | float | r | 第3行第1列の行列要素を取得します。X 軸への平行移動を表します。 |
| m32 | float | r | 第3行第1列の行列要素を取得します。Y 軸への平行移動を表します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_elements()](#get_elements__1) | 行列要素のコピーを取得します。 |
| [multiply(tx)](#multiply_tx_2) | この Matrix を、matrix パラメーターで指定された行列で、（デフォルト）Prepend 順序を使用して乗算します。 |
| [multiply(tx, order)](#multiply_tx_order_3) | この Matrix を、matrix パラメーターで指定された行列で、order パラメーターで指定された順序で乗算します。 |
| reset() | この Matrix を単位行列の要素にリセットします。 |
| [rotate(angle)](#rotate_angle_4) | この Matrix に対し、角度パラメーターで指定された量の時計回り回転を、原点（x と y のゼロ座標）を中心に、デフォルト（Prepend）順序で適用します。 |
| [rotate(angle, order)](#rotate_angle_order_5) | この Matrix に対し、角度パラメーターで指定された量の時計回り回転を、原点（x と y のゼロ座標）を中心に、指定された順序で適用します。 |
| [rotate_at(angle, point)](#rotate_at_angle_point_6) | 指定された点を中心に、この Matrix に時計回り回転を、デフォルト（Prepend）順序で適用します。 |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_7) | 指定された点を中心に、この Matrix に時計回り回転を、指定された順序で適用します。 |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_8) | 指定されたスケールベクトル（scaleX と scaleY）を、この [Matrix](/psd/python-net/aspose.psd/matrix/) に、指定された順序で適用します。 |
| [scale(sx, sy)](#scale_sx_sy_9) | 指定されたスケールベクトル（scaleX と scaleY）を、この Matrix に、（デフォルト）Prepend 順序で適用します。 |
| [transform_points(points)](#transform_points_points_10) | この [Matrix](/psd/python-net/aspose.psd/matrix/) が表す幾何変換を、指定された点の配列に適用します。 |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_11) | 指定された平行移動ベクトルを、この Matrix に、指定された順序で適用します。 |
| [translate(tx, ty)](#translate_tx_ty_12) | 指定された平行移動ベクトルを、この [Matrix](/psd/python-net/aspose.psd/matrix/) に、（デフォルト）Prepend 順序で適用します。 |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

Matrix クラスの新しいインスタンスを単位行列として初期化します。

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

[Matrix](/psd/python-net/aspose.psd/matrix/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| m11 | float | m00     M11     スケール X |
| m12 | float | m10     M12     シアー Y |
| m21 | float | m01     M21     シアー X |
| m22 | float | m11     M22     スケール Y |
| m31 | float | m02     M31     平行移動 X |
| m32 | float | m12     M32     Y 転送 |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

[Matrix](/psd/python-net/aspose.psd/matrix/) クラスのコピーを作成します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| origin | [Matrix](/psd/python-net/aspose.psd/matrix) | コーピング用の基本行列 |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

[Matrix](/psd/python-net/aspose.psd/matrix/) クラスの新しいインスタンスを、指定された矩形と点の配列で定義された幾何変換に初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | 変換される矩形を表す [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体。 |
| plgpts | [PointF[]](/psd/python-net/aspose.psd/pointf) | 上左、上右、左下の角が変換される平行四辺形の点を表す 3 つの [PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列。平行四辺形の右下の角は最初の 3 つの角から暗黙的に決定されます。 |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

[Matrix](/psd/python-net/aspose.psd/matrix/) クラスの新しいインスタンスを、指定された矩形と点の配列で定義された幾何変換に初期化します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 変換される矩形を表す [RectangleF](/psd/python-net/aspose.psd/rectanglef/) 構造体。 |
| plgpts | [Point[]](/psd/python-net/aspose.psd/point) | 上左、上右、左下の角が変換される平行四辺形の点を表す 3 つの [PointF](/psd/python-net/aspose.psd/pointf/) 構造体の配列。平行四辺形の右下の角は最初の 3 つの角から暗黙的に決定されます。 |

### Method: get_elements() {#get_elements__1}


```
 get_elements() 
```

行列要素のコピーを取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| float | 行列要素のコピー。 |


### Method: multiply(tx) {#multiply_tx_2}


```
 multiply(tx) 
```

この Matrix を、matrix パラメーターで指定された行列で、（デフォルト）Prepend 順序を使用して乗算します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | 掛け算に使用する行列。 |

### Method: multiply(tx, order) {#multiply_tx_order_3}


```
 multiply(tx, order) 
```

この Matrix を、matrix パラメーターで指定された行列で、order パラメーターで指定された順序で乗算します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | tx。 tx。 tx。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 順序。 順序。 順序。 |

### Method: rotate(angle) {#rotate_angle_4}


```
 rotate(angle) 
```

この Matrix に対し、角度パラメーターで指定された量の時計回り回転を、原点（x と y のゼロ座標）を中心に、デフォルト（Prepend）順序で適用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 角度 | float | 回転角度。 |

### Method: rotate(angle, order) {#rotate_angle_order_5}


```
 rotate(angle, order) 
```

この Matrix に対し、角度パラメーターで指定された量の時計回り回転を、原点（x と y のゼロ座標）を中心に、指定された順序で適用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 角度 | float | 回転角度。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 行列の順序。 |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_6}


```
 rotate_at(angle, point) 
```

指定された点を中心に、この Matrix に時計回り回転を、デフォルト（Prepend）順序で適用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 角度 | float | 角度。 |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | ポイントです。 |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_7}


```
 rotate_at(angle, point, order) 
```

指定された点を中心に、この Matrix に時計回り回転を、指定された順序で適用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| 角度 | float | 角度。 |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | ポイントです。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 順序。 |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_8}


```
 scale(scale_x, scale_y, order) 
```

指定されたスケールベクトル（scaleX と scaleY）を、この [Matrix](/psd/python-net/aspose.psd/matrix/) に、指定された順序で適用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| scale_x | float | スケール X。 |
| scale_y | float | スケール Y。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 順序。 |

### Method: scale(sx, sy) {#scale_sx_sy_9}


```
 scale(sx, sy) 
```

指定されたスケールベクトル（scaleX と scaleY）を、この Matrix に、（デフォルト）Prepend 順序で適用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| sx | float | sx。 sx。 sx。 |
| sy | float | sy。 sy。 sy。 |

### Method: transform_points(points) {#transform_points_points_10}


```
 transform_points(points) 
```

この [Matrix](/psd/python-net/aspose.psd/matrix/) が表す幾何変換を、指定された点の配列に適用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | 点。 |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_11}


```
 translate(offset_x, offset_y, order) 
```

指定された平行移動ベクトルを、この Matrix に、指定された順序で適用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| offset_x | float | オフセット X。 |
| offset_y | float | オフセット Y。 |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | 順序。 |

### Method: translate(tx, ty) {#translate_tx_ty_12}


```
 translate(tx, ty) 
```

指定された平行移動ベクトルを、この [Matrix](/psd/python-net/aspose.psd/matrix/) に、（デフォルト）Prepend 順序で適用します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| tx | float | tx。 tx。 tx。 |
| ty | float | ty。 ty。 ty。 |

