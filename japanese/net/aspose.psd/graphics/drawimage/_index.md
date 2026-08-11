---
title: "Graphics.DrawImage"
second_title: "Aspose.PSD for .NET API Reference"
description: "Graphics メソッド。指定された場所に、元の実際のサイズで指定された Image を描画します。"
type: docs
weight: 230
url: /ja/net/aspose.psd/graphics/drawimage/
---
{{< psd/tize >}}
## DrawImage(Image, PointF) {#drawimage_1}

指定された場所に、元の実際のサイズで指定された [`Image`](../image/) を描画します。

```csharp
public void DrawImage(Image sourceImage, PointF point)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | Image | 描画に使用する画像です。 |
| point | PointF | 描画された画像の左上隅を表す [`PointF`](../../pointf/) 構造体。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* は null です。 |

### 関連項目

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, float, float) {#drawimage_22}

指定された場所に、元の実際のサイズで指定された [`Image`](../image/) を描画します。

```csharp
public void DrawImage(Image sourceImage, float x, float y)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | Image | 描画に使用する画像です。 |
| x | シングル | 描画された画像の左上隅の x 座標です。 |
| y | シングル | 描画された画像の左上隅の y 座標です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* は null です。 |

### 関連項目

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF) {#drawimage_15}

指定された場所と指定されたサイズで指定された [`Image`](../image/) を描画します。

```csharp
public void DrawImage(Image sourceImage, RectangleF rect)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | Image | 描画に使用する画像です。 |
| rect | RectangleF | 描画された画像の位置とサイズを指定する [`RectangleF`](../../rectanglef/) 構造体。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* は null です。 |

### 関連項目

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle, GraphicsUnit) {#drawimage_11}

指定された場所と指定されたサイズで指定された [`Image`](../image/) を描画します。

```csharp
public void DrawImage(Image sourceImage, Rectangle rectDestination, GraphicsUnit graphicsUnit)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | Image | 描画に使用する画像です。 |
| rectDestination | Rectangle | 目的地の矩形です。 |
| graphicsUnit | GraphicsUnit | グラフィックス単位です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* は null です。 |

### 関連項目

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF, GraphicsUnit) {#drawimage_16}

指定された場所と指定されたサイズで指定された [`Image`](../image/) を描画します。

```csharp
public void DrawImage(Image sourceImage, RectangleF rectDestination, GraphicsUnit graphicsUnit)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | Image | 描画に使用する画像です。 |
| rectDestination | RectangleF | 目的地の矩形です。 |
| graphicsUnit | GraphicsUnit | グラフィックス単位です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* は null です。 |

### 関連項目

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle, GraphicsUnit, ImageAttributes) {#drawimage_12}

指定された場所と指定されたサイズで指定された [`Image`](../image/) を描画します。

```csharp
public void DrawImage(Image sourceImage, Rectangle rectDestination, GraphicsUnit graphicsUnit, 
    ImageAttributes imageAttributes)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | Image | 描画に使用する画像です。 |
| rectDestination | Rectangle | 目的地の矩形です。 |
| graphicsUnit | GraphicsUnit | グラフィックス単位です。 |
| imageAttributes | ImageAttributes | 画像属性です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* は null です。 |

### 関連項目

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF, GraphicsUnit, ImageAttributes) {#drawimage_17}

指定された場所と指定されたサイズで指定された [`Image`](../image/) を描画します。

```csharp
public void DrawImage(Image sourceImage, RectangleF rectDestination, GraphicsUnit graphicsUnit, 
    ImageAttributes imageAttributes)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | Image | 描画に使用する画像です。 |
| rectDestination | RectangleF | 描画先の矩形です。 |
| graphicsUnit | GraphicsUnit | グラフィックス単位です。 |
| imageAttributes | ImageAttributes | 画像属性です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* は null です。 |

### 関連項目

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle, Rectangle, GraphicsUnit) {#drawimage_13}

指定された場所と指定されたサイズで指定された [`Image`](../image/) を描画します。

```csharp
public void DrawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, 
    GraphicsUnit graphicsUnit)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | Image | 描画に使用する画像です。 |
