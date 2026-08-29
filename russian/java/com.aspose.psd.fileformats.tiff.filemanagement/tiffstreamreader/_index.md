---
title: "TiffStreamReader"
second_title: "Aspose.PSD for Java API Справочник"
description: "Поток TIFF для обработки формата файлов TIFF с little endian."
type: docs
weight: 10
url: /ru/java/com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader/
---

**Inheritance:**
java.lang.Object
```
public class TiffStreamReader
```

Поток TIFF для обработки формата файлов TIFF с little endian.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TiffStreamReader(byte[] data)](#TiffStreamReader-byte---) | Инициализирует новый экземпляр класса TiffStreamReader. |
| [TiffStreamReader(byte[] data, int startIndex)](#TiffStreamReader-byte---int-) | Инициализирует новый экземпляр класса TiffStreamReader. |
| [TiffStreamReader(byte[] data, int startIndex, int dataLength)](#TiffStreamReader-byte---int-int-) | Инициализирует новый экземпляр класса TiffStreamReader. |
| [TiffStreamReader(StreamContainer streamContainer)](#TiffStreamReader-com.aspose.psd.StreamContainer-) | Инициализирует новый экземпляр класса TiffStreamReader. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Получает длину читателя. |
| [getThrowExceptions()](#getThrowExceptions--) | Получает или задает значение, указывающее, выбрасываются ли исключения при некорректной обработке данных (чтении или записи в поток). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readBytes(byte[] array, int arrayIndex, long position, long count)](#readBytes-byte---int-long-long-) | Считывает массив значений типа byte из потока. |
| [readBytes(long position, long count)](#readBytes-long-long-) | Считывает массив беззнаковых значений типа byte из потока. |
| [readDouble(long position)](#readDouble-long-) | Считывает одно значение типа double из потока. |
| [readDoubleArray(long position, long count)](#readDoubleArray-long-long-) | Считывает массив значений типа double из потока. |
| [readFloat(long position)](#readFloat-long-) | Считывает одно значение типа float из потока. |
| [readFloatArray(long position, long count)](#readFloatArray-long-long-) | Считывает массив значений типа float из потока. |
| [readRational(long position)](#readRational-long-) | Считывает одно рациональное число из потока. |
| [readRationalArray(long position, long count)](#readRationalArray-long-long-) | Считывает массив рациональных значений из потока. |
| [readSByte(long position)](#readSByte-long-) | Считывает знаковые данные типа byte из потока. |
| [readSByteArray(long position, long count)](#readSByteArray-long-long-) | Считывает массив знаковых значений типа byte из потока. |
| [readSLong(long position)](#readSLong-long-) | Считывает знаковое целочисленное значение из потока. |
| [readSLongArray(long position, long count)](#readSLongArray-long-long-) | Считывает массив знаковых целочисленных значений из потока. |
| [readSRational(long position)](#readSRational-long-) | Считывает одно знаковое рациональное число из потока. |
| [readSRationalArray(long position, long count)](#readSRationalArray-long-long-) | Считывает массив знаковых рациональных значений из потока. |
| [readSShort(long position)](#readSShort-long-) | Считывает знаковое значение типа short из потока. |
| [readSShortArray(long position, long count)](#readSShortArray-long-long-) | Читает массив знаковых значений short из потока. |
| [readString_internalized(long position)](#readString-internalized-long-) | Читает строку из strea. |
| [readString_internalized(long position, long length)](#readString-internalized-long-long-) | Читает строку из strea. |
| [readULong(long position)](#readULong-long-) | Читает значение беззнакового целого из потока. |
| [readULongArray(long position, long count)](#readULongArray-long-long-) | Читает массив беззнаковых целочисленных значений из потока. |
| [readUShort(long position)](#readUShort-long-) | Читает значение беззнакового short из потока. |
| [readUShortArray(long position, long count)](#readUShortArray-long-long-) | Читает массив беззнаковых целочисленных значений из потока. |
| [setThrowExceptions(boolean value)](#setThrowExceptions-boolean-) | Получает или задает значение, указывающее, выбрасываются ли исключения при некорректной обработке данных (чтении или записи в поток). |
| [toStreamContainer(long startPosition)](#toStreamContainer-long-) | Преобразует базовые данные в контейнер потока. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TiffStreamReader(byte[] data) {#TiffStreamReader-byte---}
```
public TiffStreamReader(byte[] data)
```


Инициализирует новый экземпляр класса TiffStreamReader.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Массив байтовых данных. |

### TiffStreamReader(byte[] data, int startIndex) {#TiffStreamReader-byte---int-}
```
public TiffStreamReader(byte[] data, int startIndex)
```


Инициализирует новый экземпляр класса TiffStreamReader.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Массив байтовых данных. |
| startIndex | int | Начальный индекс в данные. |

### TiffStreamReader(byte[] data, int startIndex, int dataLength) {#TiffStreamReader-byte---int-int-}
```
public TiffStreamReader(byte[] data, int startIndex, int dataLength)
```


Инициализирует новый экземпляр класса TiffStreamReader.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | byte[] | Массив байтовых данных. |
| startIndex | int | Начальный индекс в данные. |
| dataLength | int | Длина данных. |

### TiffStreamReader(StreamContainer streamContainer) {#TiffStreamReader-com.aspose.psd.StreamContainer-}
```
public TiffStreamReader(StreamContainer streamContainer)
```


Инициализирует новый экземпляр класса TiffStreamReader.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока. |

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
### getLength() {#getLength--}
```
public long getLength()
```


Получает длину читателя.

Значение: Длина читателя.

**Returns:**
long
### getThrowExceptions() {#getThrowExceptions--}
```
public boolean getThrowExceptions()
```


Получает или задает значение, указывающее, выбрасываются ли исключения при некорректной обработке данных (чтении или записи в поток).

Значение:  true  если исключения выбрасываются при некорректной обработке данных; иначе условия ошибок игнорируются.

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


Считывает массив значений типа byte из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | byte[] | Массив для заполнения. |
| arrayIndex | int | Индекс массива, с которого начинать помещать значения. |
| position | long | Позиция потока для чтения. |
| count | long | Количество элементов для чтения. |

**Returns:**
long - Массив байтовых значений.
### readBytes(long position, long count) {#readBytes-long-long-}
```
public byte[] readBytes(long position, long count)
```


Считывает массив беззнаковых значений типа byte из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
byte[] - Массив беззнаковых байтовых значений.
### readDouble(long position) {#readDouble-long-}
```
public double readDouble(long position)
```


Считывает одно значение типа double из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция для чтения. |

**Returns:**
double - Одно значение типа double.
### readDoubleArray(long position, long count) {#readDoubleArray-long-long-}
```
public double[] readDoubleArray(long position, long count)
```


Считывает массив значений типа double из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
double[] - Массив значений типа double.
### readFloat(long position) {#readFloat-long-}
```
public float readFloat(long position)
```


Считывает одно значение типа float из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция для чтения. |

**Returns:**
float - Одно значение типа float.
### readFloatArray(long position, long count) {#readFloatArray-long-long-}
```
public float[] readFloatArray(long position, long count)
```


Считывает массив значений типа float из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
float[] - Массив значений типа float.
### readRational(long position) {#readRational-long-}
```
public TiffRational readRational(long position)
```


Считывает одно рациональное число из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция для чтения. |

**Returns:**
[TiffRational](../../com.aspose.psd.fileformats.tiff/tiffrational) - The rational number.
### readRationalArray(long position, long count) {#readRationalArray-long-long-}
```
public TiffRational[] readRationalArray(long position, long count)
```


Считывает массив рациональных значений из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffRational[] - Массив рациональных значений.
### readSByte(long position) {#readSByte-long-}
```
public byte readSByte(long position)
```


Считывает знаковые данные типа byte из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция для чтения. |

**Returns:**
byte - Значение знакового байта.
### readSByteArray(long position, long count) {#readSByteArray-long-long-}
```
public byte[] readSByteArray(long position, long count)
```


Считывает массив знаковых значений типа byte из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
byte[] - Массив значений знаковых байтов.
### readSLong(long position) {#readSLong-long-}
```
public int readSLong(long position)
```


Считывает знаковое целочисленное значение из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция для чтения. |

**Returns:**
int - Знаковое целочисленное значение.
### readSLongArray(long position, long count) {#readSLongArray-long-long-}
```
public int[] readSLongArray(long position, long count)
```


Считывает массив знаковых целочисленных значений из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
int[] - Массив значений знаковых целых чисел.
### readSRational(long position) {#readSRational-long-}
```
public TiffSRational readSRational(long position)
```


Считывает одно знаковое рациональное число из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция для чтения. |

**Returns:**
[TiffSRational](../../com.aspose.psd.fileformats.tiff/tiffsrational) - The signed rational number.
### readSRationalArray(long position, long count) {#readSRationalArray-long-long-}
```
public TiffSRational[] readSRationalArray(long position, long count)
```


Считывает массив знаковых рациональных значений из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
com.aspose.psd.fileformats.tiff.TiffSRational[] - Массив знаковых рациональных значений.
### readSShort(long position) {#readSShort-long-}
```
public short readSShort(long position)
```


Считывает знаковое значение типа short из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция для чтения. |

**Returns:**
short - Знаковое короткое значение.
### readSShortArray(long position, long count) {#readSShortArray-long-long-}
```
public short[] readSShortArray(long position, long count)
```


Читает массив знаковых значений short из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
short[] - Массив значений знаковых коротких чисел.
### readString_internalized(long position) {#readString-internalized-long-}
```
public final String readString_internalized(long position)
```


Читает строку из strea.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция. |

**Returns:**
java.lang.String - Строка.
### readString_internalized(long position, long length) {#readString-internalized-long-long-}
```
public final String readString_internalized(long position, long length)
```


Читает строку из strea.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция. |
| length | long | Длина. |

**Returns:**
java.lang.String - Строка.
### readULong(long position) {#readULong-long-}
```
public long readULong(long position)
```


Читает значение беззнакового целого из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция для чтения. |

**Returns:**
long - Беззнаковое целочисленное значение.
### readULongArray(long position, long count) {#readULongArray-long-long-}
```
public long[] readULongArray(long position, long count)
```


Читает массив беззнаковых целочисленных значений из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
long[] - Массив беззнаковых целочисленных значений.
### readUShort(long position) {#readUShort-long-}
```
public int readUShort(long position)
```


Читает значение беззнакового short из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция для чтения. |

**Returns:**
int - Беззнаковое короткое значение.
### readUShortArray(long position, long count) {#readUShortArray-long-long-}
```
public int[] readUShortArray(long position, long count)
```


Читает массив беззнаковых целочисленных значений из потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| position | long | Позиция для чтения. |
| count | long | Количество элементов. |

**Returns:**
int[] - Массив беззнаковых целочисленных значений.
### setThrowExceptions(boolean value) {#setThrowExceptions-boolean-}
```
public void setThrowExceptions(boolean value)
```


Получает или задает значение, указывающее, выбрасываются ли исключения при некорректной обработке данных (чтении или записи в поток).

Значение:  true  если исключения выбрасываются при некорректной обработке данных; иначе условия ошибок игнорируются.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### toStreamContainer(long startPosition) {#toStreamContainer-long-}
```
public StreamContainer toStreamContainer(long startPosition)
```


Преобразует базовые данные в контейнер потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startPosition | long | Начальная позиция, с которой начинается преобразование. |

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

