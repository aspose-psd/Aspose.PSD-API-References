---
title: "TiffStreamReader"
second_title: "Java용 Aspose.PSD API 참조"
description: "리틀 엔디언 TIFF 파일 형식을 처리하기 위한 TIFF 스트림입니다."
type: docs
weight: 10
url: /ko/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Inheritance:**
java.lang.Object
```
public class TiffStreamReader
```

리틀 엔디언 TIFF 파일 형식을 처리하기 위한 TIFF 스트림입니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | TiffStreamReader 클래스의 새 인스턴스를 초기화합니다. |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | TiffStreamReader 클래스의 새 인스턴스를 초기화합니다. |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | TiffStreamReader 클래스의 새 인스턴스를 초기화합니다. |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.psd.StreamContainer-) | TiffStreamReader 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | 리더 길이를 가져옵니다. |
| [getThrowExceptions()](#getThrowExceptions--) | 잘못된 데이터 처리(스트림을 읽거나 쓰는 경우) 시 예외가 발생하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | 스트림에서 바이트 값 배열을 읽습니다. |
| [readBytes(long position, long count)](#readBytes-long-long-) | 스트림에서 부호 없는 바이트 값 배열을 읽습니다. |
| [readDouble(long position)](#readDouble-long-) | 스트림에서 단일 double 값을 읽습니다. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | 스트림에서 double 값 배열을 읽습니다. |
| [readFloat(long position)](#readFloat-long-) | 스트림에서 단일 float 값을 읽습니다. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | 스트림에서 부동 소수점 값 배열을 읽습니다. |
| [readRational(long position)](#readRational-long-) | 스트림에서 단일 유리수 값을 읽습니다. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | 스트림에서 유리수 값 배열을 읽습니다. |
| [readSByte(long position)](#readSByte-long-) | 스트림에서 부호 있는 바이트 데이터를 읽습니다. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | 스트림에서 부호 있는 바이트 값 배열을 읽습니다. |
| [readSLong(long position)](#readSLong-long-) | 스트림에서 부호 있는 정수 값을 읽습니다. |
| [readSLongArray(long position, long count)](#readSLongArray-long-long-) | 스트림에서 부호 있는 정수 값 배열을 읽습니다. |
| [readSRational(long position)](#readSRational-long-) | 스트림에서 단일 부호 있는 유리수 값을 읽습니다. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | 스트림에서 부호 있는 유리수 값 배열을 읽습니다. |
| [readSShort(long position)](#readSShort-long-) | 스트림에서 부호 있는 짧은 정수 값을 읽습니다. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | 스트림에서 부호 있는 짧은 정수 값 배열을 읽습니다. |
| [readString_internalized(long position)](#readString-internalized-long-) | 스트림에서 문자열을 읽습니다. |
| [readString_internalized(long position, long length)](#readString-internalized-long-long-) | 스트림에서 문자열을 읽습니다. |
| [readULong(long position)](#readULong-long-) | 스트림에서 부호 없는 정수 값을 읽습니다. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | 스트림에서 부호 없는 정수 값 배열을 읽습니다. |
| [readUShort(long position)](#readUShort-long-) | 스트림에서 부호 없는 짧은 정수 값을 읽습니다. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | 스트림에서 부호 없는 정수 값 배열을 읽습니다. |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | 잘못된 데이터 처리(스트림을 읽거나 쓰는 경우) 시 예외가 발생하는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | 기본 데이터를 스트림 컨테이너로 변환합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


TiffStreamReader 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | byte[] | 바이트 배열 데이터입니다. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


TiffStreamReader 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | byte[] | 바이트 배열 데이터입니다. |
| startIndex | int | 데이터에 대한 시작 인덱스입니다. |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


TiffStreamReader 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | byte[] | 바이트 배열 데이터입니다. |
| startIndex | int | 데이터에 대한 시작 인덱스입니다. |
| dataLength | int | 데이터 길이. |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.psd.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


TiffStreamReader 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 스트림 컨테이너입니다. |

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
### getLength() {#getLength--}
```
public long getLength()
```


리더 길이를 가져옵니다.

값: 리더 길이.

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


잘못된 데이터 처리(스트림을 읽거나 쓰는 경우) 시 예외가 발생하는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 데이터 처리 오류 시 예외가 발생하면 true이며, 그렇지 않으면 오류 조건이 조용히 무시됩니다.

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




### readBytes(byte[] array, int arrayIndex, long position, long count) {#readBytes-byte---int-long-long-}
```
public long readBytes(byte[] array, int arrayIndex, long position, long count)
```


스트림에서 바이트 값 배열을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 배열 | byte[] | 채울 배열입니다. |
| arrayIndex | int | 값을 넣기 시작할 배열 인덱스. |
| position | long | 읽을 스트림 위치. |
| count | long | 읽을 요소 개수. |

**Returns:**
long - 바이트 값 배열.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


스트림에서 부호 없는 바이트 값 배열을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 읽을 위치. |
| count | long | 요소 개수. |

**Returns:**
byte[] - 부호 없는 바이트 값 배열.
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


스트림에서 단일 double 값을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 읽을 위치. |

**Returns:**
double - 단일 double 값.
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


스트림에서 double 값 배열을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 읽을 위치. |
| count | long | 요소 개수. |

**Returns:**
double[] - double 값 배열.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


스트림에서 단일 float 값을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 읽을 위치. |

**Returns:**
float - 단일 float 값.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


스트림에서 부동 소수점 값 배열을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 읽을 위치. |
| count | long | 요소 개수. |

**Returns:**
float[] - float 값 배열.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


스트림에서 단일 유리수 값을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 읽을 위치. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


스트림에서 유리수 값 배열을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 읽을 위치. |
| count | long | 요소 개수. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - rational 값 배열.
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


스트림에서 부호 있는 바이트 데이터를 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 읽을 위치. |

**Returns:**
byte - 부호 있는 바이트 값.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


스트림에서 부호 있는 바이트 값 배열을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 읽을 위치. |
| count | long | 요소 개수. |

**Returns:**
byte[] - 부호 있는 바이트 값 배열.
### readSLong(long position) {#readSLong-long-}
```
public int readSLong(long position)
```


스트림에서 부호 있는 정수 값을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 읽을 위치. |

**Returns:**
int - 부호 있는 정수 값.
### readSLongArray(long position, long count) {#readSLongArray-long-long-}
```
public int[] readSLongArray(long position, long count)
```


스트림에서 부호 있는 정수 값 배열을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 읽을 위치. |
| count | long | 요소 개수. |

**Returns:**
int[] - 부호 있는 정수 값 배열.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


스트림에서 단일 부호 있는 유리수 값을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 읽을 위치. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - The signed rational number.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


스트림에서 부호 있는 유리수 값 배열을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 읽을 위치. |
| count | long | 요소 개수. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffSRational[] - 부호 있는 rational 값 배열.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


스트림에서 부호 있는 짧은 정수 값을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 읽을 위치. |

**Returns:**
short - 부호 있는 short 값.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


스트림에서 부호 있는 짧은 정수 값 배열을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 읽을 위치. |
| count | long | 요소 개수. |

**Returns:**
short[] - 부호 있는 short 값 배열.
### readString_internalized(long position) {#readString-internalized-long-}
```
public final String readString_internalized(long position)
```


스트림에서 문자열을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 위치. |

**Returns:**
java.lang.String - 문자열.
### readString_internalized(long position, long length) {#readString-internalized-long-long-}
```
public final String readString_internalized(long position, long length)
```


스트림에서 문자열을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 위치. |
| length | long | 길이. |

**Returns:**
java.lang.String - 문자열.
### readULong(long position) {#readULong-long-}
```
public long readULong(long position)
```


스트림에서 부호 없는 정수 값을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 읽을 위치. |

**Returns:**
long - 부호 없는 정수 값.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public long[] readULongArray(long position, long count)
```


스트림에서 부호 없는 정수 값 배열을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 읽을 위치. |
| count | long | 요소 개수. |

**Returns:**
long[] - 부호 없는 정수 값들의 배열.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


스트림에서 부호 없는 짧은 정수 값을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 읽을 위치. |

**Returns:**
int - 부호 없는 short 값.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


스트림에서 부호 없는 정수 값 배열을 읽습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| position | long | 읽을 위치. |
| count | long | 요소 개수. |

**Returns:**
int[] - 부호 없는 정수 값들의 배열.
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


잘못된 데이터 처리(스트림을 읽거나 쓰는 경우) 시 예외가 발생하는지 여부를 나타내는 값을 가져오거나 설정합니다.

값: 데이터 처리 오류 시 예외가 발생하면 true이며, 그렇지 않으면 오류 조건이 조용히 무시됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


기본 데이터를 스트림 컨테이너로 변환합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| startPosition | long | 시작 변환을 위한 시작 위치. |

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  with converted data.
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

