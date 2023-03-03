---
title: GradientFillSettings.GradientType
second_title: Aspose.PSD لمرجع .NET API
description: GradientFillSettings ملكية. الحصول على نوع التدرج اللوني أو تحديده.
type: docs
weight: 90
url: /ar/net/aspose.psd.fileformats.psd.layers.fillsettings/gradientfillsettings/gradienttype/
---
## GradientFillSettings.GradientType property

الحصول على نوع التدرج اللوني أو تحديده.

```csharp
public GradientType GradientType { get; set; }
```

### Property_Value

نوع التدرج اللوني .

### أمثلة

الكود التالي يحفظ الصور بنوع مختلف من التدرج ويوضح كيفية Aspose.PSD يرسم التدرج.

```csharp
[C#]

string fileName = "FillLayerGradient.psd";
string sourceFile = fileName;
GradientType[] gradientTypes = new[]
{
    GradientType.Linear, GradientType.Radial, GradientType.Angle, GradientType.Reflected, GradientType.Diamond
};
using (var image = Image.Load(sourceFile))
{
    PsdImage psdImage = (PsdImage)image;
    FillLayer fillLayer = (FillLayer)psdImage.Layers[0];
    GradientFillSettings fillSettings = (GradientFillSettings)fillLayer.FillSettings;
    foreach (var gradientType in gradientTypes)
    {
        fillSettings.GradientType = gradientType;
        fillLayer.Update();

        string resultFile = fileName + "_" + gradientType.ToString() + ".png";
        resultFile = resultFile;
        psdImage.Save(resultFile, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### أنظر أيضا

* enum [GradientType](../../gradienttype/)
* class [GradientFillSettings](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../gradientfillsettings/)
* المجسم [Aspose.PSD](../../../)


