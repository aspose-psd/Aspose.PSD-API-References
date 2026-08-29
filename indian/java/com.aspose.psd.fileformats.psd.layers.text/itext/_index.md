---
title: "IText"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "टेक्स्ट लेयर्स के लिए टेक्स्ट एडिटिंग का इंटरफ़ेस"
type: docs
weight: 11
url: /hi/java/com.aspose.psd.fileformats.psd.layers.text/itext/
---
```
public interface IText
```

टेक्स्ट लेयर्स के लिए टेक्स्ट एडिटिंग का इंटरफ़ेस
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addPortion(ITextPortion portion)](#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-) | पाठ के भाग को अंत में जोड़ता है |
| [getItems()](#getItems--) | आइटम प्राप्त करता है। |
| [getText()](#getText--) | पाठ प्राप्त करता है। |
| [getTextOrientation()](#getTextOrientation--) | पाठ अभिविन्यास को प्राप्त करता है या सेट करता है। |
| [insertPortion(ITextPortion portion, int index)](#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-) | निर्दिष्ट स्थिति में [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) को सम्मिलित करता है |
| [producePortion()](#producePortion--) | डिफ़ॉल्ट पैरामीटरों के साथ नया भाग उत्पन्न करता है |
| [producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)](#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | इनपुट या डिफ़ॉल्ट पैरामीटरों के साथ नए भाग उत्पन्न करता है। |
| [removePortion(int index)](#removePortion-int-) | निर्दिष्ट अनुक्रमांक में भाग को हटाता है |
| [setTextOrientation(int value)](#setTextOrientation-int-) | पाठ अभिविन्यास को प्राप्त करता है या सेट करता है। |
| [updateLayerData()](#updateLayerData--) | लेयर डेटा को अपडेट करता है। |
### addPortion(ITextPortion portion) {#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-}
```
public abstract void addPortion(ITextPortion portion)
```


पाठ के भाग को अंत में जोड़ता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | भाग। |

### getItems() {#getItems--}
```
public abstract ITextPortion[] getItems()
```


आइटम प्राप्त करता है।

मान: आइटम।

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[]
### getText() {#getText--}
```
public abstract String getText()
```


पाठ प्राप्त करता है।

मान: टेक्स्ट।

**Returns:**
java.lang.String
### getTextOrientation() {#getTextOrientation--}
```
public abstract int getTextOrientation()
```


पाठ अभिविन्यास को प्राप्त करता है या सेट करता है।

मान: पाठ अभिविन्यास।

**Returns:**
int
### insertPortion(ITextPortion portion, int index) {#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-}
```
public abstract void insertPortion(ITextPortion portion, int index)
```


निर्दिष्ट स्थिति में [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) को सम्मिलित करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | भाग। |
| सूचकांक | int | सूचकांक। |

### producePortion() {#producePortion--}
```
public abstract ITextPortion producePortion()
```


डिफ़ॉल्ट पैरामीटरों के साथ नया भाग उत्पन्न करता है

**Returns:**
[ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) - Reference to newly created [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion).
### producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype) {#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract ITextPortion[] producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)
```


इनपुट या डिफ़ॉल्ट पैरामीटरों के साथ नए भाग उत्पन्न करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| portionsOfText | java.lang.String[] | नए ITextPortion बनाने के लिए पाठ के भाग। |
| stylePrototype | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | एक शैली जो, यदि null नहीं है, तो नई में लागू होगी, अन्यथा डिफ़ॉल्ट होगी। |
| paragraphPrototype | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | एक पैराग्राफ जो, यदि null नहीं है, तो नई में लागू होगा, अन्यथा डिफ़ॉल्ट होगा। |

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[] - इनपुट पैरामीटर के आधार पर नए ITextPortion भाग लौटाता है।
### removePortion(int index) {#removePortion-int-}
```
public abstract void removePortion(int index)
```


निर्दिष्ट अनुक्रमांक में भाग को हटाता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| सूचकांक | int | सूचकांक। |

### setTextOrientation(int value) {#setTextOrientation-int-}
```
public abstract void setTextOrientation(int value)
```


पाठ अभिविन्यास को प्राप्त करता है या सेट करता है।

मान: पाठ अभिविन्यास।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### updateLayerData() {#updateLayerData--}
```
public abstract void updateLayerData()
```


लेयर डेटा को अपडेट करता है।

