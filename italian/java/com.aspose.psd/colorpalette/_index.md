---
title: "ColorPalette"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Definisce un array di colori che compongono una tavolozza di colori."
type: docs
weight: 27
url: /it/java/com.aspose.psd/colorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

Definisce un array di colori che compongono una tavolozza di colori. I colori sono ARGB a 32 bit. Non ereditabile.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | Inizializza una nuova istanza della classe  ColorPalette . |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | Inizializza una nuova istanza della classe  ColorPalette  e IsCompactPalette è false. |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.psd.Color---boolean-) | Inizializza una nuova istanza della classe  ColorPalette . |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.psd.Color---) | Inizializza una nuova istanza della classe  ColorPalette  e IsCompactPalette è false. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | Copia la tavolozza. |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | Copia la tavolozza. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | Restituisce il colore della tavolozza ARGB a 32 bit per indice. |
| [getArgb32Entries()](#getArgb32Entries--) | Ottiene un array di strutture ARGB a 32 bit. |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | Restituisce il colore della tavolozza per indice. |
| [getEntries()](#getEntries--) | Ottiene un array di  com.aspose.psd.Color  strutture. |
| [getEntriesCount()](#getEntriesCount--) | Restituisce il conteggio delle voci. |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | Restituisce l'indice del colore più vicino. |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | Restituisce l'indice del colore più vicino. |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | Ottiene o imposta un valore che indica se viene utilizzata la palette compatta. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorPalette(int[] argb32Entries, boolean isCompactPalette) {#ColorPalette-int---boolean-}
```
public ColorPalette(int[] argb32Entries, boolean isCompactPalette)
```


Inizializza una nuova istanza della classe  ColorPalette .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argb32Entries | int[] | Le voci della palette di colori ARGB a 32 bit. |
| isCompactPalette | boolean | Indica se la tavolozza è compatta. |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


Inizializza una nuova istanza della classe  ColorPalette  e IsCompactPalette è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argb32Entries | int[] | Le voci della palette di colori ARGB a 32 bit. |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.psd.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


Inizializza una nuova istanza della classe  ColorPalette .

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | Le voci della tavolozza dei colori. |
| isCompactPalette | boolean | Indica se la tavolozza è compatta. |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.psd.Color---}
```
public ColorPalette(Color[] entries)
```


Inizializza una nuova istanza della classe  ColorPalette  e IsCompactPalette è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | Le voci della tavolozza dei colori. |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


Copia la tavolozza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La tavolozza dei colori. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


Copia la tavolozza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | La tavolozza dei colori. |
| useCompactPalette | boolean | Indica se la tavolozza è compatta. |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
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
public int getArgb32Color(int index)
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
public int[] getArgb32Entries()
```


Ottiene un array di strutture ARGB a 32 bit.

**Returns:**
int[] - Le voci. L'array di struttura ARGB a 32 bit che compone questa  Aspose.Imaging.ColorPalette .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor(int index) {#getColor-int-}
```
public Color getColor(int index)
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
public Color[] getEntries()
```


Ottiene un array di  com.aspose.psd.Color  strutture.

**Returns:**
com.aspose.psd.Color[] - Le voci. L'array di struttura  com.aspose.psd.Color  che compone questa  Aspose.Imaging.ColorPalette .
### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


Restituisce il conteggio delle voci.

**Returns:**
int - Il conteggio delle voci.
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public int getNearestColorIndex(Color color)
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
public int getNearestColorIndex(int argb32Color)
```


Restituisce l'indice del colore più vicino.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| argb32Color | int | Il colore ARGB a 32 bit. |

**Returns:**
int - L'indice del colore più vicino.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


Ottiene o imposta un valore che indica se viene utilizzata la palette compatta.

**Returns:**
boolean -  true  se la palette compatta è utilizzata; altrimenti,  false .

Una tavolozza compatta significa che l'immagine conterrà solo le voci della tavolozza specificate, se possibile, o, in altre parole, l'immagine sarà più compatta e occuperà meno spazio; altrimenti ci saranno 2^BitsPerPixel voci e l'immagine riserverà più spazio per tutte le possibili voci della tavolozza. Impostare questo valore a true e modificare le voci della tavolozza può causare una penalità di prestazioni poiché potrebbe verificarsi lo spostamento dei dati, quindi usarlo con attenzione.
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

