---
title: SoCoResource.Color
second_title: Aspose.PSD voor .NET API-referentie
description: SoCoResource eigendom. Krijgt de RGBkleur .
type: docs
weight: 20
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/
---
## SoCoResource.Color property

Krijgt de RGB-kleur .

```csharp
public Color Color { get; set; }
```

### Winstwaarde

De RGB-kleur

### Voorbeelden

Het volgende voorbeeld laat zien hoe u SoCoResource (Layer Resource for Color Fill Layer) bewerkt

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// Laad een bestaande afbeelding in een instantie van de PsdImage-klasse
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // Vinden van FillLayer
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // Vinden van SoCoResource in Layer Resource List
                if (resource is SoCoResource)
                {
                    var socoResource = (SoCoResource)resource;
                    var expectedColor = Color.FromArgb(63, 83, 141);
                    
                    if ((expectedColor.R != socoResource.Color.R) ||
                        (expectedColor.G != socoResource.Color.G) ||
                        (expectedColor.B != socoResource.Color.B) ||
                        (expectedColor.A != socoResource.Color.A))
                    {
                        throw new Exception("Unexpected color");
                    }

                    // De eigenschap SoCoResource Color instellen
                    socoResource.Color = Color.Red;
                    break;
                }
            }
            break;
        }
        im.Save(outputFile);
    }
}
```

### Zie ook

* struct [Color](../../../aspose.psd/color/)
* class [SoCoResource](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../socoresource/)
* montage [Aspose.PSD](../../../)


