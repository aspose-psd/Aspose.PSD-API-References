---
title: "Region.Equals"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Region-Methode. Prüft, ob das angegebene Region identisch mit diesem Region auf der angegebenen Zeichenfläche ist."
type: docs
weight: 40
url: /de/net/aspose.psd/region/equals/
---
{{< psd/tize >}}
## Equals(Region, Graphics) {#equals}

Prüft, ob das angegebene [`Region`](../) identisch mit diesem [`Region`](../) auf der angegebenen Zeichenfläche ist.

```csharp
public bool Equals(Region region, Graphics g)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| region | Region | Das zu testende [`Region`](../). |
| g | Graphics | Ein [`Graphics`](../../graphics/), das eine Zeichenfläche darstellt. |

### Rückgabewert

Wahr, wenn die Innenfläche des Region identisch mit der Innenfläche dieses Region ist, wenn die mit dem *g*-Parameter verbundene Transformation angewendet wird; andernfalls falsch.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *g* oder *region* ist null. |

### Siehe auch

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Equals(object) {#equals_1}

Prüfen, ob Objekte gleich sind.

```csharp
public override bool Equals(object obj)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | Object | Das andere Objekt. |

### Rückgabewert

Das Ergebnis des Gleichheitsvergleichs.

### Siehe auch

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


