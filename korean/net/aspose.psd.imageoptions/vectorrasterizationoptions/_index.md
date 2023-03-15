---
title: Class VectorRasterizationOptions
second_title: .NET API 참조용 Aspose.PSD
description: Aspose.PSD.ImageOptions.VectorRasterizationOptions 수업. 벡터 래스터화 옵션입니다.
type: docs
weight: 4980
url: /ko/net/aspose.psd.imageoptions/vectorrasterizationoptions/
---
## VectorRasterizationOptions class

벡터 래스터화 옵션입니다.

```csharp
public abstract class VectorRasterizationOptions : ImageOptionsBase
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [BackgroundColor](../../aspose.psd.imageoptions/vectorrasterizationoptions/backgroundcolor/) { get; set; } | 배경색을 가져오거나 설정합니다. |
| [BorderX](../../aspose.psd.imageoptions/vectorrasterizationoptions/borderx/) { get; set; } | 테두리 X를 가져오거나 설정합니다. |
| [BorderY](../../aspose.psd.imageoptions/vectorrasterizationoptions/bordery/) { get; set; } | 테두리 Y를 가져오거나 설정합니다. |
| [BufferSizeHint](../../aspose.psd/imageoptionsbase/buffersizehint/) { get; set; } | 모든 내부 버퍼에 대해 정의된 최대 허용 크기인 버퍼 크기 힌트를 가져오거나 설정합니다. |
| [CenterDrawing](../../aspose.psd.imageoptions/vectorrasterizationoptions/centerdrawing/) { get; set; } | 가운데 그리기 여부를 나타내는 값을 가져오거나 설정합니다. |
| virtual [DefaultReplacementFont](../../aspose.psd/imageoptionsbase/defaultreplacementfont/) { get; set; } | 기본 대체 글꼴(PSD 파일의 기존 레이어 글꼴이 시스템에 표시되지 않는 경우 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴)을 가져오거나 설정합니다. 기본 글꼴의 적절한 이름을 사용하려면 다음 코드 스니펫을 사용할 수 있습니다. : System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection(); System.Drawing.FontFamily[] families = col.Families; string defaultFontName = families[0].Name; PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| [Disposed](../../aspose.psd/disposableobject/disposed/) { get; } | 이 인스턴스가 삭제되었는지 여부를 나타내는 값을 가져옵니다. |
| [DrawColor](../../aspose.psd.imageoptions/vectorrasterizationoptions/drawcolor/) { get; set; } | 전경색을 가져오거나 설정합니다. |
| [FullFrame](../../aspose.psd/imageoptionsbase/fullframe/) { get; set; } | [전체 프레임]. 여부를 나타내는 값을 가져오거나 설정합니다. |
| [MultiPageOptions](../../aspose.psd/imageoptionsbase/multipageoptions/) { get; set; } | 다중 페이지 options |
| [PageHeight](../../aspose.psd.imageoptions/vectorrasterizationoptions/pageheight/) { get; set; } | 페이지 높이를 가져오거나 설정합니다. |
| [PageSize](../../aspose.psd.imageoptions/vectorrasterizationoptions/pagesize/) { get; set; } | 페이지 크기를 가져오거나 설정합니다. |
| [PageWidth](../../aspose.psd.imageoptions/vectorrasterizationoptions/pagewidth/) { get; set; } | 페이지 너비를 가져오거나 설정합니다. |
| virtual [Palette](../../aspose.psd/imageoptionsbase/palette/) { get; set; } | 색상표를 가져오거나 설정합니다. |
| [ProgressEventHandler](../../aspose.psd/imageoptionsbase/progresseventhandler/) { get; set; } | 진행률 이벤트 처리기를 가져오거나 설정합니다. |
| virtual [ResolutionSettings](../../aspose.psd/imageoptionsbase/resolutionsettings/) { get; set; } | 해상도 설정을 가져오거나 설정합니다. |
| [SmoothingMode](../../aspose.psd.imageoptions/vectorrasterizationoptions/smoothingmode/) { get; set; } | 스무딩 모드를 가져오거나 설정합니다. |
| [Source](../../aspose.psd/imageoptionsbase/source/) { get; set; } | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| [TextRenderingHint](../../aspose.psd.imageoptions/vectorrasterizationoptions/textrenderinghint/) { get; set; } | 텍스트 렌더링 힌트를 가져오거나 설정합니다. |
| [VectorRasterizationOptions](../../aspose.psd/imageoptionsbase/vectorrasterizationoptions/) { get; set; } | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| virtual [XmpData](../../aspose.psd/imageoptionsbase/xmpdata/) { get; set; } | XMP 메타데이터 컨테이너를 가져오거나 설정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| virtual [Clone](../../aspose.psd/imageoptionsbase/clone/)() | 이 인스턴스를 복제합니다. |
| [CopyTo](../../aspose.psd.imageoptions/vectorrasterizationoptions/copyto/)(VectorRasterizationOptions) | 복사 대상. |
| [Dispose](../../aspose.psd/disposableobject/dispose/)() | 현재 인스턴스를 삭제합니다. |

### 또한보십시오

* class [ImageOptionsBase](../../aspose.psd/imageoptionsbase/)
* 네임스페이스 [Aspose.PSD.ImageOptions](../../aspose.psd.imageoptions/)
* 집회 [Aspose.PSD](../../)


