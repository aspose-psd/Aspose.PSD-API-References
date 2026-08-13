---
title: "Layer.Layer"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Layer yapıcı. Layer sınıfının yeni bir örneğini başlatır. Tembel başlatma için yapıcı"
type: docs
weight: 10
url: /tr/net/aspose.psd.fileformats.psd.layers/layer/layer/
---
{{< psd/tize >}}
## Layer() {#constructor}

[`Layer`](../) sınıfının yeni bir örneğini başlatır. Tembel başlatma için yapıcı.

```csharp
public Layer()
```

## Örnekler

Aşağıdaki örnek, Aspose.PSD içinde basit yapıcı sürümü kullanılırsa yeni oluşturulan bir katmanda nasıl çizebileceğinizi gösterir.

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

    // Pen aracıyla bir dikdörtgen çizin
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // Mavi renkte Solid Brush ile başka bir dikdörtgen çizin
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

### Ayrıca Bakınız

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(RasterImage, bool) {#constructor_1}

[`Layer`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public Layer(RasterImage image, bool disposeImage = false)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| görüntü | RasterImage | Görüntü. |
| disposeImage | Boolean | `true` olarak ayarlanırsa [dispose image]. |

## Örnekler

Aşağıdaki kod, JPEG/PNG/etc görüntü dosyalarını doğrudan yüklemeden PsdImage'e yükleme yeteneğini gösterir.

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

### Ayrıca Bakınız

* class [RasterImage](../../../aspose.psd/rasterimage/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Stream) {#constructor_3}

[`Layer`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public Layer(Stream stream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Görüntü akışı |

## Örnekler

Aşağıdaki örnek, Bmp, Jpeg, Jpeg2000, Png, Psd, Tiff, Gif görüntülerini PsdImage'e katman olarak nasıl ekleyebileceğinizi gösterir.

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

### Ayrıca Bakınız

* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)

---

## Layer(Rectangle, byte[], byte[], byte[], string) {#constructor_2}

[`Layer`](../) sınıfının yeni bir örneğini bayt dizilerinden başlatır.

```csharp
public Layer(Rectangle bounds, byte[] redBytes, byte[] greenBytes, byte[] blueBytes, string name)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bounds | Rectangle | Katmanın sınırları. |
| redBytes | Byte[] | Kırmızı baytlar. |
| greenBytes | Byte[] | Yeşil baytlar. |
| blueBytes | Byte[] | Mavi baytlar. |
| name | String | Katman adı. |

### İstisnalar

| istisna | koşul |
| --- | --- |
| [PsdImageException](../../../aspose.psd.coreexceptions.imageformats/psdimageexception/) | Bayt dizileri boş olamaz veya bayt dizileri uzunluğu sınırların boyutlarına (bounds.Width * bounds.Height) eşit olmalıdır. |

### Ayrıca Bakınız

* struct [Rectangle](../../../aspose.psd/rectangle/)
* class [Layer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


