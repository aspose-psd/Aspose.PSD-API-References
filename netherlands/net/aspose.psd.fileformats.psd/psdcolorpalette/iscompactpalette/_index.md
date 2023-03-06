---
title: PsdColorPalette.IsCompactPalette
second_title: Aspose.PSD voor .NET API-referentie
description: PsdColorPalette eigendom. Krijgt een waarde die aangeeft of het palet is gecomprimeerd.
type: docs
weight: 70
url: /nl/net/aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/
---
## PsdColorPalette.IsCompactPalette property

Krijgt een waarde die aangeeft of het palet is gecomprimeerd.

```csharp
public bool IsCompactPalette { get; }
```

### Eigendoms-waarde

`WAAR` indien compact het palet; anders,`vals`.

### Opmerkingen

Compact palet betekent dat de afbeelding indien mogelijk alleen de gespecificeerde paletitems bevat of met andere woorden, de afbeelding zal compacter zijn en minder ruimte innemen; anders zijn er 2^BitsPerPixel-items en zal de afbeelding meer ruimte reserveren voor alle mogelijke paletitems . Als u deze waarde instelt op 'true' en paletitems wijzigt, kan dit prestatieverlies veroorzaken, aangezien gegevens kunnen worden verplaatst, dus wees voorzichtig.

### Zie ook

* class [PsdColorPalette](../)
* naamruimte [Aspose.PSD.FileFormats.Psd](../../psdcolorpalette/)
* montage [Aspose.PSD](../../../)


