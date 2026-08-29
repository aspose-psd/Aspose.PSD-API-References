---
title: "GaussianBlurSmartFilter"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Filter pintar GaussianBlur."
type: docs
weight: 11
url: /id/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/gaussianblursmartfilter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.smartfilters.filters.SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter)
```
public final class GaussianBlurSmartFilter extends SmartFilter
```

Filter pintar GaussianBlur.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [GaussianBlurSmartFilter()](#GaussianBlurSmartFilter--) | Menginisialisasi instance baru dari kelas [GaussianBlurSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/gaussianblursmartfilter) class. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [FilterType](#FilterType) | Pengidentifikasi dari filter pintar saat ini. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | Menerapkan filter saat ini pada input RasterImage image. |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | Menerapkan filter saat ini pada data mask [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [crate_internalized(DescriptorStructure sourceDescriptor)](#crate-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) |  |
| [deepClone()](#deepClone--) | Membuat klon memberwise dari instance saat ini dari tipe tersebut. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendMode()](#getBlendMode--) | Mendapatkan atau mengatur mode pencampuran. |
| [getClass()](#getClass--) |  |
| [getFilterId()](#getFilterId--) | Mendapatkan pengidentifikasi tipe smart filter. |
| [getName()](#getName--) | Mendapatkan nama smart filter. |
| [getOpacity()](#getOpacity--) | Mendapatkan atau mengatur nilai opasitas smart filter. |
| [getRadius()](#getRadius--) | Mendapatkan atau mengatur radius filter pintar gaussian. |
| [getSourceDescriptor()](#getSourceDescriptor--) | Struktur deskriptor sumber dengan data smart filter. |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | Mendapatkan atau mengatur status is enabled dari smart filter. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlendMode(long value)](#setBlendMode-long-) | Mendapatkan atau mengatur mode pencampuran. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Mendapatkan atau mengatur status is enabled dari smart filter. |
| [setOpacity(double value)](#setOpacity-double-) | Mendapatkan atau mengatur nilai opasitas smart filter. |
| [setRadius(double value)](#setRadius-double-) | Mendapatkan atau mengatur radius filter pintar gaussian. |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | Menyimpan informasi smart filter ke data [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) dan mengembalikan. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GaussianBlurSmartFilter() {#GaussianBlurSmartFilter--}
```
public GaussianBlurSmartFilter()
```


Menginisialisasi instance baru dari kelas [GaussianBlurSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/gaussianblursmartfilter) class.

### FilterType {#FilterType}
```
public static final int FilterType
```


Pengidentifikasi dari filter pintar saat ini.

### apply(RasterImage rasterImage) {#apply-com.aspose.psd.RasterImage-}
```
public final void apply(RasterImage rasterImage)
```


Menerapkan filter saat ini pada input RasterImage image.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.psd/rasterimage) | Gambar raster. |

### applyToMask(Layer layerWithMask) {#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public final void applyToMask(Layer layerWithMask)
```


Menerapkan filter saat ini pada data mask [Layer](../../com.aspose.psd.fileformats.psd.layers/layer).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| layerWithMask | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Lapisan dengan data mask. |

### crate_internalized(DescriptorStructure sourceDescriptor) {#crate-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public static GaussianBlurSmartFilter crate_internalized(DescriptorStructure sourceDescriptor)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceDescriptor | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

**Returns:**
[GaussianBlurSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/gaussianblursmartfilter)
### deepClone() {#deepClone--}
```
public final SmartFilter deepClone()
```


Membuat klon memberwise dari instance saat ini dari tipe tersebut.

**Returns:**
[SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter) - Returns the memberwise clone of the current instance of the type.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBlendMode() {#getBlendMode--}
```
public final long getBlendMode()
```


Mendapatkan atau mengatur mode pencampuran.

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
public int getFilterId()
```


Mendapatkan pengidentifikasi tipe smart filter.

**Returns:**
int
### getName() {#getName--}
```
public String getName()
```


Mendapatkan nama smart filter.

**Returns:**
java.lang.String
### getOpacity() {#getOpacity--}
```
public final double getOpacity()
```


Mendapatkan atau mengatur nilai opasitas smart filter.

**Returns:**
double
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Mendapatkan atau mengatur radius filter pintar gaussian.

**Returns:**
double
### getSourceDescriptor() {#getSourceDescriptor--}
```
public final DescriptorStructure getSourceDescriptor()
```


Struktur deskriptor sumber dengan data smart filter.

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


Mendapatkan atau mengatur status is enabled dari smart filter.

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


Mendapatkan atau mengatur mode pencampuran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Mendapatkan atau mengatur status is enabled dari smart filter.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setOpacity(double value) {#setOpacity-double-}
```
public final void setOpacity(double value)
```


Mendapatkan atau mengatur nilai opasitas smart filter.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Mendapatkan atau mengatur radius filter pintar gaussian.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### toDescriptorStructure_internalized() {#toDescriptorStructure-internalized--}
```
public DescriptorStructure toDescriptorStructure_internalized()
```


Menyimpan informasi smart filter ke data [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) dan mengembalikan.

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

