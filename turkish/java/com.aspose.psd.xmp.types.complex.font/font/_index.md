---
title: "Yazı tipi"
second_title: "Java için Aspose.PSD API Referansı"
description: "XMP Yazı tipini temsil eder."
type: docs
weight: 10
url: /tr/java/com.aspose.psd.xmp.types.complex.font/font/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class Font extends ComplexTypeBase
```

XMP Yazı tipini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Font()](#Font--) | Font sınıfının yeni bir örneğini başlatır. |
| [Font(String fontFamily)](#Font-java.lang.String-) | Font sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Belirtilen anahtarı ekler. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChildFontFiles()](#getChildFontFiles--) | Bileşik bir yazı tipini oluşturan yazı tiplerinin dosya adı dizisini alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getFontFace()](#getFontFace--) | Yazı tipi yüzünü alır veya ayarlar. |
| [getFontFamily()](#getFontFamily--) | Yazı tipi ailesini alır veya ayarlar. |
| [getFontFileName()](#getFontFileName--) | Tam yol olmadan yazı tipi dosya adını alır veya ayarlar. |
| [getFontName()](#getFontName--) | PostScript yazı tipi adını alır veya ayarlar. |
| [getFontType()](#getFontType--) | Yazı tipi türünü alır veya ayarlar. |
| [getNamespaceUri()](#getNamespaceUri--) | Varsayılan ad alanı URI'sını alır. |
| [getPrefix()](#getPrefix--) | Ön eki alır. |
| [getVersion()](#getVersion--) | Yazı tipi sürümünü alır veya ayarlar. |
| [getXmpRepresentation()](#getXmpRepresentation--) | XMP formatında içerilen dize değerini alır. |
| [hashCode()](#hashCode--) |  |
| [isComposite()](#isComposite--) | Bu yazı tipinin bileşik olup olmadığını gösteren değeri alır veya ayarlar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChildFontFiles(String[] value)](#setChildFontFiles-java.lang.String---) | Bileşik bir yazı tipini oluşturan yazı tiplerinin dosya adı dizisini alır veya ayarlar. |
| [setComposite(boolean value)](#setComposite-boolean-) | Bu yazı tipinin bileşik olup olmadığını gösteren değeri alır veya ayarlar. |
| [setFontFace(String value)](#setFontFace-java.lang.String-) | Yazı tipi yüzünü alır veya ayarlar. |
| [setFontFamily(String value)](#setFontFamily-java.lang.String-) | Yazı tipi ailesini alır veya ayarlar. |
| [setFontFileName(String value)](#setFontFileName-java.lang.String-) | Tam yol olmadan yazı tipi dosya adını alır veya ayarlar. |
| [setFontName(String value)](#setFontName-java.lang.String-) | PostScript yazı tipi adını alır veya ayarlar. |
| [setFontType(String value)](#setFontType-java.lang.String-) | Yazı tipi türünü alır veya ayarlar. |
| [setVersion(String value)](#setVersion-java.lang.String-) | Yazı tipi sürümünü alır veya ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font() {#Font--}
```
public Font()
```


Font sınıfının yeni bir örneğini başlatır.

### Font(String fontFamily) {#Font-java.lang.String-}
```
public Font(String fontFamily)
```


Font sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontFamily | java.lang.String | Yazı tipi ailesi. |

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
### getChildFontFiles() {#getChildFontFiles--}
```
public String[] getChildFontFiles()
```


Bileşik bir yazı tipini oluşturan yazı tiplerinin dosya adı dizisini alır veya ayarlar.

Değer: Bir birleşik yazı tipini oluşturan yazı tiplerinin dosya adı dizisi.

**Returns:**
java.lang.String[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFontFace() {#getFontFace--}
```
public String getFontFace()
```


Yazı tipi yüzünü alır veya ayarlar.

Değer: Yazı tipi yüzü.

**Returns:**
java.lang.String
### getFontFamily() {#getFontFamily--}
```
public String getFontFamily()
```


Yazı tipi ailesini alır veya ayarlar.

Değer: Yazı tipi ailesi.

**Returns:**
java.lang.String
### getFontFileName() {#getFontFileName--}
```
public String getFontFileName()
```


Tam yol olmadan yazı tipi dosya adını alır veya ayarlar.

Değer: Tam yol olmadan yazı tipi dosya adı.

**Returns:**
java.lang.String
### getFontName() {#getFontName--}
```
public String getFontName()
```


PostScript yazı tipi adını alır veya ayarlar.

Değer: PostScript yazı tipi adının adı.

**Returns:**
java.lang.String
### getFontType() {#getFontType--}
```
public String getFontType()
```


Yazı tipi türünü alır veya ayarlar.

TrueType, Type 1, Open Type ve benzeri. Değer: Yazı tipi türü.

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Varsayılan ad alanı URI'sını alır.

**Returns:**
java.lang.String - Varsayılan ad alanı URI'si.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Ön eki alır.

**Returns:**
java.lang.String - Önek.
### getVersion() {#getVersion--}
```
public String getVersion()
```


Yazı tipi sürümünü alır veya ayarlar.

/version, Type1 yazı tipleri için nameId 5, Apple True Type ve OpenType için /CIDFontVersion, CID yazı tipleri için. Bitmap yazı tipleri için boş dize. Değer: Yazı tipi sürümü.

**Returns:**
java.lang.String
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
### isComposite() {#isComposite--}
```
public boolean isComposite()
```


Bu yazı tipinin bileşik olup olmadığını gösteren değeri alır veya ayarlar.

Değer:  true  ise bu yazı tipi birleşik; aksi takdirde,  false .

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




### setChildFontFiles(String[] value) {#setChildFontFiles-java.lang.String---}
```
public void setChildFontFiles(String[] value)
```


Bileşik bir yazı tipini oluşturan yazı tiplerinin dosya adı dizisini alır veya ayarlar.

Değer: Bir birleşik yazı tipini oluşturan yazı tiplerinin dosya adı dizisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String[] |  |

### setComposite(boolean value) {#setComposite-boolean-}
```
public void setComposite(boolean value)
```


Bu yazı tipinin bileşik olup olmadığını gösteren değeri alır veya ayarlar.

Değer:  true  ise bu yazı tipi birleşik; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setFontFace(String value) {#setFontFace-java.lang.String-}
```
public void setFontFace(String value)
```


Yazı tipi yüzünü alır veya ayarlar.

Değer: Yazı tipi yüzü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setFontFamily(String value) {#setFontFamily-java.lang.String-}
```
public void setFontFamily(String value)
```


Yazı tipi ailesini alır veya ayarlar.

Değer: Yazı tipi ailesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setFontFileName(String value) {#setFontFileName-java.lang.String-}
```
public void setFontFileName(String value)
```


Tam yol olmadan yazı tipi dosya adını alır veya ayarlar.

Değer: Tam yol olmadan yazı tipi dosya adı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public void setFontName(String value)
```


PostScript yazı tipi adını alır veya ayarlar.

Değer: PostScript yazı tipi adının adı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setFontType(String value) {#setFontType-java.lang.String-}
```
public void setFontType(String value)
```


Yazı tipi türünü alır veya ayarlar.

TrueType, Type 1, Open Type ve benzeri. Değer: Yazı tipi türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


Yazı tipi sürümünü alır veya ayarlar.

/version, Type1 yazı tipleri için nameId 5, Apple True Type ve OpenType için /CIDFontVersion, CID yazı tipleri için. Bitmap yazı tipleri için boş dize. Değer: Yazı tipi sürümü.

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

