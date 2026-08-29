---
title: "Jpeg2000LoadOptions"
second_title: "Aspose.PSD for Java API Справочник"
description: "Параметры загрузки JPEG2000"
type: docs
weight: 10
url: /ru/java/com.aspose.psd.imageloadoptions/jpeg2000loadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class Jpeg2000LoadOptions extends LoadOptions
```

Параметры загрузки JPEG2000
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Jpeg2000LoadOptions()](#Jpeg2000LoadOptions--) | Инициализирует новый экземпляр класса  Jpeg2000LoadOptions . |
## Поля

| Поле | Описание |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | Пользовательские источники шрифтов |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBufferSizeHint()](#getBufferSizeHint--) | Получает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Получает  Image  фоновой Цвет. |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Получает режим восстановления данных. |
| [getDefaultMaximumDecodingTime_internalized()](#getDefaultMaximumDecodingTime-internalized--) | Получает значение максимального времени декодирования по умолчанию. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Получает значение, указывающее, следует ли [ignore after load]. |
| [getMaximumDecodingTime()](#getMaximumDecodingTime--) | Получает максимальное время декодирования в секундах (эта опция может использоваться на очень медленных или малообъёмных машинах, чтобы предотвратить зависание процесса при работе с очень большими изображениями — разрешение более 5500x6500 пикселей). |
| [getMaximumDecodingTimeForTile()](#getMaximumDecodingTimeForTile--) | Получает максимальное время декодирования для плитки. |
| [getProgressEventHandler()](#getProgressEventHandler--) | Получает обработчик события прогресса. |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Получает значение, указывающее, следует ли применять преобразование ICC‑профиля. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Это часть шаблона лицензирования предприятия. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Устанавливает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Устанавливает  Image  фон  Color . |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Устанавливает режим восстановления данных. |
| [setDefaultMaximumDecodingTime_internalized(int value)](#setDefaultMaximumDecodingTime-internalized-int-) | Устанавливает значение по умолчанию для максимального времени декодирования. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Устанавливает значение, указывающее, [ignore after load]. |
| [setMaximumDecodingTime(int value)](#setMaximumDecodingTime-int-) | Устанавливает максимальное время декодирования в секундах (эта опция может использоваться на очень медленных машинах с небольшим объёмом памяти, чтобы предотвратить зависание процесса при работе с очень большими изображениями — разрешение более 5500×6500 пикселей). |
| [setMaximumDecodingTimeForTile(int value)](#setMaximumDecodingTimeForTile-int-) | Устанавливает максимальное время декодирования для тайла. |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Получает или устанавливает менеджер памяти MGR. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Устанавливает обработчик события прогресса. |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Устанавливает значение, указывающее, следует ли применять преобразование ICC‑профиля. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | Это часть шаблона лицензирования предприятия. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Jpeg2000LoadOptions() {#Jpeg2000LoadOptions--}
```
public Jpeg2000LoadOptions()
```


Инициализирует новый экземпляр класса  Jpeg2000LoadOptions .

### CustomFontSources_internalized {#CustomFontSources-internalized}
```
public System.Collections.Generic.List<CustomFontSource> CustomFontSources_internalized
```


Пользовательские источники шрифтов

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
### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Получает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов.

Значение: подсказка размера буфера в мегабайтах. Неположительное значение означает отсутствие ограничения памяти для внутренних буферов

**Returns:**
int - подсказка размера буфера, определяющая максимальный допустимый размер для всех внутренних буферов.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataBackgroundColor() {#getDataBackgroundColor--}
```
public Color getDataBackgroundColor()
```


Получает  Image  фоновой Цвет.

**Returns:**
[Color](../../com.aspose.psd/color) - The background color.

Обычно цвет фона устанавливается, когда значение пикселя нельзя восстановить из‑за повреждения данных.
### getDataRecoveryMode() {#getDataRecoveryMode--}
```
public int getDataRecoveryMode()
```


Получает режим восстановления данных.

**Returns:**
int — режим восстановления данных.
### getDefaultMaximumDecodingTime_internalized() {#getDefaultMaximumDecodingTime-internalized--}
```
public static int getDefaultMaximumDecodingTime_internalized()
```


Получает значение максимального времени декодирования по умолчанию.

**Returns:**
int — значение по умолчанию для максимального времени декодирования.
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


Получает значение, указывающее, следует ли [ignore after load].

**Returns:**
boolean -  true  если [ignore after load]; иначе,  false .
### getMaximumDecodingTime() {#getMaximumDecodingTime--}
```
public int getMaximumDecodingTime()
```


Получает максимальное время декодирования в секундах (эта опция может использоваться на очень медленных или малообъёмных машинах, чтобы предотвратить зависание процесса при работе с очень большими изображениями — разрешение более 5500x6500 пикселей).

**Returns:**
int — максимальное время декодирования.
### getMaximumDecodingTimeForTile() {#getMaximumDecodingTimeForTile--}
```
public final int getMaximumDecodingTimeForTile()
```


Получает максимальное время декодирования для плитки.

Значение: максимальное время декодирования для тайла.

**Returns:**
int — максимальное время декодирования для тайла.
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Получает обработчик события прогресса.

Значение: обработчик события прогресса.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getUseIccProfileConversion() {#getUseIccProfileConversion--}
```
public boolean getUseIccProfileConversion()
```


Получает значение, указывающее, следует ли применять преобразование ICC‑профиля.

**Returns:**
boolean
### getVentureLicense_internalized() {#getVentureLicense-internalized--}
```
public Object getVentureLicense_internalized()
```


Это часть шаблона лицензирования предприятия. Это значение будет установлено VentureLicenser, если предприятие передаст нам объект LoadOptions.

**Returns:**
java.lang.Object
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




### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Устанавливает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов.

Значение: подсказка размера буфера в мегабайтах. Неположительное значение означает отсутствие ограничения памяти для внутренних буферов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | подсказка размера буфера, определяющая максимальный разрешённый размер для всех внутренних буферов. |

### setDataBackgroundColor(Color value) {#setDataBackgroundColor-com.aspose.psd.Color-}
```
public void setDataBackgroundColor(Color value)
```


Устанавливает  Image  фон  Color .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | [Color](../../com.aspose.psd/color) | Цвет фона. |

Обычно цвет фона устанавливается, когда значение пикселя нельзя восстановить из‑за повреждения данных. |

### setDataRecoveryMode(int value) {#setDataRecoveryMode-int-}
```
public void setDataRecoveryMode(int value)
```


Устанавливает режим восстановления данных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Режим восстановления данных. |

### setDefaultMaximumDecodingTime_internalized(int value) {#setDefaultMaximumDecodingTime-internalized-int-}
```
public static void setDefaultMaximumDecodingTime_internalized(int value)
```


Устанавливает значение по умолчанию для максимального времени декодирования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Значение по умолчанию для максимального времени декодирования. |

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


Устанавливает значение, указывающее, [ignore after load].

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | true  если [ignore after load]; иначе,  false . |

### setMaximumDecodingTime(int value) {#setMaximumDecodingTime-int-}
```
public void setMaximumDecodingTime(int value)
```


Устанавливает максимальное время декодирования в секундах (эта опция может использоваться на очень медленных машинах с небольшим объёмом памяти, чтобы предотвратить зависание процесса при работе с очень большими изображениями — разрешение более 5500×6500 пикселей).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Максимальное время декодирования. |

### setMaximumDecodingTimeForTile(int value) {#setMaximumDecodingTimeForTile-int-}
```
public final void setMaximumDecodingTimeForTile(int value)
```


Устанавливает максимальное время декодирования для тайла.

Значение: максимальное время декодирования для тайла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | Максимальное время декодирования для плитки. |

### setMemMgr_internalized(MemMgr value) {#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-}
```
public final void setMemMgr_internalized(MemMgr value)
```


Получает или устанавливает менеджер памяти MGR.

Значение: Память MGR.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.internal.memorymanagement.MemMgr |  |

### setProgressEventHandler(ProgressEventHandler value) {#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-}
```
public void setProgressEventHandler(ProgressEventHandler value)
```


Устанавливает обработчик события прогресса.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.psd/progresseventhandler) | Обработчик события прогресса. |

### setUseIccProfileConversion(boolean value) {#setUseIccProfileConversion-boolean-}
```
public void setUseIccProfileConversion(boolean value)
```


Устанавливает значение, указывающее, следует ли применять преобразование ICC‑профиля.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setVentureLicense_internalized(Object value) {#setVentureLicense-internalized-java.lang.Object-}
```
public void setVentureLicense_internalized(Object value)
```


Это часть шаблона лицензирования предприятия. Это значение будет установлено VentureLicenser, если предприятие передаст нам объект LoadOptions.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.Object |  |

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

