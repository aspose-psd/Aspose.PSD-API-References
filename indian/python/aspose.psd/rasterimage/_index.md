---
title: "RasterImage क्लास"
type: docs
weight: 3740
url: /hi/python-net/aspose.psd/rasterimage/
---

**Summary:** Represents a raster image supporting raster graphics operations.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RasterImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, Image

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| स्वत:_समायोजित_पैलेट | bool | r/w | स्वचालित पैलेट समायोजन दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | पृष्ठभूमि रंग के लिए मान प्राप्त करता है या सेट करता है। |
| बिट्स_प्रति_पिक्सेल | int | r | प्रति पिक्सेल छवि बिट्स की गिनती प्राप्त करता है। |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | छवि की सीमाएँ प्राप्त करता है। |
| बफ़र_आकार_संकेत | int | r/w | बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार परिभाषित करता है। |
| container | [Image](/psd/python-net/aspose.psd/image) | r | प्राप्त करता है [Image](/psd/python-net/aspose.psd/image/) कंटेनर। |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | ऑब्जेक्ट का डेटा स्ट्रीम प्राप्त करता है। |
| disposed | bool | r | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | फ़ाइल फ़ॉर्मेट का मान प्राप्त करता है। |
| has_alpha | bool | r | यह संकेत करने वाला मान प्राप्त करता है कि इस इंस्टेंस में अल्फा है या नहीं। |
| has_background_color | bool | r/w | छवि में बैकग्राउंड रंग है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| has_transparent_color | bool | r/w | छवि में ट्रांसपेरेंट रंग है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| height | int | r | छवि की ऊँचाई प्राप्त करता है। |
| horizontal_resolution | double | r/w | इस [RasterImage](/psd/python-net/aspose.psd/rasterimage/) की क्षैतिज रिज़ॉल्यूशन, पिक्सेल प्रति इंच में, प्राप्त करता है या सेट करता है। |
| image_opacity | float | r | इस छवि की अपारदर्शिता प्राप्त करता है। |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | इंटरप्ट मॉनिटर प्राप्त करता है या सेट करता है। |
| is_cached | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि ऑब्जेक्ट का डेटा वर्तमान में कैश किया गया है और डेटा पढ़ने की आवश्यकता नहीं है। |
| is_raw_data_available | bool | r | कच्चा डेटा लोडिंग उपलब्ध है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | रंग पैलेट को प्राप्त करता है या सेट करता है। जब पिक्सेल सीधे दर्शाए जाते हैं तो रंग पैलेट का उपयोग नहीं किया जाता है। |
| premultiply_components | bool | r/w | एक मान को प्राप्त करता है या सेट करता है जो दर्शाता है कि क्या इमेज घटकों को प्री‑मल्टिप्लाइड होना चाहिए। |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | कस्टम कलर कनवर्टर को प्राप्त करता है या सेट करता है |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | कच्चे डेटा फ़ॉर्मेट को प्राप्त करता है। |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | वर्तमान कच्चा डेटा सेटिंग्स प्राप्त करता है। नोट: इन सेटिंग्स का उपयोग करने पर डेटा बिना रूपांतरण के लोड होता है। |
| raw_fallback_index | int | r/w | पैलेट इंडेक्स सीमा से बाहर होने पर उपयोग किए जाने वाले फ़ॉलबैक इंडेक्स को प्राप्त करता है या सेट करता है |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | इंडेक्स्ड कलर कनवर्टर को प्राप्त करता है या सेट करता है |
| raw_line_size | int | r | बाइट्स में कच्ची लाइन आकार को प्राप्त करता है। |
| size | [Size](/psd/python-net/aspose.psd/size) | r | छवि का आकार प्राप्त करता है। |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | इमेज का पारदर्शी रंग प्राप्त करता है। |
| update_xmp_data | bool | r/w | एक मान को प्राप्त करता है या सेट करता है जो दर्शाता है कि XMP मेटाडेटा को अपडेट किया जाए या नहीं। |
| use_palette | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि इमेज पैलेट उपयोग किया गया है या नहीं। |
| use_raw_data | bool | r/w | एक मान को प्राप्त करता है या सेट करता है जो दर्शाता है कि जब कच्चा डेटा लोडिंग उपलब्ध हो तो उसका उपयोग किया जाए या नहीं। |
| vertical_resolution | double | r/w | इस [RasterImage](/psd/python-net/aspose.psd/rasterimage/) की लंबवत रेज़ोल्यूशन, पिक्सेल प्रति इंच में, को प्राप्त करता है या सेट करता है। |
| width | int | r | इमेज की चौड़ाई प्राप्त करता है। |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP मेटाडेटा प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| adjust_brightness(brightness) |  |
| adjust_contrast(contrast) |  |
| adjust_gamma(gamma) |  |
| adjust_gamma(gamma_red, gamma_green, gamma_blue) |  |
| binarize_bradley(brightness_difference) |  |
| binarize_bradley(brightness_difference, window_size) |  |
| binarize_fixed(threshold) |  |
| binarize_otsu() |  |
| cache_data() | डेटा को कैश करता है और सुनिश्चित करता है कि अंतर्निहित [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) से कोई अतिरिक्त डेटा लोडिंग नहीं होगी। |
| [can_load(file_path)](#can_load_file_path_1) | निर्धारित करता है कि छवि निर्दिष्ट फ़ाइल पथ से लोड की जा सकती है या नहीं। |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | निर्धारित करता है कि छवि निर्दिष्ट फ़ाइल पथ से लोड की जा सकती है और वैकल्पिक रूप से निर्दिष्ट ओपन विकल्पों का उपयोग करके। |
| [can_load(stream)](#can_load_stream_3) | निर्धारित करता है कि छवि निर्दिष्ट स्ट्रीम से लोड की जा सकती है या नहीं। |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | निर्धारित करता है कि छवि निर्दिष्ट स्ट्रीम से लोड की जा सकती है और वैकल्पिक रूप से निर्दिष्ट <paramref name="loadOptions" /> का उपयोग करके। |
| [can_save(options)](#can_save_options_5) | निर्धारित करता है कि छवि को पास किए गए सहेज विकल्पों द्वारा प्रतिनिधित्व किए गए निर्दिष्ट फ़ाइल फ़ॉर्मेट में सहेजा जा सकता है या नहीं। |
| [create(image_options, width, height)](#create_image_options_width_height_6) | निर्दिष्ट निर्माण विकल्पों का उपयोग करके नई छवि बनाता है। |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| crop(rectangle) |  |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_7) | वर्तमान छवि पर डिथरिंग करता है। |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_8) | वर्तमान छवि पर डिथरिंग करता है। |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_9) | एक छवि का 32-बिट ARGB पिक्सेल प्राप्त करता है। |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_10) | डिफ़ॉल्ट 32-बिट ARGB पिक्सेल एरे प्राप्त करता है। |
| [get_default_options(args)](#get_default_options_args_11) | डिफ़ॉल्ट विकल्प प्राप्त करता है। |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_12) | आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट पिक्सेल एरे प्राप्त करता है। |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_13) | आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट रॉ डेटा एरे प्राप्त करता है। |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_14) | डिफ़ॉल्ट रॉ डेटा एरे प्राप्त करता है। |
| [get_file_format(file_path)](#get_file_format_file_path_15) | फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [get_file_format(stream)](#get_file_format_stream_16) | फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_17) | वर्तमान छवि के अनुरूप आयत प्राप्त करता है। |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_18) | वर्तमान छवि के अनुरूप आयत प्राप्त करता है। |
| [get_modify_date(use_default)](#get_modify_date_use_default_19) | संसाधन छवि के अंतिम संशोधित होने की तिथि और समय प्राप्त करता है। |
| [get_original_options()](#get_original_options__20) | मूल फ़ाइल सेटिंग्स के आधार पर विकल्प प्राप्त करता है।<br/>            यह मूल छवि की बिट-गहराई और अन्य पैरामीटरों को अपरिवर्तित रखने में मददगार हो सकता है।<br/>            उदाहरण के लिए, यदि हम 1 बिट प्रति पिक्सेल वाले काले-सफ़ेद PNG छवि को लोड करते हैं और फिर इसे<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) मेथड का उपयोग करके सहेजते हैं, तो आउटपुट PNG छवि 8-बिट प्रति पिक्सेल के साथ उत्पन्न होगी।<br/>            इसे रोकने और 1-बिट प्रति पिक्सेल के साथ PNG छवि सहेजने के लिए, इस मेथड का उपयोग करके संबंधित सहेजने के विकल्प प्राप्त करें और उन्हें<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) मेथड को दूसरे पैरामीटर के रूप में पास करें। |
| [get_pixel(x, y)](#get_pixel_x_y_21) | छवि पिक्सेल प्राप्त करता है।<br/>            प्रदर्शन चेतावनी: सभी छवि पिक्सेल पर इटरिट करने के लिए इस मेथड का उपयोग करने से बचें, क्योंकि इससे महत्वपूर्ण प्रदर्शन समस्याएँ हो सकती हैं।<br/>            अधिक कुशल पिक्सेल हेरफेर के लिए, पूरे पिक्सेल एरे को एक साथ प्राप्त करने हेतु `LoadArgb32Pixels` मेथड का उपयोग करें। |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_22) | अनुपाती ऊँचाई प्राप्त करता है। |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_23) | अनुपाती चौड़ाई प्राप्त करता है। |
| [get_skew_angle()](#get_skew_angle__24) |    |
| grayscale() |  |
| [load(file_path)](#load_file_path_25) | निर्दिष्ट फ़ाइल से नई छवि लोड करता है। |
| [load(file_path, load_options)](#load_file_path_load_options_26) | निर्दिष्ट फ़ाइल से नई छवि लोड करता है। |
| [load(stream)](#load_stream_27) | निर्दिष्ट स्ट्रीम से नई छवि लोड करता है। |
| [load(stream, load_options)](#load_stream_load_options_28) | निर्दिष्ट स्ट्रीम से नई छवि लोड करता है। |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_29) | 32-बिट ARGB पिक्सेल लोड करता है। |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_30) | 64-बिट ARGB पिक्सेल लोड करता है। |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_31) | CMYK प्रारूप में पिक्सेल लोड करता है। |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_32) | CMYK प्रारूप में पिक्सेल लोड करता है।<br/>            यह मेथड अप्रचलित है। कृपया अधिक प्रभावी [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) मेथड का उपयोग करें। |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33) | 32-बिट ARGB पिक्सेल को पैक्स द्वारा आंशिक रूप से लोड करता है। |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_34) | पैक्स द्वारा आंशिक रूप से पिक्सेल लोड करता है। |
| [load_pixels(rectangle)](#load_pixels_rectangle_35) | पिक्सेल लोड करता है। |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_36) | कच्चा डेटा लोड करता है। |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_37) | कच्चा डेटा लोड करता है। |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_38) | निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन पढ़ता है। |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_39) | निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन पढ़ता है। |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| [resize(new_width, new_height)](#resize_new_width_new_height_40) | छवि का आकार बदलता है। डिफ़ॉल्ट रूप से [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) उपयोग किया जाता है। |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_41) | छवि का आकार बदलता है। |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_42) | छवि का आकार बदलता है। |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_43) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_44) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_45) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_46) | चौड़ाई को अनुपातिक रूप से बदलता है। डिफ़ॉल्ट रूप से [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) उपयोग किया जाता है। |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_47) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_48) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| rotate(angle) |  |
| rotate(angle, resize_proportionally, background_color) |  |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_49) | छवि को घुमाता है, उलटता है, या घुमाकर उलटता है। |
| save() | छवि डेटा को अंतर्निहित स्ट्रीम में सहेजता है। |
| [save(file_path)](#save_file_path_50) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save(file_path, options)](#save_file_path_options_51) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_52) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save(file_path, over_write)](#save_file_path_over_write_53) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save(stream)](#save_stream_54) | ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम पर सहेजता है। |
| [save(stream, options_base)](#save_stream_options_base_55) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, इमेज का डेटा निर्दिष्ट स्ट्रीम पर सहेजता है। |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_56) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, इमेज का डेटा निर्दिष्ट स्ट्रीम पर सहेजता है। |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_57) | 32-बिट ARGB पिक्सेल सहेजता है। |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_58) | पिक्सेल को सहेजता है। |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_59) | कच्चा डेटा सहेजता है। |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_60) | निर्दिष्ट स्थिति के लिए इमेज का 32-बिट ARGB पिक्सेल सेट करता है। |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_61) | इमेज पैलेट सेट करता है। |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_62) | निर्दिष्ट स्थिति के लिए इमेज पिक्सेल सेट करता है। |
| set_resolution(dpi_x, dpi_y) |  |
| [to_bitmap()](#to_bitmap__63) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_64) | पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स पर लिखता है। |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_65) | पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स पर लिखता है। |


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


```
 can_load(file_path) 
```

निर्धारित करता है कि छवि निर्दिष्ट फ़ाइल पथ से लोड की जा सकती है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | फ़ाइल पथ। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <c>true</c> यदि छवि निर्दिष्ट फ़ाइल से लोड की जा सकती है; अन्यथा, <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


```
 can_load(file_path, load_options) 
```

निर्धारित करता है कि छवि निर्दिष्ट फ़ाइल पथ से लोड की जा सकती है और वैकल्पिक रूप से निर्दिष्ट ओपन विकल्पों का उपयोग करके।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | फ़ाइल पथ। |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | लोड विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <c>true</c> यदि छवि निर्दिष्ट फ़ाइल से लोड की जा सकती है; अन्यथा, <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_3}


```
 can_load(stream) 
```

निर्धारित करता है कि छवि निर्दिष्ट स्ट्रीम से लोड की जा सकती है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | जिस स्ट्रीम से लोड करना है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <c>true</c> यदि छवि निर्दिष्ट स्ट्रीम से लोड की जा सकती है; अन्यथा, <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


```
 can_load(stream, load_options) 
```

निर्धारित करता है कि छवि निर्दिष्ट स्ट्रीम से लोड की जा सकती है और वैकल्पिक रूप से निर्दिष्ट <paramref name="loadOptions" /> का उपयोग करके।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | जिस स्ट्रीम से लोड करना है। |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | लोड विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <c>true</c> यदि छवि निर्दिष्ट स्ट्रीम से लोड की जा सकती है; अन्यथा, <c>false</c>. |


### Method: can_save(options) {#can_save_options_5}


```
 can_save(options) 
```

निर्धारित करता है कि छवि को पास किए गए सहेज विकल्पों द्वारा प्रतिनिधित्व किए गए निर्दिष्ट फ़ाइल फ़ॉर्मेट में सहेजा जा सकता है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | उपयोग करने के लिए सहेजने विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <c>true</c> यदि छवि को पास किए गए सहेजने विकल्पों द्वारा दर्शाए गए निर्दिष्ट फ़ाइल फ़ॉर्मेट में सहेजा जा सकता है; अन्यथा, <c>false</c>. |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_6}


```
 create(image_options, width, height) 
```

निर्दिष्ट निर्माण विकल्पों का उपयोग करके नई छवि बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | छवि विकल्प। |
| width | int | चौड़ाई। |
| height | int | ऊँचाई। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | नया बनाया गया चित्र। |


### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_7}


```
 dither(dithering_method, bits_count) 
```

वर्तमान छवि पर डिथरिंग करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | डिथरिंग विधि। |
| bits_count | int | डिथरिंग के लिए अंतिम बिट्स गिनती। |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_8}


```
 dither(dithering_method, bits_count, custom_palette) 
```

वर्तमान छवि पर डिथरिंग करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | डिथरिंग विधि। |
| bits_count | int | डिथरिंग के लिए अंतिम बिट्स गिनती। |
| custom_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | डिथरिंग के लिए कस्टम पैलेट। |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_9}


```
 get_argb_32_pixel(x, y) 
```

एक छवि का 32-बिट ARGB पिक्सेल प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | int | पिक्सेल X स्थान। |
| y | int | पिक्सेल Y स्थान। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | निर्दिष्ट स्थान के लिए 32-बिट ARGB पिक्सेल। |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_10}


```
 get_default_argb_32_pixels(rectangle) 
```

डिफ़ॉल्ट 32-बिट ARGB पिक्सेल एरे प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | पिक्सेल प्राप्त करने के लिए आयत। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | डिफ़ॉल्ट पिक्सेल एरे। |


### Method: get_default_options(args) {#get_default_options_args_11}


```
 get_default_options(args) 
```

डिफ़ॉल्ट विकल्प प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| args | object | आर्ग्युमेंट्स। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | डिफ़ॉल्ट विकल्प |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_12}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट पिक्सेल एरे प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | पिक्सेल प्राप्त करने के लिए आयत। |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | आंशिक पिक्सेल लोडर। |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_13}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट रॉ डेटा एरे प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | पिक्सेल प्राप्त करने के लिए आयत। |
| partial_raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | आंशिक कच्चा डेटा लोडर। |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | कच्चा डेटा सेटिंग्स। |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_14}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

डिफ़ॉल्ट रॉ डेटा एरे प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | कच्चा डेटा प्राप्त करने के लिए आयत। |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | कच्चा डेटा सेटिंग्स। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| byte | डिफ़ॉल्ट कच्चा डेटा एरे। |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_15}


```
 get_file_format(file_path) 
```

फ़ाइल फ़ॉर्मेट प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | फ़ाइल पथ। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | निर्धारित फ़ाइल फ़ॉर्मेट। |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_16}


```
 get_file_format(stream) 
```

फ़ाइल फ़ॉर्मेट प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | स्ट्रीम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | निर्धारित फ़ाइल फ़ॉर्मेट। |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_17}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

वर्तमान छवि के अनुरूप आयत प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | फ़िटिंग आयत प्राप्त करने के लिए आयत। |
| pixels | int | 32-बिट ARGB पिक्सेल। |
| width | int | ऑब्जेक्ट की चौड़ाई। |
| height | int | ऑब्जेक्ट की ऊँचाई। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | फ़िटिंग आयत या अपवाद यदि कोई फ़िटिंग आयत नहीं मिलती। |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_18}


```
 get_fitting_rectangle(rectangle, width, height) 
```

वर्तमान छवि के अनुरूप आयत प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | फ़िटिंग आयत प्राप्त करने के लिए आयत। |
| width | int | ऑब्जेक्ट की चौड़ाई। |
| height | int | ऑब्जेक्ट की ऊँचाई। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | फ़िटिंग आयत या अपवाद यदि कोई फ़िटिंग आयत नहीं मिलती। |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_19}


```
 get_modify_date(use_default) 
```

संसाधन छवि के अंतिम संशोधित होने की तिथि और समय प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| use_default | bool | यदि <c>true</c> पर सेट किया गया है तो FileInfo से जानकारी को डिफ़ॉल्ट मान के रूप में उपयोग करता है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| datetime | संसाधन छवि के अंतिम संशोधित होने की तिथि और समय। |


### Method: get_original_options() {#get_original_options__20}


```
 get_original_options() 
```

मूल फ़ाइल सेटिंग्स के आधार पर विकल्प प्राप्त करता है।<br/>            यह मूल छवि की बिट-गहराई और अन्य पैरामीटरों को अपरिवर्तित रखने में मददगार हो सकता है।<br/>            उदाहरण के लिए, यदि हम 1 बिट प्रति पिक्सेल वाले काले-सफ़ेद PNG छवि को लोड करते हैं और फिर इसे<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) मेथड का उपयोग करके सहेजते हैं, तो आउटपुट PNG छवि 8-बिट प्रति पिक्सेल के साथ उत्पन्न होगी।<br/>            इसे रोकने और 1-बिट प्रति पिक्सेल के साथ PNG छवि सहेजने के लिए, इस मेथड का उपयोग करके संबंधित सहेजने के विकल्प प्राप्त करें और उन्हें<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) मेथड को दूसरे पैरामीटर के रूप में पास करें।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | मूल फ़ाइल सेटिंग्स के आधार पर विकल्प। |


### Method: get_pixel(x, y) {#get_pixel_x_y_21}


```
 get_pixel(x, y) 
```

छवि पिक्सेल प्राप्त करता है।<br/>            प्रदर्शन चेतावनी: सभी छवि पिक्सेल पर इटरिट करने के लिए इस मेथड का उपयोग करने से बचें, क्योंकि इससे महत्वपूर्ण प्रदर्शन समस्याएँ हो सकती हैं।<br/>            अधिक कुशल पिक्सेल हेरफेर के लिए, पूरे पिक्सेल एरे को एक साथ प्राप्त करने हेतु `LoadArgb32Pixels` मेथड का उपयोग करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | int | पिक्सेल X स्थान। |
| y | int | पिक्सेल Y स्थान। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | निर्दिष्ट स्थान के लिए पिक्सेल रंग। |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_22}


```
 get_proportional_height(width, height, new_width) 
```

अनुपाती ऊँचाई प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| width | int | चौड़ाई। |
| height | int | ऊँचाई। |
| new_width | int | नई चौड़ाई। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | अनुपातिक ऊँचाई। |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_23}


