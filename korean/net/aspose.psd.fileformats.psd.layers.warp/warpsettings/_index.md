---
title: "클래스 WarpSettings"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.FileFormats.Psd.Layers.Warp.WarpSettings 클래스. 워프가 적용된 레이어의 매개변수"
type: docs
weight: 4010
url: /ko/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/
---
{{< psd/tize >}}
## WarpSettings class

워프가 적용된 레이어의 매개변수

```csharp
public class WarpSettings
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [WarpSettings](warpsettings/#constructor_1)(PlacedResource) | 새로운 `WarpSettings` 클래스 인스턴스를 초기화합니다. |
| [WarpSettings](warpsettings/#constructor)(OSTypeStructure[], Rectangle) | 새로운 `WarpSettings` 클래스 인스턴스를 초기화합니다. |
| [WarpSettings](warpsettings/#constructor_2)(PointF[], Rectangle) | 새로운 `WarpSettings` 클래스 인스턴스를 초기화합니다. |
| [WarpSettings](warpsettings/#constructor_3)(PointF[], Rectangle, WarpStyles) | 새로운 `WarpSettings` 클래스 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Bounds](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/bounds/) { get; } | 워프 이미지의 경계를 가져오거나 설정합니다 |
| [GridSize](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/) { get; set; } | 워프 그리드의 크기를 가져오거나 설정합니다. 기본값은 1입니다. |
| [MeshPoints](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/meshpoints/) { get; set; } | Photoshop 메시 포인트 |
| [RenderQuality](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/renderquality/) { get; set; } | 워프 렌더 품질 값을 가져오거나 설정합니다 - 속도와 품질 사이 |
| [Rotate](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/rotate/) { get; set; } | 회전 값을 가져오거나 설정합니다 |
| [Style](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/style/) { get; set; } | 워프 스타일을 가져오거나 설정합니다 |
| [Value](../../aspose.psd.fileformats.psd.layers.warp/warpsettings/value/) { get; set; } | 워프의 값을 가져오거나 설정합니다 |

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


