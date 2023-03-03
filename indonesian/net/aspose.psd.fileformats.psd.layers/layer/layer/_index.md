---
title: Layer.Layer
second_title: Aspose.PSD untuk Referensi .NET API
description: Layer konstruktor. Menginisialisasi instance baru dariLayer kelas. Konstruktor untuk inisialisasi lambat.
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
## Layer() {#constructor}

Menginisialisasi instance baru dari[`Layer`](../) kelas. Konstruktor untuk inisialisasi lambat.

```csharp
public Layer()
```

### Contoh

Contoh berikut menunjukkan bagaimana Anda bisa menggambar pada lapisan yang baru dibuat jika versi konstruktor sederhana digunakan di Aspose.PSD

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // menggambar persegi panjang dengan Pen tool
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // menggambar persegi panjang lain dengan Kuas Padat dalam warna Biru
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Lihat juga

* class [Layer](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* perakitan [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

Menginisialisasi instance baru dari[`Layer`](../) kelas.

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| image | RasterImage | Foto. |
| disposeImage | Boolean | jika diatur ke`BENAR` [membuang gambar]. |

### Contoh

Kode berikut menunjukkan kemampuan untuk memuat file gambar JPEG/PNG/dll ke PsdImage tanpa memuat langsung.

```csharp
[C#]

string filePath = "PsdExample.psd";
string outputFilePath = "PsdResult.psd";
using (var image = new PsdImage(200, 200))
{
    using (var im = Image.Load(filePath))
    {
        Layer layer = null;
        try
        {
            layer = new Layer((RasterImage)im);
            image.AddLayer(layer);
        }
        catch (Exception)
        {
            if (layer != null)
            {
                layer.Dispose();
            }

            throw;
        }
    }

    image.Save(outputFilePath);
}
```

### Lihat juga

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* perakitan [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

Menginisialisasi instance baru dari[`Layer`](../) kelas.

```csharp
public Layer(Stream stream)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| stream | Stream | Aliran gambar |

### Contoh

Contoh berikut menunjukkan bagaimana Anda dapat menambahkan gambar Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif sebagai layer ke PsdImage

```csharp
[C#]

string outputFilePath = "PsdResult.psd";

var filesList = new string[]
{
    "PsdExample.psd",
    "BmpExample.bmp",
    "GifExample.gif",
    "Jpeg2000Example.jpf",
    "JpegExample.jpg",
    "PngExample.png",
    "TiffExample.tif",
};

using (var image = new PsdImage(200, 200))
{
    foreach (var fileName in filesList)
    {
        string filePath = fileName;
        using (var stream = new FileStream(filePath, FileMode.Open))
        {
            Layer layer = null;
            try
            {
                layer = new Layer(stream);
                image.AddLayer(layer);
            }
            catch (Exception e)
            {
                if (layer != null)
                {
                    layer.Dispose();
                }

                throw e;
            }
        }
    }

    image.Save(outputFilePath);
}
```

### Lihat juga

* class [Layer](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* perakitan [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

Menginisialisasi instance baru dari[`Layer`](../) kelas dari array byte.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| Parameter | Jenis | Keterangan |
| --- | --- | --- |
| bounds | Rectangle | Batas lapisan. |
| redBytes | Byte[] | Byte merah. |
| greenBytes | Byte[] | Byte hijau. |
| blueBytes | Byte[] | Byte biru. |
| name | String | Nama lapisan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Array byte tidak boleh kosong atau Panjang array byte harus sama dengan dimensi batas (bounds.Width * bounds.Height) |

### Lihat juga

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* ruang nama [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* perakitan [Aspose.PSD](../../../)


