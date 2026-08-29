---
title: "الفئة Metered"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.Metered. توفر طرقًا لتعيين المفتاح المتعقب"
type: docs
weight: 5610
url: /ar/net/aspose.psd/metered/
---
{{< psd/tize >}}
## Metered class

يوفر طرقًا لتعيين المفتاح المقنن.

```csharp
public class Metered
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Metered](metered/)() | الباني الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [Equals](../../aspose.psd/metered/equals/)(object) | يحدد ما إذا كان الكائن المحدد يساوي هذا المثيل. |
| [GetProductName](../../aspose.psd/metered/getproductname/)() | يحصل على اسم المنتج. |
| [SetMeteredKey](../../aspose.psd/metered/setmeteredkey/)(string, string) | يضبط المفتاح العام والخاص المتعقب. إذا قمت بشراء ترخيص متعقب، عند بدء التطبيق يجب استدعاء هذه API، عادةً يكون ذلك كافيًا. ومع ذلك، إذا فشل دائمًا تحميل بيانات الاستهلاك وتجاوز 24 ساعة، سيتم تعيين الترخيص إلى حالة تقييم. لتجنب هذه الحالة، يجب عليك فحص حالة الترخيص بانتظام، إذا كانت في حالة تقييم، استدعِ هذه API مرة أخرى. |
| static [GetConsumptionCredit](../../aspose.psd/metered/getconsumptioncredit/)() | يحصل على رصيد الاستهلاك |
| static [GetConsumptionQuantity](../../aspose.psd/metered/getconsumptionquantity/)() | يحصل على حجم ملف الاستهلاك |
| static [IsMeteredLicensed](../../aspose.psd/metered/ismeteredlicensed/)() | تحقق مما إذا كان المتعقب مرخصًا |

## أمثلة

في هذا المثال، سيتم محاولة ضبط المفتاح العام والخاص المتعقب

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


