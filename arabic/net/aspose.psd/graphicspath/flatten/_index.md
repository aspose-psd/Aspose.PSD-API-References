---
title: "GraphicsPath.Flatten"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة GraphicsPath. تحول كل منحنى في هذا المسار إلى سلسلة من القطع الخطية المتصلة"
type: docs
weight: 90
url: /ar/net/aspose.psd/graphicspath/flatten/
---
{{< psd/tize >}}
## Flatten() {#flatten}

يحوّل كل منحنى في هذا المسار إلى سلسلة من القطع الخطية المتصلة.

```csharp
public void Flatten()
```

### انظر أيضًا

* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

يطبق التحويل المحدد ثم يحول كل منحنى في هذا [`GraphicsPath`](../) إلى سلسلة من القطع الخطية المتصلة.

```csharp
public void Flatten(Matrix matrix)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | Matrix | مصفوفة [`Matrix`](../../matrix/) تُستخدم لتحويل هذا [`GraphicsPath`](../) قبل التسوية. |

### انظر أيضًا

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

تحول كل منحنى في هذا [`GraphicsPath`](../) إلى سلسلة من القطع الخطية المتصلة.

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| matrix | Matrix | مصفوفة [`Matrix`](../../matrix/) تُستخدم لتحويل هذا [`GraphicsPath`](../) قبل التسوية. |
| السطحية | Single | يحدد الحد الأقصى للخطأ المسموح به بين المنحنى وتقريبه المسطح. القيمة الافتراضية هي 0.25. تقليل قيمة السطحية سيزيد عدد القطع الخطية في التقريب. |

### انظر أيضًا

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


