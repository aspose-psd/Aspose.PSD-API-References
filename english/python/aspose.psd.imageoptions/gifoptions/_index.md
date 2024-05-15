---
title: GifOptions Class
type: docs
weight: 30
url: /python-net/aspose.psd.imageoptions/gifoptions/
---

**Summary:** The gif file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.GifOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.4.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | Initializes a new instance of the [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) class. |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | Initializes a new instance of the [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color_index | byte | r/w | Gets or sets the GIF background color index. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| color_resolution | byte | r/w | Gets or sets the GIF color resolution. |
| default_replacement_font | string | r/w | Gets or sets the default replacement font (font that will be used to draw text when exporting to raster, if existing layer font in PSD file is not presented in system).<br/>            To take proper name of default font can be used next code snippet:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| do_palette_correction | bool | r/w | Gets or sets a value indicating whether palette correction is applied. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| has_trailer | bool | r/w | Gets or sets a value indicating whether GIF has trailer. |
| interlaced | bool | r/w | True if image should be interlaced. |
| is_palette_sorted | bool | r/w | Gets or sets a value indicating whether palette entries are sorted. |
| max_diff | int | r/w | Gets or sets the maximum allowed pixel difference. If greater than zero, lossy compression will be used.<br/>            Recommended value for optimal lossy compression is 80. 30 is very light compression, 200 is heavy.<br/>            It works best when only little loss is introduced, and due to limitation of the compression algorithm very high loss levels won't give as much gain.<br/>            The range of allowed values is [0, 1000]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | The multipage options |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Gets or sets the color palette. |
| pixel_aspect_ratio | byte | r/w | Gets or sets the GIF pixel aspect ratio. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Gets or sets the resolution settings. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Gets or sets the source to create image in. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Gets or sets the vector rasterization options. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Gets or sets the XMP metadata container. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clones this instance. |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

Initializes a new instance of the [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) class.

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

Initializes a new instance of the [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| gif_options | [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions) | The GIF Options. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Returns shallow copy of this instance |


