---
title: "GdFlResource"
second_title: "Java için Aspose.PSD API Referansı"
description: "Sınıf GdFlResource."
type: docs
weight: 33
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.FillLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/filllayerresource)
```
public class GdFlResource extends FillLayerResource
```

GdFlResource sınıfı. Bu kaynak, kırpılmış öğenin karıştırılması hakkında bilgi içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GdFlResource()](#GdFlResource--) | Yeni bir [.GdFlResource](../../null/\#GdFlResource) sınıfının örneğini başlatır. |
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
| [addUnknownStructure_internalized(OSTypeStructure structure)](#addUnknownStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Bilinmeyen yapıyı ekler. |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Kaynağın PSB'ye özgü olup olmadığını kontrol eder ve ayarlar. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateDefaultControlPoints_internalized()](#generateDefaultControlPoints-internalized--) | Varsayılan kontrol noktalarını oluşturur. |
| [generateDefaultTransparencyPoints_internalized()](#generateDefaultTransparencyPoints-internalized--) | Varsayılan şeffaflık noktalarını oluşturur. |
| [getAlignWithLayer()](#getAlignWithLayer--) | Katmanla hizalanıp [align with layer] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getAngle()](#getAngle--) | Açıyı alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | RGB'nin rengini alır. |
| [getColorModel()](#getColorModel--) | Renk Modeli - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl"). |
| [getColorPoints()](#getColorPoints--) | Renk noktalarını alır. |
| [getDither()](#getDither--) | Bu [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) nesnesinin titreme olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getGradientInterval()](#getGradientInterval--) | Renk geçişi aralığını alır veya ayarlar. |
| [getGradientMode()](#getGradientMode--) | Bu renk geçişi için mod. |
| [getGradientName()](#getGradientName--) | Gradyanın adını alır veya ayarlar. |
| [getGradientType()](#getGradientType--) |  |
| [getHeader_internalized()](#getHeader-internalized--) | Üst bilgiyi alır veya ayarlar. |
| [getHorizontalOffset()](#getHorizontalOffset--) | Yatay ofseti alır veya ayarlar. |
| [getInterpolationMethod()](#getInterpolationMethod--) | Gradient için ara değerleme yöntemini alır veya ayarlar. |
| [getKey()](#getKey--) | Katman kaynağı anahtarını alır. |
| [getLength()](#getLength--) | Katman kaynağı uzunluğunu bayt cinsinden alır. |
| [getMaximumColor()](#getMaximumColor--) | PixelDataFormat'ın maksimum rengi. |
| [getMinimumColor()](#getMinimumColor--) | PixelDataFormat'ın minimum rengi. |
| [getOffset_internalized()](#getOffset-internalized--) | Ofseti alır veya ayarlar. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Önek uzunluğunu alır. |
| [getPsdVersion()](#getPsdVersion--) | Katman kaynağı için gereken minimum psd sürümünü alır. |
| [getReverse()](#getReverse--) | Bu [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) nesnesinin ters olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getRndNumberSeed()](#getRndNumberSeed--) | Gürültü renk geçişi için renkleri oluşturmakta kullanılan rastgele sayı tohumu. |
| [getRoughness()](#getRoughness--) | Pürüz faktörü. |
| [getScale()](#getScale--) | Ölçeği alır veya ayarlar. |
| [getShowTransparency()](#getShowTransparency--) | Şeffaflığı gösterme bayrağı. |
| [getSignature()](#getSignature--) | Katman kaynağı imzasını alır. |
| [getTransparencyPoints()](#getTransparencyPoints--) | Şeffaflık noktalarını alır. |
| [getUseVectorColor()](#getUseVectorColor--) | Vektör rengi kullanma bayrağı. |
| [getVerticalOffset()](#getVerticalOffset--) | Dikey ofseti alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Kaynağın PSB'ye özgü olup olmadığını belirler. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Bu örneğin kaynak PSB'ye özgü olup olmadığını gösteren bir değeri alır. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Kaynağı belirtilen akış konteynerine kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Özel kaynak başlığını kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Başlık imzasını, tanımlayıcısını ve uzunluğunu kaydeder. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Katmanla hizalanıp [align with layer] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setAngle(double value)](#setAngle-double-) |  |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | RGB'nin rengini alır. |
| [setColorModel(String value)](#setColorModel-java.lang.String-) | Renk Modeli - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl"). |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | Renk noktalarını alır. |
| [setDither(boolean value)](#setDither-boolean-) | Bu [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) nesnesinin titreme olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setGradientInterval(double value)](#setGradientInterval-double-) | Renk geçişi aralığını alır veya ayarlar. |
| [setGradientMode(String value)](#setGradientMode-java.lang.String-) | Bu renk geçişi için mod. |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | Gradyanın adını alır veya ayarlar. |
| [setGradientType(int value)](#setGradientType-int-) |  |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Üst bilgiyi alır veya ayarlar. |
| [setHorizontalOffset(double value)](#setHorizontalOffset-double-) |  |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | Gradient için ara değerleme yöntemini alır veya ayarlar. |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat'ın maksimum rengi. |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat'ın minimum rengi. |
| [setOffset_internalized(OffsetEntity value)](#setOffset-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | Ofseti alır veya ayarlar. |
| [setReverse(boolean value)](#setReverse-boolean-) | Bu [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) nesnesinin ters olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | Gürültü renk geçişi için renkleri oluşturmakta kullanılan rastgele sayı tohumu. |
| [setRoughness(int value)](#setRoughness-int-) | Pürüz faktörü. |
| [setScale(double value)](#setScale-double-) | Ölçeği alır veya ayarlar. |
| [setShowTransparency(boolean value)](#setShowTransparency-boolean-) | Şeffaflığı gösterme bayrağı. |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | Şeffaflık noktalarını alır. |
| [setUseVectorColor(boolean value)](#setUseVectorColor-boolean-) | Vektör rengi kullanma bayrağı. |
| [setVerticalOffset(double value)](#setVerticalOffset-double-) |  |
| [toString()](#toString--) | Bu örneği temsil eden bir String döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GdFlResource() {#GdFlResource--}
```
public GdFlResource()
```


Yeni bir [.GdFlResource](../../null/\#GdFlResource) sınıfının örneğini başlatır.

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

### addUnknownStructure_internalized(OSTypeStructure structure) {#addUnknownStructure-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public void addUnknownStructure_internalized(OSTypeStructure structure)
```


Bilinmeyen yapıyı ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Yapı. |

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
### generateDefaultControlPoints_internalized() {#generateDefaultControlPoints-internalized--}
```
public static IGradientColorPoint[] generateDefaultControlPoints_internalized()
```


Varsayılan kontrol noktalarını oluşturur.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[] - Varsayılan kontrol noktaları.
### generateDefaultTransparencyPoints_internalized() {#generateDefaultTransparencyPoints-internalized--}
```
public static IGradientTransparencyPoint[] generateDefaultTransparencyPoints_internalized()
```


Varsayılan şeffaflık noktalarını oluşturur.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[] - Varsayılan şeffaflık noktaları.
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Katmanla hizalanıp [align with layer] olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer [align with layer]; aksi takdirde,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public double getAngle()
```


Açıyı alır veya ayarlar.

Açı.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public final Color getColor()
```


RGB'nin rengini alır.

**Returns:**
[Color](../../com.aspose.psd/color) - The RGB Color
### getColorModel() {#getColorModel--}
```
public final String getColorModel()
```


Renk Modeli - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl").

**Returns:**
java.lang.String
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


Renk noktalarını alır.

Değer: Renk noktaları.

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getDither() {#getDither--}
```
public final boolean getDither()
```


Bu [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) nesnesinin titreme olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer titreme; aksi takdirde,  false .

**Returns:**
boolean
### getGradientInterval() {#getGradientInterval--}
```
public final double getGradientInterval()
```


Renk geçişi aralığını alır veya ayarlar.

Değer: Renk geçişi aralığı.

**Returns:**
double
### getGradientMode() {#getGradientMode--}
```
public final String getGradientMode()
```


Bu renk geçişi için mod. 'Gradient Type' = 'Solid/Noise' = "CstS"/"ClNs" belirler.

**Returns:**
java.lang.String
### getGradientName() {#getGradientName--}
```
public String getGradientName()
```


Gradyanın adını alır veya ayarlar.

Değer: Gradyanın adı.

**Returns:**
java.lang.String
### getGradientType() {#getGradientType--}
```
public int getGradientType()
```




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
### getHorizontalOffset() {#getHorizontalOffset--}
```
public double getHorizontalOffset()
```


Yatay ofseti alır veya ayarlar.

Yatay kaydırma.

**Returns:**
double
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


PixelDataFormat'ın maksimum rengi.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


PixelDataFormat'ın minimum rengi.

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getOffset_internalized() {#getOffset-internalized--}
```
public final OffsetEntity getOffset_internalized()
```


Ofseti alır veya ayarlar.

Değer: Ofset.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
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
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


Bu [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) nesnesinin ters olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer ters; aksi takdirde,  false .

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


Pürüz faktörü.

**Returns:**
int
### getScale() {#getScale--}
```
public final double getScale()
```


Ölçeği alır veya ayarlar.

**Returns:**
double
### getShowTransparency() {#getShowTransparency--}
```
public final boolean getShowTransparency()
```


Şeffaflığı gösterme bayrağı.

**Returns:**
boolean
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


Şeffaflık noktalarını alır.

Değer: Şeffaflık noktaları.

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
### getUseVectorColor() {#getUseVectorColor--}
```
public final boolean getUseVectorColor()
```


Vektör rengi kullanma bayrağı.

**Returns:**
boolean
### getVerticalOffset() {#getVerticalOffset--}
```
public double getVerticalOffset()
```


Dikey ofseti alır veya ayarlar.

Dikey kaydırma.

**Returns:**
double
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

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Katmanla hizalanıp [align with layer] olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer [align with layer]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public void setAngle(double value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


RGB'nin rengini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setColorModel(String value) {#setColorModel-java.lang.String-}
```
public final void setColorModel(String value)
```


Renk Modeli - RGB/HSB/LAB ("RGBC"/"HSBl"/"LbCl").

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


Renk noktalarını alır.

Değer: Renk noktaları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


Bu [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) nesnesinin titreme olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer titreme; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setGradientInterval(double value) {#setGradientInterval-double-}
```
public final void setGradientInterval(double value)
```


Renk geçişi aralığını alır veya ayarlar.

Değer: Renk geçişi aralığı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setGradientMode(String value) {#setGradientMode-java.lang.String-}
```
public final void setGradientMode(String value)
```


Bu renk geçişi için mod. 'Gradient Type' = 'Solid/Noise' = "CstS"/"ClNs" belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public void setGradientName(String value)
```


Gradyanın adını alır veya ayarlar.

Değer: Gradyanın adı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setGradientType(int value) {#setGradientType-int-}
```
public void setGradientType(int value)
```




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

### setHorizontalOffset(double value) {#setHorizontalOffset-double-}
```
public void setHorizontalOffset(double value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

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


PixelDataFormat'ın maksimum rengi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


PixelDataFormat'ın minimum rengi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setOffset_internalized(OffsetEntity value) {#setOffset-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setOffset_internalized(OffsetEntity value)
```


Ofseti alır veya ayarlar.

Değer: Ofset.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


Bu [GdFlResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/gdflresource) nesnesinin ters olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer ters; aksi takdirde,  false .

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


Pürüz faktörü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


Ölçeği alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setShowTransparency(boolean value) {#setShowTransparency-boolean-}
```
public final void setShowTransparency(boolean value)
```


Şeffaflığı gösterme bayrağı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


Şeffaflık noktalarını alır.

Değer: Şeffaflık noktaları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

### setUseVectorColor(boolean value) {#setUseVectorColor-boolean-}
```
public final void setUseVectorColor(boolean value)
```


Vektör rengi kullanma bayrağı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setVerticalOffset(double value) {#setVerticalOffset-double-}
```
public void setVerticalOffset(double value)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

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

