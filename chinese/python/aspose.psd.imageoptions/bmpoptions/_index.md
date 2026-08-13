---
title: "BmpOptions 类"
type: docs
weight: 10
url: /zh/python-net/aspose.psd.imageoptions/bmpoptions/
---

**Summary:** The bmp file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.BmpOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BmpOptions()](#BmpOptions__1) | 初始化 [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/) 类的新实例。 |
| [BmpOptions(bmp_options)](#BmpOptions_bmp_options_2) | 初始化 [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bits_per_pixel | int | 读/写 | 获取或设置图像的每像素位数。 |
| buffer_size_hint | int | 读/写 | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| compression | [BitmapCompression](/psd/python-net/aspose.psd.fileformats.bmp/bitmapcompression/) | r/w | 获取或设置压缩方式。 |
| default_replacement_font | 字符串 | 读/写 | 获取或设置默认替代字体（在导出为光栅时用于绘制文本的字体，如果 PSD 文件中的现有图层字体在系统中不存在）。<br/>            要获取默认字体的正确名称，可以使用以下代码片段：<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| 已释放 | bool | r | 获取一个值，指示此实例是否已释放。 |
| full_frame | bool | 读/写 | 获取或设置一个值，指示是否为 [full frame]。 |
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


### Constructor: BmpOptions() {#BmpOptions__1}


```
 BmpOptions() 
```

初始化 [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/) 类的新实例。

### Constructor: BmpOptions(bmp_options) {#BmpOptions_bmp_options_2}


```
 BmpOptions(bmp_options) 
```

初始化 [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| bmp_options | [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions) | BMP 选项。 |

### Method: clone() {#clone__1}


```
 clone() 
```

克隆此实例。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 返回此实例的浅拷贝 |


