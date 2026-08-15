---
title: "Image Sınıfı"
type: docs
weight: 2170
url: /tr/python-net/aspose.psd/image/
---

**Summary:** The image is the base class for all type of images.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Image

**Inheritance:** IObjectWithBounds, DataStreamSupporter

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Otomatik palet ayarlamasını gösteren bir değeri alır veya ayarlar. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Arka plan renginin değerini alır veya ayarlar. |
| bits_per_pixel | int | r | Görüntünün piksel başına bit sayısını alır. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Görüntünün sınırlarını alır. |
| buffer_size_hint | int | r/w | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu belirten tampon boyutu ipucunu alır veya ayarlar. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Alır [Image](/psd/python-net/aspose.psd/image/) kapsayıcısını. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Nesnenin veri akışını alır. |
| kapatıldı | bool | r | Bu örneğin atılmış olup olmadığını gösteren bir değeri alır. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Dosya formatının değerini alır |
| arka_plan_rengi_var | bool | r/w | Görselin arka plan rengine sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| yükseklik | int | r | Görselin yüksekliğini alır. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Kesinti izleyicisini alır veya ayarlar. |
| önbellekte | bool | r | Nesnenin verisinin şu anda önbelleğe alınıp alınmadığını ve veri okumanın gerekip gerekmediğini gösteren bir değeri alır. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Renk paletini alır veya ayarlar. Renk paleti, pikseller doğrudan temsil edildiğinde kullanılmaz. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Görüntü boyutunu alır. |
| use_palette | bool | r | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değeri alır. |
| width | int | r | Görüntünün genişliğini alır. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| cache_data() | Verileri önbelleğe alır ve temel [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) üzerinden ek veri yüklemesinin yapılmayacağını garanti eder. |
| [can_load(file_path)](#can_load_file_path_1) | Görüntünün belirtilen dosya yolundan yüklenip yüklenemeyeceğini belirler. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | Görüntünün belirtilen dosya yolundan ve isteğe bağlı olarak belirtilen açma seçenekleri kullanılarak yüklenip yüklenemeyeceğini belirler. |
| [can_load(stream)](#can_load_stream_3) | Görüntünün belirtilen akıştan yüklenip yüklenemeyeceğini belirler. |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | Görüntünün belirtilen akıştan ve isteğe bağlı olarak belirtilen <paramref name="loadOptions" /> kullanılarak yüklenip yüklenemeyeceğini belirler. |
| [can_save(options)](#can_save_options_5) | Görüntünün, verilen kaydetme seçenekleriyle temsil edilen belirtilen dosya formatına kaydedilip kaydedilemeyeceğini belirler. |
| [create(image_options, width, height)](#create_image_options_width_height_6) | Belirtilen oluşturma seçenekleri kullanılarak yeni bir görüntü oluşturur. |
| [get_default_options(args)](#get_default_options_args_7) | Varsayılan seçenekleri alır. |
| [get_file_format(file_path)](#get_file_format_file_path_8) | Dosya formatını alır. |
| [get_file_format(stream)](#get_file_format_stream_9) | Dosya formatını alır. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_10) | Geçerli görüntüyü saran dikdörtgeni alır. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_11) | Geçerli görüntüyü saran dikdörtgeni alır. |
| [get_original_options()](#get_original_options__12) | Orijinal dosya ayarlarına dayalı seçenekleri alır.<br/>            Bu, orijinal görüntünün bit derinliği ve diğer parametrelerinin değişmeden kalmasını sağlamak için faydalı olabilir.<br/>            Örneğin, 1 bit/piksel bir siyah-beyaz PNG görüntüsü yükleyip ardından<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) metodunu kullanarak kaydettiğimizde, çıktı PNG görüntüsü 8 bit/piksel olarak üretilecektir.<br/>            Bunu önlemek ve PNG görüntüsünü 1 bit/piksel olarak kaydetmek için, bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) metoduna ikinci parametre olarak geçirin. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_13) | Orantılı bir yükseklik alır. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_14) | Orantılı bir genişlik alır. |
| [load(file_path)](#load_file_path_15) | Belirtilen dosyadan yeni bir görüntü yükler. |
| [load(file_path, load_options)](#load_file_path_load_options_16) | Belirtilen dosyadan yeni bir görüntü yükler. |
| [load(stream)](#load_stream_17) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load(stream, load_options)](#load_stream_load_options_18) | Belirtilen akıştan yeni bir görüntü yükler. |
| [resize(new_width, new_height)](#resize_new_width_new_height_19) | Görüntüyü yeniden boyutlandırır. Varsayılan olarak [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) kullanılır. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_20) | Görüntüyü yeniden boyutlandırır. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_21) | Görüntüyü yeniden boyutlandırır. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_22) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_23) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_24) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_25) | Genişliği orantılı olarak yeniden boyutlandırır. Varsayılan olarak [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) kullanılır. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_26) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_27) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_28) | Görüntüyü döndürür, çevirir veya döndürüp çevirir. |
| kaydet() | Görüntü verilerini temel akışa kaydeder. |
| [save(file_path)](#save_file_path_29) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| [save(file_path, options)](#save_file_path_options_30) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_31) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| [save(file_path, over_write)](#save_file_path_over_write_32) | Nesnenin verilerini belirtilen dosya konumuna kaydeder. |
| [save(stream)](#save_stream_33) | Nesnenin verilerini belirtilen akışa kaydeder. |
| [save(stream, options_base)](#save_stream_options_base_34) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_35) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_36) | Görüntü paletini ayarlar. |


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


```
 can_load(file_path) 
```

Görüntünün belirtilen dosya yolundan yüklenip yüklenemeyeceğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer görüntü belirtilen dosyadan yüklenebiliyorsa; aksi takdirde <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


```
 can_load(file_path, load_options) 
```

Görüntünün belirtilen dosya yolundan ve isteğe bağlı olarak belirtilen açma seçenekleri kullanılarak yüklenip yüklenemeyeceğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Yükleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer görüntü belirtilen dosyadan yüklenebiliyorsa; aksi takdirde <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_3}


```
 can_load(stream) 
```

Görüntünün belirtilen akıştan yüklenip yüklenemeyeceğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Yükleme yapılacak akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer görüntü belirtilen akıştan yüklenebiliyorsa; aksi takdirde <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


```
 can_load(stream, load_options) 
```

Görüntünün belirtilen akıştan ve isteğe bağlı olarak belirtilen <paramref name="loadOptions" /> kullanılarak yüklenip yüklenemeyeceğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Yükleme yapılacak akış. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Yükleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer görüntü belirtilen akıştan yüklenebiliyorsa; aksi takdirde <c>false</c>. |


### Method: can_save(options) {#can_save_options_5}


```
 can_save(options) 
```

Görüntünün, verilen kaydetme seçenekleriyle temsil edilen belirtilen dosya formatına kaydedilip kaydedilemeyeceğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Kullanılacak kaydetme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer görüntü, verilen kaydetme seçenekleriyle temsil edilen belirtilen dosya formatına kaydedilebiliyorsa; aksi takdirde <c>false</c>. |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_6}


```
 create(image_options, width, height) 
```

Belirtilen oluşturma seçenekleri kullanılarak yeni bir görüntü oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Görüntü seçenekleri. |
| width | int | Genişlik. |
| yükseklik | int | Yükseklik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Yeni oluşturulan görüntü. |


### Method: get_default_options(args) {#get_default_options_args_7}


```
 get_default_options(args) 
```

Varsayılan seçenekleri alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| argümanlar | object | Argümanlar. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Varsayılan seçenekler |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_8}


```
 get_file_format(file_path) 
```

Dosya formatını alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Belirlenen dosya formatı. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_9}


```
 get_file_format(stream) 
```

Dosya formatını alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Belirlenen dosya formatı. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_10}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Geçerli görüntüyü saran dikdörtgeni alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Uygun dikdörtgeni almak için dikdörtgen. |
| piksel | int | 32-bit ARGB pikseller. |
| width | int | Nesnenin genişliği. |
| yükseklik | int | Nesnenin yüksekliği. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Uygun dikdörtgen veya uygun bir dikdörtgen bulunamazsa istisna. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_11}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Geçerli görüntüyü saran dikdörtgeni alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Uygun dikdörtgeni almak için dikdörtgen. |
| width | int | Nesnenin genişliği. |
| yükseklik | int | Nesnenin yüksekliği. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Uygun dikdörtgen veya uygun bir dikdörtgen bulunamazsa istisna. |


### Method: get_original_options() {#get_original_options__12}


```
 get_original_options() 
```

Orijinal dosya ayarlarına dayalı seçenekleri alır.<br/>            Bu, orijinal görüntünün bit derinliği ve diğer parametrelerinin değişmeden kalmasını sağlamak için faydalı olabilir.<br/>            Örneğin, 1 bit/piksel bir siyah-beyaz PNG görüntüsü yükleyip ardından<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) metodunu kullanarak kaydettiğimizde, çıktı PNG görüntüsü 8 bit/piksel olarak üretilecektir.<br/>            Bunu önlemek ve PNG görüntüsünü 1 bit/piksel olarak kaydetmek için, bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları<br/>            [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) metoduna ikinci parametre olarak geçirin.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Orijinal dosya ayarlarına dayalı seçenekler. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_13}


```
 get_proportional_height(width, height, new_width) 
```

Orantılı bir yükseklik alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| width | int | Genişlik. |
| yükseklik | int | Yükseklik. |
| new_width | int | Yeni genişlik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Orantılı yükseklik. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_14}


```
 get_proportional_width(width, height, new_height) 
```

Orantılı bir genişlik alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| width | int | Genişlik. |
| yükseklik | int | Yükseklik. |
| new_height | int | Yeni yükseklik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| int | Orantılı genişlik. |


### Method: load(file_path)  [static] {#load_file_path_15}


```
 load(file_path) 
```

Belirtilen dosyadan yeni bir görüntü yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Görüntünün yükleneceği dosya yolu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Yüklenen görüntü. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_16}


```
 load(file_path, load_options) 
```

Belirtilen dosyadan yeni bir görüntü yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Görüntünün yükleneceği dosya yolu. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Yükleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Yüklenen görüntü. |


### Method: load(stream)  [static] {#load_stream_17}


```
 load(stream) 
```

Belirtilen akıştan yeni bir görüntü yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün yükleneceği akış. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Yüklenen görüntü. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_18}


```
 load(stream, load_options) 
```

Belirtilen akıştan yeni bir görüntü yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün yükleneceği akış. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Yükleme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Yüklenen görüntü. |


### Method: resize(new_width, new_height) {#resize_new_width_new_height_19}


```
 resize(new_width, new_height) 
```

Görüntüyü yeniden boyutlandırır. Varsayılan olarak [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) kullanılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_20}


```
 resize(new_width, new_height, resize_type) 
```

Görüntüyü yeniden boyutlandırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Yeniden boyutlandırma türü. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_21}


```
 resize(new_width, new_height, settings) 
```

Görüntüyü yeniden boyutlandırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| new_height | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Yeniden boyutlandırma ayarları. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_22}


```
 resize_height_proportionally(new_height) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_23}


```
 resize_height_proportionally(new_height, resize_type) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Yeniden boyutlandırmanın türü. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_24}


