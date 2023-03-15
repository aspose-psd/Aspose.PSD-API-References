---
title: Class ResourceBlock
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.ResourceBlock classe. Il blocco delle risorse.
type: docs
weight: 3610
url: /it/net/aspose.psd.fileformats.psd/resourceblock/
---
## ResourceBlock class

Il blocco delle risorse.

```csharp
public abstract class ResourceBlock
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| abstract [DataSize](../../aspose.psd.fileformats.psd/resourceblock/datasize/) { get; } | Ottiene la dimensione dei dati della risorsa in byte. |
| [ID](../../aspose.psd.fileformats.psd/resourceblock/id/) { get; set; } | Ottiene o imposta l'identificatore univoco per la risorsa. |
| abstract [MinimalVersion](../../aspose.psd.fileformats.psd/resourceblock/minimalversion/) { get; } | Ottiene la versione PSD minima richiesta. |
| [Name](../../aspose.psd.fileformats.psd/resourceblock/name/) { get; set; } | Ottiene o imposta il nome della risorsa. Stringa in Pascal, riempita per uniformare la dimensione (un nome nullo consiste di due byte di 0). |
| [Signature](../../aspose.psd.fileformats.psd/resourceblock/signature/) { get; } | Ottiene la firma della risorsa. Dovrebbe essere sempre '8BIM'. |
| [Size](../../aspose.psd.fileformats.psd/resourceblock/size/) { get; } | Ottiene la dimensione del blocco di risorse in byte, inclusi i relativi dati. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Save](../../aspose.psd.fileformats.psd/resourceblock/save/)(StreamContainer) | Salva il blocco di risorse nel flusso specificato. |
| virtual [ValidateValues](../../aspose.psd.fileformats.psd/resourceblock/validatevalues/)() | Convalida i valori delle risorse. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [ResouceBlockMeSaSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblockmesasignature/) | La firma della risorsa di ImageReady. |
| const [ResouceBlockSignature](../../aspose.psd.fileformats.psd/resourceblock/resouceblocksignature/) | La normale firma delle risorse di Photoshop. |

## Altri membri

| Nome | Descrizione |
| --- | --- |
| enum [ResourceBlockState](resourceblock.resourceblockstate/) | Rappresenta lo stato del blocco delle risorse. |

### Guarda anche

* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../aspose.psd.fileformats.psd/)
* assemblea [Aspose.PSD](../../)


