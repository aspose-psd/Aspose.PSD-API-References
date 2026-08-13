---
title: "Sınıf VectorPath"
second_title: "Aspose.PSD for .NET API Referansı"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VectorPath sınıfı. Vektör yollarını içeren sınıf"
type: docs
weight: 3730
url: /tr/net/aspose.psd.fileformats.psd.layers.layerresources/vectorpath/
---
{{< psd/tize >}}
## VectorPath class

Vektör yollarını içeren sınıf.

```csharp
public class VectorPath : IPath
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [VectorPath](vectorpath/)() | `VectorPath` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/isdisabled/) { get; set; } | Bu örneğin devre dışı olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [IsFillStartsWithAllPixels](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/isfillstartswithallpixels/) { get; set; } | Dolgunun tüm piksellerle başlayıp başlamadığını gösteren bir değeri alır veya ayarlar. |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/isinverted/) { get; set; } | Bu örneğin ters çevrilmiş olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/isnotlinked/) { get; set; } | Bu örneğin bağlanmamış olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/version/) { get; set; } | Sürümü alır veya ayarlar. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [GetItems](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/getitems/)() | Bir Path içindeki Şekiller dizisini alır. |
| [SetItems](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpath/setitems/)(IPathShape[]) | Bir Path içindeki Şekiller dizisini ayarlar. |

## Örnekler

Aşağıdaki kod, ShapeLayer için vsms veya vmsk kaynaklarından yol nesnelerini gösterir.

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

    // Bir şekli kaldır
    shapes.RemoveAt(1);

    // Değiştirilen verileri kaynağa kaydet
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

// Kaydedilen dosyada değiştirilen değerleri kontrol et
using (PsdImage image = (PsdImage)Image.Load(
    outFile,
    new PsdLoadOptions { LoadEffectsResource = true }))
{
    Layer shapeLayer = image.Layers[1];
    VectorPathDataResource vectorPathDataResource = (VectorPathDataResource)shapeLayer.Resources[1];

    bool isFillStartsWithAllPixels;
    List<IPathShape> shapes = GetShapesFromResource(vectorPathDataResource, out isFillStartsWithAllPixels);

    // Kaydedilen dosyada 1 şekil olmalıdır
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

### Ayrıca Bakınız

* interface [IPath](../ipath/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* assembly [Aspose.PSD](../../)


