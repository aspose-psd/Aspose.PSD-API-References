---
title: "IGradientFillSettings.Scale"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "IGradientFillSettings 속성. 정규화된 그라디언트 스케일을 백분율로 가져오거나 설정합니다."
type: docs
weight: 90
url: /ko/net/aspose.psd.fileformats.psd.layers.fillsettings/igradientfillsettings/scale/
---
{{< psd/tize >}}
## IGradientFillSettings.Scale property

**정규화된** 그라디언트 스케일(퍼센트)을 가져오거나 설정합니다.

```csharp
public int Scale { get; set; }
```

### Property Value

스케일입니다.

## 예제

다음 예제는 Scale 속성을 사용하여 그라디언트가 적용된 FillLayer를 스케일링하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFileName = "FillLayerGradient.psd";
string output = "scaledImage.png";

using (var image = (PsdImage)Image.Load(sourceFileName))
{
    // FillLayer 가져오기
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
    fillLayer.Update(); // Updates pixels data

    image.Save(output, new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 또 보기

* interface [IGradientFillSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.FillSettings](../../../aspose.psd.fileformats.psd.layers.fillsettings/)
* assembly [Aspose.PSD](../../../)


