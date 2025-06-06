---
title: PsdLoadOptions.AllowWarpRepaint
second_title: Aspose.PSD for .NET API Reference
description: PsdLoadOptions property. Gets or sets whether to save with the rendered image with or without a warp transform
type: docs
weight: 30
url: /net/aspose.psd.imageloadoptions/psdloadoptions/allowwarprepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowWarpRepaint property

Gets or sets whether to save with the rendered image, with or without a warp transform.

```csharp
public bool AllowWarpRepaint { get; set; }
```

### Property Value

`true` render image with warp transformation `false`.

## Examples

The following code demonstrates the Warp effect rendering.

```csharp
[C#]

string sourceFile = "source.psd";
string pngWarpedExport = "warped.png";
string psdWarpedExport = "warpFile.psd";

var warpLoadOptions = new PsdLoadOptions() { AllowWarpRepaint = true };

using (var image = (PsdImage)Image.Load(sourceFile, warpLoadOptions))
{
    image.Save(pngWarpedExport, new PngOptions());
    image.Save(psdWarpedExport, new PsdOptions());
}
```

### See Also

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