```
 get_proportional_width(width, height, new_height) 
```

अनुपाती चौड़ाई प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| width | int | चौड़ाई। |
| height | int | ऊँचाई। |
| new_height | int | नई ऊँचाई। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | अनुपातिक चौड़ाई। |


### Method: get_skew_angle() {#get_skew_angle__24}


```
 get_skew_angle() 
```

  

**Returns**

| प्रकार | विवरण |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_25}


```
 load(file_path) 
```

निर्दिष्ट फ़ाइल से नई छवि लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | छवि लोड करने के लिए फ़ाइल पथ। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | लोड की गई छवि। |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_26}


```
 load(file_path, load_options) 
```

निर्दिष्ट फ़ाइल से नई छवि लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | छवि लोड करने के लिए फ़ाइल पथ। |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | लोड विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | लोड की गई छवि। |


### Method: load(stream)  [static] {#load_stream_27}


```
 load(stream) 
```

निर्दिष्ट स्ट्रीम से नई छवि लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | छवि लोड करने के लिए स्ट्रीम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | लोड की गई छवि। |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_28}


```
 load(stream, load_options) 
```

निर्दिष्ट स्ट्रीम से नई छवि लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | छवि लोड करने के लिए स्ट्रीम। |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | लोड विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | लोड की गई छवि। |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_29}


