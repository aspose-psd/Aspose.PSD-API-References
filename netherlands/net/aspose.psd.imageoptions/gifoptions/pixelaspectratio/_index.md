---
title: GifOptions.PixelAspectRatio
second_title: Aspose.PSD voor .NET API-referentie
description: GifOptions eigendom. Haalt de beeldverhouding van de GIFpixel op of stelt deze in.
type: docs
weight: 90
url: /nl/net/aspose.psd.imageoptions/gifoptions/pixelaspectratio/
---
## GifOptions.PixelAspectRatio property

Haalt de beeldverhouding van de GIF-pixel op of stelt deze in.

```csharp
public byte PixelAspectRatio { get; set; }
```

### Eigendoms-waarde

De beeldverhouding van de GIF-pixel.

### Opmerkingen

Pixel-beeldverhouding - Factor die wordt gebruikt om een benadering van de beeldverhouding van de pixel in de originele afbeelding te berekenen. Als de waarde van het veld niet 0 is, wordt deze benadering van de aspectverhouding berekend op basis van de formule: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 De Pixel Aspect Ratio wordt gedefinieerd als het quotiënt van de pixel' s breedte over zijn hoogte. Het waardebereik in dit veld staat specificatie toe van de breedste pixel van 4:1 tot de hoogste pixel van 1:4 in stappen van 1/64ste. Waarden : 0 - Er wordt geen informatie over de beeldverhouding gegeven. 1..255 - Waarde gebruikt in de berekening.

### Zie ook

* class [GifOptions](../)
* naamruimte [Aspose.PSD.ImageOptions](../../gifoptions/)
* montage [Aspose.PSD](../../../)


