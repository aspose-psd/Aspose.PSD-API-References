---
title: "فئة Image"
type: docs
weight: 2170
url: /ar/python-net/aspose.psd/image/
---

**Summary:** The image is the base class for all type of images.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Image

**Inheritance:** IObjectWithBounds, DataStreamSupporter

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| تعديل_تلقائي_لوحة_الألوان | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كان تعديل اللوحة تلقائيًا. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | يحصل أو يضبط قيمة للون الخلفية. |
| بتات_لكل_بكسل | int | r | يحصل على عدد بتات الصورة لكل بكسل. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | يحصل على حدود الصورة. |
| تلميح_حجم_المخزن | int | r/w | يحصل أو يعيّن تلميح حجم المخزن المؤقت الذي يُعرّف كحد أقصى مسموح به لجميع المخازن الداخلية. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | يحصل على حاوية [Image](/psd/python-net/aspose.psd/image/). |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | يحصل على تدفق بيانات الكائن. |
| disposed | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن قد تم التخلص منه. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | يحصل على قيمة تنسيق الملف |
| has_background_color | bool | r/w | يحصل أو يضبط قيمة تشير إلى ما إذا كانت الصورة لديها لون خلفية. |
| الارتفاع | int | r | يحصل على ارتفاع الصورة. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | يحصل أو يضبط مراقب المقاطعة. |
| is_cached | bool | r | يحصل على قيمة تشير إلى ما إذا كانت بيانات الكائن مخزنة مؤقتاً حالياً ولا يلزم قراءة البيانات. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | يحصل أو يعيّن لوحة الألوان. لا تُستخدم لوحة الألوان عندما يتم تمثيل البكسلات مباشرة. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | يحصل على حجم الصورة. |
| use_palette | bool | r | يحصل على قيمة تشير إلى ما إذا كانت لوحة ألوان الصورة مستخدمة. |
| width | int | r | يحصل على عرض الصورة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| cache_data() | يقوم بتخزين البيانات مؤقتًا ويضمن عدم تحميل بيانات إضافية من [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/). |
| [can_load(file_path)](#can_load_file_path_1) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واختياريًا باستخدام خيارات الفتح المحددة. |
| [can_load(stream)](#can_load_stream_3) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد. |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واختياريًا باستخدام <paramref name=\"loadOptions\" /> المحدد. |
| [can_save(options)](#can_save_options_5) | يحدد ما إذا كان يمكن حفظ الصورة إلى تنسيق الملف المحدد الممثل بخيارات الحفظ الممررة. |
| [create(image_options, width, height)](#create_image_options_width_height_6) | ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة. |
| [get_default_options(args)](#get_default_options_args_7) | يحصل على الخيارات الافتراضية. |
| [get_file_format(file_path)](#get_file_format_file_path_8) | يحصل على تنسيق الملف. |
| [get_file_format(stream)](#get_file_format_stream_9) | يحصل على تنسيق الملف. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_10) | يحصل على المستطيل الذي يتناسب مع الصورة الحالية. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_11) | يحصل على المستطيل الذي يتناسب مع الصورة الحالية. |
| [get_original_options()](#get_original_options__12) | يحصل على الخيارات بناءً على إعدادات الملف الأصلي.<br/>            قد يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير.<br/>            على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) الطريقة، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل.<br/>            لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها<br/>            إلى [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) الطريقة كمعامل ثانٍ. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_13) | يحصل على ارتفاع نسبي. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_14) | يحصل على عرض نسبي. |
| [load(file_path)](#load_file_path_15) | يقوم بتحميل صورة جديدة من الملف المحدد. |
| [load(file_path, load_options)](#load_file_path_load_options_16) | يقوم بتحميل صورة جديدة من الملف المحدد. |
| [load(stream)](#load_stream_17) | يقوم بتحميل صورة جديدة من الدفق المحدد. |
| [load(stream, load_options)](#load_stream_load_options_18) | يقوم بتحميل صورة جديدة من الدفق المحدد. |
| [resize(new_width, new_height)](#resize_new_width_new_height_19) | يعيد تحجيم الصورة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) الافتراضي. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_20) | يعيد تحجيم الصورة. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_21) | يعيد تحجيم الصورة. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_22) | يعيد تحجيم الارتفاع بنسبية. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_23) | يعيد تحجيم الارتفاع بنسبية. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_24) | يعيد تحجيم الارتفاع بنسبية. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_25) | يعيد تحجيم العرض بنسبية. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) الافتراضي. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_26) | يعيد تحجيم العرض بنسبية. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_27) | يعيد تحجيم العرض بنسبية. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_28) | يدور، يقلب، أو يدور ويقلب الصورة. |
| save() | يحفظ بيانات الصورة إلى الدفق الأساسي. |
| [save(file_path)](#save_file_path_29) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [save(file_path, options)](#save_file_path_options_30) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_31) | يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ. |
| [save(file_path, over_write)](#save_file_path_over_write_32) | يحفظ بيانات الكائن إلى موقع الملف المحدد. |
| [save(stream)](#save_stream_33) | يحفظ بيانات الكائن إلى الدفق المحدد. |
| [save(stream, options_base)](#save_stream_options_base_34) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_35) | يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_36) | يضبط لوحة ألوان الصورة. |


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


```
 can_load(file_path) 
```

يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان يمكن تحميل الصورة من الملف المحدد؛ وإلا، <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


```
 can_load(file_path, load_options) 
```

يحدد ما إذا كان يمكن تحميل الصورة من مسار الملف المحدد واختياريًا باستخدام خيارات الفتح المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | خيارات التحميل. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان يمكن تحميل الصورة من الملف المحدد؛ وإلا، <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_3}


```
 can_load(stream) 
```

يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | الدفق للتحميل منه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان يمكن تحميل الصورة من الدفق المحدد؛ وإلا، <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


```
 can_load(stream, load_options) 
```

يحدد ما إذا كان يمكن تحميل الصورة من الدفق المحدد واختياريًا باستخدام <paramref name=\"loadOptions\" /> المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | الدفق للتحميل منه. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | خيارات التحميل. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان يمكن تحميل الصورة من الدفق المحدد؛ وإلا، <c>false</c>. |


### Method: can_save(options) {#can_save_options_5}


```
 can_save(options) 
```

يحدد ما إذا كان يمكن حفظ الصورة إلى تنسيق الملف المحدد الممثل بخيارات الحفظ الممررة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | خيارات الحفظ للاستخدام. |

**Returns**

| النوع | الوصف |
| :- | :- |
| bool | <c>true</c> إذا كان يمكن حفظ الصورة إلى تنسيق الملف المحدد الممثل بخيارات الحفظ الممررة؛ وإلا، <c>false</c>. |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_6}


```
 create(image_options, width, height) 
```

ينشئ صورة جديدة باستخدام خيارات الإنشاء المحددة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | خيارات الصورة. |
| width | int | العرض. |
| الارتفاع | int | الارتفاع. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | الصورة التي تم إنشاؤها حديثًا. |


### Method: get_default_options(args) {#get_default_options_args_7}


```
 get_default_options(args) 
```

يحصل على الخيارات الافتراضية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| args | object | المعلمات. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | الخيارات الافتراضية |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_8}


```
 get_file_format(file_path) 
```

يحصل على تنسيق الملف.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | تنسيق الملف المحدد. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_9}


```
 get_file_format(stream) 
```

يحصل على تنسيق الملف.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | التدفق. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | تنسيق الملف المحدد. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_10}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

يحصل على المستطيل الذي يتناسب مع الصورة الحالية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل للحصول على المستطيل المناسب. |
| pixels | int | بكسلات ARGB 32-بت. |
| width | int | عرض الكائن. |
| الارتفاع | int | ارتفاع الكائن. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل المناسب أو استثناء إذا لم يتم العثور على مستطيل مناسب. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_11}


```
 get_fitting_rectangle(rectangle, width, height) 
```

يحصل على المستطيل الذي يتناسب مع الصورة الحالية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل للحصول على المستطيل المناسب. |
| width | int | عرض الكائن. |
| الارتفاع | int | ارتفاع الكائن. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | المستطيل المناسب أو استثناء إذا لم يتم العثور على مستطيل مناسب. |


### Method: get_original_options() {#get_original_options__12}


```
 get_original_options() 
```

يحصل على الخيارات بناءً على إعدادات الملف الأصلي.<br/>            قد يكون هذا مفيدًا للحفاظ على عمق البت وغيرها من معلمات الصورة الأصلية دون تغيير.<br/>            على سبيل المثال، إذا قمنا بتحميل صورة PNG بالأبيض والأسود بعمق 1 بت لكل بكسل ثم حفظناها باستخدام<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) الطريقة، سيتم إنتاج صورة PNG ناتجة بعمق 8 بت لكل بكسل.<br/>            لتجنب ذلك وحفظ صورة PNG بعمق 1 بت لكل بكسل، استخدم هذه الطريقة للحصول على خيارات الحفظ المقابلة ومررها<br/>            إلى [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) الطريقة كمعامل ثانٍ.

**Returns**

| النوع | الوصف |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | الخيارات بناءً على إعدادات الملف الأصلي. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_13}


```
 get_proportional_height(width, height, new_width) 
```

يحصل على ارتفاع نسبي.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| width | int | العرض. |
| الارتفاع | int | الارتفاع. |
| new_width | int | العرض الجديد. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | الارتفاع النسبي. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_14}


```
 get_proportional_width(width, height, new_height) 
```

يحصل على عرض نسبي.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| width | int | العرض. |
| الارتفاع | int | الارتفاع. |
| new_height | int | الارتفاع الجديد. |

**Returns**

| النوع | الوصف |
| :- | :- |
| int | العرض النسبي. |


### Method: load(file_path)  [static] {#load_file_path_15}


```
 load(file_path) 
```

يقوم بتحميل صورة جديدة من الملف المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لتحميل الصورة منه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | الصورة المحملة. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_16}


```
 load(file_path, load_options) 
```

يقوم بتحميل صورة جديدة من الملف المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لتحميل الصورة منه. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | خيارات التحميل. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | الصورة المحملة. |


### Method: load(stream)  [static] {#load_stream_17}


```
 load(stream) 
```

يقوم بتحميل صورة جديدة من الدفق المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | الدفق لتحميل الصورة منه. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | الصورة المحملة. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_18}


```
 load(stream, load_options) 
```

يقوم بتحميل صورة جديدة من الدفق المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | الدفق لتحميل الصورة منه. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | خيارات التحميل. |

**Returns**

| النوع | الوصف |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | الصورة المحملة. |


### Method: resize(new_width, new_height) {#resize_new_width_new_height_19}


```
 resize(new_width, new_height) 
```

يعيد تحجيم الصورة. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) الافتراضي.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_20}


```
 resize(new_width, new_height, resize_type) 
```

يعيد تحجيم الصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | نوع التحجيم. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_21}


```
 resize(new_width, new_height, settings) 
```

يعيد تحجيم الصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | إعدادات التحجيم. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_22}


```
 resize_height_proportionally(new_height) 
```

يعيد تحجيم الارتفاع بنسبية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_23}


```
 resize_height_proportionally(new_height, resize_type) 
```

يعيد تحجيم الارتفاع بنسبية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | نوع التحجيم. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_24}


