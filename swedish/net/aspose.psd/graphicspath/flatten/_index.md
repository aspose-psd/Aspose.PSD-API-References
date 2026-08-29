---
title: "GraphicsPath.Flatten"
second_title: "Aspose.PSD för .NET API‑referens"
description: "GraphicsPath-metod. Konverterar varje kurva i denna väg till en sekvens av sammanhängande linjesegment"
type: docs
weight: 90
url: /sv/net/aspose.psd/graphicspath/flatten/
---
{{< psd/tize >}}
## Flatten() {#flatten}

Konverterar varje kurva i denna sökväg till en sekvens av sammanlänkade linjesegment.

```csharp
public void Flatten()
```

### Se även

* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

Tillämpar den angivna transformen och konverterar sedan varje kurva i denna [`GraphicsPath`](../) till en sekvens av sammanhängande linjesegment.

```csharp
public void Flatten(Matrix matrix)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | Matrix | En [`Matrix`](../../matrix/) som används för att transformera denna [`GraphicsPath`](../) före plattning. |

### Se även

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

Konverterar varje kurva i denna [`GraphicsPath`](../) till en sekvens av sammanhängande linjesegment.

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | Matrix | En [`Matrix`](../../matrix/) som används för att transformera denna [`GraphicsPath`](../) före plattning. |
| platthet | Single | Anger det maximalt tillåtna felet mellan kurvan och dess plattade approximation. Ett värde på 0,25 är standard. Att minska flatness-värdet ökar antalet linjesegment i approximationen. |

### Se även

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


