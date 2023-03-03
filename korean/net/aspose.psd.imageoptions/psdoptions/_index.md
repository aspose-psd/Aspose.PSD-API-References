---
title: Class PsdOptions
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.ImageOptions.PsdOptions 수업. psd 파일 형식은 옵션을 생성합니다.
type: docs
weight: 4900
url: /ko/net/aspose.psd.imageoptions/psdoptions/
---
## PsdOptions class

psd 파일 형식은 옵션을 생성합니다.

```csharp
public class PsdOptions : ImageOptionsBase
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PsdOptions](psdoptions/#constructor)() | 의 새 인스턴스를 초기화합니다.`PsdOptions` 클래스. |
| [PsdOptions](psdoptions/#constructor_1)(PsdImage) | 의 새 인스턴스를 초기화합니다.`PsdOptions` 클래스. |
| [PsdOptions](psdoptions/#constructor_2)(PsdOptions) | 의 새 인스턴스를 초기화합니다.`PsdOptions` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 가져오거나 설정합니다. |
| [ChannelBitsCount](../../aspose.psd.imageoptions/psdoptions/channelbitscount/) { get; set; } | 색상 채널당 비트 수를 가져오거나 설정합니다. |
| [ChannelsCount](../../aspose.psd.imageoptions/psdoptions/channelscount/) { get; set; } | 색상 채널 수를 가져오거나 설정합니다. |
| [ColorMode](../../aspose.psd.imageoptions/psdoptions/colormode/) { get; set; } | psd 색상 모드를 가져오거나 설정합니다. |
| [CompressionMethod](../../aspose.psd.imageoptions/psdoptions/compressionmethod/) { get; set; } | psd 압축 방법을 가져오거나 설정합니다. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | 기본 대체 글꼴(PSD 파일의 기존 레이어 글꼴이 시스템에 표시되지 않는 경우 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴)을 가져오거나 설정합니다. 기본 글꼴의 적절한 이름을 사용하려면 다음 코드 스니펫을 사용할 수 있습니다. : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 삭제되었는지 여부를 나타내는 값을 가져옵니다. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | [전체 프레임]. 여부를 나타내는 값을 가져오거나 설정합니다. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | 다중 페이지 options |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | 색상표를 가져오거나 설정합니다. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 진행률 이벤트 처리기를 가져오거나 설정합니다. |
| [PsdVersion](../../aspose.psd.imageoptions/psdoptions/psdversion/) { get; set; } | 파일 형식 버전을 가져오거나 설정합니다. PSD 또는 PSB일 수 있습니다. |
| [RefreshImagePreviewData](../../aspose.psd.imageoptions/psdoptions/refreshimagepreviewdata/) { get; set; } | [이미지 미리보기 데이터 새로 고침] 여부를 나타내는 값을 가져오거나 설정합니다. - 다른 PSD 이미지 뷰어와의 호환성을 최대화하는 데 사용되는 옵션입니다. Compact Framework 플랫폼에서는 최종 레이아웃으로 그리는 텍스트 레이어가 지원되지 않습니다 |
| [RemoveGlobalTextEngineResource](../../aspose.psd.imageoptions/psdoptions/removeglobaltextengineresource/) { get; set; } | 다음 여부를 나타내는 값을 가져오거나 설정합니다. - 전역 텍스트 엔진 리소스 제거 - 일부 텍스트 레이어 psd 파일에 대해 처리 후 Adobe Photoshop에서 열 수 없는 경우에만 사용됩니다(대부분 관련된 글꼴 텍스트 레이어가 없는 경우). 이 옵션을 사용한 후 사용자는 Photoshop 파일에서 다음 항목을 만들어야 합니다: 메뉴 "텍스트" -&gt; "프로세스 부재 글꼴". 이 작업 후에 모든 텍스트가 다시 나타납니다. 이 작업으로 인해 일부 최종 레이아웃이 변경될 수 있습니다. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | 해상도 설정을 가져오거나 설정합니다. |
| [Resources](../../aspose.psd.imageoptions/psdoptions/resources/) { get; set; } | psd 리소스를 가져오거나 설정합니다. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| [Version](../../aspose.psd.imageoptions/psdoptions/version/) { get; set; } | psd 파일 버전을 가져오거나 설정합니다. |
| override [XmpData](../../aspose.psd.imageoptions/psdoptions/xmpdata/) { get; set; } | XMP 데이터 가져오기 또는 설정 container |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | 이 인스턴스를 복제합니다. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 삭제합니다. |

### 예

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

이 예에서는 PsdOptions 인스턴스의 Source 속성에 지정된 일부 디스크 위치에 새 이미지 파일을 만듭니다. 실제 이미지를 생성하기 전에 PsdOptions 인스턴스에 대한 여러 속성이 설정됩니다. 특히 이 경우 실제 디스크 위치를 나타내는 Source 속성입니다.

```csharp
[C#]

//PsdOptions의 인스턴스를 만들고 다양한 속성을 설정합니다.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

// FileCreateSource의 인스턴스를 생성하고 PsdOptions 인스턴스의 소스로 할당합니다.
//두 번째 부울 매개변수는 생성할 파일이 IsTemporal인지 여부를 결정합니다.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Create 메서드를 호출하여 Image 인스턴스를 만들고 PsdOptions 인스턴스로 초기화합니다.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // 일부 이미지 처리 수행

    // 모든 변경 사항 저장
    image.Save();
}
```

다음 예는 그레이스케일 16비트 PSD 파일을 RGB 채널당 16비트로 읽고 저장하는 것이 예외 없이 올바르게 작동함을 보여줍니다.

```csharp
[C#]

string sourceFilePath = "grayscale5x5.psd";
string exportFilePath = "rgb16bit5x5.psd";
PsdOptions psdOptions = new PsdOptions()
{
    ColorMode = ColorModes.Rgb,
    ChannelBitsCount = 16,
    ChannelsCount = 4
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(exportFilePath, psdOptions);
}

string pngExportPath = Path.ChangeExtension(exportFilePath, "png");
using (PsdImage image = (PsdImage)Image.Load(exportFilePath))
{
    // 여기에 예외가 있어서는 안됩니다.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

다음 예는 그레이스케일 16비트 PSD 파일을 채널당 8비트 그레이스케일로 읽고 저장하는 것이 예외 없이 올바르게 작동함을 보여줍니다.

```csharp
[C#]

string sourceFilePath = "grayscale16bit.psd";
string exportFilePath = "grayscale16bit_Grayscale8_2_RLE.psd";
PsdOptions psdOptions = new PsdOptions()
{
    ColorMode = ColorModes.Grayscale,
    ChannelBitsCount = 8,
    ChannelsCount = 2
};

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    RasterCachedImage raster = image.Layers[0];
    Aspose.PSD.Graphics graphics = new Graphics(raster);
    int width = raster.Width;
    int height = raster.Height;
    Rectangle rect = new Rectangle(width / 3, height / 3, width - (2 * (width / 3)) - 1, height - (2 * (height / 3)) - 1);
    graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);
    image.Save(exportFilePath, psdOptions);
}

string pngExportPath = Path.ChangeExtension(exportFilePath, "png");
using (PsdImage image = (PsdImage)Image.Load(exportFilePath))
{
    // 여기에 예외가 있어서는 안됩니다.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

다음 예는 Aspose.PSD에서 PassThrough 레이어 혼합 모드를 사용하는 방법을 보여줍니다.

```csharp
[C#]

string sourceFileName = "Apple.psd";
string outputFileName = "OutputApple";
using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    if (image.Layers.Length < 23)
    {
        throw new Exception("There is not 23rd layer.");
    }

    var layer = image.Layers[23] as LayerGroup;

    if (layer == null)
    {
        throw new Exception("The 23rd layer is not a layer group.");
    }

    if (layer.Name != "AdjustmentGroup")
    {
        throw new Exception("The 23rd layer name is not 'AdjustmentGroup'.");
    }

    if (layer.BlendModeKey != BlendMode.PassThrough)
    {
        throw new Exception("AdjustmentGroup layer should have 'pass through' blend mode.");
    }

    image.Save(outputFileName + ".psd", new PsdOptions(image));
    image.Save(outputFileName + ".png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });

    layer.BlendModeKey = BlendMode.Normal;

    image.Save(outputFileName + "Normal.psd", new PsdOptions(image));
    image.Save(outputFileName + "Normal.png", new PngOptions() { ColorType = PngColorType.TruecolorWithAlpha });
}
```

다음 예는 문서 변환 진행이 예외 없이 올바르게 작동함을 보여줍니다.

```csharp
[C#]

string sourceFilePath = "Apple.psd";
Stream outputStream = new MemoryStream();

Aspose.PSD.ProgressEventHandler localProgressEventHandler = delegate(ProgressEventHandlerInfo progressInfo)
{
    string message = string.Format(
        "{0} {1}: {2} out of {3}",
        progressInfo.Description,
        progressInfo.EventType,
        progressInfo.Value,
        progressInfo.MaxValue);
    Console.WriteLine(message);
};

Console.WriteLine("---------- Loading Apple.psd ----------");
var loadOptions = new PsdLoadOptions() { ProgressEventHandler = localProgressEventHandler };
using (PsdImage image = (PsdImage)Image.Load(sourceFilePath, loadOptions))
{
    Console.WriteLine("---------- Saving Apple.psd to PNG format ----------");
    image.Save(
        outputStream,
        new PngOptions()
            {
                ColorType = PngColorType.Truecolor,
                ProgressEventHandler = localProgressEventHandler
            });

    Console.WriteLine("---------- Saving Apple.psd to PSD format ----------");
    image.Save(
        outputStream,
        new PsdOptions()
            {
                ColorMode = ColorModes.Rgb,
                ChannelsCount = 4,
                ProgressEventHandler = localProgressEventHandler
            });
}
```

이 예제는 색상 유형의 배열에서 픽셀 정보를 로드하고 배열을 조작하여 이미지로 다시 설정하는 방법을 보여줍니다. 이러한 작업을 수행하기 위해 이 예제에서는 MemoryStream 개체를 사용하여 새 이미지 파일(PSD 형식)을 만듭니다.

```csharp
[C#]

//MemoryStream 인스턴스 생성
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //PsdOptions의 인스턴스를 만들고 Source 속성을 비롯한 다양한 속성을 설정합니다.
    Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();
    psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream);

    //이미지 인스턴스 생성
    using (Aspose.PSD.RasterImage image = (Aspose.PSD.RasterImage)Aspose.PSD.Image.Create(psdOptions, 500, 500))
    {
        //영역을 이미지 경계로 지정하여 이미지의 픽셀을 가져옵니다.
        Aspose.PSD.Color[] pixels = image.LoadPixels(image.Bounds);

        //배열을 반복하고 대체 인덱스 픽셀의 색상을 설정합니다.
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //인덱스 픽셀 색상을 노란색으로 설정
                pixels[index] = Aspose.PSD.Color.Yellow;
            }
            else
            {
                //인덱스 픽셀 색상을 파란색으로 설정
                pixels[index] = Aspose.PSD.Color.Blue;
            }
        }

        //픽셀 변경 사항을 이미지에 적용
        image.SavePixels(image.Bounds, pixels);

        // 모든 변경 사항을 저장합니다.
        image.Save();
    }

    //MemoryStream을 파일에 쓰기
    stream.WriteTo(new System.IO.FileStream(@"C:\temp\output.psd", System.IO.FileMode.CreateNew));
}
```

다음 예는 그레이스케일 16비트 PSD 파일 읽기 및 저장이 예외 없이 올바르게 작동함을 보여줍니다.

```csharp
[C#]

Stack<string> outputFilePathStack = new Stack<string>();

void SaveToPsdThenLoadAndSaveToPng(
    string file,
    ColorModes colorMode,
    short channelBitsCount,
    short channelsCount,
    CompressionMethod compression,
    int layerNumber)
{
    string filePath = file + ".psd";
    string postfix = colorMode.ToString() + channelBitsCount + "_" + channelsCount + "_" + compression;
    string exportPath = file + postfix + ".psd";
    PsdOptions psdOptions = new PsdOptions()
    {
        ColorMode = colorMode,
        ChannelBitsCount = channelBitsCount,
        ChannelsCount = channelsCount,
        CompressionMethod = compression
    };

    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        RasterCachedImage raster = layerNumber >= 0 ? (RasterCachedImage)image.Layers[layerNumber] : image;

        Aspose.PSD.Graphics graphics = new Graphics(raster);
        int width = raster.Width;
        int height = raster.Height;
        Rectangle rect = new Rectangle(
            width / 3,
            height / 3,
            width - (2 * (width / 3)) - 1,
            height - (2 * (height / 3)) - 1);
        graphics.DrawRectangle(new Aspose.PSD.Pen(Color.DarkGray, 1), rect);

        image.Save(exportPath, psdOptions);
    }

    string pngExportPath = Path.ChangeExtension(exportPath, "png");
    using (PsdImage image = (PsdImage)Image.Load(exportPath))
    {
        // 여기에 예외가 있어서는 안됩니다.
        image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
    }

    outputFilePathStack.Push(exportPath);
}

SaveToPsdThenLoadAndSaveToPng("grayscale5x5", ColorModes.Cmyk, 16, 5, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb16bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb16bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("argb8bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, 0);
SaveToPsdThenLoadAndSaveToPng("argb8bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("cmyk16bit_5x5_no_layers", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
SaveToPsdThenLoadAndSaveToPng("index8bit_5x5", ColorModes.Grayscale, 16, 2, CompressionMethod.RLE, -1);
```

### 또한보십시오

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* 네임스페이스 [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* 집회 [Aspose.PSD](../../)


