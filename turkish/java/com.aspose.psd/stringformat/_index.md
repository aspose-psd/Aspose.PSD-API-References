---
title: "StringFormat"
second_title: "Java için Aspose.PSD API Referansı"
description: "Metin yerleşim bilgilerini, hizalama, yönelim ve sekme durakları gibi, üç nokta ekleme ve ulusal rakam ikamesi gibi görüntü manipülasyonlarını ve OpenType özelliklerini kapsar."
type: docs
weight: 106
url: /tr/java/com.aspose.psd/stringformat/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public final class StringFormat extends DisposableObject
```

Metin yerleşim bilgilerini (örneğin hizalama, yönelim ve sekme durakları) görüntü manipülasyonlarını (örneğin üç nokta ekleme ve ulusal rakam ikamesi) ve OpenType özelliklerini kapsar. Bu sınıf miras alınamaz.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [StringFormat()](#StringFormat--) | Yeni bir  com.aspose.psd.StringFormat  nesnesi başlatır. |
| [StringFormat(int options)](#StringFormat-int-) | Belirtilen  com.aspose.psd.StringFormatFlags  enumarasyonu ve dil ile yeni bir  com.aspose.psd.StringFormat  nesnesi başlatır. |
| [StringFormat(StringFormat format)](#StringFormat-com.aspose.psd.StringFormat-) | Belirtilen mevcut  com.aspose.psd.StringFormat  nesnesinden yeni bir  com.aspose.psd.StringFormat  nesnesi başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [close()](#close--) | Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. |
| [deepClone()](#deepClone--) | Bu  com.aspose.psd.StringFormat  nesnesinin derin bir kopyasını oluşturur. |
| [dispose()](#dispose--) | Mevcut örneği serbest bırakır. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAlignment()](#getAlignment--) | Dikey düzlemde metin hizalama bilgisini alır. |
| [getClass()](#getClass--) |  |
| [getDigitSubstitutionLanguage()](#getDigitSubstitutionLanguage--) | Yerel rakamların batı rakamlarıyla ikame edildiği durumda kullanılan dili alır. |
| [getDigitSubstitutionMethod()](#getDigitSubstitutionMethod--) | Rakam ikamesi için kullanılacak yöntemi alır. |
| [getDisposed()](#getDisposed--) | Bu örneğin atılmış olup olmadığını gösteren bir değer alır. |
| [getFirstTabOffset()](#getFirstTabOffset--) | Metin satırının başlangıcı ile ilk sekme durağı arasındaki boşluk sayısını alır. |
| [getFormatFlags()](#getFormatFlags--) | Biçimlendirme bilgilerini içeren bir  com.aspose.psd.StringFormatFlags  enumarasyonunu alır. |
| [getGenericDefault()](#getGenericDefault--) | Genel bir varsayılan  com.aspose.psd.StringFormat  nesnesini alır. |
| [getGenericTypographic()](#getGenericTypographic--) | Genel bir tipografik  com.aspose.psd.StringFormat  nesnesini alır. |
| [getHotkeyPrefix()](#getHotkeyPrefix--) | Bu  com.aspose.psd.StringFormat  nesnesi için  com.aspose.psd.HotkeyPrefix  nesnesini alır. |
| [getLineAlignment()](#getLineAlignment--) | Yatay düzlemde satır hizalamasını alır. |
| [getTabStops()](#getTabStops--) | Sekme durakları arasındaki mesafelerin bir dizisini,  P:Aspose.Imaging.getGraphics().PageUnit  özelliği tarafından belirtilen birimlerde alır. |
| [getTrimming()](#getTrimming--) | Bu  com.aspose.psd.StringFormat  nesnesi için  com.aspose.psd.StringTrimming  enumarasyonunu alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAlignment(int value)](#setAlignment-int-) | Dikey düzlemde metin hizalama bilgisini ayarlar. |
| [setDigitSubstitutionLanguage(int value)](#setDigitSubstitutionLanguage-int-) | Yerel rakamların batı rakamlarıyla ikame edildiği durumda kullanılan dili ayarlar. |
| [setDigitSubstitutionMethod(int value)](#setDigitSubstitutionMethod-int-) | Rakam ikamesi için kullanılacak yöntemi ayarlar. |
| [setFormatFlags(int value)](#setFormatFlags-int-) | Biçimlendirme bilgilerini içeren bir  com.aspose.psd.StringFormatFlags  enumarasyonunu ayarlar. |
| [setHotkeyPrefix(int value)](#setHotkeyPrefix-int-) | Bu  com.aspose.psd.StringFormat  nesnesi için  com.aspose.psd.HotkeyPrefix  nesnesini ayarlar. |
| [setLineAlignment(int value)](#setLineAlignment-int-) | Yatay düzlemde satır hizalamasını ayarlar. |
| [setTabStops(float firstTabOffset, float[] tabStops)](#setTabStops-float-float---) | Bu  com.aspose.psd.StringFormat  nesnesi için sekme duraklarını ayarlar. |
| [setTrimming(int value)](#setTrimming-int-) | Bu  com.aspose.psd.StringFormat  nesnesi için  com.aspose.psd.StringTrimming  enumarasyonunu ayarlar. |
| [toString()](#toString--) | Bu  com.aspose.psd.StringFormat  nesnesini insan tarafından okunabilir bir dizeye dönüştürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StringFormat() {#StringFormat--}
```
public StringFormat()
```


Yeni bir  com.aspose.psd.StringFormat  nesnesi başlatır.

### StringFormat(int options) {#StringFormat-int-}
```
public StringFormat(int options)
```


Belirtilen  com.aspose.psd.StringFormatFlags  enumarasyonu ve dil ile yeni bir  com.aspose.psd.StringFormat  nesnesi başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| seçenekler | int | Yeni  com.aspose.psd.StringFormat  nesnesi için  com.aspose.psd.StringFormatFlags  enumarasyonu. |

### StringFormat(StringFormat format) {#StringFormat-com.aspose.psd.StringFormat-}
```
public StringFormat(StringFormat format)
```


Belirtilen mevcut  com.aspose.psd.StringFormat  nesnesinden yeni bir  com.aspose.psd.StringFormat  nesnesi başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | [StringFormat](../../com.aspose.psd/stringformat) | Yeni  com.aspose.psd.StringFormat  nesnesini başlatmak için kullanılacak  com.aspose.psd.StringFormat  nesnesi. |

### close() {#close--}
```
public void close()
```


Closable arayüzünü uygular ve JDK 1.7'den beri try-with-resources ifadesinde kullanılabilir. Bu yöntem sadece dispose yöntemini çağırır.

### deepClone() {#deepClone--}
```
public StringFormat deepClone()
```


Bu  com.aspose.psd.StringFormat  nesnesinin derin bir kopyasını oluşturur.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The deep clone of the current  com.aspose.psd.StringFormat .
### dispose() {#dispose--}
```
public final void dispose()
```


Mevcut örneği serbest bırakır.

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
### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Dikey düzlemde metin hizalama bilgisini alır.

**Returns:**
int - Metin hizalama bilgilerini belirten bir  com.aspose.psd.StringAlignment  enumarasyonu.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDigitSubstitutionLanguage() {#getDigitSubstitutionLanguage--}
```
public int getDigitSubstitutionLanguage()
```


Yerel rakamların batı rakamlarıyla ikame edildiği durumda kullanılan dili alır.

**Returns:**
int - Yerel rakamların batı rakamlarıyla değiştirileceği dili belirten bir Ulusal Dil Desteği (NLS) dil tanımlayıcısı. Bir  System.Globalization.CultureInfo  nesnesinin  P:System.Globalization.CultureInfo.LCID  özelliğini NLS dil tanımlayıcısı olarak geçirebilirsiniz. Örneğin, "ar-EG" dizesini bir  System.Globalization.CultureInfo  yapıcısına geçirerek bir  System.Globalization.CultureInfo  nesnesi oluşturduğunuzu varsayalım. Bu  System.Globalization.CultureInfo  nesnesinin  P:System.Globalization.CultureInfo.LCID  özelliğini ve  com.aspose.psd.StringDigitSubstitute.Traditional  değerini  com.aspose.psd.StringFormat.setDigitSubstitution(int, com.aspose.psd.StringDigitSubstitute)  yöntemine geçirirseniz, Arapça-Hint rakamları görüntüleme sırasında batı rakamlarıyla değiştirilecektir.

setDigitSubstitution adlı eski yöntem için ayarlayıcı tanıtıldı.
### getDigitSubstitutionMethod() {#getDigitSubstitutionMethod--}
```
public int getDigitSubstitutionMethod()
```


Rakam ikamesi için kullanılacak yöntemi alır.

**Returns:**
int - Geçerli yazı tipi tarafından desteklenmediği için görüntülenemeyen bir dizedeki karakterlerin nasıl değiştirileceğini belirten bir  com.aspose.psd.StringDigitSubstitute  enumarasyon değeri.

SetDigitSubstitution adlı eski yöntem için ayarlayıcı tanıtıldı.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Bu örneğin atılmış olup olmadığını gösteren bir değer alır.

**Returns:**
boolean -  true  ise disposed; aksi takdirde,  false .
### getFirstTabOffset() {#getFirstTabOffset--}
```
public float getFirstTabOffset()
```


Metin satırının başlangıcı ile ilk sekme durağı arasındaki boşluk sayısını alır.

**Returns:**
float - İlk sekme ofseti.

GetTabStops adlı kaldırılmış yöntem için özellik tanıtıldı.
### getFormatFlags() {#getFormatFlags--}
```
public int getFormatFlags()
```


Biçimlendirme bilgilerini içeren bir  com.aspose.psd.StringFormatFlags  enumarasyonunu alır.

**Returns:**
int - Biçimlendirme bilgilerini içeren bir  com.aspose.psd.StringFormatFlags  enumarasyonu.
### getGenericDefault() {#getGenericDefault--}
```
public static StringFormat getGenericDefault()
```


Genel bir varsayılan  com.aspose.psd.StringFormat  nesnesini alır.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - The generic default  com.aspose.psd.StringFormat  object.
### getGenericTypographic() {#getGenericTypographic--}
```
public static StringFormat getGenericTypographic()
```


Genel bir tipografik  com.aspose.psd.StringFormat  nesnesini alır.

**Returns:**
[StringFormat](../../com.aspose.psd/stringformat) - A generic typographic  com.aspose.psd.StringFormat  object.
### getHotkeyPrefix() {#getHotkeyPrefix--}
```
public int getHotkeyPrefix()
```


Bu  com.aspose.psd.StringFormat  nesnesi için  com.aspose.psd.HotkeyPrefix  nesnesini alır.

**Returns:**
int - Bu  com.aspose.psd.StringFormat  nesnesi için  com.aspose.psd.HotkeyPrefix  nesnesi, varsayılan değer  F:Aspose.Imaging.HotkeyPrefix.None .
### getLineAlignment() {#getLineAlignment--}
```
public int getLineAlignment()
```


Yatay düzlemde satır hizalamasını alır.

**Returns:**
int - Satır hizalamasını temsil eden bir  com.aspose.psd.StringAlignment  enumarasyonu.
### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Sekme durakları arasındaki mesafelerin bir dizisini,  P:Aspose.Imaging.getGraphics().PageUnit  özelliği tarafından belirtilen birimlerde alır.

**Returns:**
float[] - Sekme durakları.

GetTabStops adlı kaldırılmış yöntem için özellik tanıtıldı.
### getTrimming() {#getTrimming--}
```
public int getTrimming()
```


Bu  com.aspose.psd.StringFormat  nesnesi için  com.aspose.psd.StringTrimming  enumarasyonunu alır.

**Returns:**
int - Bu  com.aspose.psd.StringFormat  nesnesiyle çizilen metnin, yerleşim dikdörtgeninin kenarlarını aştığında nasıl kırpılacağını gösteren bir  com.aspose.psd.StringTrimming  enumarasyonu.
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




### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Dikey düzlemde metin hizalama bilgisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Metin hizalama bilgilerini belirten bir  com.aspose.psd.StringAlignment  enumarasyonu. |

### setDigitSubstitutionLanguage(int value) {#setDigitSubstitutionLanguage-int-}
```
public void setDigitSubstitutionLanguage(int value)
```


Yerel rakamların batı rakamlarıyla ikame edildiği durumda kullanılan dili ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Yerel rakamların batı rakamlarıyla değiştirileceği dili belirten bir Ulusal Dil Desteği (NLS) dil tanımlayıcısı. Bir  System.Globalization.CultureInfo  nesnesinin  P:System.Globalization.CultureInfo.LCID  özelliğini NLS dil tanımlayıcısı olarak geçirebilirsiniz. Örneğin, "ar-EG" dizesini bir  System.Globalization.CultureInfo  yapıcısına geçirerek bir  System.Globalization.CultureInfo  nesnesi oluşturduğunuzu varsayalım. Bu  System.Globalization.CultureInfo  nesnesinin  P:System.Globalization.CultureInfo.LCID  özelliğini ve  com.aspose.psd.StringDigitSubstitute.Traditional  değerini  com.aspose.psd.StringFormat.setDigitSubstitution(int,com.aspose.psd.StringDigitSubstitute)  yöntemine geçirirseniz, Arapça-Hint rakamları görüntüleme sırasında batı rakamlarıyla değiştirilecektir. |

SetDigitSubstitution adlı eski yöntem için ayarlayıcı tanıtıldı. |

### setDigitSubstitutionMethod(int value) {#setDigitSubstitutionMethod-int-}
```
public void setDigitSubstitutionMethod(int value)
```


Rakam ikamesi için kullanılacak yöntemi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | int | Geçerli yazı tipi tarafından desteklenmediği için görüntülenemeyen bir dizedeki karakterlerin nasıl değiştirileceğini belirten bir  com.aspose.psd.StringDigitSubstitute  enumarasyon değeri. |

SetDigitSubstitution adlı eski yöntem için ayarlayıcı tanıtıldı. |

### setFormatFlags(int value) {#setFormatFlags-int-}
```
public void setFormatFlags(int value)
```


Biçimlendirme bilgilerini içeren bir  com.aspose.psd.StringFormatFlags  enumarasyonunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Biçimlendirme bilgilerini içeren bir  com.aspose.psd.StringFormatFlags  enumarasyonu. |

### setHotkeyPrefix(int value) {#setHotkeyPrefix-int-}
```
public void setHotkeyPrefix(int value)
```


Bu  com.aspose.psd.StringFormat  nesnesi için  com.aspose.psd.HotkeyPrefix  nesnesini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu  com.aspose.psd.StringFormat  nesnesi için  com.aspose.psd.HotkeyPrefix  nesnesi, varsayılan değer  F:Aspose.Imaging.HotkeyPrefix.None . |

### setLineAlignment(int value) {#setLineAlignment-int-}
```
public void setLineAlignment(int value)
```


Yatay düzlemde satır hizalamasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Satır hizalamasını temsil eden bir  com.aspose.psd.StringAlignment  enumarasyonu. |

### setTabStops(float firstTabOffset, float[] tabStops) {#setTabStops-float-float---}
```
public void setTabStops(float firstTabOffset, float[] tabStops)
```


Bu  com.aspose.psd.StringFormat  nesnesi için sekme duraklarını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| firstTabOffset | float | Bir metin satırının başlangıcı ile ilk sekme durağı arasındaki boşluk sayısı. |
| tabStops | float[] | Sekme durakları arasındaki mesafelerin,  com.aspose.psd.Graphics.PageUnit  özelliği tarafından belirtilen birimlerdeki bir dizisi. |

### setTrimming(int value) {#setTrimming-int-}
```
public void setTrimming(int value)
```


Bu  com.aspose.psd.StringFormat  nesnesi için  com.aspose.psd.StringTrimming  enumarasyonunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Bu  com.aspose.psd.StringFormat  nesnesiyle çizilen metnin, yerleşim dikdörtgeninin kenarlarını aştığında nasıl kırpılacağını belirten bir  com.aspose.psd.StringTrimming  sayımı. |

### toString() {#toString--}
```
public String toString()
```


Bu  com.aspose.psd.StringFormat  nesnesini insan tarafından okunabilir bir dizeye dönüştürür.

**Returns:**
java.lang.String - Bu  com.aspose.psd.StringFormat  nesnesinin bir dize temsili.
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

