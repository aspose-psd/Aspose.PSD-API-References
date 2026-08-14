---
title: "Layer क्लास"
type: docs
weight: 930
url: /hi/python-net/aspose.psd.fileformats.psd.layers/layer/
---

**Summary:** The psd layer.

**Module:** [aspose.psd.fileformats.psd.layers](/psd/python-net/aspose.psd.fileformats.psd.layers/)

**Full Name:** aspose.psd.fileformats.psd.layers.Layer

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [Layer()](#Layer__1) | नए [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) क्लास का उदाहरण आरंभ करता है। लेज़ी इनिशियलाइज़ेशन के लिए कंस्ट्रक्टर। |
| [Layer(bounds, red_bytes, green_bytes, blue_bytes, name)](#Layer_bounds_red_bytes_green_bytes_blue_bytes_name_2) | बाइट एरेज़ से [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) क्लास का नया उदाहरण आरंभ करता है। |
| [Layer(image, dispose_image)](#Layer_image_dispose_image_3) | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) क्लास का नया उदाहरण आरंभ करता है। |
| [Layer(stream)](#Layer_stream_4) | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) क्लास का नया उदाहरण आरंभ करता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| BLEND_SIGNATURE [स्थैतिक] | int | r | ब्लेंड मोड सिग्नेचर को दर्शाता है। |
| LAYER_HEADER_SIZE [स्थैतिक] | int | r | लेयर हेडर का आकार। |
| स्वत:_समायोजित_पैलेट | bool | r/w | स्वचालित पैलेट समायोजन दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | पृष्ठभूमि रंग के लिए मान प्राप्त करता है या सेट करता है। |
| बिट्स_प्रति_पिक्सेल | int | r | प्रति पिक्सेल छवि बिट्स की गिनती प्राप्त करता है। |
| ब्लेंड_क्लिप्ड_एलिमेंट्स | bool | r/w | क्लिप्ड तत्व के ब्लेंडिंग को प्राप्त करता है या सेट करता है। |
| blend_mode_key | [BlendMode](/psd/python-net/aspose.psd.fileformats.core.blending/blendmode/) | r/w | ब्लेंड मोड कुंजी को प्राप्त करता है या सेट करता है। |
| ब्लेंड_मोड_सिग्नेचर | int | r | ब्लेंड मोड सिग्नेचर प्राप्त करता है। |
| blending_options | [BlendingOptions](/psd/python-net/aspose.psd.fileformats.psd.layers.layereffects/blendingoptions/) | r | ब्लेंडिंग विकल्प प्राप्त करता है। |
| नीचे | int | r/w | निचले लेयर की स्थिति प्राप्त करता है या सेट करता है। |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| बफ़र_आकार_संकेत | int | r/w | बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार परिभाषित करता है। |
| channel_information | [ChannelInformation[]](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation) | r/w | चैनल जानकारी प्राप्त करता है या सेट करता है। |
| चैनल्स_गणना | ushort | r | लेयर के चैनलों की गिनती प्राप्त करता है। |
| क्लिपिंग | byte | r/w | लेयर क्लिपिंग प्राप्त करता है या सेट करता है। 0 = बेस, 1 = नॉन-बेस। |
| container | [Image](/psd/python-net/aspose.psd/image) | r | प्राप्त करता है [Image](/psd/python-net/aspose.psd/image/) कंटेनर। |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | ऑब्जेक्ट का डेटा स्ट्रीम प्राप्त करता है। |
| प्रदर्शित_नाम | string | r/w | लेयर का डिस्प्ले नाम प्राप्त करता है या सेट करता है। |
| disposed | bool | r | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| extra_length | int | r | लेयर की अतिरिक्त जानकारी की लंबाई बाइट्स में प्राप्त करता है। |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | फ़ाइल फ़ॉर्मेट का मान प्राप्त करता है। |
| fill_opacity | int | r/w | फ़िल अपारदर्शिता प्राप्त करता है या सेट करता है। |
| filler | byte | r/w | लेयर फ़िलर प्राप्त करता है या सेट करता है। |
| flags | [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags) | r/w | लेयर फ़्लैग्स प्राप्त करता है।<br/>            बिट 0 = ट्रांसपेरेंसी संरक्षित;<br/>            बिट 1 = दृश्यमान;<br/>            बिट 2 = अप्रचलित;<br/>            बिट 3 = Photoshop 5.0 और बाद के लिए 1, बताता है कि बिट 4 में उपयोगी जानकारी है या नहीं;<br/>            बिट 4 = पिक्सेल डेटा दस्तावेज़ की उपस्थिति से असंबंधित। |
| has_alpha | bool | r | यह संकेत करने वाला मान प्राप्त करता है कि इस इंस्टेंस में अल्फा है या नहीं। |
| has_background_color | bool | r/w | छवि में बैकग्राउंड रंग है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| has_transparent_color | bool | r/w | छवि में ट्रांसपेरेंट रंग है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| height | int | r | छवि की ऊँचाई प्राप्त करता है। |
| horizontal_resolution | double | r/w | इस [RasterImage](/psd/python-net/aspose.psd/rasterimage/) की क्षैतिज रिज़ॉल्यूशन, पिक्सेल प्रति इंच में, प्राप्त करता है या सेट करता है। |
| image_opacity | float | r | इस छवि की अपारदर्शिता प्राप्त करता है। |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | इंटरप्ट मॉनिटर प्राप्त करता है या सेट करता है। |
| is_cached | bool | r | यह संकेत करने वाला मान प्राप्त करता है कि छवि डेटा वर्तमान में कैश किया गया है या नहीं। |
| is_raw_data_available | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि कच्चा डेटा लोडिंग समर्थित है या नहीं। |
| is_visible | bool | r/w | लेयर दृश्यमान है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| is_visible_in_group | bool | r | यह संकेत करने वाला मान प्राप्त करता है कि यह इंस्टेंस समूह में दृश्यमान है या नहीं (यदि लेयर समूह में नहीं है तो इसका मतलब रूट समूह है)। |
| layer_blending_ranges_data | [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata) | r/w | लेयर ब्लेंडिंग रेंज डेटा प्राप्त करता है या सेट करता है। |
| layer_creation_date_time | datetime | r/w | लेयर निर्माण तिथि और समय को प्राप्त करता है या सेट करता है। |
| layer_lock | [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | r/w | Gets or sets the layer lock.<br/>            Note that if flag LayerFlags.TransparencyProtected is set it will be overwritten by layer lock flag.<br/>            To return LayerFlags.TransparencyProtected flag need to apply for layer option layer.Flags | = LayerFlags.TransparencyProtected |
| layer_mask_data | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | r/w | लेयर मास्क डेटा को प्राप्त करता है या सेट करता है। |
| layer_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | r | लेयर विकल्पों को प्राप्त करता है। |
| left | int | r/w | बाएँ लेयर की स्थिति को प्राप्त करता है या सेट करता है। |
| लंबाई | int | r | बाइट्स में कुल लेयर लंबाई को प्राप्त करता है। |
| name | string | r/w | लेयर नाम को प्राप्त करता है या सेट करता है। |
| opacity | byte | r/w | लेयर अपारदर्शिता को प्राप्त करता है या सेट करता है। 0 = पारदर्शी, 255 = अपारदर्शी। |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | रंग पैलेट को प्राप्त करता है या सेट करता है। जब पिक्सेल सीधे दर्शाए जाते हैं तो रंग पैलेट का उपयोग नहीं किया जाता है। |
| premultiply_components | bool | r/w | एक मान को प्राप्त करता है या सेट करता है जो दर्शाता है कि क्या इमेज घटकों को प्री‑मल्टिप्लाइड होना चाहिए। |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | कस्टम कलर कनवर्टर को प्राप्त करता है या सेट करता है |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | कच्चे डेटा फ़ॉर्मेट को प्राप्त करता है। |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | वर्तमान कच्चा डेटा सेटिंग्स प्राप्त करता है। नोट: इन सेटिंग्स का उपयोग करने पर डेटा बिना रूपांतरण के लोड होता है। |
| raw_fallback_index | int | r/w | पैलेट इंडेक्स सीमा से बाहर होने पर उपयोग किए जाने वाले फ़ॉलबैक इंडेक्स को प्राप्त करता है या सेट करता है |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | इंडेक्स्ड कलर कनवर्टर को प्राप्त करता है या सेट करता है |
| raw_line_size | int | r | बाइट्स में कच्ची लाइन आकार को प्राप्त करता है। |
| resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource) | r/w | लेयर संसाधनों को प्राप्त करता है या सेट करता है। |
| right | int | r/w | दाएँ लेयर की स्थिति को प्राप्त करता है या सेट करता है। |
| sheet_color_highlight | [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | r/w | लेयर्स की सूची में सजावटी शीट रंग हाइलाइट को प्राप्त करता है या सेट करता है |
| size | [Size](/psd/python-net/aspose.psd/size) | r | ऑब्जेक्ट का आकार प्राप्त करता है। |
| ऊपर | int | r/w | ऊपर लेयर की स्थिति को प्राप्त करता है या सेट करता है। |
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
| [add_layer_mask(layer_mask)](#add_layer_mask_layer_mask_1) | वर्तमान लेयर में मास्क जोड़ता है। |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_2) | छवि की चमक को समायोजित करता है। |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_3) | छवि कंट्रास्टिंग |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_4) | छवि का गामा-सुधार। |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_5) | छवि का गामा-सुधार। |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_6) | ब्रैडली के अनुकूली थ्रेशहोल्डिंग एल्गोरिद्म का उपयोग करके इंटीग्रल इमेज थ्रेशहोल्डिंग के साथ छवि का बाइनरीकरण |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_7) | ब्रैडली के अनुकूली थ्रेशहोल्डिंग एल्गोरिद्म का उपयोग करके इंटीग्रल इमेज थ्रेशहोल्डिंग के साथ छवि का बाइनरीकरण |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_8) | पूर्वनिर्धारित थ्रेशहोल्ड के साथ छवि का बाइनरीकरण |
| binarize_otsu() | ओट्सु थ्रेशहोल्डिंग के साथ छवि का बाइनरीकरण |
| cache_data() | डेटा को कैश करता है और सुनिश्चित करता है कि अंतर्निहित [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) से कोई अतिरिक्त डेटा लोडिंग नहीं होगी। |
| [can_load(file_path)](#can_load_file_path_9) | निर्धारित करता है कि छवि निर्दिष्ट फ़ाइल पथ से लोड की जा सकती है या नहीं। |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_10) | निर्धारित करता है कि छवि निर्दिष्ट फ़ाइल पथ से लोड की जा सकती है और वैकल्पिक रूप से निर्दिष्ट ओपन विकल्पों का उपयोग करके। |
| [can_load(stream)](#can_load_stream_11) | निर्धारित करता है कि छवि निर्दिष्ट स्ट्रीम से लोड की जा सकती है या नहीं। |
| [can_load(stream, load_options)](#can_load_stream_load_options_12) | निर्धारित करता है कि छवि निर्दिष्ट स्ट्रीम से लोड की जा सकती है और वैकल्पिक रूप से निर्दिष्ट <paramref name="loadOptions" /> का उपयोग करके। |
| [can_save(options)](#can_save_options_13) | निर्धारित करता है कि छवि को पास किए गए सहेज विकल्पों द्वारा प्रतिनिधित्व किए गए निर्दिष्ट फ़ाइल फ़ॉर्मेट में सहेजा जा सकता है या नहीं। |
| [create(image_options, width, height)](#create_image_options_width_height_14) | निर्दिष्ट निर्माण विकल्पों का उपयोग करके नई छवि बनाता है। |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_15) | छवि को क्रॉप करना। |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_16) | वर्तमान छवि पर डिथरिंग करता है। |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_17) | वर्तमान छवि पर डिथरिंग करता है। |
| [draw_image(location, image)](#draw_image_location_image_18) | लेयर पर छवि को ड्रॉ करता है। |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_19) | एक छवि का 32-बिट ARGB पिक्सेल प्राप्त करता है। |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_20) | डिफ़ॉल्ट 32-बिट ARGB पिक्सेल एरे प्राप्त करता है। |
| [get_default_options(args)](#get_default_options_args_21) | डिफ़ॉल्ट विकल्प प्राप्त करता है। |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_22) | आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट पिक्सेल एरे प्राप्त करता है। |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_23) | आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट रॉ डेटा एरे प्राप्त करता है। |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_24) | डिफ़ॉल्ट रॉ डेटा एरे प्राप्त करता है। |
| [get_file_format(file_path)](#get_file_format_file_path_25) | फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [get_file_format(stream)](#get_file_format_stream_26) | फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_27) | वर्तमान छवि के अनुरूप आयत प्राप्त करता है। |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_28) | वर्तमान छवि के अनुरूप आयत प्राप्त करता है। |
| [get_modify_date(use_default)](#get_modify_date_use_default_29) | संसाधन छवि के अंतिम संशोधित होने की तिथि और समय प्राप्त करता है। |
| [get_original_options()](#get_original_options__30) | मूल फ़ाइल सेटिंग्स के आधार पर विकल्प प्राप्त करता है।<br/>            यह मूल छवि की बिट-गहराई और अन्य पैरामीटरों को अपरिवर्तित रखने में मददगार हो सकता है।<br/>            उदाहरण के लिए, यदि हम 1 बिट प्रति पिक्सेल वाले काले-सफ़ेद PNG छवि को लोड करते हैं और फिर इसे<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) मेथड का उपयोग करके सहेजते हैं, तो आउटपुट PNG छवि 8-बिट प्रति पिक्सेल के साथ उत्पन्न होगी।<br/>            इसे रोकने और 1-बिट प्रति पिक्सेल के साथ PNG छवि सहेजने के लिए, इस मेथड का उपयोग करके संबंधित सहेजने के विकल्प प्राप्त करें और उन्हें<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) मेथड को दूसरे पैरामीटर के रूप में पास करें। |
| [get_pixel(x, y)](#get_pixel_x_y_31) | छवि पिक्सेल प्राप्त करता है।<br/>            प्रदर्शन चेतावनी: सभी छवि पिक्सेल पर इटरिट करने के लिए इस मेथड का उपयोग करने से बचें, क्योंकि इससे महत्वपूर्ण प्रदर्शन समस्याएँ हो सकती हैं।<br/>            अधिक कुशल पिक्सेल हेरफेर के लिए, पूरे पिक्सेल एरे को एक साथ प्राप्त करने हेतु `LoadArgb32Pixels` मेथड का उपयोग करें। |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_32) | अनुपाती ऊँचाई प्राप्त करता है। |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_33) | अनुपाती चौड़ाई प्राप्त करता है। |
| [get_skew_angle()](#get_skew_angle__34) |    |
| grayscale() | छवि को उसके ग्रेस्केल प्रतिनिधित्व में रूपांतरित करना |
| [load(file_path)](#load_file_path_35) | निर्दिष्ट फ़ाइल से नई छवि लोड करता है। |
| [load(file_path, load_options)](#load_file_path_load_options_36) | निर्दिष्ट फ़ाइल से नई छवि लोड करता है। |
| [load(stream)](#load_stream_37) | निर्दिष्ट स्ट्रीम से नई छवि लोड करता है। |
| [load(stream, load_options)](#load_stream_load_options_38) | निर्दिष्ट स्ट्रीम से नई छवि लोड करता है। |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_39) | 32-बिट ARGB पिक्सेल लोड करता है। |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_40) | 64-बिट ARGB पिक्सेल लोड करता है। |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_41) | CMYK प्रारूप में पिक्सेल लोड करता है। |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_42) | CMYK प्रारूप में पिक्सेल लोड करता है।<br/>            यह मेथड अप्रचलित है। कृपया अधिक प्रभावी [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) मेथड का उपयोग करें। |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_43) | 32-बिट ARGB पिक्सेल को आंशिक रूप से (ब्लॉकों द्वारा) लोड करता है। |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_44) | पैक्स द्वारा आंशिक रूप से पिक्सेल लोड करता है। |
| [load_pixels(rectangle)](#load_pixels_rectangle_45) | पिक्सेल लोड करता है। |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_46) | कच्चा डेटा लोड करता है। |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_47) | कच्चा डेटा लोड करता है। |
| [merge_layer_to(layer_to_merge_into)](#merge_layer_to_layer_to_merge_into_48) | लेयर को निर्दिष्ट लेयर में मिलाता है |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_49) | निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन पढ़ता है। |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_50) | निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन पढ़ता है। |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| [resize(new_width, new_height)](#resize_new_width_new_height_51) | छवि का आकार बदलता है। डिफ़ॉल्ट रूप से [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) उपयोग किया जाता है। |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_52) | छवि का आकार बदलता है। |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_53) | छवि का आकार बदलता है। |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_54) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_55) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_56) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_57) | चौड़ाई को अनुपातिक रूप से बदलता है। डिफ़ॉल्ट रूप से [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) उपयोग किया जाता है। |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_58) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_59) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| rotate(angle) |  |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_60) | छवि को केंद्र के चारों ओर घुमाता है। |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_61) | छवि को घुमाता है, उलटता है, या घुमाकर उलटता है। |
| save() | छवि डेटा को अंतर्निहित स्ट्रीम में सहेजता है। |
| [save(file_path)](#save_file_path_62) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save(file_path, options)](#save_file_path_options_63) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_64) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save(file_path, over_write)](#save_file_path_over_write_65) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save(stream)](#save_stream_66) | ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम पर सहेजता है। |
| [save(stream, options_base)](#save_stream_options_base_67) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, इमेज का डेटा निर्दिष्ट स्ट्रीम पर सहेजता है। |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_68) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, इमेज का डेटा निर्दिष्ट स्ट्रीम पर सहेजता है। |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_69) | 32-बिट ARGB पिक्सेल सहेजता है। |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_70) | पिक्सेल सहेजता है (फ़ॉर्मेट-विशिष्ट विधि)। |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_71) | कच्चा डेटा सहेजता है। |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_72) | निर्दिष्ट स्थिति के लिए इमेज का 32-बिट ARGB पिक्सेल सेट करता है। |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_73) | इमेज पैलेट सेट करता है। |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_74) | निर्दिष्ट स्थिति के लिए इमेज पिक्सेल सेट करता है। |
| set_resolution(dpi_x, dpi_y) |  |
| [shallow_copy()](#shallow_copy__75) | वर्तमान लेयर की शैलो कॉपी बनाता है।<br/>            कृपया व्याख्या के लिए <see href="https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx" /> देखें। |
| [to_bitmap()](#to_bitmap__76) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_77) | पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स पर लिखता है। |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_78) | पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स पर लिखता है। |


### Constructor: Layer() {#Layer__1}


```
 Layer() 
```

नए [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) क्लास का उदाहरण आरंभ करता है। लेज़ी इनिशियलाइज़ेशन के लिए कंस्ट्रक्टर।

### Constructor: Layer(bounds, red_bytes, green_bytes, blue_bytes, name) {#Layer_bounds_red_bytes_green_bytes_blue_bytes_name_2}


```
 Layer(bounds, red_bytes, green_bytes, blue_bytes, name) 
```

बाइट एरेज़ से [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) क्लास का नया उदाहरण आरंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | लेयर की सीमाएँ। |
| red_bytes | byte | लाल बाइट्स। |
| green_bytes | byte | हरा बाइट्स। |
| blue_bytes | byte | नीला बाइट्स। |
| name | string | लेयर का नाम। |

### Constructor: Layer(image, dispose_image) {#Layer_image_dispose_image_3}


```
 Layer(image, dispose_image) 
```

[Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) क्लास का नया उदाहरण आरंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | छवि। |
| dispose_image | bool | यदि <c>true</c> पर सेट किया गया है [इमेज डिस्पोज़ करें]। |

### Constructor: Layer(stream) {#Layer_stream_4}


```
 Layer(stream) 
```

[Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) क्लास का नया उदाहरण आरंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | इमेज स्ट्रीम। |

### Method: add_layer_mask(layer_mask) {#add_layer_mask_layer_mask_1}


```
 add_layer_mask(layer_mask) 
```

वर्तमान लेयर में मास्क जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer_mask | [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata) | लेयर मास्क। |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_2}


```
 adjust_brightness(brightness) 
```

छवि की चमक को समायोजित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| चमक | int | ब्राइटनेस मान। |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_3}


```
 adjust_contrast(contrast) 
```

छवि कंट्रास्टिंग

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| कॉन्ट्रास्ट | float | कॉन्ट्रास्ट मान (रेंज [-100; 100] में) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_4}


```
 adjust_gamma(gamma) 
```

छवि का गामा-सुधार।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| गामा | float | लाल, हरे और नीले चैनलों के लिए गामा गुणांक |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_5}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

छवि का गामा-सुधार।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| gamma_red | float | लाल चैनल के लिए गामा गुणांक |
| gamma_green | float | हरे चैनल के लिए गामा गुणांक |
| gamma_blue | float | नीले चैनल के लिए गामा गुणांक |

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_6}


```
 binarize_bradley(brightness_difference) 
```

ब्रैडली के अनुकूली थ्रेशहोल्डिंग एल्गोरिद्म का उपयोग करके इंटीग्रल इमेज थ्रेशहोल्डिंग के साथ छवि का बाइनरीकरण

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brightness_difference | डबल | पिक्सेल और इस पिक्सेल के चारों ओर केंद्रित s x s विंडो के पिक्सेल औसत के बीच चमक अंतर। |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_7}


```
 binarize_bradley(brightness_difference, window_size) 
```

ब्रैडली के अनुकूली थ्रेशहोल्डिंग एल्गोरिद्म का उपयोग करके इंटीग्रल इमेज थ्रेशहोल्डिंग के साथ छवि का बाइनरीकरण

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brightness_difference | डबल | पिक्सेल और इस पिक्सेल के चारों ओर केंद्रित s x s विंडो के पिक्सेल औसत के बीच चमक अंतर। |
| window_size | int | इस पिक्सेल के चारों ओर केंद्रित s x s विंडो के पिक्सेल का आकार |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

पूर्वनिर्धारित थ्रेशहोल्ड के साथ छवि का बाइनरीकरण

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| थ्रेशोल्ड | byte | थ्रेशोल्ड मान। यदि पिक्सेल का संबंधित ग्रे मान थ्रेशोल्ड से बड़ा है, तो उसे 255 मान दिया जाएगा, अन्यथा 0। |

### Method: can_load(file_path)  [static] {#can_load_file_path_9}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_10}


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


### Method: can_load(stream)  [static] {#can_load_stream_11}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_12}


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


### Method: can_save(options) {#can_save_options_13}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_14}


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


### Method: crop(rectangle) {#crop_rectangle_15}


```
 crop(rectangle) 
```

छवि को क्रॉप करना।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | आयत। |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_16}


```
 dither(dithering_method, bits_count) 
```

वर्तमान छवि पर डिथरिंग करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | डिथरिंग विधि। |
| bits_count | int | डिथरिंग के लिए अंतिम बिट्स गिनती। |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_17}


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

### Method: draw_image(location, image) {#draw_image_location_image_18}


```
 draw_image(location, image) 
```

लेयर पर छवि को ड्रॉ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| location | [Point](/psd/python-net/aspose.psd/point) | स्थान। |
| image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | छवि। |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_19}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_20}


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


### Method: get_default_options(args) {#get_default_options_args_21}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_22}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट पिक्सेल एरे प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | पिक्सेल प्राप्त करने के लिए आयत। |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | आंशिक पिक्सेल लोडर। |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_23}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_24}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_25}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_26}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_27}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_28}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_29}


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


### Method: get_original_options() {#get_original_options__30}


```
 get_original_options() 
```

मूल फ़ाइल सेटिंग्स के आधार पर विकल्प प्राप्त करता है।<br/>            यह मूल छवि की बिट-गहराई और अन्य पैरामीटरों को अपरिवर्तित रखने में मददगार हो सकता है।<br/>            उदाहरण के लिए, यदि हम 1 बिट प्रति पिक्सेल वाले काले-सफ़ेद PNG छवि को लोड करते हैं और फिर इसे<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) मेथड का उपयोग करके सहेजते हैं, तो आउटपुट PNG छवि 8-बिट प्रति पिक्सेल के साथ उत्पन्न होगी।<br/>            इसे रोकने और 1-बिट प्रति पिक्सेल के साथ PNG छवि सहेजने के लिए, इस मेथड का उपयोग करके संबंधित सहेजने के विकल्प प्राप्त करें और उन्हें<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) मेथड को दूसरे पैरामीटर के रूप में पास करें।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | मूल फ़ाइल सेटिंग्स के आधार पर विकल्प। |


### Method: get_pixel(x, y) {#get_pixel_x_y_31}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_32}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_33}


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


### Method: get_skew_angle() {#get_skew_angle__34}


```
 get_skew_angle() 
```

  

**Returns**

| प्रकार | विवरण |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_35}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_36}


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


### Method: load(stream)  [static] {#load_stream_37}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_38}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_39}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_40}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_41}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_42}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_43}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

32-बिट ARGB पिक्सेल को आंशिक रूप से (ब्लॉकों द्वारा) लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | पिक्सेल लोड करने के लिए आयत। |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | आंशिक पिक्सेल लोडर। |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_44}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

पैक्स द्वारा आंशिक रूप से पिक्सेल लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | वांछित आयत। |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | पिक्सेल लोडर। |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_45}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_46}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_47}


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

### Method: merge_layer_to(layer_to_merge_into) {#merge_layer_to_layer_to_merge_into_48}


```
 merge_layer_to(layer_to_merge_into) 
```

लेयर को निर्दिष्ट लेयर में मिलाता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer_to_merge_into | [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | जिस लेयर में मिलाना है। |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_49}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_50}


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


### Method: resize(new_width, new_height) {#resize_new_width_new_height_51}


```
 resize(new_width, new_height) 
```

छवि का आकार बदलता है। डिफ़ॉल्ट रूप से [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) उपयोग किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_width | int | नई चौड़ाई। |
| new_height | int | नई ऊँचाई। |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_52}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_53}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_54}


```
 resize_height_proportionally(new_height) 
```

ऊँचाई को अनुपातिक रूप से बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_height | int | नई ऊँचाई। |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_55}


```
 resize_height_proportionally(new_height, resize_type) 
```

ऊँचाई को अनुपातिक रूप से बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_height | int | नई ऊँचाई। |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | रिसाइज़ का प्रकार। |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_56}


```
 resize_height_proportionally(new_height, settings) 
```

ऊँचाई को अनुपातिक रूप से बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_height | int | नई ऊँचाई। |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | छवि रिसाइज़ सेटिंग्स। |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_57}


```
 resize_width_proportionally(new_width) 
```

चौड़ाई को अनुपातिक रूप से बदलता है। डिफ़ॉल्ट रूप से [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) उपयोग किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_width | int | नई चौड़ाई। |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_58}


```
 resize_width_proportionally(new_width, resize_type) 
```

चौड़ाई को अनुपातिक रूप से बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_width | int | नई चौड़ाई। |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | रिसाइज़ का प्रकार। |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_59}


```
 resize_width_proportionally(new_width, settings) 
```

चौड़ाई को अनुपातिक रूप से बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_width | int | नई चौड़ाई। |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | छवि रिसाइज़ सेटिंग्स। |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_60}


