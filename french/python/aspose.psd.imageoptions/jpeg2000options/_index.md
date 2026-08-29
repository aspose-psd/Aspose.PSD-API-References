---
title: "Classe Jpeg2000Options"
type: docs
weight: 50
url: /fr/python-net/aspose.psd.imageoptions/jpeg2000options/
---

**Summary:** The Jpeg2000 file format options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.Jpeg2000Options

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Jpeg2000Options()](#Jpeg2000Options__1) | Initialise une nouvelle instance de la classe [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/) |
| [Jpeg2000Options(jpeg_2000_options)](#Jpeg2000Options_jpeg_2000_options_2) | Initialise une nouvelle instance de la classe [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/) |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| codec | [Jpeg2000Codec](/psd/python-net/aspose.psd.fileformats.jpeg2000/jpeg2000codec/) | r/w | Obtient ou définit le codec JPEG2000 |
| comments | chaîne | r/w | Obtient ou définit les marqueurs de commentaire Jpeg. |
| compression_ratios | int | r/w | Obtient ou définit le tableau des ratios de compression.<br/>            Différents ratios de compression pour les couches successives.<br/>            Le taux spécifié pour chaque niveau de qualité est le facteur de compression souhaité.<br/>            Des ratios décroissants sont requis. |
| default_replacement_font | chaîne | r/w | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner du texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système).<br/>            Pour obtenir le nom correct de la police par défaut, le fragment de code suivant peut être utilisé :<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| full_frame | bool | r/w | Obtient ou définit une valeur indiquant si [full frame]. |
| irreversible | bool | r/w | Obtient ou définit une valeur indiquant s'il faut utiliser le DWT irréversible 9-7 (true) ou la compression DWT sans perte 5-3 (par défaut). |
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


### Constructor: Jpeg2000Options() {#Jpeg2000Options__1}


```
 Jpeg2000Options() 
```

Initialise une nouvelle instance de la classe [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/)

### Constructor: Jpeg2000Options(jpeg_2000_options) {#Jpeg2000Options_jpeg_2000_options_2}


```
 Jpeg2000Options(jpeg_2000_options) 
```

Initialise une nouvelle instance de la classe [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/)

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| jpeg_2000_options | [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options) | Les options du format de fichier Jpeg2000 d'où copier les paramètres. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clone cette instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Renvoie une copie superficielle de cette instance |


