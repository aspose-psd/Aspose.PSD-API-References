---
title: "LayerHashCalculator"
second_title: "Aspose.PSD for Java API Справочник"
description: "Калькулятор хеша для слоёв PSD."
type: docs
weight: 20
url: /ru/java/com.aspose.psd.fileformats.psd.layers/layerhashcalculator/
---

**Inheritance:**
java.lang.Object
```
public class LayerHashCalculator
```

Калькулятор хешей для слоёв PSD. Его можно использовать для поиска одинаковых или разных слоёв в разных файлах PSD.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LayerHashCalculator(Layer layer)](#LayerHashCalculator-com.aspose.psd.fileformats.psd.layers.Layer-) | Инициализирует новый экземпляр класса [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator). |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBlendingHash()](#getBlendingHash--) | Получает хеш смешивания. |
| [getChannelsHash()](#getChannelsHash--) | Получает хеш каналов. |
| [getClass()](#getClass--) |  |
| [getContentHash()](#getContentHash--) | Получает хеш содержимого. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LayerHashCalculator(Layer layer) {#LayerHashCalculator-com.aspose.psd.fileformats.psd.layers.Layer-}
```
public LayerHashCalculator(Layer layer)
```


Инициализирует новый экземпляр класса [LayerHashCalculator](../../com.aspose.psd.fileformats.psd.layers/layerhashcalculator).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layer | [Layer](../../com.aspose.psd.fileformats.psd.layers/layer) | Слой. |

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
### getBlendingHash() {#getBlendingHash--}
```
public final int getBlendingHash()
```


Получает хеш смешивания.

**Returns:**
int - Уникальный хеш для параметров смешивания слоя
### getChannelsHash() {#getChannelsHash--}
```
public final int getChannelsHash()
```


Получает хеш каналов.

**Returns:**
int - Хеш всех каналов слоя
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContentHash() {#getContentHash--}
```
public final int getContentHash()
```


Получает хеш содержимого.

**Returns:**
int - Хеш значимых параметров слоёв. Этот хеш различается для всех типов слоёв
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

