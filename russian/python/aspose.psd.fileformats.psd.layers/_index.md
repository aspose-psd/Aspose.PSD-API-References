---
title: "aspose.psd.fileformats.psd.layers"
type: docs
weight: 260
url: /ru/python-net/aspose.psd.fileformats.psd.layers/
---




## **Classes**
| **Класс** | **Описание** |
| :- | :- |
| [ArtboardLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/artboardlayer/) | Класс слоя артборда. |
| [BlendRange](/psd/python-net/aspose.psd.fileformats.psd.layers/blendrange/) | Диапазон смешивания. |
| [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation/) | Информация о канале. |
| [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | Раздел глобальной маски слоя. |
| [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint/) | Базовый интерфейс для настроек заливки |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/) | Загрузчик ресурсов слоя. |
| [IShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/ishapelayer/) | Описывает свойства слоя Shape. |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | Слой psd. |
| [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata/) | Данные диапазонов наложения слоя. |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | Класс группового слоя |
| [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) | Калькулятор хешей для слоёв PSD. Может использоваться для поиска одинаковых или разных слоёв в разных PSD‑файлах |
| [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) | Определяет базовый класс LayerMaskData, который содержит информацию о данных маски слоя в файле PSD.<br/>            Он может помочь программно изменять файлы Adobe® Photoshop® и автоматизировать редактирование формата PSD.<br/>            Если у слоя есть только растровая маска, ImageData содержит байты данных растровой маски.<br/>            Если у слоя есть только векторная маска, ImageData содержит байты растровых (кешированных) данных векторной маски.<br/>            Если у слоя есть как растровая, так и векторная маска, ImageData содержит комбинированные данные растровой маски и растровой векторной маски.<br/>            Длина байтов [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) должна быть равна Width * Height свойств [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/).<br/>            Обратите внимание, что простое удаление / добавление / обновление LayerMaskData недостаточно для корректного сохранения,<br/>            поскольку каналы не обновляются; однако это может обеспечить правильное рендеринг.<br/>            Для этого следует использовать метод [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/). |
| [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) | Определяет класс LayerMaskDataFull, который содержит информацию о данных маски в слое файла PSD<br/>            когда слой имеет как слой‑маску, так и векторную маску. В противном случае используется [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/).<br/>            ImageData содержит комбинированные данные растровой маски и растровой векторной маски.<br/>            Длина байтов ImageData должна быть равна свойствам MaskRectangle.Width * MaskRectangle.Height. |
| [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) | Определяет класс LayerMaskDataShort, который содержит информацию о данных маски в слое файла PSD<br/>            когда слой имеет только растровую или векторную маску, но не обе. В противном случае используется [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/).<br/>            Если у слоя есть только растровая маска, ImageData содержит байты данных растровой маски.<br/>            Если у слоя есть только векторная маска, ImageData содержит байты растровых (кешированных) данных векторной маски.<br/>            Длина байтов [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) должна быть равна Width * Height свойств [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/). |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | Представляет информацию о слое. |
| [LayerResourcesRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/) | Определяет реестр ресурсов слоёв для загрузки PSD‑файлов. |
| [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | Класс менеджера связанных слоёв. |
| [SectionDividerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/) | Слой-разделитель секции, отмечающий границы папки (группы слоёв). |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | Слой Shape. Инкапсулирует логику работы со слоем Shape и связанными ресурсами. |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | Класс текстового слоя |
## **Enumerations**
| **Перечисление** | **Описание** |
| :- | :- |
| [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags/) | Флаги слоя |
| [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags/) | Флаги маски слоя |
