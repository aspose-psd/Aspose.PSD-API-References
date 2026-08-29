---
title: "PsdImage Sınıfı"
type: docs
weight: 1760
url: /tr/python-net/aspose.psd.fileformats.psd/psdimage/
---

**Summary:** Defines the PsdImage class that provides the ability to load, edit, save PSD files as well as<br/>            update properties, add watermarks, perform graphics operations or convert one file format to another.<br/>            Aspose.PSD supports import as a layer and export to the following formats:<br/>            Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb along with export to Pdf with selectable text

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [PsdImage(path)](#PsdImage_path_1) | Belirtilen yoldan raster görüntüsü (yolda psd görüntüsü değil) kullanarak [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) sınıfının yeni bir örneğini başlatır. Varsayılan parametrelerle psd görüntüsünü başlatmak için kullanılır - Renk modu - rgb, 4 kanal, kanal başına 8 bit, Sıkıştırma - Raw. |
| [PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2) | Belirtilen yoldan raster görüntüsü (yolda psd görüntüsü değil) ve yapıcı parametreleriyle [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) sınıfının yeni bir örneğini başlatır. |
| [PsdImage(raster_image)](#PsdImage_raster_image_3) | Mevcut raster görüntüsünden (psd görüntüsü değil) RGB renk modu, 4 kanal, kanal başına 8 bit ve sıkıştırmasız olarak [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) sınıfının yeni bir örneğini başlatır. |
| [PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4) | Mevcut raster görüntüsünden (psd görüntüsü değil) yapıcı parametreleriyle [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) sınıfının yeni bir örneğini başlatır. |
| [PsdImage(stream)](#PsdImage_stream_5) | Belirtilen akıştan raster görüntüsü (akışta psd görüntüsü değil) kullanarak [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) sınıfının yeni bir örneğini başlatır. Varsayılan parametrelerle psd görüntüsünü başlatmak için kullanılır - Renk modu - rgb, 4 kanal, kanal başına 8 bit, Sıkıştırma - Raw. |
| [PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6) | Belirtilen akıştan raster görüntüsü (akışta psd görüntüsü değil) ve yapıcı parametreleriyle [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) sınıfının yeni bir örneğini başlatır. |
| [PsdImage(width, height)](#PsdImage_width_height_7) | Belirtilen genişlik ve yükseklik ile [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) sınıfının yeni bir örneğini başlatır. Boş psd görüntüsü oluşturmak için kullanılır. |
| [PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8) | Belirtilen genişlik, yükseklik, palet, renk modu, kanal sayısı ve kanal bit uzunluğu ve belirtilen sıkıştırma modu parametreleriyle [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) sınıfının yeni bir örneğini başlatır. Boş psd görüntüsü oluşturmak için kullanılır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| DEFAULT_VERSION [static] | int | r | Varsayılan PSD sürümü. |
| active_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | Etkin katmanı alır veya ayarlar. |
| auto_adjust_palette | bool | r/w | Otomatik palet ayarlamasını gösteren bir değeri alır veya ayarlar. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Arka plan renginin değerini alır veya ayarlar. |
| bits_per_channel | int | r | Kanal başına bit sayısını alır. |
| bits_per_pixel | int | r | Görüntünün piksel başına bit sayısını alır. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Nesnenin sınırlarını alır. |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| channels_count | int | r | PSD kanallarının sayısını alır. |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | CMYK PSD görüntüleri için CMYK renk profilini alır veya ayarlar. Doğru renk dönüşümü için RgbColorProfile ile eşleşmelidir. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r/w | Renk modunu alır veya ayarlar. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | r | Sıkıştırma yöntemini alır. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Alır [Image](/psd/python-net/aspose.psd/image/) kapsayıcısını. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Nesnenin veri akışını alır. |
| kapatıldı | bool | r | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Dosya formatının değerini alır |
| global_angle | int | r/w | Genel açıyı alır veya ayarlar. |
| global_layer_mask_info | [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | r | Genel katman maskesi bilgilerini alır. |
| global_layer_resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | r/w | Genel katman kaynaklarını alır veya ayarlar. |
| gray_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | Gri tonlamalı (monokrom) PSD görüntüleri için GRAY renk profilini alır veya ayarlar. |
| has_alpha | bool | r | Bu [RasterImage](/psd/python-net/aspose.psd/rasterimage/) öğesinin inç başına piksel cinsinden dikey çözünürlüğünü alır veya ayarlar. |
| arka_plan_rengi_var | bool | r/w | Görselin arka plan rengine sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| has_transparency_data | bool | r/w | Katman verileri belirtildiğinde birleştirilmiş sonuç için ilk alfa kanalının şeffaflık verisi içerip içermediğini gösteren bir değeri alır veya ayarlar. |
| şeffaf_renk_var | bool | r/w | Görselin şeffaf renge sahip olup olmadığını gösteren bir değeri alır. |
| yükseklik | int | r | Görselin yüksekliğini alır. |
| horizontal_resolution | double | r/w | Bu [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) öğesinin inç başına piksel cinsinden yatay çözünürlüğünü alır veya ayarlar. |
| görüntü_opaklığı | float | r | Bu görselin opaklığını alır. |
| image_resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock) | r/w | PSD görüntü kaynaklarını alır veya ayarlar. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Kesinti izleyicisini alır veya ayarlar. |
| önbellekte | bool | r | Görsel verisinin şu anda önbelleğe alınıp alınmadığını gösteren bir değeri alır. |
| is_flatten | bool | r | PSD görüntüsünün düzleştirilip düzleştirilmediğini gösteren bir değeri alır. |
| ham_veri_mevcut | bool | r | Ham veri yüklemenin desteklenip desteklenmediğini gösteren bir değeri alır. |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | PSD katmanlarını alır veya ayarlar. |
| linked_layers_manager | [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | r | Bağlantılı katman yöneticisini alır. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Renk paletini alır veya ayarlar. Renk paleti, pikseller doğrudan temsil edildiğinde kullanılmaz. |
| bileşenleri_ön_çarp | bool | r/w | Görüntü bileşenlerinin önceden çarpılmış olması gerekip gerekmediğini gösteren bir değeri alır veya ayarlar. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | Özel renk dönüştürücüyü alır veya ayarlar |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Ham veri biçimini alır. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Mevcut ham veri ayarlarını alır. Bu ayarları kullanırken verinin dönüşüm olmadan yüklendiğini unutmayın. |
| ham_yedek_indeks | int | r/w | Palet indeksi sınırların dışına çıktığında kullanılacak yedek indeksi alır veya ayarlar |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | İndeksli renk dönüştürücüyü alır veya ayarlar |
| ham_satır_boyutu | int | r | Ham satır boyutunu bayt cinsinden alır. |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | CMYK PSD görüntüleri için RGB renk profilini alır veya ayarlar. Doğru renk dönüşümü için CmykColorProfile ile eşleşmelidir. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Nesnenin boyutunu alır. |
| smart_object_provider | [SmartObjectProvider](/psd/python-net/aspose.psd.fileformats.psd/smartobjectprovider) | r | Akıllı nesne sağlayıcısını alır. |
| timeline | [Timeline](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/) | r | Bu [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) öğesinin [PsdImage.timeline](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) özelliğini alır. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Görüntünün şeffaf rengini alır. |
| update_xmp_data | bool | r/w | XMP meta verilerini güncelleyip güncellemeyeceğini gösteren bir değeri alır veya ayarlar. |
| use_palette | bool | r | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değeri alır. |
| use_raw_data | bool | r/w | Ham veri yüklemesi mevcut olduğunda ham veri yüklemesinin kullanılacağını gösteren bir değeri alır veya ayarlar. |
| version | int | r/w | Sürümü alır veya ayarlar. |
| vertical_resolution | double | r/w | Bu [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) öğesinin inç başına piksel cinsinden dikey çözünürlüğünü alır veya ayarlar. |
| width | int | r | Görüntünün genişliğini alır. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP meta verilerini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [add_black_white_adjustment_layer()](#add_black_white_adjustment_layer__1) | Siyah beyaz ayar katmanını ekler. |
| [add_brightness_contrast_adjustment_layer(brightness, contrast)](#add_brightness_contrast_adjustment_layer_brightness_contrast_2) | Parlaklık/kontrast ayar katmanını ekler. |
| [add_channel_mixer_adjustment_layer()](#add_channel_mixer_adjustment_layer__3) | Varsayılan parametrelerle kanal mikseri ayar katmanını ekler |
| [add_color_balance_adjustment_layer()](#add_color_balance_adjustment_layer__4) | Renk dengesi ayar katmanını ekler. |
| [add_curves_adjustment_layer()](#add_curves_adjustment_layer__5) | Eğriler ayar katmanını ekler. |
| [add_exposure_adjustment_layer(exposure, offset, gamma_correction)](#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6) | Pozlama ayar katmanını ekler. |
| [add_gradient_map_adjustment_layer()](#add_gradient_map_adjustment_layer__7) | GradientMap ayar katmanını ekler. |
| [add_hue_saturation_adjustment_layer()](#add_hue_saturation_adjustment_layer__8) | Ton/doygunluk ayar katmanını ekler. |
| [add_invert_adjustment_layer()](#add_invert_adjustment_layer__9) | Ters çevirme ayar katmanını ekler. |
| [add_layer(layer)](#add_layer_layer_10) | Katmanı ekler. |
| [add_layer_group(group_name, index, start_behaviour)](#add_layer_group_group_name_index_start_behaviour_11) | Katman grubunu ekler. |
| [add_levels_adjustment_layer()](#add_levels_adjustment_layer__12) | Seviye ayar katmanını ekler. |
| [add_photo_filter_layer(color)](#add_photo_filter_layer_color_13) | PhotoFilter katmanını ekler. |
| [add_posterize_adjustment_layer()](#add_posterize_adjustment_layer__14) | Posterize ayar katmanını ekler. |
| [add_regular_layer()](#add_regular_layer__15) | Yeni bir normal katman ekler. |
| [add_selective_color_adjustment_layer()](#add_selective_color_adjustment_layer__16) | Seçici renk ayar katmanını ekler. |
| [add_shape_layer()](#add_shape_layer__17) | Boş Şekil katmanı ekle.<br/>            Yollar olmadan. Kaydetmeden önce şekil katmanına eklenmelidir. |
| [add_text_layer(text, rect)](#add_text_layer_text_rect_18) | Yeni bir Metin katmanı ekler. |
| [add_threshold_adjustment_layer()](#add_threshold_adjustment_layer__19) | Eşik ayar katmanını ekler. |
| [add_vibrance_adjustment_layer()](#add_vibrance_adjustment_layer__20) | Canlılık ayar katmanını ekler. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_21) | Görüntünün parlaklığını ayarlar. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_22) | Görüntü kontrastı |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_23) | Bir görüntünün gama düzeltmesi. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_24) | Bir görüntünün gama düzeltmesi. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_25) | Bradley'in adaptif eşikleme algoritması ve integral görüntü eşikleme kullanarak bir görüntünün ikilileştirilmesi. |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_26) | Bradley'in adaptif eşikleme algoritması ve integral görüntü eşikleme kullanarak bir görüntünün ikilileştirilmesi. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_27) | Önceden tanımlı eşik ile bir görüntünün ikilileştirilmesi. |
| binarize_otsu() | Otsu eşikleme ile bir görüntünün ikilileştirilmesi. |
| cache_data() | Verileri önbelleğe alır ve temel [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) üzerinden ek veri yüklemesinin yapılmayacağını garanti eder. |
| [can_load(file_path)](#can_load_file_path_28) | Görüntünün belirtilen dosya yolundan yüklenip yüklenemeyeceğini belirler. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_29) | Görüntünün belirtilen dosya yolundan ve isteğe bağlı olarak belirtilen açma seçenekleri kullanılarak yüklenip yüklenemeyeceğini belirler. |
| [can_load(stream)](#can_load_stream_30) | Görüntünün belirtilen akıştan yüklenip yüklenemeyeceğini belirler. |
| [can_load(stream, load_options)](#can_load_stream_load_options_31) | Görüntünün belirtilen akıştan ve isteğe bağlı olarak belirtilen <paramref name="loadOptions" /> kullanılarak yüklenip yüklenemeyeceğini belirler. |
| [can_save(options)](#can_save_options_32) | Görüntünün, verilen kaydetme seçenekleriyle temsil edilen belirtilen dosya formatına kaydedilip kaydedilemeyeceğini belirler. |
| [convert(new_options)](#convert_new_options_33) | Bu görüntü formatını seçeneklerde belirtilen formata dönüştürür. |
| [create(image_options, width, height)](#create_image_options_width_height_34) | Belirtilen oluşturma seçenekleri kullanılarak yeni bir görüntü oluşturur. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_35) | Görüntüyü kırpar. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_36) | Mevcut görüntüde dithering uygular. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_37) | Mevcut görüntüde dithering uygular. |
| [filter(rectangle, options)](#filter_rectangle_options_38) | Belirtilen dikdörtgeni filtreler. |
| flatten_image() | Tüm katmanları düzleştirir. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_39) | 32-bit ARGB pikseli olan bir görüntüyü alır. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_40) | Varsayılan 32-bit ARGB piksel dizisini alır. |
| [get_default_options(args)](#get_default_options_args_41) | Varsayılan seçenekleri alır. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_42) | Kısmi piksel yükleyici kullanarak varsayılan piksel dizisini alır. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43) | Kısmi piksel yükleyici kullanarak varsayılan ham veri dizisini alır. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_44) | Varsayılan ham veri dizisini alır. |
| [get_file_format(file_path)](#get_file_format_file_path_45) | Dosya formatını alır. |
| [get_file_format(stream)](#get_file_format_stream_46) | Dosya formatını alır. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_47) | Geçerli görüntüyü saran dikdörtgeni alır. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_48) | Geçerli görüntüyü saran dikdörtgeni alır. |
| [get_modify_date(use_default)](#get_modify_date_use_default_49) | Kaynak görüntünün en son ne zaman değiştirildiğini gösteren tarih ve saati alır. |
| [get_original_options()](#get_original_options__50) | Orijinal dosya ayarlarına dayalı seçenekleri alır.<br/>            Bu, orijinal görüntünün bit derinliği ve diğer parametrelerinin değişmeden kalmasını sağlamak için faydalı olabilir.<br/>            Örneğin, 1 bit/piksel bir siyah-beyaz PNG görüntüsü yükleyip ardından<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) metodunu kullanarak kaydettiğimizde, çıktı PNG görüntüsü 8 bit/piksel olarak üretilecektir.<br/>            Bunu önlemek ve PNG görüntüsünü 1 bit/piksel olarak kaydetmek için, bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) metoduna ikinci parametre olarak geçirin. |
| [get_pixel(x, y)](#get_pixel_x_y_51) | Bir görüntü pikseli alır.<br/>            Performans Uyarısı: Tüm görüntü pikselleri üzerinde yineleme yapmak için bu yöntemi kullanmaktan kaçının, çünkü bu önemli performans sorunlarına yol açabilir.<br/>            Daha verimli piksel manipülasyonu için, tüm piksel dizisini aynı anda almak üzere `LoadArgb32Pixels` metodunu kullanın. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_52) | Orantılı bir yükseklik alır. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_53) | Orantılı bir genişlik alır. |
| [get_skew_angle()](#get_skew_angle__54) |    |
| grayscale() | Bir görüntünün gri tonlamalı temsiline dönüşümü |
| [load(file_path)](#load_file_path_55) | Belirtilen dosyadan yeni bir görüntü yükler. |
| [load(file_path, load_options)](#load_file_path_load_options_56) | Belirtilen dosyadan yeni bir görüntü yükler. |
| [load(stream)](#load_stream_57) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load(stream, load_options)](#load_stream_load_options_58) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_59) | 32-bit ARGB piksellerini yükler. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_60) | 64-bit ARGB piksellerini yükler. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_61) | CMYK formatında pikselleri yükler. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_62) | CMYK formatında pikselleri yükler.<br/>            Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) metodunu kullanın. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63) | 32-bit ARGB piksellerini kısmen (bloklar halinde) yükler. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_64) | Pikselleri paketler halinde kısmen yükler. |
| [load_pixels(rectangle)](#load_pixels_rectangle_65) | Pikselleri yükler. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66) | Ham verileri yükler. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67) | Ham verileri yükler. |
| [merge_layers(bottom_layer, top_layer)](#merge_layers_bottom_layer_top_layer_68) | Katmanları birleştirir. |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_69) | Belirtilen tarama satırı indeksiyle tüm tarama satırını okur. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_70) | Belirtilen tarama satırı indeksiyle tüm tarama satırını okur. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_71) | İzin verilen farkla bir rengi başka bir renk ile değiştirir ve pürüzsüz kenarları korumak için orijinal alfa değerini korur. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_72) | İzin verilen farkla bir rengi başka bir renk ile değiştirir ve pürüzsüz kenarları korumak için orijinal alfa değerini korur. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_73) | Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve orijinal alfa değerini koruyarak yumuşak kenarları korur.<br/>            Not: Şeffaflık içermeyen görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_74) | Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve orijinal alfa değerini koruyarak yumuşak kenarları korur.<br/>            Not: Şeffaflık içermeyen görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir. |
| [resize(new_width, new_height)](#resize_new_width_new_height_75) | Görüntüyü yeniden boyutlandırır. Varsayılan olarak [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) kullanılır. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_76) | Görüntüyü yeniden boyutlandırır. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_77) | Görüntüyü yeniden boyutlandırır. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_78) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_79) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_80) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_81) | Genişliği orantılı olarak yeniden boyutlandırır. Varsayılan olarak [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) kullanılır. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_82) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_83) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [rotate(angle)](#rotate_angle_84) | Görüntüyü merkezin etrafında döndürür. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_85) | Görüntüyü merkezin etrafında döndürür. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_86) | Görüntüyü döndürür, çevirir veya döndürüp çevirir. |
| kaydet() | Görüntü verilerini temel akışa kaydeder. |
| [save(file_path)](#save_file_path_87) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| [save(file_path, options)](#save_file_path_options_88) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_89) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| [save(file_path, over_write)](#save_file_path_over_write_90) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| [save(stream)](#save_stream_91) | Nesnenin verilerini belirtilen akışa kaydeder. |
| [save(stream, options_base)](#save_stream_options_base_92) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_93) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_94) | 32 bit ARGB piksellerini kaydeder. |
| cmyk_32_pikseli_kaydet(dikdörtgen, piksel) |  |
| cmyk_pikseli_kaydet(dikdörtgen, piksel) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_95) | Pikselleri kaydeder (biçime özgü yöntem). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_96) | Ham veriyi kaydeder. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_97) | Belirtilen konum için bir görüntü 32 bit ARGB pikseli ayarlar. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_98) | Görüntü paletini ayarlar. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_99) | Belirtilen konum için bir görüntü pikseli ayarlar. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_100) | Bu [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) için çözünürlüğü ayarlar. |
| [to_bitmap()](#to_bitmap__101) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102) | Tüm tarama satırını belirtilen tarama satırı indeksine yazar. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_103) | Tüm tarama satırını belirtilen tarama satırı indeksine yazar. |


### Constructor: PsdImage(path) {#PsdImage_path_1}


```
 PsdImage(path) 
```

Belirtilen yoldan raster görüntüsü (yolda psd görüntüsü değil) kullanarak [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) sınıfının yeni bir örneğini başlatır. Varsayılan parametrelerle psd görüntüsünü başlatmak için kullanılır - Renk modu - rgb, 4 kanal, kanal başına 8 bit, Sıkıştırma - Raw.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Piksel ve palet verilerini yüklemek ve başlatmak için yol. |

### Constructor: PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2}


```
 PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Belirtilen yoldan raster görüntüsü (yolda psd görüntüsü değil) ve yapıcı parametreleriyle [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Piksel ve palet verilerini yüklemek ve başlatmak için yol. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Renk modu. |
| channel_bit_depth | short | PSD kanal başına bit derinliği. |
| kanallar | short | PSD kanal sayısı. |
| psd_version | int | PSD sürümü. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Kullanılacak sıkıştırma. |

### Constructor: PsdImage(raster_image) {#PsdImage_raster_image_3}


```
 PsdImage(raster_image) 
```

Mevcut raster görüntüsünden (psd görüntüsü değil) RGB renk modu, 4 kanal, kanal başına 8 bit ve sıkıştırmasız olarak [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Piksel ve palet verilerini yüklemek ve başlatmak için kullanılacak görüntü. |

### Constructor: PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4}


```
 PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Mevcut raster görüntüsünden (psd görüntüsü değil) yapıcı parametreleriyle [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | Piksel ve palet verilerini yüklemek ve başlatmak için kullanılacak görüntü. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Renk modu. |
| channel_bit_depth | short | PSD kanal başına bit derinliği. |
| kanallar | short | PSD kanal sayısı. |
| psd_version | int | PSD sürümü. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Kullanılacak sıkıştırma. |

### Constructor: PsdImage(stream) {#PsdImage_stream_5}


```
 PsdImage(stream) 
```

Belirtilen akıştan raster görüntüsü (akışta psd görüntüsü değil) kullanarak [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) sınıfının yeni bir örneğini başlatır. Varsayılan parametrelerle psd görüntüsünü başlatmak için kullanılır - Renk modu - rgb, 4 kanal, kanal başına 8 bit, Sıkıştırma - Raw.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Piksel ve palet verilerini yüklemek ve başlatmak için kullanılacak akış. |

### Constructor: PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6}


```
 PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Belirtilen akıştan raster görüntüsü (akışta psd görüntüsü değil) ve yapıcı parametreleriyle [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Piksel ve palet verilerini yüklemek ve başlatmak için kullanılacak akış. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Renk modu. |
| channel_bit_depth | short | PSD kanal başına bit derinliği. |
| kanallar | short | PSD kanal sayısı. |
| psd_version | int | PSD sürümü. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Kullanılacak sıkıştırma. |

### Constructor: PsdImage(width, height) {#PsdImage_width_height_7}


```
 PsdImage(width, height) 
```

Belirtilen genişlik ve yükseklik ile [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) sınıfının yeni bir örneğini başlatır. Boş psd görüntüsü oluşturmak için kullanılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| width | int | Görüntü genişliği. |
| yükseklik | int | Görüntü yüksekliği. |

### Constructor: PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8}


```
 PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

Belirtilen genişlik, yükseklik, palet, renk modu, kanal sayısı ve kanal bit uzunluğu ve belirtilen sıkıştırma modu parametreleriyle [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) sınıfının yeni bir örneğini başlatır. Boş psd görüntüsü oluşturmak için kullanılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| width | int | Görüntü genişliği. |
| yükseklik | int | Görüntü yüksekliği. |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Renk paleti. |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | Renk modu. |
| channel_bit_depth | short | PSD kanal başına bit derinliği. |
| kanallar | short | PSD kanal sayısı. |
| psd_version | int | PSD sürümü. |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | Kullanılacak sıkıştırma. |

### Method: add_black_white_adjustment_layer() {#add_black_white_adjustment_layer__1}


```
 add_black_white_adjustment_layer() 
```

Siyah beyaz ayar katmanını ekler.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [BlackWhiteAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/) | Oluşturulan siyah beyaz ayar katmanı. |


### Method: add_brightness_contrast_adjustment_layer(brightness, contrast) {#add_brightness_contrast_adjustment_layer_brightness_contrast_2}


```
 add_brightness_contrast_adjustment_layer(brightness, contrast) 
```

Parlaklık/kontrast ayar katmanını ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| parlaklık | int | Parlaklık. |
| kontrast | int | Kontrast. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [BrightnessContrastLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer/) | Oluşturulan parlaklık/kontrast katmanı |


### Method: add_channel_mixer_adjustment_layer() {#add_channel_mixer_adjustment_layer__3}


```
 add_channel_mixer_adjustment_layer() 
```

Varsayılan parametrelerle kanal mikseri ayar katmanını ekler

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ChannelMixerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer/) | Eklenen Kanal Karıştırıcı Katmanı |


### Method: add_color_balance_adjustment_layer() {#add_color_balance_adjustment_layer__4}


```
 add_color_balance_adjustment_layer() 
```

Renk dengesi ayar katmanını ekler.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ColorBalanceAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/) | Yeni oluşturulan renk dengesi katmanı. |


### Method: add_curves_adjustment_layer() {#add_curves_adjustment_layer__5}


```
 add_curves_adjustment_layer() 
```

Eğriler ayar katmanını ekler.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) | Oluşturulan [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) Katmanı |


### Method: add_exposure_adjustment_layer(exposure, offset, gamma_correction) {#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6}


```
 add_exposure_adjustment_layer(exposure, offset, gamma_correction) 
```

Pozlama ayar katmanını ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| pozlama | float | Pozlama. |
| offset | float | Ofset. |
| gama_düzeltme | float | Gama düzeltmesi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ExposureLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer/) | Oluşturulan Pozlama Ayar Katmanı |


### Method: add_gradient_map_adjustment_layer() {#add_gradient_map_adjustment_layer__7}


```
 add_gradient_map_adjustment_layer() 
```

GradientMap ayar katmanını ekler.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [GradientMapLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/) | GradientMap örneği. |


### Method: add_hue_saturation_adjustment_layer() {#add_hue_saturation_adjustment_layer__8}


```
 add_hue_saturation_adjustment_layer() 
```

Ton/doygunluk ayar katmanını ekler.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [HueSaturationLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer/) | Yeni oluşturulan ton/doygunluk katmanı. |


### Method: add_invert_adjustment_layer() {#add_invert_adjustment_layer__9}


```
 add_invert_adjustment_layer() 
```

Ters çevirme ayar katmanını ekler.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [InvertAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/) | Oluşturulan ters çevirme katmanı |


### Method: add_layer(layer) {#add_layer_layer_10}


```
 add_layer(layer) 
```

Katmanı ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Katman. |

### Method: add_layer_group(group_name, index, start_behaviour) {#add_layer_group_group_name_index_start_behaviour_11}


```
 add_layer_group(group_name, index, start_behaviour) 
```

Katman grubunu ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| group_name | string | Grubun adı. |
| indeks | int | Eklenecek katmandan sonra eklenmesi gereken katmanın indeksi. |
| start_behaviour | bool | eğer <c>true</c> [start behaviour] olarak ayarlanırsa grup başlangıçta açık durumda olur, aksi takdirde küçültülmüş durumda olur. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | Grup katmanı açılıyor |


### Method: add_levels_adjustment_layer() {#add_levels_adjustment_layer__12}


```
 add_levels_adjustment_layer() 
```

Seviye ayar katmanını ekler.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [LevelsLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer/) | Yeni oluşturulan Seviyeler katmanı |


### Method: add_photo_filter_layer(color) {#add_photo_filter_layer_color_13}


```
 add_photo_filter_layer(color) 
```

PhotoFilter katmanını ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | Renk. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PhotoFilterLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer/) | Oluşturulan FotoFiltre Katmanı |


### Method: add_posterize_adjustment_layer() {#add_posterize_adjustment_layer__14}


```
 add_posterize_adjustment_layer() 
```

Posterize ayar katmanını ekler.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [PosterizeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/) | PosterizeLayer örneği. |


### Method: add_regular_layer() {#add_regular_layer__15}


```
 add_regular_layer() 
```

Yeni bir normal katman ekler.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Oluşturulan normal katman. |


### Method: add_selective_color_adjustment_layer() {#add_selective_color_adjustment_layer__16}


```
 add_selective_color_adjustment_layer() 
```

Seçici renk ayar katmanını ekler.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [SelectiveColorLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer/) | Oluşturulan seçici renk ayar katmanı. |


### Method: add_shape_layer() {#add_shape_layer__17}


```
 add_shape_layer() 
```

Boş Şekil katmanı ekle.<br/>            Yollar olmadan. Kaydetmeden önce şekil katmanına eklenmelidir.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | ShapeLayer örneği. |


### Method: add_text_layer(text, rect) {#add_text_layer_text_rect_18}


```
 add_text_layer(text, rect) 
```

Yeni bir Metin katmanı ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| text | string | Katmanın metni. |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Katmanın dikdörtgeni. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | Oluşturulan metin katmanı. |


### Method: add_threshold_adjustment_layer() {#add_threshold_adjustment_layer__19}


```
 add_threshold_adjustment_layer() 
```

Eşik ayar katmanını ekler.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ThresholdLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/) | Oluşturulan Eşik ayar katmanı. |


### Method: add_vibrance_adjustment_layer() {#add_vibrance_adjustment_layer__20}


```
 add_vibrance_adjustment_layer() 
```

Canlılık ayar katmanını ekler.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VibranceLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/) | Yeni oluşturulmuş Vibrance katmanı. |


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_21}


```
 adjust_brightness(brightness) 
```

Görüntünün parlaklığını ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| parlaklık | int | Parlaklık değeri. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_22}


```
 adjust_contrast(contrast) 
```

Görüntü kontrastı

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| kontrast | float | Kontrast değeri ([-100; 100] aralığında) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_23}


```
 adjust_gamma(gamma) 
```

Bir görüntünün gama düzeltmesi.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| gamma | float | Kırmızı, yeşil ve mavi kanallar için gamma katsayısı |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_24}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Bir görüntünün gama düzeltmesi.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| gamma_red | float | Kırmızı kanal için gamma katsayısı |
| gamma_green | float | Yeşil kanal için gamma katsayısı |
| gamma_blue | float | Mavi kanal için gamma katsayısı |

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_25}


```
 binarize_bradley(brightness_difference) 
```

Bradley'in adaptif eşikleme algoritması ve integral görüntü eşikleme kullanarak bir görüntünün ikilileştirilmesi.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brightness_difference | double | Piksel ile bu pikselin etrafında merkezlenmiş s x s piksellik pencerenin ortalaması arasındaki parlaklık farkı. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_26}


```
 binarize_bradley(brightness_difference, window_size) 
```

Bradley'in adaptif eşikleme algoritması ve integral görüntü eşikleme kullanarak bir görüntünün ikilileştirilmesi.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| brightness_difference | double | Piksel ile bu pikselin etrafında merkezlenmiş s x s piksellik pencerenin ortalaması arasındaki parlaklık farkı. |
| window_size | int | Bu pikselin etrafında merkezlenmiş s x s piksellik pencerenin boyutu |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_27}


```
 binarize_fixed(threshold) 
```

Önceden tanımlı eşik ile bir görüntünün ikilileştirilmesi.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| threshold | byte | Eşik değeri. Bir pikselin ilgili gri değeri eşikten büyükse, ona 255 değeri atanır, aksi takdirde 0. |

### Method: can_load(file_path)  [static] {#can_load_file_path_28}


```
 can_load(file_path) 
```

Görüntünün belirtilen dosya yolundan yüklenip yüklenemeyeceğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer görüntü belirtilen dosyadan yüklenebiliyorsa; aksi takdirde <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_29}


```
 can_load(file_path, load_options) 
```

Görüntünün belirtilen dosya yolundan ve isteğe bağlı olarak belirtilen açma seçenekleri kullanılarak yüklenip yüklenemeyeceğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Yükleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer görüntü belirtilen dosyadan yüklenebiliyorsa; aksi takdirde <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_30}


```
 can_load(stream) 
```

Görüntünün belirtilen akıştan yüklenip yüklenemeyeceğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Yükleme yapılacak akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer görüntü belirtilen akıştan yüklenebiliyorsa; aksi takdirde <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_31}


```
 can_load(stream, load_options) 
```

Görüntünün belirtilen akıştan ve isteğe bağlı olarak belirtilen <paramref name="loadOptions" /> kullanılarak yüklenip yüklenemeyeceğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Yükleme yapılacak akış. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Yükleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer görüntü belirtilen akıştan yüklenebiliyorsa; aksi takdirde <c>false</c>. |


### Method: can_save(options) {#can_save_options_32}


```
 can_save(options) 
```

Görüntünün, verilen kaydetme seçenekleriyle temsil edilen belirtilen dosya formatına kaydedilip kaydedilemeyeceğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Kullanılacak kaydetme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer görüntü, verilen kaydetme seçenekleriyle temsil edilen belirtilen dosya formatına kaydedilebiliyorsa; aksi takdirde <c>false</c>. |


### Method: convert(new_options) {#convert_new_options_33}


```
 convert(new_options) 
```

Bu görüntü formatını seçeneklerde belirtilen formata dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | Yeni seçenekler. |

### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_34}


```
 create(image_options, width, height) 
```

Belirtilen oluşturma seçenekleri kullanılarak yeni bir görüntü oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Görüntü seçenekleri. |
| width | int | Genişlik. |
| yükseklik | int | Yükseklik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Yeni oluşturulan görüntü. |


### Method: crop(rectangle) {#crop_rectangle_35}


```
 crop(rectangle) 
```

Görüntüyü kırpar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Dikdörtgen. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_36}


```
 dither(dithering_method, bits_count) 
```

Mevcut görüntüde dithering uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | Ditherleme yöntemi. |
| bits_count | int | Ditherleme için son bit sayısı. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_37}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Mevcut görüntüde dithering uygular.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | Ditherleme yöntemi. |
| bits_count | int | Ditherleme için son bit sayısı. |
| custom_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Ditherleme için özel palet. |

### Method: filter(rectangle, options) {#filter_rectangle_options_38}


```
 filter(rectangle, options) 
```

Belirtilen dikdörtgeni filtreler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Dikdörtgen. |
| options | [FilterOptionsBase](/psd/python-net/aspose.psd.imagefilters.filteroptions/filteroptionsbase/) | Seçenekler. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_39}


```
 get_argb_32_pixel(x, y) 
```

32-bit ARGB pikseli olan bir görüntüyü alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | int | Piksel x konumu. |
| y | int | Piksel y konumu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Belirtilen konum için 32-bit ARGB piksel. |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_40}


```
 get_default_argb_32_pixels(rectangle) 
```

Varsayılan 32-bit ARGB piksel dizisini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Pikselleri almak için dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Varsayılan piksel dizisi. |


### Method: get_default_options(args) {#get_default_options_args_41}


```
 get_default_options(args) 
```

Varsayılan seçenekleri alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| argümanlar | object | Argümanlar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Varsayılan seçenekler |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_42}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Kısmi piksel yükleyici kullanarak varsayılan piksel dizisini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Pikselleri almak için dikdörtgen. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Kısmi piksel yükleyici. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

Kısmi piksel yükleyici kullanarak varsayılan ham veri dizisini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Pikselleri almak için dikdörtgen. |
| partial_raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Kısmi ham veri yükleyici. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Ham veri ayarları. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_44}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

Varsayılan ham veri dizisini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ham veriyi almak için dikdörtgen. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Ham veri ayarları. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| byte | Varsayılan ham veri dizisi. |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_45}


```
 get_file_format(file_path) 
```

Dosya formatını alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Belirlenen dosya formatı. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_46}


```
 get_file_format(stream) 
```

Dosya formatını alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Belirlenen dosya formatı. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_47}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Geçerli görüntüyü saran dikdörtgeni alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Uygun dikdörtgeni almak için dikdörtgen. |
| piksel | int | 32-bit ARGB pikseller. |
| width | int | Nesnenin genişliği. |
| yükseklik | int | Nesnenin yüksekliği. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Uygun dikdörtgen veya uygun bir dikdörtgen bulunamazsa istisna. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_48}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Geçerli görüntüyü saran dikdörtgeni alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Uygun dikdörtgeni almak için dikdörtgen. |
| width | int | Nesnenin genişliği. |
| yükseklik | int | Nesnenin yüksekliği. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Uygun dikdörtgen veya uygun bir dikdörtgen bulunamazsa istisna. |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_49}


```
 get_modify_date(use_default) 
```

Kaynak görüntünün en son ne zaman değiştirildiğini gösteren tarih ve saati alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| use_default | bool | eğer <c>true</c> olarak ayarlanırsa, FileInfo'dan gelen bilgileri varsayılan değer olarak kullanır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| datetime | Kaynak görüntünün en son değiştirildiği tarih ve saat. |


### Method: get_original_options() {#get_original_options__50}


```
 get_original_options() 
```

Orijinal dosya ayarlarına dayalı seçenekleri alır.<br/>            Bu, orijinal görüntünün bit derinliği ve diğer parametrelerinin değişmeden kalmasını sağlamak için faydalı olabilir.<br/>            Örneğin, 1 bit/piksel bir siyah-beyaz PNG görüntüsü yükleyip ardından<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) metodunu kullanarak kaydettiğimizde, çıktı PNG görüntüsü 8 bit/piksel olarak üretilecektir.<br/>            Bunu önlemek ve PNG görüntüsünü 1 bit/piksel olarak kaydetmek için, bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) metoduna ikinci parametre olarak geçirin.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Orijinal dosya ayarlarına dayalı seçenekler. |


### Method: get_pixel(x, y) {#get_pixel_x_y_51}


```
 get_pixel(x, y) 
```

Bir görüntü pikseli alır.<br/>            Performans Uyarısı: Tüm görüntü pikselleri üzerinde yineleme yapmak için bu yöntemi kullanmaktan kaçının, çünkü bu önemli performans sorunlarına yol açabilir.<br/>            Daha verimli piksel manipülasyonu için, tüm piksel dizisini aynı anda almak üzere `LoadArgb32Pixels` metodunu kullanın.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | int | Piksel x konumu. |
| y | int | Piksel y konumu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | Belirtilen konum için piksel rengi. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_52}


```
 get_proportional_height(width, height, new_width) 
```

Orantılı bir yükseklik alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| width | int | Genişlik. |
| yükseklik | int | Yükseklik. |
| new_width | int | Yeni genişlik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Orantılı yükseklik. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_53}


```
 get_proportional_width(width, height, new_height) 
```

Orantılı bir genişlik alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| width | int | Genişlik. |
| yükseklik | int | Yükseklik. |
| new_height | int | Yeni yükseklik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Orantılı genişlik. |


### Method: get_skew_angle() {#get_skew_angle__54}


```
 get_skew_angle() 
```

  

**Returns**

| Tür | Açıklama |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_55}


```
 load(file_path) 
```

Belirtilen dosyadan yeni bir görüntü yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Görüntünün yükleneceği dosya yolu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Yüklenen görüntü. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_56}


```
 load(file_path, load_options) 
```

Belirtilen dosyadan yeni bir görüntü yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Görüntünün yükleneceği dosya yolu. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Yükleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Yüklenen görüntü. |


### Method: load(stream)  [static] {#load_stream_57}


```
 load(stream) 
```

Belirtilen akıştan yeni bir görüntü yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün yükleneceği akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Yüklenen görüntü. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_58}


```
 load(stream, load_options) 
```

Belirtilen akıştan yeni bir görüntü yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün yükleneceği akış. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Yükleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Yüklenen görüntü. |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_59}


```
 load_argb_32_pixels(rectangle) 
```

32-bit ARGB piksellerini yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Piksel yüklenecek dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Yüklenen 32-bit ARGB piksel dizisi. |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_60}


```
 load_argb_64_pixels(rectangle) 
```

64-bit ARGB piksellerini yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Piksel yüklenecek dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| long | Yüklenen 64-bit ARGB piksel dizisi. |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_61}


```
 load_cmyk_32_pixels(rectangle) 
```

CMYK formatında pikselleri yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Piksel yüklenecek dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Yüklenen CMYK pikselleri 32-bit tamsayı değerleri olarak sunulur. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_62}


```
 load_cmyk_pixels(rectangle) 
```

CMYK formatında pikselleri yükler.<br/>            Bu yöntem kullanımdan kaldırılmıştır. Lütfen daha etkili olan [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) metodunu kullanın.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Piksel yüklenecek dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Yüklenen CMYK piksel dizisi. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

32-bit ARGB piksellerini kısmen (bloklar halinde) yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Piksel yüklenecek dikdörtgen. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Kısmi piksel yükleyici. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_64}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Pikselleri paketler halinde kısmen yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | İstenen dikdörtgen. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | Piksel yükleyici. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_65}


```
 load_pixels(rectangle) 
```

Pikselleri yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Piksel yüklenecek dikdörtgen. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Yüklenen piksel dizisi. |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

Ham verileri yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ham veriyi yüklemek için dikdörtgen. |
| dest_image_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Hedef görüntünün sınırları. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Yüklenen veri için kullanılacak ham veri ayarları. Not: veri belirtilen formatta değilse veri dönüşümü gerçekleştirilecektir. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Ham veri yükleyicisi. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Ham verileri yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ham veriyi yüklemek için dikdörtgen. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Yüklenen veri için kullanılacak ham veri ayarları. Not: veri belirtilen formatta değilse veri dönüşümü gerçekleştirilecektir. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Ham veri yükleyicisi. |

### Method: merge_layers(bottom_layer, top_layer) {#merge_layers_bottom_layer_top_layer_68}


```
 merge_layers(bottom_layer, top_layer) 
```

Katmanları birleştirir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| bottom_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Alt katman. |
| top_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Üst katman. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Birleştirmeden sonraki alt katman |


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_69}


