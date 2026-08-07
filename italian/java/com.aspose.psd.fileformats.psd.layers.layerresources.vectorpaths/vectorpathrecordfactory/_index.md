---
title: "VectorPathRecordFactory"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Classe factory del record del percorso vettoriale"
type: docs
weight: 21
url: /it/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecordfactory/
---

**Inheritance:**
java.lang.Object
```
public final class VectorPathRecordFactory
```

Classe factory del record del percorso vettoriale
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [VectorPathRecordFactory()](#VectorPathRecordFactory--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [producePathRecord(byte[] data)](#producePathRecord-byte---) | Produce il record del percorso. |
| [producePathRecordSerializer_internalized(VectorPathRecord vectorPathRecord)](#producePathRecordSerializer-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord-) | Produce un discendente di VectorPathRecordSerializer a seconda del tipo di VectorPathRecord. |
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
| Parametro | Tipo | Descrizione |
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


Produce il record del percorso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati | byte[] | I dati del record. |

**Returns:**
[VectorPathRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) - Created [VectorPathRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord)
### producePathRecordSerializer_internalized(VectorPathRecord vectorPathRecord) {#producePathRecordSerializer-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord-}
```
public static VectorPathRecordSerializer producePathRecordSerializer_internalized(VectorPathRecord vectorPathRecord)
```


Produce un discendente di VectorPathRecordSerializer a seconda del tipo di VectorPathRecord.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| vectorPathRecord | [VectorPathRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) | Oggetto VectorPathRecord che dovrebbe essere serializzato. |

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.vectorpaths.serializer.VectorPathRecordSerializer - istanza di VectorPathRecordSerializer.
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

