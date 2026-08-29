---
title: "XmpElementBase"
second_title: "Java için Aspose.PSD API Referansı"
description: "Temel xmp öğesinin özniteliklerini temsil eder."
type: docs
weight: 15
url: /tr/java/com.aspose.psd.xmp/xmpelementbase/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class XmpElementBase implements System.IEquatable<XmpElementBase>
```

Temel xmp öğesinin özniteliklerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Özelliği ekler. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | Belirtilen XMP öğesini mevcut öğeye atar. |
| [clearAttributes()](#clearAttributes--) | Tüm özellikleri kaldırır. |
| [deepClone_internalized()](#deepClone-internalized--) | Bu örneği klonlar. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen  Object  nesnesinin bu örnek ile eşit olup olmadığını belirler. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Özelliği alır. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) | Bu örnek için bir karma kodu döndürür. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | Geçerli nesnenin aynı türdeki başka bir nesneye eşit olup olmadığını gösterir. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addAttribute(String attribute, String value) {#addAttribute-java.lang.String-java.lang.String-}
```
public void addAttribute(String attribute, String value)
```


Özelliği ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| attribute | java.lang.String | Özellik. |
| değer | java.lang.String | Değer. |

### assign_internalized(XmpElementBase xmpElement) {#assign-internalized-com.aspose.psd.xmp.XmpElementBase-}
```
public void assign_internalized(XmpElementBase xmpElement)
```


Belirtilen XMP öğesini mevcut öğeye atar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| xmpElement | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | XMP öğesi. |

### clearAttributes() {#clearAttributes--}
```
public void clearAttributes()
```


Tüm özellikleri kaldırır.

### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpElementBase deepClone_internalized()
```


Bu örneği klonlar.

**Returns:**
[XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) - The cloned object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen  Object  nesnesinin bu örnek ile eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Bu örnek ile karşılaştırılacak  Object  nesnesi. |

**Returns:**
boolean -  true  eğer belirtilen  Object  bu örnek ile eşitse; aksi takdirde,  false .
### getAttribute(String attribute) {#getAttribute-java.lang.String-}
```
public String getAttribute(String attribute)
```


Özelliği alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| attribute | java.lang.String | Özellik. |

**Returns:**
java.lang.String - Belirtilen özellik adı için özelliği döndürür.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu örnek için bir karma kodu döndürür.

**Returns:**
int - Bu örnek için bir karma kodu, hash algoritmaları ve hash tablosu gibi veri yapılarında kullanılmaya uygun.
### isEquals(XmpElementBase other) {#isEquals-com.aspose.psd.xmp.XmpElementBase-}
```
public boolean isEquals(XmpElementBase other)
```


Geçerli nesnenin aynı türdeki başka bir nesneye eşit olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase) | Bu nesne ile karşılaştırılacak bir nesne. |

**Returns:**
boolean - geçerli nesne diğer parametreye eşitse true; aksi takdirde false.
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

