---
title: "IColorPalette.IsCompactPalette"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "IColorPalette-Eigenschaft. Gibt einen Wert zurück, der angibt, ob eine kompakte Palette verwendet wird"
type: docs
weight: 40
url: /de/net/aspose.psd/icolorpalette/iscompactpalette/
---
{{< psd/tize >}}
## IColorPalette.IsCompactPalette property

Gibt einen Wert zurück, der angibt, ob eine kompakte Palette verwendet wird.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true`, wenn eine kompakte Palette verwendet wird; andernfalls `false`.

## Hinweise

Eine kompakte Palette bedeutet, dass das Bild nur die angegebenen Paletteneinträge enthält, falls möglich – mit anderen Worten, das Bild wird kompakter und belegt weniger Speicher; andernfalls gibt es 2^BitsPerPixel Einträge und das Bild reserviert mehr Platz für alle möglichen Paletteneinträge. Das Setzen dieses Wertes auf `true` und das Ändern von Paletteneinträgen kann zu Leistungseinbußen führen, da Datenbewegungen auftreten können, daher sollte es vorsichtig verwendet werden.

### Siehe auch

* interface [IColorPalette](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


