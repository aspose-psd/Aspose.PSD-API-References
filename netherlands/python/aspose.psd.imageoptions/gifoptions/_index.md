---
title: "GifOptions Klasse"
type: docs
weight: 30
url: /nl/python-net/aspose.psd.imageoptions/gifoptions/
---

**Summary:** The gif file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.GifOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | Initialiseert een nieuw exemplaar van de [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) klasse. |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | Initialiseert een nieuw exemplaar van de [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| background_color_index | byte | r/w | Haalt of stelt de GIF-achtergrondkleurindex in. |
| buffer_size_hint | int | r/w | Haalt op of stelt de buffergroottehint in, die is gedefinieerd als de maximaal toegestane grootte voor alle interne buffers. |
| color_resolution | byte | r/w | Haalt of stelt de GIF-kleuroplossing in. |
| default_replacement_font | string | r/w | Geeft of stelt het standaard vervangingslettertype in (lettertype dat wordt gebruikt om tekst te tekenen bij exporteren naar raster, als het bestaande laaglettertype in het PSD‑bestand niet in het systeem aanwezig is).<br/>            Om de juiste naam van het standaardlettertype te verkrijgen, kan de volgende codefragment worden gebruikt:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Geeft een waarde die aangeeft of dit exemplaar is vrijgegeven. |
| do_palette_correction | bool | r/w | Haalt of stelt een waarde in die aangeeft of paletcorrectie wordt toegepast. |
| full_frame | bool | r/w | Geeft een waarde op of haalt deze op die aangeeft of [full frame]. |
| has_trailer | bool | r/w | Haalt of stelt een waarde in die aangeeft of GIF een trailer heeft. |
| interlaced | bool | r/w | Waar als de afbeelding moet worden geïnterleaved. |
| is_palette_sorted | bool | r/w | Haalt of stelt een waarde in die aangeeft of paletinvoer gesorteerd zijn. |
| max_diff | int | r/w | Haalt of stelt het maximaal toegestane pixelverschil in. Als dit groter is dan nul, wordt verliesgevende compressie gebruikt.<br/>            Aanbevolen waarde voor optimale verliesgevende compressie is 80. 30 is zeer lichte compressie, 200 is zwaar.<br/>            Het werkt het beste wanneer slechts weinig verlies wordt geïntroduceerd, en vanwege de beperking van het compressie‑algoritme zullen zeer hoge verliesniveaus niet zoveel winst opleveren.<br/>            Het bereik van toegestane waarden is [0, 1000]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | De multipagina-opties |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Geeft het kleurenpalet op of haalt dit op. |
| pixel_aspect_ratio | byte | r/w | Haalt of stelt de GIF-pixelaspectverhouding in. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Geeft de resolutie-instellingen op of haalt deze op. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Haalt de bron op of stelt deze in om de afbeelding te maken. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Haalt de vectorrasterisatie‑opties op of stelt deze in. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Haalt de XMP-metadatacontainer op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [clone()](#clone__1) | Kloont deze instantie. |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

Initialiseert een nieuw exemplaar van de [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) klasse.

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

Initialiseert een nieuw exemplaar van de [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| gif_options | [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions) | De GIF-opties. |

### Method: clone() {#clone__1}


```
 clone() 
```

Kloont deze instantie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Retourneert een ondiepe kopie van deze instantie. |


