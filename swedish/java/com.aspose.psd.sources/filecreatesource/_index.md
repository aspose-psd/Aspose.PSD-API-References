---
title: "FileCreateSource"
second_title: "Aspose.PSD för Java API-referens"
description: "Representerar en filkälla för skapande."
type: docs
weight: 10
url: /sv/java/com.aspose.psd.sources/filecreatesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.Source](../../com.aspose.psd/source), [com.aspose.psd.sources.FileSource](../../com.aspose.psd.sources/filesource)
```
public final class FileCreateSource extends FileSource
```

Representerar en filkälla för skapande.
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [FileCreateSource(String filePath)](#FileCreateSource-java.lang.String-) | Initierar en ny instans av klassen  FileCreateSource  . |
| [FileCreateSource(String filePath, boolean isTemporal)](#FileCreateSource-java.lang.String-boolean-) | Initierar en ny instans av klassen  FileCreateSource  . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFilePath()](#getFilePath--) | Hämtar filsökvägen att skapa. |
| [getStreamContainer()](#getStreamContainer--) | Hämtar strömbehållaren. |
| [hashCode()](#hashCode--) |  |
| [isTemporal()](#isTemporal--) | Hämtar ett värde som indikerar om filen kommer att vara temporär. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileCreateSource(String filePath) {#FileCreateSource-java.lang.String-}
```
public FileCreateSource(String filePath)
```


Initierar en ny instans av klassen  FileCreateSource  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen att skapa. |

### FileCreateSource(String filePath, boolean isTemporal) {#FileCreateSource-java.lang.String-boolean-}
```
public FileCreateSource(String filePath, boolean isTemporal)
```


Initierar en ny instans av klassen  FileCreateSource  .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filsökvägen att skapa. |
| isTemporal | boolean | Om den är inställd på  true  kommer den skapade filen att vara temporär. |

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
### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Hämtar filsökvägen att skapa.

Värde: Filsökvägen att skapa.

**Returns:**
java.lang.String
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Hämtar strömbehållaren.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - the stream container.

Använd med försiktighet. Du måste avyttra strömbehållaren efter hämtning.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Hämtar ett värde som indikerar om filen kommer att vara temporär.

Värde:  true  om filen kommer att vara temporär; annars,  false .

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