```
 rotate(angle, resize_proportionally, background_color) 
```

छवि को केंद्र के चारों ओर घुमाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| कोण | float | डिग्री में घुमाव का कोण। सकारात्मक मान घड़ी की दिशा में घुमाएंगे। |
| resize_proportionally | bool | यदि <c>true</c> पर सेट किया गया है तो आपकी छवि का आकार घुमाए गए आयत (कोने के बिंदु) प्रोजेक्शन के अनुसार बदल जाएगा, अन्यथा आयाम अपरिवर्तित रहेंगे और केवल आंतरिक छवि सामग्री घुमाई जाएगी। |
| background_color | [Color](/psd/python-net/aspose.psd/color) | पृष्ठभूमि का रंग। |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_61}


```
 rotate_flip(rotate_flip_type) 
```

छवि को घुमाता है, उलटता है, या घुमाकर उलटता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | घुमाव फ़्लिप प्रकार। |

### Method: save(file_path) {#save_file_path_62}


```
 save(file_path) 
```

ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | ऑब्जेक्ट के डेटा को सहेजने के लिए फ़ाइल पथ। |

### Method: save(file_path, options) {#save_file_path_options_63}


```
 save(file_path, options) 
```

सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | फ़ाइल पथ। |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | विकल्प। |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_64}