```
 load_argb_32_pixels(rectangle) 
```

32-बिट ARGB पिक्सेल लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | पिक्सेल लोड करने के लिए आयत। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | लोड किया गया 32-बिट ARGB पिक्सेल एरे। |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_30}


```
 load_argb_64_pixels(rectangle) 
```

64-बिट ARGB पिक्सेल लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | पिक्सेल लोड करने के लिए आयत। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| long | लोड किया गया 64-बिट ARGB पिक्सेल एरे। |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_31}


```
 load_cmyk_32_pixels(rectangle) 
```

CMYK प्रारूप में पिक्सेल लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | पिक्सेल लोड करने के लिए आयत। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | लोड किए गए CMYK पिक्सेल 32-बिट पूर्णांक मानों के रूप में प्रस्तुत। |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_32}


```
 load_cmyk_pixels(rectangle) 
```

CMYK प्रारूप में पिक्सेल लोड करता है।<br/>            यह मेथड अप्रचलित है। कृपया अधिक प्रभावी [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) मेथड का उपयोग करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | पिक्सेल लोड करने के लिए आयत। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | लोड किया गया CMYK पिक्सेल एरे। |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_33}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

32-बिट ARGB पिक्सेल को पैक्स द्वारा आंशिक रूप से लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | वांछित आयत। |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | 32-बिट ARGB पिक्सेल लोडर। |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_34}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