```
 read_argb_32_scan_line(scan_line_index) 
```

Belirtilen tarama satırı indeksiyle tüm tarama satırını okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| scan_line_index | int | Tarama satırının sıfır tabanlı indeksi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Tarama satırının 32-bit ARGB renk değerleri dizisi. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_70}


```
 read_scan_line(scan_line_index) 
```

Belirtilen tarama satırı indeksiyle tüm tarama satırını okur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| scan_line_index | int | Tarama satırının sıfır tabanlı indeksi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Tarama satırının piksel renk değerleri dizisi. |


### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_71}


```
 replace_color(old_color, old_color_diff, new_color) 
```

İzin verilen farkla bir rengi başka bir renk ile değiştirir ve pürüzsüz kenarları korumak için orijinal alfa değerini korur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| old_color | [Color](/psd/python-net/aspose.psd/color) |  |
| old_color_diff | byte | Değiştirilen renk tonunu genişletebilmek için eski renkte izin verilen fark. |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_72}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

İzin verilen farkla bir rengi başka bir renk ile değiştirir ve pürüzsüz kenarları korumak için orijinal alfa değerini korur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| old_color_argb | int | Değiştirilecek eski renk ARGB değeri. |
| old_color_diff | byte | Değiştirilen renk tonunu genişletebilmek için eski renkte izin verilen fark. |
| new_color_argb | int | Eski rengi değiştirmek için yeni renk ARGB değeri. |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_73}


