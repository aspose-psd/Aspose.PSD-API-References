---
title: Class LiFdDataSource
second_title: Справочник по Aspose.PSD для .NET API
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.LiFdDataSource сорт. Определяет класс источника данных liFD в файле PSD который содержит информацию о встроенном файле. Это часть API управления форматом файла PSD который помогает изменять файлы Adobe Photoshop
type: docs
weight: 2670
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/
---
## LiFdDataSource class

Определяет класс источника данных liFD в файле PSD, который содержит информацию о встроенном файле. Это часть API управления форматом файла PSD, который помогает изменять файлы Adobe® Photoshop®

```csharp
public class LiFdDataSource : LinkDataSource
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [LiFdDataSource](lifddatasource/#constructor)() | Инициализирует новый экземпляр`LiFdDataSource` класс. |
| [LiFdDataSource](lifddatasource/#constructor_1)(int, Guid, string, string, string) | Инициализирует новый экземпляр`LiFdDataSource` класс. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate/) { get; set; } | Получает или задает значение, указывающее, заблокирован ли ресурс PSD. Состояние блокировки ресурса для ресурсов Adobe® Photoshop® CC Libraries. |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime/) { get; set; } | Получает или задает время изменения ресурса для ресурсов Adobe® Photoshop® CC Libraries. |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid/) { get; set; } | Получает или задает идентификатор дочернего документа в источнике данных liFE или liFD ресурса Lnk2 / LnkE Adobe® Photoshop®. |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid/) { get; set; } | Получает или задает идентификатор текущей выбранной композиции для дочернего документа, который будет равен -1, если ничего не выбрано. Композиции — это композиции макета страницы, которые могут создавать дизайнеры. Используя композиции слоев, вы можете создавать, управлять и просматривать несколько версий макета в одном файле Adobe® Photoshop®. Композиция слоев — это снимок состояния панели «Слои». Композиции слоев сохраняют три типа параметров слоев, но это свойство получает идентификатор выбора композиции слоев для смарт-объектов. [Композиции слоев в смарт-объектах](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Data](../../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/data/) { get; set; } | Получает или задает встроенные данные смарт-объекта в файле PSD. |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator/) { get; set; } | Получает или задает создатель файла в формате PSD LnkE/Lnk2 ресурса. |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype/) { get; set; } | Получает или задает тип встроенного или внешнего файла, который содержит ресурс Adobe® Photoshop® Lnk2 / LnkE или ссылки на него. |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor/) { get; set; } | Получает или задает значение, указывающее, имеет ли этот источник данных ссылки дескриптор открытия файла: CompId и OriginalCompId. |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink/) { get; } | Получает значение, указывающее, ссылается ли этот источник данных ссылки PSD на элемент библиотеки Adobe® Photoshop® CC Library. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length/) { get; } | Получает длину источника данных ссылки в байтах. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid/) { get; } | Получает исходный идентификатор текущей выбранной композиции для дочернего документа, который будет равен -1, если ничего не выбрано. Это свойство получает исходный идентификатор выбора композиции слоя для смарт-объектов. [Композиции слоев в смарт-объектах](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename/) { get; } | Получает исходное имя файла источника данных в ресурсе глобальной ссылки Adobe® Photoshop®. |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type/) { get; } | Получает тип источника данных глобальной ссылки Adobe® Photoshop®, который может быть одним из следующих или отсутствовать: Встроенный связанный файл liFD, соответствующий PSD Lnk2Resource Внешний связанный файл liFE, соответствующий PSD LnkeResource Псевдоним связанного файла liFA |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid/) { get; } | Получает глобальный уникальный идентификатор источника данных в ресурсе ссылки PSD. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version/) { get; } | Получает версию источника данных в ресурсе PSD LnkE/Lnk2. |

### Смотрите также

* class [LinkDataSource](../linkdatasource/)
* пространство имен [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* сборка [Aspose.PSD](../../)


