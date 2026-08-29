---
title: "ImageAttributes.SetRemapTable"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "ImageAttributes-Methode. Setzt die Farbzuordnungstabelle für die Standardkategorie"
type: docs
weight: 190
url: /de/net/aspose.psd/imageattributes/setremaptable/
---
{{< psd/tize >}}
## SetRemapTable(ColorMap[]) {#setremaptable}

Legt die Farb-Remap-Tabelle für die Standardkategorie fest.

```csharp
public void SetRemapTable(ColorMap[] map)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| map | ColorMap[] | Ein Array von Farbpaaren vom Typ [`ColorMap`](../../colormap/). Jedes Farbpaar enthält eine vorhandene Farbe (den ersten Wert) und die Farbe, auf die sie abgebildet wird (den zweiten Wert). |

### Siehe auch

* class [ColorMap](../../colormap/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetRemapTable(ColorMap[], ColorAdjustType) {#setremaptable_1}

Legt die Farb-Remap-Tabelle für eine bestimmte Kategorie fest.

```csharp
public void SetRemapTable(ColorMap[] map, ColorAdjustType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| map | ColorMap[] | Ein Array von Farbpaaren vom Typ [`ColorMap`](../../colormap/). Jedes Farbpaar enthält eine vorhandene Farbe (den ersten Wert) und die Farbe, auf die sie abgebildet wird (den zweiten Wert). |
| type | ColorAdjustType | Ein Element von [`ColorAdjustType`](../../coloradjusttype/), das die Kategorie angibt, für die die Farbzuordnungstabelle festgelegt wird. |

### Siehe auch

* class [ColorMap](../../colormap/)
* enum [ColorAdjustType](../../coloradjusttype/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


