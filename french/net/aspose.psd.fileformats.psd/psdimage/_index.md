---
title: "Classe PsdImage"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.PsdImage class. Définit la classe PsdImage qui offre la capacité de charger, modifier, enregistrer des fichiers PSD ainsi que de mettre à jour les propriétés, ajouter des filigranes, effectuer des opérations graphiques ou convertir un format de fichier en un autre. Aspose.PSD prend en charge l'importation en tant que calque et l'exportation vers les formats suivants : Png Jpeg Jpeg2000 Gif Bmp Tiff Psd Psb ainsi que l'exportation vers Pdf avec texte sélectionnable"
type: docs
weight: 4050
url: /fr/net/aspose.psd.fileformats.psd/psdimage/
---
{{< psd/tize >}}
## PsdImage class

Définit la classe PsdImage qui offre la capacité de charger, modifier, enregistrer des fichiers PSD ainsi que de mettre à jour les propriétés, ajouter des filigranes, effectuer des opérations graphiques ou convertir un format de fichier en un autre. Aspose.PSD prend en charge l'importation en tant que calque et l'exportation vers les formats suivants : Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb ainsi que l'exportation vers Pdf avec texte sélectionnable

```csharp
public sealed class PsdImage : RasterCachedImage
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PsdImage](psdimage/#constructor)(RasterImage) | Initialise une nouvelle instance de la classe `PsdImage` à partir d'une image raster existante (pas une image psd) avec le mode couleur RGB, 4 canaux, 8 bits/canal et aucune compression. |
| [PsdImage](psdimage/#constructor_4)(Stream) | Initialise une nouvelle instance de la classe `PsdImage` à partir du chemin spécifié d'une image raster (pas d'image psd dans le flux). Utilisé pour initialiser une image psd avec les paramètres par défaut : mode couleur - rgb, 4 canaux, 8 bits par canal, compression - Raw. |
| [PsdImage](psdimage/#constructor_6)(string) | Initialise une nouvelle instance de la classe `PsdImage` à partir du chemin spécifié d'une image raster (pas d'image psd dans le chemin). Utilisé pour initialiser une image psd avec les paramètres par défaut : mode couleur - rgb, 4 canaux, 8 bits par canal, compression - Raw. |
| [PsdImage](psdimage/#constructor_2)(int, int) | Initialise une nouvelle instance de la classe `PsdImage` avec la largeur et la hauteur spécifiées. Utilisé pour initialiser une image psd vide. |
| [PsdImage](psdimage/#constructor_1)(RasterImage, ColorModes, short, short, int, CompressionMethod) | Initialise une nouvelle instance de la classe `PsdImage` à partir d'une image raster existante (pas d'image psd) avec des paramètres de constructeur. |
| [PsdImage](psdimage/#constructor_5)(Stream, ColorModes, short, short, int, CompressionMethod) | Initialise une nouvelle instance de la classe `PsdImage` à partir du chemin spécifié d'une image raster (pas d'image psd dans le flux) avec des paramètres de constructeur. |
| [PsdImage](psdimage/#constructor_7)(string, ColorModes, short, short, int, CompressionMethod) | Initialise une nouvelle instance de la classe `PsdImage` à partir du chemin spécifié d'une image raster (pas d'image psd dans le chemin) avec des paramètres de constructeur. |
| [PsdImage](psdimage/#constructor_3)(int, int, IColorPalette, ColorModes, short, short, int, CompressionMethod) | Initialise une nouvelle instance de la classe `PsdImage` avec la largeur, la hauteur, la palette, le mode couleur, le nombre de canaux et la profondeur de bits des canaux ainsi que les paramètres du mode de compression spécifiés. Utilisé pour initialiser une image psd vide. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ActiveLayer](../../aspose.psd.fileformats.psd/psdimage/activelayer/) { get; set; } | Obtient ou définit le calque actif. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Obtient ou définit une valeur indiquant si la palette d'ajustement automatique. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| [BitsPerChannel](../../aspose.psd.fileformats.psd/psdimage/bitsperchannel/) { get; } | Obtient le nombre de bits par canal. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd/psdimage/bitsperpixel/) { get; } | Obtient le nombre de bits par pixel de l'image. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Obtient les limites de l'image. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Obtient ou définit l'indice de taille du tampon, qui définit la taille maximale autorisée pour tous les tampons internes. |
| [ChannelsCount](../../aspose.psd.fileformats.psd/psdimage/channelscount/) { get; } | Obtient le nombre de canaux PSD. |
| [CmykColorProfile](../../aspose.psd.fileformats.psd/psdimage/cmykcolorprofile/) { get; set; } | Obtient ou définit le profil couleur CMYK pour les images PSD CMYK. Doit être associé à RgbColorProfile pour une conversion de couleur correcte. |
| [ColorMode](../../aspose.psd.fileformats.psd/psdimage/colormode/) { get; set; } | Obtient ou définit le mode couleur. |
| [Compression](../../aspose.psd.fileformats.psd/psdimage/compression/) { get; } | Obtient la méthode de compression. |
| [Container](../../aspose.psd/image/container/) { get; } | Obtient le conteneur [`Image`](../../aspose.psd/image/). |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Obtient le flux de données de l'objet. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| override [FileFormat](../../aspose.psd.fileformats.psd/psdimage/fileformat/) { get; } | Obtient une valeur du format de fichier |
| [GlobalAngle](../../aspose.psd.fileformats.psd/psdimage/globalangle/) { get; set; } | Obtient ou définit l'angle global. |
| [GlobalLayerMaskInfo](../../aspose.psd.fileformats.psd/psdimage/globallayermaskinfo/) { get; } | Obtient les informations du masque de calque global. |
| [GlobalLayerResources](../../aspose.psd.fileformats.psd/psdimage/globallayerresources/) { get; set; } | Obtient ou définit les ressources de calque globales. |
| [GrayColorProfile](../../aspose.psd.fileformats.psd/psdimage/graycolorprofile/) { get; set; } | Obtient ou définit le profil couleur GRAY (monochrome) pour les images PSD en niveaux de gris. |
| override [HasAlpha](../../aspose.psd.fileformats.psd/psdimage/hasalpha/) { get; } | Obtient ou définit la résolution verticale, en pixels par pouce, de ce [`RasterImage`](../../aspose.psd/rasterimage/). |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Obtient ou définit une valeur indiquant si l'image possède une couleur d'arrière-plan. |
| [HasTransparencyData](../../aspose.psd.fileformats.psd/psdimage/hastransparencydata/) { get; set; } | Obtient ou définit une valeur indiquant si le premier canal alpha contient les données de transparence pour le résultat fusionné lors de la spécification des données de calques. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Obtient une valeur indiquant si l'image possède une couleur transparente. |
| override [Height](../../aspose.psd.fileformats.psd/psdimage/height/) { get; } | Obtient la hauteur de l'image. |
| override [HorizontalResolution](../../aspose.psd.fileformats.psd/psdimage/horizontalresolution/) { get; set; } | Obtient ou définit la résolution horizontale, en pixels par pouce, de ce `PsdImage`. |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Obtient l'opacité de cette image. |
| [ImageResources](../../aspose.psd.fileformats.psd/psdimage/imageresources/) { get; set; } | Obtient ou définit les ressources de l'image PSD. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Obtient ou définit le moniteur d'interruption. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Obtient une valeur indiquant si les données de l'image sont actuellement mises en cache. |
| [IsFlatten](../../aspose.psd.fileformats.psd/psdimage/isflatten/) { get; } | Obtient une valeur indiquant si l'image psd est aplatie. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Obtient une valeur indiquant si le chargement des données brutes est disponible. |
| [Layers](../../aspose.psd.fileformats.psd/psdimage/layers/) { get; set; } | Obtient ou définit les calques PSD. |
| [LinkedLayersManager](../../aspose.psd.fileformats.psd/psdimage/linkedlayersmanager/) { get; } | Obtient le gestionnaire des calques liés. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Obtient ou définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Obtient ou définit le convertisseur de couleur personnalisé |
| override [RawDataFormat](../../aspose.psd.fileformats.psd/psdimage/rawdataformat/) { get; } | Obtient le format des données brutes. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Obtient les paramètres actuels des données brutes. Notez que lors de l'utilisation de ces paramètres, les données se chargent sans conversion. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Obtient ou définit l'index de secours à utiliser lorsque l'index de la palette est hors limites |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Obtient ou définit le convertisseur de couleur indexée |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Obtient la taille brute de la ligne en octets. |
| [RgbColorProfile](../../aspose.psd.fileformats.psd/psdimage/rgbcolorprofile/) { get; set; } | Obtient ou définit le profil couleur RGB pour les images PSD CMYK. Doit être associé à CmykColorProfile pour une conversion de couleur correcte. |
| [Size](../../aspose.psd/image/size/) { get; } | Obtient la taille de l'image. |
| [SmartObjectProvider](../../aspose.psd.fileformats.psd/psdimage/smartobjectprovider/) { get; } | Obtient le fournisseur d'objets intelligents. |
| [Timeline](../../aspose.psd.fileformats.psd/psdimage/timeline/) { get; } | Obtient le [`Timeline`](./timeline/) de ce `PsdImage`. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Obtient la couleur transparente de l'image. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Obtient ou définit une valeur indiquant s'il faut mettre à jour les métadonnées XMP. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Obtient une valeur indiquant si la palette de l'image est utilisée. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Obtient ou définit une valeur indiquant s'il faut utiliser le chargement de données brutes lorsque le chargement de données brutes est disponible. |
| [Version](../../aspose.psd.fileformats.psd/psdimage/version/) { get; set; } | Obtient ou définit la version. |
| override [VerticalResolution](../../aspose.psd.fileformats.psd/psdimage/verticalresolution/) { get; set; } | Obtient ou définit la résolution verticale, en pixels par pouce, de ce `PsdImage`. |
| override [Width](../../aspose.psd.fileformats.psd/psdimage/width/) { get; } | Obtient la largeur de l'image. |
| override [XmpData](../../aspose.psd.fileformats.psd/psdimage/xmpdata/) { get; set; } | Obtient ou définit les métadonnées XMP. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddBlackWhiteAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addblackwhiteadjustmentlayer/)() | Ajoute le calque de réglage noir et blanc. |
| [AddBrightnessContrastAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addbrightnesscontrastadjustmentlayer/)(int, int) | Ajoute le calque de réglage luminosité/contraste. |
| [AddChannelMixerAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addchannelmixeradjustmentlayer/)() | Ajoute le calque de réglage du mélangeur de canaux avec les paramètres par défaut |
| [AddColorBalanceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcolorbalanceadjustmentlayer/)() | Ajoute le calque de réglage de la balance des couleurs. |
| [AddCurvesAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addcurvesadjustmentlayer/)() | Ajoute le calque de réglage des courbes. |
| [AddExposureAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addexposureadjustmentlayer/)(float, float, float) | Ajoute le calque de réglage de l'exposition. |
| [AddGradientMapAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addgradientmapadjustmentlayer/)() | Ajoute le calque de réglage GradientMap. |
| [AddHueSaturationAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addhuesaturationadjustmentlayer/)() | Ajoute le calque de réglage teinte/saturation. |
| [AddInvertAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addinvertadjustmentlayer/)() | Ajoute un calque de réglage d'inversion. |
| [AddLayer](../../aspose.psd.fileformats.psd/psdimage/addlayer/)(Layer) | Ajoute le calque. |
| [AddLayerGroup](../../aspose.psd.fileformats.psd/psdimage/addlayergroup/)(string, int, bool) | Ajoute le groupe de calques. |
| [AddLevelsAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addlevelsadjustmentlayer/)() | Ajoute le calque de réglage des niveaux. |
| [AddPhotoFilterLayer](../../aspose.psd.fileformats.psd/psdimage/addphotofilterlayer/)(Color) | Ajoute le calque PhotoFilter. |
| [AddPosterizeAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addposterizeadjustmentlayer/)() | Ajoute le calque de réglage Posterize. |
| [AddRegularLayer](../../aspose.psd.fileformats.psd/psdimage/addregularlayer/)() | Ajoute un nouveau calque ordinaire. |
| [AddSelectiveColorAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addselectivecoloradjustmentlayer/)() | Ajoute le calque de réglage couleur sélective. |
| [AddShapeLayer](../../aspose.psd.fileformats.psd/psdimage/addshapelayer/)() | Ajoute un calque Shape vide. Sans chemins. Ils doivent être ajoutés au calque shape avant l'enregistrement. |
| [AddTextLayer](../../aspose.psd.fileformats.psd/psdimage/addtextlayer/)(string, Rectangle) | Ajoute un nouveau calque Texte. |
| [AddThresholdAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addthresholdadjustmentlayer/)() | Ajoute le calque de réglage du seuil. |
| [AddVibranceAdjustmentLayer](../../aspose.psd.fileformats.psd/psdimage/addvibranceadjustmentlayer/)() | Ajoute le calque de réglage de la vibrance. |
| override [AdjustBrightness](../../aspose.psd.fileformats.psd/psdimage/adjustbrightness/)(int) | Ajuste la luminosité de l'image. |
| override [AdjustContrast](../../aspose.psd.fileformats.psd/psdimage/adjustcontrast/)(float) | Contraste d'image |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma)(float) | Correction gamma d'une image. |
| override [AdjustGamma](../../aspose.psd.fileformats.psd/psdimage/adjustgamma/#adjustgamma_1)(float, float, float) | Correction gamma d'une image. |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley)(double) | Binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage par image intégrale |
| override [BinarizeBradley](../../aspose.psd.fileformats.psd/psdimage/binarizebradley/#binarizebradley_1)(double, int) | Binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage par image intégrale |
| override [BinarizeFixed](../../aspose.psd.fileformats.psd/psdimage/binarizefixed/)(byte) | Binarisation d'une image avec un seuil prédéfini |
| override [BinarizeOtsu](../../aspose.psd.fileformats.psd/psdimage/binarizeotsu/)() | Binarisation d'une image avec le seuillage d'Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Met en cache les données et garantit qu'aucun chargement de données supplémentaire ne sera effectué à partir du [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) sous-jacent. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Détermine si l'image peut être enregistrée au format de fichier spécifié représenté par les options d'enregistrement fournies. |
| [Convert](../../aspose.psd.fileformats.psd/psdimage/convert/)(PsdOptions) | Convertit le format de cette image en celui spécifié dans les options. |
| override [Crop](../../aspose.psd.fileformats.psd/psdimage/crop/#crop)(Rectangle) | Recadrage de l'image. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Recadrer l'image avec des décalages. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Libère l'instance actuelle. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Effectue un tramage sur l'image actuelle. |
| override [Dither](../../aspose.psd.fileformats.psd/psdimage/dither/#dither_1)(DitheringMethod, int, IColorPalette) | Effectue un tramage sur l'image actuelle. |
| override [Filter](../../aspose.psd.fileformats.psd/psdimage/filter/)(Rectangle, FilterOptionsBase) | Filtre le rectangle spécifié. |
| [FlattenImage](../../aspose.psd.fileformats.psd/psdimage/flattenimage/)() | Aplatis tous les calques. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Obtient un pixel ARGB 32 bits d'une image. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Obtient le tableau de pixels ARGB 32 bits par défaut. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Obtient les options par défaut. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Obtient le tableau de pixels par défaut en utilisant le chargeur de pixels partiel. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Obtient le tableau de données brutes par défaut. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Obtient le tableau de données brutes par défaut en utilisant le chargeur de pixels partiel. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Obtient la date et l'heure de la dernière modification de l'image de ressource. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Obtient les options basées sur les paramètres du fichier original. Cela peut être utile pour conserver la profondeur de couleur et les autres paramètres de l'image originale inchangés. Par exemple, si nous chargeons une image PNG noir et blanc avec 1 bit par pixel puis l'enregistrons en utilisant la méthode [`Save`](../../aspose.psd/datastreamsupporter/save/), l'image PNG de sortie avec 8 bits par pixel sera produite. Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre à la méthode [`Save`](../../aspose.psd/image/save/) en tant que deuxième paramètre. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Obtient un pixel d'image. Avertissement de performance : évitez d'utiliser cette méthode pour parcourir tous les pixels de l'image, car cela peut entraîner d'importants problèmes de performance. Pour une manipulation des pixels plus efficace, utilisez la méthode `LoadArgb32Pixels` pour récupérer l'ensemble du tableau de pixels simultanément. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Obtient l'angle d'inclinaison. Cette méthode s'applique aux documents texte numérisés, afin de déterminer l'angle d'inclinaison lors de la numérisation. |
| override [Grayscale](../../aspose.psd.fileformats.psd/psdimage/grayscale/)() | Transformation d'une image en sa représentation en niveaux de gris |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Charge des pixels ARGB 32 bits. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Charge des pixels ARGB 64 bits. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Charge des pixels au format CMYK. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | Charge des pixels au format CMYK. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/). |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Charge partiellement des pixels ARGB 32 bits par paquets. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Charge partiellement des pixels par paquets. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Charge des pixels. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Charge des données brutes. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Charge des données brutes. |
| [MergeLayers](../../aspose.psd.fileformats.psd/psdimage/mergelayers/)(Layer, Layer) | Fusionne les calques. |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Normalise l'angle. Cette méthode s'applique aux documents texte numérisés pour éliminer la distorsion du scan. Cette méthode utilise les méthodes [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) et [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Normalise l'angle. Cette méthode s'applique aux documents texte numérisés pour éliminer la distorsion du scan. Cette méthode utilise les méthodes [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) et [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Lit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Lit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses. |
| override [ReplaceColor](../../aspose.psd.fileformats.psd/psdimage/replacecolor/#replacecolor_1)(int, byte, int) | Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| override [ReplaceNonTransparentColors](../../aspose.psd.fileformats.psd/psdimage/replacenontransparentcolors/#replacenontransparentcolors_1)(int) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Redimensionne l'image. Le redimensionnement par plus proche voisin par défaut est utilisé. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Redimensionne l'image. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Redimensionne l'image. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Redimensionne la hauteur proportionnellement. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_1)(int, ImageResizeSettings) | Redimensionne la hauteur proportionnellement. |
| override [ResizeHeightProportionally](../../aspose.psd.fileformats.psd/psdimage/resizeheightproportionally/#resizeheightproportionally_2)(int, ResizeType) | Redimensionne la hauteur proportionnellement. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Redimensionne la largeur proportionnellement. Le redimensionnement par plus proche voisin par défaut est utilisé. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_1)(int, ImageResizeSettings) | Redimensionne la largeur proportionnellement. |
| override [ResizeWidthProportionally](../../aspose.psd.fileformats.psd/psdimage/resizewidthproportionally/#resizewidthproportionally_2)(int, ResizeType) | Redimensionne la largeur proportionnellement. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate)(float) | Fait pivoter l'image autour du centre. |
| override [Rotate](../../aspose.psd.fileformats.psd/psdimage/rotate/#rotate_1)(float, bool, Color) | Fait pivoter l'image autour du centre. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Fait pivoter, retourner ou pivoter et retourner l'image. |
| [Save](../../aspose.psd/image/save/)() | Enregistre les données de l'image dans le flux sous-jacent. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Enregistre les données de l'objet dans le flux spécifié. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement. |
| override [Save](../../aspose.psd/rasterimage/save/)(Stream, ImageOptionsBase, Rectangle) | Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Enregistre les pixels ARGB 32 bits. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Enregistre les pixels. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Enregistre les pixels. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/). |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Enregistre les pixels. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Enregistre les données brutes. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Définit un pixel ARGB 32 bits de l'image pour la position spécifiée. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Définit la palette de l'image. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Définit le pixel de l'image pour la position spécifiée. |
| override [SetResolution](../../aspose.psd.fileformats.psd/psdimage/setresolution/)(double, double) | Définit la résolution pour ce `PsdImage`. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Convertit l'image raster en bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |

## Champs

| Nom | Description |
| --- | --- |
| const [DefaultVersion](../../aspose.psd.fileformats.psd/psdimage/defaultversion/) | La version PSD par défaut. |

## Exemples

Le code suivant démontre la capacité de faire pivoter l'image d'une valeur d'angle spécifique.

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

// Rotation du calque
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

### Voir aussi

* class [RasterCachedImage](../../aspose.psd/rastercachedimage/)
* namespace [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../)


