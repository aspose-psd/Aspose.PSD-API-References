---
title: "VectorShapeOriginSettings.IsOriginBoxCornersPresent"
second_title: "Aspose.PSD för .NET API‑referens"
description: "VectorShapeOriginSettings-egenskap. Hämtar ett värde som indikerar om detta objekt har egenskapen för ursprungsrutans hörn"
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/
---
{{< psd/tize >}}
## VectorShapeOriginSettings.IsOriginBoxCornersPresent property

Hämtar ett värde som indikerar om den här instansen har egenskapen för ursprungsboxens hörn.

```csharp
public bool IsOriginBoxCornersPresent { get; }
```

### Property Value

`true` om detta objekt har egenskapen för ursprungsrutans hörn; annars `false`.

## Exempel

Följande kod demonstrerar möjligheten att ändra storlek på ett formlager som innehåller vector paths.

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
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