| rectSource | Rectangle | ソース矩形です。 |
| rectDestination | Rectangle | 宛先矩形です。 |
| graphicsUnit | GraphicsUnit | グラフィックス単位です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* は null です。 |

### 関連項目

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF, RectangleF, GraphicsUnit) {#drawimage_18}

指定された場所と指定されたサイズで指定された [`Image`](../image/) を描画します。

```csharp
public void DrawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, 
    GraphicsUnit graphicsUnit)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | Image | 描画に使用する画像です。 |
| rectSource | RectangleF | ソース矩形です。 |
| rectDestination | RectangleF | 宛先矩形です。 |
| graphicsUnit | GraphicsUnit | グラフィックス単位です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* は null です。 |

### 関連項目

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) {#drawimage_14}

指定された場所と指定されたサイズで指定された [`Image`](../image/) を描画します。

```csharp
public void DrawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, 
    GraphicsUnit graphicsUnit, ImageAttributes imageAttributes)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | Image | 描画に使用する画像です。 |
| rectSource | Rectangle | ソース矩形です。 |
| rectDestination | Rectangle | 宛先矩形です。 |
| graphicsUnit | GraphicsUnit | グラフィックス単位です。 |
| imageAttributes | ImageAttributes | 画像属性です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* は null です。 |

