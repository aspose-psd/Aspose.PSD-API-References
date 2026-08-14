---
title: "Kelas GaussianBlurSmartFilter"
type: docs
weight: 20
url: /id/python-net/aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/
---

**Summary:** The GaussianBlur smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.GaussianBlurSmartFilter

**Inheritance:** SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [GaussianBlurSmartFilter()](#GaussianBlurSmartFilter__1) | Menginisialisasi instance baru dari kelas [GaussianBlurSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| FILTER_TYPE [static] | int | r | Pengidentifikasi filter pintar saat ini. |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Mendapatkan atau mengatur mode pencampuran. |
| filter_id | int | r | Mendapatkan pengidentifikasi tipe filter pintar. |
| is_enabled | bool | r/w | Mendapatkan atau mengatur status aktif dari filter pintar. |
| name | string | r | Mendapatkan nama filter pintar. |
| opasitas | double | r/w | Mendapatkan atau mengatur nilai opasitas filter pintar. |
| jari-jari | double | r/w | Mendapatkan atau mengatur radius filter pintar gaussian. |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | Struktur deskriptor sumber dengan data filter pintar. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | Menerapkan filter saat ini pada gambar [RasterImage](/psd/python-net/aspose.psd/rasterimage/) masukan. |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | Menerapkan filter saat ini pada data masker [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) masukan. |
| [clone()](#clone__3) | Membuat klon anggota dari instance saat ini dari tipe tersebut. |


### Constructor: GaussianBlurSmartFilter() {#GaussianBlurSmartFilter__1}


```
 GaussianBlurSmartFilter() 
```

Menginisialisasi instance baru dari kelas [GaussianBlurSmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/gaussianblursmartfilter/).

### Method: apply(raster_image) {#apply_raster_image_1}


```
 apply(raster_image) 
```

Menerapkan filter saat ini pada gambar [RasterImage](/psd/python-net/aspose.psd/rasterimage/) masukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Gambar raster. |

### Method: apply_to_mask(layer_with_mask) {#apply_to_mask_layer_with_mask_2}


```
 apply_to_mask(layer_with_mask) 
```

Menerapkan filter saat ini pada data masker [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) masukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layer_with_mask | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Lapisan dengan data masker. |

### Method: clone() {#clone__3}


```
 clone() 
```

Membuat klon anggota dari instance saat ini dari tipe tersebut.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [SmartFilter](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilter) | Mengembalikan klon anggota dari instance saat ini dari tipe tersebut. |


