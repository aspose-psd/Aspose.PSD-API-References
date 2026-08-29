---
title: "PsdImage.AddPosterizeAdjustmentLayer"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PsdImage-Methode. Fügt eine Posterize‑Anpassungsebene hinzu"
type: docs
weight: 430
url: /de/net/aspose.psd.fileformats.psd/psdimage/addposterizeadjustmentlayer/
---
{{< psd/tize >}}
## PsdImage.AddPosterizeAdjustmentLayer method

Fügt die Posterize-Anpassungsebene hinzu.

```csharp
public PosterizeLayer AddPosterizeAdjustmentLayer()
```

### Rückgabewert

PosterizeLayer-Instanz.

## Beispiele

Der folgende Code demonstriert die Möglichkeit, PosterizeAdjustmentLayer über PsdImage hinzuzufügen.

```csharp
[C#]

string srcFile = "zendeya.psd";
string outFile = "zendeya.psd.out.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(srcFile))
{
    psdImage.AddPosterizeAdjustmentLayer();
    psdImage.Save(outFile);
}

// Gespeicherte Änderungen überprüfen
using (PsdImage image = (PsdImage)Image.Load(
           outFile,
           new PsdLoadOptions { LoadEffectsResource = true }))
{
    AssertAreEqual(2, image.Layers.Length);

    PosterizeLayer posterizeLayer = (PosterizeLayer)image.Layers[1];

    AssertAreEqual(true, posterizeLayer is PosterizeLayer);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### Siehe auch

* class [PosterizeLayer](../../../aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/)
* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


