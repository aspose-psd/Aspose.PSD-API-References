---
title: "Kelas UnknownSmartFilter"
type: docs
weight: 70
url: /id/python-net/aspose.psd.fileformats.psd.layers.smartfilters/unknownsmartfilter/
---

**Summary:** The class to hold unknown smart filter data.

**Module:** [aspose.psd.fileformats.psd.layers.smartfilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartfilters.UnknownSmartFilter

**Inheritance:** SmartFilter

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Mendapatkan atau mengatur mode pencampuran. |
| filter_id | int | r | Mendapatkan pengidentifikasi tipe filter pintar. |
| is_enabled | bool | r/w | Mendapatkan atau mengatur status aktif dari filter pintar. |
| name | string | r | Mendapatkan nama filter pintar. |
| opasitas | double | r/w | Mendapatkan atau mengatur nilai opasitas filter pintar. |
| source_descriptor | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r | Struktur deskriptor sumber dengan data filter pintar. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [apply(raster_image)](#apply_raster_image_1) | Menerapkan filter saat ini pada gambar [RasterImage](/psd/python-net/aspose.psd/rasterimage/) masukan. |
| [apply_to_mask(layer_with_mask)](#apply_to_mask_layer_with_mask_2) | Menerapkan filter saat ini pada data masker [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) masukan. |
| [clone()](#clone__3) | Membuat klon anggota dari instance saat ini dari tipe tersebut. |


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


