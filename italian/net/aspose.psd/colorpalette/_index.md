---
title: Class ColorPalette
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.ColorPalette classe. Definisce una matrice di colori che compongono una tavolozza di colori. I colori sono colori ARGB a 32 bit. Non ereditabile.
type: docs
weight: 370
url: /it/net/aspose.psd/colorpalette/
---
## ColorPalette class

Definisce una matrice di colori che compongono una tavolozza di colori. I colori sono colori ARGB a 32 bit. Non ereditabile.

```csharp
public sealed class ColorPalette : IColorPalette
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ColorPalette](colorpalette/#constructor)(Color[]) | Inizializza una nuova istanza di`ColorPalette` class e IsCompactPalette è false. |
| [ColorPalette](colorpalette/#constructor_2)(int[]) | Inizializza una nuova istanza di`ColorPalette` class e IsCompactPalette è false. |
| [ColorPalette](colorpalette/#constructor_1)(Color[], bool) | Inizializza una nuova istanza di`ColorPalette` classe. |
| [ColorPalette](colorpalette/#constructor_3)(int[], bool) | Inizializza una nuova istanza di`ColorPalette` classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Argb32Entries](../../aspose.psd/colorpalette/argb32entries/) { get; } | Ottiene un array di strutture ARGB a 32 bit. |
| [Entries](../../aspose.psd/colorpalette/entries/) { get; } | Ottiene un array di[`Color`](../color/) strutture. |
| [EntriesCount](../../aspose.psd/colorpalette/entriescount/) { get; } | Ottiene il conteggio delle voci. |
| [IsCompactPalette](../../aspose.psd/colorpalette/iscompactpalette/) { get; } | Ottiene o imposta un valore che indica se viene utilizzata la tavolozza compatta. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette)(IColorPalette) | Copia la tavolozza. |
| static [CopyPalette](../../aspose.psd/colorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | Copia la tavolozza. |
| [GetArgb32Color](../../aspose.psd/colorpalette/getargb32color/)(int) | Ottiene il colore della tavolozza ARGB a 32 bit per indice. |
| [GetColor](../../aspose.psd/colorpalette/getcolor/)(int) | Ottiene il colore della tavolozza per indice. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | Ottiene l'indice del colore più vicino. |
| [GetNearestColorIndex](../../aspose.psd/colorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | Ottiene l'indice del colore più vicino. |

### Guarda anche

* interface [IColorPalette](../icolorpalette/)
* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


