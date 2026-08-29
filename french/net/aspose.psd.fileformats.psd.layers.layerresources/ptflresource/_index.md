---
title: "Classe PtFlResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PtFlResource classe. Classe PtFlResource. Contient les données du calque de remplissage de motif"
type: docs
weight: 3310
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---
{{< psd/tize >}}
## PtFlResource class

Classe PtFlResource. Contient les données du calque de remplissage de motif.

```csharp
public class PtFlResource : FillLayerResource
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PtFlResource](ptflresource/#constructor)() | Initialise une nouvelle instance de la classe `PtFlResource`. |
| [PtFlResource](ptflresource/#constructor_1)(string, string) | Initialise une nouvelle instance de la classe `PtFlResource`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/alignwithlayer/) { get; set; } | Obtient ou définit une valeur indiquant si [align with layer]. |
| [Angle](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/angle/) { get; set; } | Obtient ou définit l'angle. |
| [IsLinkedWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/islinkedwithlayer/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est liée au calque. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/length/) { get; } | Obtient la longueur de la ressource du calque en octets. |
| [Offset](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/offset/) { get; set; } | Obtient ou définit le décalage. |
| [PatternId](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternid/) { get; set; } | Obtient ou définit l'identifiant du motif. |
| [PatternName](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternname/) { get; set; } | Obtient ou définit le nom du motif. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| [Scale](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/scale/) { get; set; } | Obtient ou définit l'échelle. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Champs

| Nom | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/typetoolkey/) | La clé d'information de l'outil de type. |

## Exemples

L'exemple suivant montre la prise en charge du chargement et de la modification d'une ressource PtFlResource.

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
                    // Lecture
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
                    // Nous n'avons pas de données de motif dans PattResource, nous pouvons donc les ajouter.
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

### Voir aussi

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [FillLayerResource](../filllayerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


