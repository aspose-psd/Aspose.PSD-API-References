---
title: "TypeToolInfoResource"
second_title: "Aspose.PSD for Java API Справочник"
description: "Информация о типе инструмента."
type: docs
weight: 79
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.LayerResource](../../com.aspose.psd.fileformats.psd.layers/layerresource)
```
public class TypeToolInfoResource extends LayerResource
```

Информация о инструменте типа. Для версии PSD ниже 6.0.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TypeToolInfoResource()](#TypeToolInfoResource--) | Инициализирует новый экземпляр класса [TypeToolInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource). |
## Поля

| Поле | Описание |
| --- | --- |
| [PsbHeaderVersion_internalized](#PsbHeaderVersion-internalized) | Версия заголовка PSB |
| [PsbResourceSignature](#PsbResourceSignature) | Подпись ресурса, специфичная для PSB. |
| [PsdHeaderVersion_internalized](#PsdHeaderVersion-internalized) | Версия заголовка PSD |
| [ResourceSignature](#ResourceSignature) | Общая подпись ресурса. |
| [TypeToolKey](#TypeToolKey) | Ключ информации о типе инструмента. |
| [ventureLicense_internalized](#ventureLicense-internalized) | Лицензия предприятия. |
## Методы

| Метод | Описание |
| --- | --- |
| [checkAndSetIfResourceIsPsbSpecific_internalized(int key)](#checkAndSetIfResourceIsPsbSpecific-internalized-int-) | Проверяет и устанавливает, является ли ресурс специфичным для PSB. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAComponent()](#getAComponent--) | Получает или задает компонент. |
| [getBComponent()](#getBComponent--) | Получает или задает компонент b. |
| [getCharacterCount()](#getCharacterCount--) | Получает или задает количество символов. |
| [getClass()](#getClass--) |  |
| [getColorSpaceValue()](#getColorSpaceValue--) | Получает или задает значение цветового пространства. |
| [getFontVersion()](#getFontVersion--) | Получает или задает версию шрифта. |
| [getFonts()](#getFonts--) | Получает или задает шрифты. |
| [getFontsCount()](#getFontsCount--) | Получает количество шрифтов. |
| [getGComponent()](#getGComponent--) | Получает или задает компонент g. |
| [getHeader_internalized()](#getHeader-internalized--) | Получает или задает заголовок. |
| [getHorizontalPlacement()](#getHorizontalPlacement--) | Получает или задает горизонтальное размещение. |
| [getKey()](#getKey--) | Получает ключ ресурса слоя. |
| [getLength()](#getLength--) | Получает длину ресурса слоя в байтах. |
| [getLineCount()](#getLineCount--) | Получает количество строк. |
| [getLines()](#getLines--) | Получает или задает строки. |
| [getPrefixLength_internalized(int psdVersion)](#getPrefixLength-internalized-int-) | Получает длину префикса. |
| [getPsdVersion()](#getPsdVersion--) | Получает минимальную версию PSD, требуемую для ресурса слоя. |
| [getRComponent()](#getRComponent--) | Получает или задает компонент r. |
| [getScaleFactor()](#getScaleFactor--) | Получает или задает коэффициент масштабирования. |
| [getSelectionEnd()](#getSelectionEnd--) | Получает или задает конец выделения. |
| [getSelectionStart()](#getSelectionStart--) | Получает или задает начало выделения. |
| [getSignature()](#getSignature--) | Получает подпись ресурса слоя. |
| [getStyles()](#getStyles--) | Получает или задает стили шрифта. |
| [getStylesCount()](#getStylesCount--) | Получает количество стилей. |
| [getTransformMatrix()](#getTransformMatrix--) | Получает или задает матрицу преобразования. |
| [getTypeValue()](#getTypeValue--) | Получает или задает значение типа. |
| [getVersion()](#getVersion--) | Получает или задает версию. |
| [getVerticalPlacement()](#getVerticalPlacement--) | Получает или задает вертикальное размещение. |
| [hashCode()](#hashCode--) |  |
| [isResourcePsbSpecificByKey_internalized(int key)](#isResourcePsbSpecificByKey-internalized-int-) | Определяет, является ли ресурс специфичным для PSB. |
| [isResourcePsbSpecific_internalized()](#isResourcePsbSpecific-internalized--) | Получает значение, указывающее, является ли данный экземпляр ресурсом, специфичным для PSB. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(StreamContainer streamContainer, int psdVersion)](#save-com.aspose.psd.StreamContainer-int-) | Сохраняет указанный контейнер потока. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-) | Сохраняет пользовательский заголовок ресурса. |
| [saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)](#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-) | Сохраняет подпись заголовка, идентификатор и длину. |
| [setAComponent(short value)](#setAComponent-short-) | Получает или задает компонент. |
| [setBComponent(short value)](#setBComponent-short-) | Получает или задает компонент b. |
| [setCharacterCount(int value)](#setCharacterCount-int-) | Получает или задает количество символов. |
| [setColorDataRaw_internalized(byte[] value)](#setColorDataRaw-internalized-byte---) | Получает или задает необработанные данные цвета. |
| [setColorSpaceValue(short value)](#setColorSpaceValue-short-) | Получает или задает значение цветового пространства. |
| [setFontVersion(short value)](#setFontVersion-short-) | Получает или задает версию шрифта. |
| [setFonts(TypeToolFontInfo[] value)](#setFonts-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo---) | Получает или задает шрифты. |
| [setGComponent(short value)](#setGComponent-short-) | Получает или задает компонент g. |
| [setHeader_internalized(PsdHeader value)](#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-) | Получает или задает заголовок. |
| [setHorizontalPlacement(int value)](#setHorizontalPlacement-int-) | Получает или задает горизонтальное размещение. |
| [setLines(TypeToolLineInfo[] value)](#setLines-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo---) | Получает или задает строки. |
| [setRComponent(short value)](#setRComponent-short-) | Получает или задает компонент r. |
| [setScaleFactor(int value)](#setScaleFactor-int-) | Получает или задает коэффициент масштабирования. |
| [setSelectionEnd(int value)](#setSelectionEnd-int-) | Получает или задает конец выделения. |
| [setSelectionStart(int value)](#setSelectionStart-int-) | Получает или задает начало выделения. |
| [setStyles(TypeToolStyleInfo[] value)](#setStyles-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo---) | Получает или задает стили шрифта. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Получает или задает матрицу преобразования. |
| [setTypeValue(short value)](#setTypeValue-short-) | Получает или задает значение типа. |
| [setVersion(short value)](#setVersion-short-) | Получает или задает версию. |
| [setVerticalPlacement(int value)](#setVerticalPlacement-int-) | Получает или задает вертикальное размещение. |
| [toString()](#toString--) | Возвращает объект String, представляющий этот экземпляр. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TypeToolInfoResource() {#TypeToolInfoResource--}
```
public TypeToolInfoResource()
```


Инициализирует новый экземпляр класса [TypeToolInfoResource](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource).

### PsbHeaderVersion_internalized {#PsbHeaderVersion-internalized}
```
public static final int PsbHeaderVersion_internalized
```


Версия заголовка PSB

### PsbResourceSignature {#PsbResourceSignature}
```
public static final int PsbResourceSignature
```


Подпись ресурса, специфичная для PSB.

### PsdHeaderVersion_internalized {#PsdHeaderVersion-internalized}
```
public static final int PsdHeaderVersion_internalized
```


Версия заголовка PSD

### ResourceSignature {#ResourceSignature}
```
public static final int ResourceSignature
```


Общая подпись ресурса.

### TypeToolKey {#TypeToolKey}
```
public static final int TypeToolKey
```


Ключ информации о типе инструмента.

### ventureLicense_internalized {#ventureLicense-internalized}
```
public Object ventureLicense_internalized
```


Лицензия предприятия.

### checkAndSetIfResourceIsPsbSpecific_internalized(int key) {#checkAndSetIfResourceIsPsbSpecific-internalized-int-}
```
public final void checkAndSetIfResourceIsPsbSpecific_internalized(int key)
```


Проверяет и устанавливает, является ли ресурс специфичным для PSB. Некоторые ресурсы пока не распознаются, но у нас есть полный список ресурсов, специфичных для PSB, которые изменяют своё поведение при сохранении. Поэтому нам необходимо проверять это хотя бы в UnknownResource.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | int | Ключ. |

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
### getAComponent() {#getAComponent--}
```
public final short getAComponent()
```


Получает или задает компонент.

Значение: компонент a.

**Returns:**
short
### getBComponent() {#getBComponent--}
```
public final short getBComponent()
```


Получает или задает компонент b.

Значение: компонент b.

**Returns:**
short
### getCharacterCount() {#getCharacterCount--}
```
public final int getCharacterCount()
```


Получает или задает количество символов.

Значение: количество символов.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorSpaceValue() {#getColorSpaceValue--}
```
public final short getColorSpaceValue()
```


Получает или задает значение цветового пространства.

Значение: значение цветового пространства.

**Returns:**
short
### getFontVersion() {#getFontVersion--}
```
public final short getFontVersion()
```


Получает или задает версию шрифта.

Значение: версия шрифта.

**Returns:**
short
### getFonts() {#getFonts--}
```
public final TypeToolFontInfo[] getFonts()
```


Получает или задает шрифты.

Значение: шрифты.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo[]
### getFontsCount() {#getFontsCount--}
```
public final short getFontsCount()
```


Получает количество шрифтов.

**Returns:**
short
### getGComponent() {#getGComponent--}
```
public final short getGComponent()
```


Получает или задает компонент g.

Значение: компонент g.

**Returns:**
short
### getHeader_internalized() {#getHeader-internalized--}
```
public final PsdHeader getHeader_internalized()
```


Получает или задает заголовок.

Значение: Заголовок.

**Returns:**
com.aspose.internal.fileformats.psd.sections.PsdHeader
### getHorizontalPlacement() {#getHorizontalPlacement--}
```
public final int getHorizontalPlacement()
```


Получает или задает горизонтальное размещение.

Значение: горизонтальное размещение.

**Returns:**
int
### getKey() {#getKey--}
```
public final int getKey()
```


Получает ключ ресурса слоя.

**Returns:**
int
### getLength() {#getLength--}
```
public int getLength()
```


Получает длину ресурса слоя в байтах.

**Returns:**
int
### getLineCount() {#getLineCount--}
```
public final short getLineCount()
```


Получает количество строк.

Значение: количество строк.

**Returns:**
short
### getLines() {#getLines--}
```
public final TypeToolLineInfo[] getLines()
```


Получает или задает строки.

Значение: строки.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo[]
### getPrefixLength_internalized(int psdVersion) {#getPrefixLength-internalized-int-}
```
public final int getPrefixLength_internalized(int psdVersion)
```


Получает длину префикса. Значение по умолчанию — 12 для ресурсов 8BIM и 16 для 8B64.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| psdVersion | int | Версия PSD. |

**Returns:**
int — длина префикса.
### getPsdVersion() {#getPsdVersion--}
```
public int getPsdVersion()
```


Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений.

**Returns:**
int
### getRComponent() {#getRComponent--}
```
public final short getRComponent()
```


Получает или задает компонент r.

Значение: компонент r.

**Returns:**
short
### getScaleFactor() {#getScaleFactor--}
```
public final int getScaleFactor()
```


Получает или задает коэффициент масштабирования.

Значение: коэффициент масштабирования.

**Returns:**
int
### getSelectionEnd() {#getSelectionEnd--}
```
public final int getSelectionEnd()
```


Получает или задает конец выделения.

Значение: конец выделения.

**Returns:**
int
### getSelectionStart() {#getSelectionStart--}
```
public final int getSelectionStart()
```


Получает или задает начало выделения.

Значение: начало выделения.

**Returns:**
int
### getSignature() {#getSignature--}
```
public int getSignature()
```


Получает подпись ресурса слоя.

**Returns:**
int
### getStyles() {#getStyles--}
```
public final TypeToolStyleInfo[] getStyles()
```


Получает или задает стили шрифта.

Значение: стили шрифта.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo[]
### getStylesCount() {#getStylesCount--}
```
public final short getStylesCount()
```


Получает количество стилей.

**Returns:**
short
### getTransformMatrix() {#getTransformMatrix--}
```
public final double[] getTransformMatrix()
```


Получает или задает матрицу преобразования.

Значение: Трансформационная матрица.

**Returns:**
double[]
### getTypeValue() {#getTypeValue--}
```
public final short getTypeValue()
```


Получает или задает значение типа.

Значение: Значение типа.

**Returns:**
short
### getVersion() {#getVersion--}
```
public final short getVersion()
```


Получает или задает версию.

Значение: Версия.

**Returns:**
short
### getVerticalPlacement() {#getVerticalPlacement--}
```
public final int getVerticalPlacement()
```


Получает или задает вертикальное размещение.

Значение: Вертикальное размещение.

**Returns:**
int
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isResourcePsbSpecificByKey_internalized(int key) {#isResourcePsbSpecificByKey-internalized-int-}
```
public static boolean isResourcePsbSpecificByKey_internalized(int key)
```


Определяет, является ли ресурс специфичным для PSB.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | int | Ключ ресурса. |

**Returns:**
boolean —  true  если ресурс специфичен для PSB; иначе,  false .
### isResourcePsbSpecific_internalized() {#isResourcePsbSpecific-internalized--}
```
public final boolean isResourcePsbSpecific_internalized()
```


Получает значение, указывающее, является ли данный экземпляр ресурсом, специфичным для PSB.

Значение:  true  если этот экземпляр является ресурсом, специфичным для PSB; иначе,  false .

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




### save(StreamContainer streamContainer, int psdVersion) {#save-com.aspose.psd.StreamContainer-int-}
```
public void save(StreamContainer streamContainer, int psdVersion)
```


Сохраняет указанный контейнер потока.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока. |
| psdVersion | int | Версия PSD. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature)
```


Сохраняет пользовательский заголовок ресурса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока. |
| подпись | int | Подпись. |

### saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong) {#saveCustomResourceHeader-internalized-com.aspose.psd.StreamContainer-int-boolean-}
```
public final void saveCustomResourceHeader_internalized(StreamContainer streamContainer, int signature, boolean isLengthLong)
```


Сохраняет подпись заголовка, идентификатор и длину.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.psd/streamcontainer) | Контейнер потока. |
| подпись | int | Подпись. |
| isLengthLong | boolean | если установлено значение  true , длина считается длинной. |

### setAComponent(short value) {#setAComponent-short-}
```
public final void setAComponent(short value)
```


Получает или задает компонент.

Значение: компонент a.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setBComponent(short value) {#setBComponent-short-}
```
public final void setBComponent(short value)
```


Получает или задает компонент b.

Значение: компонент b.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setCharacterCount(int value) {#setCharacterCount-int-}
```
public final void setCharacterCount(int value)
```


Получает или задает количество символов.

Значение: количество символов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setColorDataRaw_internalized(byte[] value) {#setColorDataRaw-internalized-byte---}
```
public final void setColorDataRaw_internalized(byte[] value)
```


Получает или задает необработанные данные цвета.

Значение: Исходные данные цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | byte[] |  |

### setColorSpaceValue(short value) {#setColorSpaceValue-short-}
```
public final void setColorSpaceValue(short value)
```


Получает или задает значение цветового пространства.

Значение: значение цветового пространства.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setFontVersion(short value) {#setFontVersion-short-}
```
public final void setFontVersion(short value)
```


Получает или задает версию шрифта.

Значение: версия шрифта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setFonts(TypeToolFontInfo[] value) {#setFonts-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolFontInfo---}
```
public final void setFonts(TypeToolFontInfo[] value)
```


Получает или задает шрифты.

Значение: шрифты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TypeToolFontInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) |  |

### setGComponent(short value) {#setGComponent-short-}
```
public final void setGComponent(short value)
```


Получает или задает компонент g.

Значение: компонент g.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setHeader_internalized(PsdHeader value) {#setHeader-internalized-com.aspose.internal.fileformats.psd.sections.PsdHeader-}
```
public final void setHeader_internalized(PsdHeader value)
```


Получает или задает заголовок.

Значение: Заголовок.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.internal.fileformats.psd.sections.PsdHeader |  |

### setHorizontalPlacement(int value) {#setHorizontalPlacement-int-}
```
public final void setHorizontalPlacement(int value)
```


Получает или задает горизонтальное размещение.

Значение: горизонтальное размещение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setLines(TypeToolLineInfo[] value) {#setLines-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolLineInfo---}
```
public final void setLines(TypeToolLineInfo[] value)
```


Получает или задает строки.

Значение: строки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TypeToolLineInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) |  |

### setRComponent(short value) {#setRComponent-short-}
```
public final void setRComponent(short value)
```


Получает или задает компонент r.

Значение: компонент r.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setScaleFactor(int value) {#setScaleFactor-int-}
```
public final void setScaleFactor(int value)
```


Получает или задает коэффициент масштабирования.

Значение: коэффициент масштабирования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setSelectionEnd(int value) {#setSelectionEnd-int-}
```
public final void setSelectionEnd(int value)
```


Получает или задает конец выделения.

Значение: конец выделения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setSelectionStart(int value) {#setSelectionStart-int-}
```
public final void setSelectionStart(int value)
```


Получает или задает начало выделения.

Значение: начало выделения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setStyles(TypeToolStyleInfo[] value) {#setStyles-com.aspose.psd.fileformats.psd.layers.layerresources.TypeToolStyleInfo---}
```
public final void setStyles(TypeToolStyleInfo[] value)
```


Получает или задает стили шрифта.

Значение: стили шрифта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TypeToolStyleInfo\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public final void setTransformMatrix(double[] value)
```


Получает или задает матрицу преобразования.

Значение: Трансформационная матрица.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double[] |  |

### setTypeValue(short value) {#setTypeValue-short-}
```
public final void setTypeValue(short value)
```


Получает или задает значение типа.

Значение: Значение типа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setVersion(short value) {#setVersion-short-}
```
public final void setVersion(short value)
```


Получает или задает версию.

Значение: Версия.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | short |  |

### setVerticalPlacement(int value) {#setVerticalPlacement-int-}
```
public final void setVerticalPlacement(int value)
```


Получает или задает вертикальное размещение.

Значение: Вертикальное размещение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### toString() {#toString--}
```
public String toString()
```


Возвращает объект String, представляющий этот экземпляр.

**Returns:**
java.lang.String — объект String, представляющий этот экземпляр.
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

