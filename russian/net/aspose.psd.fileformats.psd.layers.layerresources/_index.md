---
title: Aspose.PSD.FileFormats.Psd.Layers.LayerResources
second_title: Справочник по Aspose.PSD для .NET API
description: Пространство имен содержит объекты формата файла PSD содержащиеся в слоях.
type: docs
weight: 270
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/
---
Пространство имен содержит объекты формата файла PSD, содержащиеся в слоях.

## Классы

| Учебный класс | Описание |
| --- | --- |
| [AdjustmentLayerResource](./adjustmentlayerresource/) | Базовый класс для ресурсов слоя настроек |
| [AnimatedDataSectionStructure](./animateddatasectionstructure/) | Раздел с анимированными данными. |
| [BlncResource](./blncresource/) | Класс BlncResource является ресурсом корректирующего слоя цвета. |
| [BlwhResource](./blwhresource/) | Класс BlwhResource является ресурсом черно-белого корректирующего слоя. |
| [BooleanResource](./booleanresource/) | Класс BooleanResource. Это псевдоресурс. В фотошопе нет |
| [BritResource](./britresource/) | Класс БритРесурс. Ресурс корректирующего слоя яркости/контрастности |
| [CgEdResource](./cgedresource/) | Класс CgEdResource. Дополнительные данные генератора контента (Photoshop CS5) |
| [ClassID](./classid/) | Объект идентификатора класса PSD. |
| [ClblResource](./clblresource/) | Класс ClblResource. Этот ресурс содержит информацию о смешивании отсеченного элемента. |
| [CmlsResource](./cmlsresource/) | Класс CmlsResource. |
| [ColorRangeHsl](./colorrangehsl/) | [`Hue2Resource`](../aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) имеет 6 цветовых диапазонов, где вы можете изменить параметры HSV. Каждый диапазон имеет 4 ключевые точки для определения границ диапазона. И это ColorRangeHsl |
| [CurvesContinuousManager](./curvescontinuousmanager/) | Менеджер корректирующего слоя кривых, управляющий кривыми |
| [CurvesDiscreteManager](./curvesdiscretemanager/) | Менеджер корректирующего слоя кривых, управляющий картой пикселей |
| [CurvesManager](./curvesmanager/) | Базовый класс для управления CurvResource |
| [CurvResource](./curvresource/) | Класс CurvResource. Ресурс настройки кривых Layer 1 байт - 0 если использовать кривые, 1 если используются пиксели на карте если 0 то: 2 байта - короткие. По умолчанию 1 4 байта - инт. Используется только последний байт за битом. Первый бит для 1 канала, Четвертый бит для 4 канала например 2 байта - короткие точки count 4 байта * количество точек - точки кривой 2 короткие: первая позиция, вторая высота 4 байта - слово "Crv" 2 байта - короткий по умолчанию 4 для Curves 4 байта - внутр. По умолчанию 1 4 байта - количество точек 4 байта * количество точек - точек кривой 2 короткая: первая позиция, вторая высота 0-4 байта - Ведущий будет складывать для четырех если 1 то: 2 байта - короткая. По умолчанию 1 4 байта - инт. Используется только последний байт. Один канал в одном бите. Первый бит для 1 канала, Четвертый бит для 4 канала например 256 * количество измененных каналов - упорядоченные значения канала в диапазоне 0 - 255 4 байта - слово "Crv" 2 байта - короткие. По умолчанию 3 для пикселей на карте 4 байта - int Channel count (2 + 256) байт - короткая 2 для индекса канала, 256 упорядоченные значения канала в диапазоне 0 - 255 |
| [CustResource](./custresource/) | Класс CustResource. Этот ресурс содержит информацию о смешивании отсеченного элемента. |
| [ExpaResource](./exparesource/) | Класс ExpaResource. Ресурс корректирующего слоя экспозиции |
| [FillLayerResource](./filllayerresource/) | Базовый класс для ресурсов слоя заливки |
| [FilterEffectMaskData](./filtereffectmaskdata/) | Класс данных маски фильтра. |
| [FXidResource](./fxidresource/) | Ресурс Filter Effects содержит каналы, маску пользователя и маску листа для интеллектуального фильтра. |
| [FxrpResource](./fxrpresource/) | Класс FxrpResource. Контрольная точка layer |
| [GdFlResource](./gdflresource/) | Класс GdFlResource. Этот ресурс содержит информацию о смешивании отсеченного элемента. |
| [Hue2Resource](./hue2resource/) | Класс Hue2Resource. Ресурс корректирующего слоя экспозиции |
| [InfxResource](./infxresource/) | Класс InfxResource. Этот ресурс содержит информацию о смешивании отсеченного элемента. |
| [IopaResource](./ioparesource/) | Класс IopaResource. Этот ресурс содержит информацию о свойстве непрозрачности заливки из стиля слоя form |
| [KnkoResource](./knkoresource/) | Класс KkoResource. Этот ресурс содержит информацию о смешивании отсеченного элемента. |
| [LayerSectionResource](./layersectionresource/) | Ресурс раздела слоя. |
| [LclrResource](./lclrresource/) | Класс LclrResource. Этот ресурс содержит информацию о цвете слоя в списке слоев PS. Это только |
| [LevelChannel](./levelchannel/) | Класс для работы с каналами в Levels Adjustment Layer |
| [LevlResource](./levlresource/) | Класс ЛевлРесаурце. Ресурс корректирующего слоя экспозиции |
| [Lfx2Resource](./lfx2resource/) | Ресурс Lfx2 (ресурс эффектов) |
| [LiFdDataSource](./lifddatasource/) | Определяет класс источника данных liFD в файле PSD, который содержит информацию о встроенном файле. Это часть API управления форматом файла PSD, который помогает изменять файлы Adobe® Photoshop® |
| [LiFeDataSource](./lifedatasource/) | Определяет класс LnkeDataSource, который содержит информацию о внешнем связанном файле. Это часть API управления форматом файла PSD, который помогает изменять файлы Adobe® Photoshop® |
| [LinkDataSource](./linkdatasource/) | Определяет класс LinkDataSource, который содержит информацию о связанном файле или ресурсе в PSD-файле. |
| [LinkResource](./linkresource/) | Определяет класс LinkResource, который содержит информацию о связанных или встроенных файлах в изображении формата PSD. Ресурс ссылки может содержать несколько[`LinkDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) экземпляры, к которым могут обращаться индексаторы в любом производном классе. |
| [Lnk2Resource](./lnk2resource/) | Определяет класс, который содержит информацию о вложенных файлах в изображение формата PSD. Ресурс ссылки может содержать несколько[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) экземпляры, к которым может обращаться индексатор. |
| [Lnk3Resource](./lnk3resource/) | Определяет класс, который содержит информацию о встроенном файле в формате PSD 32 бита на канал изображения. Ресурс ссылки может содержать несколько[`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) экземпляры, к которым может обращаться indexer. |
| [LnkeResource](./lnkeresource/) | Определяет класс LnkeResource, который содержит информацию о внешних связанных файлах или ресурсах в изображении формата PSD. Ресурс ссылки может содержать несколько[`LiFeDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) экземпляры, к которым может обращаться индексатор. Это часть API управления форматом файлов PSD, который помогает программно изменять файлы Adobe® Photoshop® |
| [LnsrResource](./lnsrresource/) | Класс lnsrResource. |
| [Lr16Resource](./lr16resource/) | Ресурс LR32. |
| [Lr32Resource](./lr32resource/) | Ресурс LR32. |
| [LspfResource](./lspfresource/) | Защищенные настройки слоя |
| [LuniResource](./luniresource/) | Имя слоя resource |
| [LyidResource](./lyidresource/) | Класс LyidResource. |
| [MixrResource](./mixrresource/) | Класс MixrResource. Ресурс настройки микшера каналов Layer |
| [MlstResource](./mlstresource/) | Ресурс mlst. Этот класс, помимо прочего, содержит информацию о положении слоя на временной шкале. |
| [NvrtResource](./nvrtresource/) | Класс NvrtResource. Ресурс инвертированного корректирующего слоя. |
| [OSTypeStructure](./ostypestructure/) | Представляет структуру типа ОС. |
| [OSTypeStructuresRegistry](./ostypestructuresregistry/) | Представляет[`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) реестр ресурсов. |
| [PattResource](./pattresource/) | Класс PattResource. Ресурс с шаблоном data |
| [PattResourceData](./pattresourcedata/) | Класс для хранения данных шаблона[`PattResource`](../aspose.psd.fileformats.psd.layers.layerresources/pattresource/) ресурс. |
| [PhflResource](./phflresource/) | Класс PhflResource. Ресурс слоя коррекции экспозиции 2 Версия ( = 3 ) или ( = 2 ) 12 4 байта для каждого цвета XYZ (только в версии 3) 10 2 байта цветового пространства, за которым следует 4 * 2 байта цветового компонента (только в версии 2) 4 Плотность 1 Сохранить яркость |
| [PhflResourceVersion2](./phflresourceversion2/) | Класс PhflResource. Ресурс слоя коррекции экспозиции 2 Версия ( = 3 ) или ( = 2 ) 12 4 байта для каждого цвета XYZ (только в версии 3) 10 2 байта цветового пространства, за которым следует 4 * 2 байта цветового компонента (только в версии 2) 4 Плотность 1 Сохранить яркость |
| [PhflResourceVersion3](./phflresourceversion3/) | Класс PhflResource. Ресурс слоя коррекции экспозиции 2 Версия ( = 3 ) или ( = 2 ) 12 4 байта для каждого цвета XYZ (только в версии 3) 10 2 байта цветового пространства, за которым следует 4 * 2 байта цветового компонента (только в версии 2) 4 Плотность 1 Сохранить яркость |
| [PlacedResource](./placedresource/) | Определяет класс PlacedResource, который содержит общую информацию о размещенном слое или слое смарт-объектов в файле PSD. Используется для поддержки слоев смарт-объектов в изображениях Adobe® Photoshop®. |
| [PlLdResource](./plldresource/) | Определяет класс PlLdResource, который содержит информацию о размещенном слое в PSD-файле. Используется для поддержки слоев смарт-объектов в изображениях Adobe® Photoshop®. Он был заменен SoLdResource в Adobe® Photoshop® CS3 |
| [PostResource](./postresource/) | Класс PostResource. Постеризация настроек слоя. |
| [PtFlResource](./ptflresource/) | Класс PtFlResource. Содержит данные слоя заливки узором. |
| [ShmdResource](./shmdresource/) | Класс ShmdResource. Настройки метаданных |
| [SmartObjectResource](./smartobjectresource/) | Определяет класс SmartObjectResource, который содержит информацию о слое смарт-объектов в PSD-файле. Является базовым классом для ресурсов Sold и Sole, который используется для поддержки слоев смарт-объектов в изображениях Adobe® Photoshop®. |
| [SmartResourceCreator](./smartresourcecreator/) | Определяет класс SmartResourceCreator, который может создавать ресурсы PlLd, SoLd и SoLe. Используется для поддержки слоев смарт-объектов в изображениях Adobe® Photoshop®. |
| [SoCoResource](./socoresource/) | Класс SoCoResource. Этот ресурс содержит информацию о Color Fill Layers |
| [SoLdResource](./soldresource/) | Определяет класс SoLdResource, который содержит информацию о слое смарт-объектов в файле PSD. Используется для поддержки слоев смарт-объектов в изображениях Adobe® Photoshop®. |
| [SoLeResource](./soleresource/) | Определяет класс SoLeResource, который содержит информацию о слое смарт-объектов в файле PSD. Используется для поддержки слоев смарт-объектов с внешними ссылками на файлы в изображениях Adobe® Photoshop®. |
| [Txt2Resource](./txt2resource/) | класс ресурса Txt2 |
| [TypeToolFontInfo](./typetoolfontinfo/) | Содержит информацию о шрифте инструмента ввода. |
| [TypeToolInfo6Resource](./typetoolinfo6resource/) | Информация о типе инструмента. Для версии PSD выше или равной 6.0. |
| [TypeToolInfoResource](./typetoolinforesource/) | Информация о типе инструмента. Для версии PSD ниже 6.0. |
| [TypeToolLineInfo](./typetoollineinfo/) | Введите информацию о строке инструмента. |
| [TypeToolStyleInfo](./typetoolstyleinfo/) | Введите информацию о стиле инструмента. |
| [UnknownResource](./unknownresource/) | Неизвестный ресурс. |
| [VectorPathDataResource](./vectorpathdataresource/) | Класс VectorPathDataResource. Этот ресурс содержит информацию о маске векторного слоя |
| [VibAResource](./vibaresource/) | Ресурс VibA. |
| [VmskResource](./vmskresource/) | Класс VmskResource. Этот ресурс содержит информацию о маске векторного слоя |
| [VogkResource](./vogkresource/) | Ресурс данных происхождения вектора. |
| [VsmsResource](./vsmsresource/) | Класс VsmsResource. Этот ресурс содержит информацию о маске векторного слоя |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IOSTypeStructureLoader](./iostypestructureloader/) | [`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) загрузчик ресурсов. |
| [IPlacedLayerResource](./iplacedlayerresource/) | Определяет интерфейс IPlacedLayerResource, который содержит информацию о размещенном слое в файле PSD. Is — это интерфейс разметки, используемый для обозначения ресурсов PlLd, Sold и Sole в изображениях Adobe® Photoshop®. Is используется для поддержки слоев смарт-объектов в изображения Adobe® Photoshop®. |
| [ISmartObjectLayerResource](./ismartobjectlayerresource/) | Определяет интерфейс ISmartObjectLayerResource, который содержит информацию о ресурсе слоя смарт-объекта в файле PSD. Это также интерфейс разметки, используемый для обозначения ресурсов Sold и Sole в изображениях Adobe® Photoshop®. |
## перечисление

| перечисление | Описание |
| --- | --- |
| [LayerLockType](./layerlocktype/) | Параметры блокировки слоя |
| [LayerSectionSubtype](./layersectionsubtype/) | Раздел subtype |
| [LayerSectionType](./layersectiontype/) | Раздел слоя type |
| [LinkDataSourceType](./linkdatasourcetype/) | Определяет перечисление LinkDataSourceType для источников данных в ресурсе ссылки PSD. |
| [LnsrResourceType](./lnsrresourcetype/) | Обнаружены возможные типы ресурсов Lnsr |
| [PlacedLayerType](./placedlayertype/) | Определяет перечисление PlacedLayerType для размещенного ресурса PlLd слоя. |
| [SheetColorHighlightEnum](./sheetcolorhighlightenum/) | Возможные цвета настройки цвета листа. Это декоративный цвет пользовательского интерфейса слоя в списке слоев в PS |


