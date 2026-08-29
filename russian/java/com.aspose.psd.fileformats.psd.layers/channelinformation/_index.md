---
title: "ChannelInformation"
second_title: "Aspose.PSD for Java API Справочник"
description: "Информация о канале."
type: docs
weight: 13
url: /ru/java/com.aspose.psd.fileformats.psd.layers/channelinformation/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class ChannelInformation implements Cloneable
```

Информация о канале.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)](#ChannelInformation-short-int-int-) |  |
## Поля

| Поле | Описание |
| --- | --- |
| [FullMaskChannelId_internalized](#FullMaskChannelId-internalized) | Идентификатор канала маски пользователя (растрового). |
| [ShortMaskChannelId_internalized](#ShortMaskChannelId-internalized) | Идентификатор короткого (растрового или векторного) канала маски. |
| [TransparencyMaskChannelId_internalized](#TransparencyMaskChannelId-internalized) | Идентификатор альфа‑канала |
## Методы

| Метод | Описание |
| --- | --- |
| [compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)](#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-) | Он сжимает данные канала |
| [create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)](#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [create_internalized(short compressionMethod, PsdHeader header)](#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-) |  |
| [deepClone_internalized(ChannelInformation[] info)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---) | Клонирует указанную информацию о канале. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBitDepth_internalized()](#getBitDepth-internalized--) | Получает разрядность канала. |
| [getChannelID()](#getChannelID--) | Получает или задает идентификатор канала. |
| [getClass()](#getClass--) |  |
| [getCompressionMethod()](#getCompressionMethod--) | Получает или задает метод сжатия. |
| [getData_internalized()](#getData-internalized--) | Получает или задает данные канала. |
| [getLength()](#getLength--) | Получает длину канала в байтах. |
| [getPsdHeaderVersion_internalized()](#getPsdHeaderVersion-internalized--) | Получает версию PSD |
| [getUncompressedData_internalized()](#getUncompressedData-internalized--) | Получает несжатые данные. |
| [hashCode()](#hashCode--) |  |
| [isShortMaskChannel_internalized()](#isShortMaskChannel-internalized--) | Получает, является ли канал ShortMask. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [saveChannelData_internalized(StreamContainer streamContainer)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-) |  |
| [saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)](#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-) | Сохраняет данные канала. |
| [setChannelID(short value)](#setChannelID-short-) | Получает или задает идентификатор канала. |
| [setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)](#setCompressedData-internalized-byte---int-int-) | Устанавливает сжатые данные. |
| [setCompressionMethod(short value)](#setCompressionMethod-short-) | Получает или задает метод сжатия. |
| [setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)](#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-) | Устанавливает сжатые данные. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ChannelInformation(short compressionMethod, int bitDepth, int psdVersion) {#ChannelInformation-short-int-int-}
```
public ChannelInformation(short compressionMethod, int bitDepth, int psdVersion)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| compressionMethod | short |  |
| bitDepth | int |  |
| psdVersion | int |  |

### FullMaskChannelId_internalized {#FullMaskChannelId-internalized}
```
public static final int FullMaskChannelId_internalized
```


Идентификатор пользовательского (растрового) масочного канала. (если слой имеет как векторную, так и растровую маску).

### ShortMaskChannelId_internalized {#ShortMaskChannelId-internalized}
```
public static final int ShortMaskChannelId_internalized
```


Идентификатор короткого (растрового или векторного) масочного канала. (если слой имеет только одну векторную или растровую маску, но не обе).

### TransparencyMaskChannelId_internalized {#TransparencyMaskChannelId-internalized}
```
public static final int TransparencyMaskChannelId_internalized
```


Идентификатор альфа‑канала

### compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds) {#compressChannel-internalized-byte---com.aspose.psd.Rectangle-com.aspose.psd.Rectangle-}
```
public final void compressChannel_internalized(byte[] rawData, Rectangle layerBounds, Rectangle layerMaskBounds)
```


Он сжимает данные канала

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rawData | byte[] | Исходные данные для сжатия |
| layerBounds | [Rectangle](../../com.aspose.psd/rectangle) | Границы слоя |
| layerMaskBounds | [Rectangle](../../com.aspose.psd/rectangle) | Границы маски слоя |

