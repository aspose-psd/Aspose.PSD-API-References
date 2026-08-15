---
title: "JpegOptions klass"
type: docs
weight: 60
url: /sv/python-net/aspose.psd.imageoptions/jpegoptions/
---

**Summary:** The jpeg file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.JpegOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | Initierar en ny instans av klassen [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/). |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | Initierar en ny instans av klassen [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| bits_per_channel | byte | r/w | Hämtar eller anger bitar per kanal för förlustfri jpeg-bild. Nu stöds 2 till 8 bitar per kanal. |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Destinations-CMYK-färgprofilen för CMYK jpeg-bilder. Används för att spara bilder. Måste vara i par med RGBColorProfile för korrekt färgkonvertering. |
| color_type | [JpegCompressionColorMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressioncolormode/) | r/w | Hämtar eller anger färgtypen för jpeg-bild. |
| comment | string | r/w | Hämtar eller anger jpeg-filens kommentar. |
| compression_type | [JpegCompressionMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressionmode/) | r/w | Hämtar eller anger komprimeringstypen. |
| default_memory_allocation_limit | int | r/w | Hämtar eller anger standardgränsen för minnesallokering. |
| default_replacement_font | string | r/w | Hämtar eller anger standardteckensnittet för ersättning (teckensnitt som kommer att användas för att rita text vid export till raster, om befintligt lagertypsnitt i PSD-filen inte finns i systemet).<br/>            För att få rätt namn på standardteckensnittet kan följande kodsnutt användas:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| borttagen | bool | r | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| exif_data | [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) | r/w | Hämta eller ange exif-datakontainer. |
| full_frame | bool | r/w | Hämtar eller anger ett värde som indikerar om [full frame]. |
| horizontal_sampling | byte | r/w | Hämtar eller anger de horisontella undersamplingsvärdena för varje komponent. |
| jfif | [JFIFData](/psd/python-net/aspose.psd.fileformats.jpeg/jfifdata/) | r/w | Hämtar eller anger jfif. |
| jpeg_ls_allowed_lossy_error | int | r/w | Hämtar eller anger JPEG-LS-differensgränsen för nästan förlustfri kodning (NEAR-parameter från JPEG-LS-specifikationen). |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglsinterleavemode/) | r/w | Hämtar eller anger JPEG-LS-interleavläge. |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | Hämtar eller anger JPEG-LS-förinställda parametrar. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Flersidiga alternativ |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Hämtar eller anger färgpaletten. |
| preblend_alpha_if_present | bool | r/w | Hämtar eller anger ett värde som indikerar om röd, grön och blå komponenter ska blandas med en bakgrundsfärg, om alfakanal finns. |
| quality | int | r/w | Hämtar eller anger bildkvalitet. |
| rd_opt_settings | [RdOptimizerSettings](/psd/python-net/aspose.psd.imageoptions/rdoptimizersettings) | r/w | Hämtar eller anger RD-optimerarens inställningar. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Hämtar eller anger upplösningsinställningarna. |
| resolution_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit) | r/w | Hämtar eller anger upplösningsenheten. |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Destinations‑RGB‑färgprofilen för CMYK‑jpeg‑bilder. Använd för att spara bilder. Måste vara i par med CMYKColorProfile för korrekt färgkonvertering. |
| sample_rounding_mode | [SampleRoundingMode](/psd/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/) | r/w | Hämtar eller anger provrundningsläget för att anpassa ett 8‑bitars värde till ett n‑bitars värde. <see cref=\"P:JpegOptions.BitsPerChannel\" /> |
| scaled_quality | int | r | Den skalade kvaliteten. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Hämtar eller anger källan för att skapa bilden i. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Hämtar eller anger vektorrasteriseringsalternativen. |
| vertical_sampling | byte | r/w | Hämtar eller anger de vertikala undersamplingsvärdena för varje komponent. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger XMP‑metadata‑behållaren. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [clone()](#clone__1) | Klonar denna instans. |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

Initierar en ny instans av klassen [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/).

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

Initierar en ny instans av klassen [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions) | JPEG‑alternativen. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klonar denna instans.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Returnerar en ytlig kopia av denna instans |


