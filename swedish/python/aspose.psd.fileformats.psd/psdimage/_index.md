---
title: "PsdImage‑klass"
type: docs
weight: 1760
url: /sv/python-net/aspose.psd.fileformats.psd/psdimage/
---

**Summary:** Defines the PsdImage class that provides the ability to load, edit, save PSD files as well as<br/>            update properties, add watermarks, perform graphics operations or convert one file format to another.<br/>            Aspose.PSD supports import as a layer and export to the following formats:<br/>            Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb along with export to Pdf with selectable text

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [PsdImage(path)](#PsdImage_path_1) | Initierar en ny instans av klassen [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) från angiven sökväg för rasterbild (inte psd‑bild i sökvägen). Används för att initiera psd‑bild med standardparametrar - färgläge - rgb, 4 kanaler, 8 bit per kanal, komprimering - Raw. |
| [PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2) | Initierar en ny instans av klassen [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) från angiven sökväg för rasterbild (inte psd‑bild i sökvägen) med konstruktörsparametrar. |
| [PsdImage(raster_image)](#PsdImage_raster_image_3) | Initierar en ny instans av klassen [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) från befintlig rasterbild (inte psd‑bild) med RGB‑färgläge, 4 kanaler, 8 bitar/kanal och ingen komprimering. |
| [PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4) | Initierar en ny instans av klassen [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) från befintlig rasterbild (inte psd‑bild) med konstruktörsparametrar. |
| [PsdImage(stream)](#PsdImage_stream_5) | Initierar en ny instans av klassen [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) från angiven sökväg för rasterbild (inte psd‑bild i ström). Används för att initiera psd‑bild med standardparametrar - färgläge - rgb, 4 kanaler, 8 bit per kanal, komprimering - Raw. |
| [PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6) | Initierar en ny instans av klassen [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) från angiven sökväg för rasterbild (inte psd‑bild i ström) med konstruktörsparametrar. |
| [PsdImage(width, height)](#PsdImage_width_height_7) | Initierar en ny instans av klassen [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) med angiven bredd och höjd. Används för att initiera en tom psd‑bild. |
| [PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8) | Initierar en ny instans av klassen [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) med angiven bredd, höjd, palett, färgläge, antal kanaler och kanalernas bitlängd samt angivna komprimeringslägesparametrar. Används för att initiera en tom psd‑bild. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| DEFAULT_VERSION [static] | int | r | Den standard PSD‑versionen. |
| active_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | Hämtar eller anger det aktiva lagret. |
| auto_adjust_palette | bool | r/w | Hämtar eller anger ett värde som indikerar om automatisk justering av palett. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Hämtar eller anger ett värde för bakgrundsfärgen. |
| bits_per_channel | int | r | Hämtar antalet bitar per kanal. |
| bits_per_pixel | int | r | Hämtar antalet bildbitar per pixel. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Hämtar objektets gränser. |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| channels_count | int | r | Hämtar antalet PSD‑kanaler. |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Hämtar eller anger CMYK‑färgprofilen för CMYK‑PSD‑bilder. Måste vara i par med RgbColorProfile för korrekt färgkonvertering. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r/w | Hämtar eller anger färgläget. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | r | Hämtar komprimeringsmetoden. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Hämtar [Image](/psd/python-net/aspose.psd/image/)‑behållaren. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Hämtar objektets datastream. |
| borttagen | bool | r | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Hämtar ett värde för filformatet |
| global_angle | int | r/w | Hämtar eller anger den globala vinkeln. |
| global_layer_mask_info | [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | r | Hämtar information om global lagermask. |
| global_layer_resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | r/w | Hämtar eller anger globala lagerresurser. |
| gray_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Hämtar eller anger GRAY (monokrom) färgprofil för Grayscale‑PSD‑bilder. |
| has_alpha | bool | r | Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för denna [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| has_background_color | bool | r/w | Hämtar eller anger ett värde som visar om bilden har bakgrundsfärg. |
| has_transparency_data | bool | r/w | Hämtar eller anger ett värde som indikerar om den första alfakanalen innehåller transparensdata för det sammanslagna resultatet när lagerdata specificeras. |
| has_transparent_color | bool | r/w | Hämtar ett värde som visar om bilden har transparent färg. |
| height | int | r | Hämtar bildens höjd. |
| horizontal_resolution | double | r/w | Hämtar eller anger den horisontella upplösningen, i pixlar per tum, för denna [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| image_opacity | float | r | Hämtar opaciteten för denna bild. |
| image_resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock) | r/w | Hämtar eller anger PSD-bildresurserna. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Hämtar eller anger avbrottsövervakaren. |
| is_cached | bool | r | Hämtar ett värde som visar om bilddata för närvarande är cachad. |
| is_flatten | bool | r | Hämtar ett värde som indikerar om PSD-bilden är plattlagd. |
| is_raw_data_available | bool | r | Hämtar ett värde som indikerar om inläsning av rådata stöds. |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | Hämtar eller anger PSD-lagren. |
| linked_layers_manager | [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | r | Hämtar den länkade lagerhanteraren. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Hämtar eller anger färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| premultiply_components | bool | r/w | Hämtar eller anger ett värde som visar om bildkomponenterna måste vara förmultiplicerade. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | Hämtar eller anger den anpassade färgkonverteraren |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Hämtar det råa dataformatet. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Hämtar de aktuella rådatainställningarna. Observera att när dessa inställningar används laddas data utan konvertering. |
| raw_fallback_index | int | r/w | Hämtar eller anger reservindexet att använda när palettindexet är utanför gränserna |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | Hämtar eller anger den indexerade färgkonverteraren |
| raw_line_size | int | r | Hämtar den råa radstorleken i byte. |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Hämtar eller anger RGB-färgprofilen för CMYK PSD-bilder. Måste vara i par med CmykColorProfile för korrekt färgkonvertering. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Hämtar objektets storlek. |
| smart_object_provider | [SmartObjectProvider](/psd/python-net/aspose.psd.fileformats.psd/smartobjectprovider) | r | Hämtar den smarta objektleverantören. |
| timeline | [Timeline](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/) | r | Hämtar [PsdImage.timeline](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) för denna [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Hämtar bildens transparenta färg. |
| update_xmp_data | bool | r/w | Hämtar eller anger ett värde som indikerar om XMP-metadata ska uppdateras. |
| use_palette | bool | r | Hämtar ett värde som indikerar om bildpaletten används. |
| use_raw_data | bool | r/w | Hämtar eller anger ett värde som indikerar om rådatainläsning ska användas när rådatainläsning är tillgänglig. |
| version | int | r/w | Hämtar eller anger versionen. |
| vertical_resolution | double | r/w | Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för denna [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| width | int | r | Hämtar bildens bredd. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger XMP-metadata. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_black_white_adjustment_layer()](#add_black_white_adjustment_layer__1) | Lägger till svartvitt justeringslager. |
| [add_brightness_contrast_adjustment_layer(brightness, contrast)](#add_brightness_contrast_adjustment_layer_brightness_contrast_2) | Lägger till ljusstyrka/kontrast justeringslager. |
| [add_channel_mixer_adjustment_layer()](#add_channel_mixer_adjustment_layer__3) | Lägger till kanalblandare justeringslager med standardparametrar |
| [add_color_balance_adjustment_layer()](#add_color_balance_adjustment_layer__4) | Lägger till färgbalansjusteringslager. |
| [add_curves_adjustment_layer()](#add_curves_adjustment_layer__5) | Lägger till kurvjusteringslager. |
| [add_exposure_adjustment_layer(exposure, offset, gamma_correction)](#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6) | Lägger till exponeringsjusteringslager. |
| [add_gradient_map_adjustment_layer()](#add_gradient_map_adjustment_layer__7) | Lägger till GradientMap-justeringslager. |
| [add_hue_saturation_adjustment_layer()](#add_hue_saturation_adjustment_layer__8) | Lägger till nyans/mättnad justeringslager. |
| [add_invert_adjustment_layer()](#add_invert_adjustment_layer__9) | Lägger till ett inverteringsjusteringslager. |
| [add_layer(layer)](#add_layer_layer_10) | Lägger till lagret. |
| [add_layer_group(group_name, index, start_behaviour)](#add_layer_group_group_name_index_start_behaviour_11) | Lägger till lagergruppen. |
| [add_levels_adjustment_layer()](#add_levels_adjustment_layer__12) | Lägger till nivåjusteringslager. |
| [add_photo_filter_layer(color)](#add_photo_filter_layer_color_13) | Lägger till fotofilterlager. |
| [add_posterize_adjustment_layer()](#add_posterize_adjustment_layer__14) | Lägger till posteriseringsjusteringslager. |
| [add_regular_layer()](#add_regular_layer__15) | Lägger till ett nytt vanligt lager. |
| [add_selective_color_adjustment_layer()](#add_selective_color_adjustment_layer__16) | Lägger till selektiv färgjusteringslager. |
| [add_shape_layer()](#add_shape_layer__17) | Lägg till ett tomt Shape‑layer.<br/>            Utan banor. De bör läggas till shape‑lagret innan sparning. |
| [add_text_layer(text, rect)](#add_text_layer_text_rect_18) | Lägger till ett nytt Text‑layer. |
| [add_threshold_adjustment_layer()](#add_threshold_adjustment_layer__19) | Lägger till Threshold‑justeringslagret. |
| [add_vibrance_adjustment_layer()](#add_vibrance_adjustment_layer__20) | Lägger till Vibrance‑justeringslagret. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_21) | Justering av bildens ljusstyrka. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_22) | Bildkontrast |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_23) | Gammakorrigering av en bild. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_24) | Gammakorrigering av en bild. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_25) | Binärisering av en bild med Bradleys adaptiva tröskelalgoritm med integralbildeströskling. |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_26) | Binärisering av en bild med Bradleys adaptiva tröskelalgoritm med integralbildeströskling. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_27) | Binärisering av en bild med fördefinierad tröskel. |
| binarize_otsu() | Binärisering av en bild med Otsu-tröskling. |
| cache_data() | Cachar data och säkerställer att ingen ytterligare datainläsning utförs från den underliggande [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/). |
| [can_load(file_path)](#can_load_file_path_28) | Avgör om bilden kan läsas in från den angivna filsökvägen. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_29) | Avgör om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna öppningsalternativen. |
| [can_load(stream)](#can_load_stream_30) | Avgör om bilden kan läsas in från den angivna strömmen. |
| [can_load(stream, load_options)](#can_load_stream_load_options_31) | Avgör om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna <paramref name="loadOptions" />. |
| [can_save(options)](#can_save_options_32) | Avgör om bilden kan sparas till det angivna filformatet som representeras av de medföljande sparalternativen. |
| [convert(new_options)](#convert_new_options_33) | Konverterar detta bildformat till det som anges i alternativ. |
| [create(image_options, width, height)](#create_image_options_width_height_34) | Skapar en ny bild med de angivna skapalternativen. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_35) | Beskär bilden. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_36) | Utför dithering på den aktuella bilden. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_37) | Utför dithering på den aktuella bilden. |
| [filter(rectangle, options)](#filter_rectangle_options_38) | Filtrerar den angivna rektangeln. |
| flatten_image() | Plattar till alla lager. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_39) | Hämtar en 32-bit ARGB-pixel från bilden. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_40) | Hämtar standardarrayen för 32-bit ARGB-pixlar. |
| [get_default_options(args)](#get_default_options_args_41) | Hämtar standardalternativen. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_42) | Hämtar standardpixelarrayen med hjälp av partiell pixel‑laddare. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43) | Hämtar standardarrayen för rådata med hjälp av partiell pixel‑laddare. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_44) | Hämtar standardarrayen för rådata. |
| [get_file_format(file_path)](#get_file_format_file_path_45) | Hämtar filformatet. |
| [get_file_format(stream)](#get_file_format_stream_46) | Hämtar filformatet. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_47) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_48) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_modify_date(use_default)](#get_modify_date_use_default_49) | Hämtar datum och tid då resursbilden senast ändrades. |
| [get_original_options()](#get_original_options__50) | Hämtar alternativen baserat på originalfilens inställningar.<br/>            Detta kan vara användbart för att behålla bitdjup och andra parametrar i originalbilden oförändrade.<br/>            Till exempel, om vi laddar en svart‑vit PNG‑bild med 1 bit per pixel och sedan sparar den med hjälp av<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/)‑metoden, kommer en PNG‑utdata med 8‑bit per pixel att skapas.<br/>            För att undvika detta och spara PNG‑bilden med 1‑bit per pixel, använd den här metoden för att hämta motsvarande sparalternativ och skicka dem<br/>            till [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/)‑metoden som den andra parametern. |
| [get_pixel(x, y)](#get_pixel_x_y_51) | Hämtar en bildpixel.<br/>            Prestandavarning: Undvik att använda denna metod för att iterera över alla bildpixlar eftersom det kan leda till betydande prestandaproblem.<br/>            För mer effektiv pixelmanipulation, använd metoden `LoadArgb32Pixels` för att hämta hela pixelarrayen samtidigt. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_52) | Hämtar en proportionell höjd. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_53) | Hämtar en proportionell bredd. |
| [get_skew_angle()](#get_skew_angle__54) |    |
| grayscale() | Transformation av en bild till dess gråskale‑representation |
| [load(file_path)](#load_file_path_55) | Laddar en ny bild från den angivna filen. |
| [load(file_path, load_options)](#load_file_path_load_options_56) | Laddar en ny bild från den angivna filen. |
| [load(stream)](#load_stream_57) | Laddar en ny bild från den angivna strömmen. |
| [load(stream, load_options)](#load_stream_load_options_58) | Laddar en ny bild från den angivna strömmen. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_59) | Laddar 32‑bit ARGB‑pixlar. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_60) | Laddar 64‑bit ARGB‑pixlar. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_61) | Laddar pixlar i CMYK‑format. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_62) | Laddar pixlar i CMYK‑format.<br/>            Denna metod är föråldrad. Använd den mer effektiva [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/)‑metoden. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63) | Laddar 32‑bitars ARGB‑pixlar delvis (i block). |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_64) | Laddar pixlar partiellt i paket. |
| [load_pixels(rectangle)](#load_pixels_rectangle_65) | Laddar pixlar. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66) | Laddar rådata. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67) | Laddar rådata. |
| [merge_layers(bottom_layer, top_layer)](#merge_layers_bottom_layer_top_layer_68) | Slår ihop lagren. |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_69) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_70) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_71) | Ersätter en färg med en annan med tillåten skillnad och bevarar original‑alphavärdet för att spara mjuka kanter. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_72) | Ersätter en färg med en annan med tillåten skillnad och bevarar original‑alphavärdet för att spara mjuka kanter. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_73) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar original‑alfavärdet för att spara mjuka kanter.<br/>            Obs: om du använder den på bilder utan transparens kommer alla färger att ersättas med en enda. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_74) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar original‑alfavärdet för att spara mjuka kanter.<br/>            Obs: om du använder den på bilder utan transparens kommer alla färger att ersättas med en enda. |
| [resize(new_width, new_height)](#resize_new_width_new_height_75) | Ändrar storlek på bilden. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) används. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_76) | Ändrar storlek på bilden. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_77) | Ändrar storlek på bilden. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_78) | Ändrar bildens höjd proportionellt. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_79) | Ändrar bildens höjd proportionellt. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_80) | Ändrar bildens höjd proportionellt. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_81) | Ändrar bildens bredd proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) används. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_82) | Ändrar bildens bredd proportionellt. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_83) | Ändrar bildens bredd proportionellt. |
| [rotate(angle)](#rotate_angle_84) | Rotera bilden kring centrum. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_85) | Rotera bilden kring centrum. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_86) | Roterar, vänder eller roterar och vänder bilden. |
| save() | Sparar bilddata till den underliggande strömmen. |
| [save(file_path)](#save_file_path_87) | Sparar objektets data till den angivna filplatsen. |
| [save(file_path, options)](#save_file_path_options_88) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_89) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| [save(file_path, over_write)](#save_file_path_over_write_90) | Sparar objektets data till den angivna filplatsen. |
| [save(stream)](#save_stream_91) | Sparar objektets data till den angivna strömmen. |
| [save(stream, options_base)](#save_stream_options_base_92) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_93) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_94) | Sparar de 32-bitars ARGB-pixlarna. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_95) | Sparar pixlar (format-specifik metod). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_96) | Sparar rådata. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_97) | Ställer in en 32-bitars ARGB-pixel för bilden på den angivna positionen. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_98) | Ställer in bildpaletten. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_99) | Ställer in en bildpixel för den angivna positionen. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_100) | Ställer in upplösningen för detta [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| [to_bitmap()](#to_bitmap__101) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_103) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |


### Constructor: PsdImage(path) {#PsdImage_path_1}


```
 PsdImage(path) 
```

Initierar en ny instans av klassen [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) från angiven sökväg för rasterbild (inte psd‑bild i sökvägen). Används för att initiera psd‑bild med standardparametrar - färgläge - rgb, 4 kanaler, 8 bit per kanal, komprimering - Raw.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sökväg | string | Sökvägen för att läsa in pixel‑ och palettdata från och initiera med. |

### Constructor: PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2}


```
 PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Initierar en ny instans av klassen [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) från angiven sökväg för rasterbild (inte psd‑bild i sökvägen) med konstruktörsparametrar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sökväg | string | Sökvägen för att läsa in pixel‑ och palettdata från och initiera med. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Färgläget. |
| channel_bit_depth | short | PSD‑bitdjupet per kanal. |
| kanaler | short | Antalet PSD‑kanaler. |
| psd_version | int | PSD-versionen. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Komprimeringen att använda. |

### Constructor: PsdImage(raster_image) {#PsdImage_raster_image_3}


```
 PsdImage(raster_image) 
```

Initierar en ny instans av klassen [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) från befintlig rasterbild (inte psd‑bild) med RGB‑färgläge, 4 kanaler, 8 bitar/kanal och ingen komprimering.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Bilden att läsa in pixel‑ och palettdata från och initiera med. |

### Constructor: PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4}


```
 PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Initierar en ny instans av klassen [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) från befintlig rasterbild (inte psd‑bild) med konstruktörsparametrar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Bilden att läsa in pixel‑ och palettdata från och initiera med. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Färgläget. |
| channel_bit_depth | short | PSD‑bitdjupet per kanal. |
| kanaler | short | Antalet PSD‑kanaler. |
| psd_version | int | PSD-versionen. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Komprimeringen att använda. |

### Constructor: PsdImage(stream) {#PsdImage_stream_5}


```
 PsdImage(stream) 
```

Initierar en ny instans av klassen [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) från angiven sökväg för rasterbild (inte psd‑bild i ström). Används för att initiera psd‑bild med standardparametrar - färgläge - rgb, 4 kanaler, 8 bit per kanal, komprimering - Raw.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen att läsa in pixel‑ och palettdata från och initiera med. |

### Constructor: PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6}


```
 PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Initierar en ny instans av klassen [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) från angiven sökväg för rasterbild (inte psd‑bild i ström) med konstruktörsparametrar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen att läsa in pixel‑ och palettdata från och initiera med. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Färgläget. |
| channel_bit_depth | short | PSD‑bitdjupet per kanal. |
| kanaler | short | Antalet PSD‑kanaler. |
| psd_version | int | PSD-versionen. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Komprimeringen att använda. |

### Constructor: PsdImage(width, height) {#PsdImage_width_height_7}


```
 PsdImage(width, height) 
```

Initierar en ny instans av klassen [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) med angiven bredd och höjd. Används för att initiera en tom psd‑bild.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int | Bildens bredd. |
| height | int | Bildens höjd. |

### Constructor: PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8}


```
 PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Initierar en ny instans av klassen [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) med angiven bredd, höjd, palett, färgläge, antal kanaler och kanalernas bitlängd samt angivna komprimeringslägesparametrar. Används för att initiera en tom psd‑bild.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int | Bildens bredd. |
| height | int | Bildens höjd. |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Färgpaletten. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Färgläget. |
| channel_bit_depth | short | PSD‑bitdjupet per kanal. |
| kanaler | short | Antalet PSD‑kanaler. |
| psd_version | int | PSD-versionen. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Komprimeringen att använda. |

### Method: add_black_white_adjustment_layer() {#add_black_white_adjustment_layer__1}


```
 add_black_white_adjustment_layer() 
```

Lägger till svartvitt justeringslager.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [BlackWhiteAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/) | Det skapade svart‑vita justeringslagret. |


### Method: add_brightness_contrast_adjustment_layer(brightness, contrast) {#add_brightness_contrast_adjustment_layer_brightness_contrast_2}


```
 add_brightness_contrast_adjustment_layer(brightness, contrast) 
```

Lägger till ljusstyrka/kontrast justeringslager.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ljusstyrka | int | Ljusstyrkan. |
| kontrast | int | Kontrasten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [BrightnessContrastLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer/) | Skapat ljusstyrka/kontrast‑lager |


### Method: add_channel_mixer_adjustment_layer() {#add_channel_mixer_adjustment_layer__3}


```
 add_channel_mixer_adjustment_layer() 
```

Lägger till kanalblandare justeringslager med standardparametrar

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ChannelMixerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer/) | Tillagt Channel Mixer‑lager |


### Method: add_color_balance_adjustment_layer() {#add_color_balance_adjustment_layer__4}


```
 add_color_balance_adjustment_layer() 
```

Lägger till färgbalansjusteringslager.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ColorBalanceAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/) | Ett nyss skapat färgbalans‑lager. |


### Method: add_curves_adjustment_layer() {#add_curves_adjustment_layer__5}


```
 add_curves_adjustment_layer() 
```

Lägger till kurvjusteringslager.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) | Skapade [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) lager |


### Method: add_exposure_adjustment_layer(exposure, offset, gamma_correction) {#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6}


```
 add_exposure_adjustment_layer(exposure, offset, gamma_correction) 
```

Lägger till exponeringsjusteringslager.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| exponering | float | Exponeringen. |
| offset | float | Förskjutningen. |
| gamma_correction | float | Gamma-korrektionen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ExposureLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer/) | Skapade exponeringjusteringslager |


### Method: add_gradient_map_adjustment_layer() {#add_gradient_map_adjustment_layer__7}


```
 add_gradient_map_adjustment_layer() 
```

Lägger till GradientMap-justeringslager.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [GradientMapLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/) | GradientMap-instans. |


### Method: add_hue_saturation_adjustment_layer() {#add_hue_saturation_adjustment_layer__8}


```
 add_hue_saturation_adjustment_layer() 
```

Lägger till nyans/mättnad justeringslager.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [HueSaturationLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer/) | Ett nyss skapat nyans/mättnadslager. |


### Method: add_invert_adjustment_layer() {#add_invert_adjustment_layer__9}


```
 add_invert_adjustment_layer() 
```

Lägger till ett inverteringsjusteringslager.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [InvertAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/) | Det skapade inverteringslagret |


### Method: add_layer(layer) {#add_layer_layer_10}


```
 add_layer(layer) 
```

Lägger till lagret.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Lagret. |

### Method: add_layer_group(group_name, index, start_behaviour) {#add_layer_group_group_name_index_start_behaviour_11}


```
 add_layer_group(group_name, index, start_behaviour) 
```

Lägger till lagergruppen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| group_name | string | Gruppens namn. |
| index | int | Index för lagret att infoga efter. |
| start_behaviour | bool | om den är inställd på <c>true</c> [start behaviour] så kommer gruppen att vara i öppet läge vid start, annars i minimerat läge. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | Öppnar grupplager |


### Method: add_levels_adjustment_layer() {#add_levels_adjustment_layer__12}


```
 add_levels_adjustment_layer() 
```

Lägger till nivåjusteringslager.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [LevelsLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer/) | Ett nyss skapat nivåer-lager. |


### Method: add_photo_filter_layer(color) {#add_photo_filter_layer_color_13}


```
 add_photo_filter_layer(color) 
```

Lägger till fotofilterlager.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Färgen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PhotoFilterLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer/) | Skapade PhotoFilter-lager |


### Method: add_posterize_adjustment_layer() {#add_posterize_adjustment_layer__14}


```
 add_posterize_adjustment_layer() 
```

Lägger till posteriseringsjusteringslager.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PosterizeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/) | PosterizeLayer-instans. |


### Method: add_regular_layer() {#add_regular_layer__15}


```
 add_regular_layer() 
```

Lägger till ett nytt vanligt lager.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Skapade vanligt lager. |


### Method: add_selective_color_adjustment_layer() {#add_selective_color_adjustment_layer__16}


```
 add_selective_color_adjustment_layer() 
```

Lägger till selektiv färgjusteringslager.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [SelectiveColorLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer/) | Det skapade selektiva färgjusteringslagret. |


### Method: add_shape_layer() {#add_shape_layer__17}


```
 add_shape_layer() 
```

Lägg till ett tomt Shape‑layer.<br/>            Utan banor. De bör läggas till shape‑lagret innan sparning.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | ShapeLayer-instans. |


### Method: add_text_layer(text, rect) {#add_text_layer_text_rect_18}


```
 add_text_layer(text, rect) 
```

Lägger till ett nytt Text‑layer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| text | string | Lagrets text. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Lagrets rektangel. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | Skapade textlager. |


### Method: add_threshold_adjustment_layer() {#add_threshold_adjustment_layer__19}


```
 add_threshold_adjustment_layer() 
```

Lägger till Threshold‑justeringslagret.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ThresholdLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/) | Det skapade tröskeljusteringslagret. |


### Method: add_vibrance_adjustment_layer() {#add_vibrance_adjustment_layer__20}


```
 add_vibrance_adjustment_layer() 
```

Lägger till Vibrance‑justeringslagret.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VibranceLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/) | Ett nyss skapat vibranslag. |


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_21}


```
 adjust_brightness(brightness) 
```

Justering av bildens ljusstyrka.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ljusstyrka | int | Ljusstyrkevärde. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_22}


```
 adjust_contrast(contrast) 
```

Bildkontrast

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| kontrast | float | Kontrastvärde (i intervallet [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_23}


```
 adjust_gamma(gamma) 
```

Gammakorrigering av en bild.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| gamma | float | Gamma för röd, grön och blå kanalers koefficient |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_24}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Gammakorrigering av en bild.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| gamma_red | float | Gamma för röd kanalkoefficient |
| gamma_green | float | Gamma för grön kanalkoefficient |
| gamma_blue | float | Gamma för blå kanalkoefficient |

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_25}


```
 binarize_bradley(brightness_difference) 
```

Binärisering av en bild med Bradleys adaptiva tröskelalgoritm med integralbildeströskling.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brightness_difference | double | Ljusstyrkeskillnaden mellan pixel och medelvärdet av ett s x s fönster av pixlar centrerat kring denna pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_26}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binärisering av en bild med Bradleys adaptiva tröskelalgoritm med integralbildeströskling.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brightness_difference | double | Ljusstyrkeskillnaden mellan pixel och medelvärdet av ett s x s fönster av pixlar centrerat kring denna pixel. |
| window_size | int | Storleken på ett s x s fönster av pixlar centrerat kring denna pixel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_27}


```
 binarize_fixed(threshold) 
```

Binärisering av en bild med fördefinierad tröskel.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tröskelvärde | byte | Tröskelvärde. Om motsvarande gråvärde för en pixel är större än tröskeln, tilldelas ett värde på 255, annars 0. |

### Method: can_load(file_path)  [static] {#can_load_file_path_28}


```
 can_load(file_path) 
```

Avgör om bilden kan läsas in från den angivna filsökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om bilden kan läsas in från den angivna filen; annars <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_29}


```
 can_load(file_path, load_options) 
```

Avgör om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna öppningsalternativen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om bilden kan läsas in från den angivna filen; annars <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_30}


```
 can_load(stream) 
```

Avgör om bilden kan läsas in från den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om bilden kan läsas in från den angivna strömmen; annars <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_31}


```
 can_load(stream, load_options) 
```

Avgör om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna <paramref name="loadOptions" />.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen att läsa från. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om bilden kan läsas in från den angivna strömmen; annars <c>false</c>. |


### Method: can_save(options) {#can_save_options_32}


```
 can_save(options) 
```

Avgör om bilden kan sparas till det angivna filformatet som representeras av de medföljande sparalternativen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Sparaalternativen att använda. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om bilden kan sparas till det angivna filformatet som representeras av de överförda sparaalternativen; annars <c>false</c>. |


### Method: convert(new_options) {#convert_new_options_33}


```
 convert(new_options) 
```

Konverterar detta bildformat till det som anges i alternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | De nya alternativen. |

### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_34}


```
 create(image_options, width, height) 
```

Skapar en ny bild med de angivna skapalternativen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Bildalternativen. |
| width | int | Bredden. |
| height | int | Höjden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Den nyss skapade bilden. |


### Method: crop(rectangle) {#crop_rectangle_35}


```
 crop(rectangle) 
```

Beskär bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_36}


```
 dither(dithering_method, bits_count) 
```

Utför dithering på den aktuella bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | Dithermetoden. |
| bits_count | int | Det slutgiltiga bitantalet för dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_37}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Utför dithering på den aktuella bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | Dithermetoden. |
| bits_count | int | Det slutgiltiga bitantalet för dithering. |
| custom_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Den anpassade paletten för dithering. |

### Method: filter(rectangle, options) {#filter_rectangle_options_38}


```
 filter(rectangle, options) 
```

Filtrerar den angivna rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln. |
| options | [FilterOptionsBase](/psd/python-net/aspose.psd.imagefilters.filteroptions/filteroptionsbase/) | Alternativen. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_39}


```
 get_argb_32_pixel(x, y) 
```

Hämtar en 32-bit ARGB-pixel från bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | Pixelns x-position. |
| y | int | Pixelns y-position. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Den 32-bitars ARGB-pixeln för den angivna platsen. |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_40}


```
 get_default_argb_32_pixels(rectangle) 
```

Hämtar standardarrayen för 32-bit ARGB-pixlar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att hämta pixlar för. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Standardpixelarrayen. |


### Method: get_default_options(args) {#get_default_options_args_41}


```
 get_default_options(args) 
```

Hämtar standardalternativen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| args | object | Argumenten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Standardalternativ |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_42}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Hämtar standardpixelarrayen med hjälp av partiell pixel‑laddare.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att hämta pixlar för. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Den partiella pixel‑laddaren. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

Hämtar standardarrayen för rådata med hjälp av partiell pixel‑laddare.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att hämta pixlar för. |
| partial_raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Den partiella rådata‑laddaren. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Rådata‑inställningarna. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_44}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

Hämtar standardarrayen för rådata.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln för att hämta rådata för. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Rådata‑inställningarna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| byte | Standard‑rådataarrayen. |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_45}


```
 get_file_format(file_path) 
```

Hämtar filformatet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Det bestämda filformatet. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_46}


```
 get_file_format(stream) 
```

Hämtar filformatet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Det bestämda filformatet. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_47}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Hämtar rektangeln som passar den aktuella bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln för att hämta en passande rektangel för. |
| pixlar | int | De 32‑bitars ARGB‑pixlarna. |
| width | int | Objektets bredd. |
| height | int | Objektets höjd. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Den passande rektangeln eller ett undantag om ingen passande rektangel kan hittas. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_48}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Hämtar rektangeln som passar den aktuella bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln för att hämta en passande rektangel för. |
| width | int | Objektets bredd. |
| height | int | Objektets höjd. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Den passande rektangeln eller ett undantag om ingen passande rektangel kan hittas. |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_49}


```
 get_modify_date(use_default) 
```

Hämtar datum och tid då resursbilden senast ändrades.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| use_default | bool | om den är satt till <c>true</c> används informationen från FileInfo som standardvärde. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| datetime | Datumet och tiden då resursbilden senast ändrades. |


### Method: get_original_options() {#get_original_options__50}


```
 get_original_options() 
```

Hämtar alternativen baserat på originalfilens inställningar.<br/>            Detta kan vara användbart för att behålla bitdjup och andra parametrar i originalbilden oförändrade.<br/>            Till exempel, om vi laddar en svart‑vit PNG‑bild med 1 bit per pixel och sedan sparar den med hjälp av<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/)‑metoden, kommer en PNG‑utdata med 8‑bit per pixel att skapas.<br/>            För att undvika detta och spara PNG‑bilden med 1‑bit per pixel, använd den här metoden för att hämta motsvarande sparalternativ och skicka dem<br/>            till [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/)‑metoden som den andra parametern.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Alternativen baserade på de ursprungliga filinställningarna. |


### Method: get_pixel(x, y) {#get_pixel_x_y_51}


```
 get_pixel(x, y) 
```

Hämtar en bildpixel.<br/>            Prestandavarning: Undvik att använda denna metod för att iterera över alla bildpixlar eftersom det kan leda till betydande prestandaproblem.<br/>            För mer effektiv pixelmanipulation, använd metoden `LoadArgb32Pixels` för att hämta hela pixelarrayen samtidigt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | Pixelns x-position. |
| y | int | Pixelns y-position. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Pixelns färg för den angivna platsen. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_52}


```
 get_proportional_height(width, height, new_width) 
```

Hämtar en proportionell höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int | Bredden. |
| height | int | Höjden. |
| new_width | int | Den nya bredden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Den proportionella höjden. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_53}


```
 get_proportional_width(width, height, new_height) 
```

Hämtar en proportionell bredd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int | Bredden. |
| height | int | Höjden. |
| new_height | int | Den nya höjden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Den proportionella bredden. |


### Method: get_skew_angle() {#get_skew_angle__54}


```
 get_skew_angle() 
```

  

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_55}


```
 load(file_path) 
```

Laddar en ny bild från den angivna filen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen att ladda bilden från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Den inlästa bilden. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_56}


```
 load(file_path, load_options) 
```

Laddar en ny bild från den angivna filen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen att ladda bilden från. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Den inlästa bilden. |


### Method: load(stream)  [static] {#load_stream_57}


```
 load(stream) 
```

Laddar en ny bild från den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen att ladda bilden från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Den inlästa bilden. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_58}


```
 load(stream, load_options) 
```

Laddar en ny bild från den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen att ladda bilden från. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Den inlästa bilden. |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_59}


```
 load_argb_32_pixels(rectangle) 
```

Laddar 32‑bit ARGB‑pixlar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att ladda pixlar från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Den inlästa 32‑bitars ARGB‑pixelarrayen. |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_60}


```
 load_argb_64_pixels(rectangle) 
```

Laddar 64‑bit ARGB‑pixlar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att ladda pixlar från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| long | Den inlästa 64‑bitars ARGB‑pixelarrayen. |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_61}


```
 load_cmyk_32_pixels(rectangle) 
```

Laddar pixlar i CMYK‑format.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att ladda pixlar från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | De inlästa CMYK‑pixlarna presenteras som 32‑bitars heltalsvärden. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_62}


```
 load_cmyk_pixels(rectangle) 
```

Laddar pixlar i CMYK‑format.<br/>            Denna metod är föråldrad. Använd den mer effektiva [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/)‑metoden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att ladda pixlar från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Den inlästa CMYK‑pixelarrayen. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Laddar 32‑bitars ARGB‑pixlar delvis (i block).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att ladda pixlar från. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Den partiella pixel‑laddaren. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_64}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Laddar pixlar partiellt i paket.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Den önskade rektangeln. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | Pixel‑laddaren. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_65}


```
 load_pixels(rectangle) 
```

Laddar pixlar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att ladda pixlar från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Den laddade pixelarrayen. |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

Laddar rådata.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att ladda rådata från. |
| dest_image_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Dest‑bildens gränser. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Rådatainställningarna att använda för laddade data. Observera att om data inte är i det angivna formatet kommer datakonvertering att utföras. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Rådata‑laddaren. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Laddar rådata.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att ladda rådata från. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Rådatainställningarna att använda för laddade data. Observera att om data inte är i det angivna formatet kommer datakonvertering att utföras. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Rådata‑laddaren. |

### Method: merge_layers(bottom_layer, top_layer) {#merge_layers_bottom_layer_top_layer_68}


```
 merge_layers(bottom_layer, top_layer) 
```

Slår ihop lagren.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bottom_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Det nedre lagret. |
| top_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Det övre lagret. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Nedre lager efter sammanslagning |


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_69}


```
 read_argb_32_scan_line(scan_line_index) 
```

Läser hela skanningslinjen med det angivna skanningslinjeindexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scan_line_index | int | Nollbaserat index för skanningslinjen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Skanningslinjens 32‑bit ARGB‑färgvärdesarray. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_70}


```
 read_scan_line(scan_line_index) 
```

Läser hela skanningslinjen med det angivna skanningslinjeindexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scan_line_index | int | Nollbaserat index för skanningslinjen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Skanningslinjens pixel‑färgvärdesarray. |


### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_71}


```
 replace_color(old_color, old_color_diff, new_color) 
```

Ersätter en färg med en annan med tillåten skillnad och bevarar original‑alphavärdet för att spara mjuka kanter.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| old_color | [Color](/psd/python-net/aspose.psd/color) |  |
| old_color_diff | byte | Tillåten skillnad i gammal färg för att kunna bredda ersatt färgton. |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_72}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

Ersätter en färg med en annan med tillåten skillnad och bevarar original‑alphavärdet för att spara mjuka kanter.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| old_color_argb | int | Gammalt färg-ARGB‑värde som ska ersättas. |
| old_color_diff | byte | Tillåten skillnad i gammal färg för att kunna bredda ersatt färgton. |
| new_color_argb | int | Nytt färg-ARGB‑värde att ersätta den gamla färgen med. |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_73}


```
 replace_non_transparent_colors(new_color) 
```

Ersätter alla icke‑transparenta färger med en ny färg och bevarar original‑alfavärdet för att spara mjuka kanter.<br/>            Obs: om du använder den på bilder utan transparens kommer alla färger att ersättas med en enda.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_74}


```
 replace_non_transparent_colors(new_color_argb) 
```

Ersätter alla icke‑transparenta färger med en ny färg och bevarar original‑alfavärdet för att spara mjuka kanter.<br/>            Obs: om du använder den på bilder utan transparens kommer alla färger att ersättas med en enda.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_color_argb | int | Nytt färg‑ARGB‑värde att ersätta icke‑transparenta färger med. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_75}


```
 resize(new_width, new_height) 
```

Ändrar storlek på bilden. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_76}


```
 resize(new_width, new_height, resize_type) 
```

Ändrar storlek på bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Typ av storleksändring. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_77}


```
 resize(new_width, new_height, settings) 
```

Ändrar storlek på bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Inställningar för storleksändring. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_78}


```
 resize_height_proportionally(new_height) 
```

Ändrar bildens höjd proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_79}


```
 resize_height_proportionally(new_height, resize_type) 
```

Ändrar bildens höjd proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Typ av storleksändring. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_80}


```
 resize_height_proportionally(new_height, settings) 
```

Ändrar bildens höjd proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Inställningar för bildstorleksändring. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_81}


