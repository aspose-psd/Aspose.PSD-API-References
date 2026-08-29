---
title: "TiffStreamWriter"
second_title: "Java용 Aspose.PSD API 참조"
description: "TIFF 스트림 라이터."
type: docs
weight: 11
url: /ko/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class TiffStreamWriter implements ISynchronizable
```

TIFF 스트림 라이터.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TiffStreamWriter(StreamContainer writer)](#TiffStreamWriter-com.aspose.psd.StreamContainer-) | TiffStreamWriter 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPosition()](#getPosition--) | 스트림 위치를 가져오거나 설정합니다. |
| [getSyncRoot()](#getSyncRoot--) | 동기화된 리소스에 대한 액세스를 동기화하는 데 사용할 수 있는 객체를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPosition(long value)](#setPosition-long-) | 스트림 위치를 가져오거나 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] data)](#write-byte---) | 지정된 데이터를 씁니다. |
| [write(byte[] data, int offset, int dataLength)](#write-byte---int-int-) | 지정된 데이터를 씁니다. |
| [writeDouble(double data)](#writeDouble-double-) | 스트림에 단일 double 값을 씁니다. |
| [writeDoubleArray(double[] data)](#writeDoubleArray-double---) | 스트림에 double 값 배열을 씁니다. |
| [writeFloat(float data)](#writeFloat-float-) | 스트림에 단일 float 값을 씁니다. |
| [writeFloatArray(float[] data)](#writeFloatArray-float---) | 스트림에 float 값 배열을 씁니다. |
| [writeRational(TiffRational data)](#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-) | 스트림에 단일 유리수 값을 씁니다. |
| [writeRationalArray(TiffRational[] data)](#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---) | 스트림에 부호 없는 유리수 값 배열을 씁니다. |
| [writeSByte(byte data)](#writeSByte-byte-) | 스트림에 단일 부호 있는 바이트 값을 씁니다. |
| [writeSByteArray(byte[] data)](#writeSByteArray-byte---) | 스트림에 부호 있는 바이트 값 배열을 씁니다. |
| [writeSLongArray(int[] data)](#writeSLongArray-int---) | 스트림에 정수 값 배열을 씁니다. |
| [writeSRational(TiffSRational data)](#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-) | 스트림에 단일 부호 있는 유리수 값을 씁니다. |
| [writeSRationalArray(TiffSRational[] data)](#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---) | 스트림에 부호 있는 유리수 값 배열을 씁니다. |
| [writeSShort(short data)](#writeSShort-short-) | 스트림에 단일 short 값을 씁니다. |
| [writeSShortArray(short[] data)](#writeSShortArray-short---) | 스트림에 short 값 배열을 씁니다. |
| [writeSlong(int data)](#writeSlong-int-) | 스트림에 단일 정수 값을 씁니다. |
| [writeUByte(byte data)](#writeUByte-byte-) | 스트림에 단일 바이트 값을 씁니다. |
| [writeULong(long data)](#writeULong-long-) | 스트림에 단일 부호 없는 정수 값을 씁니다. |
| [writeULongArray(long[] data)](#writeULongArray-long---) | 스트림에 부호 없는 정수 값 배열을 씁니다. |
| [writeUShort(int data)](#writeUShort-int-) | 스트림에 단일 부호 없는 short 값을 씁니다. |
| [writeUShortArray(int[] data)](#writeUShortArray-int---) | 스트림에 부호 없는 short 값 배열을 씁니다. |
### TiffStreamWriter(StreamContainer writer) {#TiffStreamWriter-com.aspose.psd.StreamContainer-}
```
public TiffStreamWriter(StreamContainer writer)
```


TiffStreamWriter 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| writer | [StreamContainer](../../com.aspose.psd/streamcontainer) | 스트림 라이터. |

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
### getPosition() {#getPosition--}
```
public long getPosition()
```


스트림 위치를 가져오거나 설정합니다.

값: 스트림 위치.

**Returns:**
long
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


동기화된 리소스에 대한 액세스를 동기화하는 데 사용할 수 있는 객체를 가져옵니다.

값: 동기화된 리소스에 대한 접근을 동기화하는 데 사용할 수 있는 객체.

**Returns:**
java.lang.Object
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




### setPosition(long value) {#setPosition-long-}
```
public void setPosition(long value)
```


스트림 위치를 가져오거나 설정합니다.

값: 스트림 위치.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

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

### write(byte[] data) {#write-byte---}
```
public void write(byte[] data)
```


지정된 데이터를 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | byte[] | 쓰기 위한 데이터. |

### write(byte[] data, int offset, int dataLength) {#write-byte---int-int-}
```
public void write(byte[] data, int offset, int dataLength)
```


지정된 데이터를 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | byte[] | 쓰기 위한 데이터. |
| 오프셋 | int | 데이터 오프셋. |
| dataLength | int | 데이터를 쓰기 위한 길이. |

### writeDouble(double data) {#writeDouble-double-}
```
public void writeDouble(double data)
```


스트림에 단일 double 값을 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | double | 쓰기 위한 값. |

### writeDoubleArray(double[] data) {#writeDoubleArray-double---}
```
public void writeDoubleArray(double[] data)
```


스트림에 double 값 배열을 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | double[] | 쓰기 위한 배열. |

### writeFloat(float data) {#writeFloat-float-}
```
public void writeFloat(float data)
```


스트림에 단일 float 값을 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | float | 쓰기 위한 값. |

### writeFloatArray(float[] data) {#writeFloatArray-float---}
```
public void writeFloatArray(float[] data)
```


스트림에 float 값 배열을 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | float[] | 쓰기 위한 배열. |

### writeRational(TiffRational data) {#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void writeRational(TiffRational data)
```


