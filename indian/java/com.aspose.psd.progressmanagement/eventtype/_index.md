---
title: "EventType"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "यह एन्यूम संभावित प्रगति इवेंट प्रकारों का वर्णन करता है जो छवि प्रोसेसिंग ऑपरेशन्स के दौरान हो सकते हैं।"
type: docs
weight: 11
url: /hi/java/com.aspose.psd.progressmanagement/eventtype/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum EventType extends Enum<EventType>
```

यह एन्यूम संभावित प्रगति इवेंट प्रकारों का वर्णन करता है जो छवि प्रोसेसिंग ऑपरेशन्स के दौरान हो सकते हैं।
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [Finalization](#Finalization) | ऑपरेशन का समापन |
| [Initialization](#Initialization) | ऑपरेशन का आरंभिकरण |
| [PreProcessing](#PreProcessing) | पूर्व प्रसंस्करण |
| [Processing](#Processing) | प्रसंस्करण |
| [RelativeProgress](#RelativeProgress) | ऑपरेशन प्रसंस्करण के वर्तमान चरण की सापेक्ष प्रगति |
| [StageChange](#StageChange) | ऑपरेशन का अगला चरण शुरू हुआ |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Finalization {#Finalization}
```
public static final EventType Finalization
```


ऑपरेशन का समापन

### Initialization {#Initialization}
```
public static final EventType Initialization
```


ऑपरेशन का आरंभिकरण

### PreProcessing {#PreProcessing}
```
public static final EventType PreProcessing
```


पूर्व प्रसंस्करण

### Processing {#Processing}
```
public static final EventType Processing
```


प्रसंस्करण

### RelativeProgress {#RelativeProgress}
```
public static final EventType RelativeProgress
```


ऑपरेशन प्रसंस्करण के वर्तमान चरण की सापेक्ष प्रगति

### StageChange {#StageChange}
```
public static final EventType StageChange
```


ऑपरेशन का अगला चरण शुरू हुआ

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static EventType valueOf(String name)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String |  |

**Returns:**
[EventType](../../com.aspose.psd.progressmanagement/eventtype)
### values() {#values--}
```
public static EventType[] values()
```




**Returns:**
com.aspose.psd.progressmanagement.EventType[]
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

