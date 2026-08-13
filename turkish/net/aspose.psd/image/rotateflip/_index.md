---
title: "Image.RotateFlip"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Image yöntemi. Görüntüyü döndürür, çevirir veya döndürüp çevirir."
type: docs
weight: 230
url: /tr/net/aspose.psd/image/rotateflip/
---
{{< psd/tize >}}
## Image.RotateFlip method

Görüntüyü döndürür, çevirir veya döndürüp çevirir.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Döndürme çevirme türü. |

## Örnekler

Bu örnek, bir görüntü üzerinde Döndürme işleminin kullanımını gösterir. Örnek, bir disk konumundan mevcut bir görüntü dosyasını yükler ve görüntüyü Aspose.PSD.RotateFlipType enum değerine göre Döndürme işlemini uygular.

```csharp
[C#]

//Image sınıfının bir örneğini oluşturun ve dosya yolu aracılığıyla mevcut bir görüntü dosyasıyla başlatın.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Görüntüyü X ekseni etrafında 180 derece döndürün.
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // tüm değişiklikleri kaydet.
    image.Save();
}
```

### Ayrıca Bakınız

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


