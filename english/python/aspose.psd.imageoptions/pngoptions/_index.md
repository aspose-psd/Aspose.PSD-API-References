---
title: PngOptions Class
type: docs
weight: 90
url: /python-net/aspose.psd.imageoptions/pngoptions/
---

**Summary:** The png file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PngOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.5.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PngOptions()](#PngOptions__1) | Initializes a new instance of the [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) class. |
| [PngOptions(png_options)](#PngOptions_png_options_2) | Initializes a new instance of the [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | int | r | The default compression level. |
| bit_depth | byte | r/w | The bit depth. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| color_type | [PngColorType](/psd/python-net/aspose.psd.fileformats.png/pngcolortype/) | r/w | Gets or sets the type of the color. |
| compression_level | int | r/w | The png image compression level in the 0-9 range, where 9 is maximum compression and 0 is store mode. |
| default_replacement_font | string | r/w | Gets or sets the default replacement font (font that will be used to draw text when exporting to raster, if existing layer font in PSD file is not presented in system).<br/>            To take proper name of default font can be used next code snippet:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| filter_type | [PngFilterType](/psd/python-net/aspose.psd.fileformats.png/pngfiltertype/) | r/w | Gets or sets the filter type used during png file save process. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | The multipage options |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Gets or sets the color palette. |
| progressive | bool | r/w | Gets or sets a value indicating whether this [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) is progressive. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Gets or sets the resolution settings. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Gets or sets the source to create image in. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Gets or sets the vector rasterization options. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Gets or sets the XMP metadata container. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clones this instance. |


### Constructor: PngOptions() {#PngOptions__1}


```
 PngOptions() 
```

Initializes a new instance of the [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) class.

### Constructor: PngOptions(png_options) {#PngOptions_png_options_2}


```
 PngOptions(png_options) 
```

Initializes a new instance of the [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| png_options | [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions) | The PNG options. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Returns shallow copy of this instance |


