---
title: "Blend"
second_title: "Aspose.PSD for Java API Справочник"
description: "Определяет шаблон смешивания."
type: docs
weight: 11
url: /ru/java/com.aspose.psd/blend/
---

**Inheritance:**
java.lang.Object
```
public final class Blend
```

Определяет шаблон смешивания. Этот класс не может быть унаследован.

Обычное использование класса blend заключается в определении шаблона смешивания для кисти. Поэтому свойства смешивания следует инициализировать тщательно. Массивы не могут быть null. Кисть выбросит соответствующее исключение, если массивы факторов смешивания или позиций пусты или их длина различается. Если в массиве позиций два и более элементов, первый элемент должен быть 0, а последний — 1.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Blend()](#Blend--) | Инициализирует новый экземпляр класса Blend. |
| [Blend(int count)](#Blend-int-) | Инициализирует новый экземпляр класса Blend с указанным количеством факторов и позиций. |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверяет, является ли указанный объект классом com.aspose.psd.Blend и эквивалентен ли он этому классу com.aspose.psd.Blend. |
| [getClass()](#getClass--) |  |
| [getFactors()](#getFactors--) | Получает массив факторов смешивания для градиента. |
| [getPositions()](#getPositions--) | Получает массив позиций смешивания для градиента. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFactors(float[] value)](#setFactors-float---) | Устанавливает массив факторов смешивания для градиента. |
| [setPositions(float[] value)](#setPositions-float---) | Устанавливает массив позиций смешивания для градиента. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Blend() {#Blend--}
```
public Blend()
```


Инициализирует новый экземпляр класса Blend. Количество элементов в массивах факторов и позиций будет равно 1.

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


Инициализирует новый экземпляр класса Blend с указанным количеством факторов и позиций.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| count | int | Количество элементов в массивах факторов и позиций. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Проверяет, является ли указанный объект классом com.aspose.psd.Blend и эквивалентен ли он этому классу com.aspose.psd.Blend.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для тестирования. |

**Returns:**
boolean — true, если obj является классом com.aspose.psd.Blend, эквивалентным этому классу com.aspose.psd.Blend; иначе — false.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFactors() {#getFactors--}
```
public float[] getFactors()
```


Получает массив факторов смешивания для градиента.

**Returns:**
float[] — массив факторов смешивания, определяющих процентное соотношение начального и конечного цвета, используемое в соответствующей позиции.
### getPositions() {#getPositions--}
```
public float[] getPositions()
```


Получает массив позиций смешивания для градиента.

**Returns:**
float[] — массив позиций смешивания, определяющих процентное соотношение расстояния вдоль линии градиента.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int - Хеш-код для этого экземпляра, подходящий для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFactors(float[] value) {#setFactors-float---}
```
public void setFactors(float[] value)
```


Устанавливает массив факторов смешивания для градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float[] | Массив факторов смешивания, определяющих процентное соотношение начального и конечного цвета, используемое в соответствующей позиции. |

### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


Устанавливает массив позиций смешивания для градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float[] | Массив позиций смешивания, определяющих процентное соотношение расстояния вдоль линии градиента. |

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

