---
title: GifOptions.DoPaletteCorrection
second_title: Aspose.PSD for .NET API Reference
description: GifOptions property. Gets or sets a value indicating whether palette correction is applied
type: docs
weight: 40
url: /net/aspose.psd.imageoptions/gifoptions/dopalettecorrection/
---
{{< psd/tize >}}
## GifOptions.DoPaletteCorrection property

Gets or sets a value indicating whether palette correction is applied.

```csharp
public bool DoPaletteCorrection { get; set; }
```

### Property Value

`true` if palette correction is applied; otherwise, `false`.

## Remarks

Palette correction means that whenever image is exported to GIF the source image colors will be analyzed in order to build the best matching palette (in case image Palette does not exist or not specified in the options). The analyze process takes some time however the output image will have the best matching color palette and result is visually better.

### See Also

* class [GifOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


