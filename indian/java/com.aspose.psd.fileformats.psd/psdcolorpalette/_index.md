---
title: "PsdColorPalette"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "PSD रंग पैलेट।"
type: docs
weight: 13
url: /hi/java/com.aspose.psd.fileformats.psd/psdcolorpalette/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.IPsdColorPalette](../../com.aspose.psd/ipsdcolorpalette)
```
public class PsdColorPalette implements IPsdColorPalette
```

PSD रंग पैलेट।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [PsdColorPalette(IColorPalette colorPalette)](#PsdColorPalette-com.aspose.psd.IColorPalette-) | एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है। |
| [PsdColorPalette(IColorPalette colorPalette, short transparentIndex)](#PsdColorPalette-com.aspose.psd.IColorPalette-short-) | एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है। |
| [PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)](#PsdColorPalette-byte---boolean-) | एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है। |
| [PsdColorPalette(byte[] rawEntriesData)](#PsdColorPalette-byte---) | एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है और IsCompactPalette false है। |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-byte---short-boolean-) | एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है। |
| [PsdColorPalette(byte[] rawEntriesData, short transparentIndex)](#PsdColorPalette-byte---short-) | एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है और IsCompactPalette false है। |
| [PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)](#PsdColorPalette-int---boolean-) | एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है। |
| [PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---boolean-) | एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है। |
| [PsdColorPalette(Color[] colorPaletteEntries)](#PsdColorPalette-com.aspose.psd.Color---) | एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है और IsCompactPalette false है। |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)](#PsdColorPalette-com.aspose.psd.Color---short-boolean-) | एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है। |
| [PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)](#PsdColorPalette-com.aspose.psd.Color---short-) | एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है और IsCompactPalette false है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [copyPalette(IColorPalette colorPalette)](#copyPalette-com.aspose.psd.IColorPalette-) | पैलेट की प्रतिलिपि बनाता है। |
| [copyPalette(IColorPalette colorPalette, boolean useCompactPalette)](#copyPalette-com.aspose.psd.IColorPalette-boolean-) | पैलेट की प्रतिलिपि बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArgb32Color(int index)](#getArgb32Color-int-) | इंडेक्स द्वारा 32-बिट ARGB पैलेट रंग प्राप्त करता है। |
| [getArgb32Entries()](#getArgb32Entries--) | 32-बिट ARGB रंगों की एक एरे प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getColor(int index)](#getColor-int-) | इंडेक्स द्वारा पैलेट रंग प्राप्त करता है। |
| [getEntries()](#getEntries--) | एक एरे में [Color](../../com.aspose.psd/color) संरचनाएँ प्राप्त करता है। |
| [getEntriesCount()](#getEntriesCount--) | एंट्रीज़ की गिनती प्राप्त करता है। |
| [getNearestColorIndex(Color color)](#getNearestColorIndex-com.aspose.psd.Color-) | निकटतम रंग का सूचकांक प्राप्त करता है। |
| [getNearestColorIndex(int argb32Color)](#getNearestColorIndex-int-) | निकटतम रंग का सूचकांक प्राप्त करता है। |
| [getRawEntries()](#getRawEntries--) | कच्चे रंग पैलेट प्रविष्टियों का डेटा प्राप्त करता है। |
| [getRawEntriesCount()](#getRawEntriesCount--) | कच्चे रंग पैलेट प्रविष्टियों की गिनती प्राप्त करता है। |
| [getTransparentColor()](#getTransparentColor--) | पारदर्शी रंग प्राप्त करता है। |
| [getTransparentIndex()](#getTransparentIndex--) | पारदर्शी रंग का सूचकांक प्राप्त करता है। |
| [hasTransparentColor()](#hasTransparentColor--) | एक मान प्राप्त करता है जो दर्शाता है कि पारदर्शी रंग मौजूद है या नहीं। |
| [hashCode()](#hashCode--) |  |
| [isCompactPalette()](#isCompactPalette--) | एक मान प्राप्त करता है जो दर्शाता है कि यह पैलेट संकुचित है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdColorPalette(IColorPalette colorPalette) {#PsdColorPalette-com.aspose.psd.IColorPalette-}
```
public PsdColorPalette(IColorPalette colorPalette)
```


एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | रंग पैलेट। |

### PsdColorPalette(IColorPalette colorPalette, short transparentIndex) {#PsdColorPalette-com.aspose.psd.IColorPalette-short-}
```
public PsdColorPalette(IColorPalette colorPalette, short transparentIndex)
```


एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | रंग पैलेट। |
| transparentIndex | short | पारदर्शी रंग का सूचकांक। |

### PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette) {#PsdColorPalette-byte---boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, boolean isCompactPalette)
```


एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rawEntriesData | byte[] | कच्ची प्रविष्टियों का डेटा। |
| isCompactPalette | boolean | यह दर्शाता है कि यह पैलेट संकुचित है या नहीं। |

### PsdColorPalette(byte[] rawEntriesData) {#PsdColorPalette-byte---}
```
public PsdColorPalette(byte[] rawEntriesData)
```


एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है और IsCompactPalette false है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rawEntriesData | byte[] | कच्ची प्रविष्टियों का डेटा। |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-byte---short-boolean-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex, boolean useCompactPalette)
```


एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rawEntriesData | byte[] | कच्ची प्रविष्टियों का डेटा। |
| transparentIndex | short | पारदर्शी रंग का सूचकांक। नोट: यह सूचकांक कच्ची प्रविष्टियों का सूचकांक नहीं है, बल्कि परिवर्तित रंग सरणी के लिए है। |
| useCompactPalette | boolean | यह दर्शाता है कि यह पैलेट संकुचित है या नहीं। |

### PsdColorPalette(byte[] rawEntriesData, short transparentIndex) {#PsdColorPalette-byte---short-}
```
public PsdColorPalette(byte[] rawEntriesData, short transparentIndex)
```


एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है और IsCompactPalette false है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rawEntriesData | byte[] | कच्ची प्रविष्टियों का डेटा। |
| transparentIndex | short | पारदर्शी रंग का सूचकांक। नोट: यह सूचकांक कच्ची प्रविष्टियों का सूचकांक नहीं है, बल्कि परिवर्तित रंग सरणी के लिए है। |

### PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette) {#PsdColorPalette-int---boolean-}
```
public PsdColorPalette(int[] colorPaletteArgb32Entries, boolean isCompactPalette)
```


एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorPaletteArgb32Entries | int[] | रंग पैलेट के 32-बिट ARGB प्रविष्टियाँ। |
| isCompactPalette | boolean | यह दर्शाता है कि यह पैलेट संकुचित है या नहीं। |

### PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, boolean isCompactPalette)
```


एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | रंग पैलेट की प्रविष्टियाँ। |
| isCompactPalette | boolean | यह दर्शाता है कि यह पैलेट संकुचित है या नहीं। |

### PsdColorPalette(Color[] colorPaletteEntries) {#PsdColorPalette-com.aspose.psd.Color---}
```
public PsdColorPalette(Color[] colorPaletteEntries)
```


एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है और IsCompactPalette false है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | रंग पैलेट की प्रविष्टियाँ। |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette) {#PsdColorPalette-com.aspose.psd.Color---short-boolean-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex, boolean useCompactPalette)
```


एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | रंग पैलेट की प्रविष्टियाँ। |
| transparentIndex | short | पारदर्शी रंग का सूचकांक। |
| useCompactPalette | boolean | यह दर्शाता है कि यह पैलेट संकुचित है या नहीं। |

### PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex) {#PsdColorPalette-com.aspose.psd.Color---short-}
```
public PsdColorPalette(Color[] colorPaletteEntries, short transparentIndex)
```


एक नया [PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) क्लास का उदाहरण प्रारंभ करता है और IsCompactPalette false है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorPaletteEntries | [Color\[\]](../../com.aspose.psd/color) | रंग पैलेट की प्रविष्टियाँ। |
| transparentIndex | short | पारदर्शी रंग का सूचकांक। |

### copyPalette(IColorPalette colorPalette) {#copyPalette-com.aspose.psd.IColorPalette-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette)
```


पैलेट की प्रतिलिपि बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | रंग पैलेट। |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
### copyPalette(IColorPalette colorPalette, boolean useCompactPalette) {#copyPalette-com.aspose.psd.IColorPalette-boolean-}
```
public static PsdColorPalette copyPalette(IColorPalette colorPalette, boolean useCompactPalette)
```


पैलेट की प्रतिलिपि बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.psd/icolorpalette) | रंग पैलेट। |
| useCompactPalette | boolean | यह दर्शाता है कि पैलेट संकुचित है या नहीं। |

**Returns:**
[PsdColorPalette](../../com.aspose.psd.fileformats.psd/psdcolorpalette) - The newly created and copied palette or null if null palette passed.
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
public final int getArgb32Color(int index)
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
public final int[] getArgb32Entries()
```


32-बिट ARGB रंगों की एक एरे प्राप्त करता है।

**Returns:**
int[] - 32-बिट ARGB संरचना की सरणी जो इस [ColorPalette](../../com.aspose.psd/colorpalette) को बनाती है। मान: प्रविष्टियाँ।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor(int index) {#getColor-int-}
```
public final Color getColor(int index)
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
public final Color[] getEntries()
```


एक एरे में [Color](../../com.aspose.psd/color) संरचनाएँ प्राप्त करता है।

**Returns:**
com.aspose.psd.Color[] - इस [ColorPalette](../../com.aspose.psd/colorpalette) को बनाने वाली [Color](../../com.aspose.psd/color) संरचना की सरणी। मान: प्रविष्टियाँ।
### getEntriesCount() {#getEntriesCount--}
```
public final int getEntriesCount()
```


एंट्रीज़ की गिनती प्राप्त करता है।

मान: प्रविष्टियों की गिनती।

**Returns:**
int
### getNearestColorIndex(Color color) {#getNearestColorIndex-com.aspose.psd.Color-}
```
public final int getNearestColorIndex(Color color)
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
public final int getNearestColorIndex(int argb32Color)
```


निकटतम रंग का सूचकांक प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| argb32Color | int | 32-बिट ARGB रंग। |

**Returns:**
int - निकटतम रंग का सूचकांक।
### getRawEntries() {#getRawEntries--}
```
public final byte[] getRawEntries()
```


कच्चे रंग पैलेट प्रविष्टियों का डेटा प्राप्त करता है।

मान: कच्चे रंग पैलेट प्रविष्टियों का डेटा।

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public final int getRawEntriesCount()
```


कच्चे रंग पैलेट प्रविष्टियों की गिनती प्राप्त करता है।

मान: कच्चे रंग पैलेट प्रविष्टियों की गिनती।

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public final Color getTransparentColor()
```


पारदर्शी रंग प्राप्त करता है।

मान: पारदर्शी रंग।

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public final short getTransparentIndex()
```


पारदर्शी रंग का सूचकांक प्राप्त करता है।

मान: पारदर्शी रंग का सूचकांक।

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public final boolean hasTransparentColor()
```


एक मान प्राप्त करता है जो दर्शाता है कि पारदर्शी रंग मौजूद है या नहीं।

मान: यदि पारदर्शी रंग मौजूद है तो  true , अन्यथा  false ।

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCompactPalette() {#isCompactPalette--}
```
public final boolean isCompactPalette()
```


एक मान प्राप्त करता है जो दर्शाता है कि यह पैलेट संकुचित है या नहीं।

मान: यदि पैलेट संकुचित है तो  true , अन्यथा  false ।

--------------------

संकुचित पैलेट का अर्थ है कि छवि केवल निर्दिष्ट पैलेट प्रविष्टियों को रखेगी यदि संभव हो, अन्य शब्दों में छवि अधिक संकुचित होगी और कम स्थान घेरेंगी; अन्यथा 2^BitsPerPixel प्रविष्टियाँ होंगी और छवि सभी संभावित पैलेट प्रविष्टियों के लिए अधिक स्थान आरक्षित करेगी। इस मान को true सेट करने और पैलेट प्रविष्टियों को बदलने से प्रदर्शन में गिरावट हो सकती है क्योंकि डेटा स्थानांतरण हो सकता है, इसलिए इसे सावधानीपूर्वक उपयोग करें।

**Returns:**
boolean
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

