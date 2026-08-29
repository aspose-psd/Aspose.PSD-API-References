---
title: "ProgressEventHandlerInfo"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "यह क्लास इमेज लोड/सेव/एक्सपोर्ट ऑपरेशन्स की प्रगति के बारे में जानकारी दर्शाती है, जिसे बाहरी एप्लिकेशन में उपयोगकर्ता को रूपांतरण प्रगति दिखाने के लिए इस्तेमाल किया जा सकता है"
type: docs
weight: 10
url: /hi/java/com.aspose.psd.progressmanagement/progresseventhandlerinfo/
---

**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

यह क्लास छवि लोड/सेव/एक्सपोर्ट ऑपरेशन्स की प्रगति के बारे में जानकारी दर्शाती है, जिसे बाहरी एप्लिकेशन में उपयोगकर्ता को रूपांतरण प्रगति दिखाने के लिए इस्तेमाल किया जा सकता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)](#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-) | प्रोग्रेस इवेंट हैंडलर जोड़ता है। |
| [create_internalized(int total)](#create-internalized-int-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | इवेंट का विवरण प्राप्त करता है |
| [getEventType()](#getEventType--) | इवेंट का प्रकार प्राप्त करता है। |
| [getLatestProgressEventHandler_internalized()](#getLatestProgressEventHandler-internalized--) | नवीनतम प्रोग्रेस इवेंट हैंडलर प्राप्त करता है। |
| [getMaxValue()](#getMaxValue--) | ऊपरी प्रोग्रेस मान सीमा प्राप्त करता है। |
| [getValue()](#getValue--) | वर्तमान प्रोग्रेस मान प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [indicateProgress_internalized(EventType eventType)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-) | प्रगति को दर्शाता है। |
| [indicateProgress_internalized(EventType eventType, int value)](#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-) | प्रगति को दर्शाता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMaxValue(int value)](#setMaxValue-int-) | ऊपरी प्रोग्रेस मान सीमा। |
| [setValue_internalized(int value)](#setValue-internalized-int-) | वर्तमान प्रोग्रेस मान। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler) {#addProgressEventHalder-internalized-com.aspose.psd.ProgressEventHandler-}
```
public final void addProgressEventHalder_internalized(ProgressEventHandler progressEventHandler)
```


प्रोग्रेस इवेंट हैंडलर जोड़ता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| progressEventHandler | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | प्रोग्रेस इवेंट हैंडलर। |

### create_internalized(int total) {#create-internalized-int-}
```
public static ProgressEventHandlerInfo create_internalized(int total)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| कुल | int |  |

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.psd.progressmanagement/progresseventhandlerinfo)
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
### getDescription() {#getDescription--}
```
public final String getDescription()
```


इवेंट का विवरण प्राप्त करता है

मान: विवरण।

**Returns:**
java.lang.String - इवेंट का विवरण
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


इवेंट का प्रकार प्राप्त करता है।

मान: इवेंट का प्रकार।

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype) - the type of the event.
### getLatestProgressEventHandler_internalized() {#getLatestProgressEventHandler-internalized--}
```
public ProgressEventHandler getLatestProgressEventHandler_internalized()
```


नवीनतम प्रोग्रेस इवेंट हैंडलर प्राप्त करता है।

मान: नवीनतम प्रोग्रेस इवेंट हैंडलर।

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the latest progress event handler.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


ऊपरी प्रोग्रेस मान सीमा प्राप्त करता है।

मान: ऊपरी प्रोग्रेस मान सीमा।

**Returns:**
int - ऊपरी प्रोग्रेस मान सीमा।
### getValue() {#getValue--}
```
public final int getValue()
```


वर्तमान प्रोग्रेस मान प्राप्त करता है।

मान: प्रोग्रेस मान।

**Returns:**
int - वर्तमान प्रोग्रेस मान।
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indicateProgress_internalized(EventType eventType) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-}
```
public boolean indicateProgress_internalized(EventType eventType)
```


प्रगति को दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | इवेंट का प्रकार। |

**Returns:**
boolean - यदि सफल हो तो true, अन्यथा false
### indicateProgress_internalized(EventType eventType, int value) {#indicateProgress-internalized-com.aspose.psd.progressmanagement.EventType-int-}
```
public boolean indicateProgress_internalized(EventType eventType, int value)
```


प्रगति को दर्शाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| eventType | [EventType](../../com.aspose.psd.progressmanagement/eventtype) | इवेंट का प्रकार। |
| मान | int | मान। |

**Returns:**
boolean - यदि सफल हो तो true, अन्यथा false
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setMaxValue(int value) {#setMaxValue-int-}
```
public final void setMaxValue(int value)
```


ऊपरी प्रोग्रेस मान सीमा।

मान: ऊपरी प्रोग्रेस मान सीमा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | ऊपरी प्रगति मान सीमा. |

### setValue_internalized(int value) {#setValue-internalized-int-}
```
public final void setValue_internalized(int value)
```


वर्तमान प्रोग्रेस मान।

मान: प्रोग्रेस मान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int | वर्तमान प्रगति मान. |

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

