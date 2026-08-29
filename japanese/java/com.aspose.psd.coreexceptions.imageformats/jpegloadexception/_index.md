---
title: "JpegLoadException"
second_title: "Java 用 Aspose.PSD API リファレンス"
description: "JPEG 画像読み込み例外を表します。"
type: docs
weight: 14
url: /ja/java/com.aspose.psd.coreexceptions.imageformats/jpegloadexception/
---

**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.psd.coreexceptions.ImageException](../../com.aspose.psd.coreexceptions/imageexception), [com.aspose.psd.coreexceptions.imageformats.JpegException](../../com.aspose.psd.coreexceptions.imageformats/jpegexception)
```
public class JpegLoadException extends JpegException
```

JPEG 画像読み込み例外を表します。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [JpegLoadException(String message)](#JpegLoadException-java.lang.String-) | JpegLoadException クラスの新しいインスタンスを初期化します。 |
| [JpegLoadException(String message, Throwable innerException)](#JpegLoadException-java.lang.String-java.lang.Throwable-) | JpegLoadException クラスの新しいインスタンスを初期化します。 |
| [JpegLoadException(String message, int reason)](#JpegLoadException-java.lang.String-int-) | JpegLoadException クラスの新しいインスタンスを初期化します。 |
| [JpegLoadException(String message, Throwable innerException, int reason)](#JpegLoadException-java.lang.String-java.lang.Throwable-int-) | JpegLoadException クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
| [getComponentsInfo_internalized()](#getComponentsInfo-internalized--) | JPEG 画像コンポーネント情報を取得または設定します。 |
| [getInnerException()](#getInnerException--) |  |
| [getLocalizedMessage()](#getLocalizedMessage--) |  |
| [getMessage()](#getMessage--) |  |
| [getReason()](#getReason--) | エラーの原因を取得または設定します。 |
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
| [setComponentsInfo_internalized(JpegComponentInfo[] value)](#setComponentsInfo-internalized-com.aspose.internal.fileformats.jpeg.JpegComponentInfo---) | JPEG 画像コンポーネント情報を取得または設定します。 |
| [setReason(int value)](#setReason-int-) | エラーの原因を取得または設定します。 |
| [setStackTrace(StackTraceElement[] arg0)](#setStackTrace-java.lang.StackTraceElement---) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### JpegLoadException(String message) {#JpegLoadException-java.lang.String-}
```
public JpegLoadException(String message)
```


JpegLoadException クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String | 例外メッセージです。 |

### JpegLoadException(String message, Throwable innerException) {#JpegLoadException-java.lang.String-java.lang.Throwable-}
```
public JpegLoadException(String message, Throwable innerException)
```


JpegLoadException クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String | メッセージです。 |
| innerException | java.lang.Throwable | 内部例外です。 |

### JpegLoadException(String message, int reason) {#JpegLoadException-java.lang.String-int-}
```
public JpegLoadException(String message, int reason)
```


JpegLoadException クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String | 例外メッセージです。 |
| reason | int | エラーの原因。 |

### JpegLoadException(String message, Throwable innerException, int reason) {#JpegLoadException-java.lang.String-java.lang.Throwable-int-}
```
public JpegLoadException(String message, Throwable innerException, int reason)
```


JpegLoadException クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| メッセージ | java.lang.String | 例外メッセージです。 |
| innerException | java.lang.Throwable | 内部例外です。 |
| reason | int | エラーの原因。 |

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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


JPEG 画像コンポーネント情報を取得または設定します。

値: JPEG 画像コンポーネント情報。

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


エラーの原因を取得または設定します。

値: エラーの原因。

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
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setComponentsInfo_internalized(JpegComponentInfo[] value) {#setComponentsInfo-internalized-com.aspose.internal.fileformats.jpeg.JpegComponentInfo---}
```
public void setComponentsInfo_internalized(JpegComponentInfo[] value)
```


JPEG 画像コンポーネント情報を取得または設定します。

値: JPEG 画像コンポーネント情報。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | com.aspose.internal.fileformats.jpeg.JpegComponentInfo[] |  |

### setReason(int value) {#setReason-int-}
```
public void setReason(int value)
```


エラーの原因を取得または設定します。

値: エラーの原因。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Parameters:**
| パラメーター | 型 | 説明 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