```
 replace_non_transparent_colors(new_color) 
```

Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve orijinal alfa değerini koruyarak yumuşak kenarları korur.<br/>            Not: Şeffaflık içermeyen görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_74}


```
 replace_non_transparent_colors(new_color_argb) 
```

Tüm şeffaf olmayan renkleri yeni renk ile değiştirir ve orijinal alfa değerini koruyarak yumuşak kenarları korur.<br/>            Not: Şeffaflık içermeyen görüntülerde kullanırsanız, tüm renkler tek bir renk ile değiştirilecektir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_color_argb | int | Şeffaf olmayan renkleri değiştirmek için yeni renk ARGB değeri. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_75}


```
 resize(new_width, new_height) 
```

Görüntüyü yeniden boyutlandırır. Varsayılan olarak [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) kullanılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_76}


```
 resize(new_width, new_height, resize_type) 
```

Görüntüyü yeniden boyutlandırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Yeniden boyutlandırma türü. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_77}


```
 resize(new_width, new_height, settings) 
```

Görüntüyü yeniden boyutlandırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Yeniden boyutlandırma ayarları. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_78}


```
 resize_height_proportionally(new_height) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_79}


```
 resize_height_proportionally(new_height, resize_type) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Yeniden boyutlandırmanın türü. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_80}