```
 resize_width_proportionally(new_width) 
```

Ändrar bildens bredd proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_82}


```
 resize_width_proportionally(new_width, resize_type) 
```

Ändrar bildens bredd proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Typ av storleksändring. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_83}


```
 resize_width_proportionally(new_width, settings) 
```

Ändrar bildens bredd proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Inställningar för bildstorleksändring. |

### Method: rotate(angle) {#rotate_angle_84}


```
 rotate(angle) 
```

Rotera bilden kring centrum.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_85}


```
 rotate(angle, resize_proportionally, background_color) 
```

Rotera bilden kring centrum.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |
| resize_proportionally | bool | om den är satt till <c>true</c> kommer bildens storlek att ändras enligt den roterade rektangelns (hörnpunkternas) projektioner, i annat fall lämnas dimensionerna orörda och endast bildens interna innehåll roteras. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | Bakgrundens färg. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_86}


```
 rotate_flip(rotate_flip_type) 
```

Roterar, vänder eller roterar och vänder bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Typ av rotations‑spegelvändning. |

### Method: save(file_path) {#save_file_path_87}


```
 save(file_path) 
```

Sparar objektets data till den angivna filplatsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara objektets data till. |

### Method: save(file_path, options) {#save_file_path_options_88}


```
 save(file_path, options) 
```

Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Alternativen. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_89}


