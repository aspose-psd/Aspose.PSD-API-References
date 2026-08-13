---
title: "Graphics.DrawImage"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Graphics yöntemi. Belirtilen Image'ı, özgün fiziksel boyutunu kullanarak belirtilen konumda çizer."
type: docs
weight: 230
url: /tr/net/aspose.psd/graphics/drawimage/
---
{{< psd/tize >}}
## DrawImage(Image, PointF) {#drawimage_1}

Belirtilen [`Image`](../image/)'ı, özgün fiziksel boyutunu kullanarak belirtilen konumda çizer.

```csharp
public void DrawImage(Image sourceImage, PointF point)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | Image | Çizim için kullanılacak resim. |
| point | PointF | [`PointF`](../../pointf/) çizilen görüntünün sol üst köşesini temsil eden yapı. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *sourceImage* null. |

### Ayrıca Bakınız

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, float, float) {#drawimage_22}

Belirtilen [`Image`](../image/)'ı, özgün fiziksel boyutunu kullanarak belirtilen konumda çizer.

```csharp
public void DrawImage(Image sourceImage, float x, float y)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | Image | Çizim için kullanılacak resim. |
| x | Single | Çizilen resmin sol üst köşesinin x koordinatı. |
| y | Single | Çizilen resmin sol üst köşesinin y koordinatı. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *sourceImage* null. |

