---
title: "GrdmResource"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "क्लास GrdmResource."
type: docs
weight: 35
url: /hi/java/com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource), [com.aspose.psd.fileformats.psd.layers.layerresources.AdjustmentLayerResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource)
```
public class GrdmResource extends AdjustmentLayerResource
```

GrdmResource क्लास। Gradient-Map लेयर के बारे में जानकारी शामिल है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [GrdmResource()](#GrdmResource--) |  |
| [GrdmResource(int psdVersion)](#GrdmResource-int-) | [GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource) क्लास का नया उदाहरण प्रारंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [DefaultScale_internalized](#DefaultScale-internalized) | डिफ़ॉल्ट स्केल। |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | PSB हेडर संस्करण। |
| [PsbResourceSignature](#PsbResourceSignature) | PSB-विशिष्ट रिसोर्स सिग्नेचर। |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | PSD हेडर संस्करण। |
| [ResourceSignature](#ResourceSignature) | सामान्य रिसोर्स सिग्नेचर। |
| [TypeToolKey](#TypeToolKey) | टाइप टूल जानकारी कुंजी। |
| [ventureLicense_internalized](#ventureLicense-internalized) | वेंचर लाइसेंस। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | जांचता है और सेट करता है यदि रिसोर्स PSB-विशिष्ट है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColorModel()](#getColorModel--) | रंग मॉडल। |
| [getColorPoints()](#getColorPoints--) | रंग बिंदुओं को प्राप्त करता है या सेट करता है। |
| [getData()](#getData--) | डेटा को प्राप्त करता है या सेट करता है। |
| [getDither()](#getDither--) | क्या ग्रेडिएंट डिथर किया गया है। |
| [getExpansionCount()](#getExpansionCount--) | विस्तार गणना ( = Photoshop 6.0 के लिए 2)। |
| [getGradientLength_internalized()](#getGradientLength-internalized--) | लंबाई(= Photoshop 6.0 के लिए 32) इसके जिम्मेदार होने के बारे में कोई जानकारी नहीं। |
| [getGradientMode()](#getGradientMode--) | इस ग्रेडिएंट का मोड निर्धारित करता है 'Gradient Type' = 'Solid/Noise' (0/1)। |
| [getGradientName()](#getGradientName--) | ग्रेडिएंट का नाम: यूनिकोड स्ट्रिंग, पैडेड। |
| [getHeader_internalized()](#getHeader-internalized--) | हेडर को प्राप्त करता है या सेट करता है। |
| [getInterpolation()](#getInterpolation--) | इंटरपोलेशन। |
| [getInterpolationMethod()](#getInterpolationMethod--) | ग्रेडिएंट के लिए इंटरपोलेशन विधि प्राप्त करता है या सेट करता है। |
| [getKey()](#getKey--) | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| [getLength()](#getLength--) | लेयर रिसोर्स की लंबाई बाइट्स में प्राप्त करता है। |
| [getMaximumColor()](#getMaximumColor--) | PixelDataFormat.Rgba64Bpp फ़ॉर्मेट का अधिकतम रंग। |
| [getMinimumColor()](#getMinimumColor--) | PixelDataFormat.Rgba64Bpp फ़ॉर्मेट का न्यूनतम रंग। |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | प्रिफिक्स लंबाई प्राप्त करता है। |
| [getPsdVersion()](#getPsdVersion--) | इस संसाधन के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। |
| [getReverse()](#getReverse--) | क्या ग्रेडिएंट उलटा है। |
| [getRndNumberSeed()](#getRndNumberSeed--) | नॉइज़ ग्रेडिएंट के लिए रंग उत्पन्न करने में उपयोग किया जाने वाला रैंडम नंबर सीड। |
| [getRoughness()](#getRoughness--) | रफ़नेस फ़ैक्टर जब 'Gradient type' = 'Noise' हो, तो हम 'Roughness' (0 - 2048) असाइन कर सकते हैं। |
| [getShowTransparency()](#getShowTransparency--) | पारदर्शिता दिखाने का फ़्लैग जब 'Gradient type' = 'Noise' हो, तो हम 'Add transparency' को true सेट कर सकते हैं। |
| [getSignature()](#getSignature--) | लेयर रिसोर्स सिग्नेचर प्राप्त करता है। |
| [getTransparencyPoints()](#getTransparencyPoints--) | पारदर्शिता बिंदुओं को प्राप्त करता है या सेट करता है। |
| [getUseVectorColor()](#getUseVectorColor--) | वेक्टर रंग उपयोग करने के लिए फ़्लैग। |
| [hashCode()](#hashCode--) |  |
| [initGradientLength_internalized(short value)](#initGradientLength-internalized-short-) | ग्रेडिएंट की लंबाई को प्रारंभ करता है। |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | निर्धारित करता है कि रिसोर्स PSB-विशिष्ट है या नहीं। |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | एक मान प्राप्त करता है जो दर्शाता है कि यह इंस्टेंस रिसोर्स PSB-विशिष्ट है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | संसाधन डेटा को निर्दिष्ट स्ट्रीम कंटेनर में सहेजता है। |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | कस्टम रिसोर्स हेडर को सहेजता है। |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | हेडर सिग्नेचर, पहचानकर्ता और लंबाई को सहेजता है। |
| [setColorModel(short value)](#setColorModel-short-) | रंग मॉडल। |
| [setColorPoints(IGradientColorPoint[] value)](#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---) | रंग बिंदुओं को प्राप्त करता है या सेट करता है। |
| [setDither(boolean value)](#setDither-boolean-) | क्या ग्रेडिएंट डिथर किया गया है। |
| [setExpansionCount(short value)](#setExpansionCount-short-) | विस्तार गणना ( = Photoshop 6.0 के लिए 2)। |
| [setGradientMode(int value)](#setGradientMode-int-) | इस ग्रेडिएंट का मोड निर्धारित करता है 'Gradient Type' = 'Solid/Noise' (0/1)। |
| [setGradientName(String value)](#setGradientName-java.lang.String-) | ग्रेडिएंट का नाम: यूनिकोड स्ट्रिंग, पैडेड। |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | हेडर को प्राप्त करता है या सेट करता है। |
| [setInterpolation(short value)](#setInterpolation-short-) | इंटरपोलेशन। |
| [setInterpolationMethod(long value)](#setInterpolationMethod-long-) | ग्रेडिएंट के लिए इंटरपोलेशन विधि प्राप्त करता है या सेट करता है। |
| [setMaximumColor(RawColor value)](#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat.Rgba64Bpp फ़ॉर्मेट का अधिकतम रंग। |
| [setMinimumColor(RawColor value)](#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | PixelDataFormat.Rgba64Bpp फ़ॉर्मेट का न्यूनतम रंग। |
| [setReverse(boolean value)](#setReverse-boolean-) | क्या ग्रेडिएंट उलटा है। |
| [setRndNumberSeed(int value)](#setRndNumberSeed-int-) | नॉइज़ ग्रेडिएंट के लिए रंग उत्पन्न करने में उपयोग किया जाने वाला रैंडम नंबर सीड। |
| [setRoughness(int value)](#setRoughness-int-) | रफ़नेस फ़ैक्टर जब 'Gradient type' = 'Noise' हो, तो हम 'Roughness' (0 - 2048) असाइन कर सकते हैं। |
| [setShowTransparency(short value)](#setShowTransparency-short-) | पारदर्शिता दिखाने का फ़्लैग जब 'Gradient type' = 'Noise' हो, तो हम 'Add transparency' को true सेट कर सकते हैं। |
| [setTransparencyPoints(IGradientTransparencyPoint[] value)](#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---) | पारदर्शिता बिंदुओं को प्राप्त करता है या सेट करता है। |
| [setUseVectorColor(short value)](#setUseVectorColor-short-) | वेक्टर रंग उपयोग करने के लिए फ़्लैग। |
| [toString()](#toString--) | इस इंस्टेंस का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GrdmResource() {#GrdmResource--}
```
public GrdmResource()
```


### GrdmResource(int psdVersion) {#GrdmResource-int-}
```
public GrdmResource(int psdVersion)
```


[GrdmResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/grdmresource) क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| psdVersion | int | संसाधन का PSD संस्करण। |

### DefaultScale_internalized {#DefaultScale-internalized}
```
public static final int DefaultScale_internalized
```


डिफ़ॉल्ट स्केल।

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


PSB हेडर संस्करण।

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


PSB-विशिष्ट रिसोर्स सिग्नेचर।

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


PSD हेडर संस्करण।

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


सामान्य रिसोर्स सिग्नेचर।

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


टाइप टूल जानकारी कुंजी।

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


वेंचर लाइसेंस।

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


जाँचता है और सेट करता है कि रिसोर्स PSB‑विशिष्ट है या नहीं। कुछ रिसोर्स अभी पहचाने नहीं गए हैं, लेकिन हमारे पास PSB‑विशिष्ट रिसोर्स की पूरी सूची है जो सहेजने पर उनके व्यवहार को बदलती है। इसलिए हमें कम से कम UnknownResource में इसे जाँचने की आवश्यकता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | int | कुंजी। |

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
### getColorModel() {#getColorModel--}
```
public final short getColorModel()
```


रंग मॉडल। जब 'Gradient type' = 'Noise' हो, तो हम 'Color Model' को RGB/SHB/LAB (3/4/6) असाइन कर सकते हैं।

**Returns:**
short
### getColorPoints() {#getColorPoints--}
```
public final IGradientColorPoint[] getColorPoints()
```


रंग बिंदुओं को प्राप्त करता है या सेट करता है।

मान: रंग बिंदु।

**Returns:**
com.aspose.psd.fileformats.psd.layers.IGradientColorPoint[]
### getData() {#getData--}
```
public final byte[] getData()
```


डेटा को प्राप्त करता है या सेट करता है।

मान: डेटा।

**Returns:**
byte[]
### getDither() {#getDither--}
```
public final boolean getDither()
```


क्या ग्रेडिएंट डिथर किया गया है।

**Returns:**
boolean
### getExpansionCount() {#getExpansionCount--}
```
public final short getExpansionCount()
```


विस्तार गणना ( = Photoshop 6.0 के लिए 2)।

**Returns:**
short
### getGradientLength_internalized() {#getGradientLength-internalized--}
```
public final short getGradientLength_internalized()
```


लंबाई(= Photoshop 6.0 के लिए 32) इसके जिम्मेदार होने के बारे में कोई जानकारी नहीं।

**Returns:**
short
### getGradientMode() {#getGradientMode--}
```
public final int getGradientMode()
```


इस ग्रेडिएंट का मोड निर्धारित करता है 'Gradient Type' = 'Solid/Noise' (0/1)।

**Returns:**
int
### getGradientName() {#getGradientName--}
```
public final String getGradientName()
```


ग्रेडिएंट का नाम: यूनिकोड स्ट्रिंग, पैडेड।

**Returns:**
java.lang.String
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


हेडर को प्राप्त करता है या सेट करता है।

मान: हेडर।

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getInterpolation() {#getInterpolation--}
```
public final short getInterpolation()
```


इंटरपोलेशन। जब 'Gradient Type' = 'Solid' (GradientMode = 0) हो, तो स्मूदनेस निर्धारित करता है।

**Returns:**
short
### getInterpolationMethod() {#getInterpolationMethod--}
```
public final long getInterpolationMethod()
```


ग्रेडिएंट के लिए इंटरपोलेशन विधि प्राप्त करता है या सेट करता है।

**Returns:**
long
### getKey() {#getKey--}
```
public final int getKey()
```


लेयर रिसोर्स कुंजी प्राप्त करता है।

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


लेयर रिसोर्स की लंबाई बाइट्स में प्राप्त करता है।

**Returns:**
int
### getMaximumColor() {#getMaximumColor--}
```
public final RawColor getMaximumColor()
```


PixelDataFormat.Rgba64Bpp फ़ॉर्मेट का अधिकतम रंग। रंग में ARGB चैनल होते हैं, प्रत्येक चैनल 16 बिट है।

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getMinimumColor() {#getMinimumColor--}
```
public final RawColor getMinimumColor()
```


PixelDataFormat.Rgba64Bpp फ़ॉर्मेट का न्यूनतम रंग। रंग में ARGB चैनल होते हैं, प्रत्येक चैनल 16 बिट है।

**Returns:**
[RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor)
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


प्रिफिक्स लंबाई प्राप्त करता है। डिफ़ॉल्ट मान 8BIM रिसोर्स के लिए 12 है और 8B64 के लिए 16 है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| psdVersion | int | PSD संस्करण। |

**Returns:**
int - प्रिफिक्स लंबाई।
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


इस संसाधन के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। जब इंटरपोलेशन विधि स्पष्ट रूप से संग्रहीत हो, तो संस्करण 3 आवश्यक है।

**Returns:**
int
### getReverse() {#getReverse--}
```
public final boolean getReverse()
```


क्या ग्रेडिएंट उलटा है।

**Returns:**
boolean
### getRndNumberSeed() {#getRndNumberSeed--}
```
public final int getRndNumberSeed()
```


नॉइज़ ग्रेडिएंट के लिए रंग उत्पन्न करने में उपयोग किया जाने वाला रैंडम नंबर सीड।

**Returns:**
int
### getRoughness() {#getRoughness--}
```
public final int getRoughness()
```


रफ़नेस फ़ैक्टर जब 'Gradient type' = 'Noise' हो, तो हम 'Roughness' (0 - 2048) असाइन कर सकते हैं।

**Returns:**
int
### getShowTransparency() {#getShowTransparency--}
```
public final short getShowTransparency()
```


पारदर्शिता दिखाने का फ़्लैग जब 'Gradient type' = 'Noise' हो, तो हम 'Add transparency' को true सेट कर सकते हैं।

**Returns:**
short
### getSignature() {#getSignature--}
```
public int getSignature()
```


लेयर रिसोर्स सिग्नेचर प्राप्त करता है।

**Returns:**
int
### getTransparencyPoints() {#getTransparencyPoints--}
```
public final IGradientTransparencyPoint[] getTransparencyPoints()
```


पारदर्शिता बिंदुओं को प्राप्त करता है या सेट करता है।

मान: पारदर्शिता बिंदु।

**Returns:**
com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint[]
### getUseVectorColor() {#getUseVectorColor--}
```
public final short getUseVectorColor()
```


वेक्टर रंग उपयोग करने के लिए फ़्लैग।

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initGradientLength_internalized(short value) {#initGradientLength-internalized-short-}
```
public final void initGradientLength_internalized(short value)
```


ग्रेडिएंट की लंबाई को प्रारंभ करता है। GradientLength केवल पढ़ने योग्य है, इसलिए इसे केवल एक बार असाइन किया जा सकता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short | मान। |

### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


निर्धारित करता है कि रिसोर्स PSB-विशिष्ट है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key | int | रिसोर्स कुंजी। |

**Returns:**
boolean - यदि रिसोर्स PSB‑विशिष्ट है तो true, अन्यथा false।
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


एक मान प्राप्त करता है जो दर्शाता है कि यह इंस्टेंस रिसोर्स PSB-विशिष्ट है या नहीं।

मान: यदि यह इंस्टेंस रिसोर्स PSB‑विशिष्ट है तो true, अन्यथा false।

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




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


संसाधन डेटा को निर्दिष्ट स्ट्रीम कंटेनर में सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |
| psdVersion | int | PSD संस्करण। |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


कस्टम रिसोर्स हेडर को सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |
| हस्ताक्षर | int | हस्ताक्षर। |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


हेडर सिग्नेचर, पहचानकर्ता और लंबाई को सहेजता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | स्ट्रीम कंटेनर। |
| हस्ताक्षर | int | हस्ताक्षर। |
| isLengthLong | boolean | यदि true सेट किया गया है तो लंबाई लंबी होती है। |

### setColorModel(short value) {#setColorModel-short-}
```
public final void setColorModel(short value)
```


रंग मॉडल। जब 'Gradient type' = 'Noise' हो, तो हम 'Color Model' को RGB/SHB/LAB (3/4/6) असाइन कर सकते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setColorPoints(IGradientColorPoint[] value) {#setColorPoints-com.aspose.psd.fileformats.psd.layers.IGradientColorPoint---}
```
public final void setColorPoints(IGradientColorPoint[] value)
```


रंग बिंदुओं को प्राप्त करता है या सेट करता है।

मान: रंग बिंदु।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IGradientColorPoint\[\]](../../com.aspose.psd.fileformats.psd.layers/igradientcolorpoint) |  |

### setDither(boolean value) {#setDither-boolean-}
```
public final void setDither(boolean value)
```


क्या ग्रेडिएंट डिथर किया गया है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setExpansionCount(short value) {#setExpansionCount-short-}
```
public final void setExpansionCount(short value)
```


विस्तार गणना ( = Photoshop 6.0 के लिए 2)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setGradientMode(int value) {#setGradientMode-int-}
```
public final void setGradientMode(int value)
```


इस ग्रेडिएंट का मोड निर्धारित करता है 'Gradient Type' = 'Solid/Noise' (0/1)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setGradientName(String value) {#setGradientName-java.lang.String-}
```
public final void setGradientName(String value)
```


ग्रेडिएंट का नाम: यूनिकोड स्ट्रिंग, पैडेड।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


हेडर को प्राप्त करता है या सेट करता है।

मान: हेडर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setInterpolation(short value) {#setInterpolation-short-}
```
public final void setInterpolation(short value)
```


इंटरपोलेशन। जब 'Gradient Type' = 'Solid' (GradientMode = 0) हो, तो स्मूदनेस निर्धारित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setInterpolationMethod(long value) {#setInterpolationMethod-long-}
```
public final void setInterpolationMethod(long value)
```


ग्रेडिएंट के लिए इंटरपोलेशन विधि प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | long |  |

### setMaximumColor(RawColor value) {#setMaximumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMaximumColor(RawColor value)
```


PixelDataFormat.Rgba64Bpp फ़ॉर्मेट का अधिकतम रंग। रंग में ARGB चैनल होते हैं, प्रत्येक चैनल 16 बिट है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setMinimumColor(RawColor value) {#setMinimumColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public final void setMinimumColor(RawColor value)
```


PixelDataFormat.Rgba64Bpp फ़ॉर्मेट का न्यूनतम रंग। रंग में ARGB चैनल होते हैं, प्रत्येक चैनल 16 बिट है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) |  |

### setReverse(boolean value) {#setReverse-boolean-}
```
public final void setReverse(boolean value)
```


क्या ग्रेडिएंट उलटा है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### setRndNumberSeed(int value) {#setRndNumberSeed-int-}
```
public final void setRndNumberSeed(int value)
```


नॉइज़ ग्रेडिएंट के लिए रंग उत्पन्न करने में उपयोग किया जाने वाला रैंडम नंबर सीड।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setRoughness(int value) {#setRoughness-int-}
```
public final void setRoughness(int value)
```


रफ़नेस फ़ैक्टर जब 'Gradient type' = 'Noise' हो, तो हम 'Roughness' (0 - 2048) असाइन कर सकते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setShowTransparency(short value) {#setShowTransparency-short-}
```
public final void setShowTransparency(short value)
```


पारदर्शिता दिखाने का फ़्लैग जब 'Gradient type' = 'Noise' हो, तो हम 'Add transparency' को true सेट कर सकते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setTransparencyPoints(IGradientTransparencyPoint[] value) {#setTransparencyPoints-com.aspose.psd.fileformats.psd.layers.fillsettings.IGradientTransparencyPoint---}
```
public final void setTransparencyPoints(IGradientTransparencyPoint[] value)
```


पारदर्शिता बिंदुओं को प्राप्त करता है या सेट करता है।

मान: पारदर्शिता बिंदु।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IGradientTransparencyPoint\[\]](../../com.aspose.psd.fileformats.psd.layers.fillsettings/igradienttransparencypoint) |  |

### setUseVectorColor(short value) {#setUseVectorColor-short-}
```
public final void setUseVectorColor(short value)
```


वेक्टर रंग उपयोग करने के लिए फ़्लैग।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### toString() {#toString--}
```
public String toString()
```


इस इंस्टेंस का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है।

**Returns:**
java.lang.String - इस इंस्टेंस का प्रतिनिधित्व करने वाली एक स्ट्रिंग।
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

