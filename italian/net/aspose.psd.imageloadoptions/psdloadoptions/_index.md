---
title: Class PsdLoadOptions
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.ImageLoadOptions.PsdLoadOptions classe. Opzioni caricamento psd
type: docs
weight: 4770
url: /it/net/aspose.psd.imageloadoptions/psdloadoptions/
---
## PsdLoadOptions class

Opzioni caricamento psd

```csharp
public class PsdLoadOptions : LoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PsdLoadOptions](psdloadoptions/)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AllowWarpRepaint](../../aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/) { get; set; } | Ottiene o imposta se salvare con l'immagine renderizzata, con o senza una trasformazione warp. |
| [BufferSizeHint](../../aspose.psd/loadoptions/buffersizehint/) { get; set; } | Ottiene o imposta l'hint della dimensione del buffer che è definita dimensione massima consentita per tutti i buffer interni. |
| [DataBackgroundColor](../../aspose.psd/loadoptions/databackgroundcolor/) { get; set; } | Ottiene o imposta il[`Image`](../../aspose.psd/image/) sfondo[`Color`](../../aspose.psd/color/) . |
| [DataRecoveryMode](../../aspose.psd/loadoptions/datarecoverymode/) { get; set; } | Ottiene o imposta la modalità di ripristino dei dati. |
| [IgnoreAlphaChannel](../../aspose.psd.imageloadoptions/psdloadoptions/ignorealphachannel/) { get; set; } | Ottiene o imposta un valore che indica se [ignora canale alfa]. |
| [IgnoreTextLayerWidthOnUpdate](../../aspose.psd.imageloadoptions/psdloadoptions/ignoretextlayerwidthonupdate/) { get; set; } | Ottiene o imposta un valore che indica se la larghezza fissa del livello di testo PSD verrà ignorata durante l'esecuzione dell'operazione UpdateText. |
| [LoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/loadeffectsresource/) { get; set; } | Ottiene o imposta un valore che indica se [il caricamento influisce sulla risorsa] (per impostazione predefinita la risorsa non è caricata). Quando è impostata questa opzione, solo gli effetti supportati verranno renderizzati nell'immagine unita finale. |
| [ProgressEventHandler](../../aspose.psd/loadoptions/progresseventhandler/) { get; set; } | Ottiene o imposta il gestore dell'evento progress. |
| [ReadOnlyMode](../../aspose.psd.imageloadoptions/psdloadoptions/readonlymode/) { get; set; } | Ottiene o imposta un valore che indica se [usa la modalità di sola lettura]. Questa è la modalità di sola lettura, supportata per la stessa compatibilità con Adobe Photoshop. Quando questa opzione è impostata, tutte le modifiche applicate ai livelli non verranno salvate nell'immagine finale. Tutti i dati vengono utilizzati dalla sezione ImageData, quindi è identico a Photoshop. Per impostazione predefinita, tutte le immagini caricate non sono identiche a quelle compatibili con Adobe Photoshop. |
| [UseDiskForLoadEffectsResource](../../aspose.psd.imageloadoptions/psdloadoptions/usediskforloadeffectsresource/) { get; set; } | Ottiene o imposta un valore che indica se [usa il disco per caricare la risorsa degli effetti] (di default usa il disco per caricare la risorsa degli effetti, ma può essere usata la memoria se è sufficiente impostando questo valore su false). |
| [UseIccProfileConversion](../../aspose.psd/loadoptions/useiccprofileconversion/) { get; set; } | Ottiene o imposta un valore che indica se deve essere applicata la conversione del profilo ICC. |

### Esempi

L'esempio seguente dimostra che l'avanzamento della conversione del documento funziona correttamente e senza eccezioni.

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

### Guarda anche

* class [LoadOptions](../../aspose.psd/loadoptions/)
* spazio dei nomi [Aspose.PSD.ImageLoadOptions](../../aspose.psd.imageloadoptions/)
* assemblea [Aspose.PSD](../../)


