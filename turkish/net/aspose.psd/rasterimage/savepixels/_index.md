---
title: RasterImage.SavePixels
second_title: Aspose.PSD for .NET API Referansı
description: RasterImage yöntem. Pikselleri kaydeder.
type: docs
weight: 520
url: /tr/net/aspose.psd/rasterimage/savepixels/
---
## RasterImage.SavePixels method

Pikselleri kaydeder.

```csharp
public void SavePixels(Rectangle rectangle, Color[] pixels)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rectangle | Rectangle | Piksellerin kaydedileceği dikdörtgen. |
| pixels | Color[] | Piksel dizisi. |

### Örnekler

Bu örnek, Piksel bilgilerinin bir Renk Türü Dizisinde nasıl Yükleneceğini, diziyi nasıl değiştireceğini ve tekrar görüntüye nasıl ayarlayacağını gösterir. Bu işlemleri gerçekleştirmek için bu örnek, MemoryStream nesnesini kullanarak yeni bir Görüntü dosyası (PSD formatında) oluşturur.

```csharp
[C#]

// Bir MemoryStream örneği oluştur
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Bir PsdOptions örneği oluşturun ve Source özelliği dahil olmak üzere çeşitli özelliklerini ayarlayın
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //Görüntünün bir örneğini oluştur
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //Görüntü sınırı olarak alanı belirleyerek görüntünün piksellerini alın
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //Dizi üzerinde döngü yapın ve alternatif dizinlenmiş pikselin rengini ayarlar
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Dizinlenen piksel rengini sarı olarak ayarla
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //Dizinlenmiş piksel rengini mavi olarak ayarla
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        // Piksel değişikliklerini görüntüye uygula
        image.SavePixels(image.Bounds, pixels);

        // tüm değişiklikleri kaydet.
        image.Save();
    }

    //MemoryStream'i Dosyaya Yaz
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

### Ayrıca bakınız

* struct [Rectangle](../../rectangle/)
* struct [Color](../../color/)
* class [RasterImage](../)
* ad alanı [Aspose.PSD](../../rasterimage/)
* toplantı [Aspose.PSD](../../../)


