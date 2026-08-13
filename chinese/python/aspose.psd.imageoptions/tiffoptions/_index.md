---
title: "TiffOptions 类"
type: docs
weight: 130
url: /zh/python-net/aspose.psd.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.TiffOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | 初始化 [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) 类的新实例。默认使用小端序约定。 |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | 初始化 [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) 类的新实例。 |
| [TiffOptions(options)](#TiffOptions_options_3) | 初始化 [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) 类的新实例。 |
| [TiffOptions(tags)](#TiffOptions_tags_4) | 初始化 [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/) | r/w | 获取或设置 alpha 存储选项。除 [TiffAlphaStorage.UNSPECIFIED](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/) 之外的选项<br/>            当定义了超过 3 个 [TiffOptions.samples_per_pixel](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) 时使用。 |
| 艺术家 | 字符串 | 读/写 | 获取或设置艺术家。 |
| bits_per_pixel | int | r | 获取每像素位数。 |
| bits_per_sample | ushort | 读/写 | 获取或设置每个样本的位数。 |
| buffer_size_hint | int | 读/写 | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | r/w | 获取或设置指示 tiff 字节顺序的值。 |
| color_map | ushort | 读/写 | 获取或设置颜色映射。 |
| compressed_quality | int | 读/写 | 获取或设置压缩图像质量。<br/>            与 Jpeg 压缩一起使用。 |
| compression | [TiffCompressions](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffcompressions/) | r/w | 获取或设置压缩方式。 |
| copyright | 字符串 | 读/写 | 获取或设置版权。 |
| date_time | 字符串 | 读/写 | 获取或设置日期和时间。 |
| default_memory_allocation_limit | int | 读/写 | 获取或设置默认内存分配限制。 |
| default_replacement_font | 字符串 | 读/写 | 获取或设置默认替代字体（在导出为光栅时用于绘制文本的字体，如果 PSD 文件中的现有图层字体在系统中不存在）。<br/>            要获取默认字体的正确名称，可以使用以下代码片段：<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| 已释放 | bool | r | 获取一个值，指示此实例是否已释放。 |
| document_name | 字符串 | 读/写 | 获取或设置文档的名称。 |
| exif_ifd | [TiffExifIfd](/psd/python-net/aspose.psd.fileformats.tiff/tiffexififd/) | r | 获取或设置指向 EXIF IFD 的指针。 |
| fax_t4_options | [Group3Options](/psd/python-net/aspose.psd.fileformats.tiff.enums/group3options/) | r/w | 获取或设置传真 t4 选项。 |
| file_standard | [TiffFileStandards](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffilestandards/) | r/w | 获取或设置 TIFF 文件标准。 |
| fill_order | [TiffFillOrders](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffillorders/) | r/w | 获取或设置字节位填充顺序。 |
| full_frame | bool | 读/写 | 获取或设置一个值，指示是否为 [full frame]。 |
| half_tone_hints | ushort | 读/写 | 获取或设置半色调提示。 |
| image_description | 字符串 | 读/写 | 获取或设置图像描述。 |
| image_length | uint | 读/写 | 获取或设置图像长度。 |
| image_width | uint | 读/写 | 获取或设置图像宽度。 |
| ink_names | 字符串 | 读/写 | 获取或设置墨水名称。 |
| is_extra_samples_present | bool | r | 获取一个值，指示是否存在额外样本。 |
| is_tiled | bool | r | 获取一个指示图像是否已平铺的值。 |
| is_valid | bool | r | 获取一个指示 [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) 是否已正确配置的值。使用 Validate 方法来查找失败原因。 |
| max_sample_value | ushort | 读/写 | 获取或设置最大样本值。 |
| min_sample_value | ushort | 读/写 | 获取或设置最小样本值。 |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | 多页选项 |
| orientation | [TiffOrientations](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifforientations/) | r/w | 获取或设置方向。 |
| page_name | 字符串 | 读/写 | 获取或设置页面名称。 |
| page_number | ushort | 读/写 | 获取或设置页码标签。 |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | 获取或设置颜色调色板。 |
| photometric | [TiffPhotometrics](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffphotometrics/) | r/w | 获取或设置光度。 |
| planar_configuration | [TiffPlanarConfigs](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | 获取或设置平面配置。 |
| predictor | [TiffPredictor](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffpredictor/) | r/w | 获取或设置 LZW 压缩的预测器。 |
| premultiply_components | bool | 读/写 | 获取或设置一个指示组件是否必须预乘的值。 |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | 获取或设置分辨率设置。 |
| resolution_unit | [TiffResolutionUnits](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffresolutionunits/) | r/w | 获取或设置分辨率单位。 |
| rows_per_strip | uint | 读/写 | 获取或设置每条带的行数。 |
| sample_format | [TiffSampleFormats[]](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffsampleformats/) | r/w | 获取或设置样本格式。 |
| samples_per_pixel | ushort | r | 获取每像素的样本数。要更改此属性值，请使用 [TiffOptions.bits_per_sample](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) 属性设置器。 |
| scanner_manufacturer | 字符串 | 读/写 | 获取或设置扫描仪制造商。 |
| scanner_model | 字符串 | 读/写 | 获取或设置扫描仪型号。 |
| smax_sample_value | uint | 读/写 | 获取或设置最大样本值。该值具有最匹配样本数据的字段类型（Byte、Short 或 Long 类型）。 |
| smin_sample_value | uint | 读/写 | 获取或设置最小样本值。该值具有最匹配样本数据的字段类型（Byte、Short 或 Long 类型）。 |
| software_type | 字符串 | 读/写 | 获取或设置软件类型。 |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | 获取或设置用于创建图像的源。 |
| strip_byte_counts | uint | 读/写 | 获取或设置条带字节计数。 |
| strip_offsets | uint | 读/写 | 获取或设置条带偏移量。 |
| sub_file_type | [TiffNewSubFileTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | 获取或设置此子文件中包含的数据类型的一般指示。 |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | 获取或设置标签。 |
| target_printer | 字符串 | 读/写 | 获取或设置目标打印机。 |
| threshholding | [TiffThresholds](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffthresholds/) | r/w | 获取或设置阈值处理。 |
| tile_byte_counts | uint | 读/写 | 获取或设置瓦片字节计数。 |
| tile_length | uint | 读/写 | 获取或设置瓦片长度。 |
| tile_offsets | uint | 读/写 | 获取或设置瓦片偏移量。 |
| tile_width | uint | 读/写 | 获取或设置瓦片宽度。 |
| total_pages | ushort | r | 获取总页数。 |
| valid_tag_count | int | r | 获取有效标签计数。这不是标签的总计数，而是可能被保留的标签数量。 |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | 获取或设置矢量光栅化选项。 |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | 获取或设置 XMP 元数据容器。 |
| xp_author | 字符串 | 读/写 | 获取或设置图像作者，此属性由 Windows Explorer 使用。 |
| xp_comment | 字符串 | 读/写 | 获取或设置图像注释，此属性由 Windows Explorer 使用。 |
| xp_keywords | 字符串 | 读/写 | 获取或设置图像主题，此属性由 Windows Explorer 使用。 |
| xp_subject | 字符串 | 读/写 | 获取或设置图像信息，此属性由 Windows Explorer 使用。 |
| xp_title | 字符串 | 读/写 | 获取或设置图像信息，此属性由 Windows Explorer 使用。 |
| xposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置 X 位置。 |
| xresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置 X 分辨率。 |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置 YCbCr 系数。 |
| y_cb_cr_subsampling | ushort | 读/写 | 获取或设置 YCbCr 颜色空间的子采样因子。 |
| yposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置 Y 位置。 |
| yresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | 获取或设置 Y 分辨率。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | 添加一个新标签。 |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | 添加标签。 |
| [clone()](#clone__3) | 克隆此实例。 |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_4) | 按类型获取标签的实例。 |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_5) | 获取有效标签的计数。 |
| [is_tag_present(tag)](#is_tag_present_tag_6) | 确定选项中是否存在该标签。 |
| [remove_tag(tag)](#remove_tag_tag_7) | 移除标签。 |
| validate() | 验证选项中标签的组合是否有效 |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

初始化 [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) 类的新实例。默认使用小端序约定。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | 期望的 TIFF 文件格式。 |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

初始化 [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | 期望的 TIFF 文件格式。 |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | 要使用的 TIFF 文件格式字节序。 |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

初始化 [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions) | 要复制的选项。 |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

初始化 [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | 用于初始化选项的标签。 |

### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

添加一个新标签。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | 要添加的标签。 |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

添加标签。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | 要添加的标签。 |

### Method: clone() {#clone__3}


```
 clone() 
```

克隆此实例。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 返回此实例的浅拷贝 |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_4}


```
 get_tag_by_type(tag_key) 
```

按类型获取标签的实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| tag_key | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | 标签键。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | 如果存在则为标签实例，否则为 null。 |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_5}


```
 get_valid_tags_count(tags) 
```

获取有效标签的计数。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | 要验证的标签。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 有效标签的计数。 |


### Method: is_tag_present(tag) {#is_tag_present_tag_6}


```
 is_tag_present(tag) 
```

确定选项中是否存在该标签。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | 要检查的标签 ID。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <c>true</c> 表示标签存在；否则为 <c>false</c>。 |


### Method: remove_tag(tag) {#remove_tag_tag_7}


```
 remove_tag(tag) 
```

移除标签。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | 要移除的标签。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果成功移除则为 true |


