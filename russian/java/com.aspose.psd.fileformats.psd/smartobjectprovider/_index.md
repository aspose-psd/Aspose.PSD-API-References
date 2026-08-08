---
title: "SmartObjectProvider"
second_title: "Aspose.PSD for Java API Справочник"
description: "Определяет поставщик смарт‑объектов, который обеспечивает получение/установку источников данных из глобальных связанных ресурсов файла PSD и их содержимого."
type: docs
weight: 17
url: /ru/java/com.aspose.psd.fileformats.psd/smartobjectprovider/
---

**Inheritance:**
java.lang.Object
```
public class SmartObjectProvider
```

Определяет поставщик смарт‑объектов, который обеспечивает получение/установку источников данных из глобальных связанных ресурсов файла PSD и их содержимого.
## Методы

| Метод | Описание |
| --- | --- |
| [convertToSmartObject(Layer[] layers)](#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---) | Преобразует слои в встроенный смарт‑объект. |
| [convertToSmartObject(int[] layerNumbers)](#convertToSmartObject-int...-) | Преобразует слои в встроенный смарт‑объект. |
| [create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)](#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-) | Инициализирует новый экземпляр класса [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider). |
| [embedAllLinked()](#embedAllLinked--) | Встраивает все связанные смарт‑объекты в изображение. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getContentType_internalized(System.Guid uniqueId)](#getContentType-internalized-com.aspose.ms.System.Guid-) | Получает тип содержимого слоя смарт‑объекта. |
| [getContents_internalized(System.Guid uniqueId)](#getContents-internalized-com.aspose.ms.System.Guid-) | Получает содержимое встроенного или связанного файла. |
| [getDataSource_internalized(System.Guid uniqueId)](#getDataSource-internalized-com.aspose.ms.System.Guid-) | Получает источник данных ссылки по уникальному идентификатору. |
| [hashCode()](#hashCode--) |  |
| [loadContents_internalized(System.Guid uniqueId, LoadOptions options)](#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-) | Загружает содержимое. |
| [newSmartObjectViaCopy(SmartObjectLayer sourceLayer)](#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-) | Создаёт новый слой смарт‑объекта, копируя исходный. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)](#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--) | Удаляет источники данных из встроенных и внешних ресурсов, которых нет в предоставленном списке действительных GUID. |
| [replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)](#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---) | Заменяет источник данных в глобальных ресурсах предоставленными данными для встраивания. |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-) |  |
| [replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)](#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-) | Заменяет источник данных в глобальном ресурсе LinkResource вновь созданным источником данных из внешнего файла. |
| [setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)](#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-) | Устанавливает содержимое встроенного или внешнего файла. |
| [setDataSource(LinkDataSource dataSource)](#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-) | Устанавливает (заменяет или добавляет) источник данных ссылки в глобальном ресурсе ссылок. |
| [toString()](#toString--) |  |
| [updateAllModifiedContent()](#updateAllModifiedContent--) | Обновляет содержимое всех изменённых смарт‑объектов в изображении. |
| [updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)](#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-) | Обновляет все слои смарт‑объектов в контейнере, у которых UniqueId совпадает со старым GUID. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### convertToSmartObject(Layer[] layers) {#convertToSmartObject-com.aspose.psd.fileformats.psd.layers.Layer---}
```
public final SmartObjectLayer convertToSmartObject(Layer[] layers)
```


Преобразует слои в встроенный смарт‑объект.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layers | [Layer\[\]](../../com.aspose.psd.fileformats.psd.layers/layer) | Слои. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### convertToSmartObject(int[] layerNumbers) {#convertToSmartObject-int...-}
```
public final SmartObjectLayer convertToSmartObject(int[] layerNumbers)
```


Преобразует слои в встроенный смарт‑объект.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layerNumbers | int[] | Номера слоёв. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The created [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container) {#create-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LnkeResource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.Lnk2Resource-com.aspose.psd.fileformats.psd.PsdImage-}
```
public static SmartObjectProvider create_internalized(LnkeResource externalLinkResource, Lnk2Resource embeddedLinkResource, PsdImage container)
```


Инициализирует новый экземпляр класса [SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| externalLinkResource | [LnkeResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnkeresource) |  |
| embeddedLinkResource | [Lnk2Resource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lnk2resource) |  |
| container | [PsdImage](../../com.aspose.psd.fileformats.psd/psdimage) | Контейнер. |

**Returns:**
[SmartObjectProvider](../../com.aspose.psd.fileformats.psd/smartobjectprovider)
### embedAllLinked() {#embedAllLinked--}
```
public final void embedAllLinked()
```


Встраивает все связанные смарт‑объекты в изображение.

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
### getContentType_internalized(System.Guid uniqueId) {#getContentType-internalized-com.aspose.ms.System.Guid-}
```
public final int getContentType_internalized(System.Guid uniqueId)
```


Получает тип содержимого слоя смарт‑объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Уникальный идентификатор. |

**Returns:**
int - Тип содержимого слоя умного объекта.
### getContents_internalized(System.Guid uniqueId) {#getContents-internalized-com.aspose.ms.System.Guid-}
```
public final byte[] getContents_internalized(System.Guid uniqueId)
```


Получает содержимое встроенного или связанного файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Уникальный идентификатор связанного источника данных. |

**Returns:**
byte[] - Содержимое byte[] .
### getDataSource_internalized(System.Guid uniqueId) {#getDataSource-internalized-com.aspose.ms.System.Guid-}
```
public final LinkDataSource getDataSource_internalized(System.Guid uniqueId)
```


Получает источник данных ссылки по уникальному идентификатору.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Уникальный идентификатор. |

**Returns:**
[LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) - The [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) instance.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### loadContents_internalized(System.Guid uniqueId, LoadOptions options) {#loadContents-internalized-com.aspose.ms.System.Guid-com.aspose.psd.LoadOptions-}
```
public final Image loadContents_internalized(System.Guid uniqueId, LoadOptions options)
```


Загружает содержимое.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Уникальный идентификатор. |
| options | [LoadOptions](../../com.aspose.psd/loadoptions) | Параметры загрузки. |

**Returns:**
[Image](../../com.aspose.psd/image) - The loaded  Image  instance.
### newSmartObjectViaCopy(SmartObjectLayer sourceLayer) {#newSmartObjectViaCopy-com.aspose.psd.fileformats.psd.layers.smartobjects.SmartObjectLayer-}
```
public final SmartObjectLayer newSmartObjectViaCopy(SmartObjectLayer sourceLayer)
```


Создаёт новый слой смарт‑объекта, копируя исходный.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceLayer | [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) | Исходный слой. |

**Returns:**
[SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) - The cloned [SmartObjectLayer](../../com.aspose.psd.fileformats.psd.layers.smartobjects/smartobjectlayer) instance.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources) {#removeOrphanedDataSources-internalized-com.aspose.ms.System.Collections.Generic.List-com.aspose.ms.System.Guid--}
```
public final void removeOrphanedDataSources_internalized(System.Collections.Generic.List<System.Guid> actualDataSources)
```


Удаляет источники данных из встроенных и внешних ресурсов, которые отсутствуют в предоставленном списке действительных GUID. Этот метод очищает осиротевшие источники данных, сравнивая их с текущими действительными идентификаторами источников данных.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| actualDataSources | com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Guid> | Список действительных GUID источников данных, которые следует сохранить. Источники данных, не входящие в этот список, будут удалены. |

### replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents) {#replaceDataSource-internalized-com.aspose.ms.System.Guid-byte---}
```
public final System.Guid replaceDataSource_internalized(System.Guid oldUniqueId, byte[] contents)
```


Заменяет источник данных в глобальных ресурсах предоставленными данными для встраивания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| oldUniqueId | com.aspose.ms.System.Guid | Уникальный идентификатор существующего источника данных. |
| contents | byte[] | Данные для нового источника данных. |

**Returns:**
com.aspose.ms.System.Guid - Уникальный идентификатор созданного встроенного источника данных.  LiFdDataSource .
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) |  |
| linkedPath | java.lang.String |  |

**Returns:**
com.aspose.ms.System.Guid
### replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis) {#replaceDataSource-internalized-com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources.PlacedResource-java.lang.String-boolean-}
```
public final System.Guid replaceDataSource_internalized(PlacedResource placedResource, String linkedPath, boolean isReplaceOnlyThis)
```


Заменяет источник данных в глобальном ресурсе LinkResource вновь созданным источником данных из внешнего файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| placedResource | [PlacedResource](../../com.aspose.psd.fileformats.psd.layers.layerresources.smartobjectresources/placedresource) | Размещённый ресурс. |
| linkedPath | java.lang.String | Абсолютный путь к связанному файлу. |
| isReplaceOnlyThis | boolean | Если true, то не удалять источник данных в глобальных ресурсах. |

**Returns:**
com.aspose.ms.System.Guid - Уникальный идентификатор Guid созданного связанного источника данных. [LiFeDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/lifedatasource).
### setContents_internalized(System.Guid uniqueId, byte[] data, String fileType) {#setContents-internalized-com.aspose.ms.System.Guid-byte---java.lang.String-}
```
public final void setContents_internalized(System.Guid uniqueId, byte[] data, String fileType)
```


Устанавливает содержимое встроенного или внешнего файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | com.aspose.ms.System.Guid | Уникальный идентификатор связанного источника данных. |
| данные | byte[] | Данные. |
| fileType | java.lang.String | Тип файла данных. |

### setDataSource(LinkDataSource dataSource) {#setDataSource-com.aspose.psd.fileformats.psd.layers.layerresources.linkresources.LinkDataSource-}
```
public final void setDataSource(LinkDataSource dataSource)
```


Устанавливает (заменяет или добавляет) источник данных ссылки в глобальном ресурсе ссылок.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dataSource | [LinkDataSource](../../com.aspose.psd.fileformats.psd.layers.layerresources.linkresources/linkdatasource) | Связанный источник данных. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateAllModifiedContent() {#updateAllModifiedContent--}
```
public final void updateAllModifiedContent()
```


Обновляет содержимое всех изменённых смарт‑объектов в изображении.

### updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution) {#updateDuplicateLayers-internalized-com.aspose.ms.System.Guid-com.aspose.ms.System.Guid-com.aspose.psd.ResolutionSetting-}
```
public final void updateDuplicateLayers_internalized(System.Guid oldGuid, System.Guid newGuid, ResolutionSetting resolution)
```


Обновляет все слои смарт‑объекта в контейнере, у которых  UniqueId  совпадает с  oldGuid . UniqueId совпадающих слоёв переназначается на  newGuid , и их содержимое обновляется.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| oldGuid | com.aspose.ms.System.Guid | Уникальный идентификатор исходного источника данных смарт‑объекта, который будет заменён. |
| newGuid | com.aspose.ms.System.Guid | Уникальный идентификатор нового источника данных смарт‑объекта, который следует назначить. |
| resolution | [ResolutionSetting](../../com.aspose.psd/resolutionsetting) | Настройки разрешения, применяемые при обновлении содержимого. Если  null , используется разрешение изображения. |

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

