---
title: "ShapeLayer.Fill"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "ShapeLayer 속성. Shape 레이어 내 Shape의 내부 영역에 대한 Fill 설정을 가져오거나 설정합니다"
type: docs
weight: 30
url: /ko/net/aspose.psd.fileformats.psd.layers/shapelayer/fill/
---
{{< psd/tize >}}
## ShapeLayer.Fill property

Shape 레이어의 도형 내부 영역에 대한 채우기 설정을 가져오거나 설정합니다.

```csharp
public IFillSettings Fill { get; set; }
```

## 예제

다음 코드는 ShapeLayer의 Fill 속성을 보여줍니다.

```csharp
[C#]

string srcFile = "ShapeInternalSolid.psd";
string outFile = "ShapeInternalSolid.psd.out.psd";

using (PsdImage image = (PsdImage)Image.Load(
           srcFile,
           new PsdLoadOptions { LoadEffectsResource = true }))
{
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    ColorFillSettings fillSettings = (ColorFillSettings)shapeLayer.Fill;
    fillSettings.Color = Color.Red;

    shapeLayer.Update();

    image.Save(outFile);
}

// 저장된 변경 사항 확인
using (PsdImage image = (PsdImage)Image.Load(
           outFile,
           new PsdLoadOptions { LoadEffectsResource = true }))
{
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    ColorFillSettings fillSettings = (ColorFillSettings)shapeLayer.Fill;

    AssertAreEqual(Color.Red, fillSettings.Color);

    image.Save(outFile);
}

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}
```

### 또 보기

* interface [IFillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/ifillsettings/)
* class [ShapeLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


