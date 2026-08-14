---
title: "Classe PngOptions"
type: docs
weight: 90
url: /it/python-net/aspose.psd.imageoptions/pngoptions/
---

**Summary:** The png file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PngOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PngOptions()](#PngOptions__1) | Inizializza una nuova istanza della classe [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/). |
| [PngOptions(png_options)](#PngOptions_png_options_2) | Inizializza una nuova istanza della classe [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | int | r | Il livello di compressione predefinito. |
| bit_depth | byte | r/w | La profondità di bit. |
| buffer_size_hint | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| color_type | [PngColorType](/psd/python-net/aspose.psd.fileformats.png/pngcolortype/) | r/w | Ottiene o imposta il tipo di colore. |
| compression_level | int | r/w | Il livello di compressione dell'immagine png nell'intervallo 0-9, dove 9 è la compressione massima e 0 è modalità di archiviazione. |
| default_replacement_font | string | r/w | Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema).<br/>            Per ottenere il nome corretto del font predefinito può essere usato il seguente frammento di codice:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata rilasciata. |
| filter_type | [PngFilterType](/psd/python-net/aspose.psd.fileformats.png/pngfiltertype/) | r/w | Ottiene o imposta il tipo di filtro utilizzato durante il processo di salvataggio del file png. |
| full_frame | bool | r/w | Ottiene o imposta un valore che indica se [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Le opzioni multipagina |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Ottiene o imposta la tavolozza dei colori. |
| progressive | bool | r/w | Ottiene o imposta un valore che indica se questo [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) è progressivo. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Ottiene o imposta le impostazioni di risoluzione. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Ottiene o imposta la sorgente in cui creare l'immagine. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Ottiene o imposta il contenitore dei metadati XMP. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clona questa istanza. |


### Constructor: PngOptions() {#PngOptions__1}


```
 PngOptions() 
```

Inizializza una nuova istanza della classe [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/).

### Constructor: PngOptions(png_options) {#PngOptions_png_options_2}


```
 PngOptions(png_options) 
```

Inizializza una nuova istanza della classe [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| png_options | [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions) | Le opzioni PNG. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona questa istanza.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Restituisce una copia superficiale di questa istanza |


