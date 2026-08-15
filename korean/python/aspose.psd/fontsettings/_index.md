---
title: "FontSettings 클래스"
type: docs
weight: 1370
url: /ko/python-net/aspose.psd/fontsettings/
---

**Summary:** General PSD vector formats renderer font settings.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.FontSettings

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **설명** |
| :- | :- | :- | :- |
| default_font_name [static] | 문자열 | r/w | 글꼴의 기본 이름을 가져오거나 설정합니다. |
| get_system_alternative_font [static] | bool | r/w | 대체 글꼴을 가져올지 여부를 나타내는 값을 가져오거나 설정합니다. |
## **Methods**
| **Name** | **설명** |
| :- | :- |
| clear_font_replacements() | 모든 글꼴 교체를 지웁니다. |
| [get_adobe_font_name(font_family_name)](#get_adobe_font_name_font_family_name_1) | 글꼴 패밀리 이름으로 Adobe 글꼴 이름을 가져옵니다. |
| [get_default_fonts_folders()](#get_default_fonts_folders__2) | 기본 글꼴 폴더를 가져옵니다. |
| [get_font_replacements(font_name)](#get_font_replacements_font_name_3) | 글꼴 이름으로 글꼴 교체 배열을 가져옵니다. |
| [get_fonts_folders()](#get_fonts_folders__4) | Aspose.Words가 TrueType 글꼴을 찾는 폴더 목록을 포함하는 배열의 복사본을 가져옵니다. |
| [get_replacement_font(font_name)](#get_replacement_font_font_name_5) | 가장 적합한 대체 글꼴을 가져옵니다.<br/>            모든 교체가 허용되지 않으면 첫 번째 허용되고 사용 가능한 글꼴이 반환됩니다.<br/>            사용 가능한 글꼴이 없으면 인수에서 전달된 글꼴이 반환됩니다. |
| [is_font_allowed(font_name)](#is_font_allowed_font_name_6) | 지정된 글꼴 이름이 허용되는지 여부를 결정합니다. |
| remove_font_cache_file() | 글꼴 캐시 파일을 제거합니다. |
| reset() | 폰트 폴더와 기본 폰트 이름을 시스템 기본값으로 재설정합니다. |
| [set_allowed_fonts(font_list)](#set_allowed_fonts_font_list_7) | 폰트를 폰트 목록으로 제한합니다. 제한하기 전에 실제 폰트 이름을 확인하십시오<br/>            허용된 폰트 목록을 Null로 설정하여 제한을 제거합니다. |
| [set_font_replacements(font_to_replace, font_names)](#set_font_replacements_font_to_replace_font_names_8) | 폰트 교체 목록을 설정합니다. 폰트가 허용되지 않으면 교체 폰트를 찾습니다.<br/>            목록의 첫 번째 폰트가 먼저 사용됩니다. 그것도 제한된다면 목록에서 다음 폰트가 선택됩니다.<br/>            폰트에 교체 폰트가 없거나 모든 교체 폰트가 허용되지 않으면 허용된 폰트 목록에서 첫 번째 허용 폰트가 사용됩니다.<br/>            허용되고 사용 가능한 폰트가 없을 경우 라이브러리는 시스템 기본 폰트를 사용하려 시도합니다(비허용이라도). |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_9) | 이는 하나의 폰트 디렉터리만 설정하기 위한 [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) 바로 가기입니다.<br/>            폰트 폴더에 대한 검사는 수행되지 않습니다. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_10) | TrueType 폰트가 로드되는 폴더를 설정하고 로드된 모든 폰트를 삭제합니다.<br/>            폰트 폴더에 대한 검사는 수행되지 않습니다. |
| update_fonts() | 텍스트 레이어가 포함된 PSD 파일에 대한 폰트 캐시를 업데이트합니다. 이 메서드는 폰트 폴더 fontsFolder에서 폰트를 사용하거나<br/>            FontSettings.SetFontsFolder(fontsFolder) 메서드 또는 FontSettings.Reset()으로 폰트를 재설정한 경우 PSD 파일을 처리할 때 해당 폰트가 고려되도록 보장합니다. PSD 이미지에 대해 <br/>            FontSettings.SetFontsFolder(fontsFolder) 또는 FontSettings.Reset()이 호출될 때마다 이 메서드를 사용하십시오. 이 메서드를 호출하지 않으면 폰트가 업데이트된다는 보장이 없습니다. |


### Method: get_adobe_font_name(font_family_name)  [static] {#get_adobe_font_name_font_family_name_1}


```
 get_adobe_font_name(font_family_name) 
```

글꼴 패밀리 이름으로 Adobe 글꼴 이름을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| font_family_name | 문자열 | 폰트 패밀리 이름입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| 문자열 | 폰트 패밀리 이름에 해당하는 Adobe 폰트 이름입니다. |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__2}


```
 get_default_fonts_folders() 
```

기본 글꼴 폴더를 가져옵니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| 문자열 | 시스템 폴더를 반환합니다. |


### Method: get_font_replacements(font_name)  [static] {#get_font_replacements_font_name_3}


```
 get_font_replacements(font_name) 
```

글꼴 이름으로 글꼴 교체 배열을 가져옵니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| font_name | 문자열 | 폰트 이름입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| 문자열 | 제공된 폰트에 대한 교체 이름 배열입니다. |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__4}


```
 get_fonts_folders() 
```

Aspose.Words가 TrueType 글꼴을 찾는 폴더 목록을 포함하는 배열의 복사본을 가져옵니다.

**Returns**

| 유형 | 설명 |
| :- | :- |
| 문자열 | 현재 폰트 위치의 복사본입니다. |


### Method: get_replacement_font(font_name)  [static] {#get_replacement_font_font_name_5}


```
 get_replacement_font(font_name) 
```

가장 적합한 대체 글꼴을 가져옵니다.<br/>            모든 교체가 허용되지 않으면 첫 번째 허용되고 사용 가능한 글꼴이 반환됩니다.<br/>            사용 가능한 글꼴이 없으면 인수에서 전달된 글꼴이 반환됩니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| font_name | 문자열 | 폰트 이름입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| 문자열 | 교체된 폰트의 이름입니다. |


### Method: is_font_allowed(font_name)  [static] {#is_font_allowed_font_name_6}


```
 is_font_allowed(font_name) 
```

지정된 글꼴 이름이 허용되는지 여부를 결정합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| font_name | 문자열 | 폰트 이름입니다. |

**Returns**

| 유형 | 설명 |
| :- | :- |
| bool | <c>true</c> if 지정된 폰트 이름이 허용되는 경우; 그렇지 않으면 <c>false</c>. |


### Method: set_allowed_fonts(font_list)  [static] {#set_allowed_fonts_font_list_7}


```
 set_allowed_fonts(font_list) 
```

폰트를 폰트 목록으로 제한합니다. 제한하기 전에 실제 폰트 이름을 확인하십시오<br/>            허용된 폰트 목록을 Null로 설정하여 제한을 제거합니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| font_list | 문자열 | 폰트 목록입니다. |

### Method: set_font_replacements(font_to_replace, font_names)  [static] {#set_font_replacements_font_to_replace_font_names_8}


```
 set_font_replacements(font_to_replace, font_names) 
```

폰트 교체 목록을 설정합니다. 폰트가 허용되지 않으면 교체 폰트를 찾습니다.<br/>            목록의 첫 번째 폰트가 먼저 사용됩니다. 그것도 제한된다면 목록에서 다음 폰트가 선택됩니다.<br/>            폰트에 교체 폰트가 없거나 모든 교체 폰트가 허용되지 않으면 허용된 폰트 목록에서 첫 번째 허용 폰트가 사용됩니다.<br/>            허용되고 사용 가능한 폰트가 없을 경우 라이브러리는 시스템 기본 폰트를 사용하려 시도합니다(비허용이라도).

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| font_to_replace | 문자열 | 교체할 폰트입니다. |
| font_names | 문자열 | 유사도 순서대로 정렬된 교체 폰트 이름입니다. |

### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_9}


```
 set_fonts_folder(font_folder) 
```

이는 하나의 폰트 디렉터리만 설정하기 위한 [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) 바로 가기입니다.<br/>            폰트 폴더에 대한 검사는 수행되지 않습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| font_folder | 문자열 | 폰트 폴더입니다. |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_10}


```
 set_fonts_folders(fonts_folders, recursive) 
```

TrueType 폰트가 로드되는 폴더를 설정하고 로드된 모든 폰트를 삭제합니다.<br/>            폰트 폴더에 대한 검사는 수행되지 않습니다.

**Parameters:**

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| fonts_folders | 문자열 | 폰트 폴더. |
| 재귀적 | bool | 설정이 <c>true</c> [recursive]인 경우. |

