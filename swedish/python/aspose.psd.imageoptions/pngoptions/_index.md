---
title: "PngOptions klass"
type: docs
weight: 90
url: /sv/python-net/aspose.psd.imageoptions/pngoptions/
---

**Summary:** The png file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PngOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [PngOptions()](#PngOptions__1) | Initierar en ny instans av [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) klass. |
| [PngOptions(png_options)](#PngOptions_png_options_2) | Initierar en ny instans av [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) klass. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| DEFAULT_COMPRESSION_LEVEL [static] | int | r | Den standardkomprimeringsnivån. |
| bit_depth | byte | r/w | Bitdjupet. |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| color_type | [PngColorType](/psd/python-net/aspose.psd.fileformats.png/pngcolortype/) | r/w | Hämtar eller anger färgens typ. |
| compression_level | int | r/w | PNG-bildens komprimeringsnivå i intervallet 0-9, där 9 är maximal komprimering och 0 är lagringsläge. |
| default_replacement_font | string | r/w | Hämtar eller anger standardteckensnittet för ersättning (teckensnitt som kommer att användas för att rita text vid export till raster, om befintligt lagertypsnitt i PSD-filen inte finns i systemet).<br/>            För att få rätt namn på standardteckensnittet kan följande kodsnutt användas:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| borttagen | bool | r | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| filter_type | [PngFilterType](/psd/python-net/aspose.psd.fileformats.png/pngfiltertype/) | r/w | Hämtar eller anger filtertypen som används under PNG-filsparningsprocessen. |
| full_frame | bool | r/w | Hämtar eller anger ett värde som indikerar om [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Flersidiga alternativ |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Hämtar eller anger färgpaletten. |
| progressive | bool | r/w | Hämtar eller anger ett värde som indikerar om denna [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) är progressiv. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Hämtar eller anger upplösningsinställningarna. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Hämtar eller anger källan för att skapa bilden i. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Hämtar eller anger vektorrasteriseringsalternativen. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger XMP‑metadata‑behållaren. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [clone()](#clone__1) | Klonar denna instans. |


### Constructor: PngOptions() {#PngOptions__1}


```
 PngOptions() 
```

Initierar en ny instans av [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) klass.

### Constructor: PngOptions(png_options) {#PngOptions_png_options_2}


```
 PngOptions(png_options) 
```

Initierar en ny instans av [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions/) klass.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| png_options | [PngOptions](/psd/python-net/aspose.psd.imageoptions/pngoptions) | PNG-alternativen. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klonar denna instans.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Returnerar en ytlig kopia av denna instans |


