---
title: "Jpeg2000Options Klasse"
type: docs
weight: 50
url: /de/python-net/aspose.psd.imageoptions/jpeg2000options/
---

**Summary:** The Jpeg2000 file format options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.Jpeg2000Options

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Jpeg2000Options()](#Jpeg2000Options__1) | Initialisiert eine neue Instanz der [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/) Klasse. |
| [Jpeg2000Options(jpeg_2000_options)](#Jpeg2000Options_jpeg_2000_options_2) | Initialisiert eine neue Instanz der [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| codec | [Jpeg2000Codec](/psd/python-net/aspose.psd.fileformats.jpeg2000/jpeg2000codec/) | r/w | Liest oder setzt den JPEG2000-Codec |
| comments | string | r/w | Liest oder setzt die Jpeg-Kommentar-Marker. |
| compression_ratios | int | r/w | Liest oder setzt das Array der Kompressionsraten.<br/>            Unterschiedliche Kompressionsraten für aufeinanderfolgende Schichten.<br/>            Der für jede Qualitätsstufe angegebene Wert ist der gewünschte<br/>            Kompressionsfaktor.<br/>            Abnehmende Raten erforderlich. |
| default_replacement_font | string | r/w | Ruft den Standard-Ersatzschriftart ab oder legt sie fest (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen-Schriftart in der PSD-Datei im System nicht vorhanden ist).<br/>            Um den richtigen Namen der Standardschriftart zu erhalten, kann der folgende Codeabschnitt verwendet werden:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Ruft einen Wert ab, der angibt, ob diese Instanz freigegeben wurde. |
| full_frame | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob [full frame]. |
| irreversibel | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die irreversible DWT 9-7 (true) verwendet wird oder die verlustfreie DWT 5-3-Kompression (Standard). |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Die Mehrseitigen Optionen |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Ruft die Farbpalette ab oder legt sie fest. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Liest oder setzt die Auflösungseinstellungen. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Liest oder setzt die Quelle, in der das Bild erstellt wird. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Liest oder setzt die Vektor‑Rasterisierungsoptionen. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Liest oder setzt den XMP‑Metadatencontainer. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Klonen Sie diese Instanz. |


### Constructor: Jpeg2000Options() {#Jpeg2000Options__1}


```
 Jpeg2000Options() 
```

Initialisiert eine neue Instanz der [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/) Klasse.

### Constructor: Jpeg2000Options(jpeg_2000_options) {#Jpeg2000Options_jpeg_2000_options_2}


```
 Jpeg2000Options(jpeg_2000_options) 
```

Initialisiert eine neue Instanz der [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| jpeg_2000_options | [Jpeg2000Options](/psd/python-net/aspose.psd.imageoptions/jpeg2000options) | Die Jpeg2000-Dateiformatoptionen, von denen Einstellungen kopiert werden sollen. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klonen Sie diese Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Gibt eine flache Kopie dieser Instanz zurück |


