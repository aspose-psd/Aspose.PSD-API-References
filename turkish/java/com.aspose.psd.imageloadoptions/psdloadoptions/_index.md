---
title: "PsdLoadOptions"
second_title: "Java için Aspose.PSD API Referansı"
description: "PSD yükleme seçenekleri"
type: docs
weight: 12
url: /tr/java/com.aspose.psd.imageloadoptions/psdloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class PsdLoadOptions extends LoadOptions
```

PSD yükleme seçenekleri
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PsdLoadOptions()](#PsdLoadOptions--) | Yeni bir [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions) sınıfının bir örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | Özel yazı tipi kaynakları |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowNonChangedLayerRepaint()](#getAllowNonChangedLayerRepaint--) | Katman değiştirilmemişse, render sırasında orijinal katman piksellerinin korunup korunmayacağını alır veya ayarlar. |
| [getAllowWarpRepaint()](#getAllowWarpRepaint--) | Render edilmiş görüntüyle, eğme dönüşümü ile birlikte veya olmadan kaydedilip kaydedilmeyeceğini alır veya ayarlar. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Görüntünün arka plan rengini alır. |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Veri kurtarma modunu alır. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Yükleme sonrası [ignore after load] göz ardı edilip edilmediğini gösteren bir değeri alır. |
| [getIgnoreAlphaChannel()](#getIgnoreAlphaChannel--) | [ignore alpha channel] gösterilip gösterilmediğini belirten bir değeri alır veya ayarlar. |
| [getIgnoreTextLayerWidthOnUpdate()](#getIgnoreTextLayerWidthOnUpdate--) | UpdateText işlemi yürütülürken PSD metin katmanının sabit genişliğinin göz ardı edilip edilmediğini belirten bir değeri alır veya ayarlar. |
| [getLoadEffectsResource()](#getLoadEffectsResource--) | [load effects resource] gösterilip gösterilmediğini (varsayılan olarak kaynak yüklenmez) belirten bir değeri alır veya ayarlar. |
| [getProgressEventHandler()](#getProgressEventHandler--) | İlerleme olay işleyicisini alır. |
| [getReadOnlyMode()](#getReadOnlyMode--) | [use read only mode] gösterilip gösterilmediğini belirten bir değeri alır veya ayarlar. |
| [getReadOnlyType()](#getReadOnlyType--) | PSD görüntüsü yüklenirken kullanılan salt‑okunur modu alır veya ayarlar. |
| [getUseDiskForLoadEffectsResource()](#getUseDiskForLoadEffectsResource--) | [use disk for load effects resource] gösterilip gösterilmediğini (varsayılan olarak efekt kaynağını yüklemek için disk kullanılır, ancak bu değer false olarak ayarlanırsa bellek kullanılabilir) belirten bir değeri alır veya ayarlar. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | ICC profil dönüşümünün uygulanıp uygulanmayacağını gösteren bir değeri alır. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Bu, girişim lisanslama modelinin bir parçasıdır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowNonChangedLayerRepaint(boolean value)](#setAllowNonChangedLayerRepaint-boolean-) | Katman değiştirilmemişse, render sırasında orijinal katman piksellerinin korunup korunmayacağını alır veya ayarlar. |
| [setAllowWarpRepaint(boolean value)](#setAllowWarpRepaint-boolean-) | Render edilmiş görüntüyle, eğme dönüşümü ile birlikte veya olmadan kaydedilip kaydedilmeyeceğini alır veya ayarlar. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu ayarlar. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Görüntünün arka plan rengini ayarlar. |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Veri kurtarma modunu ayarlar. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Yükleme sonrasında [ignore after load] olup olmadığını gösteren bir değeri ayarlar. |
| [setIgnoreAlphaChannel(boolean value)](#setIgnoreAlphaChannel-boolean-) | [ignore alpha channel] gösterilip gösterilmediğini belirten bir değeri alır veya ayarlar. |
| [setIgnoreTextLayerWidthOnUpdate(boolean value)](#setIgnoreTextLayerWidthOnUpdate-boolean-) | UpdateText işlemi yürütülürken PSD metin katmanının sabit genişliğinin göz ardı edilip edilmediğini belirten bir değeri alır veya ayarlar. |
| [setLoadEffectsResource(boolean value)](#setLoadEffectsResource-boolean-) | [load effects resource] gösterilip gösterilmediğini (varsayılan olarak kaynak yüklenmez) belirten bir değeri alır veya ayarlar. |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Bellek MGR'yi alır veya ayarlar. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | İlerleme olayı işleyicisini ayarlar. |
| [setReadOnlyMode(boolean value)](#setReadOnlyMode-boolean-) | [use read only mode] gösterilip gösterilmediğini belirten bir değeri alır veya ayarlar. |
| [setReadOnlyType(int value)](#setReadOnlyType-int-) | PSD görüntüsü yüklenirken kullanılan salt‑okunur modu alır veya ayarlar. |
| [setUseDiskForLoadEffectsResource(boolean value)](#setUseDiskForLoadEffectsResource-boolean-) | [use disk for load effects resource] gösterilip gösterilmediğini (varsayılan olarak efekt kaynağını yüklemek için disk kullanılır, ancak bu değer false olarak ayarlanırsa bellek kullanılabilir) belirten bir değeri alır veya ayarlar. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | ICC profil dönüşümünün uygulanıp uygulanmayacağını gösteren bir değeri ayarlar. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | Bu, girişim lisanslama modelinin bir parçasıdır. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdLoadOptions() {#PsdLoadOptions--}
```
public PsdLoadOptions()
```


Yeni bir [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions) sınıfının bir örneğini başlatır.

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
### getAllowNonChangedLayerRepaint() {#getAllowNonChangedLayerRepaint--}
```
public final boolean getAllowNonChangedLayerRepaint()
```


Katman değiştirilmemişse, render sırasında orijinal katman piksellerinin korunup korunmayacağını alır veya ayarlar.

Değer:  true  değişmemiş katmanların orijinal piksellerini korumak için; aksi takdirde,  false .

**Returns:**
boolean
### getAllowWarpRepaint() {#getAllowWarpRepaint--}
```
public final boolean getAllowWarpRepaint()
```


Render edilmiş görüntüyle, eğme dönüşümü ile birlikte veya olmadan kaydedilip kaydedilmeyeceğini alır veya ayarlar.

Değer:  true  görüntüyü warp dönüşümüyle render etmek için  false .

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
### getIgnoreAlphaChannel() {#getIgnoreAlphaChannel--}
```
public final boolean getIgnoreAlphaChannel()
```


[ignore alpha channel] gösterilip gösterilmediğini belirten bir değeri alır veya ayarlar.

Değer:  true  eğer [ignore alpha channel]; aksi takdirde,  false .

**Returns:**
boolean
### getIgnoreTextLayerWidthOnUpdate() {#getIgnoreTextLayerWidthOnUpdate--}
```
public final boolean getIgnoreTextLayerWidthOnUpdate()
```


UpdateText işlemi yürütülürken PSD metin katmanının sabit genişliğinin göz ardı edilip edilmediğini belirten bir değeri alır veya ayarlar.

Değer:  true  eğer [ignore text layer width]; aksi takdirde,  false .

**Returns:**
boolean
### getLoadEffectsResource() {#getLoadEffectsResource--}
```
public final boolean getLoadEffectsResource()
```


[load effects resource] gösterilip gösterilmediğini (varsayılan olarak kaynak yüklenmez) belirten bir değeri alır veya ayarlar. Bu seçenek ayarlandığında yalnızca desteklenen efektler son birleştirilmiş görüntüye render edilir.

Değer:  true  eğer [load effects resource]; aksi takdirde,  false .

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


İlerleme olay işleyicisini alır.

Değer: İlerleme olayı işleyicisi.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getReadOnlyMode() {#getReadOnlyMode--}
```
public final boolean getReadOnlyMode()
```


[use read only mode] gösterilip gösterilmediğini belirten bir değeri alır veya ayarlar. Bu, Adobe Photoshop ile aynı uyumluluk için desteklenen salt‑okunur moddur. Bu seçenek ayarlandığında, katmanlara uygulanan tüm değişiklikler son görüntüye kaydedilmez. Tüm veriler ImageData bölümünden alınır, bu nedenle Photoshop ile aynıdır. Varsayılan olarak, yüklenen tüm görüntüler Adobe Photoshop uyumlu değildir.

Değer:  true  eğer [use photoshop compatibility mode]; aksi takdirde,  false .

**Returns:**
boolean
### getReadOnlyType() {#getReadOnlyType--}
```
public final int getReadOnlyType()
```


PSD görüntüsü yüklenirken kullanılan salt‑okunur modu alır veya ayarlar.

Değer: ReadOnlyMode ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)) değerlerinden biri:

 *  
 *  
 *  

**Returns:**
int
### getUseDiskForLoadEffectsResource() {#getUseDiskForLoadEffectsResource--}
```
public final boolean getUseDiskForLoadEffectsResource()
```


[use disk for load effects resource] gösterilip gösterilmediğini (varsayılan olarak efekt kaynağını yüklemek için disk kullanılır, ancak bu değer false olarak ayarlanırsa bellek kullanılabilir) belirten bir değeri alır veya ayarlar.

Değer:  true  eğer [use disk for load effects resource]; aksi takdirde,  false .

**Returns:**
boolean
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




### setAllowNonChangedLayerRepaint(boolean value) {#setAllowNonChangedLayerRepaint-boolean-}
```
public final void setAllowNonChangedLayerRepaint(boolean value)
```


Katman değiştirilmemişse, render sırasında orijinal katman piksellerinin korunup korunmayacağını alır veya ayarlar.

Değer:  true  değişmemiş katmanların orijinal piksellerini korumak için; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setAllowWarpRepaint(boolean value) {#setAllowWarpRepaint-boolean-}
```
public final void setAllowWarpRepaint(boolean value)
```


Render edilmiş görüntüyle, eğme dönüşümü ile birlikte veya olmadan kaydedilip kaydedilmeyeceğini alır veya ayarlar.

Değer:  true  görüntüyü warp dönüşümüyle render etmek için  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

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

### setIgnoreAlphaChannel(boolean value) {#setIgnoreAlphaChannel-boolean-}
```
public final void setIgnoreAlphaChannel(boolean value)
```


[ignore alpha channel] gösterilip gösterilmediğini belirten bir değeri alır veya ayarlar.

Değer:  true  eğer [ignore alpha channel]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setIgnoreTextLayerWidthOnUpdate(boolean value) {#setIgnoreTextLayerWidthOnUpdate-boolean-}
```
public final void setIgnoreTextLayerWidthOnUpdate(boolean value)
```


UpdateText işlemi yürütülürken PSD metin katmanının sabit genişliğinin göz ardı edilip edilmediğini belirten bir değeri alır veya ayarlar.

Değer:  true  eğer [ignore text layer width]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setLoadEffectsResource(boolean value) {#setLoadEffectsResource-boolean-}
```
public final void setLoadEffectsResource(boolean value)
```


[load effects resource] gösterilip gösterilmediğini (varsayılan olarak kaynak yüklenmez) belirten bir değeri alır veya ayarlar. Bu seçenek ayarlandığında yalnızca desteklenen efektler son birleştirilmiş görüntüye render edilir.

Değer:  true  eğer [load effects resource]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

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

### setReadOnlyMode(boolean value) {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```


