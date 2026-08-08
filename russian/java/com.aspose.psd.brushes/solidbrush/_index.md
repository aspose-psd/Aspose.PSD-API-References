---
title: "SolidBrush"
second_title: "Aspose.PSD for Java API Справочник"
description: "Сплошная кисть предназначена для непрерывного рисования определённым цветом."
type: docs
weight: 17
url: /ru/java/com.aspose.psd.brushes/solidbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush)
```
public final class SolidBrush extends Brush
```

Solid brush предназначен для непрерывного рисования с определённым цветом. Этот класс не может быть наследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SolidBrush()](#SolidBrush--) | Инициализирует новый экземпляр класса  SolidBrush  класса. |
| [SolidBrush(Color color)](#SolidBrush-com.aspose.psd.Color-) | Инициализирует новый экземпляр класса  SolidBrush  класса. |
## Методы

| Метод | Описание |
| --- | --- |
| [close()](#close--) | Реализует интерфейс Closable и может использоваться в конструкции try-with-resources, начиная с JDK 1.7. |
| [deepClone()](#deepClone--) | Создаёт глубокую копию текущего Brush. |
| [dispose()](#dispose--) | Освобождает текущий экземпляр. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Получает или задаёт цвет кисти. |
| [getDisposed()](#getDisposed--) | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [getOpacity()](#getOpacity--) | Получает непрозрачность кисти. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Получает или задаёт цвет кисти. |
| [setOpacity(float value)](#setOpacity-float-) | Устанавливает непрозрачность кисти. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SolidBrush() {#SolidBrush--}
```
public SolidBrush()
```


Инициализирует новый экземпляр класса  SolidBrush  класса.

### SolidBrush(Color color) {#SolidBrush-com.aspose.psd.Color-}
```
public SolidBrush(Color color)
```


Инициализирует новый экземпляр класса  SolidBrush  класса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| color | [Color](../../com.aspose.psd/color) | Цвет solid brush. |

### close() {#close--}
```
public void close()
```


Реализует интерфейс Closable и может использоваться в операторе try-with-resources, начиная с JDK 1.7. Этот метод просто вызывает метод dispose.

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Создаёт глубокую копию текущего Brush.

**Returns:**
[Brush](../../com.aspose.psd/brush) - A new  Brush  which is the deep clone of this  Brush  instance.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Color getColor()
```


Получает или задаёт цвет кисти.

Значение: Цвет кисти.

**Returns:**
[Color](../../com.aspose.psd/color)
### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Получает значение, указывающее, освобожден ли этот экземпляр.

**Returns:**
boolean -  true  если освобождено; иначе,  false .
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Получает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 — кисть полностью непрозрачна.

**Returns:**
float — значение непрозрачности кисти.
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




### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public void setColor(Color value)
```


Получает или задаёт цвет кисти.

Значение: Цвет кисти.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Устанавливает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 — кисть полностью непрозрачна.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Значение непрозрачности кисти. |

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

