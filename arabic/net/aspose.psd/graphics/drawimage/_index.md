---
title: "Graphics.DrawImage"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة Graphics. ترسم الصورة المحددة باستخدام حجمها الفعلي الأصلي في الموقع المحدد."
type: docs
weight: 230
url: /ar/net/aspose.psd/graphics/drawimage/
---
{{< psd/tize >}}
## DrawImage(Image, PointF) {#drawimage_1}

ترسم [`Image`](../image/) المحددة، باستخدام حجمها الفعلي الأصلي، في الموقع المحدد.

```csharp
public void DrawImage(Image sourceImage, PointF point)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | صورة | `الصورة التي سيتم الرسم بها.` |
| point | PointF | هيكل [`PointF`](../../pointf/) الذي يمثل الزاوية العليا اليسرى للصورة المرسومة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*sourceImage* فارغ.` |

### انظر أيضًا

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, float, float) {#drawimage_22}

ترسم [`Image`](../image/) المحددة، باستخدام حجمها الفعلي الأصلي، في الموقع المحدد.

```csharp
public void DrawImage(Image sourceImage, float x, float y)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | صورة | `الصورة التي سيتم الرسم بها.` |
| x | Single | `الإحداثي السيني للزاوية العليا اليسرى للصورة المرسومة.` |
| y | Single | `الإحداثي الصادي للزاوية العليا اليسرى للصورة المرسومة.` |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*sourceImage* فارغ.` |

### انظر أيضًا

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF) {#drawimage_15}

ترسم [`Image`](../image/) المحددة في الموقع المحدد وبالحجم المحدد.

```csharp
public void DrawImage(Image sourceImage, RectangleF rect)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | صورة | `الصورة التي سيتم الرسم بها.` |
| rect | RectangleF | هيكل [`RectangleF`](../../rectanglef/) الذي يحدد موقع وحجم الصورة المرسومة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*sourceImage* فارغ.` |

### انظر أيضًا

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle, GraphicsUnit) {#drawimage_11}

ترسم [`Image`](../image/) المحددة في الموقع المحدد وبالحجم المحدد.

```csharp
public void DrawImage(Image sourceImage, Rectangle rectDestination, GraphicsUnit graphicsUnit)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | صورة | `الصورة التي سيتم الرسم بها.` |
| rectDestination | Rectangle | مستطيل الوجهة. |
| graphicsUnit | GraphicsUnit | وحدة الرسومات. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*sourceImage* فارغ.` |

### انظر أيضًا

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF, GraphicsUnit) {#drawimage_16}

ترسم [`Image`](../image/) المحددة في الموقع المحدد وبالحجم المحدد.

```csharp
public void DrawImage(Image sourceImage, RectangleF rectDestination, GraphicsUnit graphicsUnit)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | صورة | `الصورة التي سيتم الرسم بها.` |
| rectDestination | RectangleF | مستطيل الوجهة. |
| graphicsUnit | GraphicsUnit | وحدة الرسومات. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*sourceImage* فارغ.` |

### انظر أيضًا

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle, GraphicsUnit, ImageAttributes) {#drawimage_12}

ترسم [`Image`](../image/) المحددة في الموقع المحدد وبالحجم المحدد.

```csharp
public void DrawImage(Image sourceImage, Rectangle rectDestination, GraphicsUnit graphicsUnit, 
    ImageAttributes imageAttributes)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | صورة | `الصورة التي سيتم الرسم بها.` |
| rectDestination | Rectangle | مستطيل الوجهة. |
| graphicsUnit | GraphicsUnit | وحدة الرسومات. |
| imageAttributes | ImageAttributes | سمات الصورة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*sourceImage* فارغ.` |

### انظر أيضًا

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF, GraphicsUnit, ImageAttributes) {#drawimage_17}

ترسم [`Image`](../image/) المحددة في الموقع المحدد وبالحجم المحدد.

```csharp
public void DrawImage(Image sourceImage, RectangleF rectDestination, GraphicsUnit graphicsUnit, 
    ImageAttributes imageAttributes)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | صورة | `الصورة التي سيتم الرسم بها.` |
| rectDestination | RectangleF | المستطيل الوجهة للرسم فيه. |
| graphicsUnit | GraphicsUnit | وحدة الرسومات. |
| imageAttributes | ImageAttributes | سمات الصورة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*sourceImage* فارغ.` |

### انظر أيضًا

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle, Rectangle, GraphicsUnit) {#drawimage_13}

ترسم [`Image`](../image/) المحددة في الموقع المحدد وبالحجم المحدد.

```csharp
public void DrawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, 
    GraphicsUnit graphicsUnit)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | صورة | `الصورة التي سيتم الرسم بها.` |
| rectSource | Rectangle | المستطيل المصدر. |
| rectDestination | Rectangle | المستطيل الوجهة. |
| graphicsUnit | GraphicsUnit | وحدة الرسومات. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*sourceImage* فارغ.` |

### انظر أيضًا

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF, RectangleF, GraphicsUnit) {#drawimage_18}

ترسم [`Image`](../image/) المحددة في الموقع المحدد وبالحجم المحدد.

```csharp
public void DrawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, 
    GraphicsUnit graphicsUnit)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | صورة | `الصورة التي سيتم الرسم بها.` |
| rectSource | RectangleF | المستطيل المصدر. |
| rectDestination | RectangleF | المستطيل الوجهة. |
| graphicsUnit | GraphicsUnit | وحدة الرسومات. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*sourceImage* فارغ.` |

### انظر أيضًا

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle, Rectangle, GraphicsUnit, ImageAttributes) {#drawimage_14}

ترسم [`Image`](../image/) المحددة في الموقع المحدد وبالحجم المحدد.

```csharp
public void DrawImage(Image sourceImage, Rectangle rectSource, Rectangle rectDestination, 
    GraphicsUnit graphicsUnit, ImageAttributes imageAttributes)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | صورة | `الصورة التي سيتم الرسم بها.` |
| rectSource | Rectangle | المستطيل المصدر. |
| rectDestination | Rectangle | المستطيل الوجهة. |
| graphicsUnit | GraphicsUnit | وحدة الرسومات. |
| imageAttributes | ImageAttributes | سمات الصورة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*sourceImage* فارغ.` |

### انظر أيضًا

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, RectangleF, RectangleF, GraphicsUnit, ImageAttributes) {#drawimage_19}

ترسم [`Image`](../image/) المحددة في الموقع المحدد وبالحجم المحدد.

```csharp
public void DrawImage(Image sourceImage, RectangleF rectSource, RectangleF rectDestination, 
    GraphicsUnit graphicsUnit, ImageAttributes imageAttributes)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | صورة | `الصورة التي سيتم الرسم بها.` |
| rectSource | RectangleF | مستطيل المصدر. |
| rectDestination | RectangleF | مستطيل الوجهة. |
| graphicsUnit | GraphicsUnit | وحدة الرسومات المستخدمة. |
| imageAttributes | ImageAttributes | سمات الصورة المستخدمة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*sourceImage* فارغ.` |

### انظر أيضًا

* class [Image](../../image/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [ImageAttributes](../../imageattributes/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point[]) {#drawimage_6}

يرسم الجزء المحدد من *الصورة* المحددة في الموقع المحدد وبالحجم المحدد.

```csharp
public void DrawImage(Image image, Point[] destPoints)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | صورة | الصورة المراد رسمها. |
| destPoints | Point[] | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |

### انظر أيضًا

* class [Image](../../image/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point[], Rectangle) {#drawimage_7}

يرسم الجزء المحدد من *الصورة* المحددة في الموقع المحدد وبالحجم المحدد.

```csharp
public void DrawImage(Image image, Point[] destPoints, Rectangle srcRect)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | صورة | الصورة المراد رسمها. |
| destPoints | Point[] | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |
| srcRect | Rectangle | مستطيل المصدر. |

### انظر أيضًا

* class [Image](../../image/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point[], Rectangle, GraphicsUnit) {#drawimage_8}

يرسم الجزء المحدد من *الصورة* المحددة في الموقع المحدد وبالحجم المحدد.

```csharp
public void DrawImage(Image image, Point[] destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | صورة | الصورة المراد رسمها. |
| destPoints | Point[] | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |
| srcRect | Rectangle | مستطيل المصدر. |
| srcUnit | GraphicsUnit | وحدات القياس. |

### انظر أيضًا

* class [Image](../../image/)
* struct [Point](../../point/)
* struct [Rectangle](../../rectangle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point[], Rectangle, GraphicsUnit, ImageAttributes) {#drawimage_9}

يرسم الجزء المحدد من *الصورة* المحددة في الموقع المحدد وبالحجم المحدد.

```csharp
public void DrawImage(Image image, Point[] destPoints, Rectangle srcRect, GraphicsUnit srcUnit, 
    ImageAttributes imageAttributes)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | صورة | الصورة المراد رسمها. |
| destPoints | Point[] | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |
| srcRect | Rectangle | مستطيل المصدر. |
| srcUnit | GraphicsUnit | وحدات القياس. |
| imageAttributes | ImageAttributes | سمات الصورة. |

### انظر أيضًا

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

يرسم الجزء المحدد من *الصورة* المحددة في الموقع المحدد وبالحجم المحدد.

```csharp
public void DrawImage(Image image, PointF[] destPoints)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | صورة | الصورة المراد رسمها. |
| destPoints | PointF[] | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | صورة |

### انظر أيضًا

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, PointF[], RectangleF) {#drawimage_3}

يرسم الجزء المحدد من *الصورة* المحددة في الموقع المحدد وبالحجم المحدد.

```csharp
public void DrawImage(Image image, PointF[] destPoints, RectangleF srcRect)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | صورة | الصورة المراد رسمها. |
| destPoints | PointF[] | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |
| srcRect | RectangleF | مستطيل المصدر. |

### انظر أيضًا

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, PointF[], RectangleF, GraphicsUnit) {#drawimage_4}

يرسم الجزء المحدد من *الصورة* المحددة في الموقع المحدد وبالحجم المحدد.

```csharp
public void DrawImage(Image image, PointF[] destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | صورة | الصورة المراد رسمها. |
| destPoints | PointF[] | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |
| srcRect | RectangleF | مستطيل المصدر. |
| srcUnit | GraphicsUnit | وحدات القياس. |

### انظر أيضًا

* class [Image](../../image/)
* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, PointF[], RectangleF, GraphicsUnit, ImageAttributes) {#drawimage_5}

يرسم الجزء المحدد من *الصورة* المحددة في الموقع المحدد وبالحجم المحدد.

```csharp
public void DrawImage(Image image, PointF[] destPoints, RectangleF srcRect, GraphicsUnit srcUnit, 
    ImageAttributes imageAttributes)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| صورة | صورة | الصورة المراد رسمها. |
| destPoints | PointF[] | مصفوفة من ثلاث هياكل PointF تُعرّف متوازي أضلاع. |
| srcRect | RectangleF | مستطيل المصدر. |
| srcUnit | GraphicsUnit | وحدات القياس. |
| imageAttributes | ImageAttributes | سمات الصورة. |

### انظر أيضًا

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

ترسم [`Image`](../image/) المحددة في الموقع المحدد وبالحجم المحدد.

```csharp
public void DrawImage(Image sourceImage, float x, float y, float width, float height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | صورة | `الصورة التي سيتم الرسم بها.` |
| x | Single | `الإحداثي السيني للزاوية العليا اليسرى للصورة المرسومة.` |
| y | Single | `الإحداثي الصادي للزاوية العليا اليسرى للصورة المرسومة.` |
| العرض | Single | عرض الصورة المرسومة. |
| الارتفاع | Single | ارتفاع الصورة المرسومة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*sourceImage* فارغ.` |

### انظر أيضًا

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Point) {#drawimage}

ترسم [`Image`](../image/) المحددة، باستخدام حجمها الفعلي الأصلي، في الموقع المحدد.

```csharp
public void DrawImage(Image sourceImage, Point point)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | صورة | `الصورة التي سيتم الرسم بها.` |
| point | Point | [`Point`](../../point/) هيكل يمثل موقع الزاوية العلوية اليسرى للصورة المرسومة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*sourceImage* فارغ.` |

### انظر أيضًا

* class [Image](../../image/)
* struct [Point](../../point/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, int, int) {#drawimage_20}

يرسم الصورة المحددة، باستخدام حجمها الفيزيائي الأصلي، في الموقع المحدد بزوج من الإحداثيات.

```csharp
public void DrawImage(Image sourceImage, int x, int y)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | صورة | `الصورة التي سيتم الرسم بها.` |
| x | Int32 | `الإحداثي السيني للزاوية العليا اليسرى للصورة المرسومة.` |
| y | Int32 | `الإحداثي الصادي للزاوية العليا اليسرى للصورة المرسومة.` |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*sourceImage* فارغ.` |

### انظر أيضًا

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, Rectangle) {#drawimage_10}

ترسم [`Image`](../image/) المحددة في الموقع المحدد وبالحجم المحدد.

```csharp
public void DrawImage(Image sourceImage, Rectangle rect)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | صورة | `الصورة التي سيتم الرسم بها.` |
| rect | Rectangle | [`Rectangle`](../../rectangle/) هيكل يحدد موقع وحجم الصورة المرسومة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*sourceImage* فارغ.` |

### انظر أيضًا

* class [Image](../../image/)
* struct [Rectangle](../../rectangle/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawImage(Image, int, int, int, int) {#drawimage_21}

ترسم [`Image`](../image/) المحددة في الموقع المحدد وبالحجم المحدد.

```csharp
public void DrawImage(Image sourceImage, int x, int y, int width, int height)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourceImage | صورة | `الصورة التي سيتم الرسم بها.` |
| x | Int32 | `الإحداثي السيني للزاوية العليا اليسرى للصورة المرسومة.` |
| y | Int32 | `الإحداثي الصادي للزاوية العليا اليسرى للصورة المرسومة.` |
| العرض | Int32 | عرض الصورة المرسومة. |
| الارتفاع | Int32 | ارتفاع الصورة المرسومة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | `*sourceImage* فارغ.` |

### انظر أيضًا

* class [Image](../../image/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


