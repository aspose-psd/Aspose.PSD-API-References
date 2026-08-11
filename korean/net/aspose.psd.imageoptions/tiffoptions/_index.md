---
title: "클래스 TiffOptions"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.ImageOptions.TiffOptions 클래스. tiff 파일 형식 옵션. 이미지 생성 시 너비와 높이 매개변수에 의해 width와 height 태그가 덮어쓰기 되므로 직접 지정할 필요가 없습니다. 많은 옵션이 기본값을 반환하지만 이는 해당 옵션이 태그 값으로 명시적으로 설정된 것을 의미하지 않습니다. 태그가 존재하는지 확인하려면 Tags 속성이나 해당 IsTagPresent 메서드를 사용하십시오."
type: docs
weight: 5430
url: /ko/net/aspose.psd.imageoptions/tiffoptions/
---
{{< psd/tize >}}
## TiffOptions class

tiff 파일 형식 옵션. 이미지 생성 시 너비와 높이 매개변수에 의해 너비와 높이 태그가 덮어쓰기 되므로 직접 지정할 필요가 없습니다. 많은 옵션이 기본값을 반환하지만 이는 해당 옵션이 태그 값으로 명시적으로 설정된 것을 의미하지 않습니다. 태그가 존재하는지 확인하려면 Tags 속성이나 해당 IsTagPresent 메서드를 사용하십시오.

