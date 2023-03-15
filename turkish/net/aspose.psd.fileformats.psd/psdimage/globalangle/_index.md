---
title: PsdImage.GlobalAngle
second_title: Aspose.PSD for .NET API Referansı
description: PsdImage mülk. Genel açıyı alır veya ayarlar.
type: docs
weight: 100
url: /tr/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
## PsdImage.GlobalAngle property

Genel açıyı alır veya ayarlar.

```csharp
public int GlobalAngle { get; set; }
```

### Örnekler

Aşağıdaki kod, genel açı değerini değiştirmek için PsdImage.GlobalAngle özelliğine yönelik desteği gösterir.

```csharp
[C#]

// DropShadowEffect.UseGlobalLight özelliği 'true' olduğunda, DropShadowEffect nesnesi PsdImage.GlobalAngle özelliğinden açı değeri kullanır.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### Ayrıca bakınız

* class [PsdImage](../)
* ad alanı [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* toplantı [Aspose.PSD](../../../)


