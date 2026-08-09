---
title: "الفئة ImageAttributes"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "فئة Aspose.PSD.ImageAttributes. يحتوي كائن ImageAttributes على معلومات حول كيفية تعديل ألوان البت ماب وملف الميتا أثناء التصيير. يحتفظ كائن ImageAttributes بعدة إعدادات تعديل اللون بما في ذلك مصفوفات تعديل اللون، ومصفوفات تعديل التدرج الرمادي، وقيم تصحيح الجاما، وجداول خريطة الألوان، وقيم عتبة اللون. أثناء التصيير يمكن تصحيح الألوان أو تعتيمها أو إضاءتها أو إزالتها. لتطبيق هذه التعديلات، قم بإنشاء كائن ImageAttributes ومرّر مسار ذلك الكائن مع مسار Image إلى طريقة DrawImage."
type: docs
weight: 5080
url: /ar/net/aspose.psd/imageattributes/
---
{{< psd/tize >}}
## ImageAttributes class

كائن `ImageAttributes` يحتوي على معلومات حول كيفية تعديل ألوان البت ماب وملف الميتا أثناء التصيير. كائن `ImageAttributes` يحتفظ بعدة إعدادات تعديل اللون، بما في ذلك مصفوفات تعديل اللون، ومصفوفات تعديل التدرج الرمادي، وقيم تصحيح الجاما، وجداول خريطة الألوان، وقيم عتبة اللون. أثناء التصيير، يمكن تصحيح الألوان أو تعتيمها أو إضاءتها أو إزالتها. لتطبيق هذه التعديلات، قم بإنشاء كائن `ImageAttributes` ومرّر مسار ذلك الكائن (مع مسار [`Image`](../image/)) إلى طريقة DrawImage.

```csharp
public sealed class ImageAttributes
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ImageAttributes](imageattributes/)() | الباني الافتراضي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | يمسح جدول إعادة تعيين ألوان الفرشاة لهذا الكائن `ImageAttributes`. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | يمسح مفتاح اللون (نطاق الشفافية) للفئة الافتراضية. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | يمسح مفتاح اللون (نطاق الشفافية) لفئة محددة. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | يمسح مصفوفة تعديل اللون للفئة الافتراضية. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | يمسح مصفوفة تعديل اللون لفئة محددة. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | يعطل تصحيح الجاما للفئة الافتراضية. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | يعطل تصحيح الجاما لفئة محددة. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | يمسح إعداد NoOp للفئة الافتراضية. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | يمسح إعداد NoOp لفئة محددة. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | يمسح إعداد قناة الإخراج CMYK (سماوي-ماجنتا-أصفر-أسود) للفئة الافتراضية. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | يمسح إعداد قناة الإخراج (سماوي-ماجنتا-أصفر-أسود) لفئة محددة. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | يمسح إعداد ملف تعريف لون قناة الإخراج للفئة الافتراضية. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | يمسح إعداد ملف تعريف لون قناة الإخراج لفئة محددة. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | يمسح جدول إعادة تعيين الألوان للفئة الافتراضية. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | يمسح جدول إعادة تعيين الألوان لفئة محددة. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | يمسح قيمة العتبة للفئة الافتراضية. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | يمسح قيمة العتبة لفئة محددة. |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | يضبط جدول إعادة تعيين الألوان لفئة الفرشاة. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | يضبط مفتاح اللون للفئة الافتراضية. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | يضبط مفتاح اللون (نطاق الشفافية) لفئة محددة. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي للفئة الافتراضية. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي للفئة الافتراضية. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | يضبط مصفوفة تعديل اللون ومصفوفة تعديل التدرج الرمادي لفئة محددة. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | يضبط مصفوفة تعديل اللون للفئة الافتراضية. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | يضبط مصفوفة تعديل اللون للفئة الافتراضية. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | يضبط مصفوفة تعديل اللون لفئة محددة. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | يضبط قيمة غاما للفئة الافتراضية. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | يضبط قيمة غاما لفئة محددة. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | يعطل تعديل اللون للفئة الافتراضية. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | يعطل تعديل اللون لفئة محددة. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | يضبط قناة الإخراج CMYK (سماوي-أرجواني-أصفر-أسود) للفئة الافتراضية. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | يضبط قناة الإخراج CMYK (سماوي-أرجواني-أصفر-أسود) لفئة محددة. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | يضبط ملف تعريف لون قناة الإخراج للفئة الافتراضية. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | يضبط ملف تعريف لون قناة الإخراج لفئة محددة. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | يضبط جدول إعادة تعيين الألوان للفئة الافتراضية. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | يضبط جدول إعادة تعيين الألوان لفئة محددة. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | يضبط العتبة (نطاق الشفافية) للفئة الافتراضية. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | يضبط العتبة (نطاق الشفافية) لفئة محددة. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | يضبط وضع الالتفاف المستخدم لتحديد كيفية تغطية النسيج عبر الشكل، أو عند حدود الشكل. يتم تغطية النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم تغطيته. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تغطية النسيج عبر الشكل، أو عند حدود الشكل. يتم تغطية النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم تغطيته. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تغطية النسيج عبر الشكل، أو عند حدود الشكل. يتم تغطية النسيج عبر الشكل لملئه عندما يكون النسيج أصغر من الشكل الذي يتم تغطيته. |

### انظر أيضًا

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


