---
title: "SmartObjectLayer क्लास"
type: docs
weight: 10
url: /hi/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/
---

**Summary:** Defines the SmartObjectLayer class that contains embedded in the PSD file or linked smart object in the external file.<br/>            With Smart Objects, you can:<br/>            Perform nondestructive transforms. You can scale, rotate, skew, distort, perspective transform, or warp a layer<br/>            without losing original image data or quality because the transforms don�t affect the original data.<br/>            Work with vector data, such as vector artwork from Illustrator, that otherwise would be rasterized.<br/>            Perform nondestructive filtering. You can edit filters applied to Smart Objects at any time.<br/>            Edit one Smart Object and automatically update all its linked instances.<br/>            Apply a layer mask that�s either linked or unlinked to the Smart Object layer.<br/>            Try various designs with low-resolution placeholder images that you later replace with final versions.<br/>            In Adobe� Photoshop�, you can embed the contents of an image into a PSD document.<br/>            More information is here: <see href="https://helpx.adobe.com/photoshop/using/create-smart-objects.html" /><br/>            A layer with an embedded smart object contains placed (PlLd) and SoLd resources with smart object properties.<br/>            The PlLd resource can be alone for PSD versions older then 10.<br/>            These resources contain UniqueId of the LiFdDataSource in the global Lnk2Resource with the embedded filename<br/>            and other parameters, including the embedded file contents in the original format as a byte array.

**Module:** [aspose.psd.fileformats.psd.layers.smartobjects](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/)

