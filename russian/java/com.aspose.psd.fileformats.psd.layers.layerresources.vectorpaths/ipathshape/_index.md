---
title: "IPathShape"
second_title: "Aspose.PSD for Java API Справочник"
description: "Форма из узлов кривой Безье."
type: docs
weight: 31
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/ipathshape/
---
```
public interface IPathShape
```

Форма из узлов кривой Безье.
## Методы

| Метод | Описание |
| --- | --- |
| [getItems()](#getItems--) | Получает массив узлов Безье. |
| [getPathOperations()](#getPathOperations--) | Операции объединения форм пути (логические операции). |
| [isClosed()](#isClosed--) | Получает или задает свойство, определяющее, закрыта ли Shape. |
| [setClosed(boolean value)](#setClosed-boolean-) | Получает или задает свойство, определяющее, закрыта ли Shape. |
| [setItems(BezierKnotRecord[] bezierPoints)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---) | Назначает массив узлов Bexier. |
| [setPathOperations(int value)](#setPathOperations-int-) | Операции объединения форм пути (логические операции). |
### getItems() {#getItems--}
```
public abstract BezierKnotRecord[] getItems()
```


Получает массив узлов Безье.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord[] - Массив BezierKnotRecord.
### getPathOperations() {#getPathOperations--}
```
public abstract int getPathOperations()
```


Операции объединения форм пути (логические операции).

**Returns:**
int
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Получает или задает свойство, определяющее, закрыта ли Shape.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Получает или задает свойство, определяющее, закрыта ли Shape.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setItems(BezierKnotRecord[] bezierPoints) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths.BezierKnotRecord---}
```
public abstract void setItems(BezierKnotRecord[] bezierPoints)
```


Назначает массив узлов Bexier.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| bezierPoints | [BezierKnotRecord\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources.vectorpaths/bezierknotrecord) | Массив узлов Безье |

### setPathOperations(int value) {#setPathOperations-int-}
```
public abstract void setPathOperations(int value)
```


Операции объединения форм пути (логические операции).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

