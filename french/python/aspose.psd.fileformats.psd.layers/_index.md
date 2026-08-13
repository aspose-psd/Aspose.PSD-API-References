---
title: "aspose.psd.fileformats.psd.layers"
type: docs
weight: 260
url: /fr/python-net/aspose.psd.fileformats.psd.layers/
---




## **Classes**
| **Classe** | **Description** |
| :- | :- |
| [ArtboardLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/artboardlayer/) | Classe du calque artboard. |
| [BlendRange](/psd/python-net/aspose.psd.fileformats.psd.layers/blendrange/) | La plage de fusion. |
| [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation/) | Les informations du canal. |
| [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | La section du masque de calque global. |
| [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint/) | Interface de base pour les paramètres de remplissage |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/) | Le chargeur de ressources de calque. |
| [IShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/ishapelayer/) | Décrit les propriétés du calque de forme. |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Le calque PSD. |
| [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata/) | Les données des plages de fusion du calque. |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | Classe de calque de groupe |
| [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) | Calculateur de hachage pour les calques PSD. Il peut être utilisé pour trouver des calques égaux ou différents dans différents fichiers PSD. |
| [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) | Définit la classe de base LayerMaskData qui contient des informations sur les données du masque de calque dans le fichier PSD.<br/>            Elle peut aider à modifier les fichiers Adobe® Photoshop® de manière programmatique et à automatiser l'édition du format PSD.<br/>            Si le calque ne possède qu'un masque raster, ImageData contient les octets de données du masque raster.<br/>            Si le calque ne possède qu'un masque vectoriel, ImageData contient les octets de données du masque vectoriel rasterisé (mis en cache).<br/>            Si le calque possède à la fois des masques de calque et vectoriels, ImageData contient le masque raster et le masque vectoriel rasterisé combinés.<br/>            La longueur en octets de [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) doit être égale à Largeur * Hauteur des propriétés de [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/).<br/>            Notez que simplement supprimer / ajouter / mettre à jour le LayerMaskData n'est pas suffisant pour un enregistrement correct<br/>            car les canaux ne sont pas mis à jour ; bien que cela puisse fournir un rendu correct.<br/>            La méthode [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) doit être utilisée à cet effet. |
| [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) | Définit la classe LayerMaskDataFull qui contient des informations sur les données du masque dans le calque du fichier PSD<br/>            lorsque le calque possède à la fois des masques de calque et vectoriels. Sinon, un [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) est utilisé.<br/>            L'ImageData contient le masque raster et le masque vectoriel rasterisé combinés.<br/>            La longueur en octets de l'ImageData doit être égale aux propriétés MaskRectangle.Width * MaskRectangle.Height. |
| [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) | Définit la classe LayerMaskDataShort qui contient des informations sur les données du masque dans le calque du fichier PSD<br/>            lorsque le calque ne possède qu'un masque raster ou vectoriel mais pas les deux. Sinon, un [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) est utilisé.<br/>            Si le calque ne possède qu'un masque raster, l'ImageData contient les octets de données du masque raster.<br/>            Si le calque ne possède qu'un masque vectoriel, l'ImageData contient les octets de données du masque vectoriel rasterisé (mis en cache).<br/>            La longueur en octets de [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) doit être égale à Largeur * Hauteur des propriétés de [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/). |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | Représente les informations du calque. |
| [LayerResourcesRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/) | Définit le registre des ressources de calque pour le chargement des fichiers PSD. |
| [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | Classe du gestionnaire de calques liés. |
| [SectionDividerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/) | Le calque de séparateur de section pour marquer les limites du dossier (groupe de calques). |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | Calque de forme. Encapsule la logique de travail avec le calque de forme et les ressources associées. |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | La classe de calque de texte |
## **Enumerations**
| **Enumeration** | **Description** |
| :- | :- |
| [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags/) | Les indicateurs du calque |
| [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags/) | Les indicateurs du masque de calque |
