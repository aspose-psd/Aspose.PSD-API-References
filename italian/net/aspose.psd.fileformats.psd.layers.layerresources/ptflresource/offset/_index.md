---
title: PtFlResource.Offset
second_title: Aspose.PSD per riferimento API .NET
description: PtFlResource proprietà. Ottiene o imposta loffset.
type: docs
weight: 60
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/offset/
---
## PtFlResource.Offset property

Ottiene o imposta l'offset.

```csharp
public Point Offset { get; set; }
```

### Valore della proprietà

L'offset.

### Esempi

L'esempio seguente mostra il supporto del caricamento e della modifica di una risorsa PtFlResource.

```csharp
[C#]

string sourceFileName = "PatternFillLayer.psd";
string exportPath = "PtFlResource_Edited.psd";
double tolerance = 0.0001;
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            var resources = fillLayer.Resources;
            foreach (var res in resources)
            {
                if (res is PtFlResource)
                {
                    // Lettura
                    PtFlResource resource = (PtFlResource)res;
                    if (
                        resource.Offset.X != -46 ||
                        resource.Offset.Y != -45 ||
                        resource.PatternId != "a6818df2-7532-494e-9615-8fdd6b7f38e5\0" ||
                        resource.PatternName != "$$$/Presets/Patterns/OpticalSquares=Optical Squares\0" ||
                        resource.AlignWithLayer != true ||
                        resource.IsLinkedWithLayer != true ||
                        !(Math.Abs(resource.Scale - 50) < tolerance))
                    {
                        throw new Exception("PtFl Resource was read incorrect");
                    }

                    // La modifica
                    resource.Offset = new Point(-11, 13);
                    resource.Scale = 200;
                    resource.AlignWithLayer = false;
                    resource.IsLinkedWithLayer = false;
                    fillLayer.Resources = fillLayer.Resources;
                    // Non abbiamo dati di pattern in PattResource, quindi possiamo aggiungerli.
                    var fillSettings = (PatternFillSettings)fillLayer.FillSettings;
                    fillSettings.PatternData = new int[]
                    {
                        Color.Black.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                        Color.White.ToArgb(),
                    };
                    fillSettings.PatternHeight = 1;
                    fillSettings.PatternWidth = 4;
                    fillSettings.PatternName = "$$$/Presets/Patterns/VerticalLine=Vertical Line New\0";
                    fillSettings.PatternId = Guid.NewGuid().ToString() + "\0";
                    fillLayer.Update();
                }
                break;
            }
            break;
        }
    }

    im.Save(exportPath);
}
```

### Guarda anche

* struct [Point](../../../aspose.psd/point/)
* class [PtFlResource](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../ptflresource/)
* assemblea [Aspose.PSD](../../../)


