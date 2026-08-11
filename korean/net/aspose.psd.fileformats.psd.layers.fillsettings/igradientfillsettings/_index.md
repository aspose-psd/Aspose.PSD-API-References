---
title: "인터페이스 IGradientFillSettings"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.FillSettings.IGradientFillSettings 인터페이스. 그라디언트 채우기 설정을 위한 기본 인터페이스"
type: docs
weight: 2130
url: /ko/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---
{{< psd/tize >}}
## IGradientFillSettings interface

그라디언트 채우기 설정을 위한 기본 인터페이스.

```csharp
public interface IGradientFillSettings : IFillSettings
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/alignwithlayer/) { get; set; } | 레이어와 정렬되는지를 나타내는 값을 가져오거나 설정합니다 [align with layer]. |
| [Angle](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/angle/) { get; set; } | 각도를 가져오거나 설정합니다. |
| [Dither](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/dither/) { get; set; } | `IGradientFillSettings`가 디더링인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [Gradient](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradient/) { get; set; } | 특정 그라디언트 정의 인스턴스(솔리드/노이즈)를 가져오거나 설정합니다. |
| [GradientType](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradienttype/) { get; set; } | 그라디언트의 유형을 가져오거나 설정합니다. |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/horizontaloffset/) { get; set; } | 수평 오프셋을 가져오거나 설정합니다. |
| [InterpolationMethod](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/interpolationmethod/) { get; set; } | 그라디언트에 대한 보간 방법을 가져오거나 설정합니다. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/reverse/) { get; set; } | `IGradientFillSettings`가 역방향인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/) { get; set; } | **정규화된** 그라디언트 스케일(퍼센트)을 가져오거나 설정합니다. |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/verticaloffset/) { get; set; } | 수직 오프셋을 가져오거나 설정합니다. |

## 예제

다음 예제는 Gradient FillLayer 지원 및 IGradientFillSettings 편집 옵션을 보여줍니다..

```csharp
[C#]

string sourceFileName = "ComplexGradientFillLayer.psd";
string outputFile = "ComplexGradientFillLayer_output.psd";
var im = (PsdImage)Image.Load(sourceFileName);
using (im)
{
    foreach (var layer in im.Layers)
    {
        if (layer is FillLayer)
        {
            var fillLayer = (FillLayer)layer;
            if (fillLayer.FillSettings.FillType != FillType.Gradient)
            {
                throw new Exception("Wrong Fill Layer");
            }
            var settings = (GradientFillSettings)fillLayer.FillSettings;
            var solidGradient = (SolidGradient)settings.Gradient;
            if (
             Math.Abs(settings.Angle - 45) > 0.25 ||
             settings.Dither != true ||
             settings.AlignWithLayer != false ||
             settings.Reverse != false ||
             Math.Abs(settings.HorizontalOffset - (-39)) > 0.25 ||
             Math.Abs(settings.VerticalOffset - (-5)) > 0.25 ||
             solidGradient.TransparencyPoints.Length != 3 ||
             solidGradient.ColorPoints.Length != 2 ||
             Math.Abs(100.0 - solidGradient.TransparencyPoints[0].Opacity) > 0.25 ||
             solidGradient.TransparencyPoints[0].Location != 0 ||
             solidGradient.TransparencyPoints[0].MedianPointLocation != 50 ||
             solidGradient.ColorPoints[0].Color != Color.FromArgb(203, 64, 140) ||
             solidGradient.ColorPoints[0].Location != 0 ||
             solidGradient.ColorPoints[0].MedianPointLocation != 50)
            {
                throw new Exception("Gradient Fill was not read correctly");
            }
            settings.Angle = 0.0;
            settings.Dither = false;
            settings.AlignWithLayer = true;
            settings.Reverse = true;
            settings.HorizontalOffset = 25;
            settings.VerticalOffset = -15;
            var colorPoints = new List<IGradientColorPoint>(solidGradient.ColorPoints);
            var transparencyPoints = new List<IGradientTransparencyPoint>(solidGradient.TransparencyPoints);
            colorPoints.Add(new GradientColorPoint()
            {
                Color = Color.Violet,
                Location = 4096,
                MedianPointLocation = 75
            });
            colorPoints[1].Location = 3000;
            transparencyPoints.Add(new GradientTransparencyPoint()
            {
                Opacity = 80.0,
                Location = 4096,
                MedianPointLocation = 25
            });
            transparencyPoints[2].Location = 3000;
            solidGradient.ColorPoints = colorPoints.ToArray();
            solidGradient.TransparencyPoints = transparencyPoints.ToArray();
            fillLayer.Update();
            im.Save(outputFile, new PsdOptions(im));
            break;
        }
    }
}
```

### 또 보기

* interface [IFillSettings](../ifillsettings/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../)


