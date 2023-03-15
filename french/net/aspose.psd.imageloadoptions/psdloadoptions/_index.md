---
title: Class PsdLoadOptions
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.ImageLoadOptions.PsdLoadOptions classe. Options de chargement PSD
type: docs
weight: 4770
url: /fr/net/aspose.psd.imageloadoptions/psdloadoptions/
---
## PsdLoadOptions class

Options de chargement PSD

```csharp
public class PsdLoadOptions : LoadOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | Obtient ou définit s'il faut enregistrer avec l'image rendue, avec ou sans transformation warp. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | Obtient ou définit l'indice de taille de tampon qui est défini comme la taille maximale autorisée pour tous les tampons internes. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | Obtient ou définit le[`Image`](../../aspose.psd/image/) arrière-plan[`Color`](../../aspose.psd/color/) . |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | Obtient ou définit le mode de récupération des données. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | Obtient ou définit une valeur indiquant si [ignorer le canal alpha]. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | Obtient ou définit une valeur indiquant si la largeur fixe de la couche de texte PSD sera ignorée lors de l'exécution de l'opération UpdateText. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | Obtient ou définit une valeur indiquant si [charge affecte la ressource] (par défaut, la ressource n'est pas chargée). Lorsque cette option est définie, seuls les effets pris en charge seront rendus dans l'image fusionnée finale. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | Obtient ou définit le gestionnaire d'événements de progression. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | Obtient ou définit une valeur indiquant si [utiliser le mode lecture seule]. Il s'agit du mode lecture seule, pris en charge pour une compatibilité identique avec Adobe Photoshop. Lorsque cette option est définie, toutes les modifications appliquées aux calques ne seront pas enregistrées dans l'image finale. Toutes les données sont utilisées à partir de la section ImageData, elles sont donc identiques à Photoshop. Par défaut, toutes les images chargées ne sont pas identiques à Adobe Photoshop compatible. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | Obtient ou définit une valeur indiquant si [utiliser le disque pour charger la ressource d'effets] (par défaut, le disque utilisé pour charger la ressource d'effets, mais peut être utilisé la mémoire si elle est suffisante en définissant cette valeur sur false). |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | Obtient ou définit une valeur indiquant si la conversion de profil ICC doit être appliquée. |

### Exemples

L'exemple suivant montre que la progression de la conversion du document fonctionne correctement et sans exception.

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

### Voir également

* class [LoadOptions](../../aspose.psd/loadoptions/)
* espace de noms [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* Assemblée [Aspose.PSD](../../)


