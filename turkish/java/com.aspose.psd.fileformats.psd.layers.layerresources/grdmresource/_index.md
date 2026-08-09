---
title: "GrdmResource"
second_title: "Java için Aspose.PSD API Referansı"
description: "Sınıf GrdmResource."
type: docs
weight: 35
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class GrdmResource extends AdjustmentLayerResource
```

GrdmResource sınıfı. Gradient-Map katmanı hakkında bilgi içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GrdmResource()](#GrdmResource--) |  |
| [GrdmResource(int psdVersion)](#GrdmResource-int-) | Yeni bir [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource) sınıfının örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [DefaultScale_internalized](#DefaultScale-internalized) | Varsayılan ölçek. |
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
| [getClass()](#getClass--) |  |
| [getColorModel()](#getColorModel--) | Renk Modeli. |
| [getColorPoints()](#getColorPoints--) | Renk noktalarını alır veya ayarlar. |
| [getData()](#getData--) | Veriyi alır veya ayarlar. |
| [getDither()](#getDither--) | Gradyan titremeli mi. |
| [getExpansionCount()](#getExpansionCount--) | Genişleme sayısı ( = 2 Photoshop 6.0 için). |
| [getGradientLength_internalized()](#getGradientLength-internalized--) | Uzunluk (= 32 Photoshop 6.0 için) Ne için sorumlu olduğuna dair bilgi yok. |
| [getGradientMode()](#getGradientMode--) | Bu degrade için mod, 'Gradient Type' = 'Solid/Noise' (0/1) belirler. |
| [getGradientName()](#getGradientName--) | Degrade adı: Unicode dizesi, doldurulmuş. |
| [getHeader_internalized()](#getHeader-internalized--) | Üst bilgiyi alır veya ayarlar. |
| [getInterpolation()](#getInterpolation--) | Ara değerleme. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Gradient için ara değerleme yöntemini alır veya ayarlar. |
| [getKey()](#getKey--) | Katman kaynağı anahtarını alır. |
| [getLength()](#getLength--) | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| [getMaximumColor()](#getMaximumColor--) | PixelDataFormat.Rgba64Bpp formatının maksimum rengi. |
| [getMinimumColor()](#getMinimumColor--) | PixelDataFormat.Rgba64Bpp formatının minimum rengi. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Önek uzunluğunu alır. |
| [getPsdVersion()](#getPsdVersion--) | Bu kaynak için gereken minimum PSD sürümünü alır. |
| [getReverse()](#getReverse--) | Degrade ters çevrilmiş mi. |
| [getRndNumberSeed()](#getRndNumberSeed--) | Gürültü renk geçişi için renkleri oluşturmakta kullanılan rastgele sayı tohumu. |
| [getRoughness()](#getRoughness--) | Pürüzlülük faktörü. 'Gradient type' = 'Noise' olduğunda, 'Roughness' (0 - 2048) atanabilir. |
| [getShowTransparency()](#getShowTransparency--) | Şeffaflığı gösterme bayrağı. 'Gradient type' = 'Noise' olduğunda, 'Add transparency' true olarak atanabilir. |
| [getSignature()](#getSignature--) | Katman kaynağı imzasını alır. |
| [getTransparencyPoints()](#getTransparencyPoints--) | Şeffaflık noktalarını alır veya ayarlar. |
| [getUseVectorColor()](#getUseVectorColor--) | Vektör rengi kullanma bayrağı. |
| [hashCode()](#hashCode--) |  |
| [initGradientLength_internalized(short value)](#initGradientLength-internalized-short-) | Degrade uzunluğunu başlatır. |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Kaynağın PSB'ye özgü olup olmadığını belirler. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Bu örneğin kaynak PSB'ye özgü olup olmadığını gösteren bir değeri alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Kaynak verilerini belirtilen akış konteynerine kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Özel kaynak başlığını kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Başlık imzasını, tanımlayıcısını ve uzunluğunu kaydeder. |
| [setColorModel(short value)](#setColorModel-short-) | Renk Modeli. |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | Renk noktalarını alır veya ayarlar. |
| [setDither(boolean value)](#setDither-boolean-) | Gradyan titremeli mi. |
| [setExpansionCount(short value)](#setExpansionCount-short-) | Genişleme sayısı ( = 2 Photoshop 6.0 için). |
| [setGradientMode(int value)](#setGradientMode-int-) | Bu degrade için mod, 'Gradient Type' = 'Solid/Noise' (0/1) belirler. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Degrade adı: Unicode dizesi, doldurulmuş. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Üst bilgiyi alır veya ayarlar. |
| [setInterpolation(short value)](#setInterpolation-short-) | Ara değerleme. |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Gradient için ara değerleme yöntemini alır veya ayarlar. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat.Rgba64Bpp formatının maksimum rengi. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat.Rgba64Bpp formatının minimum rengi. |
| [setReverse(boolean value)](#setReverse-boolean-) | Degrade ters çevrilmiş mi. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | Gürültü renk geçişi için renkleri oluşturmakta kullanılan rastgele sayı tohumu. |
| [setRoughness(int value)](#setRoughness-int-) | Pürüzlülük faktörü. 'Gradient type' = 'Noise' olduğunda, 'Roughness' (0 - 2048) atanabilir. |
| [setShowTransparency(short value)](#setShowTransparency-short-) | Şeffaflığı gösterme bayrağı. 'Gradient type' = 'Noise' olduğunda, 'Add transparency' true olarak atanabilir. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | Şeffaflık noktalarını alır veya ayarlar. |
| [setUseVectorColor(short value)](#setUseVectorColor-short-) | Vektör rengi kullanma bayrağı. |
| [toString()](#toString--) | Bu örneği temsil eden bir String döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GrdmResource() {#GrdmResource--}
```
public GrdmResource()
```


### GrdmResource(int psdVersion) {#GrdmResource-int-}
```
public GrdmResource(int psdVersion)
```


Yeni bir [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| psdVersion | int | Kaynağın psd sürümü. |

### DefaultScale_internalized {#DefaultScale-internalized}
```
public static final int DefaultScale_internalized
```


Varsayılan ölçek.

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


Renk Modeli. 'Gradient type' = 'Noise' olduğunda, 'Color Model' RGB/SHB/LAB (3/4/6) olarak atanabilir.

**Returns:**
short
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


Renk noktalarını alır veya ayarlar.

Değer: Renk noktaları.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getData() {#getData--}
```
public final byte[] getData()
```


Veriyi alır veya ayarlar.

Değer: Veri.

**Returns:**
byte[]
### getDither() {#getDither--}
```
public final boolean getDither()
```


Gradyan titremeli mi.

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


Genişleme sayısı ( = 2 Photoshop 6.0 için).

**Returns:**
short
### getGradientLength_internalized() {#getGradientLength-internalized--}
```
public final short getGradientLength_internalized()
```


Uzunluk (= 32 Photoshop 6.0 için) Ne için sorumlu olduğuna dair bilgi yok.

**Returns:**
short
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


Bu degrade için mod, 'Gradient Type' = 'Solid/Noise' (0/1) belirler.

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


Degrade adı: Unicode dizesi, doldurulmuş.

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Üst bilgiyi alır veya ayarlar.

Değer: Başlık.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


Ara değerleme. 'Gradient Type' = 'Solid' (GradientMode = 0) olduğunda pürüzsüzlüğü belirler.

**Returns:**
short
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


Gradient için ara değerleme yöntemini alır veya ayarlar.

**Returns:**
long
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
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


PixelDataFormat.Rgba64Bpp formatının maksimum rengi. Renk ARGB kanallarına sahiptir, her kanal 16 bit'tir.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


PixelDataFormat.Rgba64Bpp formatının minimum rengi. Renk ARGB kanallarına sahiptir, her kanal 16 bit'tir.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
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


Bu kaynak için gereken minimum PSD sürümünü alır. Ara değerleme yöntemi açıkça depolandığında sürüm 3 gereklidir.

**Returns:**
int
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Degrade ters çevrilmiş mi.

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


Gürültü renk geçişi için renkleri oluşturmakta kullanılan rastgele sayı tohumu.

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


Pürüzlülük faktörü. 'Gradient type' = 'Noise' olduğunda, 'Roughness' (0 - 2048) atanabilir.

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final short getShowTransparency()
```


