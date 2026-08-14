---
title: "GraphicsPath क्लास"
type: docs
weight: 1570
url: /hi/python-net/aspose.psd/graphicspath/
---

**Summary:** Represents a series of connected lines and curves. This class cannot be inherited.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.GraphicsPath

**Inheritance:** ObjectWithBounds

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **विवरण** |
| :- | :- |
| [GraphicsPath()](#GraphicsPath__1) | एक नया इंस्टेंस प्रारंभ करता है [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) क्लास का। |
| [GraphicsPath(figures)](#GraphicsPath_figures_2) | एक नया इंस्टेंस प्रारंभ करता है [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) क्लास का। |
| [GraphicsPath(figures, fill_mode)](#GraphicsPath_figures_fill_mode_3) | एक नया इंस्टेंस प्रारंभ करता है [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) क्लास का। |
| [GraphicsPath(fill_mode)](#GraphicsPath_fill_mode_4) | एक नया इंस्टेंस प्रारंभ करता है [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) क्लास का। |
## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| bounds | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | r | ऑब्जेक्ट की सीमाओं को प्राप्त करता है या सेट करता है। |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | r | पाथ फ़िगर्स को प्राप्त करता है। |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | r/w | इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) में आकारों के अंदरूनी हिस्सों को भरने के तरीके को निर्धारित करने वाला एक [FillMode](/psd/python-net/aspose.psd/fillmode/) enumeration प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [add_figure(figure)](#add_figure_figure_1) | एक नया आकृति जोड़ता है। |
| [add_figures(figures)](#add_figures_figures_2) | नए आकृतियों को जोड़ता है। |
| [add_path(adding_path)](#add_path_adding_path_3) | निर्दिष्ट [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) को इस पथ में जोड़ता है। |
| [add_path(adding_path, connect)](#add_path_adding_path_connect_4) | निर्दिष्ट [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) को इस पथ में जोड़ता है। |
| [deep_clone()](#deep_clone__5) | इस ग्राफ़िक्स पथ की गहरी क्लोन बनाता है। |
| flatten() | इस पथ में प्रत्येक वक्र को जुड़े हुए रेखा खंडों की श्रृंखला में परिवर्तित करता है। |
| [flatten(matrix)](#flatten_matrix_6) | निर्दिष्ट ट्रांसफ़ॉर्म लागू करता है और फिर इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) में प्रत्येक वक्र को जुड़े हुए रेखा खंडों की श्रृंखला में परिवर्तित करता है। |
| [flatten(matrix, flatness)](#flatten_matrix_flatness_7) | इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) में प्रत्येक वक्र को जुड़े हुए रेखा खंडों की श्रृंखला में परिवर्तित करता है। |
| [get_bounds(matrix)](#get_bounds_matrix_8) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [get_bounds(matrix, pen)](#get_bounds_matrix_pen_9) | ऑब्जेक्ट की सीमाएँ प्राप्त करता है। |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_10) | निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) की रूपरेखा (के नीचे) में शामिल है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [Pen](/psd/python-net/aspose.psd/pen/) से खींचा जाता है। |
| [is_outline_visible(point, pen)](#is_outline_visible_point_pen_11) | निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) की रूपरेखा (के नीचे) में शामिल है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [Pen](/psd/python-net/aspose.psd/pen/) से खींचा जाता है। |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_12) | निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) की रूपरेखा (के नीचे) में शामिल है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [Pen](/psd/python-net/aspose.psd/pen/) से खींचा जाता है और निर्दिष्ट [Graphics](/psd/python-net/aspose.psd/graphics/) का उपयोग किया जाता है। |
| [is_outline_visible(pt, pen, graphics)](#is_outline_visible_pt_pen_graphics_13) | निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) की रूपरेखा (के नीचे) में शामिल है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [Pen](/psd/python-net/aspose.psd/pen/) से खींचा जाता है और निर्दिष्ट [Graphics](/psd/python-net/aspose.psd/graphics/) का उपयोग किया जाता है। |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_14) | निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) की रूपरेखा (के नीचे) में शामिल है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [Pen](/psd/python-net/aspose.psd/pen/) से खींचा जाता है। |
| [is_outline_visible(x, y, pen)](#is_outline_visible_x_y_pen_15) | निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) की रूपरेखा (के नीचे) में शामिल है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [Pen](/psd/python-net/aspose.psd/pen/) से खींचा जाता है। |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_16) | निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) की रूपरेखा (के नीचे) में शामिल है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [Pen](/psd/python-net/aspose.psd/pen/) से खींचा जाता है और निर्दिष्ट [Graphics](/psd/python-net/aspose.psd/graphics/) का उपयोग किया जाता है। |
| [is_outline_visible(x, y, pen, graphics)](#is_outline_visible_x_y_pen_graphics_17) | निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) की रूपरेखा (के नीचे) में शामिल है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [Pen](/psd/python-net/aspose.psd/pen/) से खींचा जाता है और निर्दिष्ट [Graphics](/psd/python-net/aspose.psd/graphics/) का उपयोग किया जाता है। |
| [is_visible(point)](#is_visible_point_18) | निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर शामिल है या नहीं, यह दर्शाता है। |
| [is_visible(point)](#is_visible_point_19) | निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर शामिल है या नहीं, यह दर्शाता है। |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_20) | निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर शामिल है या नहीं, यह दर्शाता है। |
| [is_visible(pt, graphics)](#is_visible_pt_graphics_21) | निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर शामिल है या नहीं, यह दर्शाता है। |
| [is_visible(x, y)](#is_visible_x_y_22) | निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर शामिल है या नहीं, यह दर्शाता है। |
| [is_visible(x, y)](#is_visible_x_y_23) | निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर शामिल है या नहीं, यह दर्शाता है। |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_24) | निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर, निर्दिष्ट [Graphics](/psd/python-net/aspose.psd/graphics/) के दृश्यमान क्लिप क्षेत्र में, शामिल है या नहीं, यह दर्शाता है। |
| [is_visible(x, y, graphics)](#is_visible_x_y_graphics_25) | निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर, निर्दिष्ट [Graphics](/psd/python-net/aspose.psd/graphics/) के दृश्यमान क्लिप क्षेत्र में, शामिल है या नहीं, यह दर्शाता है। |
| [remove_figure(figure)](#remove_figure_figure_26) | एक आकृति हटाता है। |
| [remove_figures(figures)](#remove_figures_figures_27) | आकृतियों को हटाता है। |
| reset() | ग्राफ़िक्स पथ को खाली करता है और [FillMode](/psd/python-net/aspose.psd/fillmode/) को [FillMode.ALTERNATE](/psd/python-net/aspose.psd/fillmode/) पर सेट करता है। |
| reverse() | इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के प्रत्येक आकार में आकृतियों, आकारों और बिंदुओं का क्रम उलट देता है। |
| [transform(transform)](#transform_transform_28) | निर्दिष्ट परिवर्तन को आकार पर लागू करता है। |
| [warp(dest_points, src_rect)](#warp_dest_points_src_rect_29) | एक आयत और समानांतर चतुर्भुज द्वारा परिभाषित वार्प ट्रांसफ़ॉर्म को इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) पर लागू करता है। |
| [warp(dest_points, src_rect, matrix)](#warp_dest_points_src_rect_matrix_30) | एक आयत और समानांतर चतुर्भुज द्वारा परिभाषित वार्प ट्रांसफ़ॉर्म को इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) पर लागू करता है। |
| [warp(dest_points, src_rect, matrix, warp_mode)](#warp_dest_points_src_rect_matrix_warp_mode_31) | एक आयत और समानांतर चतुर्भुज द्वारा परिभाषित वार्प ट्रांसफ़ॉर्म को इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) पर लागू करता है। |
| [warp(dest_points, src_rect, matrix, warp_mode, flatness)](#warp_dest_points_src_rect_matrix_warp_mode_flatness_32) | एक आयत और समानांतर चतुर्भुज द्वारा परिभाषित वार्प ट्रांसफ़ॉर्म को इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) पर लागू करता है। |
| [widen(pen)](#widen_pen_33) | पथ में एक अतिरिक्त रूपरेखा जोड़ता है। |
| [widen(pen, matrix)](#widen_pen_matrix_34) | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) में एक अतिरिक्त रूपरेखा जोड़ता है। |
| [widen(pen, matrix, flatness)](#widen_pen_matrix_flatness_35) | इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) को उन वक्रों से बदलता है जो उस क्षेत्र को घेरते हैं जो निर्दिष्ट पेन द्वारा इस पथ को खींचे जाने पर भरा जाता है। |


### Constructor: GraphicsPath() {#GraphicsPath__1}


```
 GraphicsPath() 
```

एक नया इंस्टेंस प्रारंभ करता है [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) क्लास का।

### Constructor: GraphicsPath(figures) {#GraphicsPath_figures_2}


```
 GraphicsPath(figures) 
```

एक नया इंस्टेंस प्रारंभ करता है [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | आरंभ करने के लिए आकृतियाँ। |

### Constructor: GraphicsPath(figures, fill_mode) {#GraphicsPath_figures_fill_mode_3}


```
 GraphicsPath(figures, fill_mode) 
```

एक नया इंस्टेंस प्रारंभ करता है [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | आरंभ करने के लिए आकृतियाँ। |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | भरण मोड। |

### Constructor: GraphicsPath(fill_mode) {#GraphicsPath_fill_mode_4}


```
 GraphicsPath(fill_mode) 
```

एक नया इंस्टेंस प्रारंभ करता है [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| fill_mode | [FillMode](/psd/python-net/aspose.psd/fillmode) | भरण मोड। |

### Method: add_figure(figure) {#add_figure_figure_1}


```
 add_figure(figure) 
```

एक नया आकृति जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | जोड़ने के लिए आकृति। |

### Method: add_figures(figures) {#add_figures_figures_2}


```
 add_figures(figures) 
```

नए आकृतियों को जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | जोड़ने के लिए आकृतियाँ। |

### Method: add_path(adding_path) {#add_path_adding_path_3}


```
 add_path(adding_path) 
```

निर्दिष्ट [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) को इस पथ में जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | जोड़ने के लिए [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) |

### Method: add_path(adding_path, connect) {#add_path_adding_path_connect_4}


```
 add_path(adding_path, connect) 
```

निर्दिष्ट [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) को इस पथ में जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| adding_path | [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | जोड़ने के लिए [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) |
| जोड़ें | bool | एक बूलियन मान जो यह निर्दिष्ट करता है कि जोड़ी गई पथ में पहला आकृति इस पथ में अंतिम आकृति का हिस्सा है या नहीं। true मान का अर्थ है कि जोड़ी गई पथ में पहला आकृति इस पथ में अंतिम आकृति का हिस्सा है। false मान का अर्थ है कि जोड़ी गई पथ में पहला आकृति इस पथ में अंतिम आकृति से अलग है। |

### Method: deep_clone() {#deep_clone__5}


```
 deep_clone() 
```

इस ग्राफ़िक्स पथ की गहरी क्लोन बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [GraphicsPath](/psd/python-net/aspose.psd/graphicspath) | ग्राफ़िक्स पथ की एक डीप क्लोन। |


### Method: flatten(matrix) {#flatten_matrix_6}


```
 flatten(matrix) 
```

निर्दिष्ट ट्रांसफ़ॉर्म लागू करता है और फिर इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) में प्रत्येक वक्र को जुड़े हुए रेखा खंडों की श्रृंखला में परिवर्तित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | फ़्लैटनिंग से पहले इस [GraphicsPath] को बदलने के लिए एक [Matrix](/psd/python-net/aspose.psd/matrix/)। |

### Method: flatten(matrix, flatness) {#flatten_matrix_flatness_7}


```
 flatten(matrix, flatness) 
```

इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) में प्रत्येक वक्र को जुड़े हुए रेखा खंडों की श्रृंखला में परिवर्तित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | फ़्लैटनिंग से पहले इस [GraphicsPath] को बदलने के लिए एक [Matrix](/psd/python-net/aspose.psd/matrix/)। |
| समतलता | float | वक्र और उसके फ़्लैटन किए गए अनुमान के बीच अधिकतम अनुमत त्रुटि को निर्दिष्ट करता है। डिफ़ॉल्ट मान 0.25 है। समतलता मान को कम करने से अनुमान में रेखा खंडों की संख्या बढ़ेगी। |

### Method: get_bounds(matrix) {#get_bounds_matrix_8}


```
 get_bounds(matrix) 
```

ऑब्जेक्ट की सीमाएँ प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | सीमाओं से पहले लागू करने के लिए मैट्रिक्स की गणना की जाएगी। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | अनुमानित ऑब्जेक्ट की सीमाएँ। |


### Method: get_bounds(matrix, pen) {#get_bounds_matrix_pen_9}


```
 get_bounds(matrix, pen) 
```

ऑब्जेक्ट की सीमाएँ प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | सीमाओं से पहले लागू करने के लिए मैट्रिक्स की गणना की जाएगी। |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | ऑब्जेक्ट के लिए उपयोग करने वाला पेन। यह ऑब्जेक्ट की सीमाओं के आकार को प्रभावित कर सकता है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [RectangleF](/psd/python-net/aspose.psd/rectanglef) | अनुमानित ऑब्जेक्ट की सीमाएँ। |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_10}


```
 is_outline_visible(point, pen) 
```

निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) की रूपरेखा (के नीचे) में शामिल है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [Pen](/psd/python-net/aspose.psd/pen/) से खींचा जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | परीक्षण के स्थान को निर्दिष्ट करने वाला एक [PointF](/psd/python-net/aspose.psd/pointf/)। |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | परीक्षण के लिए [Pen](/psd/python-net/aspose.psd/pen/)। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस [GraphicsPath] की रूपरेखा के भीतर स्थित है जब निर्दिष्ट [Pen] के साथ खींचा गया हो; अन्यथा false। |


### Method: is_outline_visible(point, pen) {#is_outline_visible_point_pen_11}


```
 is_outline_visible(point, pen) 
```

निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) की रूपरेखा (के नीचे) में शामिल है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [Pen](/psd/python-net/aspose.psd/pen/) से खींचा जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | परीक्षण के स्थान को निर्दिष्ट करने वाला एक [PointF](/psd/python-net/aspose.psd/pointf/)। |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | परीक्षण के लिए [Pen](/psd/python-net/aspose.psd/pen/)। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस [GraphicsPath] की रूपरेखा के भीतर स्थित है जब निर्दिष्ट [Pen] के साथ खींचा गया हो; अन्यथा false। |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_12}


```
 is_outline_visible(pt, pen, graphics) 
```

निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) की रूपरेखा (के नीचे) में शामिल है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [Pen](/psd/python-net/aspose.psd/pen/) से खींचा जाता है और निर्दिष्ट [Graphics](/psd/python-net/aspose.psd/graphics/) का उपयोग किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | परीक्षण के स्थान को निर्दिष्ट करने वाला एक [PointF](/psd/python-net/aspose.psd/pointf/)। |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | परीक्षण के लिए [Pen](/psd/python-net/aspose.psd/pen/)। |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | जिस [Graphics](/psd/python-net/aspose.psd/graphics/) की दृश्यता का परीक्षण करना है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस [GraphicsPath] की रूपरेखा के भीतर (नीचे) स्थित है जब निर्दिष्ट [Pen] के साथ खींचा गया हो; अन्यथा false। |


### Method: is_outline_visible(pt, pen, graphics) {#is_outline_visible_pt_pen_graphics_13}


```
 is_outline_visible(pt, pen, graphics) 
```

निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) की रूपरेखा (के नीचे) में शामिल है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [Pen](/psd/python-net/aspose.psd/pen/) से खींचा जाता है और निर्दिष्ट [Graphics](/psd/python-net/aspose.psd/graphics/) का उपयोग किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | परीक्षण के स्थान को निर्दिष्ट करने वाला एक [PointF](/psd/python-net/aspose.psd/pointf/)। |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | परीक्षण के लिए [Pen](/psd/python-net/aspose.psd/pen/)। |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | जिस [Graphics](/psd/python-net/aspose.psd/graphics/) की दृश्यता का परीक्षण करना है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस [GraphicsPath] की रूपरेखा के भीतर (नीचे) स्थित है जब निर्दिष्ट [Pen] के साथ खींचा गया हो; अन्यथा false। |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_14}


```
 is_outline_visible(x, y, pen) 
```

निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) की रूपरेखा (के नीचे) में शामिल है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [Pen](/psd/python-net/aspose.psd/pen/) से खींचा जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | float | परीक्षण के बिंदु का x-निर्देशांक। |
| y | float | परीक्षण के बिंदु का y-निर्देशांक। |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | परीक्षण के लिए [Pen](/psd/python-net/aspose.psd/pen/)। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस [GraphicsPath] की रूपरेखा के भीतर स्थित है जब निर्दिष्ट [Pen] के साथ खींचा गया हो; अन्यथा false। |


### Method: is_outline_visible(x, y, pen) {#is_outline_visible_x_y_pen_15}


```
 is_outline_visible(x, y, pen) 
```

निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) की रूपरेखा (के नीचे) में शामिल है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [Pen](/psd/python-net/aspose.psd/pen/) से खींचा जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | int | परीक्षण के बिंदु का x-निर्देशांक। |
| y | int | परीक्षण के बिंदु का y-निर्देशांक। |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | परीक्षण के लिए [Pen](/psd/python-net/aspose.psd/pen/)। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस [GraphicsPath] की रूपरेखा के भीतर स्थित है जब निर्दिष्ट [Pen] के साथ खींचा गया हो; अन्यथा false। |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_16}


```
 is_outline_visible(x, y, pen, graphics) 
```

निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) की रूपरेखा (के नीचे) में शामिल है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [Pen](/psd/python-net/aspose.psd/pen/) से खींचा जाता है और निर्दिष्ट [Graphics](/psd/python-net/aspose.psd/graphics/) का उपयोग किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | float | परीक्षण के बिंदु का x-निर्देशांक। |
| y | float | परीक्षण के बिंदु का y-निर्देशांक। |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | परीक्षण के लिए [Pen](/psd/python-net/aspose.psd/pen/)। |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | जिस [Graphics](/psd/python-net/aspose.psd/graphics/) की दृश्यता का परीक्षण करना है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस [GraphicsPath] की रूपरेखा के भीतर (नीचे) स्थित है जब निर्दिष्ट [Pen] के साथ खींचा गया हो; अन्यथा false। |


### Method: is_outline_visible(x, y, pen, graphics) {#is_outline_visible_x_y_pen_graphics_17}


```
 is_outline_visible(x, y, pen, graphics) 
```

निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) की रूपरेखा (के नीचे) में शामिल है या नहीं, यह दर्शाता है जब इसे निर्दिष्ट [Pen](/psd/python-net/aspose.psd/pen/) से खींचा जाता है और निर्दिष्ट [Graphics](/psd/python-net/aspose.psd/graphics/) का उपयोग किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | int | परीक्षण के बिंदु का x-निर्देशांक। |
| y | int | परीक्षण के बिंदु का y-निर्देशांक। |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | परीक्षण के लिए [Pen](/psd/python-net/aspose.psd/pen/)। |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | जिस [Graphics](/psd/python-net/aspose.psd/graphics/) की दृश्यता का परीक्षण करना है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस [GraphicsPath] की रूपरेखा के भीतर (नीचे) स्थित है जब निर्दिष्ट [Pen] के साथ खींचा गया हो; अन्यथा false। |


### Method: is_visible(point) {#is_visible_point_18}


```
 is_visible(point) 
```

निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर शामिल है या नहीं, यह दर्शाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | [PointF](/psd/python-net/aspose.psd/pointf) | परीक्षण के बिंदु को दर्शाने वाला एक [PointF](/psd/python-net/aspose.psd/pointf/)। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर स्थित है; अन्यथा false। |


### Method: is_visible(point) {#is_visible_point_19}


```
 is_visible(point) 
```

निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर शामिल है या नहीं, यह दर्शाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | [Point](/psd/python-net/aspose.psd/point) | परीक्षण के बिंदु को दर्शाने वाला एक [PointF](/psd/python-net/aspose.psd/pointf/)। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर स्थित है; अन्यथा false। |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_20}


```
 is_visible(pt, graphics) 
```

निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर शामिल है या नहीं, यह दर्शाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pt | [PointF](/psd/python-net/aspose.psd/pointf) | परीक्षण के बिंदु को दर्शाने वाला एक [PointF](/psd/python-net/aspose.psd/pointf/)। |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | जिस [Graphics](/psd/python-net/aspose.psd/graphics/) की दृश्यता का परीक्षण करना है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इसके भीतर स्थित है; अन्यथा false। |


### Method: is_visible(pt, graphics) {#is_visible_pt_graphics_21}


```
 is_visible(pt, graphics) 
```

निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर शामिल है या नहीं, यह दर्शाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pt | [Point](/psd/python-net/aspose.psd/point) | परीक्षण के बिंदु को दर्शाने वाला एक [PointF](/psd/python-net/aspose.psd/pointf/)। |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | जिस [Graphics](/psd/python-net/aspose.psd/graphics/) की दृश्यता का परीक्षण करना है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इसके भीतर स्थित है; अन्यथा false। |


### Method: is_visible(x, y) {#is_visible_x_y_22}


```
 is_visible(x, y) 
```

निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर शामिल है या नहीं, यह दर्शाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | float | परीक्षण के बिंदु का x-निर्देशांक। |
| y | float | परीक्षण के बिंदु का y-निर्देशांक। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर स्थित है; अन्यथा false। |


### Method: is_visible(x, y) {#is_visible_x_y_23}


```
 is_visible(x, y) 
```

निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर शामिल है या नहीं, यह दर्शाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | int | परीक्षण के बिंदु का x-निर्देशांक। |
| y | int | परीक्षण के बिंदु का y-निर्देशांक। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर स्थित है; अन्यथा false। |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_24}


```
 is_visible(x, y, graphics) 
```

निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर, निर्दिष्ट [Graphics](/psd/python-net/aspose.psd/graphics/) के दृश्यमान क्लिप क्षेत्र में, शामिल है या नहीं, यह दर्शाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | float | परीक्षण के बिंदु का x-निर्देशांक। |
| y | float | परीक्षण के बिंदु का y-निर्देशांक। |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | जिस [Graphics](/psd/python-net/aspose.psd/graphics/) की दृश्यता का परीक्षण करना है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर स्थित है; अन्यथा false। |


### Method: is_visible(x, y, graphics) {#is_visible_x_y_graphics_25}


```
 is_visible(x, y, graphics) 
```

निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर, निर्दिष्ट [Graphics](/psd/python-net/aspose.psd/graphics/) के दृश्यमान क्लिप क्षेत्र में, शामिल है या नहीं, यह दर्शाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | int | परीक्षण के बिंदु का x-निर्देशांक। |
| y | int | परीक्षण के बिंदु का y-निर्देशांक। |
| graphics | [Graphics](/psd/python-net/aspose.psd/graphics) | जिस [Graphics](/psd/python-net/aspose.psd/graphics/) की दृश्यता का परीक्षण करना है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यह विधि true लौटाती है यदि निर्दिष्ट बिंदु इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) के भीतर स्थित है; अन्यथा false। |


### Method: remove_figure(figure) {#remove_figure_figure_26}


```
 remove_figure(figure) 
```

एक आकृति हटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| figure | [Figure](/psd/python-net/aspose.psd/figure) | हटाने के लिए आकृति। |

### Method: remove_figures(figures) {#remove_figures_figures_27}


```
 remove_figures(figures) 
```

आकृतियों को हटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| figures | [Figure[]](/psd/python-net/aspose.psd/figure) | हटाने के लिए आकृतियाँ। |

### Method: transform(transform) {#transform_transform_28}


```
 transform(transform) 
```

निर्दिष्ट परिवर्तन को आकार पर लागू करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| transform | [Matrix](/psd/python-net/aspose.psd/matrix) | लागू करने के लिए परिवर्तन। |

### Method: warp(dest_points, src_rect) {#warp_dest_points_src_rect_29}


```
 warp(dest_points, src_rect) 
```

एक आयत और समानांतर चतुर्भुज द्वारा परिभाषित वार्प ट्रांसफ़ॉर्म को इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) पर लागू करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | एक [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती है, जिसमें वह आयत <paramref name="srcRect" /> द्वारा परिभाषित है, जिसे परिवर्तित किया जाता है। सरणी में तीन या चार तत्व हो सकते हैं। यदि सरणी में तीन तत्व हैं, तो समानांतर चतुर्भुज का निचला-दायाँ कोना पहले तीन बिंदुओं द्वारा निर्धारित किया जाता है। |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) जो उस आयत को दर्शाता है जिसे <paramref name="destPoints" /> द्वारा परिभाषित समानांतर चतुर्भुज में परिवर्तित किया जाता है। |

### Method: warp(dest_points, src_rect, matrix) {#warp_dest_points_src_rect_matrix_30}


```
 warp(dest_points, src_rect, matrix) 
```

एक आयत और समानांतर चतुर्भुज द्वारा परिभाषित वार्प ट्रांसफ़ॉर्म को इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) पर लागू करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | एक [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती है, जिसमें वह आयत <paramref name="srcRect" /> द्वारा परिभाषित है, जिसे परिवर्तित किया जाता है। सरणी में तीन या चार तत्व हो सकते हैं। यदि सरणी में तीन तत्व हैं, तो समानांतर चतुर्भुज का निचला-दायाँ कोना पहले तीन बिंदुओं द्वारा निर्धारित किया जाता है। |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) जो उस आयत को दर्शाता है जिसे <paramref name="destPoints" /> द्वारा परिभाषित समानांतर चतुर्भुज में परिवर्तित किया जाता है। |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | एक [Matrix](/psd/python-net/aspose.psd/matrix/) जो पथ पर लागू करने के लिए ज्यामितीय परिवर्तन निर्दिष्ट करता है। |

### Method: warp(dest_points, src_rect, matrix, warp_mode) {#warp_dest_points_src_rect_matrix_warp_mode_31}


```
 warp(dest_points, src_rect, matrix, warp_mode) 
```

एक आयत और समानांतर चतुर्भुज द्वारा परिभाषित वार्प ट्रांसफ़ॉर्म को इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) पर लागू करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | एक [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती है, जिसमें वह आयत <paramref name="srcRect" /> द्वारा परिभाषित है, जिसे परिवर्तित किया जाता है। सरणी में तीन या चार तत्व हो सकते हैं। यदि सरणी में तीन तत्व हैं, तो समानांतर चतुर्भुज का निचला-दायाँ कोना पहले तीन बिंदुओं द्वारा निर्धारित किया जाता है। |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) जो उस आयत को दर्शाता है जिसे <paramref name="destPoints" /> द्वारा परिभाषित समानांतर चतुर्भुज में परिवर्तित किया जाता है। |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | एक [Matrix](/psd/python-net/aspose.psd/matrix/) जो पथ पर लागू करने के लिए ज्यामितीय परिवर्तन निर्दिष्ट करता है। |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | एक [WarpMode](/psd/python-net/aspose.psd/warpmode/) एनीमरेशन जो यह निर्दिष्ट करता है कि यह वार्प ऑपरेशन परिप्रेक्ष्य मोड या द्विरैखिक मोड का उपयोग करता है। |

### Method: warp(dest_points, src_rect, matrix, warp_mode, flatness) {#warp_dest_points_src_rect_matrix_warp_mode_flatness_32}


```
 warp(dest_points, src_rect, matrix, warp_mode, flatness) 
```

एक आयत और समानांतर चतुर्भुज द्वारा परिभाषित वार्प ट्रांसफ़ॉर्म को इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) पर लागू करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| dest_points | [PointF[]](/psd/python-net/aspose.psd/pointf) | एक [PointF](/psd/python-net/aspose.psd/pointf/) संरचनाओं की सरणी जो एक समानांतर चतुर्भुज को परिभाषित करती है, जिसमें वह आयत <paramref name="srcRect" /> द्वारा परिभाषित है, जिसे परिवर्तित किया जाता है। सरणी में तीन या चार तत्व हो सकते हैं। यदि सरणी में तीन तत्व हैं, तो समानांतर चतुर्भुज का निचला-दायाँ कोना पहले तीन बिंदुओं द्वारा निर्धारित किया जाता है। |
| src_rect | [RectangleF](/psd/python-net/aspose.psd/rectanglef) | एक [RectangleF](/psd/python-net/aspose.psd/rectanglef/) जो उस आयत को दर्शाता है जिसे <paramref name="destPoints" /> द्वारा परिभाषित समानांतर चतुर्भुज में परिवर्तित किया जाता है। |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | एक [Matrix](/psd/python-net/aspose.psd/matrix/) जो पथ पर लागू करने के लिए ज्यामितीय परिवर्तन निर्दिष्ट करता है। |
| warp_mode | [WarpMode](/psd/python-net/aspose.psd/warpmode) | एक [WarpMode](/psd/python-net/aspose.psd/warpmode/) एनीमरेशन जो यह निर्दिष्ट करता है कि यह वार्प ऑपरेशन परिप्रेक्ष्य मोड या द्विरैखिक मोड का उपयोग करता है। |
| flatness | float | 0 से 1 के बीच का मान जो यह निर्दिष्ट करता है कि परिणामी पथ कितना समतल है। अधिक जानकारी के लिए, देखें [GraphicsPath.flatten()](/psd/python-net/aspose.psd/graphicspath/) विधियाँ। |

### Method: widen(pen) {#widen_pen_33}


```
 widen(pen) 
```

पथ में एक अतिरिक्त रूपरेखा जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | एक [Pen](/psd/python-net/aspose.psd/pen/) जो पथ की मूल रूपरेखा और इस विधि द्वारा निर्मित नई रूपरेखा के बीच की चौड़ाई निर्दिष्ट करता है। |

### Method: widen(pen, matrix) {#widen_pen_matrix_34}


```
 widen(pen, matrix) 
```

[GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) में एक अतिरिक्त रूपरेखा जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | एक [Pen](/psd/python-net/aspose.psd/pen/) जो पथ की मूल रूपरेखा और इस विधि द्वारा निर्मित नई रूपरेखा के बीच की चौड़ाई निर्दिष्ट करता है। |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | एक [Matrix](/psd/python-net/aspose.psd/matrix/) जो चौड़ाई बढ़ाने से पहले पथ पर लागू करने के लिए परिवर्तन निर्दिष्ट करता है। |

### Method: widen(pen, matrix, flatness) {#widen_pen_matrix_flatness_35}


```
 widen(pen, matrix, flatness) 
```

इस [GraphicsPath](/psd/python-net/aspose.psd/graphicspath/) को उन वक्रों से बदलता है जो उस क्षेत्र को घेरते हैं जो निर्दिष्ट पेन द्वारा इस पथ को खींचे जाने पर भरा जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| pen | [Pen](/psd/python-net/aspose.psd/pen) | एक [Pen](/psd/python-net/aspose.psd/pen/) जो पथ की मूल रूपरेखा और इस विधि द्वारा निर्मित नई रूपरेखा के बीच की चौड़ाई निर्दिष्ट करता है। |
| matrix | [Matrix](/psd/python-net/aspose.psd/matrix) | एक [Matrix](/psd/python-net/aspose.psd/matrix/) जो चौड़ाई बढ़ाने से पहले पथ पर लागू करने के लिए परिवर्तन निर्दिष्ट करता है। |
| समतलता | float | वक्रों के लिए सपाटपन निर्दिष्ट करने वाला मान। |

