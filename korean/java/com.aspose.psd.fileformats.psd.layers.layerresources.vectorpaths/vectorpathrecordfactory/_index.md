---
title: "VectorPathRecordFactory"
second_title: "Java용 Aspose.PSD API 참조"
description: "벡터 경로 레코드 팩토리 클래스"
type: docs
weight: 21
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecordfactory/
---

**Inheritance:**
java.lang.Object
```
public final class VectorPathRecordFactory
```

벡터 경로 레코드 팩토리 클래스
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [VectorPathRecordFactory()](#VectorPathRecordFactory--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [producePathRecord(byte[] data)](#producePathRecord-byte---) | 경로 레코드를 생성합니다. |
| [producePathRecordSerializer_internalized(VectorPathRecord vectorPathRecord)](#producePathRecordSerializer-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord-) | VectorPathRecord 유형에 따라 VectorPathRecordSerializer 파생 클래스를 생성합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorPathRecordFactory() {#VectorPathRecordFactory--}
```
public VectorPathRecordFactory()
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### producePathRecord(byte[] data) {#producePathRecord-byte---}
```
public static VectorPathRecord producePathRecord(byte[] data)
```


경로 레코드를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | byte[] | 레코드 데이터. |

**Returns:**
[VectorPathRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) - Created [VectorPathRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord)
### producePathRecordSerializer_internalized(VectorPathRecord vectorPathRecord) {#producePathRecordSerializer-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord-}
```
public static VectorPathRecordSerializer producePathRecordSerializer_internalized(VectorPathRecord vectorPathRecord)
```


VectorPathRecord 유형에 따라 VectorPathRecordSerializer 파생 클래스를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| vectorPathRecord | [VectorPathRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) | 직렬화되어야 하는 VectorPathRecord 객체. |

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.vectorpaths.serializer.VectorPathRecordSerializer - VectorPathRecordSerializer 인스턴스.
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

