---
title: "JpegOptions Klasse"
type: docs
weight: 60
url: /nl/python-net/aspose.psd.imageoptions/jpegoptions/
---

**Summary:** The jpeg file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.JpegOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | Initialiseert een nieuw exemplaar van de [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) klasse. |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | Initialiseert een nieuw exemplaar van de [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| bits_per_channel | byte | r/w | Haalt of stelt bits per kanaal in voor verliesvrije jpeg-afbeelding. Nu ondersteunen we van 2 tot 8 bits per kanaal. |
| buffer_size_hint | int | r/w | Haalt op of stelt de buffergroottehint in, die is gedefinieerd als de maximaal toegestane grootte voor alle interne buffers. |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Het bestemmings‑CMYK‑kleurprofiel voor CMYK‑jpeg‑afbeeldingen. Gebruik voor het opslaan van afbeeldingen. Moet in combinatie met RGBColorProfile worden gebruikt voor correcte kleurconversie. |
| color_type | [JpegCompressionColorMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressioncolormode/) | r/w | Haalt of stelt het kleurtype in voor jpeg‑afbeelding. |
| opmerking | string | r/w | Haalt of stelt de jpeg‑bestandopmerking in. |
| compression_type | [JpegCompressionMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressionmode/) | r/w | Haalt of stelt het compressietype in. |
| default_memory_allocation_limit | int | r/w | Haalt of stelt de standaard geheugenallocatielimiet in. |
| default_replacement_font | string | r/w | Geeft of stelt het standaard vervangingslettertype in (lettertype dat wordt gebruikt om tekst te tekenen bij exporteren naar raster, als het bestaande laaglettertype in het PSD‑bestand niet in het systeem aanwezig is).<br/>            Om de juiste naam van het standaardlettertype te verkrijgen, kan de volgende codefragment worden gebruikt:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Geeft een waarde die aangeeft of dit exemplaar is vrijgegeven. |
| exif_data | [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) | r/w | Haalt of stelt de exif‑datacontainer in |
| full_frame | bool | r/w | Geeft een waarde op of haalt deze op die aangeeft of [full frame]. |
| horizontal_sampling | byte | r/w | Haalt of stelt de horizontale subsampling voor elke component in. |
| jfif | [JFIFData](/psd/python-net/aspose.psd.fileformats.jpeg/jfifdata/) | r/w | Haalt of stelt de jfif in. |
| jpeg_ls_allowed_lossy_error | int | r/w | Haalt of stelt de JPEG-LS‑verschilgrens in voor bijna‑verliesloze codering (NEAR‑parameter uit de JPEG-LS‑specificatie). |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglsinterleavemode/) | r/w | Haalt of stelt de JPEG-LS‑interleavemodus in. |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | Haalt of stelt de JPEG-LS‑preset‑parameters in. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | De multipagina-opties |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Geeft het kleurenpalet op of haalt dit op. |
| preblend_alpha_if_present | bool | r/w | Haalt of stelt een waarde in die aangeeft of rode, groene en blauwe componenten moeten worden gemengd met een achtergrondkleur, als het alfacanaal aanwezig is. |
| kwaliteit | int | r/w | Haalt of stelt de afbeeldingskwaliteit in. |
| rd_opt_settings | [RdOptimizerSettings](/psd/python-net/aspose.psd.imageoptions/rdoptimizersettings) | r/w | Haalt of stelt de RD‑optimizerinstellingen in. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Geeft de resolutie-instellingen op of haalt deze op. |
| resolution_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit) | r/w | Haalt of stelt de resolutie‑eenheid in. |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Het bestemmings‑RGB‑kleurprofiel voor CMYK‑jpeg‑afbeeldingen. Gebruik voor het opslaan van afbeeldingen. Moet in combinatie met CMYKColorProfile worden gebruikt voor correcte kleurconversie. |
| sample_rounding_mode | [SampleRoundingMode](/psd/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/) | r/w | Haalt of stelt de afrondingsmodus voor monsters in om een 8‑bit‑waarde aan te passen aan een n‑bit‑waarde. <see cref=\"P:JpegOptions.BitsPerChannel\" /> |
| scaled_quality | int | r | De geschaalde kwaliteit. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Haalt de bron op of stelt deze in om de afbeelding te maken. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Haalt de vectorrasterisatie‑opties op of stelt deze in. |
| vertical_sampling | byte | r/w | Haalt op of stelt de verticale onderbemonsteringen voor elk component in. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Haalt de XMP-metadatacontainer op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [clone()](#clone__1) | Kloont deze instantie. |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

Initialiseert een nieuw exemplaar van de [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) klasse.

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

Initialiseert een nieuw exemplaar van de [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions) | De JPEG-opties. |

### Method: clone() {#clone__1}


```
 clone() 
```

Kloont deze instantie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Retourneert een ondiepe kopie van deze instantie. |


