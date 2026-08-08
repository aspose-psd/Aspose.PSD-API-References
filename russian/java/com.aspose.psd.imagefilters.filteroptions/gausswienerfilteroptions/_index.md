---
title: "GaussWienerFilterOptions"
second_title: "Aspose.PSD for Java API Справочник"
description: "Параметры фильтра Гаусса-Винера, устранение размытия Гаусс"
type: docs
weight: 15
url: /ru/java/com.aspose.psd.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.psd.imagefilters.filteroptions/filteroptionsbase), [com.aspose.psd.imagefilters.filteroptions.DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions)
```
public class GaussWienerFilterOptions extends DeconvolutionFilterOptions
```

Параметры фильтра Гаусса-Винера, устранение размытия Гаусс
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GaussWienerFilterOptions(int radius, double smooth)](#GaussWienerFilterOptions-int-double-) | Инициализирует новый экземпляр класса  GaussWienerFilterOptions  . |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions--) | Инициализирует новый экземпляр класса  GaussWienerFilterOptions  . |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBrightness()](#getBrightness--) | Получает или задает яркость. |
| [getClass()](#getClass--) |  |
| [getGrayscale()](#getGrayscale--) | Получает или задаёт значение, указывающее, является ли этот [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) градацией серого. |
| [getRadius()](#getRadius--) | Получает или задает радиус. |
| [getSmooth()](#getSmooth--) | Получает или задаёт сглаживание. |
| [getSnr()](#getSnr--) | Получает или задаёт SNR (отношение сигнал‑шум), рекомендуемый диапазон 0.002 - 0.009, значение по умолчанию = 0.007. |
| [hashCode()](#hashCode--) |  |
| [isPartialLoaded()](#isPartialLoaded--) | Получает значение, указывающее, частично ли загружен этот экземпляр. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBrightness(double value)](#setBrightness-double-) | Получает или задает яркость. |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Получает или задаёт значение, указывающее, является ли этот [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) градацией серого. |
| [setPartialLoaded(boolean value)](#setPartialLoaded-boolean-) | Получает значение, указывающее, частично ли загружен этот экземпляр. |
| [setRadius(int value)](#setRadius-int-) | Получает или задает радиус. |
| [setSmooth(double value)](#setSmooth-double-) | Получает или задаёт сглаживание. |
| [setSnr(double value)](#setSnr-double-) | Получает или задаёт SNR (отношение сигнал‑шум), рекомендуемый диапазон 0.002 - 0.009, значение по умолчанию = 0.007. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GaussWienerFilterOptions(int radius, double smooth) {#GaussWienerFilterOptions-int-double-}
```
public GaussWienerFilterOptions(int radius, double smooth)
```


Инициализирует новый экземпляр класса  GaussWienerFilterOptions  .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| radius | int | Радиус. |
| сглаживание | double | Сглаживание. |

### GaussWienerFilterOptions() {#GaussWienerFilterOptions--}
```
public GaussWienerFilterOptions()
```


Инициализирует новый экземпляр класса  GaussWienerFilterOptions  . С настройками по умолчанию.

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
### getBrightness() {#getBrightness--}
```
public final double getBrightness()
```


Получает или задаёт яркость. рекомендуемый диапазон 1 - 1.5, значение по умолчанию = 1.15.

Значение: яркость.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Получает или задает значение, указывающее, является ли этот [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) оттенком серого. Возвращает режим оттенков серого или режим RGB.

Значение:  true  если оттенок серого; иначе,  false .

**Returns:**
boolean
### getRadius() {#getRadius--}
```
public int getRadius()
```


Получает или задает радиус.

Значение: Радиус.

**Returns:**
int
### getSmooth() {#getSmooth--}
```
public double getSmooth()
```


Получает или задаёт сглаживание.

Значение: Сглаживание.

**Returns:**
double
### getSnr() {#getSnr--}
```
public final double getSnr()
```


Получает или задаёт SNR (отношение сигнал‑шум), рекомендуемый диапазон 0.002 - 0.009, значение по умолчанию = 0.007.

Значение: SNR.

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPartialLoaded() {#isPartialLoaded--}
```
public final boolean isPartialLoaded()
```


Получает значение, указывающее, частично ли загружен этот экземпляр.

Значение:  true  если этот экземпляр частично загружен; иначе,  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBrightness(double value) {#setBrightness-double-}
```
public final void setBrightness(double value)
```


Получает или задаёт яркость. рекомендуемый диапазон 1 - 1.5, значение по умолчанию = 1.15.

Значение: яркость.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Получает или задает значение, указывающее, является ли этот [DeconvolutionFilterOptions](../../com.aspose.psd.imagefilters.filteroptions/deconvolutionfilteroptions) оттенком серого. Возвращает режим оттенков серого или режим RGB.

Значение:  true  если оттенок серого; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setPartialLoaded(boolean value) {#setPartialLoaded-boolean-}
```
public final void setPartialLoaded(boolean value)
```


Получает значение, указывающее, частично ли загружен этот экземпляр.

Значение:  true  если этот экземпляр частично загружен; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setRadius(int value) {#setRadius-int-}
```
public void setRadius(int value)
```


Получает или задает радиус.

Значение: Радиус.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setSmooth(double value) {#setSmooth-double-}
```
public void setSmooth(double value)
```


Получает или задаёт сглаживание.

Значение: Сглаживание.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setSnr(double value) {#setSnr-double-}
```
public final void setSnr(double value)
```


Получает или задаёт SNR (отношение сигнал‑шум), рекомендуемый диапазон 0.002 - 0.009, значение по умолчанию = 0.007.

Значение: SNR.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

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

