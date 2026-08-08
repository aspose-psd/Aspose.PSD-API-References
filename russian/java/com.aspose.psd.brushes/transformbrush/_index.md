---
title: "TransformBrush"
second_title: "Aspose.PSD for Java API Справочник"
description: "Кисть с возможностями трансформации."
type: docs
weight: 19
url: /ru/java/com.aspose.psd.brushes/transformbrush/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.DisposableObject](../../com.aspose.psd/disposableobject), [com.aspose.psd.Brush](../../com.aspose.psd/brush)
```
public abstract class TransformBrush extends Brush
```

Кисть с возможностями трансформации.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TransformBrush()](#TransformBrush--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [close()](#close--) | Реализует интерфейс Closable и может использоваться в конструкции try-with-resources, начиная с JDK 1.7. |
| [deepClone()](#deepClone--) | Создаёт глубокую копию текущего Brush. |
| [dispose()](#dispose--) | Освобождает текущий экземпляр. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisposed()](#getDisposed--) | Получает значение, указывающее, освобожден ли этот экземпляр. |
| [getOpacity()](#getOpacity--) | Получает непрозрачность кисти. |
| [getTransform()](#getTransform--) | Получает или задаёт копию Aspose.Imaging.Matrix, определяющую локальное геометрическое преобразование для этого TransformBrush. |
| [getWrapMode()](#getWrapMode--) | Получает или задаёт перечисление Aspose.Imaging.WrapMode, указывающее режим обтекания для этого TransformBrush. |
| [hashCode()](#hashCode--) |  |
| [isTransformChanged()](#isTransformChanged--) | Получает значение, указывающее, были ли преобразования изменены каким-либо образом. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.psd.Matrix-) | Умножает Aspose.Imaging.Matrix, представляющий локальное геометрическое преобразование этого LinearGradientBrush, на указанный Aspose.Imaging.Matrix, предварительно добавляя указанный Aspose.Imaging.Matrix. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.psd.Matrix-int-) | Умножает Aspose.Imaging.Matrix, представляющий локальное геометрическое преобразование этого LinearGradientBrush, на указанный Aspose.Imaging.Matrix в указанном порядке. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [resetTransform()](#resetTransform--) | Сбрасывает свойство TransformBrush.Transform к единичному преобразованию. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Поворачивает локальное геометрическое преобразование на указанную величину. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты в указанном порядке. |
| [setOpacity(float value)](#setOpacity-float-) | Устанавливает непрозрачность кисти. |
| [setTransform(Matrix value)](#setTransform-com.aspose.psd.Matrix-) | Получает или задаёт копию Aspose.Imaging.Matrix, определяющую локальное геометрическое преобразование для этого TransformBrush. |
| [setWrapMode(int value)](#setWrapMode-int-) | Получает или задаёт перечисление Aspose.Imaging.WrapMode, указывающее режим обтекания для этого TransformBrush. |
| [toString()](#toString--) |  |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Перемещает локальное геометрическое преобразование на указанные размеры. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Перемещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TransformBrush() {#TransformBrush--}
```
public TransformBrush()
```


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
### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Получает или задаёт копию Aspose.Imaging.Matrix, определяющую локальное геометрическое преобразование для этого TransformBrush.

**Returns:**
[Matrix](../../com.aspose.psd/matrix) - A copy of the  Aspose.Imaging.Matrix  that defines a geometric transform that applies only to fills drawn with this  TransformBrush .
### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Получает или задаёт перечисление Aspose.Imaging.WrapMode, указывающее режим обтекания для этого TransformBrush.

**Returns:**
int — **Aspose.Imaging.WrapMode**, определяющий способ заполнения, выполненного этим **TransformBrush**, при тайлинге.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isTransformChanged() {#isTransformChanged--}
```
public boolean isTransformChanged()
```


Получает значение, указывающее, были ли каким-либо образом изменены преобразования. Например, установка матрицы преобразования или вызов любого из методов, изменяющих матрицу преобразования. Свойство введено для обратной совместимости с GDI+.

Значение: True, если преобразование было изменено; иначе false.

**Returns:**
boolean
### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.psd.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Умножает Aspose.Imaging.Matrix, представляющий локальное геометрическое преобразование этого LinearGradientBrush, на указанный Aspose.Imaging.Matrix, предварительно добавляя указанный Aspose.Imaging.Matrix.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Матрица **Aspose.Imaging.Matrix**, на которую умножается геометрическое преобразование. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.psd.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Умножает Aspose.Imaging.Matrix, представляющий локальное геометрическое преобразование этого LinearGradientBrush, на указанный Aspose.Imaging.Matrix в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.psd/matrix) | Матрица **Aspose.Imaging.Matrix**, на которую умножается геометрическое преобразование. |
| порядок | int | **Aspose.Imaging.MatrixOrder**, указывающий порядок умножения двух матриц. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Сбрасывает свойство TransformBrush.Transform к единичному преобразованию.

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Вращает локальное геометрическое преобразование на указанную величину. Этот метод добавляет вращение в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Поворачивает локальное геометрическое преобразование на указанную величину в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения. |
| порядок | int | **Aspose.Imaging.MatrixOrder**, указывающий, добавлять ли матрицу вращения в конец или в начало. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Масштабирует локальное геометрическое преобразование на указанные величины. Этот метод добавляет матрицу масштабирования в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Величина, на которую масштабировать преобразование по оси x. |
| sy | float | Величина, на которую масштабировать преобразование по оси y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Масштабирует локальное геометрическое преобразование на указанные коэффициенты в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Величина, на которую масштабировать преобразование по оси x. |
| sy | float | Величина, на которую масштабировать преобразование по оси y. |
| порядок | int | Объект  Aspose.Imaging.MatrixOrder , который указывает, добавлять ли матрицу масштабирования в конец или в начало. |

### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Устанавливает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 — кисть полностью непрозрачна.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Значение непрозрачности кисти. |

### setTransform(Matrix value) {#setTransform-com.aspose.psd.Matrix-}
```
public void setTransform(Matrix value)
```


Получает или задаёт копию Aspose.Imaging.Matrix, определяющую локальное геометрическое преобразование для этого TransformBrush.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.psd/matrix) |  |

### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Получает или задаёт перечисление Aspose.Imaging.WrapMode, указывающее режим обтекания для этого TransformBrush.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Перемещает локальное геометрическое преобразование на указанные размеры. Этот метод добавляет трансляцию в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Перемещает локальное геометрическое преобразование на указанные размеры в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |
| порядок | int | Порядок (prepend или append), в котором применяется трансляция. |

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

