---
title: GraphicsPath.Flatten
second_title: Aspose.PSD för .NET API-referens
description: GraphicsPath metod. Konverterar varje kurva i denna väg till en sekvens av anslutna linjesegment.
type: docs
weight: 90
url: /sv/net/aspose.psd/graphicspath/flatten/
---
## Flatten() {#flatten}

Konverterar varje kurva i denna väg till en sekvens av anslutna linjesegment.

```csharp
public void Flatten()
```

### Se även

* class [GraphicsPath](../)
* namnutrymme [Aspose.PSD](../../graphicspath/)
* hopsättning [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

Tillämpar den angivna transformationen och konverterar sedan varje kurva i denna[`GraphicsPath`](../) i en sekvens av anslutna linjesegment.

```csharp
public void Flatten(Matrix matrix)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | Matrix | A[`Matrix`](../../matrix/) för att omvandla detta[`GraphicsPath`](../) innan tillplattad. |

### Se även

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namnutrymme [Aspose.PSD](../../graphicspath/)
* hopsättning [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

Konverterar varje kurva i denna[`GraphicsPath`](../) i en sekvens av anslutna linjesegment.

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix | Matrix | A[`Matrix`](../../matrix/) för att omvandla detta[`GraphicsPath`](../) innan tillplattad. |
| flatness | Single | Anger det maximalt tillåtna felet mellan kurvan och dess tillplattade approximation. Ett värde på 0,25 är standard. Om du minskar planhetsvärdet ökar antalet linjesegment i approximationen. |

### Se även

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namnutrymme [Aspose.PSD](../../graphicspath/)
* hopsättning [Aspose.PSD](../../../)