### Ayrıca Bakınız

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF) {#drawimage_15}

Belirtilen [`Image`](../image/) 'ı belirtilen konumda ve belirtilen boyutta çizer.

```csharp
public void DrawImage(Image sourceImage, RectangleF rect)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | Image | Çizim için kullanılacak resim. |
| rect | RectangleF | [`RectangleF`](../../rectanglef/) çizilen görüntünün konumunu ve boyutunu belirten yapı. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *sourceImage* null. |

### Ayrıca Bakınız

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle, GraphicsUnit) {#drawimage_11}

Belirtilen [`Image`](../image/) 'ı belirtilen konumda ve belirtilen boyutta çizer.

```csharp
public void DrawImage(Image sourceImage, Rectangle rectDestination, GraphicsUnit graphicsUnit)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | Image | Çizim için kullanılacak resim. |
| rectDestination | Rectangle | Hedef dikdörtgen. |
| graphicsUnit | GraphicsUnit | Grafik birimi. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *sourceImage* null. |

### Ayrıca Bakınız

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF, GraphicsUnit) {#drawimage_16}

Belirtilen [`Image`](../image/) 'ı belirtilen konumda ve belirtilen boyutta çizer.

```csharp
public void DrawImage(Image sourceImage, RectangleF rectDestination, GraphicsUnit graphicsUnit)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | Image | Çizim için kullanılacak resim. |
| rectDestination | RectangleF | Hedef dikdörtgen. |
| graphicsUnit | GraphicsUnit | Grafik birimi. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *sourceImage* null. |

### Ayrıca Bakınız

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle, GraphicsUnit, ImageAttributes) {#drawimage_12}

Belirtilen [`Image`](../image/) 'ı belirtilen konumda ve belirtilen boyutta çizer.

```csharp
public void DrawImage(Image sourceImage, Rectangle rectDestination, GraphicsUnit graphicsUnit, 
    ImageAttributes imageAttributes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | Image | Çizim için kullanılacak resim. |
| rectDestination | Rectangle | Hedef dikdörtgen. |
| graphicsUnit | GraphicsUnit | Grafik birimi. |
| imageAttributes | ImageAttributes | Görüntü öznitelikleri. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *sourceImage* null. |

### Ayrıca Bakınız

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF, GraphicsUnit, ImageAttributes) {#drawimage_17}

Belirtilen [`Image`](../image/) 'ı belirtilen konumda ve belirtilen boyutta çizer.

```csharp
public void DrawImage(Image sourceImage, RectangleF rectDestination, GraphicsUnit graphicsUnit, 
    ImageAttributes imageAttributes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | Image | Çizim için kullanılacak resim. |
| rectDestination | RectangleF | Çizim yapılacak hedef dikdörtgen. |
| graphicsUnit | GraphicsUnit | Grafik birimi. |
| imageAttributes | ImageAttributes | Görüntü öznitelikleri. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *sourceImage* null. |

### Ayrıca Bakınız

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle, Rectangle, GraphicsUnit) {#drawimage_13}

Belirtilen [`Image`](../image/) 'ı belirtilen konumda ve belirtilen boyutta çizer.

```csharp
public void DrawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, 
    GraphicsUnit graphicsUnit)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | Image | Çizim için kullanılacak resim. |
| rectSource | Rectangle | Kaynak dikdörtgen. |
| rectDestination | Rectangle | Hedef dikdörtgen. |
| graphicsUnit | GraphicsUnit | Grafik birimi. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *sourceImage* null. |

### Ayrıca Bakınız

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF, RectangleF, GraphicsUnit) {#drawimage_18}

Belirtilen [`Image`](../image/) 'ı belirtilen konumda ve belirtilen boyutta çizer.

```csharp
public void DrawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, 
    GraphicsUnit graphicsUnit)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | Image | Çizim için kullanılacak resim. |
| rectSource | RectangleF | Kaynak dikdörtgen. |
| rectDestination | RectangleF | Hedef dikdörtgen. |
| graphicsUnit | GraphicsUnit | Grafik birimi. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *sourceImage* null. |

### Ayrıca Bakınız

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) {#drawimage_14}

Belirtilen [`Image`](../image/) 'ı belirtilen konumda ve belirtilen boyutta çizer.

```csharp
public void DrawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, 
    GraphicsUnit graphicsUnit, ImageAttributes imageAttributes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | Image | Çizim için kullanılacak resim. |
| rectSource | Rectangle | Kaynak dikdörtgen. |
| rectDestination | Rectangle | Hedef dikdörtgen. |
| graphicsUnit | GraphicsUnit | Grafik birimi. |
| imageAttributes | ImageAttributes | Görüntü öznitelikleri. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *sourceImage* null. |

### Ayrıca Bakınız

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) {#drawimage_19}

Belirtilen [`Image`](../image/) 'ı belirtilen konumda ve belirtilen boyutta çizer.

```csharp
public void DrawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, 
    GraphicsUnit graphicsUnit, ImageAttributes imageAttributes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | Image | Çizim için kullanılacak resim. |
| rectSource | RectangleF | Kaynak dikdörtgen. |
| rectDestination | RectangleF | Hedef dikdörtgen. |
| graphicsUnit | GraphicsUnit | Kullanılacak grafik birimi. |
| imageAttributes | ImageAttributes | Kullanılacak görüntü öznitelikleri. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *sourceImage* null. |

### Ayrıca Bakınız

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point[]) {#drawimage_6}

Belirtilen *görsel*in belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

```csharp
public void DrawImage(Image image, Point[] destPoints)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | Image | Çizilecek görüntü. |
| destPoints | Point[] | Paralelkenarı tanımlayan üç PointF yapısının dizisi. |

### Ayrıca Bakınız

* class [Image](../../image/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point[], Rectangle) {#drawimage_7}

Belirtilen *görsel*in belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

```csharp
public void DrawImage(Image image, Point[] destPoints, Rectangle srcRect)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | Image | Çizilecek görüntü. |
| destPoints | Point[] | Paralelkenarı tanımlayan üç PointF yapısının dizisi. |
| srcRect | Rectangle | Kaynak dikdörtgen. |

### Ayrıca Bakınız

* class [Image](../../image/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point[], Rectangle, GraphicsUnit) {#drawimage_8}

Belirtilen *görsel*in belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

```csharp
public void DrawImage(Image image, Point[] destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | Image | Çizilecek görüntü. |
| destPoints | Point[] | Paralelkenarı tanımlayan üç PointF yapısının dizisi. |
| srcRect | Rectangle | Kaynak dikdörtgen. |
| srcUnit | GraphicsUnit | Ölçü birimleri. |

### Ayrıca Bakınız

* class [Image](../../image/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) {#drawimage_9}

Belirtilen *görsel*in belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

```csharp
public void DrawImage(Image image, Point[] destPoints, Rectangle srcRect, GraphicsUnit srcUnit, 
    ImageAttributes imageAttributes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | Image | Çizilecek görüntü. |
| destPoints | Point[] | Paralelkenarı tanımlayan üç PointF yapısının dizisi. |
| srcRect | Rectangle | Kaynak dikdörtgen. |
| srcUnit | GraphicsUnit | Ölçü birimleri. |
| imageAttributes | ImageAttributes | Görüntü öznitelikleri. |

### Ayrıca Bakınız

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

Belirtilen *görsel*in belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

```csharp
public void DrawImage(Image image, PointF[] destPoints)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | Image | Çizilecek görüntü. |
| destPoints | PointF[] | Paralelkenarı tanımlayan üç PointF yapısının dizisi. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | görüntü |

### Ayrıca Bakınız

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, PointF[], RectangleF) {#drawimage_3}

Belirtilen *görsel*in belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

```csharp
public void DrawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | Image | Çizilecek görüntü. |
| destPoints | PointF[] | Paralelkenarı tanımlayan üç PointF yapısının dizisi. |
| srcRect | RectangleF | Kaynak dikdörtgen. |

### Ayrıca Bakınız

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, PointF[], RectangleF, GraphicsUnit) {#drawimage_4}

Belirtilen *görsel*in belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

```csharp
public void DrawImage(Image image, PointF[] destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | Image | Çizilecek görüntü. |
| destPoints | PointF[] | Paralelkenarı tanımlayan üç PointF yapısının dizisi. |
| srcRect | RectangleF | Kaynak dikdörtgen. |
| srcUnit | GraphicsUnit | Ölçü birimleri. |

### Ayrıca Bakınız

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) {#drawimage_5}

Belirtilen *görsel*in belirtilen bölümünü, belirtilen konumda ve belirtilen boyutta çizer.

```csharp
public void DrawImage(Image image, PointF[] destPoints, RectangleF srcRect, GraphicsUnit srcUnit, 
    ImageAttributes imageAttributes)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | Image | Çizilecek görüntü. |
| destPoints | PointF[] | Paralelkenarı tanımlayan üç PointF yapısının dizisi. |
| srcRect | RectangleF | Kaynak dikdörtgen. |
| srcUnit | GraphicsUnit | Ölçü birimleri. |
| imageAttributes | ImageAttributes | Görüntü öznitelikleri. |

### Ayrıca Bakınız

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

Belirtilen [`Image`](../image/) 'ı belirtilen konumda ve belirtilen boyutta çizer.

```csharp
public void DrawImage(Image sourceImage, float x, float y, float width, float height)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | Image | Çizim için kullanılacak resim. |
| x | Single | Çizilen resmin sol üst köşesinin x koordinatı. |
| y | Single | Çizilen resmin sol üst köşesinin y koordinatı. |
| width | Single | Çizilen görüntünün genişliği. |
| height | Single | Çizilen görüntünün yüksekliği. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *sourceImage* null. |

### Ayrıca Bakınız

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point) {#drawimage}

Belirtilen [`Image`](../image/)'ı, özgün fiziksel boyutunu kullanarak belirtilen konumda çizer.

```csharp
public void DrawImage(Image sourceImage, Point point)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | Image | Çizim için kullanılacak resim. |
| point | Point | [`Point`](../../point/) yapısı, çizilen görüntünün sol üst köşesinin konumunu temsil eder. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *sourceImage* null. |

### Ayrıca Bakınız

* class [Image](../../image/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, int, int) {#drawimage_20}

Belirtilen görseli, özgün fiziksel boyutunu kullanarak, bir koordinat çiftiyle belirtilen konumda çizer.

```csharp
public void DrawImage(Image sourceImage, int x, int y)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | Image | Çizim için kullanılacak resim. |
| x | Int32 | Çizilen resmin sol üst köşesinin x koordinatı. |
| y | Int32 | Çizilen resmin sol üst köşesinin y koordinatı. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *sourceImage* null. |

### Ayrıca Bakınız

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle) {#drawimage_10}

Belirtilen [`Image`](../image/) 'ı belirtilen konumda ve belirtilen boyutta çizer.

```csharp
public void DrawImage(Image sourceImage, Rectangle rect)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | Image | Çizim için kullanılacak resim. |
| rect | Rectangle | [`Rectangle`](../../rectangle/) yapısı, çizilen görüntünün konumunu ve boyutunu belirtir. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *sourceImage* null. |

### Ayrıca Bakınız

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, int, int, int, int) {#drawimage_21}

Belirtilen [`Image`](../image/) 'ı belirtilen konumda ve belirtilen boyutta çizer.

```csharp
public void DrawImage(Image sourceImage, int x, int y, int width, int height)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | Image | Çizim için kullanılacak resim. |
| x | Int32 | Çizilen resmin sol üst köşesinin x koordinatı. |
| y | Int32 | Çizilen resmin sol üst köşesinin y koordinatı. |
| width | Int32 | Çizilen görüntünün genişliği. |
| height | Int32 | Çizilen görüntünün yüksekliği. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| ArgumentNullException | *sourceImage* null. |

### Ayrıca Bakınız

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


