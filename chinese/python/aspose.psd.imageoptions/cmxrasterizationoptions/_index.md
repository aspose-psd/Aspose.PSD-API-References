---
title: "CmxRasterizationOptions 类"
type: docs
weight: 20
url: /zh/python-net/aspose.psd.imageoptions/cmxrasterizationoptions/
---

**Summary:** the CMX exporter options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.CmxRasterizationOptions

**Inheritance:** VectorRasterizationOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CmxRasterizationOptions()](#CmxRasterizationOptions__1) | 初始化 CmxRasterizationOptions 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 获取或设置背景颜色。 |
| border_x | float | 读/写 | 获取或设置 X 边框。 |
| border_y | float | 读/写 | 获取或设置 Y 边框。 |
| buffer_size_hint | int | 读/写 | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| center_drawing | bool | 读/写 | 获取或设置指示是否居中绘制的值。 |
| default_replacement_font | 字符串 | 读/写 | 获取或设置默认替代字体（在导出为光栅时用于绘制文本的字体，如果 PSD 文件中的现有图层字体在系统中不存在）。<br/>            要获取默认字体的正确名称，可以使用以下代码片段：<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| 已释放 | bool | r | 获取一个值，指示此实例是否已释放。 |
| draw_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 获取或设置前景颜色。 |
| full_frame | bool | 读/写 | 获取或设置一个值，指示是否为 [full frame]。 |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | 多页选项 |
| page_height | float | 读/写 | 获取或设置页面高度。 |
| page_size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | 获取或设置页面大小。 |
| page_width | float | 读/写 | 获取或设置页面宽度。 |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | 获取或设置颜色调色板。 |
| positioning | [PositioningTypes](/psd/python-net/aspose.psd.imageoptions/positioningtypes) | r/w | 获取或设置定位。 |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | 获取或设置分辨率设置。 |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | 获取或设置平滑模式。 |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | 获取或设置用于创建图像的源。 |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | 获取或设置文本呈现提示。 |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | 获取或设置矢量光栅化选项。 |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | 获取或设置 XMP 元数据容器。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | 克隆此实例。 |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | 复制到。 |


### Constructor: CmxRasterizationOptions() {#CmxRasterizationOptions__1}


```
 CmxRasterizationOptions() 
```

初始化 CmxRasterizationOptions 类的新实例

### Method: clone() {#clone__1}


```
 clone() 
```

克隆此实例。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 返回此实例的浅拷贝 |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

复制到。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | 矢量光栅化选项。 |

