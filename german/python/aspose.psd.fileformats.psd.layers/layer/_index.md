---
title: "Layer Klasse"
type: docs
weight: 930
url: /de/python-net/aspose.psd.fileformats.psd.layers/layer/
---

**Summary:** The psd layer.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.Layer

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Layer()](#Layer__1) | Initialisiert eine neue Instanz der [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) Klasse. Konstruktor für Lazy-Initialisierung. |
| [Layer(bounds, red_bytes, green_bytes, blue_bytes, name)](#Layer_bounds_red_bytes_green_bytes_blue_bytes_name_2) | Initialisiert eine neue Instanz der [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) Klasse aus Byte‑Arrays. |
| [Layer(image, dispose_image)](#Layer_image_dispose_image_3) | Initialisiert eine neue Instanz der [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) Klasse. |
| [Layer(stream)](#Layer_stream_4) | Initialisiert eine neue Instanz der [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| BLEND_SIGNATURE [statisch] | int | r | Stellt die Signatur des Mischmodus dar. |
| LAYER_HEADER_SIZE [statisch] | int | r | Die Größe des Layer‑Headers. |
| auto_adjust_palette | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die Palette automatisch angepasst wird. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Liest oder setzt einen Wert für die Hintergrundfarbe. |
| bits_per_pixel | int | r | Liest die Bits‑pro‑Pixel‑Anzahl des Bildes. |
| blend_clipped_elements | bool | r/w | Liest oder setzt die Überblendung des beschnittenen Elements. |
| blend_mode_key | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Liest oder setzt den Blend‑Modus‑Schlüssel. |
| blend_mode_signature | int | r | Liest die Signatur des Mischmodus. |
| blending_options | [BlendingOptions](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/) | r | Liest die Überblendungsoptionen. |
| bottom | int | r/w | Liest oder setzt die Position der untersten Ebene. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Liefert die Objektgrenzen. |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| channel_information | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r/w | Liest oder setzt die Kanalinformationen. |
| channels_count | ushort | r | Liest die Kanalanzahl der Ebene. |
| clipping | byte | r/w | Liest oder setzt das Ebenen‑Clipping. 0 = Basis, 1 = Nicht‑Basis. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Liest den [Image](/psd/python-net/aspose.psd/image/)‑Container. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Liest den Datenstrom des Objekts. |
| display_name | string | r/w | Liest oder setzt den Anzeigenamen der Ebene. |
| disposed | bool | r | Ruft einen Wert ab, der angibt, ob diese Instanz freigegeben wurde. |
| extra_length | int | r | Liest die Länge der zusätzlichen Ebeneninformationen in Bytes. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Liest einen Wert des Dateiformats |
| fill_opacity | int | r/w | Liest oder setzt die Füll‑Deckkraft. |
| filler | byte | r/w | Liest oder setzt den Ebenen‑Füller. |
| flags | [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags) | r/w | Liest oder setzt die Ebenen‑Flags.<br/>            Bit 0 = Transparenz geschützt;<br/>            Bit 1 = sichtbar;<br/>            Bit 2 = veraltet;<br/>            Bit 3 = 1 für Photoshop 5.0 und neuer, gibt an, ob Bit 4 nützliche Informationen enthält;<br/>            Bit 4 = Pixeldaten für das Aussehen des Dokuments irrelevant. |
| has_alpha | bool | r | Liest einen Wert, der angibt, ob diese Instanz Alpha enthält. |
| has_background_color | bool | r/w | Liest oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| has_transparent_color | bool | r/w | Liest einen Wert, der angibt, ob das Bild eine transparente Farbe hat. |
| height | int | r | Liest die Bildhöhe. |
| horizontal_resolution | double | r/w | Liest oder setzt die horizontale Auflösung (in Pixel pro Zoll) dieses [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| image_opacity | float | r | Liest die Deckkraft dieses Bildes. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Liest oder setzt den Interrupt‑Monitor. |
| is_cached | bool | r | Liest einen Wert, der angibt, ob Bilddaten derzeit zwischengespeichert sind. |
| is_raw_data_available | bool | r | Liest einen Wert, der angibt, ob das Laden von Rohdaten unterstützt wird. |
| is_visible | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die Ebene sichtbar ist |
| is_visible_in_group | bool | r | Liest einen Wert, der angibt, ob diese Instanz in der Gruppe sichtbar ist (wenn die Ebene nicht in einer Gruppe ist, bedeutet das die Root-Gruppe). |
| layer_blending_ranges_data | [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata) | r/w | Liest oder setzt die Daten der Mischbereiche der Ebene. |
| layer_creation_date_time | datetime | r/w | Liest oder setzt das Erstellungsdatum und die -zeit der Ebene. |
| layer_lock | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | r/w | Gets or sets the layer lock.<br/>            Note that if flag LayerFlags.TransparencyProtected is set it will be overwritten by layer lock flag.<br/>            To return LayerFlags.TransparencyProtected flag need to apply for layer option layer.Flags | = LayerFlags.TransparencyProtected |
| layer_mask_data | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | r/w | Liest oder setzt die Maskendaten der Ebene. |
| layer_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | r | Liest die Optionen der Ebene. |
| left | int | r/w | Liest oder setzt die linke Position der Ebene. |
| Länge | int | r | Liest die Gesamtlänge der Ebene in Bytes. |
| name | string | r/w | Liest oder setzt den Namen der Ebene. |
| Deckkraft | byte | r/w | Liest oder setzt die Deckkraft der Ebene. 0 = transparent, 255 = undurchsichtig. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Liest oder setzt die Farbpalette. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| premultiply_components | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die Bildkomponenten vor multipliziert werden müssen. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | Liest oder setzt den benutzerdefinierten Farbkonverter |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Liest das Rohdatenformat. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Liest die aktuellen Rohdaten‑Einstellungen. Hinweis: Beim Verwenden dieser Einstellungen werden die Daten ohne Konvertierung geladen. |
| raw_fallback_index | int | r/w | Liest oder setzt den Ausweichindex, der verwendet wird, wenn der Palettenindex außerhalb des Bereichs liegt |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | Liest oder setzt den indizierten Farbkonverter |
| raw_line_size | int | r | Liest die Rohzeilengröße in Bytes. |
| resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r/w | Liest oder setzt die Ressourcen der Ebene. |
| rechts | int | r/w | Liest oder setzt die rechte Position der Ebene. |
| sheet_color_highlight | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | r/w | Liest oder setzt die dekorative Blattfarb-Hervorhebung in der Ebenenliste |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Ruft die Objektgröße ab. |
| oben | int | r/w | Liest oder setzt die obere Position der Ebene. |
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
| [add_layer_mask(layer_mask)](#add_layer_mask_layer_mask_1) | Fügt die Maske zur aktuellen Ebene hinzu. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_2) | Anpassung der Helligkeit für das Bild. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_3) | Bildkontrast |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_4) | Gammakorrektur eines Bildes. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_5) | Gammakorrektur eines Bildes. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_6) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus mittels Integralbild‑Schwellenwert. |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_7) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus mittels Integralbild‑Schwellenwert. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_8) | Binarisierung eines Bildes mit vordefiniertem Schwellenwert |
| binarize_otsu() | Binarisierung eines Bildes mit Otsu‑Schwellenwert |
| cache_data() | Zwischenspeichert die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) durchgeführt werden. |
| [can_load(file_path)](#can_load_file_path_9) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_10) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet. |
| [can_load(stream)](#can_load_stream_11) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann. |
| [can_load(stream, load_options)](#can_load_stream_load_options_12) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann und optional die angegebenen <paramref name=\"loadOptions\" /> verwendet. |
| [can_save(options)](#can_save_options_13) | Bestimmt, ob das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen repräsentiert wird, gespeichert werden kann. |
| [create(image_options, width, height)](#create_image_options_width_height_14) | Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_15) | Zuschneiden des Bildes. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_16) | Führt Dithering am aktuellen Bild aus. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_17) | Führt Dithering am aktuellen Bild aus. |
| [draw_image(location, image)](#draw_image_location_image_18) | Zeichnet das Bild auf die Ebene. |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_19) | Liest ein 32‑Bit‑ARGB‑Pixel des Bildes. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_20) | Liest das Standard‑32‑Bit‑ARGB‑Pixelarray. |
| [get_default_options(args)](#get_default_options_args_21) | Liest die Standardoptionen. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_22) | Liest das Standard‑Pixelarray unter Verwendung des partiellen Pixel‑Loaders. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_23) | Ermittelt das Standard‑Rohdaten‑Array mithilfe des partiellen Pixel‑Loaders. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_24) | Ermittelt das Standard‑Rohdaten‑Array. |
| [get_file_format(file_path)](#get_file_format_file_path_25) | Ermittelt das Dateiformat. |
| [get_file_format(stream)](#get_file_format_stream_26) | Ermittelt das Dateiformat. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_27) | Ermittelt das Rechteck, das zum aktuellen Bild passt. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_28) | Ermittelt das Rechteck, das zum aktuellen Bild passt. |
| [get_modify_date(use_default)](#get_modify_date_use_default_29) | Ermittelt das Datum und die Uhrzeit, zu der das Ressourcen‑Bild zuletzt geändert wurde. |
| [get_original_options()](#get_original_options__30) | Ermittelt die Optionen basierend auf den ursprünglichen Dateieinstellungen.<br/>            Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen.<br/>            Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) Methode speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt.<br/>            Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und sie<br/>            an die [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) Methode als zweiten Parameter zu übergeben. |
| [get_pixel(x, y)](#get_pixel_x_y_31) | Ermittelt einen Bildpixel.<br/>            Leistungshinweis: Vermeiden Sie die Verwendung dieser Methode, um über alle Bildpixel zu iterieren, da dies zu erheblichen Leistungsproblemen führen kann.<br/>            Für eine effizientere Pixelmanipulation verwenden Sie die `LoadArgb32Pixels`‑Methode, um das gesamte Pixel‑Array gleichzeitig abzurufen. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_32) | Ermittelt eine proportionale Höhe. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_33) | Ermittelt eine proportionale Breite. |
| [get_skew_angle()](#get_skew_angle__34) |    |
| grayscale() | Transformation eines Bildes in seine Graustufen‑Darstellung |
| [load(file_path)](#load_file_path_35) | Lädt ein neues Bild aus der angegebenen Datei. |
| [load(file_path, load_options)](#load_file_path_load_options_36) | Lädt ein neues Bild aus der angegebenen Datei. |
| [load(stream)](#load_stream_37) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load(stream, load_options)](#load_stream_load_options_38) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_39) | Lädt 32‑Bit‑ARGB‑Pixel. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_40) | Lädt 64‑Bit‑ARGB‑Pixel. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_41) | Lädt Pixel im CMYK‑Format. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_42) | Lädt Pixel im CMYK‑Format.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/)‑Methode. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_43) | Lädt 32‑Bit‑ARGB‑Pixel teilweise (nach Blöcken). |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_44) | Lädt Pixel teilweise in Paketen. |
| [load_pixels(rectangle)](#load_pixels_rectangle_45) | Lädt Pixel. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_46) | Lädt Rohdaten. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_47) | Lädt Rohdaten. |
| [merge_layer_to(layer_to_merge_into)](#merge_layer_to_layer_to_merge_into_48) | Führt die Ebene mit der angegebenen Ebene zusammen |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_49) | Liest die gesamte Scan‑Zeile anhand des angegebenen Scan‑Zeilen‑Index. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_50) | Liest die gesamte Scan‑Zeile anhand des angegebenen Scan‑Zeilen‑Index. |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| [resize(new_width, new_height)](#resize_new_width_new_height_51) | Skaliert das Bild. Der Standard‑[ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wird verwendet. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_52) | Skaliert das Bild. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_53) | Skaliert das Bild. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_54) | Skaliert die Höhe proportional. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_55) | Skaliert die Höhe proportional. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_56) | Skaliert die Höhe proportional. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_57) | Skaliert die Breite proportional. Der Standard‑[ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wird verwendet. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_58) | Skaliert die Breite proportional. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_59) | Skaliert die Breite proportional. |
| rotate(angle) |  |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_60) | Bild um das Zentrum drehen. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_61) | Dreht, spiegelt oder dreht und spiegelt das Bild. |
| save() | Speichert die Bilddaten in den zugrunde liegenden Stream. |
| [save(file_path)](#save_file_path_62) | Speichert die Objektdaten am angegebenen Dateipfad. |
| [save(file_path, options)](#save_file_path_options_63) | Speichert die Objektdaten am angegebenen Dateipfad im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_64) | Speichert die Objektdaten am angegebenen Dateipfad im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(file_path, over_write)](#save_file_path_over_write_65) | Speichert die Objektdaten am angegebenen Dateipfad. |
| [save(stream)](#save_stream_66) | Speichert die Objektdaten in den angegebenen Stream. |
| [save(stream, options_base)](#save_stream_options_base_67) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_68) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_69) | Speichert die 32‑Bit‑ARGB‑Pixel. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_70) | Speichert Pixel (formatspezifische Methode). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_71) | Speichert die Rohdaten. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_72) | Setzt ein 32‑Bit‑ARGB‑Pixel des Bildes für die angegebene Position. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_73) | Setzt die Bildpalette. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_74) | Setzt ein Bildpixel für die angegebene Position. |
| set_resolution(dpi_x, dpi_y) |  |
| [shallow_copy()](#shallow_copy__75) | Erstellt eine flache Kopie der aktuellen Ebene.<br/>            Bitte <see href="https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx" /> für eine Erklärung. |
| [to_bitmap()](#to_bitmap__76) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_77) | Schreibt die gesamte Scanzeile an den angegebenen Scanzeilen‑Index. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_78) | Schreibt die gesamte Scanzeile an den angegebenen Scanzeilen‑Index. |


### Constructor: Layer() {#Layer__1}


```
 Layer() 
```

Initialisiert eine neue Instanz der [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) Klasse. Konstruktor für Lazy-Initialisierung.

### Constructor: Layer(bounds, red_bytes, green_bytes, blue_bytes, name) {#Layer_bounds_red_bytes_green_bytes_blue_bytes_name_2}


```
 Layer(bounds, red_bytes, green_bytes, blue_bytes, name) 
```

Initialisiert eine neue Instanz der [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) Klasse aus Byte‑Arrays.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Die Ebenengrenzen. |
| red_bytes | byte | Die roten Bytes. |
| green_bytes | byte | Die grünen Bytes. |
| blue_bytes | byte | Die blauen Bytes. |
| name | string | Der Ebenenname. |

### Constructor: Layer(image, dispose_image) {#Layer_image_dispose_image_3}


```
 Layer(image, dispose_image) 
```

Initialisiert eine neue Instanz der [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Das Bild. |
| dispose_image | bool | wenn gesetzt auf <c>true</c> [dispose image]. |

### Constructor: Layer(stream) {#Layer_stream_4}


```
 Layer(stream) 
```

Initialisiert eine neue Instanz der [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Bild-Stream |

### Method: add_layer_mask(layer_mask) {#add_layer_mask_layer_mask_1}


```
 add_layer_mask(layer_mask) 
```

Fügt die Maske zur aktuellen Ebene hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer_mask | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | Die Ebenenmaske. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_2}


```
 adjust_brightness(brightness) 
```

Anpassung der Helligkeit für das Bild.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Helligkeit | int | Helligkeitswert. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_3}


```
 adjust_contrast(contrast) 
```

Bildkontrast

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Kontrast | float | Kontrastwert (im Bereich [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_4}


```
 adjust_gamma(gamma) 
```

Gammakorrektur eines Bildes.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Gamma | float | Gamma‑Koeffizient für Rot-, Grün‑ und Blaukanäle |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_5}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Gammakorrektur eines Bildes.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| gamma_red | float | Gamma‑Koeffizient für den Rotkanal |
| gamma_green | float | Gamma‑Koeffizient für den Grünkanal |
| gamma_blue | float | Gamma‑Koeffizient für den Blaukanal |

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_6}


```
 binarize_bradley(brightness_difference) 
```

Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus mittels Integralbild‑Schwellenwert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brightness_difference | double | Der Helligkeitsunterschied zwischen dem Pixel und dem Durchschnitt eines s × s‑Fensters von Pixeln, das um dieses Pixel zentriert ist. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_7}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus mittels Integralbild‑Schwellenwert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brightness_difference | double | Der Helligkeitsunterschied zwischen dem Pixel und dem Durchschnitt eines s × s‑Fensters von Pixeln, das um dieses Pixel zentriert ist. |
| window_size | int | Die Größe des s × s‑Fensters von Pixeln, das um dieses Pixel zentriert ist |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

Binarisierung eines Bildes mit vordefiniertem Schwellenwert

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| threshold | byte | Schwellenwert. Wenn der entsprechende Grauwert eines Pixels größer als der Schwellenwert ist, wird ihm der Wert 255 zugewiesen, sonst 0. |

### Method: can_load(file_path)  [static] {#can_load_file_path_9}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_10}


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


### Method: can_load(stream)  [static] {#can_load_stream_11}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_12}


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


### Method: can_save(options) {#can_save_options_13}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_14}


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


### Method: crop(rectangle) {#crop_rectangle_15}


```
 crop(rectangle) 
```

Zuschneiden des Bildes.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_16}


```
 dither(dithering_method, bits_count) 
```

Führt Dithering am aktuellen Bild aus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | Die Dithering-Methode. |
| bits_count | int | Die endgültige Bitanzahl für das Dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_17}


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

### Method: draw_image(location, image) {#draw_image_location_image_18}


```
 draw_image(location, image) 
```

Zeichnet das Bild auf die Ebene.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | Die Position. |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Das Bild. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_19}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_20}


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


### Method: get_default_options(args) {#get_default_options_args_21}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_22}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Liest das Standard‑Pixelarray unter Verwendung des partiellen Pixel‑Loaders.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, für das Pixel abgerufen werden sollen. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Der partielle Pixel-Lader. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_23}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_24}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_25}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_26}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_27}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_28}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_29}


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


### Method: get_original_options() {#get_original_options__30}


```
 get_original_options() 
```

Ermittelt die Optionen basierend auf den ursprünglichen Dateieinstellungen.<br/>            Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen.<br/>            Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) Methode speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt.<br/>            Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und sie<br/>            an die [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) Methode als zweiten Parameter zu übergeben.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Optionen basierend auf den ursprünglichen Dateieinstellungen. |


### Method: get_pixel(x, y) {#get_pixel_x_y_31}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_32}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_33}


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


### Method: get_skew_angle() {#get_skew_angle__34}


```
 get_skew_angle() 
```

  

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_35}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_36}


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


### Method: load(stream)  [static] {#load_stream_37}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_38}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_39}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_40}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_41}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_42}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_43}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Lädt 32‑Bit‑ARGB‑Pixel teilweise (nach Blöcken).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, aus dem Pixel geladen werden. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Der partielle Pixel-Lader. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_44}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Lädt Pixel teilweise in Paketen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das gewünschte Rechteck. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | Der Pixel‑Lader. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_45}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_46}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_47}


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

### Method: merge_layer_to(layer_to_merge_into) {#merge_layer_to_layer_to_merge_into_48}


```
 merge_layer_to(layer_to_merge_into) 
```

Führt die Ebene mit der angegebenen Ebene zusammen

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer_to_merge_into | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Die Ebene, in die zusammengeführt wird. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_49}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_50}


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


### Method: resize(new_width, new_height) {#resize_new_width_new_height_51}


```
 resize(new_width, new_height) 
```

Skaliert das Bild. Der Standard‑[ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_52}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_53}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_54}


```
 resize_height_proportionally(new_height) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_55}


```
 resize_height_proportionally(new_height, resize_type) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Typ der Skalierung. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_56}


```
 resize_height_proportionally(new_height, settings) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Die Bildskalierungseinstellungen. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_57}


```
 resize_width_proportionally(new_width) 
```

Skaliert die Breite proportional. Der Standard‑[ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_58}


```
 resize_width_proportionally(new_width, resize_type) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Typ der Skalierung. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_59}


```
 resize_width_proportionally(new_width, settings) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Die Bildskalierungseinstellungen. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_60}


```
 rotate(angle, resize_proportionally, background_color) 
```

Bild um das Zentrum drehen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |
| resize_proportionally | bool | Wenn auf <c>true</c> gesetzt, wird die Bildgröße gemäß den Projektionen des gedrehten Rechtecks (Eckpunkte) geändert; andernfalls bleiben die Abmessungen unverändert und nur der Bildinhalt wird rotiert. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | Farbe des Hintergrunds. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_61}


```
 rotate_flip(rotate_flip_type) 
```

Dreht, spiegelt oder dreht und spiegelt das Bild.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Der Rotations-Spiegelungstyp. |

### Method: save(file_path) {#save_file_path_62}


```
 save(file_path) 
```

Speichert die Objektdaten am angegebenen Dateipfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Daten des Objekts gespeichert werden. |

### Method: save(file_path, options) {#save_file_path_options_63}


```
 save(file_path, options) 
```

Speichert die Objektdaten am angegebenen Dateipfad im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Optionen. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_64}


```
 save(file_path, options, bounds_rectangle) 
```

Speichert die Objektdaten am angegebenen Dateipfad im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Optionen. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck der Zielbildgrenzen. Setzen Sie das leere Rechteck, um die Quellgrenzen zu verwenden. |

### Method: save(file_path, over_write) {#save_file_path_over_write_65}


```
 save(file_path, over_write) 
```

Speichert die Objektdaten am angegebenen Dateipfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Daten des Objekts gespeichert werden. |
| over_write | bool | Wenn auf <c>true</c> gesetzt, werden die Dateiinhalte überschrieben, andernfalls wird angehängt. |

### Method: save(stream) {#save_stream_66}


```
 save(stream) 
```

Speichert die Objektdaten in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream, in dem die Daten des Objekts gespeichert werden. |

### Method: save(stream, options_base) {#save_stream_options_base_67}


```
 save(stream, options_base) 
```

Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream, in dem die Bilddaten gespeichert werden. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Speicheroptionen. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_68}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_69}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Speichert die 32‑Bit‑ARGB‑Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, in dem die Pixel gespeichert werden. |
| pixels | int | Das 32-Bit-ARGB-Pixel-Array. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_70}


```
 save_pixels(rectangle, pixels) 
```

Speichert Pixel (formatspezifische Methode).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, in dem die Pixel gespeichert werden. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Das 32-Bit-ARGB-Pixel-Array. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_71}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_72}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_73}


```
 set_palette(palette, update_colors) 
```

Setzt die Bildpalette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Die zu setzende Palette. |
| update_colors | bool | Wenn auf <c>true</c> gesetzt, werden die Farben gemäß der neuen Palette aktualisiert; andernfalls bleiben die Farbindizes unverändert. Beachten Sie, dass unveränderte Indizes das Bild beim Laden zum Absturz bringen können, wenn einige Indizes keinen entsprechenden Paletteneintrag haben. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_74}


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

### Method: shallow_copy() {#shallow_copy__75}


```
 shallow_copy() 
```

Erstellt eine flache Kopie der aktuellen Ebene.<br/>            Bitte <see href="https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx" /> für eine Erklärung.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Eine flache Kopie der aktuellen Ebene. |


### Method: to_bitmap() {#to_bitmap__76}


```
 to_bitmap() 
```

  

**Returns**

| Typ | Beschreibung |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_77}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Schreibt die gesamte Scanzeile an den angegebenen Scanzeilen‑Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scan_line_index | int | Nullbasierter Index der Scan‑Zeile. |
| argb_32_pixels | int | Das 32‑Bit‑ARGB‑Farben‑Array zum Schreiben. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_78}


```
 write_scan_line(scan_line_index, pixels) 
```

Schreibt die gesamte Scanzeile an den angegebenen Scanzeilen‑Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scan_line_index | int | Nullbasierter Index der Scan‑Zeile. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Das Pixel‑Farben‑Array zum Schreiben. |

