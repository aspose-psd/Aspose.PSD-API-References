---
title: Class ImageAttributes
second_title: Aspose.PSD لمرجع .NET API
description: Aspose.PSD.ImageAttributes فصل. أنImageAttributes يحتوي الكائن على معلومات حول كيفية معالجة ألوان الصور النقطية وملفات التعريف أثناء العرض. انImageAttributes يحتفظ الكائن بالعديد من إعدادات ضبط اللون  بما في ذلك مصفوفات ضبط اللون  ومصفوفات ضبط التدرج الرمادي  وقيم تصحيح جاما  وجداول خريطة الألوان  وقيم عتبة اللون. أثناء التجسيد  يمكن تصحيح الألوان وتغميقها وتفتيحها وإزالتها. لتطبيق مثل هذه التلاعبات  قم بتهيئة ملفImageAttributesكائن وتمرير مسار ذلكImageAttributes كائن جنبًا إلى جنب مع مسار ملفImage  إلى طريقة DrawImage .
type: docs
weight: 4610
url: /ar/net/aspose.psd/imageattributes/
---
## ImageAttributes class

أن`ImageAttributes` يحتوي الكائن على معلومات حول كيفية معالجة ألوان الصور النقطية وملفات التعريف أثناء العرض. ان`ImageAttributes` يحتفظ الكائن بالعديد من إعدادات ضبط اللون ، بما في ذلك مصفوفات ضبط اللون ، ومصفوفات ضبط التدرج الرمادي ، وقيم تصحيح جاما ، وجداول خريطة الألوان ، وقيم عتبة اللون. أثناء التجسيد ، يمكن تصحيح الألوان وتغميقها وتفتيحها وإزالتها. لتطبيق مثل هذه التلاعبات ، قم بتهيئة ملف`ImageAttributes`كائن وتمرير مسار ذلك`ImageAttributes` كائن (جنبًا إلى جنب مع مسار ملف[`Image`](../image/) ) إلى طريقة DrawImage .

