---
title: "SmartObjectLayer Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/
---

**Summary:** Defines the SmartObjectLayer class that contains embedded in the PSD file or linked smart object in the external file.<br/>            With Smart Objects, you can:<br/>            Perform nondestructive transforms. You can scale, rotate, skew, distort, perspective transform, or warp a layer<br/>            without losing original image data or quality because the transforms don�t affect the original data.<br/>            Work with vector data, such as vector artwork from Illustrator, that otherwise would be rasterized.<br/>            Perform nondestructive filtering. You can edit filters applied to Smart Objects at any time.<br/>            Edit one Smart Object and automatically update all its linked instances.<br/>            Apply a layer mask that�s either linked or unlinked to the Smart Object layer.<br/>            Try various designs with low-resolution placeholder images that you later replace with final versions.<br/>            In Adobe� Photoshop�, you can embed the contents of an image into a PSD document.<br/>            More information is here: <see href="https://helpx.adobe.com/photoshop/using/create-smart-objects.html" /><br/>            A layer with an embedded smart object contains placed (PlLd) and SoLd resources with smart object properties.<br/>            The PlLd resource can be alone for PSD versions older then 10.<br/>            These resources contain UniqueId of the LiFdDataSource in the global Lnk2Resource with the embedded filename<br/>            and other parameters, including the embedded file contents in the original format as a byte array.

