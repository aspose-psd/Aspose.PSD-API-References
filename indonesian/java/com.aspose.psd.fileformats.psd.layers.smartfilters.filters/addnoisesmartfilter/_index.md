---
title: "AddNoiseSmartFilter"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Filter pintar AddNoise."
type: docs
weight: 10
url: /id/java/com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.smartfilters.filters.SmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/smartfilter)
```
public final class AddNoiseSmartFilter extends SmartFilter
```

Filter pintar AddNoise.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [AddNoiseSmartFilter()](#AddNoiseSmartFilter--) | Menginisialisasi instance baru dari kelas [AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter) class. |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [FilterType](#FilterType) | Pengidentifikasi dari filter pintar saat ini. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [apply(RasterImage rasterImage)](#apply-com.aspose.psd.RasterImage-) | Menerapkan filter saat ini pada input RasterImage image. |
| [applyToMask(Layer layerWithMask)](#applyToMask-com.aspose.psd.fileformats.psd.layers.Layer-) | Menerapkan filter saat ini pada data mask [Layer](../../com.aspose.psd.fileformats.psd.layers/layer). |
| [create_internalized(DescriptorStructure sourceDescriptor)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-) |  |
| [deepClone()](#deepClone--) | Membuat klon memberwise dari instance saat ini dari tipe tersebut. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAmountNoise()](#getAmountNoise--) | Mendapatkan atau mengatur jumlah nilai noise. |
| [getBlendMode()](#getBlendMode--) | Mendapatkan atau mengatur mode pencampuran. |
| [getClass()](#getClass--) |  |
| [getDistribution()](#getDistribution--) | Mendapatkan atau mengatur distribusi filter noise. |
| [getFilterId()](#getFilterId--) | Mendapatkan pengidentifikasi tipe smart filter. |
| [getName()](#getName--) | Mendapatkan nama smart filter. |
| [getOpacity()](#getOpacity--) | Mendapatkan atau mengatur nilai opasitas smart filter. |
| [getSourceDescriptor()](#getSourceDescriptor--) | Struktur deskriptor sumber dengan data smart filter. |
| [hashCode()](#hashCode--) |  |
| [isEnabled()](#isEnabled--) | Mendapatkan atau mengatur status is enabled dari smart filter. |
| [isMonochromatic()](#isMonochromatic--) | Mendapatkan atau mengatur nilai monokromatik. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAmountNoise(double value)](#setAmountNoise-double-) | Mendapatkan atau mengatur jumlah nilai noise. |
| [setBlendMode(long value)](#setBlendMode-long-) | Mendapatkan atau mengatur mode pencampuran. |
| [setDistribution(int value)](#setDistribution-int-) | Mendapatkan atau mengatur distribusi filter noise. |
| [setEnabled(boolean value)](#setEnabled-boolean-) | Mendapatkan atau mengatur status is enabled dari smart filter. |
| [setMonochromatic(boolean value)](#setMonochromatic-boolean-) | Mendapatkan atau mengatur nilai monokromatik. |
| [setOpacity(double value)](#setOpacity-double-) | Mendapatkan atau mengatur nilai opasitas smart filter. |
| [toDescriptorStructure_internalized()](#toDescriptorStructure-internalized--) | Menyimpan informasi smart filter ke data [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) dan mengembalikan. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AddNoiseSmartFilter() {#AddNoiseSmartFilter--}
```
public AddNoiseSmartFilter()
```


Menginisialisasi instance baru dari kelas [AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter) class.

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

### create_internalized(DescriptorStructure sourceDescriptor) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures.DescriptorStructure-}
```
public static AddNoiseSmartFilter create_internalized(DescriptorStructure sourceDescriptor)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sourceDescriptor | [DescriptorStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure) |  |

**Returns:**
[AddNoiseSmartFilter](../../com.aspose.psd.fileformats.psd.layers.smartfilters.filters/addnoisesmartfilter)
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
### getAmountNoise() {#getAmountNoise--}
```
public final double getAmountNoise()
```


Mendapatkan atau mengatur jumlah nilai noise.

**Returns:**
double
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
### getDistribution() {#getDistribution--}
```
public final int getDistribution()
```


Mendapatkan atau mengatur distribusi filter noise.

**Returns:**
int
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
### isMonochromatic() {#isMonochromatic--}
```
public final boolean isMonochromatic()
```


Mendapatkan atau mengatur nilai monokromatik.

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




### setAmountNoise(double value) {#setAmountNoise-double-}
```
public final void setAmountNoise(double value)
```


Mendapatkan atau mengatur jumlah nilai noise.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### setBlendMode(long value) {#setBlendMode-long-}
```
public final void setBlendMode(long value)
```


Mendapatkan atau mengatur mode pencampuran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | long |  |

### setDistribution(int value) {#setDistribution-int-}
```
public final void setDistribution(int value)
```


Mendapatkan atau mengatur distribusi filter noise.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### setEnabled(boolean value) {#setEnabled-boolean-}
```
public final void setEnabled(boolean value)
```


Mendapatkan atau mengatur status is enabled dari smart filter.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### setMonochromatic(boolean value) {#setMonochromatic-boolean-}
```
public final void setMonochromatic(boolean value)
```


Mendapatkan atau mengatur nilai monokromatik.

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

