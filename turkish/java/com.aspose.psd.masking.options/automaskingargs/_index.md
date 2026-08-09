---
title: "AutoMaskingArgs"
second_title: "Java için Aspose.PSD API Referansı"
description: "Otomatik maskeleme yöntemleri için belirtilen argümanları temsil eder"
type: docs
weight: 11
url: /tr/java/com.aspose.psd.masking.options/automaskingargs/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.masking.options.IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

Otomatik maskeleme yöntemleri için belirtilen argümanları temsil eder
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | Maksimum yineleme sayısını alır. |
| [getNumberOfObjects()](#getNumberOfObjects--) | İlk görüntüyü ayırmak için nesne sayısını alır (isteğe bağlı), varsayılan değer 2'dir (nesne ve arka plan). |
| [getObjectsPoints()](#getObjectsPoints--) | Ayrılmış nesnelere ait noktaları alır (isteğe bağlı) NumberOfObjects koordinatları, ilk görüntünün NumberOfObjects nesnesine aittir. |
| [getObjectsRectangles()](#getObjectsRectangles--) | Ayrılmış nesnelere ait nesne dikdörtgenlerini alır (isteğe bağlı). |
| [getOrphanedPoints()](#getOrphanedPoints--) | Artık herhangi bir nesneye ait olmayan noktaları alır (isteğe bağlı). |
| [getPrecision()](#getPrecision--) | Segmentasyon yönteminin hassasiyetini alır (isteğe bağlı). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | Maksimum yineleme sayısını ayarlar. |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | İlk görüntüyü ayırmak için nesne sayısını ayarlar (isteğe bağlı), varsayılan değer 2'dir (nesne ve arka plan). |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.psd.Point-----) | Ayrılmış nesnelere ait noktaları ayarlar (isteğe bağlı) NumberOfObjects koordinatları, ilk görüntünün NumberOfObjects nesnesine aittir. |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.psd.Rectangle---) | Ayrılmış nesnelere ait nesne dikdörtgenlerini ayarlar (isteğe bağlı). |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.psd.Point---) | Artık herhangi bir nesneye ait olmayan noktaları ayarlar (isteğe bağlı). |
| [setPrecision(double value)](#setPrecision-double-) | Segmentasyon yönteminin hassasiyetini ayarlar (isteğe bağlı). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingArgs() {#AutoMaskingArgs--}
```
public AutoMaskingArgs()
```


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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


Maksimum yineleme sayısını alır.

Değer: Maksimum yineleme sayısı.

**Returns:**
int - maksimum yineleme sayısı.
### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


İlk görüntüyü ayırmak için nesne sayısını alır (isteğe bağlı), varsayılan değer 2'dir (nesne ve arka plan).

Değer: Nesne sayısı.

**Returns:**
int - ilk görüntüyü ayırmak için nesne sayısı (isteğe bağlı), varsayılan değer 2'dir (nesne ve arka plan).
### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


Ayrılmış nesnelere ait noktaları alır (isteğe bağlı) NumberOfObjects koordinatları, ilk görüntünün NumberOfObjects nesnesine aittir. Bu parametre, segmentasyon yöntemi hassasiyetini artırmak için kullanılır.

Değer: Nesne noktaları.

**Returns:**
com.aspose.psd.Point[][] - ayrılmış nesnelere ait noktalar (isteğe bağlı) NumberOfObjects koordinatları, ilk görüntünün NumberOfObjects nesnesine aittir.
### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


Ayrılmış nesnelere ait nesne dikdörtgenlerini alır (isteğe bağlı). Bu parametre, segmentasyon yöntemi hassasiyetini artırmak için kullanılır.

Değer: Nesne dikdörtgenleri.

**Returns:**
com.aspose.psd.Rectangle[] - ayrılmış nesnelere ait nesne dikdörtgenleri (isteğe bağlı).
### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


Herhangi bir nesneye artık ait olmayan noktaları alır (isteğe bağlı). Bu parametre yalnızca yeniden segmentasyon durumunda kullanılır.

Değer: Yetim noktalar.

**Returns:**
com.aspose.psd.Point[] - artık herhangi bir nesneye ait olmayan noktalar (isteğe bağlı).
### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


Segmentasyon yönteminin hassasiyetini alır (isteğe bağlı).

Değer: Segmentasyon yönteminin hassasiyeti (isteğe bağlı).

**Returns:**
double - segmentasyon yönteminin hassasiyeti (isteğe bağlı).
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




### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


Maksimum yineleme sayısını ayarlar.

Değer: Maksimum yineleme sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | azami yineleme sayısı. |

### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


İlk görüntüyü ayırmak için nesne sayısını ayarlar (isteğe bağlı), varsayılan değer 2'dir (nesne ve arka plan).

Değer: Nesne sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | başlangıç görüntüsünü ayırmak için nesne sayısı (isteğe bağlı), varsayılan değer 2'dir (nesne ve arka plan). |

### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.psd.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


Ayrılmış nesnelere ait noktaları ayarlar (isteğe bağlı) NumberOfObjects koordinatları, başlangıç görüntüsünün NumberOfObjects nesnesine aittir. Bu parametre segmentasyon yöntemi hassasiyetini artırmak için kullanılır.

Değer: Nesne noktaları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | Ayrılmış nesnelere ait noktalar (isteğe bağlı) NumberOfObjects koordinatları, başlangıç görüntüsünün NumberOfObjects nesnesine aittir. |

### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.psd.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


Ayrılmış nesnelere ait nesne dikdörtgenlerini ayarlar (isteğe bağlı). Bu parametre segmentasyon yöntemi hassasiyetini artırmak için kullanılır.

Değer: Nesne dikdörtgenleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | Ayrılmış nesnelere ait nesne dikdörtgenleri (isteğe bağlı). |

### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.psd.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


Herhangi bir nesneye artık ait olmayan noktaları ayarlar (isteğe bağlı). Bu parametre yalnızca yeniden segmentasyon durumunda kullanılır.

Değer: Yetim noktalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | Artık herhangi bir nesneye ait olmayan noktalar (isteğe bağlı). |

### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


Segmentasyon yönteminin hassasiyetini ayarlar (isteğe bağlı).

Değer: Segmentasyon yönteminin hassasiyeti (isteğe bağlı).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Segmentasyon yönteminin hassasiyeti (isteğe bağlı). |

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