पैक्स द्वारा आंशिक रूप से पिक्सेल लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | वांछित आयत। |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | पिक्सेल लोडर। |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_35}


```
 load_pixels(rectangle) 
```

पिक्सेल लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | पिक्सेल लोड करने के लिए आयत। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | लोड किया गया पिक्सेल एरे। |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_36}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

कच्चा डेटा लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | कच्चा डेटा लोड करने के लिए आयत। |
| dest_image_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | गंतव्य छवि की सीमाएँ। |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | लोड किए गए डेटा के लिए उपयोग करने की कच्चा डेटा सेटिंग्स। नोट: यदि डेटा निर्दिष्ट प्रारूप में नहीं है तो डेटा रूपांतरण किया जाएगा। |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | कच्चा डेटा लोडर। |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_37}


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

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_38}


```
 read_argb_32_scan_line(scan_line_index) 
```

निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| scan_line_index | int | स्कैन लाइन का शून्य-आधारित सूचकांक। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| int | स्कैन लाइन 32-बिट ARGB रंग मानों का एरे। |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_39}


```
 read_scan_line(scan_line_index) 
```

निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन पढ़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| scan_line_index | int | स्कैन लाइन का शून्य-आधारित सूचकांक। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | स्कैन लाइन पिक्सेल रंग मानों का एरे। |


