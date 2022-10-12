---
title: Image
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Limmagine è la classe base per tutti i tipi di immagini.
type: docs
weight: 4520
url: /it/net/aspose.psd/image/
---
## Image class

L'immagine è la classe base per tutti i tipi di immagini.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette) { get; set; } | Ottiene o imposta un valore che indica se regolare automaticamente la tavolozza. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor) { get; set; } | Ottiene o imposta un valore per il colore di sfondo. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel) { get; } | Ottiene il numero di bit dell'immagine per pixel. |
| [Bounds](../../aspose.psd/image/bounds) { get; } | Ottiene i limiti dell'immagine. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint) { get; set; } | Ottiene o imposta l'hint per la dimensione del buffer che è la dimensione massima consentita per tutti i buffer interni. |
| [Container](../../aspose.psd/image/container) { get; } | Ottiene il[`Image`](../image) contenitore. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer) { get; } | Ottiene il flusso di dati dell'oggetto. |
| [Disposed](../../aspose.psd/disposableobject/disposed) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| virtual [FileFormat](../../aspose.psd/image/fileformat) { get; } | Ottiene un valore di formato file |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor) { get; set; } | Ottiene o imposta un valore che indica se l'immagine ha il colore di sfondo. |
| abstract [Height](../../aspose.psd/image/height) { get; } | Ottiene l'altezza dell'immagine. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor) { get; set; } | Ottiene o imposta il monitor di interruzione. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached) { get; } | Ottiene un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è richiesta la lettura dei dati. |
| [Palette](../../aspose.psd/image/palette) { get; set; } | Ottiene o imposta la tavolozza dei colori. La tavolozza dei colori non viene utilizzata quando i pixel sono rappresentati direttamente. |
| [Size](../../aspose.psd/image/size) { get; } | Ottiene la dimensione dell'immagine. |
| abstract [Width](../../aspose.psd/image/width) { get; } | Ottiene la larghezza dell'immagine. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [Create](../../aspose.psd/image/create)(ImageOptionsBase, int, int) | Crea una nuova immagine utilizzando le opzioni di creazione specificate. |
| static [Load](../../aspose.psd/image/load#load)(Stream) | Carica una nuova immagine dal flusso specificato. |
| static [Load](../../aspose.psd/image/load#load_2)(string) | Carica una nuova immagine dal file specificato. |
| static [Load](../../aspose.psd/image/load#load_1)(Stream, LoadOptions) | Carica una nuova immagine dal flusso specificato. |
| static [Load](../../aspose.psd/image/load#load_3)(string, LoadOptions) | Carica una nuova immagine dal file specificato. |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata)() | Memorizza i dati nella cache e garantisce che nessun ulteriore caricamento dei dati venga eseguito dal sottostante[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.psd/image/cansave)(ImageOptionsBase) | Determina se l'immagine può essere salvata nel formato file specificato rappresentato dalle opzioni di salvataggio passate. |
| [Dispose](../../aspose.psd/disposableobject/dispose)() | Elimina l'istanza corrente. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions)(object[]) | Ottiene le opzioni predefinite. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions)() | Ottiene le opzioni in base alle impostazioni del file originale. Questo può essere utile per mantenere invariati la profondità di bit e altri parametri dell'immagine originale. Ad esempio, se carichiamo un'immagine PNG in bianco e nero con 1 bit per pixel e quindi salvalo usando il [`Save`](../datastreamsupporter/save) metodo, verrà prodotta l'immagine PNG di output con 8 bit per pixel. Per evitarlo e salvare l'immagine PNG con 1 bit per pixel, utilizzare questo metodo per ottenere le opzioni di salvataggio corrispondenti e passarle al[`Save`](./save)metodo come secondo parametro. |
| [Resize](../../aspose.psd/image/resize#resize)(int, int) | Ridimensiona l'immagine. Il predefinitoLeftTopToLeftTopviene utilizzato. |
| abstract [Resize](../../aspose.psd/image/resize#resize_1)(int, int, ImageResizeSettings) | Ridimensiona l'immagine. |
| abstract [Resize](../../aspose.psd/image/resize#resize_2)(int, int, ResizeType) | Ridimensiona l'immagine. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally#resizeheightproportionally)(int) | Ridimensiona proporzionalmente l'altezza. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally#resizeheightproportionally_1)(int, ImageResizeSettings) | Ridimensiona proporzionalmente l'altezza. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Ridimensiona proporzionalmente l'altezza. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally#resizewidthproportionally)(int) | Ridimensiona proporzionalmente la larghezza. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally#resizewidthproportionally_1)(int, ImageResizeSettings) | Ridimensiona proporzionalmente la larghezza. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Ridimensiona proporzionalmente la larghezza. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip)(RotateFlipType) | Ruota, capovolge o ruota e capovolge l'immagine. |
| [Save](../../aspose.psd/image/save#save)() | Salva i dati dell'immagine nel flusso sottostante. |
| [Save](../../aspose.psd/datastreamsupporter/save)(Stream) | Salva i dati dell'oggetto nel flusso specificato. |
| [Save](../../aspose.psd/datastreamsupporter/save)(string) | Salva i dati dell'oggetto nella posizione del file specificata. |
| [Save](../../aspose.psd/image/save#save_2)(Stream, ImageOptionsBase) | Salva i dati dell'immagine nel flusso specificato nel formato file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save)(string, bool) | Salva i dati dell'oggetto nella posizione del file specificata. |
| virtual [Save](../../aspose.psd/image/save#save_5)(string, ImageOptionsBase) | Salva i dati dell'oggetto nel percorso file specificato nel formato file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.psd/image/save#save_3)(Stream, ImageOptionsBase, Rectangle) | Salva i dati dell'immagine nel flusso specificato nel formato file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.psd/image/save#save_6)(string, ImageOptionsBase, Rectangle) | Salva i dati dell'oggetto nel percorso file specificato nel formato file specificato in base alle opzioni di salvataggio. |
| abstract [SetPalette](../../aspose.psd/image/setpalette)(IColorPalette, bool) | Imposta la tavolozza dell'immagine. |
| static [CanLoad](../../aspose.psd/image/canload#canload)(Stream) | Determina se l'immagine può essere caricata dal flusso specificato. |
| static [CanLoad](../../aspose.psd/image/canload#canload_2)(string) | Determina se l'immagine può essere caricata dal percorso file specificato. |
| static [CanLoad](../../aspose.psd/image/canload#canload_1)(Stream, LoadOptions) | Determina se l'immagine può essere caricata dal flusso specificato e, facoltativamente, utilizzando quello specificato*loadOptions* . |
| static [CanLoad](../../aspose.psd/image/canload#canload_3)(string, LoadOptions) | Determina se l'immagine può essere caricata dal percorso file specificato e, facoltativamente, utilizzando le opzioni di apertura specificate. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat#getfileformat)(Stream) | Ottiene il formato del file. |
| static [GetFileFormat](../../aspose.psd/image/getfileformat#getfileformat_1)(string) | Ottiene il formato del file. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle#getfittingrectangle)(Rectangle, int, int) | Ottiene il rettangolo che si adatta all'immagine corrente. |
| static [GetFittingRectangle](../../aspose.psd/image/getfittingrectangle#getfittingrectangle_1)(Rectangle, int[], int, int) | Ottiene il rettangolo che si adatta all'immagine corrente. |
| static [GetProportionalHeight](../../aspose.psd/image/getproportionalheight)(int, int, int) | Ottiene un'altezza proporzionale. |
| static [GetProportionalWidth](../../aspose.psd/image/getproportionalwidth)(int, int, int) | Ottiene una larghezza proporzionale. |

### Esempi

Questo esempio crea un nuovo file immagine in una posizione del disco come specificato dalla proprietà Source dell'istanza PsdOptions. Diverse proprietà per l'istanza PsdOptions vengono impostate prima di creare l'immagine effettiva. Soprattutto la proprietà Source, che in questo caso si riferisce alla posizione effettiva del disco.

```csharp
[C#]

//Crea un'istanza di PsdOptions e imposta le sue varie proprietà
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Crea un'istanza di FileCreateSource e assegnala come origine per l'istanza di PsdOptions
//Il secondo parametro booleano determina se il file da creare è Temporale o meno
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Crea un'istanza di Image e inizializzala con un'istanza di PsdOptions chiamando il metodo Create
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //eseguo un po' di elaborazione delle immagini

    // salva tutte le modifiche
    image.Save();
}
```

### Guarda anche

* class [DataStreamSupporter](../datastreamsupporter)
* interface [IObjectWithBounds](../iobjectwithbounds)
* spazio dei nomi [Aspose.PSD](../../aspose.psd)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
