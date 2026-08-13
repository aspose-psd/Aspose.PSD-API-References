---
title: "StreamSource.StreamSource"
second_title: "Aspose.PSD for .NET API Referansı"
description: "StreamSource yapıcı. StreamSource sınıfının yeni bir örneğini başlatır"
type: docs
weight: 10
url: /tr/net/aspose.psd.sources/streamsource/streamsource/
---
{{< psd/tize >}}
## StreamSource(Stream) {#constructor}

[`StreamSource`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public StreamSource(Stream stream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Açılacak akış. |

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

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## StreamSource(Stream, bool) {#constructor_1}

[`StreamSource`](../) sınıfının yeni bir örneğini başlatır.

```csharp
public StreamSource(Stream stream, bool disposeStream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | Stream | Açılacak akış. |
| disposeStream | Boolean | `true` olarak ayarlanırsa akış serbest bırakılacak. |

## Örnekler

Bu örnek, System.IO.Stream kullanarak yeni bir Image dosyası oluşturmayı gösterir.

```csharp
[C#]

//PsdOptions bir örnek oluşturur ve çeşitli özelliklerini ayarlar.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//System.IO.Stream bir örnek oluştur.
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//PsdOptions örneği için source özelliğini tanımla.
//İkinci boolean parametre, Stream'in kapsam dışına çıktığında serbest bırakılıp bırakılmayacağını belirler.
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Image bir örnek oluşturur ve Image nesnesini başlatmak için PsdOptions parametresiyle Create metodunu çağırır.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //biraz görüntü işleme yap
}
```

### Ayrıca Bakınız

* class [StreamSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


