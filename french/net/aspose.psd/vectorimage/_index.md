---
title: "Classe VectorImage"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.VectorImage. L'image vectorielle est la classe de base pour tous les types d'images vectorielles."
type: docs
weight: 6220
url: /fr/net/aspose.psd/vectorimage/
---
{{< psd/tize >}}
## VectorImage class

L’image vectorielle est la classe de base pour tous les types d’images vectorielles.

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
```

## Propriétés

| Nom | Description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Obtient ou définit une valeur indiquant si la palette d'ajustement automatique. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Obtient le nombre de bits par pixel de l'image. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Obtient les limites de l'image. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Obtient ou définit l'indice de taille du tampon, qui définit la taille maximale autorisée pour tous les tampons internes. |
| [Container](../../aspose.psd/image/container/) { get; } | Obtient le conteneur [`Image`](../image/). |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Obtient le flux de données de l'objet. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Obtient une valeur du format de fichier |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Obtient ou définit une valeur indiquant si l'image possède une couleur d'arrière-plan. |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | Obtient la hauteur de l'image. |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | Obtient la hauteur de l'objet, en pouces. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Obtient ou définit le moniteur d'interruption. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Obtient une valeur indiquant si les données de l'objet sont actuellement en cache et qu'aucune lecture de données n'est requise. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Obtient ou définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement. |
| [Size](../../aspose.psd/image/size/) { get; } | Obtient la taille de l'image. |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | Obtient la taille de l'objet, en pouces. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Obtient une valeur indiquant si la palette de l'image est utilisée. |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | Obtient la largeur de l'image. |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | Obtient la largeur de l'objet, en pouces. |

## Méthodes

| Nom | Description |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Met en cache les données et garantit qu'aucun chargement de données supplémentaire ne sera effectué à partir du [`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) sous-jacent. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Détermine si l'image peut être enregistrée au format de fichier spécifié représenté par les options d'enregistrement fournies. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Libère l'instance actuelle. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Obtient les options par défaut. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Obtient les options basées sur les paramètres du fichier original. Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés. Par exemple, si nous chargeons une image PNG noir et blanc avec 1 bit par pixel puis l'enregistrons en utilisant la méthode [`Save`](../datastreamsupporter/save/), l'image PNG de sortie avec 8 bits par pixel sera produite. Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre à la méthode [`Save`](../image/save/) en tant que deuxième paramètre. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Redimensionne l'image. Le redimensionnement par plus proche voisin par défaut est utilisé. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | Redimensionne l'image. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | Redimensionne l'image. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Redimensionne la hauteur proportionnellement. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Redimensionne la hauteur proportionnellement. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Redimensionne la hauteur proportionnellement. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Redimensionne la largeur proportionnellement. Le redimensionnement par plus proche voisin par défaut est utilisé. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Redimensionne la largeur proportionnellement. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Redimensionne la largeur proportionnellement. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Fait pivoter, retourner ou pivoter et retourner l'image. |
| [Save](../../aspose.psd/image/save/)() | Enregistre les données de l'image dans le flux sous-jacent. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Enregistre les données de l'objet dans le flux spécifié. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Définit la palette de l'image. |

### Voir aussi

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


