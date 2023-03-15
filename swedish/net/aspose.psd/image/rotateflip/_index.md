---
title: Image.RotateFlip
second_title: Aspose.PSD för .NET API-referens
description: Image metod. Roterar vänder eller roterar och vänder bilden.
type: docs
weight: 220
url: /sv/net/aspose.psd/image/rotateflip/
---
## Image.RotateFlip method

Roterar, vänder eller roterar och vänder bilden.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Typ av roterande flip. |

### Exempel

Det här exemplet visar användningen av Rotate-operationen på en bild. Exempel laddar en befintlig bildfil från någon diskplats och utför Rotate-operationen på bilden enligt värdet på Enum Aspose.PSD.RotateFlipType

```csharp
[C#]

//Skapa en instans av bildklass och initiera den med en befintlig bildfil via filsökväg
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
* namnutrymme [Aspose.PSD](../../image/)
* hopsättning [Aspose.PSD](../../../)


