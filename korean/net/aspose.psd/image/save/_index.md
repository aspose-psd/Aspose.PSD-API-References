---
title: "Image.Save"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Image 메서드. 이미지 데이터를 기본 스트림에 저장합니다."
type: docs
weight: 240
url: /ko/net/aspose.psd/image/save/
---
{{< psd/tize >}}
## Save() {#save}

이미지 데이터를 기본 스트림에 저장합니다.

```csharp
public void Save()
```

### 또 보기

* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

객체 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 저장합니다.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | String | 파일 경로. |
| 옵션 | ImageOptionsBase | 옵션. |

## 예제

다음 예제는 Aspose.PSD에서 Adobe Illustrator 파일을 PDF 형식으로 내보내는 방법을 보여줍니다.

```csharp
[C#]

string sourceFilePath = "rect2_color.ai";
string outputFilePath = "rect2_color.ai_output.pdf";
using (AiImage image = (AiImage)Image.Load(sourceFilePath))
{
    image.Save(outputFilePath, new PdfOptions());
}
```

다음 예제는 AsposePSD가 PSB 파일을 PSD 형식으로 내보내는 것을 지원함을 보여줍니다.

```csharp
[C#]

// PSB를 PDF로 저장 지원
string sourceFileName = "sample.psb";
string outFileName = "sample.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

다음 코드는 선택 가능한 텍스트가 포함된 PDF 문서로 PsdImage를 저장합니다.

```csharp
[C#]

// PSD를 PDF로 저장하면 선택 가능한 텍스트가 제공되지 않습니다.
string sourceFileName = "text.psd";
string outFileName = "text.pdf";

using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
{
    image.Save(outFileName, new PdfOptions());
}
```

다음 예제는 Aspose.PSD에서 AI 파일을 PSD 및 PNG 형식으로 내보내는 방법을 보여줍니다.

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

다음 예제는 오른쪽에서 왼쪽으로 쓰는 언어에 대해 ITextPortion을 통한 텍스트 정렬이 올바르게 작동함을 보여줍니다.

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

이 예제는 이미지를 저장하는 간단한 단계를 보여줍니다. 이 작업을 시연하기 위해, 우리는 디스크의 특정 위치에서 기존 파일을 로드하고, 이미지에 회전 작업을 수행한 뒤 파일 경로를 사용하여 JPEG 파일 형식으로 이미지를 저장합니다.

```csharp
[C#]

//이미지 클래스의 인스턴스를 생성하고 파일 경로를 통해 기존 파일로 초기화합니다.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //이미지를 X축을 기준으로 180도 회전합니다.
    image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

    //기본 JpegOptions 설정을 사용하여 이미지를 JPEG 형식으로 파일 경로에 저장합니다.
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());
}
```

다음 예제는 Aspose.PSD에서 LayerGroup 가시성을 변경하는 방법을 보여줍니다

```csharp
[C#]

string sourceFilePath = "input.psd";
string outputFilePath = "output.psd";

// 레이어 이름을 변경하고 저장합니다
using (var image = (PsdImage)Image.Load(sourceFilePath))
{
    for (int i = 0; i < image.Layers.Length; i++)
    {
        var layer = image.Layers[i];

        // 그룹 내부의 모든 것을 끕니다
        if (layer is LayerGroup)
        {
            layer.IsVisible = false;
        }
    }

    image.Save(outputFilePath);
}
```

다음 예제는 Aspose.PSD에서 단순 생성자 버전을 사용할 경우 새로 만든 레이어에 그릴 수 있는 방법을 보여줍니다

```csharp
[C#]

string outputFilePath = "output.psd";

int width = 100;
int height = 100;
using (var image = new PsdImage(width, height))
{
    var layer = new Layer();
    layer.Bottom = height;
    layer.Right = width;
    image.AddLayer(layer);

    Graphics graphic = new Graphics(layer);
    graphic.Clear(Color.Yellow);

    // Pen 도구로 사각형을 그립니다
    graphic.DrawRectangle(new Pen(Color.Red), new Rectangle(30, 10, 40, 80));

    // Solid Brush를 사용하여 파란색으로 또 다른 사각형을 그립니다
    graphic.DrawRectangle(new Pen(new SolidBrush(Color.Blue)), new Rectangle(10, 30, 80, 40));

    image.Save(outputFilePath);
}
```

다음 예제는 16비트 그레이스케일 PSD 파일을 채널당 16비트 RGB로 읽고 저장하는 것이 올바르게 작동하며 예외 없이 수행됨을 보여줍니다.

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
    // 여기서는 예외가 발생하지 않아야 합니다.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

다음 예제는 16비트 그레이스케일 PSD 파일을 채널당 8비트 그레이스케일로 읽고 저장하는 것이 올바르게 작동하며 예외 없이 수행됨을 보여줍니다.

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
    // 여기서는 예외가 발생하지 않아야 합니다.
    image.Save(pngExportPath, new PngOptions() { ColorType = PngColorType.GrayscaleWithAlpha });
}
```

다음 예제는 Aspose.PSD에서 PassThrough 레이어 혼합 모드를 사용하는 방법을 보여줍니다.

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

다음 예제는 문서 변환 진행 상황이 올바르게 작동하고 예외 없이 수행됨을 보여줍니다.

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

다음 예제는 그레이스케일 16비트 PSD 파일을 읽고 저장하는 것이 올바르게 작동하며 예외 없이 수행됨을 보여줍니다.

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
        // 여기서는 예외가 발생하지 않아야 합니다.
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

### 또 보기

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

객체 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 파일 위치에 저장합니다.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | String | 파일 경로. |
| 옵션 | ImageOptionsBase | 옵션. |
| boundsRectangle | Rectangle | 대상 이미지 경계 사각형입니다. 소스 경계에 사용할 빈 사각형을 설정합니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | 옵션 |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | 이미지 저장에 실패했습니다. |

### 또 보기

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

이미지 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 이미지 데이터를 저장할 스트림. |
| optionsBase | ImageOptionsBase | 저장 옵션. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | 현재 지원되지 않아 지정된 형식으로 저장할 수 없습니다.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | 이미지 내보내기에 실패했습니다. |

## 예제

이 예제는 이미지를 MemoryStream에 저장하는 과정을 보여줍니다. 이 작업을 시연하기 위해, 예제는 디스크의 특정 위치에서 기존 파일을 로드하고, 이미지에 회전 작업을 수행한 뒤 GIF 형식으로 이미지를 저장합니다.

```csharp
[C#]

//MemoryStream의 인스턴스를 생성합니다.
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //이미지 클래스의 인스턴스를 생성하고 파일 경로를 통해 기존 파일로 초기화합니다.
    using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
    {
        //이미지를 X축을 기준으로 180도 회전합니다.
        image.RotateFlip(Aspose.PSD.RotateFlipType.Rotate180FlipX);

        //기본 GifOptions 설정을 사용하여 이미지를 PSD 형식으로 MemoryStream에 저장합니다.
        image.Save(stream, new Aspose.PSD.ImageOptions.GifOptions());
    }
}
```

### 또 보기

* class [ImageOptionsBase](../../imageoptionsbase/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

이미지 데이터를 저장 옵션에 따라 지정된 파일 형식으로 지정된 스트림에 저장합니다.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | 스트림 | 이미지 데이터를 저장할 스트림. |
| optionsBase | ImageOptionsBase | 저장 옵션. |
| boundsRectangle | Rectangle | 대상 이미지 경계 사각형입니다. 빈 사각형을 설정하면 소스 경계를 사용합니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | optionsBase |
| ArgumentException | 현재 지원되지 않아 지정된 형식으로 저장할 수 없습니다.;optionsBase |
| [ImageSaveException](../../../aspose.psd.coreexceptions/imagesaveexception/) | 이미지 내보내기에 실패했습니다. |

### 또 보기

* class [ImageOptionsBase](../../imageoptionsbase/)
* struct [Rectangle](../../rectangle/)
* class [Image](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


