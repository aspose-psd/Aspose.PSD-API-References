---
title: "FontSettings klass"
type: docs
weight: 1370
url: /sv/python-net/aspose.psd/fontsettings/
---

**Summary:** General PSD vector formats renderer font settings.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.FontSettings

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| default_font_name [static] | string | r/w | Hämtar eller anger standardnamnet på teckensnittet. |
| get_system_alternative_font [static] | bool | r/w | Hämtar eller anger ett värde som indikerar om [get alternative font]. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| clear_font_replacements() | Rensar alla teckensnittsersättningar |
| [get_adobe_font_name(font_family_name)](#get_adobe_font_name_font_family_name_1) | Hämtar Adobe-teckensnittsnamnet via teckensnittsfamiljens namn. |
| [get_default_fonts_folders()](#get_default_fonts_folders__2) | Hämtar standardmapparna för teckensnitt. |
| [get_font_replacements(font_name)](#get_font_replacements_font_name_3) | Hämtar teckensnittsersättningsarrayen via teckensnittets namn |
| [get_fonts_folders()](#get_fonts_folders__4) | Hämtar en kopia av arrayen som innehåller listan över mappar där Aspose.Words söker efter TrueType-teckensnitt. |
| [get_replacement_font(font_name)](#get_replacement_font_font_name_5) | Hämtar det mest lämpliga ersättningsteckensnittet.<br/>            Om alla ersättningar inte är tillåtna returneras det första tillåtna och tillgängliga teckensnittet.<br/>            Om det inte finns några tillgängliga teckensnitt returneras teckensnittet från argumentet. |
| [is_font_allowed(font_name)](#is_font_allowed_font_name_6) | Bestämmer om [is font allowed] [det angivna teckensnittets namn]. |
| remove_font_cache_file() | Tar bort teckensnittscache-filen. |
| reset() | Återställer teckensnittsmappen och standardteckensnittets namn till systemstandard. |
| [set_allowed_fonts(font_list)](#set_allowed_fonts_font_list_7) | Begränsar teckensnitt med en lista av teckensnitt. Kontrollera de faktiska teckensnittsnamnen innan begränsning<br/>            Sätt den tillåtna teckensnittlistan till Null för att ta bort begränsningarna. |
| [set_font_replacements(font_to_replace, font_names)](#set_font_replacements_font_to_replace_font_names_8) | Sätter listan för teckensnittsersättningar. Om teckensnittet inte är tillåtet kommer en ersättning att hittas.<br/>            Det första teckensnittet i listan används först. Om det också är begränsat väljs nästa teckensnitt i listan.<br/>            Om teckensnittet saknar ersättningar eller alla ersättningar inte är tillåtna används det första tillåtna teckensnittet från den tillåtna teckensnittlistan.<br/>            Om det inte finns några tillåtna och tillgängliga teckensnitt kommer biblioteket att försöka använda systemstandardteckensnittet även om det inte är tillåtet. |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_9) | Detta är en genväg till [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) för att ange endast en teckensnittskatalog.<br/>            Inga kontroller utförs på teckensnittskatalogen. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_10) | Anger katalogerna där TrueType-teckensnitt laddas från och rensar alla laddade teckensnitt.<br/>            Inga kontroller utförs på teckensnittskatalogerna. |
| update_fonts() | Uppdaterar teckensnittscache för PSD-filer som innehåller textlager. Denna metod garanterar att teckensnitt från mappen fontsFolder som används<br/>            med metoden FontSettings.SetFontsFolder(fontsFolder) eller efter återställning av teckensnitt med FontSettings.Reset() tas i beaktande vid bearbetning av PSD-filer. Använd denna metod varje gång när <br/>            FontSettings.SetFontsFolder(fontsFolder) eller FontSettings.Reset() anropas för PSD-bilder. Utan att anropa denna metod finns ingen garanti för att teckensnitt uppdateras. |


### Method: get_adobe_font_name(font_family_name)  [static] {#get_adobe_font_name_font_family_name_1}


```
 get_adobe_font_name(font_family_name) 
```

Hämtar Adobe-teckensnittsnamnet via teckensnittsfamiljens namn.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_family_name | string | Teckensnittsfamiljens namn. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Adobe-teckensnittets namn enligt teckensnittsfamiljens namn. |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__2}


```
 get_default_fonts_folders() 
```

Hämtar standardmapparna för teckensnitt.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Returnerar systemkatalogen |


### Method: get_font_replacements(font_name)  [static] {#get_font_replacements_font_name_3}


```
 get_font_replacements(font_name) 
```

Hämtar teckensnittsersättningsarrayen via teckensnittets namn

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_name | string | Teckensnittets namn. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Array av namn på ersättningar för angivna teckensnitt |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__4}


```
 get_fonts_folders() 
```

Hämtar en kopia av arrayen som innehåller listan över mappar där Aspose.Words söker efter TrueType-teckensnitt.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | En kopia av de aktuella teckensnittslokalerna. |


### Method: get_replacement_font(font_name)  [static] {#get_replacement_font_font_name_5}


```
 get_replacement_font(font_name) 
```

Hämtar det mest lämpliga ersättningsteckensnittet.<br/>            Om alla ersättningar inte är tillåtna returneras det första tillåtna och tillgängliga teckensnittet.<br/>            Om det inte finns några tillgängliga teckensnitt returneras teckensnittet från argumentet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_name | string | Teckensnittets namn. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Namnet på det ersatta teckensnittet |


### Method: is_font_allowed(font_name)  [static] {#is_font_allowed_font_name_6}


```
 is_font_allowed(font_name) 
```

Bestämmer om [is font allowed] [det angivna teckensnittets namn].

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_name | string | Teckensnittets namn. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om [is font allowed] [det angivna teckensnittets namn]; annars, <c>false</c>. |


### Method: set_allowed_fonts(font_list)  [static] {#set_allowed_fonts_font_list_7}


```
 set_allowed_fonts(font_list) 
```

Begränsar teckensnitt med en lista av teckensnitt. Kontrollera de faktiska teckensnittsnamnen innan begränsning<br/>            Sätt den tillåtna teckensnittlistan till Null för att ta bort begränsningarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_list | string | Teckensnittlistan. |

### Method: set_font_replacements(font_to_replace, font_names)  [static] {#set_font_replacements_font_to_replace_font_names_8}


```
 set_font_replacements(font_to_replace, font_names) 
```

Sätter listan för teckensnittsersättningar. Om teckensnittet inte är tillåtet kommer en ersättning att hittas.<br/>            Det första teckensnittet i listan används först. Om det också är begränsat väljs nästa teckensnitt i listan.<br/>            Om teckensnittet saknar ersättningar eller alla ersättningar inte är tillåtna används det första tillåtna teckensnittet från den tillåtna teckensnittlistan.<br/>            Om det inte finns några tillåtna och tillgängliga teckensnitt kommer biblioteket att försöka använda systemstandardteckensnittet även om det inte är tillåtet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_to_replace | string | Teckensnittet att ersätta. |
| font_names | string | Ersättnings-typsnittsnamnen i ordning efter likhet. |

### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_9}


```
 set_fonts_folder(font_folder) 
```

Detta är en genväg till [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) för att ange endast en teckensnittskatalog.<br/>            Inga kontroller utförs på teckensnittskatalogen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_folder | string | Typsnittsmappen. |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_10}


```
 set_fonts_folders(fonts_folders, recursive) 
```

Anger katalogerna där TrueType-teckensnitt laddas från och rensar alla laddade teckensnitt.<br/>            Inga kontroller utförs på teckensnittskatalogerna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| fonts_folders | string | Typsnittsmapparna. |
| recursive | bool | om den är satt till <c>true</c> [rekursiv]. |

