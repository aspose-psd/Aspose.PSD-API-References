---
title: "TiffOptions 클래스"
type: docs
weight: 130
url: /ko/python-net/aspose.psd.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.TiffOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **설명** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | 새 인스턴스를 초기화합니다 [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) 클래스. 기본적으로 리틀 엔디안 방식이 사용됩니다. |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | 새 인스턴스를 초기화합니다 [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) 클래스. |
| [TiffOptions(options)](#TiffOptions_options_3) | 새 인스턴스를 초기화합니다 [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) 클래스. |
| [TiffOptions(tags)](#TiffOptions_tags_4) | 새 인스턴스를 초기화합니다 [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) 클래스. |
## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/) | r/w | 알파 저장 옵션을 가져오거나 설정합니다. [TiffAlphaStorage.UNSPECIFIED](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/) 이외의 옵션은 <br/>            3개 이상의 [TiffOptions.samples_per_pixel](/psd/python-net/aspose.psd.imageoptions/tiffoptions/)가 정의된 경우에 사용됩니다. |
| artist | 문자열 | r/w | 아티스트를 가져오거나 설정합니다. |
| bits_per_pixel | int | r | 픽셀당 비트를 가져옵니다. |
| bits_per_sample | ushort | r/w | 샘플당 비트를 가져오거나 설정합니다. |
| buffer_size_hint | int | r/w | 버퍼 크기 힌트를 가져오거나 설정합니다. 이 힌트는 모든 내부 버퍼에 허용되는 최대 크기로 정의됩니다. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | r/w | TIFF 바이트 순서를 나타내는 값을 가져오거나 설정합니다. |
| color_map | ushort | r/w | 색상 맵을 가져오거나 설정합니다. |
| compressed_quality | int | r/w | 압축된 이미지 품질을 가져오거나 설정합니다.<br/>            Jpeg 압축과 함께 사용됩니다. |
| compression | [TiffCompressions](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffcompressions/) | r/w | 압축을 가져오거나 설정합니다. |
| copyright | 문자열 | r/w | 저작권 정보를 가져오거나 설정합니다. |
| date_time | 문자열 | r/w | 날짜와 시간을 가져오거나 설정합니다. |
| default_memory_allocation_limit | int | r/w | 기본 메모리 할당 제한을 가져오거나 설정합니다. |
| default_replacement_font | 문자열 | r/w | 기본 교체 글꼴을 가져오거나 설정합니다 (PSD 파일의 기존 레이어 글꼴이 시스템에 없을 경우 래스터로 내보낼 때 텍스트를 그리는 데 사용되는 글꼴).<br/>            기본 글꼴의 올바른 이름을 가져오려면 다음 코드 스니펫을 사용할 수 있습니다:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| document_name | 문자열 | r/w | 문서 이름을 가져오거나 설정합니다. |
| exif_ifd | [TiffExifIfd](/psd/python-net/aspose.psd.fileformats.tiff/tiffexififd/) | r | EXIF IFD에 대한 포인터를 가져오거나 설정합니다. |
| fax_t4_options | [Group3Options](/psd/python-net/aspose.psd.fileformats.tiff.enums/group3options/) | r/w | 팩스 T4 옵션을 가져오거나 설정합니다. |
| file_standard | [TiffFileStandards](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffilestandards/) | r/w | TIFF 파일 표준을 가져오거나 설정합니다. |
| fill_order | [TiffFillOrders](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffillorders/) | r/w | 바이트 비트 채우기 순서를 가져오거나 설정합니다. |
| full_frame | bool | r/w | 전체 프레임인지 여부를 나타내는 값을 가져오거나 설정합니다. |
| half_tone_hints | ushort | r/w | 하프톤 힌트를 가져오거나 설정합니다. |
| image_description | 문자열 | r/w | 이미지 설명을 가져오거나 설정합니다. |
| image_length | uint | r/w | 이미지 길이를 가져오거나 설정합니다. |
| image_width | uint | r/w | 이미지 너비를 가져오거나 설정합니다. |
| ink_names | 문자열 | r/w | 잉크 이름을 가져오거나 설정합니다. |
| is_extra_samples_present | bool | r | 추가 샘플이 존재하는지 여부를 나타내는 값을 가져옵니다. |
| is_tiled | bool | r | 이미지가 타일 형식인지 여부를 나타내는 값을 가져옵니다. |
| is_valid | bool | r | Gets a value indicating whether the [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/)가 올바르게 구성되었는지 여부를 나타내는 값을 가져옵니다. 실패 원인을 찾으려면 Validate 메서드를 사용하십시오. |
| max_sample_value | ushort | r/w | 최대 샘플 값을 가져오거나 설정합니다. |
| min_sample_value | ushort | r/w | 최소 샘플 값을 가져오거나 설정합니다. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | 다중 페이지 옵션 |
| orientation | [TiffOrientations](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifforientations/) | r/w | 방향을 가져오거나 설정합니다. |
| page_name | 문자열 | r/w | 페이지 이름을 가져오거나 설정합니다. |
| page_number | ushort | r/w | 페이지 번호 태그를 가져오거나 설정합니다. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | 색상 팔레트를 가져오거나 설정합니다. |
| photometric | [TiffPhotometrics](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffphotometrics/) | r/w | 포토메트릭을 가져오거나 설정합니다. |
| planar_configuration | [TiffPlanarConfigs](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | 플래너 구성을 가져오거나 설정합니다. |
| predictor | [TiffPredictor](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffpredictor/) | r/w | LZW 압축에 대한 프레디케이터를 가져오거나 설정합니다. |
| premultiply_components | bool | r/w | 구성 요소를 사전 곱해야 하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | 해상도 설정을 가져오거나 설정합니다. |
| resolution_unit | [TiffResolutionUnits](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffresolutionunits/) | r/w | 해상도 단위를 가져오거나 설정합니다. |
| rows_per_strip | uint | r/w | 스트립당 행 수를 가져오거나 설정합니다. |
| sample_format | [TiffSampleFormats[]](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffsampleformats/) | r/w | 샘플 형식을 가져오거나 설정합니다. |
| samples_per_pixel | ushort | r | 픽셀당 샘플 수를 가져옵니다. 이 속성 값을 변경하려면 [TiffOptions.bits_per_sample](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) 속성 설정자를 사용하십시오. |
| scanner_manufacturer | 문자열 | r/w | 스캐너 제조사를 가져오거나 설정합니다. |
| scanner_model | 문자열 | r/w | 스캐너 모델을 가져오거나 설정합니다. |
| smax_sample_value | uint | r/w | 최대 샘플 값을 가져오거나 설정합니다. 이 값은 샘플 데이터에 가장 적합한 필드 유형(바이트, 쇼트 또는 롱 유형)을 가집니다. |
| smin_sample_value | uint | r/w | 최소 샘플 값을 가져오거나 설정합니다. 이 값은 샘플 데이터에 가장 적합한 필드 유형(바이트, 쇼트 또는 롱 유형)을 가집니다. |
| software_type | 문자열 | r/w | 소프트웨어 유형을 가져오거나 설정합니다. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | 이미지를 생성할 소스를 가져오거나 설정합니다. |
| strip_byte_counts | uint | r/w | 스트립 바이트 수를 가져오거나 설정합니다. |
| strip_offsets | uint | r/w | 스트립 오프셋을 가져오거나 설정합니다. |
| sub_file_type | [TiffNewSubFileTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | 이 서브파일에 포함된 데이터 종류에 대한 일반적인 표시를 가져오거나 설정합니다. |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | 태그를 가져오거나 설정합니다. |
| target_printer | 문자열 | r/w | 대상 프린터를 가져오거나 설정합니다. |
| threshholding | [TiffThresholds](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffthresholds/) | r/w | 임계값 설정을 가져오거나 설정합니다. |
| tile_byte_counts | uint | r/w | 타일 바이트 수를 가져오거나 설정합니다. |
| tile_length | uint | r/w | 타일 길이를 가져오거나 설정합니다. |
| tile_offsets | uint | r/w | 타일 오프셋을 가져오거나 설정합니다. |
| tile_width | uint | r/w | 타일 너비를 가져오거나 설정합니다. |
| total_pages | ushort | r | 전체 페이지 수를 가져옵니다. |
| valid_tag_count | int | r | 유효한 태그 수를 가져옵니다. 이는 전체 태그 수가 아니라 보존될 수 있는 태그 수입니다. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | 벡터 래스터화 옵션을 가져오거나 설정합니다. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP 메타데이터 컨테이너를 가져오거나 설정합니다. |
| xp_author | 문자열 | r/w | 이미지 작성자를 가져오거나 설정합니다. Windows Explorer에서 사용됩니다. |
| xp_comment | 문자열 | r/w | 이미지에 대한 주석을 가져오거나 설정합니다. Windows Explorer에서 사용됩니다. |
| xp_keywords | 문자열 | r/w | 이미지 주제를 가져오거나 설정합니다. Windows Explorer에서 사용됩니다. |
| xp_subject | 문자열 | r/w | 이미지에 대한 정보를 가져오거나 설정합니다. Windows Explorer에서 사용됩니다. |
| xp_title | 문자열 | r/w | 이미지에 대한 정보를 가져오거나 설정합니다. Windows Explorer에서 사용됩니다. |
| xposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | x 위치를 가져오거나 설정합니다. |
| xresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | x 해상도를 가져오거나 설정합니다. |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | YCbCrCoefficients를 가져오거나 설정합니다. |
| y_cb_cr_subsampling | ushort | r/w | YCbCr 사진 측정에 대한 서브샘플링 계수를 가져오거나 설정합니다. |
| yposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | y 위치를 가져오거나 설정합니다. |
| yresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | y 해상도를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | 새 태그를 추가합니다. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | 태그를 추가합니다. |
| [clone()](#clone__3) | 이 인스턴스를 복제합니다. |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_4) | 유형별 태그 인스턴스를 가져옵니다. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_5) | 유효한 태그 수를 가져옵니다. |
| [is_tag_present(tag)](#is_tag_present_tag_6) | 옵션에 태그가 존재하는지 여부를 결정합니다. |
| [remove_tag(tag)](#remove_tag_tag_7) | 태그를 제거합니다. |
| validate() | 옵션에 유효한 태그 조합이 있는지 검증합니다. |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

새 인스턴스를 초기화합니다 [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) 클래스. 기본적으로 리틀 엔디안 방식이 사용됩니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | 예상되는 TIFF 파일 형식. |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

새 인스턴스를 초기화합니다 [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | 예상되는 TIFF 파일 형식. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | 사용할 TIFF 파일 형식의 바이트 순서입니다. |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

새 인스턴스를 초기화합니다 [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| options | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions) | 복사할 옵션입니다. |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

새 인스턴스를 초기화합니다 [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) 클래스.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | 옵션을 초기화할 때 사용할 태그. |

### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

새 태그를 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | 추가할 태그. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

태그를 추가합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | 추가할 태그들. |

### Method: clone() {#clone__3}


```
 clone() 
```

이 인스턴스를 복제합니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 이 인스턴스의 얕은 복사본을 반환합니다. |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_4}


```
 get_tag_by_type(tag_key) 
```

유형별 태그 인스턴스를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| tag_key | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | 태그 키. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | 태그가 존재하면 해당 인스턴스, 없으면 null. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_5}


```
 get_valid_tags_count(tags) 
```

유효한 태그 수를 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | 검증할 태그. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| int | 유효한 태그 수. |


### Method: is_tag_present(tag) {#is_tag_present_tag_6}


```
 is_tag_present(tag) 
```

옵션에 태그가 존재하는지 여부를 결정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | 확인할 태그 ID. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 태그가 존재하면 <c>true</c>, 그렇지 않으면 <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_7}


```
 remove_tag(tag) 
```

태그를 제거합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | 제거할 태그. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | 제거에 성공하면 true |


