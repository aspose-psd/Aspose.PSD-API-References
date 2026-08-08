---
title: "AiLayerSection"
second_title: "Aspose.PSD for Java API Справочник"
description: "Раздел слоёв формата Ai"
type: docs
weight: 15
url: /ru/java/com.aspose.psd.fileformats.ai/ailayersection/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.fileformats.ai.AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
```
public final class AiLayerSection extends AiDataSection
```

Раздел слоёв формата Ai
## Методы

| Метод | Описание |
| --- | --- |
| [addRasterImage(AiRasterImageSection rasterImage)](#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-) | Добавляет растровое изображение. |
| [close()](#close--) | Реализует интерфейс Closable и может использоваться в конструкции try-with-resources, начиная с JDK 1.7. |
| [create_internalized(StreamContainer stream)](#create-internalized-com.aspose.psd.StreamContainer-) |  |
| [create_internalized(String name, String[] properties, StreamContainer stream)](#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-) |  |
| [dispose()](#dispose--) | Освобождает текущий экземпляр. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlue()](#getBlue--) | Получает или задает синий компонент цвета. |
| [getClass()](#getClass--) |  |
| [getColorIndex()](#getColorIndex--) | Получает или задает индекс цвета. |
| [getColorNumber()](#getColorNumber--) | Получает или задает номер цвета. |
| [getData()](#getData--) | Получает строковые данные. |
| [getDimValue()](#getDimValue--) | Получает или задает значение затемнения в процентах. |
| [getDisposed()](#getDisposed--) | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [getGreen()](#getGreen--) | Получает или задает зеленый компонент цвета. |
| [getName()](#getName--) | Получает или задает имя слоя. |
| [getRasterImages()](#getRasterImages--) | Получает растровые изображения. |
| [getRed()](#getRed--) | Получает или задает компонент красного цвета. |
| [getStream_internalized()](#getStream-internalized--) | Получает внутренний поток |
| [hasMultiLayerMasks()](#hasMultiLayerMasks--) | Получает или задает значение, указывающее, имеет ли данный экземпляр многослойные маски. |
| [hashCode()](#hashCode--) |  |
| [isImagesDimmed()](#isImagesDimmed--) | Получает или задает значение, указывающее, затемнён ли этот слой. |
| [isLocked()](#isLocked--) | Получает или задает значение, указывающее, заблокирован ли этот слой. |
| [isPreview()](#isPreview--) | Получает или задает значение, указывающее, является ли этот слой предварительным просмотром. |
| [isPrinted()](#isPrinted--) | Получает или задает значение, указывающее, будет ли этот слой напечатан. |
| [isShown()](#isShown--) | Получает или задает значение, указывающее, отображается ли этот слой. |
| [isTemplate()](#isTemplate--) | Получает или задает значение, указывающее, является ли этот слой шаблонным. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlue(int value)](#setBlue-int-) | Получает или задает синий компонент цвета. |
| [setColorIndex(int value)](#setColorIndex-int-) | Получает или задает индекс цвета. |
| [setColorNumber(int value)](#setColorNumber-int-) | Получает или задает номер цвета. |
| [setDimValue(int value)](#setDimValue-int-) | Получает или задает значение затемнения в процентах. |
| [setGreen(int value)](#setGreen-int-) | Получает или задает зеленый компонент цвета. |
| [setImagesDimmed(boolean value)](#setImagesDimmed-boolean-) | Получает или задает значение, указывающее, затемнён ли этот слой. |
| [setLocked(boolean value)](#setLocked-boolean-) | Получает или задает значение, указывающее, заблокирован ли этот слой. |
| [setMultiLayerMasks(boolean value)](#setMultiLayerMasks-boolean-) | Получает или задает значение, указывающее, имеет ли данный экземпляр многослойные маски. |
| [setName(String value)](#setName-java.lang.String-) | Получает или задает имя слоя. |
| [setPreview(boolean value)](#setPreview-boolean-) | Получает или задает значение, указывающее, является ли этот слой предварительным просмотром. |
| [setPrinted(boolean value)](#setPrinted-boolean-) | Получает или задает значение, указывающее, будет ли этот слой напечатан. |
| [setRed(int value)](#setRed-int-) | Получает или задает компонент красного цвета. |
| [setShown(boolean value)](#setShown-boolean-) | Получает или задает значение, указывающее, отображается ли этот слой. |
| [setTemplate(boolean value)](#setTemplate-boolean-) | Получает или задает значение, указывающее, является ли этот слой шаблонным. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### addRasterImage(AiRasterImageSection rasterImage) {#addRasterImage-com.aspose.psd.fileformats.ai.AiRasterImageSection-}
```
public final void addRasterImage(AiRasterImageSection rasterImage)
```


Добавляет растровое изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | [AiRasterImageSection](../../com.aspose.psd.fileformats.ai/airasterimagesection) | Растровое изображение. |

### close() {#close--}
```
public void close()
```


Реализует интерфейс Closable и может использоваться в операторе try-with-resources, начиная с JDK 1.7. Этот метод просто вызывает метод dispose.

### create_internalized(StreamContainer stream) {#create-internalized-com.aspose.psd.StreamContainer-}
```
public static AiDataSection create_internalized(StreamContainer stream)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiDataSection](../../com.aspose.psd.fileformats.ai/aidatasection)
### create_internalized(String name, String[] properties, StreamContainer stream) {#create-internalized-java.lang.String-java.lang.String---com.aspose.psd.StreamContainer-}
```
public static AiLayerSection create_internalized(String name, String[] properties, StreamContainer stream)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |
| свойства | java.lang.String[] |  |
| stream | [StreamContainer](../../com.aspose.psd/streamcontainer) |  |

**Returns:**
[AiLayerSection](../../com.aspose.psd.fileformats.ai/ailayersection)
### dispose() {#dispose--}
```
public final void dispose()
```


Освобождает текущий экземпляр.

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
### getBlue() {#getBlue--}
```
public final int getBlue()
```


Получает или задает синий компонент цвета.

Значение: Компонент синего цвета.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorIndex() {#getColorIndex--}
```
public final int getColorIndex()
```


Получает или задает индекс цвета. Этот аргумент может принимать значения от \\u20131 до 26. Каждый целочисленный параметр представляет цвет, который может быть назначен слою для целей идентификации пользователя.

Значение: Индекс цвета.

**Returns:**
int
### getColorNumber() {#getColorNumber--}
```
public final int getColorNumber()
```


Получает или задает номер цвета. -1 — пользовательское значение цвета из свойств Красный, Зеленый, Синий. Указывает настройку цвета слоя\\u2019.

Значение: Номер цвета.

**Returns:**
int
### getData() {#getData--}
```
public final String getData()
```


Получает строковые данные.

**Returns:**
java.lang.String - Строковые данные раздела
### getDimValue() {#getDimValue--}
```
public final int getDimValue()
```


Получает или задает значение затемнения в процентах. Уменьшает интенсивность связанных изображений и растровых изображений, содержащихся в слое, до указанного процента.

Значение: Значение затемнения в процентах.

**Returns:**
int
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Получает значение, указывающее, освобожден ли этот экземпляр.

**Returns:**
boolean -  true  если освобождено; иначе,  false .
### getGreen() {#getGreen--}
```
public final int getGreen()
```


Получает или задает зеленый компонент цвета.

Значение: Компонент зелёного цвета.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Получает или задает имя слоя. Указывает имя элемента, как оно отображается в панели Слои.

Значение: Имя слоя.

**Returns:**
java.lang.String
### getRasterImages() {#getRasterImages--}
```
public final AiRasterImageSection[] getRasterImages()
```


Получает растровые изображения.

Значение: Растровые изображения.

**Returns:**
com.aspose.psd.fileformats.ai.AiRasterImageSection[]
### getRed() {#getRed--}
```
public final int getRed()
```


Получает или задает компонент красного цвета.

Значение: Компонент красного цвета.

**Returns:**
int
### getStream_internalized() {#getStream-internalized--}
```
public final StreamContainer getStream_internalized()
```


Получает внутренний поток

**Returns:**
[StreamContainer](../../com.aspose.psd/streamcontainer) - The  StreamContainer  instance.
### hasMultiLayerMasks() {#hasMultiLayerMasks--}
```
public final boolean hasMultiLayerMasks()
```


Получает или задает значение, указывающее, имеет ли данный экземпляр многослойные маски.

Значение:  true  если у данного экземпляра есть многослойные маски; иначе  false .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isImagesDimmed() {#isImagesDimmed--}
```
public final boolean isImagesDimmed()
```


Получает или задает значение, указывающее, затемнён ли этот слой. Уменьшает интенсивность связанных изображений и растровых изображений, содержащихся в слое.

Значение:  true  если слой затемнён; иначе  false .

**Returns:**
boolean
### isLocked() {#isLocked--}
```
public final boolean isLocked()
```


Получает или задает значение, указывающее, заблокирован ли этот слой. Предотвращает изменения элемента.

Значение:  true  если этот слой заблокирован; иначе,  false .

**Returns:**
boolean
### isPreview() {#isPreview--}
```
public final boolean isPreview()
```


Получает или задает значение, указывающее, является ли этот слой предварительным просмотром. Отображает рисунок, содержащийся в слое, в цвете вместо контуров.

Значение:  true  если этот слой является предварительным просмотром; иначе,  false .

**Returns:**
boolean
### isPrinted() {#isPrinted--}
```
public final boolean isPrinted()
```


Получает или задает значение, указывающее, печатается ли этот слой. Делает рисунок, содержащийся в слое, печатаемым, если значение true.

Значение:  true  если этот слой печатается; иначе,  false .

**Returns:**
boolean
### isShown() {#isShown--}
```
public final boolean isShown()
```


Получает или задает значение, указывающее, отображается ли этот слой. Отображает весь рисунок, содержащийся в слое, на рабочей области, если значение true.

Значение:  true  если этот слой отображается; иначе,  false .

**Returns:**
boolean
### isTemplate() {#isTemplate--}
```
public final boolean isTemplate()
```


Получает или задает значение, указывающее, является ли этот слой шаблонным.

Значение:  true  если этот слой является шаблоном; иначе,  false .

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




### setBlue(int value) {#setBlue-int-}
```
public final void setBlue(int value)
```


Получает или задает синий компонент цвета.

Значение: Компонент синего цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setColorIndex(int value) {#setColorIndex-int-}
```
public final void setColorIndex(int value)
```


Получает или задает индекс цвета. Этот аргумент может принимать значения от \\u20131 до 26. Каждый целочисленный параметр представляет цвет, который может быть назначен слою для целей идентификации пользователя.

Значение: Индекс цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setColorNumber(int value) {#setColorNumber-int-}
```
public final void setColorNumber(int value)
```


Получает или задает номер цвета. -1 — пользовательское значение цвета из свойств Красный, Зеленый, Синий. Указывает настройку цвета слоя\\u2019.

Значение: Номер цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setDimValue(int value) {#setDimValue-int-}
```
public final void setDimValue(int value)
```


Получает или задает значение затемнения в процентах. Уменьшает интенсивность связанных изображений и растровых изображений, содержащихся в слое, до указанного процента.

Значение: Значение затемнения в процентах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setGreen(int value) {#setGreen-int-}
```
public final void setGreen(int value)
```


Получает или задает зеленый компонент цвета.

Значение: Компонент зелёного цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setImagesDimmed(boolean value) {#setImagesDimmed-boolean-}
```
public final void setImagesDimmed(boolean value)
```


Получает или задает значение, указывающее, затемнён ли этот слой. Уменьшает интенсивность связанных изображений и растровых изображений, содержащихся в слое.

Значение:  true  если слой затемнён; иначе  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setLocked(boolean value) {#setLocked-boolean-}
```
public final void setLocked(boolean value)
```


Получает или задает значение, указывающее, заблокирован ли этот слой. Предотвращает изменения элемента.

Значение:  true  если этот слой заблокирован; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setMultiLayerMasks(boolean value) {#setMultiLayerMasks-boolean-}
```
public final void setMultiLayerMasks(boolean value)
```


Получает или задает значение, указывающее, имеет ли данный экземпляр многослойные маски.

Значение:  true  если у данного экземпляра есть многослойные маски; иначе  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Получает или задает имя слоя. Указывает имя элемента, как оно отображается в панели Слои.

Значение: Имя слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setPreview(boolean value) {#setPreview-boolean-}
```
public final void setPreview(boolean value)
```


Получает или задает значение, указывающее, является ли этот слой предварительным просмотром. Отображает рисунок, содержащийся в слое, в цвете вместо контуров.

Значение:  true  если этот слой является предварительным просмотром; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setPrinted(boolean value) {#setPrinted-boolean-}
```
public final void setPrinted(boolean value)
```


Получает или задает значение, указывающее, печатается ли этот слой. Делает рисунок, содержащийся в слое, печатаемым, если значение true.

Значение:  true  если этот слой печатается; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setRed(int value) {#setRed-int-}
```
public final void setRed(int value)
```


Получает или задает компонент красного цвета.

Значение: Компонент красного цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setShown(boolean value) {#setShown-boolean-}
```
public final void setShown(boolean value)
```


Получает или задает значение, указывающее, отображается ли этот слой. Отображает весь рисунок, содержащийся в слое, на рабочей области, если значение true.

Значение:  true  если этот слой отображается; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setTemplate(boolean value) {#setTemplate-boolean-}
```
public final void setTemplate(boolean value)
```


Получает или задает значение, указывающее, является ли этот слой шаблонным.

Значение:  true  если этот слой является шаблоном; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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

