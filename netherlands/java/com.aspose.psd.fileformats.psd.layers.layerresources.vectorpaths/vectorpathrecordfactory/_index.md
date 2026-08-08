---
title: "VectorPathRecordFactory"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Vector‑pad‑record‑fabriek‑klasse"
type: docs
weight: 21
url: /nl/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecordfactory/
---

**Inheritance:**
java.lang.Object
```
public final class VectorPathRecordFactory
```

Vector‑pad‑record‑fabriek‑klasse
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [VectorPathRecordFactory()](#VectorPathRecordFactory--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [producePathRecord(byte[] data)](#producePathRecord-byte---) | Produceert het padrecord. |
| [producePathRecordSerializer_internalized(VectorPathRecord vectorPathRecord)](#producePathRecordSerializer-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord-) | Produceert een VectorPathRecordSerializer-afstammeling afhankelijk van het type VectorPathRecord. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorPathRecordFactory() {#VectorPathRecordFactory--}
```
public VectorPathRecordFactory()
```


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




### producePathRecord(byte[] data) {#producePathRecord-byte---}
```
public static VectorPathRecord producePathRecord(byte[] data)
```


Produceert het padrecord.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gegevens | byte[] | De recordgegevens. |

**Returns:**
[VectorPathRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) - Created [VectorPathRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord)
### producePathRecordSerializer_internalized(VectorPathRecord vectorPathRecord) {#producePathRecordSerializer-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord-}
```
public static VectorPathRecordSerializer producePathRecordSerializer_internalized(VectorPathRecord vectorPathRecord)
```


Produceert een VectorPathRecordSerializer-afstammeling afhankelijk van het type VectorPathRecord.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vectorPathRecord | [VectorPathRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) | VectorPathRecord-object dat geserialiseerd moet worden. |

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.vectorpaths.serializer.VectorPathRecordSerializer - VectorPathRecordSerializer instantie.
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

