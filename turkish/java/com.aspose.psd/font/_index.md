---
title: "Yazı tipi"
second_title: "Java için Aspose.PSD API Referansı"
description: "Yazı tipi yüzü, boyutu ve stil özellikleri dahil olmak üzere metin için belirli bir biçim tanımlar."
type: docs
weight: 46
url: /tr/java/com.aspose.psd/font/
---

**Inheritance:**
java.lang.Object
```
public final class Font
```

Yazı tipi yüzü, boyutu ve stil özellikleri dahil olmak üzere metin için belirli bir biçim tanımlar. Bu sınıf miras alınamaz.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.psd.Font-int-) | Belirtilen mevcut com.aspose.psd.Font ve com.aspose.psd.FontStyle enumarasyonunu kullanan yeni bir com.aspose.psd.Font başlatır. |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | Belirtilen bir boyut kullanarak yeni bir  com.aspose.psd.Font  başlatır. |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | Belirtilen bir boyut ve stil kullanarak yeni bir  com.aspose.psd.Font  başlatır. |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | Belirtilen bir boyut, stil, birim ve karakter kümesi kullanarak yeni bir  com.aspose.psd.Font  başlatır. |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | Belirtilen bir boyut, stil ve birim kullanarak yeni bir  com.aspose.psd.Font  başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [deepClone()](#deepClone--) | Bu  Font  nesnesinin tam bir derin kopyasını oluşturur. |
| [equals(Object obj)](#equals-java.lang.Object-) | Belirtilen nesnenin bir  com.aspose.psd.Font  olup olmadığını ve bu  com.aspose.psd.Font  ile aynı özellik değerlerine sahip olup olmadığını gösterir. |
| [getBold()](#getBold--) | Bu  Font  nesnesinin kalın olup olmadığını gösteren bir değer alır. |
| [getCharacterSet()](#getCharacterSet--) | Bu  Font  tarafından kullanılan karakter kümesini belirten bir bayt değeri alır. |
| [getClass()](#getClass--) |  |
| [getItalic()](#getItalic--) | Bu  Font  nesnesinin italik olup olmadığını gösteren bir değer alır. |
| [getName()](#getName--) | Bu  Font  nesnesinin yüz adı alır. |
| [getSize()](#getSize--) | Bu  Font  nesnesinin,  P:Aspose.Imaging.Font.Unit  özelliği tarafından belirtilen birimlerde ölçülen em-boyutunu alır. |
| [getStrikeout()](#getStrikeout--) | Bu  Font  nesnesinin yazı tipinin üzerinden yatay bir çizgi geçip geçmediğini gösteren bir değer alır. |
| [getStyle()](#getStyle--) | Bu  Font  nesnesi için stil bilgilerini alır. |
| [getUnderline()](#getUnderline--) | Bu  Font  nesnesinin altı çizili olup olmadığını gösteren bir değer alır. |
| [getUnit()](#getUnit--) | Bu  Font  nesnesinin ölçü birimini alır. |
| [hashCode()](#hashCode--) | Bu  com.aspose.psd.Font  nesnesinin hash kodunu alır. |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | Belirtilen bir boyut ve birim kullanarak yeni bir  com.aspose.psd.Font  başlatır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) | Bu  com.aspose.psd.Font  nesnesinin insan tarafından okunabilir bir dize temsili döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font(Font prototype, int newStyle) {#Font-com.aspose.psd.Font-int-}
```
public Font(Font prototype, int newStyle)
```


Belirtilen mevcut com.aspose.psd.Font ve com.aspose.psd.FontStyle enumarasyonunu kullanan yeni bir com.aspose.psd.Font başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.psd/font) | Yeni  com.aspose.psd.Font  oluşturmak için kullanılacak mevcut  com.aspose.psd.Font . |
| newStyle | int | Yeni  com.aspose.psd.Font  üzerine uygulanacak  com.aspose.psd.FontStyle .  com.aspose.psd.FontStyle  enumarasyonunun birden fazla değeri OR operatörü ile birleştirilebilir. |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


Belirtilen bir boyut kullanarak yeni bir  com.aspose.psd.Font  başlatır. Karakter kümesi  F:Aspose.Imaging.CharacterSet.Default , grafik birimi  F:Aspose.Imaging.GraphicsUnit.Point , yazı tipi stili ise  F:Aspose.Imaging.FontStyle.Regular  olarak ayarlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String |   com.aspose.psd.Font  adının dize temsili. |
| emSize | float | Yeni yazı tipinin puan cinsinden em-boyutu. |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


Belirtilen bir boyut ve stil kullanarak yeni bir  com.aspose.psd.Font  başlatır. Karakter kümesi  F:Aspose.Imaging.CharacterSet.Default  olarak ayarlanır, grafik birimi ise  F:Aspose.Imaging.GraphicsUnit.Point  olarak ayarlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String |   com.aspose.psd.Font  adının dize temsili. |
| emSize | float | Yeni yazı tipinin puan cinsinden em-boyutu. |
| stil | int | Yeni yazı tipinin  com.aspose.psd.FontStyle  . |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


Belirtilen bir boyut, stil, birim ve karakter kümesi kullanarak yeni bir  com.aspose.psd.Font  başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String |   com.aspose.psd.Font  adının dize temsili. |
| emSize | float | Yeni yazı tipinin em-boyutu,  unit  parametresiyle belirtilen birimlerde. |
| stil | int | Yeni yazı tipinin  com.aspose.psd.FontStyle  . |
| birim | int | Yeni yazı tipinin  com.aspose.psd.GraphicsUnit  . |
| karakterKümesi | int | Bu yazı tipi için kullanılacak bir karakter kümesi. |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


Belirtilen bir boyut, stil ve birim kullanarak yeni bir  com.aspose.psd.Font  başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String |   com.aspose.psd.Font  adının dize temsili. |
| emSize | float | Yeni yazı tipinin em-boyutu,  unit  parametresiyle belirtilen birimlerde. |
| stil | int | Yeni yazı tipinin  com.aspose.psd.FontStyle  . |
| birim | int | Yeni yazı tipinin  com.aspose.psd.GraphicsUnit  . |

### deepClone() {#deepClone--}
```
public Font deepClone()
```


Bu  Font  nesnesinin tam bir derin kopyasını oluşturur.

**Returns:**
[Font](../../com.aspose.psd/font) - The  Font  this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Belirtilen nesnenin bir  com.aspose.psd.Font  olup olmadığını ve bu  com.aspose.psd.Font  ile aynı özellik değerlerine sahip olup olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Test edilecek nesne. |

**Returns:**
boolean -  obj  parametresi bir  com.aspose.psd.Font  ise ve bu  com.aspose.psd.Font  ile aynı özellik değerlerine sahipse doğru; aksi takdirde yanlış.
### getBold() {#getBold--}
```
public boolean getBold()
```


Bu  Font  nesnesinin kalın olup olmadığını gösteren bir değer alır.

**Returns:**
boolean - Bu  Font  kalın ise doğru; aksi takdirde yanlış.
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


Bu  Font  tarafından kullanılan karakter kümesini belirten bir bayt değeri alır.

**Returns:**
int - Bu  Font  tarafından kullanılan bir karakter kümesi.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


Bu  Font  nesnesinin italik olup olmadığını gösteren bir değer alır.

**Returns:**
boolean - Bu  Font  italik ise doğru; aksi takdirde yanlış.
### getName() {#getName--}
```
public String getName()
```


Bu  Font  nesnesinin yüz adı alır.

**Returns:**
java.lang.String - Bu  Font  yüz adının bir dize temsili.
### getSize() {#getSize--}
```
public float getSize()
```


Bu  Font  nesnesinin,  P:Aspose.Imaging.Font.Unit  özelliği tarafından belirtilen birimlerde ölçülen em-boyutunu alır.

**Returns:**
float - Bu  Font  'ın em-boyutu.
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


Bu  Font  nesnesinin yazı tipinin üzerinden yatay bir çizgi geçip geçmediğini gösteren bir değer alır.

**Returns:**
boolean - Bu  Font  üzerinde yatay bir çizgi varsa doğru; aksi takdirde yanlış.
### getStyle() {#getStyle--}
```
public int getStyle()
```


Bu  Font  nesnesi için stil bilgilerini alır.

**Returns:**
int - Bu  Font  için stil bilgilerini içeren bir  FontStyle  numaralandırması.
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


Bu  Font  nesnesinin altı çizili olup olmadığını gösteren bir değer alır.

**Returns:**
boolean - Bu  Font  altı çizili ise doğru; aksi takdirde yanlış.
### getUnit() {#getUnit--}
```
public int getUnit()
```


Bu  Font  nesnesinin ölçü birimini alır.

**Returns:**
int - Bu  Font  için ölçü birimini temsil eden bir  GraphicsUnit .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Bu  com.aspose.psd.Font  nesnesinin hash kodunu alır.

**Returns:**
int - Bu  com.aspose.psd.Font  için hash kodu.
### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


Belirtilen bir boyut ve birim kullanarak yeni bir  com.aspose.psd.Font  başlatır. Karakter kümesi  F:Aspose.Imaging.CharacterSet.Default  olarak ayarlanır, stil ise  F:Aspose.Imaging.FontStyle.Regular  olarak ayarlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String |   com.aspose.psd.Font  adının dize temsili. |
| emSize | float | Yeni yazı tipinin em-boyutu,  unit  parametresiyle belirtilen birimlerde. |
| birim | int | Yeni yazı tipinin  com.aspose.psd.GraphicsUnit  . |

**Returns:**
[Font](../../com.aspose.psd/font)
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


Bu  com.aspose.psd.Font  nesnesinin insan tarafından okunabilir bir dize temsili döndürür.

**Returns:**
java.lang.String - Bu  com.aspose.psd.Font  'ı temsil eden bir dize.
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

