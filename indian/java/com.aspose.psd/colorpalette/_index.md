---
title: "कलरपैलेट"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "रंग पैलेट बनाते हुए रंगों के एरे को परिभाषित करता है।"
type: docs
weight: 27
url: /hi/java/com.aspose.psd/colorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public final class ColorPalette implements IColorPalette
```

एक रंग पैलेट बनाने वाले रंगों की एरे को परिभाषित करता है। रंग 32-बिट ARGB रंग हैं। विरासत में नहीं मिलते।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [ColorPalette(int[] argb32Entries, boolean isCompactPalette)](#ColorPalette-int---boolean-) | ColorPalette क्लास का एक नया उदाहरण आरंभ करता है। |
| [ColorPalette(int[] argb32Entries)](#ColorPalette-int---) | ColorPalette क्लास का एक नया उदाहरण आरंभ करता है और IsCompactPalette गलत है। |
| [ColorPalette(Color[] entries, boolean isCompactPalette)](#ColorPalette-com.aspose.psd.Color---boolean-) | ColorPalette क्लास का एक नया उदाहरण आरंभ करता है। |
| [ColorPalette(Color[] entries)](#ColorPalette-com.aspose.psd.Color---) | ColorPalette क्लास का एक नया उदाहरण आरंभ करता है और IsCompactPalette गलत है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | पैलेट की प्रतिलिपि बनाता है। |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | पैलेट की प्रतिलिपि बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | इंडेक्स द्वारा 32-बिट ARGB पैलेट रंग प्राप्त करता है। |
| [getArgb32Entries()](#getArgb32Entries--) | 32-बिट ARGB संरचनाओं की एक सरणी प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | इंडेक्स द्वारा पैलेट रंग प्राप्त करता है। |
| [getEntries()](#getEntries--) | com.aspose.psd.Color संरचनाओं की एक सरणी प्राप्त करता है। |
| [getEntriesCount()](#getEntriesCount--) | एंट्रीज़ की गिनती प्राप्त करता है। |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | निकटतम रंग का सूचकांक प्राप्त करता है। |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | निकटतम रंग का सूचकांक प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | कम्पैक्ट पैलेट उपयोग किया जाता है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorPalette(int[] argb32Entries, boolean isCompactPalette) {#ColorPalette-int---boolean-}
```
public ColorPalette(int[] argb32Entries, boolean isCompactPalette)
```


ColorPalette क्लास का एक नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| argb32Entries | int[] | 32-बिट ARGB रंग पैलेट प्रविष्टियाँ। |
| isCompactPalette | boolean | यह दर्शाता है कि यह पैलेट संकुचित है या नहीं। |

### ColorPalette(int[] argb32Entries) {#ColorPalette-int---}
```
public ColorPalette(int[] argb32Entries)
```


ColorPalette क्लास का एक नया उदाहरण आरंभ करता है और IsCompactPalette गलत है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| argb32Entries | int[] | 32-बिट ARGB रंग पैलेट प्रविष्टियाँ। |

### ColorPalette(Color[] entries, boolean isCompactPalette) {#ColorPalette-com.aspose.psd.Color---boolean-}
```
public ColorPalette(Color[] entries, boolean isCompactPalette)
```


ColorPalette क्लास का एक नया उदाहरण आरंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | रंग पैलेट की प्रविष्टियाँ। |
| isCompactPalette | boolean | यह दर्शाता है कि यह पैलेट संकुचित है या नहीं। |

### ColorPalette(Color[] entries) {#ColorPalette-com.aspose.psd.Color---}
```
public ColorPalette(Color[] entries)
```


ColorPalette क्लास का एक नया उदाहरण आरंभ करता है और IsCompactPalette गलत है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| entries | [Color\[\]](../../com.aspose.psd/color) | रंग पैलेट की प्रविष्टियाँ। |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette)
```


पैलेट की प्रतिलिपि बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | रंग पैलेट। |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static ColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


पैलेट की प्रतिलिपि बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | रंग पैलेट। |
| useCompactPalette | boolean | यह दर्शाता है कि पैलेट संकुचित है या नहीं। |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The newly created and copied palette or null if null palette passed.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getArgb32Color(int index) {#getArgb32Color-int-}
```
public int getArgb32Color(int index)
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
public int[] getArgb32Entries()
```


32-बिट ARGB संरचनाओं की एक सरणी प्राप्त करता है।

**Returns:**
int[] - प्रविष्टियाँ। 32-बिट ARGB संरचनाओं की सरणी जो इस Aspose.Imaging.ColorPalette को बनाती है।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor(int index) {#getColor-int-}
```
public Color getColor(int index)
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
public Color[] getEntries()
```


com.aspose.psd.Color संरचनाओं की एक सरणी प्राप्त करता है।

**Returns:**
com.aspose.psd.Color[] - प्रविष्टियाँ। com.aspose.psd.Color संरचनाओं की सरणी जो इस Aspose.Imaging.ColorPalette को बनाती है।
### getEntriesCount() {#getEntriesCount--}
```
public int getEntriesCount()
```


एंट्रीज़ की गिनती प्राप्त करता है।

**Returns:**
int - प्रविष्टियों की गिनती।
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public int getNearestColorIndex(Color color)
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
public int getNearestColorIndex(int argb32Color)
```


निकटतम रंग का सूचकांक प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| argb32Color | int | 32-बिट ARGB रंग। |

**Returns:**
int - निकटतम रंग का सूचकांक।
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompactPalette() {#isCompactPalette--}
```
public boolean isCompactPalette()
```


कम्पैक्ट पैलेट उपयोग किया जाता है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है।

**Returns:**
boolean - यदि कम्पैक्ट पैलेट उपयोग किया जाता है तो true; अन्यथा false।

संकुचित पैलेट का अर्थ है कि छवि केवल निर्दिष्ट पैलेट प्रविष्टियों को रखेगी यदि संभव हो, अन्य शब्दों में छवि अधिक संकुचित होगी और कम स्थान घेरेंगी; अन्यथा 2^BitsPerPixel प्रविष्टियाँ होंगी और छवि सभी संभावित पैलेट प्रविष्टियों के लिए अधिक स्थान आरक्षित करेगी। इस मान को true सेट करने और पैलेट प्रविष्टियों को बदलने से प्रदर्शन में गिरावट हो सकती है क्योंकि डेटा स्थानांतरण हो सकता है, इसलिए इसे सावधानीपूर्वक उपयोग करें।
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

