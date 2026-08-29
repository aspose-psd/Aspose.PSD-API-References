---
title: "PsdColorPalette"
second_title: "Riferimento API Aspose.PSD per Java"
description: "La tavolozza dei colori PSD."
type: docs
weight: 13
url: /it/java/com.aspose.psd.fileformats.psd/psdcolorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IPsdColorPalette](../../com.aspose.psd/ipsdcolorpalette)
```
public class PsdColorPalette implements IPsdColorPalette
```

La tavolozza dei colori PSD.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PsdColorPalette(IColorPalette colorPalette)](#PsdColorPalette-com.aspose.psd.IColorPalette-) | Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(IColorPalette colorPalette, short transparentIndex)](#PsdColorPalette-com.aspose.psd.IColorPalette-short-) | Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)](#PsdColorPalette-byte---boolean-) | Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData)](#PsdColorPalette-byte---) | Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) e IsCompactPalette è false. |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-byte---short-boolean-) | Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex)](#PsdColorPalette-byte---short-) | Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) e IsCompactPalette è false. |
| [PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)](#PsdColorPalette-int---boolean-) | Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---boolean-) | Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries)](#PsdColorPalette-com.aspose.psd.Color---) | Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) e IsCompactPalette è false. |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---short-boolean-) | Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette). |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)](#PsdColorPalette-com.aspose.psd.Color---short-) | Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) e IsCompactPalette è false. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Copia la tavolozza. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Copia la tavolozza. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Restituisce il colore della tavolozza ARGB a 32 bit per indice. |
| [getArgb32Entries()](#getArgb32Entries--) | Restituisce un array di colori ARGB a 32 bit. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Restituisce il colore della tavolozza per indice. |
| [getEntries()](#getEntries--) | Restituisce un array di strutture [Color](../../com.aspose.psd/color). |
| [getEntriesCount()](#getEntriesCount--) | Restituisce il conteggio delle voci. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Restituisce l'indice del colore più vicino. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Restituisce l'indice del colore più vicino. |
| [getRawEntries()](#getRawEntries--) | Restituisce i dati grezzi delle voci della tavolozza dei colori. |
| [getRawEntriesCount()](#getRawEntriesCount--) | Restituisce il conteggio grezzo delle voci della tavolozza dei colori. |
| [getTransparentColor()](#getTransparentColor--) | Restituisce il colore trasparente. |
| [getTransparentIndex()](#getTransparentIndex--) | Restituisce l'indice del colore trasparente. |
| [hasTransparentColor()](#hasTransparentColor--) | Restituisce un valore che indica se esiste un colore trasparente. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Restituisce un valore che indica se la tavolozza è compatta. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdColorPalette(IColorPalette colorPalette) {#PsdColorPalette-com.aspose.psd.IColorPalette-}
```
public PsdColorPalette(IColorPalette colorPalette)
```


Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La tavolozza dei colori. |

### PsdColorPalette(IColorPalette colorPalette, short transparentIndex) {#PsdColorPalette-com.aspose.psd.IColorPalette-short-}
```
public PsdColorPalette(IColorPalette colorPalette, short transparentIndex)
```


Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La tavolozza dei colori. |
| transparentIndex | short | L'indice del colore trasparente. |

### PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette) {#PsdColorPalette-byte---boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)
```


Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rawEntriesData | byte[] | I dati grezzi delle voci. |
| isCompactPalette | boolean | Indica se la tavolozza è compatta. |

### PsdColorPalette(byte[] rawEntriesData) {#PsdColorPalette-byte---}
```
public PsdColorPalette(byte[] rawEntriesData)
```


Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) e IsCompactPalette è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rawEntriesData | byte[] | I dati grezzi delle voci. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-byte---short-boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)
```


Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rawEntriesData | byte[] | I dati grezzi delle voci. |
| transparentIndex | short | L'indice del colore trasparente. Nota che l'indice non è l'indice grezzo delle voci, ma è per l'array di colori convertito. |
| useCompactPalette | boolean | Indica se la tavolozza è compatta. |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex) {#PsdColorPalette-byte---short-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex)
```


Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) e IsCompactPalette è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rawEntriesData | byte[] | I dati grezzi delle voci. |
| transparentIndex | short | L'indice del colore trasparente. Nota che l'indice non è l'indice grezzo delle voci, ma è per l'array di colori convertito. |

### PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette) {#PsdColorPalette-int---boolean-}
```
public PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)
```


Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorPaletteArgb32Entries | int[] | Le voci ARGB a 32 bit della tavolozza dei colori. |
| isCompactPalette | boolean | Indica se la tavolozza è compatta. |

### PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)
```


Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Le voci della tavolozza dei colori. |
| isCompactPalette | boolean | Indica se la tavolozza è compatta. |

### PsdColorPalette(Color[] colorPaletteEntries) {#PsdColorPalette-com.aspose.psd.Color---}
```
public PsdColorPalette(Color[] colorPaletteEntries)
```


Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) e IsCompactPalette è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Le voci della tavolozza dei colori. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---short-boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)
```


Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Le voci della tavolozza dei colori. |
| transparentIndex | short | L'indice del colore trasparente. |
| useCompactPalette | boolean | Indica se la tavolozza è compatta. |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex) {#PsdColorPalette-com.aspose.psd.Color---short-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)
```


Inizializza una nuova istanza della classe [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) e IsCompactPalette è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | Le voci della tavolozza dei colori. |
| transparentIndex | short | L'indice del colore trasparente. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette)
```


Copia la tavolozza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La tavolozza dei colori. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Copia la tavolozza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La tavolozza dei colori. |
| useCompactPalette | boolean | Indica se la tavolozza è compatta. |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public final int getArgb32Color(int index)
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
public final int[] getArgb32Entries()
```


Restituisce un array di colori ARGB a 32 bit.

**Returns:**
int[] - L'array di strutture ARGB a 32 bit che compongono questa [ColorPalette](../../com.aspose.psd/colorpalette). Valore: le voci.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor(int index) {#getColor-int-}
```
public final Color getColor(int index)
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
public final Color[] getEntries()
```


Restituisce un array di strutture [Color](../../com.aspose.psd/color).

**Returns:**
com.aspose.psd.Color[] - L'array di strutture [Color](../../com.aspose.psd/color) che compongono questa [ColorPalette](../../com.aspose.psd/colorpalette). Valore: le voci.
### getEntriesCount() {#getEntriesCount--}
```
public final int getEntriesCount()
```


Restituisce il conteggio delle voci.

Valore: il conteggio delle voci.

**Returns:**
int
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public final int getNearestColorIndex(Color color)
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
public final int getNearestColorIndex(int argb32Color)
```


Restituisce l'indice del colore più vicino.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argb32Color | int | Il colore ARGB a 32 bit. |

**Returns:**
int - L'indice del colore più vicino.
### getRawEntries() {#getRawEntries--}
```
public final byte[] getRawEntries()
```


Restituisce i dati grezzi delle voci della tavolozza dei colori.

Valore: I dati grezzi delle voci della tavolozza dei colori.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public final int getRawEntriesCount()
```


Restituisce il conteggio grezzo delle voci della tavolozza dei colori.

Valore: Il conteggio grezzo delle voci della tavolozza dei colori.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public final Color getTransparentColor()
```


Restituisce il colore trasparente.

Valore: Il colore trasparente.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public final short getTransparentIndex()
```


Restituisce l'indice del colore trasparente.

Valore: L'indice del colore trasparente.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public final boolean hasTransparentColor()
```


Restituisce un valore che indica se esiste un colore trasparente.

Valore:  true  se il colore trasparente esiste; altrimenti,  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompactPalette() {#isCompactPalette--}
```
public final boolean isCompactPalette()
```


Restituisce un valore che indica se la tavolozza è compatta.

Valore:  true  se la tavolozza è compatta; altrimenti,  false .

--------------------

Una tavolozza compatta significa che l'immagine conterrà solo le voci della tavolozza specificate, se possibile, o, in altre parole, l'immagine sarà più compatta e occuperà meno spazio; altrimenti ci saranno 2^BitsPerPixel voci e l'immagine riserverà più spazio per tutte le possibili voci della tavolozza. Impostare questo valore a true e modificare le voci della tavolozza può causare una penalità di prestazioni poiché potrebbe verificarsi lo spostamento dei dati, quindi usarlo con attenzione.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