### Method: resize(new_width, new_height) {#resize_new_width_new_height_40}


```
 resize(new_width, new_height) 
```

छवि का आकार बदलता है। डिफ़ॉल्ट रूप से [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) उपयोग किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_width | int | नई चौड़ाई। |
| new_height | int | नई ऊँचाई। |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_41}


```
 resize(new_width, new_height, resize_type) 
```

छवि का आकार बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_width | int | नई चौड़ाई। |
| new_height | int | नई ऊँचाई। |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | रिसाइज़ प्रकार। |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_42}


```
 resize(new_width, new_height, settings) 
```

छवि का आकार बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_width | int | नई चौड़ाई। |
| new_height | int | नई ऊँचाई। |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | रिसाइज़ सेटिंग्स। |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_43}


```
 resize_height_proportionally(new_height) 
```

ऊँचाई को अनुपातिक रूप से बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_height | int | नई ऊँचाई। |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_44}


```
 resize_height_proportionally(new_height, resize_type) 
```

ऊँचाई को अनुपातिक रूप से बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_height | int | नई ऊँचाई। |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | रिसाइज़ का प्रकार। |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_45}


```
 resize_height_proportionally(new_height, settings) 
```

ऊँचाई को अनुपातिक रूप से बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_height | int | नई ऊँचाई। |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | छवि रिसाइज़ सेटिंग्स। |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_46}


