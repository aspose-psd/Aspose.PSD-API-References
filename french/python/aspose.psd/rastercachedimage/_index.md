---
title: "RasterCachedImage Classe"
type: docs
weight: 3730
url: /fr/python-net/aspose.psd/rastercachedimage/
---

**Summary:** Represents a raster image supporting raster graphics operations. This image caches pixel data when required.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.RasterCachedImage

**Inheritance:** IObjectWithBounds, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterImage

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Obtient ou définit une valeur indiquant si la palette d'ajustement automatique est activée. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| bits_per_pixel | int | r | Obtient le nombre de bits par pixel de l'image. |
| bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | r | Obtient les limites de l'objet. |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon qui définit la taille maximale autorisée pour tous les tampons internes. |
| container | [Image](/psd/python-net/aspose.psd/image) | r | Obtient le conteneur [Image](/psd/python-net/aspose.psd/image/). |
| data_stream_container | [StreamContainer](/psd/python-net/aspose.psd/streamcontainer) | r | Obtient le flux de données de l'objet. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| file_format | [FileFormat](/psd/python-net/aspose.psd/fileformat) | r | Obtient une valeur du format de fichier |
| a_alpha | bool | r | Obtient une valeur indiquant si cette instance possède un canal alpha. |
| a_couleur_de_fond | bool | r/w | Obtient ou définit une valeur indiquant si l'image possède une couleur d'arrière-plan. |
| a_couleur_transparente | bool | r/w | Obtient une valeur indiquant si l'image possède une couleur transparente. |
| hauteur | int | r | Obtient la hauteur de l'objet. |
| horizontal_resolution | double | r/w | Obtient ou définit la résolution horizontale, en pixels par pouce, de ce [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| opacité_image | float | r | Obtient l'opacité de cette image. |
| interrupt_monitor | [InterruptMonitor](/psd/python-net/aspose.psd.multithreading/interruptmonitor/) | r/w | Obtient ou définit le moniteur d'interruption. |
| est_en_cache | bool | r | Obtient une valeur indiquant si les données de l'image sont actuellement mises en cache. |
| est_donnees_brutes_disponibles | bool | r | Obtient une valeur indiquant si le chargement des données brutes est disponible. |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | r/w | Obtient ou définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement. |
| composants_premultipliés | bool | r/w | Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés. |
| raw_custom_color_converter | [IColorConverter](/psd/python-net/aspose.psd/icolorconverter) | r/w | Obtient ou définit le convertisseur de couleur personnalisé |
| raw_data_format | [PixelDataFormat](/psd/python-net/aspose.psd/pixeldataformat) | r | Obtient le format des données brutes. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | r | Obtient les paramètres actuels des données brutes. Notez que lors de l'utilisation de ces paramètres, les données sont chargées sans conversion. |
| indice_de_repli_brut | int | r/w | Obtient ou définit l'index de secours à utiliser lorsque l'index de palette est hors limites |
| raw_indexed_color_converter | [IIndexedColorConverter](/psd/python-net/aspose.psd/iindexedcolorconverter) | r/w | Obtient ou définit le convertisseur de couleur indexée |
| taille_de_ligne_brute | int | r | Obtient la taille de la ligne brute en octets. |
| size | [Size](/psd/python-net/aspose.psd/size) | r | Obtient la taille de l'objet. |
| transparent_color | [Color](/psd/python-net/aspose.psd/color) | r/w | Obtient la couleur transparente de l'image. |
| update_xmp_data | bool | r/w | Obtient ou définit une valeur indiquant s'il faut mettre à jour les métadonnées XMP. |
| use_palette | bool | r | Obtient une valeur indiquant si la palette de l'image est utilisée. |
| use_raw_data | bool | r/w | Obtient ou définit une valeur indiquant s'il faut utiliser le chargement de données brutes lorsque le chargement de données brutes est disponible. |
| vertical_resolution | double | r/w | Obtient ou définit la résolution verticale, en pixels par pouce, de ce [RasterImage](/psd/python-net/aspose.psd/rasterimage/). |
| width | int | r | Obtient la largeur de l'objet. |
| xmp_data | [XmpPacketWrapper](/psd/python-net/aspose.psd.xmp/xmppacketwrapper/) | r/w | Obtient ou définit les métadonnées XMP. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_1) | Ajuste la luminosité d'une image. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_2) | Contraste d'image. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_3) | Correction gamma d'une image. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_4) | Correction gamma d'une image. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_5) | Binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage par image intégrale. |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_6) | Binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage par image intégrale. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_7) | Binarisation d'une image avec un seuil prédéfini. |
| binarize_otsu() | Binarisation d'une image avec le seuillage d'Otsu. |
| cache_data() | Met en cache les données et garantit qu'aucun chargement supplémentaire de données ne sera effectué depuis le [DataStreamSupporter.data_stream_container](/psd/python-net/aspose.psd/datastreamsupporter/) sous-jacent. |
| [can_load(file_path)](#can_load_file_path_8) | Détermine si l'image peut être chargée depuis le chemin de fichier spécifié. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_9) | Détermine si l'image peut être chargée depuis le chemin de fichier spécifié et éventuellement en utilisant les options d'ouverture spécifiées. |
| [can_load(stream)](#can_load_stream_10) | Détermine si l'image peut être chargée depuis le flux spécifié. |
| [can_load(stream, load_options)](#can_load_stream_load_options_11) | Détermine si l'image peut être chargée depuis le flux spécifié et éventuellement en utilisant le <paramref name="loadOptions" /> spécifié. |
| [can_save(options)](#can_save_options_12) | Détermine si l'image peut être enregistrée au format de fichier spécifié représenté par les options d'enregistrement fournies. |
| [create(image_options, width, height)](#create_image_options_width_height_13) | Crée une nouvelle image en utilisant les options de création spécifiées. |
| crop(left_shift, right_shift, top_shift, bottom_shift) |  |
| [crop(rectangle)](#crop_rectangle_14) | Recadrage de l'image. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_15) | Effectue le tramage sur l'image actuelle. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_16) | Effectue le tramage sur l'image actuelle. |
| filter(rectangle, options) |  |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_17) | Obtient un pixel ARGB 32 bits d'une image. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_18) | Obtient le tableau de pixels ARGB 32 bits par défaut. |
| [get_default_options(args)](#get_default_options_args_19) | Obtient les options par défaut. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_20) | Obtient le tableau de pixels par défaut en utilisant le chargeur de pixels partiel. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_21) | Obtient le tableau de données brutes par défaut en utilisant le chargeur de pixels partiel. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_22) | Obtient le tableau de données brutes par défaut. |
| [get_file_format(file_path)](#get_file_format_file_path_23) | Obtient le format de fichier. |
| [get_file_format(stream)](#get_file_format_stream_24) | Obtient le format de fichier. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_25) | Obtient le rectangle qui s'adapte à l'image actuelle. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_26) | Obtient le rectangle qui s'adapte à l'image actuelle. |
| [get_modify_date(use_default)](#get_modify_date_use_default_27) | Obtient la date et l'heure de la dernière modification de l'image de la ressource. |
| [get_original_options()](#get_original_options__28) | Obtient les options basées sur les paramètres du fichier original.<br/>            Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés.<br/>            Par exemple, si nous chargeons une image PNG noir-et-blanc avec 1 bit par pixel puis la sauvegardons en utilisant le<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) méthode, l'image PNG de sortie avec 8 bits par pixel sera produite.<br/>            Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre<br/>            à la [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) méthode comme deuxième paramètre. |
| [get_pixel(x, y)](#get_pixel_x_y_29) | Obtient un pixel d'image.<br/>            Avertissement de performance : évitez d'utiliser cette méthode pour parcourir tous les pixels de l'image car cela peut entraîner d'importants problèmes de performance.<br/>            Pour une manipulation de pixels plus efficace, utilisez la méthode `LoadArgb32Pixels` pour récupérer l'ensemble du tableau de pixels simultanément. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_30) | Obtient une hauteur proportionnelle. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_31) | Obtient une largeur proportionnelle. |
| [get_skew_angle()](#get_skew_angle__32) |    |
| grayscale() | Transformation d'une image en sa représentation en niveaux de gris |
| [load(file_path)](#load_file_path_33) | Charge une nouvelle image depuis le fichier spécifié. |
| [load(file_path, load_options)](#load_file_path_load_options_34) | Charge une nouvelle image depuis le fichier spécifié. |
| [load(stream)](#load_stream_35) | Charge une nouvelle image depuis le flux spécifié. |
| [load(stream, load_options)](#load_stream_load_options_36) | Charge une nouvelle image depuis le flux spécifié. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_37) | Charge des pixels ARGB 32 bits. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_38) | Charge des pixels ARGB 64 bits. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_39) | Charge des pixels au format CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_40) | Charge des pixels au format CMYK.<br/>            Cette méthode est obsolète. Veuillez utiliser de façon plus efficace la [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) méthode. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_41) | Charge partiellement les pixels ARGB 32 bits par paquets. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_42) | Charge des pixels partiellement par paquets. |
| [load_pixels(rectangle)](#load_pixels_rectangle_43) | Charge des pixels. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_44) | Charge les données brutes. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_45) | Charge les données brutes. |
| normalize_angle() |  |
| normalize_angle(resize_proportionally, background_color) |  |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_46) | Lit la ligne de balayage complète à l'index de ligne de balayage spécifié. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_47) | Lit la ligne de balayage complète à l'index de ligne de balayage spécifié. |
| replace_color(old_color, old_color_diff, new_color) |  |
| replace_color(old_color_argb, old_color_diff, new_color_argb) |  |
| replace_non_transparent_colors(new_color) |  |
| replace_non_transparent_colors(new_color_argb) |  |
| [resize(new_width, new_height)](#resize_new_width_new_height_48) | Redimensionne l'image. Le [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) par défaut est utilisé. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_49) | Redimensionne l'image. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_50) | Redimensionne l'image. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_51) | Redimensionne la hauteur proportionnellement. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_52) | Redimensionne la hauteur proportionnellement. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_53) | Redimensionne la hauteur proportionnellement. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_54) | Redimensionne la largeur proportionnellement. Le [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) par défaut est utilisé. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_55) | Redimensionne la largeur proportionnellement. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_56) | Redimensionne la largeur proportionnellement. |
| rotate(angle) |  |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_57) | Fait pivoter l'image autour du centre. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_58) | Fait pivoter, retourner ou pivoter et retourner l'image. |
| save() | Enregistre les données de l'image dans le flux sous-jacent. |
| [save(file_path)](#save_file_path_59) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [save(file_path, options)](#save_file_path_options_60) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié selon les options d'enregistrement. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_61) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié selon les options d'enregistrement. |
| [save(file_path, over_write)](#save_file_path_over_write_62) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [save(stream)](#save_stream_63) | Enregistre les données de l'objet dans le flux spécifié. |
| [save(stream, options_base)](#save_stream_options_base_64) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié selon les options d'enregistrement. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_65) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié selon les options d'enregistrement. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_66) | Enregistre les pixels ARGB 32 bits. |
| save_cmyk_32_pixels(rectangle, pixels) |  |
| save_cmyk_pixels(rectangle, pixels) |  |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_67) | Enregistre les pixels (méthode spécifique au format). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_68) | Enregistre les données brutes. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_69) | Définit un pixel ARGB 32 bits de l'image pour la position spécifiée. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_70) | Définit la palette de l'image. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_71) | Définit un pixel de l'image pour la position spécifiée. |
| set_resolution(dpi_x, dpi_y) |  |
| [to_bitmap()](#to_bitmap__72) |    |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_73) | Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_74) | Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_1}


```
 adjust_brightness(brightness) 
```

Ajuste la luminosité d'une image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| luminosité | int | Valeur de luminosité. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_2}


```
 adjust_contrast(contrast) 
```

Contraste d'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| contraste | float | Valeur de contraste (dans la plage [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_3}


```
 adjust_gamma(gamma) 
```

Correction gamma d'une image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| gamma | float | Coefficient gamma pour les canaux rouge, vert et bleu |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_4}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Correction gamma d'une image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| gamma_red | float | Coefficient gamma pour le canal rouge |
| gamma_green | float | Coefficient gamma pour le canal vert |
| gamma_blue | float | Coefficient gamma pour le canal bleu |

### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_5}


```
 binarize_bradley(brightness_difference) 
```

Binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage par image intégrale.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brightness_difference | double | La différence de luminosité entre le pixel et la moyenne d'une fenêtre de s × s pixels centrée sur ce pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_6}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarisation d'une image en utilisant l'algorithme de seuillage adaptatif de Bradley avec le seuillage par image intégrale.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brightness_difference | double | La différence de luminosité entre le pixel et la moyenne d'une fenêtre de s × s pixels centrée sur ce pixel. |
| window_size | int | La taille de la fenêtre de s × s pixels centrée sur ce pixel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_7}


```
 binarize_fixed(threshold) 
```

Binarisation d'une image avec un seuil prédéfini.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| threshold | byte | Valeur du seuil. Si la valeur de gris correspondante d'un pixel est supérieure au seuil, une valeur de 255 lui sera attribuée, sinon 0. |

### Method: can_load(file_path)  [static] {#can_load_file_path_8}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_9}


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


### Method: can_load(stream)  [static] {#can_load_stream_10}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_11}


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


### Method: can_save(options) {#can_save_options_12}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_13}


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


### Method: crop(rectangle) {#crop_rectangle_14}


```
 crop(rectangle) 
```

Recadrage de l'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_15}


```
 dither(dithering_method, bits_count) 
```

Effectue le tramage sur l'image actuelle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | La méthode de tramage. |
| bits_count | int | Le nombre final de bits pour le tramage. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_16}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Effectue le tramage sur l'image actuelle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/psd/python-net/aspose.psd/ditheringmethod) | La méthode de tramage. |
| bits_count | int | Le nombre final de bits pour le tramage. |
| custom_palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette personnalisée pour le tramage. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_17}


```
 get_argb_32_pixel(x, y) 
```

Obtient un pixel ARGB 32 bits d'une image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | L'emplacement x du pixel. |
| y | int | L'emplacement y du pixel. |

**Returns**

| Type | Description |
| :- | :- |
| int | Le pixel ARGB 32 bits pour l'emplacement spécifié. |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_18}


```
 get_default_argb_32_pixels(rectangle) 
```

Obtient le tableau de pixels ARGB 32 bits par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle pour obtenir les pixels. |

**Returns**

| Type | Description |
| :- | :- |
| int | Le tableau de pixels par défaut. |


### Method: get_default_options(args) {#get_default_options_args_19}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_20}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Obtient le tableau de pixels par défaut en utilisant le chargeur de pixels partiel.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle pour obtenir les pixels. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Le chargeur partiel de pixels. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_21}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

Obtient le tableau de données brutes par défaut en utilisant le chargeur de pixels partiel.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle pour obtenir les pixels. |
| partial_raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Le chargeur partiel de données brutes. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Les paramètres des données brutes. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_22}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

Obtient le tableau de données brutes par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle pour obtenir les données brutes. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Les paramètres des données brutes. |

**Returns**

| Type | Description |
| :- | :- |
| byte | Le tableau de données brutes par défaut. |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_23}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_24}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_25}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_26}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_27}


```
 get_modify_date(use_default) 
```

Obtient la date et l'heure de la dernière modification de l'image de la ressource.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| use_default | bool | si défini sur <c>true</c> utilise les informations de FileInfo comme valeur par défaut. |

**Returns**

| Type | Description |
| :- | :- |
| datetime | La date et l'heure auxquelles l'image de la ressource a été modifiée pour la dernière fois. |


### Method: get_original_options() {#get_original_options__28}


```
 get_original_options() 
```

Obtient les options basées sur les paramètres du fichier original.<br/>            Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés.<br/>            Par exemple, si nous chargeons une image PNG noir-et-blanc avec 1 bit par pixel puis la sauvegardons en utilisant le<br/>            [DataStreamSupporter.save(file_path)](/psd/python-net/aspose.psd/datastreamsupporter/) méthode, l'image PNG de sortie avec 8 bits par pixel sera produite.<br/>            Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre<br/>            à la [Image.save(file_path, options)](/psd/python-net/aspose.psd/image/) méthode comme deuxième paramètre.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Les options basées sur les paramètres du fichier original. |


### Method: get_pixel(x, y) {#get_pixel_x_y_29}


```
 get_pixel(x, y) 
```

Obtient un pixel d'image.<br/>            Avertissement de performance : évitez d'utiliser cette méthode pour parcourir tous les pixels de l'image car cela peut entraîner d'importants problèmes de performance.<br/>            Pour une manipulation de pixels plus efficace, utilisez la méthode `LoadArgb32Pixels` pour récupérer l'ensemble du tableau de pixels simultanément.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | L'emplacement x du pixel. |
| y | int | L'emplacement y du pixel. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/psd/python-net/aspose.psd/color) | La couleur du pixel pour l'emplacement spécifié. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_30}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_31}


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


### Method: get_skew_angle() {#get_skew_angle__32}


```
 get_skew_angle() 
```

  

**Returns**

| Type | Description |
| :- | :- |
| float |  |


### Method: load(file_path)  [static] {#load_file_path_33}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_34}


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


### Method: load(stream)  [static] {#load_stream_35}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_36}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_37}


```
 load_argb_32_pixels(rectangle) 
```

Charge des pixels ARGB 32 bits.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle depuis lequel charger les pixels. |

**Returns**

| Type | Description |
| :- | :- |
| int | Le tableau de pixels 32 bits ARGB chargé. |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_38}


```
 load_argb_64_pixels(rectangle) 
```

Charge des pixels ARGB 64 bits.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle depuis lequel charger les pixels. |

**Returns**

| Type | Description |
| :- | :- |
| long | Le tableau de pixels 64 bits ARGB chargé. |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_39}


```
 load_cmyk_32_pixels(rectangle) 
```

Charge des pixels au format CMYK.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle depuis lequel charger les pixels. |

**Returns**

| Type | Description |
| :- | :- |
| int | Les pixels CMYK chargés présentés sous forme de valeurs entières 32 bits. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_40}


```
 load_cmyk_pixels(rectangle) 
```

Charge des pixels au format CMYK.<br/>            Cette méthode est obsolète. Veuillez utiliser de façon plus efficace la [RasterImage.load_cmyk_32_pixels(rectangle)](/psd/python-net/aspose.psd/rasterimage/) méthode.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle depuis lequel charger les pixels. |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor[]](/psd/python-net/aspose.psd/cmykcolor) | Le tableau de pixels CMYK chargé. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_41}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Charge partiellement les pixels ARGB 32 bits par paquets.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle souhaité. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/psd/python-net/aspose.psd/ipartialargb32pixelloader) | Le chargeur de pixels ARGB 32 bits. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_42}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Charge des pixels partiellement par paquets.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle souhaité. |
| pixel_loader | [IPartialPixelLoader](/psd/python-net/aspose.psd/ipartialpixelloader) | Le chargeur de pixels. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_43}


