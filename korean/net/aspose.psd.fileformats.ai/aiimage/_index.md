---
title: Class AiImage
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.FileFormats.Ai.AiImage 수업. Adobe IllustratorAI Image
type: docs
weight: 1260
url: /ko/net/aspose.psd.fileformats.ai/aiimage/
---
## AiImage class

Adobe Illustrator(AI) Image

```csharp
public sealed class AiImage : Image
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [AiImage](aiimage/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AutoAdjustPalette](../../aspose.psd/image/autoadjustpalette/) { get; set; } | 팔레트 자동 조정 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [BackgroundColor](../../aspose.psd/image/backgroundcolor/) { get; set; } | 배경색 값을 가져오거나 설정합니다. |
| override [BitsPerPixel](../../aspose.psd.fileformats.ai/aiimage/bitsperpixel/) { get; } | 픽셀당 이미지 비트를 가져옵니다. |
| [Bounds](../../aspose.psd/image/bounds/) { get; } | 이미지 범위를 가져옵니다. |
| [BufferSizeHint](../../aspose.psd/image/buffersizehint/) { get; set; } | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 가져오거나 설정합니다. |
| [Container](../../aspose.psd/image/container/) { get; } | 가져오기[`Image`](../../aspose.psd/image/) 컨테이너. |
| [DataSection](../../aspose.psd.fileformats.ai/aiimage/datasection/) { get; } | 데이터 섹션을 가져옵니다. |
| [DataStreamContainer](../../aspose.psd/datastreamsupporter/datastreamcontainer/) { get; } | 개체의 데이터 스트림을 가져옵니다. |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 삭제되었는지 여부를 나타내는 값을 가져옵니다. |
| override [FileFormat](../../aspose.psd.fileformats.ai/aiimage/fileformat/) { get; } | 파일 format 의 값을 가져옵니다. |
| [FinalizeSection](../../aspose.psd.fileformats.ai/aiimage/finalizesection/) { get; } | 마무리 섹션을 가져옵니다. |
| virtual [HasBackgroundColor](../../aspose.psd/image/hasbackgroundcolor/) { get; set; } | 이미지에 배경색이 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [Header](../../aspose.psd.fileformats.ai/aiimage/header/) { get; } | 헤더를 가져옵니다. |
| override [Height](../../aspose.psd.fileformats.ai/aiimage/height/) { get; } | 이미지 높이를 가져옵니다. |
| [InterruptMonitor](../../aspose.psd/image/interruptmonitor/) { get; set; } | 인터럽트 모니터를 가져오거나 설정합니다. |
| override [IsCached](../../aspose.psd.fileformats.ai/aiimage/iscached/) { get; } | 개체의 데이터가 현재 캐시되어 있고 데이터 읽기가 필요하지 않은지 여부를 나타내는 값을 가져옵니다. |
| [Layers](../../aspose.psd.fileformats.ai/aiimage/layers/) { get; } | 레이어 섹션을 가져옵니다. |
| [Palette](../../aspose.psd/image/palette/) { get; set; } | 색상표를 가져오거나 설정합니다. 픽셀을 직접 표현하는 경우 색상 팔레트를 사용하지 않습니다. |
| [SetupSection](../../aspose.psd.fileformats.ai/aiimage/setupsection/) { get; } | 설정 섹션을 가져옵니다. |
| [Size](../../aspose.psd/image/size/) { get; } | 이미지 크기를 가져옵니다. |
| [Version](../../aspose.psd.fileformats.ai/aiimage/version/) { get; } | Adobe Illustrator의 버전을 가져옵니다. format |
| override [Width](../../aspose.psd.fileformats.ai/aiimage/width/) { get; } | 이미지 너비를 가져옵니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [AddLayer](../../aspose.psd.fileformats.ai/aiimage/addlayer/)(AiLayerSection) | AI 레이어 섹션을 추가합니다. |
| override [CacheData](../../aspose.psd.fileformats.ai/aiimage/cachedata/)() | 데이터를 캐시하고 기본에서 추가 데이터 로드가 수행되지 않도록 합니다.[`DataStreamContainer`](../../aspose.psd/datastreamsupporter/datastreamcontainer/) . |
| [CanSave](../../aspose.psd/image/cansave/)(ImageOptionsBase) | 전달된 저장 옵션으로 표시되는 지정된 파일 형식으로 이미지를 저장할 수 있는지 여부를 결정합니다. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 삭제합니다. |
| virtual [GetDefaultOptions](../../aspose.psd/image/getdefaultoptions/)(object[]) | 기본 옵션을 가져옵니다. |
| virtual [GetOriginalOptions](../../aspose.psd/image/getoriginaloptions/)() | 원본 파일 설정을 기반으로 옵션을 가져옵니다. 이것은 원본 이미지의 비트 심도 및 기타 매개 변수를 변경하지 않고 유지하는 데 유용할 수 있습니다. 예를 들어 흑백 PNG 이미지를 픽셀당 1비트로 로드한 다음 the 를 사용하여 저장[`Save`](../../aspose.psd/datastreamsupporter/save/) 방법을 사용하면 픽셀당 8비트의 출력 PNG 이미지가 생성됩니다. 이를 피하고 픽셀당 1비트의 PNG 이미지를 저장하려면 이 방법을 사용하여 해당 저장 옵션을 가져오고 them 를[`Save`](../../aspose.psd/image/save/)메소드를 두 번째 매개변수로 지정합니다. |
| [Resize](../../aspose.psd/image/resize/)(int, int) | 이미지 크기를 조정합니다. 기본값LeftTopToLeftTop사용중입니다. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_1)(int, int, ImageResizeSettings) | 이미지 크기를 조정합니다. |
| override [Resize](../../aspose.psd.fileformats.ai/aiimage/resize/#resize_2)(int, int, ResizeType) | 이미지 크기를 조정합니다. |
| [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int) | 높이를 비례적으로 조정합니다. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ImageResizeSettings) | 높이를 비례적으로 조정합니다. |
| virtual [ResizeHeightProportionally](../../aspose.psd/image/resizeheightproportionally/)(int, ResizeType) | 높이를 비례적으로 조정합니다. |
| [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int) | 너비를 비례적으로 조정합니다. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ImageResizeSettings) | 너비를 비례적으로 조정합니다. |
| virtual [ResizeWidthProportionally](../../aspose.psd/image/resizewidthproportionally/)(int, ResizeType) | 너비를 비례적으로 조정합니다. |
| override [RotateFlip](../../aspose.psd.fileformats.ai/aiimage/rotateflip/)(RotateFlipType) | 이미지를 회전, 뒤집기 또는 회전하고 뒤집습니다. |
| [Save](../../aspose.psd/image/save/)() | 이미지 데이터를 기본 스트림에 저장합니다. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(Stream) | 개체의 데이터를 지정된 스트림에 저장합니다. |
| [Save](../../aspose.psd/datastreamsupporter/save/)(string) | 개체의 데이터를 지정된 파일 위치에 저장합니다. |
| [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase) | 이미지의 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다. |
| virtual [Save](../../aspose.psd/datastreamsupporter/save/)(string, bool) | 개체의 데이터를 지정된 파일 위치에 저장합니다. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase) | 저장 옵션에 따라 객체의 데이터를 지정된 파일 위치에 지정된 파일 형식으로 저장합니다. |
| virtual [Save](../../aspose.psd/image/save/)(Stream, ImageOptionsBase, Rectangle) | 이미지의 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다. |
| virtual [Save](../../aspose.psd/image/save/)(string, ImageOptionsBase, Rectangle) | 저장 옵션에 따라 객체의 데이터를 지정된 파일 위치에 지정된 파일 형식으로 저장합니다. |
| override [SetPalette](../../aspose.psd.fileformats.ai/aiimage/setpalette/)(IColorPalette, bool) | 이미지 팔레트를 설정합니다. |

### 예

다음 예는 Aspose.PSD에서 Adobe Illustrator 파일을 PDF 형식으로 내보낼 수 있는 방법을 보여줍니다.

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

다음 예는 Aspose.PSD에서 AI 파일을 PSD 및 PNG 형식으로 내보낼 수 있는 방법을 보여줍니다.

```csharp
[C#]

string sourceFileName = "form_8.ai";
string outputFileName = "form_8_export";
using (AiImage image = (AiImage)Image.Load(sourceFileName))
{
    image.Save(outputFileName + ".psd", new PsdOptions());
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

다음 예는 Ai 형식을 PSD, PNG, JPG, GIF 및 TIF 형식으로 내보내기 지원을 보여줍니다.

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"34992OStroke",
    @"rect2_color",
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string name = sourcesFiles[i];
    string sourceFileName = name + ".ai";

    using (AiImage image = (AiImage)Image.Load(sourceFileName))
    {
        string outFileName = name + ".psd";
        ImageOptionsBase options = new PsdOptions();
        image.Save(outFileName, options);

        outFileName = name + ".png";
        options = new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha };
        image.Save(outFileName, options);

        outFileName = name + ".jpg";
        options = new JpegOptions() { Quality = 85 };
        image.Save(outFileName, options);

        outFileName = name + ".gif";
        options = new GifOptions() { DoPaletteCorrection = false };
        image.Save(outFileName, options);

        outFileName = name + ".tif";
        options = new TiffOptions(TiffExpectedFormat.TiffDeflateRgba);
        image.Save(outFileName, options);
    }
}
```

### 또한보십시오

* class [Image](../../aspose.psd/image/)
* 네임스페이스 [Aspose.PSD.FileFormats.Ai](../../aspose.psd.fileformats.ai/)
* 집회 [Aspose.PSD](../../)


