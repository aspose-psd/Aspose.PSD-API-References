---
title: "ShapeLayer.Update"
second_title: "Aspose.PSD لـ .NET مرجع API"
description: "طريقة ShapeLayer. تُحدّث الموارد من خصائص طبقة الشكل"
type: docs
weight: 60
url: /ar/net/aspose.psd.fileformats.psd.layers/shapelayer/update/
---
{{< psd/tize >}}
## ShapeLayer.Update method

يُحدّث الموارد من خصائص طبقة الشكل.

```csharp
public void Update()
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


