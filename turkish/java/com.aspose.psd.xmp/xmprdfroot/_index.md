---
title: "XmpRdfRoot"
second_title: "Java için Aspose.PSD API Referansı"
description: "rdfRDF öğesini temsil eder."
type: docs
weight: 21
url: /tr/java/com.aspose.psd.xmp/xmprdfroot/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.XmpElementBase](../../com.aspose.psd.xmp/xmpelementbase)

**All Implemented Interfaces:**
[com.aspose.psd.xmp.IXmlValue](../../com.aspose.psd.xmp/ixmlvalue)
```
public final class XmpRdfRoot extends XmpElementBase implements IXmlValue
```

rdf:RDF öğesini temsil eder. Tek bir XMP paketi, tek bir rdf:RDF XML öğesi kullanılarak serileştirilecektir. rdf:RDF öğesi içeriği yalnızca sıfır veya daha fazla rdf:Description öğesinden oluşacaktır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [XmpRdfRoot()](#XmpRdfRoot--) | XmpRdfRoot sınıfının yeni bir örneğini başlatır. |
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
| [getNamespaceUri(String prefix)](#getNamespaceUri-java.lang.String-) | Belirli bir önek ile ad alanı URI'sini alır. |
| [getXmlValue()](#getXmlValue--) | xmp değerini xml temsiline dönüştürür. |
| [hashCode()](#hashCode--) | Bu örnek için bir karma kodu döndürür. |
| [isEquals(XmpElementBase other)](#isEquals-com.aspose.psd.xmp.XmpElementBase-) | Geçerli nesnenin aynı türdeki başka bir nesneye eşit olup olmadığını gösterir. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerNamespaceUri(String prefix, String namespaceUri)](#registerNamespaceUri-java.lang.String-java.lang.String-) | Önek ile ad alanı URI'si ekler. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpRdfRoot() {#XmpRdfRoot--}
```
public XmpRdfRoot()
```


XmpRdfRoot sınıfının yeni bir örneğini başlatır.

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
### getNamespaceUri(String prefix) {#getNamespaceUri-java.lang.String-}
```
public String getNamespaceUri(String prefix)
```


Belirli bir önek ile ad alanı URI'sini alır. Önek, xmlns olmadan başlayabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | java.lang.String | Önek. |

**Returns:**
java.lang.String - Bir paket şema URI'si döndürür.
### getXmlValue() {#getXmlValue--}
```
public String getXmlValue()
```


xmp değerini xml temsiline dönüştürür.

**Returns:**
java.lang.String - XMP değerini XML dizesine dönüştürülmüş olarak döndürür.
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




### registerNamespaceUri(String prefix, String namespaceUri) {#registerNamespaceUri-java.lang.String-java.lang.String-}
```
public void registerNamespaceUri(String prefix, String namespaceUri)
```


Önek ile ad alanı URI'si ekler. Önek, xmlns olmadan başlayabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | java.lang.String | Önek. |
| namespaceUri | java.lang.String | Paket şema URI'si. |

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

