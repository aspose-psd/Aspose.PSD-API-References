---
title: "GifOptions 类"
type: docs
weight: 30
url: /zh/python-net/aspose.psd.imageoptions/gifoptions/
---

**Summary:** The gif file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.GifOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | 初始化 [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) 类的新实例。 |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | 初始化 [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color_index | byte | 读/写 | 获取或设置 GIF 背景颜色索引。 |
| buffer_size_hint | int | 读/写 | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| color_resolution | byte | 读/写 | 获取或设置 GIF 颜色分辨率。 |
| default_replacement_font | 字符串 | 读/写 | 获取或设置默认替代字体（在导出为光栅时用于绘制文本的字体，如果 PSD 文件中的现有图层字体在系统中不存在）。<br/>            要获取默认字体的正确名称，可以使用以下代码片段：<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| 已释放 | bool | r | 获取一个值，指示此实例是否已释放。 |
| do_palette_correction | bool | 读/写 | 获取或设置一个值，指示是否应用调色板校正。 |
| full_frame | bool | 读/写 | 获取或设置一个值，指示是否为 [full frame]。 |
| has_trailer | bool | 读/写 | 获取或设置一个值，指示 GIF 是否有尾部。 |
| interlaced | bool | 读/写 | 如果图像应交错，则为 True。 |
| is_palette_sorted | bool | 读/写 | 获取或设置一个值，指示调色板条目是否已排序。 |
| max_diff | int | 读/写 | 获取或设置允许的最大像素差异。如果大于零，将使用有损压缩。<br/>            推荐的最佳有损压缩值为 80。30 为轻度压缩，200 为重度压缩。<br/>            当仅引入少量损失时效果最佳，由于压缩算法的限制，非常高的损失水平不会带来太多收益。<br/>            允许的值范围是 [0, 1000]。 |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | 多页选项 |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | 获取或设置颜色调色板。 |
| pixel_aspect_ratio | byte | 读/写 | 获取或设置 GIF 像素宽高比。 |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | 获取或设置分辨率设置。 |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | 获取或设置用于创建图像的源。 |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | 获取或设置矢量光栅化选项。 |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | 获取或设置 XMP 元数据容器。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | 克隆此实例。 |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

初始化 [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) 类的新实例。

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

初始化 [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| gif_options | [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions) | GIF 选项。 |

### Method: clone() {#clone__1}


```
 clone() 
```

克隆此实例。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 返回此实例的浅拷贝 |


