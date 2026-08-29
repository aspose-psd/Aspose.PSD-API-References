---
title: "التعداد InterpolationMethod"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "التعداد Aspose.PSD.FileFormats.Psd.Layers.FillSettings.InterpolationMethod. قيم fourCC المعبأة لطريقة استيفاء التدرج في Photoshop. مفتاح الوصف gradientsInterpolationMethod"
type: docs
weight: 2160
url: /ar/net/aspose.psd.fileformats.psd.layers.fillsettings/interpolationmethod/
---
{{< psd/tize >}}
## InterpolationMethod enumeration

قيم fourCC المعبأة لطريقة استيفاء التدرج في فوتوشوب. مفتاح الوصف: "gradientsInterpolationMethod"

```csharp
public enum InterpolationMethod : uint
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Classic | `1197698163` | 'Gcls' — كلاسيكي (القيمة الافتراضية القديمة عندما يكون المفتاح غير موجود). |
| Perceptual | `1348825699` | 'Perc' — إدراكي. |
| Linear | `1282306592` | 'Lnr ' — خطي (لاحظ المسافة الزائدة). |
| Smooth | `1399680879` | 'Smoo' — ناعم. |
| Stripes | `1195986291` | 'GIMs' — مخطط. |

## أمثلة

الكود التالي يوضح دعم تصيير التدرج باستخدام طريقة Smooth.

```csharp
[C#]

string sourceFile = "GradientOverlay.psd";
string outputFile = "output_GradientOverlay.psd";
string outputFilePng = "output_GradientOverlay.png";

var srcMethod = InterpolationMethod.Linear;
var newMethod = InterpolationMethod.Smooth;

var opt = new PsdLoadOptions()
{
    LoadEffectsResource = true,
};

using (var image = (PsdImage)Image.Load(sourceFile, opt))
{
    // قراءة
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;
    AssertAreEqual(srcMethod, gradientSettings.InterpolationMethod);

    // تغيير
    gradientSettings.InterpolationMethod = newMethod;

    image.Save(outputFile);
    image.Save(outputFilePng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}

// تحقق من البيانات المحفوظة
using (var image = (PsdImage)Image.Load(outputFile, opt))
{
    var effect = image.Layers[1].BlendingOptions.Effects[0] as GradientOverlayEffect;
    var gradientSettings = effect.Settings;

    AssertAreEqual(newMethod, gradientSettings.InterpolationMethod);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### انظر أيضًا

* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


