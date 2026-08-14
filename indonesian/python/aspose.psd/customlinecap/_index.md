---
title: "Kelas CustomLineCap"
type: docs
weight: 1010
url: /id/python-net/aspose.psd/customlinecap/
---

**Summary:** Encapsulates a custom user-defined line cap.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.CustomLineCap

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [CustomLineCap(fill_path, stroke_path)](#CustomLineCap_fill_path_stroke_path_1) | Menginisialisasi instance baru dari kelas [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) dengan outline dan isi yang ditentukan. |
| [CustomLineCap(fill_path, stroke_path, base_cap)](#CustomLineCap_fill_path_stroke_path_base_cap_2) | Menginisialisasi instance baru dari kelas [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) dari enumerasi [LineCap](/psd/python-net/aspose.psd/linecap/) yang ada dengan outline dan isi yang ditentukan. |
| [CustomLineCap(fill_path, stroke_path, base_cap, base_inset)](#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3) | Menginisialisasi instance baru dari kelas [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) dari enumerasi [LineCap](/psd/python-net/aspose.psd/linecap/) yang ada dengan outline, isi, dan inset yang ditentukan. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | r/w | Mendapatkan atau mengatur enumerasi [LineCap](/psd/python-net/aspose.psd/linecap/) yang menjadi dasar [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) ini. |
| base_inset | float | r/w | Mendapatkan atau mengatur jarak antara cap dan garis. |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | Mendapatkan atau mengatur objek yang mendefinisikan isi untuk cap khusus. |
| stroke_join | [LineJoin](/psd/python-net/aspose.psd/linejoin) | r/w | Mendapatkan atau mengatur enumerasi [LineJoin](/psd/python-net/aspose.psd/linejoin/) yang menentukan bagaimana garis-garis yang menyusun objek [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) ini digabungkan. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | r/w | Mendapatkan atau mengatur objek yang mendefinisikan outline dari cap khusus. |
| width_scale | float | r/w | Mendapatkan atau mengatur jumlah skala objek Kelas [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) relatif terhadap lebar objek. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_stroke_caps(start_cap, end_cap)](#get_stroke_caps_start_cap_end_cap_1) | Mendapatkan cap yang digunakan untuk memulai dan mengakhiri garis yang membentuk cap khusus ini. |
| [set_stroke_caps(start_cap, end_cap)](#set_stroke_caps_start_cap_end_cap_2) | Mengatur cap yang digunakan untuk memulai dan mengakhiri garis yang membentuk cap khusus ini. |


### Constructor: CustomLineCap(fill_path, stroke_path) {#CustomLineCap_fill_path_stroke_path_1}


```
 CustomLineCap(fill_path, stroke_path) 
```

Menginisialisasi instance baru dari kelas [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) dengan outline dan isi yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Objek [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang mendefinisikan isi untuk cap khusus. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Objek [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang mendefinisikan outline dari cap khusus. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap) {#CustomLineCap_fill_path_stroke_path_base_cap_2}


```
 CustomLineCap(fill_path, stroke_path, base_cap) 
```

Menginisialisasi instance baru dari kelas [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) dari enumerasi [LineCap](/psd/python-net/aspose.psd/linecap/) yang ada dengan outline dan isi yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Objek [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang mendefinisikan isi untuk cap khusus. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Objek [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang mendefinisikan outline dari cap khusus. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Cap garis yang akan digunakan untuk membuat cap khusus. |

### Constructor: CustomLineCap(fill_path, stroke_path, base_cap, base_inset) {#CustomLineCap_fill_path_stroke_path_base_cap_base_inset_3}


```
 CustomLineCap(fill_path, stroke_path, base_cap, base_inset) 
```

Menginisialisasi instance baru dari kelas [CustomLineCap](/psd/python-net/aspose.psd/customlinecap/) dari enumerasi [LineCap](/psd/python-net/aspose.psd/linecap/) yang ada dengan outline, isi, dan inset yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| fill_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Objek [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang mendefinisikan isi untuk cap khusus. |
| stroke_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | Objek [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang mendefinisikan outline dari cap khusus. |
| base_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Cap garis yang akan digunakan untuk membuat cap khusus. |
| base_inset | float | Jarak antara cap dan garis. |

### Method: get_stroke_caps(start_cap, end_cap) {#get_stroke_caps_start_cap_end_cap_1}


```
 get_stroke_caps(start_cap, end_cap) 
```

Mendapatkan cap yang digunakan untuk memulai dan mengakhiri garis yang membentuk cap khusus ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| start_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | Enumerasi [LineCap](/psd/python-net/aspose.psd/linecap/) yang digunakan di awal garis dalam cap ini. |
| end_cap | [LineCap[]](/psd/python-net/aspose.psd/linecap) | Enumerasi [LineCap](/psd/python-net/aspose.psd/linecap/) yang digunakan di akhir garis dalam cap ini. |

### Method: set_stroke_caps(start_cap, end_cap) {#set_stroke_caps_start_cap_end_cap_2}


```
 set_stroke_caps(start_cap, end_cap) 
```

Mengatur cap yang digunakan untuk memulai dan mengakhiri garis yang membentuk cap khusus ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| start_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Enumerasi [LineCap](/psd/python-net/aspose.psd/linecap/) yang digunakan di awal garis dalam cap ini. |
| end_cap | [LineCap](/psd/python-net/aspose.psd/linecap) | Enumerasi [LineCap](/psd/python-net/aspose.psd/linecap/) yang digunakan di akhir garis dalam cap ini. |

