---
title: "AutoMaskingGraphCutOptions"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "ग्राफकट ऑटो मास्किंग विकल्प।"
type: docs
weight: 12
url: /hi/java/com.aspose.psd.masking.options/automaskinggraphcutoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.masking.options.MaskingOptions](../../com.aspose.psd.masking.options/maskingoptions), [com.aspose.psd.masking.options.GraphCutMaskingOptions](../../com.aspose.psd.masking.options/graphcutmaskingoptions)
```
public class AutoMaskingGraphCutOptions extends GraphCutMaskingOptions
```

ग्राफकट ऑटो मास्किंग विकल्प।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions--) | एक नया उदाहरण प्रारंभ करता है [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions) वर्ग का। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | पृष्ठभूमि वस्तु संख्या |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [appendAutoMaskingArgs_internalized(RasterImage image)](#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-) | ऑटो मास्किंग तर्क जोड़ें। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInnDefaultStrokes_internalized(RasterImage image)](#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-) | डिफ़ॉल्ट स्ट्रोक्स भरें। |
| [getArgs()](#getArgs--) | सेगमेंटेशन एल्गोरिदम के तर्कों को प्राप्त करता है। |
| [getAssumedObjects()](#getAssumedObjects--) | अनुमानित वस्तुओं को प्राप्त करता है। |
| [getAssumedObjects_internalized()](#getAssumedObjects-internalized--) |  |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | पृष्ठभूमि प्रतिस्थापन रंग को प्राप्त करता है। |
| [getCalculateDefaultStrokes()](#getCalculateDefaultStrokes--) | एक मान प्राप्त करता है जो दर्शाता है कि क्या डिफ़ॉल्ट स्ट्रोक्स की गणना की जानी चाहिए। |
| [getClass()](#getClass--) |  |
| [getCombinedObjectsRectangle_internalized()](#getCombinedObjectsRectangle-internalized--) | संयुक्त वस्तुओं का आयत प्राप्त करता है। |
| [getDecompose()](#getDecompose--) | प्राप्त करता है वह मान जो यह दर्शाता है कि क्या प्रत्येक Shape को mask से व्यक्तिगत वस्तु के रूप में या mask से संयुक्त वस्तु के रूप में, पृष्ठभूमि से अलग करके अलग करना अनावश्यक है। |
| [getDefaultBackgroundStrokes()](#getDefaultBackgroundStrokes--) | डिफ़ॉल्ट पृष्ठभूमि स्ट्रोक्स प्राप्त करता है। |
| [getDefaultForegroundStrokes()](#getDefaultForegroundStrokes--) | पूर्व-गणना किए गए डिफ़ॉल्ट अग्रभूमि स्ट्रोक्स प्राप्त करता है। |
| [getDefaultObjectsRectangles()](#getDefaultObjectsRectangles--) | डिफ़ॉल्ट वस्तुओं के आयत प्राप्त करता है। |
| [getExportOptions()](#getExportOptions--) | छवि निर्यात विकल्पों को प्राप्त करता है। |
| [getFeatheringRadius()](#getFeatheringRadius--) | फेदरिंग त्रिज्या प्राप्त करता है। |
| [getMaskingArea()](#getMaskingArea--) | मास्किंग क्षेत्र को प्राप्त करता है। |
| [getMethod()](#getMethod--) | सेगमेंटेशन विधि को प्राप्त करता है। |
| [getPrecalculationProgressEventHandler()](#getPrecalculationProgressEventHandler--) | डिफ़ॉल्ट बिंदुओं की पूर्व-गणना प्रक्रिया प्रगति इवेंट हैंडलर प्राप्त करता है। |
| [hasHumans_internalized()](#hasHumans-internalized--) | एक मान प्राप्त करता है जो दर्शाता है कि क्या अनुमानित वस्तुओं का संग्रह मानव वस्तुओं को शामिल करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.psd.masking.options.IMaskingArgs-) | सेगमेंटेशन एल्गोरिदम के तर्कों को निर्धारित करता है। |
| [setAssumedObjects(List<AssumedObjectData> value)](#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--) | अनुमानित वस्तुओं को सेट करता है। |
| [setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)](#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--) |  |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.psd.Color-) | पृष्ठभूमि प्रतिस्थापन रंग को निर्धारित करता है। |
| [setCalculateDefaultStrokes(boolean value)](#setCalculateDefaultStrokes-boolean-) | एक मान सेट करता है जो दर्शाता है कि क्या डिफ़ॉल्ट स्ट्रोक्स की गणना की जानी चाहिए। |
| [setCombinedObjectsRectangle_internalized(Rectangle value)](#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-) | संयुक्त वस्तुओं का आयत। |
| [setDecompose(boolean value)](#setDecompose-boolean-) | सेट करता है वह मान जो यह दर्शाता है कि क्या प्रत्येक Shape को mask से व्यक्तिगत वस्तु के रूप में या mask से संयुक्त वस्तु के रूप में, पृष्ठभूमि से अलग करके अलग करना अनावश्यक है। |
| [setDefaultBackgroundStrokes_internalized(Point[] value)](#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---) | डिफ़ॉल्ट पृष्ठभूमि स्ट्रोक। |
| [setDefaultForegroundStrokes_internalized(Point[] value)](#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---) | पूर्व-गणना किए गए डिफ़ॉल्ट अग्रभूमि स्ट्रोक। |
| [setDefaultObjectsRectangles_internalized(Rectangle[] value)](#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---) | डिफ़ॉल्ट ऑब्जेक्ट्स आयतें। |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.psd.ImageOptionsBase-) | छवि निर्यात विकल्पों को निर्धारित करता है। |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | फ़ेदरिंग त्रिज्या सेट करता है। |
| [setHumans_internalized(boolean value)](#setHumans-internalized-boolean-) | एक मान जो दर्शाता है कि अनुमानित ऑब्जेक्ट्स संग्रह में मानव ऑब्जेक्ट्स हैं या नहीं। |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.psd.Rectangle-) | मास्किंग क्षेत्र को निर्धारित करता है। |
| [setMethod(int value)](#setMethod-int-) | सेगमेंटेशन विधि को निर्धारित करता है। |
| [setPrecalculationProgressEventHandler(ProgressEventHandler value)](#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | डिफ़ॉल्ट पॉइंट्स पूर्व-गणना प्रक्रिया प्रगति इवेंट हैंडलर सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions--}
```
public AutoMaskingGraphCutOptions()
```


एक नया उदाहरण प्रारंभ करता है [AutoMaskingGraphCutOptions](../../com.aspose.psd.masking.options/automaskinggraphcutoptions) वर्ग का।

### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


पृष्ठभूमि वस्तु संख्या

### appendAutoMaskingArgs_internalized(RasterImage image) {#appendAutoMaskingArgs-internalized-com.aspose.psd.RasterImage-}
```
public final void appendAutoMaskingArgs_internalized(RasterImage image)
```


ऑटो मास्किंग तर्क जोड़ें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | छवि। |

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
### fillInnDefaultStrokes_internalized(RasterImage image) {#fillInnDefaultStrokes-internalized-com.aspose.psd.RasterImage-}
```
public final void fillInnDefaultStrokes_internalized(RasterImage image)
```


डिफ़ॉल्ट स्ट्रोक्स भरें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.psd/rasterimage) | छवि। |

### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


सेगमेंटेशन एल्गोरिदम के तर्कों को प्राप्त करता है।

मान: सेगमेंटेशन एल्गोरिदम के तर्क।

**Returns:**
[IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### getAssumedObjects() {#getAssumedObjects--}
```
public final List<AssumedObjectData> getAssumedObjects()
```


अनुमानित वस्तुओं को प्राप्त करता है।

**Returns:**
java.util.List<com.aspose.psd.masking.options.AssumedObjectData> - अनुमानित ऑब्जेक्ट्स।
### getAssumedObjects_internalized() {#getAssumedObjects-internalized--}
```
public final System.Collections.Generic.List<AssumedObjectData> getAssumedObjects_internalized()
```




**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData>
### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


पृष्ठभूमि प्रतिस्थापन रंग को प्राप्त करता है।

मान: पृष्ठभूमि प्रतिस्थापन रंग। यह रंग परिणामस्वरूप छवियों में पृष्ठभूमि रंग के रूप में उपयोग किया जाएगा।

**Returns:**
[Color](../../com.aspose.psd/color) - the background replacement color.
### getCalculateDefaultStrokes() {#getCalculateDefaultStrokes--}
```
public final boolean getCalculateDefaultStrokes()
```


एक मान प्राप्त करता है जो दर्शाता है कि क्या डिफ़ॉल्ट स्ट्रोक्स की गणना की जानी चाहिए।

**Returns:**
boolean - एक मान जो दर्शाता है कि डिफ़ॉल्ट स्ट्रोक्स की गणना की जानी चाहिए या नहीं।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCombinedObjectsRectangle_internalized() {#getCombinedObjectsRectangle-internalized--}
```
public final Rectangle getCombinedObjectsRectangle_internalized()
```


संयुक्त वस्तुओं का आयत प्राप्त करता है।

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the combined objects rectangle.
### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


प्राप्त करता है वह मान जो यह दर्शाता है कि क्या प्रत्येक Shape को mask से व्यक्तिगत वस्तु के रूप में या mask से संयुक्त वस्तु के रूप में, पृष्ठभूमि से अलग करके अलग करना अनावश्यक है।

मान: यदि विघटित किया जाए तो true; अन्यथा false।

**Returns:**
बूलियन - वह मान जो यह दर्शाता है कि क्या प्रत्येक Shape को mask से व्यक्तिगत वस्तु के रूप में या mask से संयुक्त वस्तु के रूप में, पृष्ठभूमि से अलग करके अलग करना अनावश्यक है।
### getDefaultBackgroundStrokes() {#getDefaultBackgroundStrokes--}
```
public final Point[] getDefaultBackgroundStrokes()
```


डिफ़ॉल्ट पृष्ठभूमि स्ट्रोक्स प्राप्त करता है।

**Returns:**
com.aspose.psd.Point[] - डिफ़ॉल्ट पृष्ठभूमि स्ट्रोक।
### getDefaultForegroundStrokes() {#getDefaultForegroundStrokes--}
```
public final Point[] getDefaultForegroundStrokes()
```


पूर्व-गणना किए गए डिफ़ॉल्ट अग्रभूमि स्ट्रोक्स प्राप्त करता है।

**Returns:**
com.aspose.psd.Point[] - पूर्व-गणना किए गए डिफ़ॉल्ट अग्रभूमि स्ट्रोक।
### getDefaultObjectsRectangles() {#getDefaultObjectsRectangles--}
```
public final Rectangle[] getDefaultObjectsRectangles()
```


डिफ़ॉल्ट वस्तुओं के आयत प्राप्त करता है।

**Returns:**
com.aspose.psd.Rectangle[] - डिफ़ॉल्ट ऑब्जेक्ट्स आयतें।
### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


छवि निर्यात विकल्पों को प्राप्त करता है।

मान: छवि निर्यात विकल्प जो परिणामस्वरूप छवियों को बनाने के लिए उपयोग किए जाएंगे।

**Returns:**
[ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) - the image export options.
### getFeatheringRadius() {#getFeatheringRadius--}
```
public final int getFeatheringRadius()
```


फेदरिंग त्रिज्या प्राप्त करता है।

**Returns:**
int - फ़ेदरिंग त्रिज्या।
### getMaskingArea() {#getMaskingArea--}
```
public final Rectangle getMaskingArea()
```


मास्किंग क्षेत्र को प्राप्त करता है।

मान: मास्किंग क्षेत्र जो स्रोत छवि का एक आंशिक भाग है। Rectangle.Empty मान का अर्थ पूर्ण स्रोत छवि क्षेत्र है।

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle) - the masking area.
### getMethod() {#getMethod--}
```
public final int getMethod()
```


सेगमेंटेशन विधि को प्राप्त करता है।

मान: विभाजन विधि।

**Returns:**
int - विभाजन विधि।
### getPrecalculationProgressEventHandler() {#getPrecalculationProgressEventHandler--}
```
public final ProgressEventHandler getPrecalculationProgressEventHandler()
```


डिफ़ॉल्ट बिंदुओं की पूर्व-गणना प्रक्रिया प्रगति इवेंट हैंडलर प्राप्त करता है।

मान: प्रोग्रेस इवेंट हैंडलर।

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the default points pre-calculation process progress event handler.
### hasHumans_internalized() {#hasHumans-internalized--}
```
public final boolean hasHumans_internalized()
```


एक मान प्राप्त करता है जो दर्शाता है कि क्या अनुमानित वस्तुओं का संग्रह मानव वस्तुओं को शामिल करता है।

**Returns:**
boolean - एक मान जो दर्शाता है कि अनुमानित ऑब्जेक्ट्स संग्रह में मानव ऑब्जेक्ट्स हैं या नहीं।
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




### setArgs(IMaskingArgs value) {#setArgs-com.aspose.psd.masking.options.IMaskingArgs-}
```
public final void setArgs(IMaskingArgs value)
```


सेगमेंटेशन एल्गोरिदम के तर्कों को निर्धारित करता है।

मान: सेगमेंटेशन एल्गोरिदम के तर्क।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IMaskingArgs](../../com.aspose.psd.masking.options/imaskingargs) | विभाजन एल्गोरिदम के तर्क। |

### setAssumedObjects(List<AssumedObjectData> value) {#setAssumedObjects-java.util.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects(List<AssumedObjectData> value)
```


अनुमानित वस्तुओं को सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.List<com.aspose.psd.masking.options.AssumedObjectData> | अनुमानित ऑब्जेक्ट्स। |

### setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value) {#setAssumedObjects-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.psd.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects_internalized(System.Collections.Generic.List<AssumedObjectData> value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | com.aspose.ms.System.Collections.Generic.List<com.aspose.psd.masking.options.AssumedObjectData> |  |

### setBackgroundReplacementColor(Color value) {#setBackgroundReplacementColor-com.aspose.psd.Color-}
```
public final void setBackgroundReplacementColor(Color value)
```


पृष्ठभूमि प्रतिस्थापन रंग को निर्धारित करता है।

मान: पृष्ठभूमि प्रतिस्थापन रंग। यह रंग परिणामस्वरूप छवियों में पृष्ठभूमि रंग के रूप में उपयोग किया जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) | पृष्ठभूमि प्रतिस्थापन रंग। |

### setCalculateDefaultStrokes(boolean value) {#setCalculateDefaultStrokes-boolean-}
```
public final void setCalculateDefaultStrokes(boolean value)
```


एक मान सेट करता है जो दर्शाता है कि क्या डिफ़ॉल्ट स्ट्रोक्स की गणना की जानी चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | एक मान जो दर्शाता है कि डिफ़ॉल्ट स्ट्रोक्स की गणना की जानी चाहिए या नहीं। |

### setCombinedObjectsRectangle_internalized(Rectangle value) {#setCombinedObjectsRectangle-internalized-com.aspose.psd.Rectangle-}
```
public final void setCombinedObjectsRectangle_internalized(Rectangle value)
```


संयुक्त वस्तुओं का आयत।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | संयुक्त ऑब्जेक्ट्स आयत। |

### setDecompose(boolean value) {#setDecompose-boolean-}
```
public final void setDecompose(boolean value)
```


सेट करता है वह मान जो यह दर्शाता है कि क्या प्रत्येक Shape को mask से व्यक्तिगत वस्तु के रूप में या mask से संयुक्त वस्तु के रूप में, पृष्ठभूमि से अलग करके अलग करना अनावश्यक है।

मान: यदि विघटित किया जाए तो true; अन्यथा false।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | एक मान जो संकेत करता है कि क्या प्रत्येक Shape को mask से व्यक्तिगत वस्तु के रूप में अलग करना अनावश्यक है या पृष्ठभूमि से अलग किए गए mask से संयुक्त वस्तु के रूप में। |

### setDefaultBackgroundStrokes_internalized(Point[] value) {#setDefaultBackgroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultBackgroundStrokes_internalized(Point[] value)
```


डिफ़ॉल्ट पृष्ठभूमि स्ट्रोक।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | डिफ़ॉल्ट पृष्ठभूमि स्ट्रोक। |

### setDefaultForegroundStrokes_internalized(Point[] value) {#setDefaultForegroundStrokes-internalized-com.aspose.psd.Point---}
```
public final void setDefaultForegroundStrokes_internalized(Point[] value)
```


पूर्व-गणना किए गए डिफ़ॉल्ट अग्रभूमि स्ट्रोक।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.psd/point) | पूर्व-गणना किए गए डिफ़ॉल्ट अग्रभूमि स्ट्रोक। |

### setDefaultObjectsRectangles_internalized(Rectangle[] value) {#setDefaultObjectsRectangles-internalized-com.aspose.psd.Rectangle---}
```
public final void setDefaultObjectsRectangles_internalized(Rectangle[] value)
```


डिफ़ॉल्ट ऑब्जेक्ट्स आयतें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.psd/rectangle) | डिफ़ॉल्ट ऑब्जेक्ट्स आयतें। |

### setExportOptions(ImageOptionsBase value) {#setExportOptions-com.aspose.psd.ImageOptionsBase-}
```
public final void setExportOptions(ImageOptionsBase value)
```


छवि निर्यात विकल्पों को निर्धारित करता है।

मान: छवि निर्यात विकल्प जो परिणामस्वरूप छवियों को बनाने के लिए उपयोग किए जाएंगे।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.psd/imageoptionsbase) | छवि निर्यात विकल्प। |

### setFeatheringRadius(int value) {#setFeatheringRadius-int-}
```
public final void setFeatheringRadius(int value)
```


फ़ेदरिंग त्रिज्या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | फ़ेदरिंग त्रिज्या। |

### setHumans_internalized(boolean value) {#setHumans-internalized-boolean-}
```
public final void setHumans_internalized(boolean value)
```


एक मान जो दर्शाता है कि अनुमानित ऑब्जेक्ट्स संग्रह में मानव ऑब्जेक्ट्स हैं या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean | एक मान जो दर्शाता है कि अनुमानित ऑब्जेक्ट्स संग्रह में मानव ऑब्जेक्ट्स हैं या नहीं। |

### setMaskingArea(Rectangle value) {#setMaskingArea-com.aspose.psd.Rectangle-}
```
public final void setMaskingArea(Rectangle value)
```


मास्किंग क्षेत्र को निर्धारित करता है।

मान: मास्किंग क्षेत्र जो स्रोत छवि का एक आंशिक भाग है। Rectangle.Empty मान का अर्थ पूर्ण स्रोत छवि क्षेत्र है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) | मास्किंग क्षेत्र। |

### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


सेगमेंटेशन विधि को निर्धारित करता है।

मान: विभाजन विधि।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | विभाजन विधि। |

### setPrecalculationProgressEventHandler(ProgressEventHandler value) {#setPrecalculationProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public final void setPrecalculationProgressEventHandler(ProgressEventHandler value)
```


डिफ़ॉल्ट पॉइंट्स पूर्व-गणना प्रक्रिया प्रगति इवेंट हैंडलर सेट करता है।

मान: प्रोग्रेस इवेंट हैंडलर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | डिफ़ॉल्ट पॉइंट्स पूर्व-गणना प्रक्रिया प्रगति इवेंट हैंडलर। |

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

