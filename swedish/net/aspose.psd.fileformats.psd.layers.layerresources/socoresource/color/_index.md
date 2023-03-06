---
title: SoCoResource.Color
second_title: Aspose.PSD för .NET API-referens
description: SoCoResource fast egendom. Får RGBfärgen .
type: docs
weight: 20
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/
---
## SoCoResource.Color property

Får RGB-färgen .

```csharp
public Color Color { get; set; }
```

### Returvärde

RGB-färgen

### Exempel

Följande exempel visar hur du redigerar SoCoResource (Layer Resource for Color Fill Layer)

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// Ladda en befintlig bild i en instans av klassen PsdImage
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // Hitta FillLayer
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // Hitta SoCoResource i Layer Resource List
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

                    // Ställa in egenskapen SoCoResource Color
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

### Se även

* struct [Color](../../../aspose.psd/color/)
* class [SoCoResource](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../socoresource/)
* hopsättning [Aspose.PSD](../../../)


