---
title: "RasterImage Klasse"
type: docs
weight: 3740
url: /de/python-net/aspose.psd/rasterimage/
---

**Summary:** Represents a raster image supporting raster graphics operations.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RasterImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, Image

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die Palette automatisch angepasst wird. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Liest oder setzt einen Wert für die Hintergrundfarbe. |
| bits_per_pixel | int | r | Liest die Bits‑pro‑Pixel‑Anzahl des Bildes. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Liest die Bildgrenzen. |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Liest den [Image](/psd/python-net/aspose.psd/image/)‑Container. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Liest den Datenstrom des Objekts. |
| disposed | bool | r | Ruft einen Wert ab, der angibt, ob diese Instanz freigegeben wurde. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Liest einen Wert des Dateiformats |
| has_alpha | bool | r | Liest einen Wert, der angibt, ob diese Instanz Alpha enthält. |
| has_background_color | bool | r/w | Liest oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| has_transparent_color | bool | r/w | Liest einen Wert, der angibt, ob das Bild eine transparente Farbe hat. |
| height | int | r | Liest die Bildhöhe. |
| horizontal_resolution | double | r/w | Liest oder setzt die horizontale Auflösung (in Pixel pro Zoll) dieses [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| image_opacity | float | r | Liest die Deckkraft dieses Bildes. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Liest oder setzt den Interrupt‑Monitor. |
| is_cached | bool | r | Liest einen Wert, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist. |
| is_raw_data_available | bool | r | Liest einen Wert, der angibt, ob das Laden von Rohdaten verfügbar ist. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Liest oder setzt die Farbpalette. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| premultiply_components | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die Bildkomponenten vor multipliziert werden müssen. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | Liest oder setzt den benutzerdefinierten Farbkonverter |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Liest das Rohdatenformat. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Liest die aktuellen Rohdaten‑Einstellungen. Hinweis: Beim Verwenden dieser Einstellungen werden die Daten ohne Konvertierung geladen. |
| raw_fallback_index | int | r/w | Liest oder setzt den Ausweichindex, der verwendet wird, wenn der Palettenindex außerhalb des Bereichs liegt |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | Liest oder setzt den indizierten Farbkonverter |
| raw_line_size | int | r | Liest die Rohzeilengröße in Bytes. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Liest die Bildgröße. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Liest die transparente Farbe des Bildes. |
| update_xmp_data | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die XMP-Metadaten aktualisiert werden sollen. |
| use_palette | bool | r | Liest einen Wert, der angibt, ob die Bildpalette verwendet wird. |
| use_raw_data | bool | r/w | Liest oder setzt einen Wert, der angibt, ob Rohdatenladen verwendet werden soll, wenn das Rohdatenladen verfügbar ist. |
| vertical_resolution | double | r/w | Liest oder setzt die vertikale Auflösung in Pixel pro Zoll dieses [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| width | int | r | Liest die Bildbreite. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Liest oder setzt die XMP-Metadaten. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| adjust_brightness(brightness) |  |
| adjust_contrast(contrast) |  |
| adjust_gamma(gamma) |  |
| adjust_gamma(gamma_red, gamma_green, gamma_blue) |  |
| binarize_bradley(brightness_difference) |  |
| binarize_bradley(brightness_difference, window_size) |  |
| binarize_fixed(threshold) |  |
| binarize_otsu() |  |
| cache_data() | Zwischenspeichert die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) durchgeführt werden. |
| [can_load(file_path)](#can_load_file_path_1) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet. |
| [can_load(stream)](#can_load_stream_3) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann. |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann und optional die angegebenen <paramref name=\"loadOptions\" /> verwendet. |
| [can_save(options)](#can_save_options_5) | Bestimmt, ob das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen repräsentiert wird, gespeichert werden kann. |
| [create(image_options, width, height)](#create_image_options_width_height_6) | Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| crop(rectangle) |  |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_7) | Führt Dithering am aktuellen Bild aus. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_8) | Führt Dithering am aktuellen Bild aus. |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_9) | Liest ein 32‑Bit‑ARGB‑Pixel des Bildes. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_10) | Liest das Standard‑32‑Bit‑ARGB‑Pixelarray. |
| [get_default_options(args)](#get_default_options_args_11) | Liest die Standardoptionen. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_12) | Liest das Standard‑Pixelarray unter Verwendung des partiellen Pixel‑Loaders. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_13) | Ermittelt das Standard‑Rohdaten‑Array mithilfe des partiellen Pixel‑Loaders. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_14) | Ermittelt das Standard‑Rohdaten‑Array. |
| [get_file_format(file_path)](#get_file_format_file_path_15) | Ermittelt das Dateiformat. |
| [get_file_format(stream)](#get_file_format_stream_16) | Ermittelt das Dateiformat. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_17) | Ermittelt das Rechteck, das zum aktuellen Bild passt. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_18) | Ermittelt das Rechteck, das zum aktuellen Bild passt. |
| [get_modify_date(use_default)](#get_modify_date_use_default_19) | Ermittelt das Datum und die Uhrzeit, zu der das Ressourcen‑Bild zuletzt geändert wurde. |
| [get_original_options()](#get_original_options__20) | Ermittelt die Optionen basierend auf den ursprünglichen Dateieinstellungen.<br/>            Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen.<br/>            Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) Methode speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt.<br/>            Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und sie<br/>            an die [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) Methode als zweiten Parameter zu übergeben. |
| [get_pixel(x, y)](#get_pixel_x_y_21) | Ermittelt einen Bildpixel.<br/>            Leistungshinweis: Vermeiden Sie die Verwendung dieser Methode, um über alle Bildpixel zu iterieren, da dies zu erheblichen Leistungsproblemen führen kann.<br/>            Für eine effizientere Pixelmanipulation verwenden Sie die `LoadArgb32Pixels`‑Methode, um das gesamte Pixel‑Array gleichzeitig abzurufen. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_22) | Ermittelt eine proportionale Höhe. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_23) | Ermittelt eine proportionale Breite. |
| [get_skew_angle()](#get_skew_angle__24) |    |
| grayscale() |  |
| [load(file_path)](#load_file_path_25) | Lädt ein neues Bild aus der angegebenen Datei. |
| [load(file_path, load_options)](#load_file_path_load_options_26) | Lädt ein neues Bild aus der angegebenen Datei. |
| [load(stream)](#load_stream_27) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load(stream, load_options)](#load_stream_load_options_28) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_29) | Lädt 32‑Bit‑ARGB‑Pixel. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_30) | Lädt 64‑Bit‑ARGB‑Pixel. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_31) | Lädt Pixel im CMYK‑Format. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_32) | Lädt Pixel im CMYK‑Format.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/)‑Methode. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33) | Lädt 32-Bit-ARGB-Pixel teilweise in Paketen. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_34) | Lädt Pixel teilweise in Paketen. |
| [load_pixels(rectangle)](#load_pixels_rectangle_35) | Lädt Pixel. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_36) | Lädt Rohdaten. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_37) | Lädt Rohdaten. |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_38) | Liest die gesamte Scan‑Zeile anhand des angegebenen Scan‑Zeilen‑Index. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_39) | Liest die gesamte Scan‑Zeile anhand des angegebenen Scan‑Zeilen‑Index. |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| [resize(new_width, new_height)](#resize_new_width_new_height_40) | Skaliert das Bild. Der Standard‑[ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wird verwendet. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_41) | Skaliert das Bild. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_42) | Skaliert das Bild. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_43) | Skaliert die Höhe proportional. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_44) | Skaliert die Höhe proportional. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_45) | Skaliert die Höhe proportional. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_46) | Skaliert die Breite proportional. Der Standard‑[ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wird verwendet. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_47) | Skaliert die Breite proportional. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_48) | Skaliert die Breite proportional. |
| rotate(angle) |  |
| rotate(angle, resize_proportionally, background_color) |  |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_49) | Dreht, spiegelt oder dreht und spiegelt das Bild. |
| save() | Speichert die Bilddaten in den zugrunde liegenden Stream. |
| [save(file_path)](#save_file_path_50) | Speichert die Objektdaten am angegebenen Dateipfad. |
| [save(file_path, options)](#save_file_path_options_51) | Speichert die Objektdaten am angegebenen Dateipfad im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_52) | Speichert die Objektdaten am angegebenen Dateipfad im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(file_path, over_write)](#save_file_path_over_write_53) | Speichert die Objektdaten am angegebenen Dateipfad. |
| [save(stream)](#save_stream_54) | Speichert die Objektdaten in den angegebenen Stream. |
| [save(stream, options_base)](#save_stream_options_base_55) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_56) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_57) | Speichert die 32‑Bit‑ARGB‑Pixel. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_58) | Speichert die Pixel. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_59) | Speichert die Rohdaten. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_60) | Setzt ein 32‑Bit‑ARGB‑Pixel des Bildes für die angegebene Position. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_61) | Setzt die Bildpalette. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_62) | Setzt ein Bildpixel für die angegebene Position. |
| set_resolution(dpi_x, dpi_y) |  |
| [to_bitmap()](#to_bitmap__63) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_64) | Schreibt die gesamte Scanzeile an den angegebenen Scanzeilen‑Index. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_65) | Schreibt die gesamte Scanzeile an den angegebenen Scanzeilen‑Index. |


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


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


### Method: can_load(stream)  [static] {#can_load_stream_3}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


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


### Method: can_save(options) {#can_save_options_5}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_6}


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


### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_7}


```
 dither(dithering_method, bits_count) 
```

Führt Dithering am aktuellen Bild aus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | Die Dithering-Methode. |
| bits_count | int | Die endgültige Bitanzahl für das Dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_8}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Führt Dithering am aktuellen Bild aus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | Die Dithering-Methode. |
| bits_count | int | Die endgültige Bitanzahl für das Dithering. |
| custom_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Die benutzerdefinierte Palette für das Dithering. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_9}


```
 get_argb_32_pixel(x, y) 
```

Liest ein 32‑Bit‑ARGB‑Pixel des Bildes.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Position des Pixels. |
| y | int | Die y-Position des Pixels. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Der 32-Bit-ARGB-Pixel für die angegebene Position. |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_10}


```
 get_default_argb_32_pixels(rectangle) 
```

Liest das Standard‑32‑Bit‑ARGB‑Pixelarray.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, für das Pixel abgerufen werden sollen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Das Standard-Pixel-Array. |


### Method: get_default_options(args) {#get_default_options_args_11}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_12}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Liest das Standard‑Pixelarray unter Verwendung des partiellen Pixel‑Loaders.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, für das Pixel abgerufen werden sollen. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Der partielle Pixel-Lader. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_13}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

Ermittelt das Standard‑Rohdaten‑Array mithilfe des partiellen Pixel‑Loaders.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, für das Pixel abgerufen werden sollen. |
| partial_raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Der partielle Rohdaten-Lader. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Die Rohdaten-Einstellungen. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_14}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

Ermittelt das Standard‑Rohdaten‑Array.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, für das Rohdaten abgerufen werden sollen. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Die Rohdaten-Einstellungen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| byte | Das Standard-Rohdaten-Array. |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_15}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_16}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_17}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_18}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_19}


```
 get_modify_date(use_default) 
```

Ermittelt das Datum und die Uhrzeit, zu der das Ressourcen‑Bild zuletzt geändert wurde.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| use_default | bool | Wenn auf <c>true</c> gesetzt, wird die Information aus FileInfo als Standardwert verwendet. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| datetime | Das Datum und die Uhrzeit, wann das Ressourcenbild zuletzt geändert wurde. |


### Method: get_original_options() {#get_original_options__20}


```
 get_original_options() 
```

Ermittelt die Optionen basierend auf den ursprünglichen Dateieinstellungen.<br/>            Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen.<br/>            Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) Methode speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt.<br/>            Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und sie<br/>            an die [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) Methode als zweiten Parameter zu übergeben.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Optionen basierend auf den ursprünglichen Dateieinstellungen. |


### Method: get_pixel(x, y) {#get_pixel_x_y_21}


```
 get_pixel(x, y) 
```

Ermittelt einen Bildpixel.<br/>            Leistungshinweis: Vermeiden Sie die Verwendung dieser Methode, um über alle Bildpixel zu iterieren, da dies zu erheblichen Leistungsproblemen führen kann.<br/>            Für eine effizientere Pixelmanipulation verwenden Sie die `LoadArgb32Pixels`‑Methode, um das gesamte Pixel‑Array gleichzeitig abzurufen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Position des Pixels. |
| y | int | Die y-Position des Pixels. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Die Pixel‑Farbe für die angegebene Position. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_22}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_23}


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


### Method: get_skew_angle() {#get_skew_angle__24}


```
 get_skew_angle() 
```

  

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_25}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_26}


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


### Method: load(stream)  [static] {#load_stream_27}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_28}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_29}


```
 load_argb_32_pixels(rectangle) 
```

Lädt 32‑Bit‑ARGB‑Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, aus dem Pixel geladen werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Das geladene 32‑Bit‑ARGB‑Pixel‑Array. |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_30}


```
 load_argb_64_pixels(rectangle) 
```

Lädt 64‑Bit‑ARGB‑Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, aus dem Pixel geladen werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| long | Das geladene 64‑Bit‑ARGB‑Pixel‑Array. |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_31}


```
 load_cmyk_32_pixels(rectangle) 
```

Lädt Pixel im CMYK‑Format.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, aus dem Pixel geladen werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Die geladenen CMYK‑Pixel, dargestellt als 32‑Bit‑Ganzzahlwerte. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_32}


```
 load_cmyk_pixels(rectangle) 
```

Lädt Pixel im CMYK‑Format.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/)‑Methode.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, aus dem Pixel geladen werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Das geladene CMYK‑Pixel‑Array. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Lädt 32-Bit-ARGB-Pixel teilweise in Paketen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das gewünschte Rechteck. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Der 32-Bit-ARGB-Pixel-Lader. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_34}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Lädt Pixel teilweise in Paketen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das gewünschte Rechteck. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | Der Pixel‑Lader. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_35}