```
 resize_width_proportionally(new_width) 
```

चौड़ाई को अनुपातिक रूप से बदलता है। डिफ़ॉल्ट रूप से [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) उपयोग किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_width | int | नई चौड़ाई। |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_47}


```
 resize_width_proportionally(new_width, resize_type) 
```

चौड़ाई को अनुपातिक रूप से बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_width | int | नई चौड़ाई। |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | रिसाइज़ का प्रकार। |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_48}


```
 resize_width_proportionally(new_width, settings) 
```

चौड़ाई को अनुपातिक रूप से बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_width | int | नई चौड़ाई। |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | छवि रिसाइज़ सेटिंग्स। |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_49}


```
 rotate_flip(rotate_flip_type) 
```

छवि को घुमाता है, उलटता है, या घुमाकर उलटता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | रोटेट फ़्लिप का प्रकार। |

### Method: save(file_path) {#save_file_path_50}


```
 save(file_path) 
```

ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | ऑब्जेक्ट के डेटा को सहेजने के लिए फ़ाइल पथ। |

### Method: save(file_path, options) {#save_file_path_options_51}


```
 save(file_path, options) 
```

सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | फ़ाइल पथ। |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | विकल्प। |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_52}


```
 save(file_path, options, bounds_rectangle) 
```

सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | फ़ाइल पथ। |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | विकल्प। |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | गंतव्य छवि सीमाएँ आयत। स्रोत सीमाओं के उपयोग के लिए खाली आयत सेट करें। |

### Method: save(file_path, over_write) {#save_file_path_over_write_53}


```
 save(file_path, over_write) 
```

ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | ऑब्जेक्ट के डेटा को सहेजने के लिए फ़ाइल पथ। |
| over_write | bool | यदि <c>true</c> पर सेट किया गया है तो फ़ाइल सामग्री को ओवरराइट करें, अन्यथा जोड़ दिया जाएगा। |

### Method: save(stream) {#save_stream_54}


```
 save(stream) 
```

ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | ऑब्जेक्ट के डेटा को सहेजने के लिए स्ट्रीम। |

### Method: save(stream, options_base) {#save_stream_options_base_55}


```
 save(stream, options_base) 
```

सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, इमेज का डेटा निर्दिष्ट स्ट्रीम पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | छवि के डेटा को सहेजने के लिए स्ट्रीम। |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | सहेजने के विकल्प। |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_56}


```
 save(stream, options_base, bounds_rectangle) 
```

सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, इमेज का डेटा निर्दिष्ट स्ट्रीम पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | छवि के डेटा को सहेजने के लिए स्ट्रीम। |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | सहेजने के विकल्प। |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | गंतव्य छवि सीमाओं का आयत। स्रोत सीमाओं के उपयोग के लिए खाली आयत सेट करें। |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_57}


