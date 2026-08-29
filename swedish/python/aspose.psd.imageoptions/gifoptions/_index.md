---
title: "GifOptions-klass"
type: docs
weight: 30
url: /sv/python-net/aspose.psd.imageoptions/gifoptions/
---

**Summary:** The gif file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.GifOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | Initierar en ny instans av klassen [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/). |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | Initierar en ny instans av klassen [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| background_color_index | byte | r/w | Hämtar eller anger GIF:ens bakgrundsfärgsindex. |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| color_resolution | byte | r/w | Hämtar eller anger GIF-färguppslösning. |
| default_replacement_font | string | r/w | Hämtar eller anger standardteckensnittet för ersättning (teckensnitt som kommer att användas för att rita text vid export till raster, om befintligt lagertypsnitt i PSD-filen inte finns i systemet).<br/>            För att få rätt namn på standardteckensnittet kan följande kodsnutt användas:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| borttagen | bool | r | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| do_palette_correction | bool | r/w | Hämtar eller anger ett värde som indikerar om palettkorrigering tillämpas. |
| full_frame | bool | r/w | Hämtar eller anger ett värde som indikerar om [full frame]. |
| has_trailer | bool | r/w | Hämtar eller anger ett värde som indikerar om GIF har trailer. |
| interlaced | bool | r/w | Sant om bilden ska vara interlaced. |
| is_palette_sorted | bool | r/w | Hämtar eller anger ett värde som indikerar om palettposter är sorterade. |
| max_diff | int | r/w | Hämtar eller anger den maximalt tillåtna pixelskillnaden. Om den är större än noll används förlustkomprimering.<br/>            Rekommenderat värde för optimal förlustkomprimering är 80. 30 är mycket lätt komprimering, 200 är tung.<br/>            Det fungerar bäst när endast liten förlust införs, och på grund av begränsningar i komprimeringsalgoritmen ger mycket höga förlustnivåer inte lika stor nytta.<br/>            Intervallet för tillåtna värden är [0, 1000]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Flersidiga alternativ |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Hämtar eller anger färgpaletten. |
| pixel_aspect_ratio | byte | r/w | Hämtar eller anger bildförhållandet för GIF-pixeln. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Hämtar eller anger upplösningsinställningarna. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Hämtar eller anger källan för att skapa bilden i. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Hämtar eller anger vektorrasteriseringsalternativen. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger XMP‑metadata‑behållaren. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [clone()](#clone__1) | Klonar denna instans. |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

Initierar en ny instans av klassen [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/).

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

Initierar en ny instans av klassen [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| gif_options | [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions) | GIF-alternativen. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klonar denna instans.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Returnerar en ytlig kopia av denna instans |


