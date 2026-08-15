---
title: "GifOptions 클래스"
type: docs
weight: 30
url: /ko/python-net/aspose.psd.imageoptions/gifoptions/
---

**Summary:** The gif file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.GifOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | 새로운 [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) 클래스 인스턴스를 초기화합니다. |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | 새로운 [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) 클래스 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| background_color_index | byte | r/w | GIF 배경 색 인덱스를 가져오거나 설정합니다. |
| buffer_size_hint | int | r/w | 버퍼 크기 힌트를 가져오거나 설정합니다. 이 힌트는 모든 내부 버퍼에 허용되는 최대 크기로 정의됩니다. |
| color_resolution | byte | r/w | GIF 색 해상도를 가져오거나 설정합니다. |
| default_replacement_font | 문자열 | r/w | 기본 교체 글꼴을 가져오거나 설정합니다 (PSD 파일의 기존 레이어 글꼴이 시스템에 없을 경우 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴).<br/>            기본 글꼴의 올바른 이름을 가져오려면 다음 코드 스니펫을 사용할 수 있습니다:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| do_palette_correction | bool | r/w | 팔레트 보정이 적용되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| full_frame | bool | r/w | 전체 프레임인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| has_trailer | bool | r/w | GIF에 트레일러가 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| interlaced | bool | r/w | 이미지를 인터레이스해야 하는 경우 true. |
| is_palette_sorted | bool | r/w | 팔레트 항목이 정렬되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| max_diff | int | r/w | 허용되는 최대 픽셀 차이를 가져오거나 설정합니다. 0보다 크면 손실 압축이 사용됩니다.<br/>            최적의 손실 압축을 위한 권장 값은 80입니다. 30은 매우 가벼운 압축이며, 200은 강한 압축입니다.<br/>            손실이 거의 도입되지 않을 때 가장 잘 작동하며, 압축 알고리즘의 제한으로 인해 매우 높은 손실 수준에서는 큰 이득을 얻지 못합니다.<br/>            허용값 범위는 [0, 1000]입니다. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | 다중 페이지 옵션 |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | 색상 팔레트를 가져오거나 설정합니다. |
| pixel_aspect_ratio | byte | r/w | GIF 픽셀 종횡비를 가져오거나 설정합니다. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | 해상도 설정을 가져오거나 설정합니다. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP 메타데이터 컨테이너를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [clone()](#clone__1) | 이 인스턴스를 복제합니다. |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

새로운 [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) 클래스 인스턴스를 초기화합니다.

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

새로운 [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| gif_options | [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions) | GIF 옵션. |

### Method: clone() {#clone__1}


```
 clone() 
```

이 인스턴스를 복제합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 이 인스턴스의 얕은 복사본을 반환합니다. |


