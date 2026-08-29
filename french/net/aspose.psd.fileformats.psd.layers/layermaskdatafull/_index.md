---
title: "Classe LayerMaskDataFull"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerMaskDataFull classe. Définit la classe LayerMaskDataFull qui contient des informations sur les données du masque dans le calque du fichier PSD lorsque le calque possède à la fois des masques de calque et des masques vectoriels. Sinon, un LayerMaskDataShort est utilisé. L'ImageData contient le masque raster et le masque vectoriel rasterisé combinés. La longueur des octets de l'ImageData doit être égale aux propriétés MaskRectangle.Width  MaskRectangle.Height."
type: docs
weight: 2450
url: /fr/net/aspose.psd.fileformats.psd.layers/layermaskdatafull/
---
{{< psd/tize >}}
## LayerMaskDataFull class

Définit la classe LayerMaskDataFull qui contient des informations sur les données du masque dans le calque du fichier PSD lorsque le calque possède à la fois des masques de calque et des masques vectoriels. Sinon, un [`LayerMaskDataShort`](../layermaskdatashort/) est utilisé. L'ImageData contient le masque raster et le masque vectoriel rasterisé combinés. La longueur des octets de l'ImageData doit être égale aux propriétés MaskRectangle.Width * MaskRectangle.Height.

```csharp
public sealed class LayerMaskDataFull : LayerMaskData
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [LayerMaskDataFull](layermaskdatafull/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BackgroundColor](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/backgroundcolor/) { get; set; } | Obtient ou définit la couleur d'arrière-plan. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layermaskdata/bottom/) { get; set; } | Obtient ou définit la position du masque de calque inférieur. |
| [DataSize](../../aspose.psd.fileformats.psd.layers/layermaskdata/datasize/) { get; } | Obtient la taille des données du masque de calque. |
| [DefaultColor](../../aspose.psd.fileformats.psd.layers/layermaskdata/defaultcolor/) { get; set; } | Obtient ou définit la couleur par défaut. |
| [EnclosingBottom](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingbottom/) { get; set; } | Obtient ou définit la position inférieure du masque raster englobant dans le calque d'image PSD. |
| [EnclosingLeft](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingleft/) { get; set; } | Obtient ou définit la position gauche du masque raster englobant dans le calque du fichier PSD. |
| [EnclosingRight](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingright/) { get; set; } | Obtient ou définit la position droite du masque raster englobant dans le calque du fichier PSD. |
| [EnclosingTop](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/enclosingtop/) { get; set; } | Obtient ou définit la position supérieure du masque raster englobant dans le calque d'image PSD. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layermaskdata/flags/) { get; set; } | Obtient ou définit les indicateurs du masque de calque. |
| [ImageData](../../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) { get; set; } | Obtient ou définit les données du masque de calque (ou le masque combiné / final s'il y a un masque vectoriel) dans le fichier PSD. |
| [Left](../../aspose.psd.fileformats.psd.layers/layermaskdata/left/) { get; set; } | Obtient ou définit la position du masque de calque gauche. |
| [MaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) { get; set; } | Obtient ou définit le [`Rectangle`](../../aspose.psd/rectangle/) du masque de calque dans le fichier PSD. Il prend les propriétés gauche, droite, haut et bas et crée un [`Rectangle`](../../aspose.psd/rectangle/). |
| [RealFlags](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/realflags/) { get; set; } | Obtient ou définit les indicateurs du masque de calque utilisés pour le masque utilisateur / raster. Pour le masque vectoriel, la propriété Flags est utilisée. |
| [Right](../../aspose.psd.fileformats.psd.layers/layermaskdata/right/) { get; set; } | Obtient ou définit la position du masque de calque droit. |
| [Top](../../aspose.psd.fileformats.psd.layers/layermaskdata/top/) { get; set; } | Obtient ou définit la position du masque de calque supérieur. |
| [UserMaskData](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskdata/) { get; set; } | Obtient ou définit les données du masque utilisateur (raster) d'un calque dans le fichier PSD. (Il y a un masque vectoriel rasterisé dans la propriété MaskData). |
| [UserMaskRectangle](../../aspose.psd.fileformats.psd.layers/layermaskdatafull/usermaskrectangle/) { get; set; } | Obtient ou définit le rectangle du masque utilisateur (englobant) dans le calque d'image PSD. |

### Voir aussi

* class [LayerMaskData](../layermaskdata/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../)


