---
title: "PsdImageResourceException"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "La excepción de recurso de imagen psd."
type: docs
weight: 18
url: /es/java/com.aspose.psd.coreexceptions.imageformats/psdimageresourceexception/
---

**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.psd.coreexceptions.ImageException](../../com.aspose.psd.coreexceptions/imageexception), [com.aspose.psd.coreexceptions.imageformats.PsdImageException](../../com.aspose.psd.coreexceptions.imageformats/psdimageexception)
```
public class PsdImageResourceException extends PsdImageException
```

La excepción de recurso de imagen psd.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PsdImageResourceException(String message, ResourceBlock resource)](#PsdImageResourceException-java.lang.String-com.aspose.psd.fileformats.psd.ResourceBlock-) | Inicializa una nueva instancia de la [PsdImageResourceException](../../com.aspose.psd.coreexceptions.imageformats/psdimageresourceexception) clase. |
| [PsdImageResourceException(String message, ResourceBlock resource, RuntimeException innerException)](#PsdImageResourceException-java.lang.String-com.aspose.psd.fileformats.psd.ResourceBlock-java.lang.RuntimeException-) | Inicializa una nueva instancia de la [PsdImageResourceException](../../com.aspose.psd.coreexceptions.imageformats/psdimageresourceexception) clase. |
## Métodos

| Método | Descripción |
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
| [getResource()](#getResource--) | Obtiene el recurso psd que causó esta excepción. |
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


Inicializa una nueva instancia de la [PsdImageResourceException](../../com.aspose.psd.coreexceptions.imageformats/psdimageresourceexception) clase.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje de la excepción. |
| resource | [ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock) | El recurso. |

### PsdImageResourceException(String message, ResourceBlock resource, RuntimeException innerException) {#PsdImageResourceException-java.lang.String-com.aspose.psd.fileformats.psd.ResourceBlock-java.lang.RuntimeException-}
```
public PsdImageResourceException(String message, ResourceBlock resource, RuntimeException innerException)
```


Inicializa una nueva instancia de la [PsdImageResourceException](../../com.aspose.psd.coreexceptions.imageformats/psdimageresourceexception) clase.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String | El mensaje de la excepción. |
| resource | [ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock) | El recurso. |
| innerException | java.lang.RuntimeException | La excepción interna. |

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

### create_internalized(String message, Error innerException) {#create-internalized-java.lang.String-java.lang.Error-}
```
public static PsdImageException create_internalized(String message, Error innerException)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mensaje | java.lang.String |  |
| innerException | java.lang.Error |  |

**Returns:**
[PsdImageException](../../com.aspose.psd.coreexceptions.imageformats/psdimageexception)
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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


Obtiene el recurso psd que causó esta excepción.

Valor: El recurso.

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
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

