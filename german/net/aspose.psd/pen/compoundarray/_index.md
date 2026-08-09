---
title: "Pen.CompoundArray"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Pen-Eigenschaft. Gibt ein Array von Werten zurück oder legt es fest, das einen Verbund-Pen definiert. Ein Verbund-Pen zeichnet eine zusammengesetzte Linie, die aus parallelen Linien und Zwischenräumen besteht."
type: docs
weight: 50
url: /de/net/aspose.psd/pen/compoundarray/
---
{{< psd/tize >}}
## Pen.CompoundArray property

Liest oder legt ein Array von Werten fest, das einen zusammengesetzten Stift definiert. Ein zusammengesetzter Stift zeichnet eine zusammengesetzte Linie, die aus parallelen Linien und Zwischenräumen besteht.

```csharp
public float[] CompoundArray { get; set; }
```

### Property Value

Ein Array von reellen Zahlen, das das Verbund-Array definiert. Die Elemente im Array müssen in aufsteigender Reihenfolge liegen, dürfen nicht kleiner als 0 und nicht größer als 1 sein.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Die `CompoundArray`-Eigenschaft wird bei einem unveränderlichen [`Pen`](../) festgelegt, wie ihn die [`Pen`](../)-Klasse zurückgibt. |

### Siehe auch

* class [Pen](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


