---
title: "FontSettings クラス"
type: docs
weight: 1370
url: /ja/python-net/aspose.psd/fontsettings/
---

**Summary:** General PSD vector formats renderer font settings.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.FontSettings

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| default_font_name [static] | string | r/w | フォントのデフォルト名を取得または設定します。 |
| get_system_alternative_font [static] | bool | r/w | 代替フォントを取得するかどうかを示す値を取得または設定します。[get alternative font] |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| clear_font_replacements() | すべてのフォント置換をクリアします |
| [get_adobe_font_name(font_family_name)](#get_adobe_font_name_font_family_name_1) | フォントファミリ名からAdobeフォント名を取得します。 |
| [get_default_fonts_folders()](#get_default_fonts_folders__2) | デフォルトのフォントフォルダーを取得します。 |
| [get_font_replacements(font_name)](#get_font_replacements_font_name_3) | フォント名でフォント置換配列を取得します |
| [get_fonts_folders()](#get_fonts_folders__4) | Aspose.Words が TrueType フォントを検索するフォルダーのリストを含む配列のコピーを取得します。 |
| [get_replacement_font(font_name)](#get_replacement_font_font_name_5) | 最も適切な置換フォントを取得します。<br/>            すべての置換が許可されていない場合、最初に許可され利用可能なフォントが返されます。<br/>            利用可能なフォントがない場合、引数からのフォントが返されます |
| [is_font_allowed(font_name)](#is_font_allowed_font_name_6) | 指定されたフォント名が許可されているかどうかを判定します。[is font allowed] |
| remove_font_cache_file() | フォントキャッシュファイルを削除します。 |
| reset() | フォントフォルダーとデフォルトのフォント名をシステム既定にリセットします。 |
| [set_allowed_fonts(font_list)](#set_allowed_fonts_font_list_7) | フォントをフォントリストで制限します。制限する前に実際のフォント名を確認してください<br/>            許可されたフォントリストを Null に設定すると制限を解除できます。 |
| [set_font_replacements(font_to_replace, font_names)](#set_font_replacements_font_to_replace_font_names_8) | フォント置換リストを設定します。フォントが許可されていない場合は置換フォントが検索されます。<br/>            リストの最初のフォントが最初に使用されます。もしそれも制限されている場合は、リストの次のフォントが選択されます。<br/>            フォントに置換がない、またはすべての置換が許可されていない場合は、許可されたフォントリストから最初に許可されたフォントが使用されます。<br/>            許可された利用可能なフォントが存在しない場合、ライブラリはシステム既定のフォントを使用しようとします（たとえ許可されていなくても）。 |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_9) | これは、1つのフォントディレクトリのみを設定するための [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) へのショートカットです。<br/>            フォントフォルダーに対してチェックは行われません。 |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_10) | TrueType フォントが読み込まれるフォルダーを設定し、すべての読み込まれたフォントをクリアします。<br/>            フォントフォルダーに対してチェックは行われません。 |
| update_fonts() | テキストレイヤーを含む PSD ファイルのフォントキャッシュを更新します。このメソッドは、fontsFolder フォルダーからのフォントが、<br/>            FontSettings.SetFontsFolder(fontsFolder) メソッドを使用するか、FontSettings.Reset() でフォントをリセットした後に、PSD ファイルの処理時に考慮されることを保証します。PSD 画像に対して FontSettings.SetFontsFolder(fontsFolder) または FontSettings.Reset() が呼び出されるたびにこのメソッドを使用してください。<br/>            このメソッドを呼び出さない場合、フォントが更新される保証はありません。 |


### Method: get_adobe_font_name(font_family_name)  [static] {#get_adobe_font_name_font_family_name_1}


```
 get_adobe_font_name(font_family_name) 
```

フォントファミリ名からAdobeフォント名を取得します。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| font_family_name | string | フォントファミリー名です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | フォントファミリー名による Adobe フォント名です。 |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__2}


```
 get_default_fonts_folders() 
```

デフォルトのフォントフォルダーを取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | システムフォルダーを返します |


### Method: get_font_replacements(font_name)  [static] {#get_font_replacements_font_name_3}


```
 get_font_replacements(font_name) 
```

フォント名でフォント置換配列を取得します

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| font_name | string | フォントの名前です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | 提供されたフォントの置換名の配列です |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__4}


```
 get_fonts_folders() 
```

Aspose.Words が TrueType フォントを検索するフォルダーのリストを含む配列のコピーを取得します。

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | 現在のフォント位置のコピーです。 |


### Method: get_replacement_font(font_name)  [static] {#get_replacement_font_font_name_5}


```
 get_replacement_font(font_name) 
```

最も適切な置換フォントを取得します。<br/>            すべての置換が許可されていない場合、最初に許可され利用可能なフォントが返されます。<br/>            利用可能なフォントがない場合、引数からのフォントが返されます

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| font_name | string | フォントの名前です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| string | 置換されたフォントの名前です |


### Method: is_font_allowed(font_name)  [static] {#is_font_allowed_font_name_6}


```
 is_font_allowed(font_name) 
```

指定されたフォント名が許可されているかどうかを判定します。[is font allowed]

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| font_name | string | フォントの名前です。 |

**Returns**

| タイプ | 説明 |
| :- | :- |
| bool | [is font allowed] [the specified font name] の場合は <c>true</c>、それ以外の場合は <c>false</c>。 |


### Method: set_allowed_fonts(font_list)  [static] {#set_allowed_fonts_font_list_7}


```
 set_allowed_fonts(font_list) 
```

フォントをフォントリストで制限します。制限する前に実際のフォント名を確認してください<br/>            許可されたフォントリストを Null に設定すると制限を解除できます。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| font_list | string | フォントリストです。 |

### Method: set_font_replacements(font_to_replace, font_names)  [static] {#set_font_replacements_font_to_replace_font_names_8}


```
 set_font_replacements(font_to_replace, font_names) 
```

フォント置換リストを設定します。フォントが許可されていない場合は置換フォントが検索されます。<br/>            リストの最初のフォントが最初に使用されます。もしそれも制限されている場合は、リストの次のフォントが選択されます。<br/>            フォントに置換がない、またはすべての置換が許可されていない場合は、許可されたフォントリストから最初に許可されたフォントが使用されます。<br/>            許可された利用可能なフォントが存在しない場合、ライブラリはシステム既定のフォントを使用しようとします（たとえ許可されていなくても）。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| font_to_replace | string | 置換対象のフォントです。 |
| font_names | string | 類似度順の置換フォント名です。 |

### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_9}


```
 set_fonts_folder(font_folder) 
```

これは、1つのフォントディレクトリのみを設定するための [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) へのショートカットです。<br/>            フォントフォルダーに対してチェックは行われません。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| font_folder | string | フォントフォルダーです。 |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_10}


```
 set_fonts_folders(fonts_folders, recursive) 
```

TrueType フォントが読み込まれるフォルダーを設定し、すべての読み込まれたフォントをクリアします。<br/>            フォントフォルダーに対してチェックは行われません。

**Parameters:**

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| fonts_folders | string | フォント フォルダーです。 |
| 再帰的 | bool | 設定が <c>true</c> の場合、[recursive]。 |

