---
title: "PsdColorPalette.IsCompactPalette"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "PsdColorPalette Eigenschaft. Gibt einen Wert zurück, der angibt, ob die Palette kompakt ist"
type: docs
weight: 70
url: /de/net/aspose.psd.fileformats.psd/psdcolorpalette/iscompactpalette/
---
{{< psd/tize >}}
## PsdColorPalette.IsCompactPalette property

Gibt einen Wert zurück, der angibt, ob die Palette kompakt ist.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true`, wenn die Palette kompakt ist; andernfalls `false`.

## Hinweise

Eine kompakte Palette bedeutet, dass das Bild nur die angegebenen Paletteneinträge enthält, falls möglich – mit anderen Worten, das Bild wird kompakter und belegt weniger Speicher; andernfalls gibt es 2^BitsPerPixel Einträge und das Bild reserviert mehr Platz für alle möglichen Paletteneinträge. Das Setzen dieses Wertes auf `true` und das Ändern von Paletteneinträgen kann zu Leistungseinbußen führen, da Datenbewegungen auftreten können, daher sollte es vorsichtig verwendet werden.

### Siehe auch

* class [PsdColorPalette](../)
* namespace [Aspose.PSD.FileFormats.Psd](../../../aspose.psd.fileformats.psd/)
* assembly [Aspose.PSD](../../../)


