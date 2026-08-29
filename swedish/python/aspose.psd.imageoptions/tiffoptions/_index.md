---
title: "TiffOptions Klass"
type: docs
weight: 130
url: /sv/python-net/aspose.psd.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.TiffOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | Initierar en ny instans av klassen [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). Som standard används little endian-konventionen. |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | Initierar en ny instans av klassen [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| [TiffOptions(options)](#TiffOptions_options_3) | Initierar en ny instans av klassen [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| [TiffOptions(tags)](#TiffOptions_tags_4) | Initierar en ny instans av klassen [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/) | r/w | Hämtar eller anger alfa lagringsalternativet. Alternativ annat än [TiffAlphaStorage.UNSPECIFIED](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/)<br/>            används när det finns mer än 3 [TiffOptions.samples_per_pixel](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) definierade. |
| artist | string | r/w | Hämtar eller anger artisten. |
| bits_per_pixel | int | r | Hämtar antalet bitar per pixel. |
| bits_per_sample | ushort | r/w | Hämtar eller anger antalet bitar per sample. |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | r/w | Hämtar eller anger ett värde som indikerar TIFF-byteordningen. |
| color_map | ushort | r/w | Hämtar eller anger färgkartan. |
| compressed_quality | int | r/w | Hämtar eller anger komprimerad bildkvalitet.<br/>            Används med JPEG-komprimering. |
| compression | [TiffCompressions](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffcompressions/) | r/w | Hämtar eller anger komprimeringen. |
| copyright | string | r/w | Hämtar eller anger upphovsrätten. |
| date_time | string | r/w | Hämtar eller anger datum och tid. |
| default_memory_allocation_limit | int | r/w | Hämtar eller anger standardgränsen för minnesallokering. |
| default_replacement_font | string | r/w | Hämtar eller anger standardteckensnittet för ersättning (teckensnitt som kommer att användas för att rita text vid export till raster, om befintligt lagertypsnitt i PSD-filen inte finns i systemet).<br/>            För att få rätt namn på standardteckensnittet kan följande kodsnutt användas:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| borttagen | bool | r | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| document_name | string | r/w | Hämtar eller anger dokumentets namn. |
| exif_ifd | [TiffExifIfd](/psd/python-net/aspose.psd.fileformats.tiff/tiffexififd/) | r | Hämtar eller anger pekaren till EXIF IFD. |
| fax_t4_options | [Group3Options](/psd/python-net/aspose.psd.fileformats.tiff.enums/group3options/) | r/w | Hämtar eller anger fax T4-alternativen. |
| file_standard | [TiffFileStandards](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffilestandards/) | r/w | Hämtar eller anger TIFF-filstandard. |
| fill_order | [TiffFillOrders](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffillorders/) | r/w | Hämtar eller anger fyllningsordning för bytebitar. |
| full_frame | bool | r/w | Hämtar eller anger ett värde som indikerar om [full frame]. |
| half_tone_hints | ushort | r/w | Hämtar eller anger halvtonehintar. |
| image_description | string | r/w | Hämtar eller anger bildbeskrivningen. |
| image_length | uint | r/w | Hämtar eller anger bildlängden. |
| image_width | uint | r/w | Hämtar eller anger bildbredden. |
| ink_names | string | r/w | Hämtar eller anger bläcknamnen. |
| is_extra_samples_present | bool | r | Hämtar ett värde som indikerar om extra prover finns. |
| is_tiled | bool | r | Hämtar ett värde som indikerar om bilden är kaklad. |
| is_valid | bool | r | Hämtar ett värde som indikerar om [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) har konfigurerats korrekt. Använd Validate method för att hitta felorsaken. |
| max_sample_value | ushort | r/w | Hämtar eller anger maximalt provvärde. |
| min_sample_value | ushort | r/w | Hämtar eller anger minimalt provvärde. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Flersidiga alternativ |
| orientation | [TiffOrientations](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifforientations/) | r/w | Hämtar eller anger orienteringen. |
| page_name | string | r/w | Hämtar eller anger sidnamnet. |
| page_number | ushort | r/w | Hämtar eller anger sidnummer-tag. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Hämtar eller anger färgpaletten. |
| photometric | [TiffPhotometrics](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffphotometrics/) | r/w | Hämtar eller anger fotometrin. |
| planar_configuration | [TiffPlanarConfigs](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | Hämtar eller anger planär konfiguration. |
| predictor | [TiffPredictor](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffpredictor/) | r/w | Hämtar eller anger förutsägaren för LZW-komprimering. |
| premultiply_components | bool | r/w | Hämtar eller anger ett värde som indikerar om komponenter måste förmultipliceras. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Hämtar eller anger upplösningsinställningarna. |
| resolution_unit | [TiffResolutionUnits](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffresolutionunits/) | r/w | Hämtar eller anger upplösningsenheten. |
| rows_per_strip | uint | r/w | Hämtar eller anger raderna per remsa. |
| sample_format | [TiffSampleFormats[]](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffsampleformats/) | r/w | Hämtar eller anger provformatet. |
| samples_per_pixel | ushort | r | Hämtar proverna per pixel. För att ändra detta egenskapsvärde, använd egenskapsinställaren för [TiffOptions.bits_per_sample](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| scanner_manufacturer | string | r/w | Hämtar eller anger skannertillverkaren. |
| scanner_model | string | r/w | Hämtar eller anger skannermodellen. |
| smax_sample_value | uint | r/w | Hämtar eller anger det maximala provvärdet. Värdet har en fälttyp som bäst matchar provdata (Byte, Short eller Long-typ). |
| smin_sample_value | uint | r/w | Hämtar eller anger det minsta provvärdet. Värdet har en fälttyp som bäst matchar provdata (Byte, Short eller Long-typ). |
| software_type | string | r/w | Hämtar eller anger programvarutypen. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Hämtar eller anger källan för att skapa bilden i. |
| strip_byte_counts | uint | r/w | Hämtar eller anger antalet byte per remsa. |
| strip_offsets | uint | r/w | Hämtar eller anger remsas offset. |
| sub_file_type | [TiffNewSubFileTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | Hämtar eller anger en allmän indikation på vilken typ av data som finns i denna underfil. |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Hämtar eller anger taggarna. |
| target_printer | string | r/w | Hämtar eller anger målskrivaren. |
| threshholding | [TiffThresholds](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffthresholds/) | r/w | Hämtar eller anger tröskelvärdet. |
| tile_byte_counts | uint | r/w | Hämtar eller anger antalet byte per ruta. |
| tile_length | uint | r/w | Hämtar eller ställer in tile length. |
| tile_offsets | uint | r/w | Hämtar eller ställer in tile offsets. |
| tile_width | uint | r/w | Hämtar eller ställer in tile width. |
| total_pages | ushort | r | Hämtar de totala sidorna. |
| valid_tag_count | int | r | Hämtar det giltiga taggantalet. Detta är inte det totala antalet taggar utan antalet taggar som kan bevaras. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Hämtar eller anger vektorrasteriseringsalternativen. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger XMP‑metadata‑behållaren. |
| xp_author | string | r/w | Hämtar eller ställer in bildens författare, som används av Windows Explorer. |
| xp_comment | string | r/w | Hämtar eller ställer in kommentar på bilden, som används av Windows Explorer. |
| xp_keywords | string | r/w | Hämtar eller ställer in ämnesbild, som används av Windows Explorer. |
| xp_subject | string | r/w | Hämtar eller ställer in information om bilden, som används av Windows Explorer. |
| xp_title | string | r/w | Hämtar eller ställer in information om bilden, som används av Windows Explorer. |
| xposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller ställer in x-positionen. |
| xresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller ställer in x-upplösningen. |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller ställer in YCbCrCoefficients. |
| y_cb_cr_subsampling | ushort | r/w | Hämtar eller ställer in subsamplingsfaktorerna för YCbCr-fotometrisk. |
| yposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller ställer in y-positionen. |
| yresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Hämtar eller anger y-upplösningen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | Lägger till en ny tagg. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | Lägger till taggarna. |
| [clone()](#clone__3) | Klonar denna instans. |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_4) | Hämtar instansen av taggen efter typ. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_5) | Hämtar antalet giltiga taggar. |
| [is_tag_present(tag)](#is_tag_present_tag_6) | Bestämmer om taggen finns i alternativen eller inte. |
| [remove_tag(tag)](#remove_tag_tag_7) | Tar bort taggen. |
| validate() | Validerar om alternativen har en giltig kombination av taggar |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

Initierar en ny instans av klassen [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). Som standard används little endian-konventionen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | Det förväntade TIFF‑filformatet. |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

Initierar en ny instans av klassen [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | Det förväntade TIFF‑filformatet. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | Byteordningen för tiff-filformatet som ska användas. |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

Initierar en ny instans av klassen [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions) | Alternativen att kopiera från. |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

Initierar en ny instans av klassen [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Taggarna att initiera alternativen med. |

### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

Lägger till en ny tagg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Taggen att lägga till. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

Lägger till taggarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Taggarna att lägga till. |

### Method: clone() {#clone__3}


```
 clone() 
```

Klonar denna instans.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Returnerar en ytlig kopia av denna instans |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_4}


```
 get_tag_by_type(tag_key) 
```

Hämtar instansen av taggen efter typ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tag_key | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | Taggnyckeln. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Instans av taggen om den finns, annars null. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_5}


```
 get_valid_tags_count(tags) 
```

Hämtar antalet giltiga taggar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Taggarna att validera. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Det giltiga antalet taggar. |


### Method: is_tag_present(tag) {#is_tag_present_tag_6}


```
 is_tag_present(tag) 
```

Bestämmer om taggen finns i alternativen eller inte.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | Tagg‑id att kontrollera. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om taggen finns; annars <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_7}


```
 remove_tag(tag) 
```

Tar bort taggen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | Taggen att ta bort. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | true om borttagning lyckades |


