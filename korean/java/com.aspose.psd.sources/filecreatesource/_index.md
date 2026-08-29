---
title: "FileCreateSource"
second_title: "Java용 Aspose.PSD API 참조"
description: "생성을 위한 파일 소스를 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.aspose.psd.sources/filecreatesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.Source](../../com.aspose.psd/source), [com.aspose.psd.sources.FileSource](../../com.aspose.psd.sources/filesource)
```
public final class FileCreateSource extends FileSource
```

생성을 위한 파일 소스를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FileCreateSource(String filePath)](#FileCreateSource-java.lang.String-) | FileCreateSource 클래스의 새 인스턴스를 초기화합니다. |
| [FileCreateSource(String filePath, boolean isTemporal)](#FileCreateSource-java.lang.String-boolean-) | FileCreateSource 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFilePath()](#getFilePath--) | 생성할 파일 경로를 가져옵니다. |
| [getStreamContainer()](#getStreamContainer--) | 스트림 컨테이너를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isTemporal()](#isTemporal--) | 파일이 일시적인지 여부를 나타내는 값을 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FileCreateSource(String filePath) {#FileCreateSource-java.lang.String-}
```
public FileCreateSource(String filePath)
```


FileCreateSource 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 생성할 파일 경로. |

### FileCreateSource(String filePath, boolean isTemporal) {#FileCreateSource-java.lang.String-boolean-}
```
public FileCreateSource(String filePath, boolean isTemporal)
```


FileCreateSource 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 생성할 파일 경로. |
| isTemporal | boolean | true 로 설정하면 생성된 파일이 임시 파일이 됩니다. |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


생성할 파일 경로를 가져옵니다.

값: 생성할 파일 경로.

**Returns:**
java.lang.String
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


스트림 컨테이너를 가져옵니다.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - the stream container.

주의해서 사용하십시오. 검색 후 스트림 컨테이너를 폐기해야 합니다.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


파일이 일시적인지 여부를 나타내는 값을 가져옵니다.

값: 파일이 일시적이면 true, 그렇지 않으면 false.

**Returns:**
boolean
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

