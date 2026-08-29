---
title: "FileSource"
second_title: "Java용 Aspose.PSD API 참조"
description: "파일 조작이 가능한 파일 소스를 나타냅니다."
type: docs
weight: 12
url: /ko/java/com.aspose.psd.sources/filesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.Source](../../com.aspose.psd/source)
```
public abstract class FileSource extends Source
```

파일 조작이 가능한 파일 소스를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FileSource()](#FileSource--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getStreamContainer()](#getStreamContainer--) | 스트림 컨테이너를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isTemporal()](#isTemporal--) | 파일이 일시적인지 여부를 나타내는 값을 가져옵니다. |
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
### getStreamContainer() {#getStreamContainer--}
```
public abstract StreamContainer getStreamContainer()
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
public abstract boolean isTemporal()
```


파일이 일시적인지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 파일이 임시인 경우 true, 그렇지 않으면 false.
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

