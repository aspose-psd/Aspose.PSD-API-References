---
title: VectorShapeOriginSettings.IsOriginBoxCornersPresent
second_title: Aspose.PSD för .NET API-referens
description: VectorShapeOriginSettings fast egendom. Får ett värde som anger om denna instans har egenskapen origin box corners.
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/
---
## VectorShapeOriginSettings.IsOriginBoxCornersPresent property

Får ett värde som anger om denna instans har egenskapen origin box corners.

```csharp
public bool IsOriginBoxCornersPresent { get; }
```

### Fastighetsvärde

`Sann` om denna instans har egenskapen origin box corners; annat,`falsk` .

### Exempel

Följande kod visar möjligheten att ändra storlek på ett formlager som innehåller vektorbanor.

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

### Se även

* class [VectorShapeOriginSettings](../)
* namnutrymme [Aspose.PSD.FileFormats.Core.VectorPaths](../../vectorshapeoriginsettings/)
* hopsättning [Aspose.PSD](../../../)


