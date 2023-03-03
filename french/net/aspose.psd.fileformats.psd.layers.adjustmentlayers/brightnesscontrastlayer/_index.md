---
title: Class BrightnessContrastLayer
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers.BrightnessContrastLayer classe. Couche de luminosité/contraste.
type: docs
weight: 1680
url: /fr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer/
---
## BrightnessContrastLayer class

Couche de luminosité/contraste.

```csharp
public class BrightnessContrastLayer : AdjustmentLayer
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Obtient ou définit une valeur indiquant si la palette de réglage automatique. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | Obtient le nombre de bits d'image par pixel. |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | Obtient les options de fusion. |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey/) { get; set; } | Obtient ou définit la clé du mode de fusion. |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | Obtient la signature du mode de fusion. |
| [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | Obtient ou définit la position de la couche inférieure. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Obtient les limites de l'image. |
| [Brightness](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer/brightness/) { get; set; } | Obtient ou définit la luminosité. Pour le PS, la plage de luminosité est de -150 à +150. Mais nous ignorons cela. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | Obtient ou définit les informations du canal. |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | Obtient le nombre de canaux de la couche. |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | Obtient ou définit l'écrêtage du calque. 0 = base, 1 = non base. |
| [Container](../../aspose.psd/image/container/) { get; } | Obtient le[`Image`](../../aspose.psd/image/) conteneur. |
| [Contrast](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer/contrast/) { get; set; } | Obtient ou définit le contraste. Pour PS, la plage de contraste est de -50 à +100. Mais nous ignorons cela. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Obtient le flux de données de l'objet. |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | Obtient ou définit le nom d'affichage de la couche. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | Obtient la longueur des informations supplémentaires de la couche en octets. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Obtient une valeur de format de fichier |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | Obtient ou définit le remplissage du calque. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | Obtient ou définit l'opacité du remplissage. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | Obtient ou définit les indicateurs de calque. bit 0 = transparence protégée ; bit 1 = visible ; bit 2 = obsolète ; bit 3 = 1 pour Photoshop 5.0 et versions ultérieures, indique si le bit 4 contient des informations utiles ; bit 4 = données de pixel sans rapport avec l'apparence du document. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | Obtient une valeur indiquant si cette instance a alpha. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Obtient ou définit une valeur indiquant si l'image a une couleur d'arrière-plan. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Obtient une valeur indiquant si l'image a une couleur transparente. |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height/) { get; } | Obtient la hauteur de l'image. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Obtient ou définit la résolution horizontale, en pixels par pouce, de ce[`RasterImage`](../../aspose.psd/rasterimage/) . |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Obtient l'opacité de cette image. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Obtient ou définit le moniteur d'interruption. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Obtient une valeur indiquant si les données d'image sont actuellement mises en cache. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Obtient une valeur indiquant si le chargement des données brutes est disponible. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | Obtient ou définit une valeur indiquant si le calque est visible |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | Obtient une valeur indiquant si cette instance est visible dans le groupe (si la couche n'est pas dans le groupe, cela signifie le groupe racine). |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | Obtient ou définit les données des plages de fusion des calques. |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | Obtient ou définit la date et l'heure de création de la couche. |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | Obtient ou définit le verrouillage de couche. Notez que si l'indicateur LayerFlags.TransparencyProtected est défini, il sera écrasé par l'indicateur de verrouillage de couche. Pour renvoyer LayerFlags.TransparencyProtected, l'indicateur doit s'appliquer à l'option de couche layer.Flags &#x7C;= LayerFlags.TransparencyProtected |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | Obtient ou définit les données du masque de calque. |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | Obtient les options de calque. |
| [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | Obtient ou définit la position du calque de gauche. |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | Obtient la longueur globale de la couche en octets. |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | Obtient ou définit le nom de la couche. |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | Obtient ou définit l'opacité du calque. 0 = transparent, 255 = opaque. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Obtient ou définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Obtient ou définit le convertisseur de couleur personnalisé |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Obtient le format des données brutes. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Obtient les paramètres de données brutes actuels. Notez que lorsque vous utilisez ces paramètres, les données se chargent sans conversion. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Obtient ou définit l'index de secours à utiliser lorsque l'index de palette est hors limites |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Obtient ou définit le convertisseur de couleur indexé |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Obtient la taille de ligne brute en octets. |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | Obtient ou définit les ressources de la couche. |
| [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | Obtient ou définit la bonne position de calque. |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | Obtient ou définit la surbrillance de la couleur de la feuille décorative dans la liste des calques |
| [Size](../../aspose.psd/image/size/) { get; } | Obtient la taille de l'image. |
| [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | Obtient ou définit la position de la couche supérieure. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Obtient la couleur transparente de l'image. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Obtient ou définit une valeur indiquant s'il faut mettre à jour les métadonnées XMP. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Obtient ou définit une valeur indiquant s'il faut utiliser le chargement des données brutes lorsque le chargement des données brutes est disponible. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Obtient ou définit la résolution verticale, en pixels par pouce, de ce[`RasterImage`](../../aspose.psd/rasterimage/) . |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width/) { get; } | Obtient la largeur de l'image. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Obtient ou définit les métadonnées XMP. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | Ajoute le masque au calque actuel. |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | Réglage d'une luminosité pour l'image. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | Image contrastée |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | Correction gamma d'une image. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | Correction gamma d'une image. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | Binarisation d'une image à l'aide de l'algorithme de seuillage adaptatif de Bradley à l'aide du seuillage d'image intégral |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | Binarisation d'une image à l'aide de l'algorithme de seuillage adaptatif de Bradley à l'aide du seuillage d'image intégral |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | Binarisation d'une image avec seuil prédéfini |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Binarisation d'une image avec seuillage Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Met en cache les données et garantit qu'aucun chargement de données supplémentaire ne sera effectué à partir du sous-jacent[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Détermine si l'image peut être enregistrée dans le format de fichier spécifié représenté par les options d'enregistrement transmises. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | Recadrage de l'image. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Recadrer l'image avec des décalages. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Supprime l'instance actuelle. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Effectue un tramage sur l'image actuelle. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | Effectue un tramage sur l'image actuelle. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | Dessine l'image sur le calque. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Filtre le rectangle spécifié. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Obtient une image pixel ARGB 32 bits. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Obtient le tableau de pixels ARGB 32 bits par défaut. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Récupère les options par défaut. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Obtient le tableau de pixels par défaut à l'aide du chargeur de pixels partiel. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Obtient le tableau de données brutes par défaut. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Obtient le tableau de données brutes par défaut à l'aide du chargeur de pixels partiel. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | Renvoie un code de hachage pour cette instance. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Obtient la date et l'heure de la dernière modification de l'image de ressource. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Obtient les options basées sur les paramètres du fichier d'origine. Cela peut être utile pour conserver la profondeur de bits et d'autres paramètres de l'image d'origine inchangés. Par exemple, si nous chargeons une image PNG noir-blanc avec 1 bit par pixel, puis enregistrez-le en utilisant the [`Save`](../../aspose.psd/datastreamsupporter/save/) , l'image PNG de sortie avec 8 bits par pixel sera produite. Pour l'éviter et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et passez-les au[`Save`](../../aspose.psd/image/save/)méthode comme deuxième paramètre. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Obtient un pixel d'image. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Obtient l'angle d'inclinaison. Cette méthode est applicable aux documents texte numérisés, pour déterminer l'angle d'inclinaison lors de la numérisation. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | Transformation d'une image en sa représentation en niveaux de gris |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Charge les pixels ARGB 32 bits. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Charge les pixels ARGB 64 bits. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Charge les pixels au format CMJN. |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Charge les pixels ARGB 32 bits partiellement par packs. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Charge les pixels partiellement par packs. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Charge les pixels. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Charge les données brutes. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Charge les données brutes. |
| override [MergeLayerTo](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/adjustmentlayer/mergelayerto/)(Layer) | Fusionne le calque avec le calque spécifié |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Normalise l'angle. Cette méthode est applicable aux documents texte numérisés pour se débarrasser de la numérisation biaisée. Cette méthode utilise[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) et[`Rotate`](../../aspose.psd/rasterimage/rotate/) méthodes. |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Normalise l'angle. Cette méthode est applicable aux documents texte numérisés pour se débarrasser de la numérisation biaisée. Cette méthode utilise[`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) et[`Rotate`](../../aspose.psd/rasterimage/rotate/) méthodes. |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Lit toute la ligne de balayage par l'index de ligne de balayage spécifié. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Lit toute la ligne de balayage par l'index de ligne de balayage spécifié. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Remplace une couleur par une autre avec la différence autorisée et conserve la valeur alpha d'origine pour enregistrer des bords lisses. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | Remplace une couleur par une autre avec la différence autorisée et conserve la valeur alpha d'origine pour enregistrer des bords lisses. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et conserve la valeur alpha d'origine pour économiser des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et conserve la valeur alpha d'origine pour économiser des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Redimensionne l'image. Le défautLeftTopToLeftTopest utilisé. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Redimensionne l'image. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Redimensionne l'image. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Redimensionne la hauteur proportionnellement. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Redimensionne la hauteur proportionnellement. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Redimensionne la hauteur proportionnellement. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Redimensionne la largeur proportionnellement. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Redimensionne la largeur proportionnellement. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Redimensionne la largeur proportionnellement. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | Faire pivoter l'image autour du centre. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | Faire pivoter l'image autour du centre. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Fait pivoter, retourne ou fait pivoter et retourne l'image. |
| [Save](../../aspose.psd/image/save/)() | Enregistre les données d'image dans le flux sous-jacent. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream) | Enregistre les données de l'objet dans le flux spécifié. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, bool) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream, ImageOptionsBase, Rectangle) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase, Rectangle) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Enregistre les pixels ARGB 32 bits. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Enregistre les pixels. |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Enregistre les pixels. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Enregistre les données brutes. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Définit un pixel ARGB 32 bits d'image pour la position spécifiée. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Définit la palette d'images. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Définit un pixel d'image pour la position spécifiée. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Définit la résolution pour ce[`RasterImage`](../../aspose.psd/rasterimage/) . |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | Crée une copie superficielle du calque actuel. Veuillez[https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx) pour explication. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Convertit l'image raster en bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Écrit toute la ligne de balayage dans l'index de ligne de balayage spécifié. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Écrit toute la ligne de balayage dans l'index de ligne de balayage spécifié. |

### Voir également

* class [Layer](../../aspose.psd.fileformats.psd.layers/layer/)
* class [AdjustmentLayer](../adjustmentlayer/)
* espace de noms [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* Assemblée [Aspose.PSD](../../)