```
 resize_height_proportionally(new_height, settings) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Görüntü yeniden boyutlandırma ayarları. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_81}


```
 resize_width_proportionally(new_width) 
```

Genişliği orantılı olarak yeniden boyutlandırır. Varsayılan olarak [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) kullanılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_82}


```
 resize_width_proportionally(new_width, resize_type) 
```

Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Yeniden boyutlandırmanın türü. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_83}


```
 resize_width_proportionally(new_width, settings) 
```

Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Görüntü yeniden boyutlandırma ayarları. |

### Method: rotate(angle) {#rotate_angle_84}


```
 rotate(angle) 
```

Görüntüyü merkezin etrafında döndürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| açı | float | Döndürme açısı derece cinsindendir. Pozitif değerler saat yönünde döndürür. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_85}


```
 rotate(angle, resize_proportionally, background_color) 
```

Görüntüyü merkezin etrafında döndürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| açı | float | Döndürme açısı derece cinsindendir. Pozitif değerler saat yönünde döndürür. |
| resize_proportionally | bool | eğer <c>true</c> olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgenin (köşe noktaları) izdüşümlerine göre değişir; diğer durumda boyutlar aynı kalır ve yalnızca iç görüntü içeriği döndürülür. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | Arka plan rengi. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_86}


```
 rotate_flip(rotate_flip_type) 