```
 save(file_path, options, bounds_rectangle) 
```

सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | फ़ाइल पथ। |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | विकल्प। |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | गंतव्य छवि सीमाओं का आयत। स्रोत सीमाओं के उपयोग के लिए खाली आयत सेट करें। |

### Method: save(file_path, over_write) {#save_file_path_over_write_65}


```
 save(file_path, over_write) 
```

ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | ऑब्जेक्ट के डेटा को सहेजने के लिए फ़ाइल पथ। |
| over_write | bool | यदि <c>true</c> पर सेट किया गया है तो फ़ाइल सामग्री को ओवरराइट करें, अन्यथा जोड़ दिया जाएगा। |

### Method: save(stream) {#save_stream_66}


```
 save(stream) 
```

ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | ऑब्जेक्ट के डेटा को सहेजने के लिए स्ट्रीम। |

### Method: save(stream, options_base) {#save_stream_options_base_67}


```
 save(stream, options_base) 
```

सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, इमेज का डेटा निर्दिष्ट स्ट्रीम पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | छवि के डेटा को सहेजने के लिए स्ट्रीम। |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | सहेजने के विकल्प। |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_68}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_69}


```
 save_argb_32_pixels(rectangle, pixels) 
```

32-बिट ARGB पिक्सेल सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | पिक्सेल सहेजने के लिए आयत। |
| pixels | int | 32-बिट ARGB पिक्सेल एरे। |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_70}


