---
title: "WarpSettings.GridSize"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "WarpSettings 속성. 워프 그리드의 크기를 가져오거나 설정합니다. 기본값은 1입니다."
type: docs
weight: 30
url: /ko/net/aspose.psd.fileformats.psd.layers.warp/warpsettings/gridsize/
---
{{< psd/tize >}}
## WarpSettings.GridSize property

워프 그리드의 크기를 가져오거나 설정합니다. 기본값은 1입니다.

```csharp
public Size GridSize { get; set; }
```

## 예제

다음 코드는 WarpSettings.GridSize 속성 지원을 보여줍니다.

```csharp
[C#]

string sourceFile = "pirate_x3.psd";
string outputFile = "export.png";

using (var psdImage = (PsdImage)Image.Load(sourceFile, new PsdLoadOptions() { AllowWarpRepaint = true, LoadEffectsResource = true }))
{
    // 워프 설정 가져오기
    WarpSettings warpSettings = ((SmartObjectLayer)(psdImage.Layers[0])).WarpSettings;

    // 새 크기 설정
    // Photoshop의 경우 값은 1에서 50 사이여야 하며 PSD 파일을 올바르게 저장할 수 없습니다.
    warpSettings.GridSize = new Size(100, 100);

    // 유효한 값 설정
    warpSettings.GridSize = new Size(3, 3);

    // x3 그리드로 예제 파일 렌더링
    psdImage.Save(outputFile, new PngOptions
    {
        ColorType = PngColorType.TruecolorWithAlpha
    });
}
```

### 또 보기

* struct [Size](../../../aspose.psd/size/)
* class [WarpSettings](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers.Warp](../../../aspose.psd.fileformats.psd.layers.warp/)
* assembly [Aspose.PSD](../../../)


