---
title: "Classe TiffOptions"
type: docs
weight: 130
url: /fr/python-net/aspose.psd.imageoptions/tiffoptions/
---

**Summary:** The tiff file format options.<br/>                Note that width and height tags will get overwritten on image creation by width and height parameters so there is no need to specify them directly.<br/>                Note that many options return a default value but that does not mean that this option is set explicitly as a tag value. To verify the tag is present use Tags property or the corresponding IsTagPresent method.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.TiffOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffOptions(expected_format)](#TiffOptions_expected_format_1) | Initialise une nouvelle instance de la classe [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). Par défaut, la convention little endian est utilisée. |
| [TiffOptions(expected_format, byte_order)](#TiffOptions_expected_format_byte_order_2) | Initialise une nouvelle instance de la classe [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| [TiffOptions(options)](#TiffOptions_options_3) | Initialise une nouvelle instance de la classe [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| [TiffOptions(tags)](#TiffOptions_tags_4) | Initialise une nouvelle instance de la classe [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alpha_storage | [TiffAlphaStorage](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/) | r/w | Obtient ou définit l'option de stockage alpha. Les options autres que [TiffAlphaStorage.UNSPECIFIED](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffalphastorage/)<br/>            sont utilisées lorsqu'il y a plus de 3 [TiffOptions.samples_per_pixel](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) définies. |
| artiste | chaîne | r/w | Obtient ou définit l'artiste. |
| bits_per_pixel | int | r | Obtient les bits par pixel. |
| bits_per_sample | ushort | r/w | Obtient ou définit les bits par échantillon. |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | r/w | Obtient ou définit une valeur indiquant l'ordre des octets tiff. |
| color_map | ushort | r/w | Obtient ou définit la carte des couleurs. |
| compressed_quality | int | r/w | Obtient ou définit la qualité de l'image compressée.<br/>            Utilisé avec la compression Jpeg. |
| compression | [TiffCompressions](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffcompressions/) | r/w | Obtient ou définit la compression. |
| copyright | chaîne | r/w | Obtient ou définit le copyright. |
| date_time | chaîne | r/w | Obtient ou définit la date et l'heure. |
| default_memory_allocation_limit | int | r/w | Obtient ou définit la limite d'allocation mémoire par défaut. |
| default_replacement_font | chaîne | r/w | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner du texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système).<br/>            Pour obtenir le nom correct de la police par défaut, le fragment de code suivant peut être utilisé :<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| document_name | chaîne | r/w | Obtient ou définit le nom du document. |
| exif_ifd | [TiffExifIfd](/psd/python-net/aspose.psd.fileformats.tiff/tiffexififd/) | r | Obtient ou définit le pointeur vers l'IFD EXIF. |
| fax_t4_options | [Group3Options](/psd/python-net/aspose.psd.fileformats.tiff.enums/group3options/) | r/w | Obtient ou définit les options fax t4. |
| file_standard | [TiffFileStandards](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffilestandards/) | r/w | Obtient ou définit la norme du fichier TIFF. |
| fill_order | [TiffFillOrders](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifffillorders/) | r/w | Obtient ou définit l'ordre de remplissage des bits d'octet. |
| full_frame | bool | r/w | Obtient ou définit une valeur indiquant si [full frame]. |
| half_tone_hints | ushort | r/w | Obtient ou définit les indications de tramage. |
| image_description | chaîne | r/w | Obtient ou définit la description de l'image. |
| image_length | uint | r/w | Obtient ou définit la longueur de l'image. |
| image_width | uint | r/w | Obtient ou définit la largeur de l'image. |
| ink_names | chaîne | r/w | Obtient ou définit les noms d'encre. |
| is_extra_samples_present | bool | r | Obtient une valeur indiquant si les échantillons supplémentaires sont présents. |
| is_tiled | bool | r | Renvoie une valeur indiquant si l'image est découpée en tuiles. |
| is_valid | bool | r | Renvoie une valeur indiquant si les [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/) ont été correctement configurés. Utilisez la méthode Validate pour trouver la raison de l'échec. |
| max_sample_value | ushort | r/w | Obtient ou définit la valeur d'échantillon maximale. |
| min_sample_value | ushort | r/w | Obtient ou définit la valeur d'échantillon minimale. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Les options multipages |
| orientation | [TiffOrientations](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifforientations/) | r/w | Obtient ou définit l'orientation. |
| page_name | chaîne | r/w | Obtient ou définit le nom de la page. |
| page_number | ushort | r/w | Obtient ou définit l'étiquette du numéro de page. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Obtient ou définit la palette de couleurs. |
| photometric | [TiffPhotometrics](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffphotometrics/) | r/w | Obtient ou définit le paramètre photométrique. |
| planar_configuration | [TiffPlanarConfigs](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffplanarconfigs/) | r/w | Obtient ou définit la configuration planaire. |
| predictor | [TiffPredictor](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffpredictor/) | r/w | Obtient ou définit le prédicteur pour la compression LZW. |
| composants_premultipliés | bool | r/w | Obtient ou définit une valeur indiquant si les composants doivent être prémultipliés. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Obtient ou définit les paramètres de résolution. |
| resolution_unit | [TiffResolutionUnits](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffresolutionunits/) | r/w | Obtient ou définit l'unité de résolution. |
| rows_per_strip | uint | r/w | Obtient ou définit le nombre de lignes par bande. |
| sample_format | [TiffSampleFormats[]](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffsampleformats/) | r/w | Obtient ou définit le format d'échantillon. |
| samples_per_pixel | ushort | r | Obtient les échantillons par pixel. Pour modifier la valeur de cette propriété, utilisez le définisseur de propriété [TiffOptions.bits_per_sample](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). |
| scanner_manufacturer | chaîne | r/w | Obtient ou définit le fabricant du scanner. |
| scanner_model | chaîne | r/w | Obtient ou définit le modèle du scanner. |
| smax_sample_value | uint | r/w | Obtient ou définit la valeur d'échantillon maximale. La valeur possède un type de champ qui correspond le mieux aux données d'échantillon (type Byte, Short ou Long). |
| smin_sample_value | uint | r/w | Obtient ou définit la valeur d'échantillon minimale. La valeur possède un type de champ qui correspond le mieux aux données d'échantillon (Byte, Short ou Long). |
| software_type | chaîne | r/w | Obtient ou définit le type de logiciel. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Obtient ou définit la source dans laquelle créer l'image. |
| strip_byte_counts | uint | r/w | Obtient ou définit le nombre d'octets de bande. |
| strip_offsets | uint | r/w | Obtient ou définit les décalages de bande. |
| sub_file_type | [TiffNewSubFileTypes](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffnewsubfiletypes/) | r/w | Obtient ou définit une indication générale du type de données contenues dans ce sous-fichier. |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | r/w | Obtient ou définit les balises. |
| target_printer | chaîne | r/w | Obtient ou définit l'imprimante cible. |
| threshholding | [TiffThresholds](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffthresholds/) | r/w | Obtient ou définit le seuillage. |
| tile_byte_counts | uint | r/w | Obtient ou définit le nombre d'octets de tuile. |
| tile_length | uint | r/w | Obtient ou définit la longueur de la tuile. |
| tile_offsets | uint | r/w | Obtient ou définit les décalages de tuile. |
| tile_width | uint | r/w | Obtient ou définit la largeur de la tuile. |
| total_pages | ushort | r | Obtient le nombre total de pages. |
| valid_tag_count | int | r | Obtient le nombre de balises valides. Ce n'est pas le nombre total de balises mais le nombre de balises qui peuvent être conservées. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Obtient ou définit les options de rasterisation vectorielle. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Obtient ou définit le conteneur de métadonnées XMP. |
| xp_author | chaîne | r/w | Obtient ou définit l'auteur de l'image, utilisé par l'Explorateur Windows. |
| xp_comment | chaîne | r/w | Obtient ou définit le commentaire de l'image, utilisé par l'Explorateur Windows. |
| xp_keywords | chaîne | r/w | Obtient ou définit le sujet de l'image, utilisé par l'Explorateur Windows. |
| xp_subject | chaîne | r/w | Obtient ou définit les informations sur l'image, utilisées par l'Explorateur Windows. |
| xp_title | chaîne | r/w | Obtient ou définit les informations sur l'image, utilisées par l'Explorateur Windows. |
| xposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la position x. |
| xresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la résolution x. |
| y_cb_cr_coefficients | [TiffRational[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit les coefficients YCbCr. |
| y_cb_cr_subsampling | ushort | r/w | Obtient ou définit les facteurs de sous-échantillonnage pour le photométrique YCbCr. |
| yposition | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la position y. |
| yresolution | [TiffRational](/psd/python-net/aspose.psd.fileformats.tiff/tiffrational/) | r/w | Obtient ou définit la résolution y. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_tag(tag_to_add)](#add_tag_tag_to_add_1) | Ajoute une nouvelle balise. |
| [add_tags(tags_to_add)](#add_tags_tags_to_add_2) | Ajoute les balises. |
| [clone()](#clone__3) | Clone cette instance. |
| [get_tag_by_type(tag_key)](#get_tag_by_type_tag_key_4) | Obtient l'instance de la balise par type. |
| [get_valid_tags_count(tags)](#get_valid_tags_count_tags_5) | Obtient le nombre d'étiquettes valides. |
| [is_tag_present(tag)](#is_tag_present_tag_6) | Détermine si la balise est présente dans les options ou non. |
| [remove_tag(tag)](#remove_tag_tag_7) | Supprime la balise. |
| validate() | Valide si les options ont une combinaison valide de balises |


### Constructor: TiffOptions(expected_format) {#TiffOptions_expected_format_1}


```
 TiffOptions(expected_format) 
```

Initialise une nouvelle instance de la classe [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/). Par défaut, la convention little endian est utilisée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | Le format de fichier TIFF attendu. |

### Constructor: TiffOptions(expected_format, byte_order) {#TiffOptions_expected_format_byte_order_2}


```
 TiffOptions(expected_format, byte_order) 
```

Initialise une nouvelle instance de la classe [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| expected_format | [TiffExpectedFormat](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffexpectedformat/) | Le format de fichier TIFF attendu. |
| byte_order | [TiffByteOrder](/psd/python-net/aspose.psd.fileformats.tiff.enums/tiffbyteorder/) | L'ordre des octets du format de fichier TIFF à utiliser. |

### Constructor: TiffOptions(options) {#TiffOptions_options_3}


```
 TiffOptions(options) 
```

Initialise une nouvelle instance de la classe [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions) | Les options à copier. |

### Constructor: TiffOptions(tags) {#TiffOptions_tags_4}


```
 TiffOptions(tags) 
```

Initialise une nouvelle instance de la classe [TiffOptions](/psd/python-net/aspose.psd.imageoptions/tiffoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Les étiquettes avec lesquelles initialiser les options. |

### Method: add_tag(tag_to_add) {#add_tag_tag_to_add_1}


```
 add_tag(tag_to_add) 
```

Ajoute une nouvelle balise.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tag_to_add | [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | L'étiquette à ajouter. |

### Method: add_tags(tags_to_add) {#add_tags_tags_to_add_2}


```
 add_tags(tags_to_add) 
```

Ajoute les balises.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tags_to_add | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Les étiquettes à ajouter. |

### Method: clone() {#clone__3}


```
 clone() 
```

Clone cette instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Renvoie une copie superficielle de cette instance |


### Method: get_tag_by_type(tag_key) {#get_tag_by_type_tag_key_4}


```
 get_tag_by_type(tag_key) 
```

Obtient l'instance de la balise par type.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tag_key | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | La clé de l'étiquette. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffDataType](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Instance de l'étiquette si elle existe ou null sinon. |


### Method: get_valid_tags_count(tags)  [static] {#get_valid_tags_count_tags_5}


```
 get_valid_tags_count(tags) 
```

Obtient le nombre d'étiquettes valides.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tags | [TiffDataType[]](/psd/python-net/aspose.psd.fileformats.tiff/tiffdatatype/) | Les étiquettes à valider. |

**Returns**

| Type | Description |
| :- | :- |
| int | Le nombre d'étiquettes valides. |


### Method: is_tag_present(tag) {#is_tag_present_tag_6}


```
 is_tag_present(tag) 
```

Détermine si la balise est présente dans les options ou non.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | L'ID de l'étiquette à vérifier. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si l'étiquette est présente; sinon, <c>false</c>. |


### Method: remove_tag(tag) {#remove_tag_tag_7}


```
 remove_tag(tag) 
```

Supprime la balise.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| tag | [TiffTags](/psd/python-net/aspose.psd.fileformats.tiff.enums/tifftags/) | L'étiquette à supprimer. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true si la suppression a réussi |