```
 load_pixels(rectangle) 
```

Lädt Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, aus dem Pixel geladen werden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Das geladene Pixel‑Array. |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_36}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

Lädt Rohdaten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, aus dem Rohdaten geladen werden. |
| dest_image_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Die Zielbild‑Grenzen. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Die Rohdaten-Einstellungen, die für geladene Daten verwendet werden. Hinweis: Wenn Daten nicht im angegebenen Format vorliegen, wird eine Datenkonvertierung durchgeführt. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Der Rohdaten-Lader. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_37}


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

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_38}


```
 read_argb_32_scan_line(scan_line_index) 
```

Liest die gesamte Scan‑Zeile anhand des angegebenen Scan‑Zeilen‑Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scan_line_index | int | Nullbasierter Index der Scan‑Zeile. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | Das Scan‑Zeilen‑32‑Bit‑ARGB‑Farbwert‑Array. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_39}


```
 read_scan_line(scan_line_index) 
```

Liest die gesamte Scan‑Zeile anhand des angegebenen Scan‑Zeilen‑Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scan_line_index | int | Nullbasierter Index der Scan‑Zeile. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Das Array der Farbwert-Pixel der Scanzeile. |


### Method: resize(new_width, new_height) {#resize_new_width_new_height_40}


```
 resize(new_width, new_height) 
```

