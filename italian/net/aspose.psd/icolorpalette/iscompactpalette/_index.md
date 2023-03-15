---
title: IColorPalette.IsCompactPalette
second_title: Aspose.PSD per riferimento API .NET
description: IColorPalette proprietà. Ottiene un valore che indica se viene utilizzata la tavolozza compatta.
type: docs
weight: 40
url: /it/net/aspose.psd/icolorpalette/iscompactpalette/
---
## IColorPalette.IsCompactPalette property

Ottiene un valore che indica se viene utilizzata la tavolozza compatta.

```csharp
public bool IsCompactPalette { get; }
```

### Valore della proprietà

`VERO` se viene utilizzata una tavolozza compatta; Altrimenti,`falso`.

### Osservazioni

Tavolozza compatta significa che l'immagine conterrà solo le voci della tavolozza specificate se possibile o in altre parole l'immagine sarà più compatta e occuperà meno spazio; altrimenti ci saranno 2^BitsPerPixel voci e l'immagine riserverà più spazio per tutte le possibili voci della tavolozza. L'impostazione di questo valore su true e la modifica delle voci della tavolozza possono causare una riduzione delle prestazioni poiché potrebbe verificarsi lo spostamento dei dati, quindi utilizzalo con attenzione.

### Guarda anche

* interface [IColorPalette](../)
* spazio dei nomi [Aspose.PSD](../../icolorpalette/)
* assemblea [Aspose.PSD](../../../)


