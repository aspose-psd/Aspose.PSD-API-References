---
title: "WarpSettings"
second_title: "Aspose.PSD for Java API Справочник"
description: "Параметры слоя с искажением"
type: docs
weight: 12
url: /ru/java/com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings/
---

**Inheritance:**
java.lang.Object
```
public class WarpSettings
```

Параметры слоя с искажением
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-) | Инициализирует новый экземпляр класса [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
| [WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)](#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-) | Инициализирует новый экземпляр класса [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
| [WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-) | Инициализирует новый экземпляр класса [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
| [WarpSettings(PlacedResource placedResource)](#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Инициализирует новый экземпляр класса [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings). |
## Поля

| Поле | Описание |
| --- | --- |
| [DefaultRenderQuality_internalized](#DefaultRenderQuality-internalized) | Значение по умолчанию свойства ProcessingArea |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBounds()](#getBounds--) | Получает или задает границы изображения искажения |
| [getClass()](#getClass--) |  |
| [getGridSize()](#getGridSize--) | Получает или задает размер сетки искажения. |
| [getMeshLinesSize_internalized()](#getMeshLinesSize-internalized--) | Получает или задает размер линий сетки. |
| [getMeshPoints()](#getMeshPoints--) | Точки сетки Photoshop |
| [getRenderQuality()](#getRenderQuality--) | Получает или задает значение качества рендеринга искажения — между скоростью и качеством. |
| [getRotate()](#getRotate--) | Получает или задает значение вращения |
| [getStyle()](#getStyle--) | Получает или задает стиль искажения |
| [getValue()](#getValue--) | Получает или задает значение искажения |
| [hashCode()](#hashCode--) |  |
| [isDefaultMeshPoints_internalized()](#isDefaultMeshPoints-internalized--) | Получает или задает пользовательские изменения в MeshPoints |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Получает или задает границы изображения искажения |
| [setGridSize(Size value)](#setGridSize-com.aspose.psd.Size-) | Получает или задает размер сетки искажения. |
| [setMeshLinesSize_internalized(Size value)](#setMeshLinesSize-internalized-com.aspose.psd.Size-) | Получает или задает размер линий сетки. |
| [setMeshPoints(PointF[] value)](#setMeshPoints-com.aspose.psd.PointF---) | Точки сетки Photoshop |
| [setMeshPoints_internalized(PlacedResource placedResource)](#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Возвращает точку сетки из векторных ресурсов |
| [setRenderQuality(int value)](#setRenderQuality-int-) | Получает или задает значение качества рендеринга искажения — между скоростью и качеством. |
| [setRotate(int value)](#setRotate-int-) | Получает или задает значение вращения |
| [setStyle(int value)](#setStyle-int-) | Получает или задает стиль искажения |
| [setValue(double value)](#setValue-double-) | Получает или задает значение искажения |
| [setWarpToResource_internalized(OSTypeStructure[] warpItems)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Сохраняет эти параметры искажения в PlacedResource |
| [setWarpToResource_internalized(PlacedResource placedResource)](#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-) | Сохраняет эти параметры искажения в PlacedResource |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WarpSettings(PointF[] meshPoints, Rectangle bounds) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds)
```


Инициализирует новый экземпляр класса [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Точки сетки искажения. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Границы изображения искажения |

### WarpSettings(PointF[] meshPoints, Rectangle bounds, int style) {#WarpSettings-com.aspose.psd.PointF---com.aspose.psd.Rectangle-int-}
```
public WarpSettings(PointF[] meshPoints, Rectangle bounds, int style)
```


Инициализирует новый экземпляр класса [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| meshPoints | [PointF\[\]](../../com.aspose.psd/pointf) | Точки сетки искажения. |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Границы изображения искажения |
| style | int | Стиль искажения. |

### WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---com.aspose.psd.Rectangle-}
```
public WarpSettings(OSTypeStructure[] warpItems, Rectangle bounds)
```


Инициализирует новый экземпляр класса [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Элементы PS с настройками искажения |
| bounds | [Rectangle](../../com.aspose.psd/rectangle) | Границы изображения искажения |

### WarpSettings(PlacedResource placedResource) {#WarpSettings-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public WarpSettings(PlacedResource placedResource)
```


Инициализирует новый экземпляр класса [WarpSettings](../../com.aspose.psd.fileformats.psd.layers.warp.structs/warpsettings).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Ресурс с настройками искажения |

### DefaultRenderQuality_internalized {#DefaultRenderQuality-internalized}
```
public static final int DefaultRenderQuality_internalized
```


Значение по умолчанию свойства ProcessingArea

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
### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Получает или задает границы изображения искажения

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getGridSize() {#getGridSize--}
```
public final Size getGridSize()
```


Получает или задает размер сетки искажения. По умолчанию 1.

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshLinesSize_internalized() {#getMeshLinesSize-internalized--}
```
public final Size getMeshLinesSize_internalized()
```


Получает или задает размер линий сетки. GridSize — это определение из PS, которое клиент может выбрать. Каждый GridSize имеет 4 линии сетки. Если количество GridSize больше 1, то последняя линия сетки первого Grid и первая линия второго Grid образуют одну линию сетки.

**Returns:**
[Size](../../com.aspose.psd/size)
### getMeshPoints() {#getMeshPoints--}
```
public final PointF[] getMeshPoints()
```


Точки сетки Photoshop

**Returns:**
com.aspose.psd.PointF[]
### getRenderQuality() {#getRenderQuality--}
```
public final int getRenderQuality()
```


Получает или задает значение качества рендеринга искажения — между скоростью и качеством.

**Returns:**
int
### getRotate() {#getRotate--}
```
public final int getRotate()
```


Получает или задает значение вращения

**Returns:**
int
### getStyle() {#getStyle--}
```
public final int getStyle()
```


Получает или задает стиль искажения

**Returns:**
int
### getValue() {#getValue--}
```
public final double getValue()
```


Получает или задает значение искажения

**Returns:**
double
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isDefaultMeshPoints_internalized() {#isDefaultMeshPoints-internalized--}
```
public final boolean isDefaultMeshPoints_internalized()
```


Получает или задает пользовательские изменения в MeshPoints

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




### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Получает или задает границы изображения искажения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setGridSize(Size value) {#setGridSize-com.aspose.psd.Size-}
```
public final void setGridSize(Size value)
```


Получает или задает размер сетки искажения. По умолчанию 1.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshLinesSize_internalized(Size value) {#setMeshLinesSize-internalized-com.aspose.psd.Size-}
```
public final void setMeshLinesSize_internalized(Size value)
```


Получает или задает размер линий сетки. GridSize — это определение из PS, которое клиент может выбрать. Каждый GridSize имеет 4 линии сетки. Если количество GridSize больше 1, то последняя линия сетки первого Grid и первая линия второго Grid образуют одну линию сетки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Size](../../com.aspose.psd/size) |  |

### setMeshPoints(PointF[] value) {#setMeshPoints-com.aspose.psd.PointF---}
```
public final void setMeshPoints(PointF[] value)
```


Точки сетки Photoshop

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.psd/pointf) |  |

### setMeshPoints_internalized(PlacedResource placedResource) {#setMeshPoints-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setMeshPoints_internalized(PlacedResource placedResource)
```


Возвращает точку сетки из векторных ресурсов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Ресурс с настройками искажения |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - The PlacedResource with set mesh points
### setRenderQuality(int value) {#setRenderQuality-int-}
```
public final void setRenderQuality(int value)
```


Получает или задает значение качества рендеринга искажения — между скоростью и качеством.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setRotate(int value) {#setRotate-int-}
```
public final void setRotate(int value)
```


Получает или задает значение вращения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setStyle(int value) {#setStyle-int-}
```
public final void setStyle(int value)
```


Получает или задает стиль искажения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setValue(double value) {#setValue-double-}
```
public final void setValue(double value)
```


Получает или задает значение искажения

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setWarpToResource_internalized(OSTypeStructure[] warpItems) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public final OSTypeStructure[] setWarpToResource_internalized(OSTypeStructure[] warpItems)
```


Сохраняет эти параметры искажения в PlacedResource

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| warpItems | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) | Ресурс с настройками искажения |

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[] - Ресурс с параметрами искажения из этого WarpParams
### setWarpToResource_internalized(PlacedResource placedResource) {#setWarpToResource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-}
```
public final PlacedResource setWarpToResource_internalized(PlacedResource placedResource)
```


Сохраняет эти параметры искажения в PlacedResource

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Ресурс с настройками искажения |

**Returns:**
[PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) - Resource with warp params from this WarpParams
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

