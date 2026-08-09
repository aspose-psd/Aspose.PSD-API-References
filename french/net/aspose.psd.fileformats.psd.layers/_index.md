---
title: "Aspose.PSD.FileFormats.Psd.Layers"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "L'espace de noms contient les calques du format de fichier PSD"
type: docs
weight: 230
url: /fr/net/aspose.psd.fileformats.psd.layers/
---
{{< psd/tize >}}
L'espace de noms contient les calques du format de fichier PSD.

## Classes

| Classe | Description |
| --- | --- |
| [ArtboardLayer](./artboardlayer/) | Classe de calque de plan de travail. |
| [BlendRange](./blendrange/) | La plage de fusion. |
| [ChannelInformation](./channelinformation/) | Les informations du canal. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | La section du masque de calque global. |
| [Layer](./layer/) | Le calque PSD. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | Les données des plages de fusion du calque. |
| [LayerGroup](./layergroup/) | Classe de calque de groupe |
| [LayerHashCalculator](./layerhashcalculator/) | Calculateur de hachage pour les calques PSD. Il peut être utilisé pour trouver des calques identiques ou différents dans différents fichiers PSD. |
| [LayerMaskData](./layermaskdata/) | Définit la classe de base LayerMaskData qui contient des informations sur les données du masque de calque dans le fichier PSD. Elle peut aider à modifier les fichiers Adobe® Photoshop® de manière programmatique et à automatiser l’édition du format PSD. Si le calque ne possède qu’un masque raster, l’ImageData contient les octets de données du masque raster. Si le calque ne possède qu’un masque vectoriel, l’ImageData contient les octets de données du masque vectoriel rasterisé (mis en cache). Si le calque possède à la fois des masques de calque et vectoriels, l’ImageData contient le masque raster et le masque vectoriel rasterisé combinés. La longueur en octets de [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) doit être égale à Largeur * Hauteur des propriétés de [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/). Notez que simplement supprimer / ajouter / mettre à jour le LayerMaskData n’est pas suffisant pour un enregistrement correct car les canaux ne sont pas mis à jour ; bien que cela puisse fournir un rendu correct. La méthode [`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) doit être utilisée à cet effet. |
| [LayerMaskDataFull](./layermaskdatafull/) | Définit la classe LayerMaskDataFull qui contient des informations sur les données du masque dans le calque du fichier PSD lorsque le calque possède à la fois des masques de calque et vectoriels. Sinon, un [`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/) est utilisé. L’ImageData contient le masque raster et le masque vectoriel rasterisé combinés. La longueur en octets de l’ImageData doit être égale aux propriétés MaskRectangle.Width * MaskRectangle.Height. |
| [LayerMaskDataShort](./layermaskdatashort/) | Définit la classe LayerMaskDataShort qui contient des informations sur les données du masque dans le calque du fichier PSD lorsque le calque ne possède qu’un masque raster ou vectoriel mais pas les deux. Sinon, un [`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/) est utilisé. Si le calque ne possède qu’un masque raster, l’ImageData contient les octets de données du masque raster. Si le calque ne possède qu’un masque vectoriel, l’ImageData contient les octets de données du masque vectoriel rasterisé (mis en cache). La longueur en octets de [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) doit être égale à Largeur * Hauteur des propriétés de [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/). |
| [LayerResource](./layerresource/) | Représente les informations du calque. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | Définit le registre des ressources de calque pour le chargement des fichiers PSD. |
| [LinkedLayersManager](./linkedlayersmanager/) | Classe du gestionnaire de calques liés. |
| [SectionDividerLayer](./sectiondividerlayer/) | Le calque de séparateur de section pour marquer les limites du dossier (groupe de calques). |
| [ShapeLayer](./shapelayer/) | Calque de forme. Encapsule la logique de travail avec le calque de forme et les ressources associées. |
| [TextLayer](./textlayer/) | La classe de calque de texte |
## Interfaces

| Interface | Description |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | Interface de base pour les paramètres de remplissage |
| [ILayerResourceLoader](./ilayerresourceloader/) | Le chargeur de ressources de calque. |
| [IShapeLayer](./ishapelayer/) | Décrit les propriétés du calque de forme. |
## Énumération

| Énumération | Description |
| --- | --- |
| [LayerFlags](./layerflags/) | Les indicateurs du calque |
| [LayerMaskFlags](./layermaskflags/) | Les indicateurs du masque de calque |


