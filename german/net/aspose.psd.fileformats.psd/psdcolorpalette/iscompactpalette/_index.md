---
title: PsdColorPalette.IsCompactPalette
second_title: Aspose.PSD für .NET-API-Referenz
description: PsdColorPalette eigendom. Ruft einen Wert ab der angibt ob die Palette kompakt ist.
type: docs
weight: 70
url: /de/net/aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/
---
## PsdColorPalette.IsCompactPalette property

Ruft einen Wert ab, der angibt, ob die Palette kompakt ist.

```csharp
public bool IsCompactPalette { get; }
```

### Eigentumswert

`WAHR` wenn kompakt es Palette; ansonsten,`FALSCH`.

### Bemerkungen

Kompakte Palette bedeutet, dass das Bild nach Möglichkeit nur die angegebenen Paletteneinträge enthält, oder anders ausgedrückt, das Bild wird kompakter und nimmt weniger Platz ein; sonst gibt es 2^BitsPerPixel-Einträge und das Bild reserviert mehr Platz für alle möglichen Paletteneinträge . Wenn Sie diesen Wert auf „true“ setzen und Paletteneinträge ändern, kann dies zu Leistungseinbußen führen, da es zu Datenverschiebungen kommen kann. Gehen Sie daher vorsichtig vor.

### Siehe auch

* class [PsdColorPalette](../)
* namensraum [Aspose.PSD.FileFormats.Psd](../../psdcolorpalette/)
* Montage [Aspose.PSD](../../../)


