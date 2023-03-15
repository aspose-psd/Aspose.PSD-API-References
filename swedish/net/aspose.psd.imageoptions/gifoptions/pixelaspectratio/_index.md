---
title: GifOptions.PixelAspectRatio
second_title: Aspose.PSD för .NET API-referens
description: GifOptions fast egendom. Hämtar eller ställer in GIFpixelns bildförhållande.
type: docs
weight: 90
url: /sv/net/aspose.psd.imageoptions/gifoptions/pixelaspectratio/
---
## GifOptions.PixelAspectRatio property

Hämtar eller ställer in GIF-pixelns bildförhållande.

```csharp
public byte PixelAspectRatio { get; set; }
```

### Fastighetsvärde

GIF-pixelns bildförhållande.

### Anmärkningar

Pixel Aspect Ratio - Faktor som används för att beräkna en approximation av bildförhållandet för pixeln i originalbilden. Om -värdet för fältet inte är 0, beräknas denna approximation av bildförhållandet baserat på formeln: Bildförhållande = (Pixelbildförhållande + 15) / 64 Pixelbildförhållandet definieras som kvoten av pixel s bredd över dess höjd. Värdeintervallet i det här fältet tillåter specifikation av den bredaste pixeln på 4:1 till den högsta pixeln på 1:4 i steg om 1/64:e. Värden : 0 - Ingen information om bildförhållande ges. 1 Värde som används i beräkningen.

### Se även

* class [GifOptions](../)
* namnutrymme [Aspose.PSD.ImageOptions](../../gifoptions/)
* hopsättning [Aspose.PSD](../../../)


