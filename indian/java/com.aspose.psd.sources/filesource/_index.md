---
title: "FileSource"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "फ़ाइल स्रोत का प्रतिनिधित्व करता है जो फ़ाइलों के हेरफेर में सक्षम है।"
type: docs
weight: 12
url: /hi/java/com.aspose.psd.sources/filesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.Source](../../com.aspose.psd/source)
```
public abstract class FileSource extends Source
```

फ़ाइल स्रोत का प्रतिनिधित्व करता है जो फ़ाइलों के हेरफेर में सक्षम है।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [FileSource()](#FileSource--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getStreamContainer()](#getStreamContainer--) | स्ट्रीम कंटेनर प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [isTemporal()](#isTemporal--) | फ़ाइल अस्थायी होगी या नहीं यह दर्शाने वाला मान प्राप्त करता है। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileSource() {#FileSource--}
```
public FileSource()
```


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
### getStreamContainer() {#getStreamContainer--}
```
public abstract StreamContainer getStreamContainer()
```


स्ट्रीम कंटेनर प्राप्त करता है।

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - the stream container.

सावधानी से उपयोग करें। पुनः प्राप्ति के बाद आपको स्ट्रीम कंटेनर को नष्ट करना होगा।
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isTemporal() {#isTemporal--}
```
public abstract boolean isTemporal()
```


फ़ाइल अस्थायी होगी या नहीं यह दर्शाने वाला मान प्राप्त करता है।

**Returns:**
बूलियन -  true  यदि फ़ाइल अस्थायी होगी; अन्यथा,  false .
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

