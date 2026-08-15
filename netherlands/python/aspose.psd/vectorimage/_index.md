---
title: "VectorImage Klasse"
type: docs
weight: 4700
url: /nl/python-net/aspose.psd/vectorimage/
---

**Summary:** The vector image is the base class for all type of vector images.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.VectorImage

**Inheritance:** IObjectWithBounds, IObjectWithSizeF, Image

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Haalt op of stelt een waarde in die aangeeft of het palet automatisch wordt aangepast. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Haalt op of stelt een waarde in voor de achtergrondkleur. |
| bits_per_pixel | int | r | Haalt het aantal bits per pixel van de afbeelding op. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Haalt de grenzen van de afbeelding op. |
| buffer_size_hint | int | r/w | Haalt op of stelt de buffergroottehint in, die is gedefinieerd als de maximaal toegestane grootte voor alle interne buffers. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Haalt de [Image](/psd/python-net/aspose.psd/image/) container op. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Haalt de gegevensstroom van het object op. |
| disposed | bool | r | Geeft een waarde die aangeeft of dit exemplaar is vrijgegeven. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Haalt een waarde van bestandsformaat op |
| has_background_color | bool | r/w | Haalt of stelt een waarde in die aangeeft of de afbeelding een achtergrondkleur heeft. |
| hoogte | int | r | Haalt de afbeeldinghoogte op. |
| height_f | float | r | Haalt de objecthoogte op, in inches. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Haalt of stelt de onderbrekingsmonitor in. |
| is_cached | bool | r | Haalt een waarde op die aangeeft of de gegevens van het object momenteel in de cache staan en er geen gegevenslezen nodig is. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Haalt op of stelt het kleurenpalet in. Het kleurenpalet wordt niet gebruikt wanneer pixels direct worden weergegeven. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Haalt de afbeeldingsgrootte op. |
| size_f | [SizeF](/psd/python-net/aspose.psd/sizef) | r | Haalt de objectgrootte op, in inches. |
| use_palette | bool | r | Haalt een waarde op die aangeeft of het afbeeldingspalet wordt gebruikt. |
| width | int | r | Haalt de breedte van de afbeelding op. |
| width_f | float | r | Haalt de objectbreedte op, in inches. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| cache_data() | Cachet de gegevens en zorgt ervoor dat er geen extra gegevens worden geladen van de onderliggende [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/). |
| [can_load(file_path)](#can_load_file_path_1) | Bepaalt of de afbeelding kan worden geladen vanaf het opgegeven bestandspad. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | Bepaalt of de afbeelding kan worden geladen vanaf het opgegeven bestandspad en eventueel met de opgegeven openopties. |
| [can_load(stream)](#can_load_stream_3) | Bepaalt of de afbeelding kan worden geladen vanaf de opgegeven stream. |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | Bepaalt of de afbeelding kan worden geladen vanaf de opgegeven stream en eventueel met de opgegeven <paramref name="loadOptions" />. |
| [can_save(options)](#can_save_options_5) | Bepaalt of de afbeelding kan worden opgeslagen in het opgegeven bestandsformaat dat wordt weergegeven door de meegegeven opslagopties. |
| [create(image_options, width, height)](#create_image_options_width_height_6) | Maakt een nieuwe afbeelding aan met de opgegeven creatieopties. |
| [get_default_options(args)](#get_default_options_args_7) | Haalt de standaardopties op. |
| [get_file_format(file_path)](#get_file_format_file_path_8) | Haalt het bestandsformaat op. |
| [get_file_format(stream)](#get_file_format_stream_9) | Haalt het bestandsformaat op. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_10) | Haalt het rechthoek op dat past bij de huidige afbeelding. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_11) | Haalt het rechthoek op dat past bij de huidige afbeelding. |
| [get_original_options()](#get_original_options__12) | Haalt de opties op op basis van de oorspronkelijke bestandsinstellingen.<br/>            Dit kan nuttig zijn om de bitsdiepte en andere parameters van de oorspronkelijke afbeelding ongewijzigd te houden.<br/>            Bijvoorbeeld, als we een zwart-witte PNG-afbeelding met 1 bit per pixel laden en deze vervolgens opslaan met de<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) methode, wordt een PNG-uitvoerafbeelding met 8 bits per pixel gegenereerd.<br/>            Om dit te voorkomen en een PNG-afbeelding met 1 bit per pixel op te slaan, gebruik deze methode om de bijbehorende opslagopties op te halen en ze<br/>            door te geven aan de [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) methode als tweede parameter. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_13) | Haalt een proportionele hoogte op. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_14) | Haalt een proportionele breedte op. |
| [load(file_path)](#load_file_path_15) | Laadt een nieuwe afbeelding vanuit het opgegeven bestand. |
| [load(file_path, load_options)](#load_file_path_load_options_16) | Laadt een nieuwe afbeelding vanuit het opgegeven bestand. |
| [load(stream)](#load_stream_17) | Laadt een nieuwe afbeelding vanuit de opgegeven stream. |
| [load(stream, load_options)](#load_stream_load_options_18) | Laadt een nieuwe afbeelding vanuit de opgegeven stream. |
| [resize(new_width, new_height)](#resize_new_width_new_height_19) | Wijzigt de grootte van de afbeelding. De standaard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wordt gebruikt. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_20) | Wijzigt de grootte van de afbeelding. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_21) | Wijzigt de grootte van de afbeelding. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_22) | Wijzigt de hoogte proportioneel. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_23) | Wijzigt de hoogte proportioneel. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_24) | Wijzigt de hoogte proportioneel. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_25) | Wijzigt de breedte proportioneel. De standaard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wordt gebruikt. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_26) | Wijzigt de breedte proportioneel. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_27) | Wijzigt de breedte proportioneel. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_28) | Roteert, spiegelt of roteert en spiegelt de afbeelding. |
| save() | Slaat de afbeeldingsgegevens op in de onderliggende stream. |
| [save(file_path)](#save_file_path_29) | Slaat de gegevens van het object op op de opgegeven bestandslocatie. |
| [save(file_path, options)](#save_file_path_options_30) | Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_31) | Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties. |
| [save(file_path, over_write)](#save_file_path_over_write_32) | Slaat de gegevens van het object op op de opgegeven bestandslocatie. |
| [save(stream)](#save_stream_33) | Slaat de gegevens van het object op in de opgegeven stream. |
| [save(stream, options_base)](#save_stream_options_base_34) | Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_35) | Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_36) | Stelt het palet van de afbeelding in. |


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


```
 can_load(file_path) 
```

Bepaalt of de afbeelding kan worden geladen vanaf het opgegeven bestandspad.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <c>true</c> als afbeelding kan worden geladen vanuit het opgegeven bestand; anders <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


```
 can_load(file_path, load_options) 
```

Bepaalt of de afbeelding kan worden geladen vanaf het opgegeven bestandspad en eventueel met de opgegeven openopties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | De laadopties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <c>true</c> als afbeelding kan worden geladen vanuit het opgegeven bestand; anders <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_3}


```
 can_load(stream) 
```

Bepaalt of de afbeelding kan worden geladen vanaf de opgegeven stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream om vanuit te laden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <c>true</c> als afbeelding kan worden geladen vanuit de opgegeven stream; anders <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


```
 can_load(stream, load_options) 
```

Bepaalt of de afbeelding kan worden geladen vanaf de opgegeven stream en eventueel met de opgegeven <paramref name="loadOptions" />.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream om vanuit te laden. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | De laadopties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <c>true</c> als afbeelding kan worden geladen vanuit de opgegeven stream; anders <c>false</c>. |


### Method: can_save(options) {#can_save_options_5}


```
 can_save(options) 
```

Bepaalt of de afbeelding kan worden opgeslagen in het opgegeven bestandsformaat dat wordt weergegeven door de meegegeven opslagopties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De te gebruiken opslagopties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <c>true</c> als afbeelding kan worden opgeslagen in het opgegeven bestandsformaat dat wordt weergegeven door de meegegeven opslagopties; anders <c>false</c>. |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_6}


```
 create(image_options, width, height) 
```

Maakt een nieuwe afbeelding aan met de opgegeven creatieopties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De afbeeldingopties. |
| width | int | De breedte. |
| hoogte | int | De hoogte. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | De nieuw aangemaakte afbeelding. |


### Method: get_default_options(args) {#get_default_options_args_7}


```
 get_default_options(args) 
```

Haalt de standaardopties op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| args | object | De argumenten. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Standaardopties |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_8}


```
 get_file_format(file_path) 
```

Haalt het bestandsformaat op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Het bepaalde bestandsformaat. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_9}


```
 get_file_format(stream) 
```

Haalt het bestandsformaat op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Het bepaalde bestandsformaat. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_10}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Haalt het rechthoek op dat past bij de huidige afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om de passende rechthoek voor op te halen. |
| pixels | int | De 32-bit ARGB-pixels. |
| width | int | De objectbreedte. |
| hoogte | int | De objecthoogte. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | De passende rechthoek of een uitzondering als er geen passende rechthoek kan worden gevonden. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_11}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Haalt het rechthoek op dat past bij de huidige afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek om de passende rechthoek voor op te halen. |
| width | int | De objectbreedte. |
| hoogte | int | De objecthoogte. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | De passende rechthoek of een uitzondering als er geen passende rechthoek kan worden gevonden. |


### Method: get_original_options() {#get_original_options__12}


```
 get_original_options() 
```

Haalt de opties op op basis van de oorspronkelijke bestandsinstellingen.<br/>            Dit kan nuttig zijn om de bitsdiepte en andere parameters van de oorspronkelijke afbeelding ongewijzigd te houden.<br/>            Bijvoorbeeld, als we een zwart-witte PNG-afbeelding met 1 bit per pixel laden en deze vervolgens opslaan met de<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) methode, wordt een PNG-uitvoerafbeelding met 8 bits per pixel gegenereerd.<br/>            Om dit te voorkomen en een PNG-afbeelding met 1 bit per pixel op te slaan, gebruik deze methode om de bijbehorende opslagopties op te halen en ze<br/>            door te geven aan de [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) methode als tweede parameter.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De opties gebaseerd op de oorspronkelijke bestandsinstellingen. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_13}


```
 get_proportional_height(width, height, new_width) 
```

Haalt een proportionele hoogte op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| width | int | De breedte. |
| hoogte | int | De hoogte. |
| new_width | int | De nieuwe breedte. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De proportionele hoogte. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_14}


```
 get_proportional_width(width, height, new_height) 
```

Haalt een proportionele breedte op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| width | int | De breedte. |
| hoogte | int | De hoogte. |
| new_height | int | De nieuwe hoogte. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De proportionele breedte. |


### Method: load(file_path)  [static] {#load_file_path_15}


```
 load(file_path) 
```

Laadt een nieuwe afbeelding vanuit het opgegeven bestand.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad om de afbeelding van te laden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | De geladen afbeelding. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_16}


```
 load(file_path, load_options) 
```

Laadt een nieuwe afbeelding vanuit het opgegeven bestand.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad om de afbeelding van te laden. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | De laadopties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | De geladen afbeelding. |


### Method: load(stream)  [static] {#load_stream_17}


```
 load(stream) 
```

Laadt een nieuwe afbeelding vanuit de opgegeven stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream om de afbeelding van te laden. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | De geladen afbeelding. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_18}


```
 load(stream, load_options) 
```

Laadt een nieuwe afbeelding vanuit de opgegeven stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream om de afbeelding van te laden. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | De laadopties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | De geladen afbeelding. |


### Method: resize(new_width, new_height) {#resize_new_width_new_height_19}


```
 resize(new_width, new_height) 
```

Wijzigt de grootte van de afbeelding. De standaard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wordt gebruikt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_width | int | De nieuwe breedte. |
| new_height | int | De nieuwe hoogte. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_20}


```
 resize(new_width, new_height, resize_type) 
```

Wijzigt de grootte van de afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_width | int | De nieuwe breedte. |
| new_height | int | De nieuwe hoogte. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Het type schalen. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_21}


```
 resize(new_width, new_height, settings) 
```

Wijzigt de grootte van de afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_width | int | De nieuwe breedte. |
| new_height | int | De nieuwe hoogte. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | De instellingen voor schalen. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_22}


```
 resize_height_proportionally(new_height) 
```

Wijzigt de hoogte proportioneel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_height | int | De nieuwe hoogte. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_23}


```
 resize_height_proportionally(new_height, resize_type) 
```

Wijzigt de hoogte proportioneel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_height | int | De nieuwe hoogte. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Type van de verkleining. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_24}


```
 resize_height_proportionally(new_height, settings) 
```

Wijzigt de hoogte proportioneel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_height | int | De nieuwe hoogte. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | De instellingen voor het verkleinen van de afbeelding. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_25}


```
 resize_width_proportionally(new_width) 
```

Wijzigt de breedte proportioneel. De standaard [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) wordt gebruikt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_width | int | De nieuwe breedte. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_26}