[use read only mode] gösterilip gösterilmediğini belirten bir değeri alır veya ayarlar. Bu, Adobe Photoshop ile aynı uyumluluk için desteklenen salt‑okunur moddur. Bu seçenek ayarlandığında, katmanlara uygulanan tüm değişiklikler son görüntüye kaydedilmez. Tüm veriler ImageData bölümünden alınır, bu nedenle Photoshop ile aynıdır. Varsayılan olarak, yüklenen tüm görüntüler Adobe Photoshop uyumlu değildir.

Değer:  true  eğer [use photoshop compatibility mode]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setReadOnlyType(int value) {#setReadOnlyType-int-}
```
public final void setReadOnlyType(int value)
```


PSD görüntüsü yüklenirken kullanılan salt‑okunur modu alır veya ayarlar.

Değer: ReadOnlyMode ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)) değerlerinden biri:

 *  
 *  
 *  

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setUseDiskForLoadEffectsResource(boolean value) {#setUseDiskForLoadEffectsResource-boolean-}
```
public final void setUseDiskForLoadEffectsResource(boolean value)
```


[use disk for load effects resource] gösterilip gösterilmediğini (varsayılan olarak efekt kaynağını yüklemek için disk kullanılır, ancak bu değer false olarak ayarlanırsa bellek kullanılabilir) belirten bir değeri alır veya ayarlar.

Değer:  true  eğer [use disk for load effects resource]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

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

