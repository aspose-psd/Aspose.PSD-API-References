---
title: "PsdImage Klasse"
type: docs
weight: 1760
url: /de/python-net/aspose.psd.fileformats.psd/psdimage/
---

**Summary:** Defines the PsdImage class that provides the ability to load, edit, save PSD files as well as<br/>            update properties, add watermarks, perform graphics operations or convert one file format to another.<br/>            Aspose.PSD supports import as a layer and export to the following formats:<br/>            Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb along with export to Pdf with selectable text

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [PsdImage(path)](#PsdImage_path_1) | Initialisiert eine neue Instanz der [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) Klasse aus dem angegebenen Pfad eines Rasterbildes (kein PSD-Bild im Pfad). Wird verwendet, um ein PSD-Bild mit Standardparametern zu initialisieren – Farbmodus – rgb, 4 Kanäle, 8 Bit pro Kanal, Kompression – Raw. |
| [PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2) | Initialisiert eine neue Instanz der [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) Klasse aus dem angegebenen Pfad eines Rasterbildes (kein PSD-Bild im Pfad) mit Konstruktorparametern. |
| [PsdImage(raster_image)](#PsdImage_raster_image_3) | Initialisiert eine neue Instanz der [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) Klasse aus einem vorhandenen Rasterbild (kein PSD-Bild) mit RGB-Farbmodus, 4 Kanälen, 8 Bit/Kanal und ohne Kompression. |
| [PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4) | Initialisiert eine neue Instanz der [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) Klasse aus einem vorhandenen Rasterbild (kein PSD‑Bild) mit Konstruktorparametern. |
| [PsdImage(stream)](#PsdImage_stream_5) | Initialisiert eine neue Instanz der [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) Klasse aus dem angegebenen Pfad eines Rasterbildes (kein PSD‑Bild im Stream). Wird verwendet, um ein PSD‑Bild mit Standardparametern zu initialisieren – Farbmodus – rgb, 4 Kanäle, 8 Bit pro Kanal, Kompression – Raw. |
| [PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6) | Initialisiert eine neue Instanz der [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) Klasse aus dem angegebenen Pfad eines Rasterbildes (kein PSD‑Bild im Stream) mit Konstruktorparametern. |
| [PsdImage(width, height)](#PsdImage_width_height_7) | Initialisiert eine neue Instanz der [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) Klasse mit angegebener Breite und Höhe. Wird verwendet, um ein leeres PSD‑Bild zu initialisieren. |
| [PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8) | Initialisiert eine neue Instanz der [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) Klasse mit angegebenen Breite, Höhe, Palette, Farbmodus, Kanalanzahl und Kanal‑Bit‑Länge sowie angegebenen Kompressionsmodus‑Parametern. Wird verwendet, um ein leeres PSD‑Bild zu initialisieren. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| DEFAULT_VERSION [static] | int | r | Die Standard‑PSD‑Version. |
| active_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | Liest oder setzt die aktive Ebene. |
| auto_adjust_palette | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die Palette automatisch angepasst wird. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Liest oder setzt einen Wert für die Hintergrundfarbe. |
| bits_per_channel | int | r | Liest die Bits pro Kanal. |
| bits_per_pixel | int | r | Liest die Bits‑pro‑Pixel‑Anzahl des Bildes. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Liefert die Objektgrenzen. |
| buffer_size_hint | int | r/w | Liest oder setzt den Hinweis zur Puffergröße, der die maximal zulässige Größe für alle internen Puffer definiert. |
| channels_count | int | r | Liest die Anzahl der PSD‑Kanäle. |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Liest oder setzt das CMYK‑Farbprofil für CMYK‑PSD‑Bilder. Muss zusammen mit RgbColorProfile verwendet werden, um eine korrekte Farbumwandlung zu gewährleisten. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r/w | Liest oder setzt den Farbmodus. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | r | Liest die Kompressionsmethode. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Liest den [Image](/psd/python-net/aspose.psd/image/)‑Container. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Liest den Datenstrom des Objekts. |
| disposed | bool | r | Ruft einen Wert ab, der angibt, ob diese Instanz freigegeben wurde. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Liest einen Wert des Dateiformats |
| global_angle | int | r/w | Ruft den globalen Winkel ab oder legt ihn fest. |
| global_layer_mask_info | [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | r | Liest die Informationen zur globalen Ebenenmaske. |
| global_layer_resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | r/w | Liest oder setzt die globalen Ebenenressourcen. |
| gray_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Liest oder setzt das GRAY‑(monochrome) Farbprofil für Graustufen‑PSD‑Bilder. |
| has_alpha | bool | r | Liest oder setzt die vertikale Auflösung in Pixel pro Zoll dieses [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| has_background_color | bool | r/w | Liest oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| has_transparency_data | bool | r/w | Liest oder setzt einen Wert, der angibt, ob der erste Alphakanal die Transparenzdaten für das zusammengeführte Ergebnis enthält, wenn Ebenendaten angegeben werden. |
| has_transparent_color | bool | r/w | Liest einen Wert, der angibt, ob das Bild eine transparente Farbe hat. |
| height | int | r | Liest die Bildhöhe. |
| horizontal_resolution | double | r/w | Liest oder setzt die horizontale Auflösung (in Pixel pro Zoll) dieses [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| image_opacity | float | r | Liest die Deckkraft dieses Bildes. |
| image_resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock) | r/w | Liest oder setzt die PSD‑Bildressourcen. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Liest oder setzt den Interrupt‑Monitor. |
| is_cached | bool | r | Liest einen Wert, der angibt, ob Bilddaten derzeit zwischengespeichert sind. |
| is_flatten | bool | r | Liest einen Wert, der angibt, ob das PSD‑Bild flachgelegt ist. |
| is_raw_data_available | bool | r | Liest einen Wert, der angibt, ob das Laden von Rohdaten unterstützt wird. |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | Liest oder setzt die PSD‑Ebenen. |
| linked_layers_manager | [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | r | Liest den Manager für verknüpfte Ebenen. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Liest oder setzt die Farbpalette. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| premultiply_components | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die Bildkomponenten vor multipliziert werden müssen. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | Liest oder setzt den benutzerdefinierten Farbkonverter |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Liest das Rohdatenformat. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Liest die aktuellen Rohdaten‑Einstellungen. Hinweis: Beim Verwenden dieser Einstellungen werden die Daten ohne Konvertierung geladen. |
| raw_fallback_index | int | r/w | Liest oder setzt den Ausweichindex, der verwendet wird, wenn der Palettenindex außerhalb des Bereichs liegt |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | Liest oder setzt den indizierten Farbkonverter |
| raw_line_size | int | r | Liest die Rohzeilengröße in Bytes. |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Liest oder setzt das RGB‑Farbprofil für CMYK‑PSD‑Bilder. Muss zusammen mit CmykColorProfile verwendet werden, um eine korrekte Farbumwandlung zu gewährleisten. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Ruft die Objektgröße ab. |
| smart_object_provider | [SmartObjectProvider](/psd/python-net/aspose.psd.fileformats.psd/smartobjectprovider) | r | Ruft den Smart-Objekt-Anbieter ab. |
| timeline | [Timeline](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/) | r | Ruft die [PsdImage.timeline](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) dieses [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Liest die transparente Farbe des Bildes. |
| update_xmp_data | bool | r/w | Liest oder setzt einen Wert, der angibt, ob die XMP-Metadaten aktualisiert werden sollen. |
| use_palette | bool | r | Liest einen Wert, der angibt, ob die Bildpalette verwendet wird. |
| use_raw_data | bool | r/w | Liest oder setzt einen Wert, der angibt, ob Rohdatenladen verwendet werden soll, wenn das Rohdatenladen verfügbar ist. |
| version | int | r/w | Liest oder setzt die Version. |
| vertical_resolution | double | r/w | Liest oder setzt die vertikale Auflösung in Pixel pro Zoll dieses [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| width | int | r | Liest die Bildbreite. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Liest oder setzt die XMP-Metadaten. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_black_white_adjustment_layer()](#add_black_white_adjustment_layer__1) | Fügt die Schwarz‑Weiß‑Anpassungsebene hinzu. |
| [add_brightness_contrast_adjustment_layer(brightness, contrast)](#add_brightness_contrast_adjustment_layer_brightness_contrast_2) | Fügt die Helligkeit/Kontrast‑Anpassungsebene hinzu. |
| [add_channel_mixer_adjustment_layer()](#add_channel_mixer_adjustment_layer__3) | Fügt die Kanalmixer‑Anpassungsebene mit Standardparametern hinzu |
| [add_color_balance_adjustment_layer()](#add_color_balance_adjustment_layer__4) | Fügt die Farbtonbalance‑Anpassungsebene hinzu. |
| [add_curves_adjustment_layer()](#add_curves_adjustment_layer__5) | Fügt die Kurven‑Anpassungsebene hinzu. |
| [add_exposure_adjustment_layer(exposure, offset, gamma_correction)](#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6) | Fügt die Belichtungs‑Anpassungsebene hinzu. |
| [add_gradient_map_adjustment_layer()](#add_gradient_map_adjustment_layer__7) | Fügt die GradientMap‑Anpassungsebene hinzu. |
| [add_hue_saturation_adjustment_layer()](#add_hue_saturation_adjustment_layer__8) | Fügt die Farbton/Sättigung‑Anpassungsebene hinzu. |
| [add_invert_adjustment_layer()](#add_invert_adjustment_layer__9) | Fügt eine Invertierungs‑Anpassungsebene hinzu. |
| [add_layer(layer)](#add_layer_layer_10) | Fügt die Ebene hinzu. |
| [add_layer_group(group_name, index, start_behaviour)](#add_layer_group_group_name_index_start_behaviour_11) | Fügt die Ebenengruppe hinzu. |
| [add_levels_adjustment_layer()](#add_levels_adjustment_layer__12) | Fügt die Levels‑Anpassungsebene hinzu. |
| [add_photo_filter_layer(color)](#add_photo_filter_layer_color_13) | Fügt die PhotoFilter‑Ebene hinzu. |
| [add_posterize_adjustment_layer()](#add_posterize_adjustment_layer__14) | Fügt die Posterize‑Anpassungsebene hinzu. |
| [add_regular_layer()](#add_regular_layer__15) | Fügt eine neue reguläre Ebene hinzu. |
| [add_selective_color_adjustment_layer()](#add_selective_color_adjustment_layer__16) | Fügt die selektive Farb‑Anpassungsebene hinzu. |
| [add_shape_layer()](#add_shape_layer__17) | Füge leere Shape‑Ebene hinzu.<br/>            Ohne Pfade. Sie sollten vor dem Speichern zur Shape‑Ebene hinzugefügt werden. |
| [add_text_layer(text, rect)](#add_text_layer_text_rect_18) | Fügt eine neue Text‑Ebene hinzu. |
| [add_threshold_adjustment_layer()](#add_threshold_adjustment_layer__19) | Fügt die Schwellenwert‑Anpassungsebene hinzu. |
| [add_vibrance_adjustment_layer()](#add_vibrance_adjustment_layer__20) | Fügt die Vibrance‑Anpassungsebene hinzu. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_21) | Anpassung der Helligkeit für das Bild. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_22) | Bildkontrast |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_23) | Gammakorrektur eines Bildes. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_24) | Gammakorrektur eines Bildes. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_25) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus mittels Integralbild‑Schwellenwert. |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_26) | Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus mittels Integralbild‑Schwellenwert. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_27) | Binarisierung eines Bildes mit vordefiniertem Schwellenwert |
| binarize_otsu() | Binarisierung eines Bildes mit Otsu‑Schwellenwert |
| cache_data() | Zwischenspeichert die Daten und stellt sicher, dass keine zusätzlichen Datenladungen vom zugrunde liegenden [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) durchgeführt werden. |
| [can_load(file_path)](#can_load_file_path_28) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_29) | Bestimmt, ob das Bild vom angegebenen Dateipfad geladen werden kann und optional die angegebenen Öffnungsoptionen verwendet. |
| [can_load(stream)](#can_load_stream_30) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann. |
| [can_load(stream, load_options)](#can_load_stream_load_options_31) | Bestimmt, ob das Bild vom angegebenen Stream geladen werden kann und optional die angegebenen <paramref name=\"loadOptions\" /> verwendet. |
| [can_save(options)](#can_save_options_32) | Bestimmt, ob das Bild im angegebenen Dateiformat, das durch die übergebenen Speicheroptionen repräsentiert wird, gespeichert werden kann. |
| [convert(new_options)](#convert_new_options_33) | Konvertiert dieses Bildformat in das in den Optionen angegebene. |
| [create(image_options, width, height)](#create_image_options_width_height_34) | Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_35) | Zuschneiden des Bildes. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_36) | Führt Dithering am aktuellen Bild aus. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_37) | Führt Dithering am aktuellen Bild aus. |
| [filter(rectangle, options)](#filter_rectangle_options_38) | Filtert das angegebene Rechteck. |
| flatten_image() | Flacht alle Ebenen ab. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_39) | Liest ein 32‑Bit‑ARGB‑Pixel des Bildes. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_40) | Liest das Standard‑32‑Bit‑ARGB‑Pixelarray. |
| [get_default_options(args)](#get_default_options_args_41) | Liest die Standardoptionen. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_42) | Liest das Standard‑Pixelarray unter Verwendung des partiellen Pixel‑Loaders. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43) | Ermittelt das Standard‑Rohdaten‑Array mithilfe des partiellen Pixel‑Loaders. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_44) | Ermittelt das Standard‑Rohdaten‑Array. |
| [get_file_format(file_path)](#get_file_format_file_path_45) | Ermittelt das Dateiformat. |
| [get_file_format(stream)](#get_file_format_stream_46) | Ermittelt das Dateiformat. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_47) | Ermittelt das Rechteck, das zum aktuellen Bild passt. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_48) | Ermittelt das Rechteck, das zum aktuellen Bild passt. |
| [get_modify_date(use_default)](#get_modify_date_use_default_49) | Ermittelt das Datum und die Uhrzeit, zu der das Ressourcen‑Bild zuletzt geändert wurde. |
| [get_original_options()](#get_original_options__50) | Ermittelt die Optionen basierend auf den ursprünglichen Dateieinstellungen.<br/>            Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen.<br/>            Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) Methode speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt.<br/>            Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und sie<br/>            an die [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) Methode als zweiten Parameter zu übergeben. |
| [get_pixel(x, y)](#get_pixel_x_y_51) | Ermittelt einen Bildpixel.<br/>            Leistungshinweis: Vermeiden Sie die Verwendung dieser Methode, um über alle Bildpixel zu iterieren, da dies zu erheblichen Leistungsproblemen führen kann.<br/>            Für eine effizientere Pixelmanipulation verwenden Sie die `LoadArgb32Pixels`‑Methode, um das gesamte Pixel‑Array gleichzeitig abzurufen. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_52) | Ermittelt eine proportionale Höhe. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_53) | Ermittelt eine proportionale Breite. |
| [get_skew_angle()](#get_skew_angle__54) |    |
| grayscale() | Transformation eines Bildes in seine Graustufen‑Darstellung |
| [load(file_path)](#load_file_path_55) | Lädt ein neues Bild aus der angegebenen Datei. |
| [load(file_path, load_options)](#load_file_path_load_options_56) | Lädt ein neues Bild aus der angegebenen Datei. |
| [load(stream)](#load_stream_57) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load(stream, load_options)](#load_stream_load_options_58) | Lädt ein neues Bild aus dem angegebenen Stream. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_59) | Lädt 32‑Bit‑ARGB‑Pixel. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_60) | Lädt 64‑Bit‑ARGB‑Pixel. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_61) | Lädt Pixel im CMYK‑Format. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_62) | Lädt Pixel im CMYK‑Format.<br/>            Diese Methode ist veraltet. Bitte verwenden Sie die effektivere [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/)‑Methode. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63) | Lädt 32‑Bit‑ARGB‑Pixel teilweise (nach Blöcken). |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_64) | Lädt Pixel teilweise in Paketen. |
| [load_pixels(rectangle)](#load_pixels_rectangle_65) | Lädt Pixel. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66) | Lädt Rohdaten. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67) | Lädt Rohdaten. |
| [merge_layers(bottom_layer, top_layer)](#merge_layers_bottom_layer_top_layer_68) | Führt die Ebenen zusammen. |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_69) | Liest die gesamte Scan‑Zeile anhand des angegebenen Scan‑Zeilen‑Index. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_70) | Liest die gesamte Scan‑Zeile anhand des angegebenen Scan‑Zeilen‑Index. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_71) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_72) | Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_73) | Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.<br/> Hinweis: Wenn Sie es bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_74) | Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.<br/> Hinweis: Wenn Sie es bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt. |
| [resize(new_width, new_height)](#resize_new_width_new_height_75) | Skaliert das Bild. Der Standard‑[ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wird verwendet. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_76) | Skaliert das Bild. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_77) | Skaliert das Bild. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_78) | Skaliert die Höhe proportional. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_79) | Skaliert die Höhe proportional. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_80) | Skaliert die Höhe proportional. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_81) | Skaliert die Breite proportional. Der Standard‑[ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wird verwendet. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_82) | Skaliert die Breite proportional. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_83) | Skaliert die Breite proportional. |
| [rotate(angle)](#rotate_angle_84) | Bild um das Zentrum drehen. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_85) | Bild um das Zentrum drehen. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_86) | Dreht, spiegelt oder dreht und spiegelt das Bild. |
| save() | Speichert die Bilddaten in den zugrunde liegenden Stream. |
| [save(file_path)](#save_file_path_87) | Speichert die Objektdaten am angegebenen Dateipfad. |
| [save(file_path, options)](#save_file_path_options_88) | Speichert die Objektdaten am angegebenen Dateipfad im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_89) | Speichert die Objektdaten am angegebenen Dateipfad im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(file_path, over_write)](#save_file_path_over_write_90) | Speichert die Objektdaten am angegebenen Dateipfad. |
| [save(stream)](#save_stream_91) | Speichert die Objektdaten in den angegebenen Stream. |
| [save(stream, options_base)](#save_stream_options_base_92) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_93) | Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_94) | Speichert die 32‑Bit‑ARGB‑Pixel. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_95) | Speichert Pixel (formatspezifische Methode). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_96) | Speichert die Rohdaten. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_97) | Setzt ein 32‑Bit‑ARGB‑Pixel des Bildes für die angegebene Position. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_98) | Setzt die Bildpalette. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_99) | Setzt ein Bildpixel für die angegebene Position. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_100) | Legt die Auflösung für dieses [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) fest. |
| [to_bitmap()](#to_bitmap__101) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102) | Schreibt die gesamte Scanzeile an den angegebenen Scanzeilen‑Index. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_103) | Schreibt die gesamte Scanzeile an den angegebenen Scanzeilen‑Index. |


### Constructor: PsdImage(path) {#PsdImage_path_1}


```
 PsdImage(path) 
```

Initialisiert eine neue Instanz der [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) Klasse aus dem angegebenen Pfad eines Rasterbildes (kein PSD-Bild im Pfad). Wird verwendet, um ein PSD-Bild mit Standardparametern zu initialisieren – Farbmodus – rgb, 4 Kanäle, 8 Bit pro Kanal, Kompression – Raw.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Pfad | string | Der Pfad, von dem Pixel- und Palettendaten geladen und mit dem initialisiert werden. |

### Constructor: PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2}


```
 PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Initialisiert eine neue Instanz der [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) Klasse aus dem angegebenen Pfad eines Rasterbildes (kein PSD-Bild im Pfad) mit Konstruktorparametern.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Pfad | string | Der Pfad, von dem Pixel- und Palettendaten geladen und mit dem initialisiert werden. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Der Farbmodus. |
| channel_bit_depth | short | Die PSD-Bittiefe pro Kanal. |
| channels | short | Die Anzahl der PSD-Kanäle. |
| psd_version | int | Die PSD-Version. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Die zu verwendende Kompression. |

### Constructor: PsdImage(raster_image) {#PsdImage_raster_image_3}


```
 PsdImage(raster_image) 
```

Initialisiert eine neue Instanz der [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) Klasse aus einem vorhandenen Rasterbild (kein PSD-Bild) mit RGB-Farbmodus, 4 Kanälen, 8 Bit/Kanal und ohne Kompression.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Das Bild, von dem Pixel- und Palettendaten geladen und mit dem initialisiert werden. |

### Constructor: PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4}


```
 PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Initialisiert eine neue Instanz der [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) Klasse aus einem vorhandenen Rasterbild (kein PSD‑Bild) mit Konstruktorparametern.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Das Bild, von dem Pixel- und Palettendaten geladen und mit dem initialisiert werden. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Der Farbmodus. |
| channel_bit_depth | short | Die PSD-Bittiefe pro Kanal. |
| channels | short | Die Anzahl der PSD-Kanäle. |
| psd_version | int | Die PSD-Version. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Die zu verwendende Kompression. |

### Constructor: PsdImage(stream) {#PsdImage_stream_5}


```
 PsdImage(stream) 
```

Initialisiert eine neue Instanz der [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) Klasse aus dem angegebenen Pfad eines Rasterbildes (kein PSD‑Bild im Stream). Wird verwendet, um ein PSD‑Bild mit Standardparametern zu initialisieren – Farbmodus – rgb, 4 Kanäle, 8 Bit pro Kanal, Kompression – Raw.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream, von dem Pixel- und Palettendaten geladen und mit dem initialisiert werden. |

### Constructor: PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6}


```
 PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Initialisiert eine neue Instanz der [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) Klasse aus dem angegebenen Pfad eines Rasterbildes (kein PSD‑Bild im Stream) mit Konstruktorparametern.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream, von dem Pixel- und Palettendaten geladen und mit dem initialisiert werden. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Der Farbmodus. |
| channel_bit_depth | short | Die PSD-Bittiefe pro Kanal. |
| channels | short | Die Anzahl der PSD-Kanäle. |
| psd_version | int | Die PSD-Version. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Die zu verwendende Kompression. |

### Constructor: PsdImage(width, height) {#PsdImage_width_height_7}


```
 PsdImage(width, height) 
```

Initialisiert eine neue Instanz der [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) Klasse mit angegebener Breite und Höhe. Wird verwendet, um ein leeres PSD‑Bild zu initialisieren.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Die Bildbreite. |
| height | int | Die Bildhöhe. |

### Constructor: PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8}


```
 PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Initialisiert eine neue Instanz der [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) Klasse mit angegebenen Breite, Höhe, Palette, Farbmodus, Kanalanzahl und Kanal‑Bit‑Länge sowie angegebenen Kompressionsmodus‑Parametern. Wird verwendet, um ein leeres PSD‑Bild zu initialisieren.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Die Bildbreite. |
| height | int | Die Bildhöhe. |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Die Farbpalette. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Der Farbmodus. |
| channel_bit_depth | short | Die PSD-Bittiefe pro Kanal. |
| channels | short | Die Anzahl der PSD-Kanäle. |
| psd_version | int | Die PSD-Version. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Die zu verwendende Kompression. |

### Method: add_black_white_adjustment_layer() {#add_black_white_adjustment_layer__1}


```
 add_black_white_adjustment_layer() 
```

Fügt die Schwarz‑Weiß‑Anpassungsebene hinzu.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [BlackWhiteAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/) | Die erstellte Schwarz-Weiß-Anpassungsebene. |


### Method: add_brightness_contrast_adjustment_layer(brightness, contrast) {#add_brightness_contrast_adjustment_layer_brightness_contrast_2}


```
 add_brightness_contrast_adjustment_layer(brightness, contrast) 
```

Fügt die Helligkeit/Kontrast‑Anpassungsebene hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Helligkeit | int | Die Helligkeit. |
| Kontrast | int | Der Kontrast. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [BrightnessContrastLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer/) | Erstellte Helligkeit/Kontrast-Ebene |


### Method: add_channel_mixer_adjustment_layer() {#add_channel_mixer_adjustment_layer__3}


```
 add_channel_mixer_adjustment_layer() 
```

Fügt die Kanalmixer‑Anpassungsebene mit Standardparametern hinzu

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ChannelMixerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer/) | Hinzugefügte Channel Mixer Ebene |


### Method: add_color_balance_adjustment_layer() {#add_color_balance_adjustment_layer__4}


```
 add_color_balance_adjustment_layer() 
```

Fügt die Farbtonbalance‑Anpassungsebene hinzu.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ColorBalanceAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/) | Eine neu erstellte Farbtonwertausgleichsebene. |


### Method: add_curves_adjustment_layer() {#add_curves_adjustment_layer__5}


```
 add_curves_adjustment_layer() 
```

Fügt die Kurven‑Anpassungsebene hinzu.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) | Erstellte [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) Ebene |


### Method: add_exposure_adjustment_layer(exposure, offset, gamma_correction) {#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6}


```
 add_exposure_adjustment_layer(exposure, offset, gamma_correction) 
```

Fügt die Belichtungs‑Anpassungsebene hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Belichtung | float | Die Belichtung. |
| offset | float | Der Versatz. |
| gamma_correction | float | Die Gammakorrektur. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ExposureLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer/) | Erstellte Belichtungsanpassungsebene |


### Method: add_gradient_map_adjustment_layer() {#add_gradient_map_adjustment_layer__7}


```
 add_gradient_map_adjustment_layer() 
```

Fügt die GradientMap‑Anpassungsebene hinzu.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [GradientMapLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/) | GradientMap-Instanz. |


### Method: add_hue_saturation_adjustment_layer() {#add_hue_saturation_adjustment_layer__8}


```
 add_hue_saturation_adjustment_layer() 
```

Fügt die Farbton/Sättigung‑Anpassungsebene hinzu.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [HueSaturationLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer/) | Eine neu erstellte Farbton/Sättigungsebene. |


### Method: add_invert_adjustment_layer() {#add_invert_adjustment_layer__9}


```
 add_invert_adjustment_layer() 
```

Fügt eine Invertierungs‑Anpassungsebene hinzu.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [InvertAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/) | Die erstellte Invertierungsebene |


### Method: add_layer(layer) {#add_layer_layer_10}


```
 add_layer(layer) 
```

Fügt die Ebene hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Die Ebene. |

### Method: add_layer_group(group_name, index, start_behaviour) {#add_layer_group_group_name_index_start_behaviour_11}


```
 add_layer_group(group_name, index, start_behaviour) 
```

Fügt die Ebenengruppe hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| group_name | string | Name der Gruppe. |
| index | int | Der Index der Ebene, nach der eingefügt werden soll. |
| start_behaviour | bool | Wenn auf <c>true</c> [start behaviour] gesetzt, befindet sich die Gruppe beim Start im offenen Zustand, andernfalls im minimierten Zustand. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | Öffnen der Gruppenebene |


### Method: add_levels_adjustment_layer() {#add_levels_adjustment_layer__12}


```
 add_levels_adjustment_layer() 
```

Fügt die Levels‑Anpassungsebene hinzu.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [LevelsLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer/) | Ein neu erstelltes Levels-Layer |


### Method: add_photo_filter_layer(color) {#add_photo_filter_layer_color_13}


```
 add_photo_filter_layer(color) 
```

Fügt die PhotoFilter‑Ebene hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Die Farbe. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PhotoFilterLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer/) | Erstelltes PhotoFilter-Layer |


### Method: add_posterize_adjustment_layer() {#add_posterize_adjustment_layer__14}


```
 add_posterize_adjustment_layer() 
```

Fügt die Posterize‑Anpassungsebene hinzu.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PosterizeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/) | PosterizeLayer-Instanz. |


### Method: add_regular_layer() {#add_regular_layer__15}


```
 add_regular_layer() 
```

Fügt eine neue reguläre Ebene hinzu.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Erstelltes reguläres Layer. |


### Method: add_selective_color_adjustment_layer() {#add_selective_color_adjustment_layer__16}


```
 add_selective_color_adjustment_layer() 
```

Fügt die selektive Farb‑Anpassungsebene hinzu.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SelectiveColorLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer/) | Das erstellte selektive Farbkorrektur-Layer. |


### Method: add_shape_layer() {#add_shape_layer__17}


```
 add_shape_layer() 
```

Füge leere Shape‑Ebene hinzu.<br/>            Ohne Pfade. Sie sollten vor dem Speichern zur Shape‑Ebene hinzugefügt werden.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | ShapeLayer-Instanz. |


### Method: add_text_layer(text, rect) {#add_text_layer_text_rect_18}


```
 add_text_layer(text, rect) 
```

Fügt eine neue Text‑Ebene hinzu.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| text | string | Der Text der Ebene. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck der Ebene. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | Erstelltes Text-Layer. |


### Method: add_threshold_adjustment_layer() {#add_threshold_adjustment_layer__19}


```
 add_threshold_adjustment_layer() 
```

Fügt die Schwellenwert‑Anpassungsebene hinzu.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ThresholdLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/) | Das erstellte Schwellenwert-Anpassungs-Layer. |


### Method: add_vibrance_adjustment_layer() {#add_vibrance_adjustment_layer__20}


```
 add_vibrance_adjustment_layer() 
```

Fügt die Vibrance‑Anpassungsebene hinzu.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VibranceLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/) | Ein neu erstelltes Vibrance-Layer. |


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_21}


```
 adjust_brightness(brightness) 
```

Anpassung der Helligkeit für das Bild.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Helligkeit | int | Helligkeitswert. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_22}


```
 adjust_contrast(contrast) 
```

Bildkontrast

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Kontrast | float | Kontrastwert (im Bereich [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_23}


```
 adjust_gamma(gamma) 
```

Gammakorrektur eines Bildes.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Gamma | float | Gamma‑Koeffizient für Rot-, Grün‑ und Blaukanäle |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_24}


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

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_25}


```
 binarize_bradley(brightness_difference) 
```

Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus mittels Integralbild‑Schwellenwert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brightness_difference | double | Der Helligkeitsunterschied zwischen dem Pixel und dem Durchschnitt eines s × s‑Fensters von Pixeln, das um dieses Pixel zentriert ist. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_26}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarisierung eines Bildes mit Bradleys adaptivem Schwellenwertalgorithmus mittels Integralbild‑Schwellenwert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| brightness_difference | double | Der Helligkeitsunterschied zwischen dem Pixel und dem Durchschnitt eines s × s‑Fensters von Pixeln, das um dieses Pixel zentriert ist. |
| window_size | int | Die Größe des s × s‑Fensters von Pixeln, das um dieses Pixel zentriert ist |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_27}


```
 binarize_fixed(threshold) 
```

Binarisierung eines Bildes mit vordefiniertem Schwellenwert

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| threshold | byte | Schwellenwert. Wenn der entsprechende Grauwert eines Pixels größer als der Schwellenwert ist, wird ihm der Wert 255 zugewiesen, sonst 0. |

### Method: can_load(file_path)  [static] {#can_load_file_path_28}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_29}


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


### Method: can_load(stream)  [static] {#can_load_stream_30}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_31}


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


### Method: can_save(options) {#can_save_options_32}


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


### Method: convert(new_options) {#convert_new_options_33}


```
 convert(new_options) 
```

Konvertiert dieses Bildformat in das in den Optionen angegebene.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | Die neuen Optionen. |

### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_34}


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


### Method: crop(rectangle) {#crop_rectangle_35}


```
 crop(rectangle) 
```

Zuschneiden des Bildes.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_36}


```
 dither(dithering_method, bits_count) 
```

Führt Dithering am aktuellen Bild aus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | Die Dithering-Methode. |
| bits_count | int | Die endgültige Bitanzahl für das Dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_37}


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

### Method: filter(rectangle, options) {#filter_rectangle_options_38}


```
 filter(rectangle, options) 
```

Filtert das angegebene Rechteck.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck. |
| options | [FilterOptionsBase](/psd/python-net/aspose.psd.imagefilters.filteroptions/filteroptionsbase/) | Die Optionen. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_39}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_40}


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


### Method: get_default_options(args) {#get_default_options_args_41}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_42}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Liest das Standard‑Pixelarray unter Verwendung des partiellen Pixel‑Loaders.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, für das Pixel abgerufen werden sollen. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Der partielle Pixel-Lader. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_44}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_45}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_46}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_47}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_48}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_49}


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


### Method: get_original_options() {#get_original_options__50}


```
 get_original_options() 
```

Ermittelt die Optionen basierend auf den ursprünglichen Dateieinstellungen.<br/>            Dies kann hilfreich sein, um die Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen.<br/>            Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es anschließend mit der<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) Methode speichern, wird ein PNG‑Ausgabebild mit 8 Bit pro Pixel erzeugt.<br/>            Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und sie<br/>            an die [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) Methode als zweiten Parameter zu übergeben.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Optionen basierend auf den ursprünglichen Dateieinstellungen. |


### Method: get_pixel(x, y) {#get_pixel_x_y_51}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_52}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_53}


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


### Method: get_skew_angle() {#get_skew_angle__54}


```
 get_skew_angle() 
```

  

**Returns**

| Typ | Beschreibung |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_55}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_56}


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


### Method: load(stream)  [static] {#load_stream_57}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_58}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_59}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_60}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_61}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_62}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Lädt 32‑Bit‑ARGB‑Pixel teilweise (nach Blöcken).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, aus dem Pixel geladen werden. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Der partielle Pixel-Lader. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_64}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Lädt Pixel teilweise in Paketen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das gewünschte Rechteck. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | Der Pixel‑Lader. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_65}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67}


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

### Method: merge_layers(bottom_layer, top_layer) {#merge_layers_bottom_layer_top_layer_68}


```
 merge_layers(bottom_layer, top_layer) 
```

Führt die Ebenen zusammen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| bottom_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Das untere Layer. |
| top_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Das obere Layer. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Unteres Layer nach dem Zusammenführen |


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_69}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_70}


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


### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_71}


```
 replace_color(old_color, old_color_diff, new_color) 
```

Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| old_color | [Color](/psd/python-net/aspose.psd/color) |  |
| old_color_diff | byte | Zulässige Differenz in der alten Farbe, um den ersetzten Farbton erweitern zu können. |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_72}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

Ersetzt eine Farbe durch eine andere mit zulässiger Differenz und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| old_color_argb | int | ARGB-Wert der alten Farbe, der ersetzt werden soll. |
| old_color_diff | byte | Zulässige Differenz in der alten Farbe, um den ersetzten Farbton erweitern zu können. |
| new_color_argb | int | ARGB-Wert der neuen Farbe, um die alte Farbe zu ersetzen. |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_73}


```
 replace_non_transparent_colors(new_color) 
```

Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.<br/> Hinweis: Wenn Sie es bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_74}


```
 replace_non_transparent_colors(new_color_argb) 
```

Ersetzt alle nicht‑transparenten Farben durch eine neue Farbe und bewahrt den ursprünglichen Alphawert, um glatte Kanten zu erhalten.<br/> Hinweis: Wenn Sie es bei Bildern ohne Transparenz verwenden, werden alle Farben durch eine einzige ersetzt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color_argb | int | Neuer ARGB‑Farbwert, um nicht transparente Farben zu ersetzen. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_75}


```
 resize(new_width, new_height) 
```

Skaliert das Bild. Der Standard‑[ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| new_height | int | Die neue Höhe. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_76}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_77}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_78}


```
 resize_height_proportionally(new_height) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_79}


```
 resize_height_proportionally(new_height, resize_type) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Typ der Skalierung. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_80}


```
 resize_height_proportionally(new_height, settings) 
```

Skaliert die Höhe proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_height | int | Die neue Höhe. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Die Bildskalierungseinstellungen. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_81}


```
 resize_width_proportionally(new_width) 
```

Skaliert die Breite proportional. Der Standard‑[ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wird verwendet.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_82}


```
 resize_width_proportionally(new_width, resize_type) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Typ der Skalierung. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_83}


```
 resize_width_proportionally(new_width, settings) 
```

Skaliert die Breite proportional.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_width | int | Die neue Breite. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Die Bildskalierungseinstellungen. |

### Method: rotate(angle) {#rotate_angle_84}


```
 rotate(angle) 
```

Bild um das Zentrum drehen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_85}


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

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_86}


```
 rotate_flip(rotate_flip_type) 
```

Dreht, spiegelt oder dreht und spiegelt das Bild.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Der Rotations-Spiegelungstyp. |

### Method: save(file_path) {#save_file_path_87}


```
 save(file_path) 
```

Speichert die Objektdaten am angegebenen Dateipfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Daten des Objekts gespeichert werden. |

### Method: save(file_path, options) {#save_file_path_options_88}


```
 save(file_path, options) 
```

Speichert die Objektdaten am angegebenen Dateipfad im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Optionen. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_89}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_90}


```
 save(file_path, over_write) 
```

Speichert die Objektdaten am angegebenen Dateipfad.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_path | string | Der Dateipfad, in dem die Daten des Objekts gespeichert werden. |
| over_write | bool | Wenn auf <c>true</c> gesetzt, werden die Dateiinhalte überschrieben, andernfalls wird angehängt. |

### Method: save(stream) {#save_stream_91}


```
 save(stream) 
```

Speichert die Objektdaten in den angegebenen Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream, in dem die Daten des Objekts gespeichert werden. |

### Method: save(stream, options_base) {#save_stream_options_base_92}


```
 save(stream, options_base) 
```

Speichert die Bilddaten in den angegebenen Stream im angegebenen Dateiformat gemäß den Speicheroptionen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Strom | _io.BufferedRandom | Der Stream, in dem die Bilddaten gespeichert werden. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Die Speicheroptionen. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_93}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_94}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Speichert die 32‑Bit‑ARGB‑Pixel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, in dem die Pixel gespeichert werden. |
| pixels | int | Das 32-Bit-ARGB-Pixel-Array. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_95}


```
 save_pixels(rectangle, pixels) 
```

Speichert Pixel (formatspezifische Methode).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Das Rechteck, in dem die Pixel gespeichert werden. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Das 32-Bit-ARGB-Pixel-Array. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_96}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_97}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_98}


```
 set_palette(palette, update_colors) 
```

Setzt die Bildpalette.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Die zu setzende Palette. |
| update_colors | bool | Wenn auf <c>true</c> gesetzt, werden die Farben gemäß der neuen Palette aktualisiert; andernfalls bleiben die Farbindizes unverändert. Beachten Sie, dass unveränderte Indizes das Bild beim Laden zum Absturz bringen können, wenn einige Indizes keinen entsprechenden Paletteneintrag haben. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_99}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_100}


```
 set_resolution(dpi_x, dpi_y) 
```

Legt die Auflösung für dieses [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) fest.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| dpi_x | double | Die horizontale Auflösung in Punkten pro Zoll des [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| dpi_y | double | Die vertikale Auflösung in Punkten pro Zoll des [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |

### Method: to_bitmap() {#to_bitmap__101}


```
 to_bitmap() 
```

  

**Returns**

| Typ | Beschreibung |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Schreibt die gesamte Scanzeile an den angegebenen Scanzeilen‑Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scan_line_index | int | Nullbasierter Index der Scan‑Zeile. |
| argb_32_pixels | int | Das 32‑Bit‑ARGB‑Farben‑Array zum Schreiben. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_103}


```
 write_scan_line(scan_line_index, pixels) 
```

Schreibt die gesamte Scanzeile an den angegebenen Scanzeilen‑Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| scan_line_index | int | Nullbasierter Index der Scan‑Zeile. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Das Pixel‑Farben‑Array zum Schreiben. |

