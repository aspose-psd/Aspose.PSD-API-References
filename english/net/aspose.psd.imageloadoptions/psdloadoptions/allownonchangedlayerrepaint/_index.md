---
title: PsdLoadOptions.AllowNonChangedLayerRepaint
second_title: Aspose.PSD for .NET API Reference
description: PsdLoadOptions property. Gets or sets whether to preserve original layer pixels during rendering if the layer has not been modified
type: docs
weight: 20
url: /net/aspose.psd.imageloadoptions/psdloadoptions/allownonchangedlayerrepaint/
---
{{< psd/tize >}}
## PsdLoadOptions.AllowNonChangedLayerRepaint property

Gets or sets whether to preserve original layer pixels during rendering if the layer has not been modified.

```csharp
public bool AllowNonChangedLayerRepaint { get; set; }
```

### Property Value

`true` to keep the original pixels of unchanged layers; otherwise, `false`.

## Examples

The following code demonstrates the new behaviour that prevent auto repaint of layers before changes.

```csharp
[C#]

string srcFile = "psdnet2400.psd";
string output1 = "unchanged-2400.png";
string output2 = "updated-2400.png";

using (var psdImage = (PsdImage)Image.Load(srcFile,
new PsdLoadOptions() { AllowNonChangedLayerRepaint = false /* The new default behaviour */ }))
{
    psdImage.Save(output1, new PngOptions());

    ((TextLayer)psdImage.Layers[1]).TextData.UpdateLayerData();

    psdImage.Save(output2, new PngOptions());
}
```

### See Also

* class [PsdLoadOptions](../)
* namespace [Aspose.PSD.ImageLoadOptions](../../../aspose.psd.imageloadoptions/)
* assembly [Aspose.PSD](../../../)


