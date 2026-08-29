---
title: "RasterImage-klass"
type: docs
weight: 3740
url: /sv/python-net/aspose.psd/rasterimage/
---

**Summary:** Represents a raster image supporting raster graphics operations.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RasterImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, Image

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Hämtar eller anger ett värde som indikerar om automatisk justering av palett. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Hämtar eller anger ett värde för bakgrundsfärgen. |
| bits_per_pixel | int | r | Hämtar antalet bildbitar per pixel. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Hämtar bildens gränser. |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Hämtar [Image](/psd/python-net/aspose.psd/image/)‑behållaren. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Hämtar objektets datastream. |
| borttagen | bool | r | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Hämtar ett värde för filformatet |
| has_alpha | bool | r | Hämtar ett värde som indikerar om denna instans har alfa. |
| has_background_color | bool | r/w | Hämtar eller anger ett värde som visar om bilden har bakgrundsfärg. |
| has_transparent_color | bool | r/w | Hämtar ett värde som visar om bilden har transparent färg. |
| height | int | r | Hämtar bildens höjd. |
| horizontal_resolution | double | r/w | Hämtar eller anger den horisontella upplösningen, i pixlar per tum, för detta [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| image_opacity | float | r | Hämtar opaciteten för denna bild. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Hämtar eller anger avbrottsövervakaren. |
| is_cached | bool | r | Hämtar ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs. |
| is_raw_data_available | bool | r | Hämtar ett värde som indikerar om inläsning av rådata är tillgänglig. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Hämtar eller anger färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| premultiply_components | bool | r/w | Hämtar eller anger ett värde som visar om bildkomponenterna måste vara förmultiplicerade. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | Hämtar eller anger den anpassade färgkonverteraren |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Hämtar det råa dataformatet. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Hämtar de aktuella rådatainställningarna. Observera att när dessa inställningar används laddas data utan konvertering. |
| raw_fallback_index | int | r/w | Hämtar eller anger reservindexet att använda när palettindexet är utanför gränserna |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | Hämtar eller anger den indexerade färgkonverteraren |
| raw_line_size | int | r | Hämtar den råa radstorleken i byte. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Hämtar bildens storlek. |
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
| adjust_brightness(brightness) |  |
| adjust_contrast(contrast) |  |
| adjust_gamma(gamma) |  |
| adjust_gamma(gamma_red, gamma_green, gamma_blue) |  |
| binarize_bradley(brightness_difference) |  |
| binarize_bradley(brightness_difference, window_size) |  |
| binarize_fixed(threshold) |  |
| binarize_otsu() |  |
| cache_data() | Cachar data och säkerställer att ingen ytterligare datainläsning utförs från den underliggande [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/). |
| [can_load(file_path)](#can_load_file_path_1) | Avgör om bilden kan läsas in från den angivna filsökvägen. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | Avgör om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna öppningsalternativen. |
| [can_load(stream)](#can_load_stream_3) | Avgör om bilden kan läsas in från den angivna strömmen. |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | Avgör om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna <paramref name="loadOptions" />. |
| [can_save(options)](#can_save_options_5) | Avgör om bilden kan sparas till det angivna filformatet som representeras av de medföljande sparalternativen. |
| [create(image_options, width, height)](#create_image_options_width_height_6) | Skapar en ny bild med de angivna skapalternativen. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| crop(rectangle) |  |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_7) | Utför dithering på den aktuella bilden. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_8) | Utför dithering på den aktuella bilden. |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_9) | Hämtar en 32-bit ARGB-pixel från bilden. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_10) | Hämtar standardarrayen för 32-bit ARGB-pixlar. |
| [get_default_options(args)](#get_default_options_args_11) | Hämtar standardalternativen. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_12) | Hämtar standardpixelarrayen med hjälp av partiell pixel‑laddare. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_13) | Hämtar standardarrayen för rådata med hjälp av partiell pixel‑laddare. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_14) | Hämtar standardarrayen för rådata. |
| [get_file_format(file_path)](#get_file_format_file_path_15) | Hämtar filformatet. |
| [get_file_format(stream)](#get_file_format_stream_16) | Hämtar filformatet. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_17) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_18) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_modify_date(use_default)](#get_modify_date_use_default_19) | Hämtar datum och tid då resursbilden senast ändrades. |
| [get_original_options()](#get_original_options__20) | Hämtar alternativen baserat på originalfilens inställningar.<br/>            Detta kan vara användbart för att behålla bitdjup och andra parametrar i originalbilden oförändrade.<br/>            Till exempel, om vi laddar en svart‑vit PNG‑bild med 1 bit per pixel och sedan sparar den med hjälp av<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/)‑metoden, kommer en PNG‑utdata med 8‑bit per pixel att skapas.<br/>            För att undvika detta och spara PNG‑bilden med 1‑bit per pixel, använd den här metoden för att hämta motsvarande sparalternativ och skicka dem<br/>            till [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/)‑metoden som den andra parametern. |
| [get_pixel(x, y)](#get_pixel_x_y_21) | Hämtar en bildpixel.<br/>            Prestandavarning: Undvik att använda denna metod för att iterera över alla bildpixlar eftersom det kan leda till betydande prestandaproblem.<br/>            För mer effektiv pixelmanipulation, använd metoden `LoadArgb32Pixels` för att hämta hela pixelarrayen samtidigt. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_22) | Hämtar en proportionell höjd. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_23) | Hämtar en proportionell bredd. |
| [get_skew_angle()](#get_skew_angle__24) |    |
| grayscale() |  |
| [load(file_path)](#load_file_path_25) | Laddar en ny bild från den angivna filen. |
| [load(file_path, load_options)](#load_file_path_load_options_26) | Laddar en ny bild från den angivna filen. |
| [load(stream)](#load_stream_27) | Laddar en ny bild från den angivna strömmen. |
| [load(stream, load_options)](#load_stream_load_options_28) | Laddar en ny bild från den angivna strömmen. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_29) | Laddar 32‑bit ARGB‑pixlar. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_30) | Laddar 64‑bit ARGB‑pixlar. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_31) | Laddar pixlar i CMYK‑format. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_32) | Laddar pixlar i CMYK‑format.<br/>            Denna metod är föråldrad. Använd den mer effektiva [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/)‑metoden. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33) | Laddar 32-bitars ARGB-pixlar delvis i paket. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_34) | Laddar pixlar partiellt i paket. |
| [load_pixels(rectangle)](#load_pixels_rectangle_35) | Laddar pixlar. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_36) | Laddar rådata. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_37) | Laddar rådata. |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_38) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_39) | Läser hela skanningslinjen med det angivna skanningslinjeindexet. |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| [resize(new_width, new_height)](#resize_new_width_new_height_40) | Ändrar storlek på bilden. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) används. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_41) | Ändrar storlek på bilden. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_42) | Ändrar storlek på bilden. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_43) | Ändrar bildens höjd proportionellt. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_44) | Ändrar bildens höjd proportionellt. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_45) | Ändrar bildens höjd proportionellt. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_46) | Ändrar bildens bredd proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) används. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_47) | Ändrar bildens bredd proportionellt. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_48) | Ändrar bildens bredd proportionellt. |
| rotate(angle) |  |
| rotate(angle, resize_proportionally, background_color) |  |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_49) | Roterar, vänder eller roterar och vänder bilden. |
| save() | Sparar bilddata till den underliggande strömmen. |
| [save(file_path)](#save_file_path_50) | Sparar objektets data till den angivna filplatsen. |
| [save(file_path, options)](#save_file_path_options_51) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_52) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| [save(file_path, over_write)](#save_file_path_over_write_53) | Sparar objektets data till den angivna filplatsen. |
| [save(stream)](#save_stream_54) | Sparar objektets data till den angivna strömmen. |
| [save(stream, options_base)](#save_stream_options_base_55) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_56) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_57) | Sparar de 32-bitars ARGB-pixlarna. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_58) | Sparar pixlarna. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_59) | Sparar rådata. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_60) | Ställer in en 32-bitars ARGB-pixel för bilden på den angivna positionen. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_61) | Ställer in bildpaletten. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_62) | Ställer in en bildpixel för den angivna positionen. |
| set_resolution(dpi_x, dpi_y) |  |
| [to_bitmap()](#to_bitmap__63) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_64) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_65) | Skriver hela skanningslinjen till det angivna skanningslinjeindexet. |


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


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


### Method: can_load(stream)  [static] {#can_load_stream_3}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


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


### Method: can_save(options) {#can_save_options_5}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_6}


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


### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_7}


```
 dither(dithering_method, bits_count) 
```

Utför dithering på den aktuella bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | Dithermetoden. |
| bits_count | int | Det slutgiltiga bitantalet för dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_8}


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

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_9}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_10}


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


### Method: get_default_options(args) {#get_default_options_args_11}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_12}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Hämtar standardpixelarrayen med hjälp av partiell pixel‑laddare.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att hämta pixlar för. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Den partiella pixel‑laddaren. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_13}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_14}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_15}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_16}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_17}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_18}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_19}


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


### Method: get_original_options() {#get_original_options__20}


```
 get_original_options() 
```

Hämtar alternativen baserat på originalfilens inställningar.<br/>            Detta kan vara användbart för att behålla bitdjup och andra parametrar i originalbilden oförändrade.<br/>            Till exempel, om vi laddar en svart‑vit PNG‑bild med 1 bit per pixel och sedan sparar den med hjälp av<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/)‑metoden, kommer en PNG‑utdata med 8‑bit per pixel att skapas.<br/>            För att undvika detta och spara PNG‑bilden med 1‑bit per pixel, använd den här metoden för att hämta motsvarande sparalternativ och skicka dem<br/>            till [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/)‑metoden som den andra parametern.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Alternativen baserade på de ursprungliga filinställningarna. |


### Method: get_pixel(x, y) {#get_pixel_x_y_21}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_22}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_23}


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


### Method: get_skew_angle() {#get_skew_angle__24}


```
 get_skew_angle() 
```

  

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_25}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_26}


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


### Method: load(stream)  [static] {#load_stream_27}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_28}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_29}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_30}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_31}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_32}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Laddar 32-bitars ARGB-pixlar delvis i paket.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Den önskade rektangeln. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | 32-bitars ARGB-pixelinläsaren. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_34}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Laddar pixlar partiellt i paket.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Den önskade rektangeln. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | Pixel‑laddaren. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_35}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_36}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_37}


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

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_38}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_39}


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


### Method: resize(new_width, new_height) {#resize_new_width_new_height_40}


```
 resize(new_width, new_height) 
```

Ändrar storlek på bilden. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_41}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_42}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_43}


```
 resize_height_proportionally(new_height) 
```

Ändrar bildens höjd proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_44}


```
 resize_height_proportionally(new_height, resize_type) 
```

Ändrar bildens höjd proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Typ av storleksändring. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_45}


```
 resize_height_proportionally(new_height, settings) 
```

Ändrar bildens höjd proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Inställningar för bildstorleksändring. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_46}


```
 resize_width_proportionally(new_width) 
```

Ändrar bildens bredd proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_47}


```
 resize_width_proportionally(new_width, resize_type) 
```

Ändrar bildens bredd proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Typ av storleksändring. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_48}


```
 resize_width_proportionally(new_width, settings) 
```

Ändrar bildens bredd proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Inställningar för bildstorleksändring. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_49}


```
 rotate_flip(rotate_flip_type) 
```

Roterar, vänder eller roterar och vänder bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Typ av rotera/vänd. |

### Method: save(file_path) {#save_file_path_50}


```
 save(file_path) 
```

Sparar objektets data till den angivna filplatsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara objektets data till. |

### Method: save(file_path, options) {#save_file_path_options_51}


```
 save(file_path, options) 
```

Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Alternativen. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_52}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_53}


```
 save(file_path, over_write) 
```

Sparar objektets data till den angivna filplatsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara objektets data till. |
| over_write | bool | om den är satt till <c>true</c> skriv över filens innehåll, annars kommer data att läggas till. |

### Method: save(stream) {#save_stream_54}


```
 save(stream) 
```

Sparar objektets data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen för att spara objektets data till. |

### Method: save(stream, options_base) {#save_stream_options_base_55}


```
 save(stream, options_base) 
```

Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen för att spara bildens data till. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Sparalternativen. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_56}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_57}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Sparar de 32-bitars ARGB-pixlarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att spara pixlar till. |
| pixlar | int | Den 32-bitars ARGB-pixelarrayen. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_58}


```
 save_pixels(rectangle, pixels) 
```

Sparar pixlarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln att spara pixlar till. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Pixelarrayen. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_59}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_60}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_61}


```
 set_palette(palette, update_colors) 
```

Ställer in bildpaletten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Paletten att ställa in. |
| update_colors | bool | Om den är satt till <c>true</c> uppdateras färgerna enligt den nya paletten; annars förblir färgindexen oförändrade. Observera att oförändrade index kan krascha bilden vid inläsning om vissa index saknar motsvarande palettposter. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_62}


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

### Method: to_bitmap() {#to_bitmap__63}


```
 to_bitmap() 
```

  

**Returns**

| Typ | Beskrivning |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_64}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Skriver hela skanningslinjen till det angivna skanningslinjeindexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scan_line_index | int | Nollbaserat index för skanningslinjen. |
| argb_32_pixels | int | Den 32-bitars ARGB-färgarrayen att skriva. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_65}


```
 write_scan_line(scan_line_index, pixels) 
```

Skriver hela skanningslinjen till det angivna skanningslinjeindexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scan_line_index | int | Nollbaserat index för skanningslinjen. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Pixelfärgarrayen att skriva. |

