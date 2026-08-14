---
title: "PsdOptions Klasse"
type: docs
weight: 100
url: /de/python-net/aspose.psd.imageoptions/psdoptions/
---

**Summary:** The psd file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.PsdOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [PsdOptions()](#PsdOptions__1) | Initialisiert eine neue Instanz der Klasse [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
| [PsdOptions(image)](#PsdOptions_image_2) | Initialisiert eine neue Instanz der Klasse [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
| [PsdOptions(options)](#PsdOptions_options_3) | Initialisiert eine neue Instanz der Klasse [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| background_contents | [RawColor](/psd/python-net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/) | r/w | Ruft ab oder legt die Hintergrundfarbe fest.<br/>            Sie ist unter transparenten Objekten zu sehen. |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| channel_bits_count | short | r/w | Ruft ab oder legt die Bitanzahl pro Farbkanal fest. |
| channels_count | short | r/w | Ruft ab oder legt die Anzahl der Farbkanäle fest. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes/) | r/w | Ruft ab oder legt den PSD-Farbmodus fest. |
| compression_method | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod/) | r/w | Ruft ab oder legt die PSD-Komprimierungsmethode fest. |
| default_replacement_font | string | r/w | Ruft den Standard-Ersatzschriftart ab oder legt sie fest (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen-Schriftart in der PSD-Datei im System nicht vorhanden ist).<br/>            Um den richtigen Namen der Standardschriftart zu erhalten, kann der folgende Codeabschnitt verwendet werden:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Ruft einen Wert ab, der angibt, ob diese Instanz freigegeben wurde. |
| full_frame | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob [full frame]. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Die Mehrseitigen Optionen |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Ruft die Farbpalette ab oder legt sie fest. |
| psd_version | [PsdVersion](/psd/python-net/aspose.psd.fileformats.psd/psdversion/) | r/w | Ruft ab oder legt die Dateiformatversion fest. Sie kann PSD oder PSB sein. |
| refresh_image_preview_data | bool | r/w | Ruft ab oder legt einen Wert fest, der angibt, ob [refresh image preview data] - Option, die verwendet wird, um die Kompatibilität mit anderen PSD-Bildbetrachtern zu maximieren.<br/>            Bitte beachten Sie, dass das Zeichnen von Textebenen in das endgültige Layout für die Compact Framework-Plattform nicht unterstützt wird. |
| remove_global_text_engine_resource | bool | r/w | Ruft ab oder legt einen Wert fest, der angibt, ob - Die globale Text-Engine-Ressource entfernen - Wird für einige textschichtige PSD-Dateien verwendet, ausschließlich in dem Fall, dass sie nach der Verarbeitung nicht in Adobe Photoshop geöffnet werden können (hauptsächlich bei fehlenden Schriftarten in Textschichten).<br/>            Nach der Verwendung dieser Option muss der Benutzer im in Photoshop geöffneten Dokument Folgendes ausführen: Menü \"Text\" -&gt; \"Fehlende Schriften verarbeiten\". Nach diesem Vorgang wird aller Text wieder angezeigt.<br/>            Bitte beachten Sie, dass dieser Vorgang einige Änderungen im endgültigen Layout verursachen kann. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Liest oder setzt die Auflösungseinstellungen. |
| resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock/) | r/w | Ruft ab oder legt die PSD-Ressourcen fest. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Liest oder setzt die Quelle, in der das Bild erstellt wird. |
| update_metadata | bool | r/w | Ruft ab oder legt einen Wert fest, der angibt, ob [update metadata].<br/>            Wenn der Wert true ist, werden die Metadaten beim Speichern eines Bildes aktualisiert. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Liest oder setzt die Vektor‑Rasterisierungsoptionen. |
| version | int | r/w | Ruft ab oder legt die PSD-Dateiversion fest. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Lese oder setze XMP-Datencontainer |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Klonen Sie diese Instanz. |


### Constructor: PsdOptions() {#PsdOptions__1}


```
 PsdOptions() 
```

Initialisiert eine neue Instanz der Klasse [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

### Constructor: PsdOptions(image) {#PsdOptions_image_2}


```
 PsdOptions(image) 
```

Initialisiert eine neue Instanz der Klasse [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) | Das Bild. |

### Constructor: PsdOptions(options) {#PsdOptions_options_3}


```
 PsdOptions(options) 
```

Initialisiert eine neue Instanz der Klasse [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions) | Die Optionen. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klonen Sie diese Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Gibt eine flache Kopie dieser Instanz zurück |


