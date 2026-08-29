---
title: "PngLoadOptions"
second_title: "Java için Aspose.PSD API Referansı"
description: "PNG yükleme seçenekleri."
type: docs
weight: 11
url: /tr/java/com.aspose.psd.imageloadoptions/pngloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class PngLoadOptions extends LoadOptions
```

PNG yükleme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PngLoadOptions()](#PngLoadOptions--) | Yeni bir  PngLoadOptions  sınıfının bir örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | Özel yazı tipi kaynakları |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Görüntünün arka plan rengini alır. |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Veri kurtarma modunu alır. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Yükleme sonrası [ignore after load] göz ardı edilip edilmediğini gösteren bir değeri alır. |
| [getProgressEventHandler()](#getProgressEventHandler--) | İlerleme olay işleyicisini alır. |
| [getStrictMode()](#getStrictMode--) | [strict mode] gösterilip gösterilmediğini belirten bir değeri alır veya ayarlar. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | ICC profil dönüşümünün uygulanıp uygulanmayacağını gösteren bir değeri alır. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Bu, girişim lisanslama modelinin bir parçasıdır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu ayarlar. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Görüntünün arka plan rengini ayarlar. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Veri kurtarma modunu ayarlar. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Yükleme sonrasında [ignore after load] olup olmadığını gösteren bir değeri ayarlar. |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Bellek MGR'yi alır veya ayarlar. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | İlerleme olayı işleyicisini ayarlar. |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | [strict mode] gösterilip gösterilmediğini belirten bir değeri alır veya ayarlar. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | ICC profil dönüşümünün uygulanıp uygulanmayacağını gösteren bir değeri ayarlar. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | Bu, girişim lisanslama modelinin bir parçasıdır. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PngLoadOptions() {#PngLoadOptions--}
```
public PngLoadOptions()
```


Yeni bir  PngLoadOptions  sınıfının bir örneğini başlatır.

### CustomFontSources_internalized {#CustomFontSources-internalized}
```
public System.Collections.Generic.List<CustomFontSource> CustomFontSources_internalized
```


Özel yazı tipi kaynakları

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
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır.

Değer: Megabayt cinsinden tampon boyutu ipucu. Pozitif olmayan değer, iç tamponlar için bellek sınırlaması olmadığı anlamına gelir.

**Returns:**
int - tüm iç tamponlar için tanımlanan maksimum izin verilen boyut olan tampon boyutu ipucu.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


Görüntünün arka plan rengini alır.

**Returns:**
[Color](../../com.aspose.psd/color) - The background color.

Genellikle, piksel değeri veri bozulması nedeniyle kurtarılamadığında arka plan rengi ayarlanır.
### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


Veri kurtarma modunu alır.

**Returns:**
int - Veri kurtarma modu.
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


Yükleme sonrası [ignore after load] göz ardı edilip edilmediğini gösteren bir değeri alır.

**Returns:**
boolean -  true  eğer [ignore after load]; aksi takdirde,  false .
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


İlerleme olay işleyicisini alır.

Değer: İlerleme olayı işleyicisi.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getStrictMode() {#getStrictMode--}
```
public boolean getStrictMode()
```


[strict mode] gösterilip gösterilmediğini belirten bir değeri alır veya ayarlar.

**Returns:**
boolean - [strict mode] gösterilip gösterilmediğini belirten bir değer.
### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


ICC profil dönüşümünün uygulanıp uygulanmayacağını gösteren bir değeri alır.

**Returns:**
boolean
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Bu, girişim lisanslama deseninin bir parçasıdır. Bu değer, girişim bize bir LoadOptions nesnesi gönderirse VentureLicenser tarafından ayarlanacaktır.

**Returns:**
java.lang.Object
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




### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu ayarlar.

Değer: Megabayt cinsinden tampon boyutu ipucu. Pozitif olmayan değer, iç tamponlar için bellek sınırlaması olmadığı anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucu. |

### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.psd.Color-}
```
public void setDataBackgroundColor(Color value)
```


Görüntünün arka plan rengini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.psd/color) | Arka plan rengi. |

Genellikle, piksel değeri veri bozulması nedeniyle kurtarılamadığında arka plan rengi ayarlanır. |

### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


Veri kurtarma modunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Veri kurtarma modu. |

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


Yükleme sonrasında [ignore after load] olup olmadığını gösteren bir değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | true  eğer [ignore after load]; aksi takdirde,  false . |

### setMemMgr_internalized(MemMgr value) {#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-}
```
public final void setMemMgr_internalized(MemMgr value)
```


Bellek MGR'yi alır veya ayarlar.

Değer: Bellek MGR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.internal.memorymanagement.MemMgr |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


İlerleme olayı işleyicisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | ilerleme olayı işleyicisi. |

### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public void setStrictMode(boolean value)
```


[strict mode] gösterilip gösterilmediğini belirten bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | [strict mode] gösterilip gösterilmediğini belirten bir değer. |

### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


ICC profil dönüşümünün uygulanıp uygulanmayacağını gösteren bir değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setVentureLicense_internalized(Object value) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object value)
```


Bu, girişim lisanslama deseninin bir parçasıdır. Bu değer, girişim bize bir LoadOptions nesnesi gönderirse VentureLicenser tarafından ayarlanacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Object |  |

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

