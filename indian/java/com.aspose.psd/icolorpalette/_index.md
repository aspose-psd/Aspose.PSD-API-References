---
title: "IColorPalette"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "रंग पैलेट इंटरफ़ेस."
type: docs
weight: 117
url: /hi/java/com.aspose.psd/icolorpalette/
---
```
public interface IColorPalette
```

रंग पैलेट इंटरफ़ेस.
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getArgb32Color(int index)](#getArgb32Color-int-) | इंडेक्स द्वारा 32-बिट ARGB पैलेट रंग प्राप्त करता है। |
| [getArgb32Entries()](#getArgb32Entries--) | 32-बिट ARGB संरचनाओं की एक सरणी प्राप्त करता है। |
| [getColor(int index)](#getColor-int-) | इंडेक्स द्वारा पैलेट रंग प्राप्त करता है। |
| [getEntries()](#getEntries--) | com.aspose.psd.Color संरचनाओं की एक सरणी प्राप्त करता है। |
| [getEntriesCount()](#getEntriesCount--) | एंट्रीज़ की गिनती प्राप्त करता है। |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | निकटतम रंग का सूचकांक प्राप्त करता है। |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | निकटतम 32-बिट ARGB रंग का सूचकांक प्राप्त करता है। |
| [isCompactPalette()](#isCompactPalette--) | यह दर्शाने वाला मान प्राप्त करता है कि संकुचित पैलेट उपयोग किया गया है या नहीं। |
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public abstract int getArgb32Color(int index)
```


इंडेक्स द्वारा 32-बिट ARGB पैलेट रंग प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| सूचकांक | int | 32-बिट ARGB पैलेट रंग का सूचकांक। |

**Returns:**
int - वह रंग पैलेट प्रविष्टि जो सूचकांक द्वारा निर्दिष्ट है।
### getArgb32Entries() {#getArgb32Entries--}
```
public abstract int[] getArgb32Entries()
```


32-बिट ARGB संरचनाओं की एक सरणी प्राप्त करता है।

**Returns:**
int[] - 32-बिट ARGB प्रविष्टियाँ। इस com.aspose.psd.ColorPalette को बनाने वाले 32-बिट ARGB संरचना की सरणी।
### getColor(int index) {#getColor-int-}
```
public abstract Color getColor(int index)
```


इंडेक्स द्वारा पैलेट रंग प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| सूचकांक | int | पैलेट रंग का सूचकांक। |

**Returns:**
[Color](../../com.aspose.psd/color) - The color palette entry specified by the  index .
### getEntries() {#getEntries--}
```
public abstract Color[] getEntries()
```


com.aspose.psd.Color संरचनाओं की एक सरणी प्राप्त करता है।

**Returns:**
com.aspose.psd.Color[] - प्रविष्टियाँ। इस com.aspose.psd.ColorPalette को बनाने वाले com.aspose.psd.Color संरचना की सरणी।
### getEntriesCount() {#getEntriesCount--}
```
public abstract int getEntriesCount()
```


एंट्रीज़ की गिनती प्राप्त करता है।

**Returns:**
int - प्रविष्टियों की गिनती।
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public abstract int getNearestColorIndex(Color color)
```


निकटतम रंग का सूचकांक प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | रंग। |

**Returns:**
int - निकटतम रंग का सूचकांक।
### getNearestColorIndex(int argb32Color) {#getNearestColorIndex-int-}
```
public abstract int getNearestColorIndex(int argb32Color)
```


निकटतम 32-बिट ARGB रंग का सूचकांक प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| argb32Color | int | 32-बिट ARGB रंग। |

**Returns:**
int - निकटतम रंग का सूचकांक।
### isCompactPalette() {#isCompactPalette--}
```
public abstract boolean isCompactPalette()
```


यह दर्शाने वाला मान प्राप्त करता है कि संकुचित पैलेट उपयोग किया गया है या नहीं।

संकुचित पैलेट का अर्थ है कि छवि केवल निर्दिष्ट पैलेट प्रविष्टियों को रखेगी यदि संभव हो, अन्य शब्दों में छवि अधिक संकुचित होगी और कम स्थान घेरेंगी; अन्यथा 2^BitsPerPixel प्रविष्टियाँ होंगी और छवि सभी संभावित पैलेट प्रविष्टियों के लिए अधिक स्थान आरक्षित करेगी। इस मान को true सेट करने और पैलेट प्रविष्टियों को बदलने से प्रदर्शन में गिरावट हो सकती है क्योंकि डेटा स्थानांतरण हो सकता है, इसलिए इसे सावधानीपूर्वक उपयोग करें।

**Returns:**
boolean - यदि कम्पैक्ट पैलेट उपयोग किया जाता है तो true; अन्यथा false।
