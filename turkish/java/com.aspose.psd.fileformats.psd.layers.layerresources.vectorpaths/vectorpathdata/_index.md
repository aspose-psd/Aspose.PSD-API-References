---
title: "VectorPathData"
second_title: "Java için Aspose.PSD API Referansı"
description: "Bir vektör yolu ile çalışmak için sınıf."
type: docs
weight: 18
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IVectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ivectorpathdata)
```
public final class VectorPathData implements IVectorPathData
```

Bir vektör yolu ile çalışmak için sınıf.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [VectorPathData(byte[] data)](#VectorPathData-byte---) | Yeni bir [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) sınıfının örneğini başlatır. |
| [VectorPathData()](#VectorPathData--) | Yeni bir [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) sınıfının örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [SizeOfTheGeneralInfo_internalized](#SizeOfTheGeneralInfo-internalized) | Sürüm ve bayraklar gibi genel bilgilerin boyutu. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAsByteArray_internalized()](#getAsByteArray-internalized--) | Byte dizisi olarak alır. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Kaynak içindeki vektör yol verisi uzunluğunu bayt olarak alır. |
| [getPaths()](#getPaths--) | Yol kayıtlarını alır veya ayarlar. |
| [getVersion()](#getVersion--) | Sürümü alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | Bu örneğin devre dışı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [isInverted()](#isInverted--) | Bu örneğin ters çevrilmiş olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [isNotLinked()](#isNotLinked--) | Bu örneğin bağlanmamış olduğunu gösteren bir değeri alır veya ayarlar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDisabled(boolean value)](#setDisabled-boolean-) | Bu örneğin devre dışı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setInverted(boolean value)](#setInverted-boolean-) | Bu örneğin ters çevrilmiş olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | Bu örneğin bağlanmamış olduğunu gösteren bir değeri alır veya ayarlar. |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | Yol kayıtlarını alır veya ayarlar. |
| [setVersion(int value)](#setVersion-int-) | Sürümü alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorPathData(byte[] data) {#VectorPathData-byte---}
```
public VectorPathData(byte[] data)
```


Yeni bir [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| veri | byte[] | Kaynak verisi. |

### VectorPathData() {#VectorPathData--}
```
public VectorPathData()
```


Yeni bir [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) sınıfının örneğini başlatır.

### SizeOfTheGeneralInfo_internalized {#SizeOfTheGeneralInfo-internalized}
```
public static final int SizeOfTheGeneralInfo_internalized
```


Sürüm ve bayraklar gibi genel bilgilerin boyutu.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAsByteArray_internalized() {#getAsByteArray-internalized--}
```
public final byte[] getAsByteArray_internalized()
```


Byte dizisi olarak alır.

**Returns:**
byte[] - Kaynak byte dizisi olarak.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public final int getLength()
```


Kaynak içindeki vektör yol verisi uzunluğunu bayt olarak alır.

**Returns:**
int
### getPaths() {#getPaths--}
```
public final VectorPathRecord[] getPaths()
```


Yol kayıtlarını alır veya ayarlar.

Değer: Yollar.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Sürümü alır veya ayarlar.

Değer: Sürüm.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDisabled() {#isDisabled--}
```
public final boolean isDisabled()
```


Bu örneğin devre dışı olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  bu örnek devre dışıysa; aksi takdirde,  false .

**Returns:**
boolean
### isInverted() {#isInverted--}
```
public final boolean isInverted()
```


Bu örneğin ters çevrilmiş olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  bu örnek ters çevrilmişse; aksi takdirde,  false .

**Returns:**
boolean
### isNotLinked() {#isNotLinked--}
```
public final boolean isNotLinked()
```


Bu örneğin bağlanmamış olduğunu gösteren bir değeri alır veya ayarlar.

Değer:  true  bu örnek bağlı değilse; aksi takdirde,  false .

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




### setDisabled(boolean value) {#setDisabled-boolean-}
```
public final void setDisabled(boolean value)
```


Bu örneğin devre dışı olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  bu örnek devre dışıysa; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setInverted(boolean value) {#setInverted-boolean-}
```
public final void setInverted(boolean value)
```


Bu örneğin ters çevrilmiş olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  bu örnek ters çevrilmişse; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public final void setNotLinked(boolean value)
```


Bu örneğin bağlanmamış olduğunu gösteren bir değeri alır veya ayarlar.

Değer:  true  bu örnek bağlı değilse; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setPaths(VectorPathRecord[] value) {#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---}
```
public final void setPaths(VectorPathRecord[] value)
```


Yol kayıtlarını alır veya ayarlar.

Değer: Yollar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [VectorPathRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Sürümü alır veya ayarlar.

Değer: Sürüm.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

