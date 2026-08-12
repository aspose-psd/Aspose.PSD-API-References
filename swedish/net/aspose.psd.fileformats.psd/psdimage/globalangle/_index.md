---
title: "PsdImage.GlobalAngle"
second_title: "Aspose.PSD för .NET API‑referens"
description: "PsdImage egenskap. Hämtar eller anger den globala vinkeln."
type: docs
weight: 100
url: /sv/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
{{< psd/tize >}}
## PsdImage.GlobalAngle property

Hämtar eller anger den globala vinkeln.

```csharp
public int GlobalAngle { get; set; }
```

## Exempel

Följande kod demonstrerar stöd för PsdImage.GlobalAngle-egenskapen för att ändra det globala vinkelvärdet.

```csharp
[C#]

// När DropShadowEffect.UseGlobalLight-egenskapen är 'true' använder DropShadowEffect-objektet vinkelvärdet från PsdImage.GlobalAngle-egenskapen.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### Se även

* class [PsdImage](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


