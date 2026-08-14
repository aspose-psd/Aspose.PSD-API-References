---
title: "VectorRasterizationOptions Klasse"
type: docs
weight: 150
url: /de/python-net/aspose.psd.imageoptions/vectorrasterizationoptions/
---

**Summary:** The vector rasterization options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.VectorRasterizationOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Liest oder setzt eine Hintergrundfarbe. |
| border_x | float | r/w | Liest oder setzt den Rand X. |
| border_y | float | r/w | Liest oder setzt den Rand Y. |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| center_drawing | bool | r/w | Liest oder setzt einen Wert, der angibt, ob zentriertes Zeichnen erfolgt. |
| default_replacement_font | string | r/w | Ruft den Standard-Ersatzschriftart ab oder legt sie fest (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen-Schriftart in der PSD-Datei im System nicht vorhanden ist).<br/>            Um den richtigen Namen der Standardschriftart zu erhalten, kann der folgende Codeabschnitt verwendet werden:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Ruft einen Wert ab, der angibt, ob diese Instanz freigegeben wurde. |
| draw_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Liest oder setzt eine Vordergrundfarbe. |
| full_frame | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Die Mehrseitigen Optionen |
| page_height | float | r/w | Liest oder setzt die Seitenhöhe. |
| page_size | [SizeF](/psd/python-net/aspose.psd/sizef) | r/w | Liest oder setzt die Seitengröße. |
| page_width | float | r/w | Ruft die Seitenbreite ab oder legt sie fest. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Ruft die Farbpalette ab oder legt sie fest. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Liest oder setzt die Auflösungseinstellungen. |
| smoothing_mode | [SmoothingMode](/psd/python-net/aspose.psd/smoothingmode) | r/w | Ruft den Glättungsmodus ab oder legt ihn fest. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Liest oder setzt die Quelle, in der das Bild erstellt wird. |
| text_rendering_hint | [TextRenderingHint](/psd/python-net/aspose.psd/textrenderinghint) | r/w | Ruft den Textdarstellungshinweis ab oder legt ihn fest. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Liest oder setzt die Vektor‑Rasterisierungsoptionen. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Liest oder setzt den XMP‑Metadatencontainer. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Klonen Sie diese Instanz. |
| [copy_to(vector_rasterization_options)](#copy_to_vector_rasterization_options_2) | Kopiert nach. |


### Method: clone() {#clone__1}


```
 clone() 
```

Klonen Sie diese Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Gibt eine flache Kopie dieser Instanz zurück |


### Method: copy_to(vector_rasterization_options) {#copy_to_vector_rasterization_options_2}


```
 copy_to(vector_rasterization_options) 
```

Kopiert nach.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | Die Vektor-Rasterisierungsoptionen. |

