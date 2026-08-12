---
title: "PsdLoadOptions.AllowNonChangedLayerRepaint"
second_title: "Aspose.PSD voor .NET API-referentie"
description: "PsdLoadOptions eigenschap. Haalt op of stelt in of de oorspronkelijke laagpixels behouden moeten blijven tijdens het renderen als de laag niet is gewijzigd"
type: docs
weight: 20
url: /nl/net/aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowNonChangedLayerRepaint property

Haalt op of stelt in of de oorspronkelijke laagpixels behouden moeten blijven tijdens het renderen als de laag niet is gewijzigd.

```csharp
public bool AllowNonChangedLayerRepaint { get; set; }
```

### Property Value

`true` om de oorspronkelijke pixels van onveranderde lagen te behouden; anders `false`.

## Voorbeelden

De volgende code toont het nieuwe gedrag dat automatisch opnieuw schilderen van lagen vóór wijzigingen voorkomt.

```csharp
[C#]

string srcFile = "psdnet2400.psd";
string output1 = "unchanged-2400.png";
string output2 = "updated-2400.png";

using (var psdImage = (PsdImage)Image.Load(srcFile,
new PsdLoadOptions() { AllowNonChangedLayerRepaint = false /* The new default behaviour */ }))
{
    psdImage.Save(output1, new PngOptions());

    ((TextLayer)psdImage.Layers[1]).TextData.UpdateLayerData();

    psdImage.Save(output2, new PngOptions());
}
```

### Zie ook

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


