---
title: VibAResource.VibAResource
second_title: Aspose.PSD for .NET API Reference
description: VibAResource constructor. Initializes a new instance of the VibAResource class
type: docs
weight: 10
url: /net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/vibaresource/
---
{{< psd/tize >}}
## VibAResource constructor

Initializes a new instance of the [`VibAResource`](../) class.

```csharp
public VibAResource()
```

## Examples

The following code example demonstrates the support of the VibAResource resource.

```csharp
[C#]

// Example of the support of read and write Vibration Resource at runtime.
string sourceFileName = "VibranceResource.psd";
string outputFileName = "out_VibranceResource.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    foreach (var layer in image.Layers)
    {
        foreach (var resource in layer.Resources)
        {
            if (resource is VibAResource)
            {
                var vibranceResource = (VibAResource)resource;

                int vibranceValue =  vibranceResource.Vibrance;
                int saturationValue = vibranceResource.Saturation;

                vibranceResource.Vibrance = vibranceValue * 2;
                vibranceResource.Saturation = saturationValue * 2;

                break;
            }
        }
    }

    image.Save(outputFileName);
}
```

### See Also

* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


