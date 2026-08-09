---
title: "Cache.ExactReallocateOnly"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Cache-Eigenschaft. Gibt einen Wert zurück oder legt ihn fest, der angibt, ob die Neuallokation exakt sein soll oder nicht. Wenn die Neuallokation nicht exakt ist, sollte die Leistung höher sein."
type: docs
weight: 50
url: /de/net/aspose.psd/cache/exactreallocateonly/
---
{{< psd/tize >}}
## Cache.ExactReallocateOnly property

Liest oder setzt einen Wert, der angibt, ob die Neuallokation exakt sein soll oder nicht. Wenn die Neuallokation nicht exakt ist, sollte die Leistung höher sein.

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### Property Value

`true`, wenn die Neuallokation exakt ist; andernfalls `false`.

## Hinweise

Die exakte Neuallokation führt eine Neuallokation zusätzlichen Speichers nur bis zum angegebenen oberen Grenzwert durch. Wird beim Neuallokieren ein oberer Grenzwert für den In‑Memory‑Speicher übergeben, werden die zwischengespeicherten Daten nach Möglichkeit auf die Festplatte kopiert. Wird ein oberer Grenzwert für den Festplattenspeicher übergeben, wird die entsprechende Ausnahme ausgelöst. Die Leistung sollte höher sein, wenn diese Option deaktiviert ist, da keine zusätzlichen Kopiervorgänge durchgeführt werden, sofern möglich; dies kann jedoch dazu führen, dass die angegebenen oberen Grenzwerte für Speicher oder Festplatte überschritten werden.

### Siehe auch

* class [Cache](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


