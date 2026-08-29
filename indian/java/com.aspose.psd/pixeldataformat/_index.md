---
title: "PixelDataFormat"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "पिक्सेल डेटा फ़ॉर्मेट।"
type: docs
weight: 80
url: /hi/java/com.aspose.psd/pixeldataformat/
---

**Inheritance:**
java.lang.Object
```
public class PixelDataFormat
```

पिक्सेल डेटा फ़ॉर्मेट। यह एक अपरिवर्तनीय ऑब्जेक्ट है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | निर्धारित करता है कि निर्दिष्ट  System.Object  इस इंस्टेंस के बराबर है या नहीं। |
| [getBgr(int bitsPerSample)](#getBgr-int-) | निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ BGR रंग प्राप्त करता है। |
| [getBgra(int bitsPerSample)](#getBgra-int-) | निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ BGRA रंग प्राप्त करता है। |
| [getBitsPerPixel()](#getBitsPerPixel--) | प्रति पिक्सेल बिट्स प्राप्त करता है। |
| [getCaption()](#getCaption--) | पिक्सेल डेटा फ़ॉर्मेट कैप्शन प्राप्त करता है। |
| [getChannelBits()](#getChannelBits--) | प्रत्येक चैनल के लिए बिट्स की गिनती प्राप्त करता है। |
| [getChannelsCount()](#getChannelsCount--) | चैनल की गिनती प्राप्त करता है। |
| [getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)](#getCieLab-int-int-int-) | निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ CIE Lab रंग प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getCmyk()](#getCmyk--) | 32 बिट्स प्रति पिक्सेल के लिए परिभाषित  PixelDataFormat  प्राप्त करता है, जिसमें सियान, मैजेंटा, येलो और ब्लैक के प्रत्येक के लिए 8 बिट्स होते हैं। |
| [getCmyk(int bitsPerSample)](#getCmyk-int-) | निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ CMYK रंग प्राप्त करता है। |
| [getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)](#getCmyk-int-int-int-int-) | निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ CMYK रंग प्राप्त करता है। |
| [getCmyk16()](#getCmyk16--) | 64 बिट्स प्रति पिक्सेल के लिए परिभाषित [PixelDataFormat](../../com.aspose.psd/pixeldataformat) प्राप्त करता है, जिसमें सियान, मैजेंटा, येलो और ब्लैक के प्रत्येक के लिए 16 बिट्स होते हैं। |
| [getCmyka()](#getCmyka--) | acmyk प्राप्त करता है। |
| [getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)](#getCmyka-int-int-int-int-int-) | निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ CMYKA रंग प्राप्त करता है। |
| [getCmyka16()](#getCmyka16--) | acmyk प्राप्त करता है। |
| [getGrayscale()](#getGrayscale--) | 8 बिट्स प्रति पिक्सेल के लिए परिभाषित  PixelDataFormat  प्राप्त करता है, जिसमें 0-255 अंतराल में ग्रेस्केल तीव्रता को दर्शाने के लिए 8 बिट्स होते हैं। |
| [getGrayscale(int bitsPerSample)](#getGrayscale-int-) | निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ ग्रेस्केल रंग प्राप्त करता है। |
| [getGrayscaleAlpha()](#getGrayscaleAlpha--) | 16 बिट्स प्रति पिक्सेल के लिए परिभाषित  PixelDataFormat  प्राप्त करता है, जिसमें 0-255 अंतराल में ग्रेस्केल तीव्रता को दर्शाने के लिए 8 बिट्स और अतिरिक्त 8 बिट अल्फा घटक होता है। |
| [getGrayscaleAlpha(int bitsPerSample)](#getGrayscaleAlpha-int-) | निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ GrayscaleAlpha रंग प्राप्त करता है। |
| [getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)](#getGrayscaleAlpha-int-int-) | निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ GrayscaleAlpha रंग प्राप्त करता है। |
| [getGrayscaleFloat32_internalized()](#getGrayscaleFloat32-internalized--) | 32 बिट्स प्रति पिक्सेल के लिए परिभाषित [PixelDataFormat](../../com.aspose.psd/pixeldataformat) प्राप्त करता है, जो फ्लोटिंग पॉइंट फ़ॉर्मेट में ग्रेस्केल तीव्रता को दर्शाता है। |
| [getPixelFormat()](#getPixelFormat--) | पिक्सेल फ़ॉर्मेट प्राप्त करता है। |
| [getRgb(int bitsPerSample)](#getRgb-int-) | निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ RGB रंग प्राप्त करता है। |
| [getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)](#getRgb-int-int-int-) | निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ RGB रंग प्राप्त करता है। |
| [getRgb16Bpp555()](#getRgb16Bpp555--) | 16 बिट्स प्रति पिक्सेल के लिए परिभाषित  PixelDataFormat  प्राप्त करता है, जिसमें लाल, हरा और नीला प्रत्येक के लिए 5 बिट्स होते हैं, अल्फा परिभाषित नहीं है। |
| [getRgb16Bpp565()](#getRgb16Bpp565--) | 16 बिट्स प्रति पिक्सेल के लिए परिभाषित  PixelDataFormat  प्राप्त करता है, जिसमें लाल के लिए 5 बिट्स, हरे के लिए 6 बिट्स और नीले के लिए 5 बिट्स होते हैं, अल्फा परिभाषित नहीं है। |
| [getRgb24Bpp()](#getRgb24Bpp--) | 24 बिट्स प्रति पिक्सेल के लिए परिभाषित  PixelDataFormat  प्राप्त करता है, जिसमें अल्फा, लाल, हरा और नीला प्रत्येक के लिए 8 बिट्स होते हैं, अल्फा परिभाषित नहीं है। |
| [getRgb24BppPng()](#getRgb24BppPng--) | 24 बिट्स प्रति पिक्सेल के लिए परिभाषित  PixelDataFormat  प्राप्त करता है, जिसमें अल्फा, लाल, हरा और नीला प्रत्येक के लिए 8 बिट्स होते हैं, अल्फा परिभाषित नहीं है। |
| [getRgb32Bpp()](#getRgb32Bpp--) | 32 बिट्स प्रति पिक्सेल के लिए परिभाषित  PixelDataFormat  प्राप्त करता है, जिसमें अल्फा, लाल, हरा और नीला प्रत्येक के लिए 8 बिट्स होते हैं। |
| [getRgbIndexed(int bitsPerSample)](#getRgbIndexed-int-) | निर्दिष्ट नमूना प्रति बिट की संख्या के साथ BGRA अनुक्रमित रंग प्राप्त करता है। |
| [getRgbIndexed1Bpp()](#getRgbIndexed1Bpp--) | 1 बिट प्रति रंग के लिए परिभाषित अनुक्रमित PixelDataFormat प्राप्त करता है। |
| [getRgbIndexed2Bpp()](#getRgbIndexed2Bpp--) | 2 बिट प्रति रंग के लिए परिभाषित अनुक्रमित PixelDataFormat प्राप्त करता है। |
| [getRgbIndexed4Bpp()](#getRgbIndexed4Bpp--) | 4 बिट प्रति रंग के लिए परिभाषित अनुक्रमित PixelDataFormat प्राप्त करता है। |
| [getRgbIndexed8Bpp()](#getRgbIndexed8Bpp--) | 8 बिट प्रति रंग के लिए परिभाषित अनुक्रमित PixelDataFormat प्राप्त करता है। |
| [getRgba(int bitsPerSample)](#getRgba-int-) | निर्दिष्ट नमूना प्रति बिट की संख्या के साथ RGBA रंग प्राप्त करता है। |
| [getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)](#getRgba-int-int-int-int-) | निर्दिष्ट नमूना प्रति बिट की संख्या के साथ RGBA रंग प्राप्त करता है। |
| [getRgba32Bpp()](#getRgba32Bpp--) | 32 बिट्स प्रति पिक्सेल के लिए परिभाषित  PixelDataFormat  प्राप्त करता है, जिसमें अल्फा, लाल, हरा और नीला प्रत्येक के लिए 8 बिट्स होते हैं। |
| [getRgba64Bpp()](#getRgba64Bpp--) | 64 बिट प्रति पिक्सेल के लिए परिभाषित, जिसमें अल्फा, लाल, हरा और नीला प्रत्येक के लिए 16 बिट हैं, ऐसा [PixelDataFormat](../../com.aspose.psd/pixeldataformat) प्राप्त करता है। |
| [getYCbCr()](#getYCbCr--) | 24 बिट प्रति पिक्सेल के लिए परिभाषित, जिसमें लुमा, ब्लू-डिफरेंस और रेड-डिफरेंस क्रोमा घटकों के प्रत्येक के लिए 8 बिट हैं, ऐसा PixelDataFormat प्राप्त करता है। |
| [getYCbCr(int bitsPerSample)](#getYCbCr-int-) | निर्दिष्ट नमूना प्रति बिट की संख्या के साथ YCbCr रंग प्राप्त करता है। |
| [getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)](#getYCbCr-int-int-int-) | निर्दिष्ट नमूना प्रति बिट की संख्या के साथ YCbCr रंग प्राप्त करता है। |
| [getYcck()](#getYcck--) | 32 बिट प्रति पिक्सेल के लिए परिभाषित, जिसमें लुमा, ब्लू-डिफरेंस, रेड-डिफरेंस और ब्लैक क्रोमा घटकों के प्रत्येक के लिए 8 बिट हैं, ऐसा PixelDataFormat प्राप्त करता है। |
| [getYcck(int bitsPerSample)](#getYcck-int-) | निर्दिष्ट नमूना प्रति बिट की संख्या के साथ YCCK रंग प्राप्त करता है। |
| [hashCode()](#hashCode--) | इस उदाहरण के लिए हैश कोड लौटाता है। |
| [isIndexed_internalized()](#isIndexed-internalized--) | यह दर्शाने वाला मान प्राप्त करता है कि यह उदाहरण अनुक्रमित है या नहीं। |
| [newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)](#newPixelDataFormat-internalized-int---int-java.lang.String-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | दो PixelDataFormat वर्गों की समानता का परिणाम लौटाता है। |
| [op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)](#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-) | दो PixelDataFormat वर्गों की असमानता का परिणाम लौटाता है। |
| [toString()](#toString--) | एक  System.String  लौटाता है जो इस उदाहरण का प्रतिनिधित्व करता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


निर्धारित करता है कि निर्दिष्ट  System.Object  इस इंस्टेंस के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | इस उदाहरण से तुलना करने के लिए  **System.Object**  । |

**Returns:**
boolean - true यदि निर्दिष्ट System.Object इस उदाहरण के बराबर है; अन्यथा false।
### getBgr(int bitsPerSample) {#getBgr-int-}
```
public static PixelDataFormat getBgr(int bitsPerSample)
```


निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ BGR रंग प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitsPerSample | int | प्रति नमूना बिटों की संख्या। |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGR color.
### getBgra(int bitsPerSample) {#getBgra-int-}
```
public static PixelDataFormat getBgra(int bitsPerSample)
```


निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ BGRA रंग प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitsPerSample | int | प्रति नमूना बिटों की संख्या। |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


प्रति पिक्सेल बिट्स प्राप्त करता है।

**Returns:**
int - प्रति पिक्सेल बिट।
### getCaption() {#getCaption--}
```
public String getCaption()
```


पिक्सेल डेटा फ़ॉर्मेट कैप्शन प्राप्त करता है।

**Returns:**
java.lang.String
### getChannelBits() {#getChannelBits--}
```
public int[] getChannelBits()
```


प्रत्येक चैनल के लिए बिट्स की गिनती प्राप्त करता है।

**Returns:**
int[] - चैनल बिट।
### getChannelsCount() {#getChannelsCount--}
```
public int getChannelsCount()
```


चैनल की गिनती प्राप्त करता है।

**Returns:**
int - चैनलों की गिनती।
### getCieLab(int bitsPerL, int bitsPerA, int bitsPerB) {#getCieLab-int-int-int-}
```
public static PixelDataFormat getCieLab(int bitsPerL, int bitsPerA, int bitsPerB)
```


निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ CIE Lab रंग प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitsPerL | int | L चैनल प्रति बिटों की संख्या। |
| bitsPerA | int | A चैनल प्रति बिटों की संख्या। |
| bitsPerB | int | B चैनल प्रति बिटों की संख्या। |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CIE Lab color.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCmyk() {#getCmyk--}
```
public static PixelDataFormat getCmyk()
```


32 बिट्स प्रति पिक्सेल के लिए परिभाषित  PixelDataFormat  प्राप्त करता है, जिसमें सियान, मैजेंटा, येलो और ब्लैक के प्रत्येक के लिए 8 बिट्स होते हैं।

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the cyan, magenta, yellow and black.
### getCmyk(int bitsPerSample) {#getCmyk-int-}
```
public static PixelDataFormat getCmyk(int bitsPerSample)
```


निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ CMYK रंग प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitsPerSample | int | प्रति नमूना बिटों की संख्या। |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel) {#getCmyk-int-int-int-int-}
```
public static PixelDataFormat getCmyk(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel)
```


निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ CMYK रंग प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitsPerCyanChannel | int | Cyan चैनल के प्रति बिटों की संख्या। |
| bitsPerMagentaChannel | int | Magenta चैनल के प्रति बिटों की संख्या। |
| bitsPerYellowChannel | int | Yellow चैनल के प्रति बिटों की संख्या। |
| bitsPerKeyChannel | int | Key चैनल के प्रति बिटों की संख्या। |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyk16() {#getCmyk16--}
```
public static PixelDataFormat getCmyk16()
```


64 बिट्स प्रति पिक्सेल के लिए परिभाषित [PixelDataFormat](../../com.aspose.psd/pixeldataformat) प्राप्त करता है, जिसमें सियान, मैजेंटा, येलो और ब्लैक के प्रत्येक के लिए 16 बिट्स होते हैं।

मान: 64 बिट प्रति पिक्सेल के लिए परिभाषित [PixelDataFormat](../../com.aspose.psd/pixeldataformat) जिसमें स्यान, मैजेंटा, येलो और ब्लैक के प्रत्येक के लिए 16 बिट होते हैं।

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getCmyka() {#getCmyka--}
```
public static PixelDataFormat getCmyka()
```


acmyk प्राप्त करता है।

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 40 bits per pixel with 8 bits for each of the alpha, cyan, magenta, yellow and black.
### getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel) {#getCmyka-int-int-int-int-int-}
```
public static PixelDataFormat getCmyka(int bitsPerCyanChannel, int bitsPerMagentaChannel, int bitsPerYellowChannel, int bitsPerKeyChannel, int bitsPerAlphaChannel)
```


निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ CMYKA रंग प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitsPerCyanChannel | int | Cyan चैनल के प्रति बिटों की संख्या। |
| bitsPerMagentaChannel | int | Magenta चैनल के प्रति बिटों की संख्या। |
| bitsPerYellowChannel | int | Yellow चैनल के प्रति बिटों की संख्या। |
| bitsPerKeyChannel | int | Key चैनल के प्रति बिटों की संख्या। |
| bitsPerAlphaChannel | int | Alpha चैनल के प्रति बिटों की संख्या। |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The CMYK color.
### getCmyka16() {#getCmyka16--}
```
public static PixelDataFormat getCmyka16()
```


acmyk प्राप्त करता है।

मान: 80 बिट प्रति पिक्सेल के लिए परिभाषित [PixelDataFormat](../../com.aspose.psd/pixeldataformat) जिसमें अल्फा, स्यान, मैजेंटा, येलो और ब्लैक के प्रत्येक के लिए 16 बिट होते हैं।

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getGrayscale() {#getGrayscale--}
```
public static PixelDataFormat getGrayscale()
```


8 बिट्स प्रति पिक्सेल के लिए परिभाषित  PixelDataFormat  प्राप्त करता है, जिसमें 0-255 अंतराल में ग्रेस्केल तीव्रता को दर्शाने के लिए 8 बिट्स होते हैं।

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 8 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval.
### getGrayscale(int bitsPerSample) {#getGrayscale-int-}
```
public static PixelDataFormat getGrayscale(int bitsPerSample)
```


निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ ग्रेस्केल रंग प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitsPerSample | int | प्रति नमूना बिटों की संख्या। |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The Grayscale color.
### getGrayscaleAlpha() {#getGrayscaleAlpha--}
```
public static PixelDataFormat getGrayscaleAlpha()
```


16 बिट्स प्रति पिक्सेल के लिए परिभाषित  PixelDataFormat  प्राप्त करता है, जिसमें 0-255 अंतराल में ग्रेस्केल तीव्रता को दर्शाने के लिए 8 बिट्स और अतिरिक्त 8 बिट अल्फा घटक होता है।

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 8 bits representing grayscale intensity in the 0-255 interval and additional 8 bit alpha component.
### getGrayscaleAlpha(int bitsPerSample) {#getGrayscaleAlpha-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample)
```


निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ GrayscaleAlpha रंग प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitsPerSample | int | प्रति नमूना बिटों की संख्या। |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits) {#getGrayscaleAlpha-int-int-}
```
public static PixelDataFormat getGrayscaleAlpha(int bitsPerSample, int alphaChannelBits)
```


निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ GrayscaleAlpha रंग प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitsPerSample | int | प्रति नमूना बिटों की संख्या। |
| alphaChannelBits | int | अल्फा चैनल में प्रत्येक सैंपल के लिए बिटों की संख्या। |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The GrayscaleAlpha color.
### getGrayscaleFloat32_internalized() {#getGrayscaleFloat32-internalized--}
```
public static PixelDataFormat getGrayscaleFloat32_internalized()
```


32 बिट्स प्रति पिक्सेल के लिए परिभाषित [PixelDataFormat](../../com.aspose.psd/pixeldataformat) प्राप्त करता है, जो फ्लोटिंग पॉइंट फ़ॉर्मेट में ग्रेस्केल तीव्रता को दर्शाता है।

मान: 32 बिट प्रति पिक्सेल के लिए परिभाषित [PixelDataFormat](../../com.aspose.psd/pixeldataformat) जो फ्लोटिंग पॉइंट फॉर्मेट में ग्रेस्केल तीव्रता को दर्शाता है।

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - the [PixelDataFormat](../../com.aspose.psd/pixeldataformat) defined for 32 bits per pixel representing grayscale intensity in floating point format.
### getPixelFormat() {#getPixelFormat--}
```
public int getPixelFormat()
```


पिक्सेल फ़ॉर्मेट प्राप्त करता है।

**Returns:**
int - पिक्सेल फॉर्मेट।
### getRgb(int bitsPerSample) {#getRgb-int-}
```
public static PixelDataFormat getRgb(int bitsPerSample)
```


निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ RGB रंग प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitsPerSample | int | प्रति नमूना बिटों की संख्या। |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel) {#getRgb-int-int-int-}
```
public static PixelDataFormat getRgb(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel)
```


निर्दिष्ट संख्या में बिट्स प्रति सैंपल के साथ RGB रंग प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitsPerRedChannel | int | Red चैनल के प्रति बिटों की संख्या। |
| bitsPerGreenChannel | int | Green चैनल के प्रति बिटों की संख्या। |
| bitsPerBlueChannel | int | Blue चैनल के प्रति बिटों की संख्या। |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGB color.
### getRgb16Bpp555() {#getRgb16Bpp555--}
```
public static PixelDataFormat getRgb16Bpp555()
```


16 बिट्स प्रति पिक्सेल के लिए परिभाषित  PixelDataFormat  प्राप्त करता है, जिसमें लाल, हरा और नीला प्रत्येक के लिए 5 बिट्स होते हैं, अल्फा परिभाषित नहीं है।

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for each of the red, green and blue, alpha is not defined.
### getRgb16Bpp565() {#getRgb16Bpp565--}
```
public static PixelDataFormat getRgb16Bpp565()
```


16 बिट्स प्रति पिक्सेल के लिए परिभाषित  PixelDataFormat  प्राप्त करता है, जिसमें लाल के लिए 5 बिट्स, हरे के लिए 6 बिट्स और नीले के लिए 5 बिट्स होते हैं, अल्फा परिभाषित नहीं है।

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 16 bits per pixel with 5 bits for red, 6 bits for green and 5 bits for blue, alpha is not defined.
### getRgb24Bpp() {#getRgb24Bpp--}
```
public static PixelDataFormat getRgb24Bpp()
```


24 बिट्स प्रति पिक्सेल के लिए परिभाषित  PixelDataFormat  प्राप्त करता है, जिसमें अल्फा, लाल, हरा और नीला प्रत्येक के लिए 8 बिट्स होते हैं, अल्फा परिभाषित नहीं है।

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb24BppPng() {#getRgb24BppPng--}
```
public static PixelDataFormat getRgb24BppPng()
```


24 बिट्स प्रति पिक्सेल के लिए परिभाषित  PixelDataFormat  प्राप्त करता है, जिसमें अल्फा, लाल, हरा और नीला प्रत्येक के लिए 8 बिट्स होते हैं, अल्फा परिभाषित नहीं है।

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the alpha, red, green and blue, alpha is not defined.
### getRgb32Bpp() {#getRgb32Bpp--}
```
public static PixelDataFormat getRgb32Bpp()
```


32 बिट्स प्रति पिक्सेल के लिए परिभाषित  PixelDataFormat  प्राप्त करता है, जिसमें अल्फा, लाल, हरा और नीला प्रत्येक के लिए 8 बिट्स होते हैं।

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgbIndexed(int bitsPerSample) {#getRgbIndexed-int-}
```
public static PixelDataFormat getRgbIndexed(int bitsPerSample)
```


निर्दिष्ट नमूना प्रति बिट की संख्या के साथ BGRA अनुक्रमित रंग प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitsPerSample | int | प्रति नमूना बिटों की संख्या। |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The BGRA color.
### getRgbIndexed1Bpp() {#getRgbIndexed1Bpp--}
```
public static PixelDataFormat getRgbIndexed1Bpp()
```


इंडेक्स्ड 1 बिट प्रति रंग के लिए परिभाषित  PixelDataFormat  प्राप्त करता है। इंडेक्स्ड पिक्सेल डेटा स्टोरेज का उद्देश्य डेटा स्टोरेज और पुनर्प्राप्ति को सभी स्थानों पर सक्षम करना है जहाँ रंग पैलेट का उपयोग किया जाता है। सावधानी से उपयोग करें, क्योंकि यह एक पैलेट से दूसरे पैलेट या RGBA से इंडेक्स्ड कलर मॉडल में रूपांतरण की आवश्यकता हो सकती है।

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 1 bit per color.
### getRgbIndexed2Bpp() {#getRgbIndexed2Bpp--}
```
public static PixelDataFormat getRgbIndexed2Bpp()
```


इंडेक्स्ड 2 बिट प्रति रंग के लिए परिभाषित  PixelDataFormat  प्राप्त करता है। इंडेक्स्ड पिक्सेल डेटा स्टोरेज का उद्देश्य डेटा स्टोरेज और पुनर्प्राप्ति को सभी स्थानों पर सक्षम करना है जहाँ रंग पैलेट का उपयोग किया जाता है। सावधानी से उपयोग करें, क्योंकि यह एक पैलेट से दूसरे पैलेट या RGBA से इंडेक्स्ड कलर मॉडल में रूपांतरण की आवश्यकता हो सकती है।

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 2 bit per color.
### getRgbIndexed4Bpp() {#getRgbIndexed4Bpp--}
```
public static PixelDataFormat getRgbIndexed4Bpp()
```


इंडेक्स्ड 4 बिट प्रति रंग के लिए परिभाषित  PixelDataFormat  प्राप्त करता है। इंडेक्स्ड पिक्सेल डेटा स्टोरेज का उद्देश्य डेटा स्टोरेज और पुनर्प्राप्ति को सभी स्थानों पर सक्षम करना है जहाँ रंग पैलेट का उपयोग किया जाता है। सावधानी से उपयोग करें, क्योंकि यह एक पैलेट से दूसरे पैलेट या RGBA से इंडेक्स्ड कलर मॉडल में रूपांतरण की आवश्यकता हो सकती है।

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 4 bit per color.
### getRgbIndexed8Bpp() {#getRgbIndexed8Bpp--}
```
public static PixelDataFormat getRgbIndexed8Bpp()
```


प्राप्त करता है  PixelDataFormat  जो कि इंडेक्स्ड 8 बिट प्रति रंग के लिए परिभाषित है। इंडेक्स्ड पिक्सेल डेटा स्टोरेज का उद्देश्य डेटा स्टोरेज और पुनर्प्राप्ति को हर जगह सक्षम बनाना है जहाँ रंग पैलेट का उपयोग होता है। सावधानी से उपयोग करें, क्योंकि यह एक पैलेट से दूसरे पैलेट में या RGBA से इंडेक्स्ड कलर मॉडल में रूपांतरण की आवश्यकता हो सकती है।

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for indexed 8 bit per color.
### getRgba(int bitsPerSample) {#getRgba-int-}
```
public static PixelDataFormat getRgba(int bitsPerSample)
```


निर्दिष्ट नमूना प्रति बिट की संख्या के साथ RGBA रंग प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitsPerSample | int | प्रति नमूना बिटों की संख्या। |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel) {#getRgba-int-int-int-int-}
```
public static PixelDataFormat getRgba(int bitsPerRedChannel, int bitsPerGreenChannel, int bitsPerBlueChannel, int bitsPerAlphaChannel)
```


निर्दिष्ट नमूना प्रति बिट की संख्या के साथ RGBA रंग प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitsPerRedChannel | int | Red चैनल के प्रति बिटों की संख्या। |
| bitsPerGreenChannel | int | Green चैनल के प्रति बिटों की संख्या। |
| bitsPerBlueChannel | int | Blue चैनल के प्रति बिटों की संख्या। |
| bitsPerAlphaChannel | int | Alpha चैनल के प्रति बिटों की संख्या। |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The RGBA color.
### getRgba32Bpp() {#getRgba32Bpp--}
```
public static PixelDataFormat getRgba32Bpp()
```


32 बिट्स प्रति पिक्सेल के लिए परिभाषित  PixelDataFormat  प्राप्त करता है, जिसमें अल्फा, लाल, हरा और नीला प्रत्येक के लिए 8 बिट्स होते हैं।

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the alpha, red, green and blue.
### getRgba64Bpp() {#getRgba64Bpp--}
```
public static PixelDataFormat getRgba64Bpp()
```


64 बिट प्रति पिक्सेल के लिए परिभाषित, जिसमें अल्फा, लाल, हरा और नीला प्रत्येक के लिए 16 बिट हैं, ऐसा [PixelDataFormat](../../com.aspose.psd/pixeldataformat) प्राप्त करता है।

मान: The [PixelDataFormat](../../com.aspose.psd/pixeldataformat) जो 64 बिट प्रति पिक्सेल के लिए परिभाषित है, जिसमें अल्फा, लाल, हरा और नीला प्रत्येक के लिए 16 बिट होते हैं।

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### getYCbCr() {#getYCbCr--}
```
public static PixelDataFormat getYCbCr()
```


24 बिट प्रति पिक्सेल के लिए परिभाषित, जिसमें लुमा, ब्लू-डिफरेंस और रेड-डिफरेंस क्रोमा घटकों के प्रत्येक के लिए 8 बिट हैं, ऐसा PixelDataFormat प्राप्त करता है।

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 24 bits per pixel with 8 bits for each of the luma, blue-difference and red-difference chroma components.
### getYCbCr(int bitsPerSample) {#getYCbCr-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerSample)
```


निर्दिष्ट नमूना प्रति बिट की संख्या के साथ YCbCr रंग प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitsPerSample | int | प्रति नमूना बिटों की संख्या। |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr) {#getYCbCr-int-int-int-}
```
public static PixelDataFormat getYCbCr(int bitsPerY, int bitsPerCb, int bitsPerCr)
```


निर्दिष्ट नमूना प्रति बिट की संख्या के साथ YCbCr रंग प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitsPerY | int | Y चैनल प्रति बिट की संख्या। |
| bitsPerCb | int | Cb चैनल प्रति बिट की संख्या। |
| bitsPerCr | int | Cr चैनल प्रति बिट की संख्या। |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCbCr color.
### getYcck() {#getYcck--}
```
public static PixelDataFormat getYcck()
```


32 बिट प्रति पिक्सेल के लिए परिभाषित, जिसमें लुमा, ब्लू-डिफरेंस, रेड-डिफरेंस और ब्लैक क्रोमा घटकों के प्रत्येक के लिए 8 बिट हैं, ऐसा PixelDataFormat प्राप्त करता है।

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The  PixelDataFormat  defined for 32 bits per pixel with 8 bits for each of the luma, blue-difference, red-difference and black chroma components.
### getYcck(int bitsPerSample) {#getYcck-int-}
```
public static PixelDataFormat getYcck(int bitsPerSample)
```


निर्दिष्ट नमूना प्रति बिट की संख्या के साथ YCCK रंग प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bitsPerSample | int | प्रति नमूना बिटों की संख्या। |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat) - The YCCK color.
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस उदाहरण के लिए हैश कोड लौटाता है।

**Returns:**
int - इस उदाहरण के लिए एक हैश कोड, जो हैशिंग एल्गोरिदम और हैश टेबल जैसी डेटा संरचनाओं में उपयोग के लिए उपयुक्त है।
### isIndexed_internalized() {#isIndexed-internalized--}
```
public final boolean isIndexed_internalized()
```


यह दर्शाने वाला मान प्राप्त करता है कि यह उदाहरण अनुक्रमित है या नहीं।

मान:  true  यदि यह इंस्टेंस इंडेक्स्ड है; अन्यथा,  false .

**Returns:**
boolean - एक मान जो दर्शाता है कि यह इंस्टेंस इंडेक्स्ड है या नहीं।
### newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption) {#newPixelDataFormat-internalized-int---int-java.lang.String-}
```
public static PixelDataFormat newPixelDataFormat_internalized(int[] channelBits, int pixelFormat, String caption)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| channelBits | int[] |  |
| pixelFormat | int |  |
| caption | java.lang.String |  |

**Returns:**
[PixelDataFormat](../../com.aspose.psd/pixeldataformat)
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Equality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Equality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


दो PixelDataFormat वर्गों की समानता का परिणाम लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | पहला  PixelDataFormat  तुलना के लिए। |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | दूसरा  PixelDataFormat  तुलना के लिए। |

**Returns:**
boolean - True यदि दोनों  pixelFormat1  और  pixelFormat2  समान डेटा रखते हैं या दोनों पैरामीटर null हैं।
### op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2) {#op-Inequality-com.aspose.psd.PixelDataFormat-com.aspose.psd.PixelDataFormat-}
```
public static boolean op_Inequality(PixelDataFormat pixelFormat1, PixelDataFormat pixelFormat2)
```


दो PixelDataFormat वर्गों की असमानता का परिणाम लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pixelFormat1 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | पहला  PixelDataFormat  तुलना के लिए। |
| pixelFormat2 | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | दूसरा  PixelDataFormat  तुलना के लिए। |

**Returns:**
boolean - True यदि दोनों  pixelFormat1  और  pixelFormat2  असमान डेटा रखते हैं या किसी एक पैरामीटर का मान null है।
### toString() {#toString--}
```
public String toString()
```


एक  System.String  लौटाता है जो इस उदाहरण का प्रतिनिधित्व करता है।

**Returns:**
java.lang.String - एक  System.String  जो इस उदाहरण का प्रतिनिधित्व करता है।
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

