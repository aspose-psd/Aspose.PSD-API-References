---
title: Image.Load
second_title: .NET API 참조용 Aspose.PSD
description: Image 방법. 지정된 파일에서 새 이미지를 로드합니다.
type: docs
weight: 20
url: /ko/net/aspose.psd/image/load/
---
## Load(string, LoadOptions) {#load_3}

지정된 파일에서 새 이미지를 로드합니다.

```csharp
public static Image Load(string filePath, LoadOptions loadOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 이미지를 로드할 파일 경로입니다. |
| loadOptions | LoadOptions | 로드 옵션. |

### 반환 값

로드된 이미지입니다.

### 또한보십시오

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* 네임스페이스 [Aspose.PSD](../../image/)
* 집회 [Aspose.PSD](../../../)

---

## Load(string) {#load_2}

지정된 파일에서 새 이미지를 로드합니다.

```csharp
public static Image Load(string filePath)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 이미지를 로드할 파일 경로. |

### 반환 값

로드된 이미지입니다.

### 예

이 예제는 지정된 파일 경로를 사용하여 기존 이미지 파일을 Aspose.PSD.Image의 인스턴스로 로드하는 방법을 보여줍니다.

```csharp
[C#]

//이미지 인스턴스를 생성하고 디스크 위치에서 기존 이미지 파일로 초기화
string path = "C:\\temp\\image.psd";
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(path))
{
    // 일부 이미지 처리 수행
}
```

다음 예제는 오른쪽에서 왼쪽으로 쓰는 언어에 대한 ITextPortion을 통한 텍스트 정렬이 올바르게 작동함을 보여줍니다.

```csharp
[C#]

string sourceFilePath = "bidi.psd";
string exportFilePath = "bidiOutput.psd";

using (PsdImage image = (PsdImage)Image.Load(sourceFilePath))
{
    TextLayer layer = (TextLayer)image.Layers[2];
    ITextPortion[] portions = layer.TextData.Items;

    portions[0].Paragraph.Justification = JustificationMode.Center;
    layer.TextData.UpdateLayerData();

    image.Save(exportFilePath);
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

* class [Image](../)
* 네임스페이스 [Aspose.PSD](../../image/)
* 집회 [Aspose.PSD](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

지정된 스트림에서 새 이미지를 로드합니다.

```csharp
public static Image Load(Stream stream, LoadOptions loadOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 이미지를 로드할 스트림입니다. |
| loadOptions | LoadOptions | 로드 옵션. |

### 반환 값

로드된 이미지입니다.

### 또한보십시오

* class [LoadOptions](../../loadoptions/)
* class [Image](../)
* 네임스페이스 [Aspose.PSD](../../image/)
* 집회 [Aspose.PSD](../../../)

---

## Load(Stream) {#load}

지정된 스트림에서 새 이미지를 로드합니다.

```csharp
public static Image Load(Stream stream)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| stream | Stream | 이미지를 로드할 스트림입니다. |

### 반환 값

로드된 이미지입니다.

### 예

이 예제는 System.IO.Stream 개체를 사용하여 기존 이미지 파일을 로드하는 방법을 보여줍니다.

```csharp
[C#]

//FileStream 인스턴스 생성
using(System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\sample.psd",System.IO.FileMode.Open))
{
    //Image 클래스의 인스턴스를 생성하고 Load 메서드를 호출하여 FileStream 객체를 통해 기존 파일을 로드합니다.
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(stream))
    {
        // 일부 이미지 처리를 수행합니다.
    }
}
```

### 또한보십시오

* class [Image](../)
* 네임스페이스 [Aspose.PSD](../../image/)
* 집회 [Aspose.PSD](../../../)


