---
title: "FontSettings"
second_title: "Java için Aspose.PSD API Referansı"
description: "Genel görüntüleme vektör formatları renderleyicisinin yazı tipi ayarları."
type: docs
weight: 47
url: /tr/java/com.aspose.psd/fontsettings/
---

**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

Genel görüntüleme vektör formatları renderleyicisinin yazı tipi ayarları.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeFontName(String fontFamilyName)](#getAdobeFontName-java.lang.String-) | Yazı tipi ailesi adına göre Adobe yazı tipi adını alır. |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | Varsayılan yazı tipi adını alır. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | Varsayılan yazı tipi klasörlerini alır. |
| [getFontReplacements(String fontName)](#getFontReplacements-java.lang.String-) | Yazı tipi adına göre yazı tipi değiştirme dizisini alır. |
| [getFontsFolders()](#getFontsFolders--) | Aspose.Imaging'in TrueType yazı tiplerini aradığı klasörlerin listesini içeren dizinin bir kopyasını alır. |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | [get alternative font] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getReplacementFont(String fontName)](#getReplacementFont-java.lang.String-) | En uygun yedek yazı tipini alır. |
| [hashCode()](#hashCode--) |  |
| [isFontAllowed(String fontName)](#isFontAllowed-java.lang.String-) | [is font allowed] [the specified font name] olup olmadığını belirler. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFontCacheFile()](#removeFontCacheFile--) | Yazı tipi önbellek dosyasını kaldırır. |
| [reset()](#reset--) | Yazı tipleri klasörünü ve varsayılan yazı tipi adını sistem varsayılanına sıfırlar. |
| [setAllowedFonts(String[] fontList)](#setAllowedFonts-java.lang.String---) | Yazı tipini, yazı tipleri listesiyle kullanımını kısıtlar. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | Varsayılan yazı tipi adını ayarlar. |
| [setFontReplacements(String fontToReplace, String[] fontNames)](#setFontReplacements-java.lang.String-java.lang.String---) | Yazı tipi değiştirme listesini ayarlar. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | Klasör için yazı tipi klasör listesini geçersiz kıl. |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | Klasörler için yazı tipi klasör listesini geçersiz kıl. |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | TrueType yazı tiplerinin yüklendiği klasörleri ayarlar ve tüm yüklü yazı tiplerini temizler. |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | [get alternative font] olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [toString()](#toString--) |  |
| [updateFonts()](#updateFonts--) | Metin katmanları içeren PSD dosyaları için yazı tipi önbelleğini günceller. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAdobeFontName(String fontFamilyName) {#getAdobeFontName-java.lang.String-}
```
public static String getAdobeFontName(String fontFamilyName)
```


Yazı tipi ailesi adına göre Adobe yazı tipi adını alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontFamilyName | java.lang.String | Yazı tipi ailesi adı. |

**Returns:**
java.lang.String - Yazı tipi ailesi adına göre adobe yazı tipi adı.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultFontName() {#getDefaultFontName--}
```
public static String getDefaultFontName()
```


Varsayılan yazı tipi adını alır.

**Returns:**
java.lang.String - varsayılan yazı tipinin adı
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


Varsayılan yazı tipi klasörlerini alır.

**Returns:**
java.lang.String[] - Sistem klasörünü döndürür
### getFontReplacements(String fontName) {#getFontReplacements-java.lang.String-}
```
public static String[] getFontReplacements(String fontName)
```


Yazı tipi adına göre yazı tipi değiştirme dizisini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | Yazı tipinin adı. |

**Returns:**
java.lang.String[] - Sağlanan yazı tipleri için yedek adlarının dizisi
### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


Aspose.Imaging'in TrueType yazı tiplerini aradığı klasörlerin listesini içeren dizinin bir kopyasını alır.

Dönen değer, Aspose.Imaging'in kullandığı verilerin bir kopyasıdır. Döndürülen dizideki girişleri değiştirirseniz, belge renderlemesi üzerinde hiçbir etkisi olmaz. Yeni yazı tipi konumlarını belirtmek için setFontsFolders yöntemini kullanın.

**Returns:**
java.lang.String[] - Mevcut yazı tipi konumlarının bir kopyası.
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


[get alternative font] olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer [get alternative font]; aksi takdirde,  false .

**Returns:**
boolean
### getReplacementFont(String fontName) {#getReplacementFont-java.lang.String-}
```
public static String getReplacementFont(String fontName)
```


En uygun yedek yazı tipini alır. Tüm yedekler izinli değilse, ilk izin verilen ve mevcut yazı tipi döndürülür. Eğer mevcut yazı tipi yoksa, argümandan gelen yazı tipi döndürülür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | Yazı tipinin adı. |

**Returns:**
java.lang.String - Değiştirilen yazı tipinin adı
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFontAllowed(String fontName) {#isFontAllowed-java.lang.String-}
```
public static boolean isFontAllowed(String fontName)
```


[is font allowed] [the specified font name] olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | Yazı tipinin adı. |

**Returns:**
boolean -  true  eğer [is font allowed] [the specified font name]; aksi takdirde,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeFontCacheFile() {#removeFontCacheFile--}
```
public static void removeFontCacheFile()
```


Yazı tipi önbellek dosyasını kaldırır.

### reset() {#reset--}
```
public static void reset()
```


Yazı tipleri klasörünü ve varsayılan yazı tipi adını sistem varsayılanına sıfırlar.

### setAllowedFonts(String[] fontList) {#setAllowedFonts-java.lang.String---}
```
public static void setAllowedFonts(String[] fontList)
```


Yazı tipini yazı tipleri listesiyle kısıtlar. Kısıtlama öncesinde gerçek yazı tipi adlarını kontrol edin. Kısıtlamaları kaldırmak için İzin verilen yazı tipi listesini Null olarak ayarlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontList | java.lang.String[] | Yazı tipi listesi. |

### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


Varsayılan yazı tipi adını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontName | java.lang.String | Yazı tipinin varsayılan adı. |

### setFontReplacements(String fontToReplace, String[] fontNames) {#setFontReplacements-java.lang.String-java.lang.String---}
```
public static void setFontReplacements(String fontToReplace, String[] fontNames)
```


Yazı tipi değiştirme listesini ayarlar. Yazı tipi izin verilmezse bir yedek bulunacaktır. Listedeki ilk yazı tipi ilk olarak kullanılacaktır. Eğer o da kısıtlanmışsa, listedeki bir sonraki yazı tipi seçilecektir. Yazı tipinin yedekleri yoksa veya tüm yedekler izin verilmezse, izin verilen yazı tipi listesinden ilk izin verilen yazı tipi kullanılacaktır. Eğer izin verilen ve kullanılabilir bir yazı tipi yoksa, kütüphane sistemin varsayılan yazı tipini kullanmaya çalışacaktır, hatta bu izin verilmemiş olsa bile.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fontToReplace | java.lang.String | Değiştirilecek yazı tipi. |
| fontNames | java.lang.String[] | Benzerlik sırasına göre yedek yazı tipi adları. |

### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


Klasör için yazı tipi klasör listesini geçersiz kıl.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| folder | java.lang.String | TrueType yazı tiplerinin bulunduğu klasör. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


Klasörler için yazı tipi klasör listesini geçersiz kıl.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| folders | java.lang.String[] | Klasör dizisi |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


TrueType yazı tiplerinin yüklendiği klasörleri ayarlar ve tüm yüklü yazı tiplerini temizler. Yazı tipi klasörleri üzerinde hiçbir kontrol yapılmaz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| folders | java.lang.String[] | Yazı tipi klasörleri. |
| recursive | boolean | eğer  true  [recursive] olarak ayarlanırsa. |

### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


[get alternative font] olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer:  true  eğer [get alternative font]; aksi takdirde,  false .

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### updateFonts() {#updateFonts--}
```
public static void updateFonts()
```


Metin katmanları içeren PSD dosyaları için yazı tipi önbelleğini günceller. Bu yöntem, FontSettings.setFontsFolder(fontsFolder) yöntemiyle fontsFolder klasöründen gelen yazı tiplerinin veya FontSettings.reset() ile sıfırlandıktan sonra gelen yazı tiplerinin PSD dosyaları işlenirken dikkate alınacağını garanti eder. PSD görüntüleri için FontSettings.setFontsFolder(fontsFolder) veya FontSettings.reset() çağrıldığında bu yöntemi her seferinde kullanın. Bu yöntem çağrılmadan yazı tiplerinin güncelleneceği garantilenmez.

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

