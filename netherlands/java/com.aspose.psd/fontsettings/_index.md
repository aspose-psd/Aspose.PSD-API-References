---
title: "FontSettings"
second_title: "Aspose.PSD voor Java API-referentie"
description: "Algemene instellingen voor lettertype van de renderer voor afbeeldingsvectorformaten."
type: docs
weight: 47
url: /nl/java/com.aspose.psd/fontsettings/
---

**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

Algemene instellingen voor lettertype van de renderer voor afbeeldingsvectorformaten.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeFontName(String fontFamilyName)](#getAdobeFontName-java.lang.String-) | Haalt de Adobe-lettertype naam op op basis van de lettertypefamilienaam. |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | Haalt de standaardlettertype naam op. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | Haalt de standaardlettertype mappen op. |
| [getFontReplacements(String fontName)](#getFontReplacements-java.lang.String-) | Haalt de array met lettertypevervangingen op op basis van de lettertype naam. |
| [getFontsFolders()](#getFontsFolders--) | Haalt een kopie van de array op die de lijst met mappen bevat waar Aspose.Imaging zoekt naar TrueType-lettertypen. |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | Haalt op of stelt een waarde in die aangeeft of [get alternative font]. |
| [getReplacementFont(String fontName)](#getReplacementFont-java.lang.String-) | Haalt het meest geschikte vervangende lettertype op. |
| [hashCode()](#hashCode--) |  |
| [isFontAllowed(String fontName)](#isFontAllowed-java.lang.String-) | Bepaalt of [is font allowed] [de opgegeven lettertype naam]. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFontCacheFile()](#removeFontCacheFile--) | Verwijdert het lettertype cachebestand. |
| [reset()](#reset--) | Reset de lettertype map en standaardlettertype naam naar de systeemstandaard. |
| [setAllowedFonts(String[] fontList)](#setAllowedFonts-java.lang.String---) | Beperkt het gebruik van lettertypen door een lijst met lettertypen. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | Stelt de standaardlettertype naam in. |
| [setFontReplacements(String fontToReplace, String[] fontNames)](#setFontReplacements-java.lang.String-java.lang.String---) | Stelt de lijst met lettertypevervangingen in. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | Overschrijf de lijst met lettertypemappen voor  folder |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | Overschrijf de lijst met lettertypemappen voor  folders |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | Stelt de mappen in waar TrueType-lettertypen van worden geladen en wist alle geladen lettertypen. |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | Haalt op of stelt een waarde in die aangeeft of [get alternative font]. |
| [toString()](#toString--) |  |
| [updateFonts()](#updateFonts--) | Werk de lettertypecache bij voor PSD-bestanden die tekstlagen bevatten. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAdobeFontName(String fontFamilyName) {#getAdobeFontName-java.lang.String-}
```
public static String getAdobeFontName(String fontFamilyName)
```


Haalt de Adobe-lettertype naam op op basis van de lettertypefamilienaam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontFamilyName | java.lang.String | De lettertypefamilienaam. |

**Returns:**
java.lang.String - De Adobe-lettertype naam op basis van de lettertypefamilienaam.
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


Haalt de standaardlettertype naam op.

**Returns:**
java.lang.String - standaardlettertype naam
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


Haalt de standaardlettertype mappen op.

**Returns:**
java.lang.String[] - Retourneert systeemmap
### getFontReplacements(String fontName) {#getFontReplacements-java.lang.String-}
```
public static String[] getFontReplacements(String fontName)
```


Haalt de array met lettertypevervangingen op op basis van de lettertype naam.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | java.lang.String | Naam van het lettertype. |

**Returns:**
java.lang.String[] - Array van namen van vervangingen voor opgegeven lettertypen
### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


Haalt een kopie van de array op die de lijst met mappen bevat waar Aspose.Imaging zoekt naar TrueType-lettertypen.

De geretourneerde waarde is een kopie van de gegevens die Aspose.Imaging gebruikt. Als u de items in de geretourneerde array wijzigt, heeft dit geen effect op het renderen van het document. Om nieuwe lettertype‑locaties op te geven, gebruikt u de methode  setFontsFolders  .

**Returns:**
java.lang.String[] - Een kopie van de huidige lettertype‑locaties.
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


Haalt op of stelt een waarde in die aangeeft of [get alternative font].

Waarde:  true  als [get alternative font]; anders,  false .

**Returns:**
boolean
### getReplacementFont(String fontName) {#getReplacementFont-java.lang.String-}
```
public static String getReplacementFont(String fontName)
```


Haalt het meest geschikte vervangende lettertype op. Als alle vervangingen niet zijn toegestaan, wordt het eerst toegestane en beschikbare lettertype geretourneerd. Als er geen beschikbare lettertypen zijn, wordt het lettertype uit het argument geretourneerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | java.lang.String | Naam van het lettertype. |

**Returns:**
java.lang.String - De naam van het vervangen lettertype
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


Bepaalt of [is font allowed] [de opgegeven lettertype naam].

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | java.lang.String | Naam van het lettertype. |

**Returns:**
boolean -  true  als [is font allowed] [de opgegeven lettertype‑naam]; anders,  false .
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


Verwijdert het lettertype cachebestand.

### reset() {#reset--}
```
public static void reset()
```


Reset de lettertype map en standaardlettertype naam naar de systeemstandaard.

### setAllowedFonts(String[] fontList) {#setAllowedFonts-java.lang.String---}
```
public static void setAllowedFonts(String[] fontList)
```


Beperkt lettertypen via een lijst van lettertypen. Controleer de echte lettertype‑namen vóór de beperking. Stel de toegestane lettertypelijst in op Null om beperkingen te verwijderen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontList | java.lang.String[] | De lettertypelijst. |

### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


Stelt de standaardlettertype naam in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | java.lang.String | De standaardnaam van het lettertype. |

### setFontReplacements(String fontToReplace, String[] fontNames) {#setFontReplacements-java.lang.String-java.lang.String---}
```
public static void setFontReplacements(String fontToReplace, String[] fontNames)
```


Stelt de lijst met lettertype‑vervangingen in. Als een lettertype niet is toegestaan, wordt er een vervanging gezocht. Het eerste lettertype in de lijst wordt als eerste gebruikt. Als dat ook beperkt is, wordt het volgende lettertype uit de lijst geselecteerd. Als een lettertype geen vervangingen heeft of alle vervangingen niet zijn toegestaan, wordt het eerst toegestane lettertype uit de toegestane lettertypelijst gebruikt. Als er geen toegestane en beschikbare lettertypen zijn, probeert de bibliotheek het systeem‑standaardlettertype te gebruiken, zelfs als dit niet is toegestaan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontToReplace | java.lang.String | Het te vervangen lettertype. |
| fontNames | java.lang.String[] | De vervangende lettertype‑namen in volgorde van gelijkenis. |

### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


Overschrijf de lijst met lettertypemappen voor  folder

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| folder | java.lang.String | Map met TrueType-lettertypen. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


Overschrijf de lijst met lettertypemappen voor  folders

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| folders | java.lang.String[] | Array van mappen |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


Stelt de mappen in waaruit TrueType-lettertypen worden geladen en wist alle geladen lettertypen. Er worden geen controles uitgevoerd op de lettertype‑mappen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| folders | java.lang.String[] | De lettertype‑mappen. |
| recursive | boolean | als ingesteld op  true  [recursive]. |

### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


Haalt op of stelt een waarde in die aangeeft of [get alternative font].

Waarde:  true  als [get alternative font]; anders,  false .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

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


Werkt de lettertypecache bij voor PSD‑bestanden die tekstlagen bevatten. Deze methode garandeert dat lettertypen uit map fontsFolder die worden gebruikt via de methode FontSettings.setFontsFolder(fontsFolder) of na het resetten van lettertypen via FontSettings.reset() in aanmerking worden genomen bij het verwerken van PSD‑bestanden. Gebruik deze methode elke keer wanneer FontSettings.setFontsFolder(fontsFolder) of FontSettings.reset() wordt aangeroepen voor PSD‑afbeeldingen. Zonder het aanroepen van deze methode is er geen garantie dat lettertypen worden bijgewerkt.

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

