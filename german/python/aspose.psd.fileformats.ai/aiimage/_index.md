---
title: "AiImage Klasse"
type: docs
weight: 40
url: /de/python-net/aspose.psd.fileformats.ai/aiimage/
---

**Summary:** The Adobe Illustrator (AI)  Image.

**Module:** [aspose.psd.fileformats.ai](/psd/python-net/aspose.psd.fileformats.ai/)

**Full Name:** aspose.psd.fileformats.ai.AiImage

**Inheritance:** IObjectWithBounds, Image

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [AiImage()](#AiImage__1) | Initialisiert eine neue Instanz der AiImage Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| active_page_index | int | r/w | Liest oder setzt den Index der aktiven Seite. |
| auto_adjust_palette | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die Palette automatisch angepasst wird. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Liest oder setzt einen Wert für die Hintergrundfarbe. |
| bits_per_pixel | int | r | Liest die Bits‑pro‑Pixel‑Anzahl des Bildes. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Liest die Bildgrenzen. |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Liest den [Image](/psd/python-net/aspose.psd/image/)‑Container. |
| data_section | [AiDataSection](/psd/python-net/aspose.psd.fileformats.ai/aidatasection) | r | Liest den Datenabschnitt. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Liest den Datenstrom des Objekts. |
| disposed | bool | r | Ruft einen Wert ab, der angibt, ob diese Instanz freigegeben wurde. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Liest einen Wert des Dateiformats. |
| finalize_section | [AiFinalizeSection](/psd/python-net/aspose.psd.fileformats.ai/aifinalizesection) | r | Liest den Abschlussabschnitt. |
| has_background_color | bool | r/w | Liest oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| header | [AiHeader](/psd/python-net/aspose.psd.fileformats.ai/aiheader) | r | Liest den Header. |
| height | int | r | Liest die Bildhöhe. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Liest oder setzt den Interrupt‑Monitor. |
| is_cached | bool | r | Liest einen Wert, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist. |
| layers | [AiLayerSection[]](/psd/python-net/aspose.psd.fileformats.ai/ailayersection) | r | Liest die Ebenenabschnitte. |
| page_count | int | r | Die Anzahl der Seiten.<br/>            Für alte AI-Formatbilder ist dieser Wert immer 0. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Liest oder setzt die Farbpalette. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| setup_section | [AiSetupSection](/psd/python-net/aspose.psd.fileformats.ai/aisetupsection) | r | Liest den Setup-Abschnitt. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Liest die Bildgröße. |
| use_palette | bool | r | Liest einen Wert, der angibt, ob die Bildpalette verwendet wird. |
| version | [AiFormatVersion](/psd/python-net/aspose.psd.fileformats.ai/aiformatversion) | r | Liest die Version des Adobe Illustrator-Formats. |
| width | int | r | Liest die Bildbreite. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r | Liest oder setzt die XMP-Metadaten. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_layer(layer)](#add_layer_layer_1) | Fügt den AI-Ebenenabschnitt hinzu. |
| cache_data() | Zwischenspeichert die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) durchgeführt werden. |
| [can_load(file_path)](#can_load_file_path_2) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_3) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet. |
| [can_load(stream)](#can_load_stream_4) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann. |
| [can_load(stream, load_options)](#can_load_stream_load_options_5) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann und optional die angegebenen <paramref name=\"loadOptions\" /> verwendet. |
| [can_save(options)](#can_save_options_6) | Bestimmt, ob das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen repräsentiert wird, gespeichert werden kann. |
| [create(image_options, width, height)](#create_image_options_width_height_7) | Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen. |
| [get_default_options(args)](#get_default_options_args_8) | Liest die Standardoptionen. |
| [get_file_format(file_path)](#get_file_format_file_path_9) | Ermittelt das Dateiformat. |
| [get_file_format(stream)](#get_file_format_stream_10) | Ermittelt das Dateiformat. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_11) | Ermittelt das Rechteck, das zum aktuellen Bild passt. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_12) | Ermittelt das Rechteck, das zum aktuellen Bild passt. |
| [get_original_options()](#get_original_options__13) | Ermittelt die Optionen basierend auf den ursprünglichen Dateieinstellungen.<br/>            Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen.<br/>            Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) Methode speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt.<br/>            Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und sie<br/>            an die [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) Methode als zweiten Parameter zu übergeben. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_14) | Ermittelt eine proportionale Höhe. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_15) | Ermittelt eine proportionale Breite. |
| [load(file_path)](#load_file_path_16) | Lädt ein neues Bild aus der angegebenen Datei. |
| [load(file_path, load_options)](#load_file_path_load_options_17) | Lädt ein neues Bild aus der angegebenen Datei. |
| [load(stream)](#load_stream_18) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load(stream, load_options)](#load_stream_load_options_19) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [resize(new_width, new_height)](#resize_new_width_new_height_20) | Skaliert das Bild. Der Standard‑[ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wird verwendet. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_21) | Skaliert das Bild. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_22) | Skaliert das Bild. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_23) | Skaliert die Höhe proportional. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_24) | Skaliert die Höhe proportional. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_25) | Skaliert die Höhe proportional. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_26) | Skaliert die Breite proportional. Der Standard‑[ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wird verwendet. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_27) | Skaliert die Breite proportional. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_28) | Skaliert die Breite proportional. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_29) | Dreht, spiegelt oder dreht und spiegelt das Bild. |
| save() | Speichert die Bilddaten in den zugrunde liegenden Stream. |
| [save(file_path)](#save_file_path_30) | Speichert die Objektdaten am angegebenen Dateipfad. |
| [save(file_path, options)](#save_file_path_options_31) | Speichert die Objektdaten am angegebenen Dateipfad im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_32) | Speichert die Objektdaten am angegebenen Dateipfad im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(file_path, over_write)](#save_file_path_over_write_33) | Speichert die Objektdaten am angegebenen Dateipfad. |
| [save(stream)](#save_stream_34) | Speichert die Objektdaten in den angegebenen Stream. |
| [save(stream, options_base)](#save_stream_options_base_35) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_36) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_37) | Setzt die Bildpalette. |


### Constructor: AiImage() {#AiImage__1}


```
 AiImage() 
```

Initialisiert eine neue Instanz der AiImage Klasse

### Method: add_layer(layer) {#add_layer_layer_1}


```
 add_layer(layer) 
```

Fügt den AI-Ebenenabschnitt hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer | [AiLayerSection](/psd/python-net/aspose.psd.fileformats.ai/ailayersection) | Der AI-Ebenenabschnitt. |

### Method: can_load(file_path)  [static] {#can_load_file_path_2}


```
 can_load(file_path) 
```

Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn das Bild aus der angegebenen Datei geladen werden kann; andernfalls <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_3}


```
 can_load(file_path, load_options) 
```

Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Die Ladeoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn das Bild aus der angegebenen Datei geladen werden kann; andernfalls <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_4}


```
 can_load(stream) 
```

Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream, aus dem geladen werden soll. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn das Bild aus dem angegebenen Stream geladen werden kann; andernfalls <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_5}


```
 can_load(stream, load_options) 
```

Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann und optional die angegebenen <paramref name=\"loadOptions\" /> verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream, aus dem geladen werden soll. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Die Ladeoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn das Bild aus dem angegebenen Stream geladen werden kann; andernfalls <c>false</c>. |


### Method: can_save(options) {#can_save_options_6}


```
 can_save(options) 
```

Bestimmt, ob das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen repräsentiert wird, gespeichert werden kann.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die zu verwendenden Speicheroptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen dargestellt wird, gespeichert werden kann; andernfalls <c>false</c>. |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_7}


```
 create(image_options, width, height) 
```

Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Bildoptionen. |
| width | int | Die Breite. |
| height | int | Die Höhe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Das neu erstellte Bild. |


### Method: get_default_options(args) {#get_default_options_args_8}


```
 get_default_options(args) 
```

Liest die Standardoptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| args | object | Die Argumente. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Standardoptionen |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_9}


```
 get_file_format(file_path) 
```

Ermittelt das Dateiformat.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Das ermittelte Dateiformat. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_10}


```
 get_file_format(stream) 
```

Ermittelt das Dateiformat.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Das ermittelte Dateiformat. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_11}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Ermittelt das Rechteck, das zum aktuellen Bild passt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, für das das passende Rechteck ermittelt werden soll. |
| pixels | int | Die 32-Bit-ARGB-Pixel. |
| width | int | Die Objektbreite. |
| height | int | Die Objekthöhe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das passende Rechteck oder eine Ausnahme, wenn kein passendes Rechteck gefunden werden kann. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_12}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Ermittelt das Rechteck, das zum aktuellen Bild passt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, für das das passende Rechteck ermittelt werden soll. |
| width | int | Die Objektbreite. |
| height | int | Die Objekthöhe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das passende Rechteck oder eine Ausnahme, wenn kein passendes Rechteck gefunden werden kann. |


### Method: get_original_options() {#get_original_options__13}


```
 get_original_options() 
```

Ermittelt die Optionen basierend auf den ursprünglichen Dateieinstellungen.<br/>            Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen.<br/>            Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) Methode speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt.<br/>            Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und sie<br/>            an die [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) Methode als zweiten Parameter zu übergeben.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Optionen basierend auf den ursprünglichen Dateieinstellungen. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_14}


```
 get_proportional_height(width, height, new_width) 
```

Ermittelt eine proportionale Höhe.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Die Breite. |
| height | int | Die Höhe. |
| new_width | int | Die neue Breite. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die proportionale Höhe. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_15}


```
 get_proportional_width(width, height, new_height) 
```

Ermittelt eine proportionale Breite.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Die Breite. |
| height | int | Die Höhe. |
| new_height | int | Die neue Höhe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die proportionale Breite. |


### Method: load(file_path)  [static] {#load_file_path_16}


```
 load(file_path) 
```

Lädt ein neues Bild aus der angegebenen Datei.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, von dem das Bild geladen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Das geladene Bild. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_17}


```
 load(file_path, load_options) 
```

Lädt ein neues Bild aus der angegebenen Datei.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, von dem das Bild geladen wird. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Die Ladeoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Das geladene Bild. |


### Method: load(stream)  [static] {#load_stream_18}


```
 load(stream) 
```

Lädt ein neues Bild aus dem angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream, von dem das Bild geladen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Das geladene Bild. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_19}


```
 load(stream, load_options) 
```

Lädt ein neues Bild aus dem angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream, von dem das Bild geladen wird. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Die Ladeoptionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Das geladene Bild. |


### Method: resize(new_width, new_height) {#resize_new_width_new_height_20}


```
 resize(new_width, new_height) 
```

Skaliert das Bild. Der Standard‑[ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_21}


```
 resize(new_width, new_height, resize_type) 
```

Skaliert das Bild.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Der Skalierungstyp. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_22}


```
 resize(new_width, new_height, settings) 
```

Skaliert das Bild.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Die Skalierungseinstellungen. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_23}


```
 resize_height_proportionally(new_height) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_24}


```
 resize_height_proportionally(new_height, resize_type) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Typ der Skalierung. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_25}


