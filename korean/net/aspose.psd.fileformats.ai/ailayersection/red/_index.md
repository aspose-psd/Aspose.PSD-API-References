---
title: AiLayerSection.Red
second_title: .NET API 참조용 Aspose.PSD
description: AiLayerSection 재산. 빨간색 구성 요소를 가져오거나 설정합니다.
type: docs
weight: 130
url: /ko/net/aspose.psd.fileformats.ai/ailayersection/red/
---
## AiLayerSection.Red property

빨간색 구성 요소를 가져오거나 설정합니다.

```csharp
public int Red { get; set; }
```

### 자산 가치

빨간색 구성 요소입니다.

### 예

다음 예제는 AI 형식 파일의 레이어 지원을 보여줍니다.

```csharp
[C#]

string sourceFilePath = "form_8_2l3_7.ai";
string outputFilePath = "form_8_2l3_7_export";

void AssertIsTrue(bool condition, string message)
{
    if (!condition)
    {
        throw new FormatException(message);
    }
}

using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    AiLayerSection layer0 = image.Layers[0];
    AssertIsTrue(layer0 != null, "Layer 0 should be not null.");
    AssertIsTrue(layer0.Name == "Layer 4", "The Name property of the layer 0 should be `Layer 4`");
    AssertIsTrue(!layer0.IsTemplate, "The IsTemplate property of the layer 0 should be false.");
    AssertIsTrue(layer0.IsLocked, "The IsLocked property of the layer 0 should be true.");
    AssertIsTrue(layer0.IsShown, "The IsShown property of the layer 0 should be true.");
    AssertIsTrue(layer0.IsPrinted, "The IsPrinted property of the layer 0 should be true.");
    AssertIsTrue(!layer0.IsPreview, "The IsPreview property of the layer 0 should be false.");
    AssertIsTrue(layer0.IsImagesDimmed, "The IsImagesDimmed property of the layer 0 should be true.");
    AssertIsTrue(layer0.DimValue == 51, "The DimValue property of the layer 0 should be 51.");
    AssertIsTrue(layer0.ColorNumber == 0, "The ColorNumber property of the layer 0 should be 0.");
    AssertIsTrue(layer0.Red == 79, "The Red property of the layer 0 should be 79.");
    AssertIsTrue(layer0.Green == 128, "The Green property of the layer 0 should be 128.");
    AssertIsTrue(layer0.Blue == 255, "The Blue property of the layer 0 should be 255.");
    AssertIsTrue(layer0.RasterImages.Length == 0, "The pixels length property of the raster image in the layer 0 should equals 0.");

    AiLayerSection layer1 = image.Layers[1];
    AssertIsTrue(layer1 != null, "Layer 1 should be not null.");
    AssertIsTrue(layer1.Name == "Layer 1", "The Name property of the layer 1 should be `Layer 1`");
    AssertIsTrue(layer1.RasterImages.Length == 1, "The length property of the raster images in the layer 1 should equals 1.");

    AiRasterImageSection rasterImage = layer1.RasterImages[0];
    AssertIsTrue(rasterImage != null, "The raster image in the layer 1 should be not null.");
    AssertIsTrue(rasterImage.Pixels != null, "The pixels property of the raster image in the layer 1 should be not null.");
    AssertIsTrue(string.Empty == rasterImage.Name, "The Name property of the raster image in the layer 1 should be empty");
    AssertIsTrue(rasterImage.Pixels.Length == 100, "The pixels length property of the raster image in the layer 1 should equals 100.");

    image.Save(outputFilePath + ".psd", new PsdOptions());
    image.Save(outputFilePath + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

### 또한보십시오

* class [AiLayerSection](../)
* 네임스페이스 [Aspose.PSD.FileFormats.Ai](../../ailayersection/)
* 집회 [Aspose.PSD](../../../)