```csharp
public class TiffOptions : ImageOptionsBase
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TiffOptions](tiffoptions/#constructor_2)(TiffDataType[]) | 새 `TiffOptions` 클래스 인스턴스를 초기화합니다. |
| [TiffOptions](tiffoptions/#constructor)(TiffExpectedFormat) | 새 `TiffOptions` 클래스 인스턴스를 초기화합니다. 기본적으로 리틀 엔디안 방식을 사용합니다. |
| [TiffOptions](tiffoptions/#constructor_3)(TiffOptions) | 새 `TiffOptions` 클래스 인스턴스를 초기화합니다. |
| [TiffOptions](tiffoptions/#constructor_1)(TiffExpectedFormat, TiffByteOrder) | 새 `TiffOptions` 클래스 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AlphaStorage](../../aspose.psd.imageoptions/tiffoptions/alphastorage/) { get; set; } | 알파 저장 옵션을 가져오거나 설정합니다. Unspecified가 아닌 옵션은 3개 이상의 [`SamplesPerPixel`](./samplesperpixel/)이 정의된 경우에 사용됩니다. |
| [Artist](../../aspose.psd.imageoptions/tiffoptions/artist/) { get; set; } | 아티스트를 가져오거나 설정합니다. |
| [BitsPerPixel](../../aspose.psd.imageoptions/tiffoptions/bitsperpixel/) { get; } | 픽셀당 비트 수를 가져옵니다. |
| [BitsPerSample](../../aspose.psd.imageoptions/tiffoptions/bitspersample/) { get; set; } | 샘플당 비트를 가져오거나 설정합니다. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 가져오거나 설정합니다. |
| [ByteOrder](../../aspose.psd.imageoptions/tiffoptions/byteorder/) { get; set; } | tiff 바이트 순서를 나타내는 값을 가져오거나 설정합니다. |
| [ColorMap](../../aspose.psd.imageoptions/tiffoptions/colormap/) { get; set; } | 색상 맵을 가져오거나 설정합니다. |
| [CompressedQuality](../../aspose.psd.imageoptions/tiffoptions/compressedquality/) { get; set; } | 압축된 이미지 품질을 가져오거나 설정합니다. Jpeg 압축과 함께 사용됩니다. |
| [Compression](../../aspose.psd.imageoptions/tiffoptions/compression/) { get; set; } | 압축을 가져오거나 설정합니다. |
| [Copyright](../../aspose.psd.imageoptions/tiffoptions/copyright/) { get; set; } | 저작권을 가져오거나 설정합니다. |
| [DateTime](../../aspose.psd.imageoptions/tiffoptions/datetime/) { get; set; } | 날짜와 시간을 가져오거나 설정합니다. |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/tiffoptions/defaultmemoryallocationlimit/) { get; set; } | 기본 메모리 할당 제한을 가져오거나 설정합니다. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | 기본 대체 폰트를 가져오거나 설정합니다 (PSD 파일의 기존 레이어 폰트가 시스템에 없을 경우 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 폰트). 기본 폰트의 올바른 이름을 가져오려면 다음 코드 스니펫을 사용할 수 있습니다: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [DocumentName](../../aspose.psd.imageoptions/tiffoptions/documentname/) { get; set; } | 문서 이름을 가져오거나 설정합니다. |
| [ExifIfd](../../aspose.psd.imageoptions/tiffoptions/exififd/) { get; } | EXIF IFD에 대한 포인터를 가져오거나 설정합니다. |
| [FaxT4Options](../../aspose.psd.imageoptions/tiffoptions/faxt4options/) { get; set; } | 팩스 t4 옵션을 가져오거나 설정합니다. |
| [FileStandard](../../aspose.psd.imageoptions/tiffoptions/filestandard/) { get; set; } | TIFF 파일 표준을 가져오거나 설정합니다. |
| [FillOrder](../../aspose.psd.imageoptions/tiffoptions/fillorder/) { get; set; } | 바이트 비트 채우기 순서를 가져오거나 설정합니다. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | 전체 프레임인지 여부를 나타내는 값을 가져오거나 설정합니다 [full frame]. |
| [HalfToneHints](../../aspose.psd.imageoptions/tiffoptions/halftonehints/) { get; set; } | 하프톤 힌트를 가져오거나 설정합니다. |
| [IccProfile](../../aspose.psd.imageoptions/tiffoptions/iccprofile/) { get; set; } | Icc 프로파일 스트림을 가져오거나 설정합니다. |
| [ImageDescription](../../aspose.psd.imageoptions/tiffoptions/imagedescription/) { get; set; } | 이미지 설명을 가져오거나 설정합니다. |
| [ImageLength](../../aspose.psd.imageoptions/tiffoptions/imagelength/) { get; set; } | 이미지 길이를 가져오거나 설정합니다. |
| [ImageWidth](../../aspose.psd.imageoptions/tiffoptions/imagewidth/) { get; set; } | 이미지 너비를 가져오거나 설정합니다. |
| [InkNames](../../aspose.psd.imageoptions/tiffoptions/inknames/) { get; set; } | 잉크 이름을 가져오거나 설정합니다. |
| [IsExtraSamplesPresent](../../aspose.psd.imageoptions/tiffoptions/isextrasamplespresent/) { get; } | 추가 샘플이 존재하는지 여부를 나타내는 값을 가져옵니다. |
| [IsTiled](../../aspose.psd.imageoptions/tiffoptions/istiled/) { get; } | 이미지가 타일형인지 여부를 나타내는 값을 가져옵니다. |
| [IsValid](../../aspose.psd.imageoptions/tiffoptions/isvalid/) { get; } | `TiffOptions` 가 올바르게 구성되었는지 여부를 나타내는 값을 가져옵니다. 실패 이유를 찾으려면 Validate 메서드를 사용하십시오. |
| [MaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/maxsamplevalue/) { get; set; } | 최대 샘플 값을 가져오거나 설정합니다. |
| [MinSampleValue](../../aspose.psd.imageoptions/tiffoptions/minsamplevalue/) { get; set; } | 최소 샘플 값을 가져오거나 설정합니다. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | 다중 페이지 옵션 |
| [Orientation](../../aspose.psd.imageoptions/tiffoptions/orientation/) { get; set; } | 방향을 가져오거나 설정합니다. |
| [PageName](../../aspose.psd.imageoptions/tiffoptions/pagename/) { get; set; } | 페이지 이름을 가져오거나 설정합니다. |
| [PageNumber](../../aspose.psd.imageoptions/tiffoptions/pagenumber/) { get; set; } | 페이지 번호 태그를 가져오거나 설정합니다. |
| override [Palette](../../aspose.psd.imageoptions/tiffoptions/palette/) { get; set; } | 컬러 팔레트를 가져오거나 설정합니다. |
| [Photometric](../../aspose.psd.imageoptions/tiffoptions/photometric/) { get; set; } | 포토메트릭을 가져오거나 설정합니다. |
| [PlanarConfiguration](../../aspose.psd.imageoptions/tiffoptions/planarconfiguration/) { get; set; } | 플래너 구성을 가져오거나 설정합니다. |
| [Predictor](../../aspose.psd.imageoptions/tiffoptions/predictor/) { get; set; } | LZW 압축에 대한 예측기를 가져오거나 설정합니다. |
| [PremultiplyComponents](../../aspose.psd.imageoptions/tiffoptions/premultiplycomponents/) { get; set; } | 구성 요소를 사전 곱해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 진행 이벤트 핸들러를 가져오거나 설정합니다. |
| override [ResolutionSettings](../../aspose.psd.imageoptions/tiffoptions/resolutionsettings/) { get; set; } | 해상도 설정을 가져오거나 설정합니다. |
| [ResolutionUnit](../../aspose.psd.imageoptions/tiffoptions/resolutionunit/) { get; set; } | 해상도 단위를 가져오거나 설정합니다. |
| [RowsPerStrip](../../aspose.psd.imageoptions/tiffoptions/rowsperstrip/) { get; set; } | 스트립당 행 수를 가져오거나 설정합니다. |
| [SampleFormat](../../aspose.psd.imageoptions/tiffoptions/sampleformat/) { get; set; } | 샘플 형식을 가져오거나 설정합니다. |
| [SamplesPerPixel](../../aspose.psd.imageoptions/tiffoptions/samplesperpixel/) { get; } | 픽셀당 샘플 수를 가져옵니다. 이 속성 값을 변경하려면 [`BitsPerSample`](./bitspersample/) 속성 설정자를 사용하십시오. |
| [ScannerManufacturer](../../aspose.psd.imageoptions/tiffoptions/scannermanufacturer/) { get; set; } | 스캐너 제조업체를 가져오거나 설정합니다. |
| [ScannerModel](../../aspose.psd.imageoptions/tiffoptions/scannermodel/) { get; set; } | 스캐너 모델을 가져오거나 설정합니다. |
| [SmaxSampleValue](../../aspose.psd.imageoptions/tiffoptions/smaxsamplevalue/) { get; set; } | 최대 샘플 값을 가져오거나 설정합니다. 이 값은 샘플 데이터에 가장 적합한 필드 유형(바이트, 쇼트 또는 롱 유형)을 가집니다. |
| [SminSampleValue](../../aspose.psd.imageoptions/tiffoptions/sminsamplevalue/) { get; set; } | 최소 샘플 값을 가져오거나 설정합니다. 이 값은 샘플 데이터에 가장 적합한 필드 유형(바이트, 쇼트 또는 롱 유형)을 가집니다. |
| [SoftwareType](../../aspose.psd.imageoptions/tiffoptions/softwaretype/) { get; set; } | 소프트웨어 유형을 가져오거나 설정합니다. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| [StripByteCounts](../../aspose.psd.imageoptions/tiffoptions/stripbytecounts/) { get; set; } | 스트립 바이트 수를 가져오거나 설정합니다. |
| [StripOffsets](../../aspose.psd.imageoptions/tiffoptions/stripoffsets/) { get; set; } | 스트립 오프셋을 가져오거나 설정합니다. |
| [SubFileType](../../aspose.psd.imageoptions/tiffoptions/subfiletype/) { get; set; } | 이 서브파일에 포함된 데이터 종류에 대한 일반적인 표시를 가져오거나 설정합니다. |
| [Tags](../../aspose.psd.imageoptions/tiffoptions/tags/) { get; set; } | 태그를 가져오거나 설정합니다. |
| [TargetPrinter](../../aspose.psd.imageoptions/tiffoptions/targetprinter/) { get; set; } | 대상 프린터를 가져오거나 설정합니다. |
| [Threshholding](../../aspose.psd.imageoptions/tiffoptions/threshholding/) { get; set; } | 임계값 설정을 가져오거나 설정합니다. |
| [TileByteCounts](../../aspose.psd.imageoptions/tiffoptions/tilebytecounts/) { get; set; } | 타일 바이트 수를 가져오거나 설정합니다. |
| [TileLength](../../aspose.psd.imageoptions/tiffoptions/tilelength/) { get; set; } | 타일 길이를 가져오거나 설정합니다. |
| [TileOffsets](../../aspose.psd.imageoptions/tiffoptions/tileoffsets/) { get; set; } | 타일 오프셋을 가져오거나 설정합니다. |
| [TileWidth](../../aspose.psd.imageoptions/tiffoptions/tilewidth/) { get; set; } | 타일 너비를 가져오거나 설정합니다. |
| [TotalPages](../../aspose.psd.imageoptions/tiffoptions/totalpages/) { get; } | 전체 페이지 수를 가져옵니다. |
| [ValidTagCount](../../aspose.psd.imageoptions/tiffoptions/validtagcount/) { get; } | 유효한 태그 수를 가져옵니다. 이는 전체 태그 수가 아니라 보존될 수 있는 태그 수입니다. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| override [XmpData](../../aspose.psd.imageoptions/tiffoptions/xmpdata/) { get; set; } | XMP 메타데이터 컨테이너를 가져오거나 설정합니다. |
| [XPAuthor](../../aspose.psd.imageoptions/tiffoptions/xpauthor/) { get; set; } | Windows Explorer에서 사용하는 이미지 작성자를 가져오거나 설정합니다. |
| [XPComment](../../aspose.psd.imageoptions/tiffoptions/xpcomment/) { get; set; } | Windows Explorer에서 사용하는 이미지에 대한 주석을 가져오거나 설정합니다. |
| [XPKeywords](../../aspose.psd.imageoptions/tiffoptions/xpkeywords/) { get; set; } | Windows Explorer에서 사용하는 이미지 주제를 가져오거나 설정합니다. |
| [Xposition](../../aspose.psd.imageoptions/tiffoptions/xposition/) { get; set; } | x 위치를 가져오거나 설정합니다. |
| [XPSubject](../../aspose.psd.imageoptions/tiffoptions/xpsubject/) { get; set; } | Windows Explorer에서 사용하는 이미지에 대한 정보를 가져오거나 설정합니다. |
| [XPTitle](../../aspose.psd.imageoptions/tiffoptions/xptitle/) { get; set; } | Windows Explorer에서 사용하는 이미지에 대한 정보를 가져오거나 설정합니다. |
| [Xresolution](../../aspose.psd.imageoptions/tiffoptions/xresolution/) { get; set; } | x 해상도를 가져오거나 설정합니다. |
| [YCbCrCoefficients](../../aspose.psd.imageoptions/tiffoptions/ycbcrcoefficients/) { get; set; } | YCbCrCoefficients를 가져오거나 설정합니다. |
| [YCbCrSubsampling](../../aspose.psd.imageoptions/tiffoptions/ycbcrsubsampling/) { get; set; } | YCbCr 사진 측정에 대한 서브샘플링 계수를 가져오거나 설정합니다. |
| [Yposition](../../aspose.psd.imageoptions/tiffoptions/yposition/) { get; set; } | y 위치를 가져오거나 설정합니다. |
| [Yresolution](../../aspose.psd.imageoptions/tiffoptions/yresolution/) { get; set; } | y 해상도를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddTag](../../aspose.psd.imageoptions/tiffoptions/addtag/)(TiffDataType) | 새 태그를 추가합니다. |
| [AddTags](../../aspose.psd.imageoptions/tiffoptions/addtags/)(TiffDataType[]) | 태그들을 추가합니다. |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | 이 인스턴스를 복제합니다. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 해제합니다. |
| [GetTagByType](../../aspose.psd.imageoptions/tiffoptions/gettagbytype/)(TiffTags) | 형식별 태그 인스턴스를 가져옵니다. |
| [IsTagPresent](../../aspose.psd.imageoptions/tiffoptions/istagpresent/)(TiffTags) | 옵션에 태그가 존재하는지 여부를 결정합니다. |
| [RemoveTag](../../aspose.psd.imageoptions/tiffoptions/removetag/)(TiffTags) | 태그를 제거합니다. |
| [Validate](../../aspose.psd.imageoptions/tiffoptions/validate/)() | 옵션에 유효한 태그 조합이 있는지 검증합니다. |
| static [GetValidTagsCount](../../aspose.psd.imageoptions/tiffoptions/getvalidtagscount/)(TiffDataType[]) | 유효한 태그 수를 가져옵니다. |

## 예제

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

이 예제는 GraphicsPath와 Graphics 클래스를 사용하여 이미지 표면에 도형(Figures)을 생성하고 조작합니다. 예제에서는 새 이미지를 생성하고 GraphicsPath 클래스를 이용해 경로를 그립니다. 마지막에 Graphics 클래스에서 제공하는 DrawPath 메서드를 호출하여 표면에 경로를 렌더링합니다. 최종적으로 이미지는 Tiff 파일 형식으로 내보내집니다.

```csharp
[C#]

//Image 인스턴스를 생성합니다.
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Graphics 클래스의 인스턴스를 생성하고 초기화합니다.
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Graphics 표면을 지웁니다.
    graphics.Clear(Color.Wheat);

    //GraphicsPath 클래스의 인스턴스를 생성합니다.
    Aspose.PSD.GraphicsPath graphicspath = new Aspose.PSD.GraphicsPath();

    //Figure 클래스의 인스턴스를 생성합니다.
    Aspose.PSD.Figure figure = new Aspose.PSD.Figure();

    //Figure 객체에 도형을 추가합니다.
    figure.AddShape(new Aspose.PSD.Shapes.RectangleShape(new RectangleF(10, 10, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.EllipseShape(new RectangleF(50, 50, 300, 300)));
    figure.AddShape(new Aspose.PSD.Shapes.PieShape(new Rectangle(new Point(250, 250), new Size(200, 200)), 0, 45));

    //Figure 객체를 GraphicsPath에 추가합니다.
    graphicspath.AddFigure(figure);

    //검은색 Pen 객체로 경로를 그립니다.
    graphics.DrawPath(new Pen(Aspose.PSD.Color.Black, 2), graphicspath);

    //TiffOptions 인스턴스를 생성하고 다양한 속성을 설정합니다.
    Aspose.PSD.ImageOptions.TiffOptions tiffOptions = new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // 모든 변경 사항을 저장합니다.
    image.Save("C:\\temp\\output.tiff", tiffOptions);
}
```

### 또 보기

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


