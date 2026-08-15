---
title: "Layer Klasse"
type: docs
weight: 930
url: /nl/python-net/aspose.psd.fileformats.psd.layers/layer/
---

**Summary:** The psd layer.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.Layer

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Layer()](#Layer__1) | Initialiseert een nieuw exemplaar van de [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) klasse. Constructor voor luie initialisatie. |
| [Layer(bounds, red_bytes, green_bytes, blue_bytes, name)](#Layer_bounds_red_bytes_green_bytes_blue_bytes_name_2) | Initialiseert een nieuw exemplaar van de [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) klasse vanuit byte-arrays. |
| [Layer(image, dispose_image)](#Layer_image_dispose_image_3) | Initialiseert een nieuw exemplaar van de [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) klasse. |
| [Layer(stream)](#Layer_stream_4) | Initialiseert een nieuw exemplaar van de [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| BLEND_SIGNATURE [static] | int | r | Stelt de blend-modushandtekening voor. |
| LAYER_HEADER_SIZE [static] | int | r | De grootte van de laagheader. |
| auto_adjust_palette | bool | r/w | Haalt op of stelt een waarde in die aangeeft of het palet automatisch wordt aangepast. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Haalt op of stelt een waarde in voor de achtergrondkleur. |
| bits_per_pixel | int | r | Haalt het aantal bits per pixel van de afbeelding op. |
| blend_clipped_elements | bool | r/w | Haalt op of stelt de blending van het bijgesneden element in. |
| blend_mode_key | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | Geeft of stelt de blend‑modussleutel in. |
| blend_mode_signature | int | r | Haalt de blend-modushandtekening op. |
| blending_options | [BlendingOptions](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/) | r | Haalt de mengopties op. |
| bottom | int | r/w | Haalt of stelt de positie van de onderste laag in. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Haalt de grenzen van het object op. |
| buffer_size_hint | int | r/w | Haalt op of stelt de buffergroottehint in, die is gedefinieerd als de maximaal toegestane grootte voor alle interne buffers. |
| channel_information | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r/w | Haalt of stelt de kanaalinformatie in. |
| channels_count | ushort | r | Haalt het aantal kanalen van de laag op. |
| clipping | byte | r/w | Haalt of stelt de laagbijsnijding in. 0 = basis, 1 = niet-basis. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Haalt de [Image](/psd/python-net/aspose.psd/image/) container op. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Haalt de gegevensstroom van het object op. |
| display_name | string | r/w | Haalt of stelt de weergavenaam van de laag in. |
| disposed | bool | r | Geeft een waarde die aangeeft of dit exemplaar is vrijgegeven. |
| extra_length | int | r | Haalt de lengte van extra laaginformatie in bytes op. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Haalt een waarde van bestandsformaat op |
| fill_opacity | int | r/w | Haalt of stelt de vulopaciteit in. |
| filler | byte | r/w | Haalt of stelt de laagvuller in. |
| flags | [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags) | r/w | Haalt of stelt de laagvlaggen in.<br/>            bit 0 = transparantie beschermd;<br/>            bit 1 = zichtbaar;<br/>            bit 2 = verouderd;<br/>            bit 3 = 1 voor Photoshop 5.0 en later, geeft aan of bit 4 nuttige informatie bevat;<br/>            bit 4 = pixelgegevens irrelevant voor het uiterlijk van het document. |
| has_alpha | bool | r | Haalt een waarde op die aangeeft of deze instantie alfa heeft. |
| has_background_color | bool | r/w | Haalt of stelt een waarde in die aangeeft of de afbeelding een achtergrondkleur heeft. |
| has_transparent_color | bool | r/w | Haalt een waarde op die aangeeft of de afbeelding een transparante kleur heeft. |
| hoogte | int | r | Haalt de afbeeldinghoogte op. |
| horizontal_resolution | double | r/w | Haalt of stelt de horizontale resolutie, in pixels per inch, van deze [RasterImage](/psd/python-net/aspose.psd/rasterimage/) in. |
| image_opacity | float | r | Haalt de opaciteit van deze afbeelding op. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Haalt of stelt de onderbrekingsmonitor in. |
| is_cached | bool | r | Haalt een waarde op die aangeeft of afbeeldingsgegevens momenteel in de cache staan. |
| is_raw_data_available | bool | r | Haalt een waarde op die aangeeft of het laden van ruwe gegevens wordt ondersteund. |
| is_visible | bool | r/w | Haalt of stelt een waarde in die aangeeft of de laag zichtbaar is |
| is_visible_in_group | bool | r | Haalt een waarde op die aangeeft of deze instantie zichtbaar is in groep (Als de laag niet in een groep zit, betekent dit de hoofdgroep). |
| layer_blending_ranges_data | [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata) | r/w | Haalt of stelt de laagmengbereiken-gegevens in. |
| layer_creation_date_time | datetime | r/w | Haalt op of stelt de datum en tijd van de laagcreatie in. |
| layer_lock | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | r/w | Gets or sets the layer lock.<br/>            Note that if flag LayerFlags.TransparencyProtected is set it will be overwritten by layer lock flag.<br/>            To return LayerFlags.TransparencyProtected flag need to apply for layer option layer.Flags | = LayerFlags.TransparencyProtected |
| layer_mask_data | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | r/w | Haalt op of stelt de laagmaskergegevens in. |
| layer_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | r | Haalt de laagopties op. |
| left | int | r/w | Haalt op of stelt de linkse laagpositie in. |
| lengte | int | r | Haalt de totale laaglengte op in bytes. |
| name | string | r/w | Haalt op of stelt de laagnaam in. |
| opacity | byte | r/w | Haalt op of stelt de laagdoorzichtigheid in. 0 = transparant, 255 = ondoorzichtig. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Haalt op of stelt het kleurenpalet in. Het kleurenpalet wordt niet gebruikt wanneer pixels direct worden weergegeven. |
| premultiply_components | bool | r/w | Haalt op of stelt een waarde in die aangeeft of de afbeeldingscomponenten voorvermenigvuldigd moeten zijn. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | Haalt op of stelt de aangepaste kleurconverter in. |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Haalt het ruwe gegevensformaat op. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Haalt de huidige ruwe‑gegevensinstellingen op. Let op: bij het gebruik van deze instellingen worden de gegevens geladen zonder conversie. |
| raw_fallback_index | int | r/w | Haalt op of stelt de fallback-index in die moet worden gebruikt wanneer de paletindex buiten de grenzen valt. |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | Haalt op of stelt de geïndexeerde kleurconverter in. |
| raw_line_size | int | r | Haalt de ruwe regelgrootte op in bytes. |
| resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r/w | Haalt op of stelt de laagbronnen in. |
| right | int | r/w | Haalt op of stelt de rechtse laagpositie in. |
| sheet_color_highlight | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | r/w | Haalt op of stelt de decoratieve bladkleurmarkering in de lagenlijst in. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Haalt de objectgrootte op. |
| boven | int | r/w | Haalt op of stelt de bovenste laagpositie in. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Haalt de transparante kleur van de afbeelding op. |
| update_xmp_data | bool | r/w | Haalt op of stelt een waarde in die aangeeft of de XMP-metadata moet worden bijgewerkt. |
| use_palette | bool | r | Haalt een waarde op die aangeeft of het afbeeldingspalet wordt gebruikt. |
| use_raw_data | bool | r/w | Haalt op of stelt een waarde in die aangeeft of ruwe gegevensladen moet worden gebruikt wanneer ruwe gegevensladen beschikbaar is. |
| vertical_resolution | double | r/w | Haalt op of stelt de verticale resolutie, in pixels per inch, van deze [RasterImage](/psd/python-net/aspose.psd/rasterimage/) in. |
| width | int | r | Haalt de breedte van de afbeelding op. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Haalt de XMP-metadata op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_layer_mask(layer_mask)](#add_layer_mask_layer_mask_1) | Voegt het masker toe aan de huidige laag. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_2) | Past de helderheid van de afbeelding aan. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_3) | Afbeeldingscontrast |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_4) | Gamma-correctie van een afbeelding. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_5) | Gamma-correctie van een afbeelding. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_6) | Binarisatie van een afbeelding met Bradley's adaptieve drempelalgoritme met behulp van de integrale afbeeldingdrempel. |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_7) | Binarisatie van een afbeelding met Bradley's adaptieve drempelalgoritme met behulp van de integrale afbeeldingdrempel. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_8) | Binarisatie van een afbeelding met vooraf gedefinieerde drempel. |
| binarize_otsu() | Binarisatie van een afbeelding met Otsu-drempelbepaling. |
| cache_data() | Cachet de gegevens en zorgt ervoor dat er geen extra gegevens worden geladen van de onderliggende [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/). |
| [can_load(file_path)](#can_load_file_path_9) | Bepaalt of de afbeelding kan worden geladen vanaf het opgegeven bestandspad. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_10) | Bepaalt of de afbeelding kan worden geladen vanaf het opgegeven bestandspad en eventueel met de opgegeven openopties. |
| [can_load(stream)](#can_load_stream_11) | Bepaalt of de afbeelding kan worden geladen vanaf de opgegeven stream. |
| [can_load(stream, load_options)](#can_load_stream_load_options_12) | Bepaalt of de afbeelding kan worden geladen vanaf de opgegeven stream en eventueel met de opgegeven <paramref name="loadOptions" />. |
| [can_save(options)](#can_save_options_13) | Bepaalt of de afbeelding kan worden opgeslagen in het opgegeven bestandsformaat dat wordt weergegeven door de meegegeven opslagopties. |
| [create(image_options, width, height)](#create_image_options_width_height_14) | Maakt een nieuwe afbeelding aan met de opgegeven creatieopties. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_15) | Bijsnijden van de afbeelding. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_16) | Voert dithering uit op de huidige afbeelding. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_17) | Voert dithering uit op de huidige afbeelding. |
| [draw_image(location, image)](#draw_image_location_image_18) | Tekent de afbeelding op de laag. |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_19) | Haalt een 32-bit ARGB-pixel van de afbeelding op. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_20) | Haalt de standaard 32-bit ARGB-pixelarray op. |
| [get_default_options(args)](#get_default_options_args_21) | Haalt de standaardopties op. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_22) | Haalt de standaard pixelarray op met behulp van de gedeeltelijke pixelloader. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_23) | Haalt de standaard ruwe gegevensarray op met behulp van de gedeeltelijke pixelloader. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_24) | Haalt de standaard ruwe gegevensarray op. |
| [get_file_format(file_path)](#get_file_format_file_path_25) | Haalt het bestandsformaat op. |
| [get_file_format(stream)](#get_file_format_stream_26) | Haalt het bestandsformaat op. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_27) | Haalt het rechthoek op dat past bij de huidige afbeelding. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_28) | Haalt het rechthoek op dat past bij de huidige afbeelding. |
| [get_modify_date(use_default)](#get_modify_date_use_default_29) | Haalt de datum en tijd op waarop de bronafbeelding voor het laatst is gewijzigd. |
| [get_original_options()](#get_original_options__30) | Haalt de opties op op basis van de oorspronkelijke bestandsinstellingen.<br/>            Dit kan nuttig zijn om de bitsdiepte en andere parameters van de oorspronkelijke afbeelding ongewijzigd te houden.<br/>            Bijvoorbeeld, als we een zwart-witte PNG-afbeelding met 1 bit per pixel laden en deze vervolgens opslaan met de<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) methode, wordt een PNG-uitvoerafbeelding met 8 bits per pixel gegenereerd.<br/>            Om dit te voorkomen en een PNG-afbeelding met 1 bit per pixel op te slaan, gebruik deze methode om de bijbehorende opslagopties op te halen en ze<br/>            door te geven aan de [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) methode als tweede parameter. |
| [get_pixel(x, y)](#get_pixel_x_y_31) | Haalt een afbeeldingspixel op.<br/>            Prestatiewaarschuwing: Vermijd het gebruik van deze methode om over alle afbeeldingspixels te itereren, omdat dit kan leiden tot aanzienlijke prestatieproblemen.<br/>            Voor efficiëntere pixelmanipulatie, gebruik de `LoadArgb32Pixels` methode om de volledige pixelarray in één keer op te halen. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_32) | Haalt een proportionele hoogte op. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_33) | Haalt een proportionele breedte op. |
| [get_skew_angle()](#get_skew_angle__34) |    |
| grayscale() | Transformatie van een afbeelding naar zijn grijstintenrepresentatie |
| [load(file_path)](#load_file_path_35) | Laadt een nieuwe afbeelding vanuit het opgegeven bestand. |
| [load(file_path, load_options)](#load_file_path_load_options_36) | Laadt een nieuwe afbeelding vanuit het opgegeven bestand. |
| [load(stream)](#load_stream_37) | Laadt een nieuwe afbeelding vanuit de opgegeven stream. |
| [load(stream, load_options)](#load_stream_load_options_38) | Laadt een nieuwe afbeelding vanuit de opgegeven stream. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_39) | Laadt 32-bit ARGB-pixels. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_40) | Laadt 64-bit ARGB-pixels. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_41) | Laadt pixels in CMYK-indeling. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_42) | Laadt pixels in CMYK-indeling.<br/>            Deze methode is verouderd. Gebruik alstublieft effectiever de [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) methode. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_43) | Laadt 32-bit ARGB-pixels gedeeltelijk (per blokken). |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_44) | Laadt pixels gedeeltelijk per pakketten. |
| [load_pixels(rectangle)](#load_pixels_rectangle_45) | Laadt pixels. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_46) | Laadt ruwe gegevens. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_47) | Laadt ruwe gegevens. |
| [merge_layer_to(layer_to_merge_into)](#merge_layer_to_layer_to_merge_into_48) | Voegt de laag samen met de opgegeven laag |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_49) | Leest de volledige scanlijn op basis van de opgegeven scanlijnindex. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_50) | Leest de volledige scanlijn op basis van de opgegeven scanlijnindex. |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| [resize(new_width, new_height)](#resize_new_width_new_height_51) | Wijzigt de grootte van de afbeelding. De standaard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wordt gebruikt. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_52) | Wijzigt de grootte van de afbeelding. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_53) | Wijzigt de grootte van de afbeelding. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_54) | Wijzigt de hoogte proportioneel. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_55) | Wijzigt de hoogte proportioneel. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_56) | Wijzigt de hoogte proportioneel. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_57) | Wijzigt de breedte proportioneel. De standaard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wordt gebruikt. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_58) | Wijzigt de breedte proportioneel. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_59) | Wijzigt de breedte proportioneel. |
| rotate(angle) |  |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_60) | Roteer de afbeelding rond het midden. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_61) | Roteert, spiegelt of roteert en spiegelt de afbeelding. |
| save() | Slaat de afbeeldingsgegevens op in de onderliggende stream. |
| [save(file_path)](#save_file_path_62) | Slaat de gegevens van het object op op de opgegeven bestandslocatie. |
| [save(file_path, options)](#save_file_path_options_63) | Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_64) | Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties. |
| [save(file_path, over_write)](#save_file_path_over_write_65) | Slaat de gegevens van het object op op de opgegeven bestandslocatie. |
| [save(stream)](#save_stream_66) | Slaat de gegevens van het object op in de opgegeven stream. |
| [save(stream, options_base)](#save_stream_options_base_67) | Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_68) | Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_69) | Slaat de 32-bit ARGB-pixels op. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_70) | Slaat pixels op (formaatspecifieke methode). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_71) | Slaat de ruwe gegevens op. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_72) | Stelt een 32-bit ARGB-pixel van de afbeelding in voor de opgegeven positie. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_73) | Stelt het palet van de afbeelding in. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_74) | Stelt een afbeeldingspixel in voor de opgegeven positie. |
| set_resolution(dpi_x, dpi_y) |  |
| [shallow_copy()](#shallow_copy__75) | Maakt een ondiepe kopie van de huidige laag.<br/>            Zie <see href="https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx" /> voor uitleg. |
| [to_bitmap()](#to_bitmap__76) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_77) | Schrijft de volledige scanlijn naar de opgegeven scanlijnindex. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_78) | Schrijft de volledige scanlijn naar de opgegeven scanlijnindex. |


### Constructor: Layer() {#Layer__1}


```
 Layer() 
```

Initialiseert een nieuw exemplaar van de [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) klasse. Constructor voor luie initialisatie.

### Constructor: Layer(bounds, red_bytes, green_bytes, blue_bytes, name) {#Layer_bounds_red_bytes_green_bytes_blue_bytes_name_2}


```
 Layer(bounds, red_bytes, green_bytes, blue_bytes, name) 
```

Initialiseert een nieuw exemplaar van de [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) klasse vanuit byte-arrays.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De grenzen van de laag. |
| red_bytes | byte | De rode bytes. |
| green_bytes | byte | De groene bytes. |
| blue_bytes | byte | De blauwe bytes. |
| name | string | De naam van de laag. |

### Constructor: Layer(image, dispose_image) {#Layer_image_dispose_image_3}


```
 Layer(image, dispose_image) 
```

Initialiseert een nieuw exemplaar van de [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | De afbeelding. |
| dispose_image | bool | indien ingesteld op <c>true</c> [dispose image]. |

### Constructor: Layer(stream) {#Layer_stream_4}


```
 Layer(stream) 
```

Initialiseert een nieuw exemplaar van de [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De afbeeldingsstream |

### Method: add_layer_mask(layer_mask) {#add_layer_mask_layer_mask_1}


```
 add_layer_mask(layer_mask) 
```

Voegt het masker toe aan de huidige laag.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer_mask | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | Het laagmasker. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_2}


```
 adjust_brightness(brightness) 
```

Past de helderheid van de afbeelding aan.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| helderheid | int | Helderheidswaarde. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_3}


```
 adjust_contrast(contrast) 
```

Afbeeldingscontrast

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| contrast | float | Contrastwaarde (in bereik [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_4}


```
 adjust_gamma(gamma) 
```

Gamma-correctie van een afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| gamma | float | Gamma-coëfficiënt voor rode, groene en blauwe kanalen |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_5}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Gamma-correctie van een afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| gamma_red | float | Gamma-coëfficiënt voor rood kanaal |
| gamma_green | float | Gamma-coëfficiënt voor groen kanaal |
| gamma_blue | float | Gamma-coëfficiënt voor blauw kanaal |

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_6}


```
 binarize_bradley(brightness_difference) 
```

Binarisatie van een afbeelding met Bradley's adaptieve drempelalgoritme met behulp van de integrale afbeeldingdrempel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brightness_difference | double | Het helderheidsverschil tussen een pixel en het gemiddelde van een s x s venster van pixels gecentreerd rond deze pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_7}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarisatie van een afbeelding met Bradley's adaptieve drempelalgoritme met behulp van de integrale afbeeldingdrempel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brightness_difference | double | Het helderheidsverschil tussen een pixel en het gemiddelde van een s x s venster van pixels gecentreerd rond deze pixel. |
| window_size | int | De grootte van een s x s venster van pixels gecentreerd rond deze pixel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

Binarisatie van een afbeelding met vooraf gedefinieerde drempel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| threshold | byte | Drempelwaarde. Als de overeenkomstige grijze waarde van een pixel groter is dan de drempel, wordt een waarde van 255 aan deze pixel toegewezen, anders 0. |

### Method: can_load(file_path)  [static] {#can_load_file_path_9}


```
 can_load(file_path) 
```

Bepaalt of de afbeelding kan worden geladen vanaf het opgegeven bestandspad.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <c>true</c> als afbeelding kan worden geladen vanuit het opgegeven bestand; anders <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_10}


```
 can_load(file_path, load_options) 
```

Bepaalt of de afbeelding kan worden geladen vanaf het opgegeven bestandspad en eventueel met de opgegeven openopties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | De laadopties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <c>true</c> als afbeelding kan worden geladen vanuit het opgegeven bestand; anders <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_11}


```
 can_load(stream) 
```

Bepaalt of de afbeelding kan worden geladen vanaf de opgegeven stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream om vanuit te laden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <c>true</c> als afbeelding kan worden geladen vanuit de opgegeven stream; anders <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_12}


```
 can_load(stream, load_options) 
```

Bepaalt of de afbeelding kan worden geladen vanaf de opgegeven stream en eventueel met de opgegeven <paramref name="loadOptions" />.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream om vanuit te laden. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | De laadopties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <c>true</c> als afbeelding kan worden geladen vanuit de opgegeven stream; anders <c>false</c>. |


### Method: can_save(options) {#can_save_options_13}


```
 can_save(options) 
```

Bepaalt of de afbeelding kan worden opgeslagen in het opgegeven bestandsformaat dat wordt weergegeven door de meegegeven opslagopties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De te gebruiken opslagopties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <c>true</c> als afbeelding kan worden opgeslagen in het opgegeven bestandsformaat dat wordt weergegeven door de meegegeven opslagopties; anders <c>false</c>. |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_14}


```
 create(image_options, width, height) 
```

Maakt een nieuwe afbeelding aan met de opgegeven creatieopties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De afbeeldingopties. |
| width | int | De breedte. |
| hoogte | int | De hoogte. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | De nieuw aangemaakte afbeelding. |


### Method: crop(rectangle) {#crop_rectangle_15}


```
 crop(rectangle) 
```

Bijsnijden van de afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_16}


```
 dither(dithering_method, bits_count) 
```

Voert dithering uit op de huidige afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | De ditheringmethode. |
| bits_count | int | Het uiteindelijke aantal bits voor dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_17}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Voert dithering uit op de huidige afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | De ditheringmethode. |
| bits_count | int | Het uiteindelijke aantal bits voor dithering. |
| custom_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Het aangepaste palet voor dithering. |

### Method: draw_image(location, image) {#draw_image_location_image_18}


```
 draw_image(location, image) 
```

Tekent de afbeelding op de laag.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | De locatie. |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | De afbeelding. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_19}


```
 get_argb_32_pixel(x, y) 
```

Haalt een 32-bit ARGB-pixel van de afbeelding op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | int | De pixel x-locatie. |
| y | int | De pixel y-locatie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De 32-bit ARGB-pixel voor de opgegeven locatie. |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_20}


```
 get_default_argb_32_pixels(rectangle) 
```

Haalt de standaard 32-bit ARGB-pixelarray op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om pixels voor op te halen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De standaard pixelarray. |


### Method: get_default_options(args) {#get_default_options_args_21}


```
 get_default_options(args) 
```

Haalt de standaardopties op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| args | object | De argumenten. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Standaardopties |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_22}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Haalt de standaard pixelarray op met behulp van de gedeeltelijke pixelloader.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om pixels voor op te halen. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | De gedeeltelijke pixelloader. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_23}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

Haalt de standaard ruwe gegevensarray op met behulp van de gedeeltelijke pixelloader.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om pixels voor op te halen. |
| partial_raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | De gedeeltelijke ruwe gegevenslader. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | De instellingen voor ruwe gegevens. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_24}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

Haalt de standaard ruwe gegevensarray op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om ruwe gegevens voor op te halen. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | De instellingen voor ruwe gegevens. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| byte | De standaard ruwe gegevensarray. |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_25}


```
 get_file_format(file_path) 
```

Haalt het bestandsformaat op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Het bepaalde bestandsformaat. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_26}


```
 get_file_format(stream) 
```

Haalt het bestandsformaat op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Het bepaalde bestandsformaat. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_27}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Haalt het rechthoek op dat past bij de huidige afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om de passende rechthoek voor op te halen. |
| pixels | int | De 32-bit ARGB-pixels. |
| width | int | De objectbreedte. |
| hoogte | int | De objecthoogte. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | De passende rechthoek of een uitzondering als er geen passende rechthoek kan worden gevonden. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_28}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Haalt het rechthoek op dat past bij de huidige afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om de passende rechthoek voor op te halen. |
| width | int | De objectbreedte. |
| hoogte | int | De objecthoogte. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | De passende rechthoek of een uitzondering als er geen passende rechthoek kan worden gevonden. |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_29}


```
 get_modify_date(use_default) 
```

Haalt de datum en tijd op waarop de bronafbeelding voor het laatst is gewijzigd.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| use_default | bool | indien ingesteld op <c>true</c> wordt de informatie van FileInfo gebruikt als standaardwaarde. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| datetime | De datum en tijd waarop de resource-afbeelding voor het laatst is gewijzigd. |


### Method: get_original_options() {#get_original_options__30}


```
 get_original_options() 
```

Haalt de opties op op basis van de oorspronkelijke bestandsinstellingen.<br/>            Dit kan nuttig zijn om de bitsdiepte en andere parameters van de oorspronkelijke afbeelding ongewijzigd te houden.<br/>            Bijvoorbeeld, als we een zwart-witte PNG-afbeelding met 1 bit per pixel laden en deze vervolgens opslaan met de<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) methode, wordt een PNG-uitvoerafbeelding met 8 bits per pixel gegenereerd.<br/>            Om dit te voorkomen en een PNG-afbeelding met 1 bit per pixel op te slaan, gebruik deze methode om de bijbehorende opslagopties op te halen en ze<br/>            door te geven aan de [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) methode als tweede parameter.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De opties gebaseerd op de oorspronkelijke bestandsinstellingen. |


### Method: get_pixel(x, y) {#get_pixel_x_y_31}


```
 get_pixel(x, y) 
```

Haalt een afbeeldingspixel op.<br/>            Prestatiewaarschuwing: Vermijd het gebruik van deze methode om over alle afbeeldingspixels te itereren, omdat dit kan leiden tot aanzienlijke prestatieproblemen.<br/>            Voor efficiëntere pixelmanipulatie, gebruik de `LoadArgb32Pixels` methode om de volledige pixelarray in één keer op te halen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | int | De pixel x-locatie. |
| y | int | De pixel y-locatie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | De pixelkleur voor de opgegeven locatie. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_32}


```
 get_proportional_height(width, height, new_width) 
```

Haalt een proportionele hoogte op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| width | int | De breedte. |
| hoogte | int | De hoogte. |
| new_width | int | De nieuwe breedte. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De proportionele hoogte. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_33}


```
 get_proportional_width(width, height, new_height) 
```

Haalt een proportionele breedte op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| width | int | De breedte. |
| hoogte | int | De hoogte. |
| new_height | int | De nieuwe hoogte. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De proportionele breedte. |


### Method: get_skew_angle() {#get_skew_angle__34}


```
 get_skew_angle() 
```

  

**Returns**

| Type | Beschrijving |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_35}


```
 load(file_path) 
```

Laadt een nieuwe afbeelding vanuit het opgegeven bestand.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad om de afbeelding van te laden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | De geladen afbeelding. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_36}


```
 load(file_path, load_options) 
```

Laadt een nieuwe afbeelding vanuit het opgegeven bestand.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad om de afbeelding van te laden. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | De laadopties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | De geladen afbeelding. |


### Method: load(stream)  [static] {#load_stream_37}


```
 load(stream) 
```

Laadt een nieuwe afbeelding vanuit de opgegeven stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream om de afbeelding van te laden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | De geladen afbeelding. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_38}


```
 load(stream, load_options) 
```

Laadt een nieuwe afbeelding vanuit de opgegeven stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream om de afbeelding van te laden. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | De laadopties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | De geladen afbeelding. |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_39}


```
 load_argb_32_pixels(rectangle) 
```

Laadt 32-bit ARGB-pixels.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om pixels uit te laden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De geladen 32-bit ARGB-pixelarray. |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_40}


```
 load_argb_64_pixels(rectangle) 
```

Laadt 64-bit ARGB-pixels.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om pixels uit te laden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| long | De geladen 64-bit ARGB-pixelarray. |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_41}


```
 load_cmyk_32_pixels(rectangle) 
```

Laadt pixels in CMYK-indeling.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om pixels uit te laden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De geladen CMYK-pixels gepresenteerd als 32-bit integerwaarden. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_42}


```
 load_cmyk_pixels(rectangle) 
```

Laadt pixels in CMYK-indeling.<br/>            Deze methode is verouderd. Gebruik alstublieft effectiever de [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) methode.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om pixels uit te laden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | De geladen CMYK-pixelarray. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_43}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Laadt 32-bit ARGB-pixels gedeeltelijk (per blokken).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om pixels uit te laden. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | De gedeeltelijke pixelloader. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_44}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Laadt pixels gedeeltelijk per pakketten.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De gewenste rechthoek. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | De pixelloader. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_45}


