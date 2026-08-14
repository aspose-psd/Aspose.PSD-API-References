---
title: "TiffOptions Klasse"
type: docs
weight: 130
url: /de/python-net/aspose.psd.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.TiffOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | Initialisiert eine neue Instanz der [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) Klasse. Standardmäßig wird die Little-Endian-Konvention verwendet. |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | Initialisiert eine neue Instanz der [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) Klasse. |
| [TiffOptions(options)](#TiffOptions_options_3) | Initialisiert eine neue Instanz der [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) Klasse. |
| [TiffOptions(tags)](#TiffOptions_tags_4) | Initialisiert eine neue Instanz der [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/) | r/w | Liest oder setzt die Alpha-Speicheroption. Optionen außer [TiffAlphaStorage.UNSPECIFIED](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/)<br/>            werden verwendet, wenn mehr als 3 [TiffOptions.samples_per_pixel](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) definiert sind. |
| Künstler | string | r/w | Liest oder setzt den Künstler. |
| bits_per_pixel | int | r | Liest die Bits pro Pixel. |
| bits_per_sample | ushort | r/w | Liest oder setzt die Bits pro Sample. |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | r/w | Liest oder setzt einen Wert, der die TIFF-Byte-Reihenfolge angibt. |
| color_map | ushort | r/w | Liest oder setzt die Farbkarte. |
| compressed_quality | int | r/w | Liest oder setzt die komprimierte Bildqualität.<br/>            Wird mit der Jpeg-Kompression verwendet. |
| compression | [TiffCompressions](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffcompressions/) | r/w | Liest oder setzt die Kompression. |
| copyright | string | r/w | Liest oder setzt das Copyright. |
| date_time | string | r/w | Liest oder setzt Datum und Uhrzeit. |
| default_memory_allocation_limit | int | r/w | Liest oder setzt das Standard‑Speicherzuweisungs‑Limit. |
| default_replacement_font | string | r/w | Ruft den Standard-Ersatzschriftart ab oder legt sie fest (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen-Schriftart in der PSD-Datei im System nicht vorhanden ist).<br/>            Um den richtigen Namen der Standardschriftart zu erhalten, kann der folgende Codeabschnitt verwendet werden:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Ruft einen Wert ab, der angibt, ob diese Instanz freigegeben wurde. |
| document_name | string | r/w | Liest oder setzt den Namen des Dokuments. |
| exif_ifd | [TiffExifIfd](/psd/python-net/aspose.psd.fileformats.tiff/tiffexififd/) | r | Liest oder setzt den Zeiger auf das EXIF IFD. |
| fax_t4_options | [Group3Options](/psd/python-net/aspose.psd.fileformats.tiff.enums/group3options/) | r/w | Liest oder setzt die Fax‑T4‑Optionen. |
| file_standard | [TiffFileStandards](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffilestandards/) | r/w | Liest oder setzt den TIFF-Dateistandard. |
| fill_order | [TiffFillOrders](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffillorders/) | r/w | Liest oder setzt die Füllreihenfolge der Byte‑Bits. |
| full_frame | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob [full frame]. |
| half_tone_hints | ushort | r/w | Liest oder setzt die Halftone‑Hinweise. |
| image_description | string | r/w | Liest oder setzt die Bildbeschreibung. |
| image_length | uint | r/w | Liest oder setzt die Bildlänge. |
| image_width | uint | r/w | Liest oder setzt die Bildbreite. |
| ink_names | string | r/w | Liest oder setzt die Tinten­namen. |
| is_extra_samples_present | bool | r | Gibt einen Wert zurück, der angibt, ob die zusätzlichen Proben vorhanden sind. |
| is_tiled | bool | r | Gibt einen Wert zurück, der angibt, ob das Bild gekachelt ist. |
| is_valid | bool | r | Gibt einen Wert zurück, der angibt, ob die [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) korrekt konfiguriert wurden. Verwenden Sie die Validate-Methode, um den Fehlergrund zu ermitteln. |
| max_sample_value | ushort | r/w | Liest oder setzt den maximalen Stichprobenwert. |
| min_sample_value | ushort | r/w | Liest oder setzt den minimalen Stichprobenwert. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Die Mehrseitigen Optionen |
| orientation | [TiffOrientations](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifforientations/) | r/w | Liest oder setzt die Orientierung. |
| page_name | string | r/w | Liest oder setzt den Seitennamen. |
| page_number | ushort | r/w | Liest oder setzt das Seitenzahl-Tag. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Ruft die Farbpalette ab oder legt sie fest. |
| photometric | [TiffPhotometrics](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffphotometrics/) | r/w | Liest oder setzt die photometrische Einstellung. |
| planar_configuration | [TiffPlanarConfigs](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | Liest oder setzt die planare Konfiguration. |
| predictor | [TiffPredictor](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffpredictor/) | r/w | Liest oder setzt den Prädiktor für die LZW-Kompression. |
| premultiply_components | bool | r/w | Liest oder setzt einen Wert, der angibt, ob Komponenten vorvermultipliziert werden müssen. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Liest oder setzt die Auflösungseinstellungen. |
| resolution_unit | [TiffResolutionUnits](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffresolutionunits/) | r/w | Liest oder setzt die Auflösungseinheit. |
| rows_per_strip | uint | r/w | Liest oder setzt die Zeilen pro Streifen. |
| sample_format | [TiffSampleFormats[]](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffsampleformats/) | r/w | Liest oder setzt das Stichprobenformat. |
| samples_per_pixel | ushort | r | Liest die Stichproben pro Pixel. Um diesen Eigenschaftswert zu ändern, verwenden Sie den Setter der [TiffOptions.bits_per_sample](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) Eigenschaft. |
| scanner_manufacturer | string | r/w | Liest oder setzt den Scanner-Hersteller. |
| scanner_model | string | r/w | Liest oder setzt das Scanner‑Modell. |
| smax_sample_value | uint | r/w | Liest oder setzt den maximalen Stichprobenwert. Der Wert hat einen Feldtyp, der am besten zu den Stichprobendaten passt (Byte, Short oder Long type). |
| smin_sample_value | uint | r/w | Liest oder setzt den minimalen Stichprobenwert. Der Wert hat einen Feldtyp, der am besten zu den Stichprobendaten passt (Byte, Short oder Long type). |
| software_type | string | r/w | Liest oder setzt den Softwaretyp. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Liest oder setzt die Quelle, in der das Bild erstellt wird. |
| strip_byte_counts | uint | r/w | Liest oder setzt die Strip‑Byte‑Zähler. |
| strip_offsets | uint | r/w | Liest oder setzt die Strip‑Offsets. |
| sub_file_type | [TiffNewSubFileTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | Liest oder setzt eine allgemeine Angabe zur Art der in dieser Unterdatei enthaltenen Daten. |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Liest oder setzt die Tags. |
| target_printer | string | r/w | Liest oder setzt den Ziel‑Drucker. |
| threshholding | [TiffThresholds](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffthresholds/) | r/w | Liest oder setzt die Schwellenwertbestimmung. |
| tile_byte_counts | uint | r/w | Liest oder setzt die Tile‑Byte‑Zähler. |
| tile_length | uint | r/w | Liest ot setzt Tile‑Länge. |
| tile_offsets | uint | r/w | Liest oder setzt die Tile‑Offsets. |
| tile_width | uint | r/w | Liest ot setzt Tile‑Breite. |
| total_pages | ushort | r | Gibt die Gesamtseitenzahl zurück. |
| valid_tag_count | int | r | Gibt die Anzahl gültiger Tags zurück. Dies ist nicht die Gesamtzahl der Tags, sondern die Anzahl der Tags, die erhalten werden können. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Liest oder setzt die Vektor‑Rasterisierungsoptionen. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Liest oder setzt den XMP‑Metadatencontainer. |
| xp_author | string | r/w | Liest oder setzt den Bildautor, der von Windows Explorer verwendet wird. |
| xp_comment | string | r/w | Liest oder setzt den Kommentar zum Bild, der von Windows Explorer verwendet wird. |
| xp_keywords | string | r/w | Liest oder setzt den Betreff des Bildes, der von Windows Explorer verwendet wird. |
| xp_subject | string | r/w | Liest oder setzt Informationen zum Bild, die von Windows Explorer verwendet werden. |
| xp_title | string | r/w | Liest oder setzt Informationen zum Bild, die von Windows Explorer verwendet werden. |
| xposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die x-Position. |
| xresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die x-Auflösung. |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die YCbCr-Koeffizienten. |
| y_cb_cr_subsampling | ushort | r/w | Liest oder setzt die Subsampling-Faktoren für die YCbCr-Photometrie. |
| yposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die y-Position. |
| yresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Liest oder setzt die y-Auflösung. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | Fügt ein neues Tag hinzu. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | Fügt die Tags hinzu. |
| [clone()](#clone__3) | Klonen Sie diese Instanz. |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_4) | Gibt die Instanz des Tags nach Typ zurück. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_5) | Liest die Anzahl gültiger Tags. |
| [is_tag_present(tag)](#is_tag_present_tag_6) | Bestimmt, ob das Tag in den Optionen vorhanden ist oder nicht. |
| [remove_tag(tag)](#remove_tag_tag_7) | Entfernt das Tag. |
| validate() | Validiert, ob die Optionen eine gültige Kombination von Tags haben |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

Initialisiert eine neue Instanz der [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) Klasse. Standardmäßig wird die Little-Endian-Konvention verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | Das erwartete TIFF‑Dateiformat. |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

Initialisiert eine neue Instanz der [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | Das erwartete TIFF‑Dateiformat. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | Die Byte‑Reihenfolge des TIFF‑Dateiformats, die verwendet werden soll. |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

Initialisiert eine neue Instanz der [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions) | Die Optionen, von denen kopiert werden soll. |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

Initialisiert eine neue Instanz der [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Die Tags, mit denen die Optionen initialisiert werden. |

### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

Fügt ein neues Tag hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Das hinzuzufügende Tag. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

Fügt die Tags hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Die hinzuzufügenden Tags. |

### Method: clone() {#clone__3}


```
 clone() 
```

Klonen Sie diese Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Gibt eine flache Kopie dieser Instanz zurück |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_4}


```
 get_tag_by_type(tag_key) 
```

Gibt die Instanz des Tags nach Typ zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tag_key | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | Der Tag‑Schlüssel. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Instanz des Tags, falls vorhanden, sonst null. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_5}


```
 get_valid_tags_count(tags) 
```

Liest die Anzahl gültiger Tags.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Die zu validierenden Tags. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die gültige Tag-Anzahl. |


### Method: is_tag_present(tag) {#is_tag_present_tag_6}


```
 is_tag_present(tag) 
```

Bestimmt, ob das Tag in den Optionen vorhanden ist oder nicht.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | Die zu prüfende Tag‑ID. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn das Tag vorhanden ist; andernfalls <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_7}


```
 remove_tag(tag) 
```

Entfernt das Tag.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | Das zu entfernende Tag. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | true, wenn erfolgreich entfernt |


