---
title: Class JpegOptions
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.ImageOptions.JpegOptions 수업. jpeg 파일 형식 생성 옵션.
type: docs
weight: 4840
url: /ko/net/aspose.psd.imageoptions/jpegoptions/
---
## JpegOptions class

jpeg 파일 형식 생성 옵션.

```csharp
public class JpegOptions : ImageOptionsBase
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [JpegOptions](jpegoptions/#constructor)() | 의 새 인스턴스를 초기화합니다.`JpegOptions` 클래스. |
| [JpegOptions](jpegoptions/#constructor_1)(JpegOptions) | 의 새 인스턴스를 초기화합니다.`JpegOptions` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BitsPerChannel](../../aspose.psd.imageoptions/jpegoptions/bitsperchannel/) { get; set; } | 무손실 jpeg 이미지의 채널당 비트를 가져오거나 설정합니다. 이제 채널당 2~8비트를 지원합니다. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 가져오거나 설정합니다. |
| [CmykColorProfile](../../aspose.psd.imageoptions/jpegoptions/cmykcolorprofile/) { get; set; } | CMYK jpeg 이미지의 대상 CMYK 색상 프로필입니다. 이미지 저장에 사용합니다. 올바른 색상 변환을 위해 RGBColorProfile과 쌍을 이루어야 합니다. |
| [ColorType](../../aspose.psd.imageoptions/jpegoptions/colortype/) { get; set; } | jpeg 이미지의 색상 유형을 가져오거나 설정합니다. |
| [Comment](../../aspose.psd.imageoptions/jpegoptions/comment/) { get; set; } | jpeg 파일 설명을 가져오거나 설정합니다. |
| [CompressionType](../../aspose.psd.imageoptions/jpegoptions/compressiontype/) { get; set; } | 압축 유형을 가져오거나 설정합니다. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | 기본 대체 글꼴(PSD 파일의 기존 레이어 글꼴이 시스템에 표시되지 않는 경우 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴)을 가져오거나 설정합니다. 기본 글꼴의 적절한 이름을 사용하려면 다음 코드 스니펫을 사용할 수 있습니다. : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 삭제되었는지 여부를 나타내는 값을 가져옵니다. |
| [ExifData](../../aspose.psd.imageoptions/jpegoptions/exifdata/) { get; set; } | exif 데이터 가져오기 또는 설정 container |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | [전체 프레임]. 여부를 나타내는 값을 가져오거나 설정합니다. |
| [HorizontalSampling](../../aspose.psd.imageoptions/jpegoptions/horizontalsampling/) { get; set; } | 각 구성 요소에 대한 수평 서브샘플링을 가져오거나 설정합니다. |
| [Jfif](../../aspose.psd.imageoptions/jpegoptions/jfif/) { get; set; } | jfif를 가져오거나 설정합니다. |
| [JpegLsAllowedLossyError](../../aspose.psd.imageoptions/jpegoptions/jpeglsallowedlossyerror/) { get; set; } | 거의 무손실 코딩을 위한 JPEG-LS 차이 범위를 가져오거나 설정합니다(JPEG-LS 사양의 NEAR 매개변수). |
| [JpegLsInterleaveMode](../../aspose.psd.imageoptions/jpegoptions/jpeglsinterleavemode/) { get; set; } | JPEG-LS 인터리브 모드를 가져오거나 설정합니다. |
| [JpegLsPreset](../../aspose.psd.imageoptions/jpegoptions/jpeglspreset/) { get; set; } | JPEG-LS 사전 설정 매개변수를 가져오거나 설정합니다. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | 다중 페이지 options |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | 색상표를 가져오거나 설정합니다. |
| [PreblendAlphaIfPresent](../../aspose.psd.imageoptions/jpegoptions/preblendalphaifpresent/) { get; set; } | 알파 채널이 있는 경우 빨간색, 녹색 및 파란색 구성 요소를 배경색과 혼합할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 진행률 이벤트 처리기를 가져오거나 설정합니다. |
| [Quality](../../aspose.psd.imageoptions/jpegoptions/quality/) { get; set; } | 이미지 품질을 가져오거나 설정합니다. |
| [RdOptSettings](../../aspose.psd.imageoptions/jpegoptions/rdoptsettings/) { get; set; } | RD 옵티마이저 설정을 가져오거나 설정합니다. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | 해상도 설정을 가져오거나 설정합니다. |
| [ResolutionUnit](../../aspose.psd.imageoptions/jpegoptions/resolutionunit/) { get; set; } | 해상도 단위를 가져오거나 설정합니다. |
| [RgbColorProfile](../../aspose.psd.imageoptions/jpegoptions/rgbcolorprofile/) { get; set; } | CMYK jpeg 이미지의 대상 RGB 색상 프로필입니다. 이미지 저장에 사용합니다. 올바른 색상 변환을 위해 CMYKColorProfile과 쌍을 이루어야 합니다. |
| [SampleRoundingMode](../../aspose.psd.imageoptions/jpegoptions/sampleroundingmode/) { get; set; } | 8비트 값을 n비트 값에 맞추도록 샘플 반올림 모드를 가져오거나 설정합니다.BitsPerChannel |
| [ScaledQuality](../../aspose.psd.imageoptions/jpegoptions/scaledquality/) { get; } | 배율 조정된 품질입니다. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| [VerticalSampling](../../aspose.psd.imageoptions/jpegoptions/verticalsampling/) { get; set; } | 각 구성 요소에 대한 수직 하위 샘플링을 가져오거나 설정합니다. |
| override [XmpData](../../aspose.psd.imageoptions/jpegoptions/xmpdata/) { get; set; } | XMP 메타데이터 컨테이너를 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | 이 인스턴스를 복제합니다. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 삭제합니다. |

### 예

이 예제는 .Net API용 Aspose.PSD를 사용하여 이미지를 Jpeg 형식으로 변환하는 방법을 보여줍니다. 이 목표를 달성하기 위해 이 예제는 기존 이미지를 로드한 다음 Jpeg 파일 형식으로 변환합니다.

```csharp
[C#]

//이미지 클래스의 인스턴스를 생성하고 파일 경로를 통해 기존 파일로 초기화
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //PsdOptions 클래스의 인스턴스 생성
    Aspose.PSD.ImageOptions.JpegOptions jpegOptions = new Aspose.PSD.ImageOptions.JpegOptions();

    //출력 이미지의 크기를 줄이기 위해 품질을 50%로 설정합니다.
    jpegOptions.Quality = 50;

    //exif 주석을 설정합니다.
    jpegOptions.ExifData = new Aspose.PSD.Exif.JpegExifData();
    jpegOptions.ExifData.Copyright = "This file was created using some custom engine. All rights reserved.";

    //제공된 JpegOptions 설정으로 이미지를 디스크 위치에 저장
    image.Save(@"C:\temp\output.jpeg", jpegOptions);
}
```

이 예제는 System.IO.Stream을 사용하여 새 이미지 파일을 만드는 방법을 보여줍니다.

```csharp
[C#]

//PsdOptions의 인스턴스를 만들고 다양한 속성을 설정합니다.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//System.IO.Stream의 인스턴스 생성
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.psd", System.IO.FileMode.Create);

//PsdOptions 인스턴스의 소스 속성을 정의합니다.
//두 번째 부울 매개변수는 범위를 벗어나면 스트림이 삭제되는지 여부를 결정합니다.
psdOptions.Source = new Aspose.PSD.Sources.StreamSource(stream, true);

//Image 인스턴스를 생성하고 PsdOptions를 매개변수로 사용하여 Create 메서드를 호출하여 Image 객체를 초기화합니다.   
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // 일부 이미지 처리 수행
}
```

이 예제는 내보내기 목적으로 SaveOptions Namespace의 다양한 클래스를 사용하는 방법을 보여줍니다. Psd 유형의 이미지는 Image 인스턴스에 로드된 다음 여러 형식으로 내보내집니다.

```csharp
[C#]

//Image 클래스의 인스턴스에 기존 이미지 로드
using (Aspose.PSD.Image image = Aspose.PSD.Image.Load(@"C:\temp\image.psd"))
{
    //기본 옵션을 사용하여 BMP 파일 형식으로 내보내기
    image.Save(@"C:\temp\output.bmp", new Aspose.PSD.ImageOptions.BmpOptions());

    //기본 옵션을 사용하여 JPEG 파일 형식으로 내보내기
    image.Save(@"C:\temp\output.jpeg", new Aspose.PSD.ImageOptions.JpegOptions());

    //기본 옵션을 사용하여 JPEG 2000 파일 형식으로 내보내기
    image.Save(@"C:\temp\output.jp2", new Aspose.PSD.ImageOptions.Jpeg2000Options());

    //기본 옵션을 사용하여 PNG 파일 형식으로 내보내기
    image.Save(@"C:\temp\output.png", new Aspose.PSD.ImageOptions.PngOptions());

    //기본 옵션을 사용하여 TIFF 파일 형식으로 내보내기
    image.Save(@"c:\temp\output.tiff", new Aspose.PSD.ImageOptions.TiffOptions(Aspose.PSD.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

### 또한보십시오

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* 네임스페이스 [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* 집회 [Aspose.PSD](../../)


