---
title: IGradientFillSettings.Scale
second_title: .NET API 참조용 Aspose.PSD
description: IGradientFillSettings 재산. 배율을 가져오거나 설정합니다.
type: docs
weight: 100
url: /ko/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
## IGradientFillSettings.Scale property

배율을 가져오거나 설정합니다.

```csharp
public int Scale { get; set; }
```

### 자산 가치

저울.

### 예

다음 예제에서는 Scale 속성을 사용하여 Gradient로 FillLayer의 크기를 조정하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // 채우기 레이어 가져오기
    FillLayer fillLayer = null;
    foreach (var layer in image.Layers)
    {
        fillLayer = layer as FillLayer;
        if (fillLayer != null)
        {
            break;
        }
    }

    var settings = fillLayer.FillSettings as IGradientFillSettings;

    // 스케일 값 업데이트
    settings.Scale = 200;
    fillLayer.Update(); // 픽셀 데이터 업데이트

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 또한보십시오

* interface [IGradientFillSettings](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../igradientfillsettings/)
* 집회 [Aspose.PSD](../../../)


