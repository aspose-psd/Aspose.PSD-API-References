---
title: RasterImage.NormalizeAngle
second_title: Aspose.PSD for .NET API Reference
description: RasterImage method. Normalizes the angle. This method is applicable to scanned text documents to get rid of the skewed scan. This method uses GetSkewAngle and Rotate methods
type: docs
weight: 430
url: /net/aspose.psd/rasterimage/normalizeangle/
---
{{< psd/tize >}}
## NormalizeAngle() {#normalizeangle}

Normalizes the angle. This method is applicable to scanned text documents to get rid of the skewed scan. This method uses [`GetSkewAngle`](../getskewangle/) and [`Rotate`](../rotate/) methods.

```csharp
public void NormalizeAngle()
```

### See Also

* class [RasterImage](../)
* namespace [Aspose.PSD](../../rasterimage/)
* assembly [Aspose.PSD](../../../)

---

## NormalizeAngle(bool, Color) {#normalizeangle_1}

Normalizes the angle. This method is applicable to scanned text documents to get rid of the skewed scan. This method uses [`GetSkewAngle`](../getskewangle/) and [`Rotate`](../rotate/) methods.

```csharp
public virtual void NormalizeAngle(bool resizeProportionally, Color backgroundColor)
```

| Parameter | Type | Description |
| --- | --- | --- |
| resizeProportionally | Boolean | if set to `true` you will have your image size changed according to rotated rectangle (corner points) projections in other case that leaves dimensions untouched and only internal image contents are rotated. |
| backgroundColor | Color | Color of the background. |

### See Also

* struct [Color](../../color/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../rasterimage/)
* assembly [Aspose.PSD](../../../)


