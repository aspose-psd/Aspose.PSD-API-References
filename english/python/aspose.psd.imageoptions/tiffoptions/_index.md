---
title: TiffOptions Class
type: docs
weight: 130
url: /python-net/aspose.psd.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.TiffOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.8.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | Initializes a new instance of the [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) class. By default little endian convention is used. |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | Initializes a new instance of the [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) class. |
| [TiffOptions(options)](#TiffOptions_options_3) | Initializes a new instance of the [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) class. |
| [TiffOptions(tags)](#TiffOptions_tags_4) | Initializes a new instance of the [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/) | r/w | Gets or sets the alpha storage option. Options other than [TiffAlphaStorage.UNSPECIFIED](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/)<br/>            are used when there are more than 3 [TiffOptions.samples_per_pixel](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) defined. |
| artist | string | r/w | Gets or sets the artist. |
| bits_per_pixel | int | r | Gets the bits per pixel. |
| bits_per_sample | ushort | r/w | Gets or sets the bits per sample. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | r/w | Gets or sets a value indicating the tiff byte order. |
| color_map | ushort | r/w | Gets or sets the color map. |
| compressed_quality | int | r/w | Gets or sets compressed image quality.<br/>            Used with the Jpeg compression. |
| compression | [TiffCompressions](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffcompressions/) | r/w | Gets or sets the compression. |
| copyright | string | r/w | Gets or sets the copyright. |
| date_time | string | r/w | Gets or sets the date and time. |
| default_memory_allocation_limit | int | r/w | Gets or sets the default memory allocation limit. |
| default_replacement_font | string | r/w | Gets or sets the default replacement font (font that will be used to draw text when exporting to raster, if existing layer font in PSD file is not presented in system).<br/>            To take proper name of default font can be used next code snippet:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| document_name | string | r/w | Gets or sets the name of the document. |
| exif_ifd | [TiffExifIfd](/psd/python-net/aspose.psd.fileformats.tiff/tiffexififd/) | r | Gets or sets the pointer to EXIF IFD. |
| fax_t4_options | [Group3Options](/psd/python-net/aspose.psd.fileformats.tiff.enums/group3options/) | r/w | Gets or sets the fax t4 options. |
| file_standard | [TiffFileStandards](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffilestandards/) | r/w | Gets or sets the TIFF file standard. |
| fill_order | [TiffFillOrders](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffillorders/) | r/w | Gets or sets the byte bits fill order. |
| full_frame | bool | r/w | Gets or sets a value indicating whether [full frame]. |
| half_tone_hints | ushort | r/w | Gets or sets the halftone hints. |
| image_description | string | r/w | Gets or sets the image description. |
| image_length | uint | r/w | Gets or sets the image length. |
| image_width | uint | r/w | Gets or sets the image width. |
| ink_names | string | r/w | Gets or sets the ink names. |
| is_extra_samples_present | bool | r | Gets a value indicating whether the extra samples is present. |
| is_tiled | bool | r | Gets a value indicating whether image is tiled. |
| is_valid | bool | r | Gets a value indicating whether the [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) have been properly configured. Use Validate method as to find the failure reason. |
| max_sample_value | ushort | r/w | Gets or sets the max sample value. |
| min_sample_value | ushort | r/w | Gets or sets the min sample value. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | The multipage options |
| orientation | [TiffOrientations](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifforientations/) | r/w | Gets or sets the orientation. |
| page_name | string | r/w | Gets or sets the page name. |
| page_number | ushort | r/w | Gets or sets the page number tag. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Gets or sets the color palette. |
| photometric | [TiffPhotometrics](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffphotometrics/) | r/w | Gets or sets the photometric. |
| planar_configuration | [TiffPlanarConfigs](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | Gets or sets the planar configuration. |
| predictor | [TiffPredictor](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffpredictor/) | r/w | Gets or sets the predictor for LZW compression. |
| premultiply_components | bool | r/w | Gets or sets a value indicating whether components must be premultiplied. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Gets or sets the resolution settings. |
| resolution_unit | [TiffResolutionUnits](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffresolutionunits/) | r/w | Gets or sets the resolution unit. |
| rows_per_strip | uint | r/w | Gets or sets the rows per strip. |
| sample_format | [TiffSampleFormats[]](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffsampleformats/) | r/w | Gets or sets the sample format. |
| samples_per_pixel | ushort | r | Gets the samples per pixel. To change this property value use the [TiffOptions.bits_per_sample](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) property setter. |
| scanner_manufacturer | string | r/w | Gets or sets the scanner manufacturer. |
| scanner_model | string | r/w | Gets or sets the scanner model. |
| smax_sample_value | uint | r/w | Gets or sets the max sample value. The value has a field type which best matches the sample data (Byte, Short or Long type). |
| smin_sample_value | uint | r/w | Gets or sets the min sample value. The value has a field type which best matches the sample data (Byte, Short or Long type). |
| software_type | string | r/w | Gets or sets the software type. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Gets or sets the source to create image in. |
| strip_byte_counts | uint | r/w | Gets or sets the strip byte counts. |
| strip_offsets | uint | r/w | Gets or sets the strip offsets. |
| sub_file_type | [TiffNewSubFileTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | Gets or sets a general indication of the kind of data contained in this subfile. |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Gets or sets the tags. |
| target_printer | string | r/w | Gets or sets the target printer. |
| threshholding | [TiffThresholds](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffthresholds/) | r/w | Gets or sets the threshholding. |
| tile_byte_counts | uint | r/w | Gets or sets the tile byte counts. |
| tile_length | uint | r/w | Gets ot sets tile length. |
| tile_offsets | uint | r/w | Gets or sets the tile offsets. |
| tile_width | uint | r/w | Gets ot sets tile width. |
| total_pages | ushort | r | Gets the total pages. |
| valid_tag_count | int | r | Gets the valid tag count. This is not the total tags count but the number of tags which may be preserved. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Gets or sets the vector rasterization options. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Gets or sets the XMP metadata container. |
| xp_author | string | r/w | Gets or sets image author, which used by Windows Explorer. |
| xp_comment | string | r/w | Gets or sets comment on image, which used by Windows Explorer. |
| xp_keywords | string | r/w | Gets or sets subject image, which used by Windows Explorer. |
| xp_subject | string | r/w | Gets or sets information about image, which used by Windows Explorer. |
| xp_title | string | r/w | Gets or sets information about image, which used by Windows Explorer. |
| xposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the x position. |
| xresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the x resolution. |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the YCbCrCoefficients. |
| y_cb_cr_subsampling | ushort | r/w | Gets or sets the subsampling factors for YCbCr photometric. |
| yposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the y position. |
| yresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Gets or sets the y resolution. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | Adds a new tag. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | Adds the tags. |
| [clone()](#clone__3) | Clones this instance. |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_4) | Gets the instance of the tag by type. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_5) | Gets the valid tags count. |
| [is_tag_present(tag)](#is_tag_present_tag_6) | Determines whether tag is present in the options or not. |
| [remove_tag(tag)](#remove_tag_tag_7) | Removes the tag. |
| validate() | Validates if options have valid combination of tags |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

Initializes a new instance of the [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) class. By default little endian convention is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | The expected tiff file format. |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

Initializes a new instance of the [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | The expected tiff file format. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | The tiff file format byte order to use. |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

Initializes a new instance of the [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| options | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions) | The options to copy from. |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

Initializes a new instance of the [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | The tags to initialize options with. |

### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

Adds a new tag.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | The tag to add. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

Adds the tags.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | The tags to add. |

### Method: clone() {#clone__3}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Returns shallow copy of this instance |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_4}


```
 get_tag_by_type(tag_key) 
```

Gets the instance of the tag by type.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tag_key | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | The tag key. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Instance of the tag if exists or null otherwise. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_5}


```
 get_valid_tags_count(tags) 
```

Gets the valid tags count.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | The tags to validate. |

**Returns**

| Type | Description |
| :- | :- |
| int | The valid tags count. |


### Method: is_tag_present(tag) {#is_tag_present_tag_6}


```
 is_tag_present(tag) 
```

Determines whether tag is present in the options or not.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | The tag id to check. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if tag is present; otherwise, <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_7}


```
 remove_tag(tag) 
```

Removes the tag.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | The tag to remove. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true if successfully removed |


