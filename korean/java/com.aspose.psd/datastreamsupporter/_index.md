---
title: "DataStreamSupporter"
second_title: "Java용 Aspose.PSD API 참조"
description: "데이터 스트림 컨테이너."
type: docs
weight: 38
url: /ko/java/com.aspose.psd/datastreamsupporter/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject)
```
public abstract class DataStreamSupporter extends DisposableObject
```

데이터 스트림 컨테이너.
## 필드

| 필드 | 설명 |
| --- | --- |
| [OnSave_internalized](#OnSave-internalized) | 이미지가 로드되거나 저장될 때 발생합니다. |
| [OnUseCredit_internalized](#OnUseCredit-internalized) | 크레딧이 사용될 때 발생합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [cacheData()](#cacheData--) | 데이터를 캐시하고 기본 DataStreamSupporter.DataStreamContainer에서 추가 데이터 로드가 수행되지 않도록 보장합니다. |
| [close()](#close--) | Closable 인터페이스를 구현하며 JDK 1.7부터 try-with-resources 구문에서 사용할 수 있습니다. |
| [dispose()](#dispose--) | 현재 인스턴스를 해제합니다. |
| [doAfterSave_internalized(System.IO.Stream stream)](#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataStreamContainer()](#getDataStreamContainer--) | 객체의 데이터 스트림을 가져옵니다. |
| [getDisposed()](#getDisposed--) | 이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다. |
| [getSourceImagePath_internalized()](#getSourceImagePath-internalized--) | 소스 이미지가 존재하는 경우 파일 경로를 가져옵니다. |
| [getUseMemoryStrategy_internalized()](#getUseMemoryStrategy-internalized--) | 객체가 메모리 최적화 전략을 사용하는지 여부를 나타내는 값을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isCached()](#isCached--) | 객체의 데이터가 현재 캐시되어 있어 데이터 읽기가 필요 없는지를 나타내는 값을 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save()](#save--) | 객체의 데이터를 현재 DataStreamSupporter에 저장합니다. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | 객체 데이터를 지정된 스트림에 저장합니다. |
| [save(RandomAccessFile file)](#save-java.io.RandomAccessFile-) | 객체 데이터를 지정된 스트림에 저장합니다. |
| [save(String filePath)](#save-java.lang.String-) | 객체 데이터를 지정된 파일 위치에 저장합니다. |
| [save(String filePath, boolean overWrite)](#save-java.lang.String-boolean-) | 객체 데이터를 지정된 파일 위치에 저장합니다. |
| [save_internalized(System.IO.Stream stream)](#save-internalized-com.aspose.ms.System.IO.Stream-) |  |
| [setDataStreamContainer(StreamContainer value)](#setDataStreamContainer-com.aspose.psd.StreamContainer-) | 객체의 데이터 스트림을 설정합니다. |
| [setIgnoreAfterSave_internalized(boolean value)](#setIgnoreAfterSave-internalized-boolean-) | 저장 후 무시 여부를 나타내는 값을 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OnSave_internalized {#OnSave-internalized}
```
public static final Event<AfterSave> OnSave_internalized
```


이미지가 로드되거나 저장될 때 발생합니다.

### OnUseCredit_internalized {#OnUseCredit-internalized}
```
public static final Event<AfterUseCredit> OnUseCredit_internalized
```


크레딧이 사용될 때 발생합니다.

### cacheData() {#cacheData--}
```
public abstract void cacheData()
```


데이터를 캐시하고 기본 DataStreamSupporter.DataStreamContainer에서 추가 데이터 로드가 수행되지 않도록 보장합니다.

### close() {#close--}
```
public void close()
```


Closable 인터페이스를 구현하며 JDK 1.7부터 try-with-resources 문에서 사용할 수 있습니다. 이 메서드는 단순히 dispose 메서드를 호출합니다.

### dispose() {#dispose--}
```
public final void dispose()
```


현재 인스턴스를 해제합니다.

### doAfterSave_internalized(System.IO.Stream stream) {#doAfterSave-internalized-com.aspose.ms.System.IO.Stream-}
```
public void doAfterSave_internalized(System.IO.Stream stream)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

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
### getDataStreamContainer() {#getDataStreamContainer--}
```
public StreamContainer getDataStreamContainer()
```


객체의 데이터 스트림을 가져옵니다.

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The object's data stream.
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


이 인스턴스가 해제되었는지 여부를 나타내는 값을 가져옵니다.

**Returns:**
boolean - disposed이면 true; 그렇지 않으면 false.
### getSourceImagePath_internalized() {#getSourceImagePath-internalized--}
```
public String getSourceImagePath_internalized()
```


소스 이미지가 존재하는 경우 파일 경로를 가져옵니다. 소스 경로를 찾을 수 없으면 빈 문자열을 반환합니다.

**Returns:**
java.lang.String - 소스 이미지의 파일 경로.
### getUseMemoryStrategy_internalized() {#getUseMemoryStrategy-internalized--}
```
public boolean getUseMemoryStrategy_internalized()
```


객체가 메모리 최적화 전략을 사용하는지 여부를 나타내는 값을 가져옵니다.

값:  true  if 객체가 메모리 최적화 전략을 사용하는 경우; 그렇지 않으면  false .

**Returns:**
boolean - 객체가 메모리 최적화 전략을 사용하는지 여부를 나타내는 값
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCached() {#isCached--}
```
public abstract boolean isCached()
```


객체의 데이터가 현재 캐시되어 있어 데이터 읽기가 필요 없는지를 나타내는 값을 가져옵니다.

**Returns:**
boolean - 객체의 데이터가 현재 캐시되어 있어 데이터 읽기가 필요 없는지를 나타내는 값.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### save() {#save--}
```
public void save()
```


객체의 데이터를 현재 DataStreamSupporter에 저장합니다.

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public void save(OutputStream stream)
```


객체 데이터를 지정된 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | java.io.OutputStream | 객체 데이터를 저장할 스트림입니다. |

### save(RandomAccessFile file) {#save-java.io.RandomAccessFile-}
```
public void save(RandomAccessFile file)
```


객체 데이터를 지정된 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 파일 | java.io.RandomAccessFile | 객체 데이터를 저장할 스트림입니다. |

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


객체 데이터를 지정된 파일 위치에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 객체의 데이터를 저장할 파일 경로. |

### save(String filePath, boolean overWrite) {#save-java.lang.String-boolean-}
```
public void save(String filePath, boolean overWrite)
```


객체 데이터를 지정된 파일 위치에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 객체의 데이터를 저장할 파일 경로. |
| 덮어쓰기 | boolean | true 로 설정하면 파일 내용을 덮어쓰고, 그렇지 않으면 추가됩니다. |

### save_internalized(System.IO.Stream stream) {#save-internalized-com.aspose.ms.System.IO.Stream-}
```
public void save_internalized(System.IO.Stream stream)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### setDataStreamContainer(StreamContainer value) {#setDataStreamContainer-com.aspose.psd.StreamContainer-}
```
public void setDataStreamContainer(StreamContainer value)
```


객체의 데이터 스트림을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StreamContainer](../../com.aspose.psd/streamcontainer) | 객체의 데이터 스트림. |

### setIgnoreAfterSave_internalized(boolean value) {#setIgnoreAfterSave-internalized-boolean-}
```
public void setIgnoreAfterSave_internalized(boolean value)
```


저장 후 무시 여부를 나타내는 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | true  인 경우 [ignore after save]; 그렇지 않으면,  false . |

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

