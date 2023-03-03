---
title: Cache.ExactReallocateOnly
second_title: Aspose.PSD für .NET-API-Referenz
description: Cache eigendom. Ruft einen Wert ab oder legt einen Wert fest der angibt ob die Neuzuweisung genau sein soll oder nicht. Wenn die Neuzuweisung nicht exakt ist sollte die Leistung höher sein.
type: docs
weight: 50
url: /de/net/aspose.psd/cache/exactreallocateonly/
---
## Cache.ExactReallocateOnly property

Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Neuzuweisung genau sein soll oder nicht. Wenn die Neuzuweisung nicht exakt ist, sollte die Leistung höher sein.

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### Eigentumswert

`WAHR` wenn die Neuzuweisung genau ist; ansonsten,`FALSCH` .

### Bemerkungen

Die exakte Neuzuweisung führt eine Neuzuweisung von zusätzlichem Speicher nur bis zur angegebenen Obergrenze durch. Wenn die Obergrenze für den Arbeitsspeicher während der Neuzuweisung überschritten wird, werden die zwischengespeicherten Daten nach Möglichkeit auf die Festplatte kopiert. Wenn die Obergrenze für den Festplattenspeicher während der Neuzuweisung überschritten wird entsprechende Exception wird geworfen. Die Performance sollte höher sein, wenn diese Option ausgeschaltet ist, da möglichst keine weiteren Kopiervorgänge durchgeführt werden, dies jedoch auch dazu führen kann, dass angegebene Speicher- oder Plattenobergrenzen überschritten werden.

### Siehe auch

* class [Cache](../)
* namensraum [Aspose.PSD](../../cache/)
* Montage [Aspose.PSD](../../../)


