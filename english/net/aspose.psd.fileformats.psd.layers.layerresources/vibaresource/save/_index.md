---
title: VibAResource.Save
second_title: Aspose.PSD for .NET API Reference
description: VibAResource method. Saves the resource to the specified stream container
type: docs
weight: 70
url: /net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/save/
---
{{< psd/tize >}}
## VibAResource.Save method

Saves the resource to the specified stream container.

```csharp
public override void Save(StreamContainer streamContainer, int psdVersion)
```

| Parameter | Type | Description |
| --- | --- | --- |
| streamContainer | StreamContainer | The stream container to save to. |
| psdVersion | Int32 | The PSD version. |

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

* class [StreamContainer](../../../aspose.psd/streamcontainer/)
* class [VibAResource](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../../)


