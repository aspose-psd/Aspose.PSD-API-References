---
title: Class UnknownResource
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Resources.UnknownResource classe. La risorsa sconosciuta. Quando un blocco di risorse non viene riconosciuto viene creato questo blocco di risorse.
type: docs
weight: 3940
url: /it/net/aspose.psd.fileformats.psd.resources/unknownresource/
---
## UnknownResource class

La risorsa sconosciuta. Quando un blocco di risorse non viene riconosciuto, viene creato questo blocco di risorse.

```csharp
public sealed class UnknownResource : ResourceBlock
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Data](../../aspose.psd.fileformats.psd.resources/unknownresource/data/) { get; } | Ottiene i dati della risorsa. |
| override [DataSize](../../aspose.psd.fileformats.psd.resources/unknownresource/datasize/) { get; } | Ottiene la dimensione dei dati della risorsa in byte. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Ottiene o imposta l'identificatore univoco per la risorsa. |
| override [MinimalVersion](../../aspose.psd.fileformats.psd.resources/unknownresource/minimalversion/) { get; } | Ottiene la versione psd minima richiesta. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Ottiene o imposta il nome della risorsa. Stringa in Pascal, riempita per uniformare la dimensione (un nome nullo consiste di due byte di 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Ottiene la firma della risorsa. Dovrebbe essere sempre '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Ottiene la dimensione del blocco di risorse in byte, inclusi i relativi dati. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Salva il blocco di risorse nel flusso specificato. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Convalida i valori delle risorse. |

### Guarda anche

* class [ResourceBlock](../../aspose.psd.fileformats.psd/resourceblock/)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Resources](../../aspose.psd.fileformats.psd.resources/)
* assemblea [Aspose.PSD](../../)


