---
title: "Jpeg2000Options 클래스"
type: docs
weight: 50
url: /ko/python-net/aspose.psd.imageoptions/jpeg2000options/
---

**Summary:** The Jpeg2000 file format options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.Jpeg2000Options

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [Jpeg2000Options()](#Jpeg2000Options__1) | 새 인스턴스를 초기화합니다 [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/) 클래스. |
| [Jpeg2000Options(jpeg_2000_options)](#Jpeg2000Options_jpeg_2000_options_2) | 새 인스턴스를 초기화합니다 [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/) 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | 버퍼 크기 힌트를 가져오거나 설정합니다. 이 힌트는 모든 내부 버퍼에 허용되는 최대 크기로 정의됩니다. |
| codec | [Jpeg2000Codec](/psd/python-net/aspose.psd.fileformats.jpeg2000/jpeg2000codec/) | r/w | JPEG2000 코덱을 가져오거나 설정합니다 |
| comments | 문자열 | r/w | Jpeg 주석 마커를 가져오거나 설정합니다. |
| compression_ratios | int | r/w | 압축 비율 배열을 가져오거나 설정합니다.<br/>            연속 레이어에 대한 서로 다른 압축 비율.<br/>            각 품질 수준에 지정된 비율은 원하는<br/>            압축 계수입니다.<br/>            비율 감소가 필요합니다. |
| default_replacement_font | 문자열 | r/w | 기본 교체 글꼴을 가져오거나 설정합니다 (PSD 파일의 기존 레이어 글꼴이 시스템에 없을 경우 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴).<br/>            기본 글꼴의 올바른 이름을 가져오려면 다음 코드 스니펫을 사용할 수 있습니다:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| full_frame | bool | r/w | 전체 프레임인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| irreversible | bool | r/w | 불가역 DWT 9-7을 사용할지 (true) 아니면 무손실 DWT 5-3 압축을 사용할지 여부를 나타내는 값을 가져오거나 설정합니다 (기본값). |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | 다중 페이지 옵션 |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | 색상 팔레트를 가져오거나 설정합니다. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | 해상도 설정을 가져오거나 설정합니다. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP 메타데이터 컨테이너를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [clone()](#clone__1) | 이 인스턴스를 복제합니다. |


### Constructor: Jpeg2000Options() {#Jpeg2000Options__1}


```
 Jpeg2000Options() 
```

새 인스턴스를 초기화합니다 [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/) 클래스.

### Constructor: Jpeg2000Options(jpeg_2000_options) {#Jpeg2000Options_jpeg_2000_options_2}


```
 Jpeg2000Options(jpeg_2000_options) 
```

새 인스턴스를 초기화합니다 [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| jpeg_2000_options | [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options) | 설정을 복사할 Jpeg2000 파일 형식 옵션. |

### Method: clone() {#clone__1}


```
 clone() 
```

이 인스턴스를 복제합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 이 인스턴스의 얕은 복사본을 반환합니다. |


