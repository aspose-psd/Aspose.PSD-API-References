---
title: "الفئة PathShape"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.PathShape فئة. الشكل المستمد من عقد منحنى Bezier"
type: docs
weight: 3210
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/
---
{{< psd/tize >}}
## PathShape class

الشكل المستخرج من عقد منحنى بيزييه.

```csharp
public class PathShape : IPathShape
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PathShape](pathshape/#constructor)() | يُهيئ مثلاً جديداً من الفئة `PathShape`. |
| [PathShape](pathshape/#constructor_1)(LengthRecord, BezierKnotRecord[]) | يُهيئ مثلاً جديداً من الفئة `PathShape`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IsClosed](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/isclosed/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان هذا المثيل مغلقاً. |
| [PathOperations](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/pathoperations/) { get; set; } | يحصل أو يعيّن عمليات المسار (العمليات البوليانية). |
| [ShapeIndex](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/shapeindex/) { get; set; } | يحصل أو يعيّن فهرس الشكل المساري الحالي في الطبقة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetItems](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/getitems/)() | يحصل على مصفوفة من عقد Bezier. |
| [SetItems](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/setitems/)(BezierKnotRecord[]) | يعيّن مصفوفة من عقد Bezier. |
| [ToVectorPathRecords](../../aspose.psd.fileformats.psd.layers.layerresources/pathshape/tovectorpathrecords/)() | ينشئ سجلات [`VectorPathRecord`](../../aspose.psd.fileformats.core.vectorpaths/vectorpathrecord/) بناءً على هذا المثيل. |

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

* interface [IPathShape](../ipathshape/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


