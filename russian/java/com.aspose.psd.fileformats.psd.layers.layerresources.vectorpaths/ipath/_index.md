---
title: "IPath"
second_title: "Aspose.PSD for Java API Справочник"
description: "Интерфейс описывает набор путей, присутствующих в слое формы."
type: docs
weight: 30
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipath/
---
```
public interface IPath
```

Интерфейс описывает набор путей, присутствующих в слое формы.
## Методы

| Метод | Описание |
| --- | --- |
| [getItems()](#getItems--) | Получает массив фигур в пути. |
| [isDisabled()](#isDisabled--) | Путь отключён. |
| [isInverted()](#isInverted--) | Путь инвертирован. |
| [isNotLinked()](#isNotLinked--) | Путь не связан. |
| [setDisabled(boolean value)](#setDisabled-boolean-) | Путь отключён. |
| [setInverted(boolean value)](#setInverted-boolean-) | Путь инвертирован. |
| [setItems(IPathShape[] shapes)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape---) | Задает массив фигур в пути. |
| [setNotLinked(boolean value)](#setNotLinked-boolean-) | Путь не связан. |
### getItems() {#getItems--}
```
public abstract IPathShape[] getItems()
```


Получает массив фигур в пути.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape[] - Массив IPathShape.
### isDisabled() {#isDisabled--}
```
public abstract boolean isDisabled()
```


Путь отключён.

**Returns:**
boolean
### isInverted() {#isInverted--}
```
public abstract boolean isInverted()
```


Путь инвертирован.

**Returns:**
boolean
### isNotLinked() {#isNotLinked--}
```
public abstract boolean isNotLinked()
```


Путь не связан.

**Returns:**
boolean
### setDisabled(boolean value) {#setDisabled-boolean-}
```
public abstract void setDisabled(boolean value)
```


Путь отключён.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setInverted(boolean value) {#setInverted-boolean-}
```
public abstract void setInverted(boolean value)
```


Путь инвертирован.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setItems(IPathShape[] shapes) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.IPathShape---}
```
public abstract void setItems(IPathShape[] shapes)
```


Задает массив фигур в пути.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapes | [IPathShape\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape) | Массив IPathShape. |

### setNotLinked(boolean value) {#setNotLinked-boolean-}
```
public abstract void setNotLinked(boolean value)
```


Путь не связан.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

