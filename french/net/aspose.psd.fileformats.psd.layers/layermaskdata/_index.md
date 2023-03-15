---
title: Class LayerMaskData
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskData classe. Définit la classe de base LayerMaskData qui contient des informations sur les données de masque de calque dans le fichier PSD. Cela peut aider à modifier les fichiers Adobe Photoshop par programmation et à automatiser lédition du format PSD. Si le calque na quun masque raster ImageData contient le raster masquer les octets de données. Si le calque na quun masque vectoriel ImageData contient les octets de données rastérisées en cache du masque vectoriel. Si le calque a à la fois des masques de calque et vectoriels ImageData contient le masque raster et le masque vectoriel rastérisé combinés. LeImageDataLa longueur en octets doit être égale à Largeur  Hauteur deMaskRectangle properties. Notez que la simple suppression/ajout/mise à jour de LayerMaskData ne suffit pas pour une sauvegarde correcte car les canaux ne sont pas mis à jour  bien quil puisse fournir un rendu correct. LeAddLayerMask méthode doit être utilisée pour cela.
type: docs
weight: 2240
url: /fr/net/aspose.psd.fileformats.psd.layers/layermaskdata/
---
## LayerMaskData class

Définit la classe de base LayerMaskData qui contient des informations sur les données de masque de calque dans le fichier PSD. Cela peut aider à modifier les fichiers Adobe® Photoshop® par programmation et à automatiser l'édition du format PSD. Si le calque n'a qu'un masque raster, ImageData contient le raster masquer les octets de données. Si le calque n'a qu'un masque vectoriel, ImageData contient les octets de données rastérisées (en cache) du masque vectoriel. Si le calque a à la fois des masques de calque et vectoriels, ImageData contient le masque raster et le masque vectoriel rastérisé combinés. Le[`ImageData`](./imagedata/)La longueur en octets doit être égale à Largeur * Hauteur de[`MaskRectangle`](./maskrectangle/) properties. Notez que la simple suppression/ajout/mise à jour de LayerMaskData ne suffit pas pour une sauvegarde correcte car les canaux ne sont pas mis à jour ; bien qu'il puisse fournir un rendu correct. Le[`AddLayerMask`](../layer/addlayermask/) méthode doit être utilisée pour cela.

```csharp
public abstract class LayerMaskData
```

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
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Obtient ou définit la bonne position du masque de calque. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Obtient ou définit la position du masque de calque supérieur. |

### Voir également

* espace de noms [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* Assemblée [Aspose.PSD](../../)


