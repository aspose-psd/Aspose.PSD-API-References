---
title: "ShapeLayer.ShapeLayer"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "منشئ ShapeLayer. يقوم بإنشاء نسخة جديدة من فئة ShapeLayer. جميع الموارد تُنشأ بالحالة الافتراضية"
type: docs
weight: 10
url: /ar/net/aspose.psd.fileformats.psd.layers/shapelayer/shapelayer/
---
{{< psd/tize >}}
## ShapeLayer constructor

يقوم بإنشاء نسخة جديدة من الفئة [`ShapeLayer`](../). جميع الموارد تُنشأ بالحالة الافتراضية.

```csharp
public ShapeLayer()
```

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


