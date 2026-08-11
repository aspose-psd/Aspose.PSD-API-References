---
title: "인터페이스 IStrokeSettings"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.IStrokeSettings interface. Shape의 스트로크 설정"
type: docs
weight: 3390
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/
---
{{< psd/tize >}}
## IStrokeSettings interface

도형의 스트로크 설정.

```csharp
public interface IStrokeSettings
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Enabled](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/enabled/) { get; set; } | 스트로크가 활성화되었습니다. |
| [Fill](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/fill/) { get; set; } | 스트로크의 채우기 설정을 가져오거나 설정합니다. |
| [LineAlignment](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/linealignment/) { get; set; } | 스트로크 스타일 라인 정렬을 가져오거나 설정합니다. |
| [LineCap](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/linecap/) { get; set; } | 스트로크 라인 캡 유형. |
| [LineDashSet](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/linedashset/) { get; set; } | 라인 대시 배열을 가져오거나 설정합니다. |
| [LineJoin](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/linejoin/) { get; set; } | 스트로크 라인 조인 유형. |
| [Size](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/istrokesettings/size/) { get; set; } | 스트로크 라인 너비. |

## 예제

다음 코드는 ShapeLayer용 vsms 또는 vmsk 리소스의 경로 객체를 보여줍니다.

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

    // 하나의 도형을 제거합니다
    shapes.RemoveAt(1);

    // 변경된 데이터를 리소스에 저장합니다
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

// 저장된 파일에서 변경된 값을 확인합니다
using (PsdImage image = (PsdImage)Image.Load(
    outFile,
    new PsdLoadOptions { LoadEffectsResource = true }))
{
    Layer shapeLayer = image.Layers[1];
    VectorPathDataResource vectorPathDataResource = (VectorPathDataResource)shapeLayer.Resources[1];

    bool isFillStartsWithAllPixels;
    List<IPathShape> shapes = GetShapesFromResource(vectorPathDataResource, out isFillStartsWithAllPixels);

    // 저장된 파일에는 도형이 1개 있어야 합니다
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

### 또 보기

* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


