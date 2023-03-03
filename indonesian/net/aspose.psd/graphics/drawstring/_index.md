---
title: Graphics.DrawString
second_title: Aspose.PSD untuk Referensi .NET API
description: Graphics metode. Menggambar string teks yang ditentukan di lokasi yang ditentukan dengan yang ditentukanBrush DanFont objek.
type: docs
weight: 320
url: /id/net/aspose.psd/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Menggambar string teks yang ditentukan di lokasi yang ditentukan dengan yang ditentukan[`Brush`](../../brush/) Dan[`Font`](../../font/) objek.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| s | String | Tali untuk menggambar. |
| font | Font | [`Font`](../../font/) yang mendefinisikan format teks dari string. |
| brush | Brush | [`Brush`](../../brush/) yang menentukan warna dan tekstur teks yang digambar. |
| x | Single | Koordinat x sudut kiri atas teks yang digambar. |
| y | Single | Koordinat y sudut kiri atas teks yang digambar. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *brush* adalah null. -atau- *s* adalah nol. |

### Lihat juga

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [Graphics](../)
* ruang nama [Aspose.PSD](../../graphics/)
* perakitan [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Menggambar string teks yang ditentukan di lokasi yang ditentukan dengan yang ditentukan[`Brush`](../../brush/) Dan[`Font`](../../font/) objek.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| s | String | Tali untuk menggambar. |
| font | Font | [`Font`](../../font/) yang mendefinisikan format teks dari string. |
| brush | Brush | [`Brush`](../../brush/) yang menentukan warna dan tekstur teks yang digambar. |
| point | PointF | [`PointF`](../../pointf/) struktur yang menentukan sudut kiri atas teks yang digambar. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *brush* adalah null. -atau- *s* adalah nol. |

### Contoh

Contoh ini mendemonstrasikan penggunaan kelas Font dan SolidBrush untuk menggambar string pada permukaan Gambar. Contoh membuat Gambar baru dan menggambar bentuk menggunakan Figures dan GraphicsPath

```csharp
[C#]

// Membuat instance dari Gambar
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Membuat dan menginisialisasi sebuah instance dari kelas Grafik
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    // Membersihkan permukaan Grafik
    graphics.Clear(Color.Wheat);

    //Membuat turunan dari Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Buat instance SolidBrush yang memiliki Warna Merah
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    //Gambar sebuah String
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // buat opsi ekspor.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // simpan semua perubahan
    image.Save("C:\\temp\\output.gif", options);
}
```

### Lihat juga

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [Graphics](../)
* ruang nama [Aspose.PSD](../../graphics/)
* perakitan [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Menggambar string teks yang ditentukan di lokasi yang ditentukan dengan yang ditentukan[`Brush`](../../brush/) Dan[`Font`](../../font/) objek menggunakan atribut pemformatan yang ditentukan[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| s | String | Tali untuk menggambar. |
| font | Font | [`Font`](../../font/) yang mendefinisikan format teks dari string. |
| brush | Brush | [`Brush`](../../brush/) yang menentukan warna dan tekstur teks yang digambar. |
| x | Single | Koordinat x sudut kiri atas teks yang digambar. |
| y | Single | Koordinat y sudut kiri atas teks yang digambar. |
| format | StringFormat | [`StringFormat`](../../stringformat/) yang menentukan atribut pemformatan, seperti penspasian garis dan perataan, yang diterapkan pada teks yang digambar. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *brush* adalah null. -atau- *s* adalah nol. |

### Lihat juga

* class [Font](../../font/)
* class [Brush](../../brush/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* ruang nama [Aspose.PSD](../../graphics/)
* perakitan [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Menggambar string teks yang ditentukan di lokasi yang ditentukan dengan yang ditentukan[`Brush`](../../brush/) Dan[`Font`](../../font/) objek menggunakan atribut pemformatan yang ditentukan[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| s | String | Tali untuk menggambar. |
| font | Font | [`Font`](../../font/) yang mendefinisikan format teks dari string. |
| brush | Brush | [`Brush`](../../brush/) yang menentukan warna dan tekstur teks yang digambar. |
| point | PointF | [`PointF`](../../pointf/) struktur yang menentukan sudut kiri atas teks yang digambar. |
| format | StringFormat | [`StringFormat`](../../stringformat/) yang menentukan atribut pemformatan, seperti penspasian garis dan perataan, yang diterapkan pada teks yang digambar. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *brush* adalah null. -atau- *s* adalah nol. |

### Lihat juga

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [PointF](../../pointf/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* ruang nama [Aspose.PSD](../../graphics/)
* perakitan [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Menggambar string teks yang ditentukan dalam persegi panjang yang ditentukan dengan yang ditentukan[`Brush`](../../brush/) Dan[`Font`](../../font/) objek.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| s | String | Tali untuk menggambar. |
| font | Font | [`Font`](../../font/) yang mendefinisikan format teks dari string. |
| brush | Brush | [`Brush`](../../brush/) yang menentukan warna dan tekstur teks yang digambar. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) struktur yang menentukan lokasi teks yang digambar. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *brush* adalah null. -atau- *s* adalah nol. |

### Lihat juga

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [Graphics](../)
* ruang nama [Aspose.PSD](../../graphics/)
* perakitan [Aspose.PSD](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Menggambar string teks yang ditentukan dalam persegi panjang yang ditentukan dengan yang ditentukan[`Brush`](../../brush/) Dan[`Font`](../../font/) objek menggunakan atribut pemformatan yang ditentukan[`StringFormat`](../../stringformat/) .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| s | String | Tali untuk menggambar. |
| font | Font | [`Font`](../../font/) yang mendefinisikan format teks dari string. |
| brush | Brush | [`Brush`](../../brush/) yang menentukan warna dan tekstur teks yang digambar. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef/) struktur yang menentukan lokasi teks yang digambar. |
| format | StringFormat | [`StringFormat`](../../stringformat/) yang menentukan atribut pemformatan, seperti penspasian garis dan perataan, yang diterapkan pada teks yang digambar. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *brush* adalah null. -atau- *s* adalah null. -atau- *brush* adalah nol. |

### Lihat juga

* class [Font](../../font/)
* class [Brush](../../brush/)
* struct [RectangleF](../../rectanglef/)
* class [StringFormat](../../stringformat/)
* class [Graphics](../)
* ruang nama [Aspose.PSD](../../graphics/)
* perakitan [Aspose.PSD](../../../)


