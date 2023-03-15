---
title: Class ThumbnailResource
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Resources.ThumbnailResource classe. Il blocco delle risorse delle miniature.
type: docs
weight: 3910
url: /it/net/aspose.psd.fileformats.psd.resources/thumbnailresource/
---
## ThumbnailResource class

Il blocco delle risorse delle miniature.

```csharp
public class ThumbnailResource : ResourceBlock
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ThumbnailResource](thumbnailresource/)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BitsPixel](../../aspose.psd.fileformats.psd.resources/thumbnailresource/bitspixel/) { get; set; } | Ottiene o imposta i bit pixel. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/thumbnailresource/datasize/) { get; } | Ottiene la dimensione dei dati della risorsa in byte. |
| [Format](../../aspose.psd.fileformats.psd.resources/thumbnailresource/format/) { get; set; } | Ottiene o imposta il formato dei dati della miniatura. |
| [Height](../../aspose.psd.fileformats.psd.resources/thumbnailresource/height/) { get; set; } | Ottiene o imposta l'altezza della miniatura in pixel. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Ottiene o imposta l'identificatore univoco per la risorsa. |
| [JpegOptions](../../aspose.psd.fileformats.psd.resources/thumbnailresource/jpegoptions/) { get; set; } | Ottiene o imposta le opzioni JPEG. Adatto quando la risorsa miniatura viene salvata solo nel formato di file JPEG. Questa opzione non ha effetto quando è definito il formato RAW. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/thumbnailresource/minimalversion/) { get; } | Ottiene la versione psd minima richiesta. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Ottiene o imposta il nome della risorsa. Stringa in Pascal, riempita per uniformare la dimensione (un nome nullo consiste di due byte di 0). |
| [PlanesCount](../../aspose.psd.fileformats.psd.resources/thumbnailresource/planescount/) { get; set; } | Ottiene o imposta il conteggio dei piani. |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Ottiene la firma della risorsa. Dovrebbe essere sempre '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Ottiene la dimensione del blocco di risorse in byte, inclusi i relativi dati. |
| [SizeAfterCompression](../../aspose.psd.fileformats.psd.resources/thumbnailresource/sizeaftercompression/) { get; } | Ottiene o imposta la dimensione dopo la compressione. Utilizzato per il controllo della coerenza. |
| [ThumbnailArgb32Data](../../aspose.psd.fileformats.psd.resources/thumbnailresource/thumbnailargb32data/) { get; set; } | Ottiene o imposta i dati della miniatura ARGB a 32 bit. |
| [ThumbnailData](../../aspose.psd.fileformats.psd.resources/thumbnailresource/thumbnaildata/) { get; set; } | Ottiene o imposta i dati della miniatura. |
| [TotalSize](../../aspose.psd.fileformats.psd.resources/thumbnailresource/totalsize/) { get; } | Ottiene la dimensione totale dei dati. |
| [Width](../../aspose.psd.fileformats.psd.resources/thumbnailresource/width/) { get; set; } | Ottiene o imposta la larghezza della miniatura in pixel. |
| [WidthBytes](../../aspose.psd.fileformats.psd.resources/thumbnailresource/widthbytes/) { get; } | Ottiene la larghezza della riga in byte. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Salva il blocco di risorse nel flusso specificato. |
| override [ValidateValues](../../aspose.psd.fileformats.psd.resources/thumbnailresource/validatevalues/)() | Convalida i valori delle risorse. |

### Guarda anche

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assemblea [Aspose.PSD](../../)


