---
title: "Kelas CurveShape"
type: docs
weight: 30
url: /id/python-net/aspose.psd.shapes/curveshape/
---

**Summary:** Represents a curved spline shape.

**Module:** [aspose.psd.shapes](/psd/python-net/aspose.psd.shapes/)

**Full Name:** aspose.psd.shapes.CurveShape

**Inheritance:** IOrderedShape, PolygonShape

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [CurveShape()](#CurveShape__1) | Menginisialisasi sebuah instance baru dari kelas [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
| [CurveShape(points)](#CurveShape_points_2) | Menginisialisasi sebuah instance baru dari kelas [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Tegangan default sebesar 0.5 digunakan. |
| [CurveShape(points, is_closed)](#CurveShape_points_is_closed_3) | Menginisialisasi sebuah instance baru dari kelas [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Tegangan default sebesar 0.5 digunakan. |
| [CurveShape(points, tension)](#CurveShape_points_tension_4) | Menginisialisasi sebuah instance baru dari kelas [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
| [CurveShape(points, tension, is_closed)](#CurveShape_points_tension_is_closed_5) | Menginisialisasi sebuah instance baru dari kelas [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Mendapatkan batas objek. |
| center | [PointF](/psd/python-net/aspose.psd/pointf) | r | Mendapatkan pusat bentuk. |
| end_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Mendapatkan titik akhir bentuk. |
| has_segments | bool | r | Mendapatkan nilai yang menunjukkan apakah bentuk memiliki segmen. |
| is_closed | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah bentuk tertutup. |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | r/w | Mendapatkan atau mengatur titik kurva. |
| segments | [ShapeSegment[]](/psd/python-net/aspose.psd/shapesegment) | r | Mendapatkan segmen bentuk. |
| start_point | [PointF](/psd/python-net/aspose.psd/pointf) | r | Mendapatkan titik awal bentuk. |
| tegangan | float | r/w | Mendapatkan atau mengatur tegangan kurva. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_bounds(matrix)](#get_bounds_matrix_1) | Mendapatkan batas objek. |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_2) | Mendapatkan batas objek. |
| reverse() | Membalik urutan titik untuk bentuk ini. |
| [transform(transform)](#transform_transform_3) | Menerapkan transformasi yang ditentukan ke bentuk. |


### Constructor: CurveShape() {#CurveShape__1}


```
 CurveShape() 
```

Menginisialisasi sebuah instance baru dari kelas [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

### Constructor: CurveShape(points) {#CurveShape_points_2}


```
 CurveShape(points) 
```

Menginisialisasi sebuah instance baru dari kelas [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Tegangan default sebesar 0.5 digunakan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array titik. |

### Constructor: CurveShape(points, is_closed) {#CurveShape_points_is_closed_3}


```
 CurveShape(points, is_closed) 
```

Menginisialisasi sebuah instance baru dari kelas [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/). Tegangan default sebesar 0.5 digunakan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array titik. |
| is_closed | bool | Jika disetel ke <c>true</c> kurva akan tertutup. |

### Constructor: CurveShape(points, tension) {#CurveShape_points_tension_4}


```
 CurveShape(points, tension) 
```

Menginisialisasi sebuah instance baru dari kelas [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array titik. |
| tegangan | float | Tegangan kurva. |

### Constructor: CurveShape(points, tension, is_closed) {#CurveShape_points_tension_is_closed_5}


```
 CurveShape(points, tension, is_closed) 
```

Menginisialisasi sebuah instance baru dari kelas [CurveShape](/psd/python-net/aspose.psd.shapes/curveshape/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Array titik. |
| tegangan | float | Tegangan kurva. |
| is_closed | bool | Jika disetel ke <c>true</c> kurva akan tertutup. |

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

