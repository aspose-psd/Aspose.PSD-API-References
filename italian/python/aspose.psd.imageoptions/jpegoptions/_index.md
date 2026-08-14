---
title: "Classe JpegOptions"
type: docs
weight: 60
url: /it/python-net/aspose.psd.imageoptions/jpegoptions/
---

**Summary:** The jpeg file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.JpegOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | Inizializza una nuova istanza della classe [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/). |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | Inizializza una nuova istanza della classe [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bits_per_channel | byte | r/w | Ottiene o imposta i bit per canale per immagine jpeg senza perdita. Ora supportiamo da 2 a 8 bit per canale. |
| buffer_size_hint | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Il profilo colore CMYK di destinazione per le immagini jpeg CMYK. Da utilizzare per salvare le immagini. Deve essere in coppia con RGBColorProfile per una corretta conversione del colore. |
| color_type | [JpegCompressionColorMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressioncolormode/) | r/w | Ottiene o imposta il tipo di colore per l'immagine jpeg. |
| commento | string | r/w | Ottiene o imposta il commento del file jpeg. |
| compression_type | [JpegCompressionMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressionmode/) | r/w | Ottiene o imposta il tipo di compressione. |
| default_memory_allocation_limit | int | r/w | Ottiene o imposta il limite di allocazione della memoria predefinito. |
| default_replacement_font | string | r/w | Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema).<br/>            Per ottenere il nome corretto del font predefinito può essere usato il seguente frammento di codice:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata rilasciata. |
| exif_data | [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) | r/w | Ottieni o imposta il contenitore dei dati exif |
| full_frame | bool | r/w | Ottiene o imposta un valore che indica se [full frame]. |
| horizontal_sampling | byte | r/w | Ottiene o imposta i campionamenti orizzontali per ciascun componente. |
| jfif | [JFIFData](/psd/python-net/aspose.psd.fileformats.jpeg/jfifdata/) | r/w | Ottiene o imposta il jfif. |
| jpeg_ls_allowed_lossy_error | int | r/w | Ottiene o imposta il limite di differenza JPEG-LS per la codifica quasi senza perdita (parametro NEAR dalla specifica JPEG-LS). |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglsinterleavemode/) | r/w | Ottiene o imposta la modalità di interleaving JPEG-LS. |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | Ottiene o imposta i parametri predefiniti JPEG-LS. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Le opzioni multipagina |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Ottiene o imposta la tavolozza dei colori. |
| preblend_alpha_if_present | bool | r/w | Ottiene o imposta un valore che indica se i componenti rosso, verde e blu devono essere mescolati con un colore di sfondo, se è presente il canale alfa. |
| quality | int | r/w | Ottiene o imposta la qualità dell'immagine. |
| rd_opt_settings | [RdOptimizerSettings](/psd/python-net/aspose.psd.imageoptions/rdoptimizersettings) | r/w | Ottiene o imposta le impostazioni dell'ottimizzatore RD. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Ottiene o imposta le impostazioni di risoluzione. |
| resolution_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit) | r/w | Ottiene o imposta l'unità di risoluzione. |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Il profilo colore RGB di destinazione per le immagini jpeg CMYK. Da utilizzare per salvare le immagini. Deve essere in coppia con CMYKColorProfile per una corretta conversione del colore. |
| sample_rounding_mode | [SampleRoundingMode](/psd/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/) | r/w | Ottiene o imposta la modalità di arrotondamento del campione per adattare un valore a 8 bit a un valore a n bit. <see cref="P:JpegOptions.BitsPerChannel" /> |
| scaled_quality | int | r | La qualità scalata. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Ottiene o imposta la sorgente in cui creare l'immagine. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| vertical_sampling | byte | r/w | Ottiene o imposta i campionamenti verticali per ciascun componente. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Ottiene o imposta il contenitore dei metadati XMP. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clona questa istanza. |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

Inizializza una nuova istanza della classe [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/).

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

Inizializza una nuova istanza della classe [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions) | Le opzioni JPEG. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona questa istanza.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Restituisce una copia superficiale di questa istanza |