```
 load_pixels(rectangle) 
```

Charge des pixels.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle depuis lequel charger les pixels. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Le tableau de pixels chargé. |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_44}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

Charge les données brutes.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle à partir duquel charger les données brutes. |
| dest_image_bounds | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Les limites de l'image de destination. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Les paramètres de données brutes à utiliser pour les données chargées. Notez que si les données ne sont pas au format spécifié, une conversion des données sera effectuée. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Le chargeur de données brutes. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_45}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Charge les données brutes.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle à partir duquel charger les données brutes. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Les paramètres de données brutes à utiliser pour les données chargées. Notez que si les données ne sont pas au format spécifié, une conversion des données sera effectuée. |
| raw_data_loader | [IPartialRawDataLoader](/psd/python-net/aspose.psd/ipartialrawdataloader) | Le chargeur de données brutes. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_46}


```
 read_argb_32_scan_line(scan_line_index) 
```

Lit la ligne de balayage complète à l'index de ligne de balayage spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Indice basé sur zéro de la ligne de numérisation. |

**Returns**

| Type | Description |
| :- | :- |
| int | Le tableau des valeurs de couleur ARGB 32 bits de la ligne de numérisation. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_47}


```
 read_scan_line(scan_line_index) 
```

Lit la ligne de balayage complète à l'index de ligne de balayage spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Indice basé sur zéro de la ligne de numérisation. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/psd/python-net/aspose.psd/color) | Le tableau des valeurs de couleur des pixels de la ligne de numérisation. |


