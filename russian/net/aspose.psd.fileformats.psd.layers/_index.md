---
title: "Aspose.PSD.FileFormats.Psd.Layers"
second_title: "Справочник API Aspose.PSD для .NET"
description: "Пространство имён содержит слои формата файла PSD."
type: docs
weight: 230
url: /ru/net/aspose.psd.fileformats.psd.layers/
---
{{< psd/tize >}}
Пространство имён содержит слои формата файлов PSD.

## Классы

| Класс | Описание |
| --- | --- |
| [ArtboardLayer](./artboardlayer/) | Класс слоя артборда. |
| [BlendRange](./blendrange/) | Диапазон смешивания. |
| [ChannelInformation](./channelinformation/) | Информация о канале. |
| [GlobalLayerMaskInfo](./globallayermaskinfo/) | Глобальный раздел маски слоя. |
| [Layer](./layer/) | Слой PSD. |
| [LayerBlendingRangesData](./layerblendingrangesdata/) | Данные диапазонов смешивания слоя. |
| [LayerGroup](./layergroup/) | Класс группы слоёв. |
| [LayerHashCalculator](./layerhashcalculator/) | Калькулятор хешей для слоёв PSD. Может использоваться для поиска одинаковых или разных слоёв в разных файлах PSD. |
| [LayerMaskData](./layermaskdata/) | Определяет базовый класс LayerMaskData, который содержит информацию о данных маски слоя в файле PSD. Он может помочь программно изменять файлы Adobe® Photoshop® и автоматизировать редактирование формата PSD. Если у слоя есть только растровая маска, ImageData содержит байты данных растровой маски. Если у слоя есть только векторная маска, ImageData содержит байты данных векторной маски, растрированные (кешированные). Если у слоя есть как растровая, так и векторная маски, ImageData содержит комбинированные данные растровой маски и растрированной векторной маски. Длина байтов [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) должна быть равна Width * Height свойств [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/). Обратите внимание, что простое удаление/добавление/обновление LayerMaskData недостаточно для корректного сохранения, так как каналы не обновляются; хотя это может обеспечить правильное отображение. Для этого следует использовать метод [`AddLayerMask`](../aspose.psd.fileformats.psd.layers/layer/addlayermask/). |
| [LayerMaskDataFull](./layermaskdatafull/) | Определяет класс LayerMaskDataFull, который содержит информацию о данных маски в слое файла PSD, когда слой имеет как растровую, так и векторную маски. В противном случае используется [`LayerMaskDataShort`](../aspose.psd.fileformats.psd.layers/layermaskdatashort/). ImageData содержит комбинированные данные растровой маски и растрированной векторной маски. Длина байтов ImageData должна быть равна свойствам MaskRectangle.Width * MaskRectangle.Height. |
| [LayerMaskDataShort](./layermaskdatashort/) | Определяет класс LayerMaskDataShort, который содержит информацию о данных маски в слое файла PSD, когда слой имеет только растровую или векторную маску, но не обе. В противном случае используется [`LayerMaskDataFull`](../aspose.psd.fileformats.psd.layers/layermaskdatafull/). Если у слоя есть только растровая маска, ImageData содержит байты данных растровой маски. Если у слоя есть только векторная маска, ImageData содержит байты данных векторной маски, растрированные (кешированные). Длина байтов [`ImageData`](../aspose.psd.fileformats.psd.layers/layermaskdata/imagedata/) должна быть равна Width * Height свойств [`MaskRectangle`](../aspose.psd.fileformats.psd.layers/layermaskdata/maskrectangle/). |
| [LayerResource](./layerresource/) | Представляет информацию о слое. |
| [LayerResourcesRegistry](./layerresourcesregistry/) | Определяет реестр ресурсов слоёв для загрузки файлов PSD. |
| [LinkedLayersManager](./linkedlayersmanager/) | Класс менеджера связанных слоёв. |
| [SectionDividerLayer](./sectiondividerlayer/) | Слой-разделитель секции, отмечающий границы папки (группы слоёв). |
| [ShapeLayer](./shapelayer/) | Слой Shape. Инкапсулирует логику работы с слоем Shape и связанными ресурсами. |
| [TextLayer](./textlayer/) | Класс текстового слоя. |
## Интерфейсы

| Интерфейс | Описание |
| --- | --- |
| [IGradientColorPoint](./igradientcolorpoint/) | Базовый интерфейс для настроек заливки |
| [ILayerResourceLoader](./ilayerresourceloader/) | Загрузчик ресурсов слоя. |
| [IShapeLayer](./ishapelayer/) | Описывает свойства слоя Shape. |
## Перечисление

| Перечисление | Описание |
| --- | --- |
| [LayerFlags](./layerflags/) | Флаги слоя. |
| [LayerMaskFlags](./layermaskflags/) | Флаги маски слоя. |


