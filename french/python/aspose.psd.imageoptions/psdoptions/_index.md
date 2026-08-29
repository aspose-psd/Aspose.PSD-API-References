---
title: "Classe PsdOptions"
type: docs
weight: 100
url: /fr/python-net/aspose.psd.imageoptions/psdoptions/
---

**Summary:** The psd file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PsdOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | Initialise une nouvelle instance de la classe [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
| [PsdOptions(image)](#PsdOptions_image_2) | Initialise une nouvelle instance de la classe [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
| [PsdOptions(options)](#PsdOptions_options_3) | Initialise une nouvelle instance de la classe [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_contents | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Obtient ou définit la couleur d'arrière-plan.<br/>            Elle peut être vue sous les objets transparents. |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| channel_bits_count | short | r/w | Obtient ou définit le nombre de bits par canal de couleur. |
| channels_count | short | r/w | Obtient ou définit le nombre de canaux de couleur. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes/) | r/w | Obtient ou définit le mode couleur PSD. |
| compression_method | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod/) | r/w | Obtient ou définit la méthode de compression PSD. |
| default_replacement_font | chaîne | r/w | Obtient ou définit la police de remplacement par défaut (police qui sera utilisée pour dessiner du texte lors de l'exportation en raster, si la police du calque existant dans le fichier PSD n'est pas présente dans le système).<br/>            Pour obtenir le nom correct de la police par défaut, le fragment de code suivant peut être utilisé :<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| full_frame | bool | r/w | Obtient ou définit une valeur indiquant si [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Les options multipages |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Obtient ou définit la palette de couleurs. |
| psd_version | [PsdVersion](/psd/python-net/aspose.psd.fileformats.psd/psdversion/) | r/w | Obtient ou définit la version du format de fichier. Elle peut être PSD ou PSB. |
| refresh_image_preview_data | bool | r/w | Obtient ou définit une valeur indiquant si [refresh image preview data] - option utilisée pour maximiser la compatibilité avec d'autres visionneuses d'images PSD.<br/>            Veuillez noter que le rendu des calques de texte dans la mise en page finale n'est pas pris en charge sur la plateforme Compact Framework. |
| remove_global_text_engine_resource | bool | r/w | Obtient ou définit une valeur indiquant si - Supprimer la ressource du moteur de texte global - Utilisé pour certains fichiers PSD à calques de texte, uniquement dans le cas où ils ne peuvent pas être ouverts dans Adobe Photoshop après traitement (principalement lié aux calques de texte avec polices manquantes).<br/>            Après avoir utilisé cette option, l'utilisateur doit effectuer dans le fichier ouvert dans Photoshop : Menu \"Text\" -&gt; \"Process absent fonts\". Après cette opération, tout le texte réapparaîtra.<br/>            Veuillez noter que cette opération peut entraîner des modifications de la mise en page finale. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Obtient ou définit les paramètres de résolution. |
| resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock/) | r/w | Obtient ou définit les ressources PSD. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Obtient ou définit la source dans laquelle créer l'image. |
| update_metadata | bool | r/w | Obtient ou définit une valeur indiquant si [update metadata].<br/>            Si la valeur est vraie, les métadonnées seront mises à jour lors de l'enregistrement de l'image. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Obtient ou définit les options de rasterisation vectorielle. |
| version | int | r/w | Obtient ou définit la version du fichier PSD. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Obtenir ou définir le conteneur de données XMP |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clone cette instance. |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

Initialise une nouvelle instance de la classe [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

### Constructor: PsdOptions(image) {#PsdOptions_image_2}


```
 PsdOptions(image) 
```

Initialise une nouvelle instance de la classe [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) | L'image. |

### Constructor: PsdOptions(options) {#PsdOptions_options_3}


```
 PsdOptions(options) 
```

Initialise une nouvelle instance de la classe [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions) | Les options. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clone cette instance.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Renvoie une copie superficielle de cette instance |


