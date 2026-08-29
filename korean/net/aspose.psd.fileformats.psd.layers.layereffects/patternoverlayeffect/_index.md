---
title: "PatternOverlayEffect 클래스"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.PatternOverlayEffect 클래스. 패턴 레이어 효과"
type: docs
weight: 2380
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/
---
{{< psd/tize >}}
## PatternOverlayEffect class

패턴 레이어 효과

```csharp
public class PatternOverlayEffect : ILayerEffect
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [BlendMode](../../aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/blendmode/) { get; set; } | 블렌드 모드를 가져오거나 설정합니다. |
| [EffectType](../../aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/effecttype/) { get; } | 효과 유형의 타입을 가져옵니다. |
| [IsVisible](../../aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/isvisible/) { get; set; } | 이 인스턴스가 표시되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [Opacity](../../aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/opacity/) { get; set; } | 불투명도를 가져오거나 설정합니다. |
| [Settings](../../aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/settings/) { get; set; } | 설정을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetEffectBounds](../../aspose.psd.fileformats.psd.layers.layereffects/patternoverlayeffect/geteffectbounds/)(Rectangle, int) | 입력 레이어 픽셀 경계를 기반으로 효과 픽셀의 경계를 계산하고 가져옵니다. |

## 예제

다음 코드는 패턴 오버레이 효과 지원을 보여줍니다.

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

string sourceFileName = "PatternOverlay.psd";
string exportPath = "PatternOverlayChanged.psd";

var newPattern = new int[]
{
    Color.Aqua.ToArgb(), Color.Red.ToArgb(), Color.Red.ToArgb(), Color.Aqua.ToArgb(),
    Color.Aqua.ToArgb(), Color.White.ToArgb(), Color.White.ToArgb(), Color.Aqua.ToArgb(),
};

var newPatternBounds = new Rectangle(0, 0, 4, 2);
var guid = Guid.NewGuid();
var newPatternName = "$$$/Presets/Patterns/Pattern=Some new pattern name\0";

var loadOptions = new PsdLoadOptions()
{
    LoadEffectsResource = true
};

using (var im = (PsdImage)Image.Load(sourceFileName, loadOptions))
{
    var patternOverlay = (PatternOverlayEffect)im.Layers[1].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Normal, patternOverlay.BlendMode);
    AssertAreEqual((byte)127, patternOverlay.Opacity);
    AssertAreEqual(true, patternOverlay.IsVisible);

    var settings = patternOverlay.Settings;
    AssertAreEqual(Color.Empty, settings.Color);
    AssertAreEqual(FillType.Pattern, settings.FillType);
    AssertAreEqual("85163837-eb9e-5b43-86fb-e6d5963ea29a".ToUpperInvariant(), settings.PatternId);
    AssertAreEqual("$$$/Presets/Patterns/OpticalSquares=Optical Squares", settings.PatternName);
    AssertAreEqual(null, settings.PointType);
    AssertAreEqual(100.00, settings.Scale);

    AssertAreEqual(true, settings.Linked);
    AssertIsTrue(Math.Abs(0 - settings.HorizontalOffset) < 0.001, "Horizontal offset is incorrect");
    AssertIsTrue(Math.Abs(0 - settings.VerticalOffset) < 0.001, "Vertical offset is incorrect");

    // 편집 테스트
    settings.Color = Color.Green;

    patternOverlay.Opacity = 193;
    patternOverlay.BlendMode = BlendMode.Difference;
    settings.HorizontalOffset = 15;
    settings.VerticalOffset = 11;

    settings.PatternName = newPatternName;
    settings.PatternId = guid.ToString();
    settings.PatternData = newPattern;
    settings.PatternWidth = newPatternBounds.Width;
    settings.PatternHeight = newPatternBounds.Height;
    
    im.Save(exportPath);
}

// 편집 후 테스트 파일
using (var im = (PsdImage)Image.Load(exportPath, loadOptions))
{
    var patternOverlay = (PatternOverlayEffect)im.Layers[1].BlendingOptions.Effects[0];

    AssertAreEqual(BlendMode.Difference, patternOverlay.BlendMode);
    AssertAreEqual((byte)193, patternOverlay.Opacity);
    AssertAreEqual(true, patternOverlay.IsVisible);

    var fillSettings = patternOverlay.Settings;
    AssertAreEqual(Color.Empty, fillSettings.Color);
    AssertAreEqual(FillType.Pattern, fillSettings.FillType);

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
    AssertAreEqual(newPattern, resource.Patterns[1].PatternData);
    AssertAreEqual(newPatternBounds, new Rectangle(0, 0, resource.Patterns[1].Width, resource.Patterns[1].Height));
    AssertAreEqual(guid.ToString().ToUpperInvariant(), resource.Patterns[1].PatternId);
    AssertAreEqual(newPatternName, resource.Patterns[1].Name + "\0");
}
```

### 또 보기

* interface [ILayerEffect](../ilayereffect/)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../)


