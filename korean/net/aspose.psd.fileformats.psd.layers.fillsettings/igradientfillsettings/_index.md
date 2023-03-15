---
title: Interface IGradientFillSettings
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.FillSettings.IGradientFillSettings 상호 작용. 채우기 설정을 위한 기본 인터페이스
type: docs
weight: 2010
url: /ko/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/
---
## IGradientFillSettings interface

채우기 설정을 위한 기본 인터페이스

```csharp
public interface IGradientFillSettings : IFillSettings
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlignWithLayer](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/alignwithlayer/) { get; set; } | [레이어와 정렬]. 여부를 나타내는 값을 가져오거나 설정합니다. |
| [Angle](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/angle/) { get; set; } | 각도를 가져오거나 설정합니다. |
| [Color](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/color/) { get; set; } | 색상을 가져오거나 설정합니다. |
| [ColorPoints](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/colorpoints/) { get; set; } | 색상 포인트를 가져옵니다. |
| [Dither](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/dither/) { get; set; } | 이 여부를 나타내는 값을 가져오거나 설정합니다.`IGradientFillSettings` 디더입니다. |
| [GradientName](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradientname/) { get; set; } | 그라데이션의 이름을 가져오거나 설정합니다. |
| [GradientType](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/gradienttype/) { get; set; } | 그라데이션 유형을 가져오거나 설정합니다. |
| [HorizontalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/horizontaloffset/) { get; set; } | 수평 오프셋을 가져오거나 설정합니다. |
| [Reverse](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/reverse/) { get; set; } | 이 여부를 나타내는 값을 가져오거나 설정합니다.`IGradientFillSettings` 반대입니다. |
| [Scale](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/) { get; set; } | 배율을 가져오거나 설정합니다. |
| [TransparencyPoints](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/transparencypoints/) { get; set; } | 투명도 포인트를 가져옵니다. |
| [VerticalOffset](../../aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/verticaloffset/) { get; set; } | 수직 오프셋을 가져오거나 설정합니다. |

### 예

다음 예제는 Gradient FillLayer 지원 및 IGradientFillSettings 편집 옵션을 보여줍니다.

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
            var settings = (IGradientFillSettings)fillLayer.FillSettings;
            if (
             Math.Abs(settings.Angle - 45) > 0.25 ||
             settings.Dither != true ||
             settings.AlignWithLayer != false ||
             settings.Reverse != false ||
             Math.Abs(settings.HorizontalOffset - (-39)) > 0.25 ||
             Math.Abs(settings.VerticalOffset - (-5)) > 0.25 ||
             settings.TransparencyPoints.Length != 3 ||
             settings.ColorPoints.Length != 2 ||
             Math.Abs(100.0 - settings.TransparencyPoints[0].Opacity) > 0.25 ||
             settings.TransparencyPoints[0].Location != 0 ||
             settings.TransparencyPoints[0].MedianPointLocation != 50 ||
             settings.ColorPoints[0].Color != Color.FromArgb(203, 64, 140) ||
             settings.ColorPoints[0].Location != 0 ||
             settings.ColorPoints[0].MedianPointLocation != 50)
            {
                throw new Exception("Gradient Fill was not read correctly");
            }
            settings.Angle = 0.0;
            settings.Dither = false;
            settings.AlignWithLayer = true;
            settings.Reverse = true;
            settings.HorizontalOffset = 25;
            settings.VerticalOffset = -15;
            var colorPoints = new List<IGradientColorPoint>(settings.ColorPoints);
            var transparencyPoints = new List<IGradientTransparencyPoint>(settings.TransparencyPoints);
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
            settings.ColorPoints = colorPoints.ToArray();
            settings.TransparencyPoints = transparencyPoints.ToArray();
            fillLayer.Update();
            im.Save(outputFile, new PsdOptions(im));
            break;
        }
    }
}
```

### 또한보십시오

* interface [IFillSettings](../ifillsettings/)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../aspose.psd.fileformats.psd.layers.fillsettings/)
* 집회 [Aspose.PSD](../../)


