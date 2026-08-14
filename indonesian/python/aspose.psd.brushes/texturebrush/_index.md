---
title: "Kelas TextureBrush"
type: docs
weight: 90
url: /id/python-net/aspose.psd.brushes/texturebrush/
---

**Summary:** Each property of the [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) class is a [Brush](/psd/python-net/aspose.psd/brush/) object that uses an image to fill the interior of a shape. This class cannot be inherited.

**Module:** [aspose.psd.brushes](/psd/python-net/aspose.psd.brushes/)

**Full Name:** aspose.psd.brushes.TextureBrush

**Inheritance:** TransformBrush

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [TextureBrush(image)](#TextureBrush_image_1) | Menginisialisasi sebuah instance baru dari kelas [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) yang menggunakan gambar yang ditentukan. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_2) | Menginisialisasi sebuah instance baru dari kelas [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) yang menggunakan gambar yang ditentukan dan persegi panjang pembatas. |
| [TextureBrush(image, destination_rectangle)](#TextureBrush_image_destination_rectangle_3) | Menginisialisasi sebuah instance baru dari kelas [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) yang menggunakan gambar yang ditentukan dan persegi panjang pembatas. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_4) | Menginisialisasi sebuah instance baru dari kelas [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) yang menggunakan gambar yang ditentukan, persegi panjang pembatas, dan atribut gambar. |
| [TextureBrush(image, destination_rectangle, image_attributes)](#TextureBrush_image_destination_rectangle_image_attributes_5) | Menginisialisasi sebuah instance baru dari kelas [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) yang menggunakan gambar yang ditentukan, persegi panjang pembatas, dan atribut gambar. |
| [TextureBrush(image, wrap_mode)](#TextureBrush_image_wrap_mode_6) | Menginisialisasi sebuah instance baru dari kelas [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) yang menggunakan gambar yang ditentukan dan mode pembungkus. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_7) | Menginisialisasi sebuah instance baru dari kelas [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) yang menggunakan gambar yang ditentukan, mode pembungkus, dan persegi panjang pembatas. |
| [TextureBrush(image, wrap_mode, destination_rectangle)](#TextureBrush_image_wrap_mode_destination_rectangle_8) | Menginisialisasi sebuah instance baru dari kelas [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) yang menggunakan gambar yang ditentukan, mode pembungkus, dan persegi panjang pembatas. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| dibuang | bool | r | Mendapatkan nilai yang menunjukkan apakah instance ini telah dibuang. |
| image | [Image](/psd/python-net/aspose.psd/image) | r | Mendapatkan objek [Image](/psd/python-net/aspose.psd/image/) yang terkait dengan objek [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | r | Mendapatkan [TextureBrush.image_attributes](/psd/python-net/aspose.psd.brushes/texturebrush/) yang terkait dengan [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini. |
| image_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | Mendapatkan [Rectangle](/psd/python-net/aspose.psd/rectangle/) yang terkait dengan [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini. |
| is_transform_changed | bool | r | Mendapatkan nilai yang menunjukkan apakah transformasi telah diubah dengan cara tertentu. Misalnya mengatur matriks transformasi atau<br/>            memanggil salah satu metode yang mengubah matriks transformasi. Properti ini diperkenalkan untuk kompatibilitas mundur dengan GDI+. |
| opasitas | float | r/w | Mendapatkan atau mengatur opasitas kuas. Nilainya harus antara 0 dan 1. Nilai 0 berarti kuas sepenuhnya terlihat, nilai 1 berarti kuas sepenuhnya tidak tembus pandang. |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | r/w | Mendapatkan atau mengatur salinan [Matrix](/psd/python-net/aspose.psd/matrix/) yang mendefinisikan transformasi geometris lokal untuk [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | r/w | Mendapatkan atau mengatur enumerasi [WrapMode](/psd/python-net/aspose.psd/wrapmode/) yang menunjukkan mode pembungkus untuk [TransformBrush](/psd/python-net/aspose.psd.brushes/transformbrush/). |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [deep_clone()](#deep_clone__1) | Membuat klon dalam baru dari [Brush](/psd/python-net/aspose.psd/brush/) saat ini. |
| [multiply_transform(matrix)](#multiply_transform_matrix_2) | Mengalikan [Matrix](/psd/python-net/aspose.psd/matrix/) yang mewakili transformasi geometris lokal dari [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) dengan [Matrix](/psd/python-net/aspose.psd/matrix/) yang ditentukan dengan menambahkan [Matrix](/psd/python-net/aspose.psd/matrix/) yang ditentukan di depan. |
| [multiply_transform(matrix, order)](#multiply_transform_matrix_order_3) | Mengalikan [Matrix](/psd/python-net/aspose.psd/matrix/) yang mewakili transformasi geometris lokal dari [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) dengan [Matrix](/psd/python-net/aspose.psd/matrix/) dalam urutan yang ditentukan. |
| reset_transform() | Mengatur ulang properti [TransformBrush.transform](/psd/python-net/aspose.psd.brushes/transformbrush/) menjadi identitas. |
| [rotate_transform(angle)](#rotate_transform_angle_4) | Memutar transformasi geometrik lokal sebesar jumlah yang ditentukan. Metode ini menambahkan rotasi ke transformasi. |
| [rotate_transform(angle, order)](#rotate_transform_angle_order_5) | Memutar transformasi geometrik lokal sebesar jumlah yang ditentukan dalam urutan yang ditentukan. |
| [scale_transform(sx, sy)](#scale_transform_sx_sy_6) | Menskalakan transformasi geometrik lokal dengan nilai yang ditentukan. Metode ini menambahkan matriks skala ke transformasi. |
| [scale_transform(sx, sy, order)](#scale_transform_sx_sy_order_7) | Menskalakan transformasi geometrik lokal dengan nilai yang ditentukan dalam urutan yang ditentukan. |
| [translate_transform(dx, dy)](#translate_transform_dx_dy_8) | Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan. Metode ini menambahkan translasi ke transformasi. |
| [translate_transform(dx, dy, order)](#translate_transform_dx_dy_order_9) | Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan. |


### Constructor: TextureBrush(image) {#TextureBrush_image_1}


```
 TextureBrush(image) 
```

Menginisialisasi sebuah instance baru dari kelas [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) yang menggunakan gambar yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | [Image](/psd/python-net/aspose.psd/image/) objek yang digunakan oleh objek [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini untuk mengisi interior. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_2}


```
 TextureBrush(image, destination_rectangle) 
```

Menginisialisasi sebuah instance baru dari kelas [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) yang menggunakan gambar yang ditentukan dan persegi panjang pembatas.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | [Image](/psd/python-net/aspose.psd/image/) objek yang digunakan oleh objek [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini untuk mengisi interior. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mewakili persegi panjang pembatas untuk objek [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini. |

### Constructor: TextureBrush(image, destination_rectangle) {#TextureBrush_image_destination_rectangle_3}


```
 TextureBrush(image, destination_rectangle) 
```

Menginisialisasi sebuah instance baru dari kelas [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) yang menggunakan gambar yang ditentukan dan persegi panjang pembatas.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | [Image](/psd/python-net/aspose.psd/image/) objek yang digunakan oleh objek [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini untuk mengisi interior. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mewakili persegi panjang pembatas untuk objek [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_4}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Menginisialisasi sebuah instance baru dari kelas [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) yang menggunakan gambar yang ditentukan, persegi panjang pembatas, dan atribut gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | [Image](/psd/python-net/aspose.psd/image/) objek yang digunakan oleh objek [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini untuk mengisi interior. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mewakili persegi panjang pembatas untuk objek [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Sebuah objek [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) yang berisi informasi tambahan tentang gambar yang digunakan oleh objek [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini. |

### Constructor: TextureBrush(image, destination_rectangle, image_attributes) {#TextureBrush_image_destination_rectangle_image_attributes_5}


```
 TextureBrush(image, destination_rectangle, image_attributes) 
```

Menginisialisasi sebuah instance baru dari kelas [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) yang menggunakan gambar yang ditentukan, persegi panjang pembatas, dan atribut gambar.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | [Image](/psd/python-net/aspose.psd/image/) objek yang digunakan oleh objek [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini untuk mengisi interior. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mewakili persegi panjang pembatas untuk objek [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini. |
| image_attributes | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes) | Sebuah objek [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) yang berisi informasi tambahan tentang gambar yang digunakan oleh objek [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini. |

### Constructor: TextureBrush(image, wrap_mode) {#TextureBrush_image_wrap_mode_6}


```
 TextureBrush(image, wrap_mode) 
```

Menginisialisasi sebuah instance baru dari kelas [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) yang menggunakan gambar yang ditentukan dan mode pembungkus.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | [Image](/psd/python-net/aspose.psd/image/) objek yang digunakan oleh objek [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini untuk mengisi interior. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Sebuah enumerasi [WrapMode](/psd/python-net/aspose.psd/wrapmode/) yang menentukan bagaimana objek [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini ditata. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_7}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Menginisialisasi sebuah instance baru dari kelas [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) yang menggunakan gambar yang ditentukan, mode pembungkus, dan persegi panjang pembatas.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | [Image](/psd/python-net/aspose.psd/image/) objek yang digunakan oleh objek [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini untuk mengisi interior. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Sebuah enumerasi [WrapMode](/psd/python-net/aspose.psd/wrapmode/) yang menentukan bagaimana objek [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini ditata. |
| destination_rectangle | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mewakili persegi panjang pembatas untuk objek [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini. |

### Constructor: TextureBrush(image, wrap_mode, destination_rectangle) {#TextureBrush_image_wrap_mode_destination_rectangle_8}


```
 TextureBrush(image, wrap_mode, destination_rectangle) 
```

Menginisialisasi sebuah instance baru dari kelas [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) yang menggunakan gambar yang ditentukan, mode pembungkus, dan persegi panjang pembatas.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | [Image](/psd/python-net/aspose.psd/image/) objek yang digunakan oleh objek [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini untuk mengisi interior. |
| wrap_mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | Sebuah enumerasi [WrapMode](/psd/python-net/aspose.psd/wrapmode/) yang menentukan bagaimana objek [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini ditata. |
| destination_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mewakili persegi panjang pembatas untuk objek [TextureBrush](/psd/python-net/aspose.psd.brushes/texturebrush/) ini. |

### Method: deep_clone() {#deep_clone__1}


```
 deep_clone() 
```

Membuat klon dalam baru dari [Brush](/psd/python-net/aspose.psd/brush/) saat ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Brush](/psd/python-net/aspose.psd/brush) | Sebuah [Brush](/psd/python-net/aspose.psd/brush/) baru yang merupakan klon mendalam dari instance [Brush](/psd/python-net/aspose.psd/brush/) ini. |


### Method: multiply_transform(matrix) {#multiply_transform_matrix_2}


```
 multiply_transform(matrix) 
```

Mengalikan [Matrix](/psd/python-net/aspose.psd/matrix/) yang mewakili transformasi geometris lokal dari [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) dengan [Matrix](/psd/python-net/aspose.psd/matrix/) yang ditentukan dengan menambahkan [Matrix](/psd/python-net/aspose.psd/matrix/) yang ditentukan di depan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | [Matrix](/psd/python-net/aspose.psd/matrix/) yang digunakan untuk mengalikan transformasi geometrik. |

### Method: multiply_transform(matrix, order) {#multiply_transform_matrix_order_3}


```
 multiply_transform(matrix, order) 
```

Mengalikan [Matrix](/psd/python-net/aspose.psd/matrix/) yang mewakili transformasi geometris lokal dari [LinearGradientBrush](/psd/python-net/aspose.psd.brushes/lineargradientbrush/) dengan [Matrix](/psd/python-net/aspose.psd/matrix/) dalam urutan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | [Matrix](/psd/python-net/aspose.psd/matrix/) yang digunakan untuk mengalikan transformasi geometrik. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Sebuah [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) yang menentukan urutan pengalian kedua matriks. |

### Method: rotate_transform(angle) {#rotate_transform_angle_4}


```
 rotate_transform(angle) 
```

Memutar transformasi geometrik lokal sebesar jumlah yang ditentukan. Metode ini menambahkan rotasi ke transformasi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sudut | float | Sudut rotasi. |

### Method: rotate_transform(angle, order) {#rotate_transform_angle_order_5}


```
 rotate_transform(angle, order) 
```

Memutar transformasi geometrik lokal sebesar jumlah yang ditentukan dalam urutan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sudut | float | Sudut rotasi. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Sebuah [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) yang menentukan apakah akan menambahkan atau menyisipkan matriks rotasi. |

### Method: scale_transform(sx, sy) {#scale_transform_sx_sy_6}


```
 scale_transform(sx, sy) 
```

Menskalakan transformasi geometrik lokal dengan nilai yang ditentukan. Metode ini menambahkan matriks skala ke transformasi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sx | float | Jumlah skala yang diterapkan pada transformasi dalam arah sumbu x. |
| sy | float | Jumlah skala yang diterapkan pada transformasi dalam arah sumbu y. |

### Method: scale_transform(sx, sy, order) {#scale_transform_sx_sy_order_7}


```
 scale_transform(sx, sy, order) 
```

Menskalakan transformasi geometrik lokal dengan nilai yang ditentukan dalam urutan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sx | float | Jumlah skala yang diterapkan pada transformasi dalam arah sumbu x. |
| sy | float | Jumlah skala yang diterapkan pada transformasi dalam arah sumbu y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Sebuah [MatrixOrder](/psd/python-net/aspose.psd/matrixorder/) yang menentukan apakah akan menambahkan atau menyisipkan matriks skala. |

### Method: translate_transform(dx, dy) {#translate_transform_dx_dy_8}


```
 translate_transform(dx, dy) 
```

Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan. Metode ini menambahkan translasi ke transformasi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dx | float | Nilai translasi pada sumbu x. |
| dy | float | Nilai translasi pada sumbu y. |

### Method: translate_transform(dx, dy, order) {#translate_transform_dx_dy_order_9}


```
 translate_transform(dx, dy, order) 
```

Menerjemahkan transformasi geometrik lokal dengan dimensi yang ditentukan dalam urutan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| dx | float | Nilai translasi pada sumbu x. |
| dy | float | Nilai translasi pada sumbu y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Urutan (menambahkan di depan atau di belakang) untuk menerapkan translasi. |

