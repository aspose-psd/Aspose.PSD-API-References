---
title: StreamSource.StreamSource
second_title: Aspose.PSD for .NET API Referansı
description: StreamSource inşaatçı. Yeni bir örneğini başlatır.StreamSource sınıf.
type: docs
weight: 10
url: /tr/net/aspose.psd.sources/streamsource/streamsource/
---
## StreamSource(Stream) {#constructor}

Yeni bir örneğini başlatır.[`StreamSource`](../) sınıf.

```csharp
public StreamSource(Stream stream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Açılacak akış. |

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

* class [StreamSource](../)
* ad alanı [Aspose.PSD.Sources](../../streamsource/)
* toplantı [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

Yeni bir örneğini başlatır.[`StreamSource`](../) sınıf.

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| stream | Stream | Açılacak akış. |
| disposeStream | Boolean | olarak ayarlanmışsa`doğru` akım bertaraf edilecektir. |

### Örnekler

Bu örnek, yeni bir Görüntü dosyası oluşturmak için System.IO.Stream'in kullanımını gösterir.

```csharp
[C#]

//PsdOptions'ın bir örneğini oluşturur ve çeşitli özelliklerini ayarlar
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//System.IO.Stream'in bir örneğini oluşturun
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//PsdOptions örneği için kaynak özelliğini tanımlayın
//İkinci boolean parametresi, Akışın kapsam dışına çıktıktan sonra atılıp atılmayacağını belirler
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Bir Image örneği oluşturur ve Image nesnesini başlatmak için parametre olarak PsdOptions ile Create yöntemini çağırır   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // biraz görüntü işleme yapalım
}
```

### Ayrıca bakınız

* class [StreamSource](../)
* ad alanı [Aspose.PSD.Sources](../../streamsource/)
* toplantı [Aspose.PSD](../../../)