**Full Name:** aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, Layer

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [SmartObjectLayer(stream)](#SmartObjectLayer_stream_1) | नए [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) क्लास का एक नया उदाहरण प्रारंभ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| BLEND_SIGNATURE [स्थैतिक] | int | r |  |
| LAYER_HEADER_SIZE [स्थैतिक] | int | r |  |
| स्वत:_समायोजित_पैलेट | bool | r/w |  |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w |    |
| बिट्स_प्रति_पिक्सेल | int | r |  |
| ब्लेंड_क्लिप्ड_एलिमेंट्स | bool | r/w |  |
| blend_mode_key | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w |    |
| ब्लेंड_मोड_सिग्नेचर | int | r |  |
| blending_options | [BlendingOptions](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/) | r |    |
| नीचे | int | r/w |  |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| बफ़र_आकार_संकेत | int | r/w |  |
| channel_information | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r/w |    |
| चैनल्स_गणना | ushort | r |  |
| क्लिपिंग | byte | r/w |  |
| container | [Image](/psd/python-net/aspose.psd/image) | r |    |
| content_type | [SmartObjectType](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjecttype) | r | स्मार्ट ऑब्जेक्ट लेयर सामग्री का प्रकार प्राप्त करता है।<br/> एम्बेडेड स्मार्ट ऑब्जेक्ट सामग्री एम्बेडेड रॉ इमेज फ़ाइल है: [LiFdDataSource.data](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifdddatasource/).<br/> लिंक्ड स्मार्ट ऑब्जेक्ट सामग्री उपलब्ध होने पर लिंक्ड इमेज फ़ाइल की रॉ सामग्री है: [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/).<br/> जब [LinkDataSource.is_library_link](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) सत्य है, तो हम Adobe� Photoshop� �� ग्राफ़िक्स लाइब्रेरी से लोडिंग का समर्थन नहीं करते।<br/> सामान्य लिंक फ़ाइलों के लिए, पहले हम [LiFeDataSource.relative_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) का उपयोग करके फ़ाइल को स्रोत इमेज पाथ [None](/psd/python-net/aspose.psd/datastreamsupporter/) के सापेक्ष खोजते हैं, यदि उपलब्ध नहीं है तो हम [LiFeDataSource.full_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) को देखते हैं, यदि फिर भी नहीं तो हम लिंक फ़ाइल को उसी डायरेक्टरी में देखते हैं जहाँ हमारी इमेज है: [None](/psd/python-net/aspose.psd/datastreamsupporter/). |
| contents | byte | r/w | स्मार्ट ऑब्जेक्ट लेयर सामग्री प्राप्त करता है या सेट करता है।<br/> एम्बेडेड स्मार्ट ऑब्जेक्ट सामग्री एम्बेडेड रॉ इमेज फ़ाइल है: [LiFdDataSource.data](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifdddatasource/) और इसकी प्रॉपर्टीज़।<br/> लिंक्ड स्मार्ट ऑब्जेक्ट सामग्री उपलब्ध होने पर लिंक्ड इमेज फ़ाइल की रॉ सामग्री है और इसकी प्रॉपर्टीज़: [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/).<br/> जब [LinkDataSource.is_library_link](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) सत्य है, तो हम Adobe� Photoshop� �� ग्राफ़िक्स लाइब्रेरी से लोडिंग का समर्थन नहीं करते।<br/> सामान्य लिंक फ़ाइलों के लिए, पहले हम [LiFeDataSource.relative_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) का उपयोग करके फ़ाइल को स्रोत इमेज पाथ [None](/psd/python-net/aspose.psd/datastreamsupporter/) के सापेक्ष खोजते हैं, यदि उपलब्ध नहीं है तो हम [LiFeDataSource.full_path](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) को देखते हैं, यदि फिर भी नहीं तो हम लिंक फ़ाइल को उसी डायरेक्टरी में देखते हैं जहाँ हमारी इमेज है: [None](/psd/python-net/aspose.psd/datastreamsupporter/). |
| contents_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | स्मार्ट ऑब्जेक्ट सामग्री की सीमाएँ प्राप्त करता है या सेट करता है। |
| contents_source | [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) | r/w | स्मार्ट ऑब्जेक्ट सामग्री का स्रोत प्राप्त करता है या सेट करता है। |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r |    |
| प्रदर्शित_नाम | string | r/w |  |
| disposed | bool | r |  |
| extra_length | int | r |  |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r |    |
| fill_opacity | int | r/w |  |
| filler | byte | r/w |  |
| flags | [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags) | r/w |    |
| has_alpha | bool | r |  |
| has_background_color | bool | r/w |  |
| has_transparent_color | bool | r/w |  |
| height | int | r | ऑब्जेक्ट की ऊँचाई प्राप्त करता है। |
| horizontal_resolution | डबल | r/w |  |
| image_opacity | float | r |  |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w |    |
| is_cached | bool | r |  |
| is_raw_data_available | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि कच्चा डेटा लोडिंग समर्थित है या नहीं। |
| is_visible | bool | r/w |  |
| is_visible_in_group | bool | r |  |
| layer_blending_ranges_data | [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata) | r/w |    |
| layer_creation_date_time | datetime | r/w |  |
| layer_lock | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | r/w |    |
| layer_mask_data | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | r/w |    |
| layer_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | r |    |
| left | int | r/w |  |
| लंबाई | int | r |  |
| name | string | r/w | टेक्स्ट लेयर का नाम प्राप्त करता है या सेट करता है। |
| opacity | byte | r/w |  |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w |    |
| premultiply_components | bool | r/w |  |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w |    |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r |    |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | वर्तमान कच्चा डेटा सेटिंग्स प्राप्त करता है। नोट: इन सेटिंग्स का उपयोग करने पर डेटा बिना रूपांतरण के लोड होता है। |
| raw_fallback_index | int | r/w |  |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w |    |
| raw_line_size | int | r |  |
| resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r/w |    |
| right | int | r/w |  |
| sheet_color_highlight | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | r/w |    |
| size | [Size](/psd/python-net/aspose.psd/size) | r | ऑब्जेक्ट का आकार प्राप्त करता है। |
| smart_filters | [SmartFilters](/psd/python-net/aspose.psd.fileformats.psd.layers.smartfilters/smartfilters/) | r | स्मार्ट फ़िल्टर प्राप्त करता है। |
| smart_object_provider | [SmartObjectProvider](/psd/python-net/aspose.psd.fileformats.psd/smartobjectprovider) | r | स्मार्ट ऑब्जेक्ट प्रदाता को प्राप्त करता है। |
| ऊपर | int | r/w |  |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w |    |
| update_xmp_data | bool | r/w |  |
| use_palette | bool | r |  |
| use_raw_data | bool | r/w |  |
| vertical_resolution | डबल | r/w |  |
| warp_settings | [WarpSettings](/psd/python-net/aspose.psd.fileformats.psd.layers.warp/warpsettings/) | r/w | यह संसाधन से सेट या प्राप्त किए गए Warp पैरामीटर को प्राप्त या सेट करता है (डिफ़ॉल्ट)। |
| width | int | r | ऑब्जेक्ट की चौड़ाई प्राप्त करता है। |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w |    |
## **Methods**
| **Name** | **विवरण** |
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
| [convert_to_linked(linked_path)](#convert_to_linked_linked_path_6) | इस एम्बेडेड स्मार्ट ऑब्जेक्ट को एक लिंक्ड स्मार्ट ऑब्जेक्ट में परिवर्तित करता है। |
| [create(image_options, width, height)](#create_image_options_width_height_7) |    |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| crop(rectangle) |  |
| dither(dithering_method, bits_count) |  |
| dither(dithering_method, bits_count, custom_palette) |  |
| draw_image(location, image) |  |
| [duplicate_layer()](#duplicate_layer__8) | इस एक को कॉपी करके एक नया स्मार्ट ऑब्जेक्ट लेयर बनाता है।<br/>            ध्यान दें कि एम्बेडेड स्मार्ट ऑब्जेक्ट्स के लिए एम्बेडेड इमेज साझा की जाती है।<br/>            यदि आप एम्बेडेड इमेज को कॉपी करना चाहते हैं तो [SmartObjectLayer.new_smart_object_via_copy()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) मेथड का उपयोग करें। |
| embed_linked() | इस लेयर में लिंक्ड स्मार्ट ऑब्जेक्ट को एम्बेड करता है। |
| [export_contents(file_path)](#export_contents_file_path_9) | एम्बेडेड या लिंक्ड सामग्री को फ़ाइल में एक्सपोर्ट करता है। |
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
| [load_contents(options)](#load_contents_options_32) | स्मार्ट ऑब्जेक्ट लेयर की एम्बेडेड या लिंक्ड इमेज सामग्री प्राप्त करता है। |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33) | 32-बिट ARGB पिक्सेल को आंशिक रूप से (ब्लॉकों द्वारा) लोड करता है। |
| load_partial_pixels(desired_rectangle, pixel_loader) |  |
| [load_pixels(rectangle)](#load_pixels_rectangle_34) |    |
| load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) |  |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_35) | कच्चा डेटा लोड करता है। |
| merge_layer_to(layer_to_merge_into) |  |
| [new_smart_object_via_copy()](#new_smart_object_via_copy__36) | इस लेयर की कॉपी करके एक नया स्मार्ट ऑब्जेक्ट लेयर बनाता है।<br/>            Adobe Photoshop की `Layer -> Smart Objects -> New Smart Object via Copy` कार्यक्षमता को पुनः उत्पन्न करता है।<br/>            ध्यान दें कि यह केवल एम्बेडेड स्मार्ट ऑब्जेक्ट्स के लिए सक्षम है क्योंकि एम्बेडेड इमेज भी कॉपी होती है।<br/>            यदि आप एम्बेडेड इमेज को साझा करना चाहते हैं तो [SmartObjectLayer.duplicate_layer()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) मेथड का उपयोग करें। |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_37) |    |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_38) |    |
| [relink_to_file(linked_path)](#relink_to_file_linked_path_39) | लिंक्ड स्मार्ट ऑब्जेक्ट को नई फ़ाइल से पुनः लिंक करता है।<br/>            बाद में UpdateModifiedContent मेथड को कॉल करने की आवश्यकता नहीं है। |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| [replace_contents(image)](#replace_contents_image_40) | स्मार्ट ऑब्जेक्ट लेयर में एम्बेडेड स्मार्ट ऑब्जेक्ट सामग्री को बदलता है। |
| [replace_contents(image, resolution)](#replace_contents_image_resolution_41) | स्मार्ट ऑब्जेक्ट लेयर में एम्बेडेड स्मार्ट ऑब्जेक्ट सामग्री को बदलता है। |
| [replace_contents(linked_path)](#replace_contents_linked_path_42) | सामग्री को फ़ाइल से बदलता है।<br/>            बाद में UpdateModifiedContent मेथड को कॉल करने की आवश्यकता नहीं है। |
| [replace_contents(linked_path, resolution)](#replace_contents_linked_path_resolution_43) | सामग्री को फ़ाइल से बदलता है।<br/>            बाद में UpdateModifiedContent मेथड को कॉल करने की आवश्यकता नहीं है। |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| resize(new_width, new_height) |  |
| resize(new_width, new_height, resize_type) |  |
| resize(new_width, new_height, settings) |  |
| resize_height_proportionally(new_height) |  |
| resize_height_proportionally(new_height, resize_type) |  |
| resize_height_proportionally(new_height, settings) |  |
| resize_width_proportionally(new_width) |  |
| resize_width_proportionally(new_width, resize_type) |  |
| resize_width_proportionally(new_width, settings) |  |
| rotate(angle) |  |
| rotate(angle, resize_proportionally, background_color) |  |
| rotate_flip(rotate_flip_type) |  |
| save() |  |
| save(file_path) |  |
| save(file_path, options) |  |
| save(file_path, options, bounds_rectangle) |  |
| save(file_path, over_write) |  |
| save(stream) |  |
| save(stream, options_base) |  |
| save(stream, options_base, bounds_rectangle) |  |
| save_argb_32_pixels(rectangle, pixels) |  |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| save_pixels(rectangle, pixels) |  |
| save_raw_data(data, data_offset, rectangle, raw_data_settings) |  |
| set_argb_32_pixel(x, y, argb_32_color) |  |
| set_palette(palette, update_colors) |  |
| set_pixel(x, y, color) |  |
| set_resolution(dpi_x, dpi_y) |  |
| [shallow_copy()](#shallow_copy__44) |    |
| [to_bitmap()](#to_bitmap__45) |    |
| update_modified_content() | स्मार्ट ऑब्जेक्ट लेयर इमेज कैश को संशोधित सामग्री के साथ अपडेट करता है। |
| write_argb_32_scan_line(scan_line_index, argb_32_pixels) |  |
| write_scan_line(scan_line_index, pixels) |  |


### Constructor: SmartObjectLayer(stream) {#SmartObjectLayer_stream_1}


```
 SmartObjectLayer(stream) 
```

नए [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) क्लास का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | आइटम्स की स्ट्रीम |

### Method: can_load(file_path)  [static] {#can_load_file_path_1}


```
 can_load(file_path) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool |  |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


```
 can_load(file_path, load_options) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool |  |


### Method: can_load(stream)  [static] {#can_load_stream_3}


```
 can_load(stream) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool |  |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


```
 can_load(stream, load_options) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool |  |


### Method: can_save(options) {#can_save_options_5}


```
 can_save(options) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool |  |


### Method: convert_to_linked(linked_path) {#convert_to_linked_linked_path_6}


```
 convert_to_linked(linked_path) 
```

इस एम्बेडेड स्मार्ट ऑब्जेक्ट को एक लिंक्ड स्मार्ट ऑब्जेक्ट में परिवर्तित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| linked_path | string | लिंक्ड पथ। |

### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_7}


```
 create(image_options, width, height) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |
| width | int |  |
| height | int |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: duplicate_layer() {#duplicate_layer__8}


```
 duplicate_layer() 
```

इस एक को कॉपी करके एक नया स्मार्ट ऑब्जेक्ट लेयर बनाता है।<br/>            ध्यान दें कि एम्बेडेड स्मार्ट ऑब्जेक्ट्स के लिए एम्बेडेड इमेज साझा की जाती है।<br/>            यदि आप एम्बेडेड इमेज को कॉपी करना चाहते हैं तो [SmartObjectLayer.new_smart_object_via_copy()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) मेथड का उपयोग करें।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | क्लोन किया गया [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) इंस्टेंस। |


### Method: export_contents(file_path) {#export_contents_file_path_9}


```
 export_contents(file_path) 
```

एम्बेडेड या लिंक्ड सामग्री को फ़ाइल में एक्सपोर्ट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | एक्सपोर्ट फ़ाइल पथ। |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_10}


```
 get_argb_32_pixel(x, y) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | int |  |
| y | int |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int |  |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_11}


```
 get_default_argb_32_pixels(rectangle) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int |  |


### Method: get_default_options(args) {#get_default_options_args_12}


```
 get_default_options(args) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| args | object |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |


### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_13}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| byte |  |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_14}


```
 get_file_format(file_path) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) |  |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_15}


```
 get_file_format(stream) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) |  |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_16}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| pixels | int |  |
| width | int |  |
| height | int |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_17}


```
 get_fitting_rectangle(rectangle, width, height) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |
| width | int |  |
| height | int |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_18}


```
 get_modify_date(use_default) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| use_default | bool |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| datetime |  |


### Method: get_original_options() {#get_original_options__19}


```
 get_original_options() 
```

  

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) |  |


### Method: get_pixel(x, y) {#get_pixel_x_y_20}


```
 get_pixel(x, y) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | int |  |
| y | int |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) |  |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_21}


```
 get_proportional_height(width, height, new_width) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| width | int |  |
| height | int |  |
| new_width | int |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int |  |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_22}


```
 get_proportional_width(width, height, new_height) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| width | int |  |
| height | int |  |
| new_height | int |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int |  |


### Method: get_skew_angle() {#get_skew_angle__23}


```
 get_skew_angle() 
```

  

**Returns**

| प्रकार | विवरण |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_24}


```
 load(file_path) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_25}


```
 load(file_path, load_options) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(stream)  [static] {#load_stream_26}


```
 load(stream) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_27}


```
 load(stream, load_options) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom |  |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) |  |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_28}


```
 load_argb_32_pixels(rectangle) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int |  |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_29}


```
 load_argb_64_pixels(rectangle) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| long |  |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_30}


```
 load_cmyk_32_pixels(rectangle) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int |  |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_31}


```
 load_cmyk_pixels(rectangle) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) |  |


### Method: load_contents(options) {#load_contents_options_32}


```
 load_contents(options) 
```

स्मार्ट ऑब्जेक्ट लेयर की एम्बेडेड या लिंक्ड इमेज सामग्री प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | लोड किया गया [Image](/psd/python-net/aspose.psd/image/) स्मार्ट ऑब्जेक्ट इंस्टेंस। |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

32-बिट ARGB पिक्सेल को आंशिक रूप से (ब्लॉकों द्वारा) लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | पिक्सेल लोड करने के लिए आयत। |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | आंशिक पिक्सेल लोडर। |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_34}


```
 load_pixels(rectangle) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) |  |


### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_35}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

कच्चा डेटा लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | कच्चा डेटा लोड करने के लिए आयत। |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | लोड किए गए डेटा के लिए उपयोग करने की कच्चा डेटा सेटिंग्स। नोट: यदि डेटा निर्दिष्ट प्रारूप में नहीं है तो डेटा रूपांतरण किया जाएगा। |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | कच्चा डेटा लोडर। |

### Method: new_smart_object_via_copy() {#new_smart_object_via_copy__36}


```
 new_smart_object_via_copy() 
```

इस लेयर की कॉपी करके एक नया स्मार्ट ऑब्जेक्ट लेयर बनाता है।<br/>            Adobe Photoshop की `Layer -> Smart Objects -> New Smart Object via Copy` कार्यक्षमता को पुनः उत्पन्न करता है।<br/>            ध्यान दें कि यह केवल एम्बेडेड स्मार्ट ऑब्जेक्ट्स के लिए सक्षम है क्योंकि एम्बेडेड इमेज भी कॉपी होती है।<br/>            यदि आप एम्बेडेड इमेज को साझा करना चाहते हैं तो [SmartObjectLayer.duplicate_layer()](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) मेथड का उपयोग करें।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | क्लोन किया गया [SmartObjectLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer/) इंस्टेंस। |


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_37}


```
 read_argb_32_scan_line(scan_line_index) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| scan_line_index | int |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int |  |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_38}


```
 read_scan_line(scan_line_index) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| scan_line_index | int |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) |  |


### Method: relink_to_file(linked_path) {#relink_to_file_linked_path_39}


```
 relink_to_file(linked_path) 
```

लिंक्ड स्मार्ट ऑब्जेक्ट को नई फ़ाइल से पुनः लिंक करता है।<br/>            बाद में UpdateModifiedContent मेथड को कॉल करने की आवश्यकता नहीं है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| linked_path | string | लिंक्ड पथ। |

### Method: replace_contents(image) {#replace_contents_image_40}


```
 replace_contents(image) 
```

स्मार्ट ऑब्जेक्ट लेयर में एम्बेडेड स्मार्ट ऑब्जेक्ट सामग्री को बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | छवि। |

### Method: replace_contents(image, resolution) {#replace_contents_image_resolution_41}


```
 replace_contents(image, resolution) 
```

स्मार्ट ऑब्जेक्ट लेयर में एम्बेडेड स्मार्ट ऑब्जेक्ट सामग्री को बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image | [Image](/psd/python-net/aspose.psd/image) | छवि। |
| resolution | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | रिज़ॉल्यूशन सेटिंग्स। यदि null है तो छवि का रिज़ॉल्यूशन उपयोग किया जाएगा। |

### Method: replace_contents(linked_path) {#replace_contents_linked_path_42}


```
 replace_contents(linked_path) 
```

सामग्री को फ़ाइल से बदलता है।<br/>            बाद में UpdateModifiedContent मेथड को कॉल करने की आवश्यकता नहीं है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| linked_path | string | लिंक्ड पथ। |

### Method: replace_contents(linked_path, resolution) {#replace_contents_linked_path_resolution_43}


```
 replace_contents(linked_path, resolution) 
```

सामग्री को फ़ाइल से बदलता है।<br/>            बाद में UpdateModifiedContent मेथड को कॉल करने की आवश्यकता नहीं है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| linked_path | string | लिंक्ड पथ। |
| resolution | [ResolutionSetting](/psd/python-net/aspose.psd/resolutionsetting) | रिज़ॉल्यूशन सेटिंग्स। यदि null है तो छवि का रिज़ॉल्यूशन उपयोग किया जाएगा। |

### Method: shallow_copy() {#shallow_copy__44}


```
 shallow_copy() 
```

  

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) |  |


### Method: to_bitmap() {#to_bitmap__45}


```
 to_bitmap() 
```

  

**Returns**

| प्रकार | विवरण |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


