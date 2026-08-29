---
title: "BlwhResource"
second_title: "Java için Aspose.PSD API Referansı"
description: "BlwhResource sınıfı, Siyah ve Beyaz Ayarlama Katmanı'nın bir kaynağıdır."
type: docs
weight: 15
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class BlwhResource extends AdjustmentLayerResource
```

BlwhResource sınıfı, Siyah ve Beyaz Ayarlama Katmanı'nın bir kaynağıdır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BlwhResource()](#BlwhResource--) | Yeni bir [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource) sınıfının örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB başlık sürümü |
| [PsbResourceSignature](#PsbResourceSignature) | PSB'ye özgü kaynak imzası. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD başlık sürümü |
| [ResourceSignature](#ResourceSignature) | Ortak kaynak imzası. |
| [TypeToolKey](#TypeToolKey) | Tip aracı bilgi anahtarı. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Girişim lisansı. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Kaynağın PSB'ye özgü olup olmadığını kontrol eder ve ayarlar. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlackAndWhitePresetFileName()](#getBlackAndWhitePresetFileName--) | Siyah ve beyaz ön ayar dosya adını alır veya ayarlar. |
| [getBlues()](#getBlues--) | Mavi değerini alır veya ayarlar. |
| [getBwPresetKind()](#getBwPresetKind--) | Siyah ve beyaz ön ayar tür değerini alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getCyans()](#getCyans--) | Camgöbeği değerini alır veya ayarlar. |
| [getData()](#getData--) | Veriyi alır veya ayarlar. |
| [getGreens()](#getGreens--) | Yeşiller değerini alır veya ayarlar. |
| [getHeader_internalized()](#getHeader-internalized--) | Üst bilgiyi alır veya ayarlar. |
| [getKey()](#getKey--) | Katman kaynağı anahtarını alır. |
| [getLength()](#getLength--) | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| [getMagentas()](#getMagentas--) | Macenta değerini alır veya ayarlar. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Önek uzunluğunu alır. |
| [getPsdVersion()](#getPsdVersion--) | Katman kaynağı için gereken minimum psd sürümünü alır. |
| [getReds()](#getReds--) | Kırmızılar değerini alır veya ayarlar. |
| [getSignature()](#getSignature--) | Katman kaynağı imzasını alır. |
| [getTintColor()](#getTintColor--) | ARGB tonlama rengini alır. |
| [getTintColorBlue_internalized()](#getTintColorBlue-internalized--) | Mavi renk tonu çift değerini alır veya ayarlar. |
| [getTintColorGreen_internalized()](#getTintColorGreen-internalized--) | Yeşil renk tonu çift değerini alır veya ayarlar. |
| [getTintColorRed_internalized()](#getTintColorRed-internalized--) | Kırmızı renk tonu çift değerini alır veya ayarlar. |
| [getUseTint()](#getUseTint--) | [tint color] kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar. |
| [getYellows()](#getYellows--) | Sarılar değerini alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Kaynağın PSB'ye özgü olup olmadığını belirler. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Bu örneğin kaynak PSB'ye özgü olup olmadığını gösteren bir değeri alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Kaynağı belirtilen akış konteynerine kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Özel kaynak başlığını kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Başlık imzasını, tanımlayıcısını ve uzunluğunu kaydeder. |
| [setBlackAndWhitePresetFileName(String value)](#setBlackAndWhitePresetFileName-java.lang.String-) | Siyah ve beyaz ön ayar dosya adını alır veya ayarlar. |
| [setBlues(int value)](#setBlues-int-) | Mavi değerini alır veya ayarlar. |
| [setBwPresetKind(int value)](#setBwPresetKind-int-) | Siyah ve beyaz ön ayar tür değerini alır veya ayarlar. |
| [setCyans(int value)](#setCyans-int-) | Camgöbeği değerini alır veya ayarlar. |
| [setGreens(int value)](#setGreens-int-) | Yeşiller değerini alır veya ayarlar. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Üst bilgiyi alır veya ayarlar. |
| [setMagentas(int value)](#setMagentas-int-) | Macenta değerini alır veya ayarlar. |
| [setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)](#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Özellik değerini tip yapısına göre ayarlar. |
| [setReds(int value)](#setReds-int-) | Kırmızılar değerini alır veya ayarlar. |
| [setTintColor(int value)](#setTintColor-int-) | Tonlama rengini ayarlar. |
| [setTintColorBlue_internalized(double value)](#setTintColorBlue-internalized-double-) | Mavi renk tonu çift değerini alır veya ayarlar. |
| [setTintColorGreen_internalized(double value)](#setTintColorGreen-internalized-double-) | Yeşil renk tonu çift değerini alır veya ayarlar. |
| [setTintColorRed_internalized(double value)](#setTintColorRed-internalized-double-) | Kırmızı renk tonu çift değerini alır veya ayarlar. |
| [setUseTint(boolean value)](#setUseTint-boolean-) | [tint color] kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar. |
| [setYellows(int value)](#setYellows-int-) | Sarılar değerini alır veya ayarlar. |
| [toString()](#toString--) | Bu örneği temsil eden bir String döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BlwhResource() {#BlwhResource--}
```
public BlwhResource()
```


Yeni bir [BlwhResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/blwhresource) sınıfının örneğini başlatır.

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


PSB başlık sürümü

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


PSB'ye özgü kaynak imzası.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


PSD başlık sürümü

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


Ortak kaynak imzası.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


Tip aracı bilgi anahtarı.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Girişim lisansı.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Kaynağın PSB'ye özgü olup olmadığını kontrol eder ve ayarlar. Şu anda bazı kaynaklar tanınmıyor, ancak kaydetme sırasında davranışlarını değiştiren PSB'ye özgü kaynakların tam listesine sahibiz. Bu yüzden bunu en azından UnknownResource içinde kontrol etmemiz gerekiyor.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | int | Anahtar. |

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
### getBlackAndWhitePresetFileName() {#getBlackAndWhitePresetFileName--}
```
public final String getBlackAndWhitePresetFileName()
```


Siyah ve beyaz ön ayar dosya adını alır veya ayarlar.

Değer: Siyah ve beyaz ön ayar dosya adı.

**Returns:**
java.lang.String
### getBlues() {#getBlues--}
```
public final int getBlues()
```


Mavi değerini alır veya ayarlar.

Değer: Maviler değeri.

**Returns:**
int
### getBwPresetKind() {#getBwPresetKind--}
```
public final int getBwPresetKind()
```


Siyah ve beyaz ön ayar tür değerini alır veya ayarlar.

Değer: Siyah ve beyaz ön ayar türü değeri.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCyans() {#getCyans--}
```
public final int getCyans()
```


Camgöbeği değerini alır veya ayarlar.

Değer: Camgöbeği değeri.

**Returns:**
int
### getData() {#getData--}
```
public final byte[] getData()
```


Veriyi alır veya ayarlar.

Değer: Veri.

**Returns:**
byte[]
### getGreens() {#getGreens--}
```
public final int getGreens()
```


Yeşiller değerini alır veya ayarlar.

Değer: Yeşiller değeri.

**Returns:**
int
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Üst bilgiyi alır veya ayarlar.

Değer: Başlık.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getKey() {#getKey--}
```
public final int getKey()
```


Katman kaynağı anahtarını alır.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Katman kaynağı uzunluğunu bayt cinsinden alır.

**Returns:**
int
### getMagentas() {#getMagentas--}
```
public final int getMagentas()
```


Macenta değerini alır veya ayarlar.

Değer: Macenta değeri.

**Returns:**
int
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Önek uzunluğunu alır. Varsayılan değer 8BIM kaynakları için 12, 8B64 için 16'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| psdVersion | int | PSD sürümü. |

**Returns:**
int - Önek Uzunluğu.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Katman kaynağı için gereken minimum psd sürümünü alır. 0, herhangi bir kısıtlama olmadığını gösterir.

**Returns:**
int
### getReds() {#getReds--}
```
public final int getReds()
```


Kırmızılar değerini alır veya ayarlar.

Değer: Kırmızılar değeri.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Katman kaynağı imzasını alır.

**Returns:**
int
### getTintColor() {#getTintColor--}
```
public int getTintColor()
```


ARGB tonlama rengini alır.

**Returns:**
int - ARGB tonlama rengi.
### getTintColorBlue_internalized() {#getTintColorBlue-internalized--}
```
public final double getTintColorBlue_internalized()
```


Mavi renk tonu çift değerini alır veya ayarlar.

Değer: Mavi renk tonu çift değeri.

**Returns:**
double
### getTintColorGreen_internalized() {#getTintColorGreen-internalized--}
```
public final double getTintColorGreen_internalized()
```


Yeşil renk tonu çift değerini alır veya ayarlar.

Değer: Yeşil renk tonu çift değeri.

**Returns:**
double
### getTintColorRed_internalized() {#getTintColorRed-internalized--}
```
public final double getTintColorRed_internalized()
```


Kırmızı renk tonu çift değerini alır veya ayarlar.

Değer: Kırmızı renk tonu çift değeri.

**Returns:**
double
### getUseTint() {#getUseTint--}
```
public final boolean getUseTint()
```


[tint color] kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer [tint color] kullanıldıysa; aksi takdirde,  false .

**Returns:**
boolean
### getYellows() {#getYellows--}
```
public final int getYellows()
```


Sarılar değerini alır veya ayarlar.

Değer: Sarılar değeri.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Kaynağın PSB'ye özgü olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | int | Kaynak anahtarı. |

**Returns:**
boolean -  true  eğer kaynak PSB'ye özgüyse; aksi takdirde,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Bu örneğin kaynak PSB'ye özgü olup olmadığını gösteren bir değeri alır.

Değer:  true  eğer bu örnek kaynak PSB'ye özgüyse; aksi takdirde,  false .

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




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Kaynağı belirtilen akış konteynerine kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Kaydedilecek akış konteyneri. |
| psdVersion | int | PSD sürümü. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Özel kaynak başlığını kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Akış konteyneri. |
| imza | int | İmza. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Başlık imzasını, tanımlayıcısını ve uzunluğunu kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Akış konteyneri. |
| imza | int | İmza. |
| isLengthLong | boolean | eğer  true  olarak ayarlanırsa uzunluk uzun olur. |

### setBlackAndWhitePresetFileName(String value) {#setBlackAndWhitePresetFileName-java.lang.String-}
```
public final void setBlackAndWhitePresetFileName(String value)
```


Siyah ve beyaz ön ayar dosya adını alır veya ayarlar.

Değer: Siyah ve beyaz ön ayar dosya adı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setBlues(int value) {#setBlues-int-}
```
public final void setBlues(int value)
```


Mavi değerini alır veya ayarlar.

Değer: Maviler değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setBwPresetKind(int value) {#setBwPresetKind-int-}
```
public final void setBwPresetKind(int value)
```


Siyah ve beyaz ön ayar tür değerini alır veya ayarlar.

Değer: Siyah ve beyaz ön ayar türü değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setCyans(int value) {#setCyans-int-}
```
public final void setCyans(int value)
```


Camgöbeği değerini alır veya ayarlar.

Değer: Camgöbeği değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setGreens(int value) {#setGreens-int-}
```
public final void setGreens(int value)
```


Yeşiller değerini alır veya ayarlar.

Değer: Yeşiller değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Üst bilgiyi alır veya ayarlar.

Değer: Başlık.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setMagentas(int value) {#setMagentas-int-}
```
public final void setMagentas(int value)
```


Macenta değerini alır veya ayarlar.

Değer: Macenta değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setPropertyValueByTypeStructure_internalized(OSTypeStructure structure) {#setPropertyValueByTypeStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void setPropertyValueByTypeStructure_internalized(OSTypeStructure structure)
```


