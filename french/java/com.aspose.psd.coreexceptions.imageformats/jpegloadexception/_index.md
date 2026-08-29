---
title: "JpegLoadException"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Représente l'exception de chargement d'image JPEG."
type: docs
weight: 14
url: /fr/java/com.aspose.psd.coreexceptions.imageformats/jpegloadexception/
---

**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.psd.coreexceptions.ImageException](../../com.aspose.psd.coreexceptions/imageexception), [com.aspose.psd.coreexceptions.imageformats.JpegException](../../com.aspose.psd.coreexceptions.imageformats/jpegexception)
```
public class JpegLoadException extends JpegException
```

Représente l'exception de chargement d'image JPEG.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [JpegLoadException(String message)](#JpegLoadException-java.lang.String-) | Initialise une nouvelle instance de la classe JpegLoadException. |
| [JpegLoadException(String message, Throwable innerException)](#JpegLoadException-java.lang.String-java.lang.Throwable-) | Initialise une nouvelle instance de la classe JpegLoadException. |
| [JpegLoadException(String message, int reason)](#JpegLoadException-java.lang.String-int-) | Initialise une nouvelle instance de la classe JpegLoadException. |
| [JpegLoadException(String message, Throwable innerException, int reason)](#JpegLoadException-java.lang.String-java.lang.Throwable-int-) | Initialise une nouvelle instance de la classe JpegLoadException. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
| [getComponentsInfo_internalized()](#getComponentsInfo-internalized--) | Obtient ou définit les informations des composants d'image JPEG. |
| [getInnerException()](#getInnerException--) |  |
| [getLocalizedMessage()](#getLocalizedMessage--) |  |
| [getMessage()](#getMessage--) |  |
| [getReason()](#getReason--) | Obtient ou définit la raison de l'erreur. |
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
| [setComponentsInfo_internalized(JpegComponentInfo[] value)](#setComponentsInfo-internalized-com.aspose.internal.fileformats.jpeg.JpegComponentInfo---) | Obtient ou définit les informations des composants d'image JPEG. |
| [setReason(int value)](#setReason-int-) | Obtient ou définit la raison de l'erreur. |
| [setStackTrace(StackTraceElement[] arg0)](#setStackTrace-java.lang.StackTraceElement---) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegLoadException(String message) {#JpegLoadException-java.lang.String-}
```
public JpegLoadException(String message)
```


Initialise une nouvelle instance de la classe JpegLoadException.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Le message d'exception. |

### JpegLoadException(String message, Throwable innerException) {#JpegLoadException-java.lang.String-java.lang.Throwable-}
```
public JpegLoadException(String message, Throwable innerException)
```


Initialise une nouvelle instance de la classe JpegLoadException.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Le message. |
| innerException | java.lang.Throwable | L'exception interne. |

### JpegLoadException(String message, int reason) {#JpegLoadException-java.lang.String-int-}
```
public JpegLoadException(String message, int reason)
```


Initialise une nouvelle instance de la classe JpegLoadException.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Le message d'exception. |
| raison | int | La raison de l'erreur. |

### JpegLoadException(String message, Throwable innerException, int reason) {#JpegLoadException-java.lang.String-java.lang.Throwable-int-}
```
public JpegLoadException(String message, Throwable innerException, int reason)
```


Initialise une nouvelle instance de la classe JpegLoadException.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| message | java.lang.String | Le message d'exception. |
| innerException | java.lang.Throwable | L'exception interne. |
| raison | int | La raison de l'erreur. |

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
booléen
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
### getComponentsInfo_internalized() {#getComponentsInfo-internalized--}
```
public JpegComponentInfo[] getComponentsInfo_internalized()
```


Obtient ou définit les informations des composants d'image JPEG.

Valeur : les informations des composants d'image JPEG.

**Returns:**
com.aspose.internal.fileformats.jpeg.JpegComponentInfo[]
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
### getReason() {#getReason--}
```
public int getReason()
```


Obtient ou définit la raison de l'erreur.

Valeur : la raison de l'erreur.

**Returns:**
int
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
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setComponentsInfo_internalized(JpegComponentInfo[] value) {#setComponentsInfo-internalized-com.aspose.internal.fileformats.jpeg.JpegComponentInfo---}
```
public void setComponentsInfo_internalized(JpegComponentInfo[] value)
```


Obtient ou définit les informations des composants d'image JPEG.

Valeur : les informations des composants d'image JPEG.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | com.aspose.internal.fileformats.jpeg.JpegComponentInfo[] |  |

### setReason(int value) {#setReason-int-}
```
public void setReason(int value)
```


Obtient ou définit la raison de l'erreur.

Valeur : la raison de l'erreur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

