---
title: CurvResource
second_title: Riferimento all'API di Aspose.PSD per .NET
description: Classe CurvResource. Risorsa di regolazione delle curve Layer 1 byte  0 se si usano le curve 1 se si usano pixel su map se 0 allora 2 byte  short. Il valore predefinito è 1 4 byte  int. Utilizzato solo lultimo byte per bit. Il primo bit è per 1 canale il quarto bit per 4 canali ad esempio 2 byte  conteggio punti brevi 4 byte  conteggio punto  punti curva 2 breve prima posizione seconda altezza 4 byte  parola Crv  2 byte  short predefinito è 4 per Curves 4 byte  int. Il valore predefinito è 1 4 byte  conteggio punti 4 byte  conteggio punti  punti della curva 2 corti prima posizione seconda altezza 04 byte  Porta ad essere piegato per quattro se 1 quindi 2 byte  breve. Il valore predefinito è 1 4 byte  int. Utilizzato solo lultimo byte. Un canale è in un bit. Il primo bit è per 1 canale il quarto bit per 4 canali ad esempio 256  conteggio dei canali modificati  valori ordinati del canale nellintervallo 0  255 4 byte  parola Crv  2 byte  breve. Il valore predefinito è 3 per i pixel su map 4 byte  int Channel count 2  256 byte  short 2 per lindice del canale 256 sono valori ordinati del canale nellintervallo 0  255
type: docs
weight: 2380
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/
---
## CurvResource class

Classe CurvResource. Risorsa di regolazione delle curve Layer 1 byte - 0 se si usano le curve, 1 se si usano pixel su map se 0 allora: 2 byte - short. Il valore predefinito è 1 4 byte - int. Utilizzato solo l'ultimo byte per bit. Il primo bit è per 1 canale, il quarto bit per 4 canali ad esempio 2 byte - conteggio punti brevi 4 byte * conteggio punto - punti curva 2 breve: prima posizione, seconda altezza 4 byte - parola "Crv " 2 byte - short predefinito è 4 per Curves 4 byte - int. Il valore predefinito è 1 4 byte - conteggio punti 4 byte * conteggio punti - punti della curva 2 corti: prima posizione, seconda altezza 0-4 byte - Porta ad essere piegato per quattro se 1 quindi: 2 byte - breve. Il valore predefinito è 1 4 byte - int. Utilizzato solo l'ultimo byte. Un canale è in un bit. Il primo bit è per 1 canale, il quarto bit per 4 canali ad esempio 256 * conteggio dei canali modificati - valori ordinati del canale nell'intervallo 0 - 255 4 byte - parola "Crv " 2 byte - breve. Il valore predefinito è 3 per i pixel su map 4 byte - int Channel count (2 + 256) byte - short 2 per l'indice del canale, 256 sono valori ordinati del canale nell'intervallo 0 - 255

```csharp
public class CurvResource : AdjustmentLayerResource
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [CurvResource](curvresource#constructor)(byte[]) | Inizializza una nuova istanza di[`CurvResource`](../curvresource) classe. |
| [CurvResource](curvresource#constructor_1)(int) | Inizializza una nuova istanza di[`CurvResource`](../curvresource) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [IsDataStoredDiscretely](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/isdatastoreddiscretely) { get; set; } | Ottiene o imposta un valore che indica se questa istanza contiene dati archiviati discreti. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/key) { get; } | Ottiene la chiave della risorsa del livello. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/length) { get; } | Ottiene la lunghezza della risorsa del livello in byte. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/psdversion) { get; } | Ottiene la versione psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature) { get; } | Ottiene la firma. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetActiveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getactivemanager)() | Ottiene il gestore attivo. |
| [GetChannelData](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getchanneldata)(int) | Ottiene i dati del canale. |
| [GetCurveManager](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/getcurvemanager)() | Ottiene il gestore curve. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/save)(StreamContainer, int) | Salva la risorsa nel contenitore del flusso specificato. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring)() | Restituisce aString che rappresenta questa istanza. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/curvresource/typetoolkey) | Il tipo di chiave info strumento. |

### Guarda anche

* class [AdjustmentLayerResource](../adjustmentlayerresource)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* assemblea [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