### Method: resize(new_width, new_height) {#resize_new_width_new_height_48}


```
 resize(new_width, new_height) 
```

Redimensionne l'image. Le [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) par défaut est utilisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| new_height | int | La nouvelle hauteur. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_49}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_50}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_51}


```
 resize_height_proportionally(new_height) 
```

Redimensionne la hauteur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_52}


```
 resize_height_proportionally(new_height, resize_type) 
```

Redimensionne la hauteur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Type du redimensionnement. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_53}


```
 resize_height_proportionally(new_height, settings) 
```

Redimensionne la hauteur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Les paramètres de redimensionnement de l'image. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_54}


```
 resize_width_proportionally(new_width) 
```

Redimensionne la largeur proportionnellement. Le [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/psd/python-net/aspose.psd/resizetype/) par défaut est utilisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_55}


```
 resize_width_proportionally(new_width, resize_type) 
```

Redimensionne la largeur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| resize_type | [ResizeType](/psd/python-net/aspose.psd/resizetype) | Type du redimensionnement. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_56}


```
 resize_width_proportionally(new_width, settings) 
```

Redimensionne la largeur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| settings | [ImageResizeSettings](/psd/python-net/aspose.psd/imageresizesettings) | Les paramètres de redimensionnement de l'image. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_57}