```
 resize_height_proportionally(new_height, settings) 
```

Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_height | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Görüntü yeniden boyutlandırma ayarları. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_25}


```
 resize_width_proportionally(new_width) 
```

Genişliği orantılı olarak yeniden boyutlandırır. Varsayılan olarak [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) kullanılır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_26}


```
 resize_width_proportionally(new_width, resize_type) 
```

Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Yeniden boyutlandırmanın türü. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_27}


```
 resize_width_proportionally(new_width, settings) 
```

Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_width | int | Yeni genişlik. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Görüntü yeniden boyutlandırma ayarları. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_28}


```
 rotate_flip(rotate_flip_type) 
```

Görüntüyü döndürür, çevirir veya döndürüp çevirir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Döndürme çevirme türü. |

### Method: save(file_path) {#save_file_path_29}


```
 save(file_path) 
```

Nesnenin verilerini belirtilen dosya konumuna kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Nesnenin verisinin kaydedileceği dosya yolu. |

### Method: save(file_path, options) {#save_file_path_options_30}


```
 save(file_path, options) 
```

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Seçenekler. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_31}


```
 save(file_path, options, bounds_rectangle) 
```

Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Dosya yolu. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Seçenekler. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Hedef görüntü sınırları dikdörtgeni. Boş dikdörtgeni, kaynak sınırları için kullanmak üzere ayarlayın. |

