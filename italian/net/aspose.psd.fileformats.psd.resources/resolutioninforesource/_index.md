---
title: Class ResolutionInfoResource
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Resources.ResolutionInfoResource classe. La risorsa informativa sulla risoluzione
type: docs
weight: 3880
url: /it/net/aspose.psd.fileformats.psd.resources/resolutioninforesource/
---
## ResolutionInfoResource class

La risorsa informativa sulla risoluzione

```csharp
public sealed class ResolutionInfoResource : ResourceBlock
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ResolutionInfoResource](resolutioninforesource/)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/datasize/) { get; } | Ottiene la dimensione dei dati della risorsa in byte. |
| [HDpi](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/hdpi/) { get; set; } | DPI orizzontale. |
| [HeightDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/heightdisplayunit/) { get; set; } | Ottiene o imposta l'unità di visualizzazione dell'altezza. |
| [HResDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/hresdisplayunit/) { get; set; } | Unità di visualizzazione per la risoluzione orizzontale. Ciò riguarda solo l' interfaccia utente; la risoluzione è ancora memorizzata nel file PSD come pixel/pollice. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Ottiene o imposta l'identificatore univoco per la risorsa. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/minimalversion/) { get; } | Ottiene la versione PSD minima richiesta. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Ottiene o imposta il nome della risorsa. Stringa in Pascal, riempita per uniformare la dimensione (un nome nullo consiste di due byte di 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Ottiene la firma della risorsa. Dovrebbe essere sempre '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Ottiene la dimensione del blocco di risorse in byte, inclusi i relativi dati. |
| [VDpi](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/vdpi/) { get; set; } | DPI verticale. |
| [VResDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/vresdisplayunit/) { get; set; } | Unità di visualizzazione per risoluzione verticale. |
| [WidthDisplayUnit](../../aspose.psd.fileformats.psd.resources/resolutioninforesource/widthdisplayunit/) { get; set; } | Ottiene o imposta l'unità di visualizzazione della larghezza. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Salva il blocco di risorse nel flusso specificato. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Convalida i valori delle risorse. |

### Guarda anche

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assemblea [Aspose.PSD](../../)


