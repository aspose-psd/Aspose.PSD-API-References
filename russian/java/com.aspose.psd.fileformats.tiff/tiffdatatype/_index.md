---
title: "TiffDataType"
second_title: "Aspose.PSD for Java API Справочник"
description: "Тип данных TIFF."
type: docs
weight: 10
url: /ru/java/com.aspose.psd.fileformats.tiff/tiffdatatype/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable
```
public abstract class TiffDataType implements Comparable<TiffDataType>
```

Тип данных TIFF.
## Методы

| Метод | Описание |
| --- | --- |
| [compareTo(TiffDataType obj)](#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-) | Сравнивает текущий экземпляр с другим объектом того же типа и возвращает целое число, указывающее, предшествует ли текущий экземпляр, следует ли за ним или находится в том же положении в порядке сортировки, что и другой объект. |
| [deepClone()](#deepClone--) | Выполняет глубокое клонирование этого экземпляра. |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [getAlignedDataSize()](#getAlignedDataSize--) | Получает размер дополнительных данных в байтах (в случае, если 12 байт недостаточно для размещения данных тега). |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Получает количество элементов. |
| [getDataSize()](#getDataSize--) | Получает размер дополнительных данных в байтах (в случае, если 12 байт недостаточно для размещения данных тега). |
| [getId()](#getId--) | Получает целочисленное представление идентификатора тега. |
| [getTagId()](#getTagId--) | Получает идентификатор тега. |
| [getTagType()](#getTagType--) | Получает тип тега. |
| [getValue()](#getValue--) | Получает значение, содержащееся в этом типе данных. |
| [hashCode()](#hashCode--) |  |
| [isPrivate_internalized()](#isPrivate-internalized--) | Получает значение, указывающее, является ли тег приватным. |
| [isValid()](#isValid--) | Получает значение, указывающее, действительны ли данные тега. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readTag(TiffStreamReader dataStream, long position)](#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-) | Читает данные тега. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Устанавливает значение, содержащееся в этом типе данных. |
| [toString()](#toString--) | Возвращает  System.String  который представляет этот экземпляр. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeAdditionalData(TiffStreamWriter dataStream)](#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-) | Записывает дополнительные данные тега. |
| [writeTag(TiffStreamWriter dataStream, long additionalDataOffset)](#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-) | Записывает данные тега. |
### compareTo(TiffDataType obj) {#compareTo-com.aspose.psd.fileformats.tiff.TiffDataType-}
```
public int compareTo(TiffDataType obj)
```


Сравнивает текущий экземпляр с другим объектом того же типа и возвращает целое число, указывающее, предшествует ли текущий экземпляр, следует ли за ним или находится в том же положении в порядке сортировки, что и другой объект.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) | Объект для сравнения с этим экземпляром. |

**Returns:**
int - 32-битное знаковое целое число, указывающее относительный порядок сравниваемых объектов. Возвращаемое значение имеет следующие значения: Значение Значение Меньше нуля Этот экземпляр меньше  obj . Ноль Этот экземпляр равен  obj . Больше нуля Этот экземпляр больше  obj .
### deepClone() {#deepClone--}
```
public TiffDataType deepClone()
```


Выполняет глубокое клонирование этого экземпляра.

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - A deep clone of the current instance.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### getAlignedDataSize() {#getAlignedDataSize--}
```
public long getAlignedDataSize()
```


Получает размер дополнительных данных в байтах (в случае, если 12 байт недостаточно для размещения данных тега).

**Returns:**
long - Размер дополнительных данных в байтах.

Это количество байтов данных, выровненное по границе слова.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCount() {#getCount--}
```
public abstract long getCount()
```


Получает количество элементов.

**Returns:**
long - Количество элементов.
### getDataSize() {#getDataSize--}
```
public abstract long getDataSize()
```


Получает размер дополнительных данных в байтах (в случае, если 12 байт недостаточно для размещения данных тега).

**Returns:**
long - Размер дополнительных данных в байтах.

Это точное количество байтов.
### getId() {#getId--}
```
public int getId()
```


Получает целочисленное представление идентификатора тега.

**Returns:**
int - Целочисленное представление идентификатора тега
### getTagId() {#getTagId--}
```
public int getTagId()
```


Получает идентификатор тега.

**Returns:**
int - Идентификатор тега.
### getTagType() {#getTagType--}
```
public abstract int getTagType()
```


Получает тип тега.

**Returns:**
int - Тип тега
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Получает значение, содержащееся в этом типе данных.

**Returns:**
java.lang.Object - Значение.
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isPrivate_internalized() {#isPrivate-internalized--}
```
public boolean isPrivate_internalized()
```


Возвращает значение, указывающее, является ли тег приватным. Приватные tiff-теги — это теги с идентификатором выше 32768.

**Returns:**
boolean -  true  если данные тега действительны; иначе  false .
### isValid() {#isValid--}
```
public boolean isValid()
```


Возвращает значение, указывающее, действительны ли данные тега. Действительный тег содержит данные, которые могут быть сохранены. Недействительный тег не может быть сохранён.

**Returns:**
boolean -  true  если данные тега действительны; иначе  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readTag(TiffStreamReader dataStream, long position) {#readTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamReader-long-}
```
public static TiffDataType readTag(TiffStreamReader dataStream, long position)
```


Читает данные тега.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataStream | [TiffStreamReader](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamreader) | Поток данных. |
| position | long | Позиция тега. |

**Returns:**
[TiffDataType](../../com.aspose.psd.fileformats.tiff/tiffdatatype) - The read tag.
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Устанавливает значение, содержащееся в этом типе данных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object | Значение. |

### toString() {#toString--}
```
public String toString()
```


Возвращает  System.String  который представляет этот экземпляр.

**Returns:**
java.lang.String -  System.String  представляющий этот экземпляр.
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

### writeAdditionalData(TiffStreamWriter dataStream) {#writeAdditionalData-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-}
```
public abstract long writeAdditionalData(TiffStreamWriter dataStream)
```


Записывает дополнительные данные тега.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | Поток данных. |

**Returns:**
long - Фактическое количество записанных байтов.
### writeTag(TiffStreamWriter dataStream, long additionalDataOffset) {#writeTag-com.aspose.psd.fileformats.tiff.filemanagement.TiffStreamWriter-long-}
```
public void writeTag(TiffStreamWriter dataStream, long additionalDataOffset)
```


Записывает данные тега.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataStream | [TiffStreamWriter](../../com.aspose.psd.fileformats.tiff.filemanagement/tiffstreamwriter) | Поток данных. |
| additionalDataOffset | long | Смещение, в которое записываются дополнительные данные. |

