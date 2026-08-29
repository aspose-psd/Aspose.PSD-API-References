---
title: "클래스 PdfOptions"
second_title: "Aspose.PSD for .NET API 레퍼런스"
description: "Aspose.PSD.ImageOptions.PdfOptions 클래스. PDF 옵션"
type: docs
weight: 5360
url: /ko/net/aspose.psd.imageoptions/pdfoptions/
---
{{< psd/tize >}}
## PdfOptions class

PDF 옵션.

```csharp
public class PdfOptions : ImageOptionsBase
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfOptions](pdfoptions/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 가져오거나 설정합니다. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | 기본 대체 폰트를 가져오거나 설정합니다 (PSD 파일의 기존 레이어 폰트가 시스템에 없을 경우 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 폰트). 기본 폰트의 올바른 이름을 가져오려면 다음 코드 스니펫을 사용할 수 있습니다: System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | 전체 프레임인지 여부를 나타내는 값을 가져오거나 설정합니다 [full frame]. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | 다중 페이지 옵션 |
| [PageSize](../../aspose.psd.imageoptions/pdfoptions/pagesize/) { get; set; } | 페이지 크기를 가져오거나 설정합니다. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | 컬러 팔레트를 가져오거나 설정합니다. |
| [PdfCoreOptions](../../aspose.psd.imageoptions/pdfoptions/pdfcoreoptions/) { get; set; } | PDF 핵심 옵션 |
| [PdfDocumentInfo](../../aspose.psd.imageoptions/pdfoptions/pdfdocumentinfo/) { get; set; } | 문서 메타데이터를 가져오거나 설정합니다. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 진행 이벤트 핸들러를 가져오거나 설정합니다. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | 해상도 설정을 가져오거나 설정합니다. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | XMP 메타데이터 컨테이너를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | 이 인스턴스를 복제합니다. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 해제합니다. |

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

다음 예제는 PsdImage를 PDF 형식으로 내보내는 지원을 보여줍니다.

```csharp
[C#]

string[] sourcesFiles = new string[]
{
    @"1.psd",
    @"little.psb",
    @"psb3.psb",
    @"inRgb16.psd",
    @"ALotOfElementTypes.psd",
    @"ColorOverlayAndShadowAndMask.psd",
    @"ThreeRegularLayersSemiTransparent.psd"
};
for (int i = 0; i < sourcesFiles.Length; i++)
{
    string sourceFileName = sourcesFiles[i];
    using (PsdImage image = (PsdImage)Image.Load(sourceFileName))
    {
        string outFileName = "PsdToPdf" + i + ".pdf";
        image.Save(outFileName, new PdfOptions());
    }
}
```

### 또 보기

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* namespace [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../)


