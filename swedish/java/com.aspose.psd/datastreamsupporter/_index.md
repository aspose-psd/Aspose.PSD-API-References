---
title: "DataStreamSupporter"
second_title: "Aspose.PSD för Java API-referens"
description: "Datastreambehållaren."
type: docs
weight: 38
url: /sv/java/com.aspose.psd/datastreamsupporter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

Datastreambehållaren.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [OnSave_internalized](#OnSave-internalized) | Uppstår när bilden har laddats eller sparats |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | Uppstår när kredit har använts |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [cacheData()](#cacheData--) | Cachar data och säkerställer att ingen ytterligare datainläsning kommer att utföras från den underliggande DataStreamSupporter.DataStreamContainer. |
| [close()](#close--) | Implementerar Closable-gränssnittet och kan användas i try-with-resources-satsen sedan JDK 1.7. |
| [dispose()](#dispose--) | Frigör den aktuella instansen. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataStreamContainer()](#getDataStreamContainer--) | Hämtar objektets datastream. |
| [getDisposed()](#getDisposed--) | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | Hämtar filsökvägen till källbilden om den finns. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | Hämtar ett värde som indikerar om objektet använder minnesoptimeringsstrategi |
| [hashCode()](#hashCode--) |  |
| [isCached()](#isCached--) | Hämtar ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save()](#save--) | Sparar objektets data till den aktuella  DataStreamSupporter . |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Sparar objektets data till den angivna strömmen. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | Sparar objektets data till den angivna strömmen. |
| [save(String filePath)](#save-java.lang.String-) | Sparar objektets data till den angivna filplatsen. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | Sparar objektets data till den angivna filplatsen. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | Ställer in objektets datastream. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | Ställer in ett värde som indikerar om [ignore after save]. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


Uppstår när bilden har laddats eller sparats

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


Uppstår när kredit har använts

### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


Cachar data och säkerställer att ingen ytterligare datainläsning kommer att utföras från den underliggande DataStreamSupporter.DataStreamContainer.

### close() {#close--}
```
public void close()
```


Implementerar Closable‑gränssnittet och kan användas i try‑with‑resources‑satsen sedan JDK 1.7. Denna metod anropar helt enkelt dispose‑metoden.

### dispose() {#dispose--}
```
public final void dispose()
```


Frigör den aktuella instansen.

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


Hämtar objektets datastream.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Hämtar ett värde som indikerar om den här instansen har frigjorts.

**Returns:**
boolean -  true  om frigjord; annars,  false .
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


Hämtar filsökvägen för källbilden om den finns. Returnerar en tom sträng om källsökvägen inte kan hittas.

**Returns:**
java.lang.String - Filsökvägen för källbilden.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


Hämtar ett värde som indikerar om objektet använder minnesoptimeringsstrategi

Värde:  true  om objektet använder minnesoptimeringsstrategi; annars  false .

**Returns:**
boolean - ett värde som indikerar om objektet använder minnesoptimeringsstrategi
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCached() {#isCached--}
```
public abstract boolean isCached()
```


Hämtar ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs.

**Returns:**
boolean - ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save() {#save--}
```
public void save()
```


Sparar objektets data till den aktuella  DataStreamSupporter .

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


Sparar objektets data till den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Strömmen att spara objektets data till. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


Sparar objektets data till den angivna strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fil | java.io.RandomAccessFile | Strömmen att spara objektets data till. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Sparar objektets data till den angivna filplatsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen att spara objektets data till. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


Sparar objektets data till den angivna filplatsen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen att spara objektets data till. |
| overWrite | boolean | Om den är satt till  true  skrivs filens innehåll över, annars kommer data att läggas till. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


Ställer in objektets datastream.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | Objektets datastream. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


Ställer in ett värde som indikerar om [ignore after save].

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | true om [ignore after save]; annars false. |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

