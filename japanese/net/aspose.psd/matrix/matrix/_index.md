---
title: Matrix.Matrix
second_title: Aspose.PSD for .NET API リファレンス
description: Matrix コンストラクタ. Matrix クラスの新しいインスタンスを単位行列として初期化します
type: docs
weight: 10
url: /ja/net/aspose.psd/matrix/matrix/
---
## Matrix() {#constructor}

Matrix クラスの新しいインスタンスを単位行列として初期化します。

```csharp
public Matrix()
```

### 関連項目

* class [Matrix](../)
* 名前空間 [Aspose.PSD](../../matrix/)
* 組み立て [Aspose.PSD](../../../)

---

## Matrix(float, float, float, float, float, float) {#constructor_4}

の新しいインスタンスを初期化します[`Matrix`](../)class.

```csharp
public Matrix(float m11, float m12, float m21, float m22, float m31, float m32)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| m11 | Single | m00 M11 スケール X |
| m12 | Single | m10 M12 せん断 Y |
| m21 | Single | m01 M21 せん断 X |
| m22 | Single | m11 M22 スケールY |
| m31 | Single | m02 M31 翻訳 X |
| m32 | Single | m12 M32 移動 Y |

### 関連項目

* class [Matrix](../)
* 名前空間 [Aspose.PSD](../../matrix/)
* 組み立て [Aspose.PSD](../../../)

---

## Matrix(RectangleF, PointF[]) {#constructor_3}

の新しいインスタンスを初期化します[`Matrix`](../)指定された長方形と点の配列によって定義される幾何学的変換へのクラス.

```csharp
public Matrix(RectangleF rect, PointF[] plgpts)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| rect | RectangleF | あ[`RectangleF`](../../rectanglef/)変換する四角形を表す構造体。 |
| plgpts | PointF[] | 3 つの配列[`PointF`](../../pointf/)四角形の左上隅、右上隅、左下隅が変換される平行四辺形の点を表す構造体。平行四辺形の右下隅は、最初の 3 つの隅によって暗示されます。 |

### 関連項目

* struct [RectangleF](../../rectanglef/)
* struct [PointF](../../pointf/)
* class [Matrix](../)
* 名前空間 [Aspose.PSD](../../matrix/)
* 組み立て [Aspose.PSD](../../../)

---

## Matrix(Rectangle, Point[]) {#constructor_2}

の新しいインスタンスを初期化します[`Matrix`](../)指定された長方形と点の配列によって定義される幾何学的変換へのクラス.

```csharp
public Matrix(Rectangle rect, Point[] plgpts)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| rect | Rectangle | あ[`Rectangle`](../../rectangle/)変換する四角形を表す構造体。 |
| plgpts | Point[] | 3 つの配列[`Point`](../../point/)四角形の左上隅、右上隅、左下隅が変換される平行四辺形の点を表す構造体。平行四辺形の右下隅は、最初の 3 つの隅によって暗示されます。 |

### 関連項目

* struct [Rectangle](../../rectangle/)
* struct [Point](../../point/)
* class [Matrix](../)
* 名前空間 [Aspose.PSD](../../matrix/)
* 組み立て [Aspose.PSD](../../../)

---

## Matrix(Matrix) {#constructor_1}

のコピーを作成します[`Matrix`](../)class.

```csharp
public Matrix(Matrix origin)
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| origin | Matrix | 対処の基本マトリックス |

### 関連項目

* class [Matrix](../)
* 名前空間 [Aspose.PSD](../../matrix/)
* 組み立て [Aspose.PSD](../../../)


