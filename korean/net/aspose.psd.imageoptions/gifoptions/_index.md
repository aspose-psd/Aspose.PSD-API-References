---
title: Class GifOptions
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.ImageOptions.GifOptions 수업. gif 파일 형식 생성 옵션입니다.
type: docs
weight: 4810
url: /ko/net/aspose.psd.imageoptions/gifoptions/
---
## GifOptions class

gif 파일 형식 생성 옵션입니다.

```csharp
public class GifOptions : ImageOptionsBase
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [GifOptions](gifoptions/#constructor)() | 의 새 인스턴스를 초기화합니다.`GifOptions` 클래스. |
| [GifOptions](gifoptions/#constructor_1)(GifOptions) | 의 새 인스턴스를 초기화합니다.`GifOptions` 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BackgroundColorIndex](../../aspose.psd.imageoptions/gifoptions/backgroundcolorindex/) { get; set; } | GIF 배경색 인덱스를 가져오거나 설정합니다. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 가져오거나 설정합니다. |
| [ColorResolution](../../aspose.psd.imageoptions/gifoptions/colorresolution/) { get; set; } | GIF 색상 해상도를 가져오거나 설정합니다. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | 기본 대체 글꼴(PSD 파일의 기존 레이어 글꼴이 시스템에 표시되지 않는 경우 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴)을 가져오거나 설정합니다. 기본 글꼴의 적절한 이름을 사용하려면 다음 코드 스니펫을 사용할 수 있습니다. : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 삭제되었는지 여부를 나타내는 값을 가져옵니다. |
| [DoPaletteCorrection](../../aspose.psd.imageoptions/gifoptions/dopalettecorrection/) { get; set; } | 팔레트 보정 적용 여부를 나타내는 값을 가져오거나 설정합니다. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | [전체 프레임]. 여부를 나타내는 값을 가져오거나 설정합니다. |
| [HasTrailer](../../aspose.psd.imageoptions/gifoptions/hastrailer/) { get; set; } | GIF에 트레일러가 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [Interlaced](../../aspose.psd.imageoptions/gifoptions/interlaced/) { get; set; } | 이미지가 인터레이스되어야 하는 경우 True입니다. |
| [IsPaletteSorted](../../aspose.psd.imageoptions/gifoptions/ispalettesorted/) { get; set; } | 팔레트 항목이 정렬되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [MaxDiff](../../aspose.psd.imageoptions/gifoptions/maxdiff/) { get; set; } | 허용되는 최대 픽셀 차이를 가져오거나 설정합니다. 0보다 크면 손실 압축이 사용됩니다. 최적의 손실 압축에 대한 권장 값은 80입니다. 30은 매우 가벼운 압축이고 200은 무겁습니다. 압축 알고리즘의 제한으로 인해 손실이 거의 없을 때 가장 잘 작동합니다. 매우 높은 손실 수준은 많은 이득을 제공하지 않습니다. 허용되는 값의 범위는 [0, 1000]입니다. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | 다중 페이지 options |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | 색상표를 가져오거나 설정합니다. |
| [PixelAspectRatio](../../aspose.psd.imageoptions/gifoptions/pixelaspectratio/) { get; set; } | GIF 픽셀 종횡비를 가져오거나 설정합니다. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 진행률 이벤트 처리기를 가져오거나 설정합니다. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | 해상도 설정을 가져오거나 설정합니다. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| override [XmpData](../../aspose.psd.imageoptions/gifoptions/xmpdata/) { get; set; } | XMP 메타데이터 컨테이너를 가져오거나 설정합니다. |

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


