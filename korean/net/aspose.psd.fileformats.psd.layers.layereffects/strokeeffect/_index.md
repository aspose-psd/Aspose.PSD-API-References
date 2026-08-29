---
title: "StrokeEffect 클래스"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.StrokeEffect 클래스. PSD 레이어용 Adobe Photoshop 스트로크 효과"
type: docs
weight: 2390
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/
---
{{< psd/tize >}}
## StrokeEffect class

PSD 레이어용 Adobe® Photoshop® 스트로크 효과입니다.

```csharp
public class StrokeEffect : ILayerEffect
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/blendmode/) { get; set; } | 블렌드 모드를 가져오거나 설정합니다. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/effecttype/) { get; } | 효과 유형을 가져옵니다. |
| [FillSettings](../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/fillsettings/) { get; set; } | 채우기 설정을 가져오거나 설정합니다. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/isvisible/) { get; set; } | 이 인스턴스가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/opacity/) { get; set; } | 불투명도를 가져오거나 설정합니다. |
| [Overprint](../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/overprint/) { get; set; } | 이 `StrokeEffect`가 현재 레이어 내용과 스트로크를 혼합할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [Position](../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/position/) { get; set; } | 스트로크 효과의 위치를 가져오거나 설정하여 스트로크를 PSD 레이어 내용에 맞게 정렬합니다. 값은 Inside(스트로크를 레이어 내용 내부에 그리기), Outside(레이어 내용 주변에 그리기), Center(내부와 외부 모두에 스트로크를 그리기) 중 하나가 될 수 있습니다. |
| [Size](../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/size/) { get; set; } | 스트로크 효과의 너비를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/geteffectbounds/)(Rectangle, int) | 입력 레이어 픽셀 경계를 기반으로 효과 픽셀의 경계를 계산하고 가져옵니다. |

## 예제

다음 코드 예제는 컬러 채우기를 사용한 스트로크 효과 렌더링을 보여줍니다.

```csharp
[C#]

// 내보내기를 위해 컬러 채우기를 사용한 스트로크 효과 렌더링을 구현합니다.
string sourceFileName = "StrokeComplex.psd";
string exportPath = "StrokeComplexRendering.psd";
string exportPathPng = "StrokeComplexRendering.png";
var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true
};
using (var im = (PsdImage)Image.Load(sourceFileName, loadOptions))
{
    for (int i = 0; i < im.Layers.Length; i++)
    {
        var effect = (StrokeEffect)im.Layers[i].BlendingOptions.Effects[0];
        var settings = (ColorFillSettings)effect.FillSettings;
        settings.Color = Color.DeepPink;
    }

    // psd 저장
    im.Save(exportPath, new PsdOptions());
    // png 저장
    im.Save(exportPathPng, new PngOptions()
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

다음 코드는 채우기 유형 - 색상인 스트로크 효과 레이어 지원을 보여줍니다.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

var sourceFileName = "Stroke.psd";
var exportPath = "StrokeColorChanged.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true
};

using (var im = (PsdImage)Image.Load(sourceFileName, loadOptions))
{
    var colorStroke = (StrokeEffect)im.Layers[1].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Normal, colorStroke.BlendMode);
    AssertAreEqual((byte)255, colorStroke.Opacity);
    AssertAreEqual(true, colorStroke.IsVisible);

    var fillSettings = (ColorFillSettings)colorStroke.FillSettings;
    AssertAreEqual(Color.Black, fillSettings.Color);
    AssertAreEqual(FillType.Color, fillSettings.FillType);

    fillSettings.Color = Color.Yellow;

    colorStroke.Opacity = 127;
    colorStroke.BlendMode = BlendMode.Color;
    im.Save(exportPath);
}

