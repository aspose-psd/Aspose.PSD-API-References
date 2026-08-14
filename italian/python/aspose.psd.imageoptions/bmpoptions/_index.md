---
title: "BmpOptions Classe"
type: docs
weight: 10
url: /it/python-net/aspose.psd.imageoptions/bmpoptions/
---

**Summary:** The bmp file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.BmpOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BmpOptions()](#BmpOptions__1) | Inizializza una nuova istanza della classe [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/). |
| [BmpOptions(bmp_options)](#BmpOptions_bmp_options_2) | Inizializza una nuova istanza della classe [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bits_per_pixel | int | r/w | Ottiene o imposta il conteggio dei bit per pixel dell'immagine. |
| buffer_size_hint | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| compression | [BitmapCompression](/psd/python-net/aspose.psd.fileformats.bmp/bitmapcompression/) | r/w | Ottiene o imposta la compressione. |
| default_replacement_font | string | r/w | Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema).<br/>            Per ottenere il nome corretto del font predefinito può essere usato il seguente frammento di codice:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata rilasciata. |
| full_frame | bool | r/w | Ottiene o imposta un valore che indica se [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Le opzioni multipagina |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Ottiene o imposta la tavolozza dei colori. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Ottiene o imposta le impostazioni di risoluzione. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Ottiene o imposta la sorgente in cui creare l'immagine. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Ottiene o imposta il contenitore dei metadati XMP. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clona questa istanza. |


### Constructor: BmpOptions() {#BmpOptions__1}


```
 BmpOptions() 
```

Inizializza una nuova istanza della classe [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/).

### Constructor: BmpOptions(bmp_options) {#BmpOptions_bmp_options_2}


```
 BmpOptions(bmp_options) 
```

Inizializza una nuova istanza della classe [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| bmp_options | [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions) | Le opzioni BMP. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona questa istanza.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Restituisce una copia superficiale di questa istanza |


