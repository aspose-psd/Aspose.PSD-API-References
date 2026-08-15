---
title: "JpegOptions 클래스"
type: docs
weight: 60
url: /ko/python-net/aspose.psd.imageoptions/jpegoptions/
---

**Summary:** The jpeg file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.JpegOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | 새로운 [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) 클래스 인스턴스를 초기화합니다. |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | 새로운 [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) 클래스 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| bits_per_channel | byte | r/w | 무손실 jpeg 이미지의 채널당 비트를 가져오거나 설정합니다. 현재 2비트부터 8비트까지 지원합니다. |
| buffer_size_hint | int | r/w | 버퍼 크기 힌트를 가져오거나 설정합니다. 이 힌트는 모든 내부 버퍼에 허용되는 최대 크기로 정의됩니다. |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | CMYK jpeg 이미지용 대상 CMYK 색상 프로필입니다. 이미지를 저장할 때 사용합니다. 올바른 색상 변환을 위해 RGBColorProfile과 쌍을 이루어야 합니다. |
| color_type | [JpegCompressionColorMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressioncolormode/) | r/w | jpeg 이미지의 색상 유형을 가져오거나 설정합니다. |
| 주석 | 문자열 | r/w | jpeg 파일 주석을 가져오거나 설정합니다. |
| compression_type | [JpegCompressionMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressionmode/) | r/w | 압축 유형을 가져오거나 설정합니다. |
| default_memory_allocation_limit | int | r/w | 기본 메모리 할당 제한을 가져오거나 설정합니다. |
| default_replacement_font | 문자열 | r/w | 기본 교체 글꼴을 가져오거나 설정합니다 (PSD 파일의 기존 레이어 글꼴이 시스템에 없을 경우 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴).<br/>            기본 글꼴의 올바른 이름을 가져오려면 다음 코드 스니펫을 사용할 수 있습니다:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| exif_data | [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) | r/w | exif 데이터 컨테이너를 가져오거나 설정합니다. |
| full_frame | bool | r/w | 전체 프레임인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| horizontal_sampling | byte | r/w | 각 구성 요소에 대한 수평 서브샘플링을 가져오거나 설정합니다. |
| jfif | [JFIFData](/psd/python-net/aspose.psd.fileformats.jpeg/jfifdata/) | r/w | jfif를 가져오거나 설정합니다. |
| jpeg_ls_allowed_lossy_error | int | r/w | 근손실 코딩을 위한 JPEG-LS 차이 한계값을 가져오거나 설정합니다 (JPEG-LS 사양의 NEAR 매개변수). |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglsinterleavemode/) | r/w | JPEG-LS 인터리브 모드를 가져오거나 설정합니다. |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | JPEG-LS 사전 설정 매개변수를 가져오거나 설정합니다. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | 다중 페이지 옵션 |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | 색상 팔레트를 가져오거나 설정합니다. |
| preblend_alpha_if_present | bool | r/w | 알파 채널이 존재할 경우 빨강, 초록 및 파랑 구성 요소를 배경 색과 혼합할지 여부를 나타내는 값을 가져오거나 설정합니다. |
| quality | int | r/w | 이미지 품질을 가져오거나 설정합니다. |
| rd_opt_settings | [RdOptimizerSettings](/psd/python-net/aspose.psd.imageoptions/rdoptimizersettings) | r/w | RD 옵티마이저 설정을 가져오거나 설정합니다. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | 해상도 설정을 가져오거나 설정합니다. |
| resolution_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit) | r/w | 해상도 단위를 가져오거나 설정합니다. |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | CMYK jpeg 이미지용 대상 RGB 색상 프로필입니다. 이미지를 저장할 때 사용합니다. 올바른 색상 변환을 위해 CMYKColorProfile과 쌍을 이루어야 합니다. |
| sample_rounding_mode | [SampleRoundingMode](/psd/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/) | r/w | 8비트 값을 n비트 값에 맞추기 위한 샘플 반올림 모드를 가져오거나 설정합니다. <see cref=\"P:JpegOptions.BitsPerChannel\" /> |
| scaled_quality | int | r | 스케일된 품질. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| vertical_sampling | byte | r/w | 각 구성 요소에 대한 수직 서브샘플링을 가져오거나 설정합니다. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP 메타데이터 컨테이너를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [clone()](#clone__1) | 이 인스턴스를 복제합니다. |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

새로운 [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) 클래스 인스턴스를 초기화합니다.

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

새로운 [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions) | JPEG 옵션. |

### Method: clone() {#clone__1}


```
 clone() 
```

이 인스턴스를 복제합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 이 인스턴스의 얕은 복사본을 반환합니다. |


