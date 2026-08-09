---
title: "Classe LayerMaskData"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData classe. Définit la classe de base LayerMaskData qui contient des informations sur les données du masque de calque dans le fichier PSD. Elle peut aider à modifier les fichiers Adobe Photoshop de manière programmatique et à automatiser l'édition du format PSD. Si le calque ne possède qu'un masque raster, l'ImageData contient les octets des données du masque raster. Si le calque ne possède qu'un masque vectoriel, l'ImageData contient les octets des données du masque vectoriel rasterisées en cache. Si le calque possède à la fois des masques de calque et des masques vectoriels, l'ImageData contient le masque raster et le masque vectoriel rasterisé combinés. La longueur des octets de l'ImageData doit être égale à la largeur * hauteur des propriétés MaskRectangle. Notez que simplement supprimer / ajouter / mettre à jour le LayerMaskData n'est pas suffisant pour un enregistrement correct car les canaux ne sont pas mis à jour, bien que cela puisse fournir un rendu correct. La méthode AddLayerMask doit être utilisée pour cela."
type: docs
weight: 2440
url: /fr/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
{{< psd/tize >}}
## LayerMaskData class

Définit la classe de base LayerMaskData qui contient des informations sur les données du masque de calque dans le fichier PSD. Elle peut aider à modifier les fichiers Adobe® Photoshop® de manière programmatique et à automatiser l'édition du format PSD. Si le calque ne possède qu'un masque raster, l'ImageData contient les octets des données du masque raster. Si le calque ne possède qu'un masque vectoriel, l'ImageData contient les octets des données du masque vectoriel rasterisé (en cache). Si le calque possède à la fois des masques de calque et des masques vectoriels, l'ImageData contient le masque raster et le masque vectoriel rasterisé combinés. Les octets de [`ImageData`](./imagedata/) doivent avoir une longueur égale à la largeur * hauteur des propriétés [`MaskRectangle`](./maskrectangle/). Notez que simplement supprimer / ajouter / mettre à jour le LayerMaskData n'est pas suffisant pour un enregistrement correct car les canaux ne sont pas mis à jour ; bien que cela puisse fournir un rendu correct. La méthode [`AddLayerMask`](../layer/addlayermask/) doit être utilisée pour cela.

```csharp
public abstract class LayerMaskData
```

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
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Obtient ou définit la position du masque de calque droit. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Obtient ou définit la position du masque de calque supérieur. |

### Voir aussi

* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


