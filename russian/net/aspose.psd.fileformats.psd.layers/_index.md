---
title: Aspose.PSD.FileFormats.Psd.Layers
second_title: Справочник по Aspose.PSD для .NET API
description: Пространство имен содержит слои формата файла PSD.
type: docs
weight: 210
url: /ru/net/aspose.psd.fileformats.psd.layers/
---
Пространство имен содержит слои формата файла PSD.

## Классы

| Учебный класс | Описание |
| --- | --- |
| [BlendRange](./blendrange/) | Диапазон смешивания. |
| [ChannelInformation](./channelinformation/) | Информация о канале. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | Раздел маски глобального слоя. |
| [Layer](./layer/) | PSD-слой. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | Данные диапазонов смешивания слоев. |
| [LayerGroup](./layergroup/) | Групповой слой class |
| [LayerHashCalculator](./layerhashcalculator/) | Калькулятор хэшей для слоев PSD. Его можно использовать для поиска одинаковых или разных слоев в разных файлах PSD |
| [LayerMaskData](./layermaskdata/) | Определяет базовый класс LayerMaskData, который содержит информацию о данных маски слоя в файле PSD. Может помочь программно модифицировать файлы Adobe® Photoshop® и автоматизировать редактирование формата PSD. Если слой имеет только растровую маску, ImageData содержит растр байты данных маски. Если слой имеет только векторную маску, ImageData содержит байты растеризованных (кэшированных) данных векторной маски. Если слой имеет как слой, так и векторную маску, ImageData содержит растровую маску и растеризованную векторную маску вместе. [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)длина в байтах должна быть равна Ширина * Высота[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) properties. Обратите внимание, что простого удаления/добавления/обновления LayerMaskData недостаточно для корректного сохранения , так как каналы не обновляются; хотя это может обеспечить правильный рендеринг. [`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/) для этого следует использовать метод. |
| [LayerMaskDataFull](./layermaskdatafull/) | Определяет класс LayerMaskDataFull, который содержит информацию о данных маски в файле PSD layer , когда слой имеет как слойную, так и векторную маску. В противном случае[`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/) используется. ImageData содержит комбинацию растровой маски и растрированной векторной маски. Длина байтов ImageData должна быть равна MaskRectangle.Width * MaskRectangle.Height properties. |
| [LayerMaskDataShort](./layermaskdatashort/) | Определяет класс LayerMaskDataShort, который содержит информацию о данных маски в файле PSD layer , когда слой имеет только растровую или векторную маску, но не обе одновременно. В противном случае[`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/) используется. Если слой имеет только растровую маску, ImageData содержит байты данных растровой маски. Если слой имеет только векторную маску, ImageData содержит байты растрированных (кэшированных) данных векторной маски. [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/)длина в байтах должна быть равна Ширина * Высота[`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/) свойства. |
| [LayerResource](./layerresource/) | Представляет информацию о слое. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | Определить реестр ресурсов слоя для загрузки файлов PSD. |
| [LinkedLayersManager](./linkedlayersmanager/) | Класс диспетчера связанных слоев. |
| [SectionDividerLayer](./sectiondividerlayer/) | Слой-разделитель раздела для обозначения границ папки (группы слоев). |
| [TextLayer](./textlayer/) | Текстовый слой class |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | Базовый интерфейс для настроек заливки |
| [ILayerResourceLoader](./ilayerresourceloader/) | Загрузчик ресурсов слоя. |
## перечисление

| перечисление | Описание |
| --- | --- |
| [LayerFlags](./layerflags/) | Флаги слоя |
| [LayerMaskFlags](./layermaskflags/) | Маска слоя flags |