```
 save_argb_32_pixels(rectangle, pixels) 
```

32-बिट ARGB पिक्सेल सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | पिक्सेल सहेजने के लिए आयत। |
| pixels | int | 32-बिट ARGB पिक्सेल एरे। |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_58}


```
 save_pixels(rectangle, pixels) 
```

पिक्सेल को सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | पिक्सेल सहेजने के लिए आयत। |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | पिक्सेल एरे। |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_59}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

कच्चा डेटा सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| data | byte | कच्चा डेटा। |
| data_offset | int | प्रारंभिक कच्चा डेटा ऑफ़सेट। |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | कच्चा डेटा आयत। |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | डेटा जिस कच्चे डेटा सेटिंग्स में है। |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_60}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

निर्दिष्ट स्थिति के लिए इमेज का 32-बिट ARGB पिक्सेल सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | int | पिक्सेल X स्थान। |
| y | int | पिक्सेल Y स्थान। |
| argb_32_color | int | निर्दिष्ट स्थिति के लिए 32-बिट ARGB पिक्सेल। |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_61}


```
 set_palette(palette, update_colors) 
```

इमेज पैलेट सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | सेट करने के लिए पैलेट। |
| update_colors | bool | यदि इसे <c>true</c> पर सेट किया जाता है तो रंग नई पैलेट के अनुसार अपडेट हो जाएंगे; अन्यथा रंग अनुक्रमांक अपरिवर्तित रहेंगे। ध्यान दें कि अपरिवर्तित अनुक्रमांक छवि को लोड करने पर क्रैश कर सकते हैं यदि कुछ अनुक्रमांक के लिए कोई संबंधित पैलेट प्रविष्टि नहीं है। |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_62}


```
 set_pixel(x, y, color) 
```

निर्दिष्ट स्थिति के लिए इमेज पिक्सेल सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | int | पिक्सेल X स्थान। |
| y | int | पिक्सेल Y स्थान। |
| color | [Color](/psd/python-net/aspose.psd/color) | निर्दिष्ट स्थिति के लिए पिक्सेल रंग। |

### Method: to_bitmap() {#to_bitmap__63}


```
 to_bitmap() 
```

  

**Returns**

| प्रकार | विवरण |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_64}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स पर लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| scan_line_index | int | स्कैन लाइन का शून्य-आधारित सूचकांक। |
| argb_32_pixels | int | लिखने के लिए 32-बिट ARGB रंगों की एरे। |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_65}


```
 write_scan_line(scan_line_index, pixels) 
```

पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स पर लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| scan_line_index | int | स्कैन लाइन का शून्य-आधारित सूचकांक। |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | लिखने के लिए पिक्सेल रंगों की एरे। |

