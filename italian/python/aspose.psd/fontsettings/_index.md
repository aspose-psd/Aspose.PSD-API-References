---
title: "Classe FontSettings"
type: docs
weight: 1370
url: /it/python-net/aspose.psd/fontsettings/
---

**Summary:** General PSD vector formats renderer font settings.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.FontSettings

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| default_font_name [static] | string | r/w | Ottiene o imposta il nome predefinito del carattere. |
| get_system_alternative_font [static] | bool | r/w | Ottiene o imposta un valore che indica se [get alternative font]. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| clear_font_replacements() | Cancella tutte le sostituzioni dei font |
| [get_adobe_font_name(font_family_name)](#get_adobe_font_name_font_family_name_1) | Ottiene il nome del font Adobe in base al nome della famiglia del font. |
| [get_default_fonts_folders()](#get_default_fonts_folders__2) | Ottiene le cartelle predefinite dei font. |
| [get_font_replacements(font_name)](#get_font_replacements_font_name_3) | Ottiene l'array delle sostituzioni dei font per il nome del font |
| [get_fonts_folders()](#get_fonts_folders__4) | Ottiene una copia dell'array che contiene l'elenco delle cartelle in cui Aspose.Words cerca i font TrueType. |
| [get_replacement_font(font_name)](#get_replacement_font_font_name_5) | Ottiene il font di sostituzione più adatto.<br/>            Se tutte le sostituzioni non sono consentite, verrà restituito il primo font consentito e disponibile.<br/>            Se non ci sono font disponibili, verrà restituito il font fornito come argomento |
| [is_font_allowed(font_name)](#is_font_allowed_font_name_6) | Determina se [is font allowed] [il nome del font specificato]. |
| remove_font_cache_file() | Rimuove il file della cache dei font. |
| reset() | Ripristina la cartella dei font e il nome del font predefinito al valore predefinito del sistema. |
| [set_allowed_fonts(font_list)](#set_allowed_fonts_font_list_7) | Limita l'uso dei font tramite un elenco di font. Si prega di verificare i nomi reali dei font prima della restrizione<br/>            Imposta l'elenco dei font consentiti a Null per rimuovere le restrizioni. |
| [set_font_replacements(font_to_replace, font_names)](#set_font_replacements_font_to_replace_font_names_8) | Imposta l'elenco di sostituzione dei font. Se il font non è consentito verrà trovata una sostituzione.<br/>            Il primo font nell'elenco sarà usato per primo. Se anche questo è limitato, verrà selezionato il font successivo nell'elenco.<br/>            Se il font non ha sostituzioni o tutte le sostituzioni non sono consentite, verrà usato il primo font consentito dall'elenco dei font consentiti.<br/>            Se non ci sono font consentiti e disponibili, la libreria proverà a utilizzare il font predefinito di sistema anche se non è consentito. |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_9) | Questo è un collegamento rapido a [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) per impostare una sola directory dei font.<br/>            Non vengono eseguiti controlli sulla cartella dei font. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_10) | Imposta le cartelle da cui vengono caricati i font TrueType e cancella tutti i font caricati.<br/>            Non vengono eseguiti controlli sulle cartelle dei font. |
| update_fonts() | Aggiorna la cache dei font per i file PSD che contengono livelli di testo. Questo metodo garantisce che i font dalla cartella fontsFolder utilizzando<br/>            il metodo FontSettings.SetFontsFolder(fontsFolder) o dopo il reset dei font con FontSettings.Reset() vengano considerati durante l'elaborazione dei file PSD. Si prega di utilizzare questo metodo ogni volta che <br/>            FontSettings.SetFontsFolder(fontsFolder) o FontSettings.Reset() vengono chiamati per immagini PSD. Senza chiamare questo metodo non vi è alcuna garanzia che i font vengano aggiornati. |


### Method: get_adobe_font_name(font_family_name)  [static] {#get_adobe_font_name_font_family_name_1}


```
 get_adobe_font_name(font_family_name) 
```

Ottiene il nome del font Adobe in base al nome della famiglia del font.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_family_name | string | Il nome della famiglia di font. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Il nome del font Adobe per nome della famiglia di font. |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__2}


```
 get_default_fonts_folders() 
```

Ottiene le cartelle predefinite dei font.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Restituisce la cartella di sistema |


### Method: get_font_replacements(font_name)  [static] {#get_font_replacements_font_name_3}


```
 get_font_replacements(font_name) 
```

Ottiene l'array delle sostituzioni dei font per il nome del font

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_name | string | Nome del font. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Array di nomi di sostituzioni per i font forniti |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__4}


```
 get_fonts_folders() 
```

Ottiene una copia dell'array che contiene l'elenco delle cartelle in cui Aspose.Words cerca i font TrueType.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Una copia delle posizioni attuali dei font. |


### Method: get_replacement_font(font_name)  [static] {#get_replacement_font_font_name_5}


```
 get_replacement_font(font_name) 
```

Ottiene il font di sostituzione più adatto.<br/>            Se tutte le sostituzioni non sono consentite, verrà restituito il primo font consentito e disponibile.<br/>            Se non ci sono font disponibili, verrà restituito il font fornito come argomento

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_name | string | Nome del font. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Il nome del font sostituito |


### Method: is_font_allowed(font_name)  [static] {#is_font_allowed_font_name_6}


```
 is_font_allowed(font_name) 
```

Determina se [is font allowed] [il nome del font specificato].

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_name | string | Nome del font. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>true</c> se [is font allowed] [il nome del font specificato]; altrimenti, <c>false</c>. |


### Method: set_allowed_fonts(font_list)  [static] {#set_allowed_fonts_font_list_7}


```
 set_allowed_fonts(font_list) 
```

Limita l'uso dei font tramite un elenco di font. Si prega di verificare i nomi reali dei font prima della restrizione<br/>            Imposta l'elenco dei font consentiti a Null per rimuovere le restrizioni.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_list | string | L'elenco dei font. |

### Method: set_font_replacements(font_to_replace, font_names)  [static] {#set_font_replacements_font_to_replace_font_names_8}


```
 set_font_replacements(font_to_replace, font_names) 
```

Imposta l'elenco di sostituzione dei font. Se il font non è consentito verrà trovata una sostituzione.<br/>            Il primo font nell'elenco sarà usato per primo. Se anche questo è limitato, verrà selezionato il font successivo nell'elenco.<br/>            Se il font non ha sostituzioni o tutte le sostituzioni non sono consentite, verrà usato il primo font consentito dall'elenco dei font consentiti.<br/>            Se non ci sono font consentiti e disponibili, la libreria proverà a utilizzare il font predefinito di sistema anche se non è consentito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_to_replace | string | Il font da sostituire. |
| font_names | string | I nomi dei font di sostituzione in ordine di somiglianza. |

### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_9}


```
 set_fonts_folder(font_folder) 
```

Questo è un collegamento rapido a [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) per impostare una sola directory dei font.<br/>            Non vengono eseguiti controlli sulla cartella dei font.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| font_folder | string | La cartella dei font. |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_10}


```
 set_fonts_folders(fonts_folders, recursive) 
```

Imposta le cartelle da cui vengono caricati i font TrueType e cancella tutti i font caricati.<br/>            Non vengono eseguiti controlli sulle cartelle dei font.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| fonts_folders | string | Le cartelle dei font. |
| ricorsivo | bool | se impostato su <c>true</c> [ricorsivo]. |

