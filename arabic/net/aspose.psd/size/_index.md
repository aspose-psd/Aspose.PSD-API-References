---
title: "الهيكل Size"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الهيكل Aspose.PSD.Size. يمثل الحجم"
type: docs
weight: 6050
url: /ar/net/aspose.psd/size/
---
{{< psd/tize >}}
## Size structure

يمثل الحجم.

```csharp
public struct Size
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Size](size/#constructor)(Point) | يُنشئ مثيلًا جديدًا من بنية `Size` من الـ [`Point`](../point/) المحدد. |
| [Size](size/#constructor_1)(int, int) | يُنشئ مثيلًا جديدًا من بنية `Size` من الأبعاد المحددة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Empty](../../aspose.psd/size/empty/) { get; } | يحصل على مثيل جديد من بنية `Size` التي لها قيم [`Width`](./width/) و [`Height`](./height/) مضبوطة على الصفر. |
| [Height](../../aspose.psd/size/height/) { get; set; } | يحصل أو يضبط المكوّن العمودي لهذا `Size`. |
| [IsEmpty](../../aspose.psd/size/isempty/) { get; } | يحصل على قيمة تشير إلى ما إذا كان هذا `Size` له عرض وارتفاع يساوي 0. |
| [Width](../../aspose.psd/size/width/) { get; set; } | يحصل أو يضبط المكوّن الأفقي لهذا `Size`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Add](../../aspose.psd/size/add/)(Size, Size) | يضيف العرض والارتفاع لبنية `Size` واحدة إلى العرض والارتفاع لبنية `Size` أخرى. |
| static [Ceiling](../../aspose.psd/size/ceiling/)(SizeF) | يحوّل بنية [`SizeF`](../sizef/) المحددة إلى بنية `Size` عن طريق تقريب قيم بنية `Size` إلى القيم الصحيحة الأعلى. |
| static [Round](../../aspose.psd/size/round/)(SizeF) | يحوّل بنية [`SizeF`](../sizef/) المحددة إلى بنية `Size` عن طريق تقريب قيم بنية [`SizeF`](../sizef/) إلى أقرب قيمة صحيحة. |
| static [Subtract](../../aspose.psd/size/subtract/)(Size, Size) | يطرح العرض والارتفاع لبنية `Size` واحدة من العرض والارتفاع لبنية `Size` أخرى. |
| static [Truncate](../../aspose.psd/size/truncate/)(SizeF) | يحوّل بنية [`SizeF`](../sizef/) المحددة إلى بنية `Size` عن طريق قطع قيم بنية [`SizeF`](../sizef/) إلى القيم الصحيحة الأدنى. |
| override [Equals](../../aspose.psd/size/equals/)(object) | يفحص ما إذا كان الكائن المحدد هو `Size` بنفس الأبعاد كما هذا `Size`. |
| override [GetHashCode](../../aspose.psd/size/gethashcode/)() | يرجع رمز تجزئة (hash code) لهذه بنية `Size`. |
| override [ToString](../../aspose.psd/size/tostring/)() | ينشئ سلسلة قابلة للقراءة من قبل الإنسان تمثل هذا `Size`. |
| [operator +](../../aspose.psd/size/op_addition/) | يضيف العرض والارتفاع لبنية `Size` واحدة إلى العرض والارتفاع لبنية `Size` أخرى. |
| [operator ==](../../aspose.psd/size/op_equality/) | يفحص ما إذا كانت بنية `Size` اثنتين متساويتين. |
| [explicit operator](../../aspose.psd/size/op_explicit/) | يحوّل الـ `Size` المحدد إلى [`Point`](../point/). |
| [implicit operator](../../aspose.psd/size/op_implicit/) | يحوّل الـ `Size` المحدد إلى [`SizeF`](../sizef/). |
| [operator !=](../../aspose.psd/size/op_inequality/) | يفحص ما إذا كانت بنية `Size` اثنتين مختلفة. |
| [operator -](../../aspose.psd/size/op_subtraction/) | يطرح العرض والارتفاع لبنية `Size` واحدة من العرض والارتفاع لبنية `Size` أخرى. |

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


