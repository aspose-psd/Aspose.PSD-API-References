---
title: "WarpSettings.RenderQuality"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "WarpSettings 속성. 속도와 품질 사이의 왜곡 렌더 품질 값을 가져오거나 설정합니다"
type: docs
weight: 50
url: /ko/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/renderquality/
---
{{< psd/tize >}}
## WarpSettings.RenderQuality property

워프 렌더 품질 값을 가져오거나 설정합니다 - 속도와 품질 사이

```csharp
public RenderQuality RenderQuality { get; set; }
```

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

* enum [RenderQuality](../../renderquality/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