Şeffaflığı gösterme bayrağı. 'Gradient type' = 'Noise' olduğunda, 'Add transparency' true olarak atanabilir.

**Returns:**
short
### getSignature() {#getSignature--}
```
public int getSignature()
```


Katman kaynağı imzasını alır.

**Returns:**
int
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


Şeffaflık noktalarını alır veya ayarlar.

Değer: Şeffaflık noktaları.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
### getUseVectorColor() {#getUseVectorColor--}
```
public final short getUseVectorColor()
```


Vektör rengi kullanma bayrağı.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initGradientLength_internalized(short value) {#initGradientLength-internalized-short-}
```
public final void initGradientLength_internalized(short value)
```


Degrade uzunluğunu başlatır. GradientLength yalnızca okunabilir, bu yüzden sadece bir kez atanabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short | Değer. |

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


Kaynak verilerini belirtilen akış konteynerine kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Akış konteyneri. |
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

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


Renk Modeli. 'Gradient type' = 'Noise' olduğunda, 'Color Model' RGB/SHB/LAB (3/4/6) olarak atanabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


Renk noktalarını alır veya ayarlar.

Değer: Renk noktaları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Gradyan titremeli mi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


Genişleme sayısı ( = 2 Photoshop 6.0 için).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setGradientMode(int value) {#setGradientMode-int-}
```
public final void setGradientMode(int value)
```


Bu degrade için mod, 'Gradient Type' = 'Solid/Noise' (0/1) belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


Degrade adı: Unicode dizesi, doldurulmuş.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

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

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


Ara değerleme. 'Gradient Type' = 'Solid' (GradientMode = 0) olduğunda pürüzsüzlüğü belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


Gradient için ara değerleme yöntemini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


PixelDataFormat.Rgba64Bpp formatının maksimum rengi. Renk ARGB kanallarına sahiptir, her kanal 16 bit'tir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


PixelDataFormat.Rgba64Bpp formatının minimum rengi. Renk ARGB kanallarına sahiptir, her kanal 16 bit'tir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Degrade ters çevrilmiş mi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


Gürültü renk geçişi için renkleri oluşturmakta kullanılan rastgele sayı tohumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


Pürüzlülük faktörü. 'Gradient type' = 'Noise' olduğunda, 'Roughness' (0 - 2048) atanabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setShowTransparency(short value) {#setShowTransparency-short-}
```
public final void setShowTransparency(short value)
```


Şeffaflığı gösterme bayrağı. 'Gradient type' = 'Noise' olduğunda, 'Add transparency' true olarak atanabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


Şeffaflık noktalarını alır veya ayarlar.

Değer: Şeffaflık noktaları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

### setUseVectorColor(short value) {#setUseVectorColor-short-}
```
public final void setUseVectorColor(short value)
```


Vektör rengi kullanma bayrağı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | short |  |

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

