---
title: "Image.Create"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Image metodu. Belirtilen oluşturma seçeneklerini kullanarak yeni bir görüntü oluşturur"
type: docs
weight: 10
url: /tr/net/aspose.psd/image/create/
---
{{< psd/tize >}}
## Image.Create method

Belirtilen oluşturma seçeneklerini kullanarak yeni bir görüntü oluşturur.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | Görüntü seçenekleri. |
| width | Int32 | Genişlik. |
| height | Int32 | Yükseklik. |

### Dönüş Değeri

Yeni oluşturulan görüntü.

## Örnekler

Bu örnek, PsdOptions örneğinin Source özelliğiyle belirtilen bir disk konumunda yeni bir Image dosyası oluşturur. Gerçek görüntüyü oluşturmadan önce PsdOptions örneği için birkaç özellik ayarlanır. Özellikle bu durumda gerçek disk konumunu belirten Source özelliği.

```csharp
[C#]

//PsdOptions bir örneği oluşturun ve çeşitli özelliklerini ayarlayın.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//FileCreateSource bir örneği oluşturun ve bunu PsdOptions örneği için Source olarak atayın.
//İkinci Boolean parametre, oluşturulacak dosyanın geçici (IsTemporal) olup olmadığını belirler.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Image bir örneği oluşturun ve Create metodunu çağırarak PsdOptions örneğiyle başlatın.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //biraz görüntü işleme yap

    // tüm değişiklikleri kaydet
    image.Save();
}
```

### Ayrıca Bakınız

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


