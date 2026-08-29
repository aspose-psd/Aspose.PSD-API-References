---
title: "Classe ColorBalanceAdjustmentLayer"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers.ColorBalanceAdjustmentLayer classe. La classe de calque d'ajustement de balance des couleurs"
type: docs
weight: 1770
url: /fr/net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/
---
{{< psd/tize >}}
## ColorBalanceAdjustmentLayer class

La classe de calque d'ajustement de la balance des couleurs.

```csharp
public class ColorBalanceAdjustmentLayer : AdjustmentLayer
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Obtient ou définit une valeur indiquant si la palette d'ajustement automatique. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| override [BitsPerPixel](../../aspose.psd.fileformats.psd.layers/layer/bitsperpixel/) { get; } | Obtient le nombre de bits par pixel de l'image. |
| [BlendClippedElements](../../aspose.psd.fileformats.psd.layers/layer/blendclippedelements/) { get; set; } | Obtient ou définit la fusion de l'élément découpé. |
| [BlendingOptions](../../aspose.psd.fileformats.psd.layers/layer/blendingoptions/) { get; } | Obtient les options de fusion. |
| virtual [BlendModeKey](../../aspose.psd.fileformats.psd.layers/layer/blendmodekey/) { get; set; } | Obtient ou définit la clé du mode de fusion. |
| [BlendModeSignature](../../aspose.psd.fileformats.psd.layers/layer/blendmodesignature/) { get; } | Obtient la signature du mode de fusion. |
| virtual [Bottom](../../aspose.psd.fileformats.psd.layers/layer/bottom/) { get; set; } | Obtient ou définit la position du calque inférieur. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Obtient les limites de l'image. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Obtient ou définit l'indice de taille du tampon, qui définit la taille maximale autorisée pour tous les tampons internes. |
| [ChannelInformation](../../aspose.psd.fileformats.psd.layers/layer/channelinformation/) { get; set; } | Obtient ou définit les informations du canal. |
| [ChannelsCount](../../aspose.psd.fileformats.psd.layers/layer/channelscount/) { get; } | Obtient le nombre de canaux du calque. |
| [Clipping](../../aspose.psd.fileformats.psd.layers/layer/clipping/) { get; set; } | Obtient ou définit le rognage du calque. 0 = base, 1 = non-base. |
| [Container](../../aspose.psd/image/container/) { get; } | Obtient le conteneur [`Image`](../../aspose.psd/image/). |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Obtient le flux de données de l'objet. |
| [DisplayName](../../aspose.psd.fileformats.psd.layers/layer/displayname/) { get; set; } | Obtient ou définit le nom d'affichage du calque. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| [ExtraLength](../../aspose.psd.fileformats.psd.layers/layer/extralength/) { get; } | Obtient la longueur des informations supplémentaires du calque en octets. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Obtient une valeur du format de fichier |
| [Filler](../../aspose.psd.fileformats.psd.layers/layer/filler/) { get; set; } | Obtient ou définit le remplissage du calque. |
| [FillOpacity](../../aspose.psd.fileformats.psd.layers/layer/fillopacity/) { get; set; } | Obtient ou définit l'opacité du remplissage. |
| [Flags](../../aspose.psd.fileformats.psd.layers/layer/flags/) { get; set; } | Obtient ou définit les indicateurs de calque. bit 0 = transparence protégée ; bit 1 = visible ; bit 2 = obsolète ; bit 3 = 1 pour Photoshop 5.0 et versions ultérieures, indique si le bit 4 contient des informations utiles ; bit 4 = données de pixel sans pertinence pour l'apparence du document. |
| override [HasAlpha](../../aspose.psd.fileformats.psd.layers/layer/hasalpha/) { get; } | Obtient une valeur indiquant si cette instance possède un canal alpha. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Obtient ou définit une valeur indiquant si l'image possède une couleur d'arrière-plan. |
| virtual [HasTransparentColor](../../aspose.psd/rasterimage/hastransparentcolor/) { get; set; } | Obtient une valeur indiquant si l'image possède une couleur transparente. |
| override [Height](../../aspose.psd.fileformats.psd.layers/layer/height/) { get; } | Obtient la hauteur de l'image. |
| [HighlightsCyanRedBalance](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/highlightscyanredbalance/) { get; set; } | Obtient ou définit le Highlights Cyan Red Balance. |
| [HighlightsMagentaGreenBalance](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/highlightsmagentagreenbalance/) { get; set; } | Obtient ou définit le Highlights Magenta Green Balance. |
| [HighlightsYellowBlueBalance](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/highlightsyellowbluebalance/) { get; set; } | Obtient ou définit le Highlights Yellow Blue Balance. |
| virtual [HorizontalResolution](../../aspose.psd/rasterimage/horizontalresolution/) { get; set; } | Obtient ou définit la résolution horizontale, en pixels par pouce, de ce [`RasterImage`](../../aspose.psd/rasterimage/). |
| virtual [ImageOpacity](../../aspose.psd/rasterimage/imageopacity/) { get; } | Obtient l'opacité de cette image. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Obtient ou définit le moniteur d'interruption. |
| override [IsCached](../../aspose.psd/rastercachedimage/iscached/) { get; } | Obtient une valeur indiquant si les données de l'image sont actuellement mises en cache. |
| [IsRawDataAvailable](../../aspose.psd/rasterimage/israwdataavailable/) { get; } | Obtient une valeur indiquant si le chargement des données brutes est disponible. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers/layer/isvisible/) { get; set; } | Obtient ou définit une valeur indiquant si le calque est visible |
| virtual [IsVisibleInGroup](../../aspose.psd.fileformats.psd.layers/layer/isvisibleingroup/) { get; } | Obtient une valeur indiquant si cette instance est visible dans le groupe (si le calque n'est pas dans un groupe, cela signifie le groupe racine). |
| [LayerBlendingRangesData](../../aspose.psd.fileformats.psd.layers/layer/layerblendingrangesdata/) { get; set; } | Obtient ou définit les données des plages de fusion du calque. |
| [LayerCreationDateTime](../../aspose.psd.fileformats.psd.layers/layer/layercreationdatetime/) { get; set; } | Obtient ou définit la date et l'heure de création du calque. |
| [LayerLock](../../aspose.psd.fileformats.psd.layers/layer/layerlock/) { get; set; } | Obtient ou définit le verrouillage du calque. Notez que si le drapeau LayerFlags.TransparencyProtected est défini, il sera écrasé par le drapeau de verrouillage du calque. Pour restituer le drapeau LayerFlags.TransparencyProtected, il faut l'appliquer à l'option de calque layer.Flags &#x7C;= LayerFlags.TransparencyProtected |
| [LayerMaskData](../../aspose.psd.fileformats.psd.layers/layer/layermaskdata/) { get; set; } | Obtient ou définit les données du masque du calque. |
| [LayerOptions](../../aspose.psd.fileformats.psd.layers/layer/layeroptions/) { get; } | Obtient les options du calque. |
| virtual [Left](../../aspose.psd.fileformats.psd.layers/layer/left/) { get; set; } | Obtient ou définit la position gauche du calque. |
| [Length](../../aspose.psd.fileformats.psd.layers/layer/length/) { get; } | Obtient la longueur totale du calque en octets. |
| [MidtonesCyanRedBalance](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonescyanredbalance/) { get; set; } | Obtient ou définit le Midtones Cyan Red Balance. |
| [MidtonesMagentaGreenBalance](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonesmagentagreenbalance/) { get; set; } | Obtient ou définit le Midtones Magenta Green Balance. |
| [MidtonesYellowBlueBalance](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/midtonesyellowbluebalance/) { get; set; } | Obtient ou définit le Midtones Yellow Blue Balance. |
| [Name](../../aspose.psd.fileformats.psd.layers/layer/name/) { get; set; } | Obtient ou définit le nom du calque. |
| [Opacity](../../aspose.psd.fileformats.psd.layers/layer/opacity/) { get; set; } | Obtient ou définit l'opacité du calque. 0 = transparent, 255 = opaque. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Obtient ou définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement. |
| virtual [PremultiplyComponents](../../aspose.psd/rasterimage/premultiplycomponents/) { get; set; } | Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/preserveluminosity/) { get; set; } | Obtient ou définit une valeur indiquant si ce [`BlncResource`](../../aspose.psd.fileformats.psd.layers.layerresources/blncresource/) préserve la luminosité. |
| [RawCustomColorConverter](../../aspose.psd/rasterimage/rawcustomcolorconverter/) { get; set; } | Obtient ou définit le convertisseur de couleur personnalisé |
| virtual [RawDataFormat](../../aspose.psd/rasterimage/rawdataformat/) { get; } | Obtient le format des données brutes. |
| [RawDataSettings](../../aspose.psd/rasterimage/rawdatasettings/) { get; } | Obtient les paramètres actuels des données brutes. Notez que lors de l'utilisation de ces paramètres, les données se chargent sans conversion. |
| [RawFallbackIndex](../../aspose.psd/rasterimage/rawfallbackindex/) { get; set; } | Obtient ou définit l'index de secours à utiliser lorsque l'index de la palette est hors limites |
| [RawIndexedColorConverter](../../aspose.psd/rasterimage/rawindexedcolorconverter/) { get; set; } | Obtient ou définit le convertisseur de couleur indexée |
| virtual [RawLineSize](../../aspose.psd/rasterimage/rawlinesize/) { get; } | Obtient la taille brute de la ligne en octets. |
| [Resources](../../aspose.psd.fileformats.psd.layers/layer/resources/) { get; set; } | Obtient ou définit les ressources du calque. |
| virtual [Right](../../aspose.psd.fileformats.psd.layers/layer/right/) { get; set; } | Obtient ou définit la position du calque droit. |
| [ShadowsCyanRedBalance](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/shadowscyanredbalance/) { get; set; } | Obtient ou définit le Shadows Cyan Red Balance. |
| [ShadowsMagentaGreenBalance](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/shadowsmagentagreenbalance/) { get; set; } | Obtient ou définit le Shadows Magenta Green Balance. |
| [ShadowsYellowBlueBalance](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/shadowsyellowbluebalance/) { get; set; } | Obtient ou définit le Shadows YellowBlue Balance. |
| [SheetColorHighlight](../../aspose.psd.fileformats.psd.layers/layer/sheetcolorhighlight/) { get; set; } | Obtient ou définit la mise en évidence de la couleur de la feuille décorative dans la liste des calques |
| [Size](../../aspose.psd/image/size/) { get; } | Obtient la taille de l'image. |
| virtual [Top](../../aspose.psd.fileformats.psd.layers/layer/top/) { get; set; } | Obtient ou définit la position du calque supérieur. |
| virtual [TransparentColor](../../aspose.psd/rasterimage/transparentcolor/) { get; set; } | Obtient la couleur transparente de l'image. |
| virtual [UpdateXmpData](../../aspose.psd/rasterimage/updatexmpdata/) { get; set; } | Obtient ou définit une valeur indiquant s'il faut mettre à jour les métadonnées XMP. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Obtient une valeur indiquant si la palette de l'image est utilisée. |
| virtual [UseRawData](../../aspose.psd/rasterimage/userawdata/) { get; set; } | Obtient ou définit une valeur indiquant s'il faut utiliser le chargement de données brutes lorsque le chargement de données brutes est disponible. |
| virtual [VerticalResolution](../../aspose.psd/rasterimage/verticalresolution/) { get; set; } | Obtient ou définit la résolution verticale, en pixels par pouce, de ce [`RasterImage`](../../aspose.psd/rasterimage/). |
| override [Width](../../aspose.psd.fileformats.psd.layers/layer/width/) { get; } | Obtient la largeur de l'image. |
| virtual [XmpData](../../aspose.psd/rasterimage/xmpdata/) { get; set; } | Obtient ou définit les métadonnées XMP. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddLayerMask](../../aspose.psd.fileformats.psd.layers/layer/addlayermask/)(LayerMaskData) | Ajoute le masque au calque actuel. |
| override [AdjustBrightness](../../aspose.psd/rastercachedimage/adjustbrightness/)(int) | Ajuste la luminosité de l'image. |
| override [AdjustContrast](../../aspose.psd/rastercachedimage/adjustcontrast/)(float) | Contraste d'image |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float) | Correction gamma d'une image. |
| override [AdjustGamma](../../aspose.psd/rastercachedimage/adjustgamma/)(float, float, float) | Correction gamma d'une image. |
| [ApplyLayerMask](../../aspose.psd.fileformats.psd.layers/layer/applylayermask/)() | Applique le masque de calque au calque, puis supprime le masque. |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double) | Binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage par image intégrale |
| override [BinarizeBradley](../../aspose.psd/rastercachedimage/binarizebradley/)(double, int) | Binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage par image intégrale |
| override [BinarizeFixed](../../aspose.psd/rastercachedimage/binarizefixed/)(byte) | Binarisation d'une image avec un seuil prédéfini |
| override [BinarizeOtsu](../../aspose.psd/rastercachedimage/binarizeotsu/)() | Binarisation d'une image avec le seuillage d'Otsu |
| override [CacheData](../../aspose.psd/rastercachedimage/cachedata/)() | Met en cache les données et garantit qu'aucun chargement de données supplémentaire ne sera effectué à partir du [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) sous-jacent. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Détermine si l'image peut être enregistrée au format de fichier spécifié représenté par les options d'enregistrement fournies. |
| override [Crop](../../aspose.psd/rastercachedimage/crop/)(Rectangle) | Recadrage de l'image. |
| virtual [Crop](../../aspose.psd/rasterimage/crop/)(int, int, int, int) | Recadrer l'image avec des décalages. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Libère l'instance actuelle. |
| [Dither](../../aspose.psd/rasterimage/dither/)(DitheringMethod, int) | Effectue un tramage sur l'image actuelle. |
| override [Dither](../../aspose.psd/rastercachedimage/dither/)(DitheringMethod, int, IColorPalette) | Effectue un tramage sur l'image actuelle. |
| [DrawImage](../../aspose.psd.fileformats.psd.layers/layer/drawimage/)(Point, RasterImage) | Dessine l'image sur le calque. |
| virtual [Filter](../../aspose.psd/rasterimage/filter/)(Rectangle, FilterOptionsBase) | Filtre le rectangle spécifié. |
| [GetArgb32Pixel](../../aspose.psd/rasterimage/getargb32pixel/)(int, int) | Obtient un pixel ARGB 32 bits d'une image. |
| [GetDefaultArgb32Pixels](../../aspose.psd/rasterimage/getdefaultargb32pixels/)(Rectangle) | Obtient le tableau de pixels ARGB 32 bits par défaut. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Obtient les options par défaut. |
| [GetDefaultPixels](../../aspose.psd/rasterimage/getdefaultpixels/)(Rectangle, IPartialArgb32PixelLoader) | Obtient le tableau de pixels par défaut en utilisant le chargeur de pixels partiel. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, RawDataSettings) | Obtient le tableau de données brutes par défaut. |
| [GetDefaultRawData](../../aspose.psd/rasterimage/getdefaultrawdata/)(Rectangle, IPartialRawDataLoader, RawDataSettings) | Obtient le tableau de données brutes par défaut en utilisant le chargeur de pixels partiel. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.layers/layer/gethashcode/)() | Renvoie un code de hachage pour cette instance. |
| virtual [GetModifyDate](../../aspose.psd/rasterimage/getmodifydate/)(bool) | Obtient la date et l'heure de la dernière modification de l'image de ressource. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Obtient les options basées sur les paramètres du fichier original. Cela peut être utile pour conserver la profondeur de couleur et les autres paramètres de l'image originale inchangés. Par exemple, si nous chargeons une image PNG noir et blanc avec 1 bit par pixel puis l'enregistrons en utilisant la méthode [`Save`](../../aspose.psd/datastreamsupporter/save/), l'image PNG de sortie avec 8 bits par pixel sera produite. Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre à la méthode [`Save`](../../aspose.psd/image/save/) en tant que deuxième paramètre. |
| [GetPixel](../../aspose.psd/rasterimage/getpixel/)(int, int) | Obtient un pixel d'image. Avertissement de performance : évitez d'utiliser cette méthode pour parcourir tous les pixels de l'image, car cela peut entraîner d'importants problèmes de performance. Pour une manipulation des pixels plus efficace, utilisez la méthode `LoadArgb32Pixels` pour récupérer l'ensemble du tableau de pixels simultanément. |
| [GetSkewAngle](../../aspose.psd/rasterimage/getskewangle/)() | Obtient l'angle d'inclinaison. Cette méthode s'applique aux documents texte numérisés, afin de déterminer l'angle d'inclinaison lors de la numérisation. |
| override [Grayscale](../../aspose.psd/rastercachedimage/grayscale/)() | Transformation d'une image en sa représentation en niveaux de gris |
| [LoadArgb32Pixels](../../aspose.psd/rasterimage/loadargb32pixels/)(Rectangle) | Charge des pixels ARGB 32 bits. |
| [LoadArgb64Pixels](../../aspose.psd/rasterimage/loadargb64pixels/)(Rectangle) | Charge des pixels ARGB 64 bits. |
| [LoadCmyk32Pixels](../../aspose.psd/rasterimage/loadcmyk32pixels/)(Rectangle) | Charge des pixels au format CMYK. |
| [LoadCmykPixels](../../aspose.psd/rasterimage/loadcmykpixels/)(Rectangle) | Charge des pixels au format CMYK. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace [`LoadCmyk32Pixels`](../../aspose.psd/rasterimage/loadcmyk32pixels/). |
| [LoadPartialArgb32Pixels](../../aspose.psd/rasterimage/loadpartialargb32pixels/)(Rectangle, IPartialArgb32PixelLoader) | Charge partiellement des pixels ARGB 32 bits par paquets. |
| [LoadPartialPixels](../../aspose.psd/rasterimage/loadpartialpixels/)(Rectangle, IPartialPixelLoader) | Charge partiellement des pixels par paquets. |
| [LoadPixels](../../aspose.psd/rasterimage/loadpixels/)(Rectangle) | Charge des pixels. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, RawDataSettings, IPartialRawDataLoader) | Charge des données brutes. |
| [LoadRawData](../../aspose.psd/rasterimage/loadrawdata/)(Rectangle, Rectangle, RawDataSettings, IPartialRawDataLoader) | Charge des données brutes. |
| override [MergeLayerTo](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/adjustmentlayer/mergelayerto/)(Layer) | Fusionne le calque avec le calque spécifié |
| [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)() | Normalise l'angle. Cette méthode s'applique aux documents texte numérisés pour éliminer la distorsion du scan. Cette méthode utilise les méthodes [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) et [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| virtual [NormalizeAngle](../../aspose.psd/rasterimage/normalizeangle/)(bool, Color) | Normalise l'angle. Cette méthode s'applique aux documents texte numérisés pour éliminer la distorsion du scan. Cette méthode utilise les méthodes [`GetSkewAngle`](../../aspose.psd/rasterimage/getskewangle/) et [`Rotate`](../../aspose.psd/rasterimage/rotate/). |
| [ReadArgb32ScanLine](../../aspose.psd/rasterimage/readargb32scanline/)(int) | Lit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| [ReadScanLine](../../aspose.psd/rasterimage/readscanline/)(int) | Lit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(Color, byte, Color) | Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses. |
| virtual [ReplaceColor](../../aspose.psd/rasterimage/replacecolor/)(int, byte, int) | Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses. |
| [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(Color) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| virtual [ReplaceNonTransparentColors](../../aspose.psd/rasterimage/replacenontransparentcolors/)(int) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses. Remarque : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Redimensionne l'image. Le redimensionnement par plus proche voisin par défaut est utilisé. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ImageResizeSettings) | Redimensionne l'image. |
| override [Resize](../../aspose.psd/rastercachedimage/resize/)(int, int, ResizeType) | Redimensionne l'image. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Redimensionne la hauteur proportionnellement. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Redimensionne la hauteur proportionnellement. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Redimensionne la hauteur proportionnellement. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Redimensionne la largeur proportionnellement. Le redimensionnement par plus proche voisin par défaut est utilisé. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Redimensionne la largeur proportionnellement. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Redimensionne la largeur proportionnellement. |
| virtual [Rotate](../../aspose.psd/rasterimage/rotate/)(float) | Fait pivoter l'image autour du centre. |
| override [Rotate](../../aspose.psd/rastercachedimage/rotate/)(float, bool, Color) | Fait pivoter l'image autour du centre. |
| override [RotateFlip](../../aspose.psd/rastercachedimage/rotateflip/)(RotateFlipType) | Fait pivoter, retourner ou pivoter et retourner l'image. |
| [Save](../../aspose.psd/image/save/)() | Enregistre les données de l'image dans le flux sous-jacent. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream) | Enregistre les données de l'objet dans le flux spécifié. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, bool) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase) | Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(Stream, ImageOptionsBase, Rectangle) | Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement. |
| override [Save](../../aspose.psd.fileformats.psd.layers/layer/save/)(string, ImageOptionsBase, Rectangle) | Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement. |
| [SaveArgb32Pixels](../../aspose.psd/rasterimage/saveargb32pixels/)(Rectangle, int[]) | Enregistre les pixels ARGB 32 bits. |
| [SaveCmyk32Pixels](../../aspose.psd/rasterimage/savecmyk32pixels/)(Rectangle, int[]) | Enregistre les pixels. |
| [SaveCmykPixels](../../aspose.psd/rasterimage/savecmykpixels/)(Rectangle, CmykColor[]) | Enregistre les pixels. Cette méthode est obsolète. Veuillez utiliser la méthode plus efficace [`SaveCmyk32Pixels`](../../aspose.psd/rasterimage/savecmyk32pixels/). |
| [SavePixels](../../aspose.psd/rasterimage/savepixels/)(Rectangle, Color[]) | Enregistre les pixels. |
| [SaveRawData](../../aspose.psd/rasterimage/saverawdata/)(byte[], int, Rectangle, RawDataSettings) | Enregistre les données brutes. |
| [SetArgb32Pixel](../../aspose.psd/rasterimage/setargb32pixel/)(int, int, int) | Définit un pixel ARGB 32 bits de l'image pour la position spécifiée. |
| override [SetPalette](../../aspose.psd/rasterimage/setpalette/)(IColorPalette, bool) | Définit la palette de l'image. |
| [SetPixel](../../aspose.psd/rasterimage/setpixel/)(int, int, Color) | Définit le pixel de l'image pour la position spécifiée. |
| virtual [SetResolution](../../aspose.psd/rasterimage/setresolution/)(double, double) | Définit la résolution pour ce [`RasterImage`](../../aspose.psd/rasterimage/). |
| [ShallowCopy](../../aspose.psd.fileformats.psd.layers/layer/shallowcopy/)() | Crée une copie superficielle de la couche actuelle. Veuillez consulter [https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx](https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx) pour une explication. |
| virtual [ToBitmap](../../aspose.psd/rasterimage/tobitmap/)() | Convertit l'image raster en bitmap. |
| [WriteArgb32ScanLine](../../aspose.psd/rasterimage/writeargb32scanline/)(int, int[]) | Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| [WriteScanLine](../../aspose.psd/rasterimage/writescanline/)(int, Color[]) | Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |

## Exemples

Le code suivant démontre la prise en charge de la ColorBalanceAdjustmentLayer.

```csharp
[C#]

var filePath = "ColorBalance.psd";
var outputPath = "ColorBalance_out.psd";
using (var im = (PsdImage)Image.Load(filePath))
{
    foreach (var layer in im.Layers)
    {
        var cbLayer = layer as ColorBalanceAdjustmentLayer;
        if (cbLayer != null)
        {
            cbLayer.ShadowsCyanRedBalance = 30;
            cbLayer.ShadowsMagentaGreenBalance = -15;
            cbLayer.ShadowsYellowBlueBalance = 40;
            cbLayer.MidtonesCyanRedBalance = -90;
            cbLayer.MidtonesMagentaGreenBalance = -25;
            cbLayer.MidtonesYellowBlueBalance = 20;
            cbLayer.HighlightsCyanRedBalance = -30;
            cbLayer.HighlightsMagentaGreenBalance = 67;
            cbLayer.HighlightsYellowBlueBalance = -95;
            cbLayer.PreserveLuminosity = true;
        }
    }

    im.Save(outputPath);
}
```

### Voir aussi

* class [AdjustmentLayer](../adjustmentlayer/)
* class [Layer](../../aspose.psd.fileformats.psd.layers/layer/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.AdjustmentLayers](../../aspose.psd.fileformats.psd.layers.adjustmentlayers/)
* assembly [Aspose.PSD](../../)


