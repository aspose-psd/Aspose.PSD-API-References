---
title: "Classe BmpOptions"
type: docs
weight: 10
url: /fr/python-net/aspose.psd.imageoptions/bmpoptions/
---

**Summary:** The bmp file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.BmpOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BmpOptions()](#BmpOptions__1) | Initialise une nouvelle instance de la classe [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/). |
| [BmpOptions(bmp_options)](#BmpOptions_bmp_options_2) | Initialise une nouvelle instance de la classe [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bits_per_pixel | int | r/w | Obtient ou définit le nombre de bits par pixel de l'image. |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| compression | [BitmapCompression](/psd/python-net/aspose.psd.fileformats.bmp/bitmapcompression/) | r/w | Obtient ou définit la compression. |
| default_replacement_font | chaîne | r/w | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner du texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système).<br/>            Pour obtenir le nom correct de la police par défaut, le fragment de code suivant peut être utilisé :<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| full_frame | bool | r/w | Obtient ou définit une valeur indiquant si [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Les options multipages |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Obtient ou définit la palette de couleurs. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Obtient ou définit les paramètres de résolution. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Obtient ou définit la source dans laquelle créer l'image. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Obtient ou définit les options de rasterisation vectorielle. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Obtient ou définit le conteneur de métadonnées XMP. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clone cette instance. |


### Constructor: BmpOptions() {#BmpOptions__1}


```
 BmpOptions() 
```

Initialise une nouvelle instance de la classe [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/).

### Constructor: BmpOptions(bmp_options) {#BmpOptions_bmp_options_2}


```
 BmpOptions(bmp_options) 
```

Initialise une nouvelle instance de la classe [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bmp_options | [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions) | Les options BMP. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clone cette instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Renvoie une copie superficielle de cette instance |


