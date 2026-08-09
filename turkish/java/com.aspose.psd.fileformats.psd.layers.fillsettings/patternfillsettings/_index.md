---
title: "PatternFillSettings"
second_title: "Java için Aspose.PSD API Referansı"
description: "Desen doldurma efekti ayarları"
type: docs
weight: 20
url: /tr/java/com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings)
```
public class PatternFillSettings extends BaseFillSettings implements IPatternFillSettings
```

Desen doldurma efekti ayarları
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PatternFillSettings()](#PatternFillSettings--) | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) sınıfının yeni bir örneğini başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)](#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-) | LFX2 kaynak düğümlerini oluşturur. |
| [getAlignWithLayer()](#getAlignWithLayer--) | [link with layer] olup olmadığını belirten bir değeri alır veya ayarlar. |
| [getAngle()](#getAngle--) | Açıyı alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Rengi alır veya ayarlar. |
| [getCompressionModeOnSave_internalized()](#getCompressionModeOnSave-internalized--) |  |
| [getFillType()](#getFillType--) | Dolgu türü |
| [getHorizontalOffset()](#getHorizontalOffset--) | Yatay ofseti alır veya ayarlar. |
| [getLinked()](#getLinked--) | Bu [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) bağlı olup olmadığını belirten bir değeri alır veya ayarlar. |
| [getPatternData()](#getPatternData--) | Desen verisini alır veya ayarlar. |
| [getPatternHeight()](#getPatternHeight--) | Desenin yüksekliğini alır veya ayarlar. |
| [getPatternId()](#getPatternId--) | Desen tanımlayıcısını alır veya ayarlar. |
| [getPatternName()](#getPatternName--) | Desenin adını alır veya ayarlar. |
| [getPatternWidth()](#getPatternWidth--) | Desenin genişliğini alır veya ayarlar. |
| [getPhase_internalized()](#getPhase-internalized--) | Fazı alır veya ayarlar. |
| [getPointType()](#getPointType--) | Noktanın tipini alır veya ayarlar. |
| [getScale()](#getScale--) | Ölçeği alır veya ayarlar. |
| [getVerticalOffset()](#getVerticalOffset--) | Dikey ofseti alır veya ayarlar. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Değer değiştiğinde tetikler. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | [link with layer] olup olmadığını belirten bir değeri alır veya ayarlar. |
| [setAngle(double value)](#setAngle-double-) | Açıyı alır veya ayarlar. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Rengi alır veya ayarlar. |
| [setHorizontalOffset(int value)](#setHorizontalOffset-int-) | Yatay ofseti alır veya ayarlar. |
| [setLinked(boolean value)](#setLinked-boolean-) | Bu [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) bağlı olup olmadığını belirten bir değeri alır veya ayarlar. |
| [setPatternData(int[] value)](#setPatternData-int---) | Desen verisini alır veya ayarlar. |
| [setPatternData_internalized(int[] patternData, byte compressionModeOnSave)](#setPatternData-internalized-int---byte-) | Kaydetme sırasında kullanılacak pattern\u2019s piksel tamponunu ve sıkıştırma modunu ayarlar. |
| [setPatternHeight(int value)](#setPatternHeight-int-) | Desenin yüksekliğini alır veya ayarlar. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Desen tanımlayıcısını alır veya ayarlar. |
| [setPatternName(String value)](#setPatternName-java.lang.String-) | Desenin adını alır veya ayarlar. |
| [setPatternWidth(int value)](#setPatternWidth-int-) | Desenin genişliğini alır veya ayarlar. |
| [setPhase_internalized(OffsetEntity value)](#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | Fazı alır veya ayarlar. |
| [setPointType(String value)](#setPointType-java.lang.String-) | Noktanın tipini alır veya ayarlar. |
| [setScale(double value)](#setScale-double-) | Ölçeği alır veya ayarlar. |
| [setVerticalOffset(int value)](#setVerticalOffset-int-) | Dikey ofseti alır veya ayarlar. |
| [setupDefaultPatternData_internalized(PatternFillSettings settings)](#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | Desenin varsayılan verilerini [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) örneğine ayarlar. |
| [toString()](#toString--) |  |
| [updatePatternData_internalized(PattResourceData pattResourceData)](#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-) | Desen özelliklerini [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) örneğinden günceller. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PatternFillSettings() {#PatternFillSettings--}
```
public PatternFillSettings()
```


[PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) sınıfının yeni bir örneğini başlatır.

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset) {#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-}
```
public static System.Collections.Generic.IGenericEnumerable<OSTypeStructure> generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)
```


LFX2 kaynak düğümlerini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pointType | java.lang.String | Noktanın tipi. |
| color | [Color](../../com.aspose.psd/color) | Renk. |
| patternName | java.lang.String | Desenin adı. |
| tanımlayıcı | java.lang.String | Tanımlayıcı. |
| ölçek | double | Ölçek. |
| bağlı | boolean | eğer  true  [linked] olarak ayarlanmışsa. |
| offset | [PointF](../../com.aspose.psd/pointf) | Ofset. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) listesi
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


[link with layer] olup olmadığını belirten bir değeri alır veya ayarlar.

Değer:  true  eğer [link with layer]; aksi takdirde,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Açıyı alır veya ayarlar.

Değer: Açı.

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


Rengi alır veya ayarlar.

Değer: Renk.

**Returns:**
[Color](../../com.aspose.psd/color)
### getCompressionModeOnSave_internalized() {#getCompressionModeOnSave-internalized--}
```
public final byte getCompressionModeOnSave_internalized()
```




**Returns:**
byte
### getFillType() {#getFillType--}
```
public int getFillType()
```


Dolgu türü

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final int getHorizontalOffset()
```


Yatay ofseti alır veya ayarlar.

Değer: Yatay ofset.

**Returns:**
int
### getLinked() {#getLinked--}
```
public final boolean getLinked()
```


Bu [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) bağlı olup olmadığını belirten bir değeri alır veya ayarlar.

Değer:  true  eğer bağlı; aksi takdirde,  false .

**Returns:**
boolean
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


Desen verisini alır veya ayarlar.

Değer: Desen verisi.

**Returns:**
int[]
### getPatternHeight() {#getPatternHeight--}
```
public final int getPatternHeight()
```


Desenin yüksekliğini alır veya ayarlar.

Değer: Desenin yüksekliği.

**Returns:**
int
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Desen tanımlayıcısını alır veya ayarlar.

Değer: Desen tanımlayıcısı.

**Returns:**
java.lang.String
### getPatternName() {#getPatternName--}
```
public final String getPatternName()
```


Desenin adını alır veya ayarlar.

Değer: Desenin adı.

**Returns:**
java.lang.String
### getPatternWidth() {#getPatternWidth--}
```
public final int getPatternWidth()
```


Desenin genişliğini alır veya ayarlar.

Değer: Desenin genişliği.

**Returns:**
int
### getPhase_internalized() {#getPhase-internalized--}
```
public final OffsetEntity getPhase_internalized()
```


Fazı alır veya ayarlar.

Değer: Faz.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
### getPointType() {#getPointType--}
```
public final String getPointType()
```


Noktanın tipini alır veya ayarlar.

Değer: Noktanın türü.

**Returns:**
java.lang.String
### getScale() {#getScale--}
```
public final double getScale()
```


Ölçeği alır veya ayarlar.

Değer: Ölçek.

**Returns:**
double
### getVerticalOffset() {#getVerticalOffset--}
```
public final int getVerticalOffset()
```


Dikey ofseti alır veya ayarlar.

Değer: Dikey ofset.

**Returns:**
int
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




### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


Değer değiştiğinde tetikler.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


[link with layer] olup olmadığını belirten bir değeri alır veya ayarlar.

Değer:  true  eğer [link with layer]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Açıyı alır veya ayarlar.

Değer: Açı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Rengi alır veya ayarlar.

Değer: Renk.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setHorizontalOffset(int value) {#setHorizontalOffset-int-}
```
public final void setHorizontalOffset(int value)
```


Yatay ofseti alır veya ayarlar.

Değer: Yatay ofset.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Bu [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) bağlı olup olmadığını belirten bir değeri alır veya ayarlar.

Değer:  true  eğer bağlı; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setPatternData(int[] value) {#setPatternData-int---}
```
public final void setPatternData(int[] value)
```


Desen verisini alır veya ayarlar.

Değer: Desen verisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

### setPatternData_internalized(int[] patternData, byte compressionModeOnSave) {#setPatternData-internalized-int---byte-}
```
public final void setPatternData_internalized(int[] patternData, byte compressionModeOnSave)
```


Kaydetme sırasında kullanılacak pattern\u2019s piksel tamponunu ve sıkıştırma modunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| patternData | int[] | 0xAARRGGBB içinde 32-bit pikseller. |
| compressionModeOnSave | byte | Desen verisinin sıkıştırmasını tanımlamak için PSD dosyası kaydedilirken kullanılan sıkıştırma modu. |

### setPatternHeight(int value) {#setPatternHeight-int-}
```
public final void setPatternHeight(int value)
```


Desenin yüksekliğini alır veya ayarlar.

Değer: Desenin yüksekliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Desen tanımlayıcısını alır veya ayarlar.

Değer: Desen tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setPatternName(String value) {#setPatternName-java.lang.String-}
```
public final void setPatternName(String value)
```


Desenin adını alır veya ayarlar.

Değer: Desenin adı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setPatternWidth(int value) {#setPatternWidth-int-}
```
public final void setPatternWidth(int value)
```


Desenin genişliğini alır veya ayarlar.

Değer: Desenin genişliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setPhase_internalized(OffsetEntity value) {#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setPhase_internalized(OffsetEntity value)
```


Fazı alır veya ayarlar.

Değer: Faz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setPointType(String value) {#setPointType-java.lang.String-}
```
public final void setPointType(String value)
```


Noktanın tipini alır veya ayarlar.

Değer: Noktanın türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


Ölçeği alır veya ayarlar.

Değer: Ölçek.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### setVerticalOffset(int value) {#setVerticalOffset-int-}
```
public final void setVerticalOffset(int value)
```


Dikey ofseti alır veya ayarlar.

Değer: Dikey ofset.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### setupDefaultPatternData_internalized(PatternFillSettings settings) {#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public static void setupDefaultPatternData_internalized(PatternFillSettings settings)
```


Desenin varsayılan verilerini [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) örneğine ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| settings | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) | Desen dolgu ayarları. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updatePatternData_internalized(PattResourceData pattResourceData) {#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-}
```
public final void updatePatternData_internalized(PattResourceData pattResourceData)
```


Desen özelliklerini [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) örneğinden günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pattResourceData | [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | Desen verisine sahip [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) örneği. |

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

