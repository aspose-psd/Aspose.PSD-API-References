---
title: Class LayerMaskDataFull
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull classe. Définit la classe LayerMaskDataFull qui contient des informations sur les données de masque dans le fichier PSD layer lorsque le calque possède à la fois des masques de calque et vectoriels. Sinon unLayerMaskDataShort est utilisé. ImageData contient le masque raster et le masque vectoriel pixellisé combinés. La longueur en octets ImageData doit être égale aux propriétés MaskRectangle.Width  MaskRectangle.Height.
type: docs
weight: 2250
url: /fr/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
## LayerMaskDataFull class

Définit la classe LayerMaskDataFull qui contient des informations sur les données de masque dans le fichier PSD layer lorsque le calque possède à la fois des masques de calque et vectoriels. Sinon, un[`LayerMaskDataShort`](../layermaskdatashort/) est utilisé. ImageData contient le masque raster et le masque vectoriel pixellisé combinés. La longueur en octets ImageData doit être égale aux propriétés MaskRectangle.Width * MaskRectangle.Height.

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | Obtient ou définit la couleur d'arrière-plan. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Obtient ou définit la position du masque de calque inférieur. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Obtient la taille des données de masque de masque de calque. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Obtient ou définit la couleur par défaut. |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | Obtient ou définit la position du masque raster inférieur englobant dans la couche d'image PSD. |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | Obtient ou définit la position du masque raster gauche englobant dans la couche de fichier PSD. |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | Obtient ou définit la position du masque raster droit englobant dans la couche de fichier PSD. |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | Obtient ou définit la position supérieure englobante du masque raster dans la couche d'image PSD. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Obtient ou définit les indicateurs de masque de calque. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Obtient ou définit les données du masque de calque (ou le masque combiné/final s'il existe un masque vectoriel) dans le fichier PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Obtient ou définit la position du masque de calque gauche. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Obtient ou définit le masque[`Rectangle`](../../aspose.psd/rectangle/)du masque de calque dans le fichier PSD. Il prend les propriétés gauche, droite, haut et bas et crée[`Rectangle`](../../aspose.psd/rectangle/) |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | Obtient ou définit les indicateurs de masque de calque utilisés pour le masque utilisateur/raster. Pour le masque vectoriel, la propriété Flags est utilisée. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Obtient ou définit la bonne position du masque de calque. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Obtient ou définit la position du masque de calque supérieur. |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | Obtient ou définit les données de masque utilisateur (raster) d'un calque dans le fichier PSD. (Il y a un masque vectoriel classé dans la propriété MaskData). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | Obtient ou définit le rectangle de masque utilisateur (enveloppant) dans la couche d'image PSD.. |

### Voir également

* class [LayerMaskData](../layermaskdata/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* Assemblée [Aspose.PSD](../../)


