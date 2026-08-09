---
title: "CurvesDiscreteManager"
second_title: "Java için Aspose.PSD API Referansı"
description: "Piksel haritasını manipüle eden Curves Adjustment Layer yöneticisi"
type: docs
weight: 25
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.CurvesManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesmanager)
```
public final class CurvesDiscreteManager extends CurvesManager
```

Eğriler Ayarlama Katmanı için piksel haritasını yöneten yönetici
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CurvesDiscreteManager(int maxChannelCount)](#CurvesDiscreteManager-int-) | Yeni bir [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager) sınıf örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBytesForResource_internalized()](#getBytesForResource-internalized--) | Kaynak için baytları alır. |
| [getClass()](#getClass--) |  |
| [getMap_internalized()](#getMap-internalized--) | Filtre işleme için haritayı alır. |
| [getMaxChannelCount()](#getMaxChannelCount--) | Azami kanal sayısını alır. |
| [getValueInPosition(int channelIndex, byte position)](#getValueInPosition-int-byte-) | Pozisyondaki değeri alır. |
| [hashCode()](#hashCode--) |  |
| [loadFromBytes_internalized(byte[] bytes)](#loadFromBytes-internalized-byte---) | Verileri baytlardan yükler. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setToDefaultValueInPosition(int channelIndex, byte position)](#setToDefaultValueInPosition-int-byte-) | Pozisyondaki değeri varsayılan değere ayarlar. |
| [setValueInPosition(int channelIndex, byte position, byte value)](#setValueInPosition-int-byte-byte-) | Pozisyondaki değeri ayarlar. |
| [setValueOfWholeChannel(int channelIndex, byte[] channelValue)](#setValueOfWholeChannel-int-byte---) | Tüm kanalın değerini ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CurvesDiscreteManager(int maxChannelCount) {#CurvesDiscreteManager-int-}
```
public CurvesDiscreteManager(int maxChannelCount)
```


Yeni bir [CurvesDiscreteManager](../../com.aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager) sınıf örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| maxChannelCount | int | Maksimum kanal sayısı. |

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
### getBytesForResource_internalized() {#getBytesForResource-internalized--}
```
public final byte[] getBytesForResource_internalized()
```


Kaynak için baytları alır.

**Returns:**
byte[] - CurvResource oluşturmak için baytlar
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMap_internalized() {#getMap-internalized--}
```
public byte[][] getMap_internalized()
```


Filtre işleme için haritayı alır.

**Returns:**
byte[][] - Dönüşüm haritası
### getMaxChannelCount() {#getMaxChannelCount--}
```
public final int getMaxChannelCount()
```


Azami kanal sayısını alır.

Değer: Maksimum kanal sayısı.

**Returns:**
int
### getValueInPosition(int channelIndex, byte position) {#getValueInPosition-int-byte-}
```
public final byte getValueInPosition(int channelIndex, byte position)
```


Pozisyondaki değeri alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| channelIndex | int | Kanalın indeksi. |
| position | byte | Konum. |

**Returns:**
byte - Eğrinin konumuna göre değeri
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadFromBytes_internalized(byte[] bytes) {#loadFromBytes-internalized-byte---}
```
public void loadFromBytes_internalized(byte[] bytes)
```


Verileri baytlardan yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baytlar | byte[] | Baytlar. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setToDefaultValueInPosition(int channelIndex, byte position) {#setToDefaultValueInPosition-int-byte-}
```
public final void setToDefaultValueInPosition(int channelIndex, byte position)
```


Pozisyondaki değeri varsayılan değere ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| channelIndex | int | Kanalın indeksi. |
| position | byte | Konum. |

### setValueInPosition(int channelIndex, byte position, byte value) {#setValueInPosition-int-byte-byte-}
```
public final void setValueInPosition(int channelIndex, byte position, byte value)
```


Pozisyondaki değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| channelIndex | int | Kanalın indeksi. |
| position | byte | Konum. |
| değer | byte | Değer. |

### setValueOfWholeChannel(int channelIndex, byte[] channelValue) {#setValueOfWholeChannel-int-byte---}
```
public final void setValueOfWholeChannel(int channelIndex, byte[] channelValue)
```


Tüm kanalın değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| channelIndex | int | Kanalın indeksi. |
| channelValue | byte[] | Kanal değeri. |

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

