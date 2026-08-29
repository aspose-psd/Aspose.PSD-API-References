---
title: "GrdmResource.InterpolationMethod"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية GrdmResource. تحصل أو تعين طريقة الاستيفاء للتدرج"
type: docs
weight: 90
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/interpolationmethod/
---
{{< psd/tize >}}
## GrdmResource.InterpolationMethod property

يحصل أو يضبط طريقة الاستيفاء للتدرج.

```csharp
public InterpolationMethod InterpolationMethod { get; set; }
```

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

* enum [InterpolationMethod](../../../aspose.psd.fileformats.psd.layers.fillsettings/interpolationmethod/)
* class [GrdmResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


