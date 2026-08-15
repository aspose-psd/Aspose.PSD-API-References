---
title: "BmpOptions‑klass"
type: docs
weight: 10
url: /sv/python-net/aspose.psd.imageoptions/bmpoptions/
---

**Summary:** The bmp file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.BmpOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [BmpOptions()](#BmpOptions__1) | Initierar en ny instans av [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/)‑klassen. |
| [BmpOptions(bmp_options)](#BmpOptions_bmp_options_2) | Initierar en ny instans av [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/)‑klassen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| bits_per_pixel | int | r/w | Hämtar eller anger antalet bildbitar per pixel. |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| compression | [BitmapCompression](/psd/python-net/aspose.psd.fileformats.bmp/bitmapcompression/) | r/w | Hämtar eller anger komprimeringen. |
| default_replacement_font | string | r/w | Hämtar eller anger standardteckensnittet för ersättning (teckensnitt som kommer att användas för att rita text vid export till raster, om befintligt lagertypsnitt i PSD-filen inte finns i systemet).<br/>            För att få rätt namn på standardteckensnittet kan följande kodsnutt användas:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| borttagen | bool | r | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| full_frame | bool | r/w | Hämtar eller anger ett värde som indikerar om [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Flersidiga alternativ |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Hämtar eller anger färgpaletten. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Hämtar eller anger upplösningsinställningarna. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Hämtar eller anger källan för att skapa bilden i. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Hämtar eller anger vektorrasteriseringsalternativen. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger XMP‑metadata‑behållaren. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [clone()](#clone__1) | Klonar denna instans. |


### Constructor: BmpOptions() {#BmpOptions__1}


```
 BmpOptions() 
```

Initierar en ny instans av [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/)‑klassen.

### Constructor: BmpOptions(bmp_options) {#BmpOptions_bmp_options_2}


```
 BmpOptions(bmp_options) 
```

Initierar en ny instans av [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/)‑klassen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bmp_options | [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions) | BMP‑alternativen. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klonar denna instans.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Returnerar en ytlig kopia av denna instans |


