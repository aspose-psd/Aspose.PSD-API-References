---
title: Image.RotateFlip
second_title: Aspose.PSD voor .NET API-referentie
description: Image methode. Roteert spiegelt of roteert en spiegelt de afbeelding.
type: docs
weight: 220
url: /nl/net/aspose.psd/image/rotateflip/
---
## Image.RotateFlip method

Roteert, spiegelt of roteert en spiegelt de afbeelding.

```csharp
public abstract void RotateFlip(RotateFlipType rotateFlipType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| rotateFlipType | RotateFlipType | Type van de geroteerde flip. |

### Voorbeelden

Dit voorbeeld demonstreert het gebruik van de bewerking Roteren op een afbeelding. Voorbeeld laadt een bestaand afbeeldingsbestand vanaf een bepaalde schijflocatie en voert de bewerking Roteren uit op de afbeelding volgens de waarde van Enum Aspose.PSD.RotateFlipType

```csharp
[C#]

// Maak een instantie van de afbeeldingsklasse en initialiseer deze met een bestaand afbeeldingsbestand via Bestandspad
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    // Draai de afbeelding 180 graden rond de X-as
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    // sla alle veranderingen op.
    image.Save();
}
```

### Zie ook

* enum [RotateFlipType](../../rotatefliptype/)
* class [Image](../)
* naamruimte [Aspose.PSD](../../image/)
* montage [Aspose.PSD](../../../)


