---
title: "TypeToolInfoResource"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "यह टाइप टूल जानकारी।"
type: docs
weight: 79
url: /hi/java/com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class TypeToolInfoResource extends LayerResource
```

टाइप टूल जानकारी। PSD संस्करण 6.0 से कम के लिए।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [TypeToolInfoResource()](#TypeToolInfoResource--) | नया उदाहरण प्रारंभ करता है [TypeToolInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource) क्लास का। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
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
| [getAComponent()](#getAComponent--) | किसी घटक को प्राप्त करता है या सेट करता है। |
| [getBComponent()](#getBComponent--) | b घटक को प्राप्त करता है या सेट करता है। |
| [getCharacterCount()](#getCharacterCount--) | अक्षर गिनती को प्राप्त करता है या सेट करता है। |
| [getClass()](#getClass--) |  |
| [getColorSpaceValue()](#getColorSpaceValue--) | रंग स्थान मान को प्राप्त करता है या सेट करता है। |
| [getFontVersion()](#getFontVersion--) | फ़ॉन्ट संस्करण को प्राप्त करता है या सेट करता है। |
| [getFonts()](#getFonts--) | फ़ॉन्ट्स को प्राप्त करता है या सेट करता है। |
| [getFontsCount()](#getFontsCount--) | फ़ॉन्ट्स की गिनती प्राप्त करता है। |
| [getGComponent()](#getGComponent--) | g घटक को प्राप्त करता है या सेट करता है। |
| [getHeader_internalized()](#getHeader-internalized--) | हेडर को प्राप्त करता है या सेट करता है। |
| [getHorizontalPlacement()](#getHorizontalPlacement--) | क्षैतिज प्लेसमेंट को प्राप्त करता है या सेट करता है। |
| [getKey()](#getKey--) | लेयर रिसोर्स कुंजी प्राप्त करता है। |
| [getLength()](#getLength--) | लेयर रिसोर्स की लंबाई बाइट्स में प्राप्त करता है। |
| [getLineCount()](#getLineCount--) | लाइन गिनती प्राप्त करता है। |
| [getLines()](#getLines--) | लाइन को प्राप्त करता है या सेट करता है। |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | प्रिफिक्स लंबाई प्राप्त करता है। |
| [getPsdVersion()](#getPsdVersion--) | लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। |
| [getRComponent()](#getRComponent--) | r घटक को प्राप्त करता है या सेट करता है। |
| [getScaleFactor()](#getScaleFactor--) | स्केल फैक्टर को प्राप्त करता है या सेट करता है। |
| [getSelectionEnd()](#getSelectionEnd--) | सेलेक्शन अंत को प्राप्त करता है या सेट करता है। |
| [getSelectionStart()](#getSelectionStart--) | चयन प्रारंभ को प्राप्त करता है या सेट करता है. |
| [getSignature()](#getSignature--) | लेयर रिसोर्स सिग्नेचर प्राप्त करता है। |
| [getStyles()](#getStyles--) | फ़ॉन्ट शैलियों को प्राप्त करता है या सेट करता है. |
| [getStylesCount()](#getStylesCount--) | शैलियों की गिनती प्राप्त करता है. |
| [getTransformMatrix()](#getTransformMatrix--) | रूपांतरण मैट्रिक्स को प्राप्त करता है या सेट करता है. |
| [getTypeValue()](#getTypeValue--) | प्रकार मान को प्राप्त करता है या सेट करता है. |
| [getVersion()](#getVersion--) | संस्करण को प्राप्त करता है या सेट करता है। |
| [getVerticalPlacement()](#getVerticalPlacement--) | ऊर्ध्वाधर प्लेसमेंट को प्राप्त करता है या सेट करता है. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | निर्धारित करता है कि रिसोर्स PSB-विशिष्ट है या नहीं। |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | एक मान प्राप्त करता है जो दर्शाता है कि यह इंस्टेंस रिसोर्स PSB-विशिष्ट है या नहीं। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | निर्दिष्ट स्ट्रीम कंटेनर को सहेजता है. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | कस्टम रिसोर्स हेडर को सहेजता है। |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | हेडर सिग्नेचर, पहचानकर्ता और लंबाई को सहेजता है। |
| [setAComponent(short value)](#setAComponent-short-) | किसी घटक को प्राप्त करता है या सेट करता है। |
| [setBComponent(short value)](#setBComponent-short-) | b घटक को प्राप्त करता है या सेट करता है। |
| [setCharacterCount(int value)](#setCharacterCount-int-) | अक्षर गिनती को प्राप्त करता है या सेट करता है। |
| [setColorDataRaw_internalized(byte[] value)](#setColorDataRaw-internalized-byte---) | रंग डेटा कच्चा को प्राप्त करता है या सेट करता है. |
| [setColorSpaceValue(short value)](#setColorSpaceValue-short-) | रंग स्थान मान को प्राप्त करता है या सेट करता है। |
| [setFontVersion(short value)](#setFontVersion-short-) | फ़ॉन्ट संस्करण को प्राप्त करता है या सेट करता है। |
| [setFonts(TypeToolFontInfo[] value)](#setFonts-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo---) | फ़ॉन्ट्स को प्राप्त करता है या सेट करता है। |
| [setGComponent(short value)](#setGComponent-short-) | g घटक को प्राप्त करता है या सेट करता है। |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | हेडर को प्राप्त करता है या सेट करता है। |
| [setHorizontalPlacement(int value)](#setHorizontalPlacement-int-) | क्षैतिज प्लेसमेंट को प्राप्त करता है या सेट करता है। |
| [setLines(TypeToolLineInfo[] value)](#setLines-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo---) | लाइन को प्राप्त करता है या सेट करता है। |
| [setRComponent(short value)](#setRComponent-short-) | r घटक को प्राप्त करता है या सेट करता है। |
| [setScaleFactor(int value)](#setScaleFactor-int-) | स्केल फैक्टर को प्राप्त करता है या सेट करता है। |
| [setSelectionEnd(int value)](#setSelectionEnd-int-) | सेलेक्शन अंत को प्राप्त करता है या सेट करता है। |
| [setSelectionStart(int value)](#setSelectionStart-int-) | चयन प्रारंभ को प्राप्त करता है या सेट करता है. |
| [setStyles(TypeToolStyleInfo[] value)](#setStyles-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo---) | फ़ॉन्ट शैलियों को प्राप्त करता है या सेट करता है. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | रूपांतरण मैट्रिक्स को प्राप्त करता है या सेट करता है. |
| [setTypeValue(short value)](#setTypeValue-short-) | प्रकार मान को प्राप्त करता है या सेट करता है. |
| [setVersion(short value)](#setVersion-short-) | संस्करण को प्राप्त करता है या सेट करता है। |
| [setVerticalPlacement(int value)](#setVerticalPlacement-int-) | ऊर्ध्वाधर प्लेसमेंट को प्राप्त करता है या सेट करता है. |
| [toString()](#toString--) | इस इंस्टेंस का प्रतिनिधित्व करने वाली एक स्ट्रिंग लौटाता है। |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TypeToolInfoResource() {#TypeToolInfoResource--}
```
public TypeToolInfoResource()
```


नया उदाहरण प्रारंभ करता है [TypeToolInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource) क्लास का।

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
### getAComponent() {#getAComponent--}
```
public final short getAComponent()
```


किसी घटक को प्राप्त करता है या सेट करता है।

मान: एक घटक.

**Returns:**
short
### getBComponent() {#getBComponent--}
```
public final short getBComponent()
```


b घटक को प्राप्त करता है या सेट करता है।

मान: b घटक.

**Returns:**
short
### getCharacterCount() {#getCharacterCount--}
```
public final int getCharacterCount()
```


अक्षर गिनती को प्राप्त करता है या सेट करता है।

मान: अक्षर गिनती.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorSpaceValue() {#getColorSpaceValue--}
```
public final short getColorSpaceValue()
```


रंग स्थान मान को प्राप्त करता है या सेट करता है।

मान: रंग स्थान मान.

**Returns:**
short
### getFontVersion() {#getFontVersion--}
```
public final short getFontVersion()
```


फ़ॉन्ट संस्करण को प्राप्त करता है या सेट करता है।

मान: फ़ॉन्ट संस्करण.

**Returns:**
short
### getFonts() {#getFonts--}
```
public final TypeToolFontInfo[] getFonts()
```


फ़ॉन्ट्स को प्राप्त करता है या सेट करता है।

मान: फ़ॉन्ट्स.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo[]
### getFontsCount() {#getFontsCount--}
```
public final short getFontsCount()
```


फ़ॉन्ट्स की गिनती प्राप्त करता है।

**Returns:**
short
### getGComponent() {#getGComponent--}
```
public final short getGComponent()
```


g घटक को प्राप्त करता है या सेट करता है।

मान: g घटक.

**Returns:**
short
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


हेडर को प्राप्त करता है या सेट करता है।

मान: हेडर।

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHorizontalPlacement() {#getHorizontalPlacement--}
```
public final int getHorizontalPlacement()
```


क्षैतिज प्लेसमेंट को प्राप्त करता है या सेट करता है।

मान: क्षैतिज प्लेसमेंट.

**Returns:**
int
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
### getLineCount() {#getLineCount--}
```
public final short getLineCount()
```


लाइन गिनती प्राप्त करता है।

मान: पंक्ति गिनती.

**Returns:**
short
### getLines() {#getLines--}
```
public final TypeToolLineInfo[] getLines()
```


लाइन को प्राप्त करता है या सेट करता है।

मान: पंक्तियाँ.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo[]
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


लेयर रिसोर्स के लिए आवश्यक न्यूनतम PSD संस्करण प्राप्त करता है। 0 का अर्थ कोई प्रतिबंध नहीं है।

**Returns:**
int
### getRComponent() {#getRComponent--}
```
public final short getRComponent()
```


r घटक को प्राप्त करता है या सेट करता है।

मान: r घटक.

**Returns:**
short
### getScaleFactor() {#getScaleFactor--}
```
public final int getScaleFactor()
```


स्केल फैक्टर को प्राप्त करता है या सेट करता है।

मान: स्केल फैक्टर.

**Returns:**
int
### getSelectionEnd() {#getSelectionEnd--}
```
public final int getSelectionEnd()
```


सेलेक्शन अंत को प्राप्त करता है या सेट करता है।

मान: चयन अंत.

**Returns:**
int
### getSelectionStart() {#getSelectionStart--}
```
public final int getSelectionStart()
```


चयन प्रारंभ को प्राप्त करता है या सेट करता है.

मान: चयन प्रारंभ.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


लेयर रिसोर्स सिग्नेचर प्राप्त करता है।

**Returns:**
int
### getStyles() {#getStyles--}
```
public final TypeToolStyleInfo[] getStyles()
```


फ़ॉन्ट शैलियों को प्राप्त करता है या सेट करता है.

मान: फ़ॉन्ट शैलियाँ.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo[]
### getStylesCount() {#getStylesCount--}
```
public final short getStylesCount()
```


शैलियों की गिनती प्राप्त करता है.

**Returns:**
short
### getTransformMatrix() {#getTransformMatrix--}
```
public final double[] getTransformMatrix()
```


रूपांतरण मैट्रिक्स को प्राप्त करता है या सेट करता है.

मान: ट्रांसफ़ॉर्म मैट्रिक्स।

**Returns:**
double[]
### getTypeValue() {#getTypeValue--}
```
public final short getTypeValue()
```


प्रकार मान को प्राप्त करता है या सेट करता है.

मान: प्रकार मान।

**Returns:**
short
### getVersion() {#getVersion--}
```
public final short getVersion()
```


संस्करण को प्राप्त करता है या सेट करता है।

मान: संस्करण।

**Returns:**
short
### getVerticalPlacement() {#getVerticalPlacement--}
```
public final int getVerticalPlacement()
```


ऊर्ध्वाधर प्लेसमेंट को प्राप्त करता है या सेट करता है.

मान: ऊर्ध्वाधर प्लेसमेंट।

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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


निर्दिष्ट स्ट्रीम कंटेनर को सहेजता है.

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

### setAComponent(short value) {#setAComponent-short-}
```
public final void setAComponent(short value)
```


किसी घटक को प्राप्त करता है या सेट करता है।

मान: एक घटक.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setBComponent(short value) {#setBComponent-short-}
```
public final void setBComponent(short value)
```


b घटक को प्राप्त करता है या सेट करता है।

मान: b घटक.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setCharacterCount(int value) {#setCharacterCount-int-}
```
public final void setCharacterCount(int value)
```


अक्षर गिनती को प्राप्त करता है या सेट करता है।

मान: अक्षर गिनती.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setColorDataRaw_internalized(byte[] value) {#setColorDataRaw-internalized-byte---}
```
public final void setColorDataRaw_internalized(byte[] value)
```


रंग डेटा कच्चा को प्राप्त करता है या सेट करता है.

मान: रंग डेटा कच्चा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | byte[] |  |

### setColorSpaceValue(short value) {#setColorSpaceValue-short-}
```
public final void setColorSpaceValue(short value)
```


रंग स्थान मान को प्राप्त करता है या सेट करता है।

मान: रंग स्थान मान.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setFontVersion(short value) {#setFontVersion-short-}
```
public final void setFontVersion(short value)
```


फ़ॉन्ट संस्करण को प्राप्त करता है या सेट करता है।

मान: फ़ॉन्ट संस्करण.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setFonts(TypeToolFontInfo[] value) {#setFonts-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo---}
```
public final void setFonts(TypeToolFontInfo[] value)
```


फ़ॉन्ट्स को प्राप्त करता है या सेट करता है।

मान: फ़ॉन्ट्स.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TypeToolFontInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) |  |

### setGComponent(short value) {#setGComponent-short-}
```
public final void setGComponent(short value)
```


g घटक को प्राप्त करता है या सेट करता है।

मान: g घटक.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

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

### setHorizontalPlacement(int value) {#setHorizontalPlacement-int-}
```
public final void setHorizontalPlacement(int value)
```


क्षैतिज प्लेसमेंट को प्राप्त करता है या सेट करता है।

मान: क्षैतिज प्लेसमेंट.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setLines(TypeToolLineInfo[] value) {#setLines-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo---}
```
public final void setLines(TypeToolLineInfo[] value)
```


लाइन को प्राप्त करता है या सेट करता है।

मान: पंक्तियाँ.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TypeToolLineInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) |  |

### setRComponent(short value) {#setRComponent-short-}
```
public final void setRComponent(short value)
```


r घटक को प्राप्त करता है या सेट करता है।

मान: r घटक.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setScaleFactor(int value) {#setScaleFactor-int-}
```
public final void setScaleFactor(int value)
```


स्केल फैक्टर को प्राप्त करता है या सेट करता है।

मान: स्केल फैक्टर.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSelectionEnd(int value) {#setSelectionEnd-int-}
```
public final void setSelectionEnd(int value)
```


सेलेक्शन अंत को प्राप्त करता है या सेट करता है।

मान: चयन अंत.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setSelectionStart(int value) {#setSelectionStart-int-}
```
public final void setSelectionStart(int value)
```


चयन प्रारंभ को प्राप्त करता है या सेट करता है.

मान: चयन प्रारंभ.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### setStyles(TypeToolStyleInfo[] value) {#setStyles-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo---}
```
public final void setStyles(TypeToolStyleInfo[] value)
```


फ़ॉन्ट शैलियों को प्राप्त करता है या सेट करता है.

मान: फ़ॉन्ट शैलियाँ.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TypeToolStyleInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public final void setTransformMatrix(double[] value)
```


रूपांतरण मैट्रिक्स को प्राप्त करता है या सेट करता है.

मान: ट्रांसफ़ॉर्म मैट्रिक्स।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double[] |  |

### setTypeValue(short value) {#setTypeValue-short-}
```
public final void setTypeValue(short value)
```


प्रकार मान को प्राप्त करता है या सेट करता है.

मान: प्रकार मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setVersion(short value) {#setVersion-short-}
```
public final void setVersion(short value)
```


संस्करण को प्राप्त करता है या सेट करता है।

मान: संस्करण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | short |  |

### setVerticalPlacement(int value) {#setVerticalPlacement-int-}
```
public final void setVerticalPlacement(int value)
```


ऊर्ध्वाधर प्लेसमेंट को प्राप्त करता है या सेट करता है.

मान: ऊर्ध्वाधर प्लेसमेंट।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

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

