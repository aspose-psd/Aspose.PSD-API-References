---
title: "Kelas AiLayerSection"
type: docs
weight: 50
url: /id/python-net/aspose.psd.fileformats.ai/ailayersection/
---

**Summary:** The Ai format Layer Section

**Module:** [aspose.psd.fileformats.ai](/psd/python-net/aspose.psd.fileformats.ai/)

**Full Name:** aspose.psd.fileformats.ai.AiLayerSection

**Inheritance:** AiDataSection

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| biru | int | r/w | Mendapatkan atau mengatur komponen warna biru. |
| color_index | int | r/w | Mendapatkan atau mengatur indeks warna.<br/> Argumen ini dapat mengambil nilai antara –1 dan 26. Setiap integer<br/> mewakili warna yang dapat ditetapkan ke lapisan untuk tujuan<br/> identifikasi pengguna. |
| color_number | int | r/w | Mendapatkan atau mengatur nomor warna. -1 adalah nilai warna khusus dari properti Merah, Hijau, Biru.<br/> Menentukan pengaturan warna lapisan. |
| dim_value | int | r/w | Mendapatkan atau mengatur nilai redup sebagai persentase.<br/> Mengurangi intensitas gambar terhubung dan gambar bitmap yang terdapat dalam lapisan ke persentase yang ditentukan. |
| dibuang | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| hijau | int | r/w | Mendapatkan atau mengatur komponen warna hijau. |
| has_multi_layer_masks | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah instance ini memiliki masker multilapis. |
| is_images_dimmed | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini redup.<br/>            Mengurangi intensitas gambar yang ditautkan dan gambar bitmap yang terdapat dalam lapisan. |
| is_locked | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini terkunci.<br/>            Mencegah perubahan pada item. |
| is_preview | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini dalam pratinjau.<br/>            Menampilkan karya seni yang terdapat dalam lapisan dengan warna alih-alih sebagai garis kontur. |
| is_printed | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini dicetak.<br/>            Membuat karya seni yang terdapat dalam lapisan dapat dicetak jika true. |
| is_shown | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini ditampilkan.<br/>            Menampilkan semua karya seni yang terdapat dalam lapisan pada papan gambar jika true. |
| is_template | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah lapisan ini merupakan lapisan templat. |
| name | string | r/w | Mendapatkan atau mengatur nama lapisan.<br/>            Menentukan nama item sebagaimana muncul di panel Layers. |
| raster_images | [AiRasterImageSection[]](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | r | Mendapatkan gambar raster. |
| merah | int | r/w | Mendapatkan atau mengatur komponen warna merah. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add_raster_image(raster_image)](#add_raster_image_raster_image_1) | Menambahkan gambar raster. |
| [get_data()](#get_data__2) | Mendapatkan data string. |


### Method: add_raster_image(raster_image) {#add_raster_image_raster_image_1}


```
 add_raster_image(raster_image) 
```

Menambahkan gambar raster.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| raster_image | [AiRasterImageSection](/psd/python-net/aspose.psd.fileformats.ai/airasterimagesection) | Gambar raster. |

### Method: get_data() {#get_data__2}


```
 get_data() 
```

Mendapatkan data string.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Data string dari bagian |