```
 resize_height_proportionally(new_height, settings) 
```

يعيد تحجيم الارتفاع بنسبية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_height | int | الارتفاع الجديد. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | إعدادات تحجيم الصورة. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_25}


```
 resize_width_proportionally(new_width) 
```

يعيد تحجيم العرض بنسبية. يتم استخدام [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) الافتراضي.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_26}


```
 resize_width_proportionally(new_width, resize_type) 
```

يعيد تحجيم العرض بنسبية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | نوع التحجيم. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_27}


```
 resize_width_proportionally(new_width, settings) 
```

يعيد تحجيم العرض بنسبية.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| new_width | int | العرض الجديد. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | إعدادات تحجيم الصورة. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_28}


```
 rotate_flip(rotate_flip_type) 
```

يدور، يقلب، أو يدور ويقلب الصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | نوع التدوير أو القلب. |

### Method: save(file_path) {#save_file_path_29}


```
 save(file_path) 
```

يحفظ بيانات الكائن إلى موقع الملف المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ بيانات الكائن إليه. |

### Method: save(file_path, options) {#save_file_path_options_30}


```
 save(file_path, options) 
```

يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | الخيارات. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_31}


```
 save(file_path, options, bounds_rectangle) 
```

يحفظ بيانات الكائن إلى موقع الملف المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | الخيارات. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | مستطيل حدود الصورة الوجهة. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |

