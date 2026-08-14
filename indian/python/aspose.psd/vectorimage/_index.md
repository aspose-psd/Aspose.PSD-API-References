---
title: "VectorImage क्लास"
type: docs
weight: 4700
url: /hi/python-net/aspose.psd/vectorimage/
---

**Summary:** The vector image is the base class for all type of vector images.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.VectorImage

**Inheritance:** IObjectWithBounds, IObjectWithSizeF, Image

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
| has_background_color | bool | r/w | छवि में बैकग्राउंड रंग है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| height | int | r | छवि की ऊँचाई प्राप्त करता है। |
| height_f | float | r | ऑब्जेक्ट की ऊँचाई प्राप्त करता है, इंच में। |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | इंटरप्ट मॉनिटर प्राप्त करता है या सेट करता है। |
| is_cached | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि ऑब्जेक्ट का डेटा वर्तमान में कैश किया गया है और डेटा पढ़ने की आवश्यकता नहीं है। |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | रंग पैलेट को प्राप्त करता है या सेट करता है। जब पिक्सेल सीधे दर्शाए जाते हैं तो रंग पैलेट का उपयोग नहीं किया जाता है। |
| size | [Size](/psd/python-net/aspose.psd/size) | r | छवि का आकार प्राप्त करता है। |
| size_f | [SizeF](/psd/python-net/aspose.psd/sizef) | r | ऑब्जेक्ट का आकार प्राप्त करता है, इंच में। |
| use_palette | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि इमेज पैलेट उपयोग किया गया है या नहीं। |
| width | int | r | इमेज की चौड़ाई प्राप्त करता है। |
| width_f | float | r | ऑब्जेक्ट की चौड़ाई प्राप्त करता है, इंच में। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| cache_data() | डेटा को कैश करता है और सुनिश्चित करता है कि अंतर्निहित [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) से कोई अतिरिक्त डेटा लोडिंग नहीं होगी। |
| [can_load(file_path)](#can_load_file_path_1) | निर्धारित करता है कि छवि निर्दिष्ट फ़ाइल पथ से लोड की जा सकती है या नहीं। |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | निर्धारित करता है कि छवि निर्दिष्ट फ़ाइल पथ से लोड की जा सकती है और वैकल्पिक रूप से निर्दिष्ट ओपन विकल्पों का उपयोग करके। |
| [can_load(stream)](#can_load_stream_3) | निर्धारित करता है कि छवि निर्दिष्ट स्ट्रीम से लोड की जा सकती है या नहीं। |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | निर्धारित करता है कि छवि निर्दिष्ट स्ट्रीम से लोड की जा सकती है और वैकल्पिक रूप से निर्दिष्ट <paramref name="loadOptions" /> का उपयोग करके। |
| [can_save(options)](#can_save_options_5) | निर्धारित करता है कि छवि को पास किए गए सहेज विकल्पों द्वारा प्रतिनिधित्व किए गए निर्दिष्ट फ़ाइल फ़ॉर्मेट में सहेजा जा सकता है या नहीं। |
| [create(image_options, width, height)](#create_image_options_width_height_6) | निर्दिष्ट निर्माण विकल्पों का उपयोग करके नई छवि बनाता है। |
| [get_default_options(args)](#get_default_options_args_7) | डिफ़ॉल्ट विकल्प प्राप्त करता है। |
| [get_file_format(file_path)](#get_file_format_file_path_8) | फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [get_file_format(stream)](#get_file_format_stream_9) | फ़ाइल फ़ॉर्मेट प्राप्त करता है। |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_10) | वर्तमान छवि के अनुरूप आयत प्राप्त करता है। |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_11) | वर्तमान छवि के अनुरूप आयत प्राप्त करता है। |
| [get_original_options()](#get_original_options__12) | मूल फ़ाइल सेटिंग्स के आधार पर विकल्प प्राप्त करता है।<br/>            यह मूल छवि की बिट-गहराई और अन्य पैरामीटरों को अपरिवर्तित रखने में मददगार हो सकता है।<br/>            उदाहरण के लिए, यदि हम 1 बिट प्रति पिक्सेल वाले काले-सफ़ेद PNG छवि को लोड करते हैं और फिर इसे<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) मेथड का उपयोग करके सहेजते हैं, तो आउटपुट PNG छवि 8-बिट प्रति पिक्सेल के साथ उत्पन्न होगी।<br/>            इसे रोकने और 1-बिट प्रति पिक्सेल के साथ PNG छवि सहेजने के लिए, इस मेथड का उपयोग करके संबंधित सहेजने के विकल्प प्राप्त करें और उन्हें<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) मेथड को दूसरे पैरामीटर के रूप में पास करें। |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_13) | अनुपाती ऊँचाई प्राप्त करता है। |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_14) | अनुपाती चौड़ाई प्राप्त करता है। |
| [load(file_path)](#load_file_path_15) | निर्दिष्ट फ़ाइल से नई छवि लोड करता है। |
| [load(file_path, load_options)](#load_file_path_load_options_16) | निर्दिष्ट फ़ाइल से नई छवि लोड करता है। |
| [load(stream)](#load_stream_17) | निर्दिष्ट स्ट्रीम से नई छवि लोड करता है। |
| [load(stream, load_options)](#load_stream_load_options_18) | निर्दिष्ट स्ट्रीम से नई छवि लोड करता है। |
| [resize(new_width, new_height)](#resize_new_width_new_height_19) | छवि का आकार बदलता है। डिफ़ॉल्ट रूप से [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) उपयोग किया जाता है। |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_20) | छवि का आकार बदलता है। |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_21) | छवि का आकार बदलता है। |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_22) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_23) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_24) | ऊँचाई को अनुपातिक रूप से बदलता है। |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_25) | चौड़ाई को अनुपातिक रूप से बदलता है। डिफ़ॉल्ट रूप से [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) उपयोग किया जाता है। |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_26) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_27) | चौड़ाई को अनुपातिक रूप से बदलता है। |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_28) | छवि को घुमाता है, उलटता है, या घुमाकर उलटता है। |
| save() | छवि डेटा को अंतर्निहित स्ट्रीम में सहेजता है। |
| [save(file_path)](#save_file_path_29) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save(file_path, options)](#save_file_path_options_30) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_31) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save(file_path, over_write)](#save_file_path_over_write_32) | ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है। |
| [save(stream)](#save_stream_33) | ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम पर सहेजता है। |
| [save(stream, options_base)](#save_stream_options_base_34) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, इमेज का डेटा निर्दिष्ट स्ट्रीम पर सहेजता है। |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_35) | सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, इमेज का डेटा निर्दिष्ट स्ट्रीम पर सहेजता है। |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_36) | इमेज पैलेट सेट करता है। |


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


### Method: get_default_options(args) {#get_default_options_args_7}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_8}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_9}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_10}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_11}


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


### Method: get_original_options() {#get_original_options__12}


```
 get_original_options() 
```

मूल फ़ाइल सेटिंग्स के आधार पर विकल्प प्राप्त करता है।<br/>            यह मूल छवि की बिट-गहराई और अन्य पैरामीटरों को अपरिवर्तित रखने में मददगार हो सकता है।<br/>            उदाहरण के लिए, यदि हम 1 बिट प्रति पिक्सेल वाले काले-सफ़ेद PNG छवि को लोड करते हैं और फिर इसे<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) मेथड का उपयोग करके सहेजते हैं, तो आउटपुट PNG छवि 8-बिट प्रति पिक्सेल के साथ उत्पन्न होगी।<br/>            इसे रोकने और 1-बिट प्रति पिक्सेल के साथ PNG छवि सहेजने के लिए, इस मेथड का उपयोग करके संबंधित सहेजने के विकल्प प्राप्त करें और उन्हें<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) मेथड को दूसरे पैरामीटर के रूप में पास करें।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | मूल फ़ाइल सेटिंग्स के आधार पर विकल्प। |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_13}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_14}


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


### Method: load(file_path)  [static] {#load_file_path_15}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_16}


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


### Method: load(stream)  [static] {#load_stream_17}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_18}


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


### Method: resize(new_width, new_height) {#resize_new_width_new_height_19}


```
 resize(new_width, new_height) 
```

छवि का आकार बदलता है। डिफ़ॉल्ट रूप से [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) उपयोग किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_width | int | नई चौड़ाई। |
| new_height | int | नई ऊँचाई। |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_20}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_21}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_22}


```
 resize_height_proportionally(new_height) 
```

ऊँचाई को अनुपातिक रूप से बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_height | int | नई ऊँचाई। |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_23}


```
 resize_height_proportionally(new_height, resize_type) 
```

ऊँचाई को अनुपातिक रूप से बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_height | int | नई ऊँचाई। |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | रिसाइज़ का प्रकार। |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_24}


```
 resize_height_proportionally(new_height, settings) 
```

ऊँचाई को अनुपातिक रूप से बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_height | int | नई ऊँचाई। |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | छवि रिसाइज़ सेटिंग्स। |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_25}


```
 resize_width_proportionally(new_width) 
```

चौड़ाई को अनुपातिक रूप से बदलता है। डिफ़ॉल्ट रूप से [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) उपयोग किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_width | int | नई चौड़ाई। |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_26}


```
 resize_width_proportionally(new_width, resize_type) 
```

चौड़ाई को अनुपातिक रूप से बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_width | int | नई चौड़ाई। |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | रिसाइज़ का प्रकार। |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_27}


```
 resize_width_proportionally(new_width, settings) 
```

चौड़ाई को अनुपातिक रूप से बदलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_width | int | नई चौड़ाई। |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | छवि रिसाइज़ सेटिंग्स। |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_28}


```
 rotate_flip(rotate_flip_type) 
```

छवि को घुमाता है, उलटता है, या घुमाकर उलटता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | रोटेट फ़्लिप का प्रकार। |

### Method: save(file_path) {#save_file_path_29}


```
 save(file_path) 
```

ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | ऑब्जेक्ट के डेटा को सहेजने के लिए फ़ाइल पथ। |

### Method: save(file_path, options) {#save_file_path_options_30}


```
 save(file_path, options) 
```

सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | फ़ाइल पथ। |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | विकल्प। |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_31}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_32}