```
 resize_height_proportionally(new_height, settings) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Die Bildskalierungseinstellungen. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_26}


```
 resize_width_proportionally(new_width) 
```

Skaliert die Breite proportional. Der Standard‑[ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_27}


```
 resize_width_proportionally(new_width, resize_type) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Typ der Skalierung. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_28}


```
 resize_width_proportionally(new_width, settings) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Die Bildskalierungseinstellungen. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_29}


```
 rotate_flip(rotate_flip_type) 
```

Dreht, spiegelt oder dreht und spiegelt das Bild.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Typ der Dreh-Spiegelung. |

### Method: save(file_path) {#save_file_path_30}


```
 save(file_path) 
```

Speichert die Objektdaten am angegebenen Dateipfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Daten des Objekts gespeichert werden. |

### Method: save(file_path, options) {#save_file_path_options_31}


```
 save(file_path, options) 
```

Speichert die Objektdaten am angegebenen Dateipfad im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Optionen. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_32}


```
 save(file_path, options, bounds_rectangle) 
```

Speichert die Objektdaten am angegebenen Dateipfad im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Optionen. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Zielbild-Begrenzungsrechteck. Setzen Sie das leere Rechteck zur Verwendung der Quellbegrenzungen. |

### Method: save(file_path, over_write) {#save_file_path_over_write_33}


```
 save(file_path, over_write) 
