---
title: GifOptions.PixelAspectRatio
second_title: Aspose.PSD per riferimento API .NET
description: GifOptions proprietà. Ottiene o imposta le proporzioni pixel GIF.
type: docs
weight: 90
url: /it/net/aspose.psd.imageoptions/gifoptions/pixelaspectratio/
---
## GifOptions.PixelAspectRatio property

Ottiene o imposta le proporzioni pixel GIF.

```csharp
public byte PixelAspectRatio { get; set; }
```

### Valore della proprietà

Le proporzioni pixel GIF.

### Osservazioni

Pixel Aspect Ratio - Fattore utilizzato per calcolare un'approssimazione delle proporzioni del pixel nell'immagine originale. Se il valore del campo non è 0, questa approssimazione dell'aspect ratio viene calcolata in base alla formula: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 Il Pixel Aspect Ratio è definito come il quoziente del pixel' s larghezza sulla sua altezza. L'intervallo di valori in questo campo consente la specificazione del pixel più largo di 4:1 al pixel più alto di 1:4 in incrementi di 1/64. Valori : 0 - Non vengono fornite informazioni sulle proporzioni. 1..255 - Valore utilizzato nel calcolo.

### Guarda anche

* class [GifOptions](../)
* spazio dei nomi [Aspose.PSD.ImageOptions](../../gifoptions/)
* assemblea [Aspose.PSD](../../../)


