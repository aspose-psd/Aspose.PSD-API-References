---
title: "FilterEffectMaskData"
second_title: "Riferimento API Aspose.PSD per Java"
description: "La classe dati della maschera filtro."
type: docs
weight: 31
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---

**Inheritance:**
java.lang.Object
```
public final class FilterEffectMaskData
```

La classe dati della maschera filtro.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FilterEffectMaskData(String guid, Rectangle rectangle, int pixelsDepth, int maxChannels, ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, ChannelInformation sheetMask)](#FilterEffectMaskData-java.lang.String-com.aspose.psd.Rectangle-int-int-com.aspose.psd.fileformats.psd.layers.ChannelInformation---com.aspose.psd.fileformats.psd.layers.ChannelInformation-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.ChannelInformation-) | Inizializza una nuova istanza della classe [FilterEffectMaskData](../../com.aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChannels()](#getChannels--) | Restituisce i canali. |
| [getClass()](#getClass--) |  |
| [getGUID()](#getGUID--) | Restituisce il GUID. |
| [getLength()](#getLength--) | Restituisce la lunghezza dei dati della maschera filtro in byte. |
| [getMaskRectangle()](#getMaskRectangle--) | Restituisce il rettangolo della maschera foglio. |
| [getMaxChannels()](#getMaxChannels--) | Restituisce il massimo del conteggio dei canali. |
| [getPixelsDepth()](#getPixelsDepth--) | Restituisce la profondità dei pixel. |
| [getRectangle()](#getRectangle--) | Restituisce il rettangolo dei canali. |
| [getSheetMask()](#getSheetMask--) | Restituisce la maschera foglio. |
| [getUserMask()](#getUserMask--) | Restituisce la maschera utente. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveData(StreamContainer streamContainer)](#saveData-com.aspose.psd.StreamContainer-) | Salva la risorsa nel contenitore di stream specificato. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FilterEffectMaskData(String guid, Rectangle rectangle, int pixelsDepth, int maxChannels, ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, ChannelInformation sheetMask) {#FilterEffectMaskData-java.lang.String-com.aspose.psd.Rectangle-int-int-com.aspose.psd.fileformats.psd.layers.ChannelInformation---com.aspose.psd.fileformats.psd.layers.ChannelInformation-com.aspose.psd.Rectangle-com.aspose.psd.fileformats.psd.layers.ChannelInformation-}
```
public FilterEffectMaskData(String guid, Rectangle rectangle, int pixelsDepth, int maxChannels, ChannelInformation[] channels, ChannelInformation userMask, Rectangle maskRectangle, ChannelInformation sheetMask)
```


Inizializza una nuova istanza della classe [FilterEffectMaskData](../../com.aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| guid | java.lang.String | Il guid della risorsa. |
| rectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo dei canali. |
| pixelsDepth | int | La profondità dei pixel. |
| maxChannels | int | Il valore massimo dei canali. |
| channels | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | I canali. |
| userMask | [ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | La maschera utente. |
| maskRectangle | [Rectangle](../../com.aspose.psd/rectangle) | Il rettangolo della maschera del foglio. |
| sheetMask | [ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | La maschera del foglio. |

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
### getChannels() {#getChannels--}
```
public final ChannelInformation[] getChannels()
```


Restituisce i canali.

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGUID() {#getGUID--}
```
public final String getGUID()
```


Restituisce il GUID.

**Returns:**
java.lang.String
### getLength() {#getLength--}
```
public final long getLength()
```


Restituisce la lunghezza dei dati della maschera filtro in byte.

**Returns:**
long
### getMaskRectangle() {#getMaskRectangle--}
```
public final Rectangle getMaskRectangle()
```


Restituisce il rettangolo della maschera foglio.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getMaxChannels() {#getMaxChannels--}
```
public final int getMaxChannels()
```


Restituisce il massimo del conteggio dei canali.

**Returns:**
int
### getPixelsDepth() {#getPixelsDepth--}
```
public final int getPixelsDepth()
```


Restituisce la profondità dei pixel.

**Returns:**
int
### getRectangle() {#getRectangle--}
```
public final Rectangle getRectangle()
```


Restituisce il rettangolo dei canali.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getSheetMask() {#getSheetMask--}
```
public final ChannelInformation getSheetMask()
```


Restituisce la maschera foglio.

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### getUserMask() {#getUserMask--}
```
public final ChannelInformation getUserMask()
```


Restituisce la maschera utente.

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### saveData(StreamContainer streamContainer) {#saveData-com.aspose.psd.StreamContainer-}
```
public final void saveData(StreamContainer streamContainer)
```


Salva la risorsa nel contenitore di stream specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Il contenitore di flusso in cui salvare. |

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

