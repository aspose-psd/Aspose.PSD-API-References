---
title: Class PhflResource
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PhflResource classe. Classe PhflResource. Risorsa del livello di regolazione dellesposizione 2 versione   3  o   2  12 4 byte ciascuno per il colore XYZ solo nella versione 3 10 2 byte di spazio colore seguito da 4  2 byte di componente colore solo nella versione 2 4 Densità 1 Mantieni luminosità
type: docs
weight: 2890
url: /it/net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/
---
## PhflResource class

Classe PhflResource. Risorsa del livello di regolazione dell'esposizione 2 versione ( = 3 ) o ( = 2 ) 12 4 byte ciascuno per il colore XYZ (solo nella versione 3) 10 2 byte di spazio colore seguito da 4 * 2 byte di componente colore (solo nella versione 2) 4 Densità 1 Mantieni luminosità

```csharp
public abstract class PhflResource : AdjustmentLayerResource
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Density](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/density/) { get; set; } | Ottiene o imposta la densità. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/key/) { get; } | Ottiene la chiave della risorsa del livello. |
| abstract [Length](../../aspose.psd.fileformats.psd.layers/layerresource/length/) { get; } | Ottiene la lunghezza della risorsa del livello in byte. |
| [PreserveLuminosity](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/preserveluminosity/) { get; set; } | Ottiene o imposta un valore che indica se [preserve luminosity]. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/psdversion/) { get; } | Ottiene la versione psd. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/signature/) { get; } | Ottiene la firma. |
| abstract [Version](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/version/) { get; } | Ottiene la versione. Il valore predefinito è 2 o 3 |

## Metodi

| Nome | Descrizione |
| --- | --- |
| abstract [GetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/getrgbcolor/)() | Ottiene il colore dell'RGB. |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/save/)(StreamContainer, int) | Salva la risorsa nel contenitore del flusso specificato. |
| abstract [SetRgbColor](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/setrgbcolor/)(Color) | Imposta il colore RGB. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Restituisce aString che rappresenta questa istanza. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/phflresource/typetoolkey/) | Il tasto informazioni dello strumento testo. |

### Guarda anche

* class [AdjustmentLayerResource](../adjustmentlayerresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assemblea [Aspose.PSD](../../)