### create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header) {#create-internalized-byte---short-int-int-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(byte[] compressedData, short compressionMethod, int width, int height, PsdHeader header)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| compressedData | byte[] |  |
| compressionMethod | short |  |
| ширина | int |  |
| высота | int |  |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### create_internalized(short compressionMethod, PsdHeader header) {#create-internalized-short-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public static ChannelInformation create_internalized(short compressionMethod, PsdHeader header)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| compressionMethod | short |  |
| header | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

**Returns:**
[ChannelInformation](../../com.aspose.psd.fileformats.psd.layers/channelinformation)
### deepClone_internalized(ChannelInformation[] info) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.ChannelInformation---}
```
public static ChannelInformation[] deepClone_internalized(ChannelInformation[] info)
```


Клонирует указанную информацию о канале.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| info | [ChannelInformation\[\]](../../com.aspose.psd.fileformats.psd.layers/channelinformation) | Информация. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.ChannelInformation[] - Клонированная маска слоя.
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
### getBitDepth_internalized() {#getBitDepth-internalized--}
```
public final int getBitDepth_internalized()
```


Получает разрядность канала.

**Returns:**
int
### getChannelID() {#getChannelID--}
```
public final short getChannelID()
```


Получает или задает идентификатор канала.

Значение: Идентификатор канала.

**Returns:**
short
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompressionMethod() {#getCompressionMethod--}
```
public final short getCompressionMethod()
```


Получает или задает метод сжатия.

Значение: Метод сжатия.

**Returns:**
short
### getData_internalized() {#getData-internalized--}
```
public final byte[] getData_internalized()
```


Получает или задает данные канала.

Значение: Данные канала.

**Returns:**
byte[]
### getLength() {#getLength--}
```
public final long getLength()
```


Получает длину канала в байтах.

Значение: Длина.

**Returns:**
long
### getPsdHeaderVersion_internalized() {#getPsdHeaderVersion-internalized--}
```
public final int getPsdHeaderVersion_internalized()
```


Получает версию PSD

**Returns:**
int
### getUncompressedData_internalized() {#getUncompressedData-internalized--}
```
public final byte[] getUncompressedData_internalized()
```


Получает несжатые данные.

**Returns:**
byte[] -
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isShortMaskChannel_internalized() {#isShortMaskChannel-internalized--}
```
public final boolean isShortMaskChannel_internalized()
```


Получает, является ли канал ShortMask.

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




### saveChannelData_internalized(StreamContainer streamContainer) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

### saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor) {#saveChannelData-internalized-com.aspose.psd.StreamContainer-boolean-}
```
public final void saveChannelData_internalized(StreamContainer streamContainer, boolean is32BitColor)
```


Сохраняет данные канала.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока для сохранения. |
| is32BitColor | boolean | true, если цвет находится в 32‑битном режиме |

### setChannelID(short value) {#setChannelID-short-}
```
public final void setChannelID(short value)
```


Получает или задает идентификатор канала.

Значение: Идентификатор канала.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight) {#setCompressedData-internalized-byte---int-int-}
```
public final void setCompressedData_internalized(byte[] compressedData, int channelWidth, int channelHeight)
```


Устанавливает сжатые данные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| compressedData | byte[] | Сжатые данные. |
| channelWidth | int | Ширина канала. |
| channelHeight | int | Высота канала. |

### setCompressionMethod(short value) {#setCompressionMethod-short-}
```
public final void setCompressionMethod(short value)
```


Получает или задает метод сжатия.

Значение: Метод сжатия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds) {#setRawData-internalized-byte---com.aspose.psd.Size-com.aspose.psd.Rectangle-}
```
public final void setRawData_internalized(byte[] rawData, Size imageSize, Rectangle currentBounds)
```


Устанавливает сжатые данные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rawData | byte[] | Сырые данные. |
| imageSize | [Size](../../com.aspose.psd/size) | Размер изображения |
| currentBounds | [Rectangle](../../com.aspose.psd/rectangle) | Границы текущих данных канала. Если изображение большое, оно будет разделено в процессе и currentBounds != imageBounds |

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

