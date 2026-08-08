---
title: "PatternFillSettings"
second_title: "Aspose.PSD for Java API Справочник"
description: "Настройки эффекта заливки узором"
type: docs
weight: 20
url: /ru/java/com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.fileformats.psd.layers.fillsettings.BaseFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/basefillsettings)

**All Implemented Interfaces:**
[com.aspose.psd.fileformats.psd.layers.fillsettings.IPatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/ipatternfillsettings)
```
public class PatternFillSettings extends BaseFillSettings implements IPatternFillSettings
```

Настройки эффекта заливки узором
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PatternFillSettings()](#PatternFillSettings--) | Инициализирует новый экземпляр класса [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings). |
## Поля

| Поле | Описание |
| --- | --- |
| [ValueChanged_internalized](#ValueChanged-internalized) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)](#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-) | Создаёт узлы ресурсов LFX2. |
| [getAlignWithLayer()](#getAlignWithLayer--) | Получает или задает значение, указывающее, есть ли [link with layer]. |
| [getAngle()](#getAngle--) | Получает или задает угол. |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Получает или задаёт цвет. |
| [getCompressionModeOnSave_internalized()](#getCompressionModeOnSave-internalized--) |  |
| [getFillType()](#getFillType--) | Тип заполнения |
| [getHorizontalOffset()](#getHorizontalOffset--) | Получает или задает горизонтальное смещение. |
| [getLinked()](#getLinked--) | Получает или задает значение, указывающее, связан ли этот [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings). |
| [getPatternData()](#getPatternData--) | Получает или задает данные шаблона. |
| [getPatternHeight()](#getPatternHeight--) | Получает или задает высоту шаблона. |
| [getPatternId()](#getPatternId--) | Получает или задает идентификатор шаблона. |
| [getPatternName()](#getPatternName--) | Получает или задает имя шаблона. |
| [getPatternWidth()](#getPatternWidth--) | Получает или задает ширину шаблона. |
| [getPhase_internalized()](#getPhase-internalized--) | Получает или задает фазу. |
| [getPointType()](#getPointType--) | Получает или задает тип точки. |
| [getScale()](#getScale--) | Получает или задает масштаб. |
| [getVerticalOffset()](#getVerticalOffset--) | Получает или задает вертикальное смещение. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [raiseValueChanged_internalized()](#raiseValueChanged-internalized--) | Вызывает событие изменения значения. |
| [setAlignWithLayer(boolean value)](#setAlignWithLayer-boolean-) | Получает или задает значение, указывающее, есть ли [link with layer]. |
| [setAngle(double value)](#setAngle-double-) | Получает или задает угол. |
| [setColor(Color value)](#setColor-com.aspose.psd.Color-) | Получает или задаёт цвет. |
| [setHorizontalOffset(int value)](#setHorizontalOffset-int-) | Получает или задает горизонтальное смещение. |
| [setLinked(boolean value)](#setLinked-boolean-) | Получает или задает значение, указывающее, связан ли этот [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings). |
| [setPatternData(int[] value)](#setPatternData-int---) | Получает или задает данные шаблона. |
| [setPatternData_internalized(int[] patternData, byte compressionModeOnSave)](#setPatternData-internalized-int---byte-) | Устанавливает буфер пикселей pattern\u2019s и режим сжатия, используемый при сохранении. |
| [setPatternHeight(int value)](#setPatternHeight-int-) | Получает или задает высоту шаблона. |
| [setPatternId(String value)](#setPatternId-java.lang.String-) | Получает или задает идентификатор шаблона. |
| [setPatternName(String value)](#setPatternName-java.lang.String-) | Получает или задает имя шаблона. |
| [setPatternWidth(int value)](#setPatternWidth-int-) | Получает или задает ширину шаблона. |
| [setPhase_internalized(OffsetEntity value)](#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-) | Получает или задает фазу. |
| [setPointType(String value)](#setPointType-java.lang.String-) | Получает или задает тип точки. |
| [setScale(double value)](#setScale-double-) | Получает или задает масштаб. |
| [setVerticalOffset(int value)](#setVerticalOffset-int-) | Получает или задает вертикальное смещение. |
| [setupDefaultPatternData_internalized(PatternFillSettings settings)](#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-) | Настраивает данные шаблона по умолчанию в экземпляре [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings). |
| [toString()](#toString--) |  |
| [updatePatternData_internalized(PattResourceData pattResourceData)](#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-) | Обновляет свойства шаблона из экземпляра [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata). |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PatternFillSettings() {#PatternFillSettings--}
```
public PatternFillSettings()
```


Инициализирует новый экземпляр класса [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings).

### ValueChanged_internalized {#ValueChanged-internalized}
```
public final Event<System.EventHandler> ValueChanged_internalized
```


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
### generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset) {#generateLfx2ResourceNodes-java.lang.String-com.aspose.psd.Color-java.lang.String-java.lang.String-double-boolean-com.aspose.psd.PointF-}
```
public static System.Collections.Generic.IGenericEnumerable<OSTypeStructure> generateLfx2ResourceNodes(String pointType, Color color, String patternName, String identifier, double scale, boolean linked, PointF offset)
```


Создаёт узлы ресурсов LFX2.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pointType | java.lang.String | Тип точки. |
| color | [Color](../../com.aspose.psd/color) | Цвет. |
| patternName | java.lang.String | Имя шаблона. |
| идентификатор | java.lang.String | Идентификатор. |
| scale | double | Масштаб. |
| связан | boolean | если установлено значение  true  [linked]. |
| offset | [PointF](../../com.aspose.psd/pointf) | Смещение. |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure> - Список [OSTypeStructure](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure)
### getAlignWithLayer() {#getAlignWithLayer--}
```
public final boolean getAlignWithLayer()
```


Получает или задает значение, указывающее, есть ли [link with layer].

Значение:  true  если [link with layer]; иначе,  false .

**Returns:**
boolean
### getAngle() {#getAngle--}
```
public final double getAngle()
```


Получает или задает угол.

Значение: Угол.

**Returns:**
double
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public final Color getColor()
```


Получает или задаёт цвет.

Значение: Цвет.

**Returns:**
[Color](../../com.aspose.psd/color)
### getCompressionModeOnSave_internalized() {#getCompressionModeOnSave-internalized--}
```
public final byte getCompressionModeOnSave_internalized()
```




**Returns:**
byte
### getFillType() {#getFillType--}
```
public int getFillType()
```


Тип заполнения

**Returns:**
int
### getHorizontalOffset() {#getHorizontalOffset--}
```
public final int getHorizontalOffset()
```


Получает или задает горизонтальное смещение.

Значение: Горизонтальное смещение.

**Returns:**
int
### getLinked() {#getLinked--}
```
public final boolean getLinked()
```


Получает или задает значение, указывающее, связан ли этот [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings).

Значение:  true  если связано; иначе,  false .

**Returns:**
boolean
### getPatternData() {#getPatternData--}
```
public final int[] getPatternData()
```


Получает или задает данные шаблона.

Значение: Данные шаблона.

**Returns:**
int[]
### getPatternHeight() {#getPatternHeight--}
```
public final int getPatternHeight()
```


Получает или задает высоту шаблона.

Значение: Высота шаблона.

**Returns:**
int
### getPatternId() {#getPatternId--}
```
public final String getPatternId()
```


Получает или задает идентификатор шаблона.

Значение: Идентификатор шаблона.

**Returns:**
java.lang.String
### getPatternName() {#getPatternName--}
```
public final String getPatternName()
```


Получает или задает имя шаблона.

Значение: Имя шаблона.

**Returns:**
java.lang.String
### getPatternWidth() {#getPatternWidth--}
```
public final int getPatternWidth()
```


Получает или задает ширину шаблона.

Значение: Ширина шаблона.

**Returns:**
int
### getPhase_internalized() {#getPhase-internalized--}
```
public final OffsetEntity getPhase_internalized()
```


Получает или задает фазу.

Значение: Фаза.

**Returns:**
com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity
### getPointType() {#getPointType--}
```
public final String getPointType()
```


Получает или задает тип точки.

Значение: Тип точки.

**Returns:**
java.lang.String
### getScale() {#getScale--}
```
public final double getScale()
```


Получает или задает масштаб.

Значение: Масштаб.

**Returns:**
double
### getVerticalOffset() {#getVerticalOffset--}
```
public final int getVerticalOffset()
```


Получает или задает вертикальное смещение.

Значение: Вертикальное смещение.

**Returns:**
int
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




### raiseValueChanged_internalized() {#raiseValueChanged-internalized--}
```
public final void raiseValueChanged_internalized()
```


Вызывает событие изменения значения.

### setAlignWithLayer(boolean value) {#setAlignWithLayer-boolean-}
```
public final void setAlignWithLayer(boolean value)
```


Получает или задает значение, указывающее, есть ли [link with layer].

Значение:  true  если [link with layer]; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


Получает или задает угол.

Значение: Угол.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setColor(Color value) {#setColor-com.aspose.psd.Color-}
```
public final void setColor(Color value)
```


Получает или задаёт цвет.

Значение: Цвет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.psd/color) |  |

### setHorizontalOffset(int value) {#setHorizontalOffset-int-}
```
public final void setHorizontalOffset(int value)
```


Получает или задает горизонтальное смещение.

Значение: Горизонтальное смещение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setLinked(boolean value) {#setLinked-boolean-}
```
public final void setLinked(boolean value)
```


Получает или задает значение, указывающее, связан ли этот [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings).

Значение:  true  если связано; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setPatternData(int[] value) {#setPatternData-int---}
```
public final void setPatternData(int[] value)
```


Получает или задает данные шаблона.

Значение: Данные шаблона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int[] |  |

### setPatternData_internalized(int[] patternData, byte compressionModeOnSave) {#setPatternData-internalized-int---byte-}
```
public final void setPatternData_internalized(int[] patternData, byte compressionModeOnSave)
```


Устанавливает буфер пикселей pattern\u2019s и режим сжатия, используемый при сохранении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| patternData | int[] | 32-битные пиксели в  0xAARRGGBB . |
| compressionModeOnSave | byte | Режим сжатия, используемый для определения сжатия данных шаблона при сохранении файла psd. |

### setPatternHeight(int value) {#setPatternHeight-int-}
```
public final void setPatternHeight(int value)
```


Получает или задает высоту шаблона.

Значение: Высота шаблона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPatternId(String value) {#setPatternId-java.lang.String-}
```
public final void setPatternId(String value)
```


Получает или задает идентификатор шаблона.

Значение: Идентификатор шаблона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setPatternName(String value) {#setPatternName-java.lang.String-}
```
public final void setPatternName(String value)
```


Получает или задает имя шаблона.

Значение: Имя шаблона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setPatternWidth(int value) {#setPatternWidth-int-}
```
public final void setPatternWidth(int value)
```


Получает или задает ширину шаблона.

Значение: Ширина шаблона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPhase_internalized(OffsetEntity value) {#setPhase-internalized-com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity-}
```
public final void setPhase_internalized(OffsetEntity value)
```


Получает или задает фазу.

Значение: Фаза.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.internal.fileformats.psd.layers.layerresources.lfx2resources.OffsetEntity |  |

### setPointType(String value) {#setPointType-java.lang.String-}
```
public final void setPointType(String value)
```


Получает или задает тип точки.

Значение: Тип точки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setScale(double value) {#setScale-double-}
```
public final void setScale(double value)
```


Получает или задает масштаб.

Значение: Масштаб.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setVerticalOffset(int value) {#setVerticalOffset-int-}
```
public final void setVerticalOffset(int value)
```


Получает или задает вертикальное смещение.

Значение: Вертикальное смещение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setupDefaultPatternData_internalized(PatternFillSettings settings) {#setupDefaultPatternData-internalized-com.aspose.psd.fileformats.psd.layers.fillsettings.PatternFillSettings-}
```
public static void setupDefaultPatternData_internalized(PatternFillSettings settings)
```


Настраивает данные шаблона по умолчанию в экземпляре [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| settings | [PatternFillSettings](../../com.aspose.psd.fileformats.psd.layers.fillsettings/patternfillsettings) | Настройки заполнения шаблоном. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updatePatternData_internalized(PattResourceData pattResourceData) {#updatePatternData-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.PattResourceData-}
```
public final void updatePatternData_internalized(PattResourceData pattResourceData)
```


Обновляет свойства шаблона из экземпляра [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pattResourceData | [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) | Экземпляр [PattResourceData](../../com.aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata) с данными шаблона. |

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

