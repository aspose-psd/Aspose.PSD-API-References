---
title: "PngOptions 클래스"
type: docs
weight: 90
url: /ko/python-net/aspose.psd.imageoptions/pngoptions/
---

**Summary:** The png file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PngOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [PngOptions()](#PngOptions__1) | 새로운 [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) 클래스 인스턴스를 초기화합니다. |
| [PngOptions(png_options)](#PngOptions_png_options_2) | 새로운 [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) 클래스 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | int | r | 기본 압축 수준. |
| bit_depth | byte | r/w | 비트 깊이. |
| buffer_size_hint | int | r/w | 버퍼 크기 힌트를 가져오거나 설정합니다. 이 힌트는 모든 내부 버퍼에 허용되는 최대 크기로 정의됩니다. |
| color_type | [PngColorType](/psd/python-net/aspose.psd.fileformats.png/pngcolortype/) | r/w | 색상의 유형을 가져오거나 설정합니다. |
| compression_level | int | r/w | 0-9 범위의 PNG 이미지 압축 수준이며, 9는 최대 압축, 0은 저장 모드입니다. |
| default_replacement_font | 문자열 | r/w | 기본 교체 글꼴을 가져오거나 설정합니다 (PSD 파일의 기존 레이어 글꼴이 시스템에 없을 경우 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴).<br/>            기본 글꼴의 올바른 이름을 가져오려면 다음 코드 스니펫을 사용할 수 있습니다:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| filter_type | [PngFilterType](/psd/python-net/aspose.psd.fileformats.png/pngfiltertype/) | r/w | PNG 파일 저장 과정에서 사용되는 필터 유형을 가져오거나 설정합니다. |
| full_frame | bool | r/w | 전체 프레임인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | 다중 페이지 옵션 |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | 색상 팔레트를 가져오거나 설정합니다. |
| progressive | bool | r/w | 이 [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/)가 진행형인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | 해상도 설정을 가져오거나 설정합니다. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP 메타데이터 컨테이너를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [clone()](#clone__1) | 이 인스턴스를 복제합니다. |


### Constructor: PngOptions() {#PngOptions__1}


```
 PngOptions() 
```

새로운 [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) 클래스 인스턴스를 초기화합니다.

### Constructor: PngOptions(png_options) {#PngOptions_png_options_2}


```
 PngOptions(png_options) 
```

새로운 [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| png_options | [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions) | PNG 옵션입니다. |

### Method: clone() {#clone__1}


```
 clone() 
```

이 인스턴스를 복제합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 이 인스턴스의 얕은 복사본을 반환합니다. |


