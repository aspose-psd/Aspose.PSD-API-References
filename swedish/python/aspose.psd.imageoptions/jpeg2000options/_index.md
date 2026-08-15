---
title: "Jpeg2000Options‑klass"
type: docs
weight: 50
url: /sv/python-net/aspose.psd.imageoptions/jpeg2000options/
---

**Summary:** The Jpeg2000 file format options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.Jpeg2000Options

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [Jpeg2000Options()](#Jpeg2000Options__1) | Initierar en ny instans av klassen [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/). |
| [Jpeg2000Options(jpeg_2000_options)](#Jpeg2000Options_jpeg_2000_options_2) | Initierar en ny instans av klassen [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| codec | [Jpeg2000Codec](/psd/python-net/aspose.psd.fileformats.jpeg2000/jpeg2000codec/) | r/w | Hämtar eller anger JPEG2000‑kodaren |
| kommentarer | string | r/w | Hämtar eller anger JPEG‑kommentarmarkörerna. |
| compression_ratios | int | r/w | Hämtar eller anger arrayen av komprimeringsförhållanden.<br/>            Olika komprimeringsförhållanden för på varandra följande lager.<br/>            Den hastighet som anges för varje kvalitetsnivå är den önskade<br/>            komprimeringsfaktorn.<br/>            Minskande förhållanden krävs. |
| default_replacement_font | string | r/w | Hämtar eller anger standardteckensnittet för ersättning (teckensnitt som kommer att användas för att rita text vid export till raster, om befintligt lagertypsnitt i PSD-filen inte finns i systemet).<br/>            För att få rätt namn på standardteckensnittet kan följande kodsnutt användas:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| borttagen | bool | r | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| full_frame | bool | r/w | Hämtar eller anger ett värde som indikerar om [full frame]. |
| irreversible | bool | r/w | Hämtar eller anger ett värde som indikerar om den irreversibla DWT 9‑7 (true) ska användas eller om förlustfri DWT 5‑3‑kompression (standard) ska användas. |
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


### Constructor: Jpeg2000Options() {#Jpeg2000Options__1}


```
 Jpeg2000Options() 
```

Initierar en ny instans av klassen [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/).

### Constructor: Jpeg2000Options(jpeg_2000_options) {#Jpeg2000Options_jpeg_2000_options_2}


```
 Jpeg2000Options(jpeg_2000_options) 
```

Initierar en ny instans av klassen [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| jpeg_2000_options | [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options) | Jpeg2000‑filformatalternativen att kopiera inställningar från. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klonar denna instans.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Returnerar en ytlig kopia av denna instans |


