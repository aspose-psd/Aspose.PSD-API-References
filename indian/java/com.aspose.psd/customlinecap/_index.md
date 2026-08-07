---
title: "CustomLineCap"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "एक कस्टम उपयोगकर्ता-परिभाषित लाइन कैप को संलग्न करता है।"
type: docs
weight: 34
url: /hi/java/com.aspose.psd/customlinecap/
---

**Inheritance:**
java.lang.Object
```
public class CustomLineCap
```

एक कस्टम उपयोगकर्ता-परिभाषित लाइन कैप को संलग्न करता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-) | निर्दिष्ट रूपरेखा और भराव के साथ  CustomLineCap  क्लास का नया उदाहरण प्रारंभ करता है। |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-) | निर्दिष्ट रूपरेखा और भराव के साथ निर्दिष्ट मौजूदा  LineCap  एनीमरेशन से  CustomLineCap  क्लास का नया उदाहरण प्रारंभ करता है। |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-) | निर्दिष्ट रूपरेखा, भराव और इनसेट के साथ निर्दिष्ट मौजूदा  LineCap  एनीमरेशन से  CustomLineCap  क्लास का नया उदाहरण प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaseCap()](#getBaseCap--) | प्राप्त करता है वह  LineCap  एनीमरेशन जिस पर यह  CustomLineCap  आधारित है। |
| [getBaseInset()](#getBaseInset--) | कैप और रेखा के बीच की दूरी प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getFillPath()](#getFillPath--) | कस्टम कैप के लिए भराव को परिभाषित करने वाले ऑब्जेक्ट को प्राप्त करता है। |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | इस कस्टम कैप को बनाने वाली रेखाओं की शुरुआत और अंत में उपयोग किए जाने वाले कैप्स को प्राप्त करता है। |
| [getStrokeJoin()](#getStrokeJoin--) | प्राप्त करता है वह  LineJoin  एनीमरेशन जो निर्धारित करता है कि इस  CustomLineCap  ऑब्जेक्ट को बनाने वाली रेखाएं कैसे जुड़ी हैं। |
| [getStrokePath()](#getStrokePath--) | कस्टम कैप की रूपरेखा को परिभाषित करने वाले ऑब्जेक्ट को प्राप्त करता है। |
| [getWidthScale()](#getWidthScale--) | प्राप्त करता है वह मात्रा जिससे इस  CustomLineCap  क्लास ऑब्जेक्ट को  System.Drawing.Pen  ऑब्जेक्ट की चौड़ाई के सापेक्ष स्केल किया जाता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBaseCap(int value)](#setBaseCap-int-) | सेट करता है वह  LineCap  एनीमरेशन जिस पर यह  CustomLineCap  आधारित है। |
| [setBaseInset(float value)](#setBaseInset-float-) | कैप और रेखा के बीच की दूरी सेट करता है। |
| [setFillPath(GraphicsPath value)](#setFillPath-com.aspose.psd.GraphicsPath-) | कस्टम कैप के लिए भराव को परिभाषित करने वाले ऑब्जेक्ट को सेट करता है। |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | इस कस्टम कैप को बनाने वाली रेखाओं की शुरुआत और अंत में उपयोग किए जाने वाले कैप्स को सेट करता है। |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | सेट करता है वह  LineJoin  एनीमरेशन जो निर्धारित करता है कि इस  CustomLineCap  ऑब्जेक्ट को बनाने वाली रेखाएं कैसे जुड़ी हैं। |
| [setStrokePath(GraphicsPath value)](#setStrokePath-com.aspose.psd.GraphicsPath-) | कस्टम कैप की रूपरेखा को परिभाषित करने वाले ऑब्जेक्ट को सेट करता है। |
| [setWidthScale(float value)](#setWidthScale-float-) | सेट करता है वह मात्रा जिससे इस  CustomLineCap  क्लास ऑब्जेक्ट को  System.Drawing.Pen  ऑब्जेक्ट की चौड़ाई के सापेक्ष स्केल किया जाता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


निर्दिष्ट रूपरेखा और भराव के साथ  CustomLineCap  क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | एक  GraphicsPath  ऑब्जेक्ट जो कस्टम कैप के लिए भराव को परिभाषित करता है। |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | एक  GraphicsPath  ऑब्जेक्ट जो कस्टम कैप की रूपरेखा को परिभाषित करता है। |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


निर्दिष्ट रूपरेखा और भराव के साथ निर्दिष्ट मौजूदा  LineCap  एनीमरेशन से  CustomLineCap  क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | एक  GraphicsPath  ऑब्जेक्ट जो कस्टम कैप के लिए भराव को परिभाषित करता है। |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | एक  GraphicsPath  ऑब्जेक्ट जो कस्टम कैप की रूपरेखा को परिभाषित करता है। |
| baseCap | int | कस्टम कैप बनाने के लिए जिस line cap से शुरू किया जाता है। |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


निर्दिष्ट रूपरेखा, भराव और इनसेट के साथ निर्दिष्ट मौजूदा  LineCap  एनीमरेशन से  CustomLineCap  क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | एक  GraphicsPath  ऑब्जेक्ट जो कस्टम कैप के लिए भराव को परिभाषित करता है। |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | एक  GraphicsPath  ऑब्जेक्ट जो कस्टम कैप की रूपरेखा को परिभाषित करता है। |
| baseCap | int | कस्टम कैप बनाने के लिए जिस line cap से शुरू किया जाता है। |
| baseInset | float | कैप और लाइन के बीच की दूरी। |

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
### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


प्राप्त करता है वह  LineCap  एनीमरेशन जिस पर यह  CustomLineCap  आधारित है।

**Returns:**
int - यह CustomLineCap जिस LineCap enumeration पर आधारित है।
### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


कैप और रेखा के बीच की दूरी प्राप्त करता है।

**Returns:**
float - कैप की शुरुआत और लाइन के अंत के बीच की दूरी।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```


कस्टम कैप के लिए भराव को परिभाषित करने वाले ऑब्जेक्ट को प्राप्त करता है।

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the fill for the custom cap.
### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public void getStrokeCaps(int[] startCap, int[] endCap)
```


इस कस्टम कैप को बनाने वाली रेखाओं की शुरुआत और अंत में उपयोग किए जाने वाले कैप्स को प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startCap | int[] | इस कैप के भीतर लाइन की शुरुआत में उपयोग किया जाने वाला LineCap enumeration। |
| endCap | int[] | इस कैप के भीतर लाइन के अंत में उपयोग किया जाने वाला LineCap enumeration। |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


प्राप्त करता है वह  LineJoin  एनीमरेशन जो निर्धारित करता है कि इस  CustomLineCap  ऑब्जेक्ट को बनाने वाली रेखाएं कैसे जुड़ी हैं।

**Returns:**
int - यह CustomLineCap ऑब्जेक्ट लाइनों को जोड़ने के लिए उपयोग करता है LineJoin enumeration।
### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


कस्टम कैप की रूपरेखा को परिभाषित करने वाले ऑब्जेक्ट को प्राप्त करता है।

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the outline of the custom cap.
### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


प्राप्त करता है वह मात्रा जिससे इस  CustomLineCap  क्लास ऑब्जेक्ट को  System.Drawing.Pen  ऑब्जेक्ट की चौड़ाई के सापेक्ष स्केल किया जाता है।

**Returns:**
float - कैप को स्केल करने की मात्रा।
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




### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


सेट करता है वह  LineCap  एनीमरेशन जिस पर यह  CustomLineCap  आधारित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | यह CustomLineCap जिस LineCap enumeration पर आधारित है। |

### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


कैप और रेखा के बीच की दूरी सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | कैप की शुरुआत और लाइन के अंत के बीच की दूरी। |

### setFillPath(GraphicsPath value) {#setFillPath-com.aspose.psd.GraphicsPath-}
```
public void setFillPath(GraphicsPath value)
```


कस्टम कैप के लिए भराव को परिभाषित करने वाले ऑब्जेक्ट को सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | कस्टम कैप के लिए फ़िल को परिभाषित करने वाला ऑब्जेक्ट। |

### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public void setStrokeCaps(int startCap, int endCap)
```


इस कस्टम कैप को बनाने वाली रेखाओं की शुरुआत और अंत में उपयोग किए जाने वाले कैप्स को सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| startCap | int | इस कैप के भीतर लाइन की शुरुआत में उपयोग किया जाने वाला LineCap enumeration। |
| endCap | int | इस कैप के भीतर लाइन के अंत में उपयोग किया जाने वाला LineCap enumeration। |

### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


सेट करता है वह  LineJoin  एनीमरेशन जो निर्धारित करता है कि इस  CustomLineCap  ऑब्जेक्ट को बनाने वाली रेखाएं कैसे जुड़ी हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | यह CustomLineCap ऑब्जेक्ट लाइनों को जोड़ने के लिए उपयोग करता है LineJoin enumeration। |

### setStrokePath(GraphicsPath value) {#setStrokePath-com.aspose.psd.GraphicsPath-}
```
public void setStrokePath(GraphicsPath value)
```


कस्टम कैप की रूपरेखा को परिभाषित करने वाले ऑब्जेक्ट को सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | कस्टम कैप की रूपरेखा को परिभाषित करने वाला ऑब्जेक्ट। |

### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


सेट करता है वह मात्रा जिससे इस  CustomLineCap  क्लास ऑब्जेक्ट को  System.Drawing.Pen  ऑब्जेक्ट की चौड़ाई के सापेक्ष स्केल किया जाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | float | कैप को स्केल करने की मात्रा। |

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

