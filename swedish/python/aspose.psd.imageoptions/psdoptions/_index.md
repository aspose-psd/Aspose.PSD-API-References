---
title: "PsdOptions‑klass"
type: docs
weight: 100
url: /sv/python-net/aspose.psd.imageoptions/psdoptions/
---

**Summary:** The psd file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PsdOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | Initierar en ny instans av klassen [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
| [PsdOptions(image)](#PsdOptions_image_2) | Initierar en ny instans av klassen [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
| [PsdOptions(options)](#PsdOptions_options_3) | Initierar en ny instans av klassen [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| background_contents | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Hämtar eller anger bakgrundsfärgen.<br/>            Den kan ses under transparenta objekt. |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| channel_bits_count | short | r/w | Hämtar eller anger bitantalet per färgkanal. |
| channels_count | short | r/w | Hämtar eller anger antalet färgkanaler. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes/) | r/w | Hämtar eller anger PSD‑färgläget. |
| compression_method | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod/) | r/w | Hämtar eller anger PSD‑komprimeringsmetoden. |
| default_replacement_font | string | r/w | Hämtar eller anger standardteckensnittet för ersättning (teckensnitt som kommer att användas för att rita text vid export till raster, om befintligt lagertypsnitt i PSD-filen inte finns i systemet).<br/>            För att få rätt namn på standardteckensnittet kan följande kodsnutt användas:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| borttagen | bool | r | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| full_frame | bool | r/w | Hämtar eller anger ett värde som indikerar om [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Flersidiga alternativ |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Hämtar eller anger färgpaletten. |
| psd_version | [PsdVersion](/psd/python-net/aspose.psd.fileformats.psd/psdversion/) | r/w | Hämtar eller anger filformatets version. Den kan vara PSD eller PSB. |
| refresh_image_preview_data | bool | r/w | Hämtar eller anger ett värde som indikerar om [refresh image preview data] - alternativet som används för att maximera kompatibiliteten med andra PSD‑bildvisare.<br/>            Observera att ritning av textlager till slutlig layout inte stöds för Compact Framework‑plattformen |
| remove_global_text_engine_resource | bool | r/w | Hämtar eller anger ett värde som indikerar om - Ta bort den globala textmotorresursen - Används för vissa textlagrade psd-filer, endast när de inte kan öppnas i Adobe Photoshop efter bearbetning (mest för saknade teckensnitt relaterade textlager).<br/>            Efter att ha använt detta alternativ måste användaren göra följande i den öppnade Photoshop-filen: Menyn "Text" -> "Processa saknade teckensnitt". Efter den operationen kommer all text att visas igen.<br/>            Observera att denna operation kan orsaka vissa slutliga layoutändringar. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Hämtar eller anger upplösningsinställningarna. |
| resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock/) | r/w | Hämtar eller anger psd-resurserna. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Hämtar eller anger källan för att skapa bilden i. |
| update_metadata | bool | r/w | Hämtar eller anger ett värde som indikerar om [update metadata].<br/>            Om värdet är true uppdateras metadata när en bild sparas. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Hämtar eller anger vektorrasteriseringsalternativen. |
| version | int | r/w | Hämtar eller anger psd-filens version. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Hämta eller ange XMP-datakontainer |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [clone()](#clone__1) | Klonar denna instans. |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

Initierar en ny instans av klassen [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

### Constructor: PsdOptions(image) {#PsdOptions_image_2}


```
 PsdOptions(image) 
```

Initierar en ny instans av klassen [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) | Bilden. |

### Constructor: PsdOptions(options) {#PsdOptions_options_3}


```
 PsdOptions(options) 
```

Initierar en ny instans av klassen [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions) | Alternativen. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klonar denna instans.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Returnerar en ytlig kopia av denna instans |


