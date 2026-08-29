---
title: "IOrderedShape"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет упорядоченную форму."
type: docs
weight: 129
url: /ru/java/com.aspose.psd/iorderedshape/
---
```
public interface IOrderedShape
```

Представляет упорядоченную форму. Упорядоченная форма — это непрерывный набор точек с начальной и конечной точкой. Непрерывный набор точек соединяется с использованием определённого правила.
## Методы

| Метод | Описание |
| --- | --- |
| [getEndPoint()](#getEndPoint--) | Возвращает конечную точку формы. |
| [getStartPoint()](#getStartPoint--) | Возвращает начальную точку формы. |
| [isClosed()](#isClosed--) | Возвращает значение, указывающее, замкнута ли упорядоченная форма. |
| [reverse()](#reverse--) | Меняет порядок точек для этой формы. |
| [setClosed(boolean value)](#setClosed-boolean-) | Устанавливает значение, указывающее, замкнута ли упорядоченная форма. |
### getEndPoint() {#getEndPoint--}
```
public abstract PointF getEndPoint()
```


Возвращает конечную точку формы.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The ending shape point.
### getStartPoint() {#getStartPoint--}
```
public abstract PointF getStartPoint()
```


Возвращает начальную точку формы.

**Returns:**
[PointF](../../com.aspose.psd/pointf) - The starting shape point.
### isClosed() {#isClosed--}
```
public abstract boolean isClosed()
```


Возвращает значение, указывающее, замкнута ли упорядоченная форма. При обработке замкнутой упорядоченной формы начальная и конечная точки не имеют значения.

**Returns:**
boolean -  true  если эта упорядоченная форма замкнута; иначе,  false .
### reverse() {#reverse--}
```
public abstract void reverse()
```


Меняет порядок точек для этой формы.

### setClosed(boolean value) {#setClosed-boolean-}
```
public abstract void setClosed(boolean value)
```


Устанавливает значение, указывающее, замкнута ли упорядоченная фигура. При обработке замкнутой упорядоченной фигуры начальная и конечная точки не имеют значения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | true, если эта упорядоченная фигура замкнута; иначе false. |

