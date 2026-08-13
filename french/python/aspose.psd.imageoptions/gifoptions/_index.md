---
title: "Classe GifOptions"
type: docs
weight: 30
url: /fr/python-net/aspose.psd.imageoptions/gifoptions/
---

**Summary:** The gif file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.GifOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | Initialise une nouvelle instance de la classe [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/). |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | Initialise une nouvelle instance de la classe [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color_index | byte | r/w | Obtient ou définit l'index de couleur d'arrière-plan du GIF. |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| color_resolution | byte | r/w | Obtient ou définit la résolution de couleur du GIF. |
| default_replacement_font | chaîne | r/w | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner du texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système).<br/>            Pour obtenir le nom correct de la police par défaut, le fragment de code suivant peut être utilisé :<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| do_palette_correction | bool | r/w | Obtient ou définit une valeur indiquant si la correction de palette est appliquée. |
| full_frame | bool | r/w | Obtient ou définit une valeur indiquant si [full frame]. |
| has_trailer | bool | r/w | Obtient ou définit une valeur indiquant si le GIF possède un trailer. |
| interlaced | bool | r/w | Vrai si l'image doit être entrelacée. |
| is_palette_sorted | bool | r/w | Obtient ou définit une valeur indiquant si les entrées de la palette sont triées. |
| max_diff | int | r/w | Obtient ou définit la différence maximale de pixel autorisée. Si elle est supérieure à zéro, une compression avec perte sera utilisée.<br/>            La valeur recommandée pour une compression avec perte optimale est de 80. 30 correspond à une compression très légère, 200 à une compression lourde.<br/>            Elle fonctionne mieux lorsque seule une petite perte est introduite, et en raison des limites de l'algorithme de compression, des niveaux de perte très élevés n'apporteront pas autant de gain.<br/>            L'intervalle des valeurs autorisées est [0, 1000]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Les options multipages |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Obtient ou définit la palette de couleurs. |
| pixel_aspect_ratio | byte | r/w | Obtient ou définit le rapport d'aspect des pixels du GIF. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Obtient ou définit les paramètres de résolution. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Obtient ou définit la source dans laquelle créer l'image. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Obtient ou définit les options de rasterisation vectorielle. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Obtient ou définit le conteneur de métadonnées XMP. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clone cette instance. |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

Initialise une nouvelle instance de la classe [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/).

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

Initialise une nouvelle instance de la classe [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| gif_options | [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions) | Les options GIF. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clone cette instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Renvoie une copie superficielle de cette instance |