```
 load_pixels(rectangle) 
```

Laadt pixels.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om pixels uit te laden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | De geladen pixelarray. |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_46}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

Laadt ruwe gegevens.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om ruwe gegevens van te laden. |
| dest_image_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De grenzen van de doelafbeelding. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | De instellingen voor ruwe gegevens die gebruikt moeten worden voor geladen gegevens. Opmerking: als de gegevens niet in het opgegeven formaat zijn, wordt er een gegevensconversie uitgevoerd. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | De ruwe gegevenslader. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_47}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Laadt ruwe gegevens.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om ruwe gegevens van te laden. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | De instellingen voor ruwe gegevens die gebruikt moeten worden voor geladen gegevens. Opmerking: als de gegevens niet in het opgegeven formaat zijn, wordt er een gegevensconversie uitgevoerd. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | De ruwe gegevenslader. |

### Method: merge_layer_to(layer_to_merge_into) {#merge_layer_to_layer_to_merge_into_48}


```
 merge_layer_to(layer_to_merge_into) 
```

Voegt de laag samen met de opgegeven laag

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer_to_merge_into | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | De laag om in te voegen. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_49}


```
 read_argb_32_scan_line(scan_line_index) 
```

Leest de volledige scanlijn op basis van de opgegeven scanlijnindex.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| scan_line_index | int | Nulgebaseerde index van de scanlijn. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De scanlijn 32-bit ARGB-kleurwaardenarray. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_50}


