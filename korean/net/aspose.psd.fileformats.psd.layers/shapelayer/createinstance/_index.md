---
title: "ShapeLayer.CreateInstance"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "ShapeLayer 메서드. ShapeLayer 클래스의 새 인스턴스를 생성합니다"
type: docs
weight: 20
url: /ko/net/aspose.psd.fileformats.psd.layers/shapelayer/createinstance/
---
{{< psd/tize >}}
## ShapeLayer.CreateInstance method

새 인스턴스를 생성합니다 [`ShapeLayer`](../) 클래스.

```csharp
public static ShapeLayer CreateInstance()
```

### 반환 값

새 인스턴스를 반환합니다 [`ShapeLayer`](../) 클래스.

## 예제

다음 코드는 ShapeLayer 레이어에 대한 지원을 보여줍니다.

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

    // 소스 파일에 2개의 도형이 포함되어 있습니다. 두 번째 도형을 제거합니다.
    pathShapesDest.RemoveAt(1);

    layerPath.SetItems(pathShapesDest.ToArray());

    shapeLayer.Update();

    image.Save(outFile);
}
```

### 또 보기

* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


