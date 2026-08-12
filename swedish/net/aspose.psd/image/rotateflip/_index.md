---
title: "Image.RotateFlip"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Image-metod. Roterar, vänder eller roterar och vänder bilden"
type: docs
weight: 230
url: /sv/net/aspose.psd/image/rotateflip/
---
{{< psd/tize >}}
## Image.RotateFlip method

Rotera, vänd eller rotera och vänd bilden.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Typ av rotate flip. |

## Exempel

Detta exempel demonstrerar användning av Rotate-operationen på en bild. Exemplet laddar en befintlig bildfil från en viss diskplats och utför Rotate-operationen på bilden enligt värdet i enum Aspose.PSD.RotateFlipType

```csharp
[C#]

//Skapa en instans av image-klassen och initiera den med en befintlig bildfil via filväg
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //Rotera bilden 180 grader runt X-axeln
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // spara alla ändringar.
    image.Save();
}
```

### Se även

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


