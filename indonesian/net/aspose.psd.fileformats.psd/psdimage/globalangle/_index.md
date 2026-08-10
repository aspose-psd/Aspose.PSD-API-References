---
title: "PsdImage.GlobalAngle"
second_title: "Aspose.PSD untuk Referensi API .NET"
description: "Properti PsdImage. Mendapatkan atau mengatur sudut global"
type: docs
weight: 100
url: /id/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
{{< psd/tize >}}
## PsdImage.GlobalAngle property

Mendapatkan atau mengatur sudut global.

```csharp
public int GlobalAngle { get; set; }
```

## Contoh

Kode berikut menunjukkan dukungan untuk properti PsdImage.GlobalAngle untuk mengubah nilai sudut global.

```csharp
[C#]

// Ketika properti DropShadowEffect.UseGlobalLight bernilai 'true', objek DropShadowEffect menggunakan nilai sudut dari properti PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### Lihat Juga

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