```

Görüntüyü döndürür, çevirir veya döndürüp çevirir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Döndürme/çevrilme türü. |

### Method: save(file_path) {#save_file_path_87}


```
 save(file_path) 
```

Nesnenin verilerini belirtilen dosya konumuna kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Nesnenin verisinin kaydedileceği dosya yolu. |

### Method: save(file_path, options) {#save_file_path_options_88}


```
 save(file_path, options) 
```

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Seçenekler. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_89}


```
 save(file_path, options, bounds_rectangle) 
```

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Seçenekler. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Hedef görüntü sınırları dikdörtgeni. Boş dikdörtgeni, kaynak sınırları için kullanmak üzere ayarlayın. |

### Method: save(file_path, over_write) {#save_file_path_over_write_90}


```
 save(file_path, over_write) 
```

Nesnenin verilerini belirtilen dosya konumuna kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Nesnenin verisinin kaydedileceği dosya yolu. |
| over_write | bool | eğer <c>true</c> olarak ayarlanırsa dosya içeriği üzerine yazılır, aksi takdirde ekleme yapılır. |

### Method: save(stream) {#save_stream_91}


```
 save(stream) 
```

Nesnenin verilerini belirtilen akışa kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Nesnenin verisinin kaydedileceği akış. |

### Method: save(stream, options_base) {#save_stream_options_base_92}


```
 save(stream, options_base) 
