---
title: "ResourceEvent"
second_title: "Java için Aspose.PSD API Referansı"
description: "Çizilen nesne için boyutları içerir."
type: docs
weight: 10
url: /tr/java/com.aspose.psd.xmp.types.complex.resourceevent/resourceevent/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class ResourceEvent extends ComplexTypeBase
```

Çizilen nesne için boyutları içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ResourceEvent()](#ResourceEvent--) | Yeni bir  ResourceEvent  sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Belirtilen anahtarı ekler. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAction()](#getAction--) | Eylemi alır. |
| [getActionDate()](#getActionDate--) | Eylem tarihini alır veya ayarlar. |
| [getChanged()](#getChanged--) | Önceki olay geçmişinden bu yana değiştirilen kaynağın bölümlerinin noktalı virgül ile ayrılmış listesini alır. |
| [getClass()](#getClass--) |  |
| [getInstanceId()](#getInstanceId--) | xmpMM:InstanceId değerini alır. |
| [getNamespaceUri()](#getNamespaceUri--) | Varsayılan ad alanı URI'sını alır. |
| [getParameters()](#getParameters--) | Eylemin ek açıklamasını alır veya ayarlar. |
| [getPrefix()](#getPrefix--) | Ön eki alır. |
| [getSofwareAgentName()](#getSofwareAgentName--) | Yazılım ajanının adını alır veya ayarlar. |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP formatında içerilen dize değerini alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAction(String value)](#setAction-java.lang.String-) | Eylemi ayarlar. |
| [setActionDate(Date value)](#setActionDate-java.util.Date-) | Eylem tarihini alır veya ayarlar. |
| [setChanged(String value)](#setChanged-java.lang.String-) | Önceki olay geçmişinden bu yana değiştirilen kaynağın bölümlerinin noktalı virgül ile ayrılmış listesini ayarlar. |
| [setInstanceId(UUID value)](#setInstanceId-java.util.UUID-) | xmpMM:InstanceId değerini alır veya ayarlar. |
| [setParameters(String value)](#setParameters-java.lang.String-) | Eylemin ek açıklamasını alır veya ayarlar. |
| [setSofwareAgentName(String value)](#setSofwareAgentName-java.lang.String-) | Yazılım ajanının adını alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ResourceEvent() {#ResourceEvent--}
```
public ResourceEvent()
```


Yeni bir  ResourceEvent  sınıfının örneğini başlatır.

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Belirtilen anahtarı ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Eklenen değerle tanımlanan anahtarın dize temsili. |
| değer | java.lang.Object | Eklenecek değer. |

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
### getAction() {#getAction--}
```
public String getAction()
```


Eylemi alır.

Tanımlı değerler: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Yeni değerler geçmiş zaman kipinde fiil olmalıdır.

**Returns:**
java.lang.String - Eylem.
### getActionDate() {#getActionDate--}
```
public Date getActionDate()
```


Eylem tarihini alır veya ayarlar.

**Returns:**
java.util.Date - Eylem tarihi.
### getChanged() {#getChanged--}
```
public String getChanged()
```


Önceki olay geçmişinden bu yana değiştirilen kaynağın bölümlerinin noktalı virgül ile ayrılmış listesini alır.

**Returns:**
java.lang.String - Önceki olay geçmişinden bu yana değiştirilen kaynağın bölümlerinin noktalı virgül ile ayrılmış listesi.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getInstanceId() {#getInstanceId--}
```
public UUID getInstanceId()
```


xmpMM:InstanceId değerini alır.

**Returns:**
java.util.UUID - xmpMM:InstanceId değerini.
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Varsayılan ad alanı URI'sını alır.

**Returns:**
java.lang.String - Varsayılan ad alanı URI'si.
### getParameters() {#getParameters--}
```
public String getParameters()
```


Eylemin ek açıklamasını alır veya ayarlar.

Değer: Eylemin ek açıklaması.

**Returns:**
java.lang.String
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Ön eki alır.

**Returns:**
java.lang.String - Önek.
### getSofwareAgentName() {#getSofwareAgentName--}
```
public String getSofwareAgentName()
```


Yazılım ajanının adını alır veya ayarlar.

**Returns:**
java.lang.String - Yazılım ajanının adı.
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


XMP formatında içerilen dize değerini alır.

**Returns:**
java.lang.String - XMP formatında içerilen dize değerini döndürür.
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




### setAction(String value) {#setAction-java.lang.String-}
```
public void setAction(String value)
```


Eylemi ayarlar.

Tanımlı değerler: converted, copied, created, cropped, edited, filtered, formatted, version\_updated, printed, published, managed, produced, resized, saved. Yeni değerler geçmiş zaman kipinde fiil olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Eylem. |

### setActionDate(Date value) {#setActionDate-java.util.Date-}
```
public void setActionDate(Date value)
```


Eylem tarihini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date | Eylem tarihi. |

### setChanged(String value) {#setChanged-java.lang.String-}
```
public void setChanged(String value)
```


Önceki olay geçmişinden bu yana değiştirilen kaynağın bölümlerinin noktalı virgül ile ayrılmış listesini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Önceki olay geçmişinden bu yana değiştirilen kaynağın bölümlerinin noktalı virgül ile ayrılmış listesi. |

### setInstanceId(UUID value) {#setInstanceId-java.util.UUID-}
```
public void setInstanceId(UUID value)
```


xmpMM:InstanceId değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.UUID | xmpMM:InstanceId'in değeri. |

### setParameters(String value) {#setParameters-java.lang.String-}
```
public void setParameters(String value)
```


Eylemin ek açıklamasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Eylemin ek açıklaması. |

### setSofwareAgentName(String value) {#setSofwareAgentName-java.lang.String-}
```
public void setSofwareAgentName(String value)
```


Yazılım ajanının adını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yazılım ajanı adı. |

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

