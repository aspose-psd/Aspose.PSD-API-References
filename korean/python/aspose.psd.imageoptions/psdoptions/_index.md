---
title: "PsdOptions 클래스"
type: docs
weight: 100
url: /ko/python-net/aspose.psd.imageoptions/psdoptions/
---

**Summary:** The psd file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PsdOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | 새 인스턴스를 초기화합니다 [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) 클래스. |
| [PsdOptions(image)](#PsdOptions_image_2) | 새 인스턴스를 초기화합니다 [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) 클래스. |
| [PsdOptions(options)](#PsdOptions_options_3) | 새 인스턴스를 초기화합니다 [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| background_contents | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | 배경 색상을 가져오거나 설정합니다.<br/>            투명 객체 아래에서 볼 수 있습니다. |
| buffer_size_hint | int | r/w | 버퍼 크기 힌트를 가져오거나 설정합니다. 이 힌트는 모든 내부 버퍼에 허용되는 최대 크기로 정의됩니다. |
| channel_bits_count | short | r/w | 색 채널당 비트 수를 가져오거나 설정합니다. |
| channels_count | short | r/w | 색 채널 수를 가져오거나 설정합니다. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes/) | r/w | PSD 색 모드를 가져오거나 설정합니다. |
| compression_method | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod/) | r/w | PSD 압축 방식을 가져오거나 설정합니다. |
| default_replacement_font | 문자열 | r/w | 기본 교체 글꼴을 가져오거나 설정합니다 (PSD 파일의 기존 레이어 글꼴이 시스템에 없을 경우 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴).<br/>            기본 글꼴의 올바른 이름을 가져오려면 다음 코드 스니펫을 사용할 수 있습니다:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| full_frame | bool | r/w | 전체 프레임인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | 다중 페이지 옵션 |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | 색상 팔레트를 가져오거나 설정합니다. |
| psd_version | [PsdVersion](/psd/python-net/aspose.psd.fileformats.psd/psdversion/) | r/w | 파일 형식 버전을 가져오거나 설정합니다. PSD 또는 PSB일 수 있습니다. |
| refresh_image_preview_data | bool | r/w | 다른 PSD 이미지 뷰어와의 호환성을 최대화하기 위해 사용되는 [refresh image preview data] 옵션인지 여부를 나타내는 값을 가져오거나 설정합니다.<br/>            참고로, Compact Framework 플랫폼에서는 텍스트 레이어를 최종 레이아웃에 그리는 것이 지원되지 않습니다. |
| remove_global_text_engine_resource | bool | r/w | 글로벌 텍스트 엔진 리소스를 제거할지 여부를 나타내는 값을 가져오거나 설정합니다 - 일부 텍스트 레이어가 있는 PSD 파일에서 처리 후 Adobe Photoshop에서 열 수 없을 때 사용됩니다(주로 누락된 폰트 텍스트 레이어와 관련).<br/>            이 옵션을 사용한 후, 사용자는 Photoshop에서 연 파일에서 다음을 수행해야 합니다: 메뉴 "Text" -> "Process absent fonts". 그 후 모든 텍스트가 다시 표시됩니다.<br/>            이 작업은 최종 레이아웃에 일부 변경을 일으킬 수 있음을 참고하십시오. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | 해상도 설정을 가져오거나 설정합니다. |
| resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock/) | r/w | PSD 리소스를 가져오거나 설정합니다. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| update_metadata | bool | r/w | 이미지를 저장하는 동안 메타데이터를 업데이트할지 여부를 나타내는 값을 가져오거나 설정합니다 [update metadata].<br/>            값이 true이면 메타데이터가 업데이트됩니다. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| version | int | r/w | PSD 파일 버전을 가져오거나 설정합니다. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP 데이터 컨테이너를 가져오거나 설정합니다 |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [clone()](#clone__1) | 이 인스턴스를 복제합니다. |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

새 인스턴스를 초기화합니다 [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) 클래스.

### Constructor: PsdOptions(image) {#PsdOptions_image_2}


```
 PsdOptions(image) 
```

새 인스턴스를 초기화합니다 [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| image | [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) | 이미지입니다. |

### Constructor: PsdOptions(options) {#PsdOptions_options_3}


```
 PsdOptions(options) 
```

새 인스턴스를 초기화합니다 [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions) | 옵션. |

### Method: clone() {#clone__1}


```
 clone() 
```

이 인스턴스를 복제합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 이 인스턴스의 얕은 복사본을 반환합니다. |


