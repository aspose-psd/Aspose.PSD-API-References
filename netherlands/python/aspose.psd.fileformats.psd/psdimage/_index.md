---
title: "PsdImage Class"
type: docs
weight: 1760
url: /nl/python-net/aspose.psd.fileformats.psd/psdimage/
---

**Summary:** Defines the PsdImage class that provides the ability to load, edit, save PSD files as well as<br/>            update properties, add watermarks, perform graphics operations or convert one file format to another.<br/>            Aspose.PSD supports import as a layer and export to the following formats:<br/>            Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb along with export to Pdf with selectable text

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [PsdImage(path)](#PsdImage_path_1) | Initialiseert een nieuw exemplaar van de [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) klasse vanaf een opgegeven pad van een rasterafbeelding (geen psd‑afbeelding in het pad). Wordt gebruikt om een psd‑afbeelding te initialiseren met standaardparameters - Kleermodus - rgb, 4 kanalen, 8 bit per kanaal, Compressie - Raw. |
| [PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2) | Initialiseert een nieuw exemplaar van de [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) klasse vanaf een opgegeven pad van een rasterafbeelding (geen psd‑afbeelding in het pad) met constructorparameters. |
| [PsdImage(raster_image)](#PsdImage_raster_image_3) | Initialiseert een nieuw exemplaar van de [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) klasse van een bestaande rasterafbeelding (geen psd‑afbeelding) met RGB‑kleermodus, 4 kanalen, 8 bit per kanaal en zonder compressie. |
| [PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4) | Initialiseert een nieuw exemplaar van de [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) klasse van een bestaande rasterafbeelding (geen psd‑afbeelding) met constructorparameters. |
| [PsdImage(stream)](#PsdImage_stream_5) | Initialiseert een nieuw exemplaar van de [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) klasse vanaf een opgegeven pad van een rasterafbeelding (geen psd‑afbeelding in de stream). Wordt gebruikt om een psd‑afbeelding te initialiseren met standaardparameters - Kleermodus - rgb, 4 kanalen, 8 bit per kanaal, Compressie - Raw. |
| [PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6) | Initialiseert een nieuw exemplaar van de [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) klasse vanaf een opgegeven pad van een rasterafbeelding (geen psd‑afbeelding in de stream) met constructorparameters. |
| [PsdImage(width, height)](#PsdImage_width_height_7) | Initialiseert een nieuw exemplaar van de [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) klasse met opgegeven breedte en hoogte. Wordt gebruikt om een lege psd‑afbeelding te initialiseren. |
| [PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8) | Initialiseert een nieuw exemplaar van de [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) klasse met opgegeven breedte, hoogte, palet, kleermodus, aantal kanalen en bitsnelheid per kanaal en opgegeven compressiemodusparameters. Wordt gebruikt om een lege psd‑afbeelding te initialiseren. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| DEFAULT_VERSION [static] | int | r | De standaard PSD-versie. |
| active_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | Haalt op of stelt de actieve laag in. |
| auto_adjust_palette | bool | r/w | Haalt op of stelt een waarde in die aangeeft of het palet automatisch wordt aangepast. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Haalt op of stelt een waarde in voor de achtergrondkleur. |
| bits_per_channel | int | r | Haalt het aantal bits per kanaal op. |
| bits_per_pixel | int | r | Haalt het aantal bits per pixel van de afbeelding op. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Haalt de grenzen van het object op. |
| buffer_size_hint | int | r/w | Haalt op of stelt de buffergroottehint in, die is gedefinieerd als de maximaal toegestane grootte voor alle interne buffers. |
| channels_count | int | r | Haalt het aantal PSD-kanalen op. |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Haalt het CMYK-kleurprofiel op of stelt het in voor CMYK PSD-afbeeldingen. Moet in combinatie met RgbColorProfile worden gebruikt voor correcte kleurconversie. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r/w | Haalt de kleermodus op of stelt deze in. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | r | Haalt de compressiemethode op. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Haalt de [Image](/psd/python-net/aspose.psd/image/) container op. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Haalt de gegevensstroom van het object op. |
| disposed | bool | r | Geeft een waarde die aangeeft of dit exemplaar is vrijgegeven. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Haalt een waarde van bestandsformaat op |
| global_angle | int | r/w | Haalt de globale hoek op of stelt deze in. |
| global_layer_mask_info | [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | r | Haalt de globale laagmaskerinformatie op. |
| global_layer_resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | r/w | Haalt de globale laagresources op of stelt deze in. |
| gray_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Haalt het GRAY (monochroom) kleurprofiel op of stelt het in voor Grayscale PSD-afbeeldingen. |
| has_alpha | bool | r | Haalt op of stelt de verticale resolutie, in pixels per inch, van deze [RasterImage](/psd/python-net/aspose.psd/rasterimage/) in. |
| has_background_color | bool | r/w | Haalt of stelt een waarde in die aangeeft of de afbeelding een achtergrondkleur heeft. |
| has_transparency_data | bool | r/w | Haalt een waarde op of stelt deze in die aangeeft of het eerste alfakanaal de transparantiegegevens bevat voor het samengevoegde resultaat bij het specificeren van laaggegevens. |
| has_transparent_color | bool | r/w | Haalt een waarde op die aangeeft of de afbeelding een transparante kleur heeft. |
| hoogte | int | r | Haalt de afbeeldinghoogte op. |
| horizontal_resolution | double | r/w | Haalt de horizontale resolutie, in pixels per inch, van deze [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) op of stelt deze in. |
| image_opacity | float | r | Haalt de opaciteit van deze afbeelding op. |
| image_resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock) | r/w | Haalt de PSD-afbeeldingsresources op of stelt deze in. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Haalt of stelt de onderbrekingsmonitor in. |
| is_cached | bool | r | Haalt een waarde op die aangeeft of afbeeldingsgegevens momenteel in de cache staan. |
| is_flatten | bool | r | Haalt een waarde op die aangeeft of de PSD-afbeelding is afgevlakt. |
| is_raw_data_available | bool | r | Haalt een waarde op die aangeeft of het laden van ruwe gegevens wordt ondersteund. |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | Haalt de PSD-lagen op of stelt deze in. |
| linked_layers_manager | [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | r | Haalt de gekoppelde lagenbeheerder op. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Haalt op of stelt het kleurenpalet in. Het kleurenpalet wordt niet gebruikt wanneer pixels direct worden weergegeven. |
| premultiply_components | bool | r/w | Haalt op of stelt een waarde in die aangeeft of de afbeeldingscomponenten voorvermenigvuldigd moeten zijn. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | Haalt op of stelt de aangepaste kleurconverter in. |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Haalt het ruwe gegevensformaat op. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Haalt de huidige ruwe‑gegevensinstellingen op. Let op: bij het gebruik van deze instellingen worden de gegevens geladen zonder conversie. |
| raw_fallback_index | int | r/w | Haalt op of stelt de fallback-index in die moet worden gebruikt wanneer de paletindex buiten de grenzen valt. |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | Haalt op of stelt de geïndexeerde kleurconverter in. |
| raw_line_size | int | r | Haalt de ruwe regelgrootte op in bytes. |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Haalt het RGB-kleurprofiel op of stelt het in voor CMYK PSD-afbeeldingen. Moet in combinatie met CmykColorProfile worden gebruikt voor correcte kleurconversie. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Haalt de objectgrootte op. |
| smart_object_provider | [SmartObjectProvider](/psd/python-net/aspose.psd.fileformats.psd/smartobjectprovider) | r | Haalt de smart object provider op. |
| timeline | [Timeline](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/) | r | Haalt de [PsdImage.timeline](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) van deze [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) op. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Haalt de transparante kleur van de afbeelding op. |
| update_xmp_data | bool | r/w | Haalt op of stelt een waarde in die aangeeft of de XMP-metadata moet worden bijgewerkt. |
| use_palette | bool | r | Haalt een waarde op die aangeeft of het afbeeldingspalet wordt gebruikt. |
| use_raw_data | bool | r/w | Haalt op of stelt een waarde in die aangeeft of ruwe gegevensladen moet worden gebruikt wanneer ruwe gegevensladen beschikbaar is. |
| version | int | r/w | Haalt de versie op of stelt deze in. |
| vertical_resolution | double | r/w | Haalt de verticale resolutie, in pixels per inch, van deze [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) op of stelt deze in. |
| width | int | r | Haalt de breedte van de afbeelding op. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Haalt de XMP-metadata op of stelt deze in. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_black_white_adjustment_layer()](#add_black_white_adjustment_layer__1) | Voegt de zwart-wit-aanpassingslaag toe. |
| [add_brightness_contrast_adjustment_layer(brightness, contrast)](#add_brightness_contrast_adjustment_layer_brightness_contrast_2) | Voegt de helderheid/contrast-aanpassingslaag toe. |
| [add_channel_mixer_adjustment_layer()](#add_channel_mixer_adjustment_layer__3) | Voegt de kanaalmixer-aanpassingslaag toe met standaardparameters |
| [add_color_balance_adjustment_layer()](#add_color_balance_adjustment_layer__4) | Voegt de kleurbalans‑aanpassingslaag toe. |
| [add_curves_adjustment_layer()](#add_curves_adjustment_layer__5) | Voegt de Curves‑aanpassingslaag toe. |
| [add_exposure_adjustment_layer(exposure, offset, gamma_correction)](#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6) | Voegt de belichtings‑aanpassingslaag toe. |
| [add_gradient_map_adjustment_layer()](#add_gradient_map_adjustment_layer__7) | Voegt GradientMap‑aanpassingslaag toe. |
| [add_hue_saturation_adjustment_layer()](#add_hue_saturation_adjustment_layer__8) | Voegt de tint/verzadiging‑aanpassingslaag toe. |
| [add_invert_adjustment_layer()](#add_invert_adjustment_layer__9) | Voegt een inversie‑aanpassingslaag toe. |
| [add_layer(layer)](#add_layer_layer_10) | Voegt de laag toe. |
| [add_layer_group(group_name, index, start_behaviour)](#add_layer_group_group_name_index_start_behaviour_11) | Voegt de laaggroep toe. |
| [add_levels_adjustment_layer()](#add_levels_adjustment_layer__12) | Voegt de Levels‑aanpassingslaag toe. |
| [add_photo_filter_layer(color)](#add_photo_filter_layer_color_13) | Voegt de PhotoFilter‑laag toe. |
| [add_posterize_adjustment_layer()](#add_posterize_adjustment_layer__14) | Voegt Posterize‑aanpassingslaag toe. |
| [add_regular_layer()](#add_regular_layer__15) | Voegt een nieuwe reguliere laag toe. |
| [add_selective_color_adjustment_layer()](#add_selective_color_adjustment_layer__16) | Voegt de selectieve kleur‑aanpassingslaag toe. |
| [add_shape_layer()](#add_shape_layer__17) | Voeg lege Shape‑laag toe.<br/>            Zonder paden. Ze moeten aan de shape‑laag worden toegevoegd vóór het opslaan. |
| [add_text_layer(text, rect)](#add_text_layer_text_rect_18) | Voegt een nieuwe Tekst‑laag toe. |
| [add_threshold_adjustment_layer()](#add_threshold_adjustment_layer__19) | Voegt de Drempel‑aanpassingslaag toe. |
| [add_vibrance_adjustment_layer()](#add_vibrance_adjustment_layer__20) | Voegt de Vibrance‑aanpassingslaag toe. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_21) | Past de helderheid van de afbeelding aan. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_22) | Afbeeldingscontrast |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_23) | Gamma-correctie van een afbeelding. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_24) | Gamma-correctie van een afbeelding. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_25) | Binarisatie van een afbeelding met Bradley's adaptieve drempelalgoritme met behulp van de integrale afbeeldingdrempel. |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_26) | Binarisatie van een afbeelding met Bradley's adaptieve drempelalgoritme met behulp van de integrale afbeeldingdrempel. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_27) | Binarisatie van een afbeelding met vooraf gedefinieerde drempel. |
| binarize_otsu() | Binarisatie van een afbeelding met Otsu-drempelbepaling. |
| cache_data() | Cachet de gegevens en zorgt ervoor dat er geen extra gegevens worden geladen van de onderliggende [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/). |
| [can_load(file_path)](#can_load_file_path_28) | Bepaalt of de afbeelding kan worden geladen vanaf het opgegeven bestandspad. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_29) | Bepaalt of de afbeelding kan worden geladen vanaf het opgegeven bestandspad en eventueel met de opgegeven openopties. |
| [can_load(stream)](#can_load_stream_30) | Bepaalt of de afbeelding kan worden geladen vanaf de opgegeven stream. |
| [can_load(stream, load_options)](#can_load_stream_load_options_31) | Bepaalt of de afbeelding kan worden geladen vanaf de opgegeven stream en eventueel met de opgegeven <paramref name="loadOptions" />. |
| [can_save(options)](#can_save_options_32) | Bepaalt of de afbeelding kan worden opgeslagen in het opgegeven bestandsformaat dat wordt weergegeven door de meegegeven opslagopties. |
| [convert(new_options)](#convert_new_options_33) | Converteert dit afbeeldingformaat naar het formaat dat in de opties is opgegeven. |
| [create(image_options, width, height)](#create_image_options_width_height_34) | Maakt een nieuwe afbeelding aan met de opgegeven creatieopties. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_35) | Bijsnijden van de afbeelding. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_36) | Voert dithering uit op de huidige afbeelding. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_37) | Voert dithering uit op de huidige afbeelding. |
| [filter(rectangle, options)](#filter_rectangle_options_38) | Filtert de opgegeven rechthoek. |
| flatten_image() | Vlak alle lagen. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_39) | Haalt een 32-bit ARGB-pixel van de afbeelding op. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_40) | Haalt de standaard 32-bit ARGB-pixelarray op. |
| [get_default_options(args)](#get_default_options_args_41) | Haalt de standaardopties op. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_42) | Haalt de standaard pixelarray op met behulp van de gedeeltelijke pixelloader. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43) | Haalt de standaard ruwe gegevensarray op met behulp van de gedeeltelijke pixelloader. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_44) | Haalt de standaard ruwe gegevensarray op. |
| [get_file_format(file_path)](#get_file_format_file_path_45) | Haalt het bestandsformaat op. |
| [get_file_format(stream)](#get_file_format_stream_46) | Haalt het bestandsformaat op. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_47) | Haalt het rechthoek op dat past bij de huidige afbeelding. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_48) | Haalt het rechthoek op dat past bij de huidige afbeelding. |
| [get_modify_date(use_default)](#get_modify_date_use_default_49) | Haalt de datum en tijd op waarop de bronafbeelding voor het laatst is gewijzigd. |
| [get_original_options()](#get_original_options__50) | Haalt de opties op op basis van de oorspronkelijke bestandsinstellingen.<br/>            Dit kan nuttig zijn om de bitsdiepte en andere parameters van de oorspronkelijke afbeelding ongewijzigd te houden.<br/>            Bijvoorbeeld, als we een zwart-witte PNG-afbeelding met 1 bit per pixel laden en deze vervolgens opslaan met de<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) methode, wordt een PNG-uitvoerafbeelding met 8 bits per pixel gegenereerd.<br/>            Om dit te voorkomen en een PNG-afbeelding met 1 bit per pixel op te slaan, gebruik deze methode om de bijbehorende opslagopties op te halen en ze<br/>            door te geven aan de [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) methode als tweede parameter. |
| [get_pixel(x, y)](#get_pixel_x_y_51) | Haalt een afbeeldingspixel op.<br/>            Prestatiewaarschuwing: Vermijd het gebruik van deze methode om over alle afbeeldingspixels te itereren, omdat dit kan leiden tot aanzienlijke prestatieproblemen.<br/>            Voor efficiëntere pixelmanipulatie, gebruik de `LoadArgb32Pixels` methode om de volledige pixelarray in één keer op te halen. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_52) | Haalt een proportionele hoogte op. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_53) | Haalt een proportionele breedte op. |
| [get_skew_angle()](#get_skew_angle__54) |    |
| grayscale() | Transformatie van een afbeelding naar zijn grijstintenrepresentatie |
| [load(file_path)](#load_file_path_55) | Laadt een nieuwe afbeelding vanuit het opgegeven bestand. |
| [load(file_path, load_options)](#load_file_path_load_options_56) | Laadt een nieuwe afbeelding vanuit het opgegeven bestand. |
| [load(stream)](#load_stream_57) | Laadt een nieuwe afbeelding vanuit de opgegeven stream. |
| [load(stream, load_options)](#load_stream_load_options_58) | Laadt een nieuwe afbeelding vanuit de opgegeven stream. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_59) | Laadt 32-bit ARGB-pixels. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_60) | Laadt 64-bit ARGB-pixels. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_61) | Laadt pixels in CMYK-indeling. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_62) | Laadt pixels in CMYK-indeling.<br/>            Deze methode is verouderd. Gebruik alstublieft effectiever de [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) methode. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63) | Laadt 32-bit ARGB-pixels gedeeltelijk (per blokken). |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_64) | Laadt pixels gedeeltelijk per pakketten. |
| [load_pixels(rectangle)](#load_pixels_rectangle_65) | Laadt pixels. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66) | Laadt ruwe gegevens. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67) | Laadt ruwe gegevens. |
| [merge_layers(bottom_layer, top_layer)](#merge_layers_bottom_layer_top_layer_68) | Voegt de lagen samen. |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_69) | Leest de volledige scanlijn op basis van de opgegeven scanlijnindex. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_70) | Leest de volledige scanlijn op basis van de opgegeven scanlijnindex. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_71) | Vervangt één kleur door een andere met toegestane afwijking en behoudt de oorspronkelijke alfa‑waarde om vloeiende randen te behouden. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_72) | Vervangt één kleur door een andere met toegestane afwijking en behoudt de oorspronkelijke alfa‑waarde om vloeiende randen te behouden. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_73) | Vervangt alle niet-transparante kleuren door een nieuwe kleur en behoudt de originele alfabeta-waarde om vloeiende randen te behouden.<br/>            Opmerking: als je het toepast op afbeeldingen zonder transparantie, worden alle kleuren vervangen door één enkele kleur. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_74) | Vervangt alle niet-transparante kleuren door een nieuwe kleur en behoudt de originele alfabeta-waarde om vloeiende randen te behouden.<br/>            Opmerking: als je het toepast op afbeeldingen zonder transparantie, worden alle kleuren vervangen door één enkele kleur. |
| [resize(new_width, new_height)](#resize_new_width_new_height_75) | Wijzigt de grootte van de afbeelding. De standaard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wordt gebruikt. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_76) | Wijzigt de grootte van de afbeelding. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_77) | Wijzigt de grootte van de afbeelding. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_78) | Wijzigt de hoogte proportioneel. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_79) | Wijzigt de hoogte proportioneel. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_80) | Wijzigt de hoogte proportioneel. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_81) | Wijzigt de breedte proportioneel. De standaard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wordt gebruikt. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_82) | Wijzigt de breedte proportioneel. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_83) | Wijzigt de breedte proportioneel. |
| [rotate(angle)](#rotate_angle_84) | Roteer de afbeelding rond het midden. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_85) | Roteer de afbeelding rond het midden. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_86) | Roteert, spiegelt of roteert en spiegelt de afbeelding. |
| save() | Slaat de afbeeldingsgegevens op in de onderliggende stream. |
| [save(file_path)](#save_file_path_87) | Slaat de gegevens van het object op op de opgegeven bestandslocatie. |
| [save(file_path, options)](#save_file_path_options_88) | Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_89) | Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties. |
| [save(file_path, over_write)](#save_file_path_over_write_90) | Slaat de gegevens van het object op op de opgegeven bestandslocatie. |
| [save(stream)](#save_stream_91) | Slaat de gegevens van het object op in de opgegeven stream. |
| [save(stream, options_base)](#save_stream_options_base_92) | Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_93) | Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_94) | Slaat de 32-bit ARGB-pixels op. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_95) | Slaat pixels op (formaatspecifieke methode). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_96) | Slaat de ruwe gegevens op. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_97) | Stelt een 32-bit ARGB-pixel van de afbeelding in voor de opgegeven positie. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_98) | Stelt het palet van de afbeelding in. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_99) | Stelt een afbeeldingspixel in voor de opgegeven positie. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_100) | Stelt de resolutie in voor deze [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| [to_bitmap()](#to_bitmap__101) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102) | Schrijft de volledige scanlijn naar de opgegeven scanlijnindex. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_103) | Schrijft de volledige scanlijn naar de opgegeven scanlijnindex. |


### Constructor: PsdImage(path) {#PsdImage_path_1}


```
 PsdImage(path) 
```

Initialiseert een nieuw exemplaar van de [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) klasse vanaf een opgegeven pad van een rasterafbeelding (geen psd‑afbeelding in het pad). Wordt gebruikt om een psd‑afbeelding te initialiseren met standaardparameters - Kleermodus - rgb, 4 kanalen, 8 bit per kanaal, Compressie - Raw.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Het pad om pixel‑ en paletgegevens van te laden en mee te initialiseren. |

### Constructor: PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2}


```
 PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Initialiseert een nieuw exemplaar van de [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) klasse vanaf een opgegeven pad van een rasterafbeelding (geen psd‑afbeelding in het pad) met constructorparameters.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Het pad om pixel‑ en paletgegevens van te laden en mee te initialiseren. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | De kleurmodus. |
| channel_bit_depth | short | De PSD-bitdiepte per kanaal. |
| kanalen | short | Het aantal PSD-kanalen. |
| psd_version | int | De PSD‑versie. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | De compressie om te gebruiken. |

### Constructor: PsdImage(raster_image) {#PsdImage_raster_image_3}


```
 PsdImage(raster_image) 
```

Initialiseert een nieuw exemplaar van de [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) klasse van een bestaande rasterafbeelding (geen psd‑afbeelding) met RGB‑kleermodus, 4 kanalen, 8 bit per kanaal en zonder compressie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | De afbeelding om pixel- en paletgegevens van te laden en mee te initialiseren. |

### Constructor: PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4}


```
 PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Initialiseert een nieuw exemplaar van de [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) klasse van een bestaande rasterafbeelding (geen psd‑afbeelding) met constructorparameters.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | De afbeelding om pixel- en paletgegevens van te laden en mee te initialiseren. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | De kleurmodus. |
| channel_bit_depth | short | De PSD-bitdiepte per kanaal. |
| kanalen | short | Het aantal PSD-kanalen. |
| psd_version | int | De PSD‑versie. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | De compressie om te gebruiken. |

### Constructor: PsdImage(stream) {#PsdImage_stream_5}


```
 PsdImage(stream) 
```

Initialiseert een nieuw exemplaar van de [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) klasse vanaf een opgegeven pad van een rasterafbeelding (geen psd‑afbeelding in de stream). Wordt gebruikt om een psd‑afbeelding te initialiseren met standaardparameters - Kleermodus - rgb, 4 kanalen, 8 bit per kanaal, Compressie - Raw.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream om pixel- en paletgegevens van te laden en mee te initialiseren. |

### Constructor: PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6}


```
 PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Initialiseert een nieuw exemplaar van de [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) klasse vanaf een opgegeven pad van een rasterafbeelding (geen psd‑afbeelding in de stream) met constructorparameters.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream om pixel- en paletgegevens van te laden en mee te initialiseren. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | De kleurmodus. |
| channel_bit_depth | short | De PSD-bitdiepte per kanaal. |
| kanalen | short | Het aantal PSD-kanalen. |
| psd_version | int | De PSD‑versie. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | De compressie om te gebruiken. |

### Constructor: PsdImage(width, height) {#PsdImage_width_height_7}


```
 PsdImage(width, height) 
```

Initialiseert een nieuw exemplaar van de [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) klasse met opgegeven breedte en hoogte. Wordt gebruikt om een lege psd‑afbeelding te initialiseren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| width | int | De afbeeldingsbreedte. |
| hoogte | int | De afbeeldingshoogte. |

### Constructor: PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8}


```
 PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Initialiseert een nieuw exemplaar van de [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) klasse met opgegeven breedte, hoogte, palet, kleermodus, aantal kanalen en bitsnelheid per kanaal en opgegeven compressiemodusparameters. Wordt gebruikt om een lege psd‑afbeelding te initialiseren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| width | int | De afbeeldingsbreedte. |
| hoogte | int | De afbeeldingshoogte. |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Het kleurenpalet. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | De kleurmodus. |
| channel_bit_depth | short | De PSD-bitdiepte per kanaal. |
| kanalen | short | Het aantal PSD-kanalen. |
| psd_version | int | De PSD‑versie. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | De compressie om te gebruiken. |

### Method: add_black_white_adjustment_layer() {#add_black_white_adjustment_layer__1}


```
 add_black_white_adjustment_layer() 
```

Voegt de zwart-wit-aanpassingslaag toe.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [BlackWhiteAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/) | De gemaakte zwart-wit-aanpassingslaag. |


### Method: add_brightness_contrast_adjustment_layer(brightness, contrast) {#add_brightness_contrast_adjustment_layer_brightness_contrast_2}


```
 add_brightness_contrast_adjustment_layer(brightness, contrast) 
```

Voegt de helderheid/contrast-aanpassingslaag toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| helderheid | int | De helderheid. |
| contrast | int | Het contrast. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [BrightnessContrastLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer/) | Gemaakte helderheid/contrastlaag |


### Method: add_channel_mixer_adjustment_layer() {#add_channel_mixer_adjustment_layer__3}


```
 add_channel_mixer_adjustment_layer() 
```

Voegt de kanaalmixer-aanpassingslaag toe met standaardparameters

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ChannelMixerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer/) | Toegevoegde Kanaalmixerlaag |


### Method: add_color_balance_adjustment_layer() {#add_color_balance_adjustment_layer__4}


```
 add_color_balance_adjustment_layer() 
```

Voegt de kleurbalans‑aanpassingslaag toe.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ColorBalanceAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/) | Een nieuw aangemaakte kleurbalanslaag. |


### Method: add_curves_adjustment_layer() {#add_curves_adjustment_layer__5}


```
 add_curves_adjustment_layer() 
```

Voegt de Curves‑aanpassingslaag toe.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) | Gemaakt [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) laag |


### Method: add_exposure_adjustment_layer(exposure, offset, gamma_correction) {#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6}


```
 add_exposure_adjustment_layer(exposure, offset, gamma_correction) 
```

Voegt de belichtings‑aanpassingslaag toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| belichting | float | De belichting. |
| offset | float | De offset. |
| gamma_correctie | float | De gamma-correctie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ExposureLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer/) | Gemaakt Exposure Adjustment Layer |


### Method: add_gradient_map_adjustment_layer() {#add_gradient_map_adjustment_layer__7}


```
 add_gradient_map_adjustment_layer() 
```

Voegt GradientMap‑aanpassingslaag toe.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [GradientMapLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/) | GradientMap instantie. |


### Method: add_hue_saturation_adjustment_layer() {#add_hue_saturation_adjustment_layer__8}


```
 add_hue_saturation_adjustment_layer() 
```

Voegt de tint/verzadiging‑aanpassingslaag toe.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [HueSaturationLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer/) | Een nieuw aangemaakte tint/verzadigingslaag. |


### Method: add_invert_adjustment_layer() {#add_invert_adjustment_layer__9}


```
 add_invert_adjustment_layer() 
```

Voegt een inversie‑aanpassingslaag toe.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [InvertAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/) | De gemaakte omkeerlaag |


### Method: add_layer(layer) {#add_layer_layer_10}


```
 add_layer(layer) 
```

Voegt de laag toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | De laag. |

### Method: add_layer_group(group_name, index, start_behaviour) {#add_layer_group_group_name_index_start_behaviour_11}


```
 add_layer_group(group_name, index, start_behaviour) 
```

Voegt de laaggroep toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| group_name | string | Naam van de groep. |
| index | int | De index van de laag waarna ingevoegd moet worden. |
| start_behaviour | bool | als ingesteld op <c>true</c> [start behaviour] dan zal de groep bij opstarten in de open staat zijn, anders in de geminimaliseerde staat. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | Openen van groepslaag |


### Method: add_levels_adjustment_layer() {#add_levels_adjustment_layer__12}


```
 add_levels_adjustment_layer() 
```

Voegt de Levels‑aanpassingslaag toe.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [LevelsLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer/) | Een nieuw aangemaakte Levels layer |


### Method: add_photo_filter_layer(color) {#add_photo_filter_layer_color_13}


```
 add_photo_filter_layer(color) 
```

Voegt de PhotoFilter‑laag toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | De kleur. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [PhotoFilterLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer/) | Gemaakt PhotoFilter Layer |


### Method: add_posterize_adjustment_layer() {#add_posterize_adjustment_layer__14}


```
 add_posterize_adjustment_layer() 
```

Voegt Posterize‑aanpassingslaag toe.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [PosterizeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/) | PosterizeLayer instantie. |


### Method: add_regular_layer() {#add_regular_layer__15}


```
 add_regular_layer() 
```

Voegt een nieuwe reguliere laag toe.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Gemaakt gewone laag. |


### Method: add_selective_color_adjustment_layer() {#add_selective_color_adjustment_layer__16}


```
 add_selective_color_adjustment_layer() 
```

Voegt de selectieve kleur‑aanpassingslaag toe.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [SelectiveColorLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer/) | De gemaakte selectieve kleuraanpassingslaag. |


### Method: add_shape_layer() {#add_shape_layer__17}


```
 add_shape_layer() 
```

Voeg lege Shape‑laag toe.<br/>            Zonder paden. Ze moeten aan de shape‑laag worden toegevoegd vóór het opslaan.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | ShapeLayer-instantie. |


### Method: add_text_layer(text, rect) {#add_text_layer_text_rect_18}


```
 add_text_layer(text, rect) 
```

Voegt een nieuwe Tekst‑laag toe.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | string | De tekst van de laag. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek van de laag. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | Aangemaakte tekstlaag. |


### Method: add_threshold_adjustment_layer() {#add_threshold_adjustment_layer__19}


```
 add_threshold_adjustment_layer() 
```

Voegt de Drempel‑aanpassingslaag toe.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ThresholdLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/) | De aangemaakte drempel-aanpassingslaag. |


### Method: add_vibrance_adjustment_layer() {#add_vibrance_adjustment_layer__20}


```
 add_vibrance_adjustment_layer() 
```

Voegt de Vibrance‑aanpassingslaag toe.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VibranceLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/) | Een nieuw aangemaakte Vibrance-laag. |


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_21}


```
 adjust_brightness(brightness) 
```

Past de helderheid van de afbeelding aan.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| helderheid | int | Helderheidswaarde. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_22}


```
 adjust_contrast(contrast) 
```

Afbeeldingscontrast

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| contrast | float | Contrastwaarde (in bereik [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_23}


```
 adjust_gamma(gamma) 
```

Gamma-correctie van een afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| gamma | float | Gamma-coëfficiënt voor rode, groene en blauwe kanalen |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_24}


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

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_25}


```
 binarize_bradley(brightness_difference) 
```

Binarisatie van een afbeelding met Bradley's adaptieve drempelalgoritme met behulp van de integrale afbeeldingdrempel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brightness_difference | double | Het helderheidsverschil tussen een pixel en het gemiddelde van een s x s venster van pixels gecentreerd rond deze pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_26}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarisatie van een afbeelding met Bradley's adaptieve drempelalgoritme met behulp van de integrale afbeeldingdrempel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| brightness_difference | double | Het helderheidsverschil tussen een pixel en het gemiddelde van een s x s venster van pixels gecentreerd rond deze pixel. |
| window_size | int | De grootte van een s x s venster van pixels gecentreerd rond deze pixel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_27}


```
 binarize_fixed(threshold) 
```

Binarisatie van een afbeelding met vooraf gedefinieerde drempel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| threshold | byte | Drempelwaarde. Als de overeenkomstige grijze waarde van een pixel groter is dan de drempel, wordt een waarde van 255 aan deze pixel toegewezen, anders 0. |

### Method: can_load(file_path)  [static] {#can_load_file_path_28}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_29}


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


### Method: can_load(stream)  [static] {#can_load_stream_30}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_31}


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


### Method: can_save(options) {#can_save_options_32}


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


### Method: convert(new_options) {#convert_new_options_33}


```
 convert(new_options) 
```

Converteert dit afbeeldingformaat naar het formaat dat in de opties is opgegeven.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | De nieuwe opties. |

### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_34}


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


### Method: crop(rectangle) {#crop_rectangle_35}


```
 crop(rectangle) 
```

Bijsnijden van de afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_36}


```
 dither(dithering_method, bits_count) 
```

Voert dithering uit op de huidige afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | De ditheringmethode. |
| bits_count | int | Het uiteindelijke aantal bits voor dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_37}


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

### Method: filter(rectangle, options) {#filter_rectangle_options_38}


```
 filter(rectangle, options) 
```

Filtert de opgegeven rechthoek.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek. |
| options | [FilterOptionsBase](/psd/python-net/aspose.psd.imagefilters.filteroptions/filteroptionsbase/) | De opties. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_39}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_40}


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


### Method: get_default_options(args) {#get_default_options_args_41}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_42}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Haalt de standaard pixelarray op met behulp van de gedeeltelijke pixelloader.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om pixels voor op te halen. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | De gedeeltelijke pixelloader. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_44}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_45}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_46}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_47}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_48}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_49}


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


### Method: get_original_options() {#get_original_options__50}


```
 get_original_options() 
```

Haalt de opties op op basis van de oorspronkelijke bestandsinstellingen.<br/>            Dit kan nuttig zijn om de bitsdiepte en andere parameters van de oorspronkelijke afbeelding ongewijzigd te houden.<br/>            Bijvoorbeeld, als we een zwart-witte PNG-afbeelding met 1 bit per pixel laden en deze vervolgens opslaan met de<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) methode, wordt een PNG-uitvoerafbeelding met 8 bits per pixel gegenereerd.<br/>            Om dit te voorkomen en een PNG-afbeelding met 1 bit per pixel op te slaan, gebruik deze methode om de bijbehorende opslagopties op te halen en ze<br/>            door te geven aan de [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) methode als tweede parameter.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De opties gebaseerd op de oorspronkelijke bestandsinstellingen. |


### Method: get_pixel(x, y) {#get_pixel_x_y_51}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_52}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_53}


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


### Method: get_skew_angle() {#get_skew_angle__54}


```
 get_skew_angle() 
```

  

**Returns**

| Type | Beschrijving |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_55}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_56}


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


### Method: load(stream)  [static] {#load_stream_57}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_58}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_59}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_60}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_61}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_62}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Laadt 32-bit ARGB-pixels gedeeltelijk (per blokken).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om pixels uit te laden. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | De gedeeltelijke pixelloader. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_64}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Laadt pixels gedeeltelijk per pakketten.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De gewenste rechthoek. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | De pixelloader. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_65}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67}


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

### Method: merge_layers(bottom_layer, top_layer) {#merge_layers_bottom_layer_top_layer_68}


```
 merge_layers(bottom_layer, top_layer) 
```

Voegt de lagen samen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| bottom_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | De onderste laag. |
| top_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | De bovenste laag. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Onderste laag na het samenvoegen |


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_69}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_70}


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


### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_71}


```
 replace_color(old_color, old_color_diff, new_color) 
```

Vervangt één kleur door een andere met toegestane afwijking en behoudt de oorspronkelijke alfa‑waarde om vloeiende randen te behouden.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| old_color | [Color](/psd/python-net/aspose.psd/color) |  |
| old_color_diff | byte | Toegestane verschil in oude kleur om de vervangen kleurtoon te kunnen verbreden. |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_72}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

Vervangt één kleur door een andere met toegestane afwijking en behoudt de oorspronkelijke alfa‑waarde om vloeiende randen te behouden.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| old_color_argb | int | Oude kleur ARGB-waarde die moet worden vervangen. |
| old_color_diff | byte | Toegestane verschil in oude kleur om de vervangen kleurtoon te kunnen verbreden. |
| new_color_argb | int | Nieuwe kleur ARGB-waarde om de oude kleur mee te vervangen. |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_73}


```
 replace_non_transparent_colors(new_color) 
```

Vervangt alle niet-transparante kleuren door een nieuwe kleur en behoudt de originele alfabeta-waarde om vloeiende randen te behouden.<br/>            Opmerking: als je het toepast op afbeeldingen zonder transparantie, worden alle kleuren vervangen door één enkele kleur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_74}


```
 replace_non_transparent_colors(new_color_argb) 
```

Vervangt alle niet-transparante kleuren door een nieuwe kleur en behoudt de originele alfabeta-waarde om vloeiende randen te behouden.<br/>            Opmerking: als je het toepast op afbeeldingen zonder transparantie, worden alle kleuren vervangen door één enkele kleur.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_color_argb | int | Nieuwe kleur ARGB-waarde om niet-transparante kleuren mee te vervangen. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_75}


```
 resize(new_width, new_height) 
```

Wijzigt de grootte van de afbeelding. De standaard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wordt gebruikt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_width | int | De nieuwe breedte. |
| new_height | int | De nieuwe hoogte. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_76}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_77}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_78}


```
 resize_height_proportionally(new_height) 
```

Wijzigt de hoogte proportioneel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_height | int | De nieuwe hoogte. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_79}


```
 resize_height_proportionally(new_height, resize_type) 
```

Wijzigt de hoogte proportioneel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_height | int | De nieuwe hoogte. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Type van de verkleining. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_80}


```
 resize_height_proportionally(new_height, settings) 
```

Wijzigt de hoogte proportioneel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_height | int | De nieuwe hoogte. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | De instellingen voor het verkleinen van de afbeelding. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_81}


```
 resize_width_proportionally(new_width) 
```

Wijzigt de breedte proportioneel. De standaard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wordt gebruikt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_width | int | De nieuwe breedte. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_82}


```
 resize_width_proportionally(new_width, resize_type) 
```

Wijzigt de breedte proportioneel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_width | int | De nieuwe breedte. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Type van de verkleining. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_83}


```
 resize_width_proportionally(new_width, settings) 
```

Wijzigt de breedte proportioneel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_width | int | De nieuwe breedte. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | De instellingen voor het verkleinen van de afbeelding. |

### Method: rotate(angle) {#rotate_angle_84}


```
 rotate(angle) 
```

Roteer de afbeelding rond het midden.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| hoek | float | De rotatiehoek in graden. Positieve waarden roteren met de klok mee. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_85}


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

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_86}


```
 rotate_flip(rotate_flip_type) 
```

Roteert, spiegelt of roteert en spiegelt de afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Het type rotatie-flip. |

### Method: save(file_path) {#save_file_path_87}


```
 save(file_path) 
```

Slaat de gegevens van het object op op de opgegeven bestandslocatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad om de gegevens van het object op te slaan. |

### Method: save(file_path, options) {#save_file_path_options_88}


```
 save(file_path, options) 
```

Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De opties. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_89}


```
 save(file_path, options, bounds_rectangle) 
```

Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De opties. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De bestemmingsrechthoek voor afbeeldingsgrenzen. Stel de lege rechthoek in om de sourse‑grenzen te gebruiken. |

### Method: save(file_path, over_write) {#save_file_path_over_write_90}


```
 save(file_path, over_write) 
```

Slaat de gegevens van het object op op de opgegeven bestandslocatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad om de gegevens van het object op te slaan. |
| over_write | bool | als ingesteld op <c>true</c> wordt de bestandsinhoud overschreven, anders wordt er toegevoegd. |

### Method: save(stream) {#save_stream_91}


```
 save(stream) 
```

Slaat de gegevens van het object op in de opgegeven stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream om de gegevens van het object op te slaan. |

### Method: save(stream, options_base) {#save_stream_options_base_92}


```
 save(stream, options_base) 
```

Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream om de gegevens van de afbeelding op te slaan. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De opslagopties. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_93}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_94}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Slaat de 32-bit ARGB-pixels op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om pixels in op te slaan. |
| pixels | int | De 32-bit ARGB-pixelarray. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_95}


```
 save_pixels(rectangle, pixels) 
```

Slaat pixels op (formaatspecifieke methode).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om pixels in op te slaan. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | De 32-bit ARGB-pixelarray. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_96}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_97}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_98}


```
 set_palette(palette, update_colors) 
```

Stelt het palet van de afbeelding in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Het palet om in te stellen. |
| update_colors | bool | indien ingesteld op <c>true</c> worden kleuren bijgewerkt volgens het nieuwe palet; anders blijven kleurindexen ongewijzigd. Merk op dat ongewijzigde indexen de afbeelding kunnen laten crashen bij het laden als sommige indexen geen overeenkomstige paletinvoer hebben. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_99}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_100}


```
 set_resolution(dpi_x, dpi_y) 
```

Stelt de resolutie in voor deze [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| dpi_x | double | De horizontale resolutie, in dots per inch, van de [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| dpi_y | double | De verticale resolutie, in dots per inch, van de [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |

### Method: to_bitmap() {#to_bitmap__101}


```
 to_bitmap() 
```

  

**Returns**

| Type | Beschrijving |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Schrijft de volledige scanlijn naar de opgegeven scanlijnindex.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| scan_line_index | int | Nulgebaseerde index van de scanlijn. |
| argb_32_pixels | int | De 32-bit ARGB-kleurenarray om te schrijven. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_103}


```
 write_scan_line(scan_line_index, pixels) 
```

Schrijft de volledige scanlijn naar de opgegeven scanlijnindex.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| scan_line_index | int | Nulgebaseerde index van de scanlijn. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | De pixelkleurenarray om te schrijven. |

