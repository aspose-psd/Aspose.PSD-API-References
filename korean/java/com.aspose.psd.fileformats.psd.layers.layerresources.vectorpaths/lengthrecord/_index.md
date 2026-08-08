---
title: "LengthRecord"
second_title: "Java용 Aspose.PSD API 참조"
description: "서브패스 길이 레코드 클래스"
type: docs
weight: 13
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord)
```
public class LengthRecord extends VectorPathRecord
```

서브패스 길이 레코드 클래스
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [LengthRecord(byte[] data)](#LengthRecord-byte---) | [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) 클래스의 새 인스턴스를 초기화합니다. |
| [LengthRecord()](#LengthRecord--) | [LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBezierKnotRecordsCount()](#getBezierKnotRecordsCount--) | 베지어 매듭 레코드 수를 가져오거나 설정합니다. |
| [getClass()](#getClass--) |  |
| [getLength_internalized()](#getLength-internalized--) | 길이를 가져옵니다. |
| [getPathOperations()](#getPathOperations--) | 경로 작업을 가져오거나 설정합니다. |
| [getRecordCount()](#getRecordCount--) | 레코드 수를 가져오거나 설정합니다. |
| [getShapeIndex()](#getShapeIndex--) | 레이어에서 현재 경로 모양의 인덱스를 가져오거나 설정합니다. |
| [getSourceData_internalized()](#getSourceData-internalized--) | 원본 소스 데이터 바이트를 가져옵니다. |
| [getType()](#getType--) | 형식을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [isClosed()](#isClosed--) | 이 인스턴스가 닫혔는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [isOpen()](#isOpen--) | 이 인스턴스가 열려 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBezierKnotRecordsCount(int value)](#setBezierKnotRecordsCount-int-) | 베지어 매듭 레코드 수를 가져오거나 설정합니다. |
| [setClosed(boolean value)](#setClosed-boolean-) | 이 인스턴스가 닫혔는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setOpen(boolean value)](#setOpen-boolean-) | 이 인스턴스가 열려 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setPathOperations(int value)](#setPathOperations-int-) | 경로 작업을 가져오거나 설정합니다. |
| [setRecordCount(int value)](#setRecordCount-int-) | 레코드 수를 가져오거나 설정합니다. |
| [setShapeIndex(int value)](#setShapeIndex-int-) | 레이어에서 현재 경로 모양의 인덱스를 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LengthRecord(byte[] data) {#LengthRecord-byte---}
```
public LengthRecord(byte[] data)
```


[LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | byte[] | 레코드 데이터. |

### LengthRecord() {#LengthRecord--}
```
public LengthRecord()
```


[LengthRecord](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/lengthrecord) 클래스의 새 인스턴스를 초기화합니다.

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
### getBezierKnotRecordsCount() {#getBezierKnotRecordsCount--}
```
public final int getBezierKnotRecordsCount()
```


베지어 매듭 레코드 수를 가져오거나 설정합니다.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength_internalized() {#getLength-internalized--}
```
public final int getLength_internalized()
```


길이를 가져옵니다.

값: 길이.

**Returns:**
int
### getPathOperations() {#getPathOperations--}
```
public final int getPathOperations()
```


경로 작업을 가져오거나 설정합니다.

**Returns:**
int
### getRecordCount() {#getRecordCount--}
```
public final int getRecordCount()
```


레코드 수를 가져오거나 설정합니다.

값: 레코드 수.

**Returns:**
int
### getShapeIndex() {#getShapeIndex--}
```
public final int getShapeIndex()
```


레이어에서 현재 경로 모양의 인덱스를 가져오거나 설정합니다.

**Returns:**
int
### getSourceData_internalized() {#getSourceData-internalized--}
```
public final byte[] getSourceData_internalized()
```


원본 소스 데이터 바이트를 가져옵니다.

**Returns:**
byte[] - 바이트 배열.
### getType() {#getType--}
```
public short getType()
```


형식을 가져옵니다.

값: 유형.

**Returns:**
short
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isClosed() {#isClosed--}
```
public final boolean isClosed()
```


이 인스턴스가 닫혔는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 이 인스턴스가 닫혔으면 true, 그렇지 않으면 false.

**Returns:**
boolean
### isOpen() {#isOpen--}
```
public final boolean isOpen()
```


이 인스턴스가 열려 있는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스가 열려 있는 경우; 그렇지 않으면  false .

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




### setBezierKnotRecordsCount(int value) {#setBezierKnotRecordsCount-int-}
```
public final void setBezierKnotRecordsCount(int value)
```


베지어 매듭 레코드 수를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setClosed(boolean value) {#setClosed-boolean-}
```
public final void setClosed(boolean value)
```


이 인스턴스가 닫혔는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 이 인스턴스가 닫혔으면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setOpen(boolean value) {#setOpen-boolean-}
```
public final void setOpen(boolean value)
```


이 인스턴스가 열려 있는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스가 열려 있는 경우; 그렇지 않으면  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setPathOperations(int value) {#setPathOperations-int-}
```
public final void setPathOperations(int value)
```


경로 작업을 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setRecordCount(int value) {#setRecordCount-int-}
```
public final void setRecordCount(int value)
```


레코드 수를 가져오거나 설정합니다.

값: 레코드 수.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setShapeIndex(int value) {#setShapeIndex-int-}
```
public final void setShapeIndex(int value)
```


레이어에서 현재 경로 모양의 인덱스를 가져오거나 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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

