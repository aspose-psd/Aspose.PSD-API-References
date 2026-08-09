---
title: "SplitStreamContainer.Read"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة SplitStreamContainer. تقرأ بايتات لملء المخزن المؤقت للبايتات المحدد"
type: docs
weight: 110
url: /ar/net/aspose.psd/splitstreamcontainer/read/
---
{{< psd/tize >}}
## Read(byte[]) {#read}

يقرأ بايتات لملء المخزن المؤقت للبايتات المحدد.

```csharp
public override int Read(byte[] bytes)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| بايت | Byte[] | البايتات للملء. |

### قيمة الإرجاع

عدد البايتات المقروءة. قد تكون هذه القيمة أقل من عدد البايتات في المخزن المؤقت إذا لم يتوفر ما يكفي من البايتات في التدفق.

### انظر أيضًا

* class [SplitStreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Read(byte[], int, int) {#read_1}

يقرأ تسلسلًا من البايتات من التدفق الحالي ويتقدم بالموقع داخل التدفق بعدد البايتات المقروءة.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المخزن المؤقت | Byte[] | مصفوفة من البايتات. عندما تعود هذه الطريقة، يحتوي المخزن المؤقت على مصفوفة البايتات المحددة مع القيم بين *offset* و(*offset* + *count* - 1) المستبدلة بالبايتات المقروءة من المصدر الحالي. |
| offset | Int32 | الإزاحة الصفرية للبايت في *buffer* التي يبدأ عندها تخزين البيانات المقروءة من التدفق الحالي. |
| العدد | Int32 | الحد الأقصى لعدد البايتات التي ستُقرأ من التدفق الحالي. |

### قيمة الإرجاع

إجمالي عدد البايتات المقروءة إلى المخزن المؤقت. قد يكون هذا أقل من عدد البايتات المطلوبة إذا لم تكن تلك البايتات متاحة حالياً، أو صفر (0) إذا تم الوصول إلى نهاية التدفق.

### انظر أيضًا

* class [SplitStreamContainer](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


