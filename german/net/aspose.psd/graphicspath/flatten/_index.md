---
title: GraphicsPath.Flatten
second_title: Aspose.PSD für .NET-API-Referenz
description: GraphicsPath methode. Konvertiert jede Kurve in diesem Pfad in eine Folge verbundener Liniensegmente.
type: docs
weight: 90
url: /de/net/aspose.psd/graphicspath/flatten/
---
## Flatten() {#flatten}

Konvertiert jede Kurve in diesem Pfad in eine Folge verbundener Liniensegmente.

```csharp
public void Flatten()
```

### Siehe auch

* class [GraphicsPath](../)
* namensraum [Aspose.PSD](../../graphicspath/)
* Montage [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

Wendet die angegebene Transformation an und wandelt dann jede Kurve in diese um[`GraphicsPath`](../) in eine Folge verbundener Liniensegmente.

```csharp
public void Flatten(Matrix matrix)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | Matrix | A[`Matrix`](../../matrix/) um dies umzuwandeln[`GraphicsPath`](../) vor dem Abflachen. |

### Siehe auch

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namensraum [Aspose.PSD](../../graphicspath/)
* Montage [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

Wandelt jede Kurve in diese um[`GraphicsPath`](../) in eine Folge verbundener Liniensegmente.

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | Matrix | A[`Matrix`](../../matrix/) um dies umzuwandeln[`GraphicsPath`](../) vor dem Abflachen. |
| flatness | Single | Gibt den maximal zulässigen Fehler zwischen der Kurve und ihrer abgeflachten Annäherung an. Ein Wert von 0,25 ist der Standardwert. Durch Verringern des Ebenheitswerts wird die Anzahl der Liniensegmente in der Annäherung erhöht. |

### Siehe auch

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namensraum [Aspose.PSD](../../graphicspath/)
* Montage [Aspose.PSD](../../../)


