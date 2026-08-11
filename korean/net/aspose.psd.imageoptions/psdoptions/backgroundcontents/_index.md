---
title: "PsdOptions.BackgroundContents"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "PsdOptions 속성. 배경 색상을 가져오거나 설정합니다. 투명 객체 아래에서 볼 수 있습니다."
type: docs
weight: 20
url: /ko/net/aspose.psd.imageoptions/psdoptions/backgroundcontents/
---
{{< psd/tize >}}
## PsdOptions.BackgroundContents property

배경 색을 가져오거나 설정합니다. 투명 객체 아래에서 볼 수 있습니다.

```csharp
public RawColor BackgroundContents { get; set; }
```

## 예제

다음 코드는 PsdOptions에서 BackgroundContents 속성 지원을 보여줍니다.

```csharp
[C#]

// psd 파일 미리보기에서 반투명도가 잘못 처리됩니다.
// BackgroundContents가 흰색으로 지정되었습니다. 투명 영역은 흰색이어야 합니다.

string sourceFile = "frog_nosymb.psd";
string outputFile = "frog_nosymb_backgroundcontents_output.psd";

using (PsdImage psdImage = (PsdImage)Image.Load(sourceFile))
{
    RawColor backgroundColor = new RawColor(PixelDataFormat.Rgb32Bpp);
    int argbValue = 255 << 24 | 255 << 16 | 255 << 8 | 255;
    backgroundColor.SetAsInt(argbValue); // White

    PsdOptions psdOptions = new PsdOptions(psdImage)
    {
        ColorMode = ColorModes.Rgb,
        CompressionMethod = CompressionMethod.RLE,
        ChannelsCount = 4,
        BackgroundContents = backgroundColor,
    };

    psdImage.Save(outputFile, psdOptions);
}
```

### 또 보기

* class [RawColor](../../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/)
* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


