---
title: "GraphicsPath.Warp"
second_title: "Aspose.PSD for .NET API Reference"
description: "GraphicsPath メソッド。矩形と平行四辺形で定義されたワープ変換をこの GraphicsPath に適用します。"
type: docs
weight: 180
url: /ja/net/aspose.psd/graphicspath/warp/
---
{{< psd/tize >}}
## Warp(PointF[], RectangleF) {#warp}

矩形と平行四辺形で定義されたワープ変換をこの[`GraphicsPath`](../)に適用します。

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| destPoints | PointF[] | `*srcRect*`で定義された矩形が変換される平行四辺形を定義する[`PointF`](../../pointf/)構造体の配列です。配列は 3 要素または 4 要素を含めることができます。配列が 3 要素の場合、平行四辺形の右下隅は最初の 3 点から暗黙的に決定されます。 |
| srcRect | RectangleF | `*destPoints*`で定義された平行四辺形に変換される矩形を表す[`RectangleF`](../../rectanglef/)です。 |

### 関連項目

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

矩形と平行四辺形で定義されたワープ変換をこの[`GraphicsPath`](../)に適用します。

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| destPoints | PointF[] | `*srcRect*`で定義された矩形が変換される平行四辺形を定義する[`PointF`](../../pointf/)構造体の配列です。配列は 3 要素または 4 要素を含めることができます。配列が 3 要素の場合、平行四辺形の右下隅は最初の 3 点から暗黙的に決定されます。 |
| srcRect | RectangleF | `*destPoints*`で定義された平行四辺形に変換される矩形を表す[`RectangleF`](../../rectanglef/)です。 |
| matrix | Matrix | パスに適用する幾何変換を指定する[`Matrix`](../../matrix/)です。 |

### 関連項目

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

矩形と平行四辺形で定義されたワープ変換をこの[`GraphicsPath`](../)に適用します。

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| destPoints | PointF[] | `*srcRect*`で定義された矩形が変換される平行四辺形を定義する[`PointF`](../../pointf/)構造体の配列です。配列は 3 要素または 4 要素を含めることができます。配列が 3 要素の場合、平行四辺形の右下隅は最初の 3 点から暗黙的に決定されます。 |
| srcRect | RectangleF | `*destPoints*`で定義された平行四辺形に変換される矩形を表す[`RectangleF`](../../rectanglef/)です。 |
| matrix | Matrix | パスに適用する幾何変換を指定する[`Matrix`](../../matrix/)です。 |
| warpMode | WarpMode | このワープ操作が透視投影モードまたは双一次モードのどちらを使用するかを指定する[`WarpMode`](../../warpmode/)列挙体です。 |

### 関連項目

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

矩形と平行四辺形で定義されたワープ変換をこの[`GraphicsPath`](../)に適用します。

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| destPoints | PointF[] | `*srcRect*`で定義された矩形が変換される平行四辺形を定義する[`PointF`](../../pointf/)構造体の配列です。配列は 3 要素または 4 要素を含めることができます。配列が 3 要素の場合、平行四辺形の右下隅は最初の 3 点から暗黙的に決定されます。 |
| srcRect | RectangleF | `*destPoints*`で定義された平行四辺形に変換される矩形を表す[`RectangleF`](../../rectanglef/)です。 |
| matrix | Matrix | パスに適用する幾何変換を指定する[`Matrix`](../../matrix/)です。 |
| warpMode | WarpMode | このワープ操作が透視投影モードまたは双一次モードのどちらを使用するかを指定する[`WarpMode`](../../warpmode/)列挙体です。 |
| flatness | Single | 結果のパスがどれだけ平坦であるかを指定する 0 から 1 までの値です。詳細については、[`Flatten`](../flatten/) メソッドをご参照ください。 |

### 関連項目

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