### Method: save(file_path, over_write) {#save_file_path_over_write_32}


```
 save(file_path, over_write) 
```

يحفظ بيانات الكائن إلى موقع الملف المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| file_path | string | مسار الملف لحفظ بيانات الكائن إليه. |
| over_write | bool | إذا تم تعيينه إلى <c>true</c> سيُستبدل محتوى الملف، وإلا سيحدث الإلحاق. |

### Method: save(stream) {#save_stream_33}


```
 save(stream) 
```

يحفظ بيانات الكائن إلى الدفق المحدد.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | الدفق لحفظ بيانات الكائن إليه. |

### Method: save(stream, options_base) {#save_stream_options_base_34}


```
 save(stream, options_base) 
```

يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | الدفق لحفظ بيانات الصورة إليه. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | خيارات الحفظ. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_35}


```
 save(stream, options_base, bounds_rectangle) 
```

يحفظ بيانات الصورة إلى الدفق المحدد بالتنسيق المحدد للملف وفقًا لخيارات الحفظ.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| تدفق | _io.BufferedRandom | الدفق لحفظ بيانات الصورة إليه. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | خيارات الحفظ. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | مستطيل حدود الصورة الوجهة. اضبط المستطيل الفارغ لاستخدام حدود المصدر. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_36}


```
 set_palette(palette, update_colors) 
```

يضبط لوحة ألوان الصورة.

**Parameters:**

| معامل | النوع | الوصف |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | لوحة الألوان لتعيينها. |
| update_colors | bool | إذا تم تعيينه إلى <c>true</c> سيتم تحديث الألوان وفقًا للوحة الألوان الجديدة؛ وإلا ستظل فهارس الألوان دون تغيير. لاحظ أن الفهارس غير المتغيرة قد تتسبب في تعطل الصورة عند التحميل إذا لم يكن لبعض الفهارس إدخالات مطابقة في لوحة الألوان. |