Skaliert das Bild. Der Standard‑[ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_41}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_42}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_43}


```
 resize_height_proportionally(new_height) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_44}


```
 resize_height_proportionally(new_height, resize_type) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Typ der Skalierung. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_45}


```
 resize_height_proportionally(new_height, settings) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Die Bildskalierungseinstellungen. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_46}


```
 resize_width_proportionally(new_width) 
```

Skaliert die Breite proportional. Der Standard‑[ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_47}


```
 resize_width_proportionally(new_width, resize_type) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Typ der Skalierung. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_48}


```
 resize_width_proportionally(new_width, settings) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Die Bildskalierungseinstellungen. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_49}


```
 rotate_flip(rotate_flip_type) 
```

Dreht, spiegelt oder dreht und spiegelt das Bild.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Typ der Dreh-Spiegelung. |

### Method: save(file_path) {#save_file_path_50}


```
 save(file_path) 
```

Speichert die Objektdaten am angegebenen Dateipfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Daten des Objekts gespeichert werden. |

### Method: save(file_path, options) {#save_file_path_options_51}


```
 save(file_path, options) 
```

Speichert die Objektdaten am angegebenen Dateipfad im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Optionen. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_52}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_53}


```
 save(file_path, over_write) 
```

Speichert die Objektdaten am angegebenen Dateipfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Daten des Objekts gespeichert werden. |
| over_write | bool | Wenn auf <c>true</c> gesetzt, werden die Dateiinhalte überschrieben, andernfalls wird angehängt. |

### Method: save(stream) {#save_stream_54}


```
 save(stream) 
