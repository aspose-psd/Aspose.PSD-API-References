---
title: "CustomLineCap"
second_title: "Aspose.PSD for Java API Справочник"
description: "Инкапсулирует пользовательский определяемый тип окончания линии."
type: docs
weight: 34
url: /ru/java/com.aspose.psd/customlinecap/
---

**Inheritance:**
java.lang.Object
```
public class CustomLineCap
```

Инкапсулирует пользовательский определяемый тип окончания линии.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-) | Инициализирует новый экземпляр класса  CustomLineCap  с указанным контуром и заливкой. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-) | Инициализирует новый экземпляр класса  CustomLineCap  из указанного существующего перечисления  LineCap  с указанным контуром и заливкой. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-) | Инициализирует новый экземпляр класса  CustomLineCap  из указанного существующего перечисления  LineCap  с указанным контуром, заливкой и отступом. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBaseCap()](#getBaseCap--) | Возвращает перечисление  LineCap  , на котором основан этот  CustomLineCap . |
| [getBaseInset()](#getBaseInset--) | Возвращает расстояние между заголовком и линией. |
| [getClass()](#getClass--) |  |
| [getFillPath()](#getFillPath--) | Возвращает объект, определяющий заливку для пользовательского заголовка. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Возвращает заголовки, используемые для начала и окончания линий, составляющих этот пользовательский заголовок. |
| [getStrokeJoin()](#getStrokeJoin--) | Возвращает перечисление  LineJoin  , определяющее, как соединяются линии, составляющие объект  CustomLineCap . |
| [getStrokePath()](#getStrokePath--) | Возвращает объект, определяющий контур пользовательского заголовка. |
| [getWidthScale()](#getWidthScale--) | Возвращает величину, на которую следует масштабировать объект класса  CustomLineCap  относительно ширины объекта  System.Drawing.Pen . |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBaseCap(int value)](#setBaseCap-int-) | Устанавливает перечисление  LineCap , на котором основан этот  CustomLineCap . |
| [setBaseInset(float value)](#setBaseInset-float-) | Устанавливает расстояние между заголовком и линией. |
| [setFillPath(GraphicsPath value)](#setFillPath-com.aspose.psd.GraphicsPath-) | Устанавливает объект, определяющий заливку для пользовательского заголовка. |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Устанавливает заголовки, используемые для начала и окончания линий, составляющих этот пользовательский заголовок. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Устанавливает перечисление  LineJoin , определяющее, как соединяются линии, составляющие объект  CustomLineCap . |
| [setStrokePath(GraphicsPath value)](#setStrokePath-com.aspose.psd.GraphicsPath-) | Устанавливает объект, определяющий контур пользовательского заголовка. |
| [setWidthScale(float value)](#setWidthScale-float-) | Устанавливает величину, на которую следует масштабировать объект класса  CustomLineCap  относительно ширины объекта  System.Drawing.Pen . |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Инициализирует новый экземпляр класса  CustomLineCap  с указанным контуром и заливкой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Объект  GraphicsPath , определяющий заливку для пользовательского заголовка. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Объект  GraphicsPath , определяющий контур пользовательского заголовка. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Инициализирует новый экземпляр класса  CustomLineCap  из указанного существующего перечисления  LineCap  с указанным контуром и заливкой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Объект  GraphicsPath , определяющий заливку для пользовательского заголовка. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Объект  GraphicsPath , определяющий контур пользовательского заголовка. |
| baseCap | int | Заголовок линии, из которого создаётся пользовательский заголовок. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.psd.GraphicsPath-com.aspose.psd.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Инициализирует новый экземпляр класса  CustomLineCap  из указанного существующего перечисления  LineCap  с указанным контуром, заливкой и отступом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Объект  GraphicsPath , определяющий заливку для пользовательского заголовка. |
| strokePath | [GraphicsPath](../../com.aspose.psd/graphicspath) | Объект  GraphicsPath , определяющий контур пользовательского заголовка. |
| baseCap | int | Заголовок линии, из которого создаётся пользовательский заголовок. |
| baseInset | float | Расстояние между заголовком и линией. |

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
### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Возвращает перечисление  LineCap  , на котором основан этот  CustomLineCap .

**Returns:**
int - Перечисление LineCap, на котором основан этот CustomLineCap.
### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Возвращает расстояние между заголовком и линией.

**Returns:**
float - Расстояние между началом заголовка и концом линии.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```


Возвращает объект, определяющий заливку для пользовательского заголовка.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the fill for the custom cap.
### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public void getStrokeCaps(int[] startCap, int[] endCap)
```


Возвращает заголовки, используемые для начала и окончания линий, составляющих этот пользовательский заголовок.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startCap | int[] | Перечисление LineCap, используемое в начале линии внутри этого заголовка. |
| endCap | int[] | Перечисление LineCap, используемое в конце линии внутри этого заголовка. |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Возвращает перечисление  LineJoin  , определяющее, как соединяются линии, составляющие объект  CustomLineCap .

**Returns:**
int - Перечисление LineJoin, которое объект CustomLineCap использует для соединения линий.
### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


Возвращает объект, определяющий контур пользовательского заголовка.

**Returns:**
[GraphicsPath](../../com.aspose.psd/graphicspath) - The object that defines the outline of the custom cap.
### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Возвращает величину, на которую следует масштабировать объект класса  CustomLineCap  относительно ширины объекта  System.Drawing.Pen .

**Returns:**
float - Величина, на которую масштабируется заголовок.
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




### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


Устанавливает перечисление  LineCap , на котором основан этот  CustomLineCap .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Перечисление LineCap, на котором основан этот CustomLineCap. |

### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Устанавливает расстояние между заголовком и линией.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Расстояние между началом заголовка и концом линии. |

### setFillPath(GraphicsPath value) {#setFillPath-com.aspose.psd.GraphicsPath-}
```
public void setFillPath(GraphicsPath value)
```


Устанавливает объект, определяющий заливку для пользовательского заголовка.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | Объект, определяющий заливку для пользовательского заголовка. |

### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public void setStrokeCaps(int startCap, int endCap)
```


Устанавливает заголовки, используемые для начала и окончания линий, составляющих этот пользовательский заголовок.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startCap | int | Перечисление LineCap, используемое в начале линии внутри этого заголовка. |
| endCap | int | Перечисление LineCap, используемое в конце линии внутри этого заголовка. |

### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Устанавливает перечисление  LineJoin , определяющее, как соединяются линии, составляющие объект  CustomLineCap .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Перечисление LineJoin, которое объект CustomLineCap использует для соединения линий. |

### setStrokePath(GraphicsPath value) {#setStrokePath-com.aspose.psd.GraphicsPath-}
```
public void setStrokePath(GraphicsPath value)
```


Устанавливает объект, определяющий контур пользовательского заголовка.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.psd/graphicspath) | Объект, определяющий контур пользовательского заголовка. |

### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Устанавливает величину, на которую следует масштабировать объект класса  CustomLineCap  относительно ширины объекта  System.Drawing.Pen .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Величина, на которую масштабируется заголовок. |

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

