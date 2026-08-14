---
title: "Kelas VstkResource"
type: docs
weight: 40
url: /id/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---

**Summary:** Resource class VstkResource. Contains information about Vector Stroke Data.<br/>            Resource should be initialized either by AssignItems method from ResourceLoader,<br/>            either by assigning values to properties of the class.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources.strokeresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.strokeresources.VstkResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [VstkResource()](#VstkResource__1) | Menginisialisasi sebuah instance baru dari kelas VstkResource |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya khusus PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Signature sumber daya umum. |
| TYPE_TOOL_KEY [static] | int | r | Kunci info type tool. |
| fill_enabled | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah pengisian Stroke diaktifkan. |
| fill_settings | [IFillSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/) | r/w | Mendapatkan atau mengatur pengaturan Fill dari Stroke. |
| key | int | r | Mendapatkan kunci sumber daya lapisan. |
| panjang | int | r | Mendapatkan panjang sumber daya lapisan dalam byte. |
| psd_version | int | r | Mendapatkan versi psd minimal yang diperlukan untuk sumber daya lapisan. 0 menunjukkan tidak ada batasan. |
| signature | int | r | Mendapatkan signature. |
| stroke_enabled | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah efek stroke diaktifkan. |
| stroke_style_blend_mode | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Mendapatkan atau mengatur mode Blend Stroke. |
| stroke_style_content | [DescriptorStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.typetoolinfostructures/descriptorstructure/) | r/w | Mendapatkan atau mengatur entitas Stroke. Properti menentukan pengaturan isi dari stroke. |
| stroke_style_line_alignment | [StrokePosition](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/) | r/w | Mendapatkan atau mengatur perataan garis gaya Stroke. |
| stroke_style_line_cap_type | [LineCapType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linecaptype) | r/w | Mendapatkan atau mengatur tipe tutup garis gaya stroke. |
| stroke_style_line_cap_width | double | r/w | Mendapatkan atau mengatur lebar tutup garis Stroke. |
| stroke_style_line_dash_offset | int | r/w | Mendapatkan atau mengatur offset dash garis gaya stroke. |
| stroke_style_line_dash_set | double | r/w | Mendapatkan atau mengatur array dash garis. |
| stroke_style_line_join_type | [LineJoinType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/linejointype) | r/w | Mendapatkan atau mengatur tipe sambungan garis gaya Stroke. |
| stroke_style_line_width | double | r/w | Mendapatkan atau mengatur lebar garis Stroke. |
| stroke_style_miter_limit | double | r/w | Mendapatkan atau mengatur batas miter gaya stroke. |
| stroke_style_opacity | int | r/w | Mendapatkan atau mengatur opasitas gaya Stroke (0-100%). |
| stroke_style_resolution | double | r/w | Mendapatkan atau mengatur resolusi gaya Stroke. |
| stroke_style_scale_lock | bool | r/w | Mendapatkan atau mengatur kunci skala gaya Stroke. |
| stroke_style_stroke_adjust | bool | r/w | Mendapatkan atau mengatur penyesuaian Stroke. |
| stroke_style_version | int | r/w | Mendapatkan atau mengatur versi gaya stroke. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Menyimpan sumber daya ke kontainer aliran yang ditentukan. |


### Constructor: VstkResource() {#VstkResource__1}


```
 VstkResource() 
```

Menginisialisasi sebuah instance baru dari kelas VstkResource

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Menyimpan sumber daya ke kontainer aliran yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Kontainer aliran untuk disimpan. |
| psd_version | int | Versi PSD. |

