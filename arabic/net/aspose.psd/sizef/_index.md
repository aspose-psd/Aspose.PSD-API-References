---
title: "الهيكل SizeF"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الهيكل Aspose.PSD.SizeF. يخزن زوجًا مرتبًا من الأعداد العشرية عادةً العرض والارتفاع لمستطيل."
type: docs
weight: 6060
url: /ar/net/aspose.psd/sizef/
---
{{< psd/tize >}}
## SizeF structure

يخزن زوجًا مرتبًا من الأعداد العائمة، عادةً العرض والارتفاع لمستطيل.

```csharp
public struct SizeF
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SizeF](sizef/#constructor)(PointF) | يُهيئ نسخة جديدة من الهيكل `SizeF` من الـ [`PointF`](../pointf/) المحدد. |
| [SizeF](sizef/#constructor_1)(SizeF) | يُهيئ نسخة جديدة من الهيكل `SizeF` من الـ `SizeF` المحدد. |
| [SizeF](sizef/#constructor_2)(float, float) | يُهيئ نسخة جديدة من بنية `SizeF` من الأبعاد المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Empty](../../aspose.psd/sizef/empty/) { get; } | يحصل على نسخة جديدة من بنية `SizeF` التي تحتوي على قيم [`Width`](./width/) و[`Height`](./height/) مضبوطة على الصفر. |
| [Height](../../aspose.psd/sizef/height/) { get; set; } | يحصل أو يعيّن المكوّن العمودي لهذا `SizeF`. |
| [IsEmpty](../../aspose.psd/sizef/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا `SizeF` يملك عرضًا وارتفاعًا صفرًا. |
| [Width](../../aspose.psd/sizef/width/) { get; set; } | يحصل أو يعيّن المكوّن الأفقي لهذا `SizeF`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Add](../../aspose.psd/sizef/add/)(SizeF, SizeF) | يضيف عرض وارتفاع بنية `SizeF` واحدة إلى عرض وارتفاع بنية `SizeF` أخرى. |
| static [Subtract](../../aspose.psd/sizef/subtract/)(SizeF, SizeF) | يطرح عرض وارتفاع بنية `SizeF` واحدة من عرض وارتفاع بنية `SizeF` أخرى. |
| override [Equals](../../aspose.psd/sizef/equals/)(object) | يفحص ما إذا كان الكائن المحدد هو `SizeF` له نفس الأبعاد مثل هذا `SizeF`. |
| override [GetHashCode](../../aspose.psd/sizef/gethashcode/)() | يرجع رمز تجزئة لهذه بنية [`Size`](../size/). |
| [ToPointF](../../aspose.psd/sizef/topointf/)() | يحوّل `SizeF` إلى [`PointF`](../pointf/). |
| [ToSize](../../aspose.psd/sizef/tosize/)() | يحوّل `SizeF` إلى بنية [`Size`](../size/) مع قيم حجم مقصوصة. |
| override [ToString](../../aspose.psd/sizef/tostring/)() | ينشئ سلسلة قابلة للقراءة تمثّل هذا `SizeF`. |
| [operator +](../../aspose.psd/sizef/op_addition/) | يضيف عرض وارتفاع بنية `SizeF` واحدة إلى عرض وارتفاع بنية `SizeF` أخرى. |
| [operator ==](../../aspose.psd/sizef/op_equality/) | يفحص ما إذا كانت بنيتا `SizeF` متساويتين. |
| [explicit operator](../../aspose.psd/sizef/op_explicit/) | يحوّل `SizeF` المحدد إلى [`PointF`](../pointf/). |
| [operator !=](../../aspose.psd/sizef/op_inequality/) | يفحص ما إذا كانت بنيتا `SizeF` مختلفتين. |
| [operator -](../../aspose.psd/sizef/op_subtraction/) | يطرح عرض وارتفاع بنية `SizeF` واحدة من عرض وارتفاع بنية `SizeF` أخرى. |

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