```
 resize_width_proportionally(new_width, resize_type) 
```

Wijzigt de breedte proportioneel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_width | int | De nieuwe breedte. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Type van de verkleining. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_27}


```
 resize_width_proportionally(new_width, settings) 
```

Wijzigt de breedte proportioneel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_width | int | De nieuwe breedte. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | De instellingen voor het verkleinen van de afbeelding. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_28}


```
 rotate_flip(rotate_flip_type) 
```

Roteert, spiegelt of roteert en spiegelt de afbeelding.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Type van de rotatie‑spiegeling. |

### Method: save(file_path) {#save_file_path_29}


```
 save(file_path) 
```

Slaat de gegevens van het object op op de opgegeven bestandslocatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad om de gegevens van het object op te slaan. |

### Method: save(file_path, options) {#save_file_path_options_30}


```
 save(file_path, options) 
```

Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De opties. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_31}


```
 save(file_path, options, bounds_rectangle) 
```

Slaat de gegevens van het object op op de opgegeven bestandslocatie in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De opties. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De bestemmingsrechthoek voor afbeeldingsgrenzen. Stel de lege rechthoek in om de sourse‑grenzen te gebruiken. |

### Method: save(file_path, over_write) {#save_file_path_over_write_32}


```
 save(file_path, over_write) 
```