```
 rotate(angle, resize_proportionally, background_color) 
```

Fait pivoter l'image autour du centre.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens horaire. |
| resize_proportionally | bool | si défini sur <c>true</c> la taille de votre image sera modifiée selon les projections du rectangle pivoté (points d'angle); sinon les dimensions restent inchangées et seul le contenu interne de l'image est pivoté. |
| background_color | [Color](/psd/python-net/aspose.psd/color) | Couleur de l'arrière-plan. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_58}


```
 rotate_flip(rotate_flip_type) 
```

Fait pivoter, retourner ou pivoter et retourner l'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/psd/python-net/aspose.psd/rotatefliptype) | Le type de retournement de rotation. |

### Method: save(file_path) {#save_file_path_59}


```
 save(file_path) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | chaîne | Le chemin du fichier où enregistrer les données de l'objet. |

### Method: save(file_path, options) {#save_file_path_options_60}


```
 save(file_path, options) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier spécifié selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | chaîne | Le chemin du fichier. |
| options | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Les options. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_61}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_62}


```
 save(file_path, over_write) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | chaîne | Le chemin du fichier où enregistrer les données de l'objet. |
| over_write | bool | si défini sur <c>true</c> écrase le contenu du fichier, sinon une addition sera effectuée. |

### Method: save(stream) {#save_stream_63}


```
 save(stream) 
