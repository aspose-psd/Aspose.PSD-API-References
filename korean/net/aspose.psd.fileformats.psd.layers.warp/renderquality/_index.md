---
title: "열거형 RenderQuality"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.RenderQuality 열거형. 워프의 렌더링 품질을 설명합니다."
type: docs
weight: 3990
url: /ko/net/aspose.psd.fileformats.psd.layers.warp/renderquality/
---
{{< psd/tize >}}
## RenderQuality enumeration

워프의 렌더링 품질을 설명합니다.

```csharp
public enum RenderQuality
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Turbo | `4` | 가장 빠른 옵션이지만 품질이 저하됩니다. |
| VeryFast | `18` | 빠른 처리가 필요하면 작은 곡률에 적합할 수 있습니다. |
| Fast | `35` | 품질이 약간 감소하지만 렌더링을 더 빠르게 할 수 있습니다. |
| Normal | `60` | 대부분의 곡률에 권장되는 값 |
| Good | `130` | 표준 품질보다 높고 속도는 느립니다. 강한 왜곡에 권장됩니다. |
| Excellent | `260` | 가장 느린 옵션입니다. 강한 왜곡 및 고해상도에 권장됩니다. |

## 예제

다음 코드는 WarpSettings.RenderQuality 속성을 사용하여 워프 변형을 구성하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFile = "Warping.psd";
List<string> outputFiles = new List<string>();

PsdLoadOptions loadOptions = new PsdLoadOptions() { LoadEffectsResource = true, AllowWarpRepaint = true };

RenderQuality[] qualityValues = { RenderQuality.Turbo, RenderQuality.Fast, RenderQuality.Normal, RenderQuality.Excellent };

for (int i = 0; i < 4; i++)
{
    using (var psdImage = (PsdImage)Image.Load(sourceFile, loadOptions))
    {
        // Smart Layer에서 WarpSettings를 가져옵니다.
        WarpSettings warpSettings = ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings;

        // 워프 처리 영역의 크기를 설정합니다.
        warpSettings.RenderQuality = qualityValues[i];
        ((SmartObjectLayer)psdImage.Layers[1]).WarpSettings = warpSettings;

        string outputFile = "export" + qualityValues[i].ToString() + ".png";
        outputFiles.Add(outputFile);

        // 여기서는 오류가 없어야 합니다.
        psdImage.Save(outputFile, new PngOptions { ColorType = PngColorType.TruecolorWithAlpha });
    }
}
```

### 또 보기

* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../)


