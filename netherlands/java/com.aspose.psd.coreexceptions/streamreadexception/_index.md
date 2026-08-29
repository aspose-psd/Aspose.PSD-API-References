---
title: "StreamReadException"
second_title: "Aspose.PSD voor Java API-referentie"
description: "De stream-lees-exception."
type: docs
weight: 22
url: /nl/java/com.aspose.psd.coreexceptions/streamreadexception/
---

**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.psd.coreexceptions.FrameworkException](../../com.aspose.psd.coreexceptions/frameworkexception)
```
public class StreamReadException extends FrameworkException
```

De stream-leesfout. Veroorzaakt wanneer het lezen van de stream mislukt door een onjuiste offset- en byteaantalverzoek.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [StreamReadException(String message)](#StreamReadException-java.lang.String-) | Initialiseert een nieuw exemplaar van de  StreamReadException  klasse. |
| [StreamReadException(String message, Throwable innerException)](#StreamReadException-java.lang.String-java.lang.Throwable-) | Initialiseert een nieuw exemplaar van de  StreamReadException  klasse. |
| [StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-java.lang.Throwable-int-int-) | Initialiseert een nieuw exemplaar van de  StreamReadException  klasse. |
| [StreamReadException(String message, int expectedReadCount, int actualReadCount)](#StreamReadException-java.lang.String-int-int-) | Initialiseert een nieuw exemplaar van de  StreamReadException  klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getActualReadCount()](#getActualReadCount--) | Haalt het werkelijke aantal gelezen bytes op. |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
| [getExpectedReadCount()](#getExpectedReadCount--) | Haalt het verwachte aantal gelezen bytes op. |
| [getInnerException()](#getInnerException--) |  |
| [getLocalizedMessage()](#getLocalizedMessage--) |  |
| [getMessage()](#getMessage--) |  |
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
### StreamReadException(String message) {#StreamReadException-java.lang.String-}
```
public StreamReadException(String message)
```


Initialiseert een nieuw exemplaar van de  StreamReadException  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het bericht. |

### StreamReadException(String message, Throwable innerException) {#StreamReadException-java.lang.String-java.lang.Throwable-}
```
public StreamReadException(String message, Throwable innerException)
```


Initialiseert een nieuw exemplaar van de  StreamReadException  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het bericht. |
| innerException | java.lang.Throwable | De interne uitzondering. |

### StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-java.lang.Throwable-int-int-}
```
public StreamReadException(String message, Throwable innerException, int expectedReadCount, int actualReadCount)
```


Initialiseert een nieuw exemplaar van de  StreamReadException  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het bericht. |
| innerException | java.lang.Throwable | De interne uitzondering. |
| expectedReadCount | int | Het verwachte leesaantal. |
| actualReadCount | int | Het werkelijke leesaantal. |

### StreamReadException(String message, int expectedReadCount, int actualReadCount) {#StreamReadException-java.lang.String-int-int-}
```
public StreamReadException(String message, int expectedReadCount, int actualReadCount)
```


Initialiseert een nieuw exemplaar van de  StreamReadException  klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| bericht | java.lang.String | Het bericht. |
| expectedReadCount | int | Het verwachte leesaantal. |
| actualReadCount | int | Het werkelijke leesaantal. |

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
### getActualReadCount() {#getActualReadCount--}
```
public int getActualReadCount()
```


Haalt het werkelijke aantal gelezen bytes op.

**Returns:**
int - Het werkelijke aantal gelezen bytes.
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
### getExpectedReadCount() {#getExpectedReadCount--}
```
public int getExpectedReadCount()
```


Haalt het verwachte aantal gelezen bytes op.

**Returns:**
int - Het verwachte aantal gelezen bytes.
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
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

