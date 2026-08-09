---
title: "XmpMeta"
second_title: "Java için Aspose.PSD API Referansı"
description: "xmpmeta'yı temsil eder."
type: docs
weight: 17
url: /tr/java/com.aspose.psd.xmp/xmpmeta/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue), com.aspose.ms.System.IEquatable
```
public final class XmpMeta extends XmpElementBase implements IXmlValue, System.IEquatable<XmpElementBase>
```

xmpmeta'yı temsil eder. İsteğe bağlı. Bu öğenin amacı, RDF'nin diğer XMP dışı kullanımlarını içerebilecek genel XML metni içinde XMP meta verilerini tanımlamaktır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmpMeta(String toolkitVersion)](#XmpMeta-java.lang.String-) | XmpMeta sınıfının yeni bir örneğini başlatır. |
| [XmpMeta()](#XmpMeta--) | XmpMeta sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addAttribute(String attribute, String value)](#addAttribute-java.lang.String-java.lang.String-) | Özelliği ekler. |
| [assign_internalized(XmpElementBase xmpElement)](#assign-internalized-com.aspose.psd.xmp.XmpElementBase-) | Belirtilen XMP öğesini mevcut öğeye atar. |
| [clearAttributes()](#clearAttributes--) | Tüm özellikleri kaldırır. |
| [deepClone_internalized()](#deepClone-internalized--) | Bu örneği klonlar. |
| [equals(Object other)](#equals-java.lang.Object-) | Belirtilen  System.Object  nesnesinin bu örnek ile eşit olup olmadığını belirler. |
| [getAdobeXmpToolkit()](#getAdobeXmpToolkit--) | Adobe Xmp araç takımı sürümünü alır veya ayarlar. |
| [getAttribute(String attribute)](#getAttribute-java.lang.String-) | Özelliği alır. |
| [getClass()](#getClass--) |  |
| [getXmlValue()](#getXmlValue--) | XMP değerini XML temsiline dönüştürür. |
| [hashCode()](#hashCode--) | Bu örnek için bir karma kodu döndürür. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | Geçerli nesnenin aynı türdeki başka bir nesneye eşit olup olmadığını gösterir. |
| [isEquals(XmpMeta other)](#isEquals-com.aspose.psd.xmp.XmpMeta-) | Geçerli nesnenin aynı türdeki başka bir nesneye eşit olup olmadığını gösterir. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdobeXmpToolkit(String value)](#setAdobeXmpToolkit-java.lang.String-) | Adobe Xmp araç takımı sürümünü alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpMeta(String toolkitVersion) {#XmpMeta-java.lang.String-}
```
public XmpMeta(String toolkitVersion)
```


XmpMeta sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| toolkitVersion | java.lang.String | Adobe XMP araç takımı sürümü. |

### XmpMeta() {#XmpMeta--}
```
public XmpMeta()
```


XmpMeta sınıfının yeni bir örneğini başlatır.

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
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Belirtilen  System.Object  nesnesinin bu örnek ile eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| diğer | java.lang.Object | Bu örnek ile karşılaştırılacak System.Object. |

**Returns:**
boolean - belirtilen System.Object bu örnek ile eşitse true; aksi takdirde false.
### getAdobeXmpToolkit() {#getAdobeXmpToolkit--}
```
public String getAdobeXmpToolkit()
```


Adobe Xmp araç takımı sürümünü alır veya ayarlar.

**Returns:**
java.lang.String
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
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


XMP değerini XML temsiline dönüştürür.

**Returns:**
java.lang.String - XMP değerini XML temsiline dönüştürülmüş olarak döndürür.
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
### isEquals(XmpMeta other) {#isEquals-com.aspose.psd.xmp.XmpMeta-}
```
public boolean isEquals(XmpMeta other)
```


Geçerli nesnenin aynı türdeki başka bir nesneye eşit olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | Bu nesne ile karşılaştırılacak bir nesne. |

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




### setAdobeXmpToolkit(String value) {#setAdobeXmpToolkit-java.lang.String-}
```
public void setAdobeXmpToolkit(String value)
```


Adobe Xmp araç takımı sürümünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

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

