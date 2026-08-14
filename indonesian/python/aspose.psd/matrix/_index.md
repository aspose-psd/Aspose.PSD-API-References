---
title: "Kelas Matrix"
type: docs
weight: 3000
url: /id/python-net/aspose.psd/matrix/
---

**Summary:** Replaces the GDI+ Matrix.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Matrix

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [Matrix()](#Matrix__1) | Menginisialisasi instance baru dari kelas Matrix sebagai matriks identitas. |
| [Matrix(m11, m12, m21, m22, m31, m32)](#Matrix_m11_m12_m21_m22_m31_m32_2) | Menginisialisasi instance baru dari kelas [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [Matrix(origin)](#Matrix_origin_3) | Membuat salinan kelas [Matrix](/psd/python-net/aspose.psd/matrix/). |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_4) | Menginisialisasi instance baru dari kelas [Matrix](/psd/python-net/aspose.psd/matrix/) ke transformasi geometrik yang didefinisikan oleh persegi panjang dan array titik yang ditentukan. |
| [Matrix(rect, plgpts)](#Matrix_rect_plgpts_5) | Menginisialisasi instance baru dari kelas [Matrix](/psd/python-net/aspose.psd/matrix/) ke transformasi geometrik yang didefinisikan oleh persegi panjang dan array titik yang ditentukan. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| TYPE_FLIP [static] | int | r | This bit flag menunjukkan bahwa transformasi yang didefinisikan oleh objek ini<br/>            melakukan pembalikan gambar cermin tentang suatu sumbu yang mengubah<br/>            sistem koordinat kanan normal menjadi sistem koordinat kiri<br/>            selain konversi yang ditunjukkan oleh bit flag lainnya.<br/>            Sistem koordinat kanan adalah yang dimana sumbu X positif<br/>            berputar berlawanan arah jarum jam untuk menumpuk pada sumbu Y positif<br/>            mirip dengan arah jari‑jari tangan kanan Anda<br/>            melengkung ketika Anda melihat ujung ibu jari secara langsung.<br/>            Sistem koordinat kiri adalah yang dimana sumbu X positif<br/>            berputar searah jarum jam untuk menumpuk pada sumbu Y positif mirip<br/>            dengan arah jari‑jari tangan kiri melengkung.<br/>            Tidak ada cara matematis untuk menentukan sudut dari<br/>            pembalikan atau transformasi cermin asli karena semua sudut<br/>            pembalikan identik dengan rotasi penyesuaian yang sesuai.<br/>            CATATAN: TypeFlip ditambahkan setelah GENERAL_TRANSFORM dipublikasikan<br/>            dan bit flag tidak dapat lagi diubah nomor secara nyaman<br/>            tanpa memperkenalkan ketidakcocokan biner dalam kode eksternal. |
| TYPE_GENERAL_ROTATION [static] | int | r | Bit flag ini menunjukkan bahwa transformasi yang didefinisikan oleh objek ini<br/>            melakukan rotasi dengan sudut sembarang selain konversi yang ditunjukkan oleh bit flag lainnya.<br/>            Rotasi mengubah sudut vektor dengan jumlah yang sama<br/>            terlepas dari arah asli vektor dan tanpa mengubah<br/>            panjang vektor.<br/>            Bit flag ini bersifat saling eksklusif dengan |
| TYPE_GENERAL_SCALE [static] | int | r | Skala umum mengalikan panjang vektor dengan nilai yang berbeda<br/>            pada arah x dan y tanpa mengubah sudut<br/>            antara vektor yang tegak lurus.<br/>            Bit flag ini bersifat saling eksklusif dengan flag TypeUniformScale. |
| TYPE_GENERAL_TRANSFORM [static] | int | r | Konstanta ini menunjukkan bahwa transformasi yang didefinisikan oleh objek ini<br/>            melakukan konversi sembarang dari koordinat masukan.<br/>            Jika transformasi ini dapat diklasifikasikan oleh salah satu konstanta di atas,<br/>            tipe akan menjadi konstanta TypeIdentity atau<br/>            kombinasi bit flag yang sesuai untuk berbagai konversi koordinat<br/>            yang dilakukan oleh transformasi ini. |
| TYPE_IDENTITY [static] | int | r | Transformasi identitas adalah yang dimana koordinat keluaran selalu<br/>            sama dengan koordinat masukan.<br/>            Jika transformasi ini bukan transformasi identitas,<br/>            tipe akan menjadi konstanta GENERAL_TRANSFORM atau<br/>            kombinasi bit flag yang sesuai untuk berbagai konversi koordinat<br/>            yang dilakukan oleh transformasi ini. |
| TYPE_MASK_ROTATION [static] | int | r | Konstanta ini adalah bit mask untuk semua bit flag rotasi. |
| TYPE_MASK_SCALE [static] | int | r | Konstanta ini adalah bit mask untuk semua bit flag skala. |
| TYPE_QUADRANT_ROTATION [static] | int | r | Bit flag ini menunjukkan bahwa transformasi yang didefinisikan oleh objek ini<br/>            melakukan rotasi kuadran dengan kelipatan 90 derajat selain konversi yang ditunjukkan oleh bit flag lainnya.<br/>            Rotasi mengubah sudut vektor dengan jumlah yang sama<br/>            terlepas dari arah asli vektor dan tanpa mengubah<br/>            panjang vektor.<br/>            Bit flag ini bersifat saling eksklusif dengan flag TypeGeneralRotation. |
| TYPE_TRANSLATION [static] | int | r | Translasi memindahkan koordinat dengan jumlah konstan pada x<br/>            dan y tanpa mengubah panjang atau sudut vektor. |
| TYPE_UNIFORM_SCALE [static] | int | r | Skala seragam mengalikan panjang vektor dengan jumlah yang sama<br/> dalam kedua arah x dan y tanpa mengubah sudut antara<br/> vektor.<br/> Bit flag ini saling eksklusif dengan flag TypeGeneralScale. |
| elements | float | r | Mendapatkan array nilai floating-point yang mewakili elemen-elemen dari [Matrix](/psd/python-net/aspose.psd/matrix/) ini. |
| m11 | float | r | Mendapatkan elemen matriks pada baris pertama kolom pertama. Mewakili skala sepanjang sumbu X. |
| m12 | float | r | Mendapatkan elemen matriks pada baris pertama kolom kedua. Mewakili geseran sepanjang sumbu Y. |
| m21 | float | r | Mendapatkan elemen matriks pada baris kedua kolom pertama. Mewakili geseran sepanjang sumbu X. |
| m22 | float | r | Mendapatkan elemen matriks pada baris kedua kolom kedua. Mewakili skala sepanjang sumbu Y. |
| m31 | float | r | Mendapatkan elemen matriks pada baris ketiga kolom pertama. Mewakili translasi sepanjang sumbu X. |
| m32 | float | r | Mendapatkan elemen matriks pada baris ketiga kolom pertama. Mewakili translasi sepanjang sumbu Y. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_elements()](#get_elements__1) | Mendapatkan salinan elemen-elemen matriks. |
| [multiply(tx)](#multiply_tx_2) | Mengalikan Matrix ini dengan matriks yang ditentukan dalam parameter matrix menggunakan urutan (default) Prepend. |
| [multiply(tx, order)](#multiply_tx_order_3) | Mengalikan Matrix ini dengan matriks yang ditentukan dalam parameter matrix, dan dalam urutan yang ditentukan dalam parameter order. |
| reset() | Mengatur ulang Matrix ini sehingga memiliki elemen-elemen dari matriks identitas. |
| [rotate(angle)](#rotate_angle_4) | Menerapkan rotasi searah jarum jam dengan jumlah yang ditentukan dalam parameter angle, sekitar titik asal (koordinat x dan y nol) untuk Matrix ini dalam urutan default (Prepend). |
| [rotate(angle, order)](#rotate_angle_order_5) | Menerapkan rotasi searah jarum jam dengan jumlah yang ditentukan dalam parameter angle, sekitar titik asal (koordinat x dan y nol) untuk Matrix ini dalam urutan yang ditentukan. |
| [rotate_at(angle, point)](#rotate_at_angle_point_6) | Menerapkan rotasi searah jarum jam sekitar titik yang ditentukan ke Matrix ini dalam urutan default (Prepend). |
| [rotate_at(angle, point, order)](#rotate_at_angle_point_order_7) | Menerapkan rotasi searah jarum jam sekitar titik yang ditentukan ke Matrix ini dalam urutan yang ditentukan. |
| [scale(scale_x, scale_y, order)](#scale_scale_x_scale_y_order_8) | Menerapkan vektor skala yang ditentukan (scaleX dan scaleY) ke [Matrix](/psd/python-net/aspose.psd/matrix/) ini menggunakan urutan yang ditentukan. |
| [scale(sx, sy)](#scale_sx_sy_9) | Menerapkan vektor skala yang ditentukan (scaleX dan scaleY) ke Matrix ini menggunakan urutan (default) Prepend. |
| [transform_points(points)](#transform_points_points_10) | Menerapkan transformasi geometrik yang diwakili oleh [Matrix](/psd/python-net/aspose.psd/matrix/) ini ke array titik yang ditentukan. |
| [translate(offset_x, offset_y, order)](#translate_offset_x_offset_y_order_11) | Menerapkan vektor translasi yang ditentukan ke Matrix ini dalam urutan yang ditentukan. |
| [translate(tx, ty)](#translate_tx_ty_12) | Menerapkan vektor translasi yang ditentukan ke [Matrix](/psd/python-net/aspose.psd/matrix/) ini menggunakan urutan Prepend (default). |


### Constructor: Matrix() {#Matrix__1}


```
 Matrix() 
```

Menginisialisasi instance baru dari kelas Matrix sebagai matriks identitas.

### Constructor: Matrix(m11, m12, m21, m22, m31, m32) {#Matrix_m11_m12_m21_m22_m31_m32_2}


```
 Matrix(m11, m12, m21, m22, m31, m32) 
```

Menginisialisasi instance baru dari kelas [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| m11 | float | m00     M11     Skala X |
| m12 | float | m10     M12     Shear Y |
| m21 | float | m01     M21     Shear X |
| m22 | float | m11     M22     Skala Y |
| m31 | float | m02     M31     Translate X |
| m32 | float | m12     M32     Translate Y |

### Constructor: Matrix(origin) {#Matrix_origin_3}


```
 Matrix(origin) 
```

Membuat salinan kelas [Matrix](/psd/python-net/aspose.psd/matrix/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| origin | [Matrix](/psd/python-net/aspose.psd/matrix) | Matriks dasar untuk penyalinan |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_4}


```
 Matrix(rect, plgpts) 
```

Menginisialisasi instance baru dari kelas [Matrix](/psd/python-net/aspose.psd/matrix/) ke transformasi geometrik yang didefinisikan oleh persegi panjang dan array titik yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | Sebuah struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mewakili persegi panjang yang akan diubah. |
| plgpts | [PointF[]](/psd/python-net/aspose.psd/pointf) | Sebuah array berisi tiga struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mewakili titik-titik sebuah paralelogram yang akan menjadi tujuan transformasi sudut kiri-atas, kanan-atas, dan kiri-bawah dari persegi panjang. Sudut kanan-bawah dari paralelogram diimplikasikan oleh tiga sudut pertama. |

### Constructor: Matrix(rect, plgpts) {#Matrix_rect_plgpts_5}


```
 Matrix(rect, plgpts) 
```

Menginisialisasi instance baru dari kelas [Matrix](/psd/python-net/aspose.psd/matrix/) ke transformasi geometrik yang didefinisikan oleh persegi panjang dan array titik yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Sebuah struktur [RectangleF](/psd/python-net/aspose.psd/rectanglef/) yang mewakili persegi panjang yang akan diubah. |
| plgpts | [Point[]](/psd/python-net/aspose.psd/point) | Sebuah array berisi tiga struktur [PointF](/psd/python-net/aspose.psd/pointf/) yang mewakili titik-titik sebuah paralelogram yang akan menjadi tujuan transformasi sudut kiri-atas, kanan-atas, dan kiri-bawah dari persegi panjang. Sudut kanan-bawah dari paralelogram diimplikasikan oleh tiga sudut pertama. |

### Method: get_elements() {#get_elements__1}


```
 get_elements() 
```

Mendapatkan salinan elemen-elemen matriks.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| float | Salinan elemen matriks. |


### Method: multiply(tx) {#multiply_tx_2}


```
 multiply(tx) 
```

Mengalikan Matrix ini dengan matriks yang ditentukan dalam parameter matrix menggunakan urutan (default) Prepend.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | Matriks yang akan dikalikan dengan. |

### Method: multiply(tx, order) {#multiply_tx_order_3}


```
 multiply(tx, order) 
```

Mengalikan Matrix ini dengan matriks yang ditentukan dalam parameter matrix, dan dalam urutan yang ditentukan dalam parameter order.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| tx | [Matrix](/psd/python-net/aspose.psd/matrix) | Tx-nya. Tx-nya. Tx-nya. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Urutannya. Urutannya. Urutannya. |

### Method: rotate(angle) {#rotate_angle_4}


```
 rotate(angle) 
```

Menerapkan rotasi searah jarum jam dengan jumlah yang ditentukan dalam parameter angle, sekitar titik asal (koordinat x dan y nol) untuk Matrix ini dalam urutan default (Prepend).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sudut | float | Sudut rotasi. |

### Method: rotate(angle, order) {#rotate_angle_order_5}


```
 rotate(angle, order) 
```

Menerapkan rotasi searah jarum jam dengan jumlah yang ditentukan dalam parameter angle, sekitar titik asal (koordinat x dan y nol) untuk Matrix ini dalam urutan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sudut | float | Sudut rotasi. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Urutan matriks. |

### Method: rotate_at(angle, point) {#rotate_at_angle_point_6}


```
 rotate_at(angle, point) 
```

Menerapkan rotasi searah jarum jam sekitar titik yang ditentukan ke Matrix ini dalam urutan default (Prepend).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sudut | float | Sudut. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Titik tersebut. |

### Method: rotate_at(angle, point, order) {#rotate_at_angle_point_order_7}


```
 rotate_at(angle, point, order) 
```

Menerapkan rotasi searah jarum jam sekitar titik yang ditentukan ke Matrix ini dalam urutan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sudut | float | Sudut. |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | Titik tersebut. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Urutan. |

### Method: scale(scale_x, scale_y, order) {#scale_scale_x_scale_y_order_8}


```
 scale(scale_x, scale_y, order) 
```

Menerapkan vektor skala yang ditentukan (scaleX dan scaleY) ke [Matrix](/psd/python-net/aspose.psd/matrix/) ini menggunakan urutan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| scale_x | float | Skala X. |
| scale_y | float | Skala Y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Urutan. |

### Method: scale(sx, sy) {#scale_sx_sy_9}


```
 scale(sx, sy) 
```

Menerapkan vektor skala yang ditentukan (scaleX dan scaleY) ke Matrix ini menggunakan urutan (default) Prepend.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sx | float | Sx-nya. Sx-nya. Sx-nya. |
| sy | float | Sy-nya. Sy-nya. Sy-nya. |

### Method: transform_points(points) {#transform_points_points_10}


```
 transform_points(points) 
```

Menerapkan transformasi geometrik yang diwakili oleh [Matrix](/psd/python-net/aspose.psd/matrix/) ini ke array titik yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| points | [PointF[]](/psd/python-net/aspose.psd/pointf) | Titik-titik. |

### Method: translate(offset_x, offset_y, order) {#translate_offset_x_offset_y_order_11}


```
 translate(offset_x, offset_y, order) 
```

Menerapkan vektor translasi yang ditentukan ke Matrix ini dalam urutan yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| offset_x | float | Offset X. |
| offset_y | float | Offset Y. |
| order | [MatrixOrder](/psd/python-net/aspose.psd/matrixorder) | Urutan. |

### Method: translate(tx, ty) {#translate_tx_ty_12}


```
 translate(tx, ty) 
```

Menerapkan vektor translasi yang ditentukan ke [Matrix](/psd/python-net/aspose.psd/matrix/) ini menggunakan urutan Prepend (default).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| tx | float | Tx-nya. Tx-nya. Tx-nya. |
| ty | float | ty. ty. ty. |

