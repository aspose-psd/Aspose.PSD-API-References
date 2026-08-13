---
title: "PsdOptions 类"
type: docs
weight: 100
url: /zh/python-net/aspose.psd.imageoptions/psdoptions/
---

**Summary:** The psd file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PsdOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | 初始化一个新的 [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) 类实例。 |
| [PsdOptions(image)](#PsdOptions_image_2) | 初始化一个新的 [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) 类实例。 |
| [PsdOptions(options)](#PsdOptions_options_3) | 初始化一个新的 [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_contents | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | 获取或设置背景颜色。<br/>            在透明对象下可见。 |
| buffer_size_hint | int | 读/写 | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| channel_bits_count | short | 读/写 | 获取或设置每个颜色通道的位数。 |
| channels_count | short | 读/写 | 获取或设置颜色通道的数量。 |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes/) | r/w | 获取或设置 PSD 颜色模式。 |
| compression_method | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod/) | r/w | 获取或设置 PSD 压缩方法。 |
| default_replacement_font | 字符串 | 读/写 | 获取或设置默认替代字体（在导出为光栅时用于绘制文本的字体，如果 PSD 文件中的现有图层字体在系统中不存在）。<br/>            要获取默认字体的正确名称，可以使用以下代码片段：<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| 已释放 | bool | r | 获取一个值，指示此实例是否已释放。 |
| full_frame | bool | 读/写 | 获取或设置一个值，指示是否为 [full frame]。 |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | 多页选项 |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | 获取或设置颜色调色板。 |
| psd_version | [PsdVersion](/psd/python-net/aspose.psd.fileformats.psd/psdversion/) | r/w | 获取或设置文件格式版本。它可以是 PSD 或 PSB。 |
| refresh_image_preview_data | bool | 读/写 | 获取或设置一个值，指示是否 [refresh image preview data] - 该选项用于最大化与其他 PSD 图像查看器的兼容性。<br/>            请注意，紧凑框架平台不支持将文本图层绘制到最终布局。 |
| remove_global_text_engine_resource | bool | 读/写 | 获取或设置一个值，指示是否 - 移除全局文本引擎资源 - 用于某些带文本图层的 PSD 文件，仅在处理后无法在 Adobe Photoshop 中打开时（主要与缺失字体的文本图层相关）。<br/>            使用此选项后，用户需要在 Photoshop 打开的文件中执行以下操作：菜单 \"Text\" -&gt; \"Process absent fonts\"。该操作后所有文本将再次出现。<br/>            请注意，此操作可能导致某些最终布局的更改。 |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | 获取或设置分辨率设置。 |
| resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock/) | r/w | 获取或设置 PSD 资源。 |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | 获取或设置用于创建图像的源。 |
| update_metadata | bool | 读/写 | 获取或设置一个值，指示是否 [update metadata]。<br/>            如果该值为 true，元数据将在保存图像时更新。 |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | 获取或设置矢量光栅化选项。 |
| version | int | 读/写 | 获取或设置 PSD 文件版本。 |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | 获取或设置 XMP 数据容器 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | 克隆此实例。 |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

初始化一个新的 [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) 类实例。

### Constructor: PsdOptions(image) {#PsdOptions_image_2}


```
 PsdOptions(image) 
```

初始化一个新的 [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) 类实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image | [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) | 图像。 |

### Constructor: PsdOptions(options) {#PsdOptions_options_3}


```
 PsdOptions(options) 
```

初始化一个新的 [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) 类实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions) | 选项。 |

### Method: clone() {#clone__1}


```
 clone() 
```

克隆此实例。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 返回此实例的浅拷贝 |


