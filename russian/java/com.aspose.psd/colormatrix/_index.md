---
title: "ColorMatrix"
second_title: "Aspose.PSD for Java API Справочник"
description: "Определяет матрицу 5 x 5, содержащую координаты пространства RGBA."
type: docs
weight: 25
url: /ru/java/com.aspose.psd/colormatrix/
---

**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

Определяет матрицу 5 x 5, содержащую координаты для пространства RGBA. Несколько методов класса com.aspose.psd.ImageAttributes регулируют цвета изображения с помощью цветовой матрицы. Этот класс не может быть наследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | Инициализирует новый экземпляр класса Aspose.Imaging.ColorMatrix. |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | Инициализирует новый экземпляр класса Aspose.Imaging.ColorMatrix, используя элементы указанной матрицы newColorMatrix. |
## Поля

| Поле | Описание |
| --- | --- |
| [MatrixDimensionElementsCount](#MatrixDimensionElementsCount) | Количество элементов в измерении матрицы. |
| [MatrixDimensionsCount](#MatrixDimensionsCount) | Количество измерений матрицы. |
| [MatrixTotalElementsCount](#MatrixTotalElementsCount) | Общее количество элементов в матрице. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMatrix()](#getMatrix--) | Получает значения матрицы. |
| [getMatrix00()](#getMatrix00--) | Получает элемент в строке 0 (ноль) и столбце 0 этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix01()](#getMatrix01--) | Получает элемент в строке 0 (ноль) и первом столбце этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix02()](#getMatrix02--) | Получает элемент в строке 0 (ноль) и втором столбце этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix03()](#getMatrix03--) | Получает элемент в строке 0 (ноль) и третьем столбце этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix04()](#getMatrix04--) | Получает элемент в строке 0 (ноль) и четвертом столбце этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix10()](#getMatrix10--) | Получает элемент в первой строке и столбце 0 (ноль) этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix11()](#getMatrix11--) | Получает элемент в первой строке и первом столбце этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix12()](#getMatrix12--) | Получает элемент в первой строке и втором столбце этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix13()](#getMatrix13--) | Получает элемент в первой строке и третьем столбце этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix14()](#getMatrix14--) | Получает элемент в первой строке и четвертом столбце этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix20()](#getMatrix20--) | Получает элемент во второй строке и столбце 0 (ноль) этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix21()](#getMatrix21--) | Получает элемент во второй строке и первом столбце этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix22()](#getMatrix22--) | Получает элемент во второй строке и втором столбце этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix23()](#getMatrix23--) | Получает элемент во второй строке и третьем столбце этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix24()](#getMatrix24--) | Получает элемент во второй строке и четвертом столбце этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix30()](#getMatrix30--) | Получает элемент в третьей строке и столбце 0 (ноль) этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix31()](#getMatrix31--) | Получает элемент в третьей строке и первом столбце этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix32()](#getMatrix32--) | Получает элемент в третьей строке и втором столбце этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix33()](#getMatrix33--) | Получает элемент в третьей строке и третьем столбце этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix34()](#getMatrix34--) | Получает элемент в третьей строке и четвертом столбце этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix40()](#getMatrix40--) | Получает элемент в четвертой строке и столбце 0 (ноль) этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix41()](#getMatrix41--) | Получает элемент в четвертой строке и первом столбце этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix42()](#getMatrix42--) | Получает элемент в четвертой строке и втором столбце этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix43()](#getMatrix43--) | Получает элемент в четвертой строке и третьем столбце этой  Aspose.Imaging.ColorMatrix . |
| [getMatrix44()](#getMatrix44--) | Получает элемент в четвертой строке и четвертом столбце этой  Aspose.Imaging.ColorMatrix . |
| [get_Item(int row, int column)](#get-Item-int-int-) | Получает элемент в указанной строке и столбце в  Aspose.Imaging.ColorMatrix . |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMatrix00(float value)](#setMatrix00-float-) | Устанавливает элемент в строке 0 (ноль) и столбце 0 этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix01(float value)](#setMatrix01-float-) | Устанавливает элемент в строке 0 (ноль) и первом столбце этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix02(float value)](#setMatrix02-float-) | Устанавливает элемент в строке 0 (ноль) и втором столбце этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix03(float value)](#setMatrix03-float-) | Устанавливает элемент в строке 0 (ноль) и третьем столбце этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix04(float value)](#setMatrix04-float-) | Устанавливает элемент в строке 0 (ноль) и четвертом столбце этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix10(float value)](#setMatrix10-float-) | Устанавливает элемент в первой строке и столбце 0 (ноль) этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix11(float value)](#setMatrix11-float-) | Устанавливает элемент в первой строке и первом столбце этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix12(float value)](#setMatrix12-float-) | Устанавливает элемент в первой строке и втором столбце этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix13(float value)](#setMatrix13-float-) | Устанавливает элемент в первой строке и третьем столбце этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix14(float value)](#setMatrix14-float-) | Устанавливает элемент в первой строке и четвертом столбце этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix20(float value)](#setMatrix20-float-) | Устанавливает элемент во второй строке и столбце 0 (ноль) этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix21(float value)](#setMatrix21-float-) | Устанавливает элемент во второй строке и первом столбце этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix22(float value)](#setMatrix22-float-) | Устанавливает элемент во второй строке и втором столбце этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix23(float value)](#setMatrix23-float-) | Устанавливает элемент во второй строке и третьем столбце этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix24(float value)](#setMatrix24-float-) | Устанавливает элемент во второй строке и четвертом столбце этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix30(float value)](#setMatrix30-float-) | Устанавливает элемент в третьей строке и столбце 0 (ноль) этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix31(float value)](#setMatrix31-float-) | Устанавливает элемент в третьей строке и первом столбце этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix32(float value)](#setMatrix32-float-) | Устанавливает элемент в третьей строке и втором столбце этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix33(float value)](#setMatrix33-float-) | Устанавливает элемент в третьей строке и третьем столбце этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix34(float value)](#setMatrix34-float-) | Устанавливает элемент в третьей строке и четвертом столбце этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix40(float value)](#setMatrix40-float-) | Устанавливает элемент в четвертой строке и столбце 0 (ноль) этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix41(float value)](#setMatrix41-float-) | Устанавливает элемент в четвертой строке и первом столбце этой  Aspose.Imaging.ColorMatrix . |
| [setMatrix42(float value)](#setMatrix42-float-) | Устанавливает элемент в четвертой строке и втором столбце этого  Aspose.Imaging.ColorMatrix . |
| [setMatrix43(float value)](#setMatrix43-float-) | Устанавливает элемент в четвертой строке и третьем столбце этого  Aspose.Imaging.ColorMatrix . |
| [setMatrix44(float value)](#setMatrix44-float-) | Устанавливает элемент в четвертой строке и четвертом столбце этого  Aspose.Imaging.ColorMatrix . |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | Устанавливает элемент в указанной строке и столбце в  Aspose.Imaging.ColorMatrix . |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


Инициализирует новый экземпляр класса Aspose.Imaging.ColorMatrix.

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


Инициализирует новый экземпляр класса Aspose.Imaging.ColorMatrix, используя элементы указанной матрицы newColorMatrix.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorMatrix | float[][] | Значения элементов для новой  Aspose.Imaging.ColorMatrix . |

### MatrixDimensionElementsCount {#MatrixDimensionElementsCount}
```
public static final int MatrixDimensionElementsCount
```


Количество элементов в измерении матрицы.

### MatrixDimensionsCount {#MatrixDimensionsCount}
```
public static final int MatrixDimensionsCount
```


Количество измерений матрицы.

### MatrixTotalElementsCount {#MatrixTotalElementsCount}
```
public static final int MatrixTotalElementsCount
```


Общее количество элементов в матрице.

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
### getMatrix() {#getMatrix--}
```
public float[][] getMatrix()
```


Получает значения матрицы.

**Returns:**
float[][] - Массив значений матрицы.
### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


Получает элемент в строке 0 (ноль) и столбце 0 этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент в 0 строке и 0 столбце этого  Aspose.Imaging.ColorMatrix .
### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


Получает элемент в строке 0 (ноль) и первом столбце этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент в 0 строке и первом столбце этого  Aspose.Imaging.ColorMatrix  .
### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


Получает элемент в строке 0 (ноль) и втором столбце этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент в 0 строке и втором столбце этого  Aspose.Imaging.ColorMatrix .
### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


Получает элемент в строке 0 (ноль) и третьем столбце этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент в 0 строке и третьем столбце этого  Aspose.Imaging.ColorMatrix .
### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


Получает элемент в строке 0 (ноль) и четвертом столбце этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент в 0 строке и четвертом столбце этого  Aspose.Imaging.ColorMatrix .
### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


Получает элемент в первой строке и столбце 0 (ноль) этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент в первой строке и 0 столбце этого  Aspose.Imaging.ColorMatrix .
### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


Получает элемент в первой строке и первом столбце этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент в первой строке и первом столбце этого  Aspose.Imaging.ColorMatrix .
### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


Получает элемент в первой строке и втором столбце этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент в первой строке и втором столбце этого  Aspose.Imaging.ColorMatrix .
### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


Получает элемент в первой строке и третьем столбце этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент в первой строке и третьем столбце этого  Aspose.Imaging.ColorMatrix .
### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


Получает элемент в первой строке и четвертом столбце этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент в первой строке и четвертом столбце этого  Aspose.Imaging.ColorMatrix .
### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


Получает элемент во второй строке и столбце 0 (ноль) этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент во второй строке и 0 столбце этого  Aspose.Imaging.ColorMatrix .
### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


Получает элемент во второй строке и первом столбце этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент во второй строке и первом столбце этого  Aspose.Imaging.ColorMatrix .
### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


Получает элемент во второй строке и втором столбце этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент во второй строке и втором столбце этого  Aspose.Imaging.ColorMatrix .
### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


Получает элемент во второй строке и третьем столбце этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент во второй строке и третьем столбце этого  Aspose.Imaging.ColorMatrix .
### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


Получает элемент во второй строке и четвертом столбце этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент во второй строке и четвертом столбце этого  Aspose.Imaging.ColorMatrix .
### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


Получает элемент в третьей строке и столбце 0 (ноль) этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент в третьей строке и 0 столбце этого  Aspose.Imaging.ColorMatrix .
### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


Получает элемент в третьей строке и первом столбце этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент в третьей строке и первом столбце этого  Aspose.Imaging.ColorMatrix .
### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


Получает элемент в третьей строке и втором столбце этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент в третьей строке и втором столбце этой Aspose.Imaging.ColorMatrix .
### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


Получает элемент в третьей строке и третьем столбце этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент в третьей строке и третьем столбце этой Aspose.Imaging.ColorMatrix .
### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


Получает элемент в третьей строке и четвертом столбце этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент в третьей строке и четвертом столбце этой Aspose.Imaging.ColorMatrix .
### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


Получает элемент в четвертой строке и столбце 0 (ноль) этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент в четвертой строке и 0 столбце этой Aspose.Imaging.ColorMatrix .
### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


Получает элемент в четвертой строке и первом столбце этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент в четвертой строке и первом столбце этой Aspose.Imaging.ColorMatrix .
### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


Получает элемент в четвертой строке и втором столбце этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент в четвертой строке и втором столбце этой Aspose.Imaging.ColorMatrix .
### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


Получает элемент в четвертой строке и третьем столбце этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент в четвертой строке и третьем столбце этой Aspose.Imaging.ColorMatrix .
### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


Получает элемент в четвертой строке и четвертом столбце этой  Aspose.Imaging.ColorMatrix .

**Returns:**
float - Элемент в четвертой строке и четвертом столбце этой Aspose.Imaging.ColorMatrix .
### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


Получает элемент в указанной строке и столбце в  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| строка | int | Номер строки. |
| столбец | int | Номер столбца. |

**Returns:**
float - Элемент в указанной строке и столбце.
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




### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


Устанавливает элемент в строке 0 (ноль) и столбце 0 этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в 0 строке и 0 столбце этой Aspose.Imaging.ColorMatrix . |

### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


Устанавливает элемент в строке 0 (ноль) и первом столбце этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в 0 строке и первом столбце этой Aspose.Imaging.ColorMatrix . |

### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


Устанавливает элемент в строке 0 (ноль) и втором столбце этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в 0 строке и втором столбце этой Aspose.Imaging ColorMatrix . |

### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


Устанавливает элемент в строке 0 (ноль) и третьем столбце этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в 0 строке и третьем столбце этой Aspose.Imaging ColorMatrix . |

### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


Устанавливает элемент в строке 0 (ноль) и четвертом столбце этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в 0 строке и четвертом столбце этой Aspose.Imaging ColorMatrix . |

### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


Устанавливает элемент в первой строке и столбце 0 (ноль) этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в первой строке и 0 столбце этой Aspose.Imaging ColorMatrix . |

### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


Устанавливает элемент в первой строке и первом столбце этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в первой строке и первом столбце этой Aspose.Imaging ColorMatrix . |

### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


Устанавливает элемент в первой строке и втором столбце этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в первой строке и втором столбце этой Aspose.Imaging ColorMatrix . |

### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


Устанавливает элемент в первой строке и третьем столбце этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в первой строке и третьем столбце этой Aspose.Imaging ColorMatrix . |

### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


Устанавливает элемент в первой строке и четвертом столбце этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в первой строке и четвертом столбце этой Aspose.Imaging ColorMatrix . |

### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


Устанавливает элемент во второй строке и столбце 0 (ноль) этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в второй строке и 0 столбце этой Aspose.Imaging ColorMatrix . |

### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


Устанавливает элемент во второй строке и первом столбце этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в второй строке и первом столбце этой Aspose.Imaging ColorMatrix . |

### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


Устанавливает элемент во второй строке и втором столбце этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент во второй строке и втором столбце этой  Aspose.Imaging.ColorMatrix . |

### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


Устанавливает элемент во второй строке и третьем столбце этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент во второй строке и третьем столбце этой  Aspose.Imaging.ColorMatrix . |

### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


Устанавливает элемент во второй строке и четвертом столбце этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент во второй строке и четвертом столбце этой  Aspose.Imaging.ColorMatrix . |

### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


Устанавливает элемент в третьей строке и столбце 0 (ноль) этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в третьей строке и 0 столбце этой  Aspose.Imaging.ColorMatrix . |

### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


Устанавливает элемент в третьей строке и первом столбце этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в третьей строке и первом столбце этой  Aspose.Imaging.ColorMatrix . |

### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


Устанавливает элемент в третьей строке и втором столбце этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в третьей строке и втором столбце этой  Aspose.Imaging.ColorMatrix . |

### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


Устанавливает элемент в третьей строке и третьем столбце этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в третьей строке и третьем столбце этой  Aspose.Imaging.ColorMatrix . |

### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


Устанавливает элемент в третьей строке и четвертом столбце этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в третьей строке и четвертом столбце этой  Aspose.Imaging.ColorMatrix . |

### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


Устанавливает элемент в четвертой строке и столбце 0 (ноль) этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в четвертой строке и 0 столбце этой  Aspose.Imaging.ColorMatrix . |

### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


Устанавливает элемент в четвертой строке и первом столбце этой  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в четвертой строке и первом столбце этой  Aspose.Imaging.ColorMatrix . |

### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


Устанавливает элемент в четвертой строке и втором столбце этого  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в четвертой строке и втором столбце этой  Aspose.Imaging.ColorMatrix . |

### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


Устанавливает элемент в четвертой строке и третьем столбце этого  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в четвертой строке и третьем столбце этой  Aspose.Imaging.ColorMatrix . |

### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


Устанавливает элемент в четвертой строке и четвертом столбце этого  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float | Элемент в четвертой строке и четвертом столбце этой  Aspose.Imaging.ColorMatrix . |

### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


Устанавливает элемент в указанной строке и столбце в  Aspose.Imaging.ColorMatrix .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| строка | int | Номер строки. |
| столбец | int | Номер столбца. |
| значение | float | Значение |

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

