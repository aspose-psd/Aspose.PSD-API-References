---
title: "PsdImage"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Définit la classe PsdImage qui permet de charger, modifier et enregistrer des fichiers PSD ainsi que de mettre à jour les propriétés, ajouter des filigranes, effectuer des opérations graphiques ou convertir un format de fichier en un autre."
type: docs
weight: 14
url: /fr/java/com.aspose.psd.fileformats.psd/psdimage/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage)
```
public final class PsdImage extends RasterCachedImage
```

Définit la classe PsdImage qui permet de charger, modifier, enregistrer des fichiers PSD ainsi que de mettre à jour les propriétés, ajouter des filigranes, effectuer des opérations graphiques ou convertir un format de fichier en un autre. Aspose.PSD prend en charge l’importation en tant que calque et l’exportation vers les formats suivants : Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb ainsi que l’exportation vers Pdf avec texte sélectionnable.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PsdImage(String path)](#PsdImage-java.lang.String-) | Initialise une nouvelle instance de la classe [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) à partir du chemin spécifié d’une image raster (pas d’image PSD dans le chemin). |
| [PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.lang.String-short-short-short-int-short-) | Initialise une nouvelle instance de la classe [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) à partir du chemin spécifié d’une image raster (pas d’image PSD dans le chemin) avec les paramètres du constructeur. |
| [PsdImage(InputStream stream)](#PsdImage-java.io.InputStream-) | Initialise une nouvelle instance de la classe [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) à partir du chemin spécifié d’une image raster (pas d’image PSD dans le flux). |
| [PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-java.io.InputStream-short-short-short-int-short-) | Initialise une nouvelle instance de la classe [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) à partir du chemin spécifié d’une image raster (pas d’image PSD dans le flux) avec les paramètres du constructeur. |
| [PsdImage(RasterImage rasterImage)](#PsdImage-com.aspose.psd.RasterImage-) | Initialise une nouvelle instance de la classe [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) à partir d’une image raster existante (pas d’image PSD) avec le mode couleur RVB, 4 canaux de 8 bits par canal et aucune compression. |
| [PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-) | Initialise une nouvelle instance de la classe [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) à partir d’une image raster existante (pas d’image PSD) avec les paramètres du constructeur. |
| [PsdImage(int width, int height)](#PsdImage-int-int-) | Initialise une nouvelle instance de la classe [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) avec la largeur et la hauteur spécifiées. |
| [PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-) | Initialise une nouvelle instance de la classe [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) avec les paramètres de largeur, hauteur, palette, mode couleur, nombre de canaux, longueur de bits des canaux et mode de compression spécifiés. |
## Champs

| Champ | Description |
| --- | --- |
| [DefaultStubEncodingName_internalized](#DefaultStubEncodingName-internalized) | Le nom d’encodage par défaut |
| [DefaultVersion](#DefaultVersion) | La version PSD par défaut. |
| [OnCreate_internalized](#OnCreate-internalized) | Se produit lorsque l'image a été chargée |
| [OnLoad_internalized](#OnLoad-internalized) | Se produit lorsque l'image a été chargée par createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Se produit lorsque l'image a été chargée ou enregistrée |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Se produit lorsque le crédit a été utilisé |
| [SyncLayersRoot_internalized](#SyncLayersRoot-internalized) | L’objet qui peut être utilisé pour synchroniser l’accès aux calques. |
| [horizontalResolution](#horizontalResolution) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addBlackWhiteAdjustmentLayer()](#addBlackWhiteAdjustmentLayer--) | Ajoute le calque de réglage noir et blanc. |
| [addBrightnessContrastAdjustmentLayer(int brightness, int contrast)](#addBrightnessContrastAdjustmentLayer-int-int-) | Ajoute le calque de réglage luminosité/contraste. |
| [addChannelMixerAdjustmentLayer()](#addChannelMixerAdjustmentLayer--) | Ajoute le calque de réglage du mélangeur de canaux avec les paramètres par défaut |
| [addColorBalanceAdjustmentLayer()](#addColorBalanceAdjustmentLayer--) | Ajoute le calque de réglage de la balance des couleurs. |
| [addCurvesAdjustmentLayer()](#addCurvesAdjustmentLayer--) | Ajoute le calque de réglage des courbes. |
| [addExposureAdjustmentLayer()](#addExposureAdjustmentLayer--) |  |
| [addExposureAdjustmentLayer(float exposure)](#addExposureAdjustmentLayer-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset)](#addExposureAdjustmentLayer-float-float-) |  |
| [addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)](#addExposureAdjustmentLayer-float-float-float-) | Ajoute le calque de réglage de l’exposition. |
| [addGradientMapAdjustmentLayer()](#addGradientMapAdjustmentLayer--) | Ajoute le calque de réglage GradientMap. |
| [addHueSaturationAdjustmentLayer()](#addHueSaturationAdjustmentLayer--) | Ajoute le calque de réglage teinte/saturation. |
| [addInvertAdjustmentLayer()](#addInvertAdjustmentLayer--) | Ajoute un calque de réglage d’inversion. |
| [addLayer(Layer layer)](#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Ajoute le calque. |
| [addLayerGroup(String groupName, int index, boolean startBehaviour)](#addLayerGroup-java.lang.String-int-boolean-) | Ajoute le groupe de calques. |
| [addLayer_internalized(Layer layer, int index)](#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-) | Ajoute le calque à l'indice. |
| [addLevelsAdjustmentLayer()](#addLevelsAdjustmentLayer--) | Ajoute le calque de réglage Levels. |
| [addPhotoFilterLayer(Color color)](#addPhotoFilterLayer-com.aspose.psd.Color-) | Ajoute le calque de filtre photo. |
| [addPosterizeAdjustmentLayer()](#addPosterizeAdjustmentLayer--) | Ajoute le calque de réglage Posterize. |
| [addRegularLayer()](#addRegularLayer--) | Ajoute un nouveau calque ordinaire. |
| [addSelectiveColorAdjustmentLayer()](#addSelectiveColorAdjustmentLayer--) | Ajoute le calque de réglage couleur sélective. |
| [addShapeLayer()](#addShapeLayer--) | Ajoute un calque Shape vide. |
| [addTextLayer(String text, Rectangle rect)](#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-) | Ajoute un nouveau calque Text. |
| [addThresholdAdjustmentLayer()](#addThresholdAdjustmentLayer--) | Ajoute le calque de réglage Threshold. |
| [addVibranceAdjustmentLayer()](#addVibranceAdjustmentLayer--) | Ajoute le calque de réglage Vibrance. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Ajustement de la luminosité d'une image. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Contraste de l'image |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Correction gamma d'une image. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Correction gamma d'une image. |
| [beginResize_internalized(int newWidth, int newHeight)](#beginResize-internalized-int-int-) | Démarre le processus de redimensionnement. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage par image intégrale |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage par image intégrale |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Binarisation d'une image avec un seuil prédéfini |
| [binarizeOtsu()](#binarizeOtsu--) | Binarisation d'une image avec le seuillage d'Otsu |
| [cacheData()](#cacheData--) | Met en cache les données et garantit qu'aucun chargement supplémentaire de données ne sera effectué depuis le DataStreamSupporter.DataStreamContainer sous-jacent. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Détermine si l'image peut être chargée depuis le flux spécifié. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-) | Détermine si l'image peut être chargée depuis le flux spécifié et éventuellement en utilisant les loadOptions spécifiés. |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Détermine si l'image peut être chargée depuis le chemin de fichier spécifié. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.psd.LoadOptions-) | Détermine si l'image peut être chargée depuis le chemin de fichier spécifié et éventuellement en utilisant les options d'ouverture spécifiées. |
| [canLoadInternal_internalized(System.IO.Stream stream)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.psd.ImageOptionsBase-) | Détermine si l'image peut être enregistrée au format de fichier spécifié représenté par les options d'enregistrement fournies. |
| [close()](#close--) | Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. |
| [convert(PsdOptions newOptions)](#convert-com.aspose.psd.imageoptions.PsdOptions-) | Convertit ce format d'image en celui spécifié dans les options. |
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Convertit en aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Crée une nouvelle image en utilisant les options de création spécifiées. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Crée une nouvelle image en utilisant les images spécifiées comme pages |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Crée une nouvelle image avec les images spécifiées comme pages. |
| [createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-) | Crée la nouvelle instance de la classe [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)](#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-) |  |
| [crop(Rectangle rectangle)](#crop-com.aspose.psd.Rectangle-) | Recadrage de l'image. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Recadrer l'image avec des décalages. |
| [dispose()](#dispose--) | Libère l'instance actuelle. |
| [dither(int ditheringMethod, int bitsCount)](#dither-int-int-) | Effectue le dithering sur l'image actuelle. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.psd.IColorPalette-) | Effectue le dithering sur l'image actuelle. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [doCrop_internalized(Rectangle rectangle)](#doCrop-internalized-com.aspose.psd.Rectangle-) | Recadrage de l'image. |
| [doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)](#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-) | Redimensionne l'image. |
| [doResize_internalized(int newWidth, int newHeight, int resizeType)](#doResize-internalized-int-int-int-) |  |
| [doRotate(float angle, boolean resizeProportionally, Color backgroundColor)](#doRotate-float-boolean-com.aspose.psd.Color-) |  |
| [doRotateFlip_internalized(int rotateFlipType)](#doRotateFlip-internalized-int-) | Fait pivoter, retourner ou pivoter et retourner l'image. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Filtre le rectangle spécifié. |
| [flattenImage()](#flattenImage--) | Aplatisse tous les calques. |
| [getActiveLayer()](#getActiveLayer--) | Obtient ou définit le calque actif. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Obtient un pixel d'image ARGB 32 bits. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Obtient une valeur indiquant si la palette d'ajustement automatique. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| [getBackgroundContents_internalized()](#getBackgroundContents-internalized--) | Obtient ou définit la couleur d'arrière-plan. |
| [getBitsPerChannel()](#getBitsPerChannel--) | Obtient le nombre de bits par canal. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtient le nombre de bits par pixel de l'image. |
| [getBounds()](#getBounds--) | Obtient les limites de l'image. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtient l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| [getChannelsCount()](#getChannelsCount--) | Obtient le nombre de canaux PSD. |
| [getClass()](#getClass--) |  |
| [getCmykColorProfile()](#getCmykColorProfile--) | Obtient ou définit le profil couleur CMYK pour les images PSD CMYK. |
| [getColorMode()](#getColorMode--) | Obtient ou définit le mode couleur. |
| [getCompression()](#getCompression--) | Obtient la méthode de compression. |
| [getContainer()](#getContainer--) | Obtient le conteneur Image. |
| [getCurrentOptions_internalized()](#getCurrentOptions-internalized--) | Obtient les options d'image actuelles. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Obtient le flux de données de l'objet. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Obtient la palette d'ajustement approfondi. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Obtient le tableau de pixels ARGB 32 bits par défaut. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Obtient les options par défaut. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Obtient le tableau de pixels par défaut en utilisant le chargeur de pixels partiel. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Obtient le tableau de données brutes par défaut en utilisant le chargeur de pixels partiel. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Obtient le tableau de données brutes par défaut. |
| [getDefaultReplacementFont_internalized()](#getDefaultReplacementFont-internalized--) | Obtient ou définit la police de remplacement par défaut. |
| [getDisposed()](#getDisposed--) | Obtient une valeur indiquant si cette instance est libérée. |
| [getFileFormat()](#getFileFormat--) | Obtient une valeur du format de fichier |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Obtient le format de fichier. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Obtient le format de fichier. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Obtient le format de fichier. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Obtient le rectangle qui s'adapte à l'image actuelle. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Obtient le rectangle qui s'adapte à l'image actuelle. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Obtient la palette à partir d'emplacements spécifiques au format |
| [getGlobalAngle()](#getGlobalAngle--) | Obtient ou définit l'angle global. |
| [getGlobalLayerMaskInfo()](#getGlobalLayerMaskInfo--) | Obtient les informations du masque de calque global. |
| [getGlobalLayerResources()](#getGlobalLayerResources--) | Obtient ou définit les ressources globales de calque. |
| [getGrayColorProfile()](#getGrayColorProfile--) | Obtient ou définit le profil couleur GRAY (monochrome) pour les images PSD en niveaux de gris. |
| [getHeight()](#getHeight--) | Obtient la hauteur de l'image. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Obtient ou définit la résolution horizontale, en pixels par pouce, de ce [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [getImageLayers_internalized()](#getImageLayers-internalized--) | Obtient ou définit les calques PSD. |
| [getImageOpacity()](#getImageOpacity--) | Obtient l'opacité de cette image. |
| [getImageResources()](#getImageResources--) | Obtient ou définit les ressources d'image PSD. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | Obtient le transformateur de données interne. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Obtient le moniteur d'interruption. |
| [getLayerAndMask_internalized()](#getLayerAndMask-internalized--) | Obtient le calque et le masque. |
| [getLayers()](#getLayers--) | Obtient ou définit les calques PSD. |
| [getLinkedLayersManager()](#getLinkedLayersManager--) | Obtient le gestionnaire de calques liés. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | Obtient ou définit l'allocation maximale autorisée pour l'enregistrement de rotation partielle. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Obtient le gestionnaire de mémoire. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Obtient la date et l'heure de la dernière modification de l'image de ressource. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getOriginalOptions()](#getOriginalOptions--) | Obtient les options basées sur les paramètres du fichier original. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Obtient l'image peignable. |
| [getPalette()](#getPalette--) | Obtient la palette de couleurs. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Obtient un pixel d'image. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Crée le cache de polices privé. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtient les informations du gestionnaire d'événement de progression. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Obtient les informations du gestionnaire d'événement de progression. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Obtient une hauteur proportionnelle. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Obtient une largeur proportionnelle. |
| [getPsdHeader_internalized()](#getPsdHeader-internalized--) | Obtient ou définit l'en-tête PSD. |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Obtient ou définit le convertisseur de couleur personnalisé |
| [getRawDataFormat()](#getRawDataFormat--) | Obtient le format de données brutes. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Obtient ou définit l'index de secours à utiliser lorsque l'index de palette est hors limites |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Obtient ou définit le convertisseur de couleur indexée |
| [getRawLineSize()](#getRawLineSize--) | Obtient la taille brute de la ligne en octets. |
| [getRgbColorProfile()](#getRgbColorProfile--) | Obtient ou définit le profil couleur RVB pour les images PSD CMYK. |
| [getRotateMode()](#getRotateMode--) | Obtient ou définit le mode de rotation. |
| [getSize()](#getSize--) | Obtient la taille de l'image. |
| [getSkewAngle()](#getSkewAngle--) | Obtient l'angle d'inclinaison. |
| [getSmartObjectProvider()](#getSmartObjectProvider--) | Obtient le fournisseur d'objets intelligents. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Obtient le chemin du fichier de l'image source si elle existe. |
| [getSyncExclusiveOperation_internalized()](#getSyncExclusiveOperation-internalized--) |  |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | Obtient la racine de synchronisation. |
| [getTimeline()](#getTimeline--) | Obtient la Chronologie ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-)) de ce [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [getTransparentColor()](#getTransparentColor--) | Obtient la couleur transparente de l'image. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Obtient ou définit une valeur indiquant s'il faut mettre à jour les métadonnées XMP. |
| [getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)](#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-) | Obtient les ressources mises à jour avec un tout nouveau bloc de ressources. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Obtient une valeur indiquant si l'objet utilise une stratégie d'optimisation de la mémoire |
| [getUseRawData()](#getUseRawData--) | Obtient ou définit une valeur indiquant s'il faut utiliser le chargement de données brutes lorsque celui-ci est disponible. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | Obtient la palette utilisée. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Obtient la licence venture. |
| [getVersion()](#getVersion--) | Obtient ou définit la version. |
| [getVerticalResolution()](#getVerticalResolution--) | Obtient ou définit la résolution verticale, en pixels par pouce, de ce [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [getWidth()](#getWidth--) | Obtient la largeur de l'image. |
| [getXmpData()](#getXmpData--) | Obtient ou définit les métadonnées XMP. |
| [grayscale()](#grayscale--) | Transformation d'une image en sa représentation en niveaux de gris |
| [hasAlpha()](#hasAlpha--) | Obtient ou définit la résolution verticale, en pixels par pouce, de ce RasterImage. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Obtient une valeur indiquant si l'image possède une couleur d'arrière-plan. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Obtient ou définit une valeur indiquant si cette instance d'image a changé après le chargement. |
| [hasTransparencyData()](#hasTransparencyData--) | Obtient ou définit une valeur indiquant si le premier canal alpha contient les données de transparence pour le résultat fusionné lors de la spécification des données des calques. |
| [hasTransparentColor()](#hasTransparentColor--) | Obtient une valeur indiquant si l'image possède une couleur transparente. |
| [hashCode()](#hashCode--) |  |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Obtient ou définit la valeur maximale de progression |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Indique la progression. |
| [insertLayerAfter_internalized(Layer layer, Layer layerToInsert)](#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | Insère le calque après le calque spécifié avec toutes les préparations |
| [isCached()](#isCached--) | Obtient une valeur indiquant si les données de l'image sont actuellement en cache. |
| [isFlatten()](#isFlatten--) | Obtient une valeur indiquant si l'image PSD est aplatie. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Obtient une valeur indiquant si le chargement de données brutes est disponible. |
| [isUsePalette()](#isUsePalette--) | Obtient une valeur indiquant si la palette de l'image est utilisée. |
| [isUsePhotoshopCompatibilityMode_internalized()](#isUsePhotoshopCompatibilityMode-internalized--) |  |
| [load(InputStream stream)](#load-java.io.InputStream-) | Charge une nouvelle image depuis le flux spécifié. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.psd.LoadOptions-) | Charge une nouvelle image depuis le flux spécifié. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Charge une nouvelle image depuis le flux spécifié. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-) | Charge une nouvelle image depuis le flux spécifié. |
| [load(String filePath)](#load-java.lang.String-) | Charge une nouvelle image depuis le fichier spécifié. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.psd.LoadOptions-) | Charge une nouvelle image depuis le fichier spécifié. |
| [loadArgb32Pixels(Rectangle rectangle)](#loadArgb32Pixels-com.aspose.psd.Rectangle-) | Charge des pixels ARGB 32 bits. |
| [loadArgb64Pixels(Rectangle rectangle)](#loadArgb64Pixels-com.aspose.psd.Rectangle-) | Charge des pixels ARGB 64 bits. |
| [loadCmyk32Pixels(Rectangle rectangle)](#loadCmyk32Pixels-com.aspose.psd.Rectangle-) | Charge des pixels au format CMYK. |
| [loadCmykPixels(Rectangle rectangle)](#loadCmykPixels-com.aspose.psd.Rectangle-) | Charge des pixels au format CMYK. |
| [loadInternal_internalized(System.IO.Stream stream)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)](#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-) |  |
| [loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Charge partiellement des pixels ARGB 32 bits par paquets. |
| [loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)](#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-) | Charge des pixels partiellement par paquets. |
| [loadPixels(Rectangle rectangle)](#loadPixels-com.aspose.psd.Rectangle-) | Charge des pixels. |
| [loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Charge les données d'image brutes en utilisant le mécanisme de traitement partiel. |
| [loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)](#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-) | Charge des données brutes. |
| [load_internalized(System.IO.Stream stream)](#load-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [load_internalized(System.IO.Stream stream, long startPosition)](#load-internalized-com.aspose.ms.System.IO.Stream-long-) | Charge une nouvelle image depuis le flux spécifié. |
| [load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)](#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-) | Charge une nouvelle image depuis le flux spécifié. |
| [mergeLayers(Layer bottomLayer, Layer topLayer)](#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-) | Fusionne les calques. |
| [normalizeAngle()](#normalizeAngle--) | Normalise l'angle. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Normalise l'angle. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Invoquez lorsque le conteneur de cette [Image](../../com.aspose.psd/image) a été défini. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Lit toute la ligne de numérisation selon l'index de ligne de numérisation spécifié. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Lit toute la ligne de numérisation selon l'index de ligne de numérisation spécifié. |
| [removeGlobalTextEngineResource_internalized()](#removeGlobalTextEngineResource-internalized--) | Supprime la ressource du moteur de texte global - La méthode est utilisée pour certains fichiers PSD à calques de texte, qui ne peuvent pas être ouverts dans Adobe Photoshop après traitement (principalement lié aux calques de texte avec polices manquantes). |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Redimensionne l'image. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Redimensionne l'image. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensionne l'image. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Redimensionne la hauteur proportionnellement. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-) | Redimensionne la hauteur proportionnellement. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Redimensionne la hauteur proportionnellement. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Redimensionne la largeur proportionnellement. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-) | Redimensionne la largeur proportionnellement. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Redimensionne la largeur proportionnellement. |
| [resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)](#resizeWithScale-internalized-double-double-int-) | Redimensionne le calque avec l'échelle inverse spécifiée. |
| [rotate(float angle)](#rotate-float-) | Faire pivoter l'image autour du centre. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.psd.Color-) | Faire pivoter l'image autour du centre. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) |  |
| [save()](#save--) | Enregistre les données de l'image dans le flux sous-jacent. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Enregistre les données de l'objet dans le flux spécifié. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Enregistre les données de l'objet dans le flux spécifié. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-) | Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement. |
| [save(String filePath)](#save-java.lang.String-) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-) | Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement. |
| [saveArgb32Pixels(Rectangle rectangle, int[] pixels)](#saveArgb32Pixels-com.aspose.psd.Rectangle-int---) | Enregistre les pixels ARGB 32 bits. |
| [saveCmyk32Pixels(Rectangle rectangle, int[] pixels)](#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---) | Enregistre les pixels. |
| [saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)](#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---) | Enregistre les pixels. |
| [savePixels(Rectangle rectangle, Color[] pixels)](#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---) | Enregistre les pixels. |
| [saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)](#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Enregistre les données brutes. |
| [saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)](#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---) | Enregistre les données de l'image dans le flux spécifié en utilisant les options d'enregistrement et les limites spécifiées. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement. |
| [setActiveLayer(Layer value)](#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-) | Obtient ou définit le calque actif. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Définit un pixel ARGB 32 bits de l'image pour la position spécifiée. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Définit une valeur indiquant si la palette s'ajuste automatiquement. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Obtient ou définit une valeur indiquant si l'image a une couleur d'arrière-plan. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| [setBackgroundContents_internalized(RawColor value)](#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Obtient ou définit la couleur d'arrière-plan. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.psd.sources.StreamSource-) | Obtient ou définit le profil couleur CMYK pour les images PSD CMYK. |
| [setColorMode(short value)](#setColorMode-short-) | Obtient ou définit le mode couleur. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Définit le conteneur Image. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Définit le chargeur de données directement. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Définit le flux de données de l'objet. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Définit la palette dans les emplacements spécifiques au format |
| [setGlobalAngle(int value)](#setGlobalAngle-int-) | L'angle global. |
| [setGlobalLayerResources(LayerResource[] value)](#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | Obtient ou définit les ressources globales de calque. |
| [setGrayColorProfile(StreamSource value)](#setGrayColorProfile-com.aspose.psd.sources.StreamSource-) | Le profil couleur GRAY (monochrome) pour les images PSD en niveaux de gris. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Obtient ou définit la résolution horizontale, en pixels par pouce, de ce [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Définit une valeur indiquant si [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Obtient ou définit une valeur indiquant si cette instance d'image a changé après le chargement. |
| [setImageResources(ResourceBlock[] value)](#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---) | Obtient ou définit les ressources d'image PSD. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | Définit le transformateur de données interne. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Définit le moniteur d'interruption. |
| [setLayers(Layer[] value)](#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---) | Obtient ou définit les calques PSD. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | Obtient ou définit l'allocation maximale autorisée pour l'enregistrement de rotation partielle. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Définit le gestionnaire de mémoire. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Définit la palette de couleurs. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Définit la palette d'image. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Définit un pixel d'image pour la position spécifiée. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Obtient ou définit le convertisseur de couleur personnalisé |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Obtient ou définit l'index de secours à utiliser lorsque l'index de palette est hors limites |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | Obtient ou définit le convertisseur de couleur indexée |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Définit la résolution pour ce [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.psd.sources.StreamSource-) | Obtient ou définit le profil couleur RVB pour les images PSD CMYK. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | Obtient ou définit le mode de rotation. |
| [setTransparencyData(boolean value)](#setTransparencyData-boolean-) | Obtient ou définit une valeur indiquant si le premier canal alpha contient les données de transparence pour le résultat fusionné lors de la spécification des données des calques. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Obtient une valeur indiquant si l'image possède une couleur transparente. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Obtient la couleur transparente de l'image. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Obtient ou définit une valeur indiquant s'il faut mettre à jour les métadonnées XMP. |
| [setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)](#setUsePhotoshopCompatibilityMode-internalized-boolean-) |  |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Obtient ou définit une valeur indiquant s'il faut utiliser le chargement de données brutes lorsque celui-ci est disponible. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Définit la licence d'entreprise. |
| [setVersion(int value)](#setVersion-int-) | Obtient ou définit la version. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Obtient ou définit la résolution verticale, en pixels par pouce, de ce [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage). |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Obtient ou définit les métadonnées XMP. |
| [toBitmap()](#toBitmap--) | Convertit l'image raster en bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
### PsdImage(String path) {#PsdImage-java.lang.String-}
```
public PsdImage(String path)
```


Initialise une nouvelle instance de la classe [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) à partir du chemin spécifié d'une image raster (pas d'image PSD dans le chemin). Utilisé pour initialiser l'image PSD avec les paramètres par défaut - Mode couleur - RVB, 4 canaux, 8 bits par canal, Compression - Raw.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | Le chemin à partir duquel charger les données de pixels et de palette et avec lequel initialiser. |

### PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.lang.String-short-short-short-int-short-}
```
public PsdImage(String path, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Initialise une nouvelle instance de la classe [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) à partir du chemin spécifié d’une image raster (pas d’image PSD dans le chemin) avec les paramètres du constructeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| chemin | java.lang.String | Le chemin à partir duquel charger les données de pixels et de palette et avec lequel initialiser. |
| colorMode | short | Le mode couleur. |
| channelBitDepth | short | La profondeur de bits PSD par canal. |
| channels | short | Le nombre de canaux PSD. |
| psdVersion | int | La version PSD. |
| compression | short | La compression à utiliser. |

### PsdImage(InputStream stream) {#PsdImage-java.io.InputStream-}
```
public PsdImage(InputStream stream)
```


Initialise une nouvelle instance de la classe [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) à partir du chemin spécifié d'une image raster (pas d'image PSD dans le flux). Utilisée pour initialiser une image PSD avec les paramètres par défaut - Mode couleur - rgb, 4 canaux, 8 bits par canal, Compression - Raw.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Le flux à partir duquel charger les données de pixels et de palette et l'utiliser pour l'initialisation. |

### PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-java.io.InputStream-short-short-short-int-short-}
```
public PsdImage(InputStream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Initialise une nouvelle instance de la classe [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) à partir du chemin spécifié d’une image raster (pas d’image PSD dans le flux) avec les paramètres du constructeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Le flux à partir duquel charger les données de pixels et de palette et l'utiliser pour l'initialisation. |
| colorMode | short | Le mode couleur. |
| channelBitDepth | short | La profondeur de bits PSD par canal. |
| channels | short | Le nombre de canaux PSD. |
| psdVersion | int | La version PSD. |
| compression | short | La compression à utiliser. |

### PsdImage(RasterImage rasterImage) {#PsdImage-com.aspose.psd.RasterImage-}
```
public PsdImage(RasterImage rasterImage)
```


Initialise une nouvelle instance de la classe [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) à partir d’une image raster existante (pas d’image PSD) avec le mode couleur RVB, 4 canaux de 8 bits par canal et aucune compression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | L'image à partir de laquelle charger les données de pixels et de palette et l'utiliser pour l'initialisation. |

### PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-com.aspose.psd.RasterImage-short-short-short-int-short-}
```
public PsdImage(RasterImage rasterImage, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Initialise une nouvelle instance de la classe [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) à partir d’une image raster existante (pas d’image PSD) avec les paramètres du constructeur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | L'image à partir de laquelle charger les données de pixels et de palette et l'utiliser pour l'initialisation. |
| colorMode | short | Le mode couleur. |
| channelBitDepth | short | La profondeur de bits PSD par canal. |
| channels | short | Le nombre de canaux PSD. |
| psdVersion | int | La version PSD. |
| compression | short | La compression à utiliser. |

### PsdImage(int width, int height) {#PsdImage-int-int-}
```
public PsdImage(int width, int height)
```


Initialise une nouvelle instance de la classe [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) avec la largeur et la hauteur spécifiées. Utilisée pour initialiser une image PSD vide.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur | int | La largeur de l'image. |
| hauteur | int | La hauteur de l'image. |

### PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#PsdImage-int-int-com.aspose.psd.IColorPalette-short-short-short-int-short-}
```
public PsdImage(int width, int height, IColorPalette colorPalette, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```


Initialise une nouvelle instance de la classe [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) avec la largeur, la hauteur, la palette, le mode couleur, le nombre de canaux et la longueur de bits des canaux ainsi que les paramètres du mode de compression spécifiés. Utilisée pour initialiser une image PSD vide.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur | int | La largeur de l'image. |
| hauteur | int | La hauteur de l'image. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La palette de couleurs. |
| colorMode | short | Le mode couleur. |
| channelBitDepth | short | La profondeur de bits PSD par canal. |
| channels | short | Le nombre de canaux PSD. |
| psdVersion | int | La version PSD. |
| compression | short | La compression à utiliser. |

### DefaultStubEncodingName_internalized {#DefaultStubEncodingName-internalized}
```
public static final String DefaultStubEncodingName_internalized
```


Le nom d’encodage par défaut

### DefaultVersion {#DefaultVersion}
```
public static final int DefaultVersion
```


La version PSD par défaut.

### OnCreate_internalized {#OnCreate-internalized}
```
public static final Event<AfterCreate> OnCreate_internalized
```


Se produit lorsque l'image a été chargée

### OnLoad_internalized {#OnLoad-internalized}
```
public static final Event<AfterLoad> OnLoad_internalized
```


Se produit lorsque l'image a été chargée par createFirstSupportedLoader

### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Se produit lorsque l'image a été chargée ou enregistrée

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Se produit lorsque le crédit a été utilisé

### SyncLayersRoot_internalized {#SyncLayersRoot-internalized}
```
public final Object SyncLayersRoot_internalized
```


L’objet qui peut être utilisé pour synchroniser l’accès aux calques.

### horizontalResolution {#horizontalResolution}
```
public double horizontalResolution
```


### addBlackWhiteAdjustmentLayer() {#addBlackWhiteAdjustmentLayer--}
```
public final BlackWhiteAdjustmentLayer addBlackWhiteAdjustmentLayer()
```


Ajoute le calque de réglage noir et blanc.

**Returns:**
[BlackWhiteAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer) - The created black white adjustment layer.
### addBrightnessContrastAdjustmentLayer(int brightness, int contrast) {#addBrightnessContrastAdjustmentLayer-int-int-}
```
public final BrightnessContrastLayer addBrightnessContrastAdjustmentLayer(int brightness, int contrast)
```


Ajoute le calque de réglage luminosité/contraste.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| luminosité | int | La luminosité. |
| contraste | int | Le contraste. |

**Returns:**
[BrightnessContrastLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer) - Created brightness/contrast layer
### addChannelMixerAdjustmentLayer() {#addChannelMixerAdjustmentLayer--}
```
public final ChannelMixerLayer addChannelMixerAdjustmentLayer()
```


Ajoute le calque de réglage du mélangeur de canaux avec les paramètres par défaut

**Returns:**
[ChannelMixerLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer) - Added Channel Mixer Layer
### addColorBalanceAdjustmentLayer() {#addColorBalanceAdjustmentLayer--}
```
public final ColorBalanceAdjustmentLayer addColorBalanceAdjustmentLayer()
```


Ajoute le calque de réglage de la balance des couleurs.

**Returns:**
[ColorBalanceAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer) - A newly created color balance layer.
### addCurvesAdjustmentLayer() {#addCurvesAdjustmentLayer--}
```
public final CurvesLayer addCurvesAdjustmentLayer()
```


Ajoute le calque de réglage des courbes.

**Returns:**
[CurvesLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer) - Created [CurvesLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer) Layer
### addExposureAdjustmentLayer() {#addExposureAdjustmentLayer--}
```
public final ExposureLayer addExposureAdjustmentLayer()
```




**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure) {#addExposureAdjustmentLayer-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| exposure | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset) {#addExposureAdjustmentLayer-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| exposure | float |  |
| décalage | float |  |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer)
### addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection) {#addExposureAdjustmentLayer-float-float-float-}
```
public final ExposureLayer addExposureAdjustmentLayer(float exposure, float offset, float gammaCorrection)
```


Ajoute le calque de réglage de l’exposition.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| exposure | float | L'exposition. |
| décalage | float | Le décalage. |
| gammaCorrection | float | La correction gamma. |

**Returns:**
[ExposureLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer) - Created Exposure Adjustment Layer
### addGradientMapAdjustmentLayer() {#addGradientMapAdjustmentLayer--}
```
public final GradientMapLayer addGradientMapAdjustmentLayer()
```


Ajoute le calque de réglage GradientMap.

**Returns:**
[GradientMapLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer) - GradientMap instance.
### addHueSaturationAdjustmentLayer() {#addHueSaturationAdjustmentLayer--}
```
public final HueSaturationLayer addHueSaturationAdjustmentLayer()
```


Ajoute le calque de réglage teinte/saturation.

**Returns:**
[HueSaturationLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer) - A newly created hue/saturation layer.
### addInvertAdjustmentLayer() {#addInvertAdjustmentLayer--}
```
public final InvertAdjustmentLayer addInvertAdjustmentLayer()
```


Ajoute un calque de réglage d’inversion.

**Returns:**
[InvertAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer) - The created invert layer
### addLayer(Layer layer) {#addLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void addLayer(Layer layer)
```


Ajoute le calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Le calque. |

### addLayerGroup(String groupName, int index, boolean startBehaviour) {#addLayerGroup-java.lang.String-int-boolean-}
```
public final LayerGroup addLayerGroup(String groupName, int index, boolean startBehaviour)
```


Ajoute le groupe de calques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| groupName | java.lang.String | Nom du groupe. |
| index | int | L'index du calque après lequel insérer. |
| startBehaviour | booléen | si défini sur  true  [start behaviour] alors le groupe sera en état ouvert au démarrage, sinon en état minimisé. |

**Returns:**
[LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) - Opening group layer
### addLayer_internalized(Layer layer, int index) {#addLayer-internalized-com.aspose.psd.fileformats.psd.layers.Layer-int-}
```
public void addLayer_internalized(Layer layer, int index)
```


Ajoute le calque à l'indice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Le calque. |
| index | int | L'index. |

### addLevelsAdjustmentLayer() {#addLevelsAdjustmentLayer--}
```
public final LevelsLayer addLevelsAdjustmentLayer()
```


Ajoute le calque de réglage Levels.

**Returns:**
[LevelsLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer) - A newly created Levels layer
### addPhotoFilterLayer(Color color) {#addPhotoFilterLayer-com.aspose.psd.Color-}
```
public final PhotoFilterLayer addPhotoFilterLayer(Color color)
```


Ajoute le calque de filtre photo.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | La couleur. |

**Returns:**
[PhotoFilterLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer) - Created PhotoFilter Layer
### addPosterizeAdjustmentLayer() {#addPosterizeAdjustmentLayer--}
```
public final PosterizeLayer addPosterizeAdjustmentLayer()
```


Ajoute le calque de réglage Posterize.

**Returns:**
[PosterizeLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer) - PosterizeLayer instance.
### addRegularLayer() {#addRegularLayer--}
```
public final Layer addRegularLayer()
```


Ajoute un nouveau calque ordinaire.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Created regular layer.
### addSelectiveColorAdjustmentLayer() {#addSelectiveColorAdjustmentLayer--}
```
public final SelectiveColorLayer addSelectiveColorAdjustmentLayer()
```


Ajoute le calque de réglage couleur sélective.

**Returns:**
[SelectiveColorLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer) - The created selective color adjustment layer.
### addShapeLayer() {#addShapeLayer--}
```
public final ShapeLayer addShapeLayer()
```


Ajoutez un calque Shape vide. Sans chemins. Ils doivent être ajoutés au calque Shape avant l'enregistrement.

**Returns:**
[ShapeLayer](../../com.aspose.psd.fileformats.psd.layers/shapelayer) - ShapeLayer instance.
### addTextLayer(String text, Rectangle rect) {#addTextLayer-java.lang.String-com.aspose.psd.Rectangle-}
```
public final TextLayer addTextLayer(String text, Rectangle rect)
```


Ajoute un nouveau calque Text.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Le texte du calque. |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle du calque. |

**Returns:**
[TextLayer](../../com.aspose.psd.fileformats.psd.layers/textlayer) - Created text layer.
### addThresholdAdjustmentLayer() {#addThresholdAdjustmentLayer--}
```
public final ThresholdLayer addThresholdAdjustmentLayer()
```


Ajoute le calque de réglage Threshold.

**Returns:**
[ThresholdLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer) - The created Threshold adjustment layer.
### addVibranceAdjustmentLayer() {#addVibranceAdjustmentLayer--}
```
public final VibranceLayer addVibranceAdjustmentLayer()
```


Ajoute le calque de réglage Vibrance.

**Returns:**
[VibranceLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer) - A newly created Vibrance layer.
### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Ajustement de la luminosité d'une image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| luminosité | int | Valeur de luminosité. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Contraste de l'image

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| contraste | float | Valeur de contraste (dans la plage [-100; 100]) |

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Correction gamma d'une image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gamma | float | Coefficient gamma pour les canaux rouge, vert et bleu |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Correction gamma d'une image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gammaRed | float | Gamma du coefficient du canal rouge |
| gammaGreen | float | Gamma du coefficient du canal vert |
| gammaBlue | float | Gamma du coefficient du canal bleu |

### beginResize_internalized(int newWidth, int newHeight) {#beginResize-internalized-int-int-}
```
public IResizeController beginResize_internalized(int newWidth, int newHeight)
```


Démarre le processus de redimensionnement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur de l'image. |
| newHeight | int | La nouvelle hauteur de l'image. |

**Returns:**
com.aspose.internal.IResizeController - Le contrôleur de redimensionnement.
### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage par image intégrale

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightnessDifference | double | La différence de luminosité entre le pixel et la moyenne d'une fenêtre de s x s pixels centrée autour de ce pixel. |

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage par image intégrale

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| brightnessDifference | double | La différence de luminosité entre le pixel et la moyenne d'une fenêtre de s x s pixels centrée autour de ce pixel. |
| windowSize | int | La taille de la fenêtre de s x s pixels centrée autour de ce pixel |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Binarisation d'une image avec un seuil prédéfini

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| threshold | byte | Valeur du seuil. Si la valeur de gris correspondante d'un pixel est supérieure au seuil, une valeur de 255 lui sera attribuée, sinon 0. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Binarisation d'une image avec le seuillage d'Otsu

### cacheData() {#cacheData--}
```
public void cacheData()
```


Met en cache les données et garantit qu'aucun chargement supplémentaire de données ne sera effectué depuis le DataStreamSupporter.DataStreamContainer sous-jacent.

### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


Détermine si l'image peut être chargée depuis le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Le flux à charger depuis. |

**Returns:**
boolean -  true  si l'image peut être chargée depuis le flux spécifié ; sinon,  false .
### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


Détermine si l'image peut être chargée depuis le flux spécifié et éventuellement en utilisant les loadOptions spécifiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Le flux à charger depuis. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Les options de chargement. |

**Returns:**
boolean -  true  si l'image peut être chargée depuis le flux spécifié ; sinon,  false .
### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


Détermine si l'image peut être chargée depuis le chemin de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier. |

**Returns:**
booléen -  vrai  si l'image peut être chargée depuis le fichier spécifié ; sinon,  faux .
### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


Détermine si l'image peut être chargée depuis le chemin de fichier spécifié et éventuellement en utilisant les options d'ouverture spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Les options de chargement. |

**Returns:**
booléen -  vrai  si l'image peut être chargée depuis le fichier spécifié ; sinon,  faux .
### canLoadInternal_internalized(System.IO.Stream stream) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
booléen
### canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#canLoadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static boolean canLoadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
booléen
### canSave(ImageOptionsBase options) {#canSave-com.aspose.psd.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


Détermine si l'image peut être enregistrée au format de fichier spécifié représenté par les options d'enregistrement fournies.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options d'enregistrement à utiliser. |

**Returns:**
booléen -  vrai  si l'image peut être enregistrée au format de fichier spécifié représenté par les options d'enregistrement fournies ; sinon,  faux .
### close() {#close--}
```
public void close()
```


Implémente l'interface Closable et peut être utilisée dans l'instruction try-with-resources depuis JDK 1.7. Cette méthode appelle simplement la méthode dispose.

### convert(PsdOptions newOptions) {#convert-com.aspose.psd.imageoptions.PsdOptions-}
```
public final void convert(PsdOptions newOptions)
```


Convertit ce format d'image en celui spécifié dans les options.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newOptions | [PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) | Les nouvelles options. |

### convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle) {#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-}
```
public ApsPage convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)
```


Convertit en aps.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options. |
| mode | int | Le mode. |
| clippingRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle de découpage. |

**Returns:**
com.aspose.foundation.rendering.ApsPage - La page APS.
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.psd.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


Crée une nouvelle image en utilisant les options de création spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options d'image. |
| largeur | int | La largeur. |
| hauteur | int | La hauteur. |

**Returns:**
[Image](../../com.aspose.psd/image) - The newly created image.
### create(Image[] images) {#create-com.aspose.psd.Image---}
```
public static Image create(Image[] images)
```


Crée une nouvelle image en utilisant les images spécifiées comme pages

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Les images. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### create(Image[] images, boolean disposeImages) {#create-com.aspose.psd.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


Crée une nouvelle image avec les images spécifiées comme pages.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.psd/image) | Les images. |
| disposeImages | booléen | si défini sur  vrai  [supprimer les images]. |

**Returns:**
[Image](../../com.aspose.psd/image) - The Image as IMultipageImage
### createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.internal.fileformats.psd.sections.ColorData-com.aspose.internal.fileformats.psd.sections.ImageResources-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-com.aspose.internal.fileformats.psd.sections.ImageData-com.aspose.psd.IColorPalette-int-com.aspose.psd.LoadOptions-boolean-}
```
public static PsdImage createInstance_internalized(PsdHeader psdHeader, ColorData colorData, ImageResources imageResources, LayerAndMaskInfo layerAndMaskInfo, ImageData imageData, IColorPalette colorPalette, int version, LoadOptions loadOptions, boolean noLayerLoad)
```


Crée la nouvelle instance de la classe [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| psdHeader | com.aspose.internal.fileformats.psd.sections.PsdHeader | L'en-tête PSD. |
| colorData | com.aspose.internal.fileformats.psd.sections.ColorData | Les données de couleur. |
| imageResources | com.aspose.internal.fileformats.psd.sections.ImageResources | Les ressources d'image. |
| layerAndMaskInfo | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo | Les informations du calque et du masque. |
| imageData | com.aspose.internal.fileformats.psd.sections.ImageData | Les données d'image. |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La palette de couleurs. |
| version | int | La version PSD. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Les options de chargement. |
| noLayerLoad | booléen | Pas de chargement de calque |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) - Returns the new instance of the [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) class.
### createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height) {#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-}
```
public static IPartialProcessor createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| redimensionneur | com.aspose.internal.rotaters.PartialRotater |  |
| pixelsSaver | com.aspose.internal.IPixelsSaver |  |
| largeur | int |  |
| hauteur | int |  |

**Returns:**
com.aspose.internal.IPartialProcessor
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static PsdImage create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
### create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression) {#create-internalized-com.aspose.ms.System.IO.Stream-short-short-short-int-short-}
```
public static PsdImage create_internalized(System.IO.Stream stream, short colorMode, short channelBitDepth, short channels, int psdVersion, short compression)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| colorMode | short |  |
| channelBitDepth | short |  |
| channels | short |  |
| psdVersion | int |  |
| compression | short |  |

**Returns:**
[PsdImage](../../com.aspose.psd.fileformats.psd/psdimage)
### crop(Rectangle rectangle) {#crop-com.aspose.psd.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recadrage de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Recadrer l'image avec des décalages.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| leftShift | int | Le décalage à gauche. |
| rightShift | int | Le décalage à droite. |
| topShift | int | Le décalage en haut. |
| bottomShift | int | Le décalage en bas. |

### dispose() {#dispose--}
```
public final void dispose()
```


Libère l'instance actuelle.

### dither(int ditheringMethod, int bitsCount) {#dither-int-int-}
```
public void dither(int ditheringMethod, int bitsCount)
```


Effectue le dithering sur l'image actuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ditheringMethod | int | La méthode de tramage. |
| bitsCount | int | Le nombre final de bits pour le tramage. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.psd.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Effectue le dithering sur l'image actuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ditheringMethod | int | La méthode de tramage. |
| bitsCount | int | Le nombre final de bits pour le tramage. |
| customPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La palette personnalisée pour le tramage. |

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### doCrop_internalized(Rectangle rectangle) {#doCrop-internalized-com.aspose.psd.Rectangle-}
```
public void doCrop_internalized(Rectangle rectangle)
```


Recadrage de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle. |

### doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings) {#doResize-internalized-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void doResize_internalized(int newWidth, int newHeight, ImageResizeSettings settings)
```


Redimensionne l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Les paramètres de redimensionnement. |

### doResize_internalized(int newWidth, int newHeight, int resizeType) {#doResize-internalized-int-int-int-}
```
public void doResize_internalized(int newWidth, int newHeight, int resizeType)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int |  |
| newHeight | int |  |
| resizeType | int |  |

### doRotate(float angle, boolean resizeProportionally, Color backgroundColor) {#doRotate-float-boolean-com.aspose.psd.Color-}
```
public void doRotate(float angle, boolean resizeProportionally, Color backgroundColor)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float |  |
| resizeProportionally | booléen |  |
| backgroundColor | [Color](../../com.aspose.psd/color) |  |

### doRotateFlip_internalized(int rotateFlipType) {#doRotateFlip-internalized-int-}
```
public void doRotateFlip_internalized(int rotateFlipType)
```


Fait pivoter, retourner ou pivoter et retourner l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotateFlipType | int | Le type de rotation et retournement. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Filtre le rectangle spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle. |
| options | [FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase) | Les options. |

### flattenImage() {#flattenImage--}
```
public final void flattenImage()
```


Aplatisse tous les calques.

### getActiveLayer() {#getActiveLayer--}
```
public final Layer getActiveLayer()
```


Obtient ou définit le calque actif.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
### getArgb32Pixel(int x, int y) {#getArgb32Pixel-int-int-}
```
public int getArgb32Pixel(int x, int y)
```


Obtient un pixel d'image ARGB 32 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | L'emplacement x du pixel. |
| y | int | L'emplacement y du pixel. |

**Returns:**
int - Le pixel ARGB 32 bits pour l'emplacement spécifié.
### getAutoAdjustPalette() {#getAutoAdjustPalette--}
```
public boolean getAutoAdjustPalette()
```


Obtient une valeur indiquant si la palette d'ajustement automatique.

**Returns:**
booléen -  true  si l'ajustement automatique de la palette est activé ; sinon,  false .
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Obtient ou définit une valeur pour la couleur d'arrière-plan.

**Returns:**
[Color](../../com.aspose.psd/color)
### getBackgroundContents_internalized() {#getBackgroundContents-internalized--}
```
public final RawColor getBackgroundContents_internalized()
```


Obtient ou définit la couleur d'arrière-plan. Elle peut être vue sous les objets transparents.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getBitsPerChannel() {#getBitsPerChannel--}
```
public final int getBitsPerChannel()
```


Obtient le nombre de bits par canal.

Valeur : les bits par canal.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtient le nombre de bits par pixel de l'image.

Valeur : Le nombre de bits par pixel de l'image.

**Returns:**
int
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Obtient les limites de l'image.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The image bounds.
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Obtient l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes.

Valeur : L'indice de taille du tampon, en mégaoctets. Une valeur non positive signifie aucune limitation de mémoire pour les tampons internes.

**Returns:**
int - l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes.
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


Obtient le nombre de canaux PSD.

Valeur : le nombre de canaux PSD.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCmykColorProfile() {#getCmykColorProfile--}
```
public final StreamSource getCmykColorProfile()
```


Obtient ou définit le profil couleur CMYK pour les images PSD CMYK. Doit être associé à RgbColorProfile pour une conversion de couleur correcte.

Valeur : le profil couleur CMYK.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Obtient ou définit le mode couleur.

Valeur : le mode couleur.

**Returns:**
short
### getCompression() {#getCompression--}
```
public final short getCompression()
```


Obtient la méthode de compression.

Valeur: la compression.

**Returns:**
short
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Obtient le conteneur Image.

Valeur : Le conteneur d'Image.

Si cette propriété n'est pas nulle, cela indique que l'image est contenue dans une autre image.

**Returns:**
[Image](../../com.aspose.psd/image)
### getCurrentOptions_internalized() {#getCurrentOptions-internalized--}
```
public final PsdOptions getCurrentOptions_internalized()
```


Obtient les options d'image actuelles.

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions) - Current options for PSD image
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Obtient le flux de données de l'objet.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDeeplyAdjustPalette_internalized() {#getDeeplyAdjustPalette-internalized--}
```
public boolean getDeeplyAdjustPalette_internalized()
```


Obtient la palette d'ajustement approfondi.

**Returns:**
boolean - La palette d'ajustement profond.
### getDefaultArgb32Pixels(Rectangle rectangle) {#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] getDefaultArgb32Pixels(Rectangle rectangle)
```


Obtient le tableau de pixels ARGB 32 bits par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle pour obtenir les pixels. |

**Returns:**
int[] - Le tableau de pixels par défaut.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Obtient les options par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| args | java.lang.Object[] | Les arguments. |

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - Default options
### getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Obtient le tableau de pixels par défaut en utilisant le chargeur de pixels partiel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle pour obtenir les pixels. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | Le chargeur partiel de pixels. |

### getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-}
```
public void getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)
```


Obtient le tableau de données brutes par défaut en utilisant le chargeur de pixels partiel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle pour obtenir les pixels. |
| partialRawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Le chargeur partiel de données brutes. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Les paramètres des données brutes. |

### getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings) {#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public byte[] getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)
```


Obtient le tableau de données brutes par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle pour obtenir les données brutes. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Les paramètres des données brutes. |

**Returns:**
byte[] - Le tableau de données brutes par défaut.
### getDefaultReplacementFont_internalized() {#getDefaultReplacementFont-internalized--}
```
public final String getDefaultReplacementFont_internalized()
```


Obtient ou définit la police de remplacement par défaut. Si la police de remplacement est définie, elle sera utilisée pour le rendu. Nous avons besoin de cette méthode pour le support interne.

**Returns:**
java.lang.String - Le nom de la police de remplacement
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Obtient une valeur indiquant si cette instance est libérée.

**Returns:**
boolean -  true  si libéré ; sinon,  false .
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Obtient une valeur du format de fichier

**Returns:**
long
### getFileFormat(System.IO.Stream stream) {#getFileFormat-com.aspose.ms.System.IO.Stream-}
```
public static long getFileFormat(System.IO.Stream stream)
```


Obtient le format de fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | stream | com.aspose.ms.System.IO.Stream | Le flux. |

--------------------

Le format de fichier déterminé ne signifie pas que l'image spécifiée peut être chargée. Utilisez l'une des surcharges de la méthode CanLoad pour déterminer si le flux peut être chargé. |

**Returns:**
long - Le format de fichier déterminé.
### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


Obtient le format de fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | stream | java.io.InputStream | Le flux. |

Le format de fichier déterminé ne signifie pas que l'image spécifiée peut être chargée. Utilisez l'une des surcharges de la méthode CanLoad pour déterminer si le flux peut être chargé. |

**Returns:**
long - Le format de fichier déterminé.
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


Obtient le format de fichier.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | filePath | java.lang.String | Le chemin du fichier. |

Le format de fichier déterminé ne signifie pas que l'image spécifiée peut être chargée. Utilisez l'une des surcharges de la méthode CanLoad pour déterminer si le fichier peut être chargé. |

**Returns:**
long - Le format de fichier déterminé.
### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


Obtient le rectangle qui s'adapte à l'image actuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle pour obtenir le rectangle d'ajustement. |
| largeur | int | La largeur de l'objet. |
| hauteur | int | La hauteur de l'objet. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


Obtient le rectangle qui s'adapte à l'image actuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle pour obtenir le rectangle d'ajustement. |
| pixels | int[] | Les pixels ARGB 32 bits. |
| largeur | int | La largeur de l'objet. |
| hauteur | int | La hauteur de l'objet. |

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


Obtient la palette à partir d'emplacements spécifiques au format

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGlobalAngle() {#getGlobalAngle--}
```
public final int getGlobalAngle()
```


Obtient ou définit l'angle global.

**Returns:**
int
### getGlobalLayerMaskInfo() {#getGlobalLayerMaskInfo--}
```
public final GlobalLayerMaskInfo getGlobalLayerMaskInfo()
```


Obtient les informations du masque de calque global.

**Returns:**
[GlobalLayerMaskInfo](../../com.aspose.psd.fileformats.psd.layers/globallayermaskinfo)
### getGlobalLayerResources() {#getGlobalLayerResources--}
```
public final LayerResource[] getGlobalLayerResources()
```


Obtient ou définit les ressources globales de calque.

Valeur : les ressources globales du calque.

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getGrayColorProfile() {#getGrayColorProfile--}
```
public final StreamSource getGrayColorProfile()
```


Obtient ou définit le profil couleur GRAY (monochrome) pour les images PSD en niveaux de gris.

Valeur : le profil couleur GRAY (monochrome).

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient la hauteur de l'image.

Valeur : la hauteur de l'image.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Obtient ou définit la résolution horizontale, en pixels par pouce, de ce [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Returns:**
double
### getImageLayers_internalized() {#getImageLayers-internalized--}
```
public final Layer[] getImageLayers_internalized()
```


Obtient ou définit les calques PSD.

Valeur: Les calques PSD.

--------------------

Notez que s'il n'y a pas de calques, les autres informations liées dans la section des informations de calque et de masque ne seront pas conservées (masques de calque, ressources et etc.).

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Obtient l'opacité de cette image.

**Returns:**
float - La valeur d'opacité entre 0,0 (entièrement transparent) et 1,0 (entièrement opaque).
### getImageResources() {#getImageResources--}
```
public final ResourceBlock[] getImageResources()
```


Obtient ou définit les ressources d'image PSD.

Valeur: Les ressources d'image PSD.

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[]
### getInnerDataTransformer_internalized() {#getInnerDataTransformer-internalized--}
```
public final IInnerDataTransformer getInnerDataTransformer_internalized()
```


Obtient le transformateur de données interne.

Valeur : le transformateur de données interne.

**Returns:**
com.aspose.internal.IInnerDataTransformer - le transformateur de données interne.
### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Obtient le moniteur d'interruption.

**Returns:**
[InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) - the interrupt monitor.
### getLayerAndMask_internalized() {#getLayerAndMask-internalized--}
```
public final LayerAndMaskInfo getLayerAndMask_internalized()
```


Obtient le calque et le masque.

Valeur: Le calque et le masque.

**Returns:**
com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo
### getLayers() {#getLayers--}
```
public final Layer[] getLayers()
```


Obtient ou définit les calques PSD.

Valeur: Les calques PSD.

--------------------

Notez que s'il n'y a pas de calques, les autres informations liées dans la section des informations de calque et de masque ne seront pas conservées (masques de calque, ressources et etc.).

**Returns:**
com.aspose.psd.fileformats.psd.layers.Layer[]
### getLinkedLayersManager() {#getLinkedLayersManager--}
```
public final LinkedLayersManager getLinkedLayersManager()
```


Obtient le gestionnaire de calques liés.

**Returns:**
[LinkedLayersManager](../../com.aspose.psd.fileformats.psd.layers/linkedlayersmanager)
### getMaxAllowedAllocationForPartialRotateSave_internalized() {#getMaxAllowedAllocationForPartialRotateSave-internalized--}
```
public static int getMaxAllowedAllocationForPartialRotateSave_internalized()
```


Obtient ou définit l'allocation maximale autorisée pour l'enregistrement de rotation partielle.

**Returns:**
int - L'allocation maximale autorisée pour l'enregistrement de rotation partielle.
### getMemoryMgr_internalized() {#getMemoryMgr-internalized--}
```
public MemMgr getMemoryMgr_internalized()
```


Obtient le gestionnaire de mémoire.

Valeur : le gestionnaire de mémoire.

**Returns:**
com.aspose.internal.memorymanagement.MemMgr - le gestionnaire de mémoire.
### getModifyDate(boolean useDefault) {#getModifyDate-boolean-}
```
public Date getModifyDate(boolean useDefault)
```


Obtient la date et l'heure de la dernière modification de l'image de ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| useDefault | booléen | si défini sur  true  utilise les informations de FileInfo comme valeur par défaut. |

**Returns:**
java.util.Date - La date et l'heure de la dernière modification de l'image ressource.
### getModifyDate_internalized(boolean useDefault) {#getModifyDate-internalized-boolean-}
```
public System.DateTime getModifyDate_internalized(boolean useDefault)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| useDefault | booléen |  |

**Returns:**
com.aspose.ms.System.DateTime
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Obtient les options basées sur les paramètres du fichier original. Cela peut être utile pour conserver la profondeur de couleur et les autres paramètres de l'image originale inchangés. Par exemple, si nous chargeons une image PNG noir-et-blanc avec 1 bit par pixel puis l'enregistrons en utilisant la méthode  DataStreamSupporter.Save(string) , l'image PNG de sortie avec 8 bits par pixel sera produite. Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre à la méthode  Image.Save(string, ImageOptionsBase)  en tant que deuxième paramètre.

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - The options based on the original file settings.
### getPaintableImage_internalized(ImageOptionsBase paintableOptions) {#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-}
```
public Image getPaintableImage_internalized(ImageOptionsBase paintableOptions)
```


Obtient l'image peignable.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| paintableOptions | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) |  |

**Returns:**
[Image](../../com.aspose.psd/image) - the paintable image.
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Obtient la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette.
### getPixel(int x, int y) {#getPixel-int-int-}
```
public Color getPixel(int x, int y)
```


Obtient un pixel d'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | L'emplacement x du pixel. |
| y | int | L'emplacement y du pixel. |

**Returns:**
[Color](../../com.aspose.psd/color) - The pixel color for the specified location.
### getPremultiplyComponents() {#getPremultiplyComponents--}
```
public boolean getPremultiplyComponents()
```


Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés.

**Returns:**
boolean -  true  si les composants de l'image doivent être prémultipliés ; sinon,  false .
### getPrivateFontCache_internalized() {#getPrivateFontCache-internalized--}
```
public final PalPrivateFontCache getPrivateFontCache_internalized()
```


Crée le cache de polices privé.

**Returns:**
com.aspose.foundation.pal.PalPrivateFontCache - Le cache de polices privées.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public final ProgressEventHandler getProgressEventHandler()
```


Obtient les informations du gestionnaire d'événement de progression.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


Obtient les informations du gestionnaire d'événement de progression.

Valeur : Les informations du gestionnaire d'événement de progression.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


Obtient une hauteur proportionnelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur | int | La largeur. |
| hauteur | int | La hauteur. |
| newWidth | int | La nouvelle largeur. |

**Returns:**
int - La hauteur proportionnelle.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


Obtient une largeur proportionnelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur | int | La largeur. |
| hauteur | int | La hauteur. |
| newHeight | int | La nouvelle hauteur. |

**Returns:**
int - La largeur proportionnelle.
### getPsdHeader_internalized() {#getPsdHeader-internalized--}
```
public final PsdHeader getPsdHeader_internalized()
```


Obtient ou définit l'en-tête PSD.

Valeur: L'en-tête PSD.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getRawCustomColorConverter() {#getRawCustomColorConverter--}
```
public IColorConverter getRawCustomColorConverter()
```


Obtient ou définit le convertisseur de couleur personnalisé

**Returns:**
[IColorConverter](../../com.aspose.psd/icolorconverter) - The custom color converter
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Obtient le format de données brutes.

Valeur: Le format de données brutes.

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getRawDataSettings() {#getRawDataSettings--}
```
public RawDataSettings getRawDataSettings()
```


Obtient les paramètres de données brutes actuels. Notez que lors de l'utilisation de ces paramètres, les données sont chargées sans conversion.

**Returns:**
[RawDataSettings](../../com.aspose.psd/rawdatasettings)
### getRawFallbackIndex() {#getRawFallbackIndex--}
```
public int getRawFallbackIndex()
```


Obtient ou définit l'index de secours à utiliser lorsque l'index de palette est hors limites

**Returns:**
int - L'index de secours à utiliser lorsque l'index de palette est hors limites
### getRawIndexedColorConverter() {#getRawIndexedColorConverter--}
```
public IIndexedColorConverter getRawIndexedColorConverter()
```


Obtient ou définit le convertisseur de couleur indexée

**Returns:**
[IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) - The indexed color converter
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Obtient la taille brute de la ligne en octets.

**Returns:**
int - La taille brute de la ligne en octets.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public final StreamSource getRgbColorProfile()
```


Obtient ou définit le profil couleur RGB pour les images PSD CMJN. Doit être associé à CmykColorProfile pour une conversion de couleur correcte.

Valeur: Le profil couleur RGB.

**Returns:**
[StreamSource](../../com.aspose.psd.sources/streamsource)
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


Obtient ou définit le mode de rotation.

**Returns:**
int - Le mode de rotation.
### getSize() {#getSize--}
```
public Size getSize()
```


Obtient la taille de l'image.

**Returns:**
[Size](../../com.aspose.psd/size) - The image size.
### getSkewAngle() {#getSkewAngle--}
```
public final float getSkewAngle()
```


Obtient l'angle d'inclinaison. Cette méthode s'applique aux documents texte numérisés, pour déterminer l'angle d'inclinaison lors de la numérisation.

**Returns:**
float - L'angle d'inclinaison, en degrés.
### getSmartObjectProvider() {#getSmartObjectProvider--}
```
public final SmartObjectProvider getSmartObjectProvider()
```


Obtient le fournisseur d'objets intelligents.

Valeur: Le fournisseur d'objets intelligents.

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Obtient le chemin du fichier de l'image source si elle existe. Retourne une chaîne vide si le chemin source est introuvable.

**Returns:**
java.lang.String - Le chemin du fichier de l'image source.
### getSyncExclusiveOperation_internalized() {#getSyncExclusiveOperation-internalized--}
```
public Object getSyncExclusiveOperation_internalized()
```




**Returns:**
java.lang.Object
### getSyncRoot_internalized() {#getSyncRoot-internalized--}
```
public final Object getSyncRoot_internalized()
```


Obtient la racine de synchronisation.

Valeur : La racine de synchronisation.

**Returns:**
java.lang.Object
### getTimeline() {#getTimeline--}
```
public Timeline getTimeline()
```


Obtient la Chronologie ([.getTimeline](../../null/\#getTimeline)/[.setTimeline(Timeline)](../../null/\#setTimeline-Timeline-)) de ce [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Returns:**
[Timeline](../../com.aspose.psd.fileformats.psd.layers.animation/timeline)
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Obtient la couleur transparente de l'image.

**Returns:**
[Color](../../com.aspose.psd/color)
### getUpdateXmpData() {#getUpdateXmpData--}
```
public boolean getUpdateXmpData()
```


Obtient ou définit une valeur indiquant s'il faut mettre à jour les métadonnées XMP.

**Returns:**
boolean -  true  si la métadonnée XMP est mise à jour ; sinon,  false .
### getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates) {#getUpdatedResourceBlocks-internalized-com.aspose.psd.fileformats.psd.ResourceBlock---com.aspose.psd.fileformats.psd.ResourceBlock-boolean-}
```
public static ResourceBlock[] getUpdatedResourceBlocks_internalized(ResourceBlock[] resources, ResourceBlock resource, boolean removeDuplicates)
```


Obtient les ressources mises à jour avec un tout nouveau bloc de ressources.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| resources | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) | Les ressources. |
| resource | [ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock) | La ressource à ajouter aux ressources existantes. |
| removeDuplicates | booléen | si défini sur  true  supprime les ressources avec des ID identiques. |

**Returns:**
com.aspose.psd.fileformats.psd.ResourceBlock[] - Retourne un tableau avec les blocs de ressources mis à jour.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Obtient une valeur indiquant si l'objet utilise une stratégie d'optimisation de la mémoire

Valeur :  true  si l'objet utilise la stratégie d'optimisation de mémoire ; sinon,  false .

**Returns:**
boolean - une valeur indiquant si l'objet utilise la stratégie d'optimisation de mémoire
### getUseRawData() {#getUseRawData--}
```
public boolean getUseRawData()
```


Obtient ou définit une valeur indiquant s'il faut utiliser le chargement de données brutes lorsque celui-ci est disponible.

**Returns:**
boolean -  true  si le chargement de données brutes est utilisé lorsque le chargement de données brutes est disponible ; sinon,  false .
### getUsedPalette_internalized() {#getUsedPalette-internalized--}
```
public final IColorPalette getUsedPalette_internalized()
```


Obtient la palette utilisée.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - the used palette.
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Obtient la licence venture.

**Returns:**
java.lang.Object - La licence venture en tant qu'objet.
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Obtient ou définit la version.

Valeur : la version.

**Returns:**
int
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Obtient ou définit la résolution verticale, en pixels par pouce, de ce [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Returns:**
double
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient la largeur de l'image.

Valeur: la largeur de l'image.

**Returns:**
int
### getXmpData() {#getXmpData--}
```
public XmpPacketWrapper getXmpData()
```


Obtient ou définit les métadonnées XMP.

Valeur: Les métadonnées XMP.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper)
### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformation d'une image en sa représentation en niveaux de gris

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Obtient ou définit la résolution verticale, en pixels par pouce, de ce RasterImage.

Valeur:  true  si cette instance possède un canal alpha ; sinon,  false .

**Returns:**
booléen
### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Obtient une valeur indiquant si l'image possède une couleur d'arrière-plan.

**Returns:**
booléen
### hasImageChanged_internalized() {#hasImageChanged-internalized--}
```
public boolean hasImageChanged_internalized()
```


Obtient ou définit une valeur indiquant si cette instance d'image a changé après le chargement.

Valeur:  true  si cette instance a une image modifiée ; sinon,  false .

**Returns:**
booléen
### hasTransparencyData() {#hasTransparencyData--}
```
public final boolean hasTransparencyData()
```


Obtient ou définit une valeur indiquant si le premier canal alpha contient les données de transparence pour le résultat fusionné lors de la spécification des données des calques.

Valeur:  true  si le premier canal alpha contient les données de transparence pour le résultat fusionné lors de la spécification des données de calques ; sinon,  false .

**Returns:**
booléen
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Obtient une valeur indiquant si l'image possède une couleur transparente.

**Returns:**
booléen
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### incrementProgressMaxValue_internalized(int value) {#incrementProgressMaxValue-internalized-int-}
```
public final void incrementProgressMaxValue_internalized(int value)
```


Obtient ou définit la valeur maximale de progression

Valeur: la valeur maximale de progression

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public final void indicateProgress_internalized(EventType eventType)
```


Indique la progression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) |  |

### insertLayerAfter_internalized(Layer layer, Layer layerToInsert) {#insertLayerAfter-internalized-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void insertLayerAfter_internalized(Layer layer, Layer layerToInsert)
```


Insère le calque après le calque spécifié avec toutes les préparations

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Le calque. |
| layerToInsert | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Le calque à insérer. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Obtient une valeur indiquant si les données de l'image sont actuellement en cache.

**Returns:**
boolean -  true  si les données d'image sont en cache ; sinon,  false .
### isFlatten() {#isFlatten--}
```
public final boolean isFlatten()
```


Obtient une valeur indiquant si l'image PSD est aplatie.

Valeur:  true  si cette instance est aplatie ; sinon,  false .

**Returns:**
booléen
### isRawDataAvailable() {#isRawDataAvailable--}
```
public boolean isRawDataAvailable()
```


Obtient une valeur indiquant si le chargement de données brutes est disponible.

**Returns:**
boolean -  true  si le chargement de ces données brutes est disponible ; sinon,  false .
### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Obtient une valeur indiquant si la palette de l'image est utilisée.

Valeur:  true  si la palette est utilisée dans l'image ; sinon,  false .

**Returns:**
boolean - une valeur indiquant si la palette d'image est utilisée.
### isUsePhotoshopCompatibilityMode_internalized() {#isUsePhotoshopCompatibilityMode-internalized--}
```
public boolean isUsePhotoshopCompatibilityMode_internalized()
```




**Returns:**
booléen
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


Charge une nouvelle image depuis le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Le flux à partir duquel charger l'image. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.psd.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


Charge une nouvelle image depuis le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Le flux à partir duquel charger l'image. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Les options de chargement. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


Charge une nouvelle image depuis le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fichier | java.io.RandomAccessFile | Le fichier à partir duquel charger l'image. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.psd.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


Charge une nouvelle image depuis le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fichier | java.io.RandomAccessFile | Le fichier à partir duquel charger l'image. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Les options de chargement. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


Charge une nouvelle image depuis le fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier à partir duquel charger l'image. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.psd.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


Charge une nouvelle image depuis le fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier à partir duquel charger l'image. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Les options de chargement. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### loadArgb32Pixels(Rectangle rectangle) {#loadArgb32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadArgb32Pixels(Rectangle rectangle)
```


Charge des pixels ARGB 32 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle à partir duquel charger les pixels. |

**Returns:**
int[] - Le tableau de pixels ARGB 32 bits chargé.
### loadArgb64Pixels(Rectangle rectangle) {#loadArgb64Pixels-com.aspose.psd.Rectangle-}
```
public long[] loadArgb64Pixels(Rectangle rectangle)
```


Charge des pixels ARGB 64 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle à partir duquel charger les pixels. |

**Returns:**
long[] - Le tableau de pixels ARGB 64 bits chargé.
### loadCmyk32Pixels(Rectangle rectangle) {#loadCmyk32Pixels-com.aspose.psd.Rectangle-}
```
public int[] loadCmyk32Pixels(Rectangle rectangle)
```


Charge des pixels au format CMYK.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle à partir duquel charger les pixels. |

**Returns:**
int[] - Le tableau de pixels CMYK chargés présentés comme valeurs entières 32 bits.
### loadCmykPixels(Rectangle rectangle) {#loadCmykPixels-com.aspose.psd.Rectangle-}
```
public CmykColor[] loadCmykPixels(Rectangle rectangle)
```


Charge les pixels au format CMYK. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace  loadCmyk32Pixels(Rectangle) .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle à partir duquel charger les pixels. |

**Returns:**
com.aspose.psd.CmykColor[] - Le tableau de pixels CMYK chargé.
### loadInternal_internalized(System.IO.Stream stream) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image loadInternal_internalized(System.IO.Stream stream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions) {#loadInternal-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.LoadOptions-}
```
public static Image loadInternal_internalized(System.IO.Stream stream, LoadOptions loadOptions)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader) {#loadPartialArgb32Pixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-}
```
public void loadPartialArgb32Pixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)
```


Charge partiellement des pixels ARGB 32 bits par paquets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle souhaité. |
| partialPixelLoader | [IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader) | Le chargeur de pixels ARGB 32 bits. |

### loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader) {#loadPartialPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialPixelLoader-}
```
public void loadPartialPixels(Rectangle desiredRectangle, IPartialPixelLoader pixelLoader)
```


Charge des pixels partiellement par paquets.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| desiredRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle souhaité. |
| pixelLoader | [IPartialPixelLoader](../../com.aspose.psd/ipartialpixelloader) | Le chargeur de pixels. |

### loadPixels(Rectangle rectangle) {#loadPixels-com.aspose.psd.Rectangle-}
```
public Color[] loadPixels(Rectangle rectangle)
```


Charge des pixels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle à partir duquel charger les pixels. |

**Returns:**
com.aspose.psd.Color[] - Le tableau de pixels chargé.
### loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Charge les données d'image brutes en utilisant le mécanisme de traitement partiel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | La zone rectangulaire souhaitée de l'image à partir de laquelle charger les données. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Les paramètres des données brutes. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Le chargeur de données brutes. |

### loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader) {#loadRawData-com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-com.aspose.psd.IPartialRawDataLoader-}
```
public void loadRawData(Rectangle rectangle, Rectangle destImageBounds, RawDataSettings rawDataSettings, IPartialRawDataLoader rawDataLoader)
```


Charge des données brutes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle à partir duquel charger les données brutes. |
| destImageBounds | [Rectangle](../../com.aspose.psd/rectangle) | Les limites de l'image de destination. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Les paramètres de données brutes à utiliser pour les données chargées. Notez que si les données ne sont pas au format spécifié, une conversion des données sera effectuée. |
| rawDataLoader | [IPartialRawDataLoader](../../com.aspose.psd/ipartialrawdataloader) | Le chargeur de données brutes. |

### load_internalized(System.IO.Stream stream) {#load-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Image load_internalized(System.IO.Stream stream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Image](../../com.aspose.psd/image)
### load_internalized(System.IO.Stream stream, long startPosition) {#load-internalized-com.aspose.ms.System.IO.Stream-long-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition)
```


Charge une nouvelle image depuis le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Le flux à partir duquel charger l'image. |
| startPosition | long | La position de départ à partir de laquelle charger l'image. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions) {#load-internalized-com.aspose.ms.System.IO.Stream-long-com.aspose.psd.LoadOptions-}
```
public static Image load_internalized(System.IO.Stream stream, long startPosition, LoadOptions loadOptions)
```


Charge une nouvelle image depuis le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Le flux à partir duquel charger l'image. |
| startPosition | long | La position de départ à partir de laquelle charger l'image. |
| loadOptions | [LoadOptions](../../com.aspose.psd/loadoptions) | Les options de chargement. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded image.
### mergeLayers(Layer bottomLayer, Layer topLayer) {#mergeLayers-com.aspose.psd.fileformats.psd.layers.Layer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final Layer mergeLayers(Layer bottomLayer, Layer topLayer)
```


Fusionne les calques.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| bottomLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Le calque inférieur. |
| topLayer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Le calque supérieur. |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Bottom layer after the merge
### normalizeAngle() {#normalizeAngle--}
```
public final void normalizeAngle()
```


Normalise l'angle. Cette méthode s'applique aux documents texte numérisés pour se débarrasser de la numérisation inclinée. Cette méthode utilise [.getSkewAngle](../../null/\#getSkewAngle) et [.rotate(float)](../../null/\#rotate-float-) méthodes.

### normalizeAngle(boolean resizeProportionally, Color backgroundColor) {#normalizeAngle-boolean-com.aspose.psd.Color-}
```
public void normalizeAngle(boolean resizeProportionally, Color backgroundColor)
```


Normalise l'angle. Cette méthode s'applique aux documents texte numérisés pour se débarrasser de la numérisation inclinée. Cette méthode utilise [.getSkewAngle](../../null/\#getSkewAngle) et [.rotate(float, boolean, Color)](../../null/\#rotate-float--boolean--Color-) méthodes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| resizeProportionally | booléen | Si réglé sur true, la taille de votre image sera modifiée selon les projections du rectangle tourné (points d'angle); dans le cas contraire, les dimensions restent inchangées et seul le contenu interne de l'image est tourné. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Couleur de l'arrière-plan. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### onContainerSet_internalized() {#onContainerSet-internalized--}
```
public void onContainerSet_internalized()
```


Invoquez lorsque le conteneur de cette [Image](../../com.aspose.psd/image) a été défini.

### readArgb32ScanLine(int scanLineIndex) {#readArgb32ScanLine-int-}
```
public int[] readArgb32ScanLine(int scanLineIndex)
```


Lit toute la ligne de numérisation selon l'index de ligne de numérisation spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scanLineIndex | int | Indice basé sur zéro de la ligne de numérisation. |

**Returns:**
int[] - Le tableau des valeurs de couleur ARGB 32 bits de la ligne de numérisation.
### readScanLine(int scanLineIndex) {#readScanLine-int-}
```
public Color[] readScanLine(int scanLineIndex)
```


Lit toute la ligne de numérisation selon l'index de ligne de numérisation spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scanLineIndex | int | Indice basé sur zéro de la ligne de numérisation. |

**Returns:**
com.aspose.psd.Color[] - Le tableau des valeurs de couleur des pixels de la ligne de numérisation.
### removeGlobalTextEngineResource_internalized() {#removeGlobalTextEngineResource-internalized--}
```
public final void removeGlobalTextEngineResource_internalized()
```


Supprime la ressource du moteur de texte global - La méthode est utilisée pour certains fichiers PSD à calques de texte, qui ne peuvent pas être ouverts dans Adobe Photoshop après traitement (principalement liés aux calques de texte avec polices manquantes). Après avoir utilisé cette option, l'utilisateur doit effectuer les actions suivantes dans le fichier ouvert dans Photoshop : Menu "Texte" -> "Traiter les polices manquantes". Après cette opération, tout le texte réapparaîtra. Veuillez noter que cette opération peut entraîner quelques modifications finales de la mise en page.

### replaceColor(Color oldColor, byte oldColorDiff, Color newColor) {#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-}
```
public void replaceColor(Color oldColor, byte oldColorDiff, Color newColor)
```


Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| oldColor | [Color](../../com.aspose.psd/color) | Ancienne couleur à remplacer. |
| oldColorDiff | byte | Différence autorisée dans l'ancienne couleur pour pouvoir élargir la teinte de couleur remplacée. |
| newColor | [Color](../../com.aspose.psd/color) | Nouvelle couleur avec laquelle remplacer l'ancienne couleur. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| oldColorArgb | int | Ancienne valeur ARGB de couleur à remplacer. |
| oldColorDiff | byte | Différence autorisée dans l'ancienne couleur pour pouvoir élargir la teinte de couleur remplacée. |
| newColorArgb | int | Nouvelle valeur ARGB de couleur avec laquelle remplacer l'ancienne couleur. |

### replaceNonTransparentColors(Color newColor) {#replaceNonTransparentColors-com.aspose.psd.Color-}
```
public void replaceNonTransparentColors(Color newColor)
```


Remplace toutes les couleurs non transparentes par la nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newColor | [Color](../../com.aspose.psd/color) | Nouvelle couleur avec laquelle remplacer les couleurs non transparentes. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Remplace toutes les couleurs non transparentes par la nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newColorArgb | int | Nouvelle valeur ARGB de couleur avec laquelle remplacer les couleurs non transparentes. |

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


Redimensionne l'image. Le type par défaut ResizeType.LeftTopToLeftTop est utilisé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.psd.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Redimensionne l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Les paramètres de redimensionnement. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Redimensionne l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Le type de redimensionnement. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


Redimensionne la hauteur proportionnellement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newHeight | int | La nouvelle hauteur. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


Redimensionne la hauteur proportionnellement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newHeight | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Les paramètres de redimensionnement de l'image. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Redimensionne la hauteur proportionnellement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newHeight | int | La nouvelle hauteur. |
| resizeType | int | Type de redimensionnement. |

### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


Redimensionne la largeur proportionnellement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.psd.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


Redimensionne la largeur proportionnellement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| settings | [ImageResizeSettings](../../com.aspose.psd/imageresizesettings) | Les paramètres de redimensionnement de l'image. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Redimensionne la largeur proportionnellement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newWidth | int | La nouvelle largeur. |
| resizeType | int | Type de redimensionnement. |

### resizeWithScale_internalized(double scaleX, double scaleY, int resizeType) {#resizeWithScale-internalized-double-double-int-}
```
public final void resizeWithScale_internalized(double scaleX, double scaleY, int resizeType)
```


Redimensionne le calque avec l'échelle inverse spécifiée. (nouvelle largeur = ancienne largeur / échelle ; nouvelle hauteur = ancienne hauteur / échelle)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scaleX | double | L'échelle X. |
| scaleY | double | L'échelle Y. |
| resizeType | int | Type de redimensionnement. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Faire pivoter l'image autour du centre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives font pivoter dans le sens horaire. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.psd.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Faire pivoter l'image autour du centre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives font pivoter dans le sens horaire. |
| resizeProportionally | booléen | Si réglé sur true, la taille de votre image sera modifiée selon les projections du rectangle tourné (points d'angle); dans le cas contraire, les dimensions restent inchangées et seul le contenu interne de l'image est tourné. |
| backgroundColor | [Color](../../com.aspose.psd/color) | Couleur de l'arrière-plan. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Fait pivoter, retourner ou pivoter et retourner l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rotateFlipType | int |  |

### save() {#save--}
```
public final void save()
```


Enregistre les données de l'image dans le flux sous-jacent.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Enregistre les données de l'objet dans le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Le flux où enregistrer les données de l'objet. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Le flux où enregistrer les données de l'image. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options d'enregistrement. |

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Le flux où enregistrer les données de l'image. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options d'enregistrement. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle des limites de l'image de destination. Définissez le rectangle vide pour utiliser les limites source. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Enregistre les données de l'objet dans le flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fichier | java.io.RandomAccessFile | Le flux où enregistrer les données de l'objet. |

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fichier | java.io.RandomAccessFile | Le fichier où enregistrer les données de l'image. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fichier | java.io.RandomAccessFile | Le fichier où enregistrer les données de l'image. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options d'enregistrement. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle des limites de l'image de destination. Définissez le rectangle vide pour utiliser les limites source. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Enregistre les données de l'objet à l'emplacement de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier où enregistrer les données de l'objet. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Enregistre les données de l'objet à l'emplacement de fichier spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier où enregistrer les données de l'objet. |
| overWrite | booléen | si défini sur true, écrase le contenu du fichier, sinon une addition sera effectuée. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options. |

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Le chemin du fichier. |
| options | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle des limites de l'image de destination. Définissez le rectangle vide pour utiliser les limites source. |

### saveArgb32Pixels(Rectangle rectangle, int[] pixels) {#saveArgb32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveArgb32Pixels(Rectangle rectangle, int[] pixels)
```


Enregistre les pixels ARGB 32 bits.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle où enregistrer les pixels. |
| pixels | int[] | Le tableau de pixels ARGB 32 bits. |

### saveCmyk32Pixels(Rectangle rectangle, int[] pixels) {#saveCmyk32Pixels-com.aspose.psd.Rectangle-int---}
```
public void saveCmyk32Pixels(Rectangle rectangle, int[] pixels)
```


Enregistre les pixels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle où enregistrer les pixels. |
| pixels | int[] | Les pixels CMYK présentés sous forme de valeurs entières 32 bits. |

### saveCmykPixels(Rectangle rectangle, CmykColor[] pixels) {#saveCmykPixels-com.aspose.psd.Rectangle-com.aspose.psd.CmykColor---}
```
public void saveCmykPixels(Rectangle rectangle, CmykColor[] pixels)
```


Enregistre les pixels. Cette méthode est obsolète. Veuillez utiliser la méthode saveCmyk32Pixels(Rectangle, int[]) plus efficace.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle où enregistrer les pixels. |
| pixels | [CmykColor\[\]](../../com.aspose.psd/cmykcolor) | Le tableau de pixels CMYK. |

### savePixels(Rectangle rectangle, Color[] pixels) {#savePixels-com.aspose.psd.Rectangle-com.aspose.psd.Color---}
```
public void savePixels(Rectangle rectangle, Color[] pixels)
```


Enregistre les pixels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle où enregistrer les pixels. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Le tableau de pixels. |

### saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings) {#saveRawData-byte---int-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-}
```
public void saveRawData(byte[] data, int dataOffset, Rectangle rectangle, RawDataSettings rawDataSettings)
```


Enregistre les données brutes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| données | byte[] | Les données brutes. |
| dataOffset | int | Le décalage de données brutes de départ. |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle des données brutes. |
| rawDataSettings | [RawDataSettings](../../com.aspose.psd/rawdatasettings) | Les paramètres des données brutes contenant les données. |

### saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport) {#saveSpecificLayers-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void saveSpecificLayers_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle, Layer[] layersToExport)
```


Enregistre les données d'image dans le flux spécifié en utilisant les options d'enregistrement et les limites spécifiées. Exporte éventuellement uniquement les calques spécifiés pour l'aperçu du rendu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Le flux dans lequel les données d'image seront enregistrées. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options d'enregistrement à utiliser. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle des limites de l'image de destination. Définissez-le sur  Rectangle.Empty  pour utiliser les limites de la source. |
| layersToExport | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | Les couches spécifiques à exporter. Une valeur  null  indique le comportement par défaut avec toutes les couches. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream | Le flux où enregistrer les données de l'image. |
| optionsBase | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | Les options d'enregistrement. |
| boundsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle des limites de l'image de destination. Définissez le rectangle vide pour utiliser les limites source. |

### setActiveLayer(Layer value) {#setActiveLayer-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void setActiveLayer(Layer value)
```


Obtient ou définit le calque actif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

### setArgb32Pixel(int x, int y, int argb32Color) {#setArgb32Pixel-int-int-int-}
```
public void setArgb32Pixel(int x, int y, int argb32Color)
```


Définit un pixel ARGB 32 bits de l'image pour la position spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | L'emplacement x du pixel. |
| y | int | L'emplacement y du pixel. |
| argb32Color | int | Le pixel ARGB 32 bits pour la position spécifiée. |

### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


Définit une valeur indiquant si la palette s'ajuste automatiquement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | true si l'ajustement automatique de la palette est activé ; sinon false. |

### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Obtient ou définit une valeur indiquant si l'image a une couleur d'arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.psd.Color-}
```
public void setBackgroundColor(Color value)
```


Obtient ou définit une valeur pour la couleur d'arrière-plan.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setBackgroundContents_internalized(RawColor value) {#setBackgroundContents-internalized-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setBackgroundContents_internalized(RawColor value)
```


Obtient ou définit la couleur d'arrière-plan. Elle peut être vue sous les objets transparents.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes.

Valeur : L'indice de taille du tampon, en mégaoctets. Une valeur non positive signifie aucune limitation de mémoire pour les tampons internes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |

### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setCmykColorProfile(StreamSource value)
```


Obtient ou définit le profil couleur CMYK pour les images PSD CMYK. Doit être associé à RgbColorProfile pour une conversion de couleur correcte.

Valeur : le profil couleur CMYK.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Obtient ou définit le mode couleur.

Valeur : le mode couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setContainer_internalized(Image container) {#setContainer-internalized-com.aspose.psd.Image-}
```
public void setContainer_internalized(Image container)
```


Définit le conteneur Image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| container | [Image](../../com.aspose.psd/image) | Le conteneur Image. |

### setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader) {#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-}
```
public void setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)
```


Définit le chargeur de données directement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| loader | [IRasterImageArgb32PixelLoader](../../com.aspose.psd/irasterimageargb32pixelloader) | Le chargeur de données. |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Définit le flux de données de l'objet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le flux de données de l'objet. |

### setFormatSpecificPalette_internalized(IColorPalette newPalette) {#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-}
```
public boolean setFormatSpecificPalette_internalized(IColorPalette newPalette)
```


Définit la palette dans les emplacements spécifiques au format

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| newPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | Nouvelle palette ARGB 32 bits. |

**Returns:**
booléen
### setGlobalAngle(int value) {#setGlobalAngle-int-}
```
public final void setGlobalAngle(int value)
```


L'angle global.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setGlobalLayerResources(LayerResource[] value) {#setGlobalLayerResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setGlobalLayerResources(LayerResource[] value)
```


Obtient ou définit les ressources globales de calque.

Valeur : les ressources globales du calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setGrayColorProfile(StreamSource value) {#setGrayColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setGrayColorProfile(StreamSource value)
```


Le profil couleur GRAY (monochrome) pour les images PSD en niveaux de gris.

Valeur : le profil couleur GRAY (monochrome).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Obtient ou définit la résolution horizontale, en pixels par pouce, de ce [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Définit une valeur indiquant si [ignore after save].

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | true si [ignore after save] ; sinon, false. |

### setImageChanged_internalized(boolean value) {#setImageChanged-internalized-boolean-}
```
public void setImageChanged_internalized(boolean value)
```


Obtient ou définit une valeur indiquant si cette instance d'image a changé après le chargement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | true si cette instance a une image modifiée ; sinon, false. |

### setImageResources(ResourceBlock[] value) {#setImageResources-com.aspose.psd.fileformats.psd.ResourceBlock---}
```
public final void setImageResources(ResourceBlock[] value)
```


Obtient ou définit les ressources d'image PSD.

Valeur: Les ressources d'image PSD.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ResourceBlock\[\]](../../com.aspose.psd.fileformats.psd/resourceblock) |  |

### setInnerDataTransformer_internalized(IInnerDataTransformer value) {#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-}
```
public final void setInnerDataTransformer_internalized(IInnerDataTransformer value)
```


Définit le transformateur de données interne.

Valeur : le transformateur de données interne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.internal.IInnerDataTransformer | le transformateur de données interne. |

### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Définit le moniteur d'interruption.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.psd.multithreading/interruptmonitor) | le moniteur d'interruption. |

### setLayers(Layer[] value) {#setLayers-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final void setLayers(Layer[] value)
```


Obtient ou définit les calques PSD.

Valeur: Les calques PSD.

--------------------

Notez que s'il n'y a pas de calques, les autres informations liées dans la section des informations de calque et de masque ne seront pas conservées (masques de calque, ressources et etc.).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) |  |

### setMaxAllowedAllocationForPartialRotateSave_internalized(int value) {#setMaxAllowedAllocationForPartialRotateSave-internalized-int-}
```
public static void setMaxAllowedAllocationForPartialRotateSave_internalized(int value)
```


Obtient ou définit l'allocation maximale autorisée pour l'enregistrement de rotation partielle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'allocation maximale autorisée pour l'enregistrement de rotation partielle. |

### setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose) {#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-}
```
public void setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)
```


Définit le gestionnaire de mémoire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| memoryManager | com.aspose.internal.memorymanagement.MemMgr | Le gestionnaire de mémoire. |
| needDispose | booléen | si défini sur true [need dispose]. |

### setPalette(IColorPalette value) {#setPalette-com.aspose.psd.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) | La palette de couleurs. |

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.psd.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Définit la palette d'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La palette à définir. |
| updateColors | booléen | si défini sur true les couleurs seront mises à jour selon la nouvelle palette ; sinon les index de couleur restent inchangés. Notez que les index inchangés peuvent faire planter l'image lors du chargement si certains index n'ont pas d'entrées de palette correspondantes. |

### setPixel(int x, int y, Color color) {#setPixel-int-int-com.aspose.psd.Color-}
```
public void setPixel(int x, int y, Color color)
```


Définit un pixel d'image pour la position spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | int | L'emplacement x du pixel. |
| y | int | L'emplacement y du pixel. |
| color | [Color](../../com.aspose.psd/color) | La couleur du pixel pour la position spécifiée. |

### setPremultiplyComponents(boolean value) {#setPremultiplyComponents-boolean-}
```
public void setPremultiplyComponents(boolean value)
```


Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | true si les composants de l'image doivent être prémultipliés ; sinon, false. |

### setRawCustomColorConverter(IColorConverter value) {#setRawCustomColorConverter-com.aspose.psd.IColorConverter-}
```
public void setRawCustomColorConverter(IColorConverter value)
```


Obtient ou définit le convertisseur de couleur personnalisé

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IColorConverter](../../com.aspose.psd/icolorconverter) | Le convertisseur de couleur personnalisé |

### setRawFallbackIndex(int value) {#setRawFallbackIndex-int-}
```
public void setRawFallbackIndex(int value)
```


Obtient ou définit l'index de secours à utiliser lorsque l'index de palette est hors limites

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | L'index de secours à utiliser lorsque l'index de palette est hors limites |

### setRawIndexedColorConverter(IIndexedColorConverter value) {#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-}
```
public void setRawIndexedColorConverter(IIndexedColorConverter value)
```


Obtient ou définit le convertisseur de couleur indexée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IIndexedColorConverter](../../com.aspose.psd/iindexedcolorconverter) | Le convertisseur de couleur indexée |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Définit la résolution pour ce [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dpiX | double | La résolution horizontale, en points par pouce, de l'image RasterImage. |
| dpiY | double | La résolution verticale, en points par pouce, de l'image RasterImage. |

### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.psd.sources.StreamSource-}
```
public final void setRgbColorProfile(StreamSource value)
```


Obtient ou définit le profil couleur RGB pour les images PSD CMJN. Doit être associé à CmykColorProfile pour une conversion de couleur correcte.

Valeur: Le profil couleur RGB.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.psd.sources/streamsource) |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


Obtient ou définit le mode de rotation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le mode de rotation. |

### setTransparencyData(boolean value) {#setTransparencyData-boolean-}
```
public final void setTransparencyData(boolean value)
```


Obtient ou définit une valeur indiquant si le premier canal alpha contient les données de transparence pour le résultat fusionné lors de la spécification des données des calques.

Valeur:  true  si le premier canal alpha contient les données de transparence pour le résultat fusionné lors de la spécification des données de calques ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Obtient une valeur indiquant si l'image possède une couleur transparente.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.psd.Color-}
```
public void setTransparentColor(Color value)
```


Obtient la couleur transparente de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setUpdateXmpData(boolean value) {#setUpdateXmpData-boolean-}
```
public void setUpdateXmpData(boolean value)
```


Obtient ou définit une valeur indiquant s'il faut mettre à jour les métadonnées XMP.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | true si la mise à jour des métadonnées XMP ; sinon false. |

### setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized) {#setUsePhotoshopCompatibilityMode-internalized-boolean-}
```
public void setUsePhotoshopCompatibilityMode_internalized(boolean usePhotoshopCompatibilityMode_internalized)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| usePhotoshopCompatibilityMode_internalized | booléen |  |

### setUseRawData(boolean value) {#setUseRawData-boolean-}
```
public void setUseRawData(boolean value)
```


Obtient ou définit une valeur indiquant s'il faut utiliser le chargement de données brutes lorsque celui-ci est disponible.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen | true si le chargement de données brutes est utilisé lorsque le chargement de données brutes est disponible ; sinon false. |

### setVentureLicense_internalized(Object ventureLicense) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object ventureLicense)
```


Définit la licence d'entreprise.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ventureLicense | java.lang.Object | La licence de l'entreprise. |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Obtient ou définit la version.

Valeur : la version.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Obtient ou définit la résolution verticale, en pixels par pouce, de ce [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Obtient ou définit les métadonnées XMP.

Valeur: Les métadonnées XMP.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) |  |

### toBitmap() {#toBitmap--}
```
public BufferedImage toBitmap()
```


Convertit l'image raster en bitmap.

**Returns:**
java.awt.image.BufferedImage - Le bitmap
### toBitmap_internalized() {#toBitmap-internalized--}
```
public System.Drawing.Bitmap toBitmap_internalized()
```




**Returns:**
com.aspose.ms.System.Drawing.Bitmap
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels) {#writeArgb32ScanLine-int-int---}
```
public void writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)
```


Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scanLineIndex | int | Indice basé sur zéro de la ligne de numérisation. |
| argb32Pixels | int[] | Le tableau de couleurs ARGB 32 bits à écrire. |

### writeScanLine(int scanLineIndex, Color[] pixels) {#writeScanLine-int-com.aspose.psd.Color---}
```
public void writeScanLine(int scanLineIndex, Color[] pixels)
```


Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| scanLineIndex | int | Indice basé sur zéro de la ligne de numérisation. |
| pixels | [Color\[\]](../../com.aspose.psd/color) | Le tableau de couleurs de pixels à écrire. |

