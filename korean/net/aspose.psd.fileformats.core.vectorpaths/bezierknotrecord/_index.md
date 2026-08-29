---
title: "클래스 BezierKnotRecord"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Core.VectorPaths.BezierKnotRecord 클래스. 리소스에서 Bezier 매듭 데이터를 읽고 쓰는 데 사용되는 Bezier Knot Record 클래스"
type: docs
weight: 1340
url: /ko/net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/
---
{{< psd/tize >}}
## BezierKnotRecord class

Bezier Knot Record 클래스는 리소스에서 Bezier knot 데이터를 읽고/쓰는 데 사용됩니다.

```csharp
public class BezierKnotRecord : VectorPathRecord
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [BezierKnotRecord](bezierknotrecord/#constructor)() | `BezierKnotRecord` 클래스의 새 인스턴스를 초기화합니다. |
| [BezierKnotRecord](bezierknotrecord/#constructor_1)(byte[]) | `BezierKnotRecord` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [IsClosed](../../aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/isclosed/) { get; set; } | 이 인스턴스가 닫혔는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [IsLinked](../../aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/islinked/) { get; set; } | 이 인스턴스가 연결되어 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [IsOpen](../../aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/isopen/) { get; set; } | 이 인스턴스가 열려 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [PathPoints](../../aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/pathpoints/) { get; set; } | 경로 포인트를 가져오거나 설정합니다. |
| [Points](../../aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/points/) { get; set; } | 포인트를 가져오거나 설정합니다. |
| override [Type](../../aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/type/) { get; } | 형식을 가져옵니다. |

## 예제

다음 예제는 VmskResource 리소스 로드 지원을 보여줍니다. 경로 편집이 어떻게 작동하는지.

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
        // 읽기
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
        // 경로 채우기 규칙에는 추가 정보가 포함되지 않습니다.
        if (pathFillRule.Type != VectorPathType.PathFillRuleRecord ||
         initialFillRule.Type != VectorPathType.InitialFillRuleRecord ||
         initialFillRule.IsFillStartsWithAllPixels != false ||
         subpathLength.Type != VectorPathType.ClosedSubpathLengthRecord ||
         subpathLength.IsClosed != true ||
         subpathLength.IsOpen != false)
        {
            throw new Exception("VmskResource paths were read wrong");
        }
        // 편집
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

다음 예제는 VsmtResource 리소스 로드 지원을 보여줍니다. 경로 편집이 어떻게 작동하는지.

```csharp
[C#]

[Test]
public void TestPsdNet140()
{
    // VsmsResource 지원
    string sourceFileName = "EmptyRectangle.psd";
    string exportPath = "EmptyRectangle_changed.psd";
    var im = (PsdImage)Image.Load(sourceFileName);
    using (im)
    {
        var resource = GetVsmsResource(im);
        // 읽기
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
            throw new Exception("VsmsResource was read wrong");
        }

        var pathFillRule = (PathFillRuleRecord)resource.Paths[0];
        var initialFillRule = (InitialFillRuleRecord)resource.Paths[1];
        var subpathLength = (LengthRecord)resource.Paths[2];

        // 경로 채우기 규칙에는 추가 정보가 포함되지 않습니다.
        if (pathFillRule.Type != VectorPathType.PathFillRuleRecord ||
        initialFillRule.Type != VectorPathType.InitialFillRuleRecord ||
        initialFillRule.IsFillStartsWithAllPixels != false ||
        subpathLength.Type != VectorPathType.ClosedSubpathLengthRecord ||
        subpathLength.IsClosed != true ||
        subpathLength.IsOpen != false)
        {
            throw new Exception("VsmsResource paths were read wrong");
        }

        // 편집
        resource.IsDisabled = true;
        resource.IsInverted = true;
        resource.IsNotLinked = true;
        var bezierKnot = (BezierKnotRecord)resource.Paths[3];
        bezierKnot.Points[0] = new Point(0, 0);
        bezierKnot = (BezierKnotRecord)resource.Paths[4];
        bezierKnot.Points[0] = new Point(8039798, 10905191);
        initialFillRule.IsFillStartsWithAllPixels = true;
        subpathLength.IsClosed = false;
        im.Save(exportPath);
    }
}

private VsmsResource GetVsmsResource(PsdImage image)
{
    var layer = image.Layers[1];
    VsmsResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VsmsResource)
        {
            resource = (VsmsResource)resources[i];
            break;
        }
    }
    if (resource == null)
    {
        throw new Exception("VsmsResource not found");
    }
    return resource;
}
```

### 또 보기

* class [VectorPathRecord](../vectorpathrecord/)
* namespace [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* assembly [Aspose.PSD](../../)


