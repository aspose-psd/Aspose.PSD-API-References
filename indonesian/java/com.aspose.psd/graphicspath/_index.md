---
title: "GraphicsPath"
second_title: "Aspose.PSD untuk Java Referensi API"
description: "Mewakili serangkaian garis dan kurva yang terhubung."
type: docs
weight: 50
url: /id/java/com.aspose.psd/graphicspath/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.ObjectWithBounds](../../com.aspose.psd/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

Mewakili serangkaian garis dan kurva yang terhubung. Kelas ini tidak dapat diwarisi.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | Menginisialisasi sebuah instance baru dari kelas GraphicsPath. |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.psd.Figure---) | Menginisialisasi sebuah instance baru dari kelas GraphicsPath. |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.psd.Figure---int-) | Menginisialisasi sebuah instance baru dari kelas GraphicsPath. |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | Menginisialisasi sebuah instance baru dari kelas GraphicsPath. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addFigure(Figure figure)](#addFigure-com.aspose.psd.Figure-) | Menambahkan sebuah figur baru. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.psd.Figure---) | Menambahkan figur-figur baru. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.psd.GraphicsPath-) | Menambahkan com.aspose.psd.GraphicsPath yang ditentukan ke jalur ini. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.psd.GraphicsPath-boolean-) | Menambahkan com.aspose.psd.GraphicsPath yang ditentukan ke jalur ini. |
| [deepClone()](#deepClone--) | Melakukan kloning mendalam dari jalur grafis ini. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | Mengonversi setiap kurva dalam jalur ini menjadi urutan segmen garis yang terhubung. |
| [flatten(Matrix matrix)](#flatten-com.aspose.psd.Matrix-) | Menerapkan transformasi yang ditentukan dan kemudian mengonversi setiap kurva dalam com.aspose.psd.GraphicsPath ini menjadi urutan segmen garis yang terhubung. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.psd.Matrix-float-) | Mengonversi setiap kurva dalam com.aspose.psd.GraphicsPath ini menjadi urutan segmen garis yang terhubung. |
| [getBounds()](#getBounds--) | Mendapatkan atau mengatur batas objek. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.psd.Matrix-) | Mendapatkan batas objek. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-) | Mendapatkan batas objek. |
| [getClass()](#getClass--) |  |
| [getFigures()](#getFigures--) | Mendapatkan figur-figur jalur. |
| [getFillMode()](#getFillMode--) | Mendapatkan enumerasi com.aspose.psd.FillMode yang menentukan bagaimana interior bentuk dalam com.aspose.psd.GraphicsPath ini diisi. |
| [hashCode()](#hashCode--) |  |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur com.aspose.psd.GraphicsPath ini ketika digambar dengan com.aspose.psd.pen yang ditentukan. |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur com.aspose.psd.GraphicsPath ini ketika digambar dengan com.aspose.psd.Pen yang ditentukan dan menggunakan com.aspose.psd.graphics yang ditentukan. |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur com.aspose.psd.GraphicsPath ini ketika digambar dengan com.aspose.psd.pen yang ditentukan. |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur com.aspose.psd.GraphicsPath ini ketika digambar dengan com.aspose.psd.Pen yang ditentukan dan menggunakan com.aspose.psd.graphics yang ditentukan. |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.psd.Pen-) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur com.aspose.psd.GraphicsPath ini ketika digambar dengan com.aspose.psd.pen yang ditentukan. |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur com.aspose.psd.GraphicsPath ini ketika digambar dengan com.aspose.psd.Pen yang ditentukan dan menggunakan com.aspose.psd.graphics yang ditentukan. |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.psd.Pen-) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur com.aspose.psd.GraphicsPath ini ketika digambar dengan com.aspose.psd.pen yang ditentukan. |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-) | Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur com.aspose.psd.GraphicsPath ini ketika digambar dengan com.aspose.psd.Pen yang ditentukan dan menggunakan com.aspose.psd.graphics yang ditentukan. |
| [isVisible(Point point)](#isVisible-com.aspose.psd.Point-) | Menunjukkan apakah titik yang ditentukan berada di dalam com.aspose.psd.graphicsPath ini. |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-) | Menunjukkan apakah titik yang ditentukan berada di dalam com.aspose.psd.graphicsPath ini. |
| [isVisible(PointF point)](#isVisible-com.aspose.psd.PointF-) | Menunjukkan apakah titik yang ditentukan berada di dalam com.aspose.psd.graphicsPath ini. |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-) | Menunjukkan apakah titik yang ditentukan berada di dalam com.aspose.psd.graphicsPath ini. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Menunjukkan apakah titik yang ditentukan berada di dalam com.aspose.psd.graphicsPath ini. |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.psd.Graphics-) | Menunjukkan apakah titik yang ditentukan berada di dalam com.aspose.psd.GraphicsPath ini dalam wilayah klip yang terlihat dari com.aspose.psd.graphics yang ditentukan. |
| [isVisible(int x, int y)](#isVisible-int-int-) | Menunjukkan apakah titik yang ditentukan berada di dalam com.aspose.psd.graphicsPath ini. |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.psd.Graphics-) | Menunjukkan apakah titik yang ditentukan berada di dalam com.aspose.psd.GraphicsPath ini, menggunakan com.aspose.psd.graphics yang ditentukan. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.psd.Figure-) | Menghapus sebuah figur. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.psd.Figure---) | Menghapus figur. |
| [reset()](#reset--) | Mengosongkan jalur grafis dan mengatur com.aspose.psd.FillMode ke F:com.aspose.psd.fillMode.alternate. |
| [reverse()](#reverse--) | Membalik urutan figur, bentuk, dan titik dalam setiap bentuk pada com.aspose.psd.graphicsPath ini. |
| [setFillMode(int value)](#setFillMode-int-) | Mengatur enumerasi com.aspose.psd.FillMode yang menentukan bagaimana interior bentuk dalam com.aspose.psd.GraphicsPath ini diisi. |
| [toString()](#toString--) |  |
| [transform(Matrix transform)](#transform-com.aspose.psd.Matrix-) | Menerapkan transformasi yang ditentukan ke bentuk. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-) | Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan paralelogram, ke com.aspose.psd.graphicsPath ini. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-) | Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan paralelogram, ke com.aspose.psd.graphicsPath ini. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-) | Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan paralelogram, ke com.aspose.psd.graphicsPath ini. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-) | Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan paralelogram, ke com.aspose.psd.graphicsPath ini. |
| [widen(Pen pen)](#widen-com.aspose.psd.Pen-) | Menambahkan garis luar tambahan ke jalur. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-) | Menambahkan garis luar tambahan ke com.aspose.psd.graphicsPath. |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-) | Mengganti com.aspose.psd.GraphicsPath ini dengan kurva yang melingkupi area yang diisi ketika jalur ini digambar dengan pena yang ditentukan. |
### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


Menginisialisasi sebuah instance baru dari kelas GraphicsPath.

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.psd.Figure---}
```
public GraphicsPath(Figure[] figures)
```


Menginisialisasi sebuah instance baru dari kelas GraphicsPath.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Figur-figur untuk diinisialisasi dari. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.psd.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


Menginisialisasi sebuah instance baru dari kelas GraphicsPath.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Figur-figur untuk diinisialisasi dari. |
| fillMode | int | Mode pengisian. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


Menginisialisasi sebuah instance baru dari kelas GraphicsPath.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fillMode | int | Mode pengisian. |

### addFigure(Figure figure) {#addFigure-com.aspose.psd.Figure-}
```
public void addFigure(Figure figure)
```


Menambahkan sebuah figur baru.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | Figur yang akan ditambahkan. |

### addFigures(Figure[] figures) {#addFigures-com.aspose.psd.Figure---}
```
public void addFigures(Figure[] figures)
```


Menambahkan figur-figur baru.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Figur-figur yang akan ditambahkan. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.psd.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


Menambahkan com.aspose.psd.GraphicsPath yang ditentukan ke jalur ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath yang akan ditambahkan. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.psd.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


Menambahkan com.aspose.psd.GraphicsPath yang ditentukan ke jalur ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | com.aspose.psd.GraphicsPath yang akan ditambahkan. |
| connect | boolean | Nilai Boolean yang menentukan apakah figur pertama dalam jalur yang ditambahkan merupakan bagian dari figur terakhir dalam jalur ini. Nilai true menunjukkan bahwa figur pertama dalam jalur yang ditambahkan merupakan bagian dari figur terakhir dalam jalur ini. Nilai false menunjukkan bahwa figur pertama dalam jalur yang ditambahkan terpisah dari figur terakhir dalam jalur ini. |

### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


Melakukan kloning mendalam dari jalur grafis ini.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - A deep clone of the graphics path.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### flatten() {#flatten--}
```
public void flatten()
```


Mengonversi setiap kurva dalam jalur ini menjadi urutan segmen garis yang terhubung.

### flatten(Matrix matrix) {#flatten-com.aspose.psd.Matrix-}
```
public void flatten(Matrix matrix)
```


Menerapkan transformasi yang ditentukan dan kemudian mengonversi setiap kurva dalam com.aspose.psd.GraphicsPath ini menjadi urutan segmen garis yang terhubung.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Sebuah com.aspose.psd.Matrix yang digunakan untuk mentransformasi com.aspose.psd.GraphicsPath ini sebelum diratakan. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.psd.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


Mengonversi setiap kurva dalam com.aspose.psd.GraphicsPath ini menjadi urutan segmen garis yang terhubung.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Sebuah com.aspose.psd.Matrix yang digunakan untuk mentransformasi com.aspose.psd.GraphicsPath ini sebelum diratakan. |
| flatness | float | Menentukan kesalahan maksimum yang diizinkan antara kurva dan pendekatan yang diratakan. Nilai default adalah 0,25. Mengurangi nilai flatness akan meningkatkan jumlah segmen garis dalam pendekatan. |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Mendapatkan atau mengatur batas objek.

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The object's bounds.
### getBounds(Matrix matrix) {#getBounds-com.aspose.psd.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Mendapatkan batas objek.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Matriks yang akan diterapkan sebelum batas dihitung. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.psd.Matrix-com.aspose.psd.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Mendapatkan batas objek.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Matriks yang akan diterapkan sebelum batas dihitung. |
| pen | [Pen](../../com.aspose.psd/pen) | Pulpen yang digunakan untuk objek. Ini dapat memengaruhi ukuran batas objek. |

**Returns:**
[RectangleF](../../com.aspose.psd/rectanglef) - The estimated object's bounds.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


Mendapatkan figur-figur jalur.

**Returns:**
com.aspose.psd.Figure[] - Figur-figur jalur.
### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


Mendapatkan enumerasi com.aspose.psd.FillMode yang menentukan bagaimana interior bentuk dalam com.aspose.psd.GraphicsPath ini diisi.

**Returns:**
int - Mode pengisian. Sebuah enumerasi com.aspose.psd.FillMode yang menentukan bagaimana interior bentuk dalam com.aspose.psd.GraphicsPath ini diisi.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur com.aspose.psd.GraphicsPath ini ketika digambar dengan com.aspose.psd.pen yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Sebuah com.aspose.psd.Point yang menentukan lokasi untuk diuji. |
| pen | [Pen](../../com.aspose.psd/pen) | Pen com.aspose.psd untuk diuji. |

**Returns:**
boolean - Metode ini mengembalikan true jika titik yang ditentukan berada di dalam kontur com.aspose.psd.GraphicsPath ini ketika digambar dengan com.aspose.psd.Pen yang ditentukan; jika tidak, false.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.Point-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur com.aspose.psd.GraphicsPath ini ketika digambar dengan com.aspose.psd.Pen yang ditentukan dan menggunakan com.aspose.psd.graphics yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | Sebuah com.aspose.psd.Point yang menentukan lokasi untuk diuji. |
| pen | [Pen](../../com.aspose.psd/pen) | Pen com.aspose.psd untuk diuji. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | com.aspose.psd.Graphics untuk menguji visibilitas. |

**Returns:**
boolean - Metode ini mengembalikan true jika titik yang ditentukan berada di dalam kontur com.aspose.psd.GraphicsPath ini sebagaimana digambar dengan com.aspose.psd.Pen yang ditentukan; jika tidak, false.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur com.aspose.psd.GraphicsPath ini ketika digambar dengan com.aspose.psd.pen yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Sebuah com.aspose.psd.PointF yang menentukan lokasi untuk diuji. |
| pen | [Pen](../../com.aspose.psd/pen) | Pen com.aspose.psd untuk diuji. |

**Returns:**
boolean - Metode ini mengembalikan true jika titik yang ditentukan berada di dalam kontur com.aspose.psd.GraphicsPath ini ketika digambar dengan com.aspose.psd.Pen yang ditentukan; jika tidak, false.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.psd.PointF-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur com.aspose.psd.GraphicsPath ini ketika digambar dengan com.aspose.psd.Pen yang ditentukan dan menggunakan com.aspose.psd.graphics yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | Sebuah com.aspose.psd.PointF yang menentukan lokasi untuk diuji. |
| pen | [Pen](../../com.aspose.psd/pen) | Pen com.aspose.psd untuk diuji. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | com.aspose.psd.Graphics untuk menguji visibilitas. |

**Returns:**
boolean - Metode ini mengembalikan true jika titik yang ditentukan berada di dalam (di bawah) kontur com.aspose.psd.GraphicsPath ini sebagaimana digambar dengan com.aspose.psd.Pen yang ditentukan; jika tidak, false.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur com.aspose.psd.GraphicsPath ini ketika digambar dengan com.aspose.psd.pen yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari titik yang akan diuji. |
| y | float | Koordinat y dari titik yang akan diuji. |
| pen | [Pen](../../com.aspose.psd/pen) | Pen com.aspose.psd untuk diuji. |

**Returns:**
boolean - Metode ini mengembalikan true jika titik yang ditentukan berada di dalam kontur com.aspose.psd.GraphicsPath ini ketika digambar dengan com.aspose.psd.Pen yang ditentukan; jika tidak, false.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur com.aspose.psd.GraphicsPath ini ketika digambar dengan com.aspose.psd.Pen yang ditentukan dan menggunakan com.aspose.psd.graphics yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari titik yang akan diuji. |
| y | float | Koordinat y dari titik yang akan diuji. |
| pen | [Pen](../../com.aspose.psd/pen) | Pen com.aspose.psd untuk diuji. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | com.aspose.psd.Graphics untuk menguji visibilitas. |

**Returns:**
boolean - Metode ini mengembalikan true jika titik yang ditentukan berada di dalam (di bawah) kontur com.aspose.psd.GraphicsPath ini sebagaimana digambar dengan com.aspose.psd.Pen yang ditentukan; jika tidak, false.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.psd.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur com.aspose.psd.GraphicsPath ini ketika digambar dengan com.aspose.psd.pen yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Koordinat x dari titik yang akan diuji. |
| y | int | Koordinat y dari titik yang akan diuji. |
| pen | [Pen](../../com.aspose.psd/pen) | Pen com.aspose.psd untuk diuji. |

**Returns:**
boolean - Metode ini mengembalikan true jika titik yang ditentukan berada di dalam kontur com.aspose.psd.GraphicsPath ini ketika digambar dengan com.aspose.psd.Pen yang ditentukan; jika tidak, false.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.psd.Pen-com.aspose.psd.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


Menunjukkan apakah titik yang ditentukan berada di dalam (di bawah) kontur com.aspose.psd.GraphicsPath ini ketika digambar dengan com.aspose.psd.Pen yang ditentukan dan menggunakan com.aspose.psd.graphics yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Koordinat x dari titik yang akan diuji. |
| y | int | Koordinat y dari titik yang akan diuji. |
| pen | [Pen](../../com.aspose.psd/pen) | Pen com.aspose.psd untuk diuji. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | com.aspose.psd.Graphics untuk menguji visibilitas. |

**Returns:**
boolean - Metode ini mengembalikan true jika titik yang ditentukan berada di dalam kontur com.aspose.psd.GraphicsPath ini sebagaimana digambar dengan com.aspose.psd.Pen yang ditentukan; jika tidak, false.
### isVisible(Point point) {#isVisible-com.aspose.psd.Point-}
```
public boolean isVisible(Point point)
```


Menunjukkan apakah titik yang ditentukan berada di dalam com.aspose.psd.graphicsPath ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [Point](../../com.aspose.psd/point) | Sebuah com.aspose.psd.Point yang mewakili titik untuk diuji. |

**Returns:**
boolean - Metode ini mengembalikan true jika titik yang ditentukan berada di dalam com.aspose.psd.GraphicsPath ini; jika tidak, false.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.psd.Point-com.aspose.psd.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


Menunjukkan apakah titik yang ditentukan berada di dalam com.aspose.psd.graphicsPath ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pt | [Point](../../com.aspose.psd/point) | Sebuah com.aspose.psd.Point yang mewakili titik untuk diuji. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | com.aspose.psd.Graphics untuk menguji visibilitas. |

**Returns:**
boolean - Metode ini mengembalikan true jika titik yang ditentukan berada di dalam com.aspose.psd.GraphicsPath ini; jika tidak, false.
### isVisible(PointF point) {#isVisible-com.aspose.psd.PointF-}
```
public boolean isVisible(PointF point)
```


Menunjukkan apakah titik yang ditentukan berada di dalam com.aspose.psd.graphicsPath ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| point | [PointF](../../com.aspose.psd/pointf) | Sebuah com.aspose.psd.PointF yang mewakili titik untuk diuji. |

**Returns:**
boolean - Metode ini mengembalikan true jika titik yang ditentukan berada di dalam com.aspose.psd.GraphicsPath ini; jika tidak, false.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.psd.PointF-com.aspose.psd.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


Menunjukkan apakah titik yang ditentukan berada di dalam com.aspose.psd.graphicsPath ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.psd/pointf) | Sebuah com.aspose.psd.PointF yang mewakili titik untuk diuji. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | com.aspose.psd.Graphics untuk menguji visibilitas. |

**Returns:**
boolean - Metode ini mengembalikan true jika titik yang ditentukan berada di dalam ini; jika tidak, false.
### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Menunjukkan apakah titik yang ditentukan berada di dalam com.aspose.psd.graphicsPath ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari titik yang akan diuji. |
| y | float | Koordinat y dari titik yang akan diuji. |

**Returns:**
boolean - Metode ini mengembalikan true jika titik yang ditentukan berada di dalam com.aspose.psd.GraphicsPath ini; jika tidak, false.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.psd.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


Menunjukkan apakah titik yang ditentukan berada di dalam com.aspose.psd.GraphicsPath ini dalam wilayah klip yang terlihat dari com.aspose.psd.graphics yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | float | Koordinat x dari titik yang akan diuji. |
| y | float | Koordinat y dari titik yang akan diuji. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | com.aspose.psd.Graphics untuk menguji visibilitas. |

**Returns:**
boolean - Metode ini mengembalikan true jika titik yang ditentukan berada di dalam com.aspose.psd.GraphicsPath ini; jika tidak, false.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


Menunjukkan apakah titik yang ditentukan berada di dalam com.aspose.psd.graphicsPath ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Koordinat x dari titik yang akan diuji. |
| y | int | Koordinat y dari titik yang akan diuji. |

**Returns:**
boolean - Metode ini mengembalikan true jika titik yang ditentukan berada di dalam com.aspose.psd.GraphicsPath ini; jika tidak, false.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.psd.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


Menunjukkan apakah titik yang ditentukan berada di dalam com.aspose.psd.GraphicsPath ini, menggunakan com.aspose.psd.graphics yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | int | Koordinat x dari titik yang akan diuji. |
| y | int | Koordinat y dari titik yang akan diuji. |
| graphics | [Graphics](../../com.aspose.psd/graphics) | com.aspose.psd.Graphics untuk menguji visibilitas. |

**Returns:**
boolean - Metode ini mengembalikan true jika titik yang ditentukan berada di dalam com.aspose.psd.GraphicsPath ini; jika tidak, false.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeFigure(Figure figure) {#removeFigure-com.aspose.psd.Figure-}
```
public void removeFigure(Figure figure)
```


Menghapus sebuah figur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.psd/figure) | Figur yang akan dihapus. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.psd.Figure---}
```
public void removeFigures(Figure[] figures)
```


Menghapus figur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.psd/figure) | Figur-figur yang akan dihapus. |

### reset() {#reset--}
```
public void reset()
```


Mengosongkan jalur grafis dan mengatur com.aspose.psd.FillMode ke F:com.aspose.psd.fillMode.alternate.

### reverse() {#reverse--}
```
public void reverse()
```


Membalik urutan figur, bentuk, dan titik dalam setiap bentuk pada com.aspose.psd.graphicsPath ini.

### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


Mengatur enumerasi com.aspose.psd.FillMode yang menentukan bagaimana interior bentuk dalam com.aspose.psd.GraphicsPath ini diisi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int | Mode pengisian. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transform(Matrix transform) {#transform-com.aspose.psd.Matrix-}
```
public void transform(Matrix transform)
```


Menerapkan transformasi yang ditentukan ke bentuk.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.psd/matrix) | Transformasi yang akan diterapkan. |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan paralelogram, ke com.aspose.psd.graphicsPath ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array struktur com.aspose.psd.PointF yang mendefinisikan sebuah paralelogram tempat persegi panjang yang didefinisikan oleh srcRect ditransformasikan. Array dapat berisi tiga atau empat elemen. Jika array berisi tiga elemen, sudut kanan-bawah paralelogram diimplikasikan oleh tiga titik pertama. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Sebuah com.aspose.psd.RectangleF yang mewakili persegi panjang yang ditransformasikan menjadi paralelogram yang didefinisikan oleh destPoints. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan paralelogram, ke com.aspose.psd.graphicsPath ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array struktur com.aspose.psd.PointF yang mendefinisikan sebuah paralelogram tempat persegi panjang yang didefinisikan oleh srcRect ditransformasikan. Array dapat berisi tiga atau empat elemen. Jika array berisi tiga elemen, sudut kanan-bawah paralelogram diimplikasikan oleh tiga titik pertama. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Sebuah com.aspose.psd.RectangleF yang mewakili persegi panjang yang ditransformasikan menjadi paralelogram yang didefinisikan oleh destPoints. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Sebuah com.aspose.psd.Matrix yang menentukan transformasi geometris yang diterapkan pada jalur. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan paralelogram, ke com.aspose.psd.graphicsPath ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array struktur com.aspose.psd.PointF yang mendefinisikan sebuah paralelogram tempat persegi panjang yang didefinisikan oleh srcRect ditransformasikan. Array dapat berisi tiga atau empat elemen. Jika array berisi tiga elemen, sudut kanan-bawah paralelogram diimplikasikan oleh tiga titik pertama. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Sebuah com.aspose.psd.RectangleF yang mewakili persegi panjang yang ditransformasikan menjadi paralelogram yang didefinisikan oleh destPoints. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Sebuah com.aspose.psd.Matrix yang menentukan transformasi geometris yang diterapkan pada jalur. |
| warpMode | int | Enumerasi com.aspose.psd.WarpMode yang menentukan apakah operasi warp ini menggunakan mode perspektif atau bilinear. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.psd.PointF---com.aspose.psd.RectangleF-com.aspose.psd.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


Menerapkan transformasi warp, yang didefinisikan oleh sebuah persegi panjang dan paralelogram, ke com.aspose.psd.graphicsPath ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Array struktur com.aspose.psd.PointF yang mendefinisikan sebuah paralelogram tempat persegi panjang yang didefinisikan oleh srcRect ditransformasikan. Array dapat berisi tiga atau empat elemen. Jika array berisi tiga elemen, sudut kanan-bawah paralelogram diimplikasikan oleh tiga titik pertama. |
| srcRect | [RectangleF](../../com.aspose.psd/rectanglef) | Sebuah com.aspose.psd.RectangleF yang mewakili persegi panjang yang ditransformasikan menjadi paralelogram yang didefinisikan oleh destPoints. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Sebuah com.aspose.psd.Matrix yang menentukan transformasi geometris yang diterapkan pada jalur. |
| warpMode | int | Enumerasi com.aspose.psd.WarpMode yang menentukan apakah operasi warp ini menggunakan mode perspektif atau bilinear. |
| flatness | float | Nilai antara 0 hingga 1 yang menentukan seberapa datar jalur yang dihasilkan. Untuk informasi lebih lanjut, lihat metode com.aspose.psd.GraphicsPath.flatten. |

### widen(Pen pen) {#widen-com.aspose.psd.Pen-}
```
public void widen(Pen pen)
```


Menambahkan garis luar tambahan ke jalur.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen com.aspose.psd yang menentukan lebar antara kontur asli jalur dan kontur baru yang dibuat oleh metode ini. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


Menambahkan garis luar tambahan ke com.aspose.psd.graphicsPath.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen com.aspose.psd yang menentukan lebar antara kontur asli jalur dan kontur baru yang dibuat oleh metode ini. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Matrix com.aspose.psd yang menentukan transformasi yang diterapkan pada jalur sebelum diperlebar. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.psd.Pen-com.aspose.psd.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


Mengganti com.aspose.psd.GraphicsPath ini dengan kurva yang melingkupi area yang diisi ketika jalur ini digambar dengan pena yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.psd/pen) | Pen com.aspose.psd yang menentukan lebar antara kontur asli jalur dan kontur baru yang dibuat oleh metode ini. |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Matrix com.aspose.psd yang menentukan transformasi yang diterapkan pada jalur sebelum diperlebar. |
| flatness | float | Nilai yang menentukan kelandutan untuk kurva. |

