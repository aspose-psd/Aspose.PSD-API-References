---
title: "클래스 PngOptions"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.ImageOptions.PngOptions 클래스. PNG 파일 형식 생성 옵션"
type: docs
weight: 5370
url: /ko/net/aspose.psd.imageoptions/pngoptions/
---
{{< psd/tize >}}
## PngOptions class

png 파일 형식 생성 옵션.

```csharp
public class PngOptions : ImageOptionsBase
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PngOptions](pngoptions/#constructor)() | `PngOptions` 클래스의 새 인스턴스를 초기화합니다. |
| [PngOptions](pngoptions/#constructor_1)(PngOptions) | `PngOptions` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BitDepth](../../aspose.psd.imageoptions/pngoptions/bitdepth/) { get; set; } | 비트 깊이입니다. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 가져오거나 설정합니다. |
| [ColorType](../../aspose.psd.imageoptions/pngoptions/colortype/) { get; set; } | 색상의 유형을 가져오거나 설정합니다. |
| [CompressionLevel](../../aspose.psd.imageoptions/pngoptions/compressionlevel/) { get; set; } | 0-9 범위의 PNG 이미지 압축 수준이며, 9는 최대 압축, 0은 저장 모드입니다. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | 기본 대체 폰트를 가져오거나 설정합니다 (PSD 파일의 기존 레이어 폰트가 시스템에 없을 경우 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 폰트). 기본 폰트의 올바른 이름을 가져오려면 다음 코드 스니펫을 사용할 수 있습니다: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [FilterType](../../aspose.psd.imageoptions/pngoptions/filtertype/) { get; set; } | PNG 파일 저장 과정에서 사용되는 필터 유형을 가져오거나 설정합니다. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | 전체 프레임인지 여부를 나타내는 값을 가져오거나 설정합니다 [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | 다중 페이지 옵션 |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | 컬러 팔레트를 가져오거나 설정합니다. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 진행 이벤트 핸들러를 가져오거나 설정합니다. |
| [Progressive](../../aspose.psd.imageoptions/pngoptions/progressive/) { get; set; } | 이 `PngOptions`가 진행형인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | 해상도 설정을 가져오거나 설정합니다. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| override [XmpData](../../aspose.psd.imageoptions/pngoptions/xmpdata/) { get; set; } | XMP 메타데이터 컨테이너를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | 이 인스턴스를 복제합니다. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 해제합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [DefaultCompressionLevel](../../aspose.psd.imageoptions/pngoptions/defaultcompressionlevel/) | 기본 압축 수준입니다. |

## 예제

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

이 예제는 내보내기 목적을 위해 SaveOptions 네임스페이스의 다양한 클래스를 사용하는 방법을 보여줍니다. Psd 형식의 이미지가 Image 인스턴스로 로드된 후 여러 형식으로 내보내집니다.

```csharp
[C#]

//Image 클래스 인스턴스에 기존 이미지를 로드합니다.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //기본 옵션을 사용하여 BMP 파일 형식으로 내보냅니다.
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //기본 옵션을 사용하여 JPEG 파일 형식으로 내보냅니다.
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //기본 옵션을 사용하여 JPEG 2000 파일 형식으로 내보냅니다.
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //기본 옵션을 사용하여 PNG 파일 형식으로 내보냅니다.
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //기본 옵션을 사용하여 TIFF 파일 형식으로 내보냅니다.
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
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

이 예제는 Graphics 클래스를 사용하여 이미지 표면에 기본 도형을 생성합니다. 동작을 보여주기 위해, 예제는 PSD 형식의 새 이미지를 만들고 Graphics 클래스가 제공하는 Draw 메서드를 사용하여 이미지 표면에 기본 도형을 그린 다음 PSD 파일 형식으로 내보냅니다.

```csharp
[C#]

//Image 인스턴스를 생성합니다.
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics 클래스의 인스턴스를 생성하고 초기화합니다.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics 표면을 지웁니다.
    graphics.Clear(Color.Wheat);

    //검은 색을 가진 Pen 객체를 지정하여 호를 그립니다, 
    //호를 둘러싼 사각형, 시작 각도 및 스윕 각도
    graphics.DrawArc(new Pen(Color.Black, 2), new Rectangle(200, 200, 100, 200), 0, 300);

    //파란 색을 가진 Pen 객체와 좌표 포인트를 지정하여 베지어 곡선을 그립니다.
    graphics.DrawBezier(new Pen(Color.Blue, 2), new Point(250, 100), new Point(300, 30), new Point(450, 100), new Point(235, 25));

    //녹색을 가진 Pen 객체와 포인트 배열을 지정하여 곡선을 그립니다
    graphics.DrawCurve(new Pen(Color.Green, 2), new[] { new Point(100, 200), new Point(100, 350), new Point(200, 450) });

    //Pen 객체와 둘러싼 사각형을 사용하여 타원을 그립니다
    graphics.DrawEllipse(new Pen(Color.Yellow, 2), new Rectangle(300, 300, 100, 100));

    //선을 그립니다 
    graphics.DrawLine(new Pen(Color.Violet, 2), new Point(100, 100), new Point(200, 200));

    //파이 조각을 그립니다
    graphics.DrawPie(new Pen(Color.Silver, 2), new Rectangle(new Point(200, 20), new Size(200, 200)), 0, 45);

    //빨간 색을 가진 Pen 객체와 포인트 배열을 지정하여 다각형을 그립니다
    graphics.DrawPolygon(new Pen(Color.Red, 2), new[] { new Point(20, 100), new Point(20, 200), new Point(220, 20) });

    //사각형을 그립니다
    graphics.DrawRectangle(new Pen(Color.Orange, 2), new Rectangle(new Point(250, 250), new Size(100, 100)));

    //SolidBrush 객체를 생성하고 다양한 속성을 설정합니다
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush();
    brush.Color = Color.Purple;
    brush.Opacity = 100;

    //SolidBrush 객체와 폰트를 사용하여 특정 지점에 문자열을 그립니다
    graphics.DrawString("This image is created by Aspose.PSD API", new Font("Times New Roman", 16), brush, new PointF(50, 400));

    //PngOptions의 인스턴스를 생성하고 다양한 속성을 설정합니다
    Aspose.PSD.ImageOptions.PngOptions pngOptions = new Aspose.PSD.ImageOptions.PngOptions();

    // 모든 변경 사항을 저장합니다.
    image.Save("C:\\temp\\output.png", pngOptions);
}
```

### 또 보기

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


