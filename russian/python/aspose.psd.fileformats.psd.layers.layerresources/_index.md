---
title: "aspose.psd.fileformats.psd.layers.layerresources"
type: docs
weight: 330
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/
---




## **Classes**
| **Класс** | **Описание** |
| :- | :- |
| [AbddResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/abddresource/) | Данные информации о Artboard. |
| [AdjustmentLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/adjustmentlayerresource/) | Базовый класс для ресурсов слоёв коррекции |
| [AnimatedDataSectionStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/) | Раздел с анимированными данными. |
| [ArtBResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artbresource/) | Данные информации о Artboard для [Layer.resources](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). |
| [ArtDResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/artdresource/) | Данные информации о Artboard для [PsdImage.global_layer_resources](/psd/python-net/aspose.psd.fileformats.psd/psdimage/). |
| [BaseArtboardInfoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/baseartboardinforesource/) | Ресурс данных информации о Artboard. |
| [BlncResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blncresource/) | Класс BlncResource является ресурсом слоя коррекции цвета. |
| [BlwhResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/blwhresource/) | Класс BlwhResource является ресурсом слоя черно‑белой коррекции. |
| [BooleanResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/booleanresource/) | Класс BooleanResource. Это псевдо‑ресурс. В Photoshop его нет. |
| [BritResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/britresource/) | Класс BritResource. Ресурс слоя коррекции яркости/контраста. |
| [CgEdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cgedresource/) | Класс CgEdResource. Дополнительные данные генератора контента (Photoshop CS5) |
| [ClassID](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/classid/) | Объект PSD Class ID. |
| [ClblResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/clblresource/) | Класс ClblResource.<br/>            Этот ресурс содержит информацию о смешивании обрезанного элемента. |
| [CmlsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/cmlsresource/) | Класс CmlsResource. |
| [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) | [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) имеет 6 цветовых диапазонов, где можно изменить параметры HSV. <br/>            Каждый диапазон имеет 4 ключевых точки для определения границ диапазона. И это ColorRangeHsl |
| [CurvResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvresource/) | Класс CurvResource. Ресурс слоя коррекции кривых<br/>            1 байт - 0 если использовать кривые, 1 если использованы пиксели на карте<br/>            если 0 тогда:<br/>            2 байта - short. По умолчанию 1<br/>            4 байта - int. Используется только последний байт по биту. Первый бит для 1 канала, четвертый бит для 4 каналов, например<br/>            2 байта - количество точек short<br/>            4 байта * количество точек - точки кривой 2 short: первая позиция, вторая высота<br/>            4 байта - слово "Crv "<br/>            2 байта - short, по умолчанию 4 для кривых<br/>            4 байта - int. По умолчанию 1<br/>            4 байта - количество точек<br/>            4 байта * количество точек - точки кривой 2 short: первая позиция, вторая высота<br/>            0-4 байта - Ведущий для свёртки четырёх<br/>            если 1 тогда:<br/>            2 байта - short. По умолчанию 1<br/>            4 байта - int. Используется только последний байт. Один канал в одном бите. Первый бит для 1 канала, четвертый бит для 4 каналов, например<br/>            256 * количество изменённых каналов - упорядоченные значения канала в диапазоне 0 - 255<br/>            4 байта - слово "Crv "<br/>            2 байта - short. По умолчанию 3 для пикселей на карте<br/>            4 байта - int количество каналов<br/>            (2 + 256) байт - short 2 для индекса канала, 256 - упорядоченные значения канала в диапазоне 0 - 255 |
| [CurvesContinuousManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvescontinuousmanager/) | Менеджер слоя коррекции кривых, который управляет кривыми |
| [CurvesDiscreteManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesdiscretemanager/) | Менеджер слоя коррекции кривых, который управляет картой пикселей |
| [CurvesManager](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/curvesmanager/) | Базовый класс для управления CurvResource |
| [CustResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/custresource/) | Класс CustResource.<br/>            Этот ресурс содержит информацию о смешивании обрезанного элемента. |
| [ExpaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/exparesource/) | Класс ExpaResource. Ресурс слоя коррекции экспозиции |
| [FXidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/) | Ресурс Filter Effects содержит каналы, пользовательскую маску и листовую маску для умного фильтра. |
| [FillLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filllayerresource/) | Базовый класс для ресурсов слоя заполнения. |
| [FilterEffectMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata/) | Класс данных фильтра маски. |
| [FxrpResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxrpresource/) | Класс FxrpResource. Точка привязки слоя |
| [GdFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/gdflresource/) | Класс GdFlResource.<br/>            Этот ресурс содержит информацию о смешивании обрезанного элемента. |
| [GrdmResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/grdmresource/) | Класс GrdmResource. Содержит информацию о слое Gradient-Map. |
| [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) | Класс Hue2Resource. Ресурс слоя коррекции экспозиции |
| [IOSTypeStructureLoader](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iostypestructureloader/) | Загрузчик ресурса [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| [IPath](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipath/) | Интерфейс описывает набор путей, присутствующих в слое Shape. |
| [IPathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ipathshape/) | Форма из узлов кривой Безье. |
| [IPlacedLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/iplacedlayerresource/) | Определяет интерфейс IPlacedLayerResource, который содержит информацию о размещённом слое в файле PSD.<br/>            Это разметочный интерфейс, используемый для обозначения ресурсов PlLd, Sold и Sole в изображениях Adobe® Photoshop®.<br/>            Он используется для поддержки слоёв смарт‑объектов в изображениях Adobe® Photoshop®. |
| [ISmartObjectLayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ismartobjectlayerresource/) | Определяет интерфейс ISmartObjectLayerResource, который содержит информацию о ресурсе слоя смарт‑объекта в файле PSD.<br/>            Это также разметочный интерфейс, используемый для обозначения ресурсов Sold и Sole в изображениях Adobe® Photoshop®. |
| [InfxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/infxresource/) | Класс InfxResource.<br/>            Этот ресурс содержит информацию о смешивании обрезанного элемента. |
| [IopaResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ioparesource/) | Класс IopaResource.<br/>            Этот ресурс содержит информацию о свойстве непрозрачности заполнения из формы стиля слоя. |
| [KnkoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/knkoresource/) | Класс KnkoResource.<br/>            Этот ресурс содержит информацию о смешивании обрезанного элемента. |
| [LayerSectionResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionresource/) | Ресурс раздела слоёв. |
| [LclrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lclrresource/) | Класс LclrResource.<br/>            Этот ресурс содержит информацию о цвете слоя в списке слоёв PS. Это единственное |
| [LevelChannel](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levelchannel/) | Класс для работы с каналами в слое коррекции уровней |
| [LevlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/levlresource/) | Класс LevlResource. Ресурс слоя коррекции экспозиции |
| [Lfx2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lfx2resource/) | Ресурс Lfx2 (ресурс эффектов) |
| [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/) | Определяет класс источника данных liFD в файле PSD, который содержит информацию о встроенном файле.<br/>            Это часть API манипуляции форматом файлов PSD, помогающая изменять файлы Adobe® Photoshop®. |
| [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/) | Определяет класс LnkeDataSource, который содержит информацию о внешнем связанном файле.<br/>            Это часть API манипуляции форматом файлов PSD, который помогает изменять файлы Adobe® Photoshop®. |
| [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/) | Определяет класс LinkDataSource, который содержит информацию о связанном файле или ресурсе в файле PSD. |
| [LinkResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkresource/) | Определяет класс LinkResource, который содержит информацию о связанных или встроенных файлах в изображении формата PSD.<br/>            Ресурс ссылки может содержать несколько экземпляров [LinkDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/), к которым можно получить доступ через индексаторы в любом производном классе. |
| [LmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lmskresource/) | Ресурс LMsk. |
| [Lnk2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk2resource/) | Определяет класс, который содержит информацию о встроенных файлах в изображении формата PSD.<br/>            Ресурс ссылки может содержать несколько экземпляров [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/), к которым можно получить доступ через индексатор. |
| [Lnk3Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnk3resource/) | Определяет класс, который содержит информацию о встроенном файле в 32‑битном изображении PSD (по каналу).<br/>            Ресурс ссылки может содержать несколько экземпляров [LiFdDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifddatasource/), к которым можно получить доступ через индексатор. |
| [LnkeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnkeresource/) | Определяет класс LnkeResource, который содержит информацию о внешних связанных файлах или ресурсах в изображении формата PSD.<br/>            Ресурс ссылки может содержать несколько экземпляров [LiFeDataSource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/), к которым можно получить доступ через индексатор.<br/>            Это часть API манипуляции форматом файлов PSD, который помогает программно изменять файлы Adobe® Photoshop®. |
| [LnsrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresource/) | Класс lnsrResource. |
| [Lr16Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lr16resource/) | Ресурс lr16. |
| [Lr32Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lr32resource/) | Ресурс lr32. |
| [LrXxResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lrxxresource/) | Ресурс lrXX. |
| [LspfResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lspfresource/) | Защищённые настройки слоя |
| [LuniResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/luniresource/) | Ресурс имени слоя |
| [LyidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyidresource/) | Класс LyidResource. |
| [LyvrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lyvrresource/) | Ресурс, представляющий версию Photoshop слоя. |
| [MixrResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mixrresource/) | Класс MixrResource. Ресурс слоя регулировки микшера каналов |
| [MlstResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/mlstresource/) | Ресурс mlst.<br/>            Этот класс, среди прочего, содержит информацию о положении слоя на временной шкале. |
| [NvrtResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/nvrtresource/) | Класс NvrtResource. Ресурс слоя регулировки инвертирования. |
| [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/) | Представляет структуру типа ОС. |
| [OSTypeStructuresRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructuresregistry/) | Представляет реестр ресурсов [OSTypeStructure](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/). |
| [PathShape](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pathshape/) | Фигура из узлов кривой Безье. |
| [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/) | Класс PattResource. Ресурс с данными шаблона |
| [PattResourceData](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresourcedata/) | Класс для хранения данных шаблона ресурса [PattResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/pattresource/). |
| [PhflResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresource/) | Класс PhflResource. Ресурс слоя регулировки экспозиции<br/>            2 версии ( = 3 ) или ( = 2 )<br/>            12 по 4 байта для цвета XYZ (только в версии 3)<br/>            10 по 2 байта цветовое пространство, за которым следуют 4 × 2 байта цветовых компонентов (только в версии 2)<br/>            4 Плотность<br/>            1 Сохранить яркость |
| [PhflResourceVersion2](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion2/) | Класс PhflResource. Ресурс слоя регулировки экспозиции<br/>            2 версии ( = 3 ) или ( = 2 )<br/>            12 по 4 байта для цвета XYZ (только в версии 3)<br/>            10 по 2 байта цветовое пространство, за которым следуют 4 × 2 байта цветовых компонентов (только в версии 2)<br/>            4 Плотность<br/>            1 Сохранить яркость |
| [PhflResourceVersion3](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/phflresourceversion3/) | Класс PhflResource. Ресурс слоя регулировки экспозиции<br/>            2 версии ( = 3 ) или ( = 2 )<br/>            12 по 4 байта для цвета XYZ (только в версии 3)<br/>            10 по 2 байта цветовое пространство, за которым следуют 4 × 2 байта цветовых компонентов (только в версии 2)<br/>            4 Плотность<br/>            1 Сохранить яркость |
| [PlLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/plldresource/) | Определяет класс PlLdResource, который содержит информацию о размещённом слое в файле PSD.<br/>            Он используется для поддержки слоёв смарт‑объектов в изображениях Adobe� Photoshop�.<br/>            Был заменён классом SoLdResource в Adobe� Photoshop� CS3 |
| [PlacedResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedresource/) | Определяет класс PlacedResource, который содержит общую информацию о размещённом слое или слое смарт‑объекта в файле PSD.<br/>            Используется для поддержки слоёв смарт‑объектов в изображениях Adobe Photoshop. |
| [PostResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/postresource/) | Класс PostResource. Настройки слоя постеризации. |
| [PtFlResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/ptflresource/) | Класс PtFlResource. Содержит данные слоя заполнения узором. |
| [ShmdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/shmdresource/) | Класс ShmdResource. Настройки метаданных |
| [SmartObjectResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartobjectresource/) | Определяет класс SmartObjectResource, который содержит информацию о слое смарт‑объекта в файле PSD.<br/>            Является базовым классом для ресурсов Sold и Sole, используемых для поддержки слоёв смарт‑объектов в изображениях Adobe Photoshop. |
| [SmartResourceCreator](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/smartresourcecreator/) | Определяет класс SmartResourceCreator, который может создавать ресурсы PlLd, SoLd и SoLe.<br/>            Используется для поддержки слоёв смарт‑объектов в изображениях Adobe Photoshop. |
| [SoCoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/socoresource/) | Класс SoCoResource.<br/>            Этот ресурс содержит информацию о слоях заливки цветом |
| [SoLdResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soldresource/) | Определяет класс SoLdResource, который содержит информацию о слое смарт‑объекта в файле PSD.<br/>            Используется для поддержки слоёв смарт‑объектов в изображениях Adobe Photoshop. |
| [SoLeResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/soleresource/) | Определяет класс SoLeResource, который содержит информацию о слое смарт‑объекта в файле PSD.<br/>            Используется для поддержки слоёв смарт‑объектов со ссылками на внешние файлы в изображениях Adobe Photoshop. |
| [Txt2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/txt2resource/) | Класс ресурса Txt2 |
| [TypeToolFontInfo](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo/) | Содержит информацию о шрифте инструмента текста. |
| [TypeToolInfo6Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinfo6resource/) | Информация инструмента текста. Для версии PSD 6.0 и выше. |
| [TypeToolInfoResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/) | Информация инструмента текста. Для версии PSD ниже 6.0. |
| [TypeToolLineInfo](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo/) | Информация о строке инструмента текста. |
| [TypeToolStyleInfo](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo/) | Информация о стиле инструмента текста. |
| [UnknownResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/unknownresource/) | Неизвестный ресурс. |
| [VectorPath](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vectorpath/) | Класс, который содержит векторные пути. |
| [VectorPathDataResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/) | Класс VectorPathDataResource.<br/>            Этот ресурс содержит информацию о векторной маске слоя |
| [VibAResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vibaresource/) | Ресурс VibA. |
| [VmskResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vmskresource/) | Класс VmskResource.<br/>            Этот ресурс содержит информацию о векторной маске слоя |
| [VogkResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vogkresource/) | Ресурс данных векторного происхождения. |
| [VsmsResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/) | Класс VsmsResource.<br/>            Этот ресурс содержит информацию о векторной маске слоя |
## **Enumerations**
| **Перечисление** | **Описание** |
| :- | :- |
| [LayerLockType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layerlocktype/) | Параметры блокировки слоя |
| [LayerSectionSubtype](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectionsubtype/) | Подтип секции |
| [LayerSectionType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/layersectiontype/) | Тип секции слоя |
| [LinkDataSourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/linkdatasourcetype/) | Определяет перечисление LinkDataSourceType для источников данных в ресурсе PSD link. |
| [LnsrResourceType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/lnsrresourcetype/) | Обнаружены возможные типы ресурсов Lnsr |
| [PlacedLayerType](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/placedlayertype/) | Определяет перечисление PlacedLayerType для ресурса размещённого слоя PlLd. |
| [SheetColorHighlightEnum](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/sheetcolorhighlightenum/) | Возможные цвета настройки Sheet color.<br/>            Это декоративный цвет интерфейса слоя в списке слоёв в PS |
