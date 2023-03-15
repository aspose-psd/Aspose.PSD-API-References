---
title: Class LayerMaskDataShort
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataShort classe. Définit la classe LayerMaskDataShort qui contient des informations sur les données de masque dans le fichier PSD layer lorsque le calque na quun masque raster ou vectoriel mais pas les deux. Sinon unLayerMaskDataFull est utilisé. Si le calque na quun masque raster ImageData contient les octets de données du masque raster. Si le calque na quun masque vectoriel ImageData contient les octets de données rastérisées en cache du masque vectoriel. LeImageDataLa longueur en octets doit être égale à Largeur  Hauteur deMaskRectangle propriétés.
type: docs
weight: 2260
url: /fr/net/aspose.psd.fileformats.psd.layers/layermaskdatashort/
---
## LayerMaskDataShort class

Définit la classe LayerMaskDataShort qui contient des informations sur les données de masque dans le fichier PSD layer lorsque le calque n'a qu'un masque raster ou vectoriel mais pas les deux. Sinon, un[`LayerMaskDataFull`](../layermaskdatafull/) est utilisé. Si le calque n'a qu'un masque raster, ImageData contient les octets de données du masque raster. Si le calque n'a qu'un masque vectoriel, ImageData contient les octets de données rastérisées (en cache) du masque vectoriel. Le[`ImageData`](../layermaskdata/imagedata/)La longueur en octets doit être égale à Largeur * Hauteur de[`MaskRectangle`](../layermaskdata/maskrectangle/) propriétés.

```csharp
public sealed class LayerMaskDataShort : LayerMaskData
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [LayerMaskDataShort](layermaskdatashort/)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Obtient ou définit la position du masque de calque inférieur. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Obtient la taille des données de masque de masque de calque. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Obtient ou définit la couleur par défaut. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Obtient ou définit les indicateurs de masque de calque. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Obtient ou définit les données du masque de calque (ou le masque combiné/final s'il existe un masque vectoriel) dans le fichier PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Obtient ou définit la position du masque de calque gauche. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Obtient ou définit le masque[`Rectangle`](../../aspose.psd/rectangle/)du masque de calque dans le fichier PSD. Il prend les propriétés gauche, droite, haut et bas et crée[`Rectangle`](../../aspose.psd/rectangle/) |
| [Padding](../../aspose.psd.fileformats.psd.layers/layermaskdatashort/padding/) { get; set; } | Obtient ou définit le rembourrage du masque de calque. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Obtient ou définit la bonne position du masque de calque. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Obtient ou définit la position du masque de calque supérieur. |

### Voir également

* class [LayerMaskData](../layermaskdata/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* Assemblée [Aspose.PSD](../../)


