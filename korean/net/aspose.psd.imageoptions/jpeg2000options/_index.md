---
title: Class Jpeg2000Options
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.ImageOptions.Jpeg2000Options 수업. Jpeg2000 파일 형식 옵션입니다.
type: docs
weight: 4830
url: /ko/net/aspose.psd.imageoptions/jpeg2000options/
---
## Jpeg2000Options class

Jpeg2000 파일 형식 옵션입니다.

```csharp
public class Jpeg2000Options : ImageOptionsBase
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Jpeg2000Options](jpeg2000options/#constructor)() | 의 새 인스턴스를 초기화합니다.`Jpeg2000Options` 클래스. |
| [Jpeg2000Options](jpeg2000options/#constructor_1)(Jpeg2000Options) | 의 새 인스턴스를 초기화합니다.`Jpeg2000Options` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 가져오거나 설정합니다. |
| [Codec](../../aspose.psd.imageoptions/jpeg2000options/codec/) { get; set; } | JPEG2000 코덱을 얻거나 설정합니다 |
| [Comments](../../aspose.psd.imageoptions/jpeg2000options/comments/) { get; set; } | Jpeg 주석 마커를 가져오거나 설정합니다. |
| [CompressionRatios](../../aspose.psd.imageoptions/jpeg2000options/compressionratios/) { get; set; } | 압축 비율의 배열을 가져오거나 설정합니다. 연속 레이어에 대한 다른 압축 비율. 각 품질 수준에 지정된 비율은 원하는 압축 비율입니다. 비율 감소가 필요합니다. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | 기본 대체 글꼴(PSD 파일의 기존 레이어 글꼴이 시스템에 표시되지 않는 경우 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴)을 가져오거나 설정합니다. 기본 글꼴의 적절한 이름을 사용하려면 다음 코드 스니펫을 사용할 수 있습니다. : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 삭제되었는지 여부를 나타내는 값을 가져옵니다. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | [전체 프레임]. 여부를 나타내는 값을 가져오거나 설정합니다. |
| [Irreversible](../../aspose.psd.imageoptions/jpeg2000options/irreversible/) { get; set; } | 되돌릴 수 없는 DWT 9-7(참) 또는 무손실 DWT 5-3 압축(기본값)을 사용하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | 다중 페이지 options |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | 색상표를 가져오거나 설정합니다. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 진행률 이벤트 처리기를 가져오거나 설정합니다. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | 해상도 설정을 가져오거나 설정합니다. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| override [XmpData](../../aspose.psd.imageoptions/jpeg2000options/xmpdata/) { get; set; } | XMP 메타데이터 컨테이너를 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | 이 인스턴스를 복제합니다. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 삭제합니다. |

### 예

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