```
 read_scan_line(scan_line_index) 
```

Leest de volledige scanlijn op basis van de opgegeven scanlijnindex.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| scan_line_index | int | Nulgebaseerde index van de scanlijn. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | De scanlijn pixelkleurwaardenarray. |


### Method: resize(new_width, new_height) {#resize_new_width_new_height_51}


```
 resize(new_width, new_height) 
```

Wijzigt de grootte van de afbeelding. De standaard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wordt gebruikt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_width | int | De nieuwe breedte. |
| new_height | int | De nieuwe hoogte. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_52}


```
 resize(new_width, new_height, resize_type) 
```

Wijzigt de grootte van de afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_width | int | De nieuwe breedte. |
| new_height | int | De nieuwe hoogte. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Het type schalen. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_53}


```
 resize(new_width, new_height, settings) 
```

Wijzigt de grootte van de afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_width | int | De nieuwe breedte. |
| new_height | int | De nieuwe hoogte. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | De instellingen voor schalen. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_54}


```
 resize_height_proportionally(new_height) 
```

Wijzigt de hoogte proportioneel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_height | int | De nieuwe hoogte. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_55}


```
 resize_height_proportionally(new_height, resize_type) 
```

Wijzigt de hoogte proportioneel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_height | int | De nieuwe hoogte. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Type van de verkleining. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_56}


