---
title: PsdImage.GlobalAngle
second_title: Aspose.PSD untuk Referensi .NET API
description: PsdImage Properti. Mendapat atau mengatur sudut global.
type: docs
weight: 100
url: /id/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
## PsdImage.GlobalAngle property

Mendapat atau mengatur sudut global.

```csharp
public int GlobalAngle { get; set; }
```

### Contoh

Kode berikut menunjukkan dukungan untuk properti PsdImage.GlobalAngle untuk mengubah nilai sudut global.

```csharp
[C#]

// Ketika properti DropShadowEffect.UseGlobalLight 'benar', maka objek DropShadowEffect menggunakan nilai sudut dari properti PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### Lihat juga

* class [PsdImage](../)
* ruang nama [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* perakitan [Aspose.PSD](../../../)


