---
title: "SmartObjectLayer Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/
---

**Summary:** Defines the SmartObjectLayer class that contains embedded in the PSD file or linked smart object in the external file.<br/>            With Smart Objects, you can:<br/>            Perform nondestructive transforms. You can scale, rotate, skew, distort, perspective transform, or warp a layer<br/>            without losing original image data or quality because the transforms don�t affect the original data.<br/>            Work with vector data, such as vector artwork from Illustrator, that otherwise would be rasterized.<br/>            Perform nondestructive filtering. You can edit filters applied to Smart Objects at any time.<br/>            Edit one Smart Object and automatically update all its linked instances.<br/>            Apply a layer mask that�s either linked or unlinked to the Smart Object layer.<br/>            Try various designs with low-resolution placeholder images that you later replace with final versions.<br/>            In Adobe� Photoshop�, you can embed the contents of an image into a PSD document.<br/>            More information is here: <see href="https://helpx.adobe.com/photoshop/using/create-smart-objects.html" /><br/>            A layer with an embedded smart object contains placed (PlLd) and SoLd resources with smart object properties.<br/>            The PlLd resource can be alone for PSD versions older then 10.<br/>            These resources contain UniqueId of the LiFdDataSource in the global Lnk2Resource with the embedded filename<br/>            and other parameters, including the embedded file contents in the original format as a byte array.

