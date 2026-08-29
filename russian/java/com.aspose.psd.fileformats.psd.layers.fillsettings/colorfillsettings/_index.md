---
title: "ColorFillSettings"
second_title: "Aspose.PSD for Java API Справочник"
description: "Настройки эффекта заливки цветом"
type: docs
weight: 11
url: /ru/java/com.aspose.psd.fileformats.psd.layers.fillsettings/colorfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IColorFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/icolorfillsettings)
```
public class ColorFillSettings extends BaseFillSettings implements IColorFillSettings
```

Настройки эффекта заливки цветом
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ColorFillSettings()](#ColorFillSettings--) | Инициализирует новый экземпляр класса [ColorFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/colorfillsettings). |
## Поля

| Поле | Описание |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Получает или задаёт цвет. |
| [getFillType()](#getFillType--) | Тип заполнения |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [parseEffectResource_internalized(OSTypeStructure structure)](#parseEffectResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-) | Разбирает ресурс эффекта. |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Вызывает событие изменения значения. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Получает или задаёт цвет. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorFillSettings() {#ColorFillSettings--}
```
public ColorFillSettings()
```


Инициализирует новый экземпляр класса [ColorFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/colorfillsettings).

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
public final Color getColor()
```


Получает или задаёт цвет.

Значение: Цвет.

**Returns:**
[Color](../../com.aspose.psd/color)
### getFillType() {#getFillType--}
```
public int getFillType()
```


Тип заполнения

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




### parseEffectResource_internalized(OSTypeStructure structure) {#parseEffectResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure-}
```
public final void parseEffectResource_internalized(OSTypeStructure structure)
```


Разбирает ресурс эффекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| structure | [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Структура. |

### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


Вызывает событие изменения значения.

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Получает или задаёт цвет.

Значение: Цвет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

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

