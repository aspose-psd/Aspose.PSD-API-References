---
title: "ColorRangeHsl 类"
type: docs
weight: 180
url: /zh/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/
---

**Summary:** [Hue2Resource](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/hue2resource/) has 6 color ranges where you can change HSV parameters. <br/>            Every range has 4 key points to identify range borders. And it's ColorRangeHsl

**Module:** [aspose.psd.fileformats.psd.layers.layerresources](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/)

**Full Name:** aspose.psd.fileformats.psd.layers.layerresources.ColorRangeHsl

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorRangeHsl()](#ColorRangeHsl__1) | 初始化 [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) 类的新实例。 |
| [ColorRangeHsl(data)](#ColorRangeHsl_data_2) | 初始化 [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| 色相 | short | 读/写 | 获取或设置色相。 |
| left_border | short | 读/写 | 获取或设置左边界。 |
| 亮度 | short | 读/写 | 获取或设置亮度。 |
| most_left_border | short | 读/写 | 获取或设置最左边界。 |
| most_right_border | short | 读/写 | 获取或设置最右边界。 |
| right_border | short | 读/写 | 获取或设置右边界。 |
| 饱和度 | short | 读/写 | 获取或设置饱和度。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_range_coefficient(hue)](#get_range_coefficient_hue_1) | 获取范围系数。 |
| [is_hue_in_big_range(hue)](#is_hue_in_big_range_hue_2) | 确定色相是否在大范围内。 |
| [is_hue_in_small_range(hue)](#is_hue_in_small_range_hue_3) | 确定色相是否在小范围内。 |
| [save(stream_container)](#save_stream_container_4) | 将数据保存到指定的流容器。 |


### Constructor: ColorRangeHsl() {#ColorRangeHsl__1}


```
 ColorRangeHsl() 
```

初始化 [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) 类的新实例。

### Constructor: ColorRangeHsl(data) {#ColorRangeHsl_data_2}


```
 ColorRangeHsl(data) 
```

初始化 [ColorRangeHsl](/psd/python-net/aspose.psd.fileformats.psd.layers.layerresources/colorrangehsl/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 数据 | byte | 颜色范围数据。 |

### Method: get_range_coefficient(hue) {#get_range_coefficient_hue_1}


```
 get_range_coefficient(hue) 
```

获取范围系数。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 色相 | double | 色相值。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| double | 饱和度范围系数。 |


### Method: is_hue_in_big_range(hue) {#is_hue_in_big_range_hue_2}


```
 is_hue_in_big_range(hue) 
```

确定色相是否在大范围内。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 色相 | double | 色相值。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果色相在大范围内则为<c>true</c>；否则为<c>false</c>。 |


### Method: is_hue_in_small_range(hue) {#is_hue_in_small_range_hue_3}


```
 is_hue_in_small_range(hue) 
```

确定色相是否在小范围内。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 色相 | double | 色相值。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <c>true</c> 如果色相在小范围内；否则为 <c>false</c>。 |


### Method: save(stream_container) {#save_stream_container_4}


```
 save(stream_container) 
```

将数据保存到指定的流容器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | 流容器。 |

