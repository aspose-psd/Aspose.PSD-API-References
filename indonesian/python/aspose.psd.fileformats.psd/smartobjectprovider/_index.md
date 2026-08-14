---
title: "Kelas SmartObjectProvider"
type: docs
weight: 1940
url: /id/python-net/aspose.psd.fileformats.psd/smartobjectprovider/
---

**Summary:** Defines the smart object provider that provides getting / setting data sources from global link resources of the PSD file and their contents.

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.SmartObjectProvider

**Aspose.PSD Version:** 24.12.0

## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [convert_to_smart_object(layer_numbers)](#convert_to_smart_object_layer_numbers_1) | Mengonversi lapisan menjadi objek pintar tersemat. |
| [convert_to_smart_object(layers)](#convert_to_smart_object_layers_2) | Mengonversi lapisan menjadi objek pintar tersemat. |
| embed_all_linked() | Menyematkan semua objek pintar yang ditautkan dalam gambar. |
| [new_smart_object_via_copy(source_layer)](#new_smart_object_via_copy_source_layer_3) | Membuat lapisan objek pintar baru dengan menyalin yang sumber. |
| update_all_modified_content() | Memperbarui konten semua objek pintar yang dimodifikasi dalam gambar. |


### Method: convert_to_smart_object(layer_numbers) {#convert_to_smart_object_layer_numbers_1}


```
 convert_to_smart_object(layer_numbers) 
```

Mengonversi lapisan menjadi objek pintar tersemat.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layer_numbers | int | Nomor lapisan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Instansi [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) yang dibuat. |


### Method: convert_to_smart_object(layers) {#convert_to_smart_object_layers_2}


```
 convert_to_smart_object(layers) 
```

Mengonversi lapisan menjadi objek pintar tersemat.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Lapisan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Instansi [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) yang dibuat. |


### Method: new_smart_object_via_copy(source_layer) {#new_smart_object_via_copy_source_layer_3}


```
 new_smart_object_via_copy(source_layer) 
```

Membuat lapisan objek pintar baru dengan menyalin yang sumber.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_layer | [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Lapisan sumber. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) | Instansi [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) yang dikloning. |


