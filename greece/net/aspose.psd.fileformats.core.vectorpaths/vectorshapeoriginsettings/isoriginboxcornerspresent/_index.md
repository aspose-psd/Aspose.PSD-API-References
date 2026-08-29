---
title: "VectorShapeOriginSettings.IsOriginBoxCornersPresent"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "VectorShapeOriginSettings property. Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει την ιδιότητα γωνιών του πλαισίου προέλευσης"
type: docs
weight: 20
url: /el/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/isoriginboxcornerspresent/
---
{{< psd/tize >}}
## VectorShapeOriginSettings.IsOriginBoxCornersPresent property

Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει την ιδιότητα γωνιών του αρχικού κουτιού.

```csharp
public bool IsOriginBoxCornersPresent { get; }
```

### Property Value

`true` εάν αυτή η παρουσία έχει την ιδιότητα γωνιών του πλαισίου προέλευσης· διαφορετικά, `false`.

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει τη δυνατότητα αλλαγής μεγέθους ενός στρώματος σχήματος που περιέχει διανυσματικές διαδρομές.

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

### Δείτε επίσης

* class [VectorShapeOriginSettings](../)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../../)