```

Speichert die Objektdaten am angegebenen Dateipfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Daten des Objekts gespeichert werden. |
| over_write | bool | Wenn auf <c>true</c> gesetzt, werden die Dateiinhalte überschrieben, andernfalls wird angehängt. |

### Method: save(stream) {#save_stream_34}


```
 save(stream) 
```

Speichert die Objektdaten in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream, in dem die Daten des Objekts gespeichert werden. |

### Method: save(stream, options_base) {#save_stream_options_base_35}


```
 save(stream, options_base) 
```

Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream, in dem die Bilddaten gespeichert werden. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Speicheroptionen. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_36}


```
 save(stream, options_base, bounds_rectangle) 
```

Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream, in dem die Bilddaten gespeichert werden. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Speicheroptionen. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck der Zielbildgrenzen. Setzen Sie das leere Rechteck, um die Quellgrenzen zu verwenden. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_37}


```
 set_palette(palette, update_colors) 
```

Setzt die Bildpalette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Die zu setzende Palette. |
| update_colors | bool | Wenn auf <c>true</c> gesetzt, werden die Farben gemäß der neuen Palette aktualisiert; andernfalls bleiben die Farbindizes unverändert. Beachten Sie, dass unveränderte Indizes das Bild beim Laden zum Absturz bringen können, wenn einige Indizes keinen entsprechenden Paletteneintrag haben. |

