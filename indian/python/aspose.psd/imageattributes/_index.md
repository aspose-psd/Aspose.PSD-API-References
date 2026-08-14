---
title: "ImageAttributes क्लास"
type: docs
weight: 2180
url: /hi/python-net/aspose.psd/imageattributes/
---

**Summary:** An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object and pass the path of that [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) object (along with the path of an [Image](/psd/python-net/aspose.psd/image/)) to the DrawImage method.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.ImageAttributes

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [ImageAttributes()](#ImageAttributes__1) | ImageAttributes क्लास का नया उदाहरण प्रारंभ करता है |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| clear_brush_remap_table() | इस [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) ऑब्जेक्ट की ब्रश रंग-रीमैप तालिका को साफ़ करता है। |
| clear_color_key() | डिफ़ॉल्ट श्रेणी के लिए रंग कुंजी (पारदर्शिता रेंज) को साफ़ करता है। |
| [clear_color_key(type)](#clear_color_key_type_1) | निर्दिष्ट श्रेणी के लिए रंग कुंजी (पारदर्शिता रेंज) को साफ़ करता है। |
| clear_color_matrix() | डिफ़ॉल्ट श्रेणी के लिए रंग-समायोजन मैट्रिक्स को साफ़ करता है। |
| [clear_color_matrix(type)](#clear_color_matrix_type_2) | निर्दिष्ट श्रेणी के लिए रंग-समायोजन मैट्रिक्स को साफ़ करता है। |
| clear_gamma() | डिफ़ॉल्ट श्रेणी के लिए गामा सुधार को निष्क्रिय करता है। |
| [clear_gamma(type)](#clear_gamma_type_3) | निर्दिष्ट श्रेणी के लिए गामा सुधार को निष्क्रिय करता है। |
| clear_no_op() | डिफ़ॉल्ट श्रेणी के लिए NoOp सेटिंग को साफ़ करता है। |
| [clear_no_op(type)](#clear_no_op_type_4) | निर्दिष्ट श्रेणी के लिए NoOp सेटिंग को साफ़ करता है। |
| clear_output_channel() | डिफ़ॉल्ट श्रेणी के लिए CMYK (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेटिंग को साफ़ करता है। |
| [clear_output_channel(type)](#clear_output_channel_type_5) | निर्दिष्ट श्रेणी के लिए (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेटिंग को साफ़ करता है। |
| clear_output_channel_color_profile() | डिफ़ॉल्ट श्रेणी के लिए आउटपुट चैनल रंग प्रोफ़ाइल सेटिंग को साफ़ करता है। |
| [clear_output_channel_color_profile(type)](#clear_output_channel_color_profile_type_6) | निर्दिष्ट श्रेणी के लिए आउटपुट चैनल रंग प्रोफ़ाइल सेटिंग को साफ़ करता है। |
| clear_remap_table() | डिफ़ॉल्ट श्रेणी के लिए रंग-रीमैप तालिका को साफ़ करता है। |
| [clear_remap_table(type)](#clear_remap_table_type_7) | निर्दिष्ट श्रेणी के लिए रंग-रीमैप तालिका को साफ़ करता है। |
| clear_threshold() | डिफ़ॉल्ट श्रेणी के लिए थ्रेशोल्ड मान को साफ़ करता है। |
| [clear_threshold(type)](#clear_threshold_type_8) | निर्दिष्ट श्रेणी के लिए थ्रेशोल्ड मान को साफ़ करता है। |
| [set_brush_remap_table(map)](#set_brush_remap_table_map_9) | ब्रश श्रेणी के लिए रंग-रीमैप तालिका को सेट करता है। |
| [set_color_key(color_low, color_high)](#set_color_key_color_low_color_high_10) | डिफ़ॉल्ट श्रेणी के लिए रंग कुंजी सेट करता है। |
| [set_color_key(color_low, color_high, type)](#set_color_key_color_low_color_high_type_11) | निर्दिष्ट श्रेणी के लिए रंग कुंजी (पारदर्शिता सीमा) सेट करता है। |
| [set_color_matrices(new_color_matrix, gray_matrix)](#set_color_matrices_new_color_matrix_gray_matrix_12) | डिफ़ॉल्ट श्रेणी के लिए रंग-समायोजन मैट्रिक्स और ग्रेस्केल-समायोजन मैट्रिक्स सेट करता है। |
| [set_color_matrices(new_color_matrix, gray_matrix, flags)](#set_color_matrices_new_color_matrix_gray_matrix_flags_13) | डिफ़ॉल्ट श्रेणी के लिए रंग-समायोजन मैट्रिक्स और ग्रेस्केल-समायोजन मैट्रिक्स सेट करता है। |
| [set_color_matrices(new_color_matrix, gray_matrix, mode, type)](#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14) | निर्दिष्ट श्रेणी के लिए रंग-समायोजन मैट्रिक्स और ग्रेस्केल-समायोजन मैट्रिक्स सेट करता है। |
| [set_color_matrix(new_color_matrix)](#set_color_matrix_new_color_matrix_15) | डिफ़ॉल्ट श्रेणी के लिए रंग-समायोजन मैट्रिक्स सेट करता है। |
| [set_color_matrix(new_color_matrix, flags)](#set_color_matrix_new_color_matrix_flags_16) | डिफ़ॉल्ट श्रेणी के लिए रंग-समायोजन मैट्रिक्स सेट करता है। |
| [set_color_matrix(new_color_matrix, mode, type)](#set_color_matrix_new_color_matrix_mode_type_17) | निर्दिष्ट श्रेणी के लिए रंग-समायोजन मैट्रिक्स सेट करता है। |
| [set_gamma(gamma)](#set_gamma_gamma_18) | डिफ़ॉल्ट श्रेणी के लिए गामा मान सेट करता है। |
| [set_gamma(gamma, type)](#set_gamma_gamma_type_19) | निर्दिष्ट श्रेणी के लिए गामा मान सेट करता है। |
| set_no_op() | डिफ़ॉल्ट श्रेणी के लिए रंग समायोजन बंद करता है। |
| [set_no_op(type)](#set_no_op_type_20) | निर्दिष्ट श्रेणी के लिए रंग समायोजन बंद करता है। |
| [set_output_channel(flags)](#set_output_channel_flags_21) | डिफ़ॉल्ट श्रेणी के लिए CMYK (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेट करता है। |
| [set_output_channel(flags, type)](#set_output_channel_flags_type_22) | निर्दिष्ट श्रेणी के लिए CMYK (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेट करता है। |
| [set_output_channel_color_profile(color_profile_filename)](#set_output_channel_color_profile_color_profile_filename_23) | डिफ़ॉल्ट श्रेणी के लिए आउटपुट चैनल रंग-प्रोफ़ाइल फ़ाइल सेट करता है। |
| [set_output_channel_color_profile(color_profile_filename, type)](#set_output_channel_color_profile_color_profile_filename_type_24) | निर्दिष्ट श्रेणी के लिए आउटपुट चैनल रंग-प्रोफ़ाइल फ़ाइल सेट करता है। |
| [set_remap_table(map)](#set_remap_table_map_25) | डिफ़ॉल्ट श्रेणी के लिए रंग-रीमैप तालिका सेट करता है। |
| [set_remap_table(map, type)](#set_remap_table_map_type_26) | निर्दिष्ट श्रेणी के लिए रंग-रीमैप तालिका सेट करता है। |
| [set_threshold(threshold)](#set_threshold_threshold_27) | डिफ़ॉल्ट श्रेणी के लिए थ्रेशोल्ड (पारदर्शिता सीमा) सेट करता है। |
| [set_threshold(threshold, type)](#set_threshold_threshold_type_28) | निर्दिष्ट श्रेणी के लिए थ्रेशोल्ड (पारदर्शिता सीमा) सेट करता है। |
| [set_wrap_mode(mode)](#set_wrap_mode_mode_29) | रैप मोड सेट करता है जो यह तय करने के लिए उपयोग किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। जब टेक्सचर आकार से छोटा हो तो उसे भरने के लिए आकार के ऊपर टाइल किया जाता है। |
| [set_wrap_mode(mode, color)](#set_wrap_mode_mode_color_30) | रैप मोड और रंग सेट करता है जो यह तय करने के लिए उपयोग किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। जब टेक्सचर आकार से छोटा हो तो उसे भरने के लिए आकार के ऊपर टाइल किया जाता है। |
| [set_wrap_mode(mode, color, clamp)](#set_wrap_mode_mode_color_clamp_31) | रैप मोड और रंग सेट करता है जो यह तय करने के लिए उपयोग किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। जब टेक्सचर आकार से छोटा हो तो उसे भरने के लिए आकार के ऊपर टाइल किया जाता है। |


### Constructor: ImageAttributes() {#ImageAttributes__1}


```
 ImageAttributes() 
```

ImageAttributes क्लास का नया उदाहरण प्रारंभ करता है

### Method: clear_color_key(type) {#clear_color_key_type_1}


```
 clear_color_key(type) 
```

निर्दिष्ट श्रेणी के लिए रंग कुंजी (पारदर्शिता रेंज) को साफ़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | एक तत्व [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) का जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए रंग कुंजी साफ़ की जाती है। |

### Method: clear_color_matrix(type) {#clear_color_matrix_type_2}


```
 clear_color_matrix(type) 
```

निर्दिष्ट श्रेणी के लिए रंग-समायोजन मैट्रिक्स को साफ़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | एक तत्व [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) का जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए रंग-समायोजन मैट्रिक्स साफ़ किया जाता है। |

### Method: clear_gamma(type) {#clear_gamma_type_3}


```
 clear_gamma(type) 
```

निर्दिष्ट श्रेणी के लिए गामा सुधार को निष्क्रिय करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | एक तत्व [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) का जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए गामा सुधार निष्क्रिय किया गया है। |

### Method: clear_no_op(type) {#clear_no_op_type_4}


```
 clear_no_op(type) 
```

निर्दिष्ट श्रेणी के लिए NoOp सेटिंग को साफ़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | एक तत्व [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) का जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए NoOp सेटिंग साफ़ की जाती है। |

### Method: clear_output_channel(type) {#clear_output_channel_type_5}


```
 clear_output_channel(type) 
```

निर्दिष्ट श्रेणी के लिए (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेटिंग को साफ़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | एक तत्व जो [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) का है, जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए आउटपुट चैनल सेटिंग साफ़ की जाती है। |

### Method: clear_output_channel_color_profile(type) {#clear_output_channel_color_profile_type_6}


```
 clear_output_channel_color_profile(type) 
```

निर्दिष्ट श्रेणी के लिए आउटपुट चैनल रंग प्रोफ़ाइल सेटिंग को साफ़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | एक तत्व जो [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) का है, जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए आउटपुट चैनल प्रोफ़ाइल सेटिंग साफ़ की जाती है। |

### Method: clear_remap_table(type) {#clear_remap_table_type_7}


```
 clear_remap_table(type) 
```

निर्दिष्ट श्रेणी के लिए रंग-रीमैप तालिका को साफ़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | एक तत्व जो [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) का है, जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए रीमैप टेबल साफ़ की जाती है। |

### Method: clear_threshold(type) {#clear_threshold_type_8}


```
 clear_threshold(type) 
```

निर्दिष्ट श्रेणी के लिए थ्रेशोल्ड मान को साफ़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | एक तत्व जो [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) का है, जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए थ्रेशोल्ड साफ़ किया जाता है। |

### Method: set_brush_remap_table(map) {#set_brush_remap_table_map_9}


```
 set_brush_remap_table(map) 
```

ब्रश श्रेणी के लिए रंग-रीमैप तालिका को सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | [ColorMap](/psd/python-net/aspose.psd/colormap/) वस्तुओं की एक सरणी। |

### Method: set_color_key(color_low, color_high) {#set_color_key_color_low_color_high_10}


```
 set_color_key(color_low, color_high) 
```

डिफ़ॉल्ट श्रेणी के लिए रंग कुंजी सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| color_low | [Color](/psd/python-net/aspose.psd/color) | निम्न रंग-कुंजी मान। |
| color_high | [Color](/psd/python-net/aspose.psd/color) | उच्च रंग-कुंजी मान। |

### Method: set_color_key(color_low, color_high, type) {#set_color_key_color_low_color_high_type_11}


```
 set_color_key(color_low, color_high, type) 
```

निर्दिष्ट श्रेणी के लिए रंग कुंजी (पारदर्शिता सीमा) सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| color_low | [Color](/psd/python-net/aspose.psd/color) | निम्न रंग-कुंजी मान। |
| color_high | [Color](/psd/python-net/aspose.psd/color) | उच्च रंग-कुंजी मान। |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | एक तत्व जो [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) का है, जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए रंग कुंजी सेट की गई है। |

### Method: set_color_matrices(new_color_matrix, gray_matrix) {#set_color_matrices_new_color_matrix_gray_matrix_12}


```
 set_color_matrices(new_color_matrix, gray_matrix) 
```

डिफ़ॉल्ट श्रेणी के लिए रंग-समायोजन मैट्रिक्स और ग्रेस्केल-समायोजन मैट्रिक्स सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | रंग-संशोधन मैट्रिक्स। |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | ग्रेस्केल-संशोधन मैट्रिक्स। |

### Method: set_color_matrices(new_color_matrix, gray_matrix, flags) {#set_color_matrices_new_color_matrix_gray_matrix_flags_13}


```
 set_color_matrices(new_color_matrix, gray_matrix, flags) 
```

डिफ़ॉल्ट श्रेणी के लिए रंग-समायोजन मैट्रिक्स और ग्रेस्केल-समायोजन मैट्रिक्स सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | रंग-संशोधन मैट्रिक्स। |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | ग्रेस्केल-संशोधन मैट्रिक्स। |
| flags | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | एक तत्व जो [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) का है, जो उस छवि और रंग के प्रकार को निर्दिष्ट करता है जो रंग-संशोधन और ग्रेस्केल-संशोधन मैट्रिक्स द्वारा प्रभावित होगा। |

### Method: set_color_matrices(new_color_matrix, gray_matrix, mode, type) {#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14}


```
 set_color_matrices(new_color_matrix, gray_matrix, mode, type) 
```

निर्दिष्ट श्रेणी के लिए रंग-समायोजन मैट्रिक्स और ग्रेस्केल-समायोजन मैट्रिक्स सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | रंग-संशोधन मैट्रिक्स। |
| gray_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | ग्रेस्केल-संशोधन मैट्रिक्स। |
| mode | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | एक तत्व जो [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) का है, जो उस छवि और रंग के प्रकार को निर्दिष्ट करता है जो रंग-संशोधन और ग्रेस्केल-संशोधन मैट्रिक्स द्वारा प्रभावित होगा। |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | एक तत्व जो [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) का है, जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए रंग-संशोधन और ग्रेस्केल-संशोधन मैट्रिक्स सेट किए गए हैं। |

### Method: set_color_matrix(new_color_matrix) {#set_color_matrix_new_color_matrix_15}


```
 set_color_matrix(new_color_matrix) 
```

डिफ़ॉल्ट श्रेणी के लिए रंग-समायोजन मैट्रिक्स सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | रंग-संशोधन मैट्रिक्स। |

### Method: set_color_matrix(new_color_matrix, flags) {#set_color_matrix_new_color_matrix_flags_16}


```
 set_color_matrix(new_color_matrix, flags) 
```

डिफ़ॉल्ट श्रेणी के लिए रंग-समायोजन मैट्रिक्स सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | रंग-संशोधन मैट्रिक्स। |
| flags | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | एक तत्व जो [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) का है, जो उस छवि और रंग के प्रकार को निर्दिष्ट करता है जो रंग-संशोधन मैट्रिक्स द्वारा प्रभावित होगा। |

### Method: set_color_matrix(new_color_matrix, mode, type) {#set_color_matrix_new_color_matrix_mode_type_17}


```
 set_color_matrix(new_color_matrix, mode, type) 
```

निर्दिष्ट श्रेणी के लिए रंग-समायोजन मैट्रिक्स सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/psd/python-net/aspose.psd/colormatrix) | रंग-संशोधन मैट्रिक्स। |
| mode | [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag) | एक तत्व जो [ColorMatrixFlag](/psd/python-net/aspose.psd/colormatrixflag/) का है, जो उस छवि और रंग के प्रकार को निर्दिष्ट करता है जो रंग-संशोधन मैट्रिक्स द्वारा प्रभावित होगा। |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | एक तत्व जो [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) का है, जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए रंग-संशोधन मैट्रिक्स सेट किया गया है। |

### Method: set_gamma(gamma) {#set_gamma_gamma_18}


```
 set_gamma(gamma) 
```

डिफ़ॉल्ट श्रेणी के लिए गामा मान सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| गामा | float | गामा सुधार मान। |

### Method: set_gamma(gamma, type) {#set_gamma_gamma_type_19}


```
 set_gamma(gamma, type) 
```

निर्दिष्ट श्रेणी के लिए गामा मान सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| गामा | float | गामा सुधार मान। |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) enumeration का एक तत्व, जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए गामा मान सेट किया गया है। |

### Method: set_no_op(type) {#set_no_op_type_20}


```
 set_no_op(type) 
```

निर्दिष्ट श्रेणी के लिए रंग समायोजन बंद करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | एक तत्व जो [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) का है, जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए रंग सुधार बंद किया गया है। |

### Method: set_output_channel(flags) {#set_output_channel_flags_21}


```
 set_output_channel(flags) 
```

डिफ़ॉल्ट श्रेणी के लिए CMYK (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| flags | [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag) | एक तत्व जो [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) का है, जो आउटपुट चैनल को निर्दिष्ट करता है। |

### Method: set_output_channel(flags, type) {#set_output_channel_flags_type_22}


```
 set_output_channel(flags, type) 
```

निर्दिष्ट श्रेणी के लिए CMYK (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| flags | [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag) | एक तत्व जो [ColorChannelFlag](/psd/python-net/aspose.psd/colorchannelflag/) का है, जो आउटपुट चैनल को निर्दिष्ट करता है। |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | एक तत्व जो [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) का है, जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए आउटपुट चैनल सेट किया गया है। |

### Method: set_output_channel_color_profile(color_profile_filename) {#set_output_channel_color_profile_color_profile_filename_23}


```
 set_output_channel_color_profile(color_profile_filename) 
```

डिफ़ॉल्ट श्रेणी के लिए आउटपुट चैनल रंग-प्रोफ़ाइल फ़ाइल सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| color_profile_filename | string | एक रंग-प्रोफ़ाइल फ़ाइल का पथनाम। यदि रंग-प्रोफ़ाइल फ़ाइल %SystemRoot%\System32\Spool\Drivers\Color निर्देशिका में है, तो यह पैरामीटर फ़ाइल नाम हो सकता है। अन्यथा, इस पैरामीटर को पूर्ण योग्य पथनाम होना चाहिए। |

### Method: set_output_channel_color_profile(color_profile_filename, type) {#set_output_channel_color_profile_color_profile_filename_type_24}


```
 set_output_channel_color_profile(color_profile_filename, type) 
```

निर्दिष्ट श्रेणी के लिए आउटपुट चैनल रंग-प्रोफ़ाइल फ़ाइल सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| color_profile_filename | string | एक रंग-प्रोफ़ाइल फ़ाइल का पथनाम। यदि रंग-प्रोफ़ाइल फ़ाइल %SystemRoot%\System32\Spool\Drivers\Color निर्देशिका में है, तो यह पैरामीटर फ़ाइल नाम हो सकता है। अन्यथा, इस पैरामीटर को पूर्ण योग्य पथनाम होना चाहिए। |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | एक तत्व जो [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) का है, जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए आउटपुट चैनल रंग-प्रोफ़ाइल फ़ाइल सेट की गई है। |

### Method: set_remap_table(map) {#set_remap_table_map_25}


```
 set_remap_table(map) 
```

डिफ़ॉल्ट श्रेणी के लिए रंग-रीमैप तालिका सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | [ColorMap](/psd/python-net/aspose.psd/colormap/) प्रकार के रंग जोड़ों की एक सरणी। प्रत्येक रंग जोड़ा एक मौजूदा रंग (पहला मान) और वह रंग जिसमें इसे मैप किया जाएगा (दूसरा मान) रखता है। |

### Method: set_remap_table(map, type) {#set_remap_table_map_type_26}


```
 set_remap_table(map, type) 
```

निर्दिष्ट श्रेणी के लिए रंग-रीमैप तालिका सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| map | [ColorMap[]](/psd/python-net/aspose.psd/colormap) | [ColorMap](/psd/python-net/aspose.psd/colormap/) प्रकार के रंग जोड़ों की एक सरणी। प्रत्येक रंग जोड़ा एक मौजूदा रंग (पहला मान) और वह रंग जिसमें इसे मैप किया जाएगा (दूसरा मान) रखता है। |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | एक तत्व जो [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) का है, जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए रंग-रीमैप टेबल सेट की गई है। |

### Method: set_threshold(threshold) {#set_threshold_threshold_27}


```
 set_threshold(threshold) 
```

डिफ़ॉल्ट श्रेणी के लिए थ्रेशोल्ड (पारदर्शिता सीमा) सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| थ्रेशोल्ड | float | एक वास्तविक संख्या जो थ्रेशोल्ड मान को निर्दिष्ट करती है। |

### Method: set_threshold(threshold, type) {#set_threshold_threshold_type_28}


```
 set_threshold(threshold, type) 
```

निर्दिष्ट श्रेणी के लिए थ्रेशोल्ड (पारदर्शिता सीमा) सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| थ्रेशोल्ड | float | 0.0 से 1.0 तक का एक थ्रेशहोल्ड मान जो रंगों को क्रमबद्ध करने के लिए ब्रेकपॉइंट के रूप में उपयोग किया जाता है, जिसे अधिकतम या न्यूनतम मान में मैप किया जाएगा। |
| type | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype) | [ColorAdjustType](/psd/python-net/aspose.psd/coloradjusttype/) का एक तत्व जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए रंग थ्रेशहोल्ड सेट किया जाता है। |

### Method: set_wrap_mode(mode) {#set_wrap_mode_mode_29}


```
 set_wrap_mode(mode) 
```

रैप मोड सेट करता है जो यह तय करने के लिए उपयोग किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। जब टेक्सचर आकार से छोटा हो तो उसे भरने के लिए आकार के ऊपर टाइल किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | [WrapMode](/psd/python-net/aspose.psd/wrapmode/) का एक तत्व जो यह निर्दिष्ट करता है कि छवि की दोहराई गई प्रतियों का उपयोग क्षेत्र को टाइल करने के लिए कैसे किया जाता है। |

### Method: set_wrap_mode(mode, color) {#set_wrap_mode_mode_color_30}


```
 set_wrap_mode(mode, color) 
```

रैप मोड और रंग सेट करता है जो यह तय करने के लिए उपयोग किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। जब टेक्सचर आकार से छोटा हो तो उसे भरने के लिए आकार के ऊपर टाइल किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | [WrapMode](/psd/python-net/aspose.psd/wrapmode/) का एक तत्व जो यह निर्दिष्ट करता है कि छवि की दोहराई गई प्रतियों का उपयोग क्षेत्र को टाइल करने के लिए कैसे किया जाता है। |
| color | [Color](/psd/python-net/aspose.psd/color) | [ImageAttributes](/psd/python-net/aspose.psd/imageattributes/) ऑब्जेक्ट जो रेंडर की गई छवि के बाहर पिक्सेल के रंग को निर्दिष्ट करता है। यह रंग दिखाई देता है यदि मोड पैरामीटर को [WrapMode.CLAMP](/psd/python-net/aspose.psd/wrapmode/) पर सेट किया गया हो और DrawImage को पास किया गया स्रोत आयत छवि से बड़ी हो। |

### Method: set_wrap_mode(mode, color, clamp) {#set_wrap_mode_mode_color_clamp_31}


```
 set_wrap_mode(mode, color, clamp) 
```

रैप मोड और रंग सेट करता है जो यह तय करने के लिए उपयोग किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। जब टेक्सचर आकार से छोटा हो तो उसे भरने के लिए आकार के ऊपर टाइल किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| mode | [WrapMode](/psd/python-net/aspose.psd/wrapmode) | [WrapMode](/psd/python-net/aspose.psd/wrapmode/) का एक तत्व जो यह निर्दिष्ट करता है कि छवि की दोहराई गई प्रतियों का उपयोग क्षेत्र को टाइल करने के लिए कैसे किया जाता है। |
| color | [Color](/psd/python-net/aspose.psd/color) | एक रंग ऑब्जेक्ट जो रेंडर की गई छवि के बाहर पिक्सेल के रंग को निर्दिष्ट करता है। यह रंग तभी दिखाई देता है जब मोड पैरामीटर को [WrapMode.CLAMP](/psd/python-net/aspose.psd/wrapmode/) पर सेट किया गया हो और DrawImage को पास किया गया स्रोत आयत छवि से बड़ी हो। |
| क्लैंप | bool | इस पैरामीटर का कोई प्रभाव नहीं है। इसे false पर सेट करें। |

