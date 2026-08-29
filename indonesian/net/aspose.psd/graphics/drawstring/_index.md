---
title: "Graphics.DrawString"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Metode Graphics. Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek Brush dan Font yang ditentukan."
type: docs
weight: 330
url: /id/net/aspose.psd/graphics/drawstring/
---
{{< psd/tize >}}
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek [`Brush`](../../brush/) dan [`Font`](../../font/) yang ditentukan.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | String | String untuk digambar. |
| font | Font | [`Font`](../../font/) yang mendefinisikan format teks dari string. |
| brush | Brush | [`Brush`](../../brush/) yang menentukan warna dan tekstur teks yang digambar. |
| x | Single | Koordinat x dari sudut kiri atas teks yang digambar. |
| y | Single | Koordinat y dari sudut kiri atas teks yang digambar. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *brush* bernilai null. -atau- *s* bernilai null. |

### Lihat Juga

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek [`Brush`](../../brush/) dan [`Font`](../../font/) yang ditentukan.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | String | String untuk digambar. |
| font | Font | [`Font`](../../font/) yang mendefinisikan format teks dari string. |
| brush | Brush | [`Brush`](../../brush/) yang menentukan warna dan tekstur teks yang digambar. |
| point | PointF | [`PointF`](../../pointf/) struktur yang menentukan sudut kiri atas teks yang digambar. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *brush* bernilai null. -atau- *s* bernilai null. |

## Contoh

Contoh ini menunjukkan penggunaan kelas Font dan SolidBrush untuk menggambar string pada permukaan Image. Contoh ini membuat Image baru dan menggambar bentuk menggunakan Figures dan GraphicsPath

```csharp
[C#]

//Membuat instance dari Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Membuat dan menginisialisasi instance dari kelas Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Membersihkan permukaan Graphics
    graphics.Clear(Color.Wheat);

    //Membuat instance dari Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Membuat instance SolidBrush dengan Warna Merah
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Menggambar String
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // membuat opsi ekspor.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // simpan semua perubahan
    image.Save("C:\\temp\\output.gif", options);
}
```

### Lihat Juga

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek [`Brush`](../../brush/) dan [`Font`](../../font/) menggunakan atribut pemformatan dari [`StringFormat`](../../stringformat/) yang ditentukan.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | String | String untuk digambar. |
| font | Font | [`Font`](../../font/) yang mendefinisikan format teks dari string. |
| brush | Brush | [`Brush`](../../brush/) yang menentukan warna dan tekstur teks yang digambar. |
| x | Single | Koordinat x dari sudut kiri atas teks yang digambar. |
| y | Single | Koordinat y dari sudut kiri atas teks yang digambar. |
| format | StringFormat | [`StringFormat`](../../stringformat/) yang menentukan atribut pemformatan, seperti spasi baris dan perataan, yang diterapkan pada teks yang digambar. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *brush* bernilai null. -atau- *s* bernilai null. |

### Lihat Juga

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Menggambar string teks yang ditentukan pada lokasi yang ditentukan dengan objek [`Brush`](../../brush/) dan [`Font`](../../font/) menggunakan atribut pemformatan dari [`StringFormat`](../../stringformat/) yang ditentukan.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | String | String untuk digambar. |
| font | Font | [`Font`](../../font/) yang mendefinisikan format teks dari string. |
| brush | Brush | [`Brush`](../../brush/) yang menentukan warna dan tekstur teks yang digambar. |
| point | PointF | [`PointF`](../../pointf/) struktur yang menentukan sudut kiri atas teks yang digambar. |
| format | StringFormat | [`StringFormat`](../../stringformat/) yang menentukan atribut pemformatan, seperti spasi baris dan perataan, yang diterapkan pada teks yang digambar. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *brush* bernilai null. -atau- *s* bernilai null. |

### Lihat Juga

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Menggambar string teks yang ditentukan dalam persegi panjang yang ditentukan dengan objek [`Brush`](../../brush/) dan [`Font`](../../font/) yang ditentukan.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | String | String untuk digambar. |
| font | Font | [`Font`](../../font/) yang mendefinisikan format teks dari string. |
| brush | Brush | [`Brush`](../../brush/) yang menentukan warna dan tekstur teks yang digambar. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) struktur yang menentukan lokasi teks yang digambar. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *brush* bernilai null. -atau- *s* bernilai null. |

### Lihat Juga

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Menggambar string teks yang ditentukan dalam persegi panjang yang ditentukan dengan objek [`Brush`](../../brush/) dan [`Font`](../../font/) menggunakan atribut pemformatan dari [`StringFormat`](../../stringformat/) yang ditentukan.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | String | String untuk digambar. |
| font | Font | [`Font`](../../font/) yang mendefinisikan format teks dari string. |
| brush | Brush | [`Brush`](../../brush/) yang menentukan warna dan tekstur teks yang digambar. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) struktur yang menentukan lokasi teks yang digambar. |
| format | StringFormat | [`StringFormat`](../../stringformat/) yang menentukan atribut pemformatan, seperti spasi baris dan perataan, yang diterapkan pada teks yang digambar. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *brush* bernilai null. -atau- *s* bernilai null. -atau- *brush* bernilai null. |

### Lihat Juga

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


