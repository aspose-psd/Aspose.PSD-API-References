---
title: "PsdLoadOptions"
second_title: "Aspose.PSD for Java API Справочник"
description: "Параметры загрузки PSD"
type: docs
weight: 12
url: /ru/java/com.aspose.psd.imageloadoptions/psdloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.LoadOptions](../../com.aspose.psd/loadoptions)
```
public class PsdLoadOptions extends LoadOptions
```

Параметры загрузки PSD
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PsdLoadOptions()](#PsdLoadOptions--) | Инициализирует новый экземпляр класса [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions). |
## Поля

| Поле | Описание |
| --- | --- |
| [CustomFontSources_internalized](#CustomFontSources-internalized) | Пользовательские источники шрифтов |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAllowNonChangedLayerRepaint()](#getAllowNonChangedLayerRepaint--) | Получает или задает, сохранять ли оригинальные пиксели слоев при рендеринге, если слой не был изменён. |
| [getAllowWarpRepaint()](#getAllowWarpRepaint--) | Получает или задает, сохранять ли с отрендеренным изображением, с трансформацией искажения или без неё. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Получает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [getClass()](#getClass--) |  |
| [getDataBackgroundColor()](#getDataBackgroundColor--) | Получает  Image  фоновой Цвет. |
| [getDataRecoveryMode()](#getDataRecoveryMode--) | Получает режим восстановления данных. |
| [getIgnoreAfterLoad_internalized()](#getIgnoreAfterLoad-internalized--) | Получает значение, указывающее, следует ли [ignore after load]. |
| [getIgnoreAlphaChannel()](#getIgnoreAlphaChannel--) | Получает или задает значение, указывающее, следует ли [ignore alpha channel]. |
| [getIgnoreTextLayerWidthOnUpdate()](#getIgnoreTextLayerWidthOnUpdate--) | Получает или задает значение, указывающее, будет ли фиксированная ширина текстового слоя PSD игнорироваться при выполнении операции UpdateText. |
| [getLoadEffectsResource()](#getLoadEffectsResource--) | Получает или задает значение, указывающее, следует ли [load effects resource] (по умолчанию ресурс не загружается). |
| [getProgressEventHandler()](#getProgressEventHandler--) | Получает обработчик события прогресса. |
| [getReadOnlyMode()](#getReadOnlyMode--) | Получает или задает значение, указывающее, следует ли [use read only mode]. |
| [getReadOnlyType()](#getReadOnlyType--) | Получает или задает режим только для чтения, используемый при загрузке PSD‑изображения. |
| [getUseDiskForLoadEffectsResource()](#getUseDiskForLoadEffectsResource--) | Получает или задает значение, указывающее, следует ли [use disk for load effects resource] (по умолчанию используется диск для загрузки ресурсов эффектов, но можно использовать память, если её достаточно, установив это значение в false). |
| [getUseIccProfileConversion()](#getUseIccProfileConversion--) | Получает значение, указывающее, следует ли применять преобразование ICC‑профиля. |
| [getVentureLicense_internalized()](#getVentureLicense-internalized--) | Это часть шаблона лицензирования предприятия. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowNonChangedLayerRepaint(boolean value)](#setAllowNonChangedLayerRepaint-boolean-) | Получает или задает, сохранять ли оригинальные пиксели слоев при рендеринге, если слой не был изменён. |
| [setAllowWarpRepaint(boolean value)](#setAllowWarpRepaint-boolean-) | Получает или задает, сохранять ли с отрендеренным изображением, с трансформацией искажения или без неё. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Устанавливает подсказку о размере буфера, определяющую максимальный допустимый размер для всех внутренних буферов. |
| [setDataBackgroundColor(Color value)](#setDataBackgroundColor-com.aspose.psd.Color-) | Устанавливает  Image  фон  Color . |
| [setDataRecoveryMode(int value)](#setDataRecoveryMode-int-) | Устанавливает режим восстановления данных. |
| [setIgnoreAfterLoad_internalized(boolean value)](#setIgnoreAfterLoad-internalized-boolean-) | Устанавливает значение, указывающее, [ignore after load]. |
| [setIgnoreAlphaChannel(boolean value)](#setIgnoreAlphaChannel-boolean-) | Получает или задает значение, указывающее, следует ли [ignore alpha channel]. |
| [setIgnoreTextLayerWidthOnUpdate(boolean value)](#setIgnoreTextLayerWidthOnUpdate-boolean-) | Получает или задает значение, указывающее, будет ли фиксированная ширина текстового слоя PSD игнорироваться при выполнении операции UpdateText. |
| [setLoadEffectsResource(boolean value)](#setLoadEffectsResource-boolean-) | Получает или задает значение, указывающее, следует ли [load effects resource] (по умолчанию ресурс не загружается). |
| [setMemMgr_internalized(MemMgr value)](#setMemMgr-internalized-com.aspose.internal.memorymanagement.MemMgr-) | Получает или устанавливает менеджер памяти MGR. |
| [setProgressEventHandler(ProgressEventHandler value)](#setProgressEventHandler-com.aspose.psd.ProgressEventHandler-) | Устанавливает обработчик события прогресса. |
| [setReadOnlyMode(boolean value)](#setReadOnlyMode-boolean-) | Получает или задает значение, указывающее, следует ли [use read only mode]. |
| [setReadOnlyType(int value)](#setReadOnlyType-int-) | Получает или задает режим только для чтения, используемый при загрузке PSD‑изображения. |
| [setUseDiskForLoadEffectsResource(boolean value)](#setUseDiskForLoadEffectsResource-boolean-) | Получает или задает значение, указывающее, следует ли [use disk for load effects resource] (по умолчанию используется диск для загрузки ресурсов эффектов, но можно использовать память, если её достаточно, установив это значение в false). |
| [setUseIccProfileConversion(boolean value)](#setUseIccProfileConversion-boolean-) | Устанавливает значение, указывающее, следует ли применять преобразование ICC‑профиля. |
| [setVentureLicense_internalized(Object value)](#setVentureLicense-internalized-java.lang.Object-) | Это часть шаблона лицензирования предприятия. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PsdLoadOptions() {#PsdLoadOptions--}
```
public PsdLoadOptions()
```


Инициализирует новый экземпляр класса [PsdLoadOptions](../../com.aspose.psd.imageloadoptions/psdloadoptions).

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
### getAllowNonChangedLayerRepaint() {#getAllowNonChangedLayerRepaint--}
```
public final boolean getAllowNonChangedLayerRepaint()
```


Получает или задает, сохранять ли оригинальные пиксели слоев при рендеринге, если слой не был изменён.

Значение:  true  — сохранять оригинальные пиксели неизменённых слоёв; иначе —  false .

**Returns:**
boolean
### getAllowWarpRepaint() {#getAllowWarpRepaint--}
```
public final boolean getAllowWarpRepaint()
```


Получает или задает, сохранять ли с отрендеренным изображением, с трансформацией искажения или без неё.

Значение:  true  — рендерить изображение с трансформацией искажения;  false  — без неё.

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
### getIgnoreAfterLoad_internalized() {#getIgnoreAfterLoad-internalized--}
```
public boolean getIgnoreAfterLoad_internalized()
```


Получает значение, указывающее, следует ли [ignore after load].

**Returns:**
boolean -  true  если [ignore after load]; иначе,  false .
### getIgnoreAlphaChannel() {#getIgnoreAlphaChannel--}
```
public final boolean getIgnoreAlphaChannel()
```


Получает или задает значение, указывающее, следует ли [ignore alpha channel].

Значение:  true  если [ignore alpha channel]; иначе —  false .

**Returns:**
boolean
### getIgnoreTextLayerWidthOnUpdate() {#getIgnoreTextLayerWidthOnUpdate--}
```
public final boolean getIgnoreTextLayerWidthOnUpdate()
```


Получает или задает значение, указывающее, будет ли фиксированная ширина текстового слоя PSD игнорироваться при выполнении операции UpdateText.

Значение:  true  если [ignore text layer width]; иначе —  false .

**Returns:**
boolean
### getLoadEffectsResource() {#getLoadEffectsResource--}
```
public final boolean getLoadEffectsResource()
```


Получает или задает значение, указывающее, следует ли [load effects resource] (по умолчанию ресурс не загружается). При установке этой опции будут отрендерены только поддерживаемые эффекты в окончательное объединённое изображение.

Значение:  true  если [load effects resource]; иначе —  false .

**Returns:**
boolean
### getProgressEventHandler() {#getProgressEventHandler--}
```
public ProgressEventHandler getProgressEventHandler()
```


Получает обработчик события прогресса.

Значение: обработчик события прогресса.

**Returns:**
[ProgressEventHandler](../../com.aspose.psd/progresseventhandler) - the progress event handler.
### getReadOnlyMode() {#getReadOnlyMode--}
```
public final boolean getReadOnlyMode()
```


Получает или задает значение, указывающее, следует ли [use read only mode]. Это режим только для чтения, поддерживаемый для полной совместимости с Adobe Photoshop. Когда эта опция включена, все изменения, применённые к слоям, не сохраняются в окончательное изображение. Все данные берутся из раздела ImageData, поэтому они идентичны Photoshop. По умолчанию все загруженные изображения не полностью совместимы с Adobe Photoshop.

Значение:  true  если [use photoshop compatibility mode]; иначе —  false .

**Returns:**
boolean
### getReadOnlyType() {#getReadOnlyType--}
```
public final int getReadOnlyType()
```


Получает или задает режим только для чтения, используемый при загрузке PSD‑изображения.

Значение: одно из значений ReadOnlyMode ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)).

 *  
 *  
 *  

**Returns:**
int
### getUseDiskForLoadEffectsResource() {#getUseDiskForLoadEffectsResource--}
```
public final boolean getUseDiskForLoadEffectsResource()
```


Получает или задает значение, указывающее, следует ли [use disk for load effects resource] (по умолчанию используется диск для загрузки ресурсов эффектов, но можно использовать память, если её достаточно, установив это значение в false).

Значение:  true  если [use disk for load effects resource]; иначе —  false .

**Returns:**
boolean
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




### setAllowNonChangedLayerRepaint(boolean value) {#setAllowNonChangedLayerRepaint-boolean-}
```
public final void setAllowNonChangedLayerRepaint(boolean value)
```


Получает или задает, сохранять ли оригинальные пиксели слоев при рендеринге, если слой не был изменён.

Значение:  true  — сохранять оригинальные пиксели неизменённых слоёв; иначе —  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setAllowWarpRepaint(boolean value) {#setAllowWarpRepaint-boolean-}
```
public final void setAllowWarpRepaint(boolean value)
```


Получает или задает, сохранять ли с отрендеренным изображением, с трансформацией искажения или без неё.

Значение:  true  — рендерить изображение с трансформацией искажения;  false  — без неё.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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

### setIgnoreAfterLoad_internalized(boolean value) {#setIgnoreAfterLoad-internalized-boolean-}
```
public void setIgnoreAfterLoad_internalized(boolean value)
```


Устанавливает значение, указывающее, [ignore after load].

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean | true  если [ignore after load]; иначе,  false . |

### setIgnoreAlphaChannel(boolean value) {#setIgnoreAlphaChannel-boolean-}
```
public final void setIgnoreAlphaChannel(boolean value)
```


Получает или задает значение, указывающее, следует ли [ignore alpha channel].

Значение:  true  если [ignore alpha channel]; иначе —  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setIgnoreTextLayerWidthOnUpdate(boolean value) {#setIgnoreTextLayerWidthOnUpdate-boolean-}
```
public final void setIgnoreTextLayerWidthOnUpdate(boolean value)
```


Получает или задает значение, указывающее, будет ли фиксированная ширина текстового слоя PSD игнорироваться при выполнении операции UpdateText.

Значение:  true  если [ignore text layer width]; иначе —  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setLoadEffectsResource(boolean value) {#setLoadEffectsResource-boolean-}
```
public final void setLoadEffectsResource(boolean value)
```


Получает или задает значение, указывающее, следует ли [load effects resource] (по умолчанию ресурс не загружается). При установке этой опции будут отрендерены только поддерживаемые эффекты в окончательное объединённое изображение.

Значение:  true  если [load effects resource]; иначе —  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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

### setReadOnlyMode(boolean value) {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```


Получает или задает значение, указывающее, следует ли [use read only mode]. Это режим только для чтения, поддерживаемый для полной совместимости с Adobe Photoshop. Когда эта опция включена, все изменения, применённые к слоям, не сохраняются в окончательное изображение. Все данные берутся из раздела ImageData, поэтому они идентичны Photoshop. По умолчанию все загруженные изображения не полностью совместимы с Adobe Photoshop.

Значение:  true  если [use photoshop compatibility mode]; иначе —  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setReadOnlyType(int value) {#setReadOnlyType-int-}
```
public final void setReadOnlyType(int value)
```


Получает или задает режим только для чтения, используемый при загрузке PSD‑изображения.

Значение: одно из значений ReadOnlyMode ([.getReadOnlyMode](../../null/\#getReadOnlyMode)/[.setReadOnlyMode(boolean)](../../null/\#setReadOnlyMode-boolean-)).

 *  
 *  
 *  

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setUseDiskForLoadEffectsResource(boolean value) {#setUseDiskForLoadEffectsResource-boolean-}
```
public final void setUseDiskForLoadEffectsResource(boolean value)
```


Получает или задает значение, указывающее, следует ли [use disk for load effects resource] (по умолчанию используется диск для загрузки ресурсов эффектов, но можно использовать память, если её достаточно, установив это значение в false).

Значение:  true  если [use disk for load effects resource]; иначе —  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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

