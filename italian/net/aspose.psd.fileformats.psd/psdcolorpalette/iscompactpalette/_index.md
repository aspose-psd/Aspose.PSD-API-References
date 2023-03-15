---
title: PsdColorPalette.IsCompactPalette
second_title: Aspose.PSD per riferimento API .NET
description: PsdColorPalette proprietà. Ottiene un valore che indica se compattare la tavolozza.
type: docs
weight: 70
url: /it/net/aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/
---
## PsdColorPalette.IsCompactPalette property

Ottiene un valore che indica se compattare la tavolozza.

```csharp
public bool IsCompactPalette { get; }
```

### Valore della proprietà

`VERO` se compatto tavolozza; Altrimenti,`falso`.

### Osservazioni

Tavolozza compatta significa che l'immagine conterrà solo le voci della tavolozza specificate, se possibile o in altre parole l'immagine sarà più compatta e occuperà meno spazio; altrimenti ci saranno 2^BitsPerPixel voci e l'immagine riserverà più spazio per tutte le possibili voci della tavolozza . L'impostazione di questo valore su true e la modifica delle voci della tavolozza possono causare una riduzione delle prestazioni poiché potrebbe verificarsi lo spostamento dei dati, quindi utilizzalo con attenzione.

### Guarda anche

* class [PsdColorPalette](../)
* spazio dei nomi [Aspose.PSD.FileFormats.Psd](../../psdcolorpalette/)
* assemblea [Aspose.PSD](../../../)


