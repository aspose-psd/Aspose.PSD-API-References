---
title: "IPlacedLayerResource"
second_title: "Aspose.PSD for Java API Справочник"
description: "Определяет интерфейс IPlacedLayerResource, который содержит информацию о размещённом слое в файле PSD."
type: docs
weight: 17
url: /ru/java/com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/iplacedlayerresource/
---
```
public interface IPlacedLayerResource
```

Определяет интерфейс IPlacedLayerResource, который содержит информацию о размещённом слое в файле PSD. Это разметочный интерфейс, используемый для обозначения ресурсов PlLd, Sold и Sole в изображениях Adobe\ufffd Photoshop\ufffd. Используется для поддержки слоёв смарт‑объектов в изображениях Adobe\ufffd Photoshop\ufffd.
## Методы

| Метод | Описание |
| --- | --- |
| [getAntiAliasPolicy()](#getAntiAliasPolicy--) | Получает или задает политику сглаживания размещённого слоя в изображении PSD. |
| [getBottom()](#getBottom--) | Получает или задает положение снизу размещённого слоя в изображении PSD. |
| [getBounds()](#getBounds--) | Получает или задает границы размещённого слоя в файле PSD. |
| [getHorizontalMeshPointUnit()](#getHorizontalMeshPointUnit--) | Получает или задает единицу измерения горизонтальных точек сетки. |
| [getHorizontalMeshPoints()](#getHorizontalMeshPoints--) | Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD. |
| [getItems()](#getItems--) | Получает или задает элементы искажения. |
| [getLeft()](#getLeft--) | Получает или задает положение слева размещённого слоя в файле PSD. |
| [getPageNumber()](#getPageNumber--) | Получает или задает номер страницы размещённого слоя в файле PSD. |
| [getPerspective()](#getPerspective--) | Получает или задает значение перспективы размещённого слоя в файле PSD. |
| [getPerspectiveOther()](#getPerspectiveOther--) | Получает или задает другое значение перспективы размещённого слоя в файле PSD. |
| [getPlacedLayerType()](#getPlacedLayerType--) | Получает или задает тип размещённого слоя в файле PSD. |
| [getRight()](#getRight--) | Получает или задает положение справа размещённого слоя в файле PSD. |
| [getTop()](#getTop--) | Получает или задает положение сверху размещённого слоя в изображении PSD. |
| [getTotalPages()](#getTotalPages--) | Получает или задает общее количество страниц размещённого слоя в файле PSD. |
| [getTransformMatrix()](#getTransformMatrix--) | Получает или задает матрицу преобразования размещённого слоя в файле PSD. |
| [getUOrder()](#getUOrder--) | Получает или задает значение порядка U размещённого слоя в файле PSD. |
| [getUniqueId()](#getUniqueId--) | Получает или задаёт глобальный уникальный идентификатор размещённого слоя смарт‑объекта в изображении PSD. |
| [getUniqueId_internalized()](#getUniqueId-internalized--) |  |
| [getVOrder()](#getVOrder--) | Получает или задает значение порядка V размещённого слоя в файле PSD. |
| [getValue()](#getValue--) | Получает или задает значение искажения размещённого слоя в изображении PSD. |
| [getVersion()](#getVersion--) | Получает версию размещённого слоя в файле PSD, обычно 3‑5. |
| [getVerticalMeshPointUnit()](#getVerticalMeshPointUnit--) | Получает или задает единицу измерения вертикальных точек сетки. |
| [getVerticalMeshPoints()](#getVerticalMeshPoints--) | Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD. |
| [isCustom()](#isCustom--) | Получает или задает значение, указывающее, является ли стиль warp данного экземпляра пользовательским. |
| [setAntiAliasPolicy(int value)](#setAntiAliasPolicy-int-) | Получает или задает политику сглаживания размещённого слоя в изображении PSD. |
| [setBottom(double value)](#setBottom-double-) | Получает или задает положение снизу размещённого слоя в изображении PSD. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.psd.Rectangle-) | Получает или задает границы размещённого слоя в файле PSD. |
| [setCustom(boolean value)](#setCustom-boolean-) | Получает или задает значение, указывающее, является ли стиль warp данного экземпляра пользовательским. |
| [setHorizontalMeshPointUnit(int value)](#setHorizontalMeshPointUnit-int-) | Получает или задает единицу измерения горизонтальных точек сетки. |
| [setHorizontalMeshPoints(double[] value)](#setHorizontalMeshPoints-double---) | Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD. |
| [setItems(OSTypeStructure[] value)](#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---) | Получает или задает элементы искажения. |
| [setLeft(double value)](#setLeft-double-) | Получает или задает положение слева размещённого слоя в файле PSD. |
| [setPageNumber(int value)](#setPageNumber-int-) | Получает или задает номер страницы размещённого слоя в файле PSD. |
| [setPerspective(double value)](#setPerspective-double-) | Получает или задает значение перспективы размещённого слоя в файле PSD. |
| [setPerspectiveOther(double value)](#setPerspectiveOther-double-) | Получает или задает другое значение перспективы размещённого слоя в файле PSD. |
| [setPlacedLayerType(int value)](#setPlacedLayerType-int-) | Получает или задает тип размещённого слоя в файле PSD. |
| [setRight(double value)](#setRight-double-) | Получает или задает положение справа размещённого слоя в файле PSD. |
| [setTop(double value)](#setTop-double-) | Получает или задает положение сверху размещённого слоя в изображении PSD. |
| [setTotalPages(int value)](#setTotalPages-int-) | Получает или задает общее количество страниц размещённого слоя в файле PSD. |
| [setTransformMatrix(double[] value)](#setTransformMatrix-double---) | Получает или задает матрицу преобразования размещённого слоя в файле PSD. |
| [setUOrder(int value)](#setUOrder-int-) | Получает или задает значение порядка U размещённого слоя в файле PSD. |
| [setUniqueId(UUID value)](#setUniqueId-java.util.UUID-) | Получает или задаёт глобальный уникальный идентификатор размещённого слоя смарт‑объекта в изображении PSD. |
| [setUniqueId_internalized(System.Guid value)](#setUniqueId-internalized-com.aspose.ms.System.Guid-) |  |
| [setVOrder(int value)](#setVOrder-int-) | Получает или задает значение порядка V размещённого слоя в файле PSD. |
| [setValue(double value)](#setValue-double-) | Получает или задает значение искажения размещённого слоя в изображении PSD. |
| [setVerticalMeshPointUnit(int value)](#setVerticalMeshPointUnit-int-) | Получает или задает единицу измерения вертикальных точек сетки. |
| [setVerticalMeshPoints(double[] value)](#setVerticalMeshPoints-double---) | Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD. |
### getAntiAliasPolicy() {#getAntiAliasPolicy--}
```
public abstract int getAntiAliasPolicy()
```


Получает или задает политику сглаживания размещённого слоя в изображении PSD.

Значение: Политика сглаживания размещённого слоя.

**Returns:**
int
### getBottom() {#getBottom--}
```
public abstract double getBottom()
```


Получает или задает положение снизу размещённого слоя в изображении PSD.

Значение: Нижнее расположение размещённого слоя.

**Returns:**
double
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


Получает или задает границы размещённого слоя в файле PSD.

Значение: Границы размещённого слоя.

**Returns:**
[Rectangle](../../com.aspose.psd/rectangle)
### getHorizontalMeshPointUnit() {#getHorizontalMeshPointUnit--}
```
public abstract int getHorizontalMeshPointUnit()
```


Получает или задает единицу измерения горизонтальных точек сетки.

Значение: Единица измерения горизонтальных точек сетки.

**Returns:**
int
### getHorizontalMeshPoints() {#getHorizontalMeshPoints--}
```
public abstract double[] getHorizontalMeshPoints()
```


Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD.

Значение: Горизонтальные точки сетки размещённого слоя.

**Returns:**
double[]
### getItems() {#getItems--}
```
public abstract OSTypeStructure[] getItems()
```


Получает или задает элементы искажения.

Значение: Элементы искажения.

**Returns:**
com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure[]
### getLeft() {#getLeft--}
```
public abstract double getLeft()
```


Получает или задает положение слева размещённого слоя в файле PSD.

Значение: Левая позиция размещённого слоя.

**Returns:**
double
### getPageNumber() {#getPageNumber--}
```
public abstract int getPageNumber()
```


Получает или задает номер страницы размещённого слоя в файле PSD.

Значение: Номер страницы размещённого слоя.

**Returns:**
int
### getPerspective() {#getPerspective--}
```
public abstract double getPerspective()
```


Получает или задает значение перспективы размещённого слоя в файле PSD.

Значение: Значение перспективы размещённого слоя.

**Returns:**
double
### getPerspectiveOther() {#getPerspectiveOther--}
```
public abstract double getPerspectiveOther()
```


Получает или задает другое значение перспективы размещённого слоя в файле PSD.

Значение: Другое значение перспективы размещённого слоя.

**Returns:**
double
### getPlacedLayerType() {#getPlacedLayerType--}
```
public abstract int getPlacedLayerType()
```


Получает или задает тип размещённого слоя в файле PSD.

Значение: Тип размещённого слоя.

**Returns:**
int
### getRight() {#getRight--}
```
public abstract double getRight()
```


Получает или задает положение справа размещённого слоя в файле PSD.

Значение: Правая позиция размещённого слоя.

**Returns:**
double
### getTop() {#getTop--}
```
public abstract double getTop()
```


Получает или задает положение сверху размещённого слоя в изображении PSD.

Значение: Верхняя позиция размещённого слоя.

**Returns:**
double
### getTotalPages() {#getTotalPages--}
```
public abstract int getTotalPages()
```


Получает или задает общее количество страниц размещённого слоя в файле PSD.

Значение: Общее количество страниц размещённого слоя.

**Returns:**
int
### getTransformMatrix() {#getTransformMatrix--}
```
public abstract double[] getTransformMatrix()
```


Получает или задает матрицу преобразования размещённого слоя в файле PSD.

Значение: Матрица преобразования размещённого слоя.

**Returns:**
double[]
### getUOrder() {#getUOrder--}
```
public abstract int getUOrder()
```


Получает или задает значение порядка U размещённого слоя в файле PSD.

Значение: Значение порядка U размещённого слоя.

**Returns:**
int
### getUniqueId() {#getUniqueId--}
```
public abstract UUID getUniqueId()
```


Получает или задаёт глобальный уникальный идентификатор размещённого слоя смарт‑объекта в изображении PSD.

Значение: Уникальный идентификатор размещённого слоя.

**Returns:**
java.util.UUID
### getUniqueId_internalized() {#getUniqueId-internalized--}
```
public abstract System.Guid getUniqueId_internalized()
```




**Returns:**
com.aspose.ms.System.Guid
### getVOrder() {#getVOrder--}
```
public abstract int getVOrder()
```


Получает или задает значение порядка V размещённого слоя в файле PSD.

Значение: Значение порядка V размещённого слоя.

**Returns:**
int
### getValue() {#getValue--}
```
public abstract double getValue()
```


Получает или задает значение искажения размещённого слоя в изображении PSD.

Значение: Значение искажения размещённого слоя.

**Returns:**
double
### getVersion() {#getVersion--}
```
public abstract int getVersion()
```


Получает версию размещённого слоя в файле PSD, обычно 3‑5.

Значение: версия размещённого или смарт‑объекта слоя.

**Returns:**
int
### getVerticalMeshPointUnit() {#getVerticalMeshPointUnit--}
```
public abstract int getVerticalMeshPointUnit()
```


Получает или задает единицу измерения вертикальных точек сетки.

Значение: Единица измерения вертикальных точек сетки.

**Returns:**
int
### getVerticalMeshPoints() {#getVerticalMeshPoints--}
```
public abstract double[] getVerticalMeshPoints()
```


Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD.

Значение: Горизонтальные точки сетки размещённого слоя.

**Returns:**
double[]
### isCustom() {#isCustom--}
```
public abstract boolean isCustom()
```


Получает или задает значение, указывающее, является ли стиль искажения этого экземпляра пользовательским. Если true, содержит точки сетки. Если установить false, удаляет точки сетки.

Значение:  true  если ресурс размещённого или смарт‑объекта слоя имеет пользовательский стиль; в противном случае,  false .

**Returns:**
boolean
### setAntiAliasPolicy(int value) {#setAntiAliasPolicy-int-}
```
public abstract void setAntiAliasPolicy(int value)
```


Получает или задает политику сглаживания размещённого слоя в изображении PSD.

Значение: Политика сглаживания размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setBottom(double value) {#setBottom-double-}
```
public abstract void setBottom(double value)
```


Получает или задает положение снизу размещённого слоя в изображении PSD.

Значение: Нижнее расположение размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setBounds(Rectangle value) {#setBounds-com.aspose.psd.Rectangle-}
```
public abstract void setBounds(Rectangle value)
```


Получает или задает границы размещённого слоя в файле PSD.

Значение: Границы размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.psd/rectangle) |  |

### setCustom(boolean value) {#setCustom-boolean-}
```
public abstract void setCustom(boolean value)
```


Получает или задает значение, указывающее, является ли стиль искажения этого экземпляра пользовательским. Если true, содержит точки сетки. Если установить false, удаляет точки сетки.

Значение:  true  если ресурс размещённого или смарт‑объекта слоя имеет пользовательский стиль; в противном случае,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setHorizontalMeshPointUnit(int value) {#setHorizontalMeshPointUnit-int-}
```
public abstract void setHorizontalMeshPointUnit(int value)
```


Получает или задает единицу измерения горизонтальных точек сетки.

Значение: Единица измерения горизонтальных точек сетки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setHorizontalMeshPoints(double[] value) {#setHorizontalMeshPoints-double---}
```
public abstract void setHorizontalMeshPoints(double[] value)
```


Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD.

Значение: Горизонтальные точки сетки размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double[] |  |

### setItems(OSTypeStructure[] value) {#setItems-com.aspose.psd.fileformats.psd.layers.layerresources.OSTypeStructure---}
```
public abstract void setItems(OSTypeStructure[] value)
```


Получает или задает элементы искажения.

Значение: Элементы искажения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [OSTypeStructure\[\]](../../com.aspose.psd.fileformats.psd.layers.layerresources/ostypestructure) |  |

### setLeft(double value) {#setLeft-double-}
```
public abstract void setLeft(double value)
```


Получает или задает положение слева размещённого слоя в файле PSD.

Значение: Левая позиция размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setPageNumber(int value) {#setPageNumber-int-}
```
public abstract void setPageNumber(int value)
```


Получает или задает номер страницы размещённого слоя в файле PSD.

Значение: Номер страницы размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPerspective(double value) {#setPerspective-double-}
```
public abstract void setPerspective(double value)
```


Получает или задает значение перспективы размещённого слоя в файле PSD.

Значение: Значение перспективы размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setPerspectiveOther(double value) {#setPerspectiveOther-double-}
```
public abstract void setPerspectiveOther(double value)
```


Получает или задает другое значение перспективы размещённого слоя в файле PSD.

Значение: Другое значение перспективы размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setPlacedLayerType(int value) {#setPlacedLayerType-int-}
```
public abstract void setPlacedLayerType(int value)
```


Получает или задает тип размещённого слоя в файле PSD.

Значение: Тип размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setRight(double value) {#setRight-double-}
```
public abstract void setRight(double value)
```


Получает или задает положение справа размещённого слоя в файле PSD.

Значение: Правая позиция размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setTop(double value) {#setTop-double-}
```
public abstract void setTop(double value)
```


Получает или задает положение сверху размещённого слоя в изображении PSD.

Значение: Верхняя позиция размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setTotalPages(int value) {#setTotalPages-int-}
```
public abstract void setTotalPages(int value)
```


Получает или задает общее количество страниц размещённого слоя в файле PSD.

Значение: Общее количество страниц размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setTransformMatrix(double[] value) {#setTransformMatrix-double---}
```
public abstract void setTransformMatrix(double[] value)
```


Получает или задает матрицу преобразования размещённого слоя в файле PSD.

Значение: Матрица преобразования размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double[] |  |

### setUOrder(int value) {#setUOrder-int-}
```
public abstract void setUOrder(int value)
```


Получает или задает значение порядка U размещённого слоя в файле PSD.

Значение: Значение порядка U размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setUniqueId(UUID value) {#setUniqueId-java.util.UUID-}
```
public abstract void setUniqueId(UUID value)
```


Получает или задаёт глобальный уникальный идентификатор размещённого слоя смарт‑объекта в изображении PSD.

Значение: Уникальный идентификатор размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.util.UUID |  |

### setUniqueId_internalized(System.Guid value) {#setUniqueId-internalized-com.aspose.ms.System.Guid-}
```
public abstract void setUniqueId_internalized(System.Guid value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | com.aspose.ms.System.Guid |  |

### setVOrder(int value) {#setVOrder-int-}
```
public abstract void setVOrder(int value)
```


Получает или задает значение порядка V размещённого слоя в файле PSD.

Значение: Значение порядка V размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setValue(double value) {#setValue-double-}
```
public abstract void setValue(double value)
```


Получает или задает значение искажения размещённого слоя в изображении PSD.

Значение: Значение искажения размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### setVerticalMeshPointUnit(int value) {#setVerticalMeshPointUnit-int-}
```
public abstract void setVerticalMeshPointUnit(int value)
```


Получает или задает единицу измерения вертикальных точек сетки.

Значение: Единица измерения вертикальных точек сетки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setVerticalMeshPoints(double[] value) {#setVerticalMeshPoints-double---}
```
public abstract void setVerticalMeshPoints(double[] value)
```


Получает или задает горизонтальные точки сетки размещённого слоя в файле PSD.

Значение: Горизонтальные точки сетки размещённого слоя.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double[] |  |