```

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün verisinin kaydedileceği akış. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Kaydetme seçenekleri. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_93}


```
 save(stream, options_base, bounds_rectangle) 
```

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün verisinin kaydedileceği akış. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Kaydetme seçenekleri. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Hedef görüntü sınırları dikdörtgeni. Kaynak sınırlarını kullanmak için boş bir dikdörtgen ayarlayın. |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_94}


```
 save_argb_32_pixels(rectangle, pixels) 
```

32 bit ARGB piksellerini kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Piksellerin kaydedileceği dikdörtgen. |
| piksel | int | 32 bit ARGB piksel dizisi. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_95}


```
 save_pixels(rectangle, pixels) 
```

Pikselleri kaydeder (biçime özgü yöntem).

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Piksellerin kaydedileceği dikdörtgen. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | 32 bit ARGB piksel dizisi. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_96}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

Ham veriyi kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| veri | byte | Ham veri. |
| data_offset | int | Başlangıç ham veri ofseti. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Ham veri dikdörtgeni. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Verinin bulunduğu ham veri ayarları. |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_97}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

Belirtilen konum için bir görüntü 32 bit ARGB pikseli ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | int | Piksel x konumu. |
| y | int | Piksel y konumu. |
| argb_32_color | int | Belirtilen konum için 32 bit ARGB piksel. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_98}


```
 set_palette(palette, update_colors) 
