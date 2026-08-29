---
title: "RawColor"
second_title: "Riferimento API Aspose.PSD per Java"
description: "La classe Raw Color aiuta a memorizzare colori con qualsiasi numero di canali, qualsiasi modalità colore e qualsiasi profondità di bit. Si prega di notare che alcune classi interne possono avere problemi nella conversione di RawColor nel suo formato nativo, quindi se l'API fornisce un colore CMYK è più affidabile utilizzare il formato fornito."
type: docs
weight: 11
url: /it/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolor/
---

**Inheritance:**
java.lang.Object
```
public final class RawColor
```

La classe Raw Color aiuta a memorizzare colori con qualsiasi numero di canali, qualsiasi modalità colore e qualsiasi profondità di bit. Si prega di notare che alcune classi interne possono avere problemi nella conversione di RawColor nel suo formato nativo, quindi se l'API fornisce un colore CMYK è più affidabile utilizzare il formato fornito. Inoltre, possono esserci alcuni casi in cui Raw Color può essere convertito.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RawColor(ColorComponent[] components)](#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---) | Inizializza una nuova istanza della classe [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor). |
| [RawColor(PixelDataFormat pixelDataFormat)](#RawColor-com.aspose.psd.PixelDataFormat-) |  |
| [RawColor(PixelDataFormat pixelDataFormat, short colorMode)](#RawColor-com.aspose.psd.PixelDataFormat-short-) | Inizializza una nuova istanza della classe [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) dal formato dati pixel utilizzando modalità colore predefinite. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se l'Object specificato è uguale a questa istanza. |
| [getAsInt()](#getAsInt--) | Ottiene il colore come int nel caso sia possibile ottenerlo. |
| [getAsLong()](#getAsLong--) | Ottiene il colore come long nel caso sia possibile ottenerlo. |
| [getBitDepth()](#getBitDepth--) | Ottiene la profondità di bit di Raw Color. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | Modalità da seguire per il colore. |
| [getColorModeName()](#getColorModeName--) | Ottiene il nome della modalità colore. |
| [getComponents()](#getComponents--) | Ottiene i componenti del colore. |
| [hashCode()](#hashCode--) | Ottieni il codice hash dell'oggetto corrente. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(RawColor left, RawColor right)](#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Implementa l'operatore ==. |
| [op_Inequality(RawColor left, RawColor right)](#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Implementa l'operatore !=. |
| [setAsInt(int value)](#setAsInt-int-) | Imposta i dati a tutti i canali dall'argomento int se possibile. |
| [setAsLong(long value)](#setAsLong-long-) | Imposta i dati a tutti i canali dall'argomento int se possibile. |
| [setColorMode(short value)](#setColorMode-short-) | Modalità da seguire per il colore. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColor(ColorComponent[] components) {#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---}
```
public RawColor(ColorComponent[] components)
```


Inizializza una nuova istanza della classe [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| components | [ColorComponent\[\]](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) | I componenti di colore personalizzati. |

### RawColor(PixelDataFormat pixelDataFormat) {#RawColor-com.aspose.psd.PixelDataFormat-}
```
public RawColor(PixelDataFormat pixelDataFormat)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) |  |

### RawColor(PixelDataFormat pixelDataFormat, short colorMode) {#RawColor-com.aspose.psd.PixelDataFormat-short-}
```
public RawColor(PixelDataFormat pixelDataFormat, short colorMode)
```


Inizializza una nuova istanza della classe [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) dal formato dati pixel utilizzando modalità colore predefinite.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Il formato dei dati pixel. |
| colorMode | short |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se l'Object specificato è uguale a questa istanza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto da confrontare con questa istanza. |

**Returns:**
boolean -  true  se l'oggetto specificato è uguale a questa istanza; altrimenti,  false .
### getAsInt() {#getAsInt--}
```
public final int getAsInt()
```


Ottiene il colore come int nel caso sia possibile ottenerlo.

**Returns:**
int - Dati dei canali memorizzati in Int
### getAsLong() {#getAsLong--}
```
public final long getAsLong()
```


Ottiene il colore come long nel caso sia possibile ottenerlo.

**Returns:**
long - Dati dei canali memorizzati in Int
### getBitDepth() {#getBitDepth--}
```
public final int getBitDepth()
```


Restituisce la profondità di bit del Raw Color. Per esempio, per il colore ARGB con 8 bit per canale/componente è 32 Bit Depth; per il colore ARGB completo con 16 bit per canale/componente è 64. La profondità di bit è accumulata dalla somma delle profondità di bit dei canali. È possibile che canali diversi abbiano profondità di bit differenti.

**Returns:**
int - La somma di tutte le profondità di bit dei canali
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Modalità da seguire per il colore.

**Returns:**
short
### getColorModeName() {#getColorModeName--}
```
public final String getColorModeName()
```


Restituisce il nome della modalità colore. Il nome della modalità colore è accumulato dai nomi dei canali/componenti

**Returns:**
java.lang.String - Stringa con il nome della modalità colore
### getComponents() {#getComponents--}
```
public final ColorComponent[] getComponents()
```


Restituisce i componenti del colore. Ogni componente è un canale separato e, se si utilizza uno schema colore non comune, è meglio lavorare con ciascun canale separatamente

Valore: I componenti del colore

**Returns:**
com.aspose.psd.fileformats.psd.rawcolor.ColorComponent[]
### hashCode() {#hashCode--}
```
public int hashCode()
```


Ottieni il codice hash dell'oggetto corrente.

**Returns:**
int - Il codice hash.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(RawColor left, RawColor right) {#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Equality(RawColor left, RawColor right)
```


Implementa l'operatore ==.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Il primo RawColor. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Il secondo RawColor. |

**Returns:**
boolean - Il risultato dell'operatore.
### op_Inequality(RawColor left, RawColor right) {#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Inequality(RawColor left, RawColor right)
```


Implementa l'operatore !=.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Il primo RawColor. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Il secondo RawColor. |

**Returns:**
boolean - Il risultato dell'operatore.
### setAsInt(int value) {#setAsInt-int-}
```
public final void setAsInt(int value)
```


Imposta i dati a tutti i canali dall'argomento int se possibile.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Il valore int che contiene i dati del componente |

### setAsLong(long value) {#setAsLong-long-}
```
public final void setAsLong(long value)
```


Imposta i dati a tutti i canali dall'argomento int se possibile.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long | Il valore int che contiene i dati del componente |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Modalità da seguire per il colore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

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

