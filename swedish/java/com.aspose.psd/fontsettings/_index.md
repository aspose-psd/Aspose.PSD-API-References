---
title: "FontSettings"
second_title: "Aspose.PSD för Java API-referens"
description: "Allmänna inställningar för teckensnitt i renderaren för bildvektorfiler."
type: docs
weight: 47
url: /sv/java/com.aspose.psd/fontsettings/
---

**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

Allmänna inställningar för teckensnitt i renderaren för bildvektorfiler.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeFontName(String fontFamilyName)](#getAdobeFontName-java.lang.String-) | Hämtar Adobe-teckensnittets namn efter teckensnittsfamiljens namn. |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | Hämtar standardteckensnittets namn. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | Hämtar standardmapparna för teckensnitt. |
| [getFontReplacements(String fontName)](#getFontReplacements-java.lang.String-) | Hämtar teckensnittsbytesarrayen efter teckensnittets namn |
| [getFontsFolders()](#getFontsFolders--) | Hämtar en kopia av arrayen som innehåller listan över mappar där Aspose.Imaging söker efter TrueType-teckensnitt. |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | Hämtar eller anger ett värde som indikerar om [get alternative font]. |
| [getReplacementFont(String fontName)](#getReplacementFont-java.lang.String-) | Hämtar det mest lämpliga ersättningsteckensnittet. |
| [hashCode()](#hashCode--) |  |
| [isFontAllowed(String fontName)](#isFontAllowed-java.lang.String-) | Bestämmer om [is font allowed] [the specified font name]. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFontCacheFile()](#removeFontCacheFile--) | Tar bort teckensnittscache-filen. |
| [reset()](#reset--) | Återställer teckensnittsmappen och standardteckensnittets namn till systemstandard. |
| [setAllowedFonts(String[] fontList)](#setAllowedFonts-java.lang.String---) | Begränsar teckensnittsanvändning med en lista av teckensnitt. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | Anger standardteckensnittets namn. |
| [setFontReplacements(String fontToReplace, String[] fontNames)](#setFontReplacements-java.lang.String-java.lang.String---) | Anger listan för teckensnittsbyte. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | Åsidosätt teckensnittsmappningslistan för  mapp |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | Åsidosätt teckensnittsmappningslistan för  mappar |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | Anger mapparna där TrueType-teckensnitt laddas från och rensar alla laddade teckensnitt. |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | Hämtar eller anger ett värde som indikerar om [get alternative font]. |
| [toString()](#toString--) |  |
| [updateFonts()](#updateFonts--) | Uppdaterar teckensnittscache för PSD-filer som innehåller textlager. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAdobeFontName(String fontFamilyName) {#getAdobeFontName-java.lang.String-}
```
public static String getAdobeFontName(String fontFamilyName)
```


Hämtar Adobe-teckensnittets namn efter teckensnittsfamiljens namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontFamilyName | java.lang.String | Teckensnittsfamiljens namn. |

**Returns:**
java.lang.String - Adobe-teckensnittets namn efter teckensnittsfamiljens namn.
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


Hämtar standardteckensnittets namn.

**Returns:**
java.lang.String - standardfontens namn
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


Hämtar standardmapparna för teckensnitt.

**Returns:**
java.lang.String[] - Returnerar systemmappen
### getFontReplacements(String fontName) {#getFontReplacements-java.lang.String-}
```
public static String[] getFontReplacements(String fontName)
```


Hämtar teckensnittsbytesarrayen efter teckensnittets namn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | Namnet på teckensnittet. |

**Returns:**
java.lang.String[] - Array av namn på ersättningar för angivna teckensnitt
### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


Hämtar en kopia av arrayen som innehåller listan över mappar där Aspose.Imaging söker efter TrueType-teckensnitt.

Det returnerade värdet är en kopia av de data som Aspose.Imaging använder. Om du ändrar posterna i den returnerade arrayen kommer det inte att påverka dokumentrenderingen. För att ange nya teckensnittslägen använder du metoden  setFontsFolders .

**Returns:**
java.lang.String[] - En kopia av de aktuella teckensnittslägena.
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


Hämtar eller anger ett värde som indikerar om [get alternative font].

Värde:  true  om [get alternative font]; annars,  false .

**Returns:**
boolean
### getReplacementFont(String fontName) {#getReplacementFont-java.lang.String-}
```
public static String getReplacementFont(String fontName)
```


Hämtar det mest lämpliga ersättningsteckensnittet. Om alla ersättningar inte är tillåtna returneras det första tillåtna och tillgängliga teckensnittet. Om det inte finns några tillgängliga teckensnitt returneras teckensnittet från argumentet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | Namnet på teckensnittet. |

**Returns:**
java.lang.String - Namnet på det ersatta teckensnittet
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


Bestämmer om [is font allowed] [the specified font name].

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | Namnet på teckensnittet. |

**Returns:**
boolean -  true  om [is font allowed] [det angivna teckensnittsnamnet]; annars,  false .
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


Tar bort teckensnittscache-filen.

### reset() {#reset--}
```
public static void reset()
```


Återställer teckensnittsmappen och standardteckensnittets namn till systemstandard.

### setAllowedFonts(String[] fontList) {#setAllowedFonts-java.lang.String---}
```
public static void setAllowedFonts(String[] fontList)
```


Begränsar teckensnitt med en lista av teckensnitt. Kontrollera de faktiska teckensnittsnamnen innan begränsning. Ställ in den tillåtna teckensnittlistan till Null för att ta bort begränsningarna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontList | java.lang.String[] | Teckensnittlistan. |

### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


Anger standardteckensnittets namn.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | java.lang.String | Det standardnamn för teckensnittet. |

### setFontReplacements(String fontToReplace, String[] fontNames) {#setFontReplacements-java.lang.String-java.lang.String---}
```
public static void setFontReplacements(String fontToReplace, String[] fontNames)
```


Ställer in listan för teckensnittsersättningar. Om ett teckensnitt inte är tillåtet kommer en ersättning att hittas. Det första teckensnittet i listan används först. Om det också är begränsat väljs nästa teckensnitt i listan. Om teckensnittet saknar ersättningar eller alla ersättningar är otillåtna används det första tillåtna teckensnittet från den tillåtna teckensnittlistan. Om det inte finns några tillåtna och tillgängliga teckensnitt kommer biblioteket att försöka använda systemets standardteckensnitt även om det inte är tillåtet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontToReplace | java.lang.String | Teckensnittet att ersätta. |
| fontNames | java.lang.String[] | Ersättningsteckensnittens namn i likhetsordning. |

### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


Åsidosätt teckensnittsmappningslistan för  mapp

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | java.lang.String | Mapp med TrueType-teckensnitt. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


Åsidosätt teckensnittsmappningslistan för  mappar

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folders | java.lang.String[] | Array av mappar |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


Ställer in mapparna där TrueType-teckensnitt laddas från och rensar alla inlästa teckensnitt. Det utförs inga kontroller på teckensnittsmapparna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folders | java.lang.String[] | Fontmapparna. |
| rekursiv | boolean | om satt till  true  [rekursiv]. |

### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


Hämtar eller anger ett värde som indikerar om [get alternative font].

Värde:  true  om [get alternative font]; annars,  false .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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


Uppdaterar teckensnittscache för PSD‑filer som innehåller textlager. Denna metod garanterar att teckensnitt från mappen fontsFolder som används med metoden FontSettings.setFontsFolder(fontsFolder) eller efter återställning av teckensnitt med FontSettings.reset() tas i beaktande vid bearbetning av PSD‑filer. Använd denna metod varje gång FontSettings.setFontsFolder(fontsFolder) eller FontSettings.reset() anropas för PSD‑bilder. Utan att anropa denna metod finns det ingen garanti för att teckensnitt uppdateras.

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