```

Görüntü paletini ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Ayarlanacak palet. |
| update_colors | bool | eğer <c>true</c> olarak ayarlanırsa renkler yeni palete göre güncellenir; aksi takdirde renk indeksleri değişmeden kalır. Değişmeyen indekslerin, bazı indekslerin karşılık gelen palet girdileri olmaması durumunda görüntünün yüklenirken çökmesine neden olabileceğini unutmayın. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_99}


```
 set_pixel(x, y, color) 
```

Belirtilen konum için bir görüntü pikseli ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | int | Piksel x konumu. |
| y | int | Piksel y konumu. |
| color | [Color](/psd/python-net/aspose.psd/color) | Belirtilen konum için piksel rengi. |

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_100}


```
 set_resolution(dpi_x, dpi_y) 
```

Bu [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) için çözünürlüğü ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| dpi_x | double | Yatay çözünürlük, inç başına nokta (dpi) cinsinden, [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| dpi_y | double | Dikey çözünürlük, inç başına nokta (dpi) cinsinden, [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |

### Method: to_bitmap() {#to_bitmap__101}


```
 to_bitmap() 
```

  

**Returns**

| Tür | Açıklama |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Tüm tarama satırını belirtilen tarama satırı indeksine yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| scan_line_index | int | Tarama satırının sıfır tabanlı indeksi. |
| argb_32_pixels | int | Yazılacak 32-bit ARGB renk dizisi. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_103}


```
 write_scan_line(scan_line_index, pixels) 
```

Tüm tarama satırını belirtilen tarama satırı indeksine yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| scan_line_index | int | Tarama satırının sıfır tabanlı indeksi. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Yazılacak piksel renkleri dizisi. |

