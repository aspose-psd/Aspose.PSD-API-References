---
title: FontSettings Class
type: docs
weight: 1320
url: /python-net/aspose.psd/fontsettings/
---

**Summary:** General PSD vector formats renderer font settings.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.FontSettings

**Aspose.PSD Version:** 24.4.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| default_font_name [static] | string | r/w | Gets or sets the default name of the font. |
| get_system_alternative_font [static] | bool | r/w | Gets or sets a value indicating whether [get alternative font]. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| clear_font_replacements() | Clears the all fonts replacements |
| [get_adobe_font_name(font_family_name)](#get_adobe_font_name_font_family_name_1) | Gets the adobe font name by font family name. |
| [get_default_fonts_folders()](#get_default_fonts_folders__2) | Gets the default fonts folders. |
| [get_font_replacements(font_name)](#get_font_replacements_font_name_3) | Gets the font replacements array by the font name |
| [get_fonts_folders()](#get_fonts_folders__4) | Gets a copy of the array that contains the list of folders where Aspose.Words looks for TrueType fonts. |
| [get_replacement_font(font_name)](#get_replacement_font_font_name_5) | Gets the most suitable replacement font.<br/>            If all replacements are not allowed then will returned first allowed and available font.<br/>            If there are no available fonts then will be returned font from argument |
| [is_font_allowed(font_name)](#is_font_allowed_font_name_6) | Determines whether [is font allowed] [the specified font name]. |
| remove_font_cache_file() | Removes of the font cache file. |
| reset() | Resets the fonts folder and default font name to the system default. |
| [set_allowed_fonts(font_list)](#set_allowed_fonts_font_list_7) | Restricts font using by list of fonts. Please check real font names before restriction<br/>            Set Allowed font list to Null to remove restrictrions |
| [set_font_replacements(font_to_replace, font_names)](#set_font_replacements_font_to_replace_font_names_8) | Sets the font replacement list. If font is not allowed then will be find replacement.<br/>            The first one font in list will be used first. If it retricted too, then will be selected next font from list.<br/>            If font has not replacements or all replacements are not allowed then will be used first allowed font from allowed font list.<br/>            If there are no allowed and available fonts then library will try use system default font even if it is not allowed. |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_9) | This is a shortcut to [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) for setting only one font directory.<br/>            There are no checks performed on the fonts folder. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_10) | Sets the folders where TrueType fonts are loaded from and clears all loaded fonts.<br/>            There are no checks performed on the fonts folders. |
| update_fonts() | Updates fonts cache for PSD files that contain text layers. This method guarantees that fonts from folder fontsFolder using<br/>            method FontSettings.SetFontsFolder(fontsFolder) or after reset fonts using FontSettings.Reset() will be taken into consideration when processing PSD files. Please use this method each time when  <br/>            FontSettings.SetFontsFolder(fontsFolder) or FontSettings.Reset() called for PSD images. Without calling this Method there is no guarantee that fonts will be updated. |


### Method: get_adobe_font_name(font_family_name)  [static] {#get_adobe_font_name_font_family_name_1}


```
 get_adobe_font_name(font_family_name) 
```

Gets the adobe font name by font family name.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font_family_name | string | The font family name. |

**Returns**

| Type | Description |
| :- | :- |
| string | The adobe font name by font family name. |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__2}


```
 get_default_fonts_folders() 
```

Gets the default fonts folders.

**Returns**

| Type | Description |
| :- | :- |
| string | Returns system folder |


### Method: get_font_replacements(font_name)  [static] {#get_font_replacements_font_name_3}


```
 get_font_replacements(font_name) 
```

Gets the font replacements array by the font name

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font_name | string | Name of the font. |

**Returns**

| Type | Description |
| :- | :- |
| string | Array of names of replacements for provided fonts |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__4}


```
 get_fonts_folders() 
```

Gets a copy of the array that contains the list of folders where Aspose.Words looks for TrueType fonts.

**Returns**

| Type | Description |
| :- | :- |
| string | A copy of the current font locations. |


### Method: get_replacement_font(font_name)  [static] {#get_replacement_font_font_name_5}


```
 get_replacement_font(font_name) 
```

Gets the most suitable replacement font.<br/>            If all replacements are not allowed then will returned first allowed and available font.<br/>            If there are no available fonts then will be returned font from argument

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font_name | string | Name of the font. |

**Returns**

| Type | Description |
| :- | :- |
| string | The name of replaced font |


### Method: is_font_allowed(font_name)  [static] {#is_font_allowed_font_name_6}


```
 is_font_allowed(font_name) 
```

Determines whether [is font allowed] [the specified font name].

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font_name | string | Name of the font. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if [is font allowed] [the specified font name]; otherwise, <c>false</c>. |


### Method: set_allowed_fonts(font_list)  [static] {#set_allowed_fonts_font_list_7}


```
 set_allowed_fonts(font_list) 
```

Restricts font using by list of fonts. Please check real font names before restriction<br/>            Set Allowed font list to Null to remove restrictrions

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font_list | string | The font list. |

### Method: set_font_replacements(font_to_replace, font_names)  [static] {#set_font_replacements_font_to_replace_font_names_8}


```
 set_font_replacements(font_to_replace, font_names) 
```

Sets the font replacement list. If font is not allowed then will be find replacement.<br/>            The first one font in list will be used first. If it retricted too, then will be selected next font from list.<br/>            If font has not replacements or all replacements are not allowed then will be used first allowed font from allowed font list.<br/>            If there are no allowed and available fonts then library will try use system default font even if it is not allowed.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font_to_replace | string | The font to replace. |
| font_names | string | The replacement font names in order of similarity. |

### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_9}


```
 set_fonts_folder(font_folder) 
```

This is a shortcut to [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) for setting only one font directory.<br/>            There are no checks performed on the fonts folder.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| font_folder | string | The font folder. |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_10}


```
 set_fonts_folders(fonts_folders, recursive) 
```

Sets the folders where TrueType fonts are loaded from and clears all loaded fonts.<br/>            There are no checks performed on the fonts folders.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| fonts_folders | string | The fonts folders. |
| recursive | bool | if set to <c>true</c> [recursive]. |

