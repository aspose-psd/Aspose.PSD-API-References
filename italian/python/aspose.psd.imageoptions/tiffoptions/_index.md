---
title: "Classe TiffOptions"
type: docs
weight: 130
url: /it/python-net/aspose.psd.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.TiffOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | Inizializza una nuova istanza della classe [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). Per impostazione predefinita viene utilizzata la convenzione little endian. |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | Inizializza una nuova istanza della classe [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| [TiffOptions(options)](#TiffOptions_options_3) | Inizializza una nuova istanza della classe [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| [TiffOptions(tags)](#TiffOptions_tags_4) | Inizializza una nuova istanza della classe [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/) | r/w | Ottiene o imposta l'opzione di archiviazione alpha. Le opzioni diverse da [TiffAlphaStorage.UNSPECIFIED](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/)<br/>            sono utilizzate quando sono definiti più di 3 [TiffOptions.samples_per_pixel](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| artista | string | r/w | Ottiene o imposta l'artista. |
| bits_per_pixel | int | r | Ottiene i bit per pixel. |
| bits_per_sample | ushort | r/w | Ottiene o imposta i bit per campione. |
| buffer_size_hint | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | r/w | Ottiene o imposta un valore che indica l'ordine dei byte tiff. |
| color_map | ushort | r/w | Ottiene o imposta la mappa dei colori. |
| compressed_quality | int | r/w | Ottiene o imposta la qualità dell'immagine compressa.<br/>            Utilizzata con la compressione Jpeg. |
| compression | [TiffCompressions](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffcompressions/) | r/w | Ottiene o imposta la compressione. |
| copyright | string | r/w | Ottiene o imposta il copyright. |
| date_time | string | r/w | Ottiene o imposta la data e l'ora. |
| default_memory_allocation_limit | int | r/w | Ottiene o imposta il limite di allocazione della memoria predefinito. |
| default_replacement_font | string | r/w | Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema).<br/>            Per ottenere il nome corretto del font predefinito può essere usato il seguente frammento di codice:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata rilasciata. |
| document_name | string | r/w | Ottiene o imposta il nome del documento. |
| exif_ifd | [TiffExifIfd](/psd/python-net/aspose.psd.fileformats.tiff/tiffexififd/) | r | Ottiene o imposta il puntatore a EXIF IFD. |
| fax_t4_options | [Group3Options](/psd/python-net/aspose.psd.fileformats.tiff.enums/group3options/) | r/w | Ottiene o imposta le opzioni fax t4. |
| file_standard | [TiffFileStandards](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffilestandards/) | r/w | Ottiene o imposta lo standard del file TIFF. |
| fill_order | [TiffFillOrders](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffillorders/) | r/w | Ottiene o imposta l'ordine di riempimento dei bit dei byte. |
| full_frame | bool | r/w | Ottiene o imposta un valore che indica se [full frame]. |
| half_tone_hints | ushort | r/w | Ottiene o imposta i suggerimenti per il mezzitono. |
| image_description | string | r/w | Ottiene o imposta la descrizione dell'immagine. |
| image_length | uint | r/w | Ottiene o imposta la lunghezza dell'immagine. |
| image_width | uint | r/w | Ottiene o imposta la larghezza dell'immagine. |
| ink_names | string | r/w | Ottiene o imposta i nomi dell'inchiostro. |
| is_extra_samples_present | bool | r | Ottiene un valore che indica se i campioni extra sono presenti. |
| is_tiled | bool | r | Restituisce un valore che indica se l'immagine è a tasselli. |
| is_valid | bool | r | Restituisce un valore che indica se le [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) sono state configurate correttamente. Utilizza il metodo Validate per trovare il motivo del fallimento. |
| max_sample_value | ushort | r/w | Ottiene o imposta il valore massimo del campione. |
| min_sample_value | ushort | r/w | Ottiene o imposta il valore minimo del campione. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Le opzioni multipagina |
| orientation | [TiffOrientations](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifforientations/) | r/w | Ottiene o imposta l'orientamento. |
| page_name | string | r/w | Ottiene o imposta il nome della pagina. |
| page_number | ushort | r/w | Ottiene o imposta il tag del numero di pagina. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Ottiene o imposta la tavolozza dei colori. |
| photometric | [TiffPhotometrics](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffphotometrics/) | r/w | Ottiene o imposta il fotometrico. |
| planar_configuration | [TiffPlanarConfigs](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | Ottiene o imposta la configurazione planare. |
| predictor | [TiffPredictor](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffpredictor/) | r/w | Ottiene o imposta il predittore per la compressione LZW. |
| premoltiplica_componenti | bool | r/w | Ottiene o imposta un valore che indica se i componenti devono essere premoltiplicati. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Ottiene o imposta le impostazioni di risoluzione. |
| resolution_unit | [TiffResolutionUnits](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffresolutionunits/) | r/w | Ottiene o imposta l'unità di risoluzione. |
| rows_per_strip | uint | r/w | Ottiene o imposta le righe per striscia. |
| sample_format | [TiffSampleFormats[]](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffsampleformats/) | r/w | Ottiene o imposta il formato del campione. |
| samples_per_pixel | ushort | r | Ottiene i campioni per pixel. Per modificare il valore di questa proprietà, utilizza il setter della proprietà [TiffOptions.bits_per_sample](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| scanner_manufacturer | string | r/w | Ottiene o imposta il produttore dello scanner. |
| scanner_model | string | r/w | Ottiene o imposta il modello dello scanner. |
| smax_sample_value | uint | r/w | Ottiene o imposta il valore massimo del campione. Il valore ha un tipo di campo che corrisponde al meglio ai dati del campione (tipo Byte, Short o Long). |
| smin_sample_value | uint | r/w | Ottiene o imposta il valore minimo del campione. Il valore ha un tipo di campo che corrisponde al meglio ai dati del campione (Byte, Short o Long). |
| software_type | string | r/w | Ottiene o imposta il tipo di software. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Ottiene o imposta la sorgente in cui creare l'immagine. |
| strip_byte_counts | uint | r/w | Ottiene o imposta i conteggi dei byte della striscia. |
| strip_offsets | uint | r/w | Ottiene o imposta gli offset della striscia. |
| sub_file_type | [TiffNewSubFileTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | Ottiene o imposta un'indicazione generale del tipo di dati contenuti in questo sottofile. |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Ottiene o imposta i tag. |
| target_printer | string | r/w | Ottiene o imposta la stampante di destinazione. |
| threshholding | [TiffThresholds](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffthresholds/) | r/w | Ottiene o imposta la soglia. |
| tile_byte_counts | uint | r/w | Ottiene o imposta i conteggi dei byte del tile. |
| tile_length | uint | r/w | Ottiene o imposta la lunghezza del tile. |
| tile_offsets | uint | r/w | Ottiene o imposta gli offset del tile. |
| tile_width | uint | r/w | Ottiene o imposta la larghezza del tile. |
| total_pages | ushort | r | Ottiene le pagine totali. |
| valid_tag_count | int | r | Ottiene il conteggio dei tag validi. Questo non è il conteggio totale dei tag ma il numero di tag che possono essere conservati. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Ottiene o imposta il contenitore dei metadati XMP. |
| xp_author | string | r/w | Ottiene o imposta l'autore dell'immagine, utilizzato da Windows Explorer. |
| xp_comment | string | r/w | Ottiene o imposta il commento sull'immagine, utilizzato da Windows Explorer. |
| xp_keywords | string | r/w | Ottiene o imposta il soggetto dell'immagine, utilizzato da Windows Explorer. |
| xp_subject | string | r/w | Ottiene o imposta le informazioni sull'immagine, utilizzato da Windows Explorer. |
| xp_title | string | r/w | Ottiene o imposta le informazioni sull'immagine, utilizzato da Windows Explorer. |
| xposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la posizione x. |
| xresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la risoluzione x. |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta i YCbCrCoefficients. |
| y_cb_cr_subsampling | ushort | r/w | Ottiene o imposta i fattori di sottocampionamento per la fotometria YCbCr. |
| yposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la posizione y. |
| yresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Ottiene o imposta la risoluzione y. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | Aggiunge un nuovo tag. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | Aggiunge i tag. |
| [clone()](#clone__3) | Clona questa istanza. |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_4) | Ottiene l'istanza del tag per tipo. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_5) | Ottiene il conteggio dei tag validi. |
| [is_tag_present(tag)](#is_tag_present_tag_6) | Determina se il tag è presente nelle opzioni o meno. |
| [remove_tag(tag)](#remove_tag_tag_7) | Rimuove il tag. |
| validate() | Convalida se le opzioni hanno una combinazione valida di tag |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

Inizializza una nuova istanza della classe [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). Per impostazione predefinita viene utilizzata la convenzione little endian.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | Il formato di file TIFF previsto. |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

Inizializza una nuova istanza della classe [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | Il formato di file TIFF previsto. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | L'ordine dei byte del formato file TIFF da utilizzare. |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

Inizializza una nuova istanza della classe [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions) | Le opzioni da cui copiare. |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

Inizializza una nuova istanza della classe [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | I tag con cui inizializzare le opzioni. |

### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

Aggiunge un nuovo tag.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Il tag da aggiungere. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

Aggiunge i tag.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | I tag da aggiungere. |

### Method: clone() {#clone__3}


```
 clone() 
```

Clona questa istanza.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Restituisce una copia superficiale di questa istanza |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_4}


```
 get_tag_by_type(tag_key) 
```

Ottiene l'istanza del tag per tipo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tag_key | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | La chiave del tag. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Istanza del tag se esiste, altrimenti null. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_5}


```
 get_valid_tags_count(tags) 
```

Ottiene il conteggio dei tag validi.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | I tag da convalidare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il conteggio dei tag validi. |


### Method: is_tag_present(tag) {#is_tag_present_tag_6}


```
 is_tag_present(tag) 
```

Determina se il tag è presente nelle opzioni o meno.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | L'ID del tag da verificare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>true</c> se il tag è presente; altrimenti, <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_7}


```
 remove_tag(tag) 
```

Rimuove il tag.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | Il tag da rimuovere. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | true se rimosso con successo |


