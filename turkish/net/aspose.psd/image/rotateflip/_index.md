---
title: Image.RotateFlip
second_title: Aspose.PSD for .NET API Referansı
description: Image yöntem. Görüntüyü döndürür çevirir veya döndürür ve çevirir.
type: docs
weight: 220
url: /tr/net/aspose.psd/image/rotateflip/
---
## Image.RotateFlip method

Görüntüyü döndürür, çevirir veya döndürür ve çevirir.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Döndürme çevirme türü. |

### Örnekler

Bu örnek, bir görüntü üzerinde Döndürme işleminin kullanımını gösterir. Örnek, bazı disk konumlarından mevcut bir görüntü dosyasını yükler ve Enum Aspose.PSD.RotateFlipType değerine göre görüntü üzerinde Döndürme işlemini gerçekleştirir

```csharp
[C#]

//image sınıfının bir örneğini oluşturun ve onu File path yoluyla mevcut bir image dosyasıyla başlatın
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Görüntüyü X ekseni etrafında 180 derece döndürün
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // tüm değişiklikleri kaydet.
    image.Save();
}
```

### Ayrıca bakınız

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* ad alanı [Aspose.PSD](../../image/)
* toplantı [Aspose.PSD](../../../)


