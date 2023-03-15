---
title: Class VectorImage
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.VectorImage classe. Limmagine vettoriale è la classe base per tutti i tipi di immagini vettoriali.
type: docs
weight: 5720
url: /it/net/aspose.psd/vectorimage/
---
## VectorImage class

L'immagine vettoriale è la classe base per tutti i tipi di immagini vettoriali.

```csharp
public abstract class VectorImage : Image, IObjectWithSizeF
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | Ottiene o imposta un valore che indica se la regolazione automatica della tavolozza. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | Ottiene o imposta un valore per il colore di sfondo. |
| abstract [BitsPerPixel](../../aspose.psd/image/bitsperpixel/) { get; } | Ottiene i bit dell'immagine per numero di pixel. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | Ottiene i limiti dell'immagine. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | Ottiene o imposta l'hint della dimensione del buffer che è definita dimensione massima consentita per tutti i buffer interni. |
| [Container](../../aspose.psd/image/container/) { get; } | Ottiene il[`Image`](../image/) contenitore. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | Ottiene il flusso di dati dell'oggetto. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | Ottiene un valore che indica se questa istanza è stata eliminata. |
| virtual [FileFormat](../../aspose.psd/image/fileformat/) { get; } | Ottiene un valore di file format |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | Ottiene o imposta un valore che indica se l'immagine ha un colore di sfondo. |
| override [Height](../../aspose.psd/vectorimage/height/) { get; } | Ottiene l'altezza dell'immagine. |
| virtual [HeightF](../../aspose.psd/vectorimage/heightf/) { get; } | Ottiene l'altezza dell'oggetto, in pollici. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | Ottiene o imposta il monitor di interrupt. |
| abstract [IsCached](../../aspose.psd/datastreamsupporter/iscached/) { get; } | Ottiene un valore che indica se i dati dell'oggetto sono attualmente memorizzati nella cache e non è richiesta alcuna lettura dei dati. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | Ottiene o imposta la tavolozza dei colori. La tavolozza dei colori non viene utilizzata quando i pixel sono rappresentati direttamente. |
| [Size](../../aspose.psd/image/size/) { get; } | Ottiene la dimensione dell'immagine. |
| [SizeF](../../aspose.psd/vectorimage/sizef/) { get; } | Ottiene la dimensione dell'oggetto, in pollici. |
| override [Width](../../aspose.psd/vectorimage/width/) { get; } | Ottiene la larghezza dell'immagine. |
| virtual [WidthF](../../aspose.psd/vectorimage/widthf/) { get; } | Ottiene la larghezza dell'oggetto, in pollici. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| abstract [CacheData](../../aspose.psd/datastreamsupporter/cachedata/)() | Memorizza i dati nella cache e garantisce che non venga eseguito alcun caricamento di dati aggiuntivi dal sottostante[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | Determina se l'immagine può essere salvata nel formato di file specificato rappresentato dalle opzioni di salvataggio passate. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | Elimina l'istanza corrente. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | Ottiene le opzioni predefinite. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | Ottiene le opzioni in base alle impostazioni del file originale. Questo può essere utile per mantenere invariati la profondità di bit e altri parametri dell'immagine originale. Ad esempio, se carichiamo un'immagine PNG in bianco e nero con 1 bit per pixel e poi salvalo usando the [`Save`](../datastreamsupporter/save/) metodo, verrà prodotta l'immagine PNG di output con 8 bit per pixel. Per evitarlo e salvare l'immagine PNG con 1 bit per pixel, utilizzare questo metodo per ottenere le opzioni di salvataggio corrispondenti e passarle al[`Save`](../image/save/)metodo come secondo parametro. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | Ridimensiona l'immagine. Il predefinitoLeftTopToLeftTopviene utilizzato. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ImageResizeSettings) | Ridimensiona l'immagine. |
| abstract [Resize](../../aspose.psd/image/resize/)(int, int, ResizeType) | Ridimensiona l'immagine. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | Ridimensiona proporzionalmente l'altezza. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | Ridimensiona proporzionalmente l'altezza. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | Ridimensiona proporzionalmente l'altezza. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | Ridimensiona proporzionalmente la larghezza. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | Ridimensiona proporzionalmente la larghezza. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | Ridimensiona proporzionalmente la larghezza. |
| abstract [RotateFlip](../../aspose.psd/image/rotateflip/)(RotateFlipType) | Ruota, capovolge o ruota e capovolge l'immagine. |
| [Save](../../aspose.psd/image/save/)() | Salva i dati dell'immagine nel flusso sottostante. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | Salva i dati dell'oggetto nel flusso specificato. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | Salva i dati dell'oggetto nella posizione file specificata. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | Salva i dati dell'immagine nel flusso specificato nel formato di file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | Salva i dati dell'oggetto nella posizione file specificata. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | Salva i dati dell'oggetto nella posizione file specificata nel formato file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | Salva i dati dell'immagine nel flusso specificato nel formato di file specificato in base alle opzioni di salvataggio. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | Salva i dati dell'oggetto nella posizione file specificata nel formato file specificato in base alle opzioni di salvataggio. |
| abstract [SetPalette](../../aspose.psd/image/setpalette/)(IColorPalette, bool) | Imposta la tavolozza dell'immagine. |

### Guarda anche

* class [Image](../image/)
* interface [IObjectWithSizeF](../../aspose.psd.interfaces/iobjectwithsizef/)
* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


