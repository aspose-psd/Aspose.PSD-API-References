---
title: "Image-klass"
type: docs
weight: 2170
url: /sv/python-net/aspose.psd/image/
---

**Summary:** The image is the base class for all type of images.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.Image

**Inheritance:** IObjectWithBounds, DataStreamSupporter

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Hämtar eller anger ett värde som indikerar om automatisk justering av palett. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Hämtar eller anger ett värde för bakgrundsfärgen. |
| bits_per_pixel | int | r | Hämtar antalet bildbitar per pixel. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Hämtar bildens gränser. |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Hämtar [Image](/psd/python-net/aspose.psd/image/)‑behållaren. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Hämtar objektets datastream. |
| borttagen | bool | r | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Hämtar ett värde för filformatet |
| has_background_color | bool | r/w | Hämtar eller anger ett värde som visar om bilden har bakgrundsfärg. |
| height | int | r | Hämtar bildens höjd. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Hämtar eller anger avbrottsövervakaren. |
| is_cached | bool | r | Hämtar ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Hämtar eller anger färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Hämtar bildens storlek. |
| use_palette | bool | r | Hämtar ett värde som indikerar om bildpaletten används. |
| width | int | r | Hämtar bildens bredd. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| cache_data() | Cachar data och säkerställer att ingen ytterligare datainläsning utförs från den underliggande [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/). |
| [can_load(file_path)](#can_load_file_path_1) | Avgör om bilden kan läsas in från den angivna filsökvägen. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | Avgör om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna öppningsalternativen. |
| [can_load(stream)](#can_load_stream_3) | Avgör om bilden kan läsas in från den angivna strömmen. |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | Avgör om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna <paramref name="loadOptions" />. |
| [can_save(options)](#can_save_options_5) | Avgör om bilden kan sparas till det angivna filformatet som representeras av de medföljande sparalternativen. |
| [create(image_options, width, height)](#create_image_options_width_height_6) | Skapar en ny bild med de angivna skapalternativen. |
| [get_default_options(args)](#get_default_options_args_7) | Hämtar standardalternativen. |
| [get_file_format(file_path)](#get_file_format_file_path_8) | Hämtar filformatet. |
| [get_file_format(stream)](#get_file_format_stream_9) | Hämtar filformatet. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_10) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_11) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_original_options()](#get_original_options__12) | Hämtar alternativen baserat på originalfilens inställningar.<br/>            Detta kan vara användbart för att behålla bitdjup och andra parametrar i originalbilden oförändrade.<br/>            Till exempel, om vi laddar en svart‑vit PNG‑bild med 1 bit per pixel och sedan sparar den med hjälp av<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/)‑metoden, kommer en PNG‑utdata med 8‑bit per pixel att skapas.<br/>            För att undvika detta och spara PNG‑bilden med 1‑bit per pixel, använd den här metoden för att hämta motsvarande sparalternativ och skicka dem<br/>            till [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/)‑metoden som den andra parametern. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_13) | Hämtar en proportionell höjd. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_14) | Hämtar en proportionell bredd. |
| [load(file_path)](#load_file_path_15) | Laddar en ny bild från den angivna filen. |
| [load(file_path, load_options)](#load_file_path_load_options_16) | Laddar en ny bild från den angivna filen. |
| [load(stream)](#load_stream_17) | Laddar en ny bild från den angivna strömmen. |
| [load(stream, load_options)](#load_stream_load_options_18) | Laddar en ny bild från den angivna strömmen. |
| [resize(new_width, new_height)](#resize_new_width_new_height_19) | Ändrar storlek på bilden. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) används. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_20) | Ändrar storlek på bilden. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_21) | Ändrar storlek på bilden. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_22) | Ändrar bildens höjd proportionellt. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_23) | Ändrar bildens höjd proportionellt. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_24) | Ändrar bildens höjd proportionellt. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_25) | Ändrar bildens bredd proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) används. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_26) | Ändrar bildens bredd proportionellt. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_27) | Ändrar bildens bredd proportionellt. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_28) | Roterar, vänder eller roterar och vänder bilden. |
| save() | Sparar bilddata till den underliggande strömmen. |
| [save(file_path)](#save_file_path_29) | Sparar objektets data till den angivna filplatsen. |
| [save(file_path, options)](#save_file_path_options_30) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_31) | Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ. |
| [save(file_path, over_write)](#save_file_path_over_write_32) | Sparar objektets data till den angivna filplatsen. |
| [save(stream)](#save_stream_33) | Sparar objektets data till den angivna strömmen. |
| [save(stream, options_base)](#save_stream_options_base_34) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_35) | Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_36) | Ställer in bildpaletten. |


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


```
 can_load(file_path) 
```

Avgör om bilden kan läsas in från den angivna filsökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om bilden kan läsas in från den angivna filen; annars <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


```
 can_load(file_path, load_options) 
```

Avgör om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna öppningsalternativen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om bilden kan läsas in från den angivna filen; annars <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_3}


```
 can_load(stream) 
```

Avgör om bilden kan läsas in från den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om bilden kan läsas in från den angivna strömmen; annars <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


```
 can_load(stream, load_options) 
```

Avgör om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna <paramref name="loadOptions" />.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen att läsa från. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om bilden kan läsas in från den angivna strömmen; annars <c>false</c>. |


### Method: can_save(options) {#can_save_options_5}


```
 can_save(options) 
```

Avgör om bilden kan sparas till det angivna filformatet som representeras av de medföljande sparalternativen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Sparaalternativen att använda. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om bilden kan sparas till det angivna filformatet som representeras av de överförda sparaalternativen; annars <c>false</c>. |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_6}


```
 create(image_options, width, height) 
```

Skapar en ny bild med de angivna skapalternativen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Bildalternativen. |
| width | int | Bredden. |
| height | int | Höjden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Den nyss skapade bilden. |


### Method: get_default_options(args) {#get_default_options_args_7}


```
 get_default_options(args) 
```

Hämtar standardalternativen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| args | object | Argumenten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Standardalternativ |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_8}


```
 get_file_format(file_path) 
```

Hämtar filformatet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Det bestämda filformatet. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_9}


```
 get_file_format(stream) 
```

Hämtar filformatet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Det bestämda filformatet. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_10}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Hämtar rektangeln som passar den aktuella bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln för att hämta en passande rektangel för. |
| pixlar | int | De 32‑bitars ARGB‑pixlarna. |
| width | int | Objektets bredd. |
| height | int | Objektets höjd. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Den passande rektangeln eller ett undantag om ingen passande rektangel kan hittas. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_11}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Hämtar rektangeln som passar den aktuella bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Rektangeln för att hämta en passande rektangel för. |
| width | int | Objektets bredd. |
| height | int | Objektets höjd. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Den passande rektangeln eller ett undantag om ingen passande rektangel kan hittas. |


### Method: get_original_options() {#get_original_options__12}


```
 get_original_options() 
```

Hämtar alternativen baserat på originalfilens inställningar.<br/>            Detta kan vara användbart för att behålla bitdjup och andra parametrar i originalbilden oförändrade.<br/>            Till exempel, om vi laddar en svart‑vit PNG‑bild med 1 bit per pixel och sedan sparar den med hjälp av<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/)‑metoden, kommer en PNG‑utdata med 8‑bit per pixel att skapas.<br/>            För att undvika detta och spara PNG‑bilden med 1‑bit per pixel, använd den här metoden för att hämta motsvarande sparalternativ och skicka dem<br/>            till [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/)‑metoden som den andra parametern.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Alternativen baserade på de ursprungliga filinställningarna. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_13}


```
 get_proportional_height(width, height, new_width) 
```

Hämtar en proportionell höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int | Bredden. |
| height | int | Höjden. |
| new_width | int | Den nya bredden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Den proportionella höjden. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_14}


```
 get_proportional_width(width, height, new_height) 
```

Hämtar en proportionell bredd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int | Bredden. |
| height | int | Höjden. |
| new_height | int | Den nya höjden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Den proportionella bredden. |


### Method: load(file_path)  [static] {#load_file_path_15}


```
 load(file_path) 
```

Laddar en ny bild från den angivna filen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen att ladda bilden från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Den inlästa bilden. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_16}


```
 load(file_path, load_options) 
```

Laddar en ny bild från den angivna filen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen att ladda bilden från. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Den inlästa bilden. |


### Method: load(stream)  [static] {#load_stream_17}


```
 load(stream) 
```

Laddar en ny bild från den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen att ladda bilden från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Den inlästa bilden. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_18}


```
 load(stream, load_options) 
```

Laddar en ny bild från den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen att ladda bilden från. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | Den inlästa bilden. |


### Method: resize(new_width, new_height) {#resize_new_width_new_height_19}


```
 resize(new_width, new_height) 
```

Ändrar storlek på bilden. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_20}


```
 resize(new_width, new_height, resize_type) 
```

Ändrar storlek på bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Typ av storleksändring. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_21}


```
 resize(new_width, new_height, settings) 
```

Ändrar storlek på bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Inställningar för storleksändring. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_22}


```
 resize_height_proportionally(new_height) 
```

Ändrar bildens höjd proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_23}


```
 resize_height_proportionally(new_height, resize_type) 
```

Ändrar bildens höjd proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Typ av storleksändring. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_24}


```
 resize_height_proportionally(new_height, settings) 
```

Ändrar bildens höjd proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Inställningar för bildstorleksändring. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_25}


