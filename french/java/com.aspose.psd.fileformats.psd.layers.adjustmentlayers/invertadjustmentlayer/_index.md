---
title: "InvertAdjustmentLayer"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "La classe du calque d'ajustement invert."
type: docs
weight: 21
url: /fr/java/com.aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.DataStreamSupporter](../../com.aspose.psd/datastreamsupporter), [com.aspose.psd.Image](../../com.aspose.psd/image), [com.aspose.psd.RasterImage](../../com.aspose.psd/rasterimage), [com.aspose.psd.RasterCachedImage](../../com.aspose.psd/rastercachedimage), [com.aspose.psd.fileformats.psd.layers.Layer](../../com.aspose.psd.fileformats.psd.layers/layer), [com.aspose.psd.fileformats.psd.layers.adjustmentlayers.AdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/adjustmentlayer)
```
public class InvertAdjustmentLayer extends AdjustmentLayer
```

La classe du calque d'ajustement invert.
## Champs

| Champ | Description |
| --- | --- |
| [BlendSignature](#BlendSignature) | Représente la signature du mode de fusion. |
| [LayerHeaderSize](#LayerHeaderSize) | La taille de l'en-tête du calque. |
| [OnCreate_internalized](#OnCreate-internalized) | Se produit lorsque l'image a été chargée |
| [OnLoad_internalized](#OnLoad-internalized) | Se produit lorsque l'image a été chargée par createFirstSupportedLoader |
| [OnSave_internalized](#OnSave-internalized) | Se produit lorsque l'image a été chargée ou enregistrée |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Se produit lorsque le crédit a été utilisé |
| [resources_internalized](#resources-internalized) | Les ressources |
## Méthodes

| Méthode | Description |
| --- | --- |
| [<T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)](#-T-tryGetResource-internalized-java.lang.Class-T--T---) | Obtient la ressource associée au type spécifié. |
| [addLayerMask(LayerMaskData layerMask)](#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Ajoute le masque au calque actuel. |
| [addResource_internalized(LayerResource resource)](#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Ajoute la ressource. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Ajustement de la luminosité d'une image. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Contraste de l'image |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Correction gamma d'une image. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Correction gamma d'une image. |
| [applyLayerMask()](#applyLayerMask--) | Applique le masque de calque au calque, puis supprime le masque. |
| [applyLayerState_internalized(LayerState layerState)](#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-) | Applique le paramètre de style de calque depuis l'entrée [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) à l'instance du [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) actuel. |
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
| [convertToAps_internalized(ImageOptionsBase options, int mode, Rectangle clippingRectangle)](#convertToAps-internalized-com.aspose.psd.ImageOptionsBase-int-com.aspose.psd.Rectangle-) | Convertit en aps. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.psd.ImageOptionsBase-int-int-) | Crée une nouvelle image en utilisant les options de création spécifiées. |
| [create(Image[] images)](#create-com.aspose.psd.Image---) | Crée une nouvelle image en utilisant les images spécifiées comme pages |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.psd.Image---boolean-) | Crée une nouvelle image avec les images spécifiées comme pages. |
| [createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)](#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-) | Crée la nouvelle instance de la classe [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [createLayerState_internalized()](#createLayerState-internalized--) | Crée la nouvelle instance [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) basée sur les valeurs actuelles de [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [createPartialRotateSaver_internalized(PartialRotater resizer, IPixelsSaver pixelsSaver, int width, int height)](#createPartialRotateSaver-internalized-com.aspose.internal.rotaters.PartialRotater-com.aspose.internal.IPixelsSaver-int-int-) |  |
| [create_internalized(PsdHeader header, LayerResource[] resources)](#create-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.fileformats.psd.layers.LayerResource---) |  |
| [create_internalized(System.IO.Stream stream)](#create-internalized-com.aspose.ms.System.IO.Stream-) |  |
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
| [drawImage(Point location, RasterImage image)](#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-) | Dessine l'image sur le calque. |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si l'Objet spécifié est égal à cette instance. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.psd.Rectangle-com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase-) | Filtre le rectangle spécifié. |
| [findAssignableResource_internalized(System.Type type)](#findAssignableResource-internalized-com.aspose.ms.System.Type-) | Trouve la ressource assignable. |
| [findPattResource_internalized()](#findPattResource-internalized--) | Trouve le PattResource |
| [findResource_internalized(int typeToolKey)](#findResource-internalized-int-) | Trouve la ressource par clé unique |
| [getAbsoluteBounds_internalized()](#getAbsoluteBounds-internalized--) | Obtient ou définit les limites absolues. |
| [getAdjustmentLayerType_internalized()](#getAdjustmentLayerType-internalized--) | Obtient le type du calque d'ajustement. |
| [getArgb32Pixel(int x, int y)](#getArgb32Pixel-int-int-) | Obtient un pixel d'image ARGB 32 bits. |
| [getAutoAdjustPalette()](#getAutoAdjustPalette--) | Obtient une valeur indiquant si la palette d'ajustement automatique. |
| [getBackgroundColor()](#getBackgroundColor--) | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtient le nombre de bits par pixel de l'image. |
| [getBlendClippedElements()](#getBlendClippedElements--) | Obtient ou définit le mélange de l'élément découpé. |
| [getBlendModeKey()](#getBlendModeKey--) | Obtient ou définit la clé du mode de fusion. |
| [getBlendModeSignature()](#getBlendModeSignature--) | Obtient la signature du mode de fusion. |
| [getBlendingOptions()](#getBlendingOptions--) | Obtient les options de mélange. |
| [getBottom()](#getBottom--) | Obtient ou définit la position du calque inférieur. |
| [getBounds()](#getBounds--) | Obtient les limites de l'image. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Obtient l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| [getBytesPerRowForFullMask_internalized(int bitDepth)](#getBytesPerRowForFullMask-internalized-int-) | Obtient le nombre d'octets par ligne pour le mode masque complet. |
| [getBytesPerRowForMask_internalized(int bitDepth)](#getBytesPerRowForMask-internalized-int-) | Obtient le nombre d'octets par ligne. |
| [getBytesPerRow_internalized(int bitDepth)](#getBytesPerRow-internalized-int-) | Obtient le nombre d'octets par ligne. |
| [getChannelInformation()](#getChannelInformation--) | Obtient ou définit les informations du canal. |
| [getChannelsCount()](#getChannelsCount--) | Obtient le nombre de canaux du calque. |
| [getClass()](#getClass--) |  |
| [getClipping()](#getClipping--) | Obtient ou définit le découpage du calque. |
| [getContainer()](#getContainer--) | Obtient le conteneur Image. |
| [getDataStreamContainer()](#getDataStreamContainer--) | Obtient le flux de données de l'objet. |
| [getDeeplyAdjustPalette_internalized()](#getDeeplyAdjustPalette-internalized--) | Obtient la palette d'ajustement approfondi. |
| [getDefaultArgb32Pixels(Rectangle rectangle)](#getDefaultArgb32Pixels-com.aspose.psd.Rectangle-) | Obtient le tableau de pixels ARGB 32 bits par défaut. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Obtient les options par défaut. |
| [getDefaultPixels(Rectangle rectangle, IPartialArgb32PixelLoader partialPixelLoader)](#getDefaultPixels-com.aspose.psd.Rectangle-com.aspose.psd.IPartialArgb32PixelLoader-) | Obtient le tableau de pixels par défaut en utilisant le chargeur de pixels partiel. |
| [getDefaultRawData(Rectangle rectangle, IPartialRawDataLoader partialRawDataLoader, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.IPartialRawDataLoader-com.aspose.psd.RawDataSettings-) | Obtient le tableau de données brutes par défaut en utilisant le chargeur de pixels partiel. |
| [getDefaultRawData(Rectangle rectangle, RawDataSettings rawDataSettings)](#getDefaultRawData-com.aspose.psd.Rectangle-com.aspose.psd.RawDataSettings-) | Obtient le tableau de données brutes par défaut. |
| [getDisplayName()](#getDisplayName--) | Obtient le nom d'affichage du calque. |
| [getDisposed()](#getDisposed--) | Obtient une valeur indiquant si cette instance est libérée. |
| [getExtraLength()](#getExtraLength--) | Obtient la longueur des informations supplémentaires du calque en octets. |
| [getFileFormat()](#getFileFormat--) | Obtient une valeur du format de fichier |
| [getFileFormat(System.IO.Stream stream)](#getFileFormat-com.aspose.ms.System.IO.Stream-) | Obtient le format de fichier. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Obtient le format de fichier. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Obtient le format de fichier. |
| [getFillOpacity()](#getFillOpacity--) | Obtient ou définit l'opacité du remplissage. |
| [getFiller()](#getFiller--) | Obtient ou définit le remplisseur du calque. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int-int-) | Obtient le rectangle qui s'adapte à l'image actuelle. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.psd.Rectangle-int---int-int-) | Obtient le rectangle qui s'adapte à l'image actuelle. |
| [getFlags()](#getFlags--) | Obtient ou définit les indicateurs du calque. |
| [getFoldersHierarchy_internalized()](#getFoldersHierarchy-internalized--) | Obtient la liste de la hiérarchie des dossiers [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) du calque actuel. |
| [getFormatSpecificPalette_internalized()](#getFormatSpecificPalette-internalized--) | Obtient la palette à partir d'emplacements spécifiques au format |
| [getGUID_internalized()](#getGUID-internalized--) | Obtient l'identifiant unique de cette instance de calque. |
| [getHeader_internalized()](#getHeader-internalized--) | Obtient ou définit l'en-tête. |
| [getHeight()](#getHeight--) | Obtient la hauteur de l'image. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Obtient ou définit la résolution horizontale, en pixels par pouce, de ce RasterImage. |
| [getImageOpacity()](#getImageOpacity--) | Obtient l'opacité de cette image. |
| [getInnerDataTransformer_internalized()](#getInnerDataTransformer-internalized--) | Obtient le transformateur de données interne. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Obtient le moniteur d'interruption. |
| [getLayerBlendingRangesData()](#getLayerBlendingRangesData--) | Obtient ou définit les données des plages de fusion du calque. |
| [getLayerCreationDateTime()](#getLayerCreationDateTime--) | Obtient ou définit la date et l'heure de création du calque. |
| [getLayerCreationDateTime_internalized()](#getLayerCreationDateTime-internalized--) |  |
| [getLayerLock()](#getLayerLock--) | Obtient ou définit le verrou du calque. |
| [getLayerMaskData()](#getLayerMaskData--) | Obtient ou définit les données du masque du calque. |
| [getLayerOptions()](#getLayerOptions--) | Obtient les options du calque. |
| [getLayerPalette_internalized()](#getLayerPalette-internalized--) | Obtient ou définit la palette du calque. |
| [getLayerType_internalized()](#getLayerType-internalized--) | Obtient le type du calque. |
| [getLeft()](#getLeft--) | Obtient ou définit la position du calque gauche. |
| [getLength()](#getLength--) | Obtient la longueur totale du calque en octets. |
| [getMaxAllowedAllocationForPartialRotateSave_internalized()](#getMaxAllowedAllocationForPartialRotateSave-internalized--) | Obtient ou définit l'allocation maximale autorisée pour l'enregistrement de rotation partielle. |
| [getMemoryMgr_internalized()](#getMemoryMgr-internalized--) | Obtient le gestionnaire de mémoire. |
| [getModifyDate(boolean useDefault)](#getModifyDate-boolean-) | Obtient la date et l'heure de la dernière modification de l'image de ressource. |
| [getModifyDate_internalized(boolean useDefault)](#getModifyDate-internalized-boolean-) |  |
| [getName()](#getName--) | Obtient ou définit le nom du calque. |
| [getOpacity()](#getOpacity--) | Obtient ou définit l'opacité du calque. |
| [getOpacityTotal_internalized()](#getOpacityTotal-internalized--) | Obtient l'opacité totale. |
| [getOriginalOptions()](#getOriginalOptions--) | Obtient les options basées sur les paramètres du fichier original. |
| [getPaintableImage_internalized(ImageOptionsBase paintableOptions)](#getPaintableImage-internalized-com.aspose.psd.ImageOptionsBase-) | Obtient l'image peignable. |
| [getPalette()](#getPalette--) | Obtient la palette de couleurs. |
| [getPixel(int x, int y)](#getPixel-int-int-) | Obtient un pixel d'image. |
| [getPremultiplyComponents()](#getPremultiplyComponents--) | Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés. |
| [getPrivateFontCache_internalized()](#getPrivateFontCache-internalized--) | Crée le cache de polices privé. |
| [getProcessor_internalized()](#getProcessor-internalized--) | Obtient le processeur. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Obtient les informations du gestionnaire d'événement de progression. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | Obtient les informations du gestionnaire d'événement de progression. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Obtient une hauteur proportionnelle. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Obtient une largeur proportionnelle. |
| [getRawCustomColorConverter()](#getRawCustomColorConverter--) | Obtient ou définit le convertisseur de couleur personnalisé |
| [getRawDataFormat()](#getRawDataFormat--) | Obtient le format de données brutes. |
| [getRawDataSettings()](#getRawDataSettings--) |  |
| [getRawFallbackIndex()](#getRawFallbackIndex--) | Obtient ou définit l'index de secours à utiliser lorsque l'index de palette est hors limites |
| [getRawIndexedColorConverter()](#getRawIndexedColorConverter--) | Obtient ou définit le convertisseur de couleur indexée |
| [getRawLineSize()](#getRawLineSize--) | Obtient la taille brute de la ligne en octets. |
| [getResources()](#getResources--) | Obtient ou définit les ressources du calque. |
| [getRight()](#getRight--) | Obtient ou définit la position du calque droit. |
| [getRotateMode()](#getRotateMode--) | Obtient ou définit le mode de rotation. |
| [getSheetColorHighlight()](#getSheetColorHighlight--) | Obtient ou définit la mise en évidence de la couleur de la feuille décorative dans la liste des calques |
| [getSize()](#getSize--) | Obtient la taille de l'image. |
| [getSkewAngle()](#getSkewAngle--) | Obtient l'angle d'inclinaison. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Obtient le chemin du fichier de l'image source si elle existe. |
| [getSyncRoot_internalized()](#getSyncRoot-internalized--) | Obtient la racine de synchronisation. |
| [getTop()](#getTop--) | Obtient ou définit la position de la couche supérieure. |
| [getTransparentColor()](#getTransparentColor--) | Obtient la couleur transparente de l'image. |
| [getUpdateXmpData()](#getUpdateXmpData--) | Obtient ou définit une valeur indiquant s'il faut mettre à jour les métadonnées XMP. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Obtient une valeur indiquant si l'objet utilise une stratégie d'optimisation de la mémoire |
| [getUseRawData()](#getUseRawData--) | Obtient ou définit une valeur indiquant s'il faut utiliser le chargement de données brutes lorsque celui-ci est disponible. |
| [getUsedPalette_internalized()](#getUsedPalette-internalized--) | Obtient la palette utilisée. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Obtient la licence venture. |
| [getVerticalResolution()](#getVerticalResolution--) | Obtient ou définit la résolution verticale, en pixels par pouce, de ce RasterImage. |
| [getWidth()](#getWidth--) | Obtient la largeur de l'image. |
| [getXmpData()](#getXmpData--) | Obtient ou définit les métadonnées XMP. |
| [grayscale()](#grayscale--) | Transformation d'une image en sa représentation en niveaux de gris |
| [hasAlpha()](#hasAlpha--) | Obtient une valeur indiquant si cette instance possède un canal alpha. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Obtient une valeur indiquant si l'image possède une couleur d'arrière-plan. |
| [hasImageChanged_internalized()](#hasImageChanged-internalized--) | Obtient ou définit une valeur indiquant si cette instance d'image a changé après le chargement. |
| [hasTransparentColor()](#hasTransparentColor--) | Obtient une valeur indiquant si l'image possède une couleur transparente. |
| [hashCode()](#hashCode--) | Renvoie un code de hachage pour cette instance. |
| [incrementProgressMaxValue_internalized(int value)](#incrementProgressMaxValue-internalized-int-) | Obtient ou définit la valeur maximale de progression |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | Indique la progression. |
| [insertResource_internalized(int index, LayerResource resource)](#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Insère une ressource dans la collection Resources. |
| [isCached()](#isCached--) | Obtient une valeur indiquant si les données de l'image sont actuellement en cache. |
| [isLayerValid_internalized()](#isLayerValid-internalized--) | Détecte si le calque est valide pour l'enregistrement dans un fichier. |
| [isRawDataAvailable()](#isRawDataAvailable--) | Obtient une valeur indiquant si le chargement de données brutes est disponible. |
| [isUsePalette()](#isUsePalette--) | Obtient une valeur indiquant si la palette de l'image est utilisée. |
| [isVisible()](#isVisible--) | Obtient ou définit une valeur indiquant si le calque est visible |
| [isVisibleInGroup()](#isVisibleInGroup--) | Obtient une valeur indiquant si cette instance est visible dans le groupe(Si le calque n'est pas dans un groupe, cela signifie le groupe racine). |
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
| [mergeLayerTo(Layer layerToMergeInto)](#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-) | Fusionne le calque avec le calque spécifié |
| [normalizeAngle()](#normalizeAngle--) | Normalise l'angle. |
| [normalizeAngle(boolean resizeProportionally, Color backgroundColor)](#normalizeAngle-boolean-com.aspose.psd.Color-) | Normalise l'angle. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [onContainerSet_internalized()](#onContainerSet-internalized--) | Invoquez lorsque le conteneur de cette  Image  a été défini. |
| [processAdjustmentLayer_internalized(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)](#processAdjustmentLayer-internalized-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-) | Traite le calque d'ajustement d'inversion. |
| [processInvert_internalized(int[] pixels)](#processInvert-internalized-int---) | Applique les corrections d'inversion au tableau int ARGB spécifié. |
| [readArgb32ScanLine(int scanLineIndex)](#readArgb32ScanLine-int-) | Lit toute la ligne de numérisation selon l'index de ligne de numérisation spécifié. |
| [readScanLine(int scanLineIndex)](#readScanLine-int-) | Lit toute la ligne de numérisation selon l'index de ligne de numérisation spécifié. |
| [removeResource_internalized(LayerResource resource)](#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-) | Supprime la ressource. |
| [replaceColor(Color oldColor, byte oldColorDiff, Color newColor)](#replaceColor-com.aspose.psd.Color-byte-com.aspose.psd.Color-) | Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses. |
| [replaceNonTransparentColors(Color newColor)](#replaceNonTransparentColors-com.aspose.psd.Color-) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Redimensionne l'image. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.psd.ImageResizeSettings-) | Redimensionne l'image. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensionne l'image. |
| [resizeChannelsData_internalized(Rectangle rect)](#resizeChannelsData-internalized-com.aspose.psd.Rectangle-) | Fusionne les données. |
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
| [save(System.IO.Stream stream)](#save-com.aspose.ms.System.IO.Stream-) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Enregistre les données de l'objet dans le flux spécifié. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-) | Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement. |
| [save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement. |
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
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [save_internalized(System.IO.Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-internalized-com.aspose.ms.System.IO.Stream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-) | Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement. |
| [save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)](#save-internalized-com.aspose.psd.StreamContainer-int-int-) | Enregistre les données dans le conteneur de flux spécifié. |
| [setAbsoluteBounds_internalized(Rectangle value)](#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-) | Obtient ou définit les limites absolues. |
| [setArgb32Pixel(int x, int y, int argb32Color)](#setArgb32Pixel-int-int-int-) | Définit un pixel ARGB 32 bits de l'image pour la position spécifiée. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Définit une valeur indiquant si la palette s'ajuste automatiquement. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Obtient ou définit une valeur indiquant si l'image a une couleur d'arrière-plan. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.psd.Color-) | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| [setBlendClippedElements(boolean value)](#setBlendClippedElements-boolean-) | Obtient ou définit le mélange de l'élément découpé. |
| [setBlendModeKey(long value)](#setBlendModeKey-long-) | Obtient ou définit la clé du mode de fusion. |
| [setBottom(int value)](#setBottom-int-) | Obtient ou définit la position du calque inférieur. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| [setChannelInformation(ChannelInformation[] value)](#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | Obtient ou définit les informations du canal. |
| [setClipping(byte value)](#setClipping-byte-) | Obtient ou définit le découpage du calque. |
| [setContainer_internalized(Image container)](#setContainer-internalized-com.aspose.psd.Image-) | Définit le conteneur Image. |
| [setDataLoaderDirectly_internalized(IRasterImageArgb32PixelLoader loader)](#setDataLoaderDirectly-internalized-com.aspose.psd.IRasterImageArgb32PixelLoader-) | Définit le chargeur de données directement. |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Définit le flux de données de l'objet. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Obtient ou définit le nom d'affichage du calque. |
| [setFillOpacity(int value)](#setFillOpacity-int-) | Obtient l'opacité du remplissage. |
| [setFiller(byte value)](#setFiller-byte-) | Obtient ou définit le remplisseur du calque. |
| [setFlags(byte value)](#setFlags-byte-) | Obtient ou définit les indicateurs du calque. |
| [setFormatSpecificPalette_internalized(IColorPalette newPalette)](#setFormatSpecificPalette-internalized-com.aspose.psd.IColorPalette-) | Définit la palette dans les emplacements spécifiques au format |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Obtient ou définit l'en-tête. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Obtient ou définit la résolution horizontale, en pixels par pouce, de ce RasterImage. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Définit une valeur indiquant si [ignore after save]. |
| [setImageChanged_internalized(boolean value)](#setImageChanged-internalized-boolean-) | Obtient ou définit une valeur indiquant si cette instance d'image a changé après le chargement. |
| [setInnerDataTransformer_internalized(IInnerDataTransformer value)](#setInnerDataTransformer-internalized-com.aspose.internal.IInnerDataTransformer-) | Définit le transformateur de données interne. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.psd.multithreading.InterruptMonitor-) | Définit le moniteur d'interruption. |
| [setLayerBlendingRangesData(LayerBlendingRangesData value)](#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-) | Obtient ou définit les données des plages de fusion du calque. |
| [setLayerCreationDateTime(Date value)](#setLayerCreationDateTime-java.util.Date-) | Obtient ou définit la date et l'heure de création du calque. |
| [setLayerCreationDateTime_internalized(System.DateTime value)](#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-) |  |
| [setLayerLock(int value)](#setLayerLock-int-) | Obtient ou définit le verrou du calque (Notez que si le drapeau LayerFlags.TransparencyProtected est défini, il sera écrasé par le drapeau de verrouillage du calque). |
| [setLayerMaskData(LayerMaskData value)](#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Obtient ou définit les données du masque du calque. |
| [setLayerPalette_internalized(IColorPalette value)](#setLayerPalette-internalized-com.aspose.psd.IColorPalette-) | Obtient ou définit la palette du calque. |
| [setLeft(int value)](#setLeft-int-) | Obtient ou définit la position du calque gauche. |
| [setMaxAllowedAllocationForPartialRotateSave_internalized(int value)](#setMaxAllowedAllocationForPartialRotateSave-internalized-int-) | Obtient ou définit l'allocation maximale autorisée pour l'enregistrement de rotation partielle. |
| [setMemoryManager_internalized(MemMgr memoryManager, boolean needDispose)](#setMemoryManager-internalized-com.aspose.internal.memorymanagement.MemMgr-boolean-) | Définit le gestionnaire de mémoire. |
| [setName(String name)](#setName-java.lang.String-) | Définit le nom du calque. |
| [setName_internalized(String value)](#setName-internalized-java.lang.String-) | Obtient ou définit le nom du calque. |
| [setOpacity(byte value)](#setOpacity-byte-) | Obtient ou définit l'opacité du calque. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.psd.IColorPalette-) | Définit la palette de couleurs. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.psd.IColorPalette-boolean-) | Définit la palette d'image. |
| [setPixel(int x, int y, Color color)](#setPixel-int-int-com.aspose.psd.Color-) | Définit un pixel d'image pour la position spécifiée. |
| [setPremultiplyComponents(boolean value)](#setPremultiplyComponents-boolean-) | Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés. |
| [setRawCustomColorConverter(IColorConverter value)](#setRawCustomColorConverter-com.aspose.psd.IColorConverter-) | Obtient ou définit le convertisseur de couleur personnalisé |
| [setRawFallbackIndex(int value)](#setRawFallbackIndex-int-) | Obtient ou définit l'index de secours à utiliser lorsque l'index de palette est hors limites |
| [setRawIndexedColorConverter(IIndexedColorConverter value)](#setRawIndexedColorConverter-com.aspose.psd.IIndexedColorConverter-) | Obtient ou définit le convertisseur de couleur indexée |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Définit la résolution pour ce  RasterImage . |
| [setResources(LayerResource[] value)](#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---) | Obtient ou définit les ressources du calque. |
| [setRight(int value)](#setRight-int-) | Obtient ou définit la position du calque droit. |
| [setRotateMode_internalized(int value)](#setRotateMode-internalized-int-) | Obtient ou définit le mode de rotation. |
| [setSheetColorHighlight(short value)](#setSheetColorHighlight-short-) | Obtient ou définit la mise en évidence de la couleur de la feuille décorative dans la liste des calques |
| [setTop(int value)](#setTop-int-) | Obtient ou définit la position de la couche supérieure. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Obtient une valeur indiquant si l'image possède une couleur transparente. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.psd.Color-) | Obtient la couleur transparente de l'image. |
| [setUpdateXmpData(boolean value)](#setUpdateXmpData-boolean-) | Obtient ou définit une valeur indiquant s'il faut mettre à jour les métadonnées XMP. |
| [setUseRawData(boolean value)](#setUseRawData-boolean-) | Obtient ou définit une valeur indiquant s'il faut utiliser le chargement de données brutes lorsque celui-ci est disponible. |
| [setVentureLicense_internalized(Object ventureLicense)](#setVentureLicense-internalized-java.lang.Object-) | Tous les produits Aspose doivent implémenter cette méthode. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Obtient ou définit la résolution verticale, en pixels par pouce, de ce RasterImage. |
| [setVisible(boolean value)](#setVisible-boolean-) | Obtient ou définit une valeur indiquant si le calque est visible |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-) | Obtient ou définit les métadonnées XMP. |
| [shallowCopy()](#shallowCopy--) | Crée une copie superficielle de la couche actuelle. |
| [toBitmap()](#toBitmap--) | Convertit l'image raster en bitmap. |
| [toBitmap_internalized()](#toBitmap-internalized--) |  |
| [toString()](#toString--) |  |
| [updateBlendingOptions_internalized(PattResource pattResource)](#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-) | Met à jour les options de fusion après la modification du calque ou des ressources globales. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeArgb32ScanLine(int scanLineIndex, int[] argb32Pixels)](#writeArgb32ScanLine-int-int---) | Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| [writeScanLine(int scanLineIndex, Color[] pixels)](#writeScanLine-int-com.aspose.psd.Color---) | Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
### BlendSignature {#BlendSignature}
```
public static final int BlendSignature
```


Représente la signature du mode de fusion.

### LayerHeaderSize {#LayerHeaderSize}
```
public static final int LayerHeaderSize
```


La taille de l'en-tête du calque.

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

### resources_internalized {#resources-internalized}
```
public ResourceNest resources_internalized
```


Les ressources

### <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource) {#-T-tryGetResource-internalized-java.lang.Class-T--T---}
```
public final boolean <T>tryGetResource_internalized(Class<T> typeOfT, T[] resource)
```


Obtient la ressource associée au type spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | resource | T[] | Lorsque cette méthode retourne, elle contient la ressource associée au type de clé spécifié, si la clé est trouvée ; sinon, elle renvoie null. |

T : Le type de clé de la valeur à obtenir. |

**Returns:**
boolean -   si contient une ressource du type spécifié ; sinon,  .
### addLayerMask(LayerMaskData layerMask) {#addLayerMask-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void addLayerMask(LayerMaskData layerMask)
```


Ajoute le masque au calque actuel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| layerMask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | Le masque du calque. |

### addResource_internalized(LayerResource resource) {#addResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void addResource_internalized(LayerResource resource)
```


Ajoute la ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | La ressource. |

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

### applyLayerMask() {#applyLayerMask--}
```
public final void applyLayerMask()
```


Applique le masque de calque au calque, puis supprime le masque.

### applyLayerState_internalized(LayerState layerState) {#applyLayerState-internalized-com.aspose.psd.fileformats.psd.layers.animation.LayerState-}
```
public final void applyLayerState_internalized(LayerState layerState)
```


Applique le paramètre de style de calque depuis l'entrée [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) à l'instance du [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) actuel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| layerState | [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) | L'état de la couche avec le nouveau style. |

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
### createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry) {#createInstance-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.IColorPalette-com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry-}
```
public static Layer createInstance_internalized(PsdHeader header, IColorPalette palette, LinkedLayersRegistry linkedLayersRegistry)
```


Crée la nouvelle instance de la classe [Layer](../../com.aspose.psd.fileformats.psd.layers/layer).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| en-tête | com.aspose.internal.fileformats.psd.sections.PsdHeader | L'en-tête. |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La palette. |
| linkedLayersRegistry | com.aspose.internal.fileformats.psd.layers.LinkedLayersRegistry | Le LinkedLayersRegistry. |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - Returns the new instance of the [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) class.
### createLayerState_internalized() {#createLayerState-internalized--}
```
public final LayerState createLayerState_internalized()
```


Crée la nouvelle instance [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) basée sur les valeurs actuelles de [Layer](../../com.aspose.psd.fileformats.psd.layers/layer).

**Returns:**
[LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) - The new [LayerState](../../com.aspose.psd.fileformats.psd.layers.animation/layerstate) instance based on current [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) values.
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
### create_internalized(PsdHeader header, LayerResource[] resources) {#create-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public static InvertAdjustmentLayer create_internalized(PsdHeader header, LayerResource[] resources)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| en-tête | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |
| resources | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

**Returns:**
[InvertAdjustmentLayer](../../com.aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer)
### create_internalized(System.IO.Stream stream) {#create-internalized-com.aspose.ms.System.IO.Stream-}
```
public static Layer create_internalized(System.IO.Stream stream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer)
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

### drawImage(Point location, RasterImage image) {#drawImage-com.aspose.psd.Point-com.aspose.psd.RasterImage-}
```
public final void drawImage(Point location, RasterImage image)
```


Dessine l'image sur le calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| location | [Point](../../com.aspose.psd/point) | L'emplacement. |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | L'image. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si l'Objet spécifié est égal à cette instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'objet à comparer avec cette instance. |

**Returns:**
booléen -  true  si l'objet spécifié est égal à cette instance ; sinon,  false .
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

### findAssignableResource_internalized(System.Type type) {#findAssignableResource-internalized-com.aspose.ms.System.Type-}
```
public final LayerResource findAssignableResource_internalized(System.Type type)
```


Trouve la ressource assignable.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| type | com.aspose.ms.System.Type | Le type. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - 
### findPattResource_internalized() {#findPattResource-internalized--}
```
public final PattResource findPattResource_internalized()
```


Trouve le PattResource

**Returns:**
[PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) - The found resource or null
### findResource_internalized(int typeToolKey) {#findResource-internalized-int-}
```
public final LayerResource findResource_internalized(int typeToolKey)
```


Trouve la ressource par clé unique

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| typeToolKey | int | La clé de l'outil de type. |

**Returns:**
[LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) - Found resource or null
### getAbsoluteBounds_internalized() {#getAbsoluteBounds-internalized--}
```
public final Rectangle getAbsoluteBounds_internalized()
```


Obtient ou définit les limites absolues.

Valeur : Les limites absolues.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getAdjustmentLayerType_internalized() {#getAdjustmentLayerType-internalized--}
```
public byte getAdjustmentLayerType_internalized()
```


Obtient le type du calque d'ajustement.

Valeur: le type du calque d'ajustement.

**Returns:**
byte
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
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtient le nombre de bits par pixel de l'image.

Valeur : Le nombre de bits par pixel de l'image.

**Returns:**
int
### getBlendClippedElements() {#getBlendClippedElements--}
```
public final boolean getBlendClippedElements()
```


Obtient ou définit le mélange de l'élément découpé.

Valeur : Le mélange de l'élément découpé.

**Returns:**
booléen
### getBlendModeKey() {#getBlendModeKey--}
```
public long getBlendModeKey()
```


Obtient ou définit la clé du mode de fusion.

Valeur : La clé du mode de mélange.

**Returns:**
long
### getBlendModeSignature() {#getBlendModeSignature--}
```
public final int getBlendModeSignature()
```


Obtient la signature du mode de fusion.

Valeur : La signature du mode de mélange.

**Returns:**
int
### getBlendingOptions() {#getBlendingOptions--}
```
public final BlendingOptions getBlendingOptions()
```


Obtient les options de mélange.

Valeur : Les options de mélange.

**Returns:**
[BlendingOptions](../../com.aspose.psd.fileformats.psd.layers.layereffects/blendingoptions)
### getBottom() {#getBottom--}
```
public int getBottom()
```


Obtient ou définit la position du calque inférieur.

Valeur : La position du calque inférieur.

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
### getBytesPerRowForFullMask_internalized(int bitDepth) {#getBytesPerRowForFullMask-internalized-int-}
```
public final int getBytesPerRowForFullMask_internalized(int bitDepth)
```


Obtient le nombre d'octets par ligne pour le mode masque complet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| profondeurDeBit | int | La profondeur de bits. |

**Returns:**
int - Octets nécessaires pour stocker 1 ligne
### getBytesPerRowForMask_internalized(int bitDepth) {#getBytesPerRowForMask-internalized-int-}
```
public final int getBytesPerRowForMask_internalized(int bitDepth)
```


Obtient le nombre d'octets par ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| profondeurDeBit | int | La profondeur de bits. |

**Returns:**
int - Octets nécessaires pour stocker 1 ligne
### getBytesPerRow_internalized(int bitDepth) {#getBytesPerRow-internalized-int-}
```
public final int getBytesPerRow_internalized(int bitDepth)
```


Obtient le nombre d'octets par ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| profondeurDeBit | int | La profondeur de bits. |

**Returns:**
int - Octets nécessaires pour stocker 1 ligne
### getChannelInformation() {#getChannelInformation--}
```
public final ChannelInformation[] getChannelInformation()
```


Obtient ou définit les informations du canal.

Valeur : Les informations du canal.

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[]
### getChannelsCount() {#getChannelsCount--}
```
public final int getChannelsCount()
```


Obtient le nombre de canaux du calque.

Valeur : Le nombre de canaux du calque.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClipping() {#getClipping--}
```
public final byte getClipping()
```


Obtient ou définit le rognage du calque. 0 = base, 1 = non-base.

Valeur : Le rognage du calque.

**Returns:**
byte
### getContainer() {#getContainer--}
```
public Image getContainer()
```


Obtient le conteneur Image.

Valeur : Le conteneur d'Image.

Si cette propriété n'est pas nulle, cela indique que l'image est contenue dans une autre image.

**Returns:**
[Image](../../com.aspose.psd/image)
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
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Obtient le nom d'affichage du calque.

Valeur : Le nom d'affichage du calque.

**Returns:**
java.lang.String
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Obtient une valeur indiquant si cette instance est libérée.

**Returns:**
boolean -  true  si libéré ; sinon,  false .
### getExtraLength() {#getExtraLength--}
```
public final int getExtraLength()
```


Obtient la longueur des informations supplémentaires du calque en octets.

Valeur : la longueur de la couche supplémentaire.

**Returns:**
int
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
### getFillOpacity() {#getFillOpacity--}
```
public final int getFillOpacity()
```


Obtient ou définit l'opacité du remplissage.

**Returns:**
int
### getFiller() {#getFiller--}
```
public final byte getFiller()
```


Obtient ou définit le remplisseur du calque.

Valeur : le remplisseur de calque.

**Returns:**
byte
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
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


Obtient ou définit les indicateurs de calque. bit 0 = transparence protégée ; bit 1 = visible ; bit 2 = obsolète ; bit 3 = 1 pour Photoshop 5.0 et versions ultérieures, indique si le bit 4 contient des informations utiles ; bit 4 = données de pixel non pertinentes pour l'apparence du document.

Valeur : les indicateurs de calque.

**Returns:**
byte
### getFoldersHierarchy_internalized() {#getFoldersHierarchy-internalized--}
```
public final System.Collections.Generic.List<Layer> getFoldersHierarchy_internalized()
```


Obtient la liste de la hiérarchie des dossiers [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) du calque actuel.

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.fileformats.psd.layers.Layer> - Retourne la liste de la hiérarchie des dossiers [LayerGroup](../../com.aspose.psd.fileformats.psd.layers/layergroup) du calque actuel.
### getFormatSpecificPalette_internalized() {#getFormatSpecificPalette-internalized--}
```
public IColorPalette getFormatSpecificPalette_internalized()
```


Obtient la palette à partir d'emplacements spécifiques au format

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Format-specific  IColorPalette .
### getGUID_internalized() {#getGUID-internalized--}
```
public final String getGUID_internalized()
```


Obtient l'identifiant unique de cette instance de calque.

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Obtient ou définit l'en-tête.

Valeur : l'en-tête.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
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


Obtient ou définit la résolution horizontale, en pixels par pouce, de ce RasterImage.

**Returns:**
double - La résolution horizontale.

Remarque : par défaut, cette valeur est toujours 96 car différentes plateformes ne peuvent pas renvoyer la résolution de l'écran. Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Obtient l'opacité de cette image.

**Returns:**
float - La valeur d'opacité entre 0,0 (entièrement transparent) et 1,0 (entièrement opaque).
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
### getLayerBlendingRangesData() {#getLayerBlendingRangesData--}
```
public final LayerBlendingRangesData getLayerBlendingRangesData()
```


Obtient ou définit les données des plages de fusion du calque.

Valeur : les données des plages de fusion du calque.

**Returns:**
[LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata)
### getLayerCreationDateTime() {#getLayerCreationDateTime--}
```
public final Date getLayerCreationDateTime()
```


Obtient ou définit la date et l'heure de création du calque.

Valeur : la date et l'heure de création du calque. S'il n'y a aucune donnée sur la DateTime de création, alors retourne le premier epoch du temps Unix.

**Returns:**
java.util.Date
### getLayerCreationDateTime_internalized() {#getLayerCreationDateTime-internalized--}
```
public final System.DateTime getLayerCreationDateTime_internalized()
```




**Returns:**
com.aspose.ms.System.DateTime
### getLayerLock() {#getLayerLock--}
```
public final int getLayerLock()
```


Obtient ou définit le verrou du calque. Notez que si le drapeau LayerFlags.TransparencyProtected est défini, il sera écrasé par le drapeau de verrou du calque. Pour renvoyer le drapeau LayerFlags.TransparencyProtected, il faut l'appliquer à l'option du calque layer.Flags |= LayerFlags.TransparencyProtected

Valeur : le verrou du calque.

**Returns:**
int
### getLayerMaskData() {#getLayerMaskData--}
```
public final LayerMaskData getLayerMaskData()
```


Obtient ou définit les données du masque du calque.

Valeur : les données du masque du calque.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
### getLayerOptions() {#getLayerOptions--}
```
public final PsdOptions getLayerOptions()
```


Obtient les options du calque.

Valeur : les options du calque.

**Returns:**
[PsdOptions](../../com.aspose.psd.imageoptions/psdoptions)
### getLayerPalette_internalized() {#getLayerPalette-internalized--}
```
public final IColorPalette getLayerPalette_internalized()
```


Obtient ou définit la palette du calque.

Valeur : la palette du calque.

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette)
### getLayerType_internalized() {#getLayerType-internalized--}
```
public byte getLayerType_internalized()
```


Obtient le type du calque.

Valeur : le type du calque.

**Returns:**
byte
### getLeft() {#getLeft--}
```
public int getLeft()
```


Obtient ou définit la position du calque gauche.

Valeur : la position gauche du calque.

**Returns:**
int
### getLength() {#getLength--}
```
public final long getLength()
```


Obtient la longueur totale du calque en octets.

**Returns:**
long
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
### getName() {#getName--}
```
public final String getName()
```


Obtient ou définit le nom du calque.

Valeur : le nom du calque.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final byte getOpacity()
```


Obtient ou définit l'opacité du calque. 0 = transparent, 255 = opaque.

Valeur : l'opacité du calque.

**Returns:**
byte
### getOpacityTotal_internalized() {#getOpacityTotal-internalized--}
```
public final byte getOpacityTotal_internalized()
```


Obtient l'opacité totale. L'opacité totale est le produit de l'Opacité du Calque et de l'Opacité de Remplissage du Calque. Elle est utilisée pour la fusion des calques.

Valeur : l'opacité totale.

**Returns:**
byte
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
### getProcessor_internalized() {#getProcessor-internalized--}
```
public final IPartialArgb32PixelLoader getProcessor_internalized()
```


Obtient le processeur.

Valeur: le processeur.

**Returns:**
[IPartialArgb32PixelLoader](../../com.aspose.psd/ipartialargb32pixelloader)
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

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The raw data format.
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
### getResources() {#getResources--}
```
public final LayerResource[] getResources()
```


Obtient ou définit les ressources du calque.

Valeur : Les ressources de calque.

**Returns:**
com.aspose.psd.fileformats.psd.layers.LayerResource[]
### getRight() {#getRight--}
```
public int getRight()
```


Obtient ou définit la position du calque droit.

Valeur : La position du calque droit.

**Returns:**
int
### getRotateMode() {#getRotateMode--}
```
public static int getRotateMode()
```


Obtient ou définit le mode de rotation.

**Returns:**
int - Le mode de rotation.
### getSheetColorHighlight() {#getSheetColorHighlight--}
```
public final short getSheetColorHighlight()
```


Obtient ou définit la mise en évidence de la couleur de la feuille décorative dans la liste des calques

Valeur : La mise en évidence de la couleur de la feuille.

**Returns:**
short
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
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Obtient le chemin du fichier de l'image source si elle existe. Retourne une chaîne vide si le chemin source est introuvable.

**Returns:**
java.lang.String - Le chemin du fichier de l'image source.
### getSyncRoot_internalized() {#getSyncRoot-internalized--}
```
public final Object getSyncRoot_internalized()
```


Obtient la racine de synchronisation.

Valeur : La racine de synchronisation.

**Returns:**
java.lang.Object
### getTop() {#getTop--}
```
public int getTop()
```


Obtient ou définit la position de la couche supérieure.

Valeur : La position du calque supérieur.

**Returns:**
int
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
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Obtient ou définit la résolution verticale, en pixels par pouce, de ce RasterImage.

**Returns:**
double - La résolution verticale.

Remarque : par défaut, cette valeur est toujours 96 car différentes plateformes ne peuvent pas renvoyer la résolution de l'écran. Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel.
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

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The XMP metadata.
### grayscale() {#grayscale--}
```
public void grayscale()
```


Transformation d'une image en sa représentation en niveaux de gris

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Obtient une valeur indiquant si cette instance possède un canal alpha.

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

**Returns:**
boolean -  true  si cette instance a une image modifiée ; sinon,  false .
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Obtient une valeur indiquant si l'image possède une couleur transparente.

**Returns:**
booléen
### hashCode() {#hashCode--}
```
public int hashCode()
```


Renvoie un code de hachage pour cette instance.

**Returns:**
int - Un code de hachage pour cette instance, adapté à une utilisation dans les algorithmes de hachage et les structures de données comme une table de hachage.
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

### insertResource_internalized(int index, LayerResource resource) {#insertResource-internalized-int-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void insertResource_internalized(int index, LayerResource resource)
```


Insère une ressource dans la collection Resources.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de la ressource qui doit être insérée. |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | La ressource qui doit être insérée. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Obtient une valeur indiquant si les données de l'image sont actuellement en cache.

**Returns:**
boolean -  true  si les données d'image sont en cache ; sinon,  false .
### isLayerValid_internalized() {#isLayerValid-internalized--}
```
public boolean isLayerValid_internalized()
```


Détecte si le calque est valide pour l'enregistrement dans un fichier.

**Returns:**
boolean -
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
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Obtient ou définit une valeur indiquant si le calque est visible

Valeur:  true  si cette instance est visible ; sinon,  false .

**Returns:**
booléen
### isVisibleInGroup() {#isVisibleInGroup--}
```
public boolean isVisibleInGroup()
```


Obtient une valeur indiquant si cette instance est visible dans le groupe(Si le calque n'est pas dans un groupe, cela signifie le groupe racine).

Valeur:  true  si cette instance est visible dans le groupe ; sinon,  false .

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
### mergeLayerTo(Layer layerToMergeInto) {#mergeLayerTo-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public void mergeLayerTo(Layer layerToMergeInto)
```


Fusionne le calque avec le calque spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| layerToMergeInto | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Le calque dans lequel fusionner. |

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


Invoquez lorsque le conteneur de cette  Image  a été défini.

### processAdjustmentLayer_internalized(Rectangle pixelsRectangle, int[] pixels, Point start, Point end) {#processAdjustmentLayer-internalized-com.aspose.psd.Rectangle-int---com.aspose.psd.Point-com.aspose.psd.Point-}
```
public Tuple<int[],Rectangle> processAdjustmentLayer_internalized(Rectangle pixelsRectangle, int[] pixels, Point start, Point end)
```


Traite le calque d'ajustement d'inversion.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixelsRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle des pixels. |
| pixels | int[] | Le tableau de pixels. |
| start | [Point](../../com.aspose.psd/point) | L'emplacement supérieur gauche des pixels. |
| end | [Point](../../com.aspose.psd/point) | L'emplacement inférieur droit des pixels. |

**Returns:**
com.aspose.internal.fileformats.psd.common.Tuple<int[],com.aspose.psd.Rectangle> - Le rectangle des pixels et les pixels traités.
### processInvert_internalized(int[] pixels) {#processInvert-internalized-int---}
```
public final void processInvert_internalized(int[] pixels)
```


Applique les corrections d'inversion au tableau int ARGB spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixels | int[] | Le tableau int ARGB. |

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
### removeResource_internalized(LayerResource resource) {#removeResource-internalized-com.aspose.psd.fileformats.psd.layers.LayerResource-}
```
public final void removeResource_internalized(LayerResource resource)
```


Supprime la ressource.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| resource | [LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource) | La ressource. |

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

### resizeChannelsData_internalized(Rectangle rect) {#resizeChannelsData-internalized-com.aspose.psd.Rectangle-}
```
public void resizeChannelsData_internalized(Rectangle rect)
```


Fusionne les données.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.psd/rectangle) | Le rectangle. |

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

### save(System.IO.Stream stream) {#save-com.aspose.ms.System.IO.Stream-}
```
public void save(System.IO.Stream stream)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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

### save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.psd.ImageOptionsBase-com.aspose.psd.Rectangle-}
```
public void save(OutputStream dstStream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dstStream | java.io.OutputStream | Le flux où enregistrer les données de l'image. |
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

### save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth) {#save-internalized-com.aspose.psd.StreamContainer-int-int-}
```
public final void save_internalized(StreamContainer streamContainer, int psdVersion, int bitDepth)
```


Enregistre les données dans le conteneur de flux spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Le conteneur de flux. |
| psdVersion | int | La version PSD. |
| profondeurDeBit | int | La profondeur de bits. |

### setAbsoluteBounds_internalized(Rectangle value) {#setAbsoluteBounds-internalized-com.aspose.psd.Rectangle-}
```
public final void setAbsoluteBounds_internalized(Rectangle value)
```


Obtient ou définit les limites absolues.

Valeur : Les limites absolues.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

### setBlendClippedElements(boolean value) {#setBlendClippedElements-boolean-}
```
public final void setBlendClippedElements(boolean value)
```


Obtient ou définit le mélange de l'élément découpé.

Valeur : Le mélange de l'élément découpé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setBlendModeKey(long value) {#setBlendModeKey-long-}
```
public void setBlendModeKey(long value)
```


Obtient ou définit la clé du mode de fusion.

Valeur : La clé du mode de mélange.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long |  |

### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Obtient ou définit la position du calque inférieur.

Valeur : La position du calque inférieur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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

### setChannelInformation(ChannelInformation[] value) {#setChannelInformation-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public final void setChannelInformation(ChannelInformation[] value)
```


Obtient ou définit les informations du canal.

Valeur : Les informations du canal.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) |  |

### setClipping(byte value) {#setClipping-byte-}
```
public final void setClipping(byte value)
```


Obtient ou définit le rognage du calque. 0 = base, 1 = non-base.

Valeur : Le rognage du calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

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

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


Obtient ou définit le nom d'affichage du calque.

Valeur : Le nom d'affichage du calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setFillOpacity(int value) {#setFillOpacity-int-}
```
public final void setFillOpacity(int value)
```


Obtient l'opacité du remplissage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setFiller(byte value) {#setFiller-byte-}
```
public final void setFiller(byte value)
```


Obtient ou définit le remplisseur du calque.

Valeur : le remplisseur de calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


Obtient ou définit les indicateurs de calque. bit 0 = transparence protégée ; bit 1 = visible ; bit 2 = obsolète ; bit 3 = 1 pour Photoshop 5.0 et versions ultérieures, indique si le bit 4 contient des informations utiles ; bit 4 = données de pixel non pertinentes pour l'apparence du document.

Valeur : les indicateurs de calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

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
### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Obtient ou définit l'en-tête.

Valeur : l'en-tête.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Obtient ou définit la résolution horizontale, en pixels par pouce, de ce RasterImage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La résolution horizontale. |

Note que par défaut cette valeur est toujours 96 puisque différentes plateformes ne peuvent pas renvoyer la résolution d'écran. Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel. |

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

### setLayerBlendingRangesData(LayerBlendingRangesData value) {#setLayerBlendingRangesData-com.aspose.psd.fileformats.psd.layers.LayerBlendingRangesData-}
```
public final void setLayerBlendingRangesData(LayerBlendingRangesData value)
```


Obtient ou définit les données des plages de fusion du calque.

Valeur : les données des plages de fusion du calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [LayerBlendingRangesData](../../com.aspose.psd.fileformats.psd.layers/layerblendingrangesdata) |  |

### setLayerCreationDateTime(Date value) {#setLayerCreationDateTime-java.util.Date-}
```
public final void setLayerCreationDateTime(Date value)
```


Obtient ou définit la date et l'heure de création du calque.

Valeur : la date et l'heure de création du calque. S'il n'y a aucune donnée sur la DateTime de création, alors retourne le premier epoch du temps Unix.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Date |  |

### setLayerCreationDateTime_internalized(System.DateTime value) {#setLayerCreationDateTime-internalized-com.aspose.ms.System.DateTime-}
```
public final void setLayerCreationDateTime_internalized(System.DateTime value)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.ms.System.DateTime |  |

### setLayerLock(int value) {#setLayerLock-int-}
```
public final void setLayerLock(int value)
```


Obtient ou définit le verrou de calque (Notez que si le drapeau LayerFlags.TransparencyProtected est défini, il sera écrasé par le drapeau de verrouillage de calque. Pour renvoyer le drapeau LayerFlags.TransparencyProtected, il faut l'appliquer à l'option de calque layer.Flags |= LayerFlags.TransparencyProtected

Valeur : le verrou du calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setLayerMaskData(LayerMaskData value) {#setLayerMaskData-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public final void setLayerMaskData(LayerMaskData value)
```


Obtient ou définit les données du masque du calque.

Valeur : les données du masque du calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) |  |

### setLayerPalette_internalized(IColorPalette value) {#setLayerPalette-internalized-com.aspose.psd.IColorPalette-}
```
public final void setLayerPalette_internalized(IColorPalette value)
```


Obtient ou définit la palette du calque.

Valeur : la palette du calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.psd/icolorpalette) |  |

### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Obtient ou définit la position du calque gauche.

Valeur : la position gauche du calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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

### setName(String name) {#setName-java.lang.String-}
```
public final void setName(String name)
```


Définit le nom du calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Le nom du calque. |

### setName_internalized(String value) {#setName-internalized-java.lang.String-}
```
public final void setName_internalized(String value)
```


Obtient ou définit le nom du calque.

Valeur : le nom du calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### setOpacity(byte value) {#setOpacity-byte-}
```
public final void setOpacity(byte value)
```


Obtient ou définit l'opacité du calque. 0 = transparent, 255 = opaque.

Valeur : l'opacité du calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte |  |

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


Définit la résolution pour ce  RasterImage .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| dpiX | double | La résolution horizontale, en points par pouce, de l'image RasterImage. |
| dpiY | double | La résolution verticale, en points par pouce, de l'image RasterImage. |

### setResources(LayerResource[] value) {#setResources-com.aspose.psd.fileformats.psd.layers.LayerResource---}
```
public final void setResources(LayerResource[] value)
```


Obtient ou définit les ressources du calque.

Valeur : Les ressources de calque.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [LayerResource\[\]](../../com.aspose.psd.fileformats.psd.layers/layerresource) |  |

### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Obtient ou définit la position du calque droit.

Valeur : La position du calque droit.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setRotateMode_internalized(int value) {#setRotateMode-internalized-int-}
```
public static void setRotateMode_internalized(int value)
```


Obtient ou définit le mode de rotation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Le mode de rotation. |

### setSheetColorHighlight(short value) {#setSheetColorHighlight-short-}
```
public final void setSheetColorHighlight(short value)
```


Obtient ou définit la mise en évidence de la couleur de la feuille décorative dans la liste des calques

Valeur : La mise en évidence de la couleur de la feuille.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Obtient ou définit la position de la couche supérieure.

Valeur : La position du calque supérieur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

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


Tous les produits Aspose doivent implémenter cette méthode. Elle est appelée par un produit GroupDocs pour indiquer si GroupDocs lui‑même est licencié ou non et spécifier un filigrane personnalisé. Lorsque GroupDocs est licencié, cette instance de document doit également se comporter comme licenciée même si le produit Aspose n’est pas licencié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| ventureLicense | java.lang.Object | licence |

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Obtient ou définit la résolution verticale, en pixels par pouce, de ce RasterImage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | double | La résolution verticale. |

Note que par défaut cette valeur est toujours 96 puisque différentes plateformes ne peuvent pas renvoyer la résolution d'écran. Vous pouvez envisager d'utiliser la méthode SetResolution pour mettre à jour les deux valeurs de résolution en un seul appel. |

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Obtient ou définit une valeur indiquant si le calque est visible

Valeur:  true  si cette instance est visible ; sinon,  false .

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.psd.xmp.XmpPacketWrapper-}
```
public void setXmpData(XmpPacketWrapper value)
```


Obtient ou définit les métadonnées XMP.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) | Les métadonnées XMP. |

### shallowCopy() {#shallowCopy--}
```
public final Layer shallowCopy()
```


Crée une copie superficielle de la couche actuelle. Veuillez   pour explication.

**Returns:**
[Layer](../../com.aspose.psd.fileformats.psd.layers/layer) - A shallow copy of the current Layer.
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
### updateBlendingOptions_internalized(PattResource pattResource) {#updateBlendingOptions-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResource-}
```
public final void updateBlendingOptions_internalized(PattResource pattResource)
```


Met à jour les options de fusion après la modification du calque ou des ressources globales.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pattResource | [PattResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresource) |  |

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

