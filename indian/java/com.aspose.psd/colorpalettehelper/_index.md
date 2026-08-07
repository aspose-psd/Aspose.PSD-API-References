---
title: "ColorPaletteHelper"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "रंग पैलेट हेरफेर के लिए सहायक क्लास।"
type: docs
weight: 28
url: /hi/java/com.aspose.psd/colorpalettehelper/
---

**Inheritance:**
java.lang.Object
```
public final class ColorPaletteHelper
```

रंग पैलेट हेरफेर के लिए सहायक क्लास।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [create4Bit()](#create4Bit--) | 4 बिट रंग पैलेट बनाता है। |
| [create4BitGrayscale(boolean minIsWhite)](#create4BitGrayscale-boolean-) | 4 बिट ग्रेस्केल पैलेट बनाता है। |
| [create8Bit()](#create8Bit--) | 8 बिट रंग पैलेट बनाता है। |
| [create8BitGrayscale(boolean minIsWhite)](#create8BitGrayscale-boolean-) | 8 बिट ग्रेस्केल पैलेट बनाता है। |
| [createMonochrome()](#createMonochrome--) | केवल 2 रंगों वाला मोनोक्रोम रंग पैलेट बनाता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-) | यदि छवि में रंग पैलेट नहीं है तो रास्टर छवि से (छवि को पैलेटाइज़ करके) रंग पैलेट प्राप्त करता है। |
| [getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)](#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-) | यदि छवि में रंग पैलेट नहीं है तो रास्टर छवि से (छवि को पैलेटाइज़ करके) रंग पैलेट प्राप्त करता है। |
| [getCloseImagePalette(RasterImage image, int entriesCount)](#getCloseImagePalette-com.aspose.psd.RasterImage-int-) | यदि छवि में रंग पैलेट नहीं है तो रास्टर छवि से (छवि को पैलेटाइज़ करके) रंग पैलेट प्राप्त करता है। |
| [getDownscalePalette(RasterImage image)](#getDownscalePalette-com.aspose.psd.RasterImage-) | प्रारंभिक छवि के रंग मानों के ऊपरी बिट्स से निर्मित 256 रंग पैलेट प्राप्त करें। |
| [getUniformColorPalette(RasterImage image)](#getUniformColorPalette-com.aspose.psd.RasterImage-) | समान 256 रंग पैलेट प्राप्त करें। |
| [hasTransparentColors(IColorPalette palette)](#hasTransparentColors-com.aspose.psd.IColorPalette-) | निर्धारित करता है कि निर्दिष्ट पैलेट में पारदर्शी रंग हैं या नहीं। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### create4Bit() {#create4Bit--}
```
public static IColorPalette create4Bit()
```


4 बिट रंग पैलेट बनाता है।

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit color palette.
### create4BitGrayscale(boolean minIsWhite) {#create4BitGrayscale-boolean-}
```
public static IColorPalette create4BitGrayscale(boolean minIsWhite)
```


4 बिट ग्रेस्केल पैलेट बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| minIsWhite | boolean | यदि इसे  true  पर सेट किया जाता है तो पैलेट सफेद रंग से शुरू होता है, अन्यथा यह काले रंग से शुरू होता है। |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 4 bit grayscale palette.
### create8Bit() {#create8Bit--}
```
public static IColorPalette create8Bit()
```


8 बिट रंग पैलेट बनाता है।

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit color palette.
### create8BitGrayscale(boolean minIsWhite) {#create8BitGrayscale-boolean-}
```
public static IColorPalette create8BitGrayscale(boolean minIsWhite)
```


8 बिट ग्रेस्केल पैलेट बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| minIsWhite | boolean | यदि इसे  true  पर सेट किया जाता है तो पैलेट सफेद रंग से शुरू होता है, अन्यथा यह काले रंग से शुरू होता है। |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The 8 bit grayscale palette.
### createMonochrome() {#createMonochrome--}
```
public static IColorPalette createMonochrome()
```


केवल 2 रंगों वाला मोनोक्रोम रंग पैलेट बनाता है।

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - Color palette for monochrome images.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount)
```


रास्टर छवि से रंग पैलेट प्राप्त करता है (छवि को पैलेटाइज़ करता है) यदि छवि में पहले से कोई पैलेट नहीं है। यदि पैलेट मौजूद है तो गणनाएँ करने के बजाय इसका उपयोग किया जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | रास्टर छवि। |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | गंतव्य छवि की सीमाएँ। |
| entriesCount | int | वांछित प्रविष्टियों की संख्या। |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette) {#getCloseImagePalette-com.aspose.psd.RasterImage-com.aspose.psd.Rectangle-int-boolean-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, Rectangle destBounds, int entriesCount, boolean useImagePalette)
```


रास्टर छवि से रंग पैलेट प्राप्त करता है (छवि को पैलेटाइज़ करता है) यदि छवि में पहले से कोई पैलेट नहीं है। यदि पैलेट मौजूद है तो गणनाएँ करने के बजाय इसका उपयोग किया जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | रास्टर छवि। |
| destBounds | [Rectangle](../../com.aspose.psd/rectangle) | गंतव्य छवि की सीमाएँ। |
| entriesCount | int | वांछित प्रविष्टियों की संख्या। |
| useImagePalette | boolean | यदि सेट किया गया है, तो यह उपलब्ध होने पर अपनी स्वयं की छवि पैलेट का उपयोग करेगा। |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getCloseImagePalette(RasterImage image, int entriesCount) {#getCloseImagePalette-com.aspose.psd.RasterImage-int-}
```
public static IColorPalette getCloseImagePalette(RasterImage image, int entriesCount)
```


रास्टर छवि से रंग पैलेट प्राप्त करता है (छवि को पैलेटाइज़ करता है) यदि छवि में पहले से कोई पैलेट नहीं है। यदि पैलेट मौजूद है तो गणनाएँ करने के बजाय इसका उपयोग किया जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | रास्टर छवि। |
| entriesCount | int | वांछित प्रविष्टियों की संख्या। |

**Returns:**
[IColorPalette](../../com.aspose.psd/icolorpalette) - The color palette which starts with the most frequent colors from the  image  and contains  entriesCount  entries.
### getDownscalePalette(RasterImage image) {#getDownscalePalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getDownscalePalette(RasterImage image)
```


प्रारंभिक छवि के रंग मानों के ऊपरी बिट्स से निर्मित 256 रंग पैलेट प्राप्त करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | छवि। |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### getUniformColorPalette(RasterImage image) {#getUniformColorPalette-com.aspose.psd.RasterImage-}
```
public static ColorPalette getUniformColorPalette(RasterImage image)
```


समान 256 रंग पैलेट प्राप्त करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | छवि। |

**Returns:**
[ColorPalette](../../com.aspose.psd/colorpalette) - The  ColorPalette .
### hasTransparentColors(IColorPalette palette) {#hasTransparentColors-com.aspose.psd.IColorPalette-}
```
public static boolean hasTransparentColors(IColorPalette palette)
```


निर्धारित करता है कि निर्दिष्ट पैलेट में पारदर्शी रंग हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.psd/icolorpalette) | पैलेट। |

**Returns:**
बूलियन -  true  यदि निर्दिष्ट पैलेट में पारदर्शी रंग हैं; अन्यथा,  false .
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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

