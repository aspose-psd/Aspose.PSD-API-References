---
title: PtFlResource.IsLinkedWithLayer
second_title: Aspose.PSD voor .NET API-referentie
description: PtFlResource eigendom. Haalt een waarde op of stelt een waarde in die aangeeft of deze instantie is gekoppeld aan een laag.
type: docs
weight: 30
url: /nl/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/islinkedwithlayer/
---
## PtFlResource.IsLinkedWithLayer property

Haalt een waarde op of stelt een waarde in die aangeeft of deze instantie is gekoppeld aan een laag.

```csharp
public bool IsLinkedWithLayer { get; set; }
```

### Eigendoms-waarde

`WAAR` als deze instantie is gekoppeld aan een laag; anders,`vals` .

### Voorbeelden

Het volgende voorbeeld demonstreert de ondersteuning van het laden en bewerken van een PtFlResource-resource.

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
                    // Lezing
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

                    // Bewerken
                    resource.Offset = new Point(-11, 13);
                    resource.Scale = 200;
                    resource.AlignWithLayer = false;
                    resource.IsLinkedWithLayer = false;
                    fillLayer.Resources = fillLayer.Resources;
                    // We hebben geen patroongegevens in PattResource, dus we kunnen deze toevoegen.
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

### Zie ook

* class [PtFlResource](../)
* naamruimte [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../ptflresource/)
* montage [Aspose.PSD](../../../)


