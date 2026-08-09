---
title: "ColorPalette.IsCompactPalette"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "ColorPalette-Eigenschaft. Gibt einen Wert zurück oder legt ihn fest, der angibt, ob eine kompakte Palette verwendet wird"
type: docs
weight: 60
url: /de/net/aspose.psd/colorpalette/iscompactpalette/
---
{{< psd/tize >}}
## ColorPalette.IsCompactPalette property

Liest oder setzt einen Wert, der angibt, ob eine kompakte Palette verwendet wird.

```csharp
public bool IsCompactPalette { get; }
```

### Property Value

`true`, wenn eine kompakte Palette verwendet wird; andernfalls `false`.

## Hinweise

Eine kompakte Palette bedeutet, dass das Bild nur die angegebenen Paletteneinträge enthält, falls möglich – mit anderen Worten, das Bild wird kompakter und belegt weniger Speicher; andernfalls gibt es 2^BitsPerPixel Einträge und das Bild reserviert mehr Platz für alle möglichen Paletteneinträge. Das Setzen dieses Wertes auf `true` und das Ändern von Paletteneinträgen kann zu Leistungseinbußen führen, da Datenbewegungen auftreten können, daher sollte es vorsichtig verwendet werden.

### Siehe auch

* class [ColorPalette](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


