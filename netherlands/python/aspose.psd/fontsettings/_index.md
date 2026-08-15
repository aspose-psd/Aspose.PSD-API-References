---
title: "FontSettings Klasse"
type: docs
weight: 1370
url: /nl/python-net/aspose.psd/fontsettings/
---

**Summary:** General PSD vector formats renderer font settings.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.FontSettings

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| default_font_name [statisch] | string | r/w | Haalt de standaardnaam van het lettertype op of stelt deze in. |
| get_system_alternative_font [statisch] | bool | r/w | Haalt een waarde op of stelt deze in die aangeeft of [get alternative font]. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| clear_font_replacements() | Verwijdert alle lettertypevervangingen |
| [get_adobe_font_name(font_family_name)](#get_adobe_font_name_font_family_name_1) | Haalt de Adobe-lettertype naam op op basis van de lettertypefamilienaam. |
| [get_default_fonts_folders()](#get_default_fonts_folders__2) | Haalt de standaardlettertype‑mappen op. |
| [get_font_replacements(font_name)](#get_font_replacements_font_name_3) | Haalt de array met lettertypevervangingen op op basis van de lettertype‑naam |
| [get_fonts_folders()](#get_fonts_folders__4) | Haalt een kopie op van de array die de lijst met mappen bevat waar Aspose.Words zoekt naar TrueType-lettertypen. |
| [get_replacement_font(font_name)](#get_replacement_font_font_name_5) | Haalt het meest geschikte vervangende lettertype op.<br/>            Als alle vervangingen niet zijn toegestaan, wordt het eerste toegestane en beschikbare lettertype geretourneerd.<br/>            Als er geen beschikbare lettertypen zijn, wordt het lettertype uit het argument geretourneerd |
| [is_font_allowed(font_name)](#is_font_allowed_font_name_6) | Bepaalt of [is font allowed] [de opgegeven lettertype‑naam]. |
| remove_font_cache_file() | Verwijdert het lettertype‑cachebestand. |
| reset() | Reset de lettertype‑map en de standaardlettertype‑naam naar de systeemstandaard. |
| [set_allowed_fonts(font_list)](#set_allowed_fonts_font_list_7) | Beperkt lettertypegebruik door een lijst met lettertypen. Controleer de werkelijke lettertype‑namen vóór beperking<br/>            Stel de lijst met toegestane lettertypen in op Null om beperkingen te verwijderen |
| [set_font_replacements(font_to_replace, font_names)](#set_font_replacements_font_to_replace_font_names_8) | Stelt de lijst met lettertype‑vervangingen in. Als een lettertype niet is toegestaan, wordt een vervanging gezocht.<br/>            Het eerste lettertype in de lijst wordt als eerste gebruikt. Als dat ook beperkt is, wordt het volgende lettertype uit de lijst geselecteerd.<br/>            Als een lettertype geen vervangingen heeft of alle vervangingen niet zijn toegestaan, wordt het eerste toegestane lettertype uit de lijst met toegestane lettertypen gebruikt.<br/>            Als er geen toegestane en beschikbare lettertypen zijn, probeert de bibliotheek het systeem‑standaardlettertype te gebruiken, zelfs als dat niet is toegestaan. |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_9) | Dit is een snelkoppeling naar [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) voor het instellen van slechts één lettertype‑directory.<br/>            Er worden geen controles uitgevoerd op de lettertype‑map. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_10) | Stelt de mappen in waar TrueType‑lettertypen vandaan worden geladen en wist alle geladen lettertypen.<br/>            Er worden geen controles uitgevoerd op de lettertype‑mappen. |
| update_fonts() | Werkt de lettertype‑cache bij voor PSD‑bestanden die tekstlagen bevatten. Deze methode garandeert dat lettertypen uit de map fontsFolder die worden gebruikt<br/>            via de methode FontSettings.SetFontsFolder(fontsFolder) of na het resetten van lettertypen met FontSettings.Reset() in aanmerking worden genomen bij het verwerken van PSD‑bestanden. Gebruik deze methode elke keer wanneer<br/>            FontSettings.SetFontsFolder(fontsFolder) of FontSettings.Reset() wordt aangeroepen voor PSD‑afbeeldingen. Zonder het aanroepen van deze methode is er geen garantie dat lettertypen worden bijgewerkt. |


### Method: get_adobe_font_name(font_family_name)  [static] {#get_adobe_font_name_font_family_name_1}


```
 get_adobe_font_name(font_family_name) 
```

Haalt de Adobe-lettertype naam op op basis van de lettertypefamilienaam.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| font_family_name | string | De naam van de lettertypefamilie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | De Adobe‑lettertype‑naam op basis van de lettertypefamilienaam. |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__2}


```
 get_default_fonts_folders() 
```

Haalt de standaardlettertype‑mappen op.

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | Retourneert de systeemmap |


### Method: get_font_replacements(font_name)  [static] {#get_font_replacements_font_name_3}


```
 get_font_replacements(font_name) 
```

Haalt de array met lettertypevervangingen op op basis van de lettertype‑naam

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| font_name | string | Naam van het lettertype. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | Array van namen van vervangingen voor opgegeven lettertypen |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__4}


```
 get_fonts_folders() 
```

Haalt een kopie op van de array die de lijst met mappen bevat waar Aspose.Words zoekt naar TrueType-lettertypen.

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | Een kopie van de huidige lettertype‑locaties. |


### Method: get_replacement_font(font_name)  [static] {#get_replacement_font_font_name_5}


```
 get_replacement_font(font_name) 
```

Haalt het meest geschikte vervangende lettertype op.<br/>            Als alle vervangingen niet zijn toegestaan, wordt het eerste toegestane en beschikbare lettertype geretourneerd.<br/>            Als er geen beschikbare lettertypen zijn, wordt het lettertype uit het argument geretourneerd

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| font_name | string | Naam van het lettertype. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | De naam van het vervangen lettertype |


### Method: is_font_allowed(font_name)  [static] {#is_font_allowed_font_name_6}


```
 is_font_allowed(font_name) 
```

Bepaalt of [is font allowed] [de opgegeven lettertype‑naam].

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| font_name | string | Naam van het lettertype. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <c>true</c> als [is font allowed] [de opgegeven lettertype‑naam]; anders, <c>false</c>. |


### Method: set_allowed_fonts(font_list)  [static] {#set_allowed_fonts_font_list_7}


```
 set_allowed_fonts(font_list) 
```

Beperkt lettertypegebruik door een lijst met lettertypen. Controleer de werkelijke lettertype‑namen vóór beperking<br/>            Stel de lijst met toegestane lettertypen in op Null om beperkingen te verwijderen

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| font_list | string | De lettertype‑lijst. |

### Method: set_font_replacements(font_to_replace, font_names)  [static] {#set_font_replacements_font_to_replace_font_names_8}


```
 set_font_replacements(font_to_replace, font_names) 
```

Stelt de lijst met lettertype‑vervangingen in. Als een lettertype niet is toegestaan, wordt een vervanging gezocht.<br/>            Het eerste lettertype in de lijst wordt als eerste gebruikt. Als dat ook beperkt is, wordt het volgende lettertype uit de lijst geselecteerd.<br/>            Als een lettertype geen vervangingen heeft of alle vervangingen niet zijn toegestaan, wordt het eerste toegestane lettertype uit de lijst met toegestane lettertypen gebruikt.<br/>            Als er geen toegestane en beschikbare lettertypen zijn, probeert de bibliotheek het systeem‑standaardlettertype te gebruiken, zelfs als dat niet is toegestaan.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| font_to_replace | string | Het te vervangen lettertype. |
| font_names | string | De vervangende lettertype‑namen in volgorde van gelijkenis. |

### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_9}


```
 set_fonts_folder(font_folder) 
```

Dit is een snelkoppeling naar [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) voor het instellen van slechts één lettertype‑directory.<br/>            Er worden geen controles uitgevoerd op de lettertype‑map.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| font_folder | string | De lettertype‑map. |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_10}


```
 set_fonts_folders(fonts_folders, recursive) 
```

Stelt de mappen in waar TrueType‑lettertypen vandaan worden geladen en wist alle geladen lettertypen.<br/>            Er worden geen controles uitgevoerd op de lettertype‑mappen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| fonts_folders | string | De lettertype-mappen. |
| recursief | bool | indien ingesteld op <c>true</c> [recursief]. |