```csharp
public sealed class ImageAttributes
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [ImageAttributes](imageattributes/)() | Default_Constructor |

## طُرق

| اسم | وصف |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.psd/imageattributes/clearbrushremaptable/)() | يمسح جدول إعادة رسم خريطة لون الفرشاة لهذا`ImageAttributes` الكائن . |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey)() | يمسح مفتاح اللون (نطاق الشفافية) للفئة الافتراضية. |
| [ClearColorKey](../../aspose.psd/imageattributes/clearcolorkey/#clearcolorkey_1)(ColorAdjustType) | يمسح مفتاح اللون (نطاق الشفافية) لفئة محددة. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix)() | يمسح مصفوفة ضبط اللون للفئة الافتراضية. |
| [ClearColorMatrix](../../aspose.psd/imageattributes/clearcolormatrix/#clearcolormatrix_1)(ColorAdjustType) | يمسح مصفوفة ضبط اللون لفئة محددة. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma)() | تعطيل تصحيح جاما للفئة الافتراضية. |
| [ClearGamma](../../aspose.psd/imageattributes/cleargamma/#cleargamma_1)(ColorAdjustType) | تعطيل تصحيح جاما لفئة محددة. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop)() | يمسح إعداد NoOp للفئة الافتراضية. |
| [ClearNoOp](../../aspose.psd/imageattributes/clearnoop/#clearnoop_1)(ColorAdjustType) | يمسح إعداد NoOp لفئة محددة. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel)() | يمسح إعداد قناة الإخراج CMYK (سماوي-أرجواني-أصفر-أسود) للفئة الافتراضية. |
| [ClearOutputChannel](../../aspose.psd/imageattributes/clearoutputchannel/#clearoutputchannel_1)(ColorAdjustType) | يمسح إعداد قناة الإخراج (سماوي - أرجواني - أصفر - أسود) لفئة محددة. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile)() | يمسح إعداد ملف تعريف لون قناة الإخراج للفئة الافتراضية. |
| [ClearOutputChannelColorProfile](../../aspose.psd/imageattributes/clearoutputchannelcolorprofile/#clearoutputchannelcolorprofile_1)(ColorAdjustType) | يمسح إعداد ملف تعريف لون قناة الإخراج لفئة محددة. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable)() | يمسح جدول إعادة تعيين الألوان للفئة الافتراضية. |
| [ClearRemapTable](../../aspose.psd/imageattributes/clearremaptable/#clearremaptable_1)(ColorAdjustType) | يمسح جدول إعادة رسم خريطة الألوان لفئة محددة. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold)() | مسح القيمة الحدية للفئة الافتراضية. |
| [ClearThreshold](../../aspose.psd/imageattributes/clearthreshold/#clearthreshold_1)(ColorAdjustType) | مسح القيمة الحدية لفئة محددة. |
| [SetBrushRemapTable](../../aspose.psd/imageattributes/setbrushremaptable/)(ColorMap[]) | يضبط جدول إعادة رسم خريطة الألوان لفئة الفرشاة. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey)(Color, Color) | يضبط مفتاح اللون للفئة الافتراضية. |
| [SetColorKey](../../aspose.psd/imageattributes/setcolorkey/#setcolorkey_1)(Color, Color, ColorAdjustType) | يضبط مفتاح اللون (نطاق الشفافية) لفئة محددة. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices)(ColorMatrix, ColorMatrix) | يضبط مصفوفة ضبط اللون ومصفوفة ضبط التدرج الرمادي للفئة الافتراضية. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | يضبط مصفوفة ضبط اللون ومصفوفة ضبط التدرج الرمادي للفئة الافتراضية. |
| [SetColorMatrices](../../aspose.psd/imageattributes/setcolormatrices/#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | يضبط مصفوفة ضبط اللون ومصفوفة ضبط التدرج الرمادي لفئة محددة. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix)(ColorMatrix) | يضبط مصفوفة ضبط اللون للفئة الافتراضية. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | يضبط مصفوفة ضبط اللون للفئة الافتراضية. |
| [SetColorMatrix](../../aspose.psd/imageattributes/setcolormatrix/#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | يضبط مصفوفة ضبط اللون لفئة محددة. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma)(float) | يضبط قيمة جاما للفئة الافتراضية. |
| [SetGamma](../../aspose.psd/imageattributes/setgamma/#setgamma_1)(float, ColorAdjustType) | يضبط قيمة جاما لفئة محددة . |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop)() | لإيقاف تشغيل ضبط اللون للفئة الافتراضية. |
| [SetNoOp](../../aspose.psd/imageattributes/setnoop/#setnoop_1)(ColorAdjustType) | لإيقاف تشغيل ضبط اللون لفئة محددة. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel)(ColorChannelFlag) | يضبط قناة الإخراج CMYK (سماوي-أرجواني-أصفر-أسود) للفئة الافتراضية. |
| [SetOutputChannel](../../aspose.psd/imageattributes/setoutputchannel/#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | يضبط قناة الإخراج CMYK (سماوي-أرجواني-أصفر-أسود) لفئة محددة. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile)(string) | يضبط ملف ملف تعريف لون قناة الإخراج للفئة الافتراضية. |
| [SetOutputChannelColorProfile](../../aspose.psd/imageattributes/setoutputchannelcolorprofile/#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | يضبط ملف ملف تعريف لون قناة الإخراج لفئة محددة. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable)(ColorMap[]) | يضبط جدول إعادة رسم خريطة الألوان للفئة الافتراضية. |
| [SetRemapTable](../../aspose.psd/imageattributes/setremaptable/#setremaptable_1)(ColorMap[], ColorAdjustType) | يضبط جدول إعادة رسم خريطة اللون لفئة محددة. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold)(float) | يضبط الحد الأدنى (نطاق الشفافية) للفئة الافتراضية. |
| [SetThreshold](../../aspose.psd/imageattributes/setthreshold/#setthreshold_1)(float, ColorAdjustType) | يضبط العتبة (نطاق الشفافية) لفئة محددة . |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode)(WrapMode) | يضبط وضع الالتفاف المستخدم لتحديد كيفية تجانب نسيج عبر شكل ما ، أو عند حدود الشكل. يتم تجانب النسيج عبر شكل لملئه عندما يكون النسيج أصغر من الشكل الذي يملأه. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_1)(WrapMode, Color) | يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تجانب نسيج عبر شكل ما ، أو عند حدود الشكل. يتم تجانب النسيج عبر شكل لملئه عندما يكون النسيج أصغر من الشكل الذي يملأه. |
| [SetWrapMode](../../aspose.psd/imageattributes/setwrapmode/#setwrapmode_2)(WrapMode, Color, bool) | يضبط وضع الالتفاف واللون المستخدم لتحديد كيفية تجانب نسيج عبر شكل ما ، أو عند حدود الشكل. يتم تجانب النسيج عبر شكل لملئه عندما يكون النسيج أصغر من الشكل الذي يملأه. |

### أنظر أيضا

* مساحة الاسم [Aspose.PSD](../../aspose.psd/)
* المجسم [Aspose.PSD](../../)


