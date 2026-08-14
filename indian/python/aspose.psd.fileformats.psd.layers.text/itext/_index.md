---
title: "IText क्लास"
type: docs
weight: 10
url: /hi/python-net/aspose.psd.fileformats.psd.layers.text/itext/
---

**Summary:** Interface for Text Editing for Text Layers

**Module:** [aspose.psd.fileformats.psd.layers.text](/psd/python-net/aspose.psd.fileformats.psd.layers.text/)

**Full Name:** aspose.psd.fileformats.psd.layers.text.IText

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **विवरण** |
| :- | :- | :- | :- |
| items | [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | r | आइटम्स प्राप्त करता है। |
| text | string | r | टेक्स्ट को प्राप्त करता है। |
| text_orientation | [TextOrientation](/psd/python-net/aspose.psd.fileformats.psd/textorientation) | r/w | पाठ अभिविन्यास को प्राप्त करता है या सेट करता है। |
## **Methods**
| **Name** | **विवरण** |
| :- | :- |
| [add_portion(portion)](#add_portion_portion_1) | पाठ के भाग को अंत में जोड़ता है |
| [insert_portion(portion, index)](#insert_portion_portion_index_2) | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) को निर्दिष्ट स्थिति में सम्मिलित करता है |
| [produce_portion()](#produce_portion__3) | डिफ़ॉल्ट पैरामीटर के साथ नया भाग उत्पन्न करता है |
| [produce_portions(portions_of_text, style_prototype, paragraph_prototype)](#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4) | इनपुट या डिफ़ॉल्ट पैरामीटर के साथ नए भाग उत्पन्न करता है। |
| [remove_portion(index)](#remove_portion_index_5) | निर्दिष्ट अनुक्रमांक में भाग को हटाता है |
| update_layer_data() | लेयर डेटा को अपडेट करता है। |


### Method: add_portion(portion) {#add_portion_portion_1}


```
 add_portion(portion) 
```

पाठ के भाग को अंत में जोड़ता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | भाग। |

### Method: insert_portion(portion, index) {#insert_portion_portion_index_2}


```
 insert_portion(portion, index) 
```

[ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) को निर्दिष्ट स्थिति में सम्मिलित करता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| portion | [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | भाग। |
| index | int | सूचकांक। |

### Method: produce_portion() {#produce_portion__3}


```
 produce_portion() 
```

डिफ़ॉल्ट पैरामीटर के साथ नया भाग उत्पन्न करता है

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | नए बनाए गए [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) का संदर्भ। |


### Method: produce_portions(portions_of_text, style_prototype, paragraph_prototype) {#produce_portions_portions_of_text_style_prototype_paragraph_prototype_4}


```
 produce_portions(portions_of_text, style_prototype, paragraph_prototype) 
```

इनपुट या डिफ़ॉल्ट पैरामीटर के साथ नए भाग उत्पन्न करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| portions_of_text | string | नए [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) बनाने के लिए पाठ के भाग। |
| style_prototype | [ITextStyle](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextstyle) | एक शैली जो, यदि null नहीं है, तो नए [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) में लागू होगी, अन्यथा डिफ़ॉल्ट होगी। |
| paragraph_prototype | [ITextParagraph](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextparagraph) | एक पैराग्राफ जो, यदि null नहीं है, तो नए [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) में लागू किया जाएगा, अन्यथा डिफ़ॉल्ट रहेगा। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ITextPortion[]](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion) | इनपुट पैरामीटरों के आधार पर नए भागों के [ITextPortion](/psd/python-net/aspose.psd.fileformats.psd.layers.text/itextportion/) को लौटाता है। |


### Method: remove_portion(index) {#remove_portion_index_5}


```
 remove_portion(index) 
```

निर्दिष्ट अनुक्रमांक में भाग को हटाता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | int | सूचकांक। |

