---
title: RasterImage.SetPalette
second_title: Aspose.PSD for .NET API Reference
description: RasterImage method. Sets the image palette
type: docs
weight: 570
url: /net/aspose.psd/rasterimage/setpalette/
---
{{< psd/tize >}}
## RasterImage.SetPalette method

Sets the image palette.

```csharp
public override void SetPalette(IColorPalette palette, bool updateColors)
```

| Parameter | Type | Description |
| --- | --- | --- |
| palette | IColorPalette | The palette to set. |
| updateColors | Boolean | if set to `true` colors will be updated according to the new palette; otherwise color indexes remain unchanged. Note that unchanged indexes may crash the image on loading if some indexes have no corresponding palette entries. |

### See Also

* interface [IColorPalette](../../icolorpalette/)
* class [RasterImage](../)
* namespace [Aspose.PSD](../../rasterimage/)
* assembly [Aspose.PSD](../../../)


