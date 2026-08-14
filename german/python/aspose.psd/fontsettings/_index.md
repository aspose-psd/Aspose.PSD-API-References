---
title: "FontSettings Klasse"
type: docs
weight: 1370
url: /de/python-net/aspose.psd/fontsettings/
---

**Summary:** General PSD vector formats renderer font settings.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.FontSettings

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| default_font_name [statisch] | string | r/w | Liest oder setzt den Standardnamen der Schriftart. |
| get_system_alternative_font [statisch] | bool | r/w | Liest oder setzt einen Wert, der angibt, ob [get alternative font]. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| clear_font_replacements() | Löscht alle Schriftart-Ersetzungen |
| [get_adobe_font_name(font_family_name)](#get_adobe_font_name_font_family_name_1) | Liest den Adobe-Schriftartnamen anhand des Schriftfamiliennamens. |
| [get_default_fonts_folders()](#get_default_fonts_folders__2) | Liest die Standardordner für Schriftarten. |
| [get_font_replacements(font_name)](#get_font_replacements_font_name_3) | Liest das Array der Schriftart-Ersetzungen anhand des Schriftartnamens |
| [get_fonts_folders()](#get_fonts_folders__4) | Liest eine Kopie des Arrays, das die Liste der Ordner enthält, in denen Aspose.Words nach TrueType-Schriftarten sucht. |
| [get_replacement_font(font_name)](#get_replacement_font_font_name_5) | Liest die am besten geeignete Ersatzschriftart.<br/>            Wenn alle Ersetzungen nicht erlaubt sind, wird die erste erlaubte und verfügbare Schriftart zurückgegeben.<br/>            Wenn keine verfügbaren Schriftarten vorhanden sind, wird die Schriftart aus dem Argument zurückgegeben. |
| [is_font_allowed(font_name)](#is_font_allowed_font_name_6) | Bestimmt, ob [is font allowed] [der angegebene Schriftartname]. |
| remove_font_cache_file() | Entfernt die Schriftart-Cache-Datei. |
| reset() | Setzt den Schriftartenordner und den Standard-Schriftartnamen auf die Systemvorgabe zurück. |
| [set_allowed_fonts(font_list)](#set_allowed_fonts_font_list_7) | Beschränkt die Schriftartverwendung anhand einer Liste von Schriftarten. Bitte prüfen Sie die tatsächlichen Schriftartnamen vor der Einschränkung<br/>            Setzen Sie die zulässige Schriftartenliste auf Null, um Einschränkungen zu entfernen. |
| [set_font_replacements(font_to_replace, font_names)](#set_font_replacements_font_to_replace_font_names_8) | Legt die Ersatzschriftartenliste fest. Wenn eine Schriftart nicht zulässig ist, wird ein Ersatz gefunden.<br/>            Die erste Schriftart in der Liste wird zuerst verwendet. Wenn sie ebenfalls eingeschränkt ist, wird die nächste Schriftart aus der Liste ausgewählt.<br/>            Wenn für die Schriftart keine Ersatzschriften vorhanden sind oder alle Ersatzschriften nicht zulässig sind, wird die zuerst zulässige Schriftart aus der zulässigen Schriftartenliste verwendet.<br/>            Wenn keine zulässigen und verfügbaren Schriftarten vorhanden sind, versucht die Bibliothek, die systemweite Standardschriftart zu verwenden, selbst wenn sie nicht zulässig ist. |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_9) | Dies ist eine Abkürzung zu [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) zum Festlegen eines einzigen Schriftartenverzeichnisses.<br/>            Es werden keine Prüfungen des Schriftartenordners durchgeführt. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_10) | Legt die Ordner fest, aus denen TrueType-Schriftarten geladen werden, und löscht alle geladenen Schriftarten.<br/>            Es werden keine Prüfungen der Schriftartenordner durchgeführt. |
| update_fonts() | Aktualisiert den Schriftarten-Cache für PSD-Dateien, die Textebenen enthalten. Diese Methode stellt sicher, dass Schriftarten aus dem Ordner fontsFolder, die über<br/>            die Methode FontSettings.SetFontsFolder(fontsFolder) oder nach dem Zurücksetzen der Schriftarten mittels FontSettings.Reset() festgelegt wurden, bei der Verarbeitung von PSD-Dateien berücksichtigt werden. Bitte verwenden Sie diese Methode jedes Mal, wenn <br/>            FontSettings.SetFontsFolder(fontsFolder) oder FontSettings.Reset() für PSD-Bilder aufgerufen wird. Ohne Aufruf dieser Methode gibt es keine Garantie, dass Schriftarten aktualisiert werden. |


### Method: get_adobe_font_name(font_family_name)  [static] {#get_adobe_font_name_font_family_name_1}


```
 get_adobe_font_name(font_family_name) 
```

Liest den Adobe-Schriftartnamen anhand des Schriftfamiliennamens.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_family_name | string | Der Name der Schriftfamilie. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Der Adobe-Schriftname anhand des Schriftfamiliennamens. |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__2}


```
 get_default_fonts_folders() 
```

Liest die Standardordner für Schriftarten.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Gibt den Systemordner zurück |


### Method: get_font_replacements(font_name)  [static] {#get_font_replacements_font_name_3}


```
 get_font_replacements(font_name) 
```

Liest das Array der Schriftart-Ersetzungen anhand des Schriftartnamens

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_name | string | Name der Schriftart. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Array von Namen der Ersatzschriften für die angegebenen Schriftarten |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__4}


```
 get_fonts_folders() 
```

Liest eine Kopie des Arrays, das die Liste der Ordner enthält, in denen Aspose.Words nach TrueType-Schriftarten sucht.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Eine Kopie der aktuellen Schriftartstandorte. |


### Method: get_replacement_font(font_name)  [static] {#get_replacement_font_font_name_5}


```
 get_replacement_font(font_name) 
```

Liest die am besten geeignete Ersatzschriftart.<br/>            Wenn alle Ersetzungen nicht erlaubt sind, wird die erste erlaubte und verfügbare Schriftart zurückgegeben.<br/>            Wenn keine verfügbaren Schriftarten vorhanden sind, wird die Schriftart aus dem Argument zurückgegeben.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_name | string | Name der Schriftart. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Der Name der ersetzten Schriftart |


### Method: is_font_allowed(font_name)  [static] {#is_font_allowed_font_name_6}


```
 is_font_allowed(font_name) 
```

Bestimmt, ob [is font allowed] [der angegebene Schriftartname].

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_name | string | Name der Schriftart. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <c>true</c> wenn [is font allowed] [der angegebene Schriftartname]; andernfalls <c>false</c>. |


### Method: set_allowed_fonts(font_list)  [static] {#set_allowed_fonts_font_list_7}


```
 set_allowed_fonts(font_list) 
```

Beschränkt die Schriftartverwendung anhand einer Liste von Schriftarten. Bitte prüfen Sie die tatsächlichen Schriftartnamen vor der Einschränkung<br/>            Setzen Sie die zulässige Schriftartenliste auf Null, um Einschränkungen zu entfernen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_list | string | Die Schriftartenliste. |

### Method: set_font_replacements(font_to_replace, font_names)  [static] {#set_font_replacements_font_to_replace_font_names_8}


```
 set_font_replacements(font_to_replace, font_names) 
```

Legt die Ersatzschriftartenliste fest. Wenn eine Schriftart nicht zulässig ist, wird ein Ersatz gefunden.<br/>            Die erste Schriftart in der Liste wird zuerst verwendet. Wenn sie ebenfalls eingeschränkt ist, wird die nächste Schriftart aus der Liste ausgewählt.<br/>            Wenn für die Schriftart keine Ersatzschriften vorhanden sind oder alle Ersatzschriften nicht zulässig sind, wird die zuerst zulässige Schriftart aus der zulässigen Schriftartenliste verwendet.<br/>            Wenn keine zulässigen und verfügbaren Schriftarten vorhanden sind, versucht die Bibliothek, die systemweite Standardschriftart zu verwenden, selbst wenn sie nicht zulässig ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_to_replace | string | Die zu ersetzende Schriftart. |
| font_names | string | Die Ersatzschriftartnamen in Reihenfolge der Ähnlichkeit. |

### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_9}


```
 set_fonts_folder(font_folder) 
```

Dies ist eine Abkürzung zu [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) zum Festlegen eines einzigen Schriftartenverzeichnisses.<br/>            Es werden keine Prüfungen des Schriftartenordners durchgeführt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_folder | string | Der Schriftartenordner. |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_10}


```
 set_fonts_folders(fonts_folders, recursive) 
```

Legt die Ordner fest, aus denen TrueType-Schriftarten geladen werden, und löscht alle geladenen Schriftarten.<br/>            Es werden keine Prüfungen der Schriftartenordner durchgeführt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| fonts_folders | string | Die Schriftartenordner. |
| rekursiv | bool | wenn gesetzt auf <c>true</c> [recursive]. |

