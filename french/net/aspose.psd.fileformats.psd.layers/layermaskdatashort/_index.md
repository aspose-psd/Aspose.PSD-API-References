---
title: "Classe LayerMaskDataShort"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort class. Définit la classe LayerMaskDataShort qui contient des informations sur les données de masque dans le calque du fichier PSD lorsque le calque possède uniquement un masque raster ou vectoriel mais pas les deux. Sinon, un LayerMaskDataFull est utilisé. Si le calque possède uniquement un masque raster, l'ImageData contient les octets des données du masque raster. Si le calque possède uniquement un masque vectoriel, l'ImageData contient les octets des données du masque vectoriel rasterisées en cache. La longueur des octets de l'ImageData doit être égale à Width  Height des propriétés MaskRectangle."
type: docs
weight: 2460
url: /fr/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
{{< psd/tize >}}
## LayerMaskDataShort class

Définit la classe LayerMaskDataShort qui contient des informations sur les données de masque dans le calque du fichier PSD lorsque le calque possède uniquement un masque raster ou vectoriel mais pas les deux. Sinon, un [`LayerMaskDataFull`](../layermaskdatafull/) est utilisé. Si le calque possède uniquement un masque raster, l'ImageData contient les octets des données du masque raster. Si le calque possède uniquement un masque vectoriel, l'ImageData contient les octets des données du masque vectoriel rasterisées (en cache). La longueur des octets du [`ImageData`](../layermaskdata/imagedata/) doit être égale à Width * Height du [`MaskRectangle`](../layermaskdata/maskrectangle/) propriétés.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | Initialise une nouvelle instance de la classe `LayerMaskDataShort`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Obtient ou définit la position du masque de calque inférieur. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Obtient la taille des données du masque de calque. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Obtient ou définit la couleur par défaut. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Obtient ou définit les indicateurs du masque de calque. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Obtient ou définit les données du masque de calque (ou le masque combiné / final s'il y a un masque vectoriel) dans le fichier PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Obtient ou définit la position du masque de calque gauche. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Obtient ou définit le [`Rectangle`](../../aspose.psd/rectangle/) du masque de calque dans le fichier PSD. Il prend les propriétés gauche, droite, haut et bas et crée un [`Rectangle`](../../aspose.psd/rectangle/). |
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | Obtient ou définit le remplissage du masque de calque. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Obtient ou définit la position du masque de calque droit. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Obtient ou définit la position du masque de calque supérieur. |

### Voir aussi

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