```
 save(file_path, over_write) 
```

ऑब्जेक्ट का डेटा निर्दिष्ट फ़ाइल स्थान पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_path | string | ऑब्जेक्ट के डेटा को सहेजने के लिए फ़ाइल पथ। |
| over_write | bool | यदि <c>true</c> पर सेट किया गया है तो फ़ाइल सामग्री को ओवरराइट करें, अन्यथा जोड़ दिया जाएगा। |

### Method: save(stream) {#save_stream_33}


```
 save(stream) 
```

ऑब्जेक्ट का डेटा निर्दिष्ट स्ट्रीम पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | ऑब्जेक्ट के डेटा को सहेजने के लिए स्ट्रीम। |

### Method: save(stream, options_base) {#save_stream_options_base_34}


```
 save(stream, options_base) 
```

सेव विकल्पों के अनुसार निर्दिष्ट फ़ाइल प्रारूप में, इमेज का डेटा निर्दिष्ट स्ट्रीम पर सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | छवि के डेटा को सहेजने के लिए स्ट्रीम। |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | सहेजने के विकल्प। |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_35}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_36}


```
 set_palette(palette, update_colors) 
```

इमेज पैलेट सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | सेट करने के लिए पैलेट। |
| update_colors | bool | यदि इसे <c>true</c> पर सेट किया जाता है तो रंग नई पैलेट के अनुसार अपडेट हो जाएंगे; अन्यथा रंग अनुक्रमांक अपरिवर्तित रहेंगे। ध्यान दें कि अपरिवर्तित अनुक्रमांक छवि को लोड करने पर क्रैश कर सकते हैं यदि कुछ अनुक्रमांक के लिए कोई संबंधित पैलेट प्रविष्टि नहीं है। |