### 関連項目

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) {#drawimage_19}

指定された場所と指定されたサイズで指定された [`Image`](../image/) を描画します。

```csharp
public void DrawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, 
    GraphicsUnit graphicsUnit, ImageAttributes imageAttributes)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | Image | 描画に使用する画像です。 |
| rectSource | RectangleF | ソース矩形です。 |
| rectDestination | RectangleF | 目的地の矩形です。 |
| graphicsUnit | GraphicsUnit | 使用するグラフィックス単位です。 |
| imageAttributes | ImageAttributes | 使用する画像属性です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* は null です。 |

### 関連項目

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point[]) {#drawimage_6}

指定された場所に、指定されたサイズで指定された *image* の指定された部分を描画します。

```csharp
public void DrawImage(Image image, Point[] destPoints)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | Image | 描画する画像です。 |
| destPoints | Point[] | 平行四辺形を定義する3つの PointF 構造体の配列です。 |

### 関連項目

* class [Image](../../image/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point[], Rectangle) {#drawimage_7}

指定された場所に、指定されたサイズで指定された *image* の指定された部分を描画します。

```csharp
public void DrawImage(Image image, Point[] destPoints, Rectangle srcRect)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | Image | 描画する画像です。 |
| destPoints | Point[] | 平行四辺形を定義する3つの PointF 構造体の配列です。 |
| srcRect | Rectangle | ソース矩形です。 |

### 関連項目

* class [Image](../../image/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point[], Rectangle, GraphicsUnit) {#drawimage_8}

指定された場所に、指定されたサイズで指定された *image* の指定された部分を描画します。

```csharp
public void DrawImage(Image image, Point[] destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | Image | 描画する画像です。 |
| destPoints | Point[] | 平行四辺形を定義する3つの PointF 構造体の配列です。 |
| srcRect | Rectangle | ソース矩形です。 |
| srcUnit | GraphicsUnit | 測定単位です。 |

### 関連項目

* class [Image](../../image/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) {#drawimage_9}

指定された場所に、指定されたサイズで指定された *image* の指定された部分を描画します。

```csharp
public void DrawImage(Image image, Point[] destPoints, Rectangle srcRect, GraphicsUnit srcUnit, 
    ImageAttributes imageAttributes)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | Image | 描画する画像です。 |
| destPoints | Point[] | 平行四辺形を定義する3つの PointF 構造体の配列です。 |
| srcRect | Rectangle | ソース矩形です。 |
| srcUnit | GraphicsUnit | 測定単位です。 |
| imageAttributes | ImageAttributes | 画像属性です。 |

### 関連項目

* class [Image](../../image/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, PointF[]) {#drawimage_2}

指定された場所に、指定されたサイズで指定された *image* の指定された部分を描画します。

```csharp
public void DrawImage(Image image, PointF[] destPoints)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | Image | 描画する画像です。 |
| destPoints | PointF[] | 平行四辺形を定義する3つの PointF 構造体の配列です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | image |

### 関連項目

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, PointF[], RectangleF) {#drawimage_3}

指定された場所に、指定されたサイズで指定された *image* の指定された部分を描画します。

```csharp
public void DrawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | Image | 描画する画像です。 |
| destPoints | PointF[] | 平行四辺形を定義する3つの PointF 構造体の配列です。 |
| srcRect | RectangleF | ソース矩形です。 |

### 関連項目

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, PointF[], RectangleF, GraphicsUnit) {#drawimage_4}

指定された場所に、指定されたサイズで指定された *image* の指定された部分を描画します。

```csharp
public void DrawImage(Image image, PointF[] destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | Image | 描画する画像です。 |
| destPoints | PointF[] | 平行四辺形を定義する3つの PointF 構造体の配列です。 |
| srcRect | RectangleF | ソース矩形です。 |
| srcUnit | GraphicsUnit | 測定単位です。 |

### 関連項目

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) {#drawimage_5}

指定された場所に、指定されたサイズで指定された *image* の指定された部分を描画します。

```csharp
public void DrawImage(Image image, PointF[] destPoints, RectangleF srcRect, GraphicsUnit srcUnit, 
    ImageAttributes imageAttributes)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| image | Image | 描画する画像です。 |
| destPoints | PointF[] | 平行四辺形を定義する3つの PointF 構造体の配列です。 |
| srcRect | RectangleF | ソース矩形です。 |
| srcUnit | GraphicsUnit | 測定単位です。 |
| imageAttributes | ImageAttributes | 画像属性です。 |

### 関連項目

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, float, float, float, float) {#drawimage_23}

指定された場所と指定されたサイズで指定された [`Image`](../image/) を描画します。

```csharp
public void DrawImage(Image sourceImage, float x, float y, float width, float height)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | Image | 描画に使用する画像です。 |
| x | シングル | 描画された画像の左上隅の x 座標です。 |
| y | シングル | 描画された画像の左上隅の y 座標です。 |
| width | シングル | 描画された画像の幅です。 |
| height | シングル | 描画された画像の高さです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* は null です。 |

### 関連項目

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point) {#drawimage}

指定された場所に、元の実際のサイズで指定された [`Image`](../image/) を描画します。

```csharp
public void DrawImage(Image sourceImage, Point point)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | Image | 描画に使用する画像です。 |
| point | Point | [`Point`](../../point/) 構造体は、描画された画像の左上隅の位置を表します。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* は null です。 |

### 関連項目

* class [Image](../../image/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, int, int) {#drawimage_20}

座標のペアで指定された場所に、元の物理サイズを使用して指定された画像を描画します。

```csharp
public void DrawImage(Image sourceImage, int x, int y)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | Image | 描画に使用する画像です。 |
| x | Int32 | 描画された画像の左上隅の x 座標です。 |
| y | Int32 | 描画された画像の左上隅の y 座標です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* は null です。 |

### 関連項目

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle) {#drawimage_10}

指定された場所と指定されたサイズで指定された [`Image`](../image/) を描画します。

```csharp
public void DrawImage(Image sourceImage, Rectangle rect)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | Image | 描画に使用する画像です。 |
| rect | Rectangle | [`Rectangle`](../../rectangle/) 構造体は、描画された画像の位置とサイズを指定します。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* は null です。 |

### 関連項目

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, int, int, int, int) {#drawimage_21}

指定された場所と指定されたサイズで指定された [`Image`](../image/) を描画します。

```csharp
public void DrawImage(Image sourceImage, int x, int y, int width, int height)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sourceImage | Image | 描画に使用する画像です。 |
| x | Int32 | 描画された画像の左上隅の x 座標です。 |
| y | Int32 | 描画された画像の左上隅の y 座標です。 |
| width | Int32 | 描画された画像の幅です。 |
| height | Int32 | 描画された画像の高さです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentNullException | *sourceImage* は null です。 |

### 関連項目

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


