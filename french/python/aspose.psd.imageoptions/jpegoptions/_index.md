---
title: "Classe JpegOptions"
type: docs
weight: 60
url: /fr/python-net/aspose.psd.imageoptions/jpegoptions/
---

**Summary:** The jpeg file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.JpegOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | Initialise une nouvelle instance de la classe [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/). |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | Initialise une nouvelle instance de la classe [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bits_per_channel | byte | r/w | Obtient ou définit les bits par canal pour une image jpeg sans perte. Nous supportons désormais de 2 à 8 bits par canal. |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Le profil couleur CMYK de destination pour les images jpeg CMYK. À utiliser pour enregistrer les images. Doit être associé au profil RGBColorProfile pour une conversion de couleur correcte. |
| color_type | [JpegCompressionColorMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressioncolormode/) | r/w | Obtient ou définit le type de couleur pour l'image jpeg. |
| commentaire | chaîne | r/w | Obtient ou définit le commentaire du fichier jpeg. |
| compression_type | [JpegCompressionMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressionmode/) | r/w | Obtient ou définit le type de compression. |
| default_memory_allocation_limit | int | r/w | Obtient ou définit la limite d'allocation mémoire par défaut. |
| default_replacement_font | chaîne | r/w | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner du texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système).<br/>            Pour obtenir le nom correct de la police par défaut, le fragment de code suivant peut être utilisé :<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| exif_data | [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) | r/w | Obtenir ou définir le conteneur de données exif |
| full_frame | bool | r/w | Obtient ou définit une valeur indiquant si [full frame]. |
| horizontal_sampling | byte | r/w | Obtient ou définit les sous-échantillonnages horizontaux pour chaque composant. |
| jfif | [JFIFData](/psd/python-net/aspose.psd.fileformats.jpeg/jfifdata/) | r/w | Obtient ou définit le jfif. |
| jpeg_ls_allowed_lossy_error | int | r/w | Obtient ou définit la limite de différence JPEG-LS pour le codage quasi sans perte (paramètre NEAR de la spécification JPEG-LS). |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglsinterleavemode/) | r/w | Obtient ou définit le mode d'entrelacement JPEG-LS. |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | Obtient ou définit les paramètres prédéfinis JPEG-LS. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Les options multipages |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Obtient ou définit la palette de couleurs. |
| preblend_alpha_if_present | bool | r/w | Obtient ou définit une valeur indiquant si les composants rouge, vert et bleu doivent être mélangés avec une couleur d'arrière-plan, si le canal alpha est présent. |
| quality | int | r/w | Obtient ou définit la qualité de l'image. |
| rd_opt_settings | [RdOptimizerSettings](/psd/python-net/aspose.psd.imageoptions/rdoptimizersettings) | r/w | Obtient ou définit les paramètres de l'optimiseur RD. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Obtient ou définit les paramètres de résolution. |
| resolution_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit) | r/w | Obtient ou définit l'unité de résolution. |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Le profil couleur RGB de destination pour les images jpeg CMYK. À utiliser pour enregistrer les images. Doit être associé au profil CMYKColorProfile pour une conversion de couleur correcte. |
| sample_rounding_mode | [SampleRoundingMode](/psd/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/) | r/w | Obtient ou définit le mode d'arrondi d'échantillon pour adapter une valeur de 8 bits à une valeur de n bits. <see cref="P:JpegOptions.BitsPerChannel" /> |
| scaled_quality | int | r | La qualité mise à l'échelle. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Obtient ou définit la source dans laquelle créer l'image. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Obtient ou définit les options de rasterisation vectorielle. |
| vertical_sampling | byte | r/w | Obtient ou définit les sous-échantillonnages verticaux pour chaque composant. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Obtient ou définit le conteneur de métadonnées XMP. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clone cette instance. |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

Initialise une nouvelle instance de la classe [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/).

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

Initialise une nouvelle instance de la classe [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions) | Les options JPEG. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clone cette instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Renvoie une copie superficielle de cette instance |


