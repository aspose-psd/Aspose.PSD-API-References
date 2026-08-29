---
title: "Classe VectorPathDataResource"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VectorPathDataResource classe. Classe VectorPathDataResource. Cette ressource contient des informations sur le masque de calque vectoriel"
type: docs
weight: 3740
url: /fr/net/aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/
---
{{< psd/tize >}}
## VectorPathDataResource class

Classe VectorPathDataResource. Cette ressource contient des informations sur le masque de calque vectoriel.

```csharp
public abstract class VectorPathDataResource : LayerResource, IVectorPathData
```

## Propriétés

| Nom | Description |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isdisabled/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est désactivée. |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isinverted/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est inversée. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isnotlinked/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance n'est pas liée. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Obtient la clé de ressource du calque. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/length/) { get; } | Obtient la longueur de la ressource du calque en octets. |
| [Paths](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/paths/) { get; set; } | Obtient ou définit les enregistrements de chemin. |
| virtual [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Obtient la version minimale de PSD requise pour la ressource du calque. 0 indique aucune restriction. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Obtient la signature. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/version/) { get; set; } | Obtient ou définit la version. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/save/)(StreamContainer, int) | Enregistre la ressource dans le conteneur de flux spécifié. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Renvoie une chaîne qui représente cette instance. |

## Exemples

L'exemple suivant démontre la prise en charge du traitement des masques vectoriels de calque. Comment fonctionne l'édition des chemins et comment Aspose.PSD dessine l'image finale.

```csharp
[C#]

string sourceFileName = "DifferentLayerMasks_Source.psd";
string exportPath = "DifferentLayerMasks_Export.psd";
string exportPathPng = "DifferentLayerMasks_Export.png";

// Lecture
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    // Apportez des modifications aux points du chemin vectoriel
    foreach (var layer in image.Layers)
    {
        foreach (var layerResource in layer.Resources)
        {
            var resource = layerResource as VectorPathDataResource;
            if (resource != null)
            {
                foreach (var pathRecord in resource.Paths)
                {
                    var bezierKnotRecord = pathRecord as BezierKnotRecord;
                    if (bezierKnotRecord != null)
                    {
                        Point p0 = bezierKnotRecord.Points[0];
                        bezierKnotRecord.Points[0] = bezierKnotRecord.Points[2];
                        bezierKnotRecord.Points[2] = p0;
                        break;
                    }
                }
            }
        }
    }

    // Exportation
    image.Save(exportPath);
    image.Save(exportPathPng, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### Voir aussi

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* interface [IVectorPathData](../../aspose.psd.fileformats.core.vectorpaths/ivectorpathdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


