---
title: "FontSettings 类"
type: docs
weight: 1370
url: /zh/python-net/aspose.psd/fontsettings/
---

**Summary:** General PSD vector formats renderer font settings.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.FontSettings

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| default_font_name [static] | 字符串 | 读/写 | 获取或设置字体的默认名称。 |
| get_system_alternative_font [static] | bool | 读/写 | 获取或设置一个值，指示是否 [get alternative font]。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| clear_font_replacements() | 清除所有字体替换 |
| [get_adobe_font_name(font_family_name)](#get_adobe_font_name_font_family_name_1) | 通过字体族名称获取 Adobe 字体名称。 |
| [get_default_fonts_folders()](#get_default_fonts_folders__2) | 获取默认字体文件夹。 |
| [get_font_replacements(font_name)](#get_font_replacements_font_name_3) | 通过字体名称获取字体替换数组 |
| [get_fonts_folders()](#get_fonts_folders__4) | 获取一个数组的副本，该数组包含 Aspose.Words 查找 TrueType 字体的文件夹列表。 |
| [get_replacement_font(font_name)](#get_replacement_font_font_name_5) | 获取最合适的替代字体。<br/>            如果所有替代字体均不被允许，则返回第一个被允许且可用的字体。<br/>            如果没有可用的字体，则返回参数中的字体。 |
| [is_font_allowed(font_name)](#is_font_allowed_font_name_6) | 确定 [is font allowed] [指定的字体名称] 是否被允许。 |
| remove_font_cache_file() | 删除字体缓存文件。 |
| reset() | 将字体文件夹和默认字体名称重置为系统默认值。 |
| [set_allowed_fonts(font_list)](#set_allowed_fonts_font_list_7) | 通过字体列表限制字体使用。请在限制前检查真实的字体名称<br/>            将允许的字体列表设为 Null 以移除限制。 |
| [set_font_replacements(font_to_replace, font_names)](#set_font_replacements_font_to_replace_font_names_8) | 设置字体替换列表。如果字体不被允许，则会寻找替代字体。<br/>            列表中的第一个字体将首先使用。如果它也被限制，则会选择列表中的下一个字体。<br/>            如果字体没有替代品或所有替代品都不被允许，则会使用允许字体列表中的第一个允许的字体。<br/>            如果没有允许且可用的字体，库将尝试使用系统默认字体，即使它不被允许。 |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_9) | 这是一个快捷方式，指向 [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/)，用于仅设置一个字体目录。<br/>            对字体文件夹不执行任何检查。 |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_10) | 设置加载 TrueType 字体的文件夹并清除所有已加载的字体。<br/>            对字体文件夹不执行任何检查。 |
| update_fonts() | 更新包含文字图层的 PSD 文件的字体缓存。此方法确保使用<br/>            FontSettings.SetFontsFolder(fontsFolder) 方法或在使用 FontSettings.Reset() 重置字体后，来自 fontsFolder 文件夹的字体在处理 PSD 文件时会被考虑。请在每次 <br/>            为 PSD 图像调用 FontSettings.SetFontsFolder(fontsFolder) 或 FontSettings.Reset() 时使用此方法。如果不调用此方法，则无法保证字体会被更新。 |


### Method: get_adobe_font_name(font_family_name)  [static] {#get_adobe_font_name_font_family_name_1}


```
 get_adobe_font_name(font_family_name) 
```

通过字体族名称获取 Adobe 字体名称。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| font_family_name | 字符串 | 字体族名称。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| 字符串 | Adobe 字体名称（按字体族名称）。 |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__2}


```
 get_default_fonts_folders() 
```

获取默认字体文件夹。

**Returns**

| 类型 | 描述 |
| :- | :- |
| 字符串 | 返回系统文件夹 |


### Method: get_font_replacements(font_name)  [static] {#get_font_replacements_font_name_3}


```
 get_font_replacements(font_name) 
```

通过字体名称获取字体替换数组

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| font_name | 字符串 | 字体名称。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| 字符串 | 提供的字体的替代名称数组 |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__4}


```
 get_fonts_folders() 
```

获取一个数组的副本，该数组包含 Aspose.Words 查找 TrueType 字体的文件夹列表。

**Returns**

| 类型 | 描述 |
| :- | :- |
| 字符串 | 当前字体位置的副本。 |


### Method: get_replacement_font(font_name)  [static] {#get_replacement_font_font_name_5}


```
 get_replacement_font(font_name) 
```

获取最合适的替代字体。<br/>            如果所有替代字体均不被允许，则返回第一个被允许且可用的字体。<br/>            如果没有可用的字体，则返回参数中的字体。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| font_name | 字符串 | 字体名称。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| 字符串 | 被替换的字体名称 |


### Method: is_font_allowed(font_name)  [static] {#is_font_allowed_font_name_6}


```
 is_font_allowed(font_name) 
```

确定 [is font allowed] [指定的字体名称] 是否被允许。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| font_name | 字符串 | 字体名称。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <c>true</c> 如果 [is font allowed] [指定的字体名称]；否则为 <c>false</c>。 |


### Method: set_allowed_fonts(font_list)  [static] {#set_allowed_fonts_font_list_7}


```
 set_allowed_fonts(font_list) 
```

通过字体列表限制字体使用。请在限制前检查真实的字体名称<br/>            将允许的字体列表设为 Null 以移除限制。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| font_list | 字符串 | 字体列表。 |

### Method: set_font_replacements(font_to_replace, font_names)  [static] {#set_font_replacements_font_to_replace_font_names_8}


```
 set_font_replacements(font_to_replace, font_names) 
```

设置字体替换列表。如果字体不被允许，则会寻找替代字体。<br/>            列表中的第一个字体将首先使用。如果它也被限制，则会选择列表中的下一个字体。<br/>            如果字体没有替代品或所有替代品都不被允许，则会使用允许字体列表中的第一个允许的字体。<br/>            如果没有允许且可用的字体，库将尝试使用系统默认字体，即使它不被允许。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| font_to_replace | 字符串 | 要替换的字体。 |
| font_names | 字符串 | 按相似度顺序排列的替代字体名称。 |

### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_9}


```
 set_fonts_folder(font_folder) 
```

这是一个快捷方式，指向 [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/)，用于仅设置一个字体目录。<br/>            对字体文件夹不执行任何检查。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| font_folder | 字符串 | 字体文件夹。 |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_10}


```
 set_fonts_folders(fonts_folders, recursive) 
```

设置加载 TrueType 字体的文件夹并清除所有已加载的字体。<br/>            对字体文件夹不执行任何检查。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| fonts_folders | 字符串 | 字体文件夹。 |
| 递归 | bool | 如果设置为 <c>true</c> [recursive]。 |

