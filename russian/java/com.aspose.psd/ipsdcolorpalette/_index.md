---
title: "IPsdColorPalette"
second_title: "Aspose.PSD for Java API Справочник"
description: "Палитра цветов pasd"
type: docs
weight: 134
url: /ru/java/com.aspose.psd/ipsdcolorpalette/
---

**All Implemented Interfaces:**
[com.aspose.psd.IColorPalette](../../com.aspose.psd/icolorpalette)
```
public interface IPsdColorPalette extends IColorPalette
```

Палитра цветов pasd
## Методы

| Метод | Описание |
| --- | --- |
| [getRawEntries()](#getRawEntries--) | Получает необработанные данные записей цветовой палитры. |
| [getRawEntriesCount()](#getRawEntriesCount--) | Получает количество необработанных записей цветовой палитры. |
| [getTransparentColor()](#getTransparentColor--) | Получает прозрачный цвет. |
| [getTransparentIndex()](#getTransparentIndex--) | Получает индекс прозрачного цвета. |
| [hasTransparentColor()](#hasTransparentColor--) | Получает значение, указывающее, существует ли прозрачный цвет. |
### getRawEntries() {#getRawEntries--}
```
public abstract byte[] getRawEntries()
```


Получает необработанные данные записей цветовой палитры.

Значение: необработанные данные записей цветовой палитры.

**Returns:**
byte[]
### getRawEntriesCount() {#getRawEntriesCount--}
```
public abstract int getRawEntriesCount()
```


Получает количество необработанных записей цветовой палитры.

Значение: количество необработанных записей цветовой палитры.

**Returns:**
int
### getTransparentColor() {#getTransparentColor--}
```
public abstract Color getTransparentColor()
```


Получает прозрачный цвет.

Значение: прозрачный цвет.

**Returns:**
[Color](../../com.aspose.psd/color)
### getTransparentIndex() {#getTransparentIndex--}
```
public abstract short getTransparentIndex()
```


Получает индекс прозрачного цвета.

Значение: индекс прозрачного цвета.

**Returns:**
short
### hasTransparentColor() {#hasTransparentColor--}
```
public abstract boolean hasTransparentColor()
```


Получает значение, указывающее, существует ли прозрачный цвет.

Значение:  true  если прозрачный цвет существует; иначе  false .

**Returns:**
boolean
