---
title: PsdImage
second_title: Référence de l'API Aspose.PSD pour .NET
description: Définit la classe PsdImage qui permet de charger de modifier denregistrer des fichiers PSD ainsi que de mettre à jour les propriétés dajouter des filigranes deffectuer des opérations graphiques ou de convertir un format de fichier en un autre. Aspose.PSD prend en charge limportation en tant que calque et lexportation vers le formats suivants  Png Jpeg Jpeg2000 Gif Bmp Tiff Psd Psb avec exportation vers Pdf avec texte sélectionnable
type: docs
weight: 3530
url: /fr/net/aspose.psd.fileformats.psd/psdimage/
---
## PsdImage class

Définit la classe PsdImage qui permet de charger, de modifier, d'enregistrer des fichiers PSD ainsi que de mettre à jour les propriétés, d'ajouter des filigranes, d'effectuer des opérations graphiques ou de convertir un format de fichier en un autre. Aspose.PSD prend en charge l'importation en tant que calque et l'exportation vers le formats suivants : Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb avec exportation vers Pdf avec texte sélectionnable

```csharp
public sealed class PsdImage : RasterCachedImage
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PsdImage](psdimage#constructor)(RasterImage) | Initialise une nouvelle instance du[`PsdImage`](../psdimage)classe à partir d'une image raster existante (pas d'image psd) avec mode couleur RVB avec 4 canaux 8 bits/canal et sans compression. |
| [PsdImage](psdimage#constructor_4)(Stream) | Initialise une nouvelle instance du[`PsdImage`](../psdimage) classe à partir du chemin spécifié à partir de l'image raster (et non de l'image psd dans le flux). Utilisé pour initialiser l'image psd avec les paramètres par défaut - Mode couleur - rvb, 4 canaux, 8 bits par canal, Compression - Raw. |
| [PsdImage](psdimage#constructor_6)(string) | Initialise une nouvelle instance du[`PsdImage`](../psdimage) classe à partir du chemin spécifié à partir de l'image raster (et non de l'image psd dans le chemin). Utilisé pour initialiser l'image psd avec les paramètres par défaut - Mode couleur - rvb, 4 canaux, 8 bits par canal, Compression - Raw. |
| [PsdImage](psdimage#constructor_2)(int, int) | Initialise une nouvelle instance du[`PsdImage`](../psdimage) classe avec une largeur et une hauteur spécifiées. Utilisé pour initialiser une image psd vide. |
| [PsdImage](psdimage#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | Initialise une nouvelle instance du[`PsdImage`](../psdimage) classe à partir d'une image raster existante (pas d'image psd) avec les paramètres du constructeur. |
| [PsdImage](psdimage#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | Initialise une nouvelle instance du[`PsdImage`](../psdimage) classe à partir du chemin spécifié à partir de l'image raster (pas de l'image psd dans le flux) avec les paramètres du constructeur. |
| [PsdImage](psdimage#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | Initialise une nouvelle instance du[`PsdImage`](../psdimage) classe à partir du chemin spécifié à partir de l'image raster (et non de l'image psd dans le chemin) avec les paramètres du constructeur. |
| [PsdImage](psdimage#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | Initialise une nouvelle instance du[`PsdImage`](../psdimage) classe avec la largeur, la hauteur, le paletter, le mode de couleur, le nombre de canaux et la longueur en bits spécifiés et les paramètres de mode de compression spécifiés. Utilisé pour initialiser une image psd vide. |

## Propriétés

| Nom | La description |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer) { get; set; } | Obtient ou définit le calque actif. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette) { get; set; } | Obtient ou définit une valeur indiquant si la palette de réglage automatique. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor) { get; set; } | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel) { get; } | Obtient les bits par canal. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel) { get; } | Obtient le nombre de bits d'image par pixel. |
| [Bounds](../../aspose.psd/image/bounds) { get; } | Obtient les limites de l'image. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount) { get; } | Obtient le nombre de canaux PSD. |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile) { get; set; } | Obtient ou définit le profil de couleur CMJN pour les images PSD CMJN. Doit être en paire avec RgbColorProfile pour une conversion de couleur correcte. |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode) { get; set; } | Obtient ou définit le mode couleur. |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression) { get; } | Obtient la méthode de compression. |
| [Container](../../aspose.psd/image/container) { get; } | Obtient le[`Image`](../../aspose.psd/image) conteneur. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer) { get; } | Obtient le flux de données de l'objet. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat) { get; } | Obtient une valeur de format de fichier |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle) { get; set; } | Obtient ou définit l'angle global. |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo) { get; } | Obtient les informations sur le masque de calque global. |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources) { get; set; } | Obtient ou définit les ressources de la couche globale. |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile) { get; set; } | Obtient ou définit le profil de couleur GREY (monochrome) pour les images PSD en niveaux de gris. |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha) { get; } | Obtient ou définit la résolution verticale, en pixels par pouce, de ce[`RasterImage`](../../aspose.psd/rasterimage) . |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor) { get; set; } | Obtient ou définit une valeur indiquant si l'image a une couleur d'arrière-plan. |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata) { get; set; } | Obtient ou définit une valeur indiquant si le premier canal alpha contient les données de transparence pour le résultat fusionné lors de la spécification des données de couches. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor) { get; set; } | Obtient une valeur indiquant si l'image a une couleur transparente. |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height) { get; } | Obtient la hauteur de l'image. |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution) { get; set; } | Obtient ou définit la résolution horizontale, en pixels par pouce, de ce[`PsdImage`](../psdimage) . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity) { get; } | Obtient l'opacité de cette image. |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources) { get; set; } | Obtient ou définit les ressources d'image PSD. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor) { get; set; } | Obtient ou définit le moniteur d'interruption. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached) { get; } | Obtient une valeur indiquant si les données d'image sont actuellement mises en cache. |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten) { get; } | Obtient une valeur indiquant si l'image psd est aplatie. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable) { get; } | Obtient une valeur indiquant si le chargement des données brutes est disponible. |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers) { get; set; } | Obtient ou définit les calques PSD. |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager) { get; } | Obtient le gestionnaire de calques liés. |
| [Palette](../../aspose.psd/image/palette) { get; set; } | Obtient ou définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents) { get; set; } | Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter) { get; set; } | Obtient ou définit le convertisseur de couleur personnalisé |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat) { get; } | Obtient le format des données brutes. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings) { get; } | Obtient les paramètres de données brutes actuels. Notez que lorsque vous utilisez ces paramètres, les données se chargent sans conversion. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex) { get; set; } | Obtient ou définit l'index de secours à utiliser lorsque l'index de palette est hors limites |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter) { get; set; } | Obtient ou définit le convertisseur de couleur indexé |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize) { get; } | Obtient la taille de ligne brute en octets. |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile) { get; set; } | Obtient ou définit le profil de couleur RVB pour les images PSD CMJN. Doit être en paire avec CmykColorProfile pour une conversion de couleur correcte. |
| [Size](../../aspose.psd/image/size) { get; } | Obtient la taille de l'image. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider) { get; } | Obtient le fournisseur d'objet intelligent. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor) { get; set; } | Obtient la couleur transparente de l'image. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata) { get; set; } | Obtient ou définit une valeur indiquant s'il faut mettre à jour les métadonnées XMP. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata) { get; set; } | Obtient ou définit une valeur indiquant s'il faut utiliser le chargement des données brutes lorsque le chargement des données brutes est disponible. |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version) { get; set; } | Obtient ou définit la version. |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution) { get; set; } | Obtient ou définit la résolution verticale, en pixels par pouce, de ce[`PsdImage`](../psdimage) . |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width) { get; } | Obtient la largeur de l'image. |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata) { get; set; } | Obtient ou définit les métadonnées XMP. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer)() | Ajoute le calque de réglage noir blanc. |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer)(int, int) | Ajoute le calque de réglage de la luminosité/contraste. |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer)() | Ajoute la couche de réglage du mélangeur de canaux avec les paramètres par défaut |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer)() | Ajoute le calque de réglage de la balance des couleurs. |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer)() | Ajoute le calque de réglage des courbes. |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer)(float, float, float) | Ajoute le calque de réglage de l'exposition. |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer)() | Ajoute le calque de réglage de teinte/saturation. |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer)() | Ajoute un calque de réglage inversé. |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer)(Layer) | Ajoute le calque. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup)(string, int, bool) | Ajoute le groupe de calques. |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer)() | Ajoute le calque de réglage des niveaux. |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer)(Color) | Ajoute le calque PhotoFilter. |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer)() | Ajoute un nouveau calque régulier. |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer)(string, Rectangle) | Ajoute un nouveau calque de texte. |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer)() | Ajoute le calque de réglage Vibrance. |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness)(int) | Réglage d'une luminosité pour l'image. |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast)(float) | Image contrastée |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma#adjustgamma)(float) | Correction gamma d'une image. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma#adjustgamma_1)(float, float, float) | Correction gamma d'une image. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley#binarizebradley)(double) | Binarisation d'une image à l'aide de l'algorithme de seuillage adaptatif de Bradley à l'aide du seuillage d'image intégral |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley#binarizebradley_1)(double, int) | Binarisation d'une image à l'aide de l'algorithme de seuillage adaptatif de Bradley à l'aide du seuillage d'image intégral |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed)(byte) | Binarisation d'une image avec seuil prédéfini |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu)() | Binarisation d'une image avec seuillage Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata)() | Met en cache les données et garantit qu'aucun chargement de données supplémentaire ne sera effectué à partir du sous-jacent[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.psd/image/cansave)(ImageOptionsBase) | Détermine si l'image peut être enregistrée dans le format de fichier spécifié représenté par les options d'enregistrement transmises. |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert)(PsdOptions) | Convertit ce format d'image en celui spécifié dans les options. |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop#crop)(Rectangle) | Recadrage de l'image. |
| virtual [Crop](../../aspose.psd/rasterimage/crop)(int, int, int, int) | Recadrer l'image avec des décalages. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Supprime l'instance actuelle. |
| [Dither](../../aspose.psd/rasterimage/dither)(DitheringMethod, int) | Effectue un tramage sur l'image actuelle. |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither#dither_1)(DitheringMethod, int, IColorPalette) | Effectue un tramage sur l'image actuelle. |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter)(Rectangle, FilterOptionsBase) | Filtre le rectangle spécifié. |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage)() | Aplatit tous les calques. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel)(int, int) | Obtient une image pixel ARGB 32 bits. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels)(Rectangle) | Obtient le tableau de pixels ARGB 32 bits par défaut. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions)(object[]) | Récupère les options par défaut. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels)(Rectangle, IPartialArgb32PixelLoader) | Obtient le tableau de pixels par défaut à l'aide du chargeur de pixels partiel. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata)(Rectangle, RawDataSettings) | Obtient le tableau de données brutes par défaut. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Obtient le tableau de données brutes par défaut à l'aide du chargeur de pixels partiel. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate)(bool) | Obtient la date et l'heure de la dernière modification de l'image de ressource. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions)() | Obtient les options basées sur les paramètres du fichier d'origine. Cela peut être utile pour conserver la profondeur de bits et d'autres paramètres de l'image d'origine inchangés. Par exemple, si nous chargeons une image PNG noir-blanc avec 1 bit par pixel, puis enregistrez-le en utilisant the [`Save`](../../aspose.psd/datastreamsupporter/save) , l'image PNG de sortie avec 8 bits par pixel sera produite. Pour l'éviter et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et passez-les au[`Save`](../../aspose.psd/image/save)méthode comme deuxième paramètre. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel)(int, int) | Obtient un pixel d'image. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle)() | Obtient l'angle d'inclinaison. Cette méthode est applicable aux documents texte numérisés, pour déterminer l'angle d'inclinaison lors de la numérisation. |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale)() | Transformation d'une image en sa représentation en niveaux de gris |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels)(Rectangle) | Charge les pixels ARGB 32 bits. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels)(Rectangle) | Charge les pixels ARGB 64 bits. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels)(Rectangle) | Charge les pixels au format CMJN. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels)(Rectangle, IPartialArgb32PixelLoader) | Charge les pixels ARGB 32 bits partiellement par packs. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels)(Rectangle, IPartialPixelLoader) | Charge les pixels partiellement par packs. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels)(Rectangle) | Charge les pixels. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Charge les données brutes. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Charge les données brutes. |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers)(Layer, Layer) | Fusionne les calques. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle)() | Normalise l'angle. Cette méthode est applicable aux documents texte numérisés pour se débarrasser de la numérisation biaisée. Cette méthode utilise[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle) et[`Rotate`](../../aspose.psd/rasterimage/rotate) méthodes. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle)(bool, Color) | Normalise l'angle. Cette méthode est applicable aux documents texte numérisés pour se débarrasser de la numérisation biaisée. Cette méthode utilise[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle) et[`Rotate`](../../aspose.psd/rasterimage/rotate) méthodes. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline)(int) | Lit toute la ligne de balayage par l'index de ligne de balayage spécifié. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline)(int) | Lit toute la ligne de balayage par l'index de ligne de balayage spécifié. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor)(Color, byte, Color) | Remplace une couleur par une autre avec la différence autorisée et conserve la valeur alpha d'origine pour enregistrer des bords lisses. |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor#replacecolor_1)(int, byte, int) | Remplace une couleur par une autre avec la différence autorisée et conserve la valeur alpha d'origine pour enregistrer des bords lisses. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors)(Color) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et conserve la valeur alpha d'origine pour économiser des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors#replacenontransparentcolors_1)(int) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et conserve la valeur alpha d'origine pour économiser des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| [Resize](../../aspose.psd/image/resize)(int, int) | Redimensionne l'image. Le défautLeftTopToLeftTopest utilisé. |
| override [Resize](../../aspose.psd/rastercachedimage/resize)(int, int, ImageResizeSettings) | Redimensionne l'image. |
| override [Resize](../../aspose.psd/rastercachedimage/resize)(int, int, ResizeType) | Redimensionne l'image. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally)(int) | Redimensionne la hauteur proportionnellement. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally#resizeheightproportionally_1)(int, ImageResizeSettings) | Redimensionne la hauteur proportionnellement. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Redimensionne la hauteur proportionnellement. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally)(int) | Redimensionne la largeur proportionnellement. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally#resizewidthproportionally_1)(int, ImageResizeSettings) | Redimensionne la largeur proportionnellement. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Redimensionne la largeur proportionnellement. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate#rotate)(float) | Faire pivoter l'image autour du centre. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate#rotate_1)(float, bool, Color) | Faire pivoter l'image autour du centre. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip)(RotateFlipType) | Fait pivoter, retourne ou fait pivoter et retourne l'image. |
| [Save](../../aspose.psd/image/save)() | Enregistre les données d'image dans le flux sous-jacent. |
| [Save](../../aspose.psd/datastreamsupporter/save)(Stream) | Enregistre les données de l'objet dans le flux spécifié. |
| [Save](../../aspose.psd/datastreamsupporter/save)(string) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [Save](../../aspose.psd/image/save)(Stream, ImageOptionsBase) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save)(string, bool) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| virtual [Save](../../aspose.psd/image/save)(string, ImageOptionsBase) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| override [Save](../../aspose.psd/rasterimage/save)(Stream, ImageOptionsBase, Rectangle) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| virtual [Save](../../aspose.psd/image/save)(string, ImageOptionsBase, Rectangle) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels)(Rectangle, int[]) | Enregistre les pixels ARGB 32 bits. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels)(Rectangle, int[]) | Enregistre les pixels. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels)(Rectangle, Color[]) | Enregistre les pixels. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata)(byte[], int, Rectangle, RawDataSettings) | Enregistre les données brutes. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel)(int, int, int) | Définit un pixel ARGB 32 bits d'image pour la position spécifiée. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette)(IColorPalette, bool) | Définit la palette d'images. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel)(int, int, Color) | Définit un pixel d'image pour la position spécifiée. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution)(double, double) | Définit la résolution pour ce[`RasterImage`](../../aspose.psd/rasterimage) . |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap)() | Convertit l'image raster en bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline)(int, int[]) | Écrit toute la ligne de balayage dans l'index de ligne de balayage spécifié. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline)(int, Color[]) | Écrit toute la ligne de balayage dans l'index de ligne de balayage spécifié. |

## Des champs

| Nom | La description |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion) | La version PSD par défaut. |

### Exemples

Le code suivant montre la possibilité de faire pivoter l'image selon une valeur d'angle spécifique.

```csharp
[C#]

string sourceFileName = "TheHat.psd";
var pngOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };

// Rotation de l'image entière
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Rotate(angle);

        string outFileName = "TheHatRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}

// Couche tournante
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    for (int i = 0; i < 4; i++)
    {
        int angle = i * 45;
        image.Layers[1].Rotate(angle);

        string outFileName = "TheHatLayerRotated" + angle + ".png";

        image.Save(outFileName, pngOptions);
    }
}
```

### Voir également

* class [RasterCachedImage](../../aspose.psd/rastercachedimage)
* espace de noms [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd)
* Assemblée [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
