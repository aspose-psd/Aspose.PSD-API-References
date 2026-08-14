---
title: "Kelas TextShape"
type: docs
weight: 90
url: /id/python-net/aspose.psd.shapes/textshape/
---

**Summary:** Represents a text shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.TextShape

**Inheritance:** RectangleProjectedShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [TextShape()](#TextShape__1) | Menginisialisasi sebuah instance baru dari kelas [TextShape](/psd/python-net/aspose.psd.shapes/textshape/). |
| [TextShape(text, rectangle, font, string_format)](#TextShape_text_rectangle_font_string_format_2) | Menginisialisasi sebuah instance baru dari kelas [TextShape](/psd/python-net/aspose.psd.shapes/textshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Mendapatkan batas objek. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Mendapatkan pusat bentuk. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | r/w | Mendapatkan atau mengatur font yang digunakan untuk menggambar teks. |
| has_segments | bool | r | Mendapatkan nilai yang menunjukkan apakah bentuk memiliki segmen. |
| left_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Mendapatkan titik kiri bawah persegi panjang. |
| left_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Mendapatkan titik kiri atas persegi panjang. |
| rectangle_height | double | r | Mendapatkan tinggi persegi panjang. |
| rectangle_width | double | r | Mendapatkan lebar persegi panjang. |
| right_bottom | [PointF](/psd/python-net/aspose.psd/pointf) | r | Mendapatkan titik kanan bawah persegi panjang. |
| right_top | [PointF](/psd/python-net/aspose.psd/pointf) | r | Mendapatkan titik kanan atas persegi panjang. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Mendapatkan segmen bentuk. |
| text | string | r/w | Mendapatkan atau mengatur teks yang digambar. |
| text_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | r/w | Mendapatkan atau mengatur format teks. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Mendapatkan batas objek. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Mendapatkan batas objek. |
| [transform(transform)](#transform_transform_3) | Menerapkan transformasi yang ditentukan ke bentuk. |


### Constructor: TextShape() {#TextShape__1}


```
 TextShape() 
```

Menginisialisasi sebuah instance baru dari kelas [TextShape](/psd/python-net/aspose.psd.shapes/textshape/).

### Constructor: TextShape(text, rectangle, font, string_format) {#TextShape_text_rectangle_font_string_format_2}


```
 TextShape(text, rectangle, font, string_format) 
```

Menginisialisasi sebuah instance baru dari kelas [TextShape](/psd/python-net/aspose.psd.shapes/textshape/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| text | string | Teks yang akan digambar. |
| rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Persegi panjang teks. |
| font | [Font](/psd/python-net/aspose.psd.xmp.types.complex.font/font) | Font yang akan digunakan. |
| string_format | [StringFormat](/psd/python-net/aspose.psd/stringformat) | Format string. |

### Method: get_bounds(matrix) {#get_bounds_matrix_1}


```
 get_bounds(matrix) 
```

Mendapatkan batas objek.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Matriks yang akan diterapkan sebelum batas akan dihitung. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Batas objek yang diperkirakan. |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_2}


```
 get_bounds(matrix, pen) 
```

Mendapatkan batas objek.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | Matriks yang akan diterapkan sebelum batas akan dihitung. |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | Pen yang digunakan untuk objek. Ini dapat memengaruhi ukuran batas objek. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Batas objek yang diperkirakan. |


### Method: transform(transform) {#transform_transform_3}


```
 transform(transform) 
```

Menerapkan transformasi yang ditentukan ke bentuk.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | Transformasi yang akan diterapkan. |

