---
title: "BmpOptions-klasse"
type: docs
weight: 10
url: /nl/python-net/aspose.psd.imageoptions/bmpoptions/
---

**Summary:** The bmp file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.BmpOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [BmpOptions()](#BmpOptions__1) | Initialiseert een nieuwe instantie van de [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/)-klasse. |
| [BmpOptions(bmp_options)](#BmpOptions_bmp_options_2) | Initialiseert een nieuwe instantie van de [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/)-klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| bits_per_pixel | int | r/w | Haalt het aantal bits per pixel van de afbeelding op of stelt dit in. |
| buffer_size_hint | int | r/w | Haalt op of stelt de buffergroottehint in, die is gedefinieerd als de maximaal toegestane grootte voor alle interne buffers. |
| compression | [BitmapCompression](/psd/python-net/aspose.psd.fileformats.bmp/bitmapcompression/) | r/w | Haalt de compressie op of stelt deze in. |
| default_replacement_font | string | r/w | Geeft of stelt het standaard vervangingslettertype in (lettertype dat wordt gebruikt om tekst te tekenen bij exporteren naar raster, als het bestaande laaglettertype in het PSD‑bestand niet in het systeem aanwezig is).<br/>            Om de juiste naam van het standaardlettertype te verkrijgen, kan de volgende codefragment worden gebruikt:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Geeft een waarde die aangeeft of dit exemplaar is vrijgegeven. |
| full_frame | bool | r/w | Geeft een waarde op of haalt deze op die aangeeft of [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | De multipagina-opties |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Geeft het kleurenpalet op of haalt dit op. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Geeft de resolutie-instellingen op of haalt deze op. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Haalt de bron op of stelt deze in om de afbeelding te maken. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Haalt de vectorrasterisatie‑opties op of stelt deze in. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Haalt de XMP-metadatacontainer op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [clone()](#clone__1) | Kloont deze instantie. |


### Constructor: BmpOptions() {#BmpOptions__1}


```
 BmpOptions() 
```

Initialiseert een nieuwe instantie van de [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/)-klasse.

### Constructor: BmpOptions(bmp_options) {#BmpOptions_bmp_options_2}


```
 BmpOptions(bmp_options) 
```

Initialiseert een nieuwe instantie van de [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/)-klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| bmp_options | [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions) | De BMP-opties. |

### Method: clone() {#clone__1}


```
 clone() 
```

Kloont deze instantie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Retourneert een ondiepe kopie van deze instantie. |


