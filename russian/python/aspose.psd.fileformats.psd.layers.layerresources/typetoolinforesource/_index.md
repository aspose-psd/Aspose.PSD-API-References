---
title: "Класс TypeToolInfoResource"
type: docs
weight: 1000
url: /ru/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolinforesource/
---

**Summary:** The type tool information. For PSD version lower than 6.0.

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.TypeToolInfoResource

**Inheritance:** LayerResource

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [TypeToolInfoResource()](#TypeToolInfoResource__1) | Инициализирует новый экземпляр класса TypeToolInfoResource |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| PSB_RESOURCE_SIGNATURE [static] | int | r | Подпись ресурса, специфичная для PSB. |
| RESOURCE_SIGNATURE [static] | int | r | Общая подпись ресурса. |
| a_component | short | r/w | Получает или задает компонент. |
| b_component | short | r/w | Получает или задает компонент b. |
| character_count | int | r/w | Получает или задает количество символов. |
| color_space_value | short | r/w | Получает или задает значение цветового пространства. |
| font_version | short | r/w | Получает или задает версию шрифта. |
| fonts | [TypeToolFontInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolfontinfo) | r/w | Получает или задает шрифты. |
| fonts_count | short | r | Получает количество шрифтов. |
| g_component | short | r/w | Получает или задает компонент g. |
| horizontal_placement | int | r/w | Получает или задает горизонтальное размещение. |
| key | int | r | Получает ключ ресурса слоя. |
| длина | int | r | Получает длину ресурса слоя в байтах. |
| line_count | short | r | Получает количество строк. |
| lines | [TypeToolLineInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoollineinfo) | r/w | Получает или задает строки. |
| psd_version | int | r | Получает минимальную версию PSD, требуемую для ресурса слоя. 0 означает отсутствие ограничений. |
| r_component | short | r/w | Получает или задает компонент r. |
| scale_factor | int | r/w | Получает или задает коэффициент масштабирования. |
| selection_end | int | r/w | Получает или задает конец выделения. |
| selection_start | int | r/w | Получает или задает начало выделения. |
| signature | int | r | Получает подпись. |
| styles | [TypeToolStyleInfo[]](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/typetoolstyleinfo) | r/w | Получает или задает стили шрифта. |
| styles_count | short | r | Получает количество стилей. |
| transform_matrix | double | r/w | Получает или задает матрицу преобразования. |
| type_value | short | r/w | Получает или задает значение типа. |
| version | short | r/w | Получает или задает версию. |
| vertical_placement | int | r/w | Получает или задает вертикальное размещение. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [save(stream_container, psd_version)](#save_stream_container_psd_version_1) | Сохраняет указанный контейнер потока. |


### Constructor: TypeToolInfoResource() {#TypeToolInfoResource__1}


```
 TypeToolInfoResource() 
```

Инициализирует новый экземпляр класса TypeToolInfoResource

### Method: save(stream_container, psd_version) {#save_stream_container_psd_version_1}


```
 save(stream_container, psd_version) 
```

Сохраняет указанный контейнер потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | Контейнер потока. |
| psd_version | int | Версия PSD. |

