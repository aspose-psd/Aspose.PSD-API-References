---
title: "GraphicsPath.Warp"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة GraphicsPath. تُطبق تحويل تشويه يُعرّف بواسطة مستطيل ومُمتَلِس إلى هذا GraphicsPath"
type: docs
weight: 180
url: /ar/net/aspose.psd/graphicspath/warp/
---
{{< psd/tize >}}
## Warp(PointF[], RectangleF) {#warp}

تُطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومُمتَلِس، إلى هذا [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| destPoints | PointF[] | مصفوفة من هياكل [`PointF`](../../pointf/) التي تُعرّف مُمتَلِسًا يتم تحويل المستطيل المُعرّف بـ *srcRect* إليه. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمُمتَلِس تُستنتج من النقاط الثلاث الأولى. |
| srcRect | RectangleF | ‏[`RectangleF`](../../rectanglef/) التي تمثّل المستطيل الذي يتم تحويله إلى المُمتَلِس المُعرّف بـ *destPoints*. |

### انظر أيضًا

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix) {#warp_1}

تُطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومُمتَلِس، إلى هذا [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| destPoints | PointF[] | مصفوفة من هياكل [`PointF`](../../pointf/) التي تُعرّف مُمتَلِسًا يتم تحويل المستطيل المُعرّف بـ *srcRect* إليه. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمُمتَلِس تُستنتج من النقاط الثلاث الأولى. |
| srcRect | RectangleF | ‏[`RectangleF`](../../rectanglef/) التي تمثّل المستطيل الذي يتم تحويله إلى المُمتَلِس المُعرّف بـ *destPoints*. |
| matrix | Matrix | ‏[`Matrix`](../../matrix/) التي تحدد تحويلًا هندسيًا لتطبيقه على المسار. |

### انظر أيضًا

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode) {#warp_2}

تُطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومُمتَلِس، إلى هذا [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| destPoints | PointF[] | مصفوفة من هياكل [`PointF`](../../pointf/) التي تُعرّف مُمتَلِسًا يتم تحويل المستطيل المُعرّف بـ *srcRect* إليه. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمُمتَلِس تُستنتج من النقاط الثلاث الأولى. |
| srcRect | RectangleF | ‏[`RectangleF`](../../rectanglef/) التي تمثّل المستطيل الذي يتم تحويله إلى المُمتَلِس المُعرّف بـ *destPoints*. |
| matrix | Matrix | ‏[`Matrix`](../../matrix/) التي تحدد تحويلًا هندسيًا لتطبيقه على المسار. |
| warpMode | WarpMode | ‏[`WarpMode`](../../warpmode/) تعداد يحدد ما إذا كان عملية التشويه هذه تستخدم وضع المنظور أو الوضع الثنائي الخطّي. |

### انظر أيضًا

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Warp(PointF[], RectangleF, Matrix, WarpMode, float) {#warp_3}

تُطبق تحويل تشويه، يُعرّف بواسطة مستطيل ومُمتَلِس، إلى هذا [`GraphicsPath`](../).

```csharp
public void Warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, WarpMode warpMode, 
    float flatness)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| destPoints | PointF[] | مصفوفة من هياكل [`PointF`](../../pointf/) التي تُعرّف مُمتَلِسًا يتم تحويل المستطيل المُعرّف بـ *srcRect* إليه. يمكن أن تحتوي المصفوفة على ثلاثة أو أربعة عناصر. إذا احتوت المصفوفة على ثلاثة عناصر، فإن الزاوية السفلية اليمنى للمُمتَلِس تُستنتج من النقاط الثلاث الأولى. |
| srcRect | RectangleF | ‏[`RectangleF`](../../rectanglef/) التي تمثّل المستطيل الذي يتم تحويله إلى المُمتَلِس المُعرّف بـ *destPoints*. |
| matrix | Matrix | ‏[`Matrix`](../../matrix/) التي تحدد تحويلًا هندسيًا لتطبيقه على المسار. |
| warpMode | WarpMode | ‏[`WarpMode`](../../warpmode/) تعداد يحدد ما إذا كان عملية التشويه هذه تستخدم وضع المنظور أو الوضع الثنائي الخطّي. |
| flatness | Single | قيمة تتراوح بين 0 و 1 تحدد مدى تسطيح المسار الناتج. لمزيد من المعلومات، راجع طرق [`Flatten`](../flatten/). |

### انظر أيضًا

* struct [PointF](../../pointf/)
* struct [RectangleF](../../rectanglef/)
* class [Matrix](../../matrix/)
* enum [WarpMode](../../warpmode/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


