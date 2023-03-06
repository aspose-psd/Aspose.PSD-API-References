---
title: PsdImage.GlobalAngle
second_title: Aspose.PSD för .NET API-referens
description: PsdImage fast egendom. Hämtar eller ställer in den globala vinkeln.
type: docs
weight: 100
url: /sv/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
## PsdImage.GlobalAngle property

Hämtar eller ställer in den globala vinkeln.

```csharp
public int GlobalAngle { get; set; }
```

### Exempel

Följande kod visar stöd för egenskapen PsdImage.GlobalAngle för att ändra det globala vinkelvärdet.

```csharp
[C#]

// När egenskapen DropShadowEffect.UseGlobalLight är 'true' använder DropShadowEffect-objektet vinkelvärdet från egenskapen PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### Se även

* class [PsdImage](../)
* namnutrymme [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* hopsättning [Aspose.PSD](../../../)