```

Enregistre les données de l'objet dans le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'objet. |

### Method: save(stream, options_base) {#save_stream_options_base_64}


```
 save(stream, options_base) 
```

Enregistre les données de l'image dans le flux spécifié dans le format de fichier spécifié selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'image. |
| options_base | [ImageOptionsBase](/psd/python-net/aspose.psd/imageoptionsbase) | Les options d'enregistrement. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_65}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_66}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Enregistre les pixels ARGB 32 bits.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle où enregistrer les pixels. |
| pixels | int | Le tableau de pixels ARGB 32 bits. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_67}


```
 save_pixels(rectangle, pixels) 
```

Enregistre les pixels (méthode spécifique au format).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle où enregistrer les pixels. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Le tableau de pixels ARGB 32 bits. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_68}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

Enregistre les données brutes.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| data | byte | Les données brutes. |
| data_offset | int | Le décalage de départ des données brutes. |
| rectangle | [Rectangle](/psd/python-net/aspose.psd/rectangle) | Le rectangle des données brutes. |
| raw_data_settings | [RawDataSettings](/psd/python-net/aspose.psd/rawdatasettings) | Les paramètres des données brutes où se trouvent les données. |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_69}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

Définit un pixel ARGB 32 bits de l'image pour la position spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | L'emplacement x du pixel. |
| y | int | L'emplacement y du pixel. |
| argb_32_color | int | Le pixel ARGB 32 bits pour la position spécifiée. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_70}


```
 set_palette(palette, update_colors) 
