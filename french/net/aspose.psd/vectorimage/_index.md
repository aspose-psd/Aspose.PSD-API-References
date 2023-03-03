---
title: Class VectorImage
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.VectorImage classe. Limage vectorielle est la classe de base pour tous les types dimages vectorielles.
type: docs
weight: 5720
url: /fr/net/aspose.psd/vectorimage/
---
## VectorImage class

L'image vectorielle est la classe de base pour tous les types d'images vectorielles.

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Obtient ou définit une valeur indiquant si la palette de réglage automatique. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Obtient le nombre de bits d'image par pixel. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Obtient les limites de l'image. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [Container](../../aspose.psd/image/container/) { get; } | Obtient le[`Image`](../image/) conteneur. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Obtient le flux de données de l'objet. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Obtient une valeur de format de fichier |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Obtient ou définit une valeur indiquant si l'image a une couleur d'arrière-plan. |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | Obtient la hauteur de l'image. |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | Obtient la hauteur de l'objet, en pouces. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Obtient ou définit le moniteur d'interruption. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Obtient une valeur indiquant si les données de l'objet sont actuellement mises en cache et qu'aucune lecture de données n'est requise. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Obtient ou définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement. |
| [Size](../../aspose.psd/image/size/) { get; } | Obtient la taille de l'image. |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | Obtient la taille de l'objet, en pouces. |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | Obtient la largeur de l'image. |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | Obtient la largeur de l'objet, en pouces. |

## Méthodes

| Nom | La description |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Met en cache les données et garantit qu'aucun chargement de données supplémentaire ne sera effectué à partir du sous-jacent[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Détermine si l'image peut être enregistrée dans le format de fichier spécifié représenté par les options d'enregistrement transmises. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Supprime l'instance actuelle. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Récupère les options par défaut. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Obtient les options basées sur les paramètres du fichier d'origine. Cela peut être utile pour conserver la profondeur de bits et d'autres paramètres de l'image d'origine inchangés. Par exemple, si nous chargeons une image PNG noir-blanc avec 1 bit par pixel, puis enregistrez-le en utilisant the [`Save`](../datastreamsupporter/save/) , l'image PNG de sortie avec 8 bits par pixel sera produite. Pour l'éviter et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et passez-les au[`Save`](../image/save/)méthode comme deuxième paramètre. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Redimensionne l'image. Le défautLeftTopToLeftTopest utilisé. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | Redimensionne l'image. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | Redimensionne l'image. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Redimensionne la hauteur proportionnellement. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Redimensionne la hauteur proportionnellement. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Redimensionne la hauteur proportionnellement. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Redimensionne la largeur proportionnellement. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Redimensionne la largeur proportionnellement. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Redimensionne la largeur proportionnellement. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Fait pivoter, retourne ou fait pivoter et retourne l'image. |
| [Save](../../aspose.psd/image/save/)() | Enregistre les données d'image dans le flux sous-jacent. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Enregistre les données de l'objet dans le flux spécifié. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Définit la palette d'images. |

### Voir également

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* espace de noms [Aspose.PSD](../../aspose.psd/)
* Assemblée [Aspose.PSD](../../)


