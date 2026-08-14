---
title: "JpegOptions Klasse"
type: docs
weight: 60
url: /de/python-net/aspose.psd.imageoptions/jpegoptions/
---

**Summary:** The jpeg file format create options.

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.JpegOptions

**Inheritance:** ImageOptionsBase

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [JpegOptions()](#JpegOptions__1) | Initialisiert eine neue Instanz der [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) Klasse. |
| [JpegOptions(jpeg_options)](#JpegOptions_jpeg_options_2) | Initialisiert eine neue Instanz der [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bits_per_channel | byte | r/w | Liest oder setzt Bits pro Kanal für verlustfreie JPEG-Bilder. Jetzt unterstützen wir von 2 bis 8 Bits pro Kanal. |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Das Ziel‑CMYK‑Farbprofil für CMYK‑JPEG‑Bilder. Wird zum Speichern von Bildern verwendet. Muss zusammen mit RGBColorProfile für korrekte Farbumwandlung verwendet werden. |
| color_type | [JpegCompressionColorMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressioncolormode/) | r/w | Liest oder setzt den Farbtyp für JPEG‑Bilder. |
| comment | string | r/w | Liest oder setzt den JPEG‑Dateikommentar. |
| compression_type | [JpegCompressionMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpegcompressionmode/) | r/w | Liest oder setzt den Kompressionstyp. |
| default_memory_allocation_limit | int | r/w | Liest oder setzt das Standard‑Speicherzuweisungs‑Limit. |
| default_replacement_font | string | r/w | Ruft den Standard-Ersatzschriftart ab oder legt sie fest (Schriftart, die zum Zeichnen von Text beim Export in Raster verwendet wird, wenn die vorhandene Ebenen-Schriftart in der PSD-Datei im System nicht vorhanden ist).<br/>            Um den richtigen Namen der Standardschriftart zu erhalten, kann der folgende Codeabschnitt verwendet werden:<br/>            System.Drawing.Text.InstalledFontCollection col = new System.Drawing.Text.InstalledFontCollection();<br/>            System.Drawing.FontFamily families = col.Families;<br/>            string defaultFontName = families[0].Name;        <br/>            PsdLoadOptions psdLoadOptions = new PsdLoadOptions() { DefaultReplacementFont = defaultFontName }); |
| disposed | bool | r | Ruft einen Wert ab, der angibt, ob diese Instanz freigegeben wurde. |
| exif_data | [JpegExifData](/psd/python-net/aspose.psd.exif/jpegexifdata/) | r/w | Lese oder setze den EXIF‑Datencontainer. |
| full_frame | bool | r/w | Ruft einen Wert ab oder legt ihn fest, der angibt, ob [full frame]. |
| horizontal_sampling | byte | r/w | Liest oder setzt die horizontalen Subsamplings für jede Komponente. |
| jfif | [JFIFData](/psd/python-net/aspose.psd.fileformats.jpeg/jfifdata/) | r/w | Liest oder setzt das JFIF. |
| jpeg_ls_allowed_lossy_error | int | r/w | Liest oder setzt die JPEG‑LS‑Differenzgrenze für nahezu verlustlose Kodierung (NEAR‑Parameter aus der JPEG‑LS‑Spezifikation). |
| jpeg_ls_interleave_mode | [JpegLsInterleaveMode](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglsinterleavemode/) | r/w | Liest oder setzt den JPEG‑LS‑Interleave‑Modus. |
| jpeg_ls_preset | [JpegLsPresetCodingParameters](/psd/python-net/aspose.psd.fileformats.jpeg/jpeglspresetcodingparameters/) | r/w | Liest oder setzt die JPEG‑LS‑Voreinstellungsparameter. |
| multi_page_options | [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions) | r/w | Die Mehrseitigen Optionen |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Ruft die Farbpalette ab oder legt sie fest. |
| preblend_alpha_if_present | bool | r/w | Liest oder setzt einen Wert, der angibt, ob Rot-, Grün- und Blau‑Komponenten mit einer Hintergrundfarbe gemischt werden sollen, wenn ein Alpha‑Kanal vorhanden ist. |
| quality | int | r/w | Liest oder setzt die Bildqualität. |
| rd_opt_settings | [RdOptimizerSettings](/psd/python-net/aspose.psd.imageoptions/rdoptimizersettings) | r/w | Liest oder setzt die RD‑Optimizer‑Einstellungen. |
| resolution_settings | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | r/w | Liest oder setzt die Auflösungseinstellungen. |
| resolution_unit | [ResolutionUnit](/psd/python-net/aspose.psd.fileformats.psd.resources.resolutionenums/resolutionunit) | r/w | Liest oder setzt die Auflösungseinheit. |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Das Ziel‑RGB‑Farbprofil für CMYK‑JPEG‑Bilder. Wird zum Speichern von Bildern verwendet. Muss zusammen mit CMYKColorProfile für korrekte Farbumwandlung verwendet werden. |
| sample_rounding_mode | [SampleRoundingMode](/psd/python-net/aspose.psd.fileformats.jpeg/sampleroundingmode/) | r/w | Ruft ab oder legt fest, wie der Beispielrundungsmodus einen 8‑Bit‑Wert an einen n‑Bit‑Wert anpasst. <see cref=\"P:JpegOptions.BitsPerChannel\" /> |
| scaled_quality | int | r | Die skalierte Qualität. |
| source | [Source](/psd/python-net/aspose.psd/source) | r/w | Liest oder setzt die Quelle, in der das Bild erstellt wird. |
| vector_rasterization_options | [VectorRasterizationOptions](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | Liest oder setzt die Vektor‑Rasterisierungsoptionen. |
| vertical_sampling | byte | r/w | Ruft ab oder legt die vertikalen Subsamplings für jede Komponente fest. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Liest oder setzt den XMP‑Metadatencontainer. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Klonen Sie diese Instanz. |


### Constructor: JpegOptions() {#JpegOptions__1}


```
 JpegOptions() 
```

Initialisiert eine neue Instanz der [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) Klasse.

### Constructor: JpegOptions(jpeg_options) {#JpegOptions_jpeg_options_2}


```
 JpegOptions(jpeg_options) 
```

Initialisiert eine neue Instanz der [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| jpeg_options | [JpegOptions](/psd/python-net/aspose.psd.imageoptions/jpegoptions) | Die JPEG-Optionen. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klonen Sie diese Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Gibt eine flache Kopie dieser Instanz zurück |