```

Définit la palette de l'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/psd/python-net/aspose.psd/icolorpalette) | La palette à définir. |
| update_colors | bool | si défini sur <c>true</c> les couleurs seront mises à jour selon la nouvelle palette ; sinon les index de couleur restent inchangés. Notez que les index inchangés peuvent provoquer un plantage de l'image lors du chargement si certains index n'ont aucune entrée correspondante dans la palette. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_71}


```
 set_pixel(x, y, color) 
```

Définit un pixel de l'image pour la position spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | L'emplacement x du pixel. |
| y | int | L'emplacement y du pixel. |
| color | [Color](/psd/python-net/aspose.psd/color) | La couleur du pixel pour la position spécifiée. |

### Method: to_bitmap() {#to_bitmap__72}


```
 to_bitmap() 
```

  

**Returns**

| Type | Description |
| :- | :- |
| aspose.pydrawing.Bitmap |  |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_73}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Indice basé sur zéro de la ligne de numérisation. |
| argb_32_pixels | int | Le tableau de couleurs ARGB 32 bits à écrire. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_74}


```
 write_scan_line(scan_line_index, pixels) 
```

Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Indice basé sur zéro de la ligne de numérisation. |
| pixels | [Color[]](/psd/python-net/aspose.psd/color) | Le tableau de couleurs de pixels à écrire. |

