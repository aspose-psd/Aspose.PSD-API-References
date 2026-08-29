---
title: "MultiPageOptions"
second_title: "Aspose.PSD for Java API Справочник"
description: "Базовый класс для форматов, поддерживающих несколько страниц."
type: docs
weight: 17
url: /ru/java/com.aspose.psd.imageoptions/multipageoptions/
---

**Inheritance:**
java.lang.Object
```
public class MultiPageOptions
```

Базовый класс для форматов, поддерживающих несколько страниц.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MultiPageOptions()](#MultiPageOptions--) | Инициализирует новый экземпляр класса  MultiPageOptions . |
| [MultiPageOptions(int[] pages)](#MultiPageOptions-int---) | Инициализирует новый экземпляр класса  MultiPageOptions . |
| [MultiPageOptions(int[] pages, Rectangle exportArea)](#MultiPageOptions-int---com.aspose.psd.Rectangle-) | Инициализирует новый экземпляр класса  MultiPageOptions . |
| [MultiPageOptions(String[] pageTitles)](#MultiPageOptions-java.lang.String---) | Инициализирует новый экземпляр класса  MultiPageOptions . |
| [MultiPageOptions(String[] pageTitles, Rectangle exportArea)](#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-) | Инициализирует новый экземпляр класса  MultiPageOptions . |
| [MultiPageOptions(IntRange[] ranges)](#MultiPageOptions-com.aspose.psd.IntRange---) | Инициализирует новый экземпляр класса  MultiPageOptions . |
| [MultiPageOptions(IntRange[] ranges, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-) | Инициализирует новый экземпляр класса  MultiPageOptions . |
| [MultiPageOptions(IntRange range)](#MultiPageOptions-com.aspose.psd.IntRange-) | Инициализирует новый экземпляр класса  MultiPageOptions . |
| [MultiPageOptions(IntRange range, Rectangle exportArea)](#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-) | Инициализирует новый экземпляр класса  MultiPageOptions . |
| [MultiPageOptions(int page)](#MultiPageOptions-int-) | Инициализирует новый экземпляр класса  MultiPageOptions . |
| [MultiPageOptions(int page, Rectangle exportArea)](#MultiPageOptions-int-com.aspose.psd.Rectangle-) | Инициализирует новый экземпляр класса  MultiPageOptions . |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getExportArea()](#getExportArea--) | Получает или задаёт область экспорта. |
| [getMergeLayers()](#getMergeLayers--) | Получает значение, указывающее, следует ли [merege layers]. |
| [getMode()](#getMode--) | Получает или задает режим. |
| [getOutputLayersNames()](#getOutputLayersNames--) | Получает или задает имена выходных слоёв(Работает, если формат экспорта поддерживает именование слоёв, например для Psd) |
| [getPageRasterizationOptions()](#getPageRasterizationOptions--) | Получает параметры растеризации страницы. |
| [getPageTitles()](#getPageTitles--) | Получает или задает заголовки страниц. |
| [getPages()](#getPages--) | Получает или задает страницы. |
| [getTimeInterval_internalized()](#getTimeInterval-internalized--) | Получает временной интервал. |
| [hashCode()](#hashCode--) |  |
| [initPages(IntRange[] ranges)](#initPages-com.aspose.psd.IntRange---) | Инициализирует страницы из массива диапазонов |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setExportArea(Rectangle value)](#setExportArea-com.aspose.psd.Rectangle-) | Получает или задаёт область экспорта. |
| [setMergeLayers(boolean value)](#setMergeLayers-boolean-) | Устанавливает значение, указывающее, следует ли [merege layers]. |
| [setMode(int value)](#setMode-int-) | Получает или задает режим. |
| [setOutputLayersNames(String[] value)](#setOutputLayersNames-java.lang.String---) | Получает или задает имена выходных слоёв(Работает, если формат экспорта поддерживает именование слоёв, например для Psd) |
| [setPageRasterizationOptions(VectorRasterizationOptions[] value)](#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---) | Устанавливает параметры растеризации страницы. |
| [setPageTitles(String[] value)](#setPageTitles-java.lang.String---) | Получает или задает заголовки страниц. |
| [setPages(int[] value)](#setPages-int---) | Получает или задает страницы. |
| [setTimeInterval_internalized(TimeInterval value)](#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-) | Устанавливает временной интервал. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MultiPageOptions() {#MultiPageOptions--}
```
public MultiPageOptions()
```


Инициализирует новый экземпляр класса  MultiPageOptions .

### MultiPageOptions(int[] pages) {#MultiPageOptions-int---}
```
public MultiPageOptions(int[] pages)
```


Инициализирует новый экземпляр класса  MultiPageOptions .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| страницы | int[] | Страницы. |

### MultiPageOptions(int[] pages, Rectangle exportArea) {#MultiPageOptions-int---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int[] pages, Rectangle exportArea)
```


Инициализирует новый экземпляр класса  MultiPageOptions .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| страницы | int[] | Массив страниц. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Область экспорта. |

### MultiPageOptions(String[] pageTitles) {#MultiPageOptions-java.lang.String---}
```
public MultiPageOptions(String[] pageTitles)
```


Инициализирует новый экземпляр класса  MultiPageOptions .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Заголовки страниц. |

### MultiPageOptions(String[] pageTitles, Rectangle exportArea) {#MultiPageOptions-java.lang.String---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(String[] pageTitles, Rectangle exportArea)
```


Инициализирует новый экземпляр класса  MultiPageOptions .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageTitles | java.lang.String[] | Заголовки страниц. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Область экспорта. |

### MultiPageOptions(IntRange[] ranges) {#MultiPageOptions-com.aspose.psd.IntRange---}
```
public MultiPageOptions(IntRange[] ranges)
```


Инициализирует новый экземпляр класса  MultiPageOptions .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | Тип  IntRange . |

### MultiPageOptions(IntRange[] ranges, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange---com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange[] ranges, Rectangle exportArea)
```


Инициализирует новый экземпляр класса  MultiPageOptions .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | Тип  IntRange . |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Область экспорта. |

### MultiPageOptions(IntRange range) {#MultiPageOptions-com.aspose.psd.IntRange-}
```
public MultiPageOptions(IntRange range)
```


Инициализирует новый экземпляр класса  MultiPageOptions .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | Тип  IntRange . |

### MultiPageOptions(IntRange range, Rectangle exportArea) {#MultiPageOptions-com.aspose.psd.IntRange-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(IntRange range, Rectangle exportArea)
```


Инициализирует новый экземпляр класса  MultiPageOptions .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| range | [IntRange](../../com.aspose.psd/intrange) | Тип  IntRange . |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Область экспорта. |

### MultiPageOptions(int page) {#MultiPageOptions-int-}
```
public MultiPageOptions(int page)
```


Инициализирует новый экземпляр класса  MultiPageOptions .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| page | int | Индекс страницы. |

### MultiPageOptions(int page, Rectangle exportArea) {#MultiPageOptions-int-com.aspose.psd.Rectangle-}
```
public MultiPageOptions(int page, Rectangle exportArea)
```


Инициализирует новый экземпляр класса  MultiPageOptions .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| page | int | Индекс страницы. |
| exportArea | [Rectangle](../../com.aspose.psd/rectangle) | Область экспорта. |

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
### getExportArea() {#getExportArea--}
```
public Rectangle getExportArea()
```


Получает или задаёт область экспорта.

Значение: Область экспорта.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getMergeLayers() {#getMergeLayers--}
```
public final boolean getMergeLayers()
```


Получает значение, указывающее, следует ли [merege layers].

Значение:  true  если [merege layers]; иначе,  false .

**Returns:**
boolean - значение, указывающее, следует ли [merege layers].
### getMode() {#getMode--}
```
public int getMode()
```


Получает или задает режим.

Значение: Режим.

**Returns:**
int
### getOutputLayersNames() {#getOutputLayersNames--}
```
public String[] getOutputLayersNames()
```


Получает или задает имена выходных слоёв(Работает, если формат экспорта поддерживает именование слоёв, например для Psd)

Значение: Имена выходных слоёв.

**Returns:**
java.lang.String[]
### getPageRasterizationOptions() {#getPageRasterizationOptions--}
```
public final VectorRasterizationOptions[] getPageRasterizationOptions()
```


Получает параметры растеризации страницы.

**Returns:**
com.aspose.psd.imageoptions.VectorRasterizationOptions[] - параметры растеризации страницы.
### getPageTitles() {#getPageTitles--}
```
public String[] getPageTitles()
```


Получает или задает заголовки страниц.

Значение: Заголовки страниц.

**Returns:**
java.lang.String[]
### getPages() {#getPages--}
```
public int[] getPages()
```


Получает или задает страницы.

Значение: Страницы.

**Returns:**
int[]
### getTimeInterval_internalized() {#getTimeInterval-internalized--}
```
public final TimeInterval getTimeInterval_internalized()
```


Получает временной интервал.

Значение: Временной интервал.

**Returns:**
[TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) - the time interval.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initPages(IntRange[] ranges) {#initPages-com.aspose.psd.IntRange---}
```
public void initPages(IntRange[] ranges)
```


Инициализирует страницы из массива диапазонов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| ranges | [IntRange\[\]](../../com.aspose.psd/intrange) | Диапазоны. |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setExportArea(Rectangle value) {#setExportArea-com.aspose.psd.Rectangle-}
```
public void setExportArea(Rectangle value)
```


Получает или задаёт область экспорта.

Значение: Область экспорта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setMergeLayers(boolean value) {#setMergeLayers-boolean-}
```
public final void setMergeLayers(boolean value)
```


Устанавливает значение, указывающее, следует ли [merege layers].

Значение:  true  если [merege layers]; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | значение, указывающее, следует ли [merege layers]. |

### setMode(int value) {#setMode-int-}
```
public void setMode(int value)
```


Получает или задает режим.

Значение: Режим.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setOutputLayersNames(String[] value) {#setOutputLayersNames-java.lang.String---}
```
public void setOutputLayersNames(String[] value)
```


Получает или задает имена выходных слоёв(Работает, если формат экспорта поддерживает именование слоёв, например для Psd)

Значение: Имена выходных слоёв.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String[] |  |

### setPageRasterizationOptions(VectorRasterizationOptions[] value) {#setPageRasterizationOptions-com.aspose.psd.imageoptions.VectorRasterizationOptions---}
```
public final void setPageRasterizationOptions(VectorRasterizationOptions[] value)
```


Устанавливает параметры растеризации страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [VectorRasterizationOptions\[\]](../../com.aspose.psd.imageoptions/vectorrasterizationoptions) | параметры растеризации страницы. |

### setPageTitles(String[] value) {#setPageTitles-java.lang.String---}
```
public void setPageTitles(String[] value)
```


Получает или задает заголовки страниц.

Значение: Заголовки страниц.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String[] |  |

### setPages(int[] value) {#setPages-int---}
```
public void setPages(int[] value)
```


Получает или задает страницы.

Значение: Страницы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int[] |  |

### setTimeInterval_internalized(TimeInterval value) {#setTimeInterval-internalized-com.aspose.psd.imageoptions.TimeInterval-}
```
public final void setTimeInterval_internalized(TimeInterval value)
```


Устанавливает временной интервал.

Значение: Временной интервал.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [TimeInterval](../../com.aspose.psd.imageoptions/timeinterval) | временной интервал. |

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

