---
title: "SoCoResource.Color"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "SoCoResource Eigenschaft. Gibt die RGB-Farbe zurück"
type: docs
weight: 20
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/
---
{{< psd/tize >}}
## SoCoResource.Color property

Liest die RGB-Farbe.

```csharp
public Color Color { get; set; }
```

### Rückgabewert

Die RGB-Farbe

## Beispiele

Das folgende Beispiel demonstriert, wie Sie SoCoResource bearbeiten (Layer-Ressource für Farbfüllschicht)

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// Laden Sie ein vorhandenes Bild in eine Instanz der Klasse PsdImage.
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // Suche nach FillLayer
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // Suche nach SoCoResource in der Layer-Ressourcenliste
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

                    // Festlegen der SoCoResource-Farbeigenschaft
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
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


