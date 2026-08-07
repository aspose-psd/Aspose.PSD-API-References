---
title: "ImageAttributes"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "एक com.aspose.psd.ImageAttributes ऑब्जेक्ट रेंडरिंग के दौरान बिटमैप और मेटाफाइल रंगों को कैसे संशोधित किया जाता है, इस बारे में जानकारी रखता है।"
type: docs
weight: 55
url: /hi/java/com.aspose.psd/imageattributes/
---

**Inheritance:**
java.lang.Object
```
public final class ImageAttributes
```

एक com.aspose.psd.ImageAttributes ऑब्जेक्ट रेंडरिंग के दौरान बिटमैप और मेटाफाइल रंगों को कैसे संशोधित किया जाता है, इस बारे में जानकारी रखता है। एक com.aspose.psd.ImageAttributes ऑब्जेक्ट कई रंग-संशोधन सेटिंग्स को बनाए रखता है, जिसमें रंग-संशोधन मैट्रिक्स, ग्रेस्केल-संशोधन मैट्रिक्स, गामा-सुधार मान, रंग-मैप तालिकाएँ और रंग-थ्रेशहोल्ड मान शामिल हैं। रेंडरिंग के दौरान, रंगों को सुधारा, गहरा, हल्का या हटाया जा सकता है। ऐसी संशोधनों को लागू करने के लिए, एक com.aspose.psd.ImageAttributes ऑब्जेक्ट को प्रारंभ करें और उस com.aspose.psd.ImageAttributes ऑब्जेक्ट का पथ (साथ ही एक [Image](../../com.aspose.psd/image) का पथ) drawImage मेथड को पास करें।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [ImageAttributes()](#ImageAttributes--) | com.aspose.psd.ImageAttributes क्लास का एक नया इंस्टेंस प्रारंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [imageAttributes_internalized](#imageAttributes-internalized) | GDI इमेज एट्रिब्यूट्स। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [clearBrushRemapTable()](#clearBrushRemapTable--) | इस com.aspose.psd.ImageAttributes ऑब्जेक्ट की ब्रश रंग-रीमैप तालिका को साफ़ करता है। |
| [clearColorKey()](#clearColorKey--) | डिफ़ॉल्ट श्रेणी के लिए रंग कुंजी (पारदर्शिता सीमा) को साफ़ करता है। |
| [clearColorKey(int type)](#clearColorKey-int-) | निर्दिष्ट श्रेणी के लिए रंग कुंजी (पारदर्शिता सीमा) को साफ़ करता है। |
| [clearColorMatrix()](#clearColorMatrix--) | डिफ़ॉल्ट श्रेणी के लिए रंग-संशोधन मैट्रिक्स को साफ़ करता है। |
| [clearColorMatrix(int type)](#clearColorMatrix-int-) | निर्दिष्ट श्रेणी के लिए रंग-संशोधन मैट्रिक्स को साफ़ करता है। |
| [clearGamma()](#clearGamma--) | डिफ़ॉल्ट श्रेणी के लिए गामा सुधार को निष्क्रिय करता है। |
| [clearGamma(int type)](#clearGamma-int-) | निर्दिष्ट श्रेणी के लिए गामा सुधार को निष्क्रिय करता है। |
| [clearNoOp()](#clearNoOp--) | डिफ़ॉल्ट श्रेणी के लिए NoOp सेटिंग को साफ़ करता है। |
| [clearNoOp(int type)](#clearNoOp-int-) | निर्दिष्ट श्रेणी के लिए NoOp सेटिंग को साफ़ करता है। |
| [clearOutputChannel()](#clearOutputChannel--) | डिफ़ॉल्ट श्रेणी के लिए CMYK (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेटिंग को साफ़ करता है। |
| [clearOutputChannel(int type)](#clearOutputChannel-int-) | निर्दिष्ट श्रेणी के लिए (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेटिंग को साफ़ करता है। |
| [clearOutputChannelColorProfile()](#clearOutputChannelColorProfile--) | डिफ़ॉल्ट श्रेणी के लिए आउटपुट चैनल रंग प्रोफ़ाइल सेटिंग को साफ़ करता है। |
| [clearOutputChannelColorProfile(int type)](#clearOutputChannelColorProfile-int-) | निर्दिष्ट श्रेणी के लिए आउटपुट चैनल रंग प्रोफ़ाइल सेटिंग को साफ़ करता है। |
| [clearRemapTable()](#clearRemapTable--) | डिफ़ॉल्ट श्रेणी के लिए रंग-रीमैप तालिका को साफ़ करता है। |
| [clearRemapTable(int type)](#clearRemapTable-int-) | निर्दिष्ट श्रेणी के लिए रंग-रीमैप तालिका को साफ़ करता है। |
| [clearThreshold()](#clearThreshold--) | डिफ़ॉल्ट श्रेणी के लिए थ्रेशहोल्ड मान को साफ़ करता है। |
| [clearThreshold(int type)](#clearThreshold-int-) | निर्दिष्ट वर्ग के लिए थ्रेशहोल्ड मान को साफ़ करता है। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrushRemapTable(ColorMap[] map)](#setBrushRemapTable-com.aspose.psd.ColorMap---) | ब्रश वर्ग के लिए रंग-रीमैप तालिका सेट करता है। |
| [setColorKey(Color colorLow, Color colorHigh)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-) | डिफ़ॉल्ट वर्ग के लिए रंग कुंजी सेट करता है। |
| [setColorKey(Color colorLow, Color colorHigh, int type)](#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-) | निर्दिष्ट वर्ग के लिए रंग कुंजी (पारदर्शिता सीमा) सेट करता है। |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-) | डिफ़ॉल्ट वर्ग के लिए रंग-समायोजन मैट्रिक्स और ग्रेस्केल-समायोजन मैट्रिक्स सेट करता है। |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-) | डिफ़ॉल्ट वर्ग के लिए रंग-समायोजन मैट्रिक्स और ग्रेस्केल-समायोजन मैट्रिक्स सेट करता है। |
| [setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)](#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | निर्दिष्ट वर्ग के लिए रंग-समायोजन मैट्रिक्स और ग्रेस्केल-समायोजन मैट्रिक्स सेट करता है। |
| [setColorMatrix(ColorMatrix newColorMatrix)](#setColorMatrix-com.aspose.psd.ColorMatrix-) | डिफ़ॉल्ट वर्ग के लिए रंग-समायोजन मैट्रिक्स सेट करता है। |
| [setColorMatrix(ColorMatrix newColorMatrix, int flags)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-) | डिफ़ॉल्ट वर्ग के लिए रंग-समायोजन मैट्रिक्स सेट करता है। |
| [setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)](#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-) | निर्दिष्ट वर्ग के लिए रंग-समायोजन मैट्रिक्स सेट करता है। |
| [setGamma(float gamma)](#setGamma-float-) | डिफ़ॉल्ट वर्ग के लिए गामा मान सेट करता है। |
| [setGamma(float gamma, int type)](#setGamma-float-int-) | निर्दिष्ट वर्ग के लिए गामा मान सेट करता है। |
| [setNoOp()](#setNoOp--) | डिफ़ॉल्ट वर्ग के लिए रंग समायोजन बंद करता है। |
| [setNoOp(int type)](#setNoOp-int-) | निर्दिष्ट वर्ग के लिए रंग समायोजन बंद करता है। |
| [setOutputChannel(int flags)](#setOutputChannel-int-) | डिफ़ॉल्ट वर्ग के लिए CMYK (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेट करता है। |
| [setOutputChannel(int flags, int type)](#setOutputChannel-int-int-) | निर्दिष्ट वर्ग के लिए CMYK (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेट करता है। |
| [setOutputChannelColorProfile(String colorProfileFilename)](#setOutputChannelColorProfile-java.lang.String-) | डिफ़ॉल्ट वर्ग के लिए आउटपुट चैनल रंग-प्रोफ़ाइल फ़ाइल सेट करता है। |
| [setOutputChannelColorProfile(String colorProfileFilename, int type)](#setOutputChannelColorProfile-java.lang.String-int-) | निर्दिष्ट वर्ग के लिए आउटपुट चैनल रंग-प्रोफ़ाइल फ़ाइल सेट करता है। |
| [setRemapTable(ColorMap[] map)](#setRemapTable-com.aspose.psd.ColorMap---) | डिफ़ॉल्ट वर्ग के लिए रंग-रीमैप तालिका सेट करता है। |
| [setRemapTable(ColorMap[] map, int type)](#setRemapTable-com.aspose.psd.ColorMap---int-) | निर्दिष्ट वर्ग के लिए रंग-रीमैप तालिका सेट करता है। |
| [setThreshold(float threshold)](#setThreshold-float-) | डिफ़ॉल्ट वर्ग के लिए थ्रेशहोल्ड (पारदर्शिता सीमा) सेट करता है। |
| [setThreshold(float threshold, int type)](#setThreshold-float-int-) | निर्दिष्ट वर्ग के लिए थ्रेशहोल्ड (पारदर्शिता सीमा) सेट करता है। |
| [setWrapMode(int mode)](#setWrapMode-int-) | रैप मोड सेट करता है जो यह तय करने के लिए उपयोग किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। |
| [setWrapMode(int mode, Color color)](#setWrapMode-int-com.aspose.psd.Color-) | रैप मोड और रंग सेट करता है जो यह तय करने के लिए उपयोग किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। |
| [setWrapMode(int mode, Color color, boolean clamp)](#setWrapMode-int-com.aspose.psd.Color-boolean-) | रैप मोड और रंग सेट करता है जो यह तय करने के लिए उपयोग किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImageAttributes() {#ImageAttributes--}
```
public ImageAttributes()
```


com.aspose.psd.ImageAttributes क्लास का एक नया इंस्टेंस प्रारंभ करता है।

### imageAttributes_internalized {#imageAttributes-internalized}
```
public final System.Drawing.Imaging.ImageAttributes imageAttributes_internalized
```


GDI इमेज एट्रिब्यूट्स।

### clearBrushRemapTable() {#clearBrushRemapTable--}
```
public void clearBrushRemapTable()
```


इस com.aspose.psd.ImageAttributes ऑब्जेक्ट की ब्रश रंग-रीमैप तालिका को साफ़ करता है।

### clearColorKey() {#clearColorKey--}
```
public void clearColorKey()
```


डिफ़ॉल्ट श्रेणी के लिए रंग कुंजी (पारदर्शिता सीमा) को साफ़ करता है।

### clearColorKey(int type) {#clearColorKey-int-}
```
public void clearColorKey(int type)
```


निर्दिष्ट श्रेणी के लिए रंग कुंजी (पारदर्शिता सीमा) को साफ़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int |   Aspose.Imaging.ColorAdjustType  का एक तत्व जो उस वर्ग को निर्दिष्ट करता है जिसके लिए रंग कुंजी साफ़ की जाती है। |

### clearColorMatrix() {#clearColorMatrix--}
```
public void clearColorMatrix()
```


डिफ़ॉल्ट श्रेणी के लिए रंग-संशोधन मैट्रिक्स को साफ़ करता है।

### clearColorMatrix(int type) {#clearColorMatrix-int-}
```
public void clearColorMatrix(int type)
```


निर्दिष्ट श्रेणी के लिए रंग-संशोधन मैट्रिक्स को साफ़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int |   Aspose.Imaging.ColorAdjustType  का एक तत्व जो उस वर्ग को निर्दिष्ट करता है जिसके लिए रंग-समायोजन मैट्रिक्स साफ़ किया जाता है। |

### clearGamma() {#clearGamma--}
```
public void clearGamma()
```


डिफ़ॉल्ट श्रेणी के लिए गामा सुधार को निष्क्रिय करता है।

### clearGamma(int type) {#clearGamma-int-}
```
public void clearGamma(int type)
```


निर्दिष्ट श्रेणी के लिए गामा सुधार को निष्क्रिय करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int |   Aspose.Imaging.ColorAdjustType  का एक तत्व जो उस वर्ग को निर्दिष्ट करता है जिसके लिए गामा सुधार निष्क्रिय किया गया है। |

### clearNoOp() {#clearNoOp--}
```
public void clearNoOp()
```


डिफ़ॉल्ट श्रेणी के लिए NoOp सेटिंग को साफ़ करता है।

### clearNoOp(int type) {#clearNoOp-int-}
```
public void clearNoOp(int type)
```


निर्दिष्ट श्रेणी के लिए NoOp सेटिंग को साफ़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType का एक तत्व जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए NoOp सेटिंग साफ़ की जाती है। |

### clearOutputChannel() {#clearOutputChannel--}
```
public void clearOutputChannel()
```


डिफ़ॉल्ट श्रेणी के लिए CMYK (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेटिंग को साफ़ करता है।

### clearOutputChannel(int type) {#clearOutputChannel-int-}
```
public void clearOutputChannel(int type)
```


निर्दिष्ट श्रेणी के लिए (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेटिंग को साफ़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType का एक तत्व जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए आउटपुट चैनल सेटिंग साफ़ की जाती है। |

### clearOutputChannelColorProfile() {#clearOutputChannelColorProfile--}
```
public void clearOutputChannelColorProfile()
```


डिफ़ॉल्ट श्रेणी के लिए आउटपुट चैनल रंग प्रोफ़ाइल सेटिंग को साफ़ करता है।

### clearOutputChannelColorProfile(int type) {#clearOutputChannelColorProfile-int-}
```
public void clearOutputChannelColorProfile(int type)
```


निर्दिष्ट श्रेणी के लिए आउटपुट चैनल रंग प्रोफ़ाइल सेटिंग को साफ़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType का एक तत्व जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए आउटपुट चैनल प्रोफ़ाइल सेटिंग साफ़ की जाती है। |

### clearRemapTable() {#clearRemapTable--}
```
public void clearRemapTable()
```


डिफ़ॉल्ट श्रेणी के लिए रंग-रीमैप तालिका को साफ़ करता है।

### clearRemapTable(int type) {#clearRemapTable-int-}
```
public void clearRemapTable(int type)
```


निर्दिष्ट श्रेणी के लिए रंग-रीमैप तालिका को साफ़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType का एक तत्व जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए रीमैप टेबल साफ़ की जाती है। |

### clearThreshold() {#clearThreshold--}
```
public void clearThreshold()
```


डिफ़ॉल्ट श्रेणी के लिए थ्रेशहोल्ड मान को साफ़ करता है।

### clearThreshold(int type) {#clearThreshold-int-}
```
public void clearThreshold(int type)
```


निर्दिष्ट वर्ग के लिए थ्रेशहोल्ड मान को साफ़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType का एक तत्व जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए थ्रेशोल्ड साफ़ किया जाता है। |

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




### setBrushRemapTable(ColorMap[] map) {#setBrushRemapTable-com.aspose.psd.ColorMap---}
```
public void setBrushRemapTable(ColorMap[] map)
```


ब्रश वर्ग के लिए रंग-रीमैप तालिका सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | com.aspose.psd.ColorMap वस्तुओं की एक सरणी। |

### setColorKey(Color colorLow, Color colorHigh) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-}
```
public void setColorKey(Color colorLow, Color colorHigh)
```


डिफ़ॉल्ट वर्ग के लिए रंग कुंजी सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | निम्न रंग-की मान। |
| colorHigh | [Color](../../com.aspose.psd/color) | उच्च रंग-की मान। |

### setColorKey(Color colorLow, Color colorHigh, int type) {#setColorKey-com.aspose.psd.Color-com.aspose.psd.Color-int-}
```
public void setColorKey(Color colorLow, Color colorHigh, int type)
```


निर्दिष्ट वर्ग के लिए रंग कुंजी (पारदर्शिता सीमा) सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorLow | [Color](../../com.aspose.psd/color) | निम्न रंग-की मान। |
| colorHigh | [Color](../../com.aspose.psd/color) | उच्च रंग-की मान। |
| type | int | Aspose.Imaging.ColorAdjustType का एक तत्व जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए रंग कुंजी सेट की जाती है। |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix)
```


डिफ़ॉल्ट वर्ग के लिए रंग-समायोजन मैट्रिक्स और ग्रेस्केल-समायोजन मैट्रिक्स सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | रंग-समायोजन मैट्रिक्स। |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | ग्रेस्केल-समायोजन मैट्रिक्स। |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int flags)
```


डिफ़ॉल्ट वर्ग के लिए रंग-समायोजन मैट्रिक्स और ग्रेस्केल-समायोजन मैट्रिक्स सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | रंग-समायोजन मैट्रिक्स। |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | ग्रेस्केल-समायोजन मैट्रिक्स। |
| फ़्लैग्स | int | Aspose.Imaging.ColorMatrixFlag का एक तत्व जो उस छवि और रंग के प्रकार को निर्दिष्ट करता है जो रंग-समायोजन और ग्रेस्केल-समायोजन मैट्रिक्स द्वारा प्रभावित होगा। |

### setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type) {#setColorMatrices-com.aspose.psd.ColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrices(ColorMatrix newColorMatrix, ColorMatrix grayMatrix, int mode, int type)
```


निर्दिष्ट वर्ग के लिए रंग-समायोजन मैट्रिक्स और ग्रेस्केल-समायोजन मैट्रिक्स सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | रंग-समायोजन मैट्रिक्स। |
| grayMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | ग्रेस्केल-समायोजन मैट्रिक्स। |
| mode | int | Aspose.Imaging.ColorMatrixFlag का एक तत्व जो उस छवि और रंग के प्रकार को निर्दिष्ट करता है जो रंग-समायोजन और ग्रेस्केल-समायोजन मैट्रिक्स द्वारा प्रभावित होगा। |
| type | int | Aspose.Imaging.ColorAdjustType का एक तत्व जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए रंग-समायोजन और ग्रेस्केल-समायोजन मैट्रिक्स सेट किए जाते हैं। |

### setColorMatrix(ColorMatrix newColorMatrix) {#setColorMatrix-com.aspose.psd.ColorMatrix-}
```
public void setColorMatrix(ColorMatrix newColorMatrix)
```


डिफ़ॉल्ट वर्ग के लिए रंग-समायोजन मैट्रिक्स सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | रंग-समायोजन मैट्रिक्स। |

### setColorMatrix(ColorMatrix newColorMatrix, int flags) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int flags)
```


डिफ़ॉल्ट वर्ग के लिए रंग-समायोजन मैट्रिक्स सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | रंग-समायोजन मैट्रिक्स। |
| फ़्लैग्स | int | Aspose.Imaging.ColorMatrixFlag का एक तत्व जो उस छवि और रंग के प्रकार को निर्दिष्ट करता है जो रंग-समायोजन मैट्रिक्स द्वारा प्रभावित होगा। |

### setColorMatrix(ColorMatrix newColorMatrix, int mode, int type) {#setColorMatrix-com.aspose.psd.ColorMatrix-int-int-}
```
public void setColorMatrix(ColorMatrix newColorMatrix, int mode, int type)
```


निर्दिष्ट वर्ग के लिए रंग-समायोजन मैट्रिक्स सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| newColorMatrix | [ColorMatrix](../../com.aspose.psd/colormatrix) | रंग-समायोजन मैट्रिक्स। |
| mode | int | Aspose.Imaging.ColorMatrixFlag का एक तत्व जो उस छवि और रंग के प्रकार को निर्दिष्ट करता है जो रंग-समायोजन मैट्रिक्स द्वारा प्रभावित होगा। |
| type | int | Aspose.Imaging.ColorAdjustType का एक तत्व जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए रंग-समायोजन मैट्रिक्स सेट किया जाता है। |

### setGamma(float gamma) {#setGamma-float-}
```
public void setGamma(float gamma)
```


डिफ़ॉल्ट वर्ग के लिए गामा मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| gamma | float | गामा सुधार मान। |

### setGamma(float gamma, int type) {#setGamma-float-int-}
```
public void setGamma(float gamma, int type)
```


निर्दिष्ट वर्ग के लिए गामा मान सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| gamma | float | गामा सुधार मान। |
| type | int | Aspose.Imaging.ColorAdjustType enumeration का एक तत्व जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए गामा मान सेट किया जाता है। |

### setNoOp() {#setNoOp--}
```
public void setNoOp()
```


डिफ़ॉल्ट वर्ग के लिए रंग समायोजन बंद करता है।

### setNoOp(int type) {#setNoOp-int-}
```
public void setNoOp(int type)
```


निर्दिष्ट वर्ग के लिए रंग समायोजन बंद करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| type | int | Aspose.Imaging.ColorAdjustType का एक तत्व जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए रंग सुधार बंद किया जाता है। |

### setOutputChannel(int flags) {#setOutputChannel-int-}
```
public void setOutputChannel(int flags)
```


डिफ़ॉल्ट वर्ग के लिए CMYK (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्लैग्स | int | Aspose.Imaging.ColorChannelFlag का एक तत्व जो आउटपुट चैनल को निर्दिष्ट करता है। |

### setOutputChannel(int flags, int type) {#setOutputChannel-int-int-}
```
public void setOutputChannel(int flags, int type)
```


निर्दिष्ट वर्ग के लिए CMYK (सियान-मैजेंटा-येलो-ब्लैक) आउटपुट चैनल सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़्लैग्स | int | Aspose.Imaging.ColorChannelFlag का एक तत्व जो आउटपुट चैनल को निर्दिष्ट करता है। |
| type | int | Aspose.Imaging.ColorAdjustType का एक तत्व जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए आउटपुट चैनल सेट किया जाता है। |

### setOutputChannelColorProfile(String colorProfileFilename) {#setOutputChannelColorProfile-java.lang.String-}
```
public void setOutputChannelColorProfile(String colorProfileFilename)
```


डिफ़ॉल्ट वर्ग के लिए आउटपुट चैनल रंग-प्रोफ़ाइल फ़ाइल सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | एक रंग-प्रोफ़ाइल फ़ाइल का पथ नाम। यदि रंग-प्रोफ़ाइल फ़ाइल %SystemRoot%\\System32\\Spool\\Drivers\\Color निर्देशिका में है, तो यह पैरामीटर फ़ाइल नाम हो सकता है। अन्यथा, इस पैरामीटर को पूर्ण योग्य पथ नाम होना चाहिए। |

### setOutputChannelColorProfile(String colorProfileFilename, int type) {#setOutputChannelColorProfile-java.lang.String-int-}
```
public void setOutputChannelColorProfile(String colorProfileFilename, int type)
```


निर्दिष्ट वर्ग के लिए आउटपुट चैनल रंग-प्रोफ़ाइल फ़ाइल सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorProfileFilename | java.lang.String | एक रंग-प्रोफ़ाइल फ़ाइल का पथ नाम। यदि रंग-प्रोफ़ाइल फ़ाइल %SystemRoot%\\System32\\Spool\\Drivers\\Color निर्देशिका में है, तो यह पैरामीटर फ़ाइल नाम हो सकता है। अन्यथा, इस पैरामीटर को पूर्ण योग्य पथ नाम होना चाहिए। |
| type | int | Aspose.Imaging.ColorAdjustType का एक तत्व जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए आउटपुट चैनल रंग-प्रोफ़ाइल फ़ाइल सेट की जाती है। |

### setRemapTable(ColorMap[] map) {#setRemapTable-com.aspose.psd.ColorMap---}
```
public void setRemapTable(ColorMap[] map)
```


डिफ़ॉल्ट वर्ग के लिए रंग-रीमैप तालिका सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | com.aspose.psd.ColorMap प्रकार के रंग जोड़ों की एक सरणी। प्रत्येक रंग जोड़ा एक मौजूदा रंग (पहला मान) और वह रंग जिसमें इसे मैप किया जाएगा (दूसरा मान) रखता है। |

### setRemapTable(ColorMap[] map, int type) {#setRemapTable-com.aspose.psd.ColorMap---int-}
```
public void setRemapTable(ColorMap[] map, int type)
```


निर्दिष्ट वर्ग के लिए रंग-रीमैप तालिका सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| map | [ColorMap\[\]](../../com.aspose.psd/colormap) | com.aspose.psd.ColorMap प्रकार के रंग जोड़ों की एक सरणी। प्रत्येक रंग जोड़ा एक मौजूदा रंग (पहला मान) और वह रंग जिसमें इसे मैप किया जाएगा (दूसरा मान) रखता है। |
| type | int | Aspose.Imaging.ColorAdjustType का एक तत्व जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए रंग-रीमैप तालिका निर्धारित की गई है। |

### setThreshold(float threshold) {#setThreshold-float-}
```
public void setThreshold(float threshold)
```


डिफ़ॉल्ट वर्ग के लिए थ्रेशहोल्ड (पारदर्शिता सीमा) सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| threshold | float | एक वास्तविक संख्या जो थ्रेशोल्ड मान को निर्दिष्ट करती है। |

### setThreshold(float threshold, int type) {#setThreshold-float-int-}
```
public void setThreshold(float threshold, int type)
```


निर्दिष्ट वर्ग के लिए थ्रेशहोल्ड (पारदर्शिता सीमा) सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| threshold | float | 0.0 से 1.0 तक का थ्रेशोल्ड मान जो रंगों को क्रमबद्ध करने के लिए ब्रेकपॉइंट के रूप में उपयोग किया जाता है, जिन्हें अधिकतम या न्यूनतम मान में मैप किया जाएगा। |
| type | int | Aspose.Imaging.ColorAdjustType का एक तत्व जो उस श्रेणी को निर्दिष्ट करता है जिसके लिए रंग थ्रेशोल्ड सेट किया गया है। |

### setWrapMode(int mode) {#setWrapMode-int-}
```
public void setWrapMode(int mode)
```


रैप मोड सेट करता है जिसका उपयोग यह तय करने के लिए किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। जब टेक्सचर आकार से छोटा हो तो उसे भरने के लिए आकार के ऊपर टाइल किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mode | int | Aspose.Imaging.WrapMode का एक तत्व जो यह निर्दिष्ट करता है कि छवि की दोहराई गई प्रतियों का उपयोग क्षेत्र को टाइल करने के लिए कैसे किया जाता है। |

### setWrapMode(int mode, Color color) {#setWrapMode-int-com.aspose.psd.Color-}
```
public void setWrapMode(int mode, Color color)
```


रैप मोड और रंग सेट करता है जिसका उपयोग यह तय करने के लिए किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। जब टेक्सचर आकार से छोटा हो तो उसे भरने के लिए आकार के ऊपर टाइल किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mode | int | Aspose.Imaging.WrapMode का एक तत्व जो यह निर्दिष्ट करता है कि छवि की दोहराई गई प्रतियों का उपयोग क्षेत्र को टाइल करने के लिए कैसे किया जाता है। |
| color | [Color](../../com.aspose.psd/color) | com.aspose.psd.ImageAttributes ऑब्जेक्ट जो रेंडर की गई छवि के बाहर पिक्सेल के रंग को निर्दिष्ट करता है। यह रंग तब दिखाई देता है जब मोड पैरामीटर WrapMode.Clamp पर सेट हो और DrawImage को पास किया गया स्रोत आयत छवि से बड़ा हो। |

### setWrapMode(int mode, Color color, boolean clamp) {#setWrapMode-int-com.aspose.psd.Color-boolean-}
```
public void setWrapMode(int mode, Color color, boolean clamp)
```


रैप मोड और रंग सेट करता है जिसका उपयोग यह तय करने के लिए किया जाता है कि टेक्सचर को आकार के ऊपर या आकार की सीमाओं पर कैसे टाइल किया जाए। जब टेक्सचर आकार से छोटा हो तो उसे भरने के लिए आकार के ऊपर टाइल किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mode | int | Aspose.Imaging.WrapMode का एक तत्व जो यह निर्दिष्ट करता है कि छवि की दोहराई गई प्रतियों का उपयोग क्षेत्र को टाइल करने के लिए कैसे किया जाता है। |
| color | [Color](../../com.aspose.psd/color) | एक रंग ऑब्जेक्ट जो रेंडर की गई छवि के बाहर पिक्सेल के रंग को निर्दिष्ट करता है। यह रंग तब दिखाई देता है जब मोड पैरामीटर WrapMode.Clamp पर सेट हो और DrawImage को पास किया गया स्रोत आयत छवि से बड़ा हो। |
| क्लैंप | boolean | इस पैरामीटर का कोई प्रभाव नहीं है। इसे false पर सेट करें। |

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