// 편집 후 테스트 파일
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var colorStroke = (StrokeEffect)im.Layers[1].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Color, colorStroke.BlendMode);
    AssertAreEqual((byte)127, colorStroke.Opacity);
    AssertAreEqual(true, colorStroke.IsVisible);

    var fillSettings = (ColorFillSettings)colorStroke.FillSettings;
    AssertAreEqual(Color.Yellow, fillSettings.Color);
    AssertAreEqual(FillType.Color, fillSettings.FillType);
}
```

다음 코드는 채우기 유형이 Pattern인 스트로크 효과 레이어 지원을 보여줍니다.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (expected is Array && actual is Array)
    {
        Array array1 = (Array)expected;
        Array array2 = (Array)actual;
        AssertAreEqual(array1.Length, array2.Length);

        for (int i = 0; i < array1.Length; i++)
        {
            AssertAreEqual(array1.GetValue(i), array2.GetValue(i));
        }
        return;
    }

    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

string sourceFileName = "Stroke.psd";
string exportPath = "StrokePatternChanged.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true
};

// 새 데이터 준비 중
var newPattern = new int[]
{
    Color.Aqua.ToArgb(), Color.Red.ToArgb(), Color.Red.ToArgb(), Color.Aqua.ToArgb(),
    Color.Aqua.ToArgb(), Color.White.ToArgb(), Color.White.ToArgb(), Color.Aqua.ToArgb(),
    Color.Aqua.ToArgb(), Color.White.ToArgb(), Color.White.ToArgb(), Color.Aqua.ToArgb(),
    Color.Aqua.ToArgb(), Color.Red.ToArgb(), Color.Red.ToArgb(), Color.Aqua.ToArgb(),
};

var newPatternBounds = new Rectangle(0, 0, 4, 4);
var guid = Guid.NewGuid();

using (var im = (PsdImage)Image.Load(sourceFileName, loadOptions))
{
    var patternStroke = (StrokeEffect)im.Layers[3].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Normal, patternStroke.BlendMode);
    AssertAreEqual((byte)255, patternStroke.Opacity);
    AssertAreEqual(true, patternStroke.IsVisible);

    var fillSettings = (PatternFillSettings)patternStroke.FillSettings;
    AssertAreEqual(FillType.Pattern, fillSettings.FillType);

    patternStroke.Opacity = 127;
    patternStroke.BlendMode = BlendMode.Color;

    PattResource resource;
    foreach (var globalLayerResource in im.GlobalLayerResources)
    {
        if (globalLayerResource is PattResource)
        {
            resource = (PattResource)globalLayerResource;
            resource.Patterns[0].PatternId = guid.ToString();
            resource.Patterns[0].Name = "$$$/Presets/Patterns/HorizontalLine1=Horizontal Line 9\0";

            resource.Patterns[0].SetPattern(newPattern, newPatternBounds);
        }
    }

    ((PatternFillSettings)patternStroke.FillSettings).PatternName = "$$$/Presets/Patterns/HorizontalLine1=Horizontal Line 9\0";

    ((PatternFillSettings)patternStroke.FillSettings).PatternId = guid.ToString() + "\0";
    im.Save(exportPath);
}

// 편집 후 테스트 파일
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var patternStroke = (StrokeEffect)im.Layers[3].BlendingOptions.Effects[0];

    PattResource resource = null;
    foreach (var globalLayerResource in im.GlobalLayerResources)
    {
        if (globalLayerResource is PattResource)
        {
            resource = (PattResource)globalLayerResource;
        }
    }

    if (resource == null)
    {
        throw new Exception("PattResource not found");
    }

    // 패턴 데이터 확인
    AssertAreEqual(newPattern, resource.Patterns[0].PatternData);
    AssertAreEqual(newPatternBounds, new Rectangle(0, 0, resource.Patterns[0].Width, resource.Patterns[0].Height));
    AssertAreEqual(guid.ToString().ToUpperInvariant(), resource.Patterns[0].PatternId);

    AssertAreEqual(BlendMode.Color, patternStroke.BlendMode);
    AssertAreEqual((byte)127, patternStroke.Opacity);
    AssertAreEqual(true, patternStroke.IsVisible);

    var fillSettings = (PatternFillSettings)patternStroke.FillSettings;

    AssertAreEqual(FillType.Pattern, fillSettings.FillType);
}
```

다음 코드는 채우기 유형이 Gradient인 스트로크 효과 레이어 지원을 보여줍니다.

