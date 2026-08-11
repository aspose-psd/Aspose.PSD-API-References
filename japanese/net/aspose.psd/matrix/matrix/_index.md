---
title: "Matrix.Matrix"
second_title: "Aspose.PSD for .NET API Reference"
description: "Matrix コンストラクタ。 Matrix クラスの新しいインスタンスを単位行列として初期化します。"
type: docs
weight: 10
url: /ja/net/aspose.psd/matrix/matrix/
---
{{< psd/tize >}}
## Matrix() {#constructor}

Matrix クラスの新しいインスタンスを単位行列として初期化します。

```csharp
public Matrix()
```

### 関連項目

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(float, float, float, float, float, float) {#constructor_4}

`[`Matrix`](../)` クラスの新しいインスタンスを初期化します。

```csharp
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| m11 | シングル | m00 M11 スケール X |
| m12 | シングル | m10 M12 シアー Y |
| m21 | シングル | m01 M21 シアー X |
| m22 | シングル | m11 M22 Y方向スケール |
| m31 | シングル | m02 M31 X方向平行移動 |
| m32 | シングル | m12 M32 Y方向平行移動 |

### 関連項目

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(RectangleF, PointF[]) {#constructor_3}

指定された矩形と点の配列で定義された幾何変換に対して、[`Matrix`](../) クラスの新しいインスタンスを初期化します。

```csharp
public Matrix(RectangleF rect, PointF[] plgpts)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) 構造体は、変換される矩形を表します。 |
| plgpts | PointF[] | [`PointF`](../../pointf/) 構造体の 3 要素の配列で、矩形の左上、右上、左下の各角が変換される平行四辺形の点を表します。平行四辺形の右下の角は、最初の 3 つの角から暗黙的に決定されます。 |

### 関連項目

* struct [RectangleF](../../rectanglef/)
* struct [PointF](../../pointf/)
* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(Rectangle, Point[]) {#constructor_2}

指定された矩形と点の配列で定義された幾何変換に対して、[`Matrix`](../) クラスの新しいインスタンスを初期化します。

```csharp
public Matrix(Rectangle rect, Point[] plgpts)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | Rectangle | [`Rectangle`](../../rectangle/) 構造体は、変換される矩形を表します。 |
| plgpts | Point[] | [`Point`](../../point/) 構造体の 3 要素の配列で、矩形の左上、右上、左下の各角が変換される平行四辺形の点を表します。平行四辺形の右下の角は、最初の 3 つの角から暗黙的に決定されます。 |

### 関連項目

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Matrix(Matrix) {#constructor_1}

[`Matrix`](../) クラスのコピーを作成します。

```csharp
public Matrix(Matrix origin)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| origin | Matrix | コピー用のベース行列です。 |

### 関連項目

* class [Matrix](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


