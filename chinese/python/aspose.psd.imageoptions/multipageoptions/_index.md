---
title: "MultiPageOptions 类"
type: docs
weight: 70
url: /zh/python-net/aspose.psd.imageoptions/multipageoptions/
---

**Summary:** Base class for multiple pages supported formats

**Module:** [aspose.psd.imageoptions](/psd/python-net/aspose.psd.imageoptions/)

**Full Name:** aspose.psd.imageoptions.MultiPageOptions

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MultiPageOptions()](#MultiPageOptions__1) | 初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。 |
| [MultiPageOptions(page)](#MultiPageOptions_page_2) | 初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。 |
| [MultiPageOptions(page, export_area)](#MultiPageOptions_page_export_area_3) | 初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。 |
| [MultiPageOptions(page_titles)](#MultiPageOptions_page_titles_4) | 初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。 |
| [MultiPageOptions(page_titles, export_area)](#MultiPageOptions_page_titles_export_area_5) | 初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。 |
| [MultiPageOptions(pages)](#MultiPageOptions_pages_6) | 初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。 |
| [MultiPageOptions(pages, export_area)](#MultiPageOptions_pages_export_area_7) | 初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。 |
| [MultiPageOptions(range)](#MultiPageOptions_range_8) | 初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。 |
| [MultiPageOptions(range, export_area)](#MultiPageOptions_range_export_area_9) | 初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。 |
| [MultiPageOptions(ranges)](#MultiPageOptions_ranges_10) | 初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。 |
| [MultiPageOptions(ranges, export_area)](#MultiPageOptions_ranges_export_area_11) | 初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r/w | 获取或设置导出区域。 |
| merge_layers | bool | 读/写 | 获取或设置一个值，指示是否 [merege layers]。 |
| mode | [MultiPageMode](/psd/python-net/aspose.psd.imageoptions/multipagemode) | r/w | 获取或设置模式。 |
| output_layers_names | 字符串 | 读/写 | 获取或设置输出层名称（如果导出格式支持层命名，例如 Psd，则有效） |
| page_rasterization_options | [VectorRasterizationOptions[]](/psd/python-net/aspose.psd.imageoptions/vectorrasterizationoptions) | r/w | 获取或设置页面光栅化选项。 |
| page_titles | 字符串 | 读/写 | 获取或设置页面标题。 |
| pages | int | 读/写 | 获取或设置页面。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [init_pages(ranges)](#init_pages_ranges_1) | 从范围数组初始化页面。 |


### Constructor: MultiPageOptions() {#MultiPageOptions__1}


```
 MultiPageOptions() 
```

初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。

### Constructor: MultiPageOptions(page) {#MultiPageOptions_page_2}


```
 MultiPageOptions(page) 
```

初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| page | int |  |

### Constructor: MultiPageOptions(page, export_area) {#MultiPageOptions_page_export_area_3}


```
 MultiPageOptions(page, export_area) 
```

初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| page | int |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 导出区域。 |

### Constructor: MultiPageOptions(page_titles) {#MultiPageOptions_page_titles_4}


```
 MultiPageOptions(page_titles) 
```

初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| page_titles | 字符串 | 页面标题。 |

### Constructor: MultiPageOptions(page_titles, export_area) {#MultiPageOptions_page_titles_export_area_5}


```
 MultiPageOptions(page_titles, export_area) 
```

初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| page_titles | 字符串 | 页面标题。 |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 导出区域。 |

### Constructor: MultiPageOptions(pages) {#MultiPageOptions_pages_6}


```
 MultiPageOptions(pages) 
```

初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pages | int | 页面。 |

### Constructor: MultiPageOptions(pages, export_area) {#MultiPageOptions_pages_export_area_7}


```
 MultiPageOptions(pages, export_area) 
```

初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| pages | int | 页面数组。 |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 导出区域。 |

### Constructor: MultiPageOptions(range) {#MultiPageOptions_range_8}


```
 MultiPageOptions(range) 
```

初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |

### Constructor: MultiPageOptions(range, export_area) {#MultiPageOptions_range_export_area_9}


```
 MultiPageOptions(range, export_area) 
```

初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| range | [IntRange](/psd/python-net/aspose.psd/intrange) |  |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 导出区域。 |

### Constructor: MultiPageOptions(ranges) {#MultiPageOptions_ranges_10}


```
 MultiPageOptions(ranges) 
```

初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | 该 [IntRange](/psd/python-net/aspose.psd/intrange/)。 |

### Constructor: MultiPageOptions(ranges, export_area) {#MultiPageOptions_ranges_export_area_11}


```
 MultiPageOptions(ranges, export_area) 
```

初始化一个新的 [MultiPageOptions](/psd/python-net/aspose.psd.imageoptions/multipageoptions/) 类的实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | 该 [IntRange](/psd/python-net/aspose.psd/intrange/)。 |
| export_area | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 导出区域。 |

### Method: init_pages(ranges) {#init_pages_ranges_1}


```
 init_pages(ranges) 
```

从范围数组初始化页面。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| ranges | [IntRange[]](/psd/python-net/aspose.psd/intrange) | 范围。 |