```
 save(file_path, options, bounds_rectangle) 
```

Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Alternativen. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Destinationens bildgränsrektangel. Ställ in den tomma rektangeln för att använda källgränserna. |

### Method: save(file_path, over_write) {#save_file_path_over_write_90}


```
 save(file_path, over_write) 
```

Sparar objektets data till den angivna filplatsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara objektets data till. |
| over_write | bool | om den är satt till <c>true</c> skriv över filens innehåll, annars kommer data att läggas till. |

### Method: save(stream) {#save_stream_91}


```
 save(stream) 
```

Sparar objektets data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen för att spara objektets data till. |

### Method: save(stream, options_base) {#save_stream_options_base_92}


```
 save(stream, options_base) 
```

Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen för att spara bildens data till. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Sparalternativen. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_93}


```
 save(stream, options_base, bounds_rectangle) 
```

Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen för att spara bildens data till. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Sparalternativen. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Destinationens bildgränser rektangel. Ställ in den tomma rektangeln för att använda källgränserna. |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_94}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Sparar de 32-bitars ARGB-pixlarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att spara pixlar till. |
| pixlar | int | Den 32-bitars ARGB-pixelarrayen. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_95}


```
 save_pixels(rectangle, pixels) 
```

Sparar pixlar (format-specifik metod).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att spara pixlar till. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Den 32-bitars ARGB-pixelarrayen. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_96}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