```csharp
[C#]

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}
void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new FormatException(message ?? "Objects are not equal.");
    }
}

string sourceFileName = "Stroke.psd";
string exportPath = "StrokeGradientChanged.psd";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true
};

using (var im = (PsdImage)Image.Load(sourceFileName, loadOptions))
{
    var gradientStroke = (StrokeEffect)im.Layers[2].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Normal, gradientStroke.BlendMode);
    AssertAreEqual((byte)255, gradientStroke.Opacity);
    AssertAreEqual(true, gradientStroke.IsVisible);

    var fillSettings = (GradientFillSettings)gradientStroke.FillSettings;
    AssertAreEqual(FillType.Gradient, fillSettings.FillType);
    AssertAreEqual(true, fillSettings.AlignWithLayer);
    AssertAreEqual(GradientType.Linear, fillSettings.GradientType);
    AssertIsTrue(Math.Abs(90 - fillSettings.Angle) < 0.001, "Angle is incorrect");
    AssertAreEqual(false, fillSettings.Dither);
    AssertIsTrue(Math.Abs(0 - fillSettings.HorizontalOffset) < 0.001, "Horizontal offset is incorrect");
    AssertIsTrue(Math.Abs(0 - fillSettings.VerticalOffset) < 0.001, "Vertical offset is incorrect");
    AssertAreEqual(false, fillSettings.Reverse);

    // 색상 포인트
    var solidGradient = (SolidGradient)fillSettings.Gradient;
    var colorPoints = solidGradient.ColorPoints;
    AssertAreEqual(2, colorPoints.Length);

    AssertAreEqual(Color.Black, colorPoints[0].Color);
    AssertAreEqual(0, colorPoints[0].Location);
    AssertAreEqual(50, colorPoints[0].MedianPointLocation);

    AssertAreEqual(Color.White, colorPoints[1].Color);
    AssertAreEqual(4096, colorPoints[1].Location);
    AssertAreEqual(50, colorPoints[1].MedianPointLocation);

    // 투명도 포인트
    var transparencyPoints = solidGradient.TransparencyPoints;
    AssertAreEqual(2, transparencyPoints.Length);

    AssertAreEqual(0, transparencyPoints[0].Location);
    AssertAreEqual(50, transparencyPoints[0].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[0].Opacity);

    AssertAreEqual(4096, transparencyPoints[1].Location);
    AssertAreEqual(50, transparencyPoints[1].MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoints[1].Opacity);

    // 편집 테스트
    gradientStroke.Opacity = 127;
    gradientStroke.BlendMode = BlendMode.Color;

    fillSettings.AlignWithLayer = false;
    fillSettings.GradientType = GradientType.Radial;
    fillSettings.Angle = 45;
    fillSettings.Dither = true;
    fillSettings.HorizontalOffset = 15;
    fillSettings.VerticalOffset = 11;
    fillSettings.Reverse = true;

    // 새 색상 포인트 추가
    var colorPoint = solidGradient.AddColorPoint();
    colorPoint.Color = Color.Green;
    colorPoint.Location = 4096;
    colorPoint.MedianPointLocation = 75;

    // 이전 포인트 위치 변경
    solidGradient.ColorPoints[1].Location = 1899;

    // 새 투명도 포인트 추가
    var transparencyPoint = solidGradient.AddTransparencyPoint();
    transparencyPoint.Opacity = 25;
    transparencyPoint.MedianPointLocation = 25;
    transparencyPoint.Location = 4096;

    // 이전 투명도 포인트 위치 변경
    solidGradient.TransparencyPoints[1].Location = 2411;

    im.Save(exportPath);
}

// 편집 후 테스트 파일
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var gradientStroke = (StrokeEffect)im.Layers[2].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Color, gradientStroke.BlendMode);
    AssertAreEqual((byte)127, gradientStroke.Opacity);
    AssertAreEqual(true, gradientStroke.IsVisible);

    var fillSettings = (GradientFillSettings)gradientStroke.FillSettings;
    var solidGradient = (SolidGradient)fillSettings.Gradient;
    AssertAreEqual(FillType.Gradient, fillSettings.FillType);

    // 색상 포인트 확인
    AssertAreEqual(3, solidGradient.ColorPoints.Length);

    var point = solidGradient.ColorPoints[0];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.Black, point.Color);
    AssertAreEqual(0, point.Location);

    point = solidGradient.ColorPoints[1];
    AssertAreEqual(50, point.MedianPointLocation);
    AssertAreEqual(Color.White, point.Color);
    AssertAreEqual(1899, point.Location);

    point = solidGradient.ColorPoints[2];
    AssertAreEqual(75, point.MedianPointLocation);
    AssertAreEqual(Color.Green, point.Color);
    AssertAreEqual(4096, point.Location);

    // 투명 포인트 확인
    AssertAreEqual(3, solidGradient.TransparencyPoints.Length);

    var transparencyPoint = solidGradient.TransparencyPoints[0];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoint.Opacity);
    AssertAreEqual(0, transparencyPoint.Location);

    transparencyPoint = solidGradient.TransparencyPoints[1];
    AssertAreEqual(50, transparencyPoint.MedianPointLocation);
    AssertAreEqual(100.00, transparencyPoint.Opacity);
    AssertAreEqual(2411, transparencyPoint.Location);

    transparencyPoint = solidGradient.TransparencyPoints[2];
    AssertAreEqual(25, transparencyPoint.MedianPointLocation);
    AssertAreEqual(25.00, transparencyPoint.Opacity);
    AssertAreEqual(4096, transparencyPoint.Location);
}
```

### 또 보기

* interface [ILayerEffect](../ilayereffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


