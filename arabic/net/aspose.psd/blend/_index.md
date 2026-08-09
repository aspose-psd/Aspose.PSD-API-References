---
title: "الفئة Blend"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.Blend. تُعرّف نمط المزج. لا يمكن وراثة هذه الفئة"
type: docs
weight: 110
url: /ar/net/aspose.psd/blend/
---
{{< psd/tize >}}
## Blend class

يحدد نمط المزج. لا يمكن وراثة هذه الفئة.

```csharp
public sealed class Blend
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Blend](blend/#constructor)() | يُنشئ مثيلاً جديداً للفئة `Blend`. سيكون عدد العناصر في مصفوفات العامل والمزج مساوياً لـ 1. |
| [Blend](blend/#constructor_1)(int) | يُنشئ مثيلاً جديداً للفئة `Blend` بعدد المحدد من العوامل والمواضع. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Factors](../../aspose.psd/blend/factors/) { get; set; } | يحصل أو يعيّن مصفوفة عوامل المزج للتدرج. |
| [Positions](../../aspose.psd/blend/positions/) { get; set; } | يحصل أو يعيّن مصفوفة مواضع المزج للتدرج. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.psd/blend/equals/)(object) | يفحص ما إذا كان الكائن المحدد من فئة `Blend` ومكافئ لهذه الفئة `Blend`. |
| override [GetHashCode](../../aspose.psd/blend/gethashcode/)() | يرجع رمز تجزئة لهذه المثيلة. |

## ملاحظات

الاستخدام النموذجي لفئة المزج هو تعريف نمط مزج للفرشاة. وبالتالي يجب تهيئة خصائص المزج بعناية. لا يُسمح بالمصفوفات الفارغة. ستطرح الفرشاة الاستثناء المناسب إذا كانت مصفوفة عوامل المزج أو مواضعها فارغة أو إذا لم يكن طولها متساوياً. إذا كان هناك عنصران أو أكثر في مصفوفة المواضع، يجب أن يكون العنصر الأول 0 والأخير 1.

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