Slaat de gegevens van het object op op de opgegeven bestandslocatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_path | string | Het bestandspad om de gegevens van het object op te slaan. |
| over_write | bool | als ingesteld op <c>true</c> wordt de bestandsinhoud overschreven, anders wordt er toegevoegd. |

### Method: save(stream) {#save_stream_33}


```
 save(stream) 
```

Slaat de gegevens van het object op in de opgegeven stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream om de gegevens van het object op te slaan. |

### Method: save(stream, options_base) {#save_stream_options_base_34}


```
 save(stream, options_base) 
```

Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream om de gegevens van de afbeelding op te slaan. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De opslagopties. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_35}


```
 save(stream, options_base, bounds_rectangle) 
```

Slaat de gegevens van de afbeelding op in de opgegeven stream in het opgegeven bestandsformaat volgens de opslagopties.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | De stream om de gegevens van de afbeelding op te slaan. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | De opslagopties. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | De rechthoek met de grenzen van de doelafbeelding. Stel de lege rechthoek in om de brongrenzen te gebruiken. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_36}


```
 set_palette(palette, update_colors) 
```

Stelt het palet van de afbeelding in.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | Het palet om in te stellen. |
| update_colors | bool | indien ingesteld op <c>true</c> worden kleuren bijgewerkt volgens het nieuwe palet; anders blijven kleurindexen ongewijzigd. Merk op dat ongewijzigde indexen de afbeelding kunnen laten crashen bij het laden als sommige indexen geen overeenkomstige paletinvoer hebben. |

