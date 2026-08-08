---
title: "RdOptimizerSettings"
second_title: "Aspose.PSD for Java API Справочник"
description: "Класс настроек оптимизатора RD."
type: docs
weight: 22
url: /ru/java/com.aspose.psd.imageoptions/rdoptimizersettings/
---

**Inheritance:**
java.lang.Object
```
public class RdOptimizerSettings
```

Класс настроек оптимизатора RD.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [RdOptimizerSettings()](#RdOptimizerSettings--) | Инициализирует новый экземпляр класса RdOptimizerSettings. |
## Методы

| Метод | Описание |
| --- | --- |
| [create()](#create--) | Создаёт этот экземпляр. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBppMax()](#getBppMax--) | Получает максимальное значение R для учёта в битах на пиксель |
| [getBppScale()](#getBppScale--) | Получает коэффициент масштабирования BPP (бит на пиксель). |
| [getClass()](#getClass--) |  |
| [getDcClamp_internalized()](#getDcClamp-internalized--) | Получает значение DC clamp для ограничения диапазона значений квантизации первого пикселя в левом верхнем углу блока. |
| [getDiscretizedBppMax()](#getDiscretizedBppMax--) | Получает максимальное значение R для учёта. |
| [getMaxChannel_internalized()](#getMaxChannel-internalized--) | Получает максимальное количество цветовых каналов для использования. |
| [getMaxPixelValue()](#getMaxPixelValue--) | Получает максимальное значение пикселя. |
| [getMaxQ()](#getMaxQ--) | Получает максимальное значение квантизации. |
| [getMinQ()](#getMinQ--) | Получает минимально допустимое значение квантования. |
| [getPsnrMax()](#getPsnrMax--) | Получает максимальное ожидаемое значение PSNR. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBppMax(double value)](#setBppMax-double-) | Устанавливает максимальное значение R для рассмотрения в битах на пиксель. |
| [setBppScale(int value)](#setBppScale-int-) | Устанавливает коэффициент масштабирования BPP (бит на пиксель). |
| [setMaxChannel_internalized(int value)](#setMaxChannel-internalized-int-) | Устанавливает максимальное количество цветовых каналов для использования. |
| [setMaxQ(int value)](#setMaxQ-int-) | Устанавливает максимальное значение квантования. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RdOptimizerSettings() {#RdOptimizerSettings--}
```
public RdOptimizerSettings()
```


Инициализирует новый экземпляр класса RdOptimizerSettings.

### create() {#create--}
```
public static RdOptimizerSettings create()
```


Создаёт этот экземпляр.

**Returns:**
[RdOptimizerSettings](../../com.aspose.psd.imageoptions/rdoptimizersettings) - returns RDOptimizerSettings class instance
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
### getBppMax() {#getBppMax--}
```
public double getBppMax()
```


Получает максимальное значение R для учёта в битах на пиксель

**Returns:**
double — максимальное значение R для рассмотрения в битах на пиксель.
### getBppScale() {#getBppScale--}
```
public int getBppScale()
```


Получает коэффициент масштабирования BPP (бит на пиксель).

**Returns:**
int — масштаб BPP.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDcClamp_internalized() {#getDcClamp-internalized--}
```
public int getDcClamp_internalized()
```


Получает значение DC clamp для ограничения диапазона значений квантизации первого пикселя в левом верхнем углу блока.

**Returns:**
int — значение ограничения DC.
### getDiscretizedBppMax() {#getDiscretizedBppMax--}
```
public int getDiscretizedBppMax()
```


Получает максимальное значение R для учёта.

**Returns:**
int — максимальное значение R для рассмотрения.
### getMaxChannel_internalized() {#getMaxChannel-internalized--}
```
public int getMaxChannel_internalized()
```


Получает максимальное количество цветовых каналов для использования.

**Returns:**
int — максимальный индекс цветового канала.
### getMaxPixelValue() {#getMaxPixelValue--}
```
public int getMaxPixelValue()
```


Получает максимальное значение пикселя.

**Returns:**
int — максимальное значение пикселя.
### getMaxQ() {#getMaxQ--}
```
public int getMaxQ()
```


Получает максимальное значение квантизации.

**Returns:**
int — максимальное значение квантования.
### getMinQ() {#getMinQ--}
```
public int getMinQ()
```


Получает минимально допустимое значение квантования.

**Returns:**
int — минимальное допустимое значение квантования.
### getPsnrMax() {#getPsnrMax--}
```
public int getPsnrMax()
```


Получает максимальное ожидаемое значение PSNR.

**Returns:**
int — максимальное значение пикселя.
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




### setBppMax(double value) {#setBppMax-double-}
```
public void setBppMax(double value)
```


Устанавливает максимальное значение R для рассмотрения в битах на пиксель.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double | Максимальное значение R для рассмотрения в битах на пиксель. |

### setBppScale(int value) {#setBppScale-int-}
```
public void setBppScale(int value)
```


Устанавливает коэффициент масштабирования BPP (бит на пиксель).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Масштаб BPP. |

### setMaxChannel_internalized(int value) {#setMaxChannel-internalized-int-}
```
public void setMaxChannel_internalized(int value)
```


Устанавливает максимальное количество цветовых каналов для использования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Максимальный индекс цветового канала. |

### setMaxQ(int value) {#setMaxQ-int-}
```
public void setMaxQ(int value)
```


Устанавливает максимальное значение квантования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Максимальное значение квантования. |

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