**Module:** [aspose.psd.fileformats.psd.layers.smartobjects](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, Layer

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [SmartObjectLayer(stream)](#SmartObjectLayer_stream_1) | [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| BLEND_SIGNATURE [static] | int | r |  |
| LAYER_HEADER_SIZE [static] | int | r |  |
| auto_adjust_palette | bool | r/w |  |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w |    |
| bits_per_pixel | int | r |  |
| blend_clipped_elements | bool | r/w |  |
| blend_mode_key | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w |    |
| blend_mode_signature | int | r |  |
| blending_options | [BlendingOptions](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/) | r |    |
| alt | int | r/w |  |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Nesnenin sınırlarını alır. |
| buffer_size_hint | int | r/w |  |
| channel_information | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r/w |    |
| channels_count | ushort | r |  |
| clipping | byte | r/w |  |
| container | [Image](/psd/python-net/aspose.psd/image) | r |    |
| content_type | [SmartObjectType](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjecttype) | r | Akıllı nesne katmanının içeriğinin türünü alır.<br/>            Gömülü akıllı nesne içeriği, gömülü ham görüntü dosyasıdır: [LiFdDataSource.data](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifdddatasource/).<br/>            Bağlantılı akıllı nesne içeriği, mevcutsa bağlantılı görüntü dosyasının ham içeriğidir: [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/).<br/>            [LinkDataSource.is_library_link](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) doğru olduğunda Adobe� Photoshop� �� Graphics Library'den yüklemeyi desteklemiyoruz.<br/>            Normal bağlantı dosyaları için, önce dosyayı kaynak görüntü yolu [None](/psd/python-net/aspose.psd/datastreamsupporter/) ile göreceli olarak aramak için [LiFeDataSource.relative_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) kullanıyoruz,<br/>            mevcut değilse [LiFeDataSource.full_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) adresine bakıyoruz,<br/>            yoksa bağlantı dosyasını görüntümüzün bulunduğu aynı dizinde arıyoruz: [None](/psd/python-net/aspose.psd/datastreamsupporter/). |
| contents | byte | r/w | Akıllı nesne katmanının içeriğini alır veya ayarlar.<br/>            Gömülü akıllı nesne içeriği, gömülü ham görüntü dosyasıdır: [LiFdDataSource.data](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifdddatasource/) ve özellikleridir.<br/>            Bağlantılı akıllı nesne içeriği, mevcutsa bağlantılı görüntü dosyasının ham içeriği ve özellikleridir: [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/).<br/>            [LinkDataSource.is_library_link](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) doğru olduğunda Adobe� Photoshop� �� Graphics Library'den yüklemeyi desteklemiyoruz.<br/>            Normal bağlantı dosyaları için, önce dosyayı kaynak görüntü yolu [None](/psd/python-net/aspose.psd/datastreamsupporter/) ile göreceli olarak aramak için [LiFeDataSource.relative_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) kullanıyoruz,<br/>            mevcut değilse [LiFeDataSource.full_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) adresine bakıyoruz,<br/>            yoksa bağlantı dosyasını görüntümüzün bulunduğu aynı dizinde arıyoruz: [None](/psd/python-net/aspose.psd/datastreamsupporter/). |
| contents_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | Akıllı nesne içeriğinin sınırlarını alır veya ayarlar. |
| contents_source | [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) | r/w | Akıllı nesne içeriğinin kaynağını alır veya ayarlar. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r |    |
| görüntü_adı | string | r/w |  |
| kapatıldı | bool | r |  |
| ek_uzunluk | int | r |  |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r |    |
| dolgu_opaklığı | int | r/w |  |
| doldurucu | byte | r/w |  |
| flags | [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags) | r/w |    |
| alfa_var | bool | r |  |
| arka_plan_rengi_var | bool | r/w |  |
| şeffaf_renk_var | bool | r/w |  |
| yükseklik | int | r | Nesnenin yüksekliğini alır. |
| yatay_çözünürlük | double | r/w |  |
| görüntü_opaklığı | float | r |  |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w |    |
| önbellekte | bool | r |  |
| ham_veri_mevcut | bool | r | Ham veri yüklemenin desteklenip desteklenmediğini gösteren bir değeri alır. |
| görünür | bool | r/w |  |
| grupta_görünür | bool | r |  |
| layer_blending_ranges_data | [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata) | r/w |    |
| katman_oluşturma_tarih_saat | datetime | r/w |  |
| layer_lock | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | r/w |    |
| layer_mask_data | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | r/w |    |
| layer_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | r |    |
| sol | int | r/w |  |
| uzunluk | int | r |  |
| name | string | r/w | Metin katmanının adını alır veya ayarlar. |
| opaklık | byte | r/w |  |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w |    |
| bileşenleri_ön_çarp | bool | r/w |  |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w |    |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r |    |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Mevcut ham veri ayarlarını alır. Bu ayarları kullanırken verinin dönüşüm olmadan yüklendiğini unutmayın. |
| ham_yedek_indeks | int | r/w |  |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w |    |
| ham_satır_boyutu | int | r |  |
| resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r/w |    |
| sağ | int | r/w |  |
| sheet_color_highlight | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | r/w |    |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Nesnenin boyutunu alır. |
| smart_filters | [SmartFilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilters/) | r | Akıllı filtreleri alır. |
| smart_object_provider | [SmartObjectProvider](/psd/python-net/aspose.psd.fileformats.psd/smartobjectprovider) | r | Akıllı nesne sağlayıcısını alır. |
| üst | int | r/w |  |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w |    |
| update_xmp_data | bool | r/w |  |
| use_palette | bool | r |  |
| use_raw_data | bool | r/w |  |
| vertical_resolution | double | r/w |  |
| warp_settings | [WarpSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.warp/warpsettings/) | r/w | Kaynak üzerinden ayarlanmış veya alınmış Warp parametrelerini alır veya ayarlar (varsayılan). |
| width | int | r | Nesnenin genişliğini alır. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w |    |
## **Methods**
| **Name** | **Açıklama** |
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
| [convert_to_linked(linked_path)](#convert_to_linked_linked_path_6) | Bu gömülü akıllı nesneyi bağlı bir akıllı nesneye dönüştürür. |
| [create(image_options, width, height)](#create_image_options_width_height_7) |    |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| crop(rectangle) |  |
| dither(dithering_method, bits_count) |  |
| dither(dithering_method, bits_count, custom_palette) |  |
| draw_image(location, image) |  |
| [duplicate_layer()](#duplicate_layer__8) | Bu katmanı kopyalayarak yeni bir akıllı nesne katmanı oluşturur.<br/>            Gömülü akıllı nesneler için gömülü görüntünün paylaşıldığını unutmayın.<br/>            Gömülü görüntüyü kopyalamak istiyorsanız [SmartObjectLayer.new_smart_object_via_copy()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) yöntemini kullanın. |
| embed_linked() | Bağlı akıllı nesneyi bu katmana gömer. |
| [export_contents(file_path)](#export_contents_file_path_9) | Gömülü veya bağlı içerikleri bir dosyaya dışa aktarır. |
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
| [load_contents(options)](#load_contents_options_32) | Akıllı nesne katmanının gömülü veya bağlı görüntü içeriklerini alır. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33) | 32-bit ARGB piksellerini kısmen (bloklar halinde) yükler. |
| load_partial_pixels(desired_rectangle, pixel_loader) |  |
| [load_pixels(rectangle)](#load_pixels_rectangle_34) |    |
| load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) |  |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_35) | Ham verileri yükler. |
| merge_layer_to(layer_to_merge_into) |  |
| [new_smart_object_via_copy()](#new_smart_object_via_copy__36) | Bu katmanı kopyalayarak yeni bir akıllı nesne katmanı oluşturur.<br/>            Adobe Photoshop'un `Layer -&gt; Smart Objects -&gt; New Smart Object via Copy` işlevselliğini yeniden üretir.<br/>            Yalnızca gömülü akıllı nesneler için etkin olduğunu, çünkü gömülü görüntünün de kopyalandığını unutmayın.<br/>            Gömülü görüntüyü paylaşmak istiyorsanız [SmartObjectLayer.duplicate_layer()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) yöntemini kullanın. |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_37) |    |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_38) |    |
| [relink_to_file(linked_path)](#relink_to_file_linked_path_39) | Bağlı akıllı nesneyi yeni bir dosyaya yeniden bağlar.<br/>            Daha sonra UpdateModifiedContent yöntemini çağırmaya gerek yoktur. |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| [replace_contents(image)](#replace_contents_image_40) | Akıllı nesne katmanında gömülü akıllı nesne içeriklerini değiştirir. |
| [replace_contents(image, resolution)](#replace_contents_image_resolution_41) | Akıllı nesne katmanında gömülü akıllı nesne içeriklerini değiştirir. |
| [replace_contents(linked_path)](#replace_contents_linked_path_42) | İçerikleri bir dosyayla değiştirir.<br/>            Daha sonra UpdateModifiedContent yöntemini çağırmaya gerek yoktur. |
| [replace_contents(linked_path, resolution)](#replace_contents_linked_path_resolution_43) | İçerikleri bir dosyayla değiştirir.<br/>            Daha sonra UpdateModifiedContent yöntemini çağırmaya gerek yoktur. |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| resize(new_width, new_height) |  |
| resize(new_width, new_height, resize_type) |  |
| boyutlandır(yeni_genişlik, yeni_yükseklik, ayarlar) |  |
| yüksekliği_orantılı_olarak_boyutlandır(yeni_yükseklik) |  |
| yüksekliği_orantılı_olarak_boyutlandır(yeni_yükseklik, boyutlandırma_türü) |  |
| yüksekliği_orantılı_olarak_boyutlandır(yeni_yükseklik, ayarlar) |  |
| genişliği_orantılı_olarak_boyutlandır(yeni_genişlik) |  |
| genişliği_orantılı_olarak_boyutlandır(yeni_genişlik, boyutlandırma_türü) |  |
| genişliği_orantılı_olarak_boyutlandır(yeni_genişlik, ayarlar) |  |
| döndür(açı) |  |
| döndür(açı, orantılı_boyutlandır, arka_plan_rengi) |  |
| döndür_çevir(döndür_çevir_türü) |  |
| kaydet() |  |
| kaydet(dosya_yolu) |  |
| kaydet(dosya_yolu, seçenekler) |  |
| kaydet(dosya_yolu, seçenekler, sınır_dikdörtgeni) |  |
| kaydet(dosya_yolu, üzerine_yaz) |  |
| kaydet(akış) |  |
| kaydet(akış, seçenekler_tabani) |  |
| kaydet(akış, seçenekler_tabani, sınır_dikdörtgeni) |  |
| argb_32_pikseli_kaydet(dikdörtgen, piksel) |  |
| cmyk_32_pikseli_kaydet(dikdörtgen, piksel) |  |
| cmyk_pikseli_kaydet(dikdörtgen, piksel) |  |
| pikseli_kaydet(dikdörtgen, piksel) |  |
| ham_veriyi_kaydet(veri, veri_ofseti, dikdörtgen, ham_veri_ayarları) |  |
| argb_32_pikselini_ayarla(x, y, argb_32_renk) |  |
| paleti_ayarla(palet, renkleri_güncelle) |  |
| set_pixel(x, y, color) |  |
| set_resolution(dpi_x, dpi_y) |  |
| [shallow_copy()](#shallow_copy__44) |    |
| [to_bitmap()](#to_bitmap__45) |    |
| update_modified_content() | Akıllı nesne katmanı görüntü önbelleğini değiştirilmiş içerikle günceller. |
| write_argb_32_scan_line(scan_line_index, argb_32_pixels) |  |
| write_scan_line(scan_line_index, pixels) |  |


### Constructor: SmartObjectLayer(stream) {#SmartObjectLayer_stream_1}


```
 SmartObjectLayer(stream) 
```

[SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) sınıfının yeni bir örneğini başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Öğelerin akışı. |

### Method: can_load(file_path)  [static] {#can_load_file_path_1}


```
 can_load(file_path) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool |  |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


```
 can_load(file_path, load_options) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool |  |


### Method: can_load(stream)  [static] {#can_load_stream_3}


```
 can_load(stream) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool |  |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


```
 can_load(stream, load_options) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool |  |


### Method: can_save(options) {#can_save_options_5}


```
 can_save(options) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool |  |


### Method: convert_to_linked(linked_path) {#convert_to_linked_linked_path_6}


```
 convert_to_linked(linked_path) 
```

Bu gömülü akıllı nesneyi bağlı bir akıllı nesneye dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| linked_path | string | Bağlı yol. |

### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_7}


```
 create(image_options, width, height) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |
| width | int |  |
| yükseklik | int |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: duplicate_layer() {#duplicate_layer__8}


```
 duplicate_layer() 
```

Bu katmanı kopyalayarak yeni bir akıllı nesne katmanı oluşturur.<br/>            Gömülü akıllı nesneler için gömülü görüntünün paylaşıldığını unutmayın.<br/>            Gömülü görüntüyü kopyalamak istiyorsanız [SmartObjectLayer.new_smart_object_via_copy()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) yöntemini kullanın.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | Klonlanmış [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) örneği. |


### Method: export_contents(file_path) {#export_contents_file_path_9}


```
 export_contents(file_path) 
```

Gömülü veya bağlı içerikleri bir dosyaya dışa aktarır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dışa aktarma dosya yolu. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_10}


```
 get_argb_32_pixel(x, y) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | int |  |
| y | int |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int |  |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_11}


```
 get_default_argb_32_pixels(rectangle) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int |  |


### Method: get_default_options(args) {#get_default_options_args_12}


```
 get_default_options(args) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| argümanlar | object |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |


### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_13}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| byte |  |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_14}


```
 get_file_format(file_path) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) |  |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_15}


```
 get_file_format(stream) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) |  |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_16}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| piksel | int |  |
| width | int |  |
| yükseklik | int |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_17}


```
 get_fitting_rectangle(rectangle, width, height) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| width | int |  |
| yükseklik | int |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_18}


```
 get_modify_date(use_default) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| use_default | bool |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| datetime |  |


### Method: get_original_options() {#get_original_options__19}


```
 get_original_options() 
```

  

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |


### Method: get_pixel(x, y) {#get_pixel_x_y_20}


```
 get_pixel(x, y) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | int |  |
| y | int |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) |  |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_21}


```
 get_proportional_height(width, height, new_width) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| width | int |  |
| yükseklik | int |  |
| new_width | int |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int |  |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_22}


```
 get_proportional_width(width, height, new_height) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| width | int |  |
| yükseklik | int |  |
| new_height | int |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int |  |


### Method: get_skew_angle() {#get_skew_angle__23}


```
 get_skew_angle() 
```

  

**Returns**

| Tür | Açıklama |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_24}


```
 load(file_path) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_25}


```
 load(file_path, load_options) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(stream)  [static] {#load_stream_26}


```
 load(stream) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_27}


```
 load(stream, load_options) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_28}


```
 load_argb_32_pixels(rectangle) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int |  |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_29}


```
 load_argb_64_pixels(rectangle) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| long |  |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_30}


```
 load_cmyk_32_pixels(rectangle) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int |  |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_31}


```
 load_cmyk_pixels(rectangle) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) |  |


### Method: load_contents(options) {#load_contents_options_32}


```
 load_contents(options) 
```

Akıllı nesne katmanının gömülü veya bağlı görüntü içeriklerini alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Yüklenen [Image](/psd/python-net/aspose.psd/image/) akıllı nesne örneği. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

32-bit ARGB piksellerini kısmen (bloklar halinde) yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Piksel yüklenecek dikdörtgen. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Kısmi piksel yükleyici. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_34}


```
 load_pixels(rectangle) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) |  |


### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_35}


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

### Method: new_smart_object_via_copy() {#new_smart_object_via_copy__36}


```
 new_smart_object_via_copy() 
```

Bu katmanı kopyalayarak yeni bir akıllı nesne katmanı oluşturur.<br/>            Adobe Photoshop'un `Layer -&gt; Smart Objects -&gt; New Smart Object via Copy` işlevselliğini yeniden üretir.<br/>            Yalnızca gömülü akıllı nesneler için etkin olduğunu, çünkü gömülü görüntünün de kopyalandığını unutmayın.<br/>            Gömülü görüntüyü paylaşmak istiyorsanız [SmartObjectLayer.duplicate_layer()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) yöntemini kullanın.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | Klonlanmış [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) örneği. |


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_37}


```
 read_argb_32_scan_line(scan_line_index) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| scan_line_index | int |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int |  |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_38}


```
 read_scan_line(scan_line_index) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| scan_line_index | int |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) |  |


### Method: relink_to_file(linked_path) {#relink_to_file_linked_path_39}


```
 relink_to_file(linked_path) 
```

Bağlı akıllı nesneyi yeni bir dosyaya yeniden bağlar.<br/>            Daha sonra UpdateModifiedContent yöntemini çağırmaya gerek yoktur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| linked_path | string | Bağlı yol. |

### Method: replace_contents(image) {#replace_contents_image_40}


```
 replace_contents(image) 
```

Akıllı nesne katmanında gömülü akıllı nesne içeriklerini değiştirir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Görsel. |

### Method: replace_contents(image, resolution) {#replace_contents_image_resolution_41}


```
 replace_contents(image, resolution) 
```

Akıllı nesne katmanında gömülü akıllı nesne içeriklerini değiştirir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | Görsel. |
| resolution | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | Çözünürlük ayarları. Null ise görsel çözünürlüğü kullanılacaktır. |

### Method: replace_contents(linked_path) {#replace_contents_linked_path_42}


```
 replace_contents(linked_path) 
```

İçerikleri bir dosyayla değiştirir.<br/>            Daha sonra UpdateModifiedContent yöntemini çağırmaya gerek yoktur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| linked_path | string | Bağlı yol. |

### Method: replace_contents(linked_path, resolution) {#replace_contents_linked_path_resolution_43}


```
 replace_contents(linked_path, resolution) 
```

İçerikleri bir dosyayla değiştirir.<br/>            Daha sonra UpdateModifiedContent yöntemini çağırmaya gerek yoktur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| linked_path | string | Bağlı yol. |
| resolution | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | Çözünürlük ayarları. Null ise görsel çözünürlüğü kullanılacaktır. |

### Method: shallow_copy() {#shallow_copy__44}


```
 shallow_copy() 
```

  

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) |  |


### Method: to_bitmap() {#to_bitmap__45}


```
 to_bitmap() 
```

  

**Returns**

| Tür | Açıklama |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


