---
title: "JpegOptions 类"
type: docs
weight: 60
url: /zh/python-net/aspose.psd.imageoptions/jpegoptions/
---

**Summary:** The jpeg file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.JpegOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | 初始化 [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) 类的新实例。 |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | 初始化 [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bits_per_channel | byte | 读/写 | 获取或设置无损 jpeg 图像的每通道位数。现在我们支持每通道 2 到 8 位。 |
| buffer_size_hint | int | 读/写 | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | CMYK jpeg 图像的目标 CMYK 颜色配置文件。用于保存图像。必须与 RGBColorProfile 配对，以实现正确的颜色转换。 |
| color_type | [JpegCompressionColorMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressioncolormode/) | r/w | 获取或设置 jpeg 图像的颜色类型。 |
| 注释 | 字符串 | 读/写 | 获取或设置 jpeg 文件的注释。 |
| compression_type | [JpegCompressionMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressionmode/) | r/w | 获取或设置压缩类型。 |
| default_memory_allocation_limit | int | 读/写 | 获取或设置默认内存分配限制。 |
| default_replacement_font | 字符串 | 读/写 | 获取或设置默认替代字体（在导出为光栅时用于绘制文本的字体，如果 PSD 文件中的现有图层字体在系统中不存在）。<br/>            要获取默认字体的正确名称，可以使用以下代码片段：<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| 已释放 | bool | r | 获取一个值，指示此实例是否已释放。 |
| exif_data | [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) | r/w | 获取或设置 exif 数据容器 |
| full_frame | bool | 读/写 | 获取或设置一个值，指示是否为 [full frame]。 |
| horizontal_sampling | byte | 读/写 | 获取或设置每个组件的水平子采样。 |
| jfif | [JFIFData](/psd/python-net/aspose.psd.fileformats.jpeg/jfifdata/) | r/w | 获取或设置 jfif。 |
| jpeg_ls_allowed_lossy_error | int | 读/写 | 获取或设置 JPEG-LS 近无损编码的差值界限（来自 JPEG-LS 规范的 NEAR 参数）。 |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglsinterleavemode/) | r/w | 获取或设置 JPEG-LS 交错模式。 |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | 获取或设置 JPEG-LS 预设参数。 |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | 多页选项 |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | 获取或设置颜色调色板。 |
| preblend_alpha_if_present | bool | 读/写 | 获取或设置一个值，指示在存在 alpha 通道时是否应将红、绿、蓝组件与背景颜色混合。 |
| quality | int | 读/写 | 获取或设置图像质量。 |
| rd_opt_settings | [RdOptimizerSettings](/psd/python-net/aspose.psd.imageoptions/rdoptimizersettings) | r/w | 获取或设置 RD 优化器设置。 |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | 获取或设置分辨率设置。 |
| resolution_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit) | r/w | 获取或设置分辨率单位。 |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | CMYK jpeg 图像的目标 RGB 颜色配置文件。用于保存图像。必须与 CMYKColorProfile 配对，以实现正确的颜色转换。 |
| sample_rounding_mode | [SampleRoundingMode](/psd/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/) | r/w | 获取或设置样本四舍五入模式，以将 8 位值适配为 n 位值。 <see cref="P:JpegOptions.BitsPerChannel" /> |
| scaled_quality | int | r | 缩放质量。 |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | 获取或设置用于创建图像的源。 |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | 获取或设置矢量光栅化选项。 |
| vertical_sampling | byte | 读/写 | 获取或设置每个组件的垂直子采样。 |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | 获取或设置 XMP 元数据容器。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | 克隆此实例。 |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

初始化 [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) 类的新实例。

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

初始化 [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions) | JPEG 选项。 |

### Method: clone() {#clone__1}


```
 clone() 
```

克隆此实例。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 返回此实例的浅拷贝 |


