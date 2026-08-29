---
title: "الفئة VectorPath"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "الفئة Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VectorPath. الفئة التي تحتوي على مسارات المتجهات"
type: docs
weight: 3730
url: /ar/net/aspose.psd.fileformats.psd.layers.layerresources/vectorpath/
---
{{< psd/tize >}}
## VectorPath class

الفئة التي تحتوي على مسارات المتجه.

```csharp
public class VectorPath : IPath
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [VectorPath](vectorpath/)() | ينشئ مثيلًا جديدًا للفئة `VectorPath`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/isdisabled/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل معطلاً. |
| [IsFillStartsWithAllPixels](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/isfillstartswithallpixels/) { get; set; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كان التعبئة تبدأ بجميع البكسلات. |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/isinverted/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل مقلوبًا. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/isnotlinked/) { get; set; } | يحصل أو يضبط قيمة تشير إلى ما إذا كان هذا المثيل غير مرتبط. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/version/) { get; set; } | يحصل أو يضبط الإصدار. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetItems](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/getitems/)() | يحصل على مصفوفة من الأشكال في مسار. |
| [SetItems](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/setitems/)(IPathShape[]) | يعيّن مصفوفة من الأشكال في مسار. |

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

* interface [IPath](../ipath/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


