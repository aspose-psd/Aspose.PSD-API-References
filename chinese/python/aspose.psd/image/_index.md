---
title: "Image 类"
type: docs
weight: 2170
url: /zh/python-net/aspose.psd/image/
---

**Summary:** The image is the base class for all type of images.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Image

**Inheritance:** IObjectWithBounds, DataStreamSupporter

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | 读/写 | 获取或设置指示是否自动调整调色板的值。 |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | 获取或设置背景颜色的值。 |
| bits_per_pixel | int | r | 获取图像每像素位数。 |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | 获取图像边界。 |
| buffer_size_hint | int | 读/写 | 获取或设置缓冲区大小提示，该提示定义了所有内部缓冲区的最大允许大小。 |
| container | [Image](/psd/python-net/aspose.psd/image) | r | 获取 [Image](/psd/python-net/aspose.psd/image/) 容器。 |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | 获取对象的数据流。 |
| 已释放 | bool | r | 获取一个值，指示此实例是否已释放。 |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | 获取文件格式的值 |
| has_background_color | bool | 读/写 | 获取或设置一个值，指示图像是否具有背景颜色。 |
| height | int | r | 获取图像高度。 |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | 获取或设置中断监视器。 |
| is_cached | bool | r | 获取一个值，指示对象的数据当前是否已缓存且无需读取数据。 |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | 获取或设置颜色调色板。当像素直接表示时，不使用颜色调色板。 |
| size | [Size](/psd/python-net/aspose.psd/size) | r | 获取图像尺寸。 |
| use_palette | bool | r | 获取一个值，指示是否使用图像调色板。 |
| width | int | r | 获取图像宽度。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| cache_data() | 缓存数据，并确保不会从底层 [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) 进行额外的数据加载。 |
| [can_load(file_path)](#can_load_file_path_1) | 确定是否可以从指定的文件路径加载图像。 |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | 确定是否可以从指定的文件路径加载图像，且可选地使用指定的打开选项。 |
| [can_load(stream)](#can_load_stream_3) | 确定是否可以从指定的流加载图像。 |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | 确定是否可以从指定的流加载图像，且可选地使用指定的 <paramref name="loadOptions" />。 |
| [can_save(options)](#can_save_options_5) | 确定是否可以将图像保存为由传入的保存选项表示的指定文件格式。 |
| [create(image_options, width, height)](#create_image_options_width_height_6) | 使用指定的创建选项创建新图像。 |
| [get_default_options(args)](#get_default_options_args_7) | 获取默认选项。 |
| [get_file_format(file_path)](#get_file_format_file_path_8) | 获取文件格式。 |
| [get_file_format(stream)](#get_file_format_stream_9) | 获取文件格式。 |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_10) | 获取适合当前图像的矩形。 |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_11) | 获取适合当前图像的矩形。 |
| [get_original_options()](#get_original_options__12) | 获取基于原始文件设置的选项。<br/>            这有助于保持原始图像的位深度和其他参数不变。<br/>            例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) 方法保存，它将生成每像素 8 位的输出 PNG 图像。<br/>            为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项并将它们<br/>            作为第二个参数传递给 [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) 方法。 |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_13) | 获取等比例高度。 |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_14) | 获取等比例宽度。 |
| [load(file_path)](#load_file_path_15) | 从指定文件加载新图像。 |
| [load(file_path, load_options)](#load_file_path_load_options_16) | 从指定文件加载新图像。 |
| [load(stream)](#load_stream_17) | 从指定流加载新图像。 |
| [load(stream, load_options)](#load_stream_load_options_18) | 从指定流加载新图像。 |
| [resize(new_width, new_height)](#resize_new_width_new_height_19) | 调整图像大小。使用默认的 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)。 |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_20) | 调整图像大小。 |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_21) | 调整图像大小。 |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_22) | 等比例调整高度。 |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_23) | 等比例调整高度。 |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_24) | 等比例调整高度。 |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_25) | 等比例调整宽度。使用默认的 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)。 |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_26) | 等比例调整宽度。 |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_27) | 等比例调整宽度。 |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_28) | 旋转、翻转或同时旋转并翻转图像。 |
| save() | 将图像数据保存到底层流。 |
| [save(file_path)](#save_file_path_29) | 将对象的数据保存到指定的文件位置。 |
| [save(file_path, options)](#save_file_path_options_30) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_31) | 根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。 |
| [save(file_path, over_write)](#save_file_path_over_write_32) | 将对象的数据保存到指定的文件位置。 |
| [save(stream)](#save_stream_33) | 将对象的数据保存到指定的流中。 |
| [save(stream, options_base)](#save_stream_options_base_34) | 根据保存选项，将图像的数据以指定的文件格式保存到指定的流中。 |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_35) | 根据保存选项，将图像的数据以指定的文件格式保存到指定的流中。 |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_36) | 设置图像调色板。 |


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


```
 can_load(file_path) 
```

确定是否可以从指定的文件路径加载图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 文件路径。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <c>true</c> 如果可以从指定文件加载图像；否则为 <c>false</c>。 |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


```
 can_load(file_path, load_options) 
```

确定是否可以从指定的文件路径加载图像，且可选地使用指定的打开选项。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 文件路径。 |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | 加载选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <c>true</c> 如果可以从指定文件加载图像；否则为 <c>false</c>。 |


### Method: can_load(stream)  [static] {#can_load_stream_3}


```
 can_load(stream) 
```

确定是否可以从指定的流加载图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 要加载的流。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <c>true</c> 如果可以从指定流加载图像；否则为 <c>false</c>。 |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


```
 can_load(stream, load_options) 
```

确定是否可以从指定的流加载图像，且可选地使用指定的 <paramref name="loadOptions" />。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 要加载的流。 |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | 加载选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <c>true</c> 如果可以从指定流加载图像；否则为 <c>false</c>。 |


### Method: can_save(options) {#can_save_options_5}


```
 can_save(options) 
```

确定是否可以将图像保存为由传入的保存选项表示的指定文件格式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 要使用的保存选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <c>true</c> 如果可以使用传入的保存选项将图像保存为指定的文件格式；否则为 <c>false</c>。 |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_6}


```
 create(image_options, width, height) 
```

使用指定的创建选项创建新图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 图像选项。 |
| width | int | 宽度。 |
| height | int | 高度。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | 新创建的图像。 |


### Method: get_default_options(args) {#get_default_options_args_7}


```
 get_default_options(args) 
```

获取默认选项。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| args | object | 参数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 默认选项 |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_8}


```
 get_file_format(file_path) 
```

获取文件格式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 文件路径。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | 确定的文件格式。 |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_9}


```
 get_file_format(stream) 
```

获取文件格式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 流。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | 确定的文件格式。 |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_10}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

获取适合当前图像的矩形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 获取适配矩形的矩形。 |
| pixels | int | 32 位 ARGB 像素。 |
| width | int | 对象宽度。 |
| height | int | 对象高度。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 适配矩形，若未找到适配矩形则抛出异常。 |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_11}


```
 get_fitting_rectangle(rectangle, width, height) 
```

获取适合当前图像的矩形。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 获取适配矩形的矩形。 |
| width | int | 对象宽度。 |
| height | int | 对象高度。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | 适配矩形，若未找到适配矩形则抛出异常。 |


### Method: get_original_options() {#get_original_options__12}


```
 get_original_options() 
```

获取基于原始文件设置的选项。<br/>            这有助于保持原始图像的位深度和其他参数不变。<br/>            例如，如果我们加载一张每像素 1 位的黑白 PNG 图像，然后使用<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) 方法保存，它将生成每像素 8 位的输出 PNG 图像。<br/>            为避免这种情况并以每像素 1 位保存 PNG 图像，请使用此方法获取相应的保存选项并将它们<br/>            作为第二个参数传递给 [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) 方法。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 基于原始文件设置的选项。 |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_13}


```
 get_proportional_height(width, height, new_width) 
```

获取等比例高度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| width | int | 宽度。 |
| height | int | 高度。 |
| new_width | int | 新的宽度。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 等比例高度。 |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_14}


```
 get_proportional_width(width, height, new_height) 
```

获取等比例宽度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| width | int | 宽度。 |
| height | int | 高度。 |
| new_height | int | 新的高度。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 等比例宽度。 |


### Method: load(file_path)  [static] {#load_file_path_15}


```
 load(file_path) 
```

从指定文件加载新图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 加载图像的文件路径。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | 已加载的图像。 |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_16}


```
 load(file_path, load_options) 
```

从指定文件加载新图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 加载图像的文件路径。 |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | 加载选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | 已加载的图像。 |


### Method: load(stream)  [static] {#load_stream_17}


```
 load(stream) 
```

从指定流加载新图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 加载图像的流。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | 已加载的图像。 |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_18}


```
 load(stream, load_options) 
```

从指定流加载新图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 加载图像的流。 |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | 加载选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | 已加载的图像。 |


### Method: resize(new_width, new_height) {#resize_new_width_new_height_19}


```
 resize(new_width, new_height) 
```

调整图像大小。使用默认的 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| new_height | int | 新的高度。 |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_20}


```
 resize(new_width, new_height, resize_type) 
```

调整图像大小。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| new_height | int | 新的高度。 |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | 调整大小的类型。 |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_21}


```
 resize(new_width, new_height, settings) 
```

调整图像大小。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| new_height | int | 新的高度。 |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | 调整大小的设置。 |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_22}


```
 resize_height_proportionally(new_height) 
```

等比例调整高度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_height | int | 新的高度。 |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_23}


```
 resize_height_proportionally(new_height, resize_type) 
```

等比例调整高度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_height | int | 新的高度。 |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | 调整大小的类型。 |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_24}


```
 resize_height_proportionally(new_height, settings) 
```

等比例调整高度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_height | int | 新的高度。 |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | 图像调整大小设置。 |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_25}


```
 resize_width_proportionally(new_width) 
```

等比例调整宽度。使用默认的 [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_width | int | 新的宽度。 |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_26}


```
 resize_width_proportionally(new_width, resize_type) 
```

等比例调整宽度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | 调整大小的类型。 |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_27}


```
 resize_width_proportionally(new_width, settings) 
```

等比例调整宽度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_width | int | 新的宽度。 |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | 图像调整大小设置。 |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_28}


