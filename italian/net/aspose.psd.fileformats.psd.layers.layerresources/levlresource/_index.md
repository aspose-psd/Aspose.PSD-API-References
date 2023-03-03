---
title: Class LevlResource
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LevlResource classe. Class LevlResource. Risorsa del livello di regolazione dellesposizione
type: docs
weight: 2640
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/
---
## LevlResource class

Class LevlResource. Risorsa del livello di regolazione dell'esposizione

```csharp
public class LevlResource : AdjustmentLayerResource
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [LevlResource](levlresource/#constructor)() | Inizializza una nuova istanza di`LevlResource` classe. |
| [LevlResource](levlresource/#constructor_1)(byte[]) | Inizializza una nuova istanza di`LevlResource` class. Supportato in scala di grigi, due tonalità, RGB, CMYK, modalità colore Lab 2 byte - Versione (=2) 29 * 10 byte - Set di record di livello con 5 numeri interi brevi 4 byte - Intestazione Lvls (inizia all'indice 292) 2 byte - Versione (=3) 2 byte - Conteggio del record di livello totale 10 * (Conteggio totale - 29) La fine zero della risorsa Lvls dovrebbe essere piegata anche per quattro |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/key/) { get; } | Ottiene la chiave della risorsa del livello. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/length/) { get; } | Ottiene la lunghezza della risorsa del livello in byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/psdversion/) { get; } | Ottiene la versione psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Ottiene la firma. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/version/) { get; } | Ottiene la versione. Il valore predefinito è 2 |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetChannel](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/getchannel/)(int) | Ottiene il canale. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Salva la risorsa nel contenitore del flusso specificato. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Restituisce aString che rappresenta questa istanza. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/levlresource/typetoolkey/) | Il tasto informazioni dello strumento testo. |

### Guarda anche

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assemblea [Aspose.PSD](../../)


