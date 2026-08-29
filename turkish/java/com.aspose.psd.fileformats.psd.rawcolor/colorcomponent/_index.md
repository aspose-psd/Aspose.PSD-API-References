---
title: "ColorComponent"
second_title: "Java için Aspose.PSD API Referansı"
description: "Renk bileşeni, Kanal Değeri ve Kanal Değeri üzerine bir soyutlamadır."
type: docs
weight: 10
url: /tr/java/com.aspose.psd.fileformats.psd.rawcolor/colorcomponent/
---

**Inheritance:**
java.lang.Object
```
public final class ColorComponent
```

Renk bileşeni, Channel Value ve Channel Value üzerine bir soyutlamadır. Her renk, bir ColorComponent dizisinden oluşur.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ColorComponent(byte bitDepth, String fullName)](#ColorComponent-byte-java.lang.String-) | Yeni bir [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth()](#getBitDepth--) | Color Component/Channel'ın bit derinliğini alır |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Color Component'ın açıklamasını alır |
| [getFullName()](#getFullName--) | İsim ve boşlukla ayrılmış açıklama ile renk bileşeninin tam adını alır |
| [getName()](#getName--) | Renk bileşeninin adını alır. |
| [getPermittedFullNames()](#getPermittedFullNames--) | İzin verilen tam adları alır. |
| [getValue()](#getValue--) | Değeri alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(long value)](#setValue-long-) | Değeri alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorComponent(byte bitDepth, String fullName) {#ColorComponent-byte-java.lang.String-}
```
public ColorComponent(byte bitDepth, String fullName)
```


Yeni bir [ColorComponent](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) sınıfı örneği başlatır. Lütfen kontrol edin

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bitDepth | byte | Bit derinliği. |
| fullName | java.lang.String | Tam ad. |

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
### getBitDepth() {#getBitDepth--}
```
public final byte getBitDepth()
```


Color Component/Channel'ın bit derinliğini alır

Değer: Bit derinliği.

**Returns:**
byte
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Color Component'ın açıklamasını alır

Değer: Açıklama.

**Returns:**
java.lang.String
### getFullName() {#getFullName--}
```
public final String getFullName()
```


İsim ve boşlukla ayrılmış açıklama ile renk bileşeninin tam adını alır

Değer: Tam ad.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public final String getName()
```


Renk bileşeninin adını alır.

Değer: Ad.

**Returns:**
java.lang.String
### getPermittedFullNames() {#getPermittedFullNames--}
```
public static String[] getPermittedFullNames()
```


İzin verilen tam adları alır.

Değer: İzin verilen tam adlar.

**Returns:**
java.lang.String[]
### getValue() {#getValue--}
```
public final long getValue()
```


Değeri alır veya ayarlar. Lütfen unutmayın, değeri mevcut bit derinliğinde saklanabilecekten daha yüksek bir değere ayarlamaya çalışırsanız bir istisna alırsınız.

Değer: Değer.

**Returns:**
long
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




### setValue(long value) {#setValue-long-}
```
public final void setValue(long value)
```


Değeri alır veya ayarlar. Lütfen unutmayın, değeri mevcut bit derinliğinde saklanabilecekten daha yüksek bir değere ayarlamaya çalışırsanız bir istisna alırsınız.

Değer: Değer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

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

