---
title: "PsdOptions Klasse"
type: docs
weight: 100
url: /nl/python-net/aspose.psd.imageoptions/psdoptions/
---

**Summary:** The psd file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PsdOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | Initialiseert een nieuw exemplaar van de [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) klasse. |
| [PsdOptions(image)](#PsdOptions_image_2) | Initialiseert een nieuw exemplaar van de [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) klasse. |
| [PsdOptions(options)](#PsdOptions_options_3) | Initialiseert een nieuw exemplaar van de [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| background_contents | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Haalt op of stelt de kleur van de achtergrond in.<br/>            Deze kan worden gezien onder transparante objecten. |
| buffer_size_hint | int | r/w | Haalt op of stelt de buffergroottehint in, die is gedefinieerd als de maximaal toegestane grootte voor alle interne buffers. |
| channel_bits_count | short | r/w | Haalt op of stelt het aantal bits per kleurkanaal in. |
| channels_count | short | r/w | Haalt op of stelt het aantal kleurkanalen in. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes/) | r/w | Haalt op of stelt de psd-kleurmodus in. |
| compression_method | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod/) | r/w | Haalt op of stelt de psd-compressiemethode in. |
| default_replacement_font | string | r/w | Geeft of stelt het standaard vervangingslettertype in (lettertype dat wordt gebruikt om tekst te tekenen bij exporteren naar raster, als het bestaande laaglettertype in het PSD‑bestand niet in het systeem aanwezig is).<br/>            Om de juiste naam van het standaardlettertype te verkrijgen, kan de volgende codefragment worden gebruikt:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Geeft een waarde die aangeeft of dit exemplaar is vrijgegeven. |
| full_frame | bool | r/w | Geeft een waarde op of haalt deze op die aangeeft of [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | De multipagina-opties |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Geeft het kleurenpalet op of haalt dit op. |
| psd_version | [PsdVersion](/psd/python-net/aspose.psd.fileformats.psd/psdversion/) | r/w | Haalt op of stelt de bestandsformaatversie in. Het kan PSD of PSB zijn. |
| refresh_image_preview_data | bool | r/w | Haalt op of stelt een waarde in die aangeeft of [refresh image preview data] - optie gebruikt om de compatibiliteit met andere PSD-beeldkijkers te maximaliseren.<br/>            Let op, het tekenen van tekstlagen naar de uiteindelijke lay-out wordt niet ondersteund voor het Compact Framework-platform. |
| remove_global_text_engine_resource | bool | r/w | Haalt op of stelt een waarde in die aangeeft of - Verwijder de globale tekstengine‑resource - Gebruikt voor sommige tekstlaag‑psd‑bestanden, alleen in het geval dat ze na verwerking niet kunnen worden geopend in Adobe Photoshop (voornamelijk gerelateerd aan ontbrekende lettertype‑tekstlagen).<br/>            Na het gebruiken van deze optie moet de gebruiker het volgende doen in het geopende Photoshop‑bestand: Menu "Text" -&gt; "Process absent fonts". Na die bewerking zal alle tekst weer verschijnen.<br/>            Let op, dat deze bewerking enkele wijzigingen in de uiteindelijke lay-out kan veroorzaken. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Geeft de resolutie-instellingen op of haalt deze op. |
| resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock/) | r/w | Haalt op of stelt de psd-resources in. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Haalt de bron op of stelt deze in om de afbeelding te maken. |
| update_metadata | bool | r/w | Haalt op of stelt een waarde in die aangeeft of [update metadata].<br/>            Als de waarde waar is, wordt de metadata bijgewerkt tijdens het opslaan van een afbeelding. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Haalt de vectorrasterisatie‑opties op of stelt deze in. |
| version | int | r/w | Haalt op of stelt de psd-bestandsversie in. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Haalt of stelt de XMP-gegevenscontainer in |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [clone()](#clone__1) | Kloont deze instantie. |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

Initialiseert een nieuw exemplaar van de [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) klasse.

### Constructor: PsdOptions(image) {#PsdOptions_image_2}


```
 PsdOptions(image) 
```

Initialiseert een nieuw exemplaar van de [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) | De afbeelding. |

### Constructor: PsdOptions(options) {#PsdOptions_options_3}


```
 PsdOptions(options) 
```

Initialiseert een nieuw exemplaar van de [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions) | De opties. |

### Method: clone() {#clone__1}


```
 clone() 
```

Kloont deze instantie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Retourneert een ondiepe kopie van deze instantie. |


