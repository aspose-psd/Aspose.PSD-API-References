---
title: GraphicsPath.Warp
second_title: Aspose.PSD لمرجع .NET API
description: GraphicsPath طريقة. يطبق تحويل الالتواء  المحدد بواسطة مستطيل ومتوازي أضلاع  على هذاGraphicsPath .
type: docs
weight: 180
url: /ar/net/aspose.psd/graphicspath/warp/
---
## Warp(PointF[], RectangleF) {#warp}

يطبق تحويل الالتواء ، المحدد بواسطة مستطيل ومتوازي أضلاع ، على هذا[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| destPoints | PointF[] | مجموعة من[`PointF`](../../pointf/) الهياكل التي تحدد متوازي الأضلاع الذي يحدده المستطيل*srcRect*يتحول. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا كانت المصفوفة تحتوي على ثلاثة عناصر ، فإن الزاوية اليمنى السفلية من متوازي الأضلاع تكون ضمنية بالنقاط الثلاث الأولى. |
| srcRect | RectangleF | أ[`RectangleF`](../../rectanglef/) الذي يمثل المستطيل المحول إلى متوازي الأضلاع المحدد بواسطة*destPoints*. |

### أنظر أيضا

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* مساحة الاسم [Aspose.PSD](../../graphicspath/)
* المجسم [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

يطبق تحويل الالتواء ، المحدد بواسطة مستطيل ومتوازي أضلاع ، على هذا[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| destPoints | PointF[] | مجموعة من[`PointF`](../../pointf/) الهياكل التي تحدد متوازي الأضلاع الذي يحدده المستطيل*srcRect*يتحول. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا كانت المصفوفة تحتوي على ثلاثة عناصر ، فإن الزاوية اليمنى السفلية من متوازي الأضلاع تكون ضمنية بالنقاط الثلاث الأولى. |
| srcRect | RectangleF | أ[`RectangleF`](../../rectanglef/) الذي يمثل المستطيل المحول إلى متوازي الأضلاع المحدد بواسطة*destPoints*. |
| matrix | Matrix | أ[`Matrix`](../../matrix/) يحدد تحويلًا هندسيًا لتطبيقه على المسار. |

### أنظر أيضا

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* مساحة الاسم [Aspose.PSD](../../graphicspath/)
* المجسم [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

يطبق تحويل الالتواء ، المحدد بواسطة مستطيل ومتوازي أضلاع ، على هذا[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| destPoints | PointF[] | مجموعة من[`PointF`](../../pointf/) الهياكل التي تحدد متوازي الأضلاع الذي يحدده المستطيل*srcRect*يتحول. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا كانت المصفوفة تحتوي على ثلاثة عناصر ، فإن الزاوية اليمنى السفلية من متوازي الأضلاع تكون ضمنية بالنقاط الثلاث الأولى. |
| srcRect | RectangleF | أ[`RectangleF`](../../rectanglef/) الذي يمثل المستطيل المحول إلى متوازي الأضلاع المحدد بواسطة*destPoints*. |
| matrix | Matrix | أ[`Matrix`](../../matrix/) يحدد تحويلًا هندسيًا لتطبيقه على المسار. |
| warpMode | WarpMode | أ[`WarpMode`](../../warpmode/) التعداد الذي يحدد ما إذا كانت عملية الالتواء تستخدم الوضع المنظور أو الوضع ثنائي الخطوط. |

### أنظر أيضا

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* مساحة الاسم [Aspose.PSD](../../graphicspath/)
* المجسم [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

يطبق تحويل الالتواء ، المحدد بواسطة مستطيل ومتوازي أضلاع ، على هذا[`GraphicsPath`](../) .

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| destPoints | PointF[] | مجموعة من[`PointF`](../../pointf/) الهياكل التي تحدد متوازي الأضلاع الذي يحدده المستطيل*srcRect*يتحول. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا كانت المصفوفة تحتوي على ثلاثة عناصر ، فإن الزاوية اليمنى السفلية من متوازي الأضلاع تكون ضمنية بالنقاط الثلاث الأولى. |
| srcRect | RectangleF | أ[`RectangleF`](../../rectanglef/) الذي يمثل المستطيل المحول إلى متوازي الأضلاع المحدد بواسطة*destPoints*. |
| matrix | Matrix | أ[`Matrix`](../../matrix/) يحدد تحويلًا هندسيًا لتطبيقه على المسار. |
| warpMode | WarpMode | أ[`WarpMode`](../../warpmode/) التعداد الذي يحدد ما إذا كانت عملية الالتواء تستخدم الوضع المنظور أو الوضع ثنائي الخطوط. |
| flatness | Single | قيمة من 0 إلى 1 تحدد مدى استواء المسار الناتج. لمزيد من المعلومات ، راجع[`Flatten`](../flatten/) طُرق. |

### أنظر أيضا

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* مساحة الاسم [Aspose.PSD](../../graphicspath/)
* المجسم [Aspose.PSD](../../../)


