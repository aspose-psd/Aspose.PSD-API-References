---
title: "PsdImage क्लास"
type: docs
weight: 1760
url: /hi/python-net/aspose.psd.fileformats.psd/psdimage/
---

**Summary:** Defines the PsdImage class that provides the ability to load, edit, save PSD files as well as<br/>            update properties, add watermarks, perform graphics operations or convert one file format to another.<br/>            Aspose.PSD supports import as a layer and export to the following formats:<br/>            Png, Jpeg, Jpeg2000, Gif, Bmp, Tiff, Psd, Psb along with export to Pdf with selectable text

**Module:** [aspose.psd.fileformats.psd](/psd/python-net/aspose.psd.fileformats.psd/)

**Full Name:** aspose.psd.fileformats.psd.PsdImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [PsdImage(path)](#PsdImage_path_1) | निर्दिष्ट पथ से रास्टर इमेज (पथ में psd इमेज नहीं) के आधार पर [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) क्लास का एक नया इंस्टेंस प्रारंभ करता है। डिफ़ॉल्ट पैरामीटर के साथ psd इमेज को इनिशियलाइज़ करने के लिए उपयोग किया जाता है - कलर मोड - rgb, 4 चैनल, प्रति चैनल 8 बिट, कम्प्रेशन - Raw। |
| [PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2) | निर्दिष्ट पथ से रास्टर इमेज (पथ में psd इमेज नहीं) के साथ कंस्ट्रक्टर पैरामीटर का उपयोग करके [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [PsdImage(raster_image)](#PsdImage_raster_image_3) | मौजूदा रास्टर इमेज (psd इमेज नहीं) से RGB कलर मोड, 4 चैनल, प्रति चैनल 8 बिट और बिना कम्प्रेशन के साथ [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4) | मौजूदा रास्टर इमेज (psd इमेज नहीं) से कंस्ट्रक्टर पैरामीटर का उपयोग करके [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [PsdImage(stream)](#PsdImage_stream_5) | निर्दिष्ट पथ से रास्टर इमेज (स्ट्रीम में psd इमेज नहीं) के आधार पर [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) क्लास का एक नया इंस्टेंस प्रारंभ करता है। डिफ़ॉल्ट पैरामीटर के साथ psd इमेज को इनिशियलाइज़ करने के लिए उपयोग किया जाता है - कलर मोड - rgb, 4 चैनल, प्रति चैनल 8 बिट, कम्प्रेशन - Raw। |
| [PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6) | निर्दिष्ट पथ से रास्टर इमेज (स्ट्रीम में psd इमेज नहीं) के साथ कंस्ट्रक्टर पैरामीटर का उपयोग करके [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
| [PsdImage(width, height)](#PsdImage_width_height_7) | निर्दिष्ट चौड़ाई और ऊँचाई के साथ [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) क्लास का एक नया इंस्टेंस प्रारंभ करता है। खाली psd इमेज को इनिशियलाइज़ करने के लिए उपयोग किया जाता है। |
| [PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression)](#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8) | निर्दिष्ट चौड़ाई, ऊँचाई, पैलेट, कलर मोड, चैनल संख्या और चैनल बिट-लेंथ तथा निर्दिष्ट कम्प्रेशन मोड पैरामीटर के साथ [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) क्लास का एक नया इंस्टेंस प्रारंभ करता है। खाली psd इमेज को इनिशियलाइज़ करने के लिए उपयोग किया जाता है। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| DEFAULT_VERSION [स्थैतिक] | int | r | डिफ़ॉल्ट PSD संस्करण। |
| active_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | सक्रिय लेयर को प्राप्त करता है या सेट करता है। |
| स्वत:_समायोजित_पैलेट | bool | r/w | स्वचालित पैलेट समायोजन दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | पृष्ठभूमि रंग के लिए मान प्राप्त करता है या सेट करता है। |
| bits_per_channel | int | r | प्रति चैनल बिट्स प्राप्त करता है। |
| बिट्स_प्रति_पिक्सेल | int | r | प्रति पिक्सेल छवि बिट्स की गिनती प्राप्त करता है। |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| बफ़र_आकार_संकेत | int | r/w | बफ़र आकार संकेत प्राप्त करता है या सेट करता है, जो सभी आंतरिक बफ़रों के लिए अधिकतम अनुमत आकार परिभाषित करता है। |
| चैनल्स_गणना | int | r | PSD चैनलों की गिनती प्राप्त करता है। |
| cmyk_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | CMYK PSD छवियों के लिए CMYK कलर प्रोफ़ाइल को प्राप्त करता है या सेट करता है। सही रंग रूपांतरण के लिए इसे RgbColorProfile के साथ जोड़ा जाना चाहिए। |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | r/w | कलर मोड को प्राप्त करता है या सेट करता है। |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | r | कम्प्रेशन विधि प्राप्त करता है। |
| container | [Image](/psd/python-net/aspose.psd/image) | r | प्राप्त करता है [Image](/psd/python-net/aspose.psd/image/) कंटेनर। |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | ऑब्जेक्ट का डेटा स्ट्रीम प्राप्त करता है। |
| disposed | bool | r | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस डिस्पोज़ किया गया है या नहीं। |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | फ़ाइल फ़ॉर्मेट का मान प्राप्त करता है। |
| global_angle | int | r/w | वैश्विक कोण प्राप्त करता है या सेट करता है। |
| global_layer_mask_info | [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | r | ग्लोबल लेयर मास्क जानकारी प्राप्त करता है। |
| global_layer_resources | [LayerResource[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | r/w | ग्लोबल लेयर संसाधनों को प्राप्त करता है या सेट करता है। |
| gray_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | ग्रेस्केल PSD छवियों के लिए GRAY (मोनोक्रोम) कलर प्रोफ़ाइल को प्राप्त करता है या सेट करता है। |
| has_alpha | bool | r | इस [RasterImage](/psd/python-net/aspose.psd/rasterimage/) की लंबवत रेज़ोल्यूशन, पिक्सेल प्रति इंच में, को प्राप्त करता है या सेट करता है। |
| has_background_color | bool | r/w | छवि में बैकग्राउंड रंग है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| has_transparency_data | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि जब लेयर डेटा निर्दिष्ट किया जाता है तो पहला अल्फा चैनल मर्ज किए गए परिणाम के लिए ट्रांसपेरेंसी डेटा रखता है या नहीं। |
| has_transparent_color | bool | r/w | छवि में ट्रांसपेरेंट रंग है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| height | int | r | छवि की ऊँचाई प्राप्त करता है। |
| horizontal_resolution | double | r/w | इस [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) की क्षैतिज रेज़ोल्यूशन, पिक्सेल प्रति इंच में, प्राप्त करता है या सेट करता है। |
| image_opacity | float | r | इस छवि की अपारदर्शिता प्राप्त करता है। |
| image_resources | [ResourceBlock[]](/psd/python-net/aspose.psd.fileformats.psd/resourceblock) | r/w | PSD इमेज संसाधनों को प्राप्त करता है या सेट करता है। |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | इंटरप्ट मॉनिटर प्राप्त करता है या सेट करता है। |
| is_cached | bool | r | यह संकेत करने वाला मान प्राप्त करता है कि छवि डेटा वर्तमान में कैश किया गया है या नहीं। |
| is_flatten | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि PSD इमेज फ्लैटन किया गया है या नहीं। |
| is_raw_data_available | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि कच्चा डेटा लोडिंग समर्थित है या नहीं। |
| layers | [Layer[]](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | r/w | PSD लेयर्स को प्राप्त करता है या सेट करता है। |
| linked_layers_manager | [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | r | लिंक्ड लेयर्स मैनेजर को प्राप्त करता है। |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | रंग पैलेट को प्राप्त करता है या सेट करता है। जब पिक्सेल सीधे दर्शाए जाते हैं तो रंग पैलेट का उपयोग नहीं किया जाता है। |
| premultiply_components | bool | r/w | एक मान को प्राप्त करता है या सेट करता है जो दर्शाता है कि क्या इमेज घटकों को प्री‑मल्टिप्लाइड होना चाहिए। |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | कस्टम कलर कनवर्टर को प्राप्त करता है या सेट करता है |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | कच्चे डेटा फ़ॉर्मेट को प्राप्त करता है। |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | वर्तमान कच्चा डेटा सेटिंग्स प्राप्त करता है। नोट: इन सेटिंग्स का उपयोग करने पर डेटा बिना रूपांतरण के लोड होता है। |
| raw_fallback_index | int | r/w | पैलेट इंडेक्स सीमा से बाहर होने पर उपयोग किए जाने वाले फ़ॉलबैक इंडेक्स को प्राप्त करता है या सेट करता है |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | इंडेक्स्ड कलर कनवर्टर को प्राप्त करता है या सेट करता है |
| raw_line_size | int | r | बाइट्स में कच्ची लाइन आकार को प्राप्त करता है। |
| rgb_color_profile | [StreamSource](/psd/python-net/aspose.psd.sources/streamsource/) | r/w | CMYK PSD छवियों के लिए RGB कलर प्रोफ़ाइल को प्राप्त करता है या सेट करता है। सही रंग रूपांतरण के लिए इसे CmykColorProfile के साथ जोड़ा जाना चाहिए। |
| size | [Size](/psd/python-net/aspose.psd/size) | r | ऑब्जेक्ट का आकार प्राप्त करता है। |
| smart_object_provider | [SmartObjectProvider](/psd/python-net/aspose.psd.fileformats.psd/smartobjectprovider) | r | स्मार्ट ऑब्जेक्ट प्रदाता को प्राप्त करता है। |
| timeline | [Timeline](/psd/python-net/aspose.psd.fileformats.psd.layers.animation/timeline/) | r | इस [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) का [PsdImage.timeline](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) प्राप्त करता है। |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | इमेज का पारदर्शी रंग प्राप्त करता है। |
| update_xmp_data | bool | r/w | एक मान को प्राप्त करता है या सेट करता है जो दर्शाता है कि XMP मेटाडेटा को अपडेट किया जाए या नहीं। |
| use_palette | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि इमेज पैलेट उपयोग किया गया है या नहीं। |
| use_raw_data | bool | r/w | एक मान को प्राप्त करता है या सेट करता है जो दर्शाता है कि जब कच्चा डेटा लोडिंग उपलब्ध हो तो उसका उपयोग किया जाए या नहीं। |
| version | int | r/w | संस्करण प्राप्त करता है या सेट करता है। |
| vertical_resolution | double | r/w | इस [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) की ऊर्ध्वाधर रेज़ोल्यूशन, पिक्सेल प्रति इंच में, प्राप्त करता है या सेट करता है। |
| width | int | r | इमेज की चौड़ाई प्राप्त करता है। |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | XMP मेटाडेटा प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [add_black_white_adjustment_layer()](#add_black_white_adjustment_layer__1) | ब्लैक व्हाइट एडजस्टमेंट लेयर जोड़ता है। |
| [add_brightness_contrast_adjustment_layer(brightness, contrast)](#add_brightness_contrast_adjustment_layer_brightness_contrast_2) | ब्राइटनेस/कॉन्ट्रास्ट एडजस्टमेंट लेयर जोड़ता है। |
| [add_channel_mixer_adjustment_layer()](#add_channel_mixer_adjustment_layer__3) | डिफ़ॉल्ट पैरामीटर के साथ चैनल मिक्सर एडजस्टमेंट लेयर जोड़ता है। |
| [add_color_balance_adjustment_layer()](#add_color_balance_adjustment_layer__4) | रंग संतुलन समायोजन लेयर जोड़ता है। |
| [add_curves_adjustment_layer()](#add_curves_adjustment_layer__5) | कर्व्स समायोजन लेयर जोड़ता है। |
| [add_exposure_adjustment_layer(exposure, offset, gamma_correction)](#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6) | एक्सपोज़र समायोजन लेयर जोड़ता है। |
| [add_gradient_map_adjustment_layer()](#add_gradient_map_adjustment_layer__7) | ग्रेडिएंटमैप समायोजन लेयर जोड़ता है। |
| [add_hue_saturation_adjustment_layer()](#add_hue_saturation_adjustment_layer__8) | ह्यू/सैचुरेशन समायोजन लेयर जोड़ता है। |
| [add_invert_adjustment_layer()](#add_invert_adjustment_layer__9) | इनवर्ट समायोजन लेयर जोड़ता है। |
| [add_layer(layer)](#add_layer_layer_10) | लेयर जोड़ता है। |
| [add_layer_group(group_name, index, start_behaviour)](#add_layer_group_group_name_index_start_behaviour_11) | लेयर समूह को जोड़ता है। |
| [add_levels_adjustment_layer()](#add_levels_adjustment_layer__12) | लेवल्स समायोजन लेयर जोड़ता है। |
| [add_photo_filter_layer(color)](#add_photo_filter_layer_color_13) | फ़ोटोफ़िल्टर लेयर जोड़ता है। |
| [add_posterize_adjustment_layer()](#add_posterize_adjustment_layer__14) | पोस्टराइज़ समायोजन लेयर जोड़ता है। |
| [add_regular_layer()](#add_regular_layer__15) | एक नया नियमित लेयर जोड़ता है। |
| [add_selective_color_adjustment_layer()](#add_selective_color_adjustment_layer__16) | सेलेक्टिव कलर समायोजन लेयर जोड़ता है। |
| [add_shape_layer()](#add_shape_layer__17) | खाली शेप लेयर जोड़ें।<br/>            बिना पाथ के। इन्हें सहेजने से पहले शेप लेयर में जोड़ना चाहिए। |
| [add_text_layer(text, rect)](#add_text_layer_text_rect_18) | एक नया टेक्स्ट लेयर जोड़ता है। |
| [add_threshold_adjustment_layer()](#add_threshold_adjustment_layer__19) | थ्रेशोल्ड समायोजन लेयर जोड़ता है। |
| [add_vibrance_adjustment_layer()](#add_vibrance_adjustment_layer__20) | वाइब्रेंस समायोजन लेयर जोड़ता है। |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_21) | छवि की चमक को समायोजित करता है। |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_22) | छवि कंट्रास्टिंग |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_23) | छवि का गामा-सुधार। |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_24) | छवि का गामा-सुधार। |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_25) | ब्रैडली के अनुकूली थ्रेशहोल्डिंग एल्गोरिद्म का उपयोग करके इंटीग्रल इमेज थ्रेशहोल्डिंग के साथ छवि का बाइनरीकरण |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_26) | ब्रैडली के अनुकूली थ्रेशहोल्डिंग एल्गोरिद्म का उपयोग करके इंटीग्रल इमेज थ्रेशहोल्डिंग के साथ छवि का बाइनरीकरण |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_27) | पूर्वनिर्धारित थ्रेशहोल्ड के साथ छवि का बाइनरीकरण |
| binarize_otsu() | ओट्सु थ्रेशहोल्डिंग के साथ छवि का बाइनरीकरण |
| cache_data() | डेटा को कैश करता है और सुनिश्चित करता है कि अंतर्निहित [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) से कोई अतिरिक्त डेटा लोडिंग नहीं होगी। |
| [can_load(file_path)](#can_load_file_path_28) | निर्धारित करता है कि छवि निर्दिष्ट फ़ाइल पथ से लोड की जा सकती है या नहीं। |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_29) | निर्धारित करता है कि छवि निर्दिष्ट फ़ाइल पथ से लोड की जा सकती है और वैकल्पिक रूप से निर्दिष्ट ओपन विकल्पों का उपयोग करके। |
| [can_load(stream)](#can_load_stream_30) | निर्धारित करता है कि छवि निर्दिष्ट स्ट्रीम से लोड की जा सकती है या नहीं। |
| [can_load(stream, load_options)](#can_load_stream_load_options_31) | निर्धारित करता है कि छवि निर्दिष्ट स्ट्रीम से लोड की जा सकती है और वैकल्पिक रूप से निर्दिष्ट <paramref name="loadOptions" /> का उपयोग करके। |
| [can_save(options)](#can_save_options_32) | निर्धारित करता है कि छवि को पास किए गए सहेज विकल्पों द्वारा प्रतिनिधित्व किए गए निर्दिष्ट फ़ाइल फ़ॉर्मेट में सहेजा जा सकता है या नहीं। |
| [convert(new_options)](#convert_new_options_33) | इस इमेज फ़ॉर्मेट को विकल्पों में निर्दिष्ट फ़ॉर्मेट में बदलता है। |
| [create(image_options, width, height)](#create_image_options_width_height_34) | निर्दिष्ट निर्माण विकल्पों का उपयोग करके नई छवि बनाता है। |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_35) | छवि को क्रॉप करना। |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_36) | वर्तमान छवि पर डिथरिंग करता है। |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_37) | वर्तमान छवि पर डिथरिंग करता है। |
| [filter(rectangle, options)](#filter_rectangle_options_38) | निर्दिष्ट आयत को फ़िल्टर करता है। |
| flatten_image() | सभी लेयर्स को फ्लैट करता है। |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_39) | एक छवि का 32-बिट ARGB पिक्सेल प्राप्त करता है। |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_40) | डिफ़ॉल्ट 32-बिट ARGB पिक्सेल एरे प्राप्त करता है। |
| [get_default_options(args)](#get_default_options_args_41) | डिफ़ॉल्ट विकल्प प्राप्त करता है। |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_42) | आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट पिक्सेल एरे प्राप्त करता है। |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43) | आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट रॉ डेटा एरे प्राप्त करता है। |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_44) | डिफ़ॉल्ट रॉ डेटा एरे प्राप्त करता है। |
| [get_file_format(file_path)](#get_file_format_file_path_45) | फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [get_file_format(stream)](#get_file_format_stream_46) | फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_47) | वर्तमान छवि के अनुरूप आयत प्राप्त करता है। |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_48) | वर्तमान छवि के अनुरूप आयत प्राप्त करता है। |
| [get_modify_date(use_default)](#get_modify_date_use_default_49) | संसाधन छवि के अंतिम संशोधित होने की तिथि और समय प्राप्त करता है। |
| [get_original_options()](#get_original_options__50) | मूल फ़ाइल सेटिंग्स के आधार पर विकल्प प्राप्त करता है।<br/>            यह मूल छवि की बिट-गहराई और अन्य पैरामीटरों को अपरिवर्तित रखने में मददगार हो सकता है।<br/>            उदाहरण के लिए, यदि हम 1 बिट प्रति पिक्सेल वाले काले-सफ़ेद PNG छवि को लोड करते हैं और फिर इसे<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) मेथड का उपयोग करके सहेजते हैं, तो आउटपुट PNG छवि 8-बिट प्रति पिक्सेल के साथ उत्पन्न होगी।<br/>            इसे रोकने और 1-बिट प्रति पिक्सेल के साथ PNG छवि सहेजने के लिए, इस मेथड का उपयोग करके संबंधित सहेजने के विकल्प प्राप्त करें और उन्हें<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) मेथड को दूसरे पैरामीटर के रूप में पास करें। |
| [get_pixel(x, y)](#get_pixel_x_y_51) | छवि पिक्सेल प्राप्त करता है।<br/>            प्रदर्शन चेतावनी: सभी छवि पिक्सेल पर इटरिट करने के लिए इस मेथड का उपयोग करने से बचें, क्योंकि इससे महत्वपूर्ण प्रदर्शन समस्याएँ हो सकती हैं।<br/>            अधिक कुशल पिक्सेल हेरफेर के लिए, पूरे पिक्सेल एरे को एक साथ प्राप्त करने हेतु `LoadArgb32Pixels` मेथड का उपयोग करें। |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_52) | अनुपाती ऊँचाई प्राप्त करता है। |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_53) | अनुपाती चौड़ाई प्राप्त करता है। |
| [get_skew_angle()](#get_skew_angle__54) |    |
| grayscale() | छवि को उसके ग्रेस्केल प्रतिनिधित्व में रूपांतरित करना |
| [load(file_path)](#load_file_path_55) | निर्दिष्ट फ़ाइल से नई छवि लोड करता है। |
| [load(file_path, load_options)](#load_file_path_load_options_56) | निर्दिष्ट फ़ाइल से नई छवि लोड करता है। |
| [load(stream)](#load_stream_57) | निर्दिष्ट स्ट्रीम से नई छवि लोड करता है। |
| [load(stream, load_options)](#load_stream_load_options_58) | निर्दिष्ट स्ट्रीम से नई छवि लोड करता है। |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_59) | 32-बिट ARGB पिक्सेल लोड करता है। |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_60) | 64-बिट ARGB पिक्सेल लोड करता है। |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_61) | CMYK प्रारूप में पिक्सेल लोड करता है। |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_62) | CMYK प्रारूप में पिक्सेल लोड करता है।<br/>            यह मेथड अप्रचलित है। कृपया अधिक प्रभावी [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) मेथड का उपयोग करें। |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63) | 32-बिट ARGB पिक्सेल को आंशिक रूप से (ब्लॉकों द्वारा) लोड करता है। |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_64) | पैक्स द्वारा आंशिक रूप से पिक्सेल लोड करता है। |
| [load_pixels(rectangle)](#load_pixels_rectangle_65) | पिक्सेल लोड करता है। |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66) | कच्चा डेटा लोड करता है। |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67) | कच्चा डेटा लोड करता है। |
| [merge_layers(bottom_layer, top_layer)](#merge_layers_bottom_layer_top_layer_68) | लेयर्स को मर्ज करता है। |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_69) | निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन पढ़ता है। |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_70) | निर्दिष्ट स्कैन लाइन इंडेक्स द्वारा पूरी स्कैन लाइन पढ़ता है। |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_71) | एक रंग को दूसरे से अनुमत अंतर के साथ बदलता है और स्मूथ किनारों को बचाने के लिए मूल अल्फा वैल्यू को संरक्षित रखता है। |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_72) | एक रंग को दूसरे से अनुमत अंतर के साथ बदलता है और स्मूथ किनारों को बचाने के लिए मूल अल्फा वैल्यू को संरक्षित रखता है। |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_73) | सभी गैर-ट्रांसपेरेंट रंगों को नए रंग से बदलता है और स्मूद एजेज़ को बचाने के लिए मूल अल्फा वैल्यू को संरक्षित रखता है।<br/>            नोट: यदि आप इसे बिना ट्रांसपेरेंसी वाली छवियों पर उपयोग करते हैं, तो सभी रंग एक ही रंग से बदल दिए जाएंगे। |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_74) | सभी गैर-ट्रांसपेरेंट रंगों को नए रंग से बदलता है और स्मूद एजेज़ को बचाने के लिए मूल अल्फा वैल्यू को संरक्षित रखता है।<br/>            नोट: यदि आप इसे बिना ट्रांसपेरेंसी वाली छवियों पर उपयोग करते हैं, तो सभी रंग एक ही रंग से बदल दिए जाएंगे। |
| [resize(new_width, new_height)](#resize_new_width_new_height_75) | छवि का आकार बदलता है। डिफ़ॉल्ट रूप से [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) उपयोग किया जाता है। |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_76) | छवि का आकार बदलता है। |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_77) | छवि का आकार बदलता है। |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_78) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_79) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_80) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_81) | चौड़ाई को अनुपातिक रूप से बदलता है। डिफ़ॉल्ट रूप से [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) उपयोग किया जाता है। |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_82) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_83) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| [rotate(angle)](#rotate_angle_84) | छवि को केंद्र के चारों ओर घुमाता है। |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_85) | छवि को केंद्र के चारों ओर घुमाता है। |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_86) | छवि को घुमाता है, उलटता है, या घुमाकर उलटता है। |
| save() | छवि डेटा को अंतर्निहित स्ट्रीम में सहेजता है। |
| [save(file_path)](#save_file_path_87) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save(file_path, options)](#save_file_path_options_88) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_89) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save(file_path, over_write)](#save_file_path_over_write_90) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save(stream)](#save_stream_91) | ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम पर सहेजता है। |
| [save(stream, options_base)](#save_stream_options_base_92) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, इमेज का डेटा निर्दिष्ट स्ट्रीम पर सहेजता है। |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_93) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, इमेज का डेटा निर्दिष्ट स्ट्रीम पर सहेजता है। |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_94) | 32-बिट ARGB पिक्सेल सहेजता है। |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_95) | पिक्सेल सहेजता है (फ़ॉर्मेट-विशिष्ट विधि)। |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_96) | कच्चा डेटा सहेजता है। |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_97) | निर्दिष्ट स्थिति के लिए इमेज का 32-बिट ARGB पिक्सेल सेट करता है। |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_98) | इमेज पैलेट सेट करता है। |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_99) | निर्दिष्ट स्थिति के लिए इमेज पिक्सेल सेट करता है। |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_100) | इस [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) के लिए रिज़ॉल्यूशन सेट करता है। |
| [to_bitmap()](#to_bitmap__101) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102) | पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स पर लिखता है। |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_103) | पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स पर लिखता है। |


### Constructor: PsdImage(path) {#PsdImage_path_1}


```
 PsdImage(path) 
```

निर्दिष्ट पथ से रास्टर इमेज (पथ में psd इमेज नहीं) के आधार पर [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) क्लास का एक नया इंस्टेंस प्रारंभ करता है। डिफ़ॉल्ट पैरामीटर के साथ psd इमेज को इनिशियलाइज़ करने के लिए उपयोग किया जाता है - कलर मोड - rgb, 4 चैनल, प्रति चैनल 8 बिट, कम्प्रेशन - Raw।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| पथ | string | पिक्सेल और पैलेट डेटा लोड करने और इनिशियलाइज़ करने के लिए पाथ। |

### Constructor: PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_path_color_mode_channel_bit_depth_channels_psd_version_compression_2}


```
 PsdImage(path, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

निर्दिष्ट पथ से रास्टर इमेज (पथ में psd इमेज नहीं) के साथ कंस्ट्रक्टर पैरामीटर का उपयोग करके [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| पथ | string | पिक्सेल और पैलेट डेटा लोड करने और इनिशियलाइज़ करने के लिए पाथ। |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | रंग मोड। |
| channel_bit_depth | short | PSD चैनल प्रति बिट गहराई। |
| चैनल | short | PSD चैनलों की गिनती। |
| psd_version | int | PSD संस्करण। |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | उपयोग करने के लिए संपीड़न। |

### Constructor: PsdImage(raster_image) {#PsdImage_raster_image_3}


```
 PsdImage(raster_image) 
```

मौजूदा रास्टर इमेज (psd इमेज नहीं) से RGB कलर मोड, 4 चैनल, प्रति चैनल 8 बिट और बिना कम्प्रेशन के साथ [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | पिक्सेल और पैलेट डेटा लोड करने और प्रारंभ करने के लिए छवि। |

### Constructor: PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_raster_image_color_mode_channel_bit_depth_channels_psd_version_compression_4}


```
 PsdImage(raster_image, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

मौजूदा रास्टर इमेज (psd इमेज नहीं) से कंस्ट्रक्टर पैरामीटर का उपयोग करके [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| raster_image | [RasterImage](/psd/python-net/aspose.psd/rasterimage) | पिक्सेल और पैलेट डेटा लोड करने और प्रारंभ करने के लिए छवि। |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | रंग मोड। |
| channel_bit_depth | short | PSD चैनल प्रति बिट गहराई। |
| चैनल | short | PSD चैनलों की गिनती। |
| psd_version | int | PSD संस्करण। |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | उपयोग करने के लिए संपीड़न। |

### Constructor: PsdImage(stream) {#PsdImage_stream_5}


```
 PsdImage(stream) 
```

निर्दिष्ट पथ से रास्टर इमेज (स्ट्रीम में psd इमेज नहीं) के आधार पर [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) क्लास का एक नया इंस्टेंस प्रारंभ करता है। डिफ़ॉल्ट पैरामीटर के साथ psd इमेज को इनिशियलाइज़ करने के लिए उपयोग किया जाता है - कलर मोड - rgb, 4 चैनल, प्रति चैनल 8 बिट, कम्प्रेशन - Raw।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | पिक्सेल और पैलेट डेटा लोड करने और प्रारंभ करने के लिए स्ट्रीम। |

### Constructor: PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_stream_color_mode_channel_bit_depth_channels_psd_version_compression_6}


```
 PsdImage(stream, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

निर्दिष्ट पथ से रास्टर इमेज (स्ट्रीम में psd इमेज नहीं) के साथ कंस्ट्रक्टर पैरामीटर का उपयोग करके [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) क्लास का एक नया इंस्टेंस प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | पिक्सेल और पैलेट डेटा लोड करने और प्रारंभ करने के लिए स्ट्रीम। |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | रंग मोड। |
| channel_bit_depth | short | PSD चैनल प्रति बिट गहराई। |
| चैनल | short | PSD चैनलों की गिनती। |
| psd_version | int | PSD संस्करण। |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | उपयोग करने के लिए संपीड़न। |

### Constructor: PsdImage(width, height) {#PsdImage_width_height_7}


```
 PsdImage(width, height) 
```

निर्दिष्ट चौड़ाई और ऊँचाई के साथ [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) क्लास का एक नया इंस्टेंस प्रारंभ करता है। खाली psd इमेज को इनिशियलाइज़ करने के लिए उपयोग किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| width | int | छवि की चौड़ाई। |
| height | int | छवि की ऊँचाई। |

### Constructor: PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) {#PsdImage_width_height_color_palette_color_mode_channel_bit_depth_channels_psd_version_compression_8}


```
 PsdImage(width, height, color_palette, color_mode, channel_bit_depth, channels, psd_version, compression) 
```

निर्दिष्ट चौड़ाई, ऊँचाई, पैलेट, कलर मोड, चैनल संख्या और चैनल बिट-लेंथ तथा निर्दिष्ट कम्प्रेशन मोड पैरामीटर के साथ [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) क्लास का एक नया इंस्टेंस प्रारंभ करता है। खाली psd इमेज को इनिशियलाइज़ करने के लिए उपयोग किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| width | int | छवि की चौड़ाई। |
| height | int | छवि की ऊँचाई। |
| color_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | रंग पैलेट। |
| color_mode | [ColorModes](/psd/python-net/aspose.psd.fileformats.psd/colormodes) | रंग मोड। |
| channel_bit_depth | short | PSD चैनल प्रति बिट गहराई। |
| चैनल | short | PSD चैनलों की गिनती। |
| psd_version | int | PSD संस्करण। |
| compression | [CompressionMethod](/psd/python-net/aspose.psd.fileformats.psd/compressionmethod) | उपयोग करने के लिए संपीड़न। |

### Method: add_black_white_adjustment_layer() {#add_black_white_adjustment_layer__1}


```
 add_black_white_adjustment_layer() 
```

ब्लैक व्हाइट एडजस्टमेंट लेयर जोड़ता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [BlackWhiteAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/blackwhiteadjustmentlayer/) | बनाया गया काला-श्वेत समायोजन लेयर। |


### Method: add_brightness_contrast_adjustment_layer(brightness, contrast) {#add_brightness_contrast_adjustment_layer_brightness_contrast_2}


```
 add_brightness_contrast_adjustment_layer(brightness, contrast) 
```

ब्राइटनेस/कॉन्ट्रास्ट एडजस्टमेंट लेयर जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| चमक | int | ब्राइटनेस। |
| कॉन्ट्रास्ट | int | कॉन्ट्रास्ट। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [BrightnessContrastLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/brightnesscontrastlayer/) | बनाया गया चमक/विरोधाभास लेयर |


### Method: add_channel_mixer_adjustment_layer() {#add_channel_mixer_adjustment_layer__3}


```
 add_channel_mixer_adjustment_layer() 
```

डिफ़ॉल्ट पैरामीटर के साथ चैनल मिक्सर एडजस्टमेंट लेयर जोड़ता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ChannelMixerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/channelmixerlayer/) | जोड़ा गया चैनल मिक्सर लेयर |


### Method: add_color_balance_adjustment_layer() {#add_color_balance_adjustment_layer__4}


```
 add_color_balance_adjustment_layer() 
```

रंग संतुलन समायोजन लेयर जोड़ता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ColorBalanceAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/colorbalanceadjustmentlayer/) | एक नया बनाया गया रंग संतुलन लेयर। |


### Method: add_curves_adjustment_layer() {#add_curves_adjustment_layer__5}


```
 add_curves_adjustment_layer() 
```

कर्व्स समायोजन लेयर जोड़ता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) | बनाया गया [CurvesLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/curveslayer/) लेयर |


### Method: add_exposure_adjustment_layer(exposure, offset, gamma_correction) {#add_exposure_adjustment_layer_exposure_offset_gamma_correction_6}


```
 add_exposure_adjustment_layer(exposure, offset, gamma_correction) 
```

एक्सपोज़र समायोजन लेयर जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| एक्सपोज़र | float | एक्सपोज़र। |
| offset | float | ऑफ़सेट। |
| gamma_correction | float | गामा सुधार। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ExposureLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/exposurelayer/) | बनाया गया एक्सपोज़र समायोजन लेयर |


### Method: add_gradient_map_adjustment_layer() {#add_gradient_map_adjustment_layer__7}


```
 add_gradient_map_adjustment_layer() 
```

ग्रेडिएंटमैप समायोजन लेयर जोड़ता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [GradientMapLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/gradientmaplayer/) | GradientMap उदाहरण। |


### Method: add_hue_saturation_adjustment_layer() {#add_hue_saturation_adjustment_layer__8}


```
 add_hue_saturation_adjustment_layer() 
```

ह्यू/सैचुरेशन समायोजन लेयर जोड़ता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [HueSaturationLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/huesaturationlayer/) | एक नया बनाया गया ह्यू/सैचुरेशन लेयर। |


### Method: add_invert_adjustment_layer() {#add_invert_adjustment_layer__9}


```
 add_invert_adjustment_layer() 
```

इनवर्ट समायोजन लेयर जोड़ता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [InvertAdjustmentLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/invertadjustmentlayer/) | बनाया गया इनवर्ट लेयर |


### Method: add_layer(layer) {#add_layer_layer_10}


```
 add_layer(layer) 
```

लेयर जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | लेयर। |

### Method: add_layer_group(group_name, index, start_behaviour) {#add_layer_group_group_name_index_start_behaviour_11}


```
 add_layer_group(group_name, index, start_behaviour) 
```

लेयर समूह को जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| group_name | string | समूह का नाम। |
| index | int | उस लेयर का इंडेक्स जिसके बाद सम्मिलित किया जाना है। |
| start_behaviour | bool | यदि <c>true</c> [start behaviour] पर सेट किया गया है तो समूह स्टार्ट अप पर खुली स्थिति में रहेगा, अन्यथा न्यूनतम स्थिति में रहेगा। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | समूह लेयर खोलना |


### Method: add_levels_adjustment_layer() {#add_levels_adjustment_layer__12}


```
 add_levels_adjustment_layer() 
```

लेवल्स समायोजन लेयर जोड़ता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [LevelsLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/levelslayer/) | एक नया बनाया गया लेवल्स लेयर |


### Method: add_photo_filter_layer(color) {#add_photo_filter_layer_color_13}


```
 add_photo_filter_layer(color) 
```

फ़ोटोफ़िल्टर लेयर जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| color | [Color](/psd/python-net/aspose.psd/color) | रंग। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PhotoFilterLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/photofilterlayer/) | बनाया गया फोटोफ़िल्टर लेयर |


### Method: add_posterize_adjustment_layer() {#add_posterize_adjustment_layer__14}


```
 add_posterize_adjustment_layer() 
```

पोस्टराइज़ समायोजन लेयर जोड़ता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PosterizeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/posterizelayer/) | PosterizeLayer उदाहरण। |


### Method: add_regular_layer() {#add_regular_layer__15}


```
 add_regular_layer() 
```

एक नया नियमित लेयर जोड़ता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | बनाया गया नियमित लेयर। |


### Method: add_selective_color_adjustment_layer() {#add_selective_color_adjustment_layer__16}


```
 add_selective_color_adjustment_layer() 
```

सेलेक्टिव कलर समायोजन लेयर जोड़ता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [SelectiveColorLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/selectivecolorlayer/) | बनाया गया चयनात्मक रंग समायोजन लेयर। |


### Method: add_shape_layer() {#add_shape_layer__17}


```
 add_shape_layer() 
```

खाली शेप लेयर जोड़ें।<br/>            बिना पाथ के। इन्हें सहेजने से पहले शेप लेयर में जोड़ना चाहिए।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | ShapeLayer उदाहरण। |


### Method: add_text_layer(text, rect) {#add_text_layer_text_rect_18}


```
 add_text_layer(text, rect) 
```

एक नया टेक्स्ट लेयर जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| text | string | लेयर का टेक्स्ट। |
| rect | [Rectangle](/psd/python-net/aspose.psd/rectangle) | लेयर का आयत। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | बनाया गया टेक्स्ट लेयर। |


### Method: add_threshold_adjustment_layer() {#add_threshold_adjustment_layer__19}


```
 add_threshold_adjustment_layer() 
```

थ्रेशोल्ड समायोजन लेयर जोड़ता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ThresholdLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/thresholdlayer/) | बनाया गया थ्रेशहोल्ड समायोजन लेयर। |


### Method: add_vibrance_adjustment_layer() {#add_vibrance_adjustment_layer__20}


```
 add_vibrance_adjustment_layer() 
```

वाइब्रेंस समायोजन लेयर जोड़ता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VibranceLayer](/psd/python-net/aspose.psd.fileformats.psd.layers.adjustmentlayers/vibrancelayer/) | एक नया बनाया गया वाइब्रेंस लेयर। |


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_21}


```
 adjust_brightness(brightness) 
```

छवि की चमक को समायोजित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| चमक | int | ब्राइटनेस मान। |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_22}


```
 adjust_contrast(contrast) 
```

छवि कंट्रास्टिंग

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| कॉन्ट्रास्ट | float | कॉन्ट्रास्ट मान (रेंज [-100; 100] में) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_23}


```
 adjust_gamma(gamma) 
```

छवि का गामा-सुधार।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| गामा | float | लाल, हरे और नीले चैनलों के लिए गामा गुणांक |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_24}


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

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_25}


```
 binarize_bradley(brightness_difference) 
```

ब्रैडली के अनुकूली थ्रेशहोल्डिंग एल्गोरिद्म का उपयोग करके इंटीग्रल इमेज थ्रेशहोल्डिंग के साथ छवि का बाइनरीकरण

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brightness_difference | डबल | पिक्सेल और इस पिक्सेल के चारों ओर केंद्रित s x s विंडो के पिक्सेल औसत के बीच चमक अंतर। |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_26}


```
 binarize_bradley(brightness_difference, window_size) 
```

ब्रैडली के अनुकूली थ्रेशहोल्डिंग एल्गोरिद्म का उपयोग करके इंटीग्रल इमेज थ्रेशहोल्डिंग के साथ छवि का बाइनरीकरण

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| brightness_difference | डबल | पिक्सेल और इस पिक्सेल के चारों ओर केंद्रित s x s विंडो के पिक्सेल औसत के बीच चमक अंतर। |
| window_size | int | इस पिक्सेल के चारों ओर केंद्रित s x s विंडो के पिक्सेल का आकार |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_27}


```
 binarize_fixed(threshold) 
```

पूर्वनिर्धारित थ्रेशहोल्ड के साथ छवि का बाइनरीकरण

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| थ्रेशोल्ड | byte | थ्रेशोल्ड मान। यदि पिक्सेल का संबंधित ग्रे मान थ्रेशोल्ड से बड़ा है, तो उसे 255 मान दिया जाएगा, अन्यथा 0। |

### Method: can_load(file_path)  [static] {#can_load_file_path_28}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_29}


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


### Method: can_load(stream)  [static] {#can_load_stream_30}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_31}


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


### Method: can_save(options) {#can_save_options_32}


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


### Method: convert(new_options) {#convert_new_options_33}


```
 convert(new_options) 
```

इस इमेज फ़ॉर्मेट को विकल्पों में निर्दिष्ट फ़ॉर्मेट में बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_options | [PsdOptions](/psd/python-net/aspose.psd.imageoptions/psdoptions/) | नए विकल्प। |

### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_34}


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


### Method: crop(rectangle) {#crop_rectangle_35}


```
 crop(rectangle) 
```

छवि को क्रॉप करना।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | आयत। |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_36}


```
 dither(dithering_method, bits_count) 
```

वर्तमान छवि पर डिथरिंग करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | डिथरिंग विधि। |
| bits_count | int | डिथरिंग के लिए अंतिम बिट्स गिनती। |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_37}


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

### Method: filter(rectangle, options) {#filter_rectangle_options_38}


```
 filter(rectangle, options) 
```

निर्दिष्ट आयत को फ़िल्टर करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | आयत। |
| options | [FilterOptionsBase](/psd/python-net/aspose.psd.imagefilters.filteroptions/filteroptionsbase/) | विकल्प। |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_39}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_40}


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


### Method: get_default_options(args) {#get_default_options_args_41}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_42}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

आंशिक पिक्सेल लोडर का उपयोग करके डिफ़ॉल्ट पिक्सेल एरे प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | पिक्सेल प्राप्त करने के लिए आयत। |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | आंशिक पिक्सेल लोडर। |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_43}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_44}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_45}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_46}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_47}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_48}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_49}


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


### Method: get_original_options() {#get_original_options__50}


```
 get_original_options() 
```

मूल फ़ाइल सेटिंग्स के आधार पर विकल्प प्राप्त करता है।<br/>            यह मूल छवि की बिट-गहराई और अन्य पैरामीटरों को अपरिवर्तित रखने में मददगार हो सकता है।<br/>            उदाहरण के लिए, यदि हम 1 बिट प्रति पिक्सेल वाले काले-सफ़ेद PNG छवि को लोड करते हैं और फिर इसे<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) मेथड का उपयोग करके सहेजते हैं, तो आउटपुट PNG छवि 8-बिट प्रति पिक्सेल के साथ उत्पन्न होगी।<br/>            इसे रोकने और 1-बिट प्रति पिक्सेल के साथ PNG छवि सहेजने के लिए, इस मेथड का उपयोग करके संबंधित सहेजने के विकल्प प्राप्त करें और उन्हें<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) मेथड को दूसरे पैरामीटर के रूप में पास करें।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | मूल फ़ाइल सेटिंग्स के आधार पर विकल्प। |


### Method: get_pixel(x, y) {#get_pixel_x_y_51}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_52}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_53}


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


### Method: get_skew_angle() {#get_skew_angle__54}


```
 get_skew_angle() 
```

  

**Returns**

| प्रकार | विवरण |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_55}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_56}


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


### Method: load(stream)  [static] {#load_stream_57}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_58}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_59}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_60}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_61}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_62}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

32-बिट ARGB पिक्सेल को आंशिक रूप से (ब्लॉकों द्वारा) लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | पिक्सेल लोड करने के लिए आयत। |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | आंशिक पिक्सेल लोडर। |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_64}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

पैक्स द्वारा आंशिक रूप से पिक्सेल लोड करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | वांछित आयत। |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | पिक्सेल लोडर। |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_65}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_66}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_67}


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

### Method: merge_layers(bottom_layer, top_layer) {#merge_layers_bottom_layer_top_layer_68}


```
 merge_layers(bottom_layer, top_layer) 
```

लेयर्स को मर्ज करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| bottom_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | निचला लेयर। |
| top_layer | [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | ऊपरी लेयर। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | मर्ज के बाद निचला लेयर |


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_69}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_70}


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


### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_71}


```
 replace_color(old_color, old_color_diff, new_color) 
```

एक रंग को दूसरे से अनुमत अंतर के साथ बदलता है और स्मूथ किनारों को बचाने के लिए मूल अल्फा वैल्यू को संरक्षित रखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| old_color | [Color](/psd/python-net/aspose.psd/color) |  |
| old_color_diff | byte | पुराने रंग में अनुमति दिया गया अंतर, जिससे बदले गए रंग टोन को विस्तारित किया जा सके। |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_72}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

एक रंग को दूसरे से अनुमत अंतर के साथ बदलता है और स्मूथ किनारों को बचाने के लिए मूल अल्फा वैल्यू को संरक्षित रखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| old_color_argb | int | बदले जाने वाले पुराने रंग का ARGB मान। |
| old_color_diff | byte | पुराने रंग में अनुमति दिया गया अंतर, जिससे बदले गए रंग टोन को विस्तारित किया जा सके। |
| new_color_argb | int | नए रंग का ARGB मान, जिससे पुराने रंग को बदला जाएगा। |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_73}


```
 replace_non_transparent_colors(new_color) 
```

सभी गैर-ट्रांसपेरेंट रंगों को नए रंग से बदलता है और स्मूद एजेज़ को बचाने के लिए मूल अल्फा वैल्यू को संरक्षित रखता है।<br/>            नोट: यदि आप इसे बिना ट्रांसपेरेंसी वाली छवियों पर उपयोग करते हैं, तो सभी रंग एक ही रंग से बदल दिए जाएंगे।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_color | [Color](/psd/python-net/aspose.psd/color) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_74}


```
 replace_non_transparent_colors(new_color_argb) 
```

सभी गैर-ट्रांसपेरेंट रंगों को नए रंग से बदलता है और स्मूद एजेज़ को बचाने के लिए मूल अल्फा वैल्यू को संरक्षित रखता है।<br/>            नोट: यदि आप इसे बिना ट्रांसपेरेंसी वाली छवियों पर उपयोग करते हैं, तो सभी रंग एक ही रंग से बदल दिए जाएंगे।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_color_argb | int | गैर-ट्रांसपेरेंट रंगों को बदलने के लिए नया रंग ARGB मान। |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_75}


```
 resize(new_width, new_height) 
```

छवि का आकार बदलता है। डिफ़ॉल्ट रूप से [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) उपयोग किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_width | int | नई चौड़ाई। |
| new_height | int | नई ऊँचाई। |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_76}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_77}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_78}


```
 resize_height_proportionally(new_height) 
```

ऊँचाई को अनुपातिक रूप से बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_height | int | नई ऊँचाई। |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_79}


```
 resize_height_proportionally(new_height, resize_type) 
```

ऊँचाई को अनुपातिक रूप से बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_height | int | नई ऊँचाई। |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | रिसाइज़ का प्रकार। |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_80}


```
 resize_height_proportionally(new_height, settings) 
```

ऊँचाई को अनुपातिक रूप से बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_height | int | नई ऊँचाई। |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | छवि रिसाइज़ सेटिंग्स। |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_81}


```
 resize_width_proportionally(new_width) 
```

चौड़ाई को अनुपातिक रूप से बदलता है। डिफ़ॉल्ट रूप से [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) उपयोग किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_width | int | नई चौड़ाई। |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_82}


```
 resize_width_proportionally(new_width, resize_type) 
```

चौड़ाई को अनुपातिक रूप से बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_width | int | नई चौड़ाई। |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | रिसाइज़ का प्रकार। |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_83}


```
 resize_width_proportionally(new_width, settings) 
```

चौड़ाई को अनुपातिक रूप से बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_width | int | नई चौड़ाई। |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | छवि रिसाइज़ सेटिंग्स। |

### Method: rotate(angle) {#rotate_angle_84}


```
 rotate(angle) 
```

छवि को केंद्र के चारों ओर घुमाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| कोण | float | डिग्री में घुमाव का कोण। सकारात्मक मान घड़ी की दिशा में घुमाएंगे। |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_85}


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

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_86}


```
 rotate_flip(rotate_flip_type) 
```

छवि को घुमाता है, उलटता है, या घुमाकर उलटता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | घुमाव फ़्लिप प्रकार। |

### Method: save(file_path) {#save_file_path_87}


```
 save(file_path) 
```

ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | ऑब्जेक्ट के डेटा को सहेजने के लिए फ़ाइल पथ। |

### Method: save(file_path, options) {#save_file_path_options_88}


```
 save(file_path, options) 
```

सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | फ़ाइल पथ। |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | विकल्प। |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_89}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_90}


```
 save(file_path, over_write) 
```

ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | ऑब्जेक्ट के डेटा को सहेजने के लिए फ़ाइल पथ। |
| over_write | bool | यदि <c>true</c> पर सेट किया गया है तो फ़ाइल सामग्री को ओवरराइट करें, अन्यथा जोड़ दिया जाएगा। |

### Method: save(stream) {#save_stream_91}


```
 save(stream) 
```

ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | ऑब्जेक्ट के डेटा को सहेजने के लिए स्ट्रीम। |

### Method: save(stream, options_base) {#save_stream_options_base_92}


```
 save(stream, options_base) 
```

सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, इमेज का डेटा निर्दिष्ट स्ट्रीम पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | छवि के डेटा को सहेजने के लिए स्ट्रीम। |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | सहेजने के विकल्प। |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_93}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_94}


```
 save_argb_32_pixels(rectangle, pixels) 
```

32-बिट ARGB पिक्सेल सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | पिक्सेल सहेजने के लिए आयत। |
| pixels | int | 32-बिट ARGB पिक्सेल एरे। |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_95}


```
 save_pixels(rectangle, pixels) 
```

पिक्सेल सहेजता है (फ़ॉर्मेट-विशिष्ट विधि)।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | पिक्सेल सहेजने के लिए आयत। |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | 32-बिट ARGB पिक्सेल एरे। |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_96}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_97}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_98}


```
 set_palette(palette, update_colors) 
```

इमेज पैलेट सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | सेट करने के लिए पैलेट। |
| update_colors | bool | यदि इसे <c>true</c> पर सेट किया जाता है तो रंग नई पैलेट के अनुसार अपडेट हो जाएंगे; अन्यथा रंग अनुक्रमांक अपरिवर्तित रहेंगे। ध्यान दें कि अपरिवर्तित अनुक्रमांक छवि को लोड करने पर क्रैश कर सकते हैं यदि कुछ अनुक्रमांक के लिए कोई संबंधित पैलेट प्रविष्टि नहीं है। |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_99}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_100}


```
 set_resolution(dpi_x, dpi_y) 
```

इस [PsdImage](/psd/python-net/aspose.psd.fileformats.psd/psdimage/) के लिए रिज़ॉल्यूशन सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| dpi_x | double | हॉरिज़ॉन्टल रिज़ॉल्यूशन (डॉट्स प्रति इंच में) [RasterImage](/psd/python-net/aspose.psd/rasterimage/) का। |
| dpi_y | double | वर्टिकल रिज़ॉल्यूशन (डॉट्स प्रति इंच में) [RasterImage](/psd/python-net/aspose.psd/rasterimage/) का। |

### Method: to_bitmap() {#to_bitmap__101}


```
 to_bitmap() 
```

  

**Returns**

| प्रकार | विवरण |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_102}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स पर लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| scan_line_index | int | स्कैन लाइन का शून्य-आधारित सूचकांक। |
| argb_32_pixels | int | लिखने के लिए 32-बिट ARGB रंगों की एरे। |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_103}


```
 write_scan_line(scan_line_index, pixels) 
```

पूरी स्कैन लाइन को निर्दिष्ट स्कैन लाइन इंडेक्स पर लिखता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| scan_line_index | int | स्कैन लाइन का शून्य-आधारित सूचकांक। |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | लिखने के लिए पिक्सेल रंगों की एरे। |

