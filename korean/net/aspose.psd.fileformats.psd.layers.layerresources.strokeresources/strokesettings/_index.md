---
title: "Class StrokeSettings"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources.StrokeSettings class. 도형의 스트로크 설정"
type: docs
weight: 3420
url: /ko/net/aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/
---
{{< psd/tize >}}
## StrokeSettings class

도형의 스트로크 설정.

```csharp
public class StrokeSettings : IStrokeSettings
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [StrokeSettings](strokesettings/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Enabled](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/enabled/) { get; set; } | 스트로크가 활성화되는지를 가져오거나 설정합니다. |
| [Fill](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/fill/) { get; set; } | 스트로크의 채우기 설정을 가져오거나 설정합니다. |
| [LineAlignment](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/linealignment/) { get; set; } | 스트로크 스타일 라인 정렬을 가져오거나 설정합니다. |
| [LineCap](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/linecap/) { get; set; } | 스트로크 라인 캡 유형을 가져오거나 설정합니다. |
| [LineDashSet](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/linedashset/) { get; set; } | 라인 대시 배열을 가져오거나 설정합니다. |
| [LineJoin](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/linejoin/) { get; set; } | 스트로크 라인 조인 유형을 가져오거나 설정합니다. |
| [Size](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/strokesettings/size/) { get; set; } | 스트로크 라인 너비를 가져오거나 설정합니다. |

## 예제

다음 코드는 도형 스트로크 렌더링 지원을 보여줍니다.

```csharp
[C#]

string sourceFile = "StrokeShapeTest.psd";
string outputFilePsd = "StrokeShapeTest.out.psd";
string outputFilePng = "StrokeShapeTest.out.png";

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    Layer layer = image.Layers[1];
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    ColorFillSettings fillSettings = (ColorFillSettings)shapeLayer.Fill;
    fillSettings.Color = Color.GreenYellow;
    shapeLayer.Update();

    ShapeLayer shapeLayer2 = (ShapeLayer)image.Layers[3];
    GradientFillSettings gradientSettings = (GradientFillSettings)shapeLayer2.Fill;
    SolidGradient solidGradient = (SolidGradient)gradientSettings.Gradient;
    gradientSettings.Dither = true;
    gradientSettings.Reverse = true;
    gradientSettings.AlignWithLayer = false;
    gradientSettings.Angle = 20;
    gradientSettings.Scale = 50;
    solidGradient.ColorPoints[0].Location = 100;
    solidGradient.ColorPoints[1].Location = 4000;
    solidGradient.TransparencyPoints[0].Location = 200;
    solidGradient.TransparencyPoints[1].Location = 3800;
    solidGradient.TransparencyPoints[0].Opacity = 90;
    solidGradient.TransparencyPoints[1].Opacity = 10;
    shapeLayer2.Update();

    ShapeLayer shapeLayer3 = (ShapeLayer)image.Layers[5];
    StrokeSettings strokeSettings = (StrokeSettings)shapeLayer3.Stroke;
    strokeSettings.Size = 15;
    ColorFillSettings strokeFillSettings = (ColorFillSettings)strokeSettings.Fill;
    strokeFillSettings.Color = Color.GreenYellow;
    shapeLayer3.Update();

    image.Save(outputFilePsd);
    image.Save(outputFilePng, new PngOptions());
}

// 변경된 데이터를 확인합니다.
using (PsdImage image = (PsdImage)Image.Load(outputFilePsd))
{
    ShapeLayer shapeLayer = (ShapeLayer)image.Layers[1];
    ColorFillSettings fillSettings = (ColorFillSettings)shapeLayer.Fill;
    AssertAreEqual(Color.GreenYellow, fillSettings.Color);

    ShapeLayer shapeLayer2 = (ShapeLayer)image.Layers[3];
    GradientFillSettings gradientSettings = (GradientFillSettings)shapeLayer2.Fill;
    SolidGradient solidGradient = (SolidGradient)gradientSettings.Gradient;
    AssertAreEqual(true, gradientSettings.Dither);
    AssertAreEqual(true, gradientSettings.Reverse);
    AssertAreEqual(false, gradientSettings.AlignWithLayer);
    AssertAreEqual(20.0, gradientSettings.Angle);
    AssertAreEqual(50, gradientSettings.Scale);
    AssertAreEqual(100, solidGradient.ColorPoints[0].Location);
    AssertAreEqual(4000, solidGradient.ColorPoints[1].Location);
    AssertAreEqual(200, solidGradient.TransparencyPoints[0].Location);
    AssertAreEqual(3800, solidGradient.TransparencyPoints[1].Location);
    AssertAreEqual(90.0, solidGradient.TransparencyPoints[0].Opacity);
    AssertAreEqual(10.0, solidGradient.TransparencyPoints[1].Opacity);

    ShapeLayer shapeLayer3 = (ShapeLayer)image.Layers[5];
    StrokeSettings strokeSettings = (StrokeSettings)shapeLayer3.Stroke;
    ColorFillSettings strokeFillSettings = (ColorFillSettings)strokeSettings.Fill;
    AssertAreEqual(15.0, strokeSettings.Size);
    AssertAreEqual(Color.GreenYellow, strokeFillSettings.Color);
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

* interface [IStrokeSettings](../istrokesettings/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerResources.StrokeResources](../../aspose.psd.fileformats.psd.layers.layerresources.strokeresources/)
* assembly [Aspose.PSD](../../)


