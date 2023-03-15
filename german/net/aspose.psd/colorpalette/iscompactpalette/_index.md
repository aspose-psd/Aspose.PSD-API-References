---
title: ColorPalette.IsCompactPalette
second_title: Aspose.PSD für .NET-API-Referenz
description: ColorPalette eigendom. Ruft einen Wert ab oder legt einen Wert fest der angibt ob eine kompakte Palette verwendet wird.
type: docs
weight: 60
url: /de/net/aspose.psd/colorpalette/iscompactpalette/
---
## ColorPalette.IsCompactPalette property

Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob eine kompakte Palette verwendet wird.

```csharp
public bool IsCompactPalette { get; }
```

### Eigentumswert

`WAHR` wenn Kompaktpalette verwendet wird; ansonsten,`FALSCH`.

### Bemerkungen

Kompakte Palette bedeutet, dass das Bild nach Möglichkeit nur die angegebenen Paletteneinträge enthält, oder anders ausgedrückt, das Bild wird kompakter und nimmt weniger Platz ein; sonst gibt es 2^BitsPerPixel-Einträge und das Bild reserviert mehr Platz für alle möglichen Paletteneinträge. Wenn Sie diesen Wert auf „true“ setzen und Paletteneinträge ändern, kann dies zu Leistungseinbußen führen, da es zu Datenverschiebungen kommen kann. Gehen Sie daher vorsichtig vor.

### Siehe auch

* class [ColorPalette](../)
* namensraum [Aspose.PSD](../../colorpalette/)
* Montage [Aspose.PSD](../../../)


