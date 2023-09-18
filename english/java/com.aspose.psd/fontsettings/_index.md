---
title: FontSettings
second_title: Aspose.PSD for Java API Reference
description: General imaging vector formats renderer font settings.
type: docs
weight: 47
url: /java/com.aspose.psd/fontsettings/
---

**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

General imaging vector formats renderer font settings.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeFontName(String fontFamilyName)](#getAdobeFontName-java.lang.String-) | Gets the adobe font name by font family name. |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | Gets the default font name. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | Gets the default fonts folders. |
| [getFontReplacements(String fontName)](#getFontReplacements-java.lang.String-) | Gets the font replacements array by the font name |
| [getFontsFolders()](#getFontsFolders--) | Gets a copy of the array that contains the list of folders where Aspose.Imaging looks for TrueType fonts. |
| [getReplacementFont(String fontName)](#getReplacementFont-java.lang.String-) | Gets the most suitable replacement font. |
| [hashCode()](#hashCode--) |  |
| [isFontAllowed(String fontName)](#isFontAllowed-java.lang.String-) | Determines whether [is font allowed] [the specified font name]. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [reset()](#reset--) | Resets the fonts folder and default font name to the system default. |
| [setAllowedFonts(String[] fontList)](#setAllowedFonts-java.lang.String---) | Restricts font using by list of fonts. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | Sets the default font name. |
| [setFontReplacements(String fontToReplace, String[] fontNames)](#setFontReplacements-java.lang.String-java.lang.String---) | Sets the font replacement list. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | Override font folder list for  folder  |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | Override font folder list for  folders  |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | Sets the folders where TrueType fonts are loaded from and clears all loaded fonts. |
| [toString()](#toString--) |  |
| [updateFonts()](#updateFonts--) | Updates fonts cache for PSD files that contain text layers. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAdobeFontName(String fontFamilyName) {#getAdobeFontName-java.lang.String-}
```
public static String getAdobeFontName(String fontFamilyName)
```


Gets the adobe font name by font family name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontFamilyName | java.lang.String | The font family name. |

**Returns:**
java.lang.String - The adobe font name by font family name.
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


Gets the default font name.

**Returns:**
java.lang.String - default font's name
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


Gets the default fonts folders.

**Returns:**
java.lang.String[] - Returns system folder
### getFontReplacements(String fontName) {#getFontReplacements-java.lang.String-}
```
public static String[] getFontReplacements(String fontName)
```


Gets the font replacements array by the font name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Name of the font. |

**Returns:**
java.lang.String[] - Array of names of replacements for provided fonts
### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


Gets a copy of the array that contains the list of folders where Aspose.Imaging looks for TrueType fonts.

The returned value is a copy of the data that Aspose.Imaging uses. If you change the entries in the returned array, it will have no effect on document rendering. To specify new font locations use the  setFontsFolders  method.

**Returns:**
java.lang.String[] - A copy of the current font locations.
### getReplacementFont(String fontName) {#getReplacementFont-java.lang.String-}
```
public static String getReplacementFont(String fontName)
```


Gets the most suitable replacement font. If all replacements are not allowed then will returned first allowed and available font. If there are no available fonts then will be returned font from argument

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Name of the font. |

**Returns:**
java.lang.String - The name of replaced font
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


Determines whether [is font allowed] [the specified font name].

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | Name of the font. |

**Returns:**
boolean -  true  if [is font allowed] [the specified font name]; otherwise,  false .
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### reset() {#reset--}
```
public static void reset()
```


Resets the fonts folder and default font name to the system default.

### setAllowedFonts(String[] fontList) {#setAllowedFonts-java.lang.String---}
```
public static void setAllowedFonts(String[] fontList)
```


Restricts font using by list of fonts. Please check real font names before restriction Set Allowed font list to Null to remove restrictrions

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontList | java.lang.String[] | The font list. |

### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


Sets the default font name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontName | java.lang.String | The default name of the font. |

### setFontReplacements(String fontToReplace, String[] fontNames) {#setFontReplacements-java.lang.String-java.lang.String---}
```
public static void setFontReplacements(String fontToReplace, String[] fontNames)
```


Sets the font replacement list. If font is not allowed then will be find replacement. The first one font in list will be used first. If it retricted too, then will be selected next font from list. If font has not replacements or all replacements are not allowed then will be used first allowed font from allowed font list. If there are no allowed and available fonts then library will try use system default font even if it is not allowed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontToReplace | java.lang.String | The font to replace. |
| fontNames | java.lang.String[] | The replacement font names in order of similarity. |

### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


Override font folder list for  folder 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | java.lang.String | Folder with TrueType fonts. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


Override font folder list for  folders 

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folders | java.lang.String[] | Array of folder |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


Sets the folders where TrueType fonts are loaded from and clears all loaded fonts. There are no checks performed on the fonts folders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folders | java.lang.String[] | The fonts folders. |
| recursive | boolean | if set to  true  [recursive]. |

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


Updates fonts cache for PSD files that contain text layers. This method guarantees that fonts from folder fontsFolder using method FontSettings.setFontsFolder(fontsFolder) or after reset fonts using FontSettings.reset() will be taken into consideration when processing PSD files. Please use this method each time when FontSettings.setFontsFolder(fontsFolder) or FontSettings.reset() called for PSD images. Without calling this Method there is no guarantee that fonts will be updated.

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

