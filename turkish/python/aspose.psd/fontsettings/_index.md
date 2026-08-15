---
title: "FontSettings Sınıfı"
type: docs
weight: 1370
url: /tr/python-net/aspose.psd/fontsettings/
---

**Summary:** General PSD vector formats renderer font settings.

**Module:** [aspose.psd](/psd/python-net/aspose.psd/)

**Full Name:** aspose.psd.FontSettings

**Aspose.PSD Version:** 24.12.0

## **Properties**
| **Name** | **Tür** | **Erişim** | **Açıklama** |
| :- | :- | :- | :- |
| default_font_name [static] | string | r/w | Yazı tipinin varsayılan adını alır veya ayarlar. |
| get_system_alternative_font [static] | bool | r/w | Alternatif yazı tipinin alınması gerektiğini gösteren bir değeri alır veya ayarlar [get alternative font]. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| clear_font_replacements() | Tüm yazı tipi değişikliklerini temizler |
| [get_adobe_font_name(font_family_name)](#get_adobe_font_name_font_family_name_1) | Yazı tipi ailesi adına göre Adobe yazı tipi adını alır. |
| [get_default_fonts_folders()](#get_default_fonts_folders__2) | Varsayılan yazı tipleri klasörlerini alır. |
| [get_font_replacements(font_name)](#get_font_replacements_font_name_3) | Yazı tipi adına göre yazı tipi değişiklikleri dizisini alır |
| [get_fonts_folders()](#get_fonts_folders__4) | Aspose.Words'ün TrueType yazı tiplerini aradığı klasörlerin listesini içeren dizinin bir kopyasını alır. |
| [get_replacement_font(font_name)](#get_replacement_font_font_name_5) | En uygun yedek yazı tipini alır.<br/>            Tüm yedekler izin verilmiyorsa, ilk izin verilen ve mevcut yazı tipi döndürülecektir.<br/>            Eğer mevcut yazı tipi yoksa, argümandan gelen yazı tipi döndürülecektir |
| [is_font_allowed(font_name)](#is_font_allowed_font_name_6) | Belirtilen yazı tipi adının izinli olup olmadığını belirler [is font allowed] [the specified font name]. |
| remove_font_cache_file() | Yazı tipi önbellek dosyasını kaldırır. |
| reset() | Yazı tipi klasörünü ve varsayılan yazı tipi adını sistem varsayılanına sıfırlar. |
| [set_allowed_fonts(font_list)](#set_allowed_fonts_font_list_7) | Yazı tipini yazı tipi listesiyle kısıtlar. Kısıtlama yapmadan önce gerçek yazı tipi adlarını kontrol edin<br/>            Kısıtlamaları kaldırmak için İzin verilen yazı tipi listesini Null olarak ayarlayın |
| [set_font_replacements(font_to_replace, font_names)](#set_font_replacements_font_to_replace_font_names_8) | Yazı tipi değiştirme listesini ayarlar. Yazı tipi izin verilmiyorsa bir yedek bulunacaktır.<br/>            Listede ilk yazı tipi ilk olarak kullanılacaktır. Eğer o da kısıtlanmışsa, listeden bir sonraki yazı tipi seçilecektir.<br/>            Yazı tipinin yedekleri yoksa veya tüm yedekler izin verilmiyorsa, izin verilen yazı tipi listesinden ilk izin verilen yazı tipi kullanılacaktır.<br/>            Eğer izin verilen ve mevcut yazı tipleri yoksa, kütüphane sistem varsayılan yazı tipini kullanmaya çalışacaktır, hatta izin verilmemiş olsa bile. |
| [set_fonts_folder(font_folder)](#set_fonts_folder_font_folder_9) | Bu, yalnızca bir yazı tipi dizini ayarlamak için [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) kısayoludur.<br/>            Yazı tipi klasörü üzerinde hiçbir kontrol yapılmaz. |
| [set_fonts_folders(fonts_folders, recursive)](#set_fonts_folders_fonts_folders_recursive_10) | TrueType yazı tiplerinin yüklendiği klasörleri ayarlar ve tüm yüklü yazı tiplerini temizler.<br/>            Yazı tipi klasörleri üzerinde hiçbir kontrol yapılmaz. |
| update_fonts() | Metin katmanları içeren PSD dosyaları için yazı tipi önbelleğini günceller. Bu yöntem, fontsFolder klasöründen gelen yazı tiplerinin<br/>            FontSettings.SetFontsFolder(fontsFolder) yöntemiyle veya FontSettings.Reset() ile yazı tipleri sıfırlandıktan sonra PSD dosyaları işlenirken dikkate alınacağını garanti eder. Lütfen bu yöntemi her seferinde kullanın <br/>            FontSettings.SetFontsFolder(fontsFolder) veya FontSettings.Reset() PSD görüntüleri için çağrıldığında. Bu yöntem çağrılmadan yazı tiplerinin güncelleneceği garantilenmez. |


### Method: get_adobe_font_name(font_family_name)  [static] {#get_adobe_font_name_font_family_name_1}


```
 get_adobe_font_name(font_family_name) 
```

Yazı tipi ailesi adına göre Adobe yazı tipi adını alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| font_family_name | string | Yazı tipi ailesi adı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Yazı tipi ailesi adına göre Adobe yazı tipi adı. |


### Method: get_default_fonts_folders()  [static] {#get_default_fonts_folders__2}


```
 get_default_fonts_folders() 
```

Varsayılan yazı tipleri klasörlerini alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Sistem klasörünü döndürür |


### Method: get_font_replacements(font_name)  [static] {#get_font_replacements_font_name_3}


```
 get_font_replacements(font_name) 
```

Yazı tipi adına göre yazı tipi değişiklikleri dizisini alır

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| font_name | string | Yazı tipinin adı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Sağlanan yazı tipleri için yedek adlarının dizisi |


### Method: get_fonts_folders()  [static] {#get_fonts_folders__4}


```
 get_fonts_folders() 
```

Aspose.Words'ün TrueType yazı tiplerini aradığı klasörlerin listesini içeren dizinin bir kopyasını alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Mevcut yazı tipi konumlarının bir kopyası. |


### Method: get_replacement_font(font_name)  [static] {#get_replacement_font_font_name_5}


```
 get_replacement_font(font_name) 
```

En uygun yedek yazı tipini alır.<br/>            Tüm yedekler izin verilmiyorsa, ilk izin verilen ve mevcut yazı tipi döndürülecektir.<br/>            Eğer mevcut yazı tipi yoksa, argümandan gelen yazı tipi döndürülecektir

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| font_name | string | Yazı tipinin adı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Değiştirilen yazı tipinin adı |


### Method: is_font_allowed(font_name)  [static] {#is_font_allowed_font_name_6}


```
 is_font_allowed(font_name) 
```

Belirtilen yazı tipi adının izinli olup olmadığını belirler [is font allowed] [the specified font name].

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| font_name | string | Yazı tipinin adı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <c>true</c> eğer [is font allowed] [the specified font name]; aksi takdirde <c>false</c>. |


### Method: set_allowed_fonts(font_list)  [static] {#set_allowed_fonts_font_list_7}


```
 set_allowed_fonts(font_list) 
```

Yazı tipini yazı tipi listesiyle kısıtlar. Kısıtlama yapmadan önce gerçek yazı tipi adlarını kontrol edin<br/>            Kısıtlamaları kaldırmak için İzin verilen yazı tipi listesini Null olarak ayarlayın

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| font_list | string | Yazı tipi listesi. |

### Method: set_font_replacements(font_to_replace, font_names)  [static] {#set_font_replacements_font_to_replace_font_names_8}


```
 set_font_replacements(font_to_replace, font_names) 
```

Yazı tipi değiştirme listesini ayarlar. Yazı tipi izin verilmiyorsa bir yedek bulunacaktır.<br/>            Listede ilk yazı tipi ilk olarak kullanılacaktır. Eğer o da kısıtlanmışsa, listeden bir sonraki yazı tipi seçilecektir.<br/>            Yazı tipinin yedekleri yoksa veya tüm yedekler izin verilmiyorsa, izin verilen yazı tipi listesinden ilk izin verilen yazı tipi kullanılacaktır.<br/>            Eğer izin verilen ve mevcut yazı tipleri yoksa, kütüphane sistem varsayılan yazı tipini kullanmaya çalışacaktır, hatta izin verilmemiş olsa bile.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| font_to_replace | string | Değiştirilecek yazı tipi. |
| font_names | string | Benzerliğe göre sıralanmış yedek yazı tipi adları. |

### Method: set_fonts_folder(font_folder)  [static] {#set_fonts_folder_font_folder_9}


```
 set_fonts_folder(font_folder) 
```

Bu, yalnızca bir yazı tipi dizini ayarlamak için [FontSettings.set_fonts_folders(fonts_folders, recursive)](/psd/python-net/aspose.psd/fontsettings/) kısayoludur.<br/>            Yazı tipi klasörü üzerinde hiçbir kontrol yapılmaz.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| font_folder | string | Yazı tipi klasörü. |

### Method: set_fonts_folders(fonts_folders, recursive)  [static] {#set_fonts_folders_fonts_folders_recursive_10}


```
 set_fonts_folders(fonts_folders, recursive) 
```

TrueType yazı tiplerinin yüklendiği klasörleri ayarlar ve tüm yüklü yazı tiplerini temizler.<br/>            Yazı tipi klasörleri üzerinde hiçbir kontrol yapılmaz.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| fonts_folders | string | Yazı tipleri klasörleri. |
| özyinelemeli | bool | eğer <c>true</c> olarak ayarlanırsa [recursive]. |

