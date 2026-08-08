---
title: "LayerMaskDataFull"
second_title: "Aspose.PSD for Java API Справочник"
description: "Определяет класс LayerMaskDataFull, который содержит информацию о данных маски в слое PSD‑файла, когда слой имеет как слой‑маску, так и векторные маски."
type: docs
weight: 22
url: /ru/java/com.aspose.psd.fileformats.psd.layers/layermaskdatafull/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata)
```
public final class LayerMaskDataFull extends LayerMaskData
```

Определяет класс LayerMaskDataFull, который содержит информацию о данных маски в слое файла PSD, когда слой имеет как слой, так и векторные маски. В противном случае используется [LayerMaskDataShort](../../com.aspose.psd.fileformats.psd.layers/layermaskdatashort). ImageData содержит растровую маску и растровую векторную маску, объединённые. Длина байтов ImageData должна быть равна свойствам MaskRectangle.Width \* MaskRectangle.Height.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LayerMaskDataFull()](#LayerMaskDataFull--) | Инициализирует новый экземпляр класса [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull). |
## Методы

| Метод | Описание |
| --- | --- |
| [deepClone_internalized()](#deepClone-internalized--) | Клонирует этот экземпляр. |
| [deepClone_internalized(LayerMaskData mask)](#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-) | Клонирует маску слоя. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBackgroundColor()](#getBackgroundColor--) | Получает или задает цвет фона. |
| [getBottom()](#getBottom--) | Получает или задает позицию нижней маски слоя. |
| [getClass()](#getClass--) |  |
| [getDataSize()](#getDataSize--) | Получает размер данных маски слоя. |
| [getDefaultColor()](#getDefaultColor--) | Получает или задает цвет по умолчанию. |
| [getEnclosingBottom()](#getEnclosingBottom--) | Получает или задает положение нижней части охватывающей растровой маски в слое изображения PSD. |
| [getEnclosingLeft()](#getEnclosingLeft--) | Получает или задает положение левой части охватывающей растровой маски в слое файла PSD. |
| [getEnclosingRight()](#getEnclosingRight--) | Получает или задает положение правой части охватывающей растровой маски в слое файла PSD. |
| [getEnclosingTop()](#getEnclosingTop--) | Получает или задает положение верхней части охватывающей растровой маски в слое изображения PSD. |
| [getFlags()](#getFlags--) | Получает или задает флаги маски слоя. |
| [getHeight_internalized()](#getHeight-internalized--) | Получает высоту маски. |
| [getImageData()](#getImageData--) | Получает или задает данные маски слоя (или комбинированную / окончательную маску, если присутствует векторная маска) в файле PSD. |
| [getLeft()](#getLeft--) | Получает или задает позицию левой маски слоя. |
| [getMaskRectangle()](#getMaskRectangle--) | Получает или задает mask  Rectangle  маски слоя в файле PSD. |
| [getRealFlags()](#getRealFlags--) | Получает или задает флаги маски слоя, которые используются для пользовательской/растровой маски. |
| [getRight()](#getRight--) | Получает или задает позицию правой маски слоя. |
| [getTop()](#getTop--) | Получает или задает позицию верхней маски слоя. |
| [getUserMaskData()](#getUserMaskData--) | Получает или задает данные пользовательской (растровой) маски слоя в файле PSD. |
| [getUserMaskRectangle()](#getUserMaskRectangle--) | Получает или задает прямоугольник пользовательской маски (ограничивающий) в слое изображения PSD. |
| [getWidth_internalized()](#getWidth-internalized--) | Получает ширину маски. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save_internalized(StreamContainer streamContainer)](#save-internalized-com.aspose.psd.StreamContainer-) | Сохраняет [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) в указанный StreamContainer. |
| [setBackgroundColor(byte value)](#setBackgroundColor-byte-) | Получает или задает цвет фона. |
| [setBottom(int value)](#setBottom-int-) | Получает или задает позицию нижней маски слоя. |
| [setDefaultColor(byte value)](#setDefaultColor-byte-) | Получает или задает цвет по умолчанию. |
| [setEnclosingBottom(int value)](#setEnclosingBottom-int-) | Получает или задает положение нижней части охватывающей растровой маски в слое изображения PSD. |
| [setEnclosingLeft(int value)](#setEnclosingLeft-int-) | Получает или задает положение левой части охватывающей растровой маски в слое файла PSD. |
| [setEnclosingRight(int value)](#setEnclosingRight-int-) | Получает или задает положение правой части охватывающей растровой маски в слое файла PSD. |
| [setEnclosingTop(int value)](#setEnclosingTop-int-) | Получает или задает положение верхней части охватывающей растровой маски в слое изображения PSD. |
| [setFlags(byte value)](#setFlags-byte-) | Получает или задает флаги маски слоя. |
| [setImageData(byte[] value)](#setImageData-byte---) | Получает или задает данные маски слоя (или комбинированную / окончательную маску, если присутствует векторная маска) в файле PSD. |
| [setLeft(int value)](#setLeft-int-) | Получает или задает позицию левой маски слоя. |
| [setMaskRectangle(Rectangle value)](#setMaskRectangle-com.aspose.psd.Rectangle-) | Получает или задает mask  Rectangle  маски слоя в файле PSD. |
| [setRealFlags(byte value)](#setRealFlags-byte-) | Получает или задает флаги маски слоя, которые используются для пользовательской/растровой маски. |
| [setRight(int value)](#setRight-int-) | Получает или задает позицию правой маски слоя. |
| [setTop(int value)](#setTop-int-) | Получает или задает позицию верхней маски слоя. |
| [setUserMaskData(byte[] value)](#setUserMaskData-byte---) | Получает или задает данные пользовательской (растровой) маски слоя в файле PSD. |
| [setUserMaskRectangle(Rectangle value)](#setUserMaskRectangle-com.aspose.psd.Rectangle-) | Получает или задает прямоугольник пользовательской маски (ограничивающий) в слое изображения PSD. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerMaskDataFull() {#LayerMaskDataFull--}
```
public LayerMaskDataFull()
```


Инициализирует новый экземпляр класса [LayerMaskDataFull](../../com.aspose.psd.fileformats.psd.layers/layermaskdatafull).

### deepClone_internalized() {#deepClone-internalized--}
```
public LayerMaskData deepClone_internalized()
```


Клонирует этот экземпляр.

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
### deepClone_internalized(LayerMaskData mask) {#deepClone-internalized-com.aspose.psd.fileformats.psd.layers.LayerMaskData-}
```
public static LayerMaskData deepClone_internalized(LayerMaskData mask)
```


Клонирует маску слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mask | [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) | Маска. |

**Returns:**
[LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) - The cloned layer mask.
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
### getBackgroundColor() {#getBackgroundColor--}
```
public final byte getBackgroundColor()
```


Получает или задает цвет фона.

Значение: Фоновый цвет.

**Returns:**
byte
### getBottom() {#getBottom--}
```
public final int getBottom()
```


Получает или задает позицию нижней маски слоя.

Значение: позиция нижней маски слоя.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataSize() {#getDataSize--}
```
public final int getDataSize()
```


Получает размер данных маски слоя.

Значение: Размер данных маски слоя.

**Returns:**
int
### getDefaultColor() {#getDefaultColor--}
```
public final byte getDefaultColor()
```


Получает или задает цвет по умолчанию.

Значение: Цвет по умолчанию.

**Returns:**
byte
### getEnclosingBottom() {#getEnclosingBottom--}
```
public final int getEnclosingBottom()
```


Получает или задает положение нижней части охватывающей растровой маски в слое изображения PSD.

Значение: позиция нижней маски слоя.

**Returns:**
int
### getEnclosingLeft() {#getEnclosingLeft--}
```
public final int getEnclosingLeft()
```


Получает или задает положение левой части охватывающей растровой маски в слое файла PSD.

Значение: Позиция левой маски слоя.

**Returns:**
int
### getEnclosingRight() {#getEnclosingRight--}
```
public final int getEnclosingRight()
```


Получает или задает положение правой части охватывающей растровой маски в слое файла PSD.

Значение: Позиция правой маски слоя.

**Returns:**
int
### getEnclosingTop() {#getEnclosingTop--}
```
public final int getEnclosingTop()
```


Получает или задает положение верхней части охватывающей растровой маски в слое изображения PSD.

Значение: Позиция верхней маски слоя.

**Returns:**
int
### getFlags() {#getFlags--}
```
public final byte getFlags()
```


Получает или задает флаги маски слоя.

Значение: Флаги маски слоя.

**Returns:**
byte
### getHeight_internalized() {#getHeight-internalized--}
```
public final int getHeight_internalized()
```


Получает высоту маски.

Значение: Высота.

**Returns:**
int
### getImageData() {#getImageData--}
```
public final byte[] getImageData()
```


Получает или задает данные маски слоя (или комбинированную / окончательную маску, если присутствует векторная маска) в файле PSD.

Значение: Данные изображения.

**Returns:**
byte[]
### getLeft() {#getLeft--}
```
public final int getLeft()
```


Получает или задает позицию левой маски слоя.

Значение: Позиция левой маски слоя.

**Returns:**
int
### getMaskRectangle() {#getMaskRectangle--}
```
public final Rectangle getMaskRectangle()
```


Получает или задает прямоугольник маски слоя в файле PSD. Он принимает свойства left, right, top и bottom и создает прямоугольник.

Значение: Прямоугольник маски.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getRealFlags() {#getRealFlags--}
```
public final byte getRealFlags()
```


Получает или задает флаги маски слоя, которые используются для пользовательской/растровой маски. Для векторной маски используется свойство Flags.

Значение: Реальные флаги маски слоя.

**Returns:**
byte
### getRight() {#getRight--}
```
public final int getRight()
```


Получает или задает позицию правой маски слоя.

Значение: Позиция правой маски слоя.

**Returns:**
int
### getTop() {#getTop--}
```
public final int getTop()
```


Получает или задает позицию верхней маски слоя.

Значение: Позиция верхней маски слоя.

**Returns:**
int
### getUserMaskData() {#getUserMaskData--}
```
public final byte[] getUserMaskData()
```


Получает или задает данные пользовательской (растровой) маски слоя в файле PSD. (В свойстве MaskData находится растеризованная векторная маска).

Значение: Данные изображения слоя в файле PSD.

**Returns:**
byte[]
### getUserMaskRectangle() {#getUserMaskRectangle--}
```
public final Rectangle getUserMaskRectangle()
```


Получает или задает прямоугольник пользовательской маски (ограничивающий) в слое изображения PSD.

Значение: Прямоугольник пользовательской маски.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getWidth_internalized() {#getWidth-internalized--}
```
public final int getWidth_internalized()
```


Получает ширину маски.

Значение: Ширина.

**Returns:**
int
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




### save_internalized(StreamContainer streamContainer) {#save-internalized-com.aspose.psd.StreamContainer-}
```
public void save_internalized(StreamContainer streamContainer)
```


Сохраняет [LayerMaskData](../../com.aspose.psd.fileformats.psd.layers/layermaskdata) в указанный StreamContainer.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока для сохранения данных. |

### setBackgroundColor(byte value) {#setBackgroundColor-byte-}
```
public final void setBackgroundColor(byte value)
```


Получает или задает цвет фона.

Значение: Фоновый цвет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte |  |

### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


Получает или задает позицию нижней маски слоя.

Значение: позиция нижней маски слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setDefaultColor(byte value) {#setDefaultColor-byte-}
```
public final void setDefaultColor(byte value)
```


Получает или задает цвет по умолчанию.

Значение: Цвет по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte |  |

### setEnclosingBottom(int value) {#setEnclosingBottom-int-}
```
public final void setEnclosingBottom(int value)
```


Получает или задает положение нижней части охватывающей растровой маски в слое изображения PSD.

Значение: позиция нижней маски слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setEnclosingLeft(int value) {#setEnclosingLeft-int-}
```
public final void setEnclosingLeft(int value)
```


Получает или задает положение левой части охватывающей растровой маски в слое файла PSD.

Значение: Позиция левой маски слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setEnclosingRight(int value) {#setEnclosingRight-int-}
```
public final void setEnclosingRight(int value)
```


Получает или задает положение правой части охватывающей растровой маски в слое файла PSD.

Значение: Позиция правой маски слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setEnclosingTop(int value) {#setEnclosingTop-int-}
```
public final void setEnclosingTop(int value)
```


Получает или задает положение верхней части охватывающей растровой маски в слое изображения PSD.

Значение: Позиция верхней маски слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setFlags(byte value) {#setFlags-byte-}
```
public final void setFlags(byte value)
```


Получает или задает флаги маски слоя.

Значение: Флаги маски слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte |  |

### setImageData(byte[] value) {#setImageData-byte---}
```
public final void setImageData(byte[] value)
```


Получает или задает данные маски слоя (или комбинированную / окончательную маску, если присутствует векторная маска) в файле PSD.

Значение: Данные изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Получает или задает позицию левой маски слоя.

Значение: Позиция левой маски слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setMaskRectangle(Rectangle value) {#setMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setMaskRectangle(Rectangle value)
```


Получает или задает прямоугольник маски слоя в файле PSD. Он принимает свойства left, right, top и bottom и создает прямоугольник.

Значение: Прямоугольник маски.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setRealFlags(byte value) {#setRealFlags-byte-}
```
public final void setRealFlags(byte value)
```


Получает или задает флаги маски слоя, которые используются для пользовательской/растровой маски. Для векторной маски используется свойство Flags.

Значение: Реальные флаги маски слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte |  |

### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


Получает или задает позицию правой маски слоя.

Значение: Позиция правой маски слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Получает или задает позицию верхней маски слоя.

Значение: Позиция верхней маски слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setUserMaskData(byte[] value) {#setUserMaskData-byte---}
```
public final void setUserMaskData(byte[] value)
```


Получает или задает данные пользовательской (растровой) маски слоя в файле PSD. (В свойстве MaskData находится растеризованная векторная маска).

Значение: Данные изображения слоя в файле PSD.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setUserMaskRectangle(Rectangle value) {#setUserMaskRectangle-com.aspose.psd.Rectangle-}
```
public final void setUserMaskRectangle(Rectangle value)
```


Получает или задает прямоугольник пользовательской маски (ограничивающий) в слое изображения PSD.

Значение: Прямоугольник пользовательской маски.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

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

