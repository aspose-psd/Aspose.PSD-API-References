---
title: "ArtDResource"
second_title: "Java için Aspose.PSD API Referansı"
description: "PsdImage.GlobalLayerResources/ için Artboard bilgi verileri."
type: docs
weight: 12
url: /tr/java/com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artdresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources.BaseArtboardInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/baseartboardinforesource)
```
public final class ArtDResource extends BaseArtboardInfoResource
```

PsdImage.GlobalLayerResources ([PsdImage.getGlobalLayerResources](../../com.aspose.psd.fileformats.psd/psdimage\#getGlobalLayerResources)/[PsdImage.setGlobalLayerResources(LayerResource[])](../../com.aspose.psd.fileformats.psd/psdimage\#setGlobalLayerResources-LayerResource---)) için Artboard bilgi verileri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ArtDResource()](#ArtDResource--) | [ArtDResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artdresource) sınıfının yeni bir örneğini başlatır. |
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
| [getArtboardCount_internalized()](#getArtboardCount-internalized--) | Art-boards sayısını alır veya ayarlar. |
| [getAutoExpandOffset_internalized()](#getAutoExpandOffset-internalized--) | Otomatik genişletme ofsetini alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getClassId_internalized()](#getClassId-internalized--) | Kaynak sınıf kimliğini alır veya ayarlar. |
| [getClassName_internalized()](#getClassName-internalized--) | Kaynak sınıf adını alır veya ayarlar. |
| [getDocDefaultNewArtboardBackgroundColor_internalized()](#getDocDefaultNewArtboardBackgroundColor-internalized--) | DocDefaultNewArtboardBackgroundColor ([.getDocDefaultNewArtboardBackgroundColor\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)) değerini alır veya ayarlar. |
| [getDocDefaultNewArtboardBackgroundType_internalized()](#getDocDefaultNewArtboardBackgroundType-internalized--) | DocDefaultNewArtboardBackgroundType ([.getDocDefaultNewArtboardBackgroundType\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType\_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType-internalized-int-)) değerini alır veya ayarlar. |
| [getHeader_internalized()](#getHeader-internalized--) | Üst bilgiyi alır veya ayarlar. |
| [getItems()](#getItems--) | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) öğelerini alır veya ayarlar. |
| [getKey()](#getKey--) | Katman kaynağı anahtarını alır. |
| [getLength()](#getLength--) |    |
| [getOriginPoint_internalized()](#getOriginPoint-internalized--) | Orijin noktasını alır veya ayarlar. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Önek uzunluğunu alır. |
| [getPsdVersion()](#getPsdVersion--) | Katman kaynağı için gereken minimum psd sürümünü alır. |
| [getSignature()](#getSignature--) | Katman kaynağı imzasını alır. |
| [getVersion_internalized()](#getVersion-internalized--) | Kaynak sürümünü alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [isAutoExpandEnabled_internalized()](#isAutoExpandEnabled-internalized--) | Alır veya ayarlar IsAutoExpandEnabled ([.isAutoExpandEnabled\_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled\_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)). |
| [isAutoNestEnabled_internalized()](#isAutoNestEnabled-internalized--) | Alır veya ayarlar IsAutoNestEnabled ([.isAutoNestEnabled\_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled\_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)). |
| [isAutoPositionEnabled_internalized()](#isAutoPositionEnabled-internalized--) | Alır veya ayarlar IsAutoPositionEnabled ([.isAutoPositionEnabled\_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled\_internalized(boolean)](../../null/\#setAutoPositionEnabled-internalized-boolean-)). |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Kaynağın PSB'ye özgü olup olmadığını belirler. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Bu örneğin kaynak PSB'ye özgü olup olmadığını gösteren bir değeri alır. |
| [isShrinkwrapOnSaveEnabled_internalized()](#isShrinkwrapOnSaveEnabled-internalized--) | Alır veya ayarlar IsShrinkwrapOnSaveEnabled ([.isShrinkwrapOnSaveEnabled\_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled\_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled-internalized-boolean-)). |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Kaynağı belirtilen akış konteynerine kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Özel kaynak başlığını kaydeder. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Başlık imzasını, tanımlayıcısını ve uzunluğunu kaydeder. |
| [setArtboardCount_internalized(int value)](#setArtboardCount-internalized-int-) | Art-boards sayısını alır veya ayarlar. |
| [setAutoExpandEnabled_internalized(boolean value)](#setAutoExpandEnabled-internalized-boolean-) | Alır veya ayarlar IsAutoExpandEnabled ([.isAutoExpandEnabled\_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled\_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)). |
| [setAutoExpandOffset_internalized(PointF value)](#setAutoExpandOffset-internalized-com.aspose.psd.PointF-) | Otomatik genişletme ofsetini alır veya ayarlar. |
| [setAutoNestEnabled_internalized(boolean value)](#setAutoNestEnabled-internalized-boolean-) | Alır veya ayarlar IsAutoNestEnabled ([.isAutoNestEnabled\_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled\_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)). |
| [setAutoPositionEnabled_internalized(boolean value)](#setAutoPositionEnabled-internalized-boolean-) | Alır veya ayarlar IsAutoPositionEnabled ([.isAutoPositionEnabled\_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled\_internalized(boolean)](../../null/\#setAutoPositionEnabled-internalized-boolean-)). |
| [setClassId_internalized(ClassID value)](#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-) | Kaynak sınıf kimliğini alır veya ayarlar. |
| [setClassName_internalized(String value)](#setClassName-internalized-java.lang.String-) | Kaynak sınıf adını alır veya ayarlar. |
| [setDocDefaultNewArtboardBackgroundColor_internalized(Color value)](#setDocDefaultNewArtboardBackgroundColor-internalized-com.aspose.psd.Color-) | DocDefaultNewArtboardBackgroundColor ([.getDocDefaultNewArtboardBackgroundColor\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)) değerini alır veya ayarlar. |
| [setDocDefaultNewArtboardBackgroundType_internalized(int value)](#setDocDefaultNewArtboardBackgroundType-internalized-int-) | DocDefaultNewArtboardBackgroundType ([.getDocDefaultNewArtboardBackgroundType\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType\_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType-internalized-int-)) değerini alır veya ayarlar. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Üst bilgiyi alır veya ayarlar. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) öğelerini alır veya ayarlar. |
| [setOriginPoint_internalized(PointF value)](#setOriginPoint-internalized-com.aspose.psd.PointF-) | Orijin noktasını alır veya ayarlar. |
| [setShrinkwrapOnSaveEnabled_internalized(boolean value)](#setShrinkwrapOnSaveEnabled-internalized-boolean-) | Alır veya ayarlar IsShrinkwrapOnSaveEnabled ([.isShrinkwrapOnSaveEnabled\_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled\_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled-internalized-boolean-)). |
| [setVersion_internalized(int value)](#setVersion-internalized-int-) | Kaynak sürümünü alır veya ayarlar. |
| [toString()](#toString--) | Bu örneği temsil eden bir String döndürür. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ArtDResource() {#ArtDResource--}
```
public ArtDResource()
```


[ArtDResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.artboardresources/artdresource) sınıfının yeni bir örneğini başlatır.

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
### getArtboardCount_internalized() {#getArtboardCount-internalized--}
```
public final int getArtboardCount_internalized()
```


Art-boards sayısını alır veya ayarlar.

**Returns:**
int
### getAutoExpandOffset_internalized() {#getAutoExpandOffset-internalized--}
```
public final PointF getAutoExpandOffset_internalized()
```


Otomatik genişletme ofsetini alır veya ayarlar.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getClassId_internalized() {#getClassId-internalized--}
```
public final ClassID getClassId_internalized()
```


Kaynak sınıf kimliğini alır veya ayarlar.

**Returns:**
[ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid)
### getClassName_internalized() {#getClassName-internalized--}
```
public final String getClassName_internalized()
```


Kaynak sınıf adını alır veya ayarlar.

**Returns:**
java.lang.String
### getDocDefaultNewArtboardBackgroundColor_internalized() {#getDocDefaultNewArtboardBackgroundColor-internalized--}
```
public final Color getDocDefaultNewArtboardBackgroundColor_internalized()
```


DocDefaultNewArtboardBackgroundColor ([.getDocDefaultNewArtboardBackgroundColor\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)) değerini alır veya ayarlar.

**Returns:**
[Color](../../com.aspose.psd/color)
### getDocDefaultNewArtboardBackgroundType_internalized() {#getDocDefaultNewArtboardBackgroundType-internalized--}
```
public final int getDocDefaultNewArtboardBackgroundType_internalized()
```


DocDefaultNewArtboardBackgroundType ([.getDocDefaultNewArtboardBackgroundType\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType\_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType-internalized-int-)) değerini alır veya ayarlar.

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
### getItems() {#getItems--}
```
public final OSTypeStructure[] getItems()
```


[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) öğelerini alır veya ayarlar.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
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


  

**Returns:**
int
### getOriginPoint_internalized() {#getOriginPoint-internalized--}
```
public final PointF getOriginPoint_internalized()
```


Orijin noktasını alır veya ayarlar.

**Returns:**
[PointF](../../com.aspose.psd/pointf)
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
### getSignature() {#getSignature--}
```
public int getSignature()
```


Katman kaynağı imzasını alır.

**Returns:**
int
### getVersion_internalized() {#getVersion-internalized--}
```
public final int getVersion_internalized()
```


Kaynak sürümünü alır veya ayarlar.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isAutoExpandEnabled_internalized() {#isAutoExpandEnabled-internalized--}
```
public final boolean isAutoExpandEnabled_internalized()
```


Alır veya ayarlar IsAutoExpandEnabled ([.isAutoExpandEnabled\_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled\_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)).

**Returns:**
boolean
### isAutoNestEnabled_internalized() {#isAutoNestEnabled-internalized--}
```
public final boolean isAutoNestEnabled_internalized()
```


Alır veya ayarlar IsAutoNestEnabled ([.isAutoNestEnabled\_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled\_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)).

**Returns:**
boolean
### isAutoPositionEnabled_internalized() {#isAutoPositionEnabled-internalized--}
```
public final boolean isAutoPositionEnabled_internalized()
```


Alır veya ayarlar IsAutoPositionEnabled ([.isAutoPositionEnabled\_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled\_internalized(boolean)](../../null/\#setAutoPositionEnabled-internalized-boolean-)).

**Returns:**
boolean
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
### isShrinkwrapOnSaveEnabled_internalized() {#isShrinkwrapOnSaveEnabled-internalized--}
```
public final boolean isShrinkwrapOnSaveEnabled_internalized()
```


Alır veya ayarlar IsShrinkwrapOnSaveEnabled ([.isShrinkwrapOnSaveEnabled\_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled\_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled-internalized-boolean-)).

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

### setArtboardCount_internalized(int value) {#setArtboardCount-internalized-int-}
```
public final void setArtboardCount_internalized(int value)
```


Art-boards sayısını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setAutoExpandEnabled_internalized(boolean value) {#setAutoExpandEnabled-internalized-boolean-}
```
public final void setAutoExpandEnabled_internalized(boolean value)
```


Alır veya ayarlar IsAutoExpandEnabled ([.isAutoExpandEnabled\_internalized](../../null/\#isAutoExpandEnabled-internalized)/[.setAutoExpandEnabled\_internalized(boolean)](../../null/\#setAutoExpandEnabled-internalized-boolean-)).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setAutoExpandOffset_internalized(PointF value) {#setAutoExpandOffset-internalized-com.aspose.psd.PointF-}
```
public final void setAutoExpandOffset_internalized(PointF value)
```


Otomatik genişletme ofsetini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setAutoNestEnabled_internalized(boolean value) {#setAutoNestEnabled-internalized-boolean-}
```
public final void setAutoNestEnabled_internalized(boolean value)
```


Alır veya ayarlar IsAutoNestEnabled ([.isAutoNestEnabled\_internalized](../../null/\#isAutoNestEnabled-internalized)/[.setAutoNestEnabled\_internalized(boolean)](../../null/\#setAutoNestEnabled-internalized-boolean-)).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setAutoPositionEnabled_internalized(boolean value) {#setAutoPositionEnabled-internalized-boolean-}
```
public final void setAutoPositionEnabled_internalized(boolean value)
```


Alır veya ayarlar IsAutoPositionEnabled ([.isAutoPositionEnabled\_internalized](../../null/\#isAutoPositionEnabled-internalized)/[.setAutoPositionEnabled\_internalized(boolean)](../../null/\#setAutoPositionEnabled-internalized-boolean-)).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setClassId_internalized(ClassID value) {#setClassId-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.ClassID-}
```
public final void setClassId_internalized(ClassID value)
```


Kaynak sınıf kimliğini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ClassID](../../com.aspose.psd.fileformats.psd.layers.layerresources/classid) |  |

### setClassName_internalized(String value) {#setClassName-internalized-java.lang.String-}
```
public final void setClassName_internalized(String value)
```


Kaynak sınıf adını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setDocDefaultNewArtboardBackgroundColor_internalized(Color value) {#setDocDefaultNewArtboardBackgroundColor-internalized-com.aspose.psd.Color-}
```
public final void setDocDefaultNewArtboardBackgroundColor_internalized(Color value)
```


DocDefaultNewArtboardBackgroundColor ([.getDocDefaultNewArtboardBackgroundColor\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundColor-internalized)/[.setDocDefaultNewArtboardBackgroundColor()](../../null/\#setDocDefaultNewArtboardBackgroundColor--)) değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setDocDefaultNewArtboardBackgroundType_internalized(int value) {#setDocDefaultNewArtboardBackgroundType-internalized-int-}
```
public final void setDocDefaultNewArtboardBackgroundType_internalized(int value)
```


DocDefaultNewArtboardBackgroundType ([.getDocDefaultNewArtboardBackgroundType\_internalized](../../null/\#getDocDefaultNewArtboardBackgroundType-internalized)/[.setDocDefaultNewArtboardBackgroundType\_internalized(int)](../../null/\#setDocDefaultNewArtboardBackgroundType-internalized-int-)) değerini alır veya ayarlar.

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

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final void setItems(OSTypeStructure[] value)
```


[OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) öğelerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setOriginPoint_internalized(PointF value) {#setOriginPoint-internalized-com.aspose.psd.PointF-}
```
public final void setOriginPoint_internalized(PointF value)
```


Orijin noktasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [PointF](../../com.aspose.psd/pointf) |  |

### setShrinkwrapOnSaveEnabled_internalized(boolean value) {#setShrinkwrapOnSaveEnabled-internalized-boolean-}
```
public final void setShrinkwrapOnSaveEnabled_internalized(boolean value)
```


Alır veya ayarlar IsShrinkwrapOnSaveEnabled ([.isShrinkwrapOnSaveEnabled\_internalized](../../null/\#isShrinkwrapOnSaveEnabled-internalized)/[.setShrinkwrapOnSaveEnabled\_internalized(boolean)](../../null/\#setShrinkwrapOnSaveEnabled-internalized-boolean-)).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setVersion_internalized(int value) {#setVersion-internalized-int-}
```
public final void setVersion_internalized(int value)
```


Kaynak sürümünü alır veya ayarlar.

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