```
 resize_height_proportionally(new_height, settings) 
```

Wijzigt de hoogte proportioneel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_height | int | De nieuwe hoogte. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | De instellingen voor het verkleinen van de afbeelding. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_57}


```
 resize_width_proportionally(new_width) 
```

Wijzigt de breedte proportioneel. De standaard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wordt gebruikt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_width | int | De nieuwe breedte. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_58}


```
 resize_width_proportionally(new_width, resize_type) 
```

Wijzigt de breedte proportioneel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_width | int | De nieuwe breedte. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Type van de verkleining. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_59}


```
 resize_width_proportionally(new_width, settings) 
```

Wijzigt de breedte proportioneel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_width | int | De nieuwe breedte. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | De instellingen voor het verkleinen van de afbeelding. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_60}


```
 rotate(angle, resize_proportionally, background_color) 
```

Roteer de afbeelding rond het midden.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| hoek | float | De rotatiehoek in graden. Positieve waarden roteren met de klok mee. |
| resize_proportionally | bool | als ingesteld op <c>true</c> wordt de afbeeldingsgrootte aangepast volgens de projecties van het geroteerde rechthoek (hoekpunten); anders blijven de afmetingen ongewijzigd en wordt alleen de interne afbeeldinginhoud geroteerd. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | Kleur van de achtergrond. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_61}


