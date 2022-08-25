---
title: PtFlResource
second_title: Référence de l'API Aspose.PSD pour .NET
description: Classe PtFlResource. Contient des données de calque de remplissage de motif.
type: docs
weight: 2930
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/
---
## PtFlResource class

Classe PtFlResource. Contient des données de calque de remplissage de motif.

```csharp
public class PtFlResource : FillLayerResource
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PtFlResource](ptflresource)(string, string) | Initialise une nouvelle instance du[`PtFlResource`](../ptflresource) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/alignwithlayer) { get; set; } | Obtient ou définit une valeur indiquant si [aligner avec le calque]. |
| [IsLinkedWithLayer](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/islinkedwithlayer) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est liée à la couche. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/key) { get; } | Obtient la clé de ressource de couche. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/length) { get; } | Obtient la longueur de la ressource de couche en octets. |
| [Offset](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/offset) { get; set; } | Obtient ou définit le décalage. |
| [PatternId](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternid) { get; set; } | Obtient ou définit l'identifiant du modèle. |
| [PatternName](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/patternname) { get; set; } | Obtient ou définit le nom du modèle. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/psdversion) { get; } | Obtient la version minimale de psd requise pour la ressource de couche. 0 indique aucune restriction. |
| [Scale](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/scale) { get; set; } | Obtient ou définit l'échelle. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/signature) { get; } | Obtient la signature de ressource de couche. |

## Méthodes

| Nom | La description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/save)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring)() | Renvoie unString qui représente cette instance. |

## Des champs

| Nom | La description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/ptflresource/typetoolkey) | La clé d'informations sur l'outil de type. |

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

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource)
* class [FillLayerResource](../filllayerresource)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* Assemblée [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
