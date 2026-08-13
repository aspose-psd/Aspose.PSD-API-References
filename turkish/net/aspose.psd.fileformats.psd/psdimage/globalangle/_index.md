---
title: "PsdImage.GlobalAngle"
second_title: "Aspose.PSD for .NET API Referansı"
description: "PsdImage özelliği. Global açıyı alır veya ayarlar"
type: docs
weight: 100
url: /tr/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
{{< psd/tize >}}
## PsdImage.GlobalAngle property

Global açıyı alır veya ayarlar.

```csharp
public int GlobalAngle { get; set; }
```

## Örnekler

Aşağıdaki kod, global açı değerini değiştirmek için PsdImage.GlobalAngle özelliğinin desteğini gösterir.

```csharp
[C#]

// DropShadowEffect.UseGlobalLight özelliği 'true' olduğunda, DropShadowEffect nesnesi açı değerini PsdImage.GlobalAngle özelliğinden kullanır.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### Ayrıca Bakınız

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


