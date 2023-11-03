---
title: Class VmskResource
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VmskResource class. Class VmskResource. This resource contains information about vector layer mask
type: docs
weight: 3550
url: /net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/
---
{{< psd/tize >}}
## VmskResource class

Class VmskResource. This resource contains information about vector layer mask

```csharp
public class VmskResource : VectorPathDataResource
```

## Constructors

| Name | Description |
| --- | --- |
| [VmskResource](vmskresource/#constructor)() | Initializes a new instance of the `VmskResource` class. |
| [VmskResource](vmskresource/#constructor_1)(byte[]) | Initializes a new instance of the `VmskResource` class. |

## Properties

| Name | Description |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isdisabled/) { get; set; } | Gets or sets a value indicating whether this instance is disabled. |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isinverted/) { get; set; } | Gets or sets a value indicating whether this instance is inverted. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isnotlinked/) { get; set; } | Gets or sets a value indicating whether this instance is not linked. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/vmskresource/key/) { get; } | Gets the layer resource key. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/length/) { get; } | Gets the layer resource length in bytes. |
| [Paths](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/paths/) { get; set; } | Gets or sets the path records. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/psdversion/) { get; } | Gets the psd version. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/signature/) { get; } | Gets the signature. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/version/) { get; set; } | Gets or sets the version. |

## Methods

| Name | Description |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/save/)(StreamContainer, int) | Saves the resource to the specified stream container. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vmskresource/typetoolkey/) | The type tool info key. |

## Examples

The following example demonstrates the support of VmskResource resource loading. How works the editing of paths.

```csharp
[C#]

[Test]
public void TestPsdNet106()
{
    string sourceFileName = "Rectangle.psd";
    string exportPath = "Rectangle_changed.psd";
    var im = (PsdImage)Image.Load(sourceFileName);
    using (im)
    {
        var resource = GetVmskResource(im);
        // Reading
        if (resource.IsDisabled != false ||
         resource.IsInverted != false ||
         resource.IsNotLinked != false ||
         resource.Paths.Length != 7 ||
         resource.Paths[0].Type != VectorPathType.PathFillRuleRecord ||
         resource.Paths[1].Type != VectorPathType.InitialFillRuleRecord ||
         resource.Paths[2].Type != VectorPathType.ClosedSubpathLengthRecord ||
         resource.Paths[3].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked ||
         resource.Paths[4].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked ||
         resource.Paths[5].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked ||
         resource.Paths[6].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked)
        {
            throw new Exception("VmskResource was read wrong");
        }
        var pathFillRule = (PathFillRuleRecord)resource.Paths[0];
        var initialFillRule = (InitialFillRuleRecord)resource.Paths[1];
        var subpathLength = (LengthRecord)resource.Paths[2];
        // Path fill rule doesn't contain any additional information
        if (pathFillRule.Type != VectorPathType.PathFillRuleRecord ||
         initialFillRule.Type != VectorPathType.InitialFillRuleRecord ||
         initialFillRule.IsFillStartsWithAllPixels != false ||
         subpathLength.Type != VectorPathType.ClosedSubpathLengthRecord ||
         subpathLength.IsClosed != true ||
         subpathLength.IsOpen != false)
        {
            throw new Exception("VmskResource paths were read wrong");
        }
        // Editing
        resource.IsDisabled = true;
        resource.IsInverted = true;
        resource.IsNotLinked = true;
        var bezierKnot = (BezierKnotRecord)resource.Paths[3];
        bezierKnot.Points[0] = new Point(0, 0);
        bezierKnot = (BezierKnotRecord)resource.Paths[4];
        bezierKnot.Points[0] = new Point(8039797, 10905190);
        initialFillRule.IsFillStartsWithAllPixels = true;
        subpathLength.IsClosed = false;
        im.Save(exportPath);
    }
}

private VmskResource GetVmskResource(PsdImage image)
{
    var layer = image.Layers[1];
    VmskResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VmskResource)
        {
            resource = (VmskResource)resources[i];
            break;
        }
    }
    if (resource == null)
    {
        throw new Exception("VmskResource not found");
    }
    return resource;
}
```

### See Also

* class [VectorPathDataResource](../vectorpathdataresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


