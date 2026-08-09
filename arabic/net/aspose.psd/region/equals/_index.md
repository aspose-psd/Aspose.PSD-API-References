---
title: "Region.Equals"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة Region. تختبر ما إذا كان Region المحدد مطابقًا لهذا Region على سطح الرسم المحدد."
type: docs
weight: 40
url: /ar/net/aspose.psd/region/equals/
---
{{< psd/tize >}}
## Equals(Region, Graphics) {#equals}

تختبر ما إذا كان [`Region`](../) المحدد مطابقًا لهذا [`Region`](../) على سطح الرسم المحدد.

```csharp
public bool Equals(Region region, Graphics g)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| region | Region | الـ [`Region`](../) للاختبار. |
| g | Graphics | الـ [`Graphics`](../../graphics/) التي تمثل سطح رسم. |

### قيمة الإرجاع

صحيح إذا كان داخل المنطقة مطابقًا لداخل هذه المنطقة عندما يتم تطبيق التحويل المرتبط بمعامل *g*؛ وإلا، خطأ.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *g *or* region* هو null. |

### انظر أيضًا

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Equals(object) {#equals_1}

تحقق مما إذا كانت الكائنات متساوية.

```csharp
public override bool Equals(object obj)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | Object | الكائن الآخر. |

### قيمة الإرجاع

نتيجة مقارنة المساواة.

### انظر أيضًا

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


