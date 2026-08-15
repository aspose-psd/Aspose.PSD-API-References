---
title: "Klasse PngOptions"
type: docs
weight: 90
url: /nl/python-net/aspose.psd.imageoptions/pngoptions/
---

**Summary:** The png file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PngOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [PngOptions()](#PngOptions__1) | Initialiseert een nieuwe instantie van de [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) klasse. |
| [PngOptions(png_options)](#PngOptions_png_options_2) | Initialiseert een nieuwe instantie van de [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | int | r | Het standaard compressieniveau. |
| bit_depth | byte | r/w | De bitsdiepte. |
| buffer_size_hint | int | r/w | Haalt op of stelt de buffergroottehint in, die is gedefinieerd als de maximaal toegestane grootte voor alle interne buffers. |
| color_type | [PngColorType](/psd/python-net/aspose.psd.fileformats.png/pngcolortype/) | r/w | Haalt of stelt het type van de kleur in. |
| compression_level | int | r/w | Het png-beeldcompressieniveau in het bereik 0-9, waarbij 9 maximale compressie is en 0 opslagmodus. |
| default_replacement_font | string | r/w | Geeft of stelt het standaard vervangingslettertype in (lettertype dat wordt gebruikt om tekst te tekenen bij exporteren naar raster, als het bestaande laaglettertype in het PSD‑bestand niet in het systeem aanwezig is).<br/>            Om de juiste naam van het standaardlettertype te verkrijgen, kan de volgende codefragment worden gebruikt:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Geeft een waarde die aangeeft of dit exemplaar is vrijgegeven. |
| filter_type | [PngFilterType](/psd/python-net/aspose.psd.fileformats.png/pngfiltertype/) | r/w | Haalt op of stelt het filtertype in dat wordt gebruikt tijdens het opslaan van png-bestanden. |
| full_frame | bool | r/w | Geeft een waarde op of haalt deze op die aangeeft of [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | De multipagina-opties |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Geeft het kleurenpalet op of haalt dit op. |
| progressive | bool | r/w | Haalt een waarde op of stelt een waarde in die aangeeft of deze [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) progressief is. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Geeft de resolutie-instellingen op of haalt deze op. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Haalt de bron op of stelt deze in om de afbeelding te maken. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Haalt de vectorrasterisatie‑opties op of stelt deze in. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Haalt de XMP-metadatacontainer op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [clone()](#clone__1) | Kloont deze instantie. |


### Constructor: PngOptions() {#PngOptions__1}


```
 PngOptions() 
```

Initialiseert een nieuwe instantie van de [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) klasse.

### Constructor: PngOptions(png_options) {#PngOptions_png_options_2}


```
 PngOptions(png_options) 
```

Initialiseert een nieuwe instantie van de [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| png_options | [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions) | De PNG-opties. |

### Method: clone() {#clone__1}


```
 clone() 
```

Kloont deze instantie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Retourneert een ondiepe kopie van deze instantie. |