Özellik değerini tip yapısına göre ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Yapı. |

### setReds(int value) {#setReds-int-}
```
public final void setReds(int value)
```


Kırmızılar değerini alır veya ayarlar.

Değer: Kırmızılar değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setTintColor(int value) {#setTintColor-int-}
```
public void setTintColor(int value)
```


Tonlama rengini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Değer. |

### setTintColorBlue_internalized(double value) {#setTintColorBlue-internalized-double-}
```
public final void setTintColorBlue_internalized(double value)
```


Mavi renk tonu çift değerini alır veya ayarlar.

Değer: Mavi renk tonu çift değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setTintColorGreen_internalized(double value) {#setTintColorGreen-internalized-double-}
```
public final void setTintColorGreen_internalized(double value)
```


Yeşil renk tonu çift değerini alır veya ayarlar.

Değer: Yeşil renk tonu çift değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setTintColorRed_internalized(double value) {#setTintColorRed-internalized-double-}
```
public final void setTintColorRed_internalized(double value)
```


Kırmızı renk tonu çift değerini alır veya ayarlar.

Değer: Kırmızı renk tonu çift değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setUseTint(boolean value) {#setUseTint-boolean-}
```
public final void setUseTint(boolean value)
```


[tint color] kullanılıp kullanılmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer [tint color] kullanıldıysa; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setYellows(int value) {#setYellows-int-}
```
public final void setYellows(int value)
```


Sarılar değerini alır veya ayarlar.

Değer: Sarılar değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### toString() {#toString--}
```
public String toString()
```


Bu örneği temsil eden bir String döndürür.

**Returns:**
java.lang.String - Bu örneği temsil eden bir dize.
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

