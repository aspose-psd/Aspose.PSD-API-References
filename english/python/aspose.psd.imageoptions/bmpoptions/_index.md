---
title: BmpOptions Class
type: docs
weight: 10
url: /python-net/aspose.psd.imageoptions/bmpoptions/
---

**Summary:** The bmp file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.BmpOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.6.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BmpOptions()](#BmpOptions__1) | Initializes a new instance of the [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/) class. |
| [BmpOptions(bmp_options)](#BmpOptions_bmp_options_2) | Initializes a new instance of the [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bits_per_pixel | int | r/w | Gets or sets the image bits per pixel count. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| compression | [BitmapCompression](/psd/python-net/aspose.psd.fileformats.bmp/bitmapcompression/) | r/w | Gets or sets the compression. |
| default_replacement_font | string | r/w | Gets or sets the default replacement font (font that will be used to draw text when exporting to raster, if existing layer font in PSD file is not presented in system).<br/>            To take proper name of default font can be used next code snippet:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | The multipage options |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Gets or sets the color palette. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Gets or sets the resolution settings. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Gets or sets the source to create image in. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Gets or sets the vector rasterization options. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Gets or sets the XMP metadata container. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clones this instance. |


### Constructor: BmpOptions() {#BmpOptions__1}


```
 BmpOptions() 
```

Initializes a new instance of the [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/) class.

### Constructor: BmpOptions(bmp_options) {#BmpOptions_bmp_options_2}


```
 BmpOptions(bmp_options) 
```

Initializes a new instance of the [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| bmp_options | [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions) | The BMP options. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Returns shallow copy of this instance |


