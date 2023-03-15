---
title: Layer.Layer
second_title: Aspose.PSD for .NET API Referansı
description: Layer inşaatçı. Yeni bir örneğini başlatır.Layer sınıf. Geç başlatma için yapıcı.
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
## Layer() {#constructor}

Yeni bir örneğini başlatır.[`Layer`](../) sınıf. Geç başlatma için yapıcı.

```csharp
public Layer()
```

### Örnekler

Aşağıdaki örnek, Aspose.PSD'de basit kurucu sürümü kullanılıyorsa yeni oluşturulmuş bir katman üzerinde nasıl çizim yapabileceğinizi gösterir.

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

    // Kalem aracıyla bir dikdörtgen çizin
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // Düz Fırça ile Mavi renkte başka bir dikdörtgen çizin
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Ayrıca bakınız

* class [Layer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* toplantı [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

Yeni bir örneğini başlatır.[`Layer`](../) sınıf.

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| image | RasterImage | Görüntü. |
| disposeImage | Boolean | olarak ayarlanmışsa`doğru` [resmi atın]. |

### Örnekler

Aşağıdaki kod, JPEG/PNG/etc resim dosyalarını doğrudan yüklemeden PsdImage'a yükleme yeteneğini gösterir.

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

### Ayrıca bakınız

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* toplantı [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

Yeni bir örneğini başlatır.[`Layer`](../) sınıf.

```csharp
public Layer(Stream stream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | görüntü akışı |

### Örnekler

Aşağıdaki örnek, Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif resimlerini PsdImage'a nasıl katman olarak ekleyebileceğinizi göstermektedir.

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

### Ayrıca bakınız

* class [Layer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* toplantı [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

Yeni bir örneğini başlatır.[`Layer`](../) bayt dizilerinden sınıf.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| bounds | Rectangle | Katman sınırları. |
| redBytes | Byte[] | Kırmızı baytlar. |
| greenBytes | Byte[] | Yeşil baytlar. |
| blueBytes | Byte[] | mavi bayt. |
| name | String | Katman adı. |

### istisnalar

| istisna | şart |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Bayt dizileri boş olamaz veya Bayt dizilerinin uzunluğu sınır boyutlarına eşit olmalıdır (sınır.Genişlik * sınırlar.Yükseklik) |

### Ayrıca bakınız

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* ad alanı [Aspose.PSD.FileFormats.Psd.Layers](../../layer/)
* toplantı [Aspose.PSD](../../../)