```
 resize_width_proportionally(new_width) 
```

Ändrar bildens bredd proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_26}


```
 resize_width_proportionally(new_width, resize_type) 
```

Ändrar bildens bredd proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Typ av storleksändring. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_27}


```
 resize_width_proportionally(new_width, settings) 
```

Ändrar bildens bredd proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Inställningar för bildstorleksändring. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_28}


```
 rotate_flip(rotate_flip_type) 
```

Roterar, vänder eller roterar och vänder bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Typ av rotera/vänd. |

### Method: save(file_path) {#save_file_path_29}


```
 save(file_path) 
```

Sparar objektets data till den angivna filplatsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara objektets data till. |

### Method: save(file_path, options) {#save_file_path_options_30}


```
 save(file_path, options) 
```

Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Alternativen. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_31}


```
 save(file_path, options, bounds_rectangle) 
```

Sparar objektets data till den angivna filplatsen i det angivna filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Alternativen. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Destinationens bildgränsrektangel. Ställ in den tomma rektangeln för att använda källgränserna. |

### Method: save(file_path, over_write) {#save_file_path_over_write_32}


```
 save(file_path, over_write) 
```

Sparar objektets data till den angivna filplatsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara objektets data till. |
| over_write | bool | om den är satt till <c>true</c> skriv över filens innehåll, annars kommer data att läggas till. |

### Method: save(stream) {#save_stream_33}


```
 save(stream) 
```

Sparar objektets data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen för att spara objektets data till. |

### Method: save(stream, options_base) {#save_stream_options_base_34}


```
 save(stream, options_base) 
```

Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen för att spara bildens data till. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Sparalternativen. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_35}


```
 save(stream, options_base, bounds_rectangle) 
```

Sparar bildens data till den angivna strömmen i det angivna filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | Strömmen för att spara bildens data till. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Sparalternativen. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Destinationens bildgränser rektangel. Ställ in den tomma rektangeln för att använda källgränserna. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_36}


```
 set_palette(palette, update_colors) 
```

Ställer in bildpaletten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Paletten att ställa in. |
| update_colors | bool | Om den är satt till <c>true</c> uppdateras färgerna enligt den nya paletten; annars förblir färgindexen oförändrade. Observera att oförändrade index kan krascha bilden vid inläsning om vissa index saknar motsvarande palettposter. |

