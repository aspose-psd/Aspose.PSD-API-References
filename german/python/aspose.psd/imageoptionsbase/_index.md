---
title: "ImageOptionsBase Klasse"
type: docs
weight: 2270
url: /de/python-net/aspose.psd/imageoptionsbase/
---

**Summary:** The image base options.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageOptionsBase

**Inheritance:** DisposableObject

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| default_replacement_font | string | r/w | Ruft den Standard-Ersatzschriftart ab oder legt sie fest (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen-Schriftart in der PSD-Datei im System nicht vorhanden ist).<br/>            Um den richtigen Namen der Standardschriftart zu erhalten, kann der folgende Codeabschnitt verwendet werden:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Ruft einen Wert ab, der angibt, ob diese Instanz freigegeben wurde. |
| full_frame | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) | r/w | Die Mehrseitigen Optionen |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Ruft die Farbpalette ab oder legt sie fest. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Liest oder setzt die Auflösungseinstellungen. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Liest oder setzt die Quelle, in der das Bild erstellt wird. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions/) | r/w | Liest oder setzt die Vektor‑Rasterisierungsoptionen. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Liest oder setzt den XMP‑Metadatencontainer. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Klonen Sie diese Instanz. |


### Method: clone() {#clone__1}


```
 clone() 
```

Klonen Sie diese Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Gibt eine flache Kopie dieser Instanz zurück |


