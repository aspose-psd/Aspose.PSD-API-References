---
title: "FontSettings Класс"
type: docs
weight: 1370
url: /ru/python-net/aspose.psd/fontsettings/
---

**Summary:** General PSD vector formats renderer font settings.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.FontSettings

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| default_font_name [static] | string | r/w | Получает или задает имя шрифта по умолчанию. |
| get_system_alternative_font [static] | bool | r/w | Получает или задает значение, указывающее, следует ли [get alternative font]. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| clear_font_replacements() | Очищает все замены шрифтов |
| [get_adobe_font_name(font_family_name)](#get_adobe_font_name_font_family_name_1) | Получает имя шрифта Adobe по имени семейства шрифтов. |
| [get_default_fonts_folders()](#get_default_fonts_folders__2) | Получает папки шрифтов по умолчанию. |
| [get_font_replacements(font_name)](#get_font_replacements_font_name_3) | Получает массив замен шрифтов по имени шрифта |
| [get_fonts_folders()](#get_fonts_folders__4) | Получает копию массива, содержащего список папок, где Aspose.Words ищет TrueType шрифты. |
| [get_replacement_font(font_name)](#get_replacement_font_font_name_5) | Получает наиболее подходящий заменяющий шрифт.<br/>            Если все замены не разрешены, будет возвращён первый разрешённый и доступный шрифт.<br/>            Если доступных шрифтов нет, будет возвращён шрифт из аргумента |
| [is_font_allowed(font_name)](#is_font_allowed_font_name_6) | Определяет, [is font allowed] [the specified font name]. |
| remove_font_cache_file() | Удаляет файл кэша шрифтов. |
| reset() | Сбрасывает папку шрифтов и имя шрифта по умолчанию до системных значений. |
| [set_allowed_fonts(font_list)](#set_allowed_fonts_font_list_7) | Ограничивает использование шрифтов списком шрифтов. Пожалуйста, проверьте реальные имена шрифтов перед ограничением<br/>            Установите список разрешённых шрифтов в Null, чтобы снять ограничения. |
| [set_font_replacements(font_to_replace, font_names)](#set_font_replacements_font_to_replace_font_names_8) | Устанавливает список замен шрифтов. Если шрифт не разрешён, будет найдена замена.<br/>            Первый шрифт в списке будет использован первым. Если он также ограничен, будет выбран следующий шрифт из списка.<br/>            Если у шрифта нет замен или все замены не разрешены, будет использован первый разрешённый шрифт из списка разрешённых шрифтов.<br/>            Если нет ни разрешённых, ни доступных шрифтов, библиотека попытается использовать системный шрифт по умолчанию, даже если он не разрешён. |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_9) | Это сокращение для [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) при указании только одной папки шрифтов.<br/>            Проверки папки шрифтов не выполняются. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_10) | Устанавливает папки, из которых загружаются TrueType‑шрифты, и очищает все загруженные шрифты.<br/>            Проверки папок шрифтов не выполняются. |
| update_fonts() | Обновляет кэш шрифтов для PSD‑файлов, содержащих текстовые слои. Этот метод гарантирует, что шрифты из папки fontsFolder, использующие<br/>            метод FontSettings.SetFontsFolder(fontsFolder) или после сброса шрифтов с помощью FontSettings.Reset(), будут учитываться при обработке PSD‑файлов. Пожалуйста, вызывайте этот метод каждый раз, когда <br/>            FontSettings.SetFontsFolder(fontsFolder) или FontSettings.Reset() вызываются для PSD‑изображений. Без вызова этого метода нет гарантии, что шрифты будут обновлены. |


### Method: get_adobe_font_name(font_family_name)  [static] {#get_adobe_font_name_font_family_name_1}


```
 get_adobe_font_name(font_family_name) 
```

Получает имя шрифта Adobe по имени семейства шрифтов.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_family_name | string | Имя семейства шрифта. |

**Returns**

| Тип | Описание |
| :- | :- |
| string | Имя шрифта Adobe по имени семейства шрифта. |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__2}


```
 get_default_fonts_folders() 
```

Получает папки шрифтов по умолчанию.

**Returns**

| Тип | Описание |
| :- | :- |
| string | Возвращает системную папку |


### Method: get_font_replacements(font_name)  [static] {#get_font_replacements_font_name_3}


```
 get_font_replacements(font_name) 
```

Получает массив замен шрифтов по имени шрифта

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_name | string | Имя шрифта. |

**Returns**

| Тип | Описание |
| :- | :- |
| string | Массив имён замен для указанных шрифтов |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__4}


```
 get_fonts_folders() 
```

Получает копию массива, содержащего список папок, где Aspose.Words ищет TrueType шрифты.

**Returns**

| Тип | Описание |
| :- | :- |
| string | Копия текущих местоположений шрифтов. |


### Method: get_replacement_font(font_name)  [static] {#get_replacement_font_font_name_5}


```
 get_replacement_font(font_name) 
```

Получает наиболее подходящий заменяющий шрифт.<br/>            Если все замены не разрешены, будет возвращён первый разрешённый и доступный шрифт.<br/>            Если доступных шрифтов нет, будет возвращён шрифт из аргумента

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_name | string | Имя шрифта. |

**Returns**

| Тип | Описание |
| :- | :- |
| string | Имя заменённого шрифта |


### Method: is_font_allowed(font_name)  [static] {#is_font_allowed_font_name_6}


```
 is_font_allowed(font_name) 
```

Определяет, [is font allowed] [the specified font name].

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_name | string | Имя шрифта. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <c>true</c> если [is font allowed] [the specified font name]; иначе, <c>false</c>. |


### Method: set_allowed_fonts(font_list)  [static] {#set_allowed_fonts_font_list_7}


```
 set_allowed_fonts(font_list) 
```

Ограничивает использование шрифтов списком шрифтов. Пожалуйста, проверьте реальные имена шрифтов перед ограничением<br/>            Установите список разрешённых шрифтов в Null, чтобы снять ограничения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_list | string | Список шрифтов. |

### Method: set_font_replacements(font_to_replace, font_names)  [static] {#set_font_replacements_font_to_replace_font_names_8}


```
 set_font_replacements(font_to_replace, font_names) 
```

Устанавливает список замен шрифтов. Если шрифт не разрешён, будет найдена замена.<br/>            Первый шрифт в списке будет использован первым. Если он также ограничен, будет выбран следующий шрифт из списка.<br/>            Если у шрифта нет замен или все замены не разрешены, будет использован первый разрешённый шрифт из списка разрешённых шрифтов.<br/>            Если нет ни разрешённых, ни доступных шрифтов, библиотека попытается использовать системный шрифт по умолчанию, даже если он не разрешён.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_to_replace | string | Шрифт для замены. |
| font_names | string | Имена заменяющих шрифтов в порядке схожести. |

### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_9}


```
 set_fonts_folder(font_folder) 
```

Это сокращение для [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) при указании только одной папки шрифтов.<br/>            Проверки папки шрифтов не выполняются.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| font_folder | string | Папка шрифтов. |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_10}


```
 set_fonts_folders(fonts_folders, recursive) 
```

Устанавливает папки, из которых загружаются TrueType‑шрифты, и очищает все загруженные шрифты.<br/>            Проверки папок шрифтов не выполняются.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| fonts_folders | string | Папки шрифтов. |
| рекурсивный | bool | если установлено в <c>true</c> [recursive]. |

