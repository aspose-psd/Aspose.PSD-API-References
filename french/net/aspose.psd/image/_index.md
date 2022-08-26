---
title: Image
second_title: Référence de l'API Aspose.PSD pour .NET
description: Limage est la classe de base pour tous les types dimages.
type: docs
weight: 4520
url: /fr/net/aspose.psd/image/
---
## Image class

L'image est la classe de base pour tous les types d'images.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette) { get; set; } | Obtient ou définit une valeur indiquant si la palette de réglage automatique. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor) { get; set; } | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel) { get; } | Obtient le nombre de bits d'image par pixel. |
| [Bounds](../../aspose.psd/image/bounds) { get; } | Obtient les limites de l'image. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [Container](../../aspose.psd/image/container) { get; } | Obtient le[`Image`](../image) conteneur. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer) { get; } | Obtient le flux de données de l'objet. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Obtient une valeur indiquant si cette instance est supprimée. |
| virtual [FileFormat](../../aspose.psd/image/fileformat) { get; } | Obtient une valeur de format de fichier |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor) { get; set; } | Obtient ou définit une valeur indiquant si l'image a une couleur d'arrière-plan. |
| abstract [Height](../../aspose.psd/image/height) { get; } | Obtient la hauteur de l'image. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor) { get; set; } | Obtient ou définit le moniteur d'interruption. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached) { get; } | Obtient une valeur indiquant si les données de l'objet sont actuellement mises en cache et qu'aucune lecture de données n'est requise. |
| [Palette](../../aspose.psd/image/palette) { get; set; } | Obtient ou définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement. |
| [Size](../../aspose.psd/image/size) { get; } | Obtient la taille de l'image. |
| abstract [Width](../../aspose.psd/image/width) { get; } | Obtient la largeur de l'image. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [Create](../../aspose.psd/image/create)(ImageOptionsBase, int, int) | Crée une nouvelle image en utilisant les options de création spécifiées. |
| static [Load](../../aspose.psd/image/load#load)(Stream) | Charge une nouvelle image à partir du flux spécifié. |
| static [Load](../../aspose.psd/image/load#load_2)(string) | Charge une nouvelle image à partir du fichier spécifié. |
| static [Load](../../aspose.psd/image/load#load_1)(Stream, LoadOptions) | Charge une nouvelle image à partir du flux spécifié. |
| static [Load](../../aspose.psd/image/load#load_3)(string, LoadOptions) | Charge une nouvelle image à partir du fichier spécifié. |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata)() | Met en cache les données et garantit qu'aucun chargement de données supplémentaire ne sera effectué à partir du sous-jacent[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.psd/image/cansave)(ImageOptionsBase) | Détermine si l'image peut être enregistrée dans le format de fichier spécifié représenté par les options d'enregistrement transmises. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Supprime l'instance actuelle. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions)(object[]) | Récupère les options par défaut. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions)() | Obtient les options basées sur les paramètres du fichier d'origine. Cela peut être utile pour conserver la profondeur de bits et d'autres paramètres de l'image d'origine inchangés. Par exemple, si nous chargeons une image PNG noir-blanc avec 1 bit par pixel, puis enregistrez-le en utilisant the [`Save`](../datastreamsupporter/save) , l'image PNG de sortie avec 8 bits par pixel sera produite. Pour l'éviter et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et passez-les au[`Save`](./save)méthode comme deuxième paramètre. |
| [Resize](../../aspose.psd/image/resize#resize)(int, int) | Redimensionne l'image. Le défautLeftTopToLeftTopest utilisé. |
| abstract [Resize](../../aspose.psd/image/resize#resize_1)(int, int, ImageResizeSettings) | Redimensionne l'image. |
| abstract [Resize](../../aspose.psd/image/resize#resize_2)(int, int, ResizeType) | Redimensionne l'image. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally#resizeheightproportionally)(int) | Redimensionne la hauteur proportionnellement. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally#resizeheightproportionally_1)(int, ImageResizeSettings) | Redimensionne la hauteur proportionnellement. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Redimensionne la hauteur proportionnellement. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally#resizewidthproportionally)(int) | Redimensionne la largeur proportionnellement. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally#resizewidthproportionally_1)(int, ImageResizeSettings) | Redimensionne la largeur proportionnellement. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Redimensionne la largeur proportionnellement. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip)(RotateFlipType) | Fait pivoter, retourne ou fait pivoter et retourne l'image. |
| [Save](../../aspose.psd/image/save#save)() | Enregistre les données d'image dans le flux sous-jacent. |
| [Save](../../aspose.psd/datastreamsupporter/save)(Stream) | Enregistre les données de l'objet dans le flux spécifié. |
| [Save](../../aspose.psd/datastreamsupporter/save)(string) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [Save](../../aspose.psd/image/save#save_2)(Stream, ImageOptionsBase) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save)(string, bool) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| virtual [Save](../../aspose.psd/image/save#save_5)(string, ImageOptionsBase) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| virtual [Save](../../aspose.psd/image/save#save_3)(Stream, ImageOptionsBase, Rectangle) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| virtual [Save](../../aspose.psd/image/save#save_6)(string, ImageOptionsBase, Rectangle) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié en fonction des options d'enregistrement. |
| abstract [SetPalette](../../aspose.psd/image/setpalette)(IColorPalette, bool) | Définit la palette d'images. |
| static [CanLoad](../../aspose.psd/image/canload#canload)(Stream) | Détermine si l'image peut être chargée à partir du flux spécifié. |
| static [CanLoad](../../aspose.psd/image/canload#canload_2)(string) | Détermine si l'image peut être chargée à partir du chemin de fichier spécifié. |
| static [CanLoad](../../aspose.psd/image/canload#canload_1)(Stream, LoadOptions) | Détermine si l'image peut être chargée à partir du flux spécifié et éventuellement en utilisant le*loadOptions* . |
| static [CanLoad](../../aspose.psd/image/canload#canload_3)(string, LoadOptions) | Détermine si l'image peut être chargée à partir du chemin de fichier spécifié et éventuellement à l'aide des options d'ouverture spécifiées. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat#getfileformat)(Stream) | Obtient le format de fichier. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat#getfileformat_1)(string) | Obtient le format de fichier. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle#getfittingrectangle)(Rectangle, int, int) | Obtient un rectangle qui correspond à l'image actuelle. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle#getfittingrectangle_1)(Rectangle, int[], int, int) | Obtient un rectangle qui correspond à l'image actuelle. |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight)(int, int, int) | Obtient une hauteur proportionnelle. |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth)(int, int, int) | Obtient une largeur proportionnelle. |

### Exemples

Cet exemple crée un nouveau fichier Image à un emplacement de disque spécifié par la propriété Source de l'instance PsdOptions. Plusieurs propriétés pour l'instance PsdOptions sont définies avant de créer l'image réelle. Surtout la propriété Source, qui fait référence à l'emplacement réel du disque dans ce cas.

```csharp
[C#]

//Créer une instance de PsdOptions et définir ses différentes propriétés
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Créer une instance de FileCreateSource et l'affecter comme Source pour l'instance de PsdOptions
// Le deuxième paramètre booléen détermine si le fichier à créer est temporel ou non
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Créer une instance de Image et l'initialiser avec une instance de PsdOptions en appelant la méthode Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // faire du traitement d'image

    // Enregistrer toutes les modifications
    image.Save();
}
```

### Voir également

* class [DataStreamSupporter](../datastreamsupporter)
* interface [IObjectWithBounds](../iobjectwithbounds)
* espace de noms [Aspose.PSD](../../aspose.psd)
* Assemblée [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
