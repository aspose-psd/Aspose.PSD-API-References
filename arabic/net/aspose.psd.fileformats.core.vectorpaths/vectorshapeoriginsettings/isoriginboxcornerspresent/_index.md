---
title: "VectorShapeOriginSettings.IsOriginBoxCornersPresent"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "خاصية VectorShapeOriginSettings. يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على خاصية زوايا صندوق الأصل"
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/
---
{{< psd/tize >}}
## VectorShapeOriginSettings.IsOriginBoxCornersPresent property

يحصل على قيمة تشير إلى ما إذا كان لهذا المثيل خاصية زوايا صندوق الأصل.

```csharp
public bool IsOriginBoxCornersPresent { get; }
```

### Property Value

`true` إذا كان هذا الكائن يحتوي على خاصية زوايا صندوق الأصل؛ وإلا `false`.

## أمثلة

الكود التالي يوضح القدرة على تغيير حجم طبقات الشكل التي تحتوي على مسارات متجهة.

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

### انظر أيضًا

* class [VectorShapeOriginSettings](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


