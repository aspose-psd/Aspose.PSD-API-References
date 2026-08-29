---
title: "ArtboardLayer.BackgroundColor"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "ArtboardLayer 속성. 아트보드 배경 색상을 가져오거나 설정합니다"
type: docs
weight: 10
url: /ko/net/aspose.psd.fileformats.psd.layers/artboardlayer/backgroundcolor/
---
{{< psd/tize >}}
## ArtboardLayer.BackgroundColor property

아트보드 배경 색상을 가져오거나 설정합니다.

```csharp
public override Color BackgroundColor { get; set; }
```

## 예제

다음 코드는 ArtboardLayer를 개별 이미지와 하나의 이미지로 모두 내보내는 지원을 보여줍니다.

```csharp
[C#]

string srcFile = "artboard2.psd";

string outFilePng0 = "art0.png";
string outFilePng1 = "art1.png";
string outFilePng2 = "art2.png";
string outFilePng3 = "art3.png";

using (var psdImage = (PsdImage)Image.Load(srcFile))
{
    ArtboardLayer art1 = (ArtboardLayer)psdImage.Layers[4];
    ArtboardLayer art2 = (ArtboardLayer)psdImage.Layers[9];
    ArtboardLayer art3 = (ArtboardLayer)psdImage.Layers[14];

    var pngSaveOptions = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
    art1.Save(outFilePng1, pngSaveOptions);
    art2.Save(outFilePng2, pngSaveOptions);
    art3.Save(outFilePng3, pngSaveOptions);

    psdImage.Save(outFilePng0, pngSaveOptions);
}
```

### 또 보기

* struct [Color](../../../aspose.psd/color/)
* class [ArtboardLayer](../)
* namespace [Aspose.PSD.FileFormats.Psd.Layers](../../../aspose.psd.fileformats.psd.layers/)
* assembly [Aspose.PSD](../../../)


