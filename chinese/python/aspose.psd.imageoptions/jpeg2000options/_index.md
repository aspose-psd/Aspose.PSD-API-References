---
title: "Jpeg2000Options 类"
type: docs
weight: 50
url: /zh/python-net/aspose.psd.imageoptions/jpeg2000options/
---

**Summary:** The Jpeg2000 file format options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.Jpeg2000Options

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Jpeg2000Options()](#Jpeg2000Options__1) | 初始化一个新的 [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/) 类的实例。 |
| [Jpeg2000Options(jpeg_2000_options)](#Jpeg2000Options_jpeg_2000_options_2) | 初始化一个新的 [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | 读/写 | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| codec | [Jpeg2000Codec](/psd/python-net/aspose.psd.fileformats.jpeg2000/jpeg2000codec/) | r/w | 获取或设置 JPEG2000 编解码器 |
| comments | 字符串 | 读/写 | 获取或设置 JPEG 注释标记。 |
| compression_ratios | int | 读/写 | 获取或设置压缩比的数组。<br/>            不同层的压缩比。<br/>            为每个质量级别指定的比率是期望的<br/>            压缩因子。<br/>            需要降低比率。 |
| default_replacement_font | 字符串 | 读/写 | 获取或设置默认替代字体（在导出为光栅时用于绘制文本的字体，如果 PSD 文件中的现有图层字体在系统中不存在）。<br/>            要获取默认字体的正确名称，可以使用以下代码片段：<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| 已释放 | bool | r | 获取一个值，指示此实例是否已释放。 |
| full_frame | bool | 读/写 | 获取或设置一个值，指示是否为 [full frame]。 |
| irreversible | bool | 读/写 | 获取或设置一个值，指示是使用不可逆的 DWT 9-7（true）还是使用无损的 DWT 5-3 压缩（默认）。 |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | 多页选项 |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | 获取或设置颜色调色板。 |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | 获取或设置分辨率设置。 |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | 获取或设置用于创建图像的源。 |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | 获取或设置矢量光栅化选项。 |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | 获取或设置 XMP 元数据容器。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | 克隆此实例。 |


### Constructor: Jpeg2000Options() {#Jpeg2000Options__1}


```
 Jpeg2000Options() 
```

初始化一个新的 [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/) 类的实例。

### Constructor: Jpeg2000Options(jpeg_2000_options) {#Jpeg2000Options_jpeg_2000_options_2}


```
 Jpeg2000Options(jpeg_2000_options) 
```

初始化一个新的 [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/) 类的实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| jpeg_2000_options | [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options) | 要从中复制设置的 Jpeg2000 文件格式选项。 |

### Method: clone() {#clone__1}


```
 clone() 
```

克隆此实例。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 返回此实例的浅拷贝 |


