---
title: "Lagerklass"
type: docs
weight: 930
url: /sv/python-net/aspose.psd.fileformats.psd.layers/layer/
---

**Summary:** The psd layer.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.Layer

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [Layer()](#Layer__1) | Initierar en ny instans av klassen [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). Konstruktor för lat initiering. |
| [Layer(bounds, red_bytes, green_bytes, blue_bytes, name)](#Layer_bounds_red_bytes_green_bytes_blue_bytes_name_2) | Initierar en ny instans av klassen [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) från bytearrayer. |
| [Layer(image, dispose_image)](#Layer_image_dispose_image_3) | Initierar en ny instans av klassen [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). |
| [Layer(stream)](#Layer_stream_4) | Initierar en ny instans av klassen [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| BLEND_SIGNATURE [static] | int | r | Representerar blandningslägets signatur. |
| LAYER_HEADER_SIZE [static] | int | r | Lagrets huvudstorlek. |
| auto_adjust_palette | bool | r/w | Hämtar eller anger ett värde som indikerar om automatisk justering av palett. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Hämtar eller anger ett värde för bakgrundsfärgen. |
| bits_per_pixel | int | r | Hämtar antalet bildbitar per pixel. |
| blend_clipped_elements | bool | r/w | Hämtar eller anger blandningen av klippt element. |
| blend_mode_key | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Hämtar eller anger nyckeln för blandningsläget. |
| blend_mode_signature | int | r | Hämtar blandningslägets signatur. |
| blending_options | [BlendingOptions](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/) | r | Hämtar blandningsalternativen. |
| nedre | int | r/w | Hämtar eller anger den nedre lagrets position. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Hämtar objektets gränser. |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| channel_information | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r/w | Hämtar eller anger kanalinformationen. |
| channels_count | ushort | r | Hämtar lagrets kanalantal. |
| clipping | byte | r/w | Hämtar eller anger lagrets beskärning. 0 = bas, 1 = icke-bas. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Hämtar [Image](/psd/python-net/aspose.psd/image/)‑behållaren. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Hämtar objektets datastream. |
| display_name | string | r/w | Hämtar eller anger lagrets visningsnamn. |
| borttagen | bool | r | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| extra_length | int | r | Hämtar lagrets extra informationslängd i byte. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Hämtar ett värde för filformatet |
| fill_opacity | int | r/w | Hämtar eller anger fyllnadens opacitet. |
| filler | byte | r/w | Hämtar eller anger lagrets fyllnad. |
| flags | [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags) | r/w | Hämtar eller anger lagrets flaggor.<br/>            bit 0 = transparensskyddad;<br/>            bit 1 = synlig;<br/>            bit 2 = föråldrad;<br/>            bit 3 = 1 för Photoshop 5.0 och senare, anger om bit 4 innehåller användbar information;<br/>            bit 4 = pixeldata irrelevant för dokumentets utseende. |
| has_alpha | bool | r | Hämtar ett värde som indikerar om denna instans har alfa. |
| has_background_color | bool | r/w | Hämtar eller anger ett värde som visar om bilden har bakgrundsfärg. |
| has_transparent_color | bool | r/w | Hämtar ett värde som visar om bilden har transparent färg. |
| height | int | r | Hämtar bildens höjd. |
| horizontal_resolution | double | r/w | Hämtar eller anger den horisontella upplösningen, i pixlar per tum, för detta [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| image_opacity | float | r | Hämtar opaciteten för denna bild. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Hämtar eller anger avbrottsövervakaren. |
| is_cached | bool | r | Hämtar ett värde som visar om bilddata för närvarande är cachad. |
| is_raw_data_available | bool | r | Hämtar ett värde som indikerar om inläsning av rådata stöds. |
| is_visible | bool | r/w | Hämtar eller anger ett värde som visar om lagret är synligt |
| is_visible_in_group | bool | r | Hämtar ett värde som visar om detta objekt är synligt i grupp (Om lagret inte är i en grupp betyder det rotgrupp). |
| layer_blending_ranges_data | [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata) | r/w | Hämtar eller anger data för lagerblandningsintervall. |
| layer_creation_date_time | datetime | r/w | Hämtar eller anger lagrets skapelsedatum och tid. |
| layer_lock | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | r/w | Gets or sets the layer lock.<br/>            Note that if flag LayerFlags.TransparencyProtected is set it will be overwritten by layer lock flag.<br/>            To return LayerFlags.TransparencyProtected flag need to apply for layer option layer.Flags | = LayerFlags.TransparencyProtected |
| layer_mask_data | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | r/w | Hämtar eller anger data för lagermasken. |
| layer_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | r | Hämtar lageralternativen. |
| vänster | int | r/w | Hämtar eller anger lagrets vänstra position. |
| längd | int | r | Hämtar den totala lagrets längd i byte. |
| name | string | r/w | Hämtar eller anger lagrets namn. |
| opacity | byte | r/w | Hämtar eller anger lagrets opacitet. 0 = transparent, 255 = ogenomskinlig. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Hämtar eller anger färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| premultiply_components | bool | r/w | Hämtar eller anger ett värde som visar om bildkomponenterna måste vara förmultiplicerade. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | Hämtar eller anger den anpassade färgkonverteraren |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Hämtar det råa dataformatet. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Hämtar de aktuella rådatainställningarna. Observera att när dessa inställningar används laddas data utan konvertering. |
| raw_fallback_index | int | r/w | Hämtar eller anger reservindexet att använda när palettindexet är utanför gränserna |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | Hämtar eller anger den indexerade färgkonverteraren |
| raw_line_size | int | r | Hämtar den råa radstorleken i byte. |
| resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r/w | Hämtar eller anger lagerresurserna. |
| höger | int | r/w | Hämtar eller anger den högra lagerpositionen. |
| sheet_color_highlight | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | r/w | Hämtar eller anger färgmarkeringen för dekorativt blad i lagerlistan. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Hämtar objektets storlek. |
| övre | int | r/w | Hämtar eller anger den översta lagerpositionen. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Hämtar bildens transparenta färg. |
| update_xmp_data | bool | r/w | Hämtar eller anger ett värde som indikerar om XMP-metadata ska uppdateras. |
| use_palette | bool | r | Hämtar ett värde som indikerar om bildpaletten används. |
| use_raw_data | bool | r/w | Hämtar eller anger ett värde som indikerar om rådatainläsning ska användas när rådatainläsning är tillgänglig. |
| vertical_resolution | double | r/w | Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för denna [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| width | int | r | Hämtar bildens bredd. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger XMP-metadata. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_layer_mask(layer_mask)](#add_layer_mask_layer_mask_1) | Lägger till masken till det aktuella lagret. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_2) | Justering av bildens ljusstyrka. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_3) | Bildkontrast |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_4) | Gammakorrigering av en bild. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_5) | Gammakorrigering av en bild. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_6) | Binärisering av en bild med Bradleys adaptiva tröskelalgoritm med integralbildeströskling. |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_7) | Binärisering av en bild med Bradleys adaptiva tröskelalgoritm med integralbildeströskling. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_8) | Binärisering av en bild med fördefinierad tröskel. |
| binarize_otsu() | Binärisering av en bild med Otsu-tröskling. |
| cache_data() | Cachar data och säkerställer att ingen ytterligare datainläsning utförs från den underliggande [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/). |
| [can_load(file_path)](#can_load_file_path_9) | Avgör om bilden kan läsas in från den angivna filsökvägen. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_10) | Avgör om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna öppningsalternativen. |
| [can_load(stream)](#can_load_stream_11) | Avgör om bilden kan läsas in från den angivna strömmen. |
| [can_load(stream, load_options)](#can_load_stream_load_options_12) | Avgör om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna <paramref name="loadOptions" />. |
| [can_save(options)](#can_save_options_13) | Avgör om bilden kan sparas till det angivna filformatet som representeras av de medföljande sparalternativen. |
| [create(image_options, width, height)](#create_image_options_width_height_14) | Skapar en ny bild med de angivna skapalternativen. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_15) | Beskär bilden. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_16) | Utför dithering på den aktuella bilden. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_17) | Utför dithering på den aktuella bilden. |
| [draw_image(location, image)](#draw_image_location_image_18) | Ritar bilden på lagret. |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_19) | Hämtar en 32-bit ARGB-pixel från bilden. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_20) | Hämtar standardarrayen för 32-bit ARGB-pixlar. |
| [get_default_options(args)](#get_default_options_args_21) | Hämtar standardalternativen. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_22) | Hämtar standardpixelarrayen med hjälp av partiell pixel‑laddare. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_23) | Hämtar standardarrayen för rådata med hjälp av partiell pixel‑laddare. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_24) | Hämtar standardarrayen för rådata. |
| [get_file_format(file_path)](#get_file_format_file_path_25) | Hämtar filformatet. |
| [get_file_format(stream)](#get_file_format_stream_26) | Hämtar filformatet. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_27) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_28) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_modify_date(use_default)](#get_modify_date_use_default_29) | Hämtar datum och tid då resursbilden senast ändrades. |
| [get_original_options()](#get_original_options__30) | Hämtar alternativen baserat på originalfilens inställningar.<br/>            Detta kan vara användbart för att behålla bitdjup och andra parametrar i originalbilden oförändrade.<br/>            Till exempel, om vi laddar en svart‑vit PNG‑bild med 1 bit per pixel och sedan sparar den med hjälp av<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/)‑metoden, kommer en PNG‑utdata med 8‑bit per pixel att skapas.<br/>            För att undvika detta och spara PNG‑bilden med 1‑bit per pixel, använd den här metoden för att hämta motsvarande sparalternativ och skicka dem<br/>            till [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/)‑metoden som den andra parametern. |
| [get_pixel(x, y)](#get_pixel_x_y_31) | Hämtar en bildpixel.<br/>            Prestandavarning: Undvik att använda denna metod för att iterera över alla bildpixlar eftersom det kan leda till betydande prestandaproblem.<br/>            För mer effektiv pixelmanipulation, använd metoden `LoadArgb32Pixels` för att hämta hela pixelarrayen samtidigt. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_32) | Hämtar en proportionell höjd. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_33) | Hämtar en proportionell bredd. |
| [get_skew_angle()](#get_skew_angle__34) |    |
| grayscale() | Transformation av en bild till dess gråskale‑representation |
| [load(file_path)](#load_file_path_35) | Laddar en ny bild från den angivna filen. |
| [load(file_path, load_options)](#load_file_path_load_options_36) | Laddar en ny bild från den angivna filen. |
| [load(stream)](#load_stream_37) | Laddar en ny bild från den angivna strömmen. |
| [load(stream, load_options)](#load_stream_load_options_38) | Laddar en ny bild från den angivna strömmen. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_39) | Laddar 32‑bit ARGB‑pixlar. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_40) | Laddar 64‑bit ARGB‑pixlar. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_41) | Laddar pixlar i CMYK‑format. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_42) | Laddar pixlar i CMYK‑format.<br/>            Denna metod är föråldrad. Använd den mer effektiva [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/)‑metoden. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_43) | Laddar 32‑bitars ARGB‑pixlar delvis (i block). |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_44) | Laddar pixlar partiellt i paket. |
| [load_pixels(rectangle)](#load_pixels_rectangle_45) | Laddar pixlar. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_46) | Laddar rådata. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_47) | Laddar rådata. |
| [merge_layer_to(layer_to_merge_into)](#merge_layer_to_layer_to_merge_into_48) | Slår samman lagret med angivet lager. |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_49) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_50) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| [resize(new_width, new_height)](#resize_new_width_new_height_51) | Ändrar storlek på bilden. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) används. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_52) | Ändrar storlek på bilden. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_53) | Ändrar storlek på bilden. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_54) | Ändrar bildens höjd proportionellt. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_55) | Ändrar bildens höjd proportionellt. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_56) | Ändrar bildens höjd proportionellt. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_57) | Ändrar bildens bredd proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) används. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_58) | Ändrar bildens bredd proportionellt. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_59) | Ändrar bildens bredd proportionellt. |
| rotate(angle) |  |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_60) | Rotera bilden kring centrum. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_61) | Roterar, vänder eller roterar och vänder bilden. |
| save() | Sparar bilddata till den underliggande strömmen. |
| [save(file_path)](#save_file_path_62) | Sparar objektets data till den angivna filplatsen. |
| [save(file_path, options)](#save_file_path_options_63) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_64) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| [save(file_path, over_write)](#save_file_path_over_write_65) | Sparar objektets data till den angivna filplatsen. |
| [save(stream)](#save_stream_66) | Sparar objektets data till den angivna strömmen. |
| [save(stream, options_base)](#save_stream_options_base_67) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_68) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_69) | Sparar de 32-bitars ARGB-pixlarna. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_70) | Sparar pixlar (format-specifik metod). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_71) | Sparar rådata. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_72) | Ställer in en 32-bitars ARGB-pixel för bilden på den angivna positionen. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_73) | Ställer in bildpaletten. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_74) | Ställer in en bildpixel för den angivna positionen. |
| set_resolution(dpi_x, dpi_y) |  |
| [shallow_copy()](#shallow_copy__75) | Skapar en ytlig kopia av det aktuella lagret.<br/>            Vänligen <see href="https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx" /> för förklaring. |
| [to_bitmap()](#to_bitmap__76) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_77) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_78) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |


### Constructor: Layer() {#Layer__1}


```
 Layer() 
```

Initierar en ny instans av klassen [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). Konstruktor för lat initiering.

### Constructor: Layer(bounds, red_bytes, green_bytes, blue_bytes, name) {#Layer_bounds_red_bytes_green_bytes_blue_bytes_name_2}


```
 Layer(bounds, red_bytes, green_bytes, blue_bytes, name) 
```

Initierar en ny instans av klassen [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) från bytearrayer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Lagrets gränser. |
| red_bytes | byte | De röda bytena. |
| green_bytes | byte | De gröna byte. |
| blue_bytes | byte | De blå byte. |
| name | string | Lagrets namn. |

### Constructor: Layer(image, dispose_image) {#Layer_image_dispose_image_3}


```
 Layer(image, dispose_image) 
```

Initierar en ny instans av klassen [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Bilden. |
| dispose_image | bool | om inställd på <c>true</c> [dispose image]. |

### Constructor: Layer(stream) {#Layer_stream_4}


```
 Layer(stream) 
```

Initierar en ny instans av klassen [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Bildströmmen |

### Method: add_layer_mask(layer_mask) {#add_layer_mask_layer_mask_1}


```
 add_layer_mask(layer_mask) 
```

Lägger till masken till det aktuella lagret.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer_mask | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | Lagermasken. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_2}


```
 adjust_brightness(brightness) 
```

Justering av bildens ljusstyrka.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ljusstyrka | int | Ljusstyrkevärde. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_3}


```
 adjust_contrast(contrast) 
```

Bildkontrast

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| kontrast | float | Kontrastvärde (i intervallet [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_4}


```
 adjust_gamma(gamma) 
```

Gammakorrigering av en bild.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| gamma | float | Gamma för röd, grön och blå kanalers koefficient |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_5}


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

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_6}


```
 binarize_bradley(brightness_difference) 
```

Binärisering av en bild med Bradleys adaptiva tröskelalgoritm med integralbildeströskling.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brightness_difference | double | Ljusstyrkeskillnaden mellan pixel och medelvärdet av ett s x s fönster av pixlar centrerat kring denna pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_7}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binärisering av en bild med Bradleys adaptiva tröskelalgoritm med integralbildeströskling.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brightness_difference | double | Ljusstyrkeskillnaden mellan pixel och medelvärdet av ett s x s fönster av pixlar centrerat kring denna pixel. |
| window_size | int | Storleken på ett s x s fönster av pixlar centrerat kring denna pixel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

Binärisering av en bild med fördefinierad tröskel.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tröskelvärde | byte | Tröskelvärde. Om motsvarande gråvärde för en pixel är större än tröskeln, tilldelas ett värde på 255, annars 0. |

### Method: can_load(file_path)  [static] {#can_load_file_path_9}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_10}


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


### Method: can_load(stream)  [static] {#can_load_stream_11}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_12}


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


### Method: can_save(options) {#can_save_options_13}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_14}


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


### Method: crop(rectangle) {#crop_rectangle_15}


```
 crop(rectangle) 
```

Beskär bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_16}


```
 dither(dithering_method, bits_count) 
```

Utför dithering på den aktuella bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | Dithermetoden. |
| bits_count | int | Det slutgiltiga bitantalet för dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_17}


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

### Method: draw_image(location, image) {#draw_image_location_image_18}


```
 draw_image(location, image) 
```

Ritar bilden på lagret.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | Platsen. |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Bilden. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_19}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_20}


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


### Method: get_default_options(args) {#get_default_options_args_21}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_22}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Hämtar standardpixelarrayen med hjälp av partiell pixel‑laddare.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att hämta pixlar för. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Den partiella pixel‑laddaren. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_23}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_24}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_25}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_26}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_27}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_28}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_29}


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


### Method: get_original_options() {#get_original_options__30}


```
 get_original_options() 
```

Hämtar alternativen baserat på originalfilens inställningar.<br/>            Detta kan vara användbart för att behålla bitdjup och andra parametrar i originalbilden oförändrade.<br/>            Till exempel, om vi laddar en svart‑vit PNG‑bild med 1 bit per pixel och sedan sparar den med hjälp av<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/)‑metoden, kommer en PNG‑utdata med 8‑bit per pixel att skapas.<br/>            För att undvika detta och spara PNG‑bilden med 1‑bit per pixel, använd den här metoden för att hämta motsvarande sparalternativ och skicka dem<br/>            till [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/)‑metoden som den andra parametern.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Alternativen baserade på de ursprungliga filinställningarna. |


### Method: get_pixel(x, y) {#get_pixel_x_y_31}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_32}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_33}


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


### Method: get_skew_angle() {#get_skew_angle__34}


```
 get_skew_angle() 
```

  

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_35}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_36}


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


### Method: load(stream)  [static] {#load_stream_37}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_38}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_39}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_40}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_41}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_42}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_43}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Laddar 32‑bitars ARGB‑pixlar delvis (i block).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att ladda pixlar från. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Den partiella pixel‑laddaren. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_44}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Laddar pixlar partiellt i paket.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Den önskade rektangeln. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | Pixel‑laddaren. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_45}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_46}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_47}


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

### Method: merge_layer_to(layer_to_merge_into) {#merge_layer_to_layer_to_merge_into_48}


```
 merge_layer_to(layer_to_merge_into) 
```

Slår samman lagret med angivet lager.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer_to_merge_into | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Lagret att slå samman med. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_49}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_50}


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


### Method: resize(new_width, new_height) {#resize_new_width_new_height_51}


```
 resize(new_width, new_height) 
```

Ändrar storlek på bilden. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_52}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_53}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_54}


```
 resize_height_proportionally(new_height) 
```

Ändrar bildens höjd proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_55}


```
 resize_height_proportionally(new_height, resize_type) 
```

Ändrar bildens höjd proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Typ av storleksändring. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_56}


```
 resize_height_proportionally(new_height, settings) 
```

Ändrar bildens höjd proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Inställningar för bildstorleksändring. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_57}


```
 resize_width_proportionally(new_width) 
```

Ändrar bildens bredd proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_58}


```
 resize_width_proportionally(new_width, resize_type) 
```

Ändrar bildens bredd proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Typ av storleksändring. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_59}


```
 resize_width_proportionally(new_width, settings) 
```

Ändrar bildens bredd proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Inställningar för bildstorleksändring. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_60}


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

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_61}


```
 rotate_flip(rotate_flip_type) 
```

Roterar, vänder eller roterar och vänder bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Typ av rotations‑spegelvändning. |

### Method: save(file_path) {#save_file_path_62}


```
 save(file_path) 
```

Sparar objektets data till den angivna filplatsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara objektets data till. |

### Method: save(file_path, options) {#save_file_path_options_63}


```
 save(file_path, options) 
```

Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Alternativen. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_64}


```
 save(file_path, options, bounds_rectangle) 
```

Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Alternativen. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Destinationens bildgränser rektangel. Ställ in den tomma rektangeln för att använda källgränserna. |

### Method: save(file_path, over_write) {#save_file_path_over_write_65}


```
 save(file_path, over_write) 
```

Sparar objektets data till den angivna filplatsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara objektets data till. |
| over_write | bool | om den är satt till <c>true</c> skriv över filens innehåll, annars kommer data att läggas till. |

### Method: save(stream) {#save_stream_66}


```
 save(stream) 
```

Sparar objektets data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen för att spara objektets data till. |

### Method: save(stream, options_base) {#save_stream_options_base_67}


```
 save(stream, options_base) 
```

Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen för att spara bildens data till. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Sparalternativen. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_68}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_69}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Sparar de 32-bitars ARGB-pixlarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att spara pixlar till. |
| pixlar | int | Den 32-bitars ARGB-pixelarrayen. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_70}


```
 save_pixels(rectangle, pixels) 
```

Sparar pixlar (format-specifik metod).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att spara pixlar till. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Den 32-bitars ARGB-pixelarrayen. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_71}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_72}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_73}


