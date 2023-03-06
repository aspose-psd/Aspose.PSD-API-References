---
title: PsdImage.GlobalAngle
second_title: Aspose.PSD voor .NET API-referentie
description: PsdImage eigendom. Haalt of stelt de globale hoek in.
type: docs
weight: 100
url: /nl/net/aspose.psd.fileformats.psd/psdimage/globalangle/
---
## PsdImage.GlobalAngle property

Haalt of stelt de globale hoek in.

```csharp
public int GlobalAngle { get; set; }
```

### Voorbeelden

De volgende code demonstreert ondersteuning voor de eigenschap PsdImage.GlobalAngle om de globale hoekwaarde te wijzigen.

```csharp
[C#]

// Als de eigenschap DropShadowEffect.UseGlobalLight 'true' is, gebruikt het object DropShadowEffect de hoekwaarde van de eigenschap PsdImage.GlobalAngle.

using (PsdImage image = (PsdImage)Image.Load("4.psd"))
{
    image.GlobalAngle = 30;
    image.Save("output.psd");
}
```

### Zie ook

* class [PsdImage](../)
* naamruimte [Aspose.PSD.FileFormats.Psd](../../psdimage/)
* montage [Aspose.PSD](../../../)


