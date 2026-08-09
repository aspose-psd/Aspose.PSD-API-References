---
title: "ShapeLayer.CreateInstance"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة ShapeLayer. تنشئ مثيلاً جديداً من الفئة ShapeLayer."
type: docs
weight: 20
url: /ar/net/aspose.psd.fileformats.psd.layers/shapelayer/createinstance/
---
{{< psd/tize >}}
## ShapeLayer.CreateInstance method

ينشئ مثيلاً جديداً من الفئة [`ShapeLayer`](../).

```csharp
public static ShapeLayer CreateInstance()
```

### قيمة الإرجاع

يرجع المثيل الجديد من الفئة [`ShapeLayer`](../).

## أمثلة

الكود التالي يُظهر الدعم لطبقة ShapeLayer.

```csharp
[C#]

string srcFile = "ShapeLayerTest.psd";
string outFile = "ShapeLayerTest-out.psd";

using (PsdImage image = (PsdImage)Image.Load(srcFile, new PsdLoadOptions { LoadEffectsResource = true }))
{
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    IPath layerPath = shapeLayer.Path;

    IPathShape[] pathShapeSource = layerPath.GetItems();
    List<IPathShape> pathShapesDest = new List<IPathShape>(pathShapeSource);

    // ملف المصدر يحتوي على شكلين. احذف الشكل الثاني.
    pathShapesDest.RemoveAt(1);

    layerPath.SetItems(pathShapesDest.ToArray());

    shapeLayer.Update();

    image.Save(outFile);
}
```

### انظر أيضًا

* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


