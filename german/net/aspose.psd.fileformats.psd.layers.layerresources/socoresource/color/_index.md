---
title: SoCoResource.Color
second_title: Aspose.PSD für .NET-API-Referenz
description: SoCoResource eigendom. Ruft die RGBFarbe ab .
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/
---
## SoCoResource.Color property

Ruft die RGB-Farbe ab .

```csharp
public Color Color { get; set; }
```

### Rückgabewert

Die RGB-Farbe

### Beispiele

Das folgende Beispiel zeigt, wie Sie SoCoResource (Ebenenressource für Farbfüllungsebene) bearbeiten.

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// Ein vorhandenes Bild in eine Instanz der PsdImage-Klasse laden
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // Finden von FillLayer
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // Finden von SoCoResource in der Layer-Ressourcenliste
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

                    // Festlegen der SoCoResource Color-Eigenschaft
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

### Siehe auch

* struct [Color](../../../aspose.psd/color/)
* class [SoCoResource](../)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../socoresource/)
* Montage [Aspose.PSD](../../../)


