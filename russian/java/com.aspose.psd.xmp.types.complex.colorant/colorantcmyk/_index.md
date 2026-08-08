---
title: "ColorantCmyk"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет CMYK Colorant."
type: docs
weight: 13
url: /ru/java/com.aspose.psd.xmp.types.complex.colorant/colorantcmyk/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase), [com.aspose.psd.xmp.types.complex.colorant.ColorantBase](../../com.aspose.psd.xmp.types.complex.colorant/colorantbase)
```
public final class ColorantCmyk extends ColorantBase
```

Представляет CMYK Colorant.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ColorantCmyk()](#ColorantCmyk--) | Инициализирует новый экземпляр класса ColorantCmyk. |
| [ColorantCmyk(float black, float cyan, float magenta, float yellow)](#ColorantCmyk-float-float-float-float-) | Инициализирует новый экземпляр класса ColorantCmyk. |
## Поля

| Поле | Описание |
| --- | --- |
| [ColorValueMax](#ColorValueMax) | Максимальное значение цвета в CMYK colorant. |
| [ColorValueMin](#ColorValueMin) | Минимальное значение цвета в CMYK colorant. |
## Методы

| Метод | Описание |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Добавляет указанный ключ. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlack()](#getBlack--) | Получает или задает значение черного компонента. |
| [getClass()](#getClass--) |  |
| [getColorType()](#getColorType--) | Получает или задаёт тип цвета. |
| [getCyan()](#getCyan--) | Получает или задает значение цианового компонента. |
| [getMagenta()](#getMagenta--) | Получает или задает значение пурпурного компонента. |
| [getMode()](#getMode--) | Получает ColorMode. |
| [getNamespaceUri()](#getNamespaceUri--) | Получает URI пространства имён по умолчанию. |
| [getPrefix()](#getPrefix--) | Получает префикс. |
| [getSwatchName()](#getSwatchName--) | Получает или задает имя образца. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Получает строковое значение в формате XMP. |
| [getYellow()](#getYellow--) | Получает или задает значение желтого компонента. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBlack(float value)](#setBlack-float-) | Получает или задает значение черного компонента. |
| [setColorType(int value)](#setColorType-int-) | Получает или задаёт тип цвета. |
| [setCyan(float value)](#setCyan-float-) | Получает или задает значение цианового компонента. |
| [setMagenta(float value)](#setMagenta-float-) | Получает или задает значение пурпурного компонента. |
| [setSwatchName(String value)](#setSwatchName-java.lang.String-) | Получает или задает имя образца. |
| [setYellow(float value)](#setYellow-float-) | Получает или задает значение желтого компонента. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorantCmyk() {#ColorantCmyk--}
```
public ColorantCmyk()
```


Инициализирует новый экземпляр класса ColorantCmyk.

### ColorantCmyk(float black, float cyan, float magenta, float yellow) {#ColorantCmyk-float-float-float-float-}
```
public ColorantCmyk(float black, float cyan, float magenta, float yellow)
```


Инициализирует новый экземпляр класса ColorantCmyk.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| черный | float | Значение черного компонента. |
| циан | float | Значение компонента цвета циан. |
| пурпурный | float | Значение пурпурного компонента. |
| желтый | float | Значение желтого компонента. |

### ColorValueMax {#ColorValueMax}
```
public static final float ColorValueMax
```


Максимальное значение цвета в CMYK colorant.

### ColorValueMin {#ColorValueMin}
```
public static final float ColorValueMin
```


Минимальное значение цвета в CMYK colorant.

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Добавляет указанный ключ.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Строковое представление ключа, идентифицированного с добавленным значением. |
| значение | java.lang.Object | Значение для добавления. |

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
### getBlack() {#getBlack--}
```
public float getBlack()
```


Получает или задает значение черного компонента.

Значение: значение черного компонента.

**Returns:**
float
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorType() {#getColorType--}
```
public int getColorType()
```


Получает или задаёт тип цвета.

Значение: Тип цвета.

**Returns:**
int
### getCyan() {#getCyan--}
```
public float getCyan()
```


Получает или задает значение цианового компонента.

Значение: значение цианового компонента.

**Returns:**
float
### getMagenta() {#getMagenta--}
```
public float getMagenta()
```


Получает или задает значение пурпурного компонента.

Значение: значение пурпурного компонента.

**Returns:**
float
### getMode() {#getMode--}
```
public int getMode()
```


Получает ColorMode.

Значение: Режим цвета.

**Returns:**
int
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Получает URI пространства имён по умолчанию.

**Returns:**
java.lang.String - Значение URI пространства имён по умолчанию.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Получает префикс.

**Returns:**
java.lang.String - Префикс.
### getSwatchName() {#getSwatchName--}
```
public String getSwatchName()
```


Получает или задает имя образца.

Значение: Имя образца.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Получает строковое значение в формате XMP.

**Returns:**
java.lang.String - Возвращает строковое значение в формате XMP.
### getYellow() {#getYellow--}
```
public float getYellow()
```


Получает или задает значение желтого компонента.

Значение: значение желтого компонента.

**Returns:**
float
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




### setBlack(float value) {#setBlack-float-}
```
public void setBlack(float value)
```


Получает или задает значение черного компонента.

Значение: значение черного компонента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


Получает или задаёт тип цвета.

Значение: Тип цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setCyan(float value) {#setCyan-float-}
```
public void setCyan(float value)
```


Получает или задает значение цианового компонента.

Значение: значение цианового компонента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setMagenta(float value) {#setMagenta-float-}
```
public void setMagenta(float value)
```


Получает или задает значение пурпурного компонента.

Значение: значение пурпурного компонента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### setSwatchName(String value) {#setSwatchName-java.lang.String-}
```
public void setSwatchName(String value)
```


Получает или задает имя образца.

Значение: Имя образца.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setYellow(float value) {#setYellow-float-}
```
public void setYellow(float value)
```


Получает или задает значение желтого компонента.

Значение: значение желтого компонента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

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

