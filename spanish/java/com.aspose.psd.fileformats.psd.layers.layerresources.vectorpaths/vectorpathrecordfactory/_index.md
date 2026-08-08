---
title: "VectorPathRecordFactory"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Clase fábrica de registro de ruta vectorial"
type: docs
weight: 21
url: /es/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecordfactory/
---

**Inheritance:**
java.lang.Object
```
public final class VectorPathRecordFactory
```

Clase fábrica de registro de ruta vectorial
## Constructores

| Constructor | Descripción |
| --- | --- |
| [VectorPathRecordFactory()](#VectorPathRecordFactory--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [producePathRecord(byte[] data)](#producePathRecord-byte---) | Produce el registro de ruta. |
| [producePathRecordSerializer_internalized(VectorPathRecord vectorPathRecord)](#producePathRecordSerializer-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord-) | Produce una subclase de VectorPathRecordSerializer según el tipo de VectorPathRecord. |
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
| Parámetro | Tipo | Descripción |
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


Produce el registro de ruta.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| data | byte[] | Los datos del registro. |

**Returns:**
[VectorPathRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) - Created [VectorPathRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord)
### producePathRecordSerializer_internalized(VectorPathRecord vectorPathRecord) {#producePathRecordSerializer-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord-}
```
public static VectorPathRecordSerializer producePathRecordSerializer_internalized(VectorPathRecord vectorPathRecord)
```


Produce una subclase de VectorPathRecordSerializer según el tipo de VectorPathRecord.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| vectorPathRecord | [VectorPathRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) | Objeto VectorPathRecord que debe serializarse. |

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.vectorpaths.serializer.VectorPathRecordSerializer - instancia de VectorPathRecordSerializer.
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

