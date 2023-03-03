---
title: Class MixrResource
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.MixrResource classe. Classe MixrResource. Risorsa del livello di regolazione del mixer dei canali
type: docs
weight: 2820
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/
---
## MixrResource class

Classe MixrResource. Risorsa del livello di regolazione del mixer dei canali

```csharp
public sealed class MixrResource : AdjustmentLayerResource
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MixrResource](mixrresource/#constructor)() | Inizializza una nuova istanza di`MixrResource` class. La specifica del formato PSD contiene la seguente descrizione: 2 Version ( = 1) 2 Monochrome 20 RGB o CMYK colore più costante per le impostazioni del mixer. 4 * 2 byte di colore con 2 byte di costante. |
| [MixrResource](mixrresource/#constructor_1)(byte[]) | Inizializza una nuova istanza di`MixrResource` class. La specifica del formato PSD contiene la seguente descrizione: 2 Version ( = 1) 2 Monochrome 20 RGB o CMYK colore più costante per le impostazioni del mixer. 4 * 2 byte di colore con 2 byte di costante. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/key/) { get; } | Ottiene la chiave della risorsa del livello. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/length/) { get; } | Ottiene la lunghezza della risorsa del livello in byte. |
| [Monochrome](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/monochrome/) { get; set; } | Ottiene o imposta un valore che indica se this`MixrResource` è monocromatico. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/psdversion/) { get; } | Ottiene la versione psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Ottiene la firma. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/version/) { get; set; } | Ottiene o imposta la versione. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/getchannelinfo/)(int) | Ottiene i dati grezzi delle informazioni sul canale |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Salva la risorsa nel contenitore del flusso specificato. |
| [SetChannelInfo](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/setchannelinfo/)(int, byte[]) | Imposta le informazioni sul canale. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Restituisce aString che rappresenta questa istanza. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/mixrresource/typetoolkey/) | Il tasto informazioni dello strumento testo. |

### Guarda anche

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assemblea [Aspose.PSD](../../)


