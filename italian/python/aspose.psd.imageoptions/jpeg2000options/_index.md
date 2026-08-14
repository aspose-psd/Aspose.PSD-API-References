---
title: "Classe Jpeg2000Options"
type: docs
weight: 50
url: /it/python-net/aspose.psd.imageoptions/jpeg2000options/
---

**Summary:** The Jpeg2000 file format options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.Jpeg2000Options

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Jpeg2000Options()](#Jpeg2000Options__1) | Inizializza una nuova istanza della classe [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/). |
| [Jpeg2000Options(jpeg_2000_options)](#Jpeg2000Options_jpeg_2000_options_2) | Inizializza una nuova istanza della classe [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| codec | [Jpeg2000Codec](/psd/python-net/aspose.psd.fileformats.jpeg2000/jpeg2000codec/) | r/w | Ottiene o imposta il codec JPEG2000 |
| comments | string | r/w | Ottiene o imposta i marcatori di commento Jpeg. |
| compression_ratios | int | r/w | Ottiene o imposta l'Array di rapporto di compressione.<br/>            Diversi rapporti di compressione per i livelli successivi.<br/>            Il tasso specificato per ogni livello di qualità è il fattore di compressione desiderato.<br/>            Sono richiesti rapporti decrescenti. |
| default_replacement_font | string | r/w | Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema).<br/>            Per ottenere il nome corretto del font predefinito può essere usato il seguente frammento di codice:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata rilasciata. |
| full_frame | bool | r/w | Ottiene o imposta un valore che indica se [full frame]. |
| irreversible | bool | r/w | Ottiene o imposta un valore che indica se utilizzare il DWT irreversibile 9-7 (true) o utilizzare la compressione DWT lossless 5-3 (predefinito). |
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


### Constructor: Jpeg2000Options() {#Jpeg2000Options__1}


```
 Jpeg2000Options() 
```

Inizializza una nuova istanza della classe [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/).

### Constructor: Jpeg2000Options(jpeg_2000_options) {#Jpeg2000Options_jpeg_2000_options_2}


```
 Jpeg2000Options(jpeg_2000_options) 
```

Inizializza una nuova istanza della classe [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| jpeg_2000_options | [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options) | Le opzioni del formato file Jpeg2000 da cui copiare le impostazioni. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona questa istanza.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Restituisce una copia superficiale di questa istanza |


