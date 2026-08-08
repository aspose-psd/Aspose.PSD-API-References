---
title: "TiffStreamWriter"
second_title: "Aspose.PSD for Java API Справочник"
description: "Записыватель потока TIFF."
type: docs
weight: 11
url: /ru/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.internal.interfaces.ISynchronizable
```
public class TiffStreamWriter implements ISynchronizable
```

Записыватель потока TIFF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffStreamWriter(StreamContainer writer)](#TiffStreamWriter-com.aspose.psd.StreamContainer-) | Инициализирует новый экземпляр класса TiffStreamWriter. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getPosition()](#getPosition--) | Получает или задает позицию потока. |
| [getSyncRoot()](#getSyncRoot--) | Получает объект, который может использоваться для синхронизации доступа к синхронизированному ресурсу. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPosition(long value)](#setPosition-long-) | Получает или задает позицию потока. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write(byte[] data)](#write-byte---) | Записывает указанные данные. |
| [write(byte[] data, int offset, int dataLength)](#write-byte---int-int-) | Записывает указанные данные. |
| [writeDouble(double data)](#writeDouble-double-) | Записывает одно значение double в поток. |
| [writeDoubleArray(double[] data)](#writeDoubleArray-double---) | Записывает массив значений double в поток. |
| [writeFloat(float data)](#writeFloat-float-) | Записывает одно значение float в поток. |
| [writeFloatArray(float[] data)](#writeFloatArray-float---) | Записывает массив значений float в поток. |
| [writeRational(TiffRational data)](#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-) | Записывает одно значение рационального числа в поток. |
| [writeRationalArray(TiffRational[] data)](#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---) | Записывает массив беззнаковых рациональных значений в поток. |
| [writeSByte(byte data)](#writeSByte-byte-) | Записывает одно знаковое байтовое значение в поток. |
| [writeSByteArray(byte[] data)](#writeSByteArray-byte---) | Записывает массив знаковых байтовых значений в поток. |
| [writeSLongArray(int[] data)](#writeSLongArray-int---) | Записывает массив целочисленных значений в поток. |
| [writeSRational(TiffSRational data)](#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-) | Записывает одно знаковое рациональное число в поток. |
| [writeSRationalArray(TiffSRational[] data)](#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---) | Записывает массив знаковых рациональных чисел в поток. |
| [writeSShort(short data)](#writeSShort-short-) | Записывает одно значение типа short в поток. |
| [writeSShortArray(short[] data)](#writeSShortArray-short---) | Записывает массив значений типа short в поток. |
| [writeSlong(int data)](#writeSlong-int-) | Записывает одно целочисленное значение в поток. |
| [writeUByte(byte data)](#writeUByte-byte-) | Записывает одно байтовое значение в поток. |
| [writeULong(long data)](#writeULong-long-) | Записывает одно беззнаковое целочисленное значение в поток. |
| [writeULongArray(long[] data)](#writeULongArray-long---) | Записывает массив беззнаковых целочисленных значений в поток. |
| [writeUShort(int data)](#writeUShort-int-) | Записывает одно беззнаковое значение типа short в поток. |
| [writeUShortArray(int[] data)](#writeUShortArray-int---) | Записывает массив беззнаковых значений типа short в поток. |
### TiffStreamWriter(StreamContainer writer) {#TiffStreamWriter-com.aspose.psd.StreamContainer-}
```
public TiffStreamWriter(StreamContainer writer)
```


Инициализирует новый экземпляр класса TiffStreamWriter.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| writer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Записыватель потока. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
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


Получает или задает позицию потока.

Значение: Позиция потока.

**Returns:**
long
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Получает объект, который может использоваться для синхронизации доступа к синхронизированному ресурсу.

Значение: Объект, который может использоваться для синхронизации доступа к синхронизированному ресурсу.

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


Получает или задает позицию потока.

Значение: Позиция потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | long |  |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

### write(byte[] data) {#write-byte---}
```
public void write(byte[] data)
```


Записывает указанные данные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Данные для записи. |

### write(byte[] data, int offset, int dataLength) {#write-byte---int-int-}
```
public void write(byte[] data, int offset, int dataLength)
```


Записывает указанные данные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Данные для записи. |
| смещение | int | Смещение данных. |
| dataLength | int | Длина данных для записи. |

### writeDouble(double data) {#writeDouble-double-}
```
public void writeDouble(double data)
```


Записывает одно значение double в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | double | Значение для записи. |

### writeDoubleArray(double[] data) {#writeDoubleArray-double---}
```
public void writeDoubleArray(double[] data)
```


Записывает массив значений double в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | double[] | Массив для записи. |

### writeFloat(float data) {#writeFloat-float-}
```
public void writeFloat(float data)
```


Записывает одно значение float в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | float | Значение для записи. |

### writeFloatArray(float[] data) {#writeFloatArray-float---}
```
public void writeFloatArray(float[] data)
```


Записывает массив значений float в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | float[] | Массив для записи. |

### writeRational(TiffRational data) {#writeRational-com.aspose.psd.fileformats.tiff.TiffRational-}
```
public void writeRational(TiffRational data)
```


Записывает одно значение рационального числа в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | [TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) | Значение для записи. |

### writeRationalArray(TiffRational[] data) {#writeRationalArray-com.aspose.psd.fileformats.tiff.TiffRational---}
```
public void writeRationalArray(TiffRational[] data)
```


Записывает массив беззнаковых рациональных значений в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | [TiffRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffrational) | Массив для записи. |

### writeSByte(byte data) {#writeSByte-byte-}
```
public void writeSByte(byte data)
```


Записывает одно знаковое байтовое значение в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte | Значение для записи. |

### writeSByteArray(byte[] data) {#writeSByteArray-byte---}
```
public void writeSByteArray(byte[] data)
```


Записывает массив знаковых байтовых значений в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Массив для записи. |

### writeSLongArray(int[] data) {#writeSLongArray-int---}
```
public void writeSLongArray(int[] data)
```


Записывает массив целочисленных значений в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | int[] | Массив для записи. |

### writeSRational(TiffSRational data) {#writeSRational-com.aspose.psd.fileformats.tiff.TiffSRational-}
```
public void writeSRational(TiffSRational data)
```


Записывает одно знаковое рациональное число в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | [TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) | Значение для записи. |

### writeSRationalArray(TiffSRational[] data) {#writeSRationalArray-com.aspose.psd.fileformats.tiff.TiffSRational---}
```
public void writeSRationalArray(TiffSRational[] data)
```


Записывает массив знаковых рациональных чисел в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| data | [TiffSRational\[\]](../../com.aspose.psd.fileformats.tiff/tiffsrational) | Массив для записи. |

### writeSShort(short data) {#writeSShort-short-}
```
public void writeSShort(short data)
```


Записывает одно значение типа short в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | short | Значение для записи. |

### writeSShortArray(short[] data) {#writeSShortArray-short---}
```
public void writeSShortArray(short[] data)
```


Записывает массив значений типа short в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | short[] | Массив для записи. |

### writeSlong(int data) {#writeSlong-int-}
```
public void writeSlong(int data)
```


Записывает одно целочисленное значение в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | int | Значение для записи. |

### writeUByte(byte data) {#writeUByte-byte-}
```
public void writeUByte(byte data)
```


Записывает одно байтовое значение в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte | Значение для записи. |

### writeULong(long data) {#writeULong-long-}
```
public void writeULong(long data)
```


Записывает одно беззнаковое целочисленное значение в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | long | Значение для записи. |

### writeULongArray(long[] data) {#writeULongArray-long---}
```
public void writeULongArray(long[] data)
```


Записывает массив беззнаковых целочисленных значений в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | long[] | Массив для записи. |

### writeUShort(int data) {#writeUShort-int-}
```
public void writeUShort(int data)
```


Записывает одно беззнаковое значение типа short в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | int | Значение для записи. |

### writeUShortArray(int[] data) {#writeUShortArray-int---}
```
public void writeUShortArray(int[] data)
```


Записывает массив беззнаковых значений типа short в поток.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | int[] | Массив для записи. |