```
 rotate_flip(rotate_flip_type) 
```

Roteert, spiegelt of roteert en spiegelt de afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Het type rotatie-flip. |

### Method: save(file_path) {#save_file_path_62}


```
 save(file_path) 
```

Slaat de gegevens van het object op op de opgegeven bestandslocatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad om de gegevens van het object op te slaan. |

### Method: save(file_path, options) {#save_file_path_options_63}


```
 save(file_path, options) 
```

Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De opties. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_64}


```
 save(file_path, options, bounds_rectangle) 
```

Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De opties. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek met de grenzen van de doelafbeelding. Stel de lege rechthoek in om de brongrenzen te gebruiken. |

### Method: save(file_path, over_write) {#save_file_path_over_write_65}


```
 save(file_path, over_write) 
```

Slaat de gegevens van het object op op de opgegeven bestandslocatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad om de gegevens van het object op te slaan. |
| over_write | bool | als ingesteld op <c>true</c> wordt de bestandsinhoud overschreven, anders wordt er toegevoegd. |

### Method: save(stream) {#save_stream_66}


```
 save(stream) 
```

Slaat de gegevens van het object op in de opgegeven stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream om de gegevens van het object op te slaan. |

### Method: save(stream, options_base) {#save_stream_options_base_67}


```
 save(stream, options_base) 
```

Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream om de gegevens van de afbeelding op te slaan. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De opslagopties. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_68}


