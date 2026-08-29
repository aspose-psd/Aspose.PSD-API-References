---
title: "JpegLoadException"
second_title: "Java용 Aspose.PSD API 참조"
description: "JPEG 이미지 로드 예외를 나타냅니다."
type: docs
weight: 14
url: /ko/java/com.aspose.psd.coreexceptions.imageformats/jpegloadexception/
---

**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.psd.coreexceptions.ImageException](../../com.aspose.psd.coreexceptions/imageexception), [com.aspose.psd.coreexceptions.imageformats.JpegException](../../com.aspose.psd.coreexceptions.imageformats/jpegexception)
```
public class JpegLoadException extends JpegException
```

JPEG 이미지 로드 예외를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [JpegLoadException(String message)](#JpegLoadException-java.lang.String-) | JpegLoadException 클래스의 새 인스턴스를 초기화합니다. |
| [JpegLoadException(String message, Throwable innerException)](#JpegLoadException-java.lang.String-java.lang.Throwable-) | JpegLoadException 클래스의 새 인스턴스를 초기화합니다. |
| [JpegLoadException(String message, int reason)](#JpegLoadException-java.lang.String-int-) | JpegLoadException 클래스의 새 인스턴스를 초기화합니다. |
| [JpegLoadException(String message, Throwable innerException, int reason)](#JpegLoadException-java.lang.String-java.lang.Throwable-int-) | JpegLoadException 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
| [getComponentsInfo_internalized()](#getComponentsInfo-internalized--) | JPEG 이미지 구성 요소 정보를 가져오거나 설정합니다. |
| [getInnerException()](#getInnerException--) |  |
| [getLocalizedMessage()](#getLocalizedMessage--) |  |
| [getMessage()](#getMessage--) |  |
| [getReason()](#getReason--) | 오류 이유를 가져오거나 설정합니다. |
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
| [setComponentsInfo_internalized(JpegComponentInfo[] value)](#setComponentsInfo-internalized-com.aspose.internal.fileformats.jpeg.JpegComponentInfo---) | JPEG 이미지 구성 요소 정보를 가져오거나 설정합니다. |
| [setReason(int value)](#setReason-int-) | 오류 이유를 가져오거나 설정합니다. |
| [setStackTrace(StackTraceElement[] arg0)](#setStackTrace-java.lang.StackTraceElement---) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegLoadException(String message) {#JpegLoadException-java.lang.String-}
```
public JpegLoadException(String message)
```


JpegLoadException 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String | 예외 메시지. |

### JpegLoadException(String message, Throwable innerException) {#JpegLoadException-java.lang.String-java.lang.Throwable-}
```
public JpegLoadException(String message, Throwable innerException)
```


JpegLoadException 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String | 메시지. |
| innerException | java.lang.Throwable | 내부 예외. |

### JpegLoadException(String message, int reason) {#JpegLoadException-java.lang.String-int-}
```
public JpegLoadException(String message, int reason)
```


JpegLoadException 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String | 예외 메시지. |
| 이유 | int | 오류의 이유. |

### JpegLoadException(String message, Throwable innerException, int reason) {#JpegLoadException-java.lang.String-java.lang.Throwable-int-}
```
public JpegLoadException(String message, Throwable innerException, int reason)
```


JpegLoadException 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| message | java.lang.String | 예외 메시지. |
| innerException | java.lang.Throwable | 내부 예외. |
| 이유 | int | 오류의 이유. |

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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
### getComponentsInfo_internalized() {#getComponentsInfo-internalized--}
```
public JpegComponentInfo[] getComponentsInfo_internalized()
```


JPEG 이미지 구성 요소 정보를 가져오거나 설정합니다.

값: JPEG 이미지 구성 요소 정보.

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


오류 이유를 가져오거나 설정합니다.

값: 오류의 이유.

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
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setComponentsInfo_internalized(JpegComponentInfo[] value) {#setComponentsInfo-internalized-com.aspose.internal.fileformats.jpeg.JpegComponentInfo---}
```
public void setComponentsInfo_internalized(JpegComponentInfo[] value)
```


JPEG 이미지 구성 요소 정보를 가져오거나 설정합니다.

값: JPEG 이미지 구성 요소 정보.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.internal.fileformats.jpeg.JpegComponentInfo[] |  |

### setReason(int value) {#setReason-int-}
```
public void setReason(int value)
```


오류 이유를 가져오거나 설정합니다.

값: 오류의 이유.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

