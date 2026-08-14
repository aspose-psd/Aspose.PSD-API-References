---
title: "Kelas FilterEffectMaskData"
type: docs
weight: 310
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/
---

**Summary:** The filter mask data class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FilterEffectMaskData

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask)](#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1) | Menginisialisasi sebuah instance baru dari kelas [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Mendapatkan saluran. |
| guid | string | r | Mendapatkan GUID. |
| panjang | int | r | Mendapatkan panjang data filter mask dalam byte. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Mendapatkan persegi panjang mask lembar. |
| max_channels | int | r | Mendapatkan nilai maksimum jumlah saluran. |
| pixels_depth | int | r | Mendapatkan kedalaman piksel. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Mendapatkan persegi panjang saluran. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Mendapatkan mask lembar. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r | Mendapatkan mask pengguna. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save_data(stream_container)](#save_data_stream_container_1) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |


### Constructor: FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) {#FilterEffectMaskData_guid_rectangle_pixels_depth_max_channels_channels_user_mask_mask_rectangle_sheet_mask_1}


```
 FilterEffectMaskData(guid, rectangle, pixels_depth, max_channels, channels, user_mask, mask_rectangle, sheet_mask) 
```

Menginisialisasi sebuah instance baru dari kelas [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| guid | string | guid sumber daya. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang saluran. |
| pixels_depth | int | Kedalaman piksel. |
| max_channels | int | Nilai maksimum saluran. |
| channels | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Saluran. |
| user_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Masker pengguna. |
| mask_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Persegi panjang masker lembar. |
| sheet_mask | [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | Masker lembar. |

### Method: save_data(stream_container) {#save_data_stream_container_1}


```
 save_data(stream_container) 
```

Menyimpan sumber daya ke kontainer aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran untuk disimpan. |

