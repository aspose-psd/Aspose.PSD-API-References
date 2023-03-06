---
title: Image.Create
second_title: Aspose.PSD for .NET API Referansı
description: Image yöntem. Belirtilen oluşturma seçeneklerini kullanarak yeni bir görüntü oluşturur.
type: docs
weight: 10
url: /tr/net/aspose.psd/image/create/
---
## Image.Create method

Belirtilen oluşturma seçeneklerini kullanarak yeni bir görüntü oluşturur.

```csharp
public static Image Create(ImageOptionsBase imageOptions, int width, int height)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| imageOptions | ImageOptionsBase | Görüntü seçenekleri. |
| width | Int32 | Genişlik. |
| height | Int32 | Yükseklik. |

### Geri dönüş değeri

Yeni oluşturulan görüntü.

### Örnekler

Bu örnek, PsdOptions örneğinin Source özelliği tarafından belirtildiği gibi bazı disk konumlarında yeni bir Görüntü dosyası oluşturur. Gerçek görüntüyü oluşturmadan önce PsdOptions örneği için çeşitli özellikler ayarlanır. Özellikle bu durumda gerçek disk konumuna atıfta bulunan Source özelliği.

```csharp
[C#]

//PsdOptions'ın bir örneğini oluşturun ve çeşitli özelliklerini ayarlayın
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Bir FileCreateSource örneği oluşturun ve bunu PsdOptions örneği için Kaynak olarak atayın
//İkinci Boolean parametresi oluşturulacak dosyanın IsTemporal olup olmadığını belirler.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Bir Image örneği oluşturun ve Create yöntemini çağırarak onu PsdOptions örneğiyle başlatın
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // biraz görüntü işleme yapalım

    // tüm değişiklikleri kaydet
    image.Save();
}
```

### Ayrıca bakınız

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* ad alanı [Aspose.PSD](../../image/)
* toplantı [Aspose.PSD](../../../)


