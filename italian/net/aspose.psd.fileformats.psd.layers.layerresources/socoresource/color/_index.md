---
title: SoCoResource.Color
second_title: Aspose.PSD per riferimento API .NET
description: SoCoResource proprietà. Ottiene il colore RGB .
type: docs
weight: 20
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/color/
---
## SoCoResource.Color property

Ottiene il colore RGB .

```csharp
public Color Color { get; set; }
```

### Valore di ritorno

Il colore RGB

### Esempi

L'esempio seguente mostra come modificare SoCoResource (Layer Resource for Color Fill Layer)

```csharp
[C#]

string sourceFile = "ColorFillLayer.psd";
string outputFile = "SoCoResource_Edited.psd";

// Carica un'immagine esistente in un'istanza della classe PsdImage
var im = (PsdImage)Image.Load(sourceFile);

using (im)
{
    foreach (var layer in im.Layers)
    {
        // Individuazione di FillLayer
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            foreach (var resource in fillLayer.Resources)
            {
                // Ricerca di SoCoResource nell'elenco delle risorse del livello
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

                    // Impostazione della proprietà SoCoResource Color
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

### Guarda anche

* struct [Color](../../../aspose.psd/color/)
* class [SoCoResource](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../socoresource/)
* assemblea [Aspose.PSD](../../../)


