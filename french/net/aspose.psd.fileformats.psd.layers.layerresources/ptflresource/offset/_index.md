---
title: PtFlResource.Offset
second_title: Référence de l'API Aspose.PSD pour .NET
description: PtFlResource propriété. Obtient ou définit le décalage.
type: docs
weight: 60
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/offset/
---
## PtFlResource.Offset property

Obtient ou définit le décalage.

```csharp
public Point Offset { get; set; }
```

### Valeur de la propriété

Le décalage.

### Exemples

L'exemple suivant illustre la prise en charge du chargement et de la modification d'une ressource PtFlResource.

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
                    // En lisant
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

                    // Édition
                    resource.Offset = new Point(-11, 13);
                    resource.Scale = 200;
                    resource.AlignWithLayer = false;
                    resource.IsLinkedWithLayer = false;
                    fillLayer.Resources = fillLayer.Resources;
                    // Nous n'avons pas de données de modèle dans PattResource, nous pouvons donc les ajouter.
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

### Voir également

* struct [Point](../../../aspose.psd/point/)
* class [PtFlResource](../)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../ptflresource/)
* Assemblée [Aspose.PSD](../../../)


