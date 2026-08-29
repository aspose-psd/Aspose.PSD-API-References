---
title: "VectorShapeOriginSettings.IsTransformPresent"
second_title: "Aspose.PSD για .NET API Αναφορά"
description: "Ιδιότητα VectorShapeOriginSettings. Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει την ιδιότητα μετασχηματισμού"
type: docs
weight: 100
url: /el/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/
---
{{< psd/tize >}}
## VectorShapeOriginSettings.IsTransformPresent property

Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει την ιδιότητα μετασχηματισμού.

```csharp
public bool IsTransformPresent { get; }
```

### Property Value

`true` εάν αυτή η παρουσία έχει την ιδιότητα μετασχηματισμού· διαφορετικά, `false`.

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


