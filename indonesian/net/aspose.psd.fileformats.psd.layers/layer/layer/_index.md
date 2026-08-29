---
title: "Layer.Layer"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Konstruktor Layer. Menginisialisasi sebuah instance baru dari kelas Layer. Konstruktor untuk inisialisasi malas"
type: docs
weight: 10
url: /id/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
{{< psd/tize >}}
## Layer() {#constructor}

Menginisialisasi sebuah instance baru dari kelas [`Layer`](../). Konstruktor untuk inisialisasi malas.

```csharp
public Layer()
```

## Contoh

Contoh berikut menunjukkan cara Anda dapat menggambar pada lapisan yang baru dibuat jika versi konstruktor sederhana digunakan dalam Aspose.PSD

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

    // gambar sebuah persegi panjang dengan alat Pen
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // gambar persegi panjang lain dengan Kuas Solid berwarna Biru
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Lihat Juga

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

Menginisialisasi sebuah instance baru dari kelas [`Layer`](../).

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| gambar | RasterImage | Gambar. |
| disposeImage | Boolean | jika diatur ke `true` [dispose image]. |

## Contoh

Kode berikut menunjukkan kemampuan memuat file gambar JPEG/PNG/dll ke PsdImage tanpa pemuatan langsung.

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

### Lihat Juga

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

Menginisialisasi sebuah instance baru dari kelas [`Layer`](../).

```csharp
public Layer(Stream stream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Aliran gambar |

## Contoh

Contoh berikut menunjukkan cara Anda dapat menambahkan gambar Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif sebagai lapisan ke PsdImage

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

### Lihat Juga

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

Menginisialisasi instance baru dari kelas [`Layer`](../) dari array byte.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| batas | Rectangle | Batas lapisan. |
| redBytes | Byte[] | Byte merah. |
| greenBytes | Byte[] | Byte hijau. |
| blueBytes | Byte[] | Byte biru. |
| name | String | Nama lapisan. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Array byte tidak boleh kosong atau panjang array byte harus sama dengan dimensi batas (bounds.Width * bounds.Height). |

### Lihat Juga

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