### Method: save(file_path, over_write) {#save_file_path_over_write_32}


```
 save(file_path, over_write) 
```

Nesnenin verilerini belirtilen dosya konumuna kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | string | Nesnenin verisinin kaydedileceği dosya yolu. |
| over_write | bool | eğer <c>true</c> olarak ayarlanırsa dosya içeriği üzerine yazılır, aksi takdirde ekleme yapılır. |

### Method: save(stream) {#save_stream_33}


```
 save(stream) 
```

Nesnenin verilerini belirtilen akışa kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Nesnenin verisinin kaydedileceği akış. |

### Method: save(stream, options_base) {#save_stream_options_base_34}


```
 save(stream, options_base) 
```

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün verisinin kaydedileceği akış. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Kaydetme seçenekleri. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_35}


```
 save(stream, options_base, bounds_rectangle) 
```

Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntünün verisinin kaydedileceği akış. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Kaydetme seçenekleri. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Hedef görüntü sınırları dikdörtgeni. Kaynak sınırlarını kullanmak için boş bir dikdörtgen ayarlayın. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_36}


```
 set_palette(palette, update_colors) 
```

Görüntü paletini ayarlar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Ayarlanacak palet. |
| update_colors | bool | eğer <c>true</c> olarak ayarlanırsa renkler yeni palete göre güncellenir; aksi takdirde renk indeksleri değişmeden kalır. Değişmeyen indekslerin, bazı indekslerin karşılık gelen palet girdileri olmaması durumunda görüntünün yüklenirken çökmesine neden olabileceğini unutmayın. |

