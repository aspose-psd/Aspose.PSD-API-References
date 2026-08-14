---
title: "GifOptions Klasse"
type: docs
weight: 30
url: /de/python-net/aspose.psd.imageoptions/gifoptions/
---

**Summary:** The gif file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.GifOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [GifOptions()](#GifOptions__1) | Initialisiert eine neue Instanz der [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) Klasse. |
| [GifOptions(gif_options)](#GifOptions_gif_options_2) | Initialisiert eine neue Instanz der [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| background_color_index | byte | r/w | Ruft den GIF-Hintergrundfarbindex ab oder legt ihn fest. |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| color_resolution | byte | r/w | Ruft die GIF-Farbauflösung ab oder legt sie fest. |
| default_replacement_font | string | r/w | Ruft den Standard-Ersatzschriftart ab oder legt sie fest (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen-Schriftart in der PSD-Datei im System nicht vorhanden ist).<br/>            Um den richtigen Namen der Standardschriftart zu erhalten, kann der folgende Codeabschnitt verwendet werden:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Ruft einen Wert ab, der angibt, ob diese Instanz freigegeben wurde. |
| do_palette_correction | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob die Palettenkorrektur angewendet wird. |
| full_frame | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob [full frame]. |
| has_trailer | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob das GIF einen Trailer hat. |
| interlaced | bool | r/w | Wahr, wenn das Bild zeilenweise dargestellt werden soll. |
| is_palette_sorted | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob Paletteneinträge sortiert sind. |
| max_diff | int | r/w | Ruft die maximal zulässige Pixeldifferenz ab oder legt sie fest. Ist sie größer als Null, wird verlustbehaftete Kompression verwendet.<br/>            Empfohlener Wert für optimale verlustbehaftete Kompression ist 80. 30 steht für sehr leichte Kompression, 200 für stark.<br/>            Sie funktioniert am besten, wenn nur wenig Verlust eingeführt wird, und aufgrund der Beschränkung des Kompressionsalgorithmus führen sehr hohe Verluststufen nicht zu einem entsprechenden Gewinn.<br/>            Der zulässige Wertebereich ist [0, 1000]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Die Mehrseitigen Optionen |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Ruft die Farbpalette ab oder legt sie fest. |
| pixel_aspect_ratio | byte | r/w | Ruft das Seitenverhältnis der GIF-Pixel ab oder legt es fest. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Liest oder setzt die Auflösungseinstellungen. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Liest oder setzt die Quelle, in der das Bild erstellt wird. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Liest oder setzt die Vektor‑Rasterisierungsoptionen. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Liest oder setzt den XMP‑Metadatencontainer. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Klonen Sie diese Instanz. |


### Constructor: GifOptions() {#GifOptions__1}


```
 GifOptions() 
```

Initialisiert eine neue Instanz der [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) Klasse.

### Constructor: GifOptions(gif_options) {#GifOptions_gif_options_2}


```
 GifOptions(gif_options) 
```

Initialisiert eine neue Instanz der [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| gif_options | [GifOptions](/psd/python-net/aspose.psd.imageoptions/gifoptions) | Die GIF-Optionen. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klonen Sie diese Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Gibt eine flache Kopie dieser Instanz zurück |


