---
title: "SmartFilter"
second_title: "Java için Aspose.PSD API Referansı"
description: "Akıllı filtrelerin temel mantığını işlemek için sınıf."
type: docs
weight: 13
url: /tr/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, java.lang.Cloneable
```
public abstract class SmartFilter implements System.ICloneable, Cloneable
```

Akıllı filtrelerin temel mantığını işlemek için sınıf.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SmartFilter()](#SmartFilter--) | Yeni bir [SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | Geçerli filtreyi girdi  RasterImage  görüntüsüne uygular. |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | Geçerli filtreyi girdi [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) maske verilerine uygular. |
| [deepClone()](#deepClone--) | Türün geçerli örneğinin üye bazlı klonunu oluşturur. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Karışım modunu alır veya ayarlar. |
| [getClass()](#getClass--) |  |
| [getFilterId()](#getFilterId--) | Akıllı filtre türü tanımlayıcısını alır. |
| [getName()](#getName--) | Akıllı filtre adını alır. |
| [getOpacity()](#getOpacity--) | Akıllı filtrenin opaklık değerini alır veya ayarlar. |
| [getSourceDescriptor()](#getSourceDescriptor--) | Akıllı filtre verileriyle kaynak tanımlayıcı yapısı. |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | Akıllı filtrenin etkin durumunu alır veya ayarlar. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Karışım modunu alır veya ayarlar. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Akıllı filtrenin etkin durumunu alır veya ayarlar. |
| [setOpacity(double value)](#setOpacity-double-) | Akıllı filtrenin opaklık değerini alır veya ayarlar. |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | Akıllı filtre bilgilerini [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) verisine kaydeder ve döndürür. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SmartFilter() {#SmartFilter--}
```
public SmartFilter()
```


Yeni bir [SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) sınıfının örneğini başlatır.

### apply(RasterImage rasterImage) {#apply-com.aspose.psd.RasterImage-}
```
public final void apply(RasterImage rasterImage)
```


Geçerli filtreyi girdi  RasterImage  görüntüsüne uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | Raster görüntüsü. |

### applyToMask(Layer layerWithMask) {#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void applyToMask(Layer layerWithMask)
```


Geçerli filtreyi girdi [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) maske verilerine uygular.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layerWithMask | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Maske verilerine sahip katman. |

### deepClone() {#deepClone--}
```
public final SmartFilter deepClone()
```


Türün geçerli örneğinin üye bazlı klonunu oluşturur.

**Returns:**
[SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) - Returns the memberwise clone of the current instance of the type.
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
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Karışım modunu alır veya ayarlar.

**Returns:**
long
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFilterId() {#getFilterId--}
```
public abstract int getFilterId()
```


Akıllı filtre türü tanımlayıcısını alır.

**Returns:**
int
### getName() {#getName--}
```
public abstract String getName()
```


Akıllı filtre adını alır.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Akıllı filtrenin opaklık değerini alır veya ayarlar.

**Returns:**
double
### getSourceDescriptor() {#getSourceDescriptor--}
```
public final DescriptorStructure getSourceDescriptor()
```


Akıllı filtre verileriyle kaynak tanımlayıcı yapısı.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isEnabled() {#isEnabled--}
```
public final boolean isEnabled()
```


Akıllı filtrenin etkin durumunu alır veya ayarlar.

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




### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Karışım modunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Akıllı filtrenin etkin durumunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Akıllı filtrenin opaklık değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### toDescriptorStructure_internalized() {#toDescriptorStructure-internalized--}
```
public DescriptorStructure toDescriptorStructure_internalized()
```


Akıllı filtre bilgilerini [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) verisine kaydeder ve döndürür.

**Returns:**
[DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) - The [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) with saved smart filter information.
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