```
 rotate_flip(rotate_flip_type) 
```

旋转、翻转或同时旋转并翻转图像。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | 旋转翻转的类型。 |

### Method: save(file_path) {#save_file_path_29}


```
 save(file_path) 
```

将对象的数据保存到指定的文件位置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 用于保存对象数据的文件路径。 |

### Method: save(file_path, options) {#save_file_path_options_30}


```
 save(file_path, options) 
```

根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 文件路径。 |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 选项。 |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_31}


```
 save(file_path, options, bounds_rectangle) 
```

根据保存选项，将对象的数据以指定的文件格式保存到指定的文件位置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 文件路径。 |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 选项。 |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 目标图像边界矩形。将空矩形设置为使用源边界。 |

### Method: save(file_path, over_write) {#save_file_path_over_write_32}


```
 save(file_path, over_write) 
```

将对象的数据保存到指定的文件位置。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_path | 字符串 | 用于保存对象数据的文件路径。 |
| over_write | bool | 如果设置为 <c>true</c>，则覆盖文件内容；否则将追加。 |

### Method: save(stream) {#save_stream_33}


```
 save(stream) 
```

将对象的数据保存到指定的流中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于保存对象数据的流。 |

### Method: save(stream, options_base) {#save_stream_options_base_34}


```
 save(stream, options_base) 
```

根据保存选项，将图像的数据以指定的文件格式保存到指定的流中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于保存图像数据的流。 |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 保存选项。 |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_35}


```
 save(stream, options_base, bounds_rectangle) 
```

根据保存选项，将图像的数据以指定的文件格式保存到指定的流中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 流 | _io.BufferedRandom | 用于保存图像数据的流。 |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | 保存选项。 |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | 目标图像边界矩形。设置为空矩形以使用源边界。 |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_36}


```
 set_palette(palette, update_colors) 
```

设置图像调色板。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | 要设置的调色板。 |
| update_colors | bool | 如果设置为 <c>true</c>，颜色将根据新调色板进行更新；否则颜色索引保持不变。请注意，如果某些索引没有对应的调色板条目，未更改的索引可能在加载时导致图像崩溃。 |