**Module:** [aspose.psd.fileformats.psd.layers.smartobjects](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, Layer

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [SmartObjectLayer(stream)](#SmartObjectLayer_stream_1) | Initialisiert eine neue Instanz der [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| BLEND_SIGNATURE [statisch] | int | r |  |
| LAYER_HEADER_SIZE [statisch] | int | r |  |
| auto_adjust_palette | bool | r/w |  |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w |    |
| bits_per_pixel | int | r |  |
| blend_clipped_elements | bool | r/w |  |
| blend_mode_key | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w |    |
| blend_mode_signature | int | r |  |
| blending_options | [BlendingOptions](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/) | r |    |
| bottom | int | r/w |  |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Liefert die Objektgrenzen. |
| buffer_size_hint | int | r/w |  |
| channel_information | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r/w |    |
| channels_count | ushort | r |  |
| clipping | byte | r/w |  |
| container | [Image](/psd/python-net/aspose.psd/image) | r |    |
| content_type | [SmartObjectType](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjecttype) | r | Ermittelt den Typ des Inhalts der Smart‑Object‑Ebene.<br/>            Der eingebettete Smart‑Object‑Inhalt ist die eingebettete Rohbilddatei: [LiFdDataSource.data](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/).<br/>            Der verknüpfte Smart‑Object‑Inhalt ist der Rohinhalt der verknüpften Bilddatei, falls verfügbar: [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/).<br/>            Wir unterstützen das Laden aus der Adobe� Photoshop� �� Graphics Library nicht, wenn [LinkDataSource.is_library_link](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) true ist.<br/>            Für reguläre Verknüpfungsdateien verwenden wir zunächst [LiFeDataSource.relative_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/), um die Datei relativ zum Quellbildpfad [None](/psd/python-net/aspose.psd/datastreamsupporter/) zu suchen,<br/>            falls sie nicht verfügbar ist, prüfen wir [LiFeDataSource.full_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/),<br/>            falls nicht, suchen wir die Verknüpfungsdatei im selben Verzeichnis wie unser Bild: [None](/psd/python-net/aspose.psd/datastreamsupporter/). |
| contents | byte | r/w | Ruft die Inhalte der Smart‑Object‑Ebene ab oder legt sie fest.<br/>            Der eingebettete Smart‑Object‑Inhalt ist die eingebettete Rohbilddatei: [LiFdDataSource.data](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) und deren Eigenschaften.<br/>            Der verknüpfte Smart‑Object‑Inhalt ist der Rohinhalt der verknüpften Bilddatei, falls verfügbar, sowie deren Eigenschaften: [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/).<br/>            Wir unterstützen das Laden aus der Adobe� Photoshop� �� Graphics Library nicht, wenn [LinkDataSource.is_library_link](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) true ist.<br/>            Für reguläre Verknüpfungsdateien verwenden wir zunächst [LiFeDataSource.relative_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/), um die Datei relativ zum Quellbildpfad [None](/psd/python-net/aspose.psd/datastreamsupporter/) zu suchen,<br/>            falls sie nicht verfügbar ist, prüfen wir [LiFeDataSource.full_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/),<br/>            falls nicht, suchen wir die Verknüpfungsdatei im selben Verzeichnis wie unser Bild: [None](/psd/python-net/aspose.psd/datastreamsupporter/). |
| contents_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Liest oder setzt die Begrenzungen des Smart‑Objekt‑Inhalts. |
| contents_source | [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) | r/w | Liest oder setzt die Quelle des Smart‑Objekt‑Inhalts. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r |    |
| display_name | string | r/w |  |
| disposed | bool | r |  |
| extra_length | int | r |  |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r |    |
| fill_opacity | int | r/w |  |
| filler | byte | r/w |  |
| flags | [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags) | r/w |    |
| has_alpha | bool | r |  |
| has_background_color | bool | r/w |  |
| has_transparent_color | bool | r/w |  |
| height | int | r | Liest die Objekt‑Höhe. |
| horizontal_resolution | double | r/w |  |
| image_opacity | float | r |  |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w |    |
| is_cached | bool | r |  |
| is_raw_data_available | bool | r | Liest einen Wert, der angibt, ob das Laden von Rohdaten unterstützt wird. |
| is_visible | bool | r/w |  |
| is_visible_in_group | bool | r |  |
| layer_blending_ranges_data | [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata) | r/w |    |
| layer_creation_date_time | datetime | r/w |  |
| layer_lock | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | r/w |    |
| layer_mask_data | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | r/w |    |
| layer_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | r |    |
| left | int | r/w |  |
| Länge | int | r |  |
| name | string | r/w | Liest oder setzt den Namen der Textebene. |
| Deckkraft | byte | r/w |  |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w |    |
| premultiply_components | bool | r/w |  |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w |    |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r |    |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Liest die aktuellen Rohdaten‑Einstellungen. Hinweis: Beim Verwenden dieser Einstellungen werden die Daten ohne Konvertierung geladen. |
| raw_fallback_index | int | r/w |  |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w |    |
| raw_line_size | int | r |  |
| resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r/w |    |
| rechts | int | r/w |  |
| sheet_color_highlight | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | r/w |    |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Ruft die Objektgröße ab. |
| smart_filters | [SmartFilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilters/) | r | Ruft die intelligenten Filter ab. |
| smart_object_provider | [SmartObjectProvider](/psd/python-net/aspose.psd.fileformats.psd/smartobjectprovider) | r | Ruft den Smart-Objekt-Anbieter ab. |
| oben | int | r/w |  |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w |    |
| update_xmp_data | bool | r/w |  |
| use_palette | bool | r |  |
| use_raw_data | bool | r/w |  |
| vertical_resolution | double | r/w |  |
| warp_settings | [WarpSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.warp/warpsettings/) | r/w | Ruft Warp-Parameter ab oder setzt sie, die aus der Ressource (Standard) gesetzt oder abgerufen wurden. |
| width | int | r | Ruft die Objektbreite ab. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w |    |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| add_layer_mask(layer_mask) |  |
| adjust_brightness(brightness) |  |
| adjust_contrast(contrast) |  |
| adjust_gamma(gamma) |  |
| adjust_gamma(gamma_red, gamma_green, gamma_blue) |  |
| binarize_bradley(brightness_difference) |  |
| binarize_bradley(brightness_difference, window_size) |  |
| binarize_fixed(threshold) |  |
| binarize_otsu() |  |
| cache_data() |  |
| [can_load(file_path)](#can_load_file_path_1) |    |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) |    |
| [can_load(stream)](#can_load_stream_3) |    |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) |    |
| [can_save(options)](#can_save_options_5) |    |
| [convert_to_linked(linked_path)](#convert_to_linked_linked_path_6) | Konvertiert dieses eingebettete Smart-Objekt in ein verknüpftes Smart-Objekt. |
| [create(image_options, width, height)](#create_image_options_width_height_7) |    |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| crop(rectangle) |  |
| dither(dithering_method, bits_count) |  |
| dither(dithering_method, bits_count, custom_palette) |  |
| draw_image(location, image) |  |
| [duplicate_layer()](#duplicate_layer__8) | Erstellt eine neue Smart‑Object‑Ebene, indem diese kopiert wird.<br/>            Hinweis: Bei eingebetteten Smart Objects wird das eingebettete Bild gemeinsam genutzt.<br/>            Wenn Sie das eingebettete Bild kopieren möchten, verwenden Sie die Methode [SmartObjectLayer.new_smart_object_via_copy()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |
| embed_linked() | Bettet das verknüpfte Smart‑Object in diese Ebene ein. |
| [export_contents(file_path)](#export_contents_file_path_9) | Exportiert die eingebetteten oder verknüpften Inhalte in eine Datei. |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_10) |    |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_11) |    |
| [get_default_options(args)](#get_default_options_args_12) |    |
| get_default_pixels(rectangle, partial_pixel_loader) |  |
| get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) |  |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_13) |    |
| [get_file_format(file_path)](#get_file_format_file_path_14) |    |
| [get_file_format(stream)](#get_file_format_stream_15) |    |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_16) |    |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_17) |    |
| [get_modify_date(use_default)](#get_modify_date_use_default_18) |    |
| [get_original_options()](#get_original_options__19) |    |
| [get_pixel(x, y)](#get_pixel_x_y_20) |    |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_21) |    |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_22) |    |
| [get_skew_angle()](#get_skew_angle__23) |    |
| grayscale() |  |
| [load(file_path)](#load_file_path_24) |    |
| [load(file_path, load_options)](#load_file_path_load_options_25) |    |
| [load(stream)](#load_stream_26) |    |
| [load(stream, load_options)](#load_stream_load_options_27) |    |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_28) |    |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_29) |    |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_30) |    |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_31) |    |
| [load_contents(options)](#load_contents_options_32) | Ruft die eingebetteten oder verknüpften Bildinhalte der Smart‑Object‑Ebene ab. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33) | Lädt 32‑Bit‑ARGB‑Pixel teilweise (nach Blöcken). |
| load_partial_pixels(desired_rectangle, pixel_loader) |  |
| [load_pixels(rectangle)](#load_pixels_rectangle_34) |    |
| load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) |  |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_35) | Lädt Rohdaten. |
| merge_layer_to(layer_to_merge_into) |  |
| [new_smart_object_via_copy()](#new_smart_object_via_copy__36) | Erstellt eine neue Smart‑Object‑Ebene, indem diese kopiert wird.<br/>            Reproduziert die Funktionalität `Layer -&gt; Smart Objects -&gt; New Smart Object via Copy` von Adobe� Photoshop�.<br/>            Hinweis: Sie ist nur für eingebettete Smart Objects aktiviert, da das eingebettete Bild ebenfalls kopiert wird.<br/>            Wenn Sie das eingebettete Bild teilen möchten, verwenden Sie die Methode [SmartObjectLayer.duplicate_layer()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/). |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_37) |    |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_38) |    |
| [relink_to_file(linked_path)](#relink_to_file_linked_path_39) | Verknüpft das verknüpfte Smart‑Object erneut mit einer neuen Datei.<br/>            Es ist nicht nötig, danach die Methode UpdateModifiedContent aufzurufen. |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| [replace_contents(image)](#replace_contents_image_40) | Ersetzt die in der Smart‑Object‑Ebene eingebetteten Smart‑Object‑Inhalte. |
| [replace_contents(image, resolution)](#replace_contents_image_resolution_41) | Ersetzt die in der Smart‑Object‑Ebene eingebetteten Smart‑Object‑Inhalte. |
| [replace_contents(linked_path)](#replace_contents_linked_path_42) | Ersetzt die Inhalte durch eine Datei.<br/>            Es ist nicht nötig, danach die Methode UpdateModifiedContent aufzurufen. |
| [replace_contents(linked_path, resolution)](#replace_contents_linked_path_resolution_43) | Ersetzt die Inhalte durch eine Datei.<br/>            Es ist nicht nötig, danach die Methode UpdateModifiedContent aufzurufen. |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| resize(new_width, new_height) |  |
| resize(new_width, new_height, resize_type) |  |
| resize(new_width, new_height, settings) |  |
| resize_height_proportionally(new_height) |  |
| resize_height_proportionally(new_height, resize_type) |  |
| resize_height_proportionally(new_height, settings) |  |
| resize_width_proportionally(new_width) |  |
| resize_width_proportionally(new_width, resize_type) |  |
| resize_width_proportionally(new_width, settings) |  |
| rotate(angle) |  |
| rotate(angle, resize_proportionally, background_color) |  |
| rotate_flip(rotate_flip_type) |  |
| save() |  |
| save(file_path) |  |
| save(file_path, options) |  |
| save(file_path, options, bounds_rectangle) |  |
| save(file_path, over_write) |  |
| save(stream) |  |
| save(stream, options_base) |  |
| save(stream, options_base, bounds_rectangle) |  |
| save_argb_32_pixels(rectangle, pixels) |  |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| save_pixels(rectangle, pixels) |  |
| save_raw_data(data, data_offset, rectangle, raw_data_settings) |  |
| set_argb_32_pixel(x, y, argb_32_color) |  |
| set_palette(palette, update_colors) |  |
| set_pixel(x, y, color) |  |
| set_resolution(dpi_x, dpi_y) |  |
| [shallow_copy()](#shallow_copy__44) |    |
| [to_bitmap()](#to_bitmap__45) |    |
| update_modified_content() | Aktualisiert den Bild‑Cache der SmartObject‑Ebene mit dem geänderten Inhalt. |
| write_argb_32_scan_line(scan_line_index, argb_32_pixels) |  |
| write_scan_line(scan_line_index, pixels) |  |


### Constructor: SmartObjectLayer(stream) {#SmartObjectLayer_stream_1}


```
 SmartObjectLayer(stream) 
```

Initialisiert eine neue Instanz der [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream der Elemente |

### Method: can_load(file_path)  [static] {#can_load_file_path_1}


```
 can_load(file_path) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool |  |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


```
 can_load(file_path, load_options) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool |  |


### Method: can_load(stream)  [static] {#can_load_stream_3}


```
 can_load(stream) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool |  |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


```
 can_load(stream, load_options) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool |  |


### Method: can_save(options) {#can_save_options_5}


```
 can_save(options) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool |  |


### Method: convert_to_linked(linked_path) {#convert_to_linked_linked_path_6}


```
 convert_to_linked(linked_path) 
```

Konvertiert dieses eingebettete Smart-Objekt in ein verknüpftes Smart-Objekt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| linked_path | string | Der verknüpfte Pfad. |

### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_7}


```
 create(image_options, width, height) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |
| width | int |  |
| height | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: duplicate_layer() {#duplicate_layer__8}


```
 duplicate_layer() 
```

Erstellt eine neue Smart‑Object‑Ebene, indem diese kopiert wird.<br/>            Hinweis: Bei eingebetteten Smart Objects wird das eingebettete Bild gemeinsam genutzt.<br/>            Wenn Sie das eingebettete Bild kopieren möchten, verwenden Sie die Methode [SmartObjectLayer.new_smart_object_via_copy()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/).

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | Die geklonte [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) Instanz. |


### Method: export_contents(file_path) {#export_contents_file_path_9}


```
 export_contents(file_path) 
```

Exportiert die eingebetteten oder verknüpften Inhalte in eine Datei.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Exportdateipfad. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_10}


```
 get_argb_32_pixel(x, y) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int |  |
| y | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int |  |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_11}


```
 get_default_argb_32_pixels(rectangle) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int |  |


### Method: get_default_options(args) {#get_default_options_args_12}


```
 get_default_options(args) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| args | object |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |


### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_13}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| byte |  |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_14}


```
 get_file_format(file_path) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) |  |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_15}


```
 get_file_format(stream) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) |  |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_16}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| pixels | int |  |
| width | int |  |
| height | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_17}


```
 get_fitting_rectangle(rectangle, width, height) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| width | int |  |
| height | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_18}


```
 get_modify_date(use_default) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| use_default | bool |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| datetime |  |


### Method: get_original_options() {#get_original_options__19}


```
 get_original_options() 
```

  

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |


### Method: get_pixel(x, y) {#get_pixel_x_y_20}


```
 get_pixel(x, y) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int |  |
| y | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) |  |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_21}


```
 get_proportional_height(width, height, new_width) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int |  |
| height | int |  |
| new_width | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int |  |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_22}


```
 get_proportional_width(width, height, new_height) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int |  |
| height | int |  |
| new_height | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int |  |


### Method: get_skew_angle() {#get_skew_angle__23}


```
 get_skew_angle() 
```

  

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_24}


```
 load(file_path) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_25}


```
 load(file_path, load_options) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(stream)  [static] {#load_stream_26}


```
 load(stream) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_27}


```
 load(stream, load_options) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_28}


```
 load_argb_32_pixels(rectangle) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int |  |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_29}


```
 load_argb_64_pixels(rectangle) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| long |  |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_30}


```
 load_cmyk_32_pixels(rectangle) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int |  |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_31}


```
 load_cmyk_pixels(rectangle) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) |  |


### Method: load_contents(options) {#load_contents_options_32}


```
 load_contents(options) 
```

Ruft die eingebetteten oder verknüpften Bildinhalte der Smart‑Object‑Ebene ab.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Die Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Das geladene [Image](/psd/python-net/aspose.psd/image/) Smart-Objekt-Instanz. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Lädt 32‑Bit‑ARGB‑Pixel teilweise (nach Blöcken).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, aus dem Pixel geladen werden. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Der partielle Pixel-Lader. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_34}


```
 load_pixels(rectangle) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) |  |


### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_35}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Lädt Rohdaten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, aus dem Rohdaten geladen werden. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Die Rohdaten-Einstellungen, die für geladene Daten verwendet werden. Hinweis: Wenn Daten nicht im angegebenen Format vorliegen, wird eine Datenkonvertierung durchgeführt. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Der Rohdaten-Lader. |

### Method: new_smart_object_via_copy() {#new_smart_object_via_copy__36}


```
 new_smart_object_via_copy() 
```

Erstellt eine neue Smart‑Object‑Ebene, indem diese kopiert wird.<br/>            Reproduziert die Funktionalität `Layer -&gt; Smart Objects -&gt; New Smart Object via Copy` von Adobe� Photoshop�.<br/>            Hinweis: Sie ist nur für eingebettete Smart Objects aktiviert, da das eingebettete Bild ebenfalls kopiert wird.<br/>            Wenn Sie das eingebettete Bild teilen möchten, verwenden Sie die Methode [SmartObjectLayer.duplicate_layer()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/).

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | Die geklonte [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) Instanz. |


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_37}


```
 read_argb_32_scan_line(scan_line_index) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scan_line_index | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int |  |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_38}


```
 read_scan_line(scan_line_index) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scan_line_index | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) |  |


### Method: relink_to_file(linked_path) {#relink_to_file_linked_path_39}


```
 relink_to_file(linked_path) 
```

Verknüpft das verknüpfte Smart‑Object erneut mit einer neuen Datei.<br/>            Es ist nicht nötig, danach die Methode UpdateModifiedContent aufzurufen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| linked_path | string | Der verknüpfte Pfad. |

### Method: replace_contents(image) {#replace_contents_image_40}


```
 replace_contents(image) 
```

Ersetzt die in der Smart‑Object‑Ebene eingebetteten Smart‑Object‑Inhalte.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Das Bild. |

### Method: replace_contents(image, resolution) {#replace_contents_image_resolution_41}


```
 replace_contents(image, resolution) 
```

Ersetzt die in der Smart‑Object‑Ebene eingebetteten Smart‑Object‑Inhalte.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Das Bild. |
| resolution | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | Die Auflösungseinstellungen. Wenn null, wird die Bildauflösung verwendet. |

### Method: replace_contents(linked_path) {#replace_contents_linked_path_42}


```
 replace_contents(linked_path) 
```

Ersetzt die Inhalte durch eine Datei.<br/>            Es ist nicht nötig, danach die Methode UpdateModifiedContent aufzurufen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| linked_path | string | Der verknüpfte Pfad. |

### Method: replace_contents(linked_path, resolution) {#replace_contents_linked_path_resolution_43}


```
 replace_contents(linked_path, resolution) 
```

Ersetzt die Inhalte durch eine Datei.<br/>            Es ist nicht nötig, danach die Methode UpdateModifiedContent aufzurufen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| linked_path | string | Der verknüpfte Pfad. |
| resolution | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | Die Auflösungseinstellungen. Wenn null, wird die Bildauflösung verwendet. |

### Method: shallow_copy() {#shallow_copy__44}


```
 shallow_copy() 
```

  

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) |  |


### Method: to_bitmap() {#to_bitmap__45}


```
 to_bitmap() 
```

  

**Returns**

| Typ | Beschreibung |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


