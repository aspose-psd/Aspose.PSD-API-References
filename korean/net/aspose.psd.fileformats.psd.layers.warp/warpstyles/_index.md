---
title: "열거형 WarpStyles"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpStyles 열거형. 지원되는 워프 스타일 유형"
type: docs
weight: 4020
url: /ko/net/aspose.psd.fileformats.psd.layers.warp/warpstyles/
---
{{< psd/tize >}}
## WarpStyles enumeration

지원되는 워프 스타일 유형

```csharp
public enum WarpStyles
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | `0` | 레이어가 변형되지 않을 때 스타일이 설정됩니다 |
| Custom | `1` | 점의 임의 이동을 가진 스타일 |
| Arc | `2` | 워프의 아크 스타일 |
| ArcUpper | `3` | 워프의 상부 아크 스타일 |
| ArcLower | `4` | 워프의 하부 아크 스타일 |
| Arch | `5` | 워프의 아치 스타일 |
| Bulge | `6` | 워프의 돌출 스타일 |
| Flag | `7` | 워프의 플래그 스타일 |
| Fish | `8` | 워프의 물고기 스타일 |
| Rise | `9` | 워프의 상승 스타일 |
| Wave | `10` | 워프의 파동 스타일 |
| Twist | `11` | 워프의 비틀림 유형 |
| Squeeze | `12` | 워프의 압축 유형 |
| Inflate | `13` | 워프의 팽창 유형 |

## 예제

다음 코드는 WarpSettings를 조작하여 SmartObjectLayer와 TexLayer에 워프 변환을 적용하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "smart_without_warp.psd";

var opt = new PsdLoadOptions()
{
    LoadEffectsResource = true,
    AllowWarpRepaint = true
};

string[] outputImageFile = new string[4];
string[] outputPsdFile = new string[4];

for (int caseIndex = 0; caseIndex < outputImageFile.Length; caseIndex++)
{
    outputImageFile[caseIndex] = "export_" + caseIndex + ".png";
    outputPsdFile[caseIndex] = "export_" + caseIndex + ".psd";

    using (PsdImage img = (PsdImage)Image.Load(sourceFile, opt))
    {
        foreach (Layer layer in img.Layers)
        {
            if (layer is SmartObjectLayer)
            {
                var smartLayer = (SmartObjectLayer)layer;
                smartLayer.WarpSettings = GetWarpSettingsByIndex(smartLayer.WarpSettings, caseIndex);
            }

            if (layer is TextLayer)
            {
                var textLayer = (TextLayer)layer;

                if (caseIndex != 3)
                {
                    textLayer.WarpSettings = GetWarpSettingsByIndex(textLayer.WarpSettings, caseIndex);
                }
            }
        }

        img.Save(outputPsdFile[caseIndex], new PsdOptions());
    }

    using (PsdImage img = (PsdImage)Image.Load(outputPsdFile[caseIndex], opt))
    {
        img.Save(outputImageFile[caseIndex],
            new PngOptions() { CompressionLevel = 9, ColorType = PngColorType.TruecolorWithAlpha });
    }
}

WarpSettings GetWarpSettingsByIndex(WarpSettings warpParams, int caseIndex)
{
    switch (caseIndex)
    {
        case 0:
            warpParams.Style = WarpStyles.Rise;
            warpParams.Rotate = WarpRotates.Horizontal;
            warpParams.Value = 20;
            break;
        case 1:
            warpParams.Style = WarpStyles.Rise;
            warpParams.Rotate = WarpRotates.Vertical;
            warpParams.Value = 10;
            break;
        case 2:
            warpParams.Style = WarpStyles.Flag;
            warpParams.Rotate = WarpRotates.Horizontal;
            warpParams.Value = 30;
            break;
        case 3:
            warpParams.Style = WarpStyles.Custom;
            warpParams.MeshPoints[2].Y += 70;
            break;
    }

    return warpParams;
}
```

### 또 보기

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


