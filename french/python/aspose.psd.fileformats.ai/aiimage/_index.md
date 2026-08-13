---
title: "Classe AiImage"
type: docs
weight: 40
url: /fr/python-net/aspose.psd.fileformats.ai/aiimage/
---

**Summary:** The Adobe Illustrator (AI)  Image.

**Module:** [aspose.psd.fileformats.ai](/psd/python-net/aspose.psd.fileformats.ai/)

**Full Name:** aspose.psd.fileformats.ai.AiImage

**Inheritance:** IObjectWithBounds, Image

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [AiImage()](#AiImage__1) | Initialise une nouvelle instance de la classe AiImage |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| active_page_index | int | r/w | Obtient ou définit l'index de la page active. |
| auto_adjust_palette | bool | r/w | Obtient ou définit une valeur indiquant si la palette d'ajustement automatique est activée. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| bits_per_pixel | int | r | Obtient le nombre de bits par pixel de l'image. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Obtient les limites de l'image. |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Obtient le conteneur [Image](/psd/python-net/aspose.psd/image/). |
| data_section | [AiDataSection](/psd/python-net/aspose.psd.fileformats.ai/aidatasection) | r | Obtient la section de données. |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Obtient le flux de données de l'objet. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Obtient une valeur du format de fichier. |
| finalize_section | [AiFinalizeSection](/psd/python-net/aspose.psd.fileformats.ai/aifinalizesection) | r | Obtient la section de finalisation. |
| a_couleur_de_fond | bool | r/w | Obtient ou définit une valeur indiquant si l'image possède une couleur d'arrière-plan. |
| header | [AiHeader](/psd/python-net/aspose.psd.fileformats.ai/aiheader) | r | Obtient l'en-tête |
| hauteur | int | r | Obtient la hauteur de l'image. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Obtient ou définit le moniteur d'interruption. |
| est_en_cache | bool | r | Obtient une valeur indiquant si les données de l'objet sont actuellement en cache et qu'aucune lecture de données n'est requise. |
| layers | [AiLayerSection[]](/psd/python-net/aspose.psd.fileformats.ai/ailayersection) | r | Obtient les sections de calque |
| page_count | int | r | Le nombre de pages.<br/>            Pour les images au format AI ancien, il est toujours égal à 0. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Obtient ou définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement. |
| setup_section | [AiSetupSection](/psd/python-net/aspose.psd.fileformats.ai/aisetupsection) | r | Obtient la section de configuration |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Obtient la taille de l'image |
| use_palette | bool | r | Obtient une valeur indiquant si la palette de l'image est utilisée. |
| version | [AiFormatVersion](/psd/python-net/aspose.psd.fileformats.ai/aiformatversion) | r | Obtient la version du format Adobe Illustrator |
| width | int | r | Obtient la largeur de l'image. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r | Obtient ou définit les métadonnées XMP. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_layer(layer)](#add_layer_layer_1) | Ajoute la section de calque AI |
| cache_data() | Met en cache les données et garantit qu'aucun chargement supplémentaire de données ne sera effectué depuis le [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) sous-jacent. |
| [can_load(file_path)](#can_load_file_path_2) | Détermine si l'image peut être chargée depuis le chemin de fichier spécifié. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_3) | Détermine si l'image peut être chargée depuis le chemin de fichier spécifié et éventuellement en utilisant les options d'ouverture spécifiées. |
| [can_load(stream)](#can_load_stream_4) | Détermine si l'image peut être chargée depuis le flux spécifié. |
| [can_load(stream, load_options)](#can_load_stream_load_options_5) | Détermine si l'image peut être chargée depuis le flux spécifié et éventuellement en utilisant le <paramref name="loadOptions" /> spécifié. |
| [can_save(options)](#can_save_options_6) | Détermine si l'image peut être enregistrée au format de fichier spécifié représenté par les options d'enregistrement fournies. |
| [create(image_options, width, height)](#create_image_options_width_height_7) | Crée une nouvelle image en utilisant les options de création spécifiées. |
| [get_default_options(args)](#get_default_options_args_8) | Obtient les options par défaut. |
| [get_file_format(file_path)](#get_file_format_file_path_9) | Obtient le format de fichier. |
| [get_file_format(stream)](#get_file_format_stream_10) | Obtient le format de fichier. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_11) | Obtient le rectangle qui s'adapte à l'image actuelle. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_12) | Obtient le rectangle qui s'adapte à l'image actuelle. |
| [get_original_options()](#get_original_options__13) | Obtient les options basées sur les paramètres du fichier original.<br/>            Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés.<br/>            Par exemple, si nous chargeons une image PNG noir-et-blanc avec 1 bit par pixel puis la sauvegardons en utilisant le<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) méthode, l'image PNG de sortie avec 8 bits par pixel sera produite.<br/>            Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre<br/>            à la [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) méthode comme deuxième paramètre. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_14) | Obtient une hauteur proportionnelle. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_15) | Obtient une largeur proportionnelle. |
| [load(file_path)](#load_file_path_16) | Charge une nouvelle image depuis le fichier spécifié. |
| [load(file_path, load_options)](#load_file_path_load_options_17) | Charge une nouvelle image depuis le fichier spécifié. |
| [load(stream)](#load_stream_18) | Charge une nouvelle image depuis le flux spécifié. |
| [load(stream, load_options)](#load_stream_load_options_19) | Charge une nouvelle image depuis le flux spécifié. |
| [resize(new_width, new_height)](#resize_new_width_new_height_20) | Redimensionne l'image. Le [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) par défaut est utilisé. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_21) | Redimensionne l'image. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_22) | Redimensionne l'image. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_23) | Redimensionne la hauteur proportionnellement. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_24) | Redimensionne la hauteur proportionnellement. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_25) | Redimensionne la hauteur proportionnellement. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_26) | Redimensionne la largeur proportionnellement. Le [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) par défaut est utilisé. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_27) | Redimensionne la largeur proportionnellement. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_28) | Redimensionne la largeur proportionnellement. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_29) | Fait pivoter, retourner ou pivoter et retourner l'image. |
| save() | Enregistre les données de l'image dans le flux sous-jacent. |
| [save(file_path)](#save_file_path_30) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [save(file_path, options)](#save_file_path_options_31) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié selon les options d'enregistrement. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_32) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié selon les options d'enregistrement. |
| [save(file_path, over_write)](#save_file_path_over_write_33) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [save(stream)](#save_stream_34) | Enregistre les données de l'objet dans le flux spécifié. |
| [save(stream, options_base)](#save_stream_options_base_35) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié selon les options d'enregistrement. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_36) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié selon les options d'enregistrement. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_37) | Définit la palette de l'image. |


### Constructor: AiImage() {#AiImage__1}


```
 AiImage() 
```

Initialise une nouvelle instance de la classe AiImage

### Method: add_layer(layer) {#add_layer_layer_1}


```
 add_layer(layer) 
```

Ajoute la section de calque AI

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layer | [AiLayerSection](/psd/python-net/aspose.psd.fileformats.ai/ailayersection) | La section de calque AI |

### Method: can_load(file_path)  [static] {#can_load_file_path_2}


```
 can_load(file_path) 
```

Détermine si l'image peut être chargée depuis le chemin de fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | chaîne | Le chemin du fichier. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si l'image peut être chargée depuis le fichier spécifié ; sinon, <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_3}


```
 can_load(file_path, load_options) 
```

Détermine si l'image peut être chargée depuis le chemin de fichier spécifié et éventuellement en utilisant les options d'ouverture spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | chaîne | Le chemin du fichier. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Les options de chargement. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si l'image peut être chargée depuis le fichier spécifié ; sinon, <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_4}


```
 can_load(stream) 
```

Détermine si l'image peut être chargée depuis le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux à charger. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si l'image peut être chargée depuis le flux spécifié ; sinon, <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_5}


```
 can_load(stream, load_options) 
```

Détermine si l'image peut être chargée depuis le flux spécifié et éventuellement en utilisant le <paramref name="loadOptions" /> spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux à charger. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Les options de chargement. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si l'image peut être chargée depuis le flux spécifié ; sinon, <c>false</c>. |


### Method: can_save(options) {#can_save_options_6}


```
 can_save(options) 
```

Détermine si l'image peut être enregistrée au format de fichier spécifié représenté par les options d'enregistrement fournies.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Les options d'enregistrement à utiliser. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si l'image peut être enregistrée au format de fichier spécifié représenté par les options d'enregistrement fournies ; sinon, <c>false</c>. |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_7}


```
 create(image_options, width, height) 
```

Crée une nouvelle image en utilisant les options de création spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Les options d'image. |
| width | int | La largeur. |
| hauteur | int | La hauteur. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | L'image nouvellement créée. |


### Method: get_default_options(args) {#get_default_options_args_8}


```
 get_default_options(args) 
```

Obtient les options par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| args | object | Les arguments. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Options par défaut |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_9}


```
 get_file_format(file_path) 
```

Obtient le format de fichier.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | chaîne | Le chemin du fichier. |

**Returns**

| Type | Description |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Le format de fichier déterminé. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_10}


```
 get_file_format(stream) 
```

Obtient le format de fichier.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux. |

**Returns**

| Type | Description |
| :- | :- |
| [FileFormat](/psd/python-net/aspose.psd/fileformat) | Le format de fichier déterminé. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_11}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Obtient le rectangle qui s'adapte à l'image actuelle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle pour obtenir le rectangle d'ajustement. |
| pixels | int | Les pixels ARGB 32 bits. |
| width | int | La largeur de l'objet. |
| hauteur | int | La hauteur de l'objet. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle d'ajustement ou une exception si aucun rectangle d'ajustement ne peut être trouvé. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_12}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Obtient le rectangle qui s'adapte à l'image actuelle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle pour obtenir le rectangle d'ajustement. |
| width | int | La largeur de l'objet. |
| hauteur | int | La hauteur de l'objet. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle d'ajustement ou une exception si aucun rectangle d'ajustement ne peut être trouvé. |


### Method: get_original_options() {#get_original_options__13}


```
 get_original_options() 
```

Obtient les options basées sur les paramètres du fichier original.<br/>            Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés.<br/>            Par exemple, si nous chargeons une image PNG noir-et-blanc avec 1 bit par pixel puis la sauvegardons en utilisant le<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) méthode, l'image PNG de sortie avec 8 bits par pixel sera produite.<br/>            Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre<br/>            à la [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) méthode comme deuxième paramètre.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Les options basées sur les paramètres du fichier original. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_14}


```
 get_proportional_height(width, height, new_width) 
```

Obtient une hauteur proportionnelle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| width | int | La largeur. |
| hauteur | int | La hauteur. |
| new_width | int | La nouvelle largeur. |

**Returns**

| Type | Description |
| :- | :- |
| int | La hauteur proportionnelle. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_15}


```
 get_proportional_width(width, height, new_height) 
```

Obtient une largeur proportionnelle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| width | int | La largeur. |
| hauteur | int | La hauteur. |
| new_height | int | La nouvelle hauteur. |

**Returns**

| Type | Description |
| :- | :- |
| int | La largeur proportionnelle. |


### Method: load(file_path)  [static] {#load_file_path_16}


```
 load(file_path) 
```

Charge une nouvelle image depuis le fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | chaîne | Le chemin du fichier depuis lequel charger l'image. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | L'image chargée. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_17}


```
 load(file_path, load_options) 
```

Charge une nouvelle image depuis le fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | chaîne | Le chemin du fichier depuis lequel charger l'image. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Les options de chargement. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | L'image chargée. |


### Method: load(stream)  [static] {#load_stream_18}


```
 load(stream) 
```

Charge une nouvelle image depuis le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux depuis lequel charger l'image. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | L'image chargée. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_19}


```
 load(stream, load_options) 
```

Charge une nouvelle image depuis le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux depuis lequel charger l'image. |
| load_options | [LoadOptions](/psd/python-net/aspose.psd/loadoptions) | Les options de chargement. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/psd/python-net/aspose.psd/image) | L'image chargée. |


### Method: resize(new_width, new_height) {#resize_new_width_new_height_20}


```
 resize(new_width, new_height) 
```

Redimensionne l'image. Le [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) par défaut est utilisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| new_height | int | La nouvelle hauteur. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_21}


```
 resize(new_width, new_height, resize_type) 
```

Redimensionne l'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| new_height | int | La nouvelle hauteur. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Le type de redimensionnement. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_22}


```
 resize(new_width, new_height, settings) 
```

Redimensionne l'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| new_height | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Les paramètres de redimensionnement. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_23}


```
 resize_height_proportionally(new_height) 
```

Redimensionne la hauteur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_24}


```
 resize_height_proportionally(new_height, resize_type) 
```

Redimensionne la hauteur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Type du redimensionnement. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_25}


```
 resize_height_proportionally(new_height, settings) 
```

Redimensionne la hauteur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Les paramètres de redimensionnement de l'image. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_26}


```
 resize_width_proportionally(new_width) 
```

Redimensionne la largeur proportionnellement. Le [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) par défaut est utilisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_27}


```
 resize_width_proportionally(new_width, resize_type) 
```

Redimensionne la largeur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Type du redimensionnement. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_28}


```
 resize_width_proportionally(new_width, settings) 
```

Redimensionne la largeur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Les paramètres de redimensionnement de l'image. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_29}


```
 rotate_flip(rotate_flip_type) 
```

Fait pivoter, retourner ou pivoter et retourner l'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Type de la rotation inversée |

### Method: save(file_path) {#save_file_path_30}


```
 save(file_path) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | chaîne | Le chemin du fichier où enregistrer les données de l'objet. |

### Method: save(file_path, options) {#save_file_path_options_31}


```
 save(file_path, options) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | chaîne | Le chemin du fichier. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Les options. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_32}


```
 save(file_path, options, bounds_rectangle) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | chaîne | Le chemin du fichier. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Les options. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle des limites de l'image de destination. Définissez le rectangle vide pour utiliser les limites de la source. |

### Method: save(file_path, over_write) {#save_file_path_over_write_33}


```
 save(file_path, over_write) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | chaîne | Le chemin du fichier où enregistrer les données de l'objet. |
| over_write | bool | si défini sur <c>true</c> écrase le contenu du fichier, sinon une addition sera effectuée. |

### Method: save(stream) {#save_stream_34}


```
 save(stream) 
```

Enregistre les données de l'objet dans le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'objet. |

### Method: save(stream, options_base) {#save_stream_options_base_35}


```
 save(stream, options_base) 
```

Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'image. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Les options d'enregistrement. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_36}


```
 save(stream, options_base, bounds_rectangle) 
```

Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'image. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Les options d'enregistrement. |
| bounds_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle des limites de l'image de destination. Définissez le rectangle vide pour utiliser les limites de la source. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_37}


```
 set_palette(palette, update_colors) 
```

Définit la palette de l'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette à définir. |
| update_colors | bool | si défini sur <c>true</c> les couleurs seront mises à jour selon la nouvelle palette ; sinon les index de couleur restent inchangés. Notez que les index inchangés peuvent provoquer un plantage de l'image lors du chargement si certains index n'ont aucune entrée correspondante dans la palette. |

