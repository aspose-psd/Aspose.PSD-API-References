---
title: "BmpOptions Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.psd.imageoptions/bmpoptions/
---

**Summary:** The bmp file format creation options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.BmpOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [BmpOptions()](#BmpOptions__1) | Initialisiert eine neue Instanz der [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/) Klasse. |
| [BmpOptions(bmp_options)](#BmpOptions_bmp_options_2) | Initialisiert eine neue Instanz der [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bits_per_pixel | int | r/w | Liest oder setzt die Bits‑pro‑Pixel‑Anzahl des Bildes. |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| compression | [BitmapCompression](/psd/python-net/aspose.psd.fileformats.bmp/bitmapcompression/) | r/w | Liest oder setzt die Kompression. |
| default_replacement_font | string | r/w | Ruft den Standard-Ersatzschriftart ab oder legt sie fest (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen-Schriftart in der PSD-Datei im System nicht vorhanden ist).<br/>            Um den richtigen Namen der Standardschriftart zu erhalten, kann der folgende Codeabschnitt verwendet werden:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Ruft einen Wert ab, der angibt, ob diese Instanz freigegeben wurde. |
| full_frame | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob [full frame]. |
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


### Constructor: BmpOptions() {#BmpOptions__1}


```
 BmpOptions() 
```

Initialisiert eine neue Instanz der [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/) Klasse.

### Constructor: BmpOptions(bmp_options) {#BmpOptions_bmp_options_2}


```
 BmpOptions(bmp_options) 
```

Initialisiert eine neue Instanz der [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bmp_options | [BmpOptions](/psd/python-net/aspose.psd.imageoptions/bmpoptions) | Die BMP-Optionen. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klonen Sie diese Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Gibt eine flache Kopie dieser Instanz zurück |


