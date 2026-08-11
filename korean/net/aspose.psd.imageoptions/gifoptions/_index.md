---
title: "클래스 GifOptions"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.ImageOptions.GifOptions 클래스. gif 파일 형식 생성 옵션"
type: docs
weight: 5300
url: /ko/net/aspose.psd.imageoptions/gifoptions/
---
{{< psd/tize >}}
## GifOptions class

GIF 파일 형식 생성 옵션입니다.

```csharp
public class GifOptions : ImageOptionsBase
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [GifOptions](gifoptions/#constructor)() | `GifOptions` 클래스의 새 인스턴스를 초기화합니다. |
| [GifOptions](gifoptions/#constructor_1)(GifOptions) | `GifOptions` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BackgroundColorIndex](../../aspose.psd.imageoptions/gifoptions/backgroundcolorindex/) { get; set; } | GIF 배경 색 인덱스를 가져오거나 설정합니다. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 가져오거나 설정합니다. |
| [ColorResolution](../../aspose.psd.imageoptions/gifoptions/colorresolution/) { get; set; } | GIF 색 해상도를 가져오거나 설정합니다. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | 기본 대체 폰트를 가져오거나 설정합니다 (PSD 파일의 기존 레이어 폰트가 시스템에 없을 경우 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 폰트). 기본 폰트의 올바른 이름을 가져오려면 다음 코드 스니펫을 사용할 수 있습니다: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [DoPaletteCorrection](../../aspose.psd.imageoptions/gifoptions/dopalettecorrection/) { get; set; } | 팔레트 보정이 적용되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | 전체 프레임인지 여부를 나타내는 값을 가져오거나 설정합니다 [full frame]. |
| [HasTrailer](../../aspose.psd.imageoptions/gifoptions/hastrailer/) { get; set; } | GIF에 트레일러가 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [Interlaced](../../aspose.psd.imageoptions/gifoptions/interlaced/) { get; set; } | 이미지를 인터레이스해야 하는 경우 true. |
| [IsPaletteSorted](../../aspose.psd.imageoptions/gifoptions/ispalettesorted/) { get; set; } | 팔레트 항목이 정렬되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [MaxDiff](../../aspose.psd.imageoptions/gifoptions/maxdiff/) { get; set; } | 허용되는 최대 픽셀 차이를 가져오거나 설정합니다. 0보다 크면 손실 압축이 사용됩니다. 최적의 손실 압축을 위한 권장 값은 80입니다. 30은 매우 가벼운 압축이며, 200은 강력합니다. 손실이 거의 없을 때 가장 잘 작동하며, 압축 알고리즘의 제한으로 매우 높은 손실 수준에서는 큰 이득을 얻지 못합니다. 허용 값 범위는 [0, 1000]입니다. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | 다중 페이지 옵션 |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | 컬러 팔레트를 가져오거나 설정합니다. |
| [PixelAspectRatio](../../aspose.psd.imageoptions/gifoptions/pixelaspectratio/) { get; set; } | GIF 픽셀 종횡비를 가져오거나 설정합니다. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 진행 이벤트 핸들러를 가져오거나 설정합니다. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | 해상도 설정을 가져오거나 설정합니다. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| override [XmpData](../../aspose.psd.imageoptions/gifoptions/xmpdata/) { get; set; } | XMP 메타데이터 컨테이너를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | 이 인스턴스를 복제합니다. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 해제합니다. |

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

### 또 보기

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


