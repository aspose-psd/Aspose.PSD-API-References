---
title: "Classe AiImage"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Aspose.PSD.FileFormats.Ai.AiImage class. L'image AI d'Adobe Illustrator"
type: docs
weight: 1270
url: /fr/net/aspose.psd.fileformats.ai/aiimage/
---
{{< psd/tize >}}
## AiImage class

L'image Adobe Illustrator (AI).

```csharp
public sealed class AiImage : Image
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [AiImage](aiimage/)() | Initialise une nouvelle instance de la classe `AiImage`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [ActivePageIndex](../../aspose.psd.fileformats.ai/aiimage/activepageindex/) { get; set; } | Obtient ou définit l'index de la page active. |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Obtient ou définit une valeur indiquant si la palette d'ajustement automatique. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| override [BitsPerPixel](../../aspose.psd.fileformats.ai/aiimage/bitsperpixel/) { get; } | Obtient le nombre de bits par pixel de l'image. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Obtient les limites de l'image. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Obtient ou définit l'indice de taille du tampon, qui définit la taille maximale autorisée pour tous les tampons internes. |
| [Container](../../aspose.psd/image/container/) { get; } | Obtient le conteneur [`Image`](../../aspose.psd/image/). |
| [DataSection](../../aspose.psd.fileformats.ai/aiimage/datasection/) { get; } | Obtient la section de données. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Obtient le flux de données de l'objet. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Obtient une valeur indiquant si cette instance est libérée. |
| override [FileFormat](../../aspose.psd.fileformats.ai/aiimage/fileformat/) { get; } | Obtient une valeur du format de fichier. |
| [FinalizeSection](../../aspose.psd.fileformats.ai/aiimage/finalizesection/) { get; } | Obtient la section de finalisation. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Obtient ou définit une valeur indiquant si l'image possède une couleur d'arrière-plan. |
| [Header](../../aspose.psd.fileformats.ai/aiimage/header/) { get; } | Obtient l'en-tête. |
| override [Height](../../aspose.psd.fileformats.ai/aiimage/height/) { get; } | Obtient la hauteur de l'image. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Obtient ou définit le moniteur d'interruption. |
| override [IsCached](../../aspose.psd.fileformats.ai/aiimage/iscached/) { get; } | Obtient une valeur indiquant si les données de l'objet sont actuellement en cache et qu'aucune lecture de données n'est requise. |
| [Layers](../../aspose.psd.fileformats.ai/aiimage/layers/) { get; } | Obtient les sections de calque. |
| [PageCount](../../aspose.psd.fileformats.ai/aiimage/pagecount/) { get; } | Le nombre de pages. Pour les images du ancien format AI, il est toujours égal à 0. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Obtient ou définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement. |
| [SetupSection](../../aspose.psd.fileformats.ai/aiimage/setupsection/) { get; } | Obtient la section de configuration. |
| [Size](../../aspose.psd/image/size/) { get; } | Obtient la taille de l'image. |
| virtual [UsePalette](../../aspose.psd/image/usepalette/) { get; } | Obtient une valeur indiquant si la palette de l'image est utilisée. |
| [Version](../../aspose.psd.fileformats.ai/aiimage/version/) { get; } | Obtient la version du format Adobe Illustrator. |
| override [Width](../../aspose.psd.fileformats.ai/aiimage/width/) { get; } | Obtient la largeur de l'image. |
| [XmpData](../../aspose.psd.fileformats.ai/aiimage/xmpdata/) { get; } | Obtient les métadonnées XMP. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddLayer](../../aspose.psd.fileformats.ai/aiimage/addlayer/)(AiLayerSection) | Ajoute la section de calque AI. |
| override [CacheData](../../aspose.psd.fileformats.ai/aiimage/cachedata/)() | Met en cache les données et garantit qu'aucun chargement de données supplémentaire ne sera effectué à partir du [`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) sous-jacent. |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Détermine si l'image peut être enregistrée au format de fichier spécifié représenté par les options d'enregistrement fournies. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Libère l'instance actuelle. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Obtient les options par défaut. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Obtient les options basées sur les paramètres du fichier original. Cela peut être utile pour conserver la profondeur de couleur et les autres paramètres de l'image originale inchangés. Par exemple, si nous chargeons une image PNG noir et blanc avec 1 bit par pixel puis l'enregistrons en utilisant la méthode [`Save`](../../aspose.psd/datastreamsupporter/save/), l'image PNG de sortie avec 8 bits par pixel sera produite. Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre à la méthode [`Save`](../../aspose.psd/image/save/) en tant que deuxième paramètre. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Redimensionne l'image. Le redimensionnement par plus proche voisin par défaut est utilisé. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_1)(int, int, ImageResizeSettings) | Redimensionne l'image. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_2)(int, int, ResizeType) | Redimensionne l'image. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Redimensionne la hauteur proportionnellement. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Redimensionne la hauteur proportionnellement. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Redimensionne la hauteur proportionnellement. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Redimensionne la largeur proportionnellement. Le redimensionnement par plus proche voisin par défaut est utilisé. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Redimensionne la largeur proportionnellement. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Redimensionne la largeur proportionnellement. |
| override [RotateFlip](../../aspose.psd.fileformats.ai/aiimage/rotateflip/)(RotateFlipType) | Fait pivoter, retourner ou pivoter et retourner l'image. |
| [Save](../../aspose.psd/image/save/)() | Enregistre les données de l'image dans le flux sous-jacent. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Enregistre les données de l'objet dans le flux spécifié. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Enregistre les données de l'image dans le flux spécifié au format de fichier indiqué selon les options d'enregistrement. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Enregistre les données de l'objet à l'emplacement de fichier spécifié au format de fichier indiqué selon les options d'enregistrement. |
| override [SetPalette](../../aspose.psd.fileformats.ai/aiimage/setpalette/)(IColorPalette, bool) | Définit la palette de l'image. |

## Exemples

L'exemple suivant montre comment vous pouvez exporter des fichiers Adobe Illustrator au format PDF dans Aspose.PSD

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

L'exemple suivant montre comment vous pouvez exporter un fichier AI au format PSD et PNG dans Aspose.PSD

```csharp
[C#]

string sourceFileName = "form_8.ai";
string outputFileName = "form_8_export";
using (AiImage image = (AiImage)Image.Load(sourceFileName))
{
    image.Save(outputFileName + ".psd", new PsdOptions());
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

L'exemple suivant montre la prise en charge de l'exportation du format Ai vers les formats PSD, PNG, JPG, GIF et TIF.

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"34992OStroke",
    @"rect2_color",
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string name = sourcesFiles[i];
    string sourceFileName = name + ".ai";

    using (AiImage image = (AiImage)Image.Load(sourceFileName))
    {
        string outFileName = name + ".psd";
        ImageOptionsBase options = new PsdOptions();
        image.Save(outFileName, options);

        outFileName = name + ".png";
        options = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
        image.Save(outFileName, options);

        outFileName = name + ".jpg";
        options = new JpegOptions() { Quality = 85 };
        image.Save(outFileName, options);

        outFileName = name + ".gif";
        options = new GifOptions() { DoPaletteCorrection = false };
        image.Save(outFileName, options);

        outFileName = name + ".tif";
        options = new TiffOptions(TiffExpectedFormat.TiffDeflateRgba);
        image.Save(outFileName, options);
    }
}
```

### Voir aussi

* class [Image](../../aspose.psd/image/)
* namespace [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* assembly [Aspose.PSD](../../)


