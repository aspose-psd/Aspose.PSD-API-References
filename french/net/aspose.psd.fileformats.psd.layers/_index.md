---
title: Aspose.PSD.FileFormats.Psd.Layers
second_title: Référence de l'API Aspose.PSD pour .NET
description: Lespace de noms contient des couches de format de fichier PSD.
type: docs
weight: 210
url: /fr/net/aspose.psd.fileformats.psd.layers/
---
L'espace de noms contient des couches de format de fichier PSD.

## Des classes

| Classer | La description |
| --- | --- |
| [BlendRange](./blendrange/) | La plage de fusion. |
| [ChannelInformation](./channelinformation/) | Les informations du canal. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | La section du masque de calque global. |
| [Layer](./layer/) | La couche psd. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | Les données des plages de fusion des calques. |
| [LayerGroup](./layergroup/) | Classe de couche de groupe |
| [LayerHashCalculator](./layerhashcalculator/) | Calculatrice de hachage pour les couches PSD. Il peut être utilisé pour trouver des couches égales ou différentes dans différents fichiers PSD |
| [LayerMaskData](./layermaskdata/) | Définit la classe de base LayerMaskData qui contient des informations sur les données de masque de calque dans le fichier PSD. Cela peut aider à modifier les fichiers Adobe® Photoshop® par programmation et à automatiser l'édition du format PSD. Si le calque n'a qu'un masque raster, ImageData contient le raster masquer les octets de données. Si le calque n'a qu'un masque vectoriel, ImageData contient les octets de données rastérisées (en cache) du masque vectoriel. Si le calque a à la fois des masques de calque et vectoriels, ImageData contient le masque raster et le masque vectoriel rastérisé combinés. Le[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)La longueur en octets doit être égale à Largeur * Hauteur de[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) properties. Notez que la simple suppression/ajout/mise à jour de LayerMaskData ne suffit pas pour une sauvegarde correcte car les canaux ne sont pas mis à jour ; bien qu'il puisse fournir un rendu correct. Le[`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) méthode doit être utilisée pour cela. |
| [LayerMaskDataFull](./layermaskdatafull/) | Définit la classe LayerMaskDataFull qui contient des informations sur les données de masque dans le fichier PSD layer lorsque le calque possède à la fois des masques de calque et vectoriels. Sinon, un[`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/) est utilisé. ImageData contient le masque raster et le masque vectoriel pixellisé combinés. La longueur en octets ImageData doit être égale aux propriétés MaskRectangle.Width * MaskRectangle.Height. |
| [LayerMaskDataShort](./layermaskdatashort/) | Définit la classe LayerMaskDataShort qui contient des informations sur les données de masque dans le fichier PSD layer lorsque le calque n'a qu'un masque raster ou vectoriel mais pas les deux. Sinon, un[`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/) est utilisé. Si le calque n'a qu'un masque raster, ImageData contient les octets de données du masque raster. Si le calque n'a qu'un masque vectoriel, ImageData contient les octets de données rastérisées (en cache) du masque vectoriel. Le[`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)La longueur en octets doit être égale à Largeur * Hauteur de[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) propriétés. |
| [LayerResource](./layerresource/) | Représente les informations de calque. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | Définir le registre des ressources de la couche pour le chargement des fichiers PSD. |
| [LinkedLayersManager](./linkedlayersmanager/) | Classe de gestionnaire de couches liées. |
| [SectionDividerLayer](./sectiondividerlayer/) | Le calque de séparation de section pour marquer les limites du dossier (groupe de calques). |
| [TextLayer](./textlayer/) | La classe de calque de texte |
## Interfaces

| Interface | La description |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | Interface de base pour les paramètres de remplissage |
| [ILayerResourceLoader](./ilayerresourceloader/) | Le chargeur de ressources de couche. |
## Énumération

| Énumération | La description |
| --- | --- |
| [LayerFlags](./layerflags/) | La couche flags |
| [LayerMaskFlags](./layermaskflags/) | Le masque de calque flags |


