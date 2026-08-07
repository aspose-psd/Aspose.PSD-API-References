---
title: "InterruptMonitor"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "इंटरप्शन के बारे में जानकारी का प्रतिनिधित्व करता है।"
type: docs
weight: 10
url: /hi/java/com.aspose.psd.multithreading/interruptmonitor/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.multithreading.IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor)
```
public class InterruptMonitor implements IInterruptMonitor
```

इंटरप्शन के बारे में जानकारी का प्रतिनिधित्व करता है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [InterruptMonitor()](#InterruptMonitor--) | InterruptMonitor क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getThreadLocalInstance()](#getThreadLocalInstance--) | प्रत्येक थ्रेड के लिए अद्वितीय IInterruptMonitor इंस्टेंस प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [interrupt()](#interrupt--) | ऑपरेशनों को बाधित करने के लिए एक अनुरोध भेजता है। |
| [isInterrupted()](#isInterrupted--) | ऑपरेशनों को बाधित किया जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| [isThreadInterrupted()](#isThreadInterrupted--) | यदि वर्तमान थ्रेड के लिए interrupt monitor मौजूद है और उसे बाधित किया गया है तो true लौटाता है, अन्यथा false। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setThreadLocalInstance(IInterruptMonitor value)](#setThreadLocalInstance-com.aspose.psd.multithreading.IInterruptMonitor-) | प्रत्येक थ्रेड के लिए अद्वितीय IInterruptMonitor इंस्टेंस सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### InterruptMonitor() {#InterruptMonitor--}
```
public InterruptMonitor()
```


InterruptMonitor क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।

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
### getThreadLocalInstance() {#getThreadLocalInstance--}
```
public static IInterruptMonitor getThreadLocalInstance()
```


प्रत्येक थ्रेड के लिए अद्वितीय IInterruptMonitor इंस्टेंस प्राप्त करता है।

**Returns:**
[IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### interrupt() {#interrupt--}
```
public void interrupt()
```


ऑपरेशनों को बाधित करने के लिए एक अनुरोध भेजता है।

### isInterrupted() {#isInterrupted--}
```
public boolean isInterrupted()
```


ऑपरेशनों को बाधित किया जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त करता है।

**Returns:**
boolean
### isThreadInterrupted() {#isThreadInterrupted--}
```
public static boolean isThreadInterrupted()
```


यदि वर्तमान थ्रेड के लिए interrupt monitor मौजूद है और उसे बाधित किया गया है तो true लौटाता है, अन्यथा false।

**Returns:**
boolean - यदि वर्तमान थ्रेड के लिए interrupt monitor मौजूद है और उसे बाधित किया गया है तो true, अन्यथा false।
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setThreadLocalInstance(IInterruptMonitor value) {#setThreadLocalInstance-com.aspose.psd.multithreading.IInterruptMonitor-}
```
public static void setThreadLocalInstance(IInterruptMonitor value)
```


प्रत्येक थ्रेड के लिए अद्वितीय IInterruptMonitor इंस्टेंस सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IInterruptMonitor](../../com.aspose.psd.multithreading/iinterruptmonitor) |  |

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