```

Speichert die Objektdaten in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream, in dem die Daten des Objekts gespeichert werden. |

### Method: save(stream, options_base) {#save_stream_options_base_55}


```
 save(stream, options_base) 
```

Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream, in dem die Bilddaten gespeichert werden. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Speicheroptionen. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_56}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_57}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Speichert die 32‑Bit‑ARGB‑Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, in dem die Pixel gespeichert werden. |
| pixels | int | Das 32-Bit-ARGB-Pixel-Array. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_58}


```
 save_pixels(rectangle, pixels) 
```

Speichert die Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, in dem die Pixel gespeichert werden. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Das Pixel-Array. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_59}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

Speichert die Rohdaten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| data | byte | Die Rohdaten. |
| data_offset | int | Der Start-Offset der Rohdaten. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rohdaten-Rechteck. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Die Rohdaten-Einstellungen, in denen die Daten vorliegen. |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_60}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

Setzt ein 32‑Bit‑ARGB‑Pixel des Bildes für die angegebene Position.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Position des Pixels. |
| y | int | Die y-Position des Pixels. |
| argb_32_color | int | Das 32‑Bit‑ARGB‑Pixel für die angegebene Position. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_61}


```
 set_palette(palette, update_colors) 
```

Setzt die Bildpalette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Die zu setzende Palette. |
| update_colors | bool | Wenn auf <c>true</c> gesetzt, werden die Farben gemäß der neuen Palette aktualisiert; andernfalls bleiben die Farbindizes unverändert. Beachten Sie, dass unveränderte Indizes das Bild beim Laden zum Absturz bringen können, wenn einige Indizes keinen entsprechenden Paletteneintrag haben. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_62}


```
 set_pixel(x, y, color) 
```

Setzt ein Bildpixel für die angegebene Position.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | int | Die x-Position des Pixels. |
| y | int | Die y-Position des Pixels. |
| color | [Color](/psd/python-net/aspose.psd/color) | Die Pixel‑Farbe für die angegebene Position. |

### Method: to_bitmap() {#to_bitmap__63}


```
 to_bitmap() 
```

  

**Returns**

| Typ | Beschreibung |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_64}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Schreibt die gesamte Scanzeile an den angegebenen Scanzeilen‑Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scan_line_index | int | Nullbasierter Index der Scan‑Zeile. |
| argb_32_pixels | int | Das 32‑Bit‑ARGB‑Farben‑Array zum Schreiben. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_65}


```
 write_scan_line(scan_line_index, pixels) 
```

Schreibt die gesamte Scanzeile an den angegebenen Scanzeilen‑Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scan_line_index | int | Nullbasierter Index der Scan‑Zeile. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Das Pixel‑Farben‑Array zum Schreiben. |

