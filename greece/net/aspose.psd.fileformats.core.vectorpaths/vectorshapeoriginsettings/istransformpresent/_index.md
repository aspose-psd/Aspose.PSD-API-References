---
title: VectorShapeOriginSettings.IsTransformPresent
second_title: Aspose.PSD για Αναφορά API .NET
description: VectorShapeOriginSettings ιδιοκτησία. Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει την ιδιότητα μετασχηματισμού.
type: docs
weight: 100
url: /el/net/aspose.psd.fileformats.core.vectorpaths/vectorshapeoriginsettings/istransformpresent/
---
## VectorShapeOriginSettings.IsTransformPresent property

Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει την ιδιότητα μετασχηματισμού.

```csharp
public bool IsTransformPresent { get; }
```

### Αξία περιουσίας

`αληθής` αν αυτή η περίπτωση έχει την ιδιότητα μετασχηματισμού. σε διαφορετική περίπτωση,`ψευδής` .

### Παραδείγματα

Ο ακόλουθος κώδικας δείχνει τη δυνατότητα αλλαγής μεγέθους στρωμάτων σχήματος που περιέχει διανυσματικά μονοπάτια.

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
* χώρος ονομάτων [Aspose.PSD.FileFormats.Core.VectorPaths](../../vectorshapeoriginsettings/)
* συνέλευση [Aspose.PSD](../../../)


