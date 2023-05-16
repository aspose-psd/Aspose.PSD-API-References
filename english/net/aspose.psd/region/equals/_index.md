---
title: Region.Equals
second_title: Aspose.PSD for .NET API Reference
description: Region method. Tests whether the specified Region is identical to this Region on the specified drawing surface
type: docs
weight: 40
url: /net/aspose.psd/region/equals/
---
{{< psd/tize >}}
## Region.Equals method

Tests whether the specified [`Region`](../) is identical to this [`Region`](../) on the specified drawing surface.

```csharp
public bool Equals(Region region, Graphics g)
```

| Parameter | Type | Description |
| --- | --- | --- |
| region | Region | The [`Region`](../) to test. |
| g | Graphics | A [`Graphics`](../../graphics/) that represents a drawing surface. |

### Return Value

True if the interior of region is identical to the interior of this region when the transformation associated with the *g* parameter is applied; otherwise, false.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *g *or* region* is null. |

### See Also

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../region/)
* assembly [Aspose.PSD](../../../)


