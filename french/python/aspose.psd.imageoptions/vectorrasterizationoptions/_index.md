---
title: "Classe VectorRasterizationOptions"
type: docs
weight: 150
url: /fr/python-net/aspose.psd.imageoptions/vectorrasterizationoptions/
---

**Summary:** The vector rasterization options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.VectorRasterizationOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtient ou définit une couleur d'arrière-plan. |
| border_x | float | r/w | Obtient ou définit la bordure X. |
| border_y | float | r/w | Obtient ou définit la bordure Y. |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| center_drawing | bool | r/w | Obtient ou définit une valeur indiquant si le dessin est centré. |
| default_replacement_font | chaîne | r/w | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner du texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système).<br/>            Pour obtenir le nom correct de la police par défaut, le fragment de code suivant peut être utilisé :<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| draw_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtient ou définit une couleur de premier plan. |
| full_frame | bool | r/w | Obtient ou définit une valeur indiquant si [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Les options multipages |
| page_height | float | r/w | Obtient ou définit la hauteur de la page. |
| page_size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | Obtient ou définit la taille de la page. |
| page_width | float | r/w | Obtient ou définit la largeur de la page. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Obtient ou définit la palette de couleurs. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Obtient ou définit les paramètres de résolution. |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | Obtient ou définit le mode d'anticrénelage. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Obtient ou définit la source dans laquelle créer l'image. |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | Obtient ou définit l'indice de rendu du texte. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Obtient ou définit les options de rasterisation vectorielle. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Obtient ou définit le conteneur de métadonnées XMP. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clone cette instance. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Copie vers. |


### Method: clone() {#clone__1}


```
 clone() 
```

Clone cette instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Renvoie une copie superficielle de cette instance |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Copie vers.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | Les options de rasterisation vectorielle. |

