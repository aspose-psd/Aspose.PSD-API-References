---
title: Enum StrokePosition
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Psd.Layers.LayerEffects.StrokePosition 열거형. 위치 설정은 획이 적용되는 레이어에 대한 획의 정렬을 제어합니다.StrokeEffect .
type: docs
weight: 2200
url: /ko/net/aspose.psd.fileformats.psd.layers.layereffects/strokeposition/
---
## StrokePosition enumeration

위치 설정은 획이 적용되는 레이어에 대한 획의 정렬을 제어합니다.[`StrokeEffect`](../strokeeffect/) .

```csharp
public enum StrokePosition : short
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Inside | `0` | 획은 모양의 가장자리에서 만들어지고 개체의 중심까지 안쪽으로 커집니다. |
| Center | `1` | 획은 모양의 가장자리에서 만들어지고 안쪽과 바깥쪽으로 모두 커집니다. |
| Outside | `2` | 획은 모양의 가장자리에서 만들어지고 객체에서 멀어지면서 바깥쪽으로 커집니다. |

### 예

이 예는 색상, 그라데이션 또는 패턴과 같은 다양한 유형의 채우기로 획 효과를 추가하는 기능을 보여줍니다.

```csharp
[C#]

using (var psdImage = (PsdImage)Image.Load(srcFile, new PsdLoadOptions() { LoadEffectsResource = true }))
{
    StrokeEffect strokeEffect;
    IColorFillSettings colorFillSettings;
    IGradientFillSettings gradientFillSettings;
    IPatternFillSettings patternFillSettings;

    // 1. 내부 위치에 색상 채우기를 추가합니다.
    strokeEffect = psdImage.Layers[1].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Inside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 2. 외부 위치에 색상 채우기를 추가합니다.
    strokeEffect = psdImage.Layers[2].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Outside;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 3. Center 위치에 색상 채우기를 추가합니다.
    strokeEffect = psdImage.Layers[3].BlendingOptions.AddStroke(FillType.Color);
    strokeEffect.Size = 7;
    strokeEffect.Position = StrokePosition.Center;
    colorFillSettings = strokeEffect.FillSettings as IColorFillSettings;
    colorFillSettings.Color = Color.Green;

    // 4. 내부 위치에 그라디언트 채우기를 추가합니다.
    strokeEffect = psdImage.Layers[4].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = false;
    gradientFillSettings.Angle = 90;

    // 5. 외부 위치에 그라데이션 채우기를 추가합니다.
    strokeEffect = psdImage.Layers[5].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Outside;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 90;

    // 6. 위치 중심에 그라데이션 채우기를 추가합니다.
    strokeEffect = psdImage.Layers[6].BlendingOptions.AddStroke(FillType.Gradient);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Center;
    gradientFillSettings = strokeEffect.FillSettings as IGradientFillSettings;
    gradientFillSettings.AlignWithLayer = true;
    gradientFillSettings.Angle = 0;

    // 7. 내부 위치에 패턴 채우기를 추가합니다.
    strokeEffect = psdImage.Layers[7].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 5;
    strokeEffect.Position = StrokePosition.Inside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 200;

    // 8. 외부 위치에 패턴 채우기를 추가합니다.
    strokeEffect = psdImage.Layers[8].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Outside;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 100;

    // 9. Center 위치에 패턴 채우기를 추가합니다.
    strokeEffect = psdImage.Layers[9].BlendingOptions.AddStroke(FillType.Pattern);
    strokeEffect.Size = 10;
    strokeEffect.Position = StrokePosition.Center;
    patternFillSettings = strokeEffect.FillSettings as IPatternFillSettings;
    patternFillSettings.Scale = 75;

    psdImage.Save(outputFilePng, new PngOptions());
}
```

### 또한보십시오

* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.LayerEffects](../../aspose.psd.fileformats.psd.layers.layereffects/)
* 집회 [Aspose.PSD](../../)


