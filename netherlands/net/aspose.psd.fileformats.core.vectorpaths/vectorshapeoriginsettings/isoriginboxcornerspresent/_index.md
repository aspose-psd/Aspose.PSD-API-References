---
title: VectorShapeOriginSettings.IsOriginBoxCornersPresent
second_title: Aspose.PSD voor .NET API-referentie
description: VectorShapeOriginSettings eigendom. Krijgt een waarde die aangeeft of deze instantie de eigenschap origin box corners heeft.
type: docs
weight: 20
url: /nl/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/
---
## VectorShapeOriginSettings.IsOriginBoxCornersPresent property

Krijgt een waarde die aangeeft of deze instantie de eigenschap origin box corners heeft.

```csharp
public bool IsOriginBoxCornersPresent { get; }
```

### Eigendoms-waarde

`WAAR` als deze instantie de eigenschap origin box corners heeft; anders,`vals` .

### Voorbeelden

De volgende code demonstreert de mogelijkheid om de grootte van een vormlaag te wijzigen die vectorpaden bevat.

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

### Zie ook

* class [VectorShapeOriginSettings](../)
* naamruimte [Aspose.PSD.FileFormats.Core.VectorPaths](../../vectorshapeoriginsettings/)
* montage [Aspose.PSD](../../../)


