---
title: VectorShapeOriginSettings.IsOriginBoxCornersPresent
second_title: Aspose.PSD لمرجع .NET API
description: VectorShapeOriginSettings ملكية. يحصل على قيمة تشير إلى ما إذا كان هذا المثيل يحتوي على خاصية أركان مربع الأصل.
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/
---
## VectorShapeOriginSettings.IsOriginBoxCornersPresent property

يحصل على قيمة تشير إلى ما إذا كان هذا المثيل يحتوي على خاصية أركان مربع الأصل.

```csharp
public bool IsOriginBoxCornersPresent { get; }
```

### Property_Value

`حقيقي` إذا كان هذا المثال له خاصية أركان مربع الأصل ؛ خلاف ذلك،`خطأ شنيع` .

### أمثلة

يوضح الكود التالي القدرة على تغيير حجم طبقات الشكل التي تحتوي على مسارات متجهة.

```csharp
[C#]

string sourceFileName = "vectorShapes.psd";
string outputFileName = "out_vectorShapes.psd";
string sourcePath = sourceFileName;
string outputPath = outputFileName;
string outputPathPng = Path.ChangeExtension(outputPath, ".png");
using (var psdImage = (PsdImage)Image.Load(sourcePath))
{
    foreach (var layer in psdImage.Layers)
    {
        layer.Resize(layer.Width * 5 / 4, layer.Height / 2);
    }

    psdImage.Save(outputPath);
    psdImage.Save(outputPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### أنظر أيضا

* class [VectorShapeOriginSettings](../)
* مساحة الاسم [Aspose.PSD.FileFormats.Core.VectorPaths](../../vectorshapeoriginsettings/)
* المجسم [Aspose.PSD](../../../)


