---
title: "VersionInfoResource"
second_title: "Java용 Aspose.PSD API 참조"
description: "버전 정보 리소스"
type: docs
weight: 41
url: /ko/java/com.aspose.psd.fileformats.psd.resources/versioninforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.ResourceBlock](../../com.aspose.psd.fileformats.psd/resourceblock)
```
public final class VersionInfoResource extends ResourceBlock
```

버전 정보 리소스
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [VersionInfoResource()](#VersionInfoResource--) | 새 인스턴스를 초기화합니다. [VersionInfoResource](../../com.aspose.psd.fileformats.psd.resources/versioninforesource) 클래스. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [ResouceBlockMeSaSignature](#ResouceBlockMeSaSignature) | ImageReady의 리소스 서명입니다. |
| [ResouceBlockSignature](#ResouceBlockSignature) | 일반 Photoshop 리소스 서명입니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | 리소스 데이터 크기를 바이트 단위로 가져옵니다. |
| [getFileVersion()](#getFileVersion--) | 파일 버전을 가져오거나 설정합니다. |
| [getID()](#getID--) | 리소스의 고유 식별자를 가져오거나 설정합니다. |
| [getMinimalVersion()](#getMinimalVersion--) | 최소 요구되는 PSD 버전을 가져옵니다. |
| [getName()](#getName--) | 리소스 이름을 가져오거나 설정합니다. |
| [getReaderName()](#getReaderName--) | 리더의 이름을 가져오거나 설정합니다. |
| [getSignature()](#getSignature--) | 리소스 시그니처를 가져옵니다. |
| [getSize()](#getSize--) | 데이터를 포함한 바이트 단위의 리소스 블록 크기를 가져옵니다. |
| [getVersion()](#getVersion--) | 버전을 가져오거나 설정합니다. |
| [getWriterName()](#getWriterName--) | 라이터의 이름을 가져오거나 설정합니다. |
| [hasRealMergedData()](#hasRealMergedData--) | 이 인스턴스에 실제 병합 데이터가 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer stream)](#save-com.aspose.psd.StreamContainer-) | 지정된 스트림에 리소스 블록을 저장합니다. |
| [setFileVersion(long value)](#setFileVersion-long-) | 파일 버전을 가져오거나 설정합니다. |
| [setID(short value)](#setID-short-) | 리소스의 고유 식별자를 가져오거나 설정합니다. |
| [setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)](#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-) | 레이어 및 마스크 정보를 가져오거나 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 리소스 이름을 가져오거나 설정합니다. |
| [setReaderName(String value)](#setReaderName-java.lang.String-) | 리더의 이름을 가져오거나 설정합니다. |
| [setRealMergedData(boolean value)](#setRealMergedData-boolean-) | 이 인스턴스에 실제 병합 데이터가 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [setSignature_internalized(int signature)](#setSignature-internalized-int-) |  |
| [setState_internalized(int value)](#setState-internalized-int-) | 리소스 블록 상태를 가져오거나 설정합니다. |
| [setVersion(long value)](#setVersion-long-) | 버전을 가져오거나 설정합니다. |
| [setWriterName(String value)](#setWriterName-java.lang.String-) | 라이터의 이름을 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [validateValues()](#validateValues--) | 리소스 값을 검증합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VersionInfoResource() {#VersionInfoResource--}
```
public VersionInfoResource()
```


새 인스턴스를 초기화합니다. [VersionInfoResource](../../com.aspose.psd.fileformats.psd.resources/versioninforesource) 클래스.

### ResouceBlockMeSaSignature {#ResouceBlockMeSaSignature}
```
public static final int ResouceBlockMeSaSignature
```


ImageReady의 리소스 서명입니다.

### ResouceBlockSignature {#ResouceBlockSignature}
```
public static final int ResouceBlockSignature
```


일반 Photoshop 리소스 서명입니다.

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
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


리소스 데이터 크기를 바이트 단위로 가져옵니다.

값: 리소스 데이터 크기.

**Returns:**
int
### getFileVersion() {#getFileVersion--}
```
public final long getFileVersion()
```


파일 버전을 가져오거나 설정합니다.

값: 파일 버전.

**Returns:**
long
### getID() {#getID--}
```
public final short getID()
```


리소스의 고유 식별자를 가져오거나 설정합니다.

값: 리소스의 고유 식별자.

**Returns:**
short
### getMinimalVersion() {#getMinimalVersion--}
```
public int getMinimalVersion()
```


최소 요구되는 PSD 버전을 가져옵니다.

값: 최소 PSD 버전.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


리소스 이름을 가져오거나 설정합니다. 파스칼 문자열이며, 크기를 짝수로 맞추기 위해 패딩됩니다(널 이름은 0 두 바이트로 구성됩니다).

값: 리소스 이름.

**Returns:**
java.lang.String
### getReaderName() {#getReaderName--}
```
public final String getReaderName()
```


리더의 이름을 가져오거나 설정합니다.

값: 리더의 이름.

**Returns:**
java.lang.String
### getSignature() {#getSignature--}
```
public final int getSignature()
```


리소스 시그니처를 가져옵니다. 항상 '8BIM'이어야 합니다.

값: 리소스 시그니처.

**Returns:**
int
### getSize() {#getSize--}
```
public final int getSize()
```


데이터를 포함한 바이트 단위의 리소스 블록 크기를 가져옵니다.

값: 리소스 블록 크기.

**Returns:**
int
### getVersion() {#getVersion--}
```
public final long getVersion()
```


버전을 가져오거나 설정합니다.

값: 버전.

**Returns:**
long
### getWriterName() {#getWriterName--}
```
public final String getWriterName()
```


라이터의 이름을 가져오거나 설정합니다.

값: 라이터의 이름.

**Returns:**
java.lang.String
### hasRealMergedData() {#hasRealMergedData--}
```
public final boolean hasRealMergedData()
```


이 인스턴스에 실제 병합 데이터가 있는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 이 인스턴스에 실제 병합 데이터가 있으면 true, 그렇지 않으면 false.

**Returns:**
boolean
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




### save(StreamContainer stream) {#save-com.aspose.psd.StreamContainer-}
```
public final void save(StreamContainer stream)
```


지정된 스트림에 리소스 블록을 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) | 리소스 블록을 저장할 스트림. |

### setFileVersion(long value) {#setFileVersion-long-}
```
public final void setFileVersion(long value)
```


파일 버전을 가져오거나 설정합니다.

값: 파일 버전.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setID(short value) {#setID-short-}
```
public final void setID(short value)
```


리소스의 고유 식별자를 가져오거나 설정합니다.

값: 리소스의 고유 식별자.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | short |  |

### setLayerAndMaskInfo_internalized(LayerAndMaskInfo value) {#setLayerAndMaskInfo-internalized-com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo-}
```
public final void setLayerAndMaskInfo_internalized(LayerAndMaskInfo value)
```


레이어 및 마스크 정보를 가져오거나 설정합니다.

값: 레이어 및 마스크 정보.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | com.aspose.internal.fileformats.psd.sections.LayerAndMaskInfo |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


리소스 이름을 가져오거나 설정합니다. 파스칼 문자열이며, 크기를 짝수로 맞추기 위해 패딩됩니다(널 이름은 0 두 바이트로 구성됩니다).

값: 리소스 이름.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setReaderName(String value) {#setReaderName-java.lang.String-}
```
public final void setReaderName(String value)
```


리더의 이름을 가져오거나 설정합니다.

값: 리더의 이름.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### setRealMergedData(boolean value) {#setRealMergedData-boolean-}
```
public final void setRealMergedData(boolean value)
```


이 인스턴스에 실제 병합 데이터가 있는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 이 인스턴스에 실제 병합 데이터가 있으면 true, 그렇지 않으면 false.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setSignature_internalized(int signature) {#setSignature-internalized-int-}
```
public void setSignature_internalized(int signature)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 시그니처 | int |  |

### setState_internalized(int value) {#setState-internalized-int-}
```
public final void setState_internalized(int value)
```


리소스 블록 상태를 가져오거나 설정합니다.

값: 리소스 블록 상태.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### setVersion(long value) {#setVersion-long-}
```
public final void setVersion(long value)
```


버전을 가져오거나 설정합니다.

값: 버전.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### setWriterName(String value) {#setWriterName-java.lang.String-}
```
public final void setWriterName(String value)
```


라이터의 이름을 가져오거나 설정합니다.

값: 라이터의 이름.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### validateValues() {#validateValues--}
```
public void validateValues()
```


리소스 값을 검증합니다.

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

