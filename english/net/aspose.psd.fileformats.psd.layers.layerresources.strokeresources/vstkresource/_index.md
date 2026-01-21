---
title: Class VstkResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.VstkResource class. Resource class VstkResource. Contains information about Vector Stroke Data. Resource should be initialized either by AssignItems method from ResourceLoader either by assigning values to properties of the class
type: docs
weight: 3410
url: /net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/
---
{{< psd/tize >}}
## VstkResource class

Resource class VstkResource. Contains information about Vector Stroke Data. Resource should be initialized either by AssignItems method from ResourceLoader, either by assigning values to properties of the class.

```csharp
public class VstkResource : LayerResource
```

## Constructors

| Name | Description |
| --- | --- |
| [VstkResource](vstkresource/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [FillEnabled](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/fillenabled/) { get; set; } | Gets or sets a value indicating whether Stroke fill enabled. |
| [FillSettings](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/fillsettings/) { get; set; } | Gets or sets Fill settings of the Stroke. |
| [Key](../../aspose.psd.fileformats.psd.layers/layerresource/key/) { get; } | Gets the layer resource key. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/length/) { get; } | Gets the layer resource length in bytes. |
| [PsdVersion](../../aspose.psd.fileformats.psd.layers/layerresource/psdversion/) { get; } | Gets the minimal psd version required for layer resource. 0 indicates no restrictions. |
| virtual [Signature](../../aspose.psd.fileformats.psd.layers/layerresource/signature/) { get; } | Gets the signature. |
| [StrokeEnabled](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokeenabled/) { get; set; } | Gets or sets a value indicating whether stroke effect enabled. |
| [StrokeStyleBlendMode](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestyleblendmode/) { get; set; } | Gets or sets Stroke Blend mode. |
| [StrokeStyleContent](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylecontent/) { get; set; } | Gets or sets Stroke entity. Property determines fill settings of the stroke. |
| [StrokeStyleLineAlignment](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinealignment/) { get; set; } | Gets or sets Stroke style line alignment. |
| [StrokeStyleLineCapType](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinecaptype/) { get; set; } | Gets or sets the type of the stroke style line cap. |
| [StrokeStyleLineCapWidth](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinecapwidth/) { get; set; } | Gets or sets Stroke line cap width. |
| [StrokeStyleLineDashOffset](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinedashoffset/) { get; set; } | Gets or sets the stroke style line dash offset. |
| [StrokeStyleLineDashSet](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinedashset/) { get; set; } | Gets or sets array of line dashes. |
| [StrokeStyleLineJoinType](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinejointype/) { get; set; } | Gets or sets Stroke style line join type. |
| [StrokeStyleLineWidth](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylelinewidth/) { get; set; } | Gets or sets Stroke line width. |
| [StrokeStyleMiterLimit](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylemiterlimit/) { get; set; } | Gets or sets the stroke style miter limit. |
| [StrokeStyleOpacity](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestyleopacity/) { get; set; } | Gets or sets Stroke style opacity (0-100%). |
| [StrokeStyleResolution](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestyleresolution/) { get; set; } | Gets or sets Stroke style resolution. |
| [StrokeStyleScaleLock](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylescalelock/) { get; set; } | Gets or sets Stroke style scale lock. |
| [StrokeStyleStrokeAdjust](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestylestrokeadjust/) { get; set; } | Gets or sets Stroke adjust. |
| [StrokeStyleVersion](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/strokestyleversion/) { get; set; } | Gets or sets the stroke style version. |

## Methods

| Name | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/save/)(StreamContainer, int) | Saves the resource to the specified stream container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/vstkresource/typetoolkey/) | The type tool info key. |

## Examples

The following code demonstrates the support of VstkResource resource.

```csharp
[C#]

string srcFile = "StrokeShapeTest1.psd";
string dstFile = "StrokeShapeTest2.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile))
{
    Layer layer = image.Layers[1];
    foreach (LayerResource resource in layer.Resources)
    {
        if (resource is VstkResource)
        {
            VstkResource vstkResource = (VstkResource)resource;
            vstkResource.StrokeStyleLineAlignment = StrokePosition.Outside;
            vstkResource.StrokeStyleLineWidth = 20;
        }
    }

    image.Save(dstFile);
}
```

### See Also

* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


