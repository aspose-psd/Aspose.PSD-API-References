---
title: "IColorPalette"
second_title: "Riferimento API Aspose.PSD per Java"
description: "L'interfaccia della tavolozza dei colori."
type: docs
weight: 117
url: /it/java/com.aspose.psd/icolorpalette/
---
```
public interface IColorPalette
```

L'interfaccia della tavolozza dei colori.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Restituisce il colore della tavolozza ARGB a 32 bit per indice. |
| [getArgb32Entries()](#getArgb32Entries--) | Ottiene un array di strutture ARGB a 32 bit. |
| [getColor(int index)](#getColor-int-) | Restituisce il colore della tavolozza per indice. |
| [getEntries()](#getEntries--) | Ottiene un array di  com.aspose.psd.Color  strutture. |
| [getEntriesCount()](#getEntriesCount--) | Restituisce il conteggio delle voci. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Restituisce l'indice del colore più vicino. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Ottiene l'indice del colore ARGB a 32 bit più vicino. |
| [isCompactPalette()](#isCompactPalette--) | Ottiene un valore che indica se viene utilizzata una tavolozza compatta. |
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public abstract int getArgb32Color(int index)
```


Restituisce il colore della tavolozza ARGB a 32 bit per indice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int | L'indice del colore della tavolozza ARGB a 32 bit. |

**Returns:**
int - La voce della tavolozza dei colori specificata dall'indice.
### getArgb32Entries() {#getArgb32Entries--}
```
public abstract int[] getArgb32Entries()
```


Ottiene un array di strutture ARGB a 32 bit.

**Returns:**
int[] - Le voci ARGB a 32 bit. L'array di strutture ARGB a 32 bit che compongono questo com.aspose.psd.ColorPalette.
### getColor(int index) {#getColor-int-}
```
public abstract Color getColor(int index)
```


Restituisce il colore della tavolozza per indice.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indice | int | L'indice del colore della tavolozza. |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public abstract Color[] getEntries()
```


Ottiene un array di  com.aspose.psd.Color  strutture.

**Returns:**
com.aspose.psd.Color[] - Le voci. L'array di strutture com.aspose.psd.Color che compongono questo com.aspose.psd.ColorPalette.
### getEntriesCount() {#getEntriesCount--}
```
public abstract int getEntriesCount()
```


Restituisce il conteggio delle voci.

**Returns:**
int - Il conteggio delle voci.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public abstract int getNearestColorIndex(Color color)
```


Restituisce l'indice del colore più vicino.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Il colore. |

**Returns:**
int - L'indice del colore più vicino.
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public abstract int getNearestColorIndex(int argb32Color)
```


Ottiene l'indice del colore ARGB a 32 bit più vicino.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argb32Color | int | Il colore ARGB a 32 bit. |

**Returns:**
int - L'indice del colore più vicino.
### isCompactPalette() {#isCompactPalette--}
```
public abstract boolean isCompactPalette()
```


Ottiene un valore che indica se viene utilizzata una tavolozza compatta.

Una tavolozza compatta significa che l'immagine conterrà solo le voci della tavolozza specificate, se possibile, o, in altre parole, l'immagine sarà più compatta e occuperà meno spazio; altrimenti ci saranno 2^BitsPerPixel voci e l'immagine riserverà più spazio per tutte le possibili voci della tavolozza. Impostare questo valore a true e modificare le voci della tavolozza può causare una penalità di prestazioni poiché potrebbe verificarsi lo spostamento dei dati, quindi usarlo con attenzione.

**Returns:**
boolean -  true  se la palette compatta è utilizzata; altrimenti,  false .
