---
title: "Aspose.PSD.FileFormats.Psd.Layers.LayerResources"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Пространство имён содержит сущности формата файлов PSD, содержащиеся в слоях."
type: docs
weight: 300
url: /ru/net/aspose.psd.fileformats.psd.layers.layerresources/
---
{{< psd/tize >}}
Пространство имён содержит сущности формата файлов PSD, содержащиеся в слоях.

## Классы

| Класс | Описание |
| --- | --- |
| [AbddResource](./abddresource/) | Данные информации о рабочей области. |
| [AdjustmentLayerResource](./adjustmentlayerresource/) | Базовый класс для ресурсов слоёв коррекции. |
| [AnimatedDataSectionStructure](./animateddatasectionstructure/) | Раздел с анимированными данными. |
| [ArtBResource](./artbresource/) | Данные информации о рабочей области для [`Resources`](../aspose.psd.fileformats.psd.layers/layer/resources/). |
| [ArtDResource](./artdresource/) | Данные информации о рабочей области для [`GlobalLayerResources`](../aspose.psd.fileformats.psd/psdimage/globallayerresources/). |
| [BaseArtboardInfoResource](./baseartboardinforesource/) | Ресурс данных информации о рабочей области. |
| [BaseFxResource](./basefxresource/) | Базовый ресурс эффектов. |
| [BaseLayerSectionResource](./baselayersectionresource/) | Базовый класс для ресурсов раздела слоёв. |
| [BlncResource](./blncresource/) | Класс BlncResource является ресурсом слоя коррекции цвета. |
| [BlwhResource](./blwhresource/) | Класс BlwhResource является ресурсом слоя чёрно‑белой коррекции. |
| [BooleanResource](./booleanresource/) | Класс BooleanResource. Это псевдо‑ресурс. В Photoshop его нет. |
| [BritResource](./britresource/) | Класс BritResource. Ресурс слоя коррекции яркости/контраста. |
| [CgEdResource](./cgedresource/) | Класс CgEdResource. Дополнительные данные генератора контента (Photoshop CS5). |
| [ClassID](./classid/) | Объект PSD Class ID. |
| [ClblResource](./clblresource/) | Класс ClblResource. Этот ресурс содержит информацию о наложении обрезанного элемента. |
| [CmlsResource](./cmlsresource/) | Класс CmlsResource. |
| [ColorRangeHsl](./colorrangehsl/) | [`Hue2Resource`](../aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) имеет 6 цветовых диапазонов, где можно изменить параметры HSV. Каждый диапазон имеет 4 ключевых точки для определения границ диапазона. И это ColorRangeHsl. |
| [CurvesContinuousManager](./curvescontinuousmanager/) | Менеджер слоя коррекции кривых, который управляет кривыми. |
| [CurvesDiscreteManager](./curvesdiscretemanager/) | Менеджер слоя коррекции кривых, который управляет картой пикселей. |
| [CurvesManager](./curvesmanager/) | Базовый класс для управления CurvResource. |
| [CurvResource](./curvresource/) | Класс CurvResource. Ресурс слоя коррекции кривых. 1 байт — 0, если используются кривые, 1, если используется карта пикселей; если 0, то: 2 байта — short. По умолчанию 1. 4 байта — int. Используется только последний байт по биту. Первый бит — для 1 канала, четвёртый бит — для 4 каналов, например 2 байта — short количество точек. 4 байта * количество точек — точки кривой. 2 short: первая позиция, вторая высота. 4 байта — слово "Crv ". 2 байта — short, по умолчанию 4 для кривых. 4 байта — int, по умолчанию 1. 4 байта — количество точек. 4 байта * количество точек — точки кривой. 2 short: первая позиция, вторая высота. 0‑4 байта — ведущие для четырёх, если 1, то: 2 байта — short, по умолчанию 1. 4 байта — int, используется только последний байт. Один канал в одном бите. Первый бит — для 1 канала, четвёртый бит — для 4 каналов, например 256 * количество изменённых каналов — упорядоченные значения канала в диапазоне 0‑255. 4 байта — слово "Crv ". 2 байта — short, по умолчанию 3 для карты пикселей. 4 байта — int количество каналов (2 + 256) байт — short 2 для индекса канала, 256 — упорядоченные значения канала в диапазоне 0‑255. |
| [CustResource](./custresource/) | Класс CustResource. Этот ресурс содержит информацию о наложении обрезанного элемента. |
| [ExpaResource](./exparesource/) | Класс ExpaResource. Ресурс слоя коррекции экспозиции |
| [FillLayerResource](./filllayerresource/) | Базовый класс для ресурсов слоя заливки. |
| [FilterEffectMaskData](./filtereffectmaskdata/) | Класс данных фильтровой маски. |
| [FXidResource](./fxidresource/) | Ресурс Filter Effects содержит каналы, пользовательскую маску и листовую маску для умного фильтра. |
| [FxrpResource](./fxrpresource/) | Класс FxrpResource. Точка привязки слоя |
| [GdFlResource](./gdflresource/) | Класс GdFlResource. Этот ресурс содержит информацию о смешивании обрезанного элемента. |
| [GrdmResource](./grdmresource/) | Класс GrdmResource. Содержит информацию о слое Gradient-Map. |
| [Hue2Resource](./hue2resource/) | Класс Hue2Resource. Ресурс слоя коррекции экспозиции |
| [IfxsResource](./ifxsresource/) | Ресурс Ifxs (ресурс эффектов группового слоя) |
| [ImfxResource](./imfxresource/) | Ресурс Imfx (ресурс мульти-эффектов) |
| [InfxResource](./infxresource/) | Класс InfxResource. Этот ресурс содержит информацию о смешивании обрезанного элемента. |
| [IopaResource](./ioparesource/) | Класс IopaResource. Этот ресурс содержит информацию о свойстве непрозрачности заливки из формы стиля слоя |
| [KnkoResource](./knkoresource/) | Класс KnkoResource. Этот ресурс содержит информацию о смешивании обрезанного элемента. |
| [LayerSectionResource](./layersectionresource/) | Ресурс секции слоя. |
| [LclrResource](./lclrresource/) | Класс LclrResource. Этот ресурс содержит информацию о цвете слоя в списке слоёв PS. Это только |
| [LevelChannel](./levelchannel/) | Класс для работы с каналами в слое коррекции уровней |
| [LevlResource](./levlresource/) | Класс LevlResource. Ресурс слоя коррекции экспозиции |
| [Lfx2Resource](./lfx2resource/) | Ресурс Lfx2 (ресурс обычных эффектов) |
| [LiFdDataSource](./lifddatasource/) | Определяет класс источника данных liFD в файле PSD, который содержит информацию о встроенном файле. Это часть API манипуляции форматом файлов PSD, помогающего изменять файлы Adobe® Photoshop®. |
| [LiFeDataSource](./lifedatasource/) | Определяет класс LnkeDataSource, который содержит информацию о внешнем связанном файле. Это часть API манипуляции форматом файлов PSD, помогающего изменять файлы Adobe® Photoshop®. |
| [LinkDataSource](./linkdatasource/) | Определяет класс LinkDataSource, который содержит информацию о связанном файле или ресурсе в файле PSD. |
| [LinkResource](./linkresource/) | Определяет класс LinkResource, который содержит информацию о связанных или встроенных файлах в изображении формата PSD. Ресурс ссылки может содержать несколько экземпляров [`LinkDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/), к которым можно получить доступ через индексаторы в любом производном классе. |
| [LmskResource](./lmskresource/) | Ресурс LMsk. |
| [Lnk2Resource](./lnk2resource/) | Определяет класс, который содержит информацию о встроенных файлах в изображении формата PSD. Ресурс ссылки может содержать несколько экземпляров [`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/), к которым можно получить доступ через индексатор. |
| [Lnk3Resource](./lnk3resource/) | Определяет класс, который содержит информацию о встроенном файле в 32‑битном изображении формата PSD (на канал). Ресурс ссылки может содержать несколько экземпляров [`LiFdDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/), к которым можно получить доступ через индексатор. |
| [LnkeResource](./lnkeresource/) | Определяет класс LnkeResource, который содержит информацию о внешних связанных файлах или ресурсах в изображении формата PSD. Ресурс ссылки может содержать несколько экземпляров [`LiFeDataSource`](../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/), к которым можно получить доступ через индексатор. Это часть API манипуляции форматом файлов PSD, который помогает программно изменять файлы Adobe® Photoshop®. |
| [LnsrResource](./lnsrresource/) | Класс lnsrResource. |
| [Lr16Resource](./lr16resource/) | Ресурс lr16. |
| [Lr32Resource](./lr32resource/) | Ресурс lr32. |
| [LrXxResource](./lrxxresource/) | Ресурс lrXX. |
| [LsdkResource](./lsdkresource/) | Ресурс слоя lsdk (ресурс вложенного раздела слоя). |
| [LspfResource](./lspfresource/) | Защищённые настройки слоя |
| [LuniResource](./luniresource/) | Ресурс имени слоя |
| [LyidResource](./lyidresource/) | Класс LyidResource. |
| [LyvrResource](./lyvrresource/) | Ресурс, представляющий версию Photoshop слоя. |
| [MixrResource](./mixrresource/) | Класс MixrResource. Ресурс слоя коррекции Channel Mixer |
| [MlstResource](./mlstresource/) | Ресурс mlst. Этот класс, среди прочего, содержит информацию о позиции слоя на временной шкале. |
| [NvrtResource](./nvrtresource/) | Класс NvrtResource. Ресурс слоя коррекции Invert. |
| [OSTypeStructure](./ostypestructure/) | Представляет структуру типа OS. |
| [OSTypeStructuresRegistry](./ostypestructuresregistry/) | Представляет реестр ресурсов [`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| [PathShape](./pathshape/) | Фигура из узлов кривой Безье. |
| [PattResource](./pattresource/) | Класс PattResource. Ресурс с данными шаблона |
| [PattResourceData](./pattresourcedata/) | Класс для хранения данных шаблона ресурса [`PattResource`](../aspose.psd.fileformats.psd.layers.layerresources/pattresource/). |
| [PhflResource](./phflresource/) | Класс PhflResource. Ресурс слоя коррекции Exposure. Версия 2 ( = 3 ) или ( = 2 ) 12 4 байта каждый для цвета XYZ (только в версии 3) 10 2 байта цветовое пространство, за которым следуют 4 * 2 байта цветового компонента (только в версии 2) 4 Плотность 1 Сохранить яркость |
| [PhflResourceVersion2](./phflresourceversion2/) | Класс PhflResource. Ресурс слоя коррекции Exposure. Версия 2 ( = 3 ) или ( = 2 ) 12 4 байта каждый для цвета XYZ (только в версии 3) 10 2 байта цветовое пространство, за которым следуют 4 * 2 байта цветового компонента (только в версии 2) 4 Плотность 1 Сохранить яркость |
| [PhflResourceVersion3](./phflresourceversion3/) | Класс PhflResource. Ресурс слоя коррекции Exposure. Версия 2 ( = 3 ) или ( = 2 ) 12 4 байта каждый для цвета XYZ (только в версии 3) 10 2 байта цветовое пространство, за которым следуют 4 * 2 байта цветового компонента (только в версии 2) 4 Плотность 1 Сохранить яркость |
| [PlacedResource](./placedresource/) | Определяет класс PlacedResource, который содержит общую информацию о размещённом слое или слое смарт‑объекта в файле PSD. Используется для поддержки слоёв смарт‑объектов в изображениях Adobe® Photoshop®. |
| [PlLdResource](./plldresource/) | Определяет класс PlLdResource, который содержит информацию о размещённом слое в файле PSD. Используется для поддержки слоёв смарт‑объектов в изображениях Adobe® Photoshop®. Был заменён классом SoLdResource в Adobe® Photoshop® CS3. |
| [PostResource](./postresource/) | Класс PostResource. Настройки слоя Posterize. |
| [PtFlResource](./ptflresource/) | Класс PtFlResource. Содержит данные слоя заполнения шаблоном. |
| [ShmdResource](./shmdresource/) | Класс ShmdResource. Настройки метаданных |
| [SmartObjectResource](./smartobjectresource/) | Определяет класс SmartObjectResource, который содержит информацию о слое смарт‑объекта в файле PSD. Это базовый класс для ресурсов Sold и Sole, используемый для поддержки слоёв смарт‑объектов в изображениях Adobe® Photoshop®. |
| [SmartResourceCreator](./smartresourcecreator/) | Определяет класс SmartResourceCreator, который может создавать ресурсы PlLd, SoLd и SoLe. Используется для поддержки слоёв умных объектов в изображениях Adobe® Photoshop®. |
| [SoCoResource](./socoresource/) | Класс SoCoResource. Этот ресурс содержит информацию о слоях заливки цветом. |
| [SoLdResource](./soldresource/) | Определяет класс SoLdResource, который содержит информацию о слое умного объекта в файле PSD. Используется для поддержки слоёв умных объектов в изображениях Adobe® Photoshop®. |
| [SoLeResource](./soleresource/) | Определяет класс SoLeResource, который содержит информацию о слое умного объекта в файле PSD. Используется для поддержки слоёв умных объектов со ссылками на внешние файлы в изображениях Adobe® Photoshop®. |
| [Txt2Resource](./txt2resource/) | Класс ресурса Txt2 |
| [TypeToolFontInfo](./typetoolfontinfo/) | Содержит информацию о шрифте инструмента «Текст». |
| [TypeToolInfo6Resource](./typetoolinfo6resource/) | Информация об инструменте «Текст». Для версии PSD 6.0 и выше. |
| [TypeToolInfoResource](./typetoolinforesource/) | Информация об инструменте «Текст». Для версии PSD ниже 6.0. |
| [TypeToolLineInfo](./typetoollineinfo/) | Информация о линии инструмента «Текст». |
| [TypeToolStyleInfo](./typetoolstyleinfo/) | Информация о стиле инструмента «Текст». |
| [UnknownResource](./unknownresource/) | Неизвестный ресурс. |
| [VectorPath](./vectorpath/) | Класс, содержащий векторные пути. |
| [VectorPathDataResource](./vectorpathdataresource/) | Класс VectorPathDataResource. Этот ресурс содержит информацию о векторной маске слоя. |
| [VibAResource](./vibaresource/) | Ресурс VibA. |
| [VmskResource](./vmskresource/) | Класс VmskResource. Этот ресурс содержит информацию о векторной маске слоя. |
| [VogkResource](./vogkresource/) | Ресурс данных происхождения вектора. |
| [VsmsResource](./vsmsresource/) | Класс VsmsResource. Этот ресурс содержит информацию о векторной маске слоя. |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IOSTypeStructureLoader](./iostypestructureloader/) | Загрузчик ресурса [`OSTypeStructure`](../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| [IPath](./ipath/) | Интерфейс описывает набор путей, присутствующих в слое Shape. |
| [IPathShape](./ipathshape/) | Фигура, полученная из узлов кривой Безье. |
| [IPlacedLayerResource](./iplacedlayerresource/) | Определяет интерфейс IPlacedLayerResource, который содержит информацию о размещённом слое в файле PSD. Это разметочный интерфейс, используемый для обозначения ресурсов PlLd, Sold и Sole в изображениях Adobe® Photoshop®. Используется для поддержки слоёв умных объектов в изображениях Adobe® Photoshop®. |
| [ISmartObjectLayerResource](./ismartobjectlayerresource/) | Определяет интерфейс ISmartObjectLayerResource, который содержит информацию о ресурсе слоя умного объекта в файле PSD. Это также разметочный интерфейс, используемый для обозначения как ресурсов Sold, так и Sole в изображениях Adobe® Photoshop®. |
## Перечисление

| Перечисление | Описание |
| --- | --- |
| [LayerLockType](./layerlocktype/) | Параметры блокировки слоя |
| [LayerSectionSubtype](./layersectionsubtype/) | Подтип секции |
| [LayerSectionType](./layersectiontype/) | Тип секции слоя |
| [LinkDataSourceType](./linkdatasourcetype/) | Определяет перечисление LinkDataSourceType для источников данных в ресурсе PSD link. |
| [LnsrResourceType](./lnsrresourcetype/) | Обнаружены возможные типы ресурсов Lnsr |
| [PlacedLayerType](./placedlayertype/) | Определяет перечисление PlacedLayerType для размещённого слоя ресурса PlLd. |
| [SheetColorHighlightEnum](./sheetcolorhighlightenum/) | Возможные цвета настройки Sheet color. Это декоративный цвет интерфейса слоя в списке слоёв в PS. |


