---
title: IColorPalette.IsCompactPalette
second_title: Aspose.PSD für .NET-API-Referenz
description: IColorPalette eigendom. Ruft einen Wert ab der angibt ob die kompakte Palette verwendet wird.
type: docs
weight: 40
url: /de/net/aspose.psd/icolorpalette/iscompactpalette/
---
## IColorPalette.IsCompactPalette property

Ruft einen Wert ab, der angibt, ob die kompakte Palette verwendet wird.

```csharp
public bool IsCompactPalette { get; }
```

### Eigentumswert

`WAHR` wenn Kompaktpalette verwendet wird; ansonsten,`FALSCH`.

### Bemerkungen

Kompakte Palette bedeutet, dass das Bild nach Möglichkeit nur die angegebenen Paletteneinträge enthält, oder anders ausgedrückt, das Bild wird kompakter und nimmt weniger Platz ein; sonst gibt es 2^BitsPerPixel-Einträge und das Bild reserviert mehr Platz für alle möglichen Paletteneinträge. Wenn Sie diesen Wert auf „true“ setzen und Paletteneinträge ändern, kann dies zu Leistungseinbußen führen, da es zu Datenverschiebungen kommen kann. Gehen Sie daher vorsichtig vor.

### Siehe auch

* interface [IColorPalette](../)
* namensraum [Aspose.PSD](../../icolorpalette/)
* Montage [Aspose.PSD](../../../)


