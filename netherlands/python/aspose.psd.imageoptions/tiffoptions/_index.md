---
title: "TiffOptions klasse"
type: docs
weight: 130
url: /nl/python-net/aspose.psd.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.TiffOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | Initialiseert een nieuw exemplaar van de [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) klasse. Standaard wordt de little‑endian‑conventie gebruikt. |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | Initialiseert een nieuw exemplaar van de [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) klasse. |
| [TiffOptions(options)](#TiffOptions_options_3) | Initialiseert een nieuw exemplaar van de [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) klasse. |
| [TiffOptions(tags)](#TiffOptions_tags_4) | Initialiseert een nieuw exemplaar van de [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/) | r/w | Haalt op of stelt de alfa‑opslagoptie in. Opties anders dan [TiffAlphaStorage.UNSPECIFIED](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/)<br/>            worden gebruikt wanneer er meer dan 3 [TiffOptions.samples_per_pixel](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) zijn gedefinieerd. |
| kunstenaar | string | r/w | Haalt op of stelt de kunstenaar in. |
| bits_per_pixel | int | r | Haalt de bits per pixel op. |
| bits_per_sample | ushort | r/w | Haalt op of stelt de bits per sample in. |
| buffer_size_hint | int | r/w | Haalt op of stelt de buffergroottehint in, die is gedefinieerd als de maximaal toegestane grootte voor alle interne buffers. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | r/w | Haalt op of stelt een waarde in die de TIFF‑bytevolgorde aangeeft. |
| color_map | ushort | r/w | Geeft of stelt de kleurkaart in. |
| compressed_quality | int | r/w | Geeft of stelt de gecomprimeerde afbeeldingskwaliteit in.<br/>            Gebruikt met de Jpeg-compressie. |
| compression | [TiffCompressions](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffcompressions/) | r/w | Haalt de compressie op of stelt deze in. |
| copyright | string | r/w | Geeft of stelt het copyright in. |
| date_time | string | r/w | Geeft of stelt de datum en tijd in. |
| default_memory_allocation_limit | int | r/w | Haalt of stelt de standaard geheugenallocatielimiet in. |
| default_replacement_font | string | r/w | Geeft of stelt het standaard vervangingslettertype in (lettertype dat wordt gebruikt om tekst te tekenen bij exporteren naar raster, als het bestaande laaglettertype in het PSD‑bestand niet in het systeem aanwezig is).<br/>            Om de juiste naam van het standaardlettertype te verkrijgen, kan de volgende codefragment worden gebruikt:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Geeft een waarde die aangeeft of dit exemplaar is vrijgegeven. |
| document_name | string | r/w | Geeft of stelt de naam van het document in. |
| exif_ifd | [TiffExifIfd](/psd/python-net/aspose.psd.fileformats.tiff/tiffexififd/) | r | Haalt op of stelt de pointer naar EXIF IFD in. |
| fax_t4_options | [Group3Options](/psd/python-net/aspose.psd.fileformats.tiff.enums/group3options/) | r/w | Geeft of stelt de fax t4-opties in. |
| file_standard | [TiffFileStandards](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffilestandards/) | r/w | Geeft of stelt de TIFF-bestandsstandaard in. |
| fill_order | [TiffFillOrders](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffillorders/) | r/w | Geeft of stelt de vulvolgorde van bytebits in. |
| full_frame | bool | r/w | Geeft een waarde op of haalt deze op die aangeeft of [full frame]. |
| half_tone_hints | ushort | r/w | Geeft of stelt de halftoonhints in. |
| image_description | string | r/w | Geeft of stelt de afbeeldingsbeschrijving in. |
| image_length | uint | r/w | Geeft of stelt de afbeeldingslengte in. |
| image_width | uint | r/w | Geeft of stelt de afbeeldingsbreedte in. |
| ink_names | string | r/w | Geeft of stelt de inktnamen in. |
| is_extra_samples_present | bool | r | Geeft een waarde die aangeeft of de extra monsters aanwezig zijn. |
| is_tiled | bool | r | Haalt een waarde op die aangeeft of de afbeelding getegeld is. |
| is_valid | bool | r | Haalt een waarde op die aangeeft of de [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) correct zijn geconfigureerd. Gebruik de Validate-methode om de foutoorzaak te vinden. |
| max_sample_value | ushort | r/w | Haalt of stelt de maximale monsterwaarde in. |
| min_sample_value | ushort | r/w | Haalt of stelt de minimale monsterwaarde in. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | De multipagina-opties |
| orientation | [TiffOrientations](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifforientations/) | r/w | Haalt of stelt de oriëntatie in. |
| page_name | string | r/w | Haalt of stelt de paginanaam in. |
| page_number | ushort | r/w | Haalt of stelt de paginanummer-tag in. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Geeft het kleurenpalet op of haalt dit op. |
| photometric | [TiffPhotometrics](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffphotometrics/) | r/w | Haalt of stelt de fotometrie in. |
| planar_configuration | [TiffPlanarConfigs](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | Haalt of stelt de planaire configuratie in. |
| predictor | [TiffPredictor](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffpredictor/) | r/w | Haalt of stelt de predictor voor LZW-compressie in. |
| premultiply_components | bool | r/w | Haalt of stelt een waarde in die aangeeft of componenten voorvermenigvuldigd moeten worden. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Geeft de resolutie-instellingen op of haalt deze op. |
| resolution_unit | [TiffResolutionUnits](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffresolutionunits/) | r/w | Haalt of stelt de resolutie‑eenheid in. |
| rows_per_strip | uint | r/w | Haalt of stelt het aantal rijen per strook in. |
| sample_format | [TiffSampleFormats[]](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffsampleformats/) | r/w | Haalt of stelt het monsterformaat in. |
| samples_per_pixel | ushort | r | Haalt het aantal monsters per pixel op. Om deze eigenschapswaarde te wijzigen, gebruik de setter van de [TiffOptions.bits_per_sample](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) eigenschap. |
| scanner_manufacturer | string | r/w | Haalt of stelt de scannerfabrikant in. |
| scanner_model | string | r/w | Haalt of stelt het scannermodel in. |
| smax_sample_value | uint | r/w | Haalt of stelt de maximale monsterwaarde in. De waarde heeft een veldtype dat het beste overeenkomt met de monstergegevens (Byte-, Short- of Long-type). |
| smin_sample_value | uint | r/w | Haalt of stelt de minimale monsterwaarde in. De waarde heeft een veldtype dat het beste overeenkomt met de monstergegevens (Byte, Short of Long type). |
| software_type | string | r/w | Haalt of stelt het type software in. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Haalt de bron op of stelt deze in om de afbeelding te maken. |
| strip_byte_counts | uint | r/w | Haalt of stelt de strip‑byte‑telling in. |
| strip_offsets | uint | r/w | Haalt of stelt de strip‑offsets in. |
| sub_file_type | [TiffNewSubFileTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | Haalt of stelt een algemene indicatie van het type gegevens dat in dit subbestand zit, in. |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Haalt of stelt de tags in. |
| target_printer | string | r/w | Haalt of stelt de doelprinter in. |
| threshholding | [TiffThresholds](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffthresholds/) | r/w | Haalt of stelt de drempelwaarde in. |
| tile_byte_counts | uint | r/w | Haalt of stelt de tegel‑byte‑telling in. |
| tile_length | uint | r/w | Haalt ot stelt tile length. |
| tile_offsets | uint | r/w | Haalt of stelt de tegel‑offsets in. |
| tile_width | uint | r/w | Haalt ot stelt tile width. |
| total_pages | ushort | r | Haalt de totale pagina's op. |
| valid_tag_count | int | r | Haalt de geldige tagtelling op. Dit is niet het totale aantal tags, maar het aantal tags dat bewaard kan blijven. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Haalt de vectorrasterisatie‑opties op of stelt deze in. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Haalt de XMP-metadatacontainer op of stelt deze in. |
| xp_author | string | r/w | Haalt op of stelt de afbeelding auteur in, die wordt gebruikt door Windows Verkenner. |
| xp_comment | string | r/w | Haalt op of stelt een opmerking op de afbeelding in, die wordt gebruikt door Windows Verkenner. |
| xp_keywords | string | r/w | Haalt op of stelt het onderwerp van de afbeelding in, die wordt gebruikt door Windows Verkenner. |
| xp_subject | string | r/w | Haalt op of stelt informatie over de afbeelding in, die wordt gebruikt door Windows Verkenner. |
| xp_title | string | r/w | Haalt op of stelt informatie over de afbeelding in, die wordt gebruikt door Windows Verkenner. |
| xposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt op of stelt de x-positie in. |
| xresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt op of stelt de x-resolutie in. |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt op of stelt de YCbCrCoefficients in. |
| y_cb_cr_subsampling | ushort | r/w | Haalt op of stelt de subsamplingfactoren voor YCbCr-fotometrisch in. |
| yposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt op of stelt de y-positie in. |
| yresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Haalt op of stelt de y-resolutie in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | Voegt een nieuw label toe. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | Voegt de labels toe. |
| [clone()](#clone__3) | Kloont deze instantie. |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_4) | Haalt de instantie van het label op op type. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_5) | Haalt het aantal geldige tags op. |
| [is_tag_present(tag)](#is_tag_present_tag_6) | Bepaalt of het label aanwezig is in de opties al dan niet. |
| [remove_tag(tag)](#remove_tag_tag_7) | Verwijdert het label. |
| validate() | Valideert of de opties een geldige combinatie van labels hebben |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

Initialiseert een nieuw exemplaar van de [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) klasse. Standaard wordt de little‑endian‑conventie gebruikt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | Het verwachte TIFF‑bestandsformaat. |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

Initialiseert een nieuw exemplaar van de [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | Het verwachte TIFF‑bestandsformaat. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | De bytevolgorde van het TIFF-bestandsformaat die moet worden gebruikt. |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

Initialiseert een nieuw exemplaar van de [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions) | De opties om van te kopiëren. |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

Initialiseert een nieuw exemplaar van de [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | De tags om opties mee te initialiseren. |

### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

Voegt een nieuw label toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | De tag om toe te voegen. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

Voegt de labels toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | De tags om toe te voegen. |

### Method: clone() {#clone__3}


```
 clone() 
```

Kloont deze instantie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Retourneert een ondiepe kopie van deze instantie. |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_4}


```
 get_tag_by_type(tag_key) 
```

Haalt de instantie van het label op op type.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| tag_key | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | De tag-sleutel. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Instantie van de tag als deze bestaat, anders null. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_5}


```
 get_valid_tags_count(tags) 
```

Haalt het aantal geldige tags op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | De te valideren tags. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | Het aantal geldige tags. |


### Method: is_tag_present(tag) {#is_tag_present_tag_6}


```
 is_tag_present(tag) 
```

Bepaalt of het label aanwezig is in de opties al dan niet.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | De tag-id om te controleren. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <c>true</c> als de tag aanwezig is; anders <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_7}


```
 remove_tag(tag) 
```

Verwijdert het label.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | De tag om te verwijderen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | true als succesvol verwijderd |


