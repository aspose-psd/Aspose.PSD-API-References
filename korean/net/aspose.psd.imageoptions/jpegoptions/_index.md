---
title: "JpegOptions 클래스"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.ImageOptions.JpegOptions 클래스. jpeg 파일 형식 생성 옵션"
type: docs
weight: 5330
url: /ko/net/aspose.psd.imageoptions/jpegoptions/
---
{{< psd/tize >}}
## JpegOptions class

jpeg 파일 형식 생성 옵션.

```csharp
public class JpegOptions : ImageOptionsBase
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | `JpegOptions` 클래스의 새 인스턴스를 초기화합니다. |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | `JpegOptions` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | 무손실 jpeg 이미지의 채널당 비트를 가져오거나 설정합니다. 현재 2비트에서 8비트까지 지원합니다. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 가져오거나 설정합니다. |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | CMYK jpeg 이미지용 대상 CMYK 색 프로파일입니다. 이미지를 저장할 때 사용합니다. 올바른 색 변환을 위해 RGBColorProfile와 쌍을 이루어야 합니다. |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | jpeg 이미지의 색 유형을 가져오거나 설정합니다. |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | jpeg 파일 주석을 가져오거나 설정합니다. |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | 압축 유형을 가져오거나 설정합니다. |
| [DefaultMemoryAllocationLimit](../../aspose.psd.imageoptions/jpegoptions/defaultmemoryallocationlimit/) { get; set; } | 기본 메모리 할당 제한을 가져오거나 설정합니다. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | 기본 대체 폰트를 가져오거나 설정합니다 (PSD 파일의 기존 레이어 폰트가 시스템에 없을 경우 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 폰트). 기본 폰트의 올바른 이름을 가져오려면 다음 코드 스니펫을 사용할 수 있습니다: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | exif 데이터 컨테이너를 가져오거나 설정합니다. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | 전체 프레임인지 여부를 나타내는 값을 가져오거나 설정합니다 [full frame]. |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | 각 구성 요소에 대한 수평 서브샘플링을 가져오거나 설정합니다. |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | jfif를 가져오거나 설정합니다. |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | 근손실 코딩을 위한 JPEG-LS 차이 한계값을 가져오거나 설정합니다 (JPEG-LS 사양의 NEAR 매개변수). |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | JPEG-LS 인터리브 모드를 가져오거나 설정합니다. |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | JPEG-LS 사전 설정 매개변수를 가져오거나 설정합니다. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | 다중 페이지 옵션 |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | 컬러 팔레트를 가져오거나 설정합니다. |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | 알파 채널이 존재하는 경우, 빨강, 초록 및 파랑 구성 요소를 배경 색과 혼합할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 진행 이벤트 핸들러를 가져오거나 설정합니다. |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | 이미지 품질을 가져오거나 설정합니다. |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | RD 옵티마이저 설정을 가져오거나 설정합니다. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | 해상도 설정을 가져오거나 설정합니다. |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | 해상도 단위를 가져오거나 설정합니다. |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | CMYK JPEG 이미지용 대상 RGB 색상 프로파일입니다. 이미지를 저장할 때 사용합니다. 올바른 색상 변환을 위해 CMYKColorProfile와 쌍을 이루어야 합니다. |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | 8비트 값을 n비트 값에 맞추기 위한 샘플 반올림 모드를 가져오거나 설정합니다. BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | 스케일된 품질. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | 각 구성 요소에 대한 수직 서브샘플링을 가져오거나 설정합니다. |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | XMP 메타데이터 컨테이너를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | 이 인스턴스를 복제합니다. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 해제합니다. |

## 예제

이 예제는 Aspose.PSD for .Net API를 사용하여 이미지를 JPEG 형식으로 변환하는 방법을 보여줍니다. 이를 위해 이 예제는 기존 이미지를 로드한 다음 JPEG 파일 형식으로 변환합니다.

```csharp
[C#]

//이미지 클래스의 인스턴스를 생성하고 파일 경로를 통해 기존 파일로 초기화합니다.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //PsdOptions 클래스의 인스턴스를 생성합니다.
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    //출력 이미지의 크기를 줄이기 위해 품질을 50%로 설정합니다.
    jpegOptions.Quality = 50;

    //EXIF 주석을 설정합니다.
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //제공된 JpegOptions 설정을 사용하여 이미지를 디스크 위치에 저장합니다.
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

이 예제는 System.IO.Stream을 사용하여 새 이미지 파일을 생성하는 방법을 보여줍니다.

```csharp
[C#]

//PsdOptions의 인스턴스를 생성하고 다양한 속성을 설정합니다.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//System.IO.Stream의 인스턴스를 생성합니다.
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//PsdOptions 인스턴스의 source 속성을 정의합니다.
//두 번째 부울 매개변수는 스트림이 범위를 벗어나면 폐기되는지를 결정합니다.
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Image의 인스턴스를 생성하고 PsdOptions를 매개변수로 전달하여 Create 메서드를 호출해 Image 객체를 초기화합니다.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //이미지 처리를 수행합니다.
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

### 또 보기

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