Sparar rådata.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | byte | Den råa datan. |
| data_offset | int | Startoffset för rådata. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rådatarektangeln. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Rådatainställningarna som datan är i. |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_97}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

Ställer in en 32-bitars ARGB-pixel för bilden på den angivna positionen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | Pixelns x-position. |
| y | int | Pixelns y-position. |
| argb_32_color | int | Den 32-bitars ARGB-pixeln för den angivna positionen. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_98}


```
 set_palette(palette, update_colors) 
```

Ställer in bildpaletten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Paletten att ställa in. |
| update_colors | bool | Om den är satt till <c>true</c> uppdateras färgerna enligt den nya paletten; annars förblir färgindexen oförändrade. Observera att oförändrade index kan krascha bilden vid inläsning om vissa index saknar motsvarande palettposter. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_99}


```
 set_pixel(x, y, color) 
```

Ställer in en bildpixel för den angivna positionen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | Pixelns x-position. |
| y | int | Pixelns y-position. |
| color | [Color](/psd/python-net/aspose.psd/color) | Pixelns färg för den angivna positionen. |

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_100}


```
 set_resolution(dpi_x, dpi_y) 
```

Ställer in upplösningen för detta [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dpi_x | double | Den horisontella upplösningen, i punkter per tum, för [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| dpi_y | double | Den vertikala upplösningen, i punkter per tum, för [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |

### Method: to_bitmap() {#to_bitmap__101}


```
 to_bitmap() 
```

  

**Returns**

| Typ | Beskrivning |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Skriver hela skanningslinjen till det angivna skanningslinjeindexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scan_line_index | int | Nollbaserat index för skanningslinjen. |
| argb_32_pixels | int | Den 32-bitars ARGB-färgarrayen att skriva. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_103}


```
 write_scan_line(scan_line_index, pixels) 
```

Skriver hela skanningslinjen till det angivna skanningslinjeindexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scan_line_index | int | Nollbaserat index för skanningslinjen. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Pixelfärgarrayen att skriva. |

