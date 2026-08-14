---
title: "Classe PsdOptions"
type: docs
weight: 100
url: /it/python-net/aspose.psd.imageoptions/psdoptions/
---

**Summary:** The psd file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PsdOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | Inizializza una nuova istanza della classe [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
| [PsdOptions(image)](#PsdOptions_image_2) | Inizializza una nuova istanza della classe [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
| [PsdOptions(options)](#PsdOptions_options_3) | Inizializza una nuova istanza della classe [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_contents | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Ottiene o imposta il colore di sfondo.<br/>            Può essere visto sotto gli oggetti trasparenti. |
| buffer_size_hint | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| channel_bits_count | short | r/w | Ottiene o imposta il conteggio dei bit per canale colore. |
| channels_count | short | r/w | Ottiene o imposta il numero di canali colore. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes/) | r/w | Ottiene o imposta la modalità colore PSD. |
| compression_method | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod/) | r/w | Ottiene o imposta il metodo di compressione PSD. |
| default_replacement_font | string | r/w | Ottiene o imposta il font di sostituzione predefinito (font che verrà usato per disegnare il testo durante l'esportazione in raster, se il font del livello esistente nel file PSD non è presente nel sistema).<br/>            Per ottenere il nome corretto del font predefinito può essere usato il seguente frammento di codice:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata rilasciata. |
| full_frame | bool | r/w | Ottiene o imposta un valore che indica se [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Le opzioni multipagina |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Ottiene o imposta la tavolozza dei colori. |
| psd_version | [PsdVersion](/psd/python-net/aspose.psd.fileformats.psd/psdversion/) | r/w | Ottiene o imposta la versione del formato file. Può essere PSD o PSB. |
| refresh_image_preview_data | bool | r/w | Ottiene o imposta un valore che indica se [refresh image preview data] - opzione utilizzata per massimizzare la compatibilità con altri visualizzatori di immagini PSD.<br/>            Si prega di notare che il disegno dei livelli di testo nel layout finale non è supportato per la piattaforma Compact Framework. |
| remove_global_text_engine_resource | bool | r/w | Ottiene o imposta un valore che indica se - Rimuovere la risorsa globale del motore di testo - Utilizzato per alcuni file PSD con livelli di testo, nel solo caso in cui non possano essere aperti in Adobe Photoshop dopo l'elaborazione (principalmente per livelli di testo con font mancanti).<br/>            Dopo aver usato questa opzione, l'utente deve eseguire quanto segue nel file aperto in Photoshop: Menu "Text" -> "Process absent fonts". Dopo tale operazione tutto il testo riapparirà.<br/>            Si prega di notare che questa operazione può causare alcune modifiche al layout finale. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Ottiene o imposta le impostazioni di risoluzione. |
| resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock/) | r/w | Ottiene o imposta le risorse PSD. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Ottiene o imposta la sorgente in cui creare l'immagine. |
| update_metadata | bool | r/w | Ottiene o imposta un valore che indica se [update metadata].<br/>            Se il valore è true, i metadati saranno aggiornati durante il salvataggio dell'immagine. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Ottiene o imposta le opzioni di rasterizzazione vettoriale. |
| version | int | r/w | Ottiene o imposta la versione del file PSD. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Ottieni o imposta il contenitore dati XMP |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clona questa istanza. |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

Inizializza una nuova istanza della classe [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

### Constructor: PsdOptions(image) {#PsdOptions_image_2}


```
 PsdOptions(image) 
```

Inizializza una nuova istanza della classe [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image | [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) | L'immagine. |

### Constructor: PsdOptions(options) {#PsdOptions_options_3}


```
 PsdOptions(options) 
```

Inizializza una nuova istanza della classe [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions) | Le opzioni. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona questa istanza.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Restituisce una copia superficiale di questa istanza |


