---
title: "Classe PsdLoadOptions"
second_title: "Aspose.PSD pour .NET Référence de l'API"
description: "Classe Aspose.PSD.ImageLoadOptions.PsdLoadOptions. Options de chargement PSD"
type: docs
weight: 5250
url: /fr/net/aspose.psd.imageloadoptions/psdloadoptions/
---
{{< psd/tize >}}
## PsdLoadOptions class

Options de chargement PSD

```csharp
public class PsdLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AllowNonChangedLayerRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/) { get; set; } | Obtient ou définit s'il faut conserver les pixels de calque originaux lors du rendu si le calque n'a pas été modifié. |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | Obtient ou définit s'il faut enregistrer avec l'image rendue, avec ou sans transformation de distorsion. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | Obtient ou définit l'indice de taille du tampon, qui définit la taille maximale autorisée pour tous les tampons internes. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | Obtient ou définit l'arrière-plan de l'[`Image`](../../aspose.psd/image/) [`Color`](../../aspose.psd/color/). |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | Obtient ou définit le mode de récupération des données. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | Obtient ou définit une valeur indiquant si [ignore alpha channel]. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | Obtient ou définit une valeur indiquant si la largeur fixe du calque texte PSD sera ignorée lors de l'exécution de l'opération UpdateText. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | Obtient ou définit une valeur indiquant si [load effects resource] (par défaut la ressource n'est pas chargée). Lorsque cette option est définie, seuls les effets pris en charge seront rendus dans l'image fusionnée finale. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | Obtient ou définit le gestionnaire d'événement de progression. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | Obtient ou définit une valeur indiquant si [use read only mode]. Il s'agit d'un mode lecture seule, pris en charge pour une compatibilité identique avec Adobe Photoshop. Lorsque cette option est activée, toutes les modifications appliquées aux calques ne seront pas enregistrées dans l'image finale. Toutes les données proviennent de la section ImageData, ce qui la rend identique à Photoshop. Par défaut, toutes les images chargées ne sont pas compatibles identiquement avec Adobe Photoshop. |
| [ReadOnlyType](../../aspose.psd.imageloadoptions/psdloadoptions/readonlytype/) { get; set; } | Obtient ou définit le mode lecture seule utilisé lors du chargement d'une image PSD. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | Obtient ou définit une valeur indiquant si [use disk for load effects resource] (par défaut, le disque est utilisé pour charger les ressources d'effets, mais la mémoire peut être utilisée si elle est suffisante en réglant cette valeur sur false). |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | Obtient ou définit une valeur indiquant si la conversion du profil ICC doit être appliquée. |

## Exemples

L'exemple suivant montre que la progression de la conversion de document fonctionne correctement et sans exception.

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

### Voir aussi

* class [LoadOptions](../../aspose.psd/loadoptions/)
* namespace [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../)


