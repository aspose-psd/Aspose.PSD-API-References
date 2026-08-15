---
title: "Класс FXidResource"
type: docs
weight: 290
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/
---

**Summary:** The Filter Effects resource contains channels, a user mask, and a sheet mask for the smart filter.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.FXidResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [FXidResource(key, version, filter_effect_masks)](#FXidResource_key_version_filter_effect_masks_1) | Инициализирует новый экземпляр класса [FXidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| F_EID_TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента FEid. |
| F_XID_TYPE_TOOL_KEY [static] | int | r | Ключ информации о типе инструмента FXid. |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| filter_effect_masks | [FilterEffectMaskData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata) | r | Получает маски эффектов фильтра. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| signature | int | r | Получает подпись. |
| version | int | r | Получает версию. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет ресурс в указанный контейнер потока. |


### Constructor: FXidResource(key, version, filter_effect_masks) {#FXidResource_key_version_filter_effect_masks_1}


```
 FXidResource(key, version, filter_effect_masks) 
```

Инициализирует новый экземпляр класса [FXidResource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/fxidresource/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| key | int | Ключ ресурса. |
| version | int | Версия. |
| filter_effect_masks | [FilterEffectMaskData[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/filtereffectmaskdata) | Маски эффектов фильтра. |

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Сохраняет ресурс в указанный контейнер потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока для сохранения. |
| psd_version | int | Версия PSD. |

