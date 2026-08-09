---
title: "GraphicsPath.Flatten"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "GraphicsPath‑Methode. Wandelt jede Kurve in diesem Pfad in eine Sequenz verbundener Liniensegmente um"
type: docs
weight: 90
url: /de/net/aspose.psd/graphicspath/flatten/
---
{{< psd/tize >}}
## Flatten() {#flatten}

Konvertiert jede Kurve in diesem Pfad in eine Sequenz zusammenhängender Liniensegmente.

```csharp
public void Flatten()
```

### Siehe auch

* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

Wendet die angegebene Transformation an und wandelt dann jede Kurve in diesem [`GraphicsPath`](../) in eine Sequenz verbundener Liniensegmente um.

```csharp
public void Flatten(Matrix matrix)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | Matrix | Eine [`Matrix`](../../matrix/), mit der dieses [`GraphicsPath`](../) vor dem Glätten transformiert wird. |

### Siehe auch

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

Wandelt jede Kurve in diesem [`GraphicsPath`](../) in eine Sequenz verbundener Liniensegmente um.

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix | Matrix | Eine [`Matrix`](../../matrix/), mit der dieses [`GraphicsPath`](../) vor dem Glätten transformiert wird. |
| Flachheit | Single | Gibt den maximal zulässigen Fehler zwischen der Kurve und ihrer abgeflachten Annäherung an. Der Standardwert ist 0,25. Eine Verringerung des Glättungswertes erhöht die Anzahl der Liniensegmente in der Annäherung. |

### Siehe auch

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


