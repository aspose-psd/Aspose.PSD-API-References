---
title: "واجهة IStrokeSettings"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "واجهة Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.IStrokeSettings. إعدادات الخط للأشكال"
type: docs
weight: 3390
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/
---
{{< psd/tize >}}
## IStrokeSettings interface

إعدادات الخط للأشكال.

```csharp
public interface IStrokeSettings
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Enabled](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/enabled/) { get; set; } | تم تمكين الخط. |
| [Fill](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/fill/) { get; set; } | يحصل أو يضبط إعدادات التعبئة للخط. |
| [LineAlignment](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/linealignment/) { get; set; } | يحصل أو يضبط محاذاة خط نمط الخط. |
| [LineCap](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/linecap/) { get; set; } | نوع طرف خط الخط. |
| [LineDashSet](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/linedashset/) { get; set; } | يحصل أو يضبط مصفوفة من الشرطات. |
| [LineJoin](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/linejoin/) { get; set; } | نوع وصل خط الخط. |
| [Size](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/size/) { get; set; } | عرض خط الخط. |

## أمثلة

الكود التالي يوضح كائنات المسار من موارد vsms أو vmsk لطبقة ShapeLayer.

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

    // إزالة شكل واحد
    shapes.RemoveAt(1);

    // احفظ البيانات المعدلة إلى المورد
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

// تحقق من القيم المعدلة في الملف المحفوظ
using (PsdImage image = (PsdImage)Image.Load(
    outFile,
    new PsdLoadOptions { LoadEffectsResource = true }))
{
    Layer shapeLayer = image.Layers[1];
    VectorPathDataResource vectorPathDataResource = (VectorPathDataResource)shapeLayer.Resources[1];

    bool isFillStartsWithAllPixels;
    List<IPathShape> shapes = GetShapesFromResource(vectorPathDataResource, out isFillStartsWithAllPixels);

    // يجب أن يحتوي الملف المحفوظ على شكل واحد
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

### انظر أيضًا

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