```
 save(stream, options_base, bounds_rectangle) 
```

Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream om de gegevens van de afbeelding op te slaan. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De opslagopties. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek met de grenzen van de doelafbeelding. Stel de lege rechthoek in om de brongrenzen te gebruiken. |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_69}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Slaat de 32-bit ARGB-pixels op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om pixels in op te slaan. |
| pixels | int | De 32-bit ARGB-pixelarray. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_70}


```
 save_pixels(rectangle, pixels) 
```

Slaat pixels op (formaatspecifieke methode).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om pixels in op te slaan. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | De 32-bit ARGB-pixelarray. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_71}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

Slaat de ruwe gegevens op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| data | byte | De ruwe gegevens. |
| data_offset | int | De beginnende offset van de ruwe gegevens. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek van de ruwe gegevens. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | De instellingen van de ruwe gegevens waarin de data zich bevindt. |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_72}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

Stelt een 32-bit ARGB-pixel van de afbeelding in voor de opgegeven positie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | int | De pixel x-locatie. |
| y | int | De pixel y-locatie. |
| argb_32_color | int | De 32-bit ARGB-pixel voor de opgegeven positie. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_73}


```
 set_palette(palette, update_colors) 
```

Stelt het palet van de afbeelding in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Het palet om in te stellen. |
| update_colors | bool | indien ingesteld op <c>true</c> worden kleuren bijgewerkt volgens het nieuwe palet; anders blijven kleurindexen ongewijzigd. Merk op dat ongewijzigde indexen de afbeelding kunnen laten crashen bij het laden als sommige indexen geen overeenkomstige paletinvoer hebben. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_74}


```
 set_pixel(x, y, color) 
```

Stelt een afbeeldingspixel in voor de opgegeven positie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | int | De pixel x-locatie. |
| y | int | De pixel y-locatie. |
| color | [Color](/psd/python-net/aspose.psd/color) | De pixelkleur voor de opgegeven positie. |

### Method: shallow_copy() {#shallow_copy__75}


```
 shallow_copy() 
```

Maakt een ondiepe kopie van de huidige laag.<br/>            Zie <see href="https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx" /> voor uitleg.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | Een ondiepe kopie van de huidige Laag. |


### Method: to_bitmap() {#to_bitmap__76}


```
 to_bitmap() 
```

  

**Returns**

| Type | Beschrijving |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_77}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Schrijft de volledige scanlijn naar de opgegeven scanlijnindex.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| scan_line_index | int | Nulgebaseerde index van de scanlijn. |
| argb_32_pixels | int | De 32-bit ARGB-kleurenarray om te schrijven. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_78}


```
 write_scan_line(scan_line_index, pixels) 
```

Schrijft de volledige scanlijn naar de opgegeven scanlijnindex.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| scan_line_index | int | Nulgebaseerde index van de scanlijn. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | De pixelkleurenarray om te schrijven. |

