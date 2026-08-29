---
title: "FileOpenSource"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Vertegenwoordigt een bestandbron voor openen."
type: docs
weight: 11
url: /nl/java/com.aspose.psd.sources/fileopensource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.Source](../../com.aspose.psd/source), [com.aspose.psd.sources.FileSource](../../com.aspose.psd.sources/filesource)
```
public final class FileOpenSource extends FileSource
```

Vertegenwoordigt een bestandbron voor openen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FileOpenSource(String filePath)](#FileOpenSource-java.lang.String-) | Initialiseert een nieuw exemplaar van de  FileOpenSource  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFilePath()](#getFilePath--) | Haalt het bestandspad op om te openen. |
| [getStreamContainer()](#getStreamContainer--) | Haalt de streamcontainer op. |
| [hashCode()](#hashCode--) |  |
| [isTemporal()](#isTemporal--) | Haalt een waarde op die aangeeft of het bestand tijdelijk zal zijn. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileOpenSource(String filePath) {#FileOpenSource-java.lang.String-}
```
public FileOpenSource(String filePath)
```


Initialiseert een nieuw exemplaar van de  FileOpenSource  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | java.lang.String | Het bestandspad om te openen. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt het bestandspad op om te openen.

Waarde: Het bestandspad om te openen.

**Returns:**
java.lang.String
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Haalt de streamcontainer op.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - the stream container.

Voorzichtig gebruiken. U moet de stroomcontainer na het ophalen vrijgeven.
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


Haalt een waarde op die aangeeft of het bestand tijdelijk zal zijn.

Waarde:  true  als het bestand tijdelijk zal zijn; anders,  false .

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

