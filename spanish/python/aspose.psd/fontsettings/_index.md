---
title: "Clase FontSettings"
type: docs
weight: 1370
url: /es/python-net/aspose.psd/fontsettings/
---

**Summary:** General PSD vector formats renderer font settings.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.FontSettings

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| default_font_name [static] | string | r/w | Obtiene o establece el nombre predeterminado de la fuente. |
| get_system_alternative_font [static] | bool | r/w | Obtiene o establece un valor que indica si [get alternative font]. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| clear_font_replacements() | Borra todas las sustituciones de fuentes |
| [get_adobe_font_name(font_family_name)](#get_adobe_font_name_font_family_name_1) | Obtiene el nombre de fuente Adobe a partir del nombre de la familia de fuentes. |
| [get_default_fonts_folders()](#get_default_fonts_folders__2) | Obtiene las carpetas predeterminadas de fuentes. |
| [get_font_replacements(font_name)](#get_font_replacements_font_name_3) | Obtiene la matriz de sustituciones de fuentes por el nombre de la fuente |
| [get_fonts_folders()](#get_fonts_folders__4) | Obtiene una copia de la matriz que contiene la lista de carpetas donde Aspose.Words busca fuentes TrueType. |
| [get_replacement_font(font_name)](#get_replacement_font_font_name_5) | Obtiene la fuente de sustitución más adecuada.<br/>            Si todas las sustituciones no están permitidas, se devolverá la primera fuente permitida y disponible.<br/>            Si no hay fuentes disponibles, se devolverá la fuente del argumento |
| [is_font_allowed(font_name)](#is_font_allowed_font_name_6) | Determina si [is font allowed] [the specified font name]. |
| remove_font_cache_file() | Elimina el archivo de caché de fuentes. |
| reset() | Restablece la carpeta de fuentes y el nombre de fuente predeterminado al valor predeterminado del sistema. |
| [set_allowed_fonts(font_list)](#set_allowed_fonts_font_list_7) | Restringe el uso de fuentes mediante una lista de fuentes. Por favor, verifica los nombres reales de las fuentes antes de la restricción<br/>            Establece la lista de fuentes permitidas a Null para eliminar las restricciones |
| [set_font_replacements(font_to_replace, font_names)](#set_font_replacements_font_to_replace_font_names_8) | Establece la lista de reemplazo de fuentes. Si la fuente no está permitida, se encontrará un reemplazo.<br/>            La primera fuente de la lista se usará primero. Si también está restringida, se seleccionará la siguiente fuente de la lista.<br/>            Si la fuente no tiene reemplazos o todos los reemplazos no están permitidos, se usará la primera fuente permitida de la lista de fuentes permitidas.<br/>            Si no hay fuentes permitidas y disponibles, la biblioteca intentará usar la fuente predeterminada del sistema aunque no esté permitida. |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_9) | Este es un acceso directo a [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) para configurar solo un directorio de fuentes.<br/>            No se realizan verificaciones en la carpeta de fuentes. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_10) | Establece las carpetas desde donde se cargan las fuentes TrueType y borra todas las fuentes cargadas.<br/>            No se realizan verificaciones en las carpetas de fuentes. |
| update_fonts() | Actualiza la caché de fuentes para archivos PSD que contienen capas de texto. Este método garantiza que las fuentes de la carpeta fontsFolder usando<br/>            el método FontSettings.SetFontsFolder(fontsFolder) o después de restablecer fuentes con FontSettings.Reset() se tengan en cuenta al procesar archivos PSD. Por favor, use este método cada vez que <br/>            se llame a FontSettings.SetFontsFolder(fontsFolder) o FontSettings.Reset() para imágenes PSD. Sin llamar a este método no hay garantía de que las fuentes se actualicen. |


### Method: get_adobe_font_name(font_family_name)  [static] {#get_adobe_font_name_font_family_name_1}


```
 get_adobe_font_name(font_family_name) 
```

Obtiene el nombre de fuente Adobe a partir del nombre de la familia de fuentes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_family_name | string | El nombre de la familia de fuentes. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | El nombre de la fuente Adobe por nombre de familia de fuentes. |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__2}


```
 get_default_fonts_folders() 
```

Obtiene las carpetas predeterminadas de fuentes.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Devuelve la carpeta del sistema |


### Method: get_font_replacements(font_name)  [static] {#get_font_replacements_font_name_3}


```
 get_font_replacements(font_name) 
```

Obtiene la matriz de sustituciones de fuentes por el nombre de la fuente

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_name | string | Nombre de la fuente. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Matriz de nombres de reemplazos para las fuentes proporcionadas |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__4}


```
 get_fonts_folders() 
```

Obtiene una copia de la matriz que contiene la lista de carpetas donde Aspose.Words busca fuentes TrueType.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Una copia de las ubicaciones actuales de fuentes. |


### Method: get_replacement_font(font_name)  [static] {#get_replacement_font_font_name_5}


```
 get_replacement_font(font_name) 
```

Obtiene la fuente de sustitución más adecuada.<br/>            Si todas las sustituciones no están permitidas, se devolverá la primera fuente permitida y disponible.<br/>            Si no hay fuentes disponibles, se devolverá la fuente del argumento

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_name | string | Nombre de la fuente. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | El nombre de la fuente reemplazada |


### Method: is_font_allowed(font_name)  [static] {#is_font_allowed_font_name_6}


```
 is_font_allowed(font_name) 
```

Determina si [is font allowed] [the specified font name].

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_name | string | Nombre de la fuente. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <c>true</c> si [is font allowed] [el nombre de fuente especificado]; de lo contrario, <c>false</c>. |


### Method: set_allowed_fonts(font_list)  [static] {#set_allowed_fonts_font_list_7}


```
 set_allowed_fonts(font_list) 
```

Restringe el uso de fuentes mediante una lista de fuentes. Por favor, verifica los nombres reales de las fuentes antes de la restricción<br/>            Establece la lista de fuentes permitidas a Null para eliminar las restricciones

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_list | string | La lista de fuentes. |

### Method: set_font_replacements(font_to_replace, font_names)  [static] {#set_font_replacements_font_to_replace_font_names_8}


```
 set_font_replacements(font_to_replace, font_names) 
```

Establece la lista de reemplazo de fuentes. Si la fuente no está permitida, se encontrará un reemplazo.<br/>            La primera fuente de la lista se usará primero. Si también está restringida, se seleccionará la siguiente fuente de la lista.<br/>            Si la fuente no tiene reemplazos o todos los reemplazos no están permitidos, se usará la primera fuente permitida de la lista de fuentes permitidas.<br/>            Si no hay fuentes permitidas y disponibles, la biblioteca intentará usar la fuente predeterminada del sistema aunque no esté permitida.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_to_replace | string | La fuente a reemplazar. |
| font_names | string | Los nombres de fuentes de reemplazo en orden de similitud. |

### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_9}


```
 set_fonts_folder(font_folder) 
```

Este es un acceso directo a [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) para configurar solo un directorio de fuentes.<br/>            No se realizan verificaciones en la carpeta de fuentes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| font_folder | string | La carpeta de fuentes. |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_10}


```
 set_fonts_folders(fonts_folders, recursive) 
```

Establece las carpetas desde donde se cargan las fuentes TrueType y borra todas las fuentes cargadas.<br/>            No se realizan verificaciones en las carpetas de fuentes.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| fonts_folders | string | Las carpetas de fuentes. |
| recursivo | bool | si se establece en <c>true</c> [recursive]. |

