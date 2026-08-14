---
title: "ITextStyle क्लास"
type: docs
weight: 40
url: /hi/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle/
---

**Summary:** Interface to work with Text Style

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.ITextStyle

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| auto_kerning | [AutoKerning](/psd/python-net/aspose.psd.fileformats.psd/autokerning) | r/w | ऑटो केरनिंग को प्राप्त करता है या सेट करता है। |
| auto_leading | bool | r/w | क्या [automatic leading] है यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| baseline_shift | डबल | r/w | बेसलाइन शिफ्ट। |
| contextual_alternates | bool | r/w | अक्षरों को जोड़ने के लिए उपयोग किए जाने वाले कॉन्टेक्स्चुअल अल्टरनेट्स। |
| discretionary_ligatures | bool | r/w | अक्षरों को जोड़ने के लिए उपयोग किए जाने वाले डिस्क्रेशनरी लिगेचर, विशेष रूप से स्क्रिप्ट फ़ॉन्ट्स में। |
| faux_bold | bool | r/w | क्या फ़ॉक्स बोल्ड सक्षम है यह प्राप्त करता है या सेट करता है। |
| faux_italic | bool | r/w | क्या फ़ॉक्स बोल्ड सक्षम है यह प्राप्त करता है या सेट करता है। |
| fill_color | [Color](/psd/python-net/aspose.psd/color) | r/w | फ़िल का रंग प्राप्त करता है या सेट करता है। |
| font_baseline | [FontBaseline](/psd/python-net/aspose.psd.fileformats.psd/fontbaseline) | r/w | फ़ॉन्ट बेसलाइन। |
| font_caps | [FontCaps](/psd/python-net/aspose.psd.fileformats.psd/fontcaps) | r/w | फ़ॉन्ट कैप्स। |
| font_index | int | r | फ़ॉन्ट इंडेक्स प्राप्त करता है। |
| font_name | string | r/w | फ़ॉन्ट नाम को प्राप्त करता है या सेट करता है। |
| font_size | डबल | r/w | फ़ॉन्ट का आकार प्राप्त करता है या सेट करता है। |
| fractions | bool | r/w | फ़्रैक्शन प्रतीकों को विशेष ग्लिफ़ से बदला जा सकता है। |
| hindi_numbers | bool | r/w | क्या [hindi numbers] है यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| horizontal_scale | डबल | r/w | हॉरिज़ॉन्टल स्केल। |
| is_standard_vertical_roman_alignment_enabled | bool | r/w | मानक वर्टिकल रोमन अलाइनमेंट को प्राप्त करता है या सेट करता है.<br/>            यह BaselineDirection संसाधन मान पर आधारित है और केवल तब लागू होता है जब टेक्स्ट अभिविन्यास [TextOrientation.VERTICAL](/psd/python-net/aspose.psd.fileformats.psd/textorientation/) हो। |
| kerning | int | r/w | केर्निंग को प्राप्त करता है या सेट करता है। |
| language_index | int | r | भाषा सूचकांक को प्राप्त करता है। |
| leading | डबल | r/w | लीडिंग को प्राप्त करता है या सेट करता है। |
| no_break | bool | r/w | नो ब्रेक मान को प्राप्त करता है या सेट करता है। |
| standard_ligatures | bool | r/w | अक्षरों को जोड़ने के लिए उपयोग किए जाने वाले मानक संदर्भात्मक लिगेचर। |
| strikethrough | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [strikethrough] है या नहीं। |
| stroke_color | [Color](/psd/python-net/aspose.psd/color) | r/w | स्ट्रोक के रंग को प्राप्त करता है या सेट करता है। |
| tracking | int | r/w | ट्रैकिंग को प्राप्त करता है या सेट करता है। |
| underline | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि [underline] है या नहीं। |
| vertical_scale | डबल | r/w | ऊर्ध्वाधर स्केल। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [apply(style)](#apply_style_1) | निर्दिष्ट शैली को लागू करता है। |
| [is_equal(style)](#is_equal_style_2) | निर्धारित करता है कि निर्दिष्ट शैली समान है या नहीं। |


### Method: apply(style) {#apply_style_1}


```
 apply(style) 
```

निर्दिष्ट शैली को लागू करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | शैली। |

### Method: is_equal(style) {#is_equal_style_2}


```
 is_equal(style) 
```

निर्धारित करता है कि निर्दिष्ट शैली समान है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| style | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | शैली। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <c>true</c> यदि निर्दिष्ट शैली समान है; अन्यथा, <c>false</c>. |


