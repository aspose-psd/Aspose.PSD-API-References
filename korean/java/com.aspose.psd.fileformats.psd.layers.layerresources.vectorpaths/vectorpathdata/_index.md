---
title: "VectorPathData"
second_title: "Java용 Aspose.PSD API 참조"
description: "벡터 경로를 다루는 클래스."
type: docs
weight: 18
url: /ko/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IVectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ivectorpathdata)
```
public final class VectorPathData implements IVectorPathData
```

벡터 경로를 다루는 클래스.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [VectorPathData(byte[] data)](#VectorPathData-byte---) | [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) 클래스의 새 인스턴스를 초기화합니다. |
| [VectorPathData()](#VectorPathData--) | [VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) 클래스의 새 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [SizeOfTheGeneralInfo_internalized](#SizeOfTheGeneralInfo-internalized) | 버전 및 플래그와 같은 일반 정보의 크기. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAsByteArray_internalized()](#getAsByteArray-internalized--) | 바이트 배열로 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 리소스에서 벡터 경로 데이터 길이를 바이트 단위로 가져옵니다. |
| [getPaths()](#getPaths--) | 경로 레코드를 가져오거나 설정합니다. |
| [getVersion()](#getVersion--) | 버전을 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [isDisabled()](#isDisabled--) | 이 인스턴스가 비활성화되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [isInverted()](#isInverted--) | 이 인스턴스가 반전되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [isNotLinked()](#isNotLinked--) | 이 인스턴스가 연결되지 않았는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDisabled(boolean value)](#setDisabled-boolean-) | 이 인스턴스가 비활성화되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setInverted(boolean value)](#setInverted-boolean-) | 이 인스턴스가 반전되었는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | 이 인스턴스가 연결되지 않았는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setPaths(VectorPathRecord[] value)](#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---) | 경로 레코드를 가져오거나 설정합니다. |
| [setVersion(int value)](#setVersion-int-) | 버전을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VectorPathData(byte[] data) {#VectorPathData-byte---}
```
public VectorPathData(byte[] data)
```


[VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | byte[] | 리소스 데이터. |

### VectorPathData() {#VectorPathData--}
```
public VectorPathData()
```


[VectorPathData](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathdata) 클래스의 새 인스턴스를 초기화합니다.

### SizeOfTheGeneralInfo_internalized {#SizeOfTheGeneralInfo-internalized}
```
public static final int SizeOfTheGeneralInfo_internalized
```


버전 및 플래그와 같은 일반 정보의 크기.

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
### getAsByteArray_internalized() {#getAsByteArray-internalized--}
```
public final byte[] getAsByteArray_internalized()
```


바이트 배열로 가져옵니다.

**Returns:**
byte[] - 리소스를 바이트 배열로.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public final int getLength()
```


리소스에서 벡터 경로 데이터 길이를 바이트 단위로 가져옵니다.

**Returns:**
int
### getPaths() {#getPaths--}
```
public final VectorPathRecord[] getPaths()
```


경로 레코드를 가져오거나 설정합니다.

값: 경로.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord[]
### getVersion() {#getVersion--}
```
public final int getVersion()
```


버전을 가져오거나 설정합니다.

값: 버전.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDisabled() {#isDisabled--}
```
public final boolean isDisabled()
```


이 인스턴스가 비활성화되었는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스가 비활성화된 경우; 그렇지 않으면,  false .

**Returns:**
boolean
### isInverted() {#isInverted--}
```
public final boolean isInverted()
```


이 인스턴스가 반전되었는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스가 반전된 경우; 그렇지 않으면,  false .

**Returns:**
boolean
### isNotLinked() {#isNotLinked--}
```
public final boolean isNotLinked()
```


이 인스턴스가 연결되지 않았는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스가 연결되지 않은 경우; 그렇지 않으면,  false .

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




### setDisabled(boolean value) {#setDisabled-boolean-}
```
public final void setDisabled(boolean value)
```


이 인스턴스가 비활성화되었는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스가 비활성화된 경우; 그렇지 않으면,  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setInverted(boolean value) {#setInverted-boolean-}
```
public final void setInverted(boolean value)
```


이 인스턴스가 반전되었는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스가 반전된 경우; 그렇지 않으면,  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public final void setNotLinked(boolean value)
```


이 인스턴스가 연결되지 않았는지 여부를 나타내는 값을 가져오거나 설정합니다.

값:  true  이 인스턴스가 연결되지 않은 경우; 그렇지 않으면,  false .

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setPaths(VectorPathRecord[] value) {#setPaths-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.VectorPathRecord---}
```
public final void setPaths(VectorPathRecord[] value)
```


경로 레코드를 가져오거나 설정합니다.

값: 경로.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [VectorPathRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/vectorpathrecord) |  |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


버전을 가져오거나 설정합니다.

값: 버전.

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

