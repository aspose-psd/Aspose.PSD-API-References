---
title: "PsdImageResourceException"
second_title: "Aspose.PSD for Java API संदर्भ"
description: "psd इमेज रिसोर्स अपवाद।"
type: docs
weight: 18
url: /hi/java/com.aspose.psd.coreexceptions.imageformats/psdimageresourceexception/
---

**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.psd.coreexceptions.ImageException](../../com.aspose.psd.coreexceptions/imageexception), [com.aspose.psd.coreexceptions.imageformats.PsdImageException](../../com.aspose.psd.coreexceptions.imageformats/psdimageexception)
```
public class PsdImageResourceException extends PsdImageException
```

psd इमेज रिसोर्स अपवाद।
## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [PsdImageResourceException(String message, ResourceBlock resource)](#PsdImageResourceException-java.lang.String-com.aspose.psd.fileformats.psd.ResourceBlock-) | [PsdImageResourceException](../../com.aspose.psd.coreexceptions.imageformats/psdimageresourceexception) वर्ग का नया उदाहरण प्रारंभ करता है। |
| [PsdImageResourceException(String message, ResourceBlock resource, RuntimeException innerException)](#PsdImageResourceException-java.lang.String-com.aspose.psd.fileformats.psd.ResourceBlock-java.lang.RuntimeException-) | [PsdImageResourceException](../../com.aspose.psd.coreexceptions.imageformats/psdimageresourceexception) वर्ग का नया उदाहरण प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [create_internalized(String message, Error innerException)](#create-internalized-java.lang.String-java.lang.Error-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
| [getInnerException()](#getInnerException--) |  |
| [getLocalizedMessage()](#getLocalizedMessage--) |  |
| [getMessage()](#getMessage--) |  |
| [getResource()](#getResource--) | इस अपवाद का कारण बनने वाला psd संसाधन प्राप्त करता है। |
| [getStackTrace()](#getStackTrace--) |  |
| [getSuppressed()](#getSuppressed--) |  |
| [getType()](#getType--) |  |
| [hashCode()](#hashCode--) |  |
| [initCause(Throwable arg0)](#initCause-java.lang.Throwable-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [printStackTrace()](#printStackTrace--) |  |
| [printStackTrace(PrintStream arg0)](#printStackTrace-java.io.PrintStream-) |  |
| [printStackTrace(PrintWriter arg0)](#printStackTrace-java.io.PrintWriter-) |  |
| [setStackTrace(StackTraceElement[] arg0)](#setStackTrace-java.lang.StackTraceElement---) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdImageResourceException(String message, ResourceBlock resource) {#PsdImageResourceException-java.lang.String-com.aspose.psd.fileformats.psd.ResourceBlock-}
```
public PsdImageResourceException(String message, ResourceBlock resource)
```


[PsdImageResourceException](../../com.aspose.psd.coreexceptions.imageformats/psdimageresourceexception) वर्ग का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संदेश | java.lang.String | अपवाद संदेश। |
| resource | [ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock) | संसाधन। |

### PsdImageResourceException(String message, ResourceBlock resource, RuntimeException innerException) {#PsdImageResourceException-java.lang.String-com.aspose.psd.fileformats.psd.ResourceBlock-java.lang.RuntimeException-}
```
public PsdImageResourceException(String message, ResourceBlock resource, RuntimeException innerException)
```


[PsdImageResourceException](../../com.aspose.psd.coreexceptions.imageformats/psdimageresourceexception) वर्ग का नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संदेश | java.lang.String | अपवाद संदेश। |
| resource | [ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock) | संसाधन। |
| innerException | java.lang.RuntimeException | आंतरिक अपवाद। |

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

### create_internalized(String message, Error innerException) {#create-internalized-java.lang.String-java.lang.Error-}
```
public static PsdImageException create_internalized(String message, Error innerException)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संदेश | java.lang.String |  |
| innerException | java.lang.Error |  |

**Returns:**
[PsdImageException](../../com.aspose.psd.coreexceptions.imageformats/psdimageexception)
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
### fillInStackTrace() {#fillInStackTrace--}
```
public synchronized Throwable fillInStackTrace()
```




**Returns:**
java.lang.Throwable
### getCause() {#getCause--}
```
public synchronized Throwable getCause()
```




**Returns:**
java.lang.Throwable
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getInnerException() {#getInnerException--}
```
public Throwable getInnerException()
```




**Returns:**
java.lang.Throwable
### getLocalizedMessage() {#getLocalizedMessage--}
```
public String getLocalizedMessage()
```




**Returns:**
java.lang.String
### getMessage() {#getMessage--}
```
public String getMessage()
```




**Returns:**
java.lang.String
### getResource() {#getResource--}
```
public final ResourceBlock getResource()
```


इस अपवाद का कारण बनने वाला psd संसाधन प्राप्त करता है।

मान: संसाधन।

**Returns:**
[ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
### getStackTrace() {#getStackTrace--}
```
public StackTraceElement[] getStackTrace()
```




**Returns:**
java.lang.StackTraceElement[]
### getSuppressed() {#getSuppressed--}
```
public final synchronized Throwable[] getSuppressed()
```




**Returns:**
java.lang.Throwable[]
### getType() {#getType--}
```
public System.Type getType()
```




**Returns:**
com.aspose.ms.System.Type
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initCause(Throwable arg0) {#initCause-java.lang.Throwable-}
```
public synchronized Throwable initCause(Throwable arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

**Returns:**
java.lang.Throwable
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### printStackTrace() {#printStackTrace--}
```
public void printStackTrace()
```




### printStackTrace(PrintStream arg0) {#printStackTrace-java.io.PrintStream-}
```
public void printStackTrace(PrintStream arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| arg0 | java.lang.StackTraceElement[] |  |

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

