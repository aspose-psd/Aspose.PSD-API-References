---
title: "Kelas Region"
type: docs
weight: 3870
url: /id/python-net/aspose.psd/region/
---

**Summary:** Describes the interior of a graphics shape composed of rectangles and paths. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Region

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [Region()](#Region__1) | Menginisialisasi [Region](/psd/python-net/aspose.psd/region/) baru. |
| [Region(path)](#Region_path_2) | Menginisialisasi [Region](/psd/python-net/aspose.psd/region/) baru dengan [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang ditentukan. |
| [Region(rect)](#Region_rect_3) | Menginisialisasi [Region](/psd/python-net/aspose.psd/region/) baru dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan. |
| [Region(rect)](#Region_rect_4) | Menginisialisasi [Region](/psd/python-net/aspose.psd/region/) baru dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [complement(path)](#complement_path_1) | Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini untuk berisi bagian dari [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang ditentukan yang tidak berpotongan dengan [Region](/psd/python-net/aspose.psd/region/) ini. |
| [complement(rect)](#complement_rect_2) | Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini untuk berisi bagian dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan yang tidak berpotongan dengan [Region](/psd/python-net/aspose.psd/region/) ini. |
| [complement(rect)](#complement_rect_3) | Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini untuk berisi bagian dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan yang tidak berpotongan dengan [Region](/psd/python-net/aspose.psd/region/) ini. |
| [complement(region)](#complement_region_4) | Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini untuk berisi bagian dari [Region](/psd/python-net/aspose.psd/region/) yang ditentukan yang tidak berpotongan dengan [Region](/psd/python-net/aspose.psd/region/) ini. |
| [deep_clone()](#deep_clone__5) | Membuat salinan dalam yang tepat dari [Region](/psd/python-net/aspose.psd/region/) ini. |
| [exclude(path)](#exclude_path_6) | Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini untuk hanya berisi bagian interiornya yang tidak berpotongan dengan [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang ditentukan. |
| [exclude(rect)](#exclude_rect_7) | Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini untuk hanya berisi bagian interiornya yang tidak berpotongan dengan struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan. |
| [exclude(rect)](#exclude_rect_8) | Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini untuk hanya berisi bagian interiornya yang tidak berpotongan dengan struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan. |
| [exclude(region)](#exclude_region_9) | Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini untuk hanya berisi bagian interiornya yang tidak berpotongan dengan [Region](/psd/python-net/aspose.psd/region/) yang ditentukan. |
| [intersect(path)](#intersect_path_10) | Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi irisan dirinya dengan [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang ditentukan. |
| [intersect(rect)](#intersect_rect_11) | Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi irisan dirinya dengan struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan. |
| [intersect(rect)](#intersect_rect_12) | Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi irisan dirinya dengan struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan. |
| [intersect(region)](#intersect_region_13) | Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi irisan dirinya dengan [Region](/psd/python-net/aspose.psd/region/) yang ditentukan. |
| [is_empty(g)](#is_empty_g_14) | Menguji apakah [Region](/psd/python-net/aspose.psd/region/) ini memiliki interior kosong pada permukaan gambar yang ditentukan. |
| [is_infinite(g)](#is_infinite_g_15) | Menguji apakah [Region](/psd/python-net/aspose.psd/region/) ini memiliki interior tak terbatas pada permukaan gambar yang ditentukan. |
| [is_visible(point)](#is_visible_point_16) | Menguji apakah struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini. |
| [is_visible(point)](#is_visible_point_17) | Menguji apakah struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini. |
| [is_visible(point, g)](#is_visible_point_g_18) | Menguji apakah struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini ketika digambar menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan. |
| [is_visible(point, g)](#is_visible_point_g_19) | Menguji apakah struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini ketika digambar menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan. |
| [is_visible(rect)](#is_visible_rect_20) | Menguji apakah ada bagian dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini. |
| [is_visible(rect)](#is_visible_rect_21) | Menguji apakah ada bagian dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini. |
| [is_visible(rect, g)](#is_visible_rect_g_22) | Menguji apakah ada bagian dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini ketika digambar menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan. |
| [is_visible(rect, g)](#is_visible_rect_g_23) | Menguji apakah ada bagian dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini ketika digambar menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan. |
| [is_visible(x, y)](#is_visible_x_y_24) | Menguji apakah titik yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini. |
| [is_visible(x, y, g)](#is_visible_x_y_g_25) | Menguji apakah titik yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini ketika digambar menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan. |
| [is_visible(x, y, g)](#is_visible_x_y_g_26) | Menguji apakah titik yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini ketika digambar menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan. |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_27) | Menguji apakah bagian mana pun dari persegi panjang yang ditentukan terkandung dalam [Region](/psd/python-net/aspose.psd/region/) ini. |
| [is_visible(x, y, width, height)](#is_visible_x_y_width_height_28) | Menguji apakah bagian mana pun dari persegi panjang yang ditentukan terkandung dalam [Region](/psd/python-net/aspose.psd/region/) ini. |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_29) | Menguji apakah bagian mana pun dari persegi panjang yang ditentukan terkandung dalam [Region](/psd/python-net/aspose.psd/region/) ini ketika digambar menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan. |
| [is_visible(x, y, width, height, g)](#is_visible_x_y_width_height_g_30) | Menguji apakah bagian mana pun dari persegi panjang yang ditentukan terkandung dalam [Region](/psd/python-net/aspose.psd/region/) ini ketika digambar menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan. |
| make_empty() | Menginisialisasi [Region](/psd/python-net/aspose.psd/region/) ini dengan interior kosong. |
| make_infinite() | Menginisialisasi objek [Region](/psd/python-net/aspose.psd/region/) ini dengan interior tak terbatas. |
| [transform(matrix)](#transform_matrix_31) | Mengubah [Region](/psd/python-net/aspose.psd/region/) ini dengan [Matrix](/psd/python-net/aspose.psd/matrix/) yang ditentukan. |
| [translate(dx, dy)](#translate_dx_dy_32) | Menggeser koordinat [Region](/psd/python-net/aspose.psd/region/) ini sebesar jumlah yang ditentukan. |
| [translate(dx, dy)](#translate_dx_dy_33) | Menggeser koordinat [Region](/psd/python-net/aspose.psd/region/) ini sebesar jumlah yang ditentukan. |
| [union(path)](#union_path_34) | Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi gabungan antara dirinya sendiri dan [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang ditentukan. |
| [union(rect)](#union_rect_35) | Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi gabungan antara dirinya sendiri dan struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan. |
| [union(rect)](#union_rect_36) | Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi gabungan antara dirinya sendiri dan struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan. |
| [union(region)](#union_region_37) | Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi gabungan antara dirinya sendiri dan [Region](/psd/python-net/aspose.psd/region/) yang ditentukan. |
| [xor(path)](#xor_path_38) | Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi gabungan dikurangi irisan antara dirinya sendiri dengan [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang ditentukan. |
| [xor(rect)](#xor_rect_39) | Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi gabungan dikurangi irisan antara dirinya sendiri dengan struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan. |
| [xor(rect)](#xor_rect_40) | Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi gabungan dikurangi irisan antara dirinya sendiri dengan struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan. |
| [xor(region)](#xor_region_41) | Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi gabungan dikurangi irisan antara dirinya sendiri dengan [Region](/psd/python-net/aspose.psd/region/) yang ditentukan. |


### Constructor: Region() {#Region__1}


```
 Region() 
```

Menginisialisasi [Region](/psd/python-net/aspose.psd/region/) baru.

### Constructor: Region(path) {#Region_path_2}


```
 Region(path) 
```

Menginisialisasi [Region](/psd/python-net/aspose.psd/region/) baru dengan [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang mendefinisikan [Region](/psd/python-net/aspose.psd/region/) baru. |

### Constructor: Region(rect) {#Region_rect_3}


```
 Region(rect) 
```

Menginisialisasi [Region](/psd/python-net/aspose.psd/region/) baru dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mendefinisikan interior [Region](/psd/python-net/aspose.psd/region/) baru. |

### Constructor: Region(rect) {#Region_rect_4}


```
 Region(rect) 
```

Menginisialisasi [Region](/psd/python-net/aspose.psd/region/) baru dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mendefinisikan interior [Region](/psd/python-net/aspose.psd/region/) baru. |

### Method: complement(path) {#complement_path_1}


```
 complement(path) 
```

Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini untuk berisi bagian dari [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang ditentukan yang tidak berpotongan dengan [Region](/psd/python-net/aspose.psd/region/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) untuk melengkapi [Region](/psd/python-net/aspose.psd/region/) ini. |

### Method: complement(rect) {#complement_rect_2}


```
 complement(rect) 
```

Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini untuk berisi bagian dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan yang tidak berpotongan dengan [Region](/psd/python-net/aspose.psd/region/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) untuk melengkapi [Region](/psd/python-net/aspose.psd/region/) ini. |

### Method: complement(rect) {#complement_rect_3}


```
 complement(rect) 
```

Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini untuk berisi bagian dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan yang tidak berpotongan dengan [Region](/psd/python-net/aspose.psd/region/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) untuk melengkapi [Region](/psd/python-net/aspose.psd/region/) ini. |

### Method: complement(region) {#complement_region_4}


```
 complement(region) 
```

Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini untuk berisi bagian dari [Region](/psd/python-net/aspose.psd/region/) yang ditentukan yang tidak berpotongan dengan [Region](/psd/python-net/aspose.psd/region/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | Objek [Region](/psd/python-net/aspose.psd/region/) untuk melengkapi objek [Region](/psd/python-net/aspose.psd/region/) ini. |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

Membuat salinan dalam yang tepat dari [Region](/psd/python-net/aspose.psd/region/) ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/) yang dibuat oleh metode ini. |


### Method: exclude(path) {#exclude_path_6}


```
 exclude(path) 
```

Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini untuk hanya berisi bagian interiornya yang tidak berpotongan dengan [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) untuk dikecualikan dari [Region](/psd/python-net/aspose.psd/region/) ini. |

### Method: exclude(rect) {#exclude_rect_7}


```
 exclude(rect) 
```

Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini untuk hanya berisi bagian interiornya yang tidak berpotongan dengan struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) untuk dikecualikan dari [Region](/psd/python-net/aspose.psd/region/) ini. |

### Method: exclude(rect) {#exclude_rect_8}


```
 exclude(rect) 
```

Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini untuk hanya berisi bagian interiornya yang tidak berpotongan dengan struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) untuk dikecualikan dari [Region](/psd/python-net/aspose.psd/region/) ini. |

### Method: exclude(region) {#exclude_region_9}


```
 exclude(region) 
```

Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini untuk hanya berisi bagian interiornya yang tidak berpotongan dengan [Region](/psd/python-net/aspose.psd/region/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/) untuk dikecualikan dari [Region](/psd/python-net/aspose.psd/region/) ini. |

### Method: intersect(path) {#intersect_path_10}


```
 intersect(path) 
```

Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi irisan dirinya dengan [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) untuk beririsan dengan [Region](/psd/python-net/aspose.psd/region/) ini. |

### Method: intersect(rect) {#intersect_rect_11}


```
 intersect(rect) 
```

Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi irisan dirinya dengan struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) untuk beririsan dengan [Region](/psd/python-net/aspose.psd/region/) ini. |

### Method: intersect(rect) {#intersect_rect_12}


```
 intersect(rect) 
```

Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi irisan dirinya dengan struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) untuk beririsan dengan [Region](/psd/python-net/aspose.psd/region/) ini. |

### Method: intersect(region) {#intersect_region_13}


```
 intersect(region) 
```

Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi irisan dirinya dengan [Region](/psd/python-net/aspose.psd/region/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/) untuk beririsan dengan [Region](/psd/python-net/aspose.psd/region/) ini. |

### Method: is_empty(g) {#is_empty_g_14}


```
 is_empty(g) 
```

Menguji apakah [Region](/psd/python-net/aspose.psd/region/) ini memiliki interior kosong pada permukaan gambar yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | [Graphics](/psd/python-net/aspose.psd/graphics/) yang mewakili permukaan gambar. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | true jika interior dari [Region](/psd/python-net/aspose.psd/region/) kosong ketika transformasi yang terkait dengan <paramref name="g" /> diterapkan; jika tidak, false. |


### Method: is_infinite(g) {#is_infinite_g_15}


```
 is_infinite(g) 
```

Menguji apakah [Region](/psd/python-net/aspose.psd/region/) ini memiliki interior tak terbatas pada permukaan gambar yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | [Graphics](/psd/python-net/aspose.psd/graphics/) yang mewakili permukaan gambar. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | true jika interior dari [Region](/psd/python-net/aspose.psd/region/) tak berhingga ketika transformasi yang terkait dengan <paramref name="g" /> diterapkan; jika tidak, false. |


### Method: is_visible(point) {#is_visible_point_16}


```
 is_visible(point) 
```

Menguji apakah struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Struktur [PointF](/psd/python-net/aspose.psd/pointf/) untuk diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | true ketika <paramref name="point" /> berada di dalam [Region](/psd/python-net/aspose.psd/region/); jika tidak, false. |


### Method: is_visible(point) {#is_visible_point_17}


```
 is_visible(point) 
```

Menguji apakah struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Struktur [PointF](/psd/python-net/aspose.psd/pointf/) untuk diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | true ketika <paramref name="point" /> berada di dalam [Region](/psd/python-net/aspose.psd/region/); jika tidak, false. |


### Method: is_visible(point, g) {#is_visible_point_g_18}


```
 is_visible(point, g) 
```

Menguji apakah struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini ketika digambar menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Struktur [PointF](/psd/python-net/aspose.psd/pointf/) untuk diuji. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Sebuah [Graphics](/psd/python-net/aspose.psd/graphics/) yang mewakili konteks grafis. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | true ketika <paramref name="point" /> berada di dalam [Region](/psd/python-net/aspose.psd/region/); jika tidak, false. |


### Method: is_visible(point, g) {#is_visible_point_g_19}


```
 is_visible(point, g) 
```

Menguji apakah struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini ketika digambar menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | Struktur [PointF](/psd/python-net/aspose.psd/pointf/) untuk diuji. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Sebuah [Graphics](/psd/python-net/aspose.psd/graphics/) yang mewakili konteks grafis. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | true ketika <paramref name="point" /> berada di dalam [Region](/psd/python-net/aspose.psd/region/); jika tidak, false. |


### Method: is_visible(rect) {#is_visible_rect_20}


```
 is_visible(rect) 
```

Menguji apakah ada bagian dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) untuk diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | true ketika sebagian apa pun dari <paramref name="rect" /> berada di dalam [Region](/psd/python-net/aspose.psd/region/); jika tidak, false. |


### Method: is_visible(rect) {#is_visible_rect_21}


```
 is_visible(rect) 
```

Menguji apakah ada bagian dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) untuk diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | true ketika sebagian apa pun dari <paramref name="rect" /> berada di dalam [Region](/psd/python-net/aspose.psd/region/); jika tidak, false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_22}


```
 is_visible(rect, g) 
```

Menguji apakah ada bagian dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini ketika digambar menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) untuk diuji. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Sebuah [Graphics](/psd/python-net/aspose.psd/graphics/) yang mewakili konteks grafis. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | true ketika <paramref name="rect" /> berada di dalam [Region](/psd/python-net/aspose.psd/region/); jika tidak, false. |


### Method: is_visible(rect, g) {#is_visible_rect_g_23}


```
 is_visible(rect, g) 
```

Menguji apakah ada bagian dari struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini ketika digambar menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) untuk diuji. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Sebuah [Graphics](/psd/python-net/aspose.psd/graphics/) yang mewakili konteks grafis. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | true ketika <paramref name="rect" /> berada di dalam [Region](/psd/python-net/aspose.psd/region/); jika tidak, false. |


### Method: is_visible(x, y) {#is_visible_x_y_24}


```
 is_visible(x, y) 
```

Menguji apakah titik yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | float | Koordinat x dari titik yang akan diuji. |
| y | float | Koordinat y dari titik yang akan diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | True ketika titik yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/); jika tidak, false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_25}


```
 is_visible(x, y, g) 
```

Menguji apakah titik yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini ketika digambar menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | float | Koordinat x dari titik yang akan diuji. |
| y | float | Koordinat y dari titik yang akan diuji. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Sebuah [Graphics](/psd/python-net/aspose.psd/graphics/) yang mewakili konteks grafis. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | True ketika titik yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/); jika tidak, false. |


### Method: is_visible(x, y, g) {#is_visible_x_y_g_26}


```
 is_visible(x, y, g) 
```

Menguji apakah titik yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/) ini ketika digambar menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | int | Koordinat x dari titik yang akan diuji. |
| y | int | Koordinat y dari titik yang akan diuji. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Sebuah [Graphics](/psd/python-net/aspose.psd/graphics/) yang mewakili konteks grafis. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | True ketika titik yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/); jika tidak, false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_27}


```
 is_visible(x, y, width, height) 
```

Menguji apakah bagian mana pun dari persegi panjang yang ditentukan terkandung dalam [Region](/psd/python-net/aspose.psd/region/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | float | Koordinat x dari sudut kiri atas persegi panjang yang akan diuji. |
| y | float | Koordinat y dari sudut kiri atas persegi panjang yang akan diuji. |
| width | float | Lebar persegi panjang yang akan diuji. |
| tinggi | float | Tinggi persegi panjang yang akan diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | true ketika sebagian apa pun dari persegi panjang yang ditentukan berada di dalam objek [Region](/psd/python-net/aspose.psd/region/); jika tidak, false. |


### Method: is_visible(x, y, width, height) {#is_visible_x_y_width_height_28}


```
 is_visible(x, y, width, height) 
```

Menguji apakah bagian mana pun dari persegi panjang yang ditentukan terkandung dalam [Region](/psd/python-net/aspose.psd/region/) ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | int | Koordinat x dari sudut kiri atas persegi panjang yang akan diuji. |
| y | int | Koordinat y dari sudut kiri atas persegi panjang yang akan diuji. |
| width | int | Lebar persegi panjang yang akan diuji. |
| tinggi | int | Tinggi persegi panjang yang akan diuji. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | true ketika sebagian apa pun dari persegi panjang yang ditentukan berada di dalam objek [Region](/psd/python-net/aspose.psd/region/); jika tidak, false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_29}


```
 is_visible(x, y, width, height, g) 
```

Menguji apakah bagian mana pun dari persegi panjang yang ditentukan terkandung dalam [Region](/psd/python-net/aspose.psd/region/) ini ketika digambar menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | float | Koordinat x dari sudut kiri atas persegi panjang yang akan diuji. |
| y | float | Koordinat y dari sudut kiri atas persegi panjang yang akan diuji. |
| width | float | Lebar persegi panjang yang akan diuji. |
| tinggi | float | Tinggi persegi panjang yang akan diuji. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Sebuah [Graphics](/psd/python-net/aspose.psd/graphics/) yang mewakili konteks grafis. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | true ketika sebagian apa pun dari persegi panjang yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/); jika tidak, false. |


### Method: is_visible(x, y, width, height, g) {#is_visible_x_y_width_height_g_30}


```
 is_visible(x, y, width, height, g) 
```

Menguji apakah bagian mana pun dari persegi panjang yang ditentukan terkandung dalam [Region](/psd/python-net/aspose.psd/region/) ini ketika digambar menggunakan [Graphics](/psd/python-net/aspose.psd/graphics/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | int | Koordinat x dari sudut kiri atas persegi panjang yang akan diuji. |
| y | int | Koordinat y dari sudut kiri atas persegi panjang yang akan diuji. |
| width | int | Lebar persegi panjang yang akan diuji. |
| tinggi | int | Tinggi persegi panjang yang akan diuji. |
| g | [Graphics](/psd/python-net/aspose.psd/graphics) | Sebuah [Graphics](/psd/python-net/aspose.psd/graphics/) yang mewakili konteks grafis. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | true ketika sebagian apa pun dari persegi panjang yang ditentukan berada di dalam [Region](/psd/python-net/aspose.psd/region/); jika tidak, false. |


### Method: transform(matrix) {#transform_matrix_31}


```
 transform(matrix) 
```

Mengubah [Region](/psd/python-net/aspose.psd/region/) ini dengan [Matrix](/psd/python-net/aspose.psd/matrix/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Matriks [Matrix](/psd/python-net/aspose.psd/matrix/) yang digunakan untuk mentransformasi [Region](/psd/python-net/aspose.psd/region/). |

### Method: translate(dx, dy) {#translate_dx_dy_32}


```
 translate(dx, dy) 
```

Menggeser koordinat [Region](/psd/python-net/aspose.psd/region/) ini sebesar jumlah yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dx | float | Jumlah untuk menggeser [Region](/psd/python-net/aspose.psd/region/) ini secara horizontal. |
| dy | float | Jumlah untuk menggeser [Region](/psd/python-net/aspose.psd/region/) ini secara vertikal. |

### Method: translate(dx, dy) {#translate_dx_dy_33}


```
 translate(dx, dy) 
```

Menggeser koordinat [Region](/psd/python-net/aspose.psd/region/) ini sebesar jumlah yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dx | int | Jumlah untuk menggeser [Region](/psd/python-net/aspose.psd/region/) ini secara horizontal. |
| dy | int | Jumlah untuk menggeser [Region](/psd/python-net/aspose.psd/region/) ini secara vertikal. |

### Method: union(path) {#union_path_34}


```
 union(path) 
```

Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi gabungan antara dirinya sendiri dan [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) untuk digabungkan dengan [Region](/psd/python-net/aspose.psd/region/) ini. |

### Method: union(rect) {#union_rect_35}


```
 union(rect) 
```

Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi gabungan antara dirinya sendiri dan struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) untuk digabungkan dengan [Region](/psd/python-net/aspose.psd/region/) ini. |

### Method: union(rect) {#union_rect_36}


```
 union(rect) 
```

Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi gabungan antara dirinya sendiri dan struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) untuk digabungkan dengan [Region](/psd/python-net/aspose.psd/region/) ini. |

### Method: union(region) {#union_region_37}


```
 union(region) 
```

Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi gabungan antara dirinya sendiri dan [Region](/psd/python-net/aspose.psd/region/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/) untuk digabungkan dengan [Region](/psd/python-net/aspose.psd/region/) ini. |

### Method: xor(path) {#xor_path_38}


```
 xor(path) 
```

Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi gabungan dikurangi irisan antara dirinya sendiri dengan [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) untuk XOR dengan [Region](/psd/python-net/aspose.psd/region/) ini. |

### Method: xor(rect) {#xor_rect_39}


```
 xor(rect) 
```

Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi gabungan dikurangi irisan antara dirinya sendiri dengan struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) untuk XOR dengan [Region](/psd/python-net/aspose.psd/region/) ini. |

### Method: xor(rect) {#xor_rect_40}


```
 xor(rect) 
```

Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi gabungan dikurangi irisan antara dirinya sendiri dengan struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) untuk XOR dengan [Region](/psd/python-net/aspose.psd/region/) ini. |

### Method: xor(region) {#xor_region_41}


```
 xor(region) 
```

Memperbarui [Region](/psd/python-net/aspose.psd/region/) ini menjadi gabungan dikurangi irisan antara dirinya sendiri dengan [Region](/psd/python-net/aspose.psd/region/) yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| region | [Region](/psd/python-net/aspose.psd/region) | [Region](/psd/python-net/aspose.psd/region/) untuk XOR dengan [Region](/psd/python-net/aspose.psd/region/) ini. |