스트림에 단일 유리수 값을 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | 쓰기 위한 값. |

### writeRationalArray(TiffRational[] data) {#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void writeRationalArray(TiffRational[] data)
```


스트림에 부호 없는 유리수 값 배열을 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | 쓰기 위한 배열. |

### writeSByte(byte data) {#writeSByte-byte-}
```
public void writeSByte(byte data)
```


스트림에 단일 부호 있는 바이트 값을 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | byte | 쓰기 위한 값. |

### writeSByteArray(byte[] data) {#writeSByteArray-byte---}
```
public void writeSByteArray(byte[] data)
```


스트림에 부호 있는 바이트 값 배열을 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | byte[] | 쓰기 위한 배열. |

### writeSLongArray(int[] data) {#writeSLongArray-int---}
```
public void writeSLongArray(int[] data)
```


스트림에 정수 값 배열을 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | int[] | 쓰기 위한 배열. |

### writeSRational(TiffSRational data) {#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void writeSRational(TiffSRational data)
```


스트림에 단일 부호 있는 유리수 값을 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) | 쓰기 위한 값. |

### writeSRationalArray(TiffSRational[] data) {#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---}
```
public void writeSRationalArray(TiffSRational[] data)
```


스트림에 부호 있는 유리수 값 배열을 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | [TiffSRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffsrational) | 쓰기 위한 배열. |

### writeSShort(short data) {#writeSShort-short-}
```
public void writeSShort(short data)
```


스트림에 단일 short 값을 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | short | 쓰기 위한 값. |

### writeSShortArray(short[] data) {#writeSShortArray-short---}
```
public void writeSShortArray(short[] data)
```


스트림에 short 값 배열을 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | short[] | 쓰기 위한 배열. |

### writeSlong(int data) {#writeSlong-int-}
```
public void writeSlong(int data)
```


스트림에 단일 정수 값을 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | int | 쓰기 위한 값. |

### writeUByte(byte data) {#writeUByte-byte-}
```
public void writeUByte(byte data)
```


스트림에 단일 바이트 값을 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | byte | 쓰기 위한 값. |

### writeULong(long data) {#writeULong-long-}
```
public void writeULong(long data)
```


스트림에 단일 부호 없는 정수 값을 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | long | 쓰기 위한 값. |

### writeULongArray(long[] data) {#writeULongArray-long---}
```
public void writeULongArray(long[] data)
```


스트림에 부호 없는 정수 값 배열을 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | long[] | 쓰기 위한 배열. |

### writeUShort(int data) {#writeUShort-int-}
```
public void writeUShort(int data)
```


스트림에 단일 부호 없는 short 값을 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | int | 쓰기 위한 값. |

### writeUShortArray(int[] data) {#writeUShortArray-int---}
```
public void writeUShortArray(int[] data)
```


스트림에 부호 없는 short 값 배열을 씁니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | int[] | 쓰기 위한 배열. |