```
 set_palette(palette, update_colors) 
```

Ställer in bildpaletten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Paletten att ställa in. |
| update_colors | bool | Om den är satt till <c>true</c> uppdateras färgerna enligt den nya paletten; annars förblir färgindexen oförändrade. Observera att oförändrade index kan krascha bilden vid inläsning om vissa index saknar motsvarande palettposter. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_74}


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

### Method: shallow_copy() {#shallow_copy__75}


```
 shallow_copy() 
```

Skapar en ytlig kopia av det aktuella lagret.<br/>            Vänligen <see href="https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx" /> för förklaring.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | En ytlig kopia av det aktuella lagret. |


### Method: to_bitmap() {#to_bitmap__76}


```
 to_bitmap() 
```

  

**Returns**

| Typ | Beskrivning |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_77}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Skriver hela skanningslinjen till det angivna skanningslinjeindexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scan_line_index | int | Nollbaserat index för skanningslinjen. |
| argb_32_pixels | int | Den 32-bitars ARGB-färgarrayen att skriva. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_78}


```
 write_scan_line(scan_line_index, pixels) 
```

Skriver hela skanningslinjen till det angivna skanningslinjeindexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scan_line_index | int | Nollbaserat index för skanningslinjen. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Pixelfärgarrayen att skriva. |

