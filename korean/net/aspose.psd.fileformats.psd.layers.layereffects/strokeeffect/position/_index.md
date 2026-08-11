---
title: "StrokeEffect.Position"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "StrokeEffect 속성. 스트로크 효과의 위치를 가져오거나 설정하여 스트로크를 PSD 레이어 콘텐츠에 맞게 정렬합니다. 값은 Inside를 선택하면 PSD 레이어 콘텐츠 내부에 스트로크를 그리며, Outside를 선택하면 PSD 레이어 콘텐츠 주변에 스트로크를 그리고, Center를 선택하면 스트로크를 내부와 외부 모두에 그립니다."
type: docs
weight: 70
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/strokeeffect/position/
---
{{< psd/tize >}}
## StrokeEffect.Position property

스트로크 효과의 위치를 가져오거나 설정하여 스트로크를 PSD 레이어 내용에 맞게 정렬합니다. 값은 Inside(스트로크를 레이어 내용 내부에 그리기), Outside(레이어 내용 주변에 그리기), Center(내부와 외부 모두에 스트로크를 그리기) 중 하나가 될 수 있습니다.

```csharp
public StrokePosition Position { get; set; }
```

## 예제

이 예제는 Color, Gradient 또는 Pattern과 같은 다양한 채우기 유형으로 스트로크 효과를 추가하는 기능을 보여줍니다.

```csharp
[C#]

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    StrokeEffect strokeEffect;
    IColorFillSettings colorFillSettings;
    IGradientFillSettings gradientFillSettings;
    IPatternFillSettings patternFillSettings;

    // 1. Color 채우기를 추가합니다, 위치 Inside
    strokeEffect = psdImage.Layers[1].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Inside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 2. Color 채우기를 추가합니다, 위치 Outside
    strokeEffect = psdImage.Layers[2].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Outside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 3. Color 채우기를 추가합니다, 위치 Center
    strokeEffect = psdImage.Layers[3].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Center;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 4. Gradient 채우기를 추가합니다, 위치 Inside
    strokeEffect = psdImage.Layers[4].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Angle = 90;

    // 5. Gradient 채우기를 추가합니다, 위치 Outside
    strokeEffect = psdImage.Layers[5].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Outside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 90;

    // 6. Gradient 채우기를 추가합니다, 위치 Center
    strokeEffect = psdImage.Layers[6].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Center;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 0;

    // 7. Pattern 채우기를 추가합니다, 위치 Inside
    strokeEffect = psdImage.Layers[7].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 200;

    // 8. Pattern 채우기를 추가합니다, 위치 Outside
    strokeEffect = psdImage.Layers[8].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Outside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 100;

    // 9. Pattern 채우기를 추가합니다, 위치 Center
    strokeEffect = psdImage.Layers[9].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Center;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 75;

    psdImage.Save(outputFilePng, new PngOptions());
}
```

### 또 보기

* enum [StrokePosition](../../strokeposition/)
* class [StrokeEffect](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../../aspose.psd.fileformats.psd.layers.layereffects/)
* assembly [Aspose.PSD](../../../)