```
 save_pixels(rectangle, pixels) 
```

पिक्सेल सहेजता है (फ़ॉर्मेट-विशिष्ट विधि)।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | पिक्सेल सहेजने के लिए आयत। |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | 32-बिट ARGB पिक्सेल एरे। |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_71}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_72}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_73}


```
 set_palette(palette, update_colors) 
```

इमेज पैलेट सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | सेट करने के लिए पैलेट। |
| update_colors | bool | यदि इसे <c>true</c> पर सेट किया जाता है तो रंग नई पैलेट के अनुसार अपडेट हो जाएंगे; अन्यथा रंग अनुक्रमांक अपरिवर्तित रहेंगे। ध्यान दें कि अपरिवर्तित अनुक्रमांक छवि को लोड करने पर क्रैश कर सकते हैं यदि कुछ अनुक्रमांक के लिए कोई संबंधित पैलेट प्रविष्टि नहीं है। |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_74}


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

### Method: shallow_copy() {#shallow_copy__75}


```
 shallow_copy() 
```

वर्तमान लेयर की शैलो कॉपी बनाता है।<br/>            कृपया व्याख्या के लिए <see href="https://msdn.microsoft.com/ru-ru/library/system.object.memberwiseclone(v=vs.110).aspx" /> देखें।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.xmp.schemas.photoshop/layer) | वर्तमान लेयर की एक उथली प्रति। |


### Method: to_bitmap() {#to_bitmap__76}


```
 to_bitmap() 
```

  

**Returns**

| प्रकार | विवरण |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_77}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स पर लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| scan_line_index | int | स्कैन लाइन का शून्य-आधारित सूचकांक। |
| argb_32_pixels | int | लिखने के लिए 32-बिट ARGB रंगों की एरे। |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_78}


```
 write_scan_line(scan_line_index, pixels) 
```

पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स पर लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| scan_line_index | int | स्कैन लाइन का शून्य-आधारित सूचकांक। |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | लिखने के लिए पिक्सेल रंगों की एरे। |

