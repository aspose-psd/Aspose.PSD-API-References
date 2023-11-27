---
title: Interface IStrokeSettings
second_title: Aspose.PSD for .NET API Reference
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.IStrokeSettings interface. Stroke settings of Shapes
type: docs
weight: 3200
url: /net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/
---
{{< psd/tize >}}
## IStrokeSettings interface

Stroke settings of Shapes.

```csharp
public interface IStrokeSettings
```

## Properties

| Name | Description |
| --- | --- |
| [Enabled](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/enabled/) { get; set; } | Stroke is enabled. |
| [Fill](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/fill/) { get; set; } | Gets or sets Fill settings of the Stroke. |
| [LineAlignment](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/linealignment/) { get; set; } | Gets or sets Stroke style line alignment. |
| [LineCap](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/linecap/) { get; set; } | Stroke line cap type. |
| [LineDashSet](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/linedashset/) { get; set; } | Gets or sets array of line dashes. |
| [LineJoin](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/linejoin/) { get; set; } | Stroke line join type. |
| [Size](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/size/) { get; set; } | Stroke line width. |

## Examples

The following code demonstrates path objects from vsms or vmsk resources for ShapeLayer.

```csharp
[C#]

string srcFile = "ShapeLayerTest.psd";
string outFile = "ShapeLayerTest-out.psd";

using (PsdImage image = (PsdImage)Image.Load(
    srcFile,
    new PsdLoadOptions { LoadEffectsResource = true }))
{
    Layer shapeLayer = image.Layers[1];
    VectorPathDataResource vectorPathDataResource = (VectorPathDataResource)shapeLayer.Resources[1];

    bool isFillStartsWithAllPixels;
    List<IPathShape> shapes = GetShapesFromResource(vectorPathDataResource, out isFillStartsWithAllPixels);

    // Remove one shape
    shapes.RemoveAt(1);

    // Save changed data to resource
    List<VectorPathRecord> path = new List<VectorPathRecord>();
    path.Add(new PathFillRuleRecord(null));
    path.Add(new InitialFillRuleRecord(isFillStartsWithAllPixels));

    for (ushort i = 0; i < shapes.Count; i++)
    {
        PathShape shape = (PathShape)shapes[i];
        shape.ShapeIndex = i;
        path.AddRange(shape.ToVectorPathRecords());
    }

    vectorPathDataResource.Paths = path.ToArray();

    image.Save(outFile);
}

// Check changed values in saved file
using (PsdImage image = (PsdImage)Image.Load(
    outFile,
    new PsdLoadOptions { LoadEffectsResource = true }))
{
    Layer shapeLayer = image.Layers[1];
    VectorPathDataResource vectorPathDataResource = (VectorPathDataResource)shapeLayer.Resources[1];

    bool isFillStartsWithAllPixels;
    List<IPathShape> shapes = GetShapesFromResource(vectorPathDataResource, out isFillStartsWithAllPixels);

    // Saved file should have 1 shape
    AssertAreEqual(1, shapes.Count);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

List<IPathShape> GetShapesFromResource(
    VectorPathDataResource vectorPathDataResource,
    out bool isFillStartsWithAllPixels)
{
    List<IPathShape> shapes = new List<IPathShape>();
    LengthRecord lengthRecord = null;
    isFillStartsWithAllPixels = false;
    List<BezierKnotRecord> bezierKnotRecords = new List<BezierKnotRecord>();

    foreach (var pathRecord in vectorPathDataResource.Paths)
    {
        if (pathRecord is LengthRecord)
        {
            if (bezierKnotRecords.Count > 0)
            {
                shapes.Add(new PathShape(lengthRecord, bezierKnotRecords.ToArray()));
                lengthRecord = null;
                bezierKnotRecords.Clear();
            }

            lengthRecord = (LengthRecord)pathRecord;
        }
        else if (pathRecord is BezierKnotRecord)
        {
            bezierKnotRecords.Add((BezierKnotRecord)pathRecord);
        }
        else if (pathRecord is InitialFillRuleRecord)
        {
            InitialFillRuleRecord initialFillRuleRecord = (InitialFillRuleRecord)pathRecord;
            isFillStartsWithAllPixels = initialFillRuleRecord.IsFillStartsWithAllPixels;
        }
    }

    if (bezierKnotRecords.Count > 0)
    {
        shapes.Add(new PathShape(lengthRecord, bezierKnotRecords.ToArray()));
        lengthRecord = null;
        bezierKnotRecords.Clear();
    }

    return shapes;
}
```

### See Also

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


