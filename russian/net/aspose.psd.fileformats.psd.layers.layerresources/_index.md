---
title: Aspose.PSD.FileFormats.Psd.Layers.LayerResources
second_title: Справочник по Aspose.PSD для .NET API
description: Пространство имен содержит объекты формата файла PSD содержащиеся в слоях.
type: docs
weight: 260
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/
---
Пространство имен содержит объекты формата файла PSD, содержащиеся в слоях.

## Классы

| Учебный класс | Описание |
| --- | --- |
| [AdjustmentLayerResource](./adjustmentlayerresource) | Базовый класс для ресурсов корректирующего слоя |
| [AnimatedDataSectionStructure](./animateddatasectionstructure) | Раздел с анимированными данными. |
| [BlncResource](./blncresource) | Класс BlncResource является ресурсом слоя настройки цвета. |
| [BlwhResource](./blwhresource) | Класс BlwhResource является ресурсом черно-белого корректирующего слоя. |
| [BooleanResource](./booleanresource) | Класс BooleanResource. Это псевдоресурс. В Photoshop нет |
| [BritResource](./britresource) | Класс BritResource. Ресурс слоя регулировки яркости/контрастности |
| [CgEdResource](./cgedresource) | Класс CgEdResource. Дополнительные данные генератора контента (Photoshop CS5) |
| [ClassID](./classid) | Объект идентификатора класса PSD. |
| [ClblResource](./clblresource) | Класс ClblResource. Этот ресурс содержит информацию о смешивании обрезанного элемента. |
| [CmlsResource](./cmlsresource) | Класс CmlsResource. |
| [ColorRangeHsl](./colorrangehsl) | [`Hue2Resource`](../aspose.psd.fileformats.psd.layers.layerresources/hue2resource)имеет 6 цветовых диапазонов, в которых можно изменить параметры HSV. Каждый диапазон имеет 4 ключевые точки для определения границ диапазона. И это ColorRangeHsl |
| [CurvesContinuousManager](./curvescontinuousmanager) | Менеджер корректирующего слоя кривых, управляющий кривыми |
| [CurvesDiscreteManager](./curvesdiscretemanager) | Менеджер корректирующего слоя кривых, управляющий картой пикселей |
| [CurvesManager](./curvesmanager) | Базовый класс для управления CurvResource |
| [CurvResource](./curvresource) | Класс CurvResource. Ресурс корректирующего слоя кривых 1 байт - 0 если используются кривые, 1 если используются пиксели на карте если 0 то: 2 байта - короткие. По умолчанию 1 4 байта - инт. Используется только последний байт за битом. Первый бит для 1 канала, Четвертый бит для 4 канала например 2 байта - количество коротких точек 4 байта * количество точек - точек кривой 2 коротко:первая позиция , вторая высота 4 байта - слово "Crv" 2 байта - короткое по умолчанию 4 для кривых 4 байта - инт. По умолчанию 1 4 байта - количество точек 4 байта * количество точек - точки кривой 2 короткие:первая позиция, вторая высота 0-4 байта - Ведущий нужно сложить на четыре если 1 то: 2 байта - короткий. По умолчанию 1 4 байта - инт. Используется только последний байт. Один канал в одном бите. Первый бит для 1 канала, Четвертый бит для 4 канала например 256 * количество измененных каналов - упорядоченные значения канала в диапазоне 0 - 255 4 байта - слово " Crv" 2 байта - короткий. По умолчанию 3 для пикселей на карте 4 байта - int Количество каналов (2 + 256) байт - короткая 2 для индекса канала, 256 упорядоченных значений канала в диапазоне 0 - 255 |
| [CustResource](./custresource) | Класс CustResource. Этот ресурс содержит информацию о смешивании обрезанного элемента. |
| [ExpaResource](./exparesource) | Класс ExpaResource. Ресурс корректирующего слоя экспозиции |
| [FillLayerResource](./filllayerresource) | Базовый класс для ресурсов слоя заливки |
| [FilterEffectMaskData](./filtereffectmaskdata) | Класс данных маски фильтра. |
| [FXidResource](./fxidresource) | Ресурс Filter Effects содержит каналы, маску пользователя и маску листа для интеллектуального фильтра. |
| [FxrpResource](./fxrpresource) | Класс FxrpResource. Контрольная точка слоя |
| [GdFlResource](./gdflresource) | Класс GdFlResource. Этот ресурс содержит информацию о смешивании обрезанного элемента. |
| [Hue2Resource](./hue2resource) | Класс Hue2Resource. Ресурс корректирующего слоя экспозиции |
| [InfxResource](./infxresource) | Класс InfxResource. Этот ресурс содержит информацию о смешивании обрезанного элемента. |
| [IopaResource](./ioparesource) | Класс IopaResource. Этот ресурс содержит информацию о свойстве непрозрачности заливки из формы стиля слоя |
| [KnkoResource](./knkoresource) | Класс KkoResource. Этот ресурс содержит информацию о смешивании обрезанного элемента. |
| [LayerSectionResource](./layersectionresource) | Ресурс раздела слоя. |
| [LclrResource](./lclrresource) | Класс LclrResource. Этот ресурс содержит информацию о цвете слоя в списке слоев PS. Это всего лишь |
| [LevelChannel](./levelchannel) | Класс для работы с каналами в слое Levels Adjustment Layer |
| [LevlResource](./levlresource) | Класс LevlResource. Ресурс корректирующего слоя экспозиции |
| [Lfx2Resource](./lfx2resource) | Ресурс Lfx2 (ресурс эффектов) |
| [LiFdDataSource](./lifddatasource) | Определяет класс источника данных liFD в файле PSD, который содержит информацию о встроенном файле. Это часть API управления форматом файлов PSD, который помогает изменять файлы Adobe® Photoshop® |
| [LiFeDataSource](./lifedatasource) | Определяет класс LnkeDataSource, который содержит информацию о внешнем связанном файле. Это часть API управления форматом файлов PSD, который помогает изменять файлы Adobe® Photoshop® |
| [LinkDataSource](./linkdatasource) | Определяет класс LinkDataSource, который содержит информацию о связанном файле или активе в файле PSD. |
| [LinkResource](./linkresource) | Определяет класс LinkResource, который содержит информацию о связанных или встроенных файлах в изображении формата PSD. Ресурс ссылки может содержать несколько экземпляров[`LinkDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource), к которым могут обращаться индексаторы в любом производном классе. |
| [Lnk2Resource](./lnk2resource) | Определяет класс, который содержит информацию о встроенных файлах изображения в формате PSD. Ресурс ссылки может содержать несколько экземпляров[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource), к которым может обращаться индексатор. |
| [Lnk3Resource](./lnk3resource) | Определяет класс, который содержит информацию о встроенном файле в формате PSD 32 бита на канал изображения. Ресурс ссылки может содержать несколько экземпляров[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource), к которым может обращаться индексатор. |
| [LnkeResource](./lnkeresource) | Определяет класс LnkeResource, который содержит информацию о внешних связанных файлах или активах в изображении формата PSD. Ресурс ссылки может содержать несколько экземпляров[`LiFeDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource), к которым может обращаться индексатор. Это часть API-интерфейса управления форматом файлов PSD, который помогает программно изменять файлы Adobe® Photoshop® |
| [LnsrResource](./lnsrresource) | Класс lnsrResource. |
| [Lr16Resource](./lr16resource) | Ресурс LR32. |
| [Lr32Resource](./lr32resource) | Ресурс LR32. |
| [LspfResource](./lspfresource) | Настройки защищенного слоя |
| [LuniResource](./luniresource) | Ресурс имени слоя |
| [LyidResource](./lyidresource) | Класс LyidResource. |
| [MixrResource](./mixrresource) | Класс MixrResource. Ресурс корректирующего слоя микшера каналов |
| [NvrtResource](./nvrtresource) | Класс NvrtResource. Ресурс инвертированного корректирующего слоя. |
| [OSTypeStructure](./ostypestructure) | Представляет структуру типа ОС. |
| [OSTypeStructuresRegistry](./ostypestructuresregistry) | Представляет реестр ресурсов[`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure). |
| [PattResource](./pattresource) | Класс PattResource. Ресурс с данными шаблона |
| [PattResourceData](./pattresourcedata) | Класс для хранения данных шаблона для[`PattResource`](../aspose.psd.fileformats.psd.layers.layerresources/pattresource)ресурса. |
| [PhflResource](./phflresource) | Класс PhflResource. Ресурс корректирующего слоя экспозиции 2 Версия ( = 3 ) или ( = 2 ) 12 4 байта каждый для цвета XYZ (только в версии 3) 10 2 байта цветового пространства, за которым следует цветовой компонент 4 * 2 байта (только в версии 2) 4 Density 1 Preserve Luminosity |
| [PhflResourceVersion2](./phflresourceversion2) | Класс PhflResource. Ресурс корректирующего слоя экспозиции 2 Версия ( = 3 ) или ( = 2 ) 12 4 байта каждый для цвета XYZ (только в версии 3) 10 2 байта цветового пространства, за которым следует цветовой компонент 4 * 2 байта (только в версии 2) 4 Density 1 Preserve Luminosity |
| [PhflResourceVersion3](./phflresourceversion3) | Класс PhflResource. Ресурс корректирующего слоя экспозиции 2 Версия ( = 3 ) или ( = 2 ) 12 4 байта каждый для цвета XYZ (только в версии 3) 10 2 байта цветового пространства, за которым следует цветовой компонент 4 * 2 байта (только в версии 2) 4 Density 1 Preserve Luminosity |
| [PlacedResource](./placedresource) | Определяет класс PlacedResource, который содержит общую информацию о размещенном слое или слое смарт-объекта в файле PSD. Используется для поддержки слоев смарт-объектов в изображениях Adobe® Photoshop®. |
| [PlLdResource](./plldresource) | Определяет класс PlLdResource, который содержит информацию о размещенном слое в файле PSD. Используется для поддержки слоев смарт-объектов в изображениях Adobe® Photoshop®. Он был заменен на SoLdResource в Adobe® Photoshop® CS3 |
| [PtFlResource](./ptflresource) | Класс PtFlResource. Содержит данные слоя заполнения узором. |
| [ShmdResource](./shmdresource) | Класс ShmdResource. Настройки метаданных |
| [SmartObjectResource](./smartobjectresource) | Определяет класс SmartObjectResource, который содержит информацию о слое смарт-объектов в PSD-файле. Является базовым классом для ресурсов Sold и Sole, который используется для поддержки слоев смарт-объектов в изображениях Adobe® Photoshop®. |
| [SmartResourceCreator](./smartresourcecreator) | Определяет класс SmartResourceCreator, который может создавать ресурсы PlLd, SoLd и SoLe. Используется для поддержки слоев смарт-объектов в изображениях Adobe® Photoshop®. |
| [SoCoResource](./socoresource) | Класс SoCoResource. Этот ресурс содержит информацию о слоях заливки цветом |
| [SoLdResource](./soldresource) | Определяет класс SoLdResource, который содержит информацию о слое смарт-объекта в файле PSD. Используется для поддержки слоев смарт-объектов в изображениях Adobe® Photoshop®. |
| [SoLeResource](./soleresource) | Определяет класс SoLeResource, который содержит информацию о слое смарт-объекта в файле PSD. Используется для поддержки слоев смарт-объектов с внешними ссылками на файлы в изображениях Adobe® Photoshop®. |
| [Txt2Resource](./txt2resource) | Класс ресурсов Txt2 |
| [TypeToolFontInfo](./typetoolfontinfo) | Содержит информацию о шрифте инструмента ввода. |
| [TypeToolInfo6Resource](./typetoolinfo6resource) | Информация о типе инструмента. Для версии PSD выше или равной 6.0. |
| [TypeToolInfoResource](./typetoolinforesource) | Информация о типе инструмента. Для версии PSD ниже 6.0. |
| [TypeToolLineInfo](./typetoollineinfo) | Введите информацию о строке инструмента. |
| [TypeToolStyleInfo](./typetoolstyleinfo) | Введите информацию о стиле инструмента. |
| [UnknownResource](./unknownresource) | Неизвестный ресурс. |
| [VectorPathDataResource](./vectorpathdataresource) | Класс VectorPathDataResource. Этот ресурс содержит информацию о маске векторного слоя |
| [VibAResource](./vibaresource) | Ресурс VibA. |
| [VmskResource](./vmskresource) | Класс VmskResource. Этот ресурс содержит информацию о маске векторного слоя |
| [VogkResource](./vogkresource) | Ресурс данных о происхождении вектора. |
| [VsmsResource](./vsmsresource) | Класс VsmsResource. Этот ресурс содержит информацию о маске векторного слоя |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IOSTypeStructureLoader](./iostypestructureloader) | Загрузчик ресурсов[`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure). |
| [IPlacedLayerResource](./iplacedlayerresource) | Определяет интерфейс IPlacedLayerResource, который содержит информацию о размещенном слое в файле PSD. Является интерфейсом разметки, используемым для обозначения ресурсов PlLd, Sold и Sole в изображениях Adobe® Photoshop®. Используется для поддержки слоев смарт-объектов в изображениях Adobe® Photoshop®. |
| [ISmartObjectLayerResource](./ismartobjectlayerresource) | Определяет интерфейс ISmartObjectLayerResource, который содержит информацию о ресурсе слоя смарт-объекта в файле PSD. Это также интерфейс разметки, используемый для обозначения ресурсов Sold и Sole в изображениях Adobe® Photoshop®. |
## перечисление

| перечисление | Описание |
| --- | --- |
| [LayerLockType](./layerlocktype) | Опции блокировки слоя |
| [LayerSectionSubtype](./layersectionsubtype) | Подтип секции |
| [LayerSectionType](./layersectiontype) | Тип раздела слоя |
| [LinkDataSourceType](./linkdatasourcetype) | Определяет перечисление LinkDataSourceType для источников данных в ресурсе ссылки PSD. |
| [LnsrResourceType](./lnsrresourcetype) | Обнаружены возможные типы ресурсов Lnsr |
| [PlacedLayerType](./placedlayertype) | Определяет перечисление PlacedLayerType для размещенного ресурса PlLd слоя. |
| [SheetColorHighlightEnum](./sheetcolorhighlightenum) | Возможные цвета настройки цвета листа. Это декоративный цвет пользовательского интерфейса в списке слоев в PS |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
