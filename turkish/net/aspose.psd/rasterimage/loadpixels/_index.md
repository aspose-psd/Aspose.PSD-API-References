---
title: "RasterImage.LoadPixels"
second_title: "Aspose.PSD for .NET API Referansı"
description: "RasterImage yöntemi. Pikselleri yükler."
type: docs
weight: 410
url: /tr/net/aspose.psd/rasterimage/loadpixels/
---
{{< psd/tize >}}
## RasterImage.LoadPixels method

Pikselleri yükler.

```csharp
public Color[] LoadPixels(Rectangle rectangle)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dikdörtgen | Rectangle | Piksellerin yükleneceği dikdörtgen. |

### Dönüş Değeri

Yüklenen piksel dizisi.

## Örnekler

Bu örnek, Pixel bilgilerini Color tipinde bir diziye nasıl yükleneceğini, diziyi nasıl manipüle edeceğini ve tekrar görüntüye nasıl ayarlayacağını gösterir. Bu işlemleri gerçekleştirmek için örnek, MemoryStream nesnesi kullanarak yeni bir Image dosyası (PSD formatında) oluşturur.

```csharp
[C#]

//MemoryStream bir örneği oluşturun.
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //PsdOptions bir örneği oluşturun ve Source özelliği dahil olmak üzere çeşitli özelliklerini ayarlayın.
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Image bir örneği oluşturun.
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Görüntünün piksellerini, alanı görüntü sınırı olarak belirterek alın
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Diziyi döngüye al ve alternatif indeksli pikselin rengini ayarlar
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //İndeksli pikselin rengini sarıya ayarla
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //İndeksli pikselin rengini maviye ayarla
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //Piksel değişikliklerini görüntüye uygula
        image.SavePixels(image.Bounds, pixels);

        // tüm değişiklikleri kaydet.
        image.Save();
    }

    //MemoryStream'i dosyaya yaz
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Ayrıca Bakınız

* struct [Color](../../color/)
* struct [Rectangle](../../rectangle/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


