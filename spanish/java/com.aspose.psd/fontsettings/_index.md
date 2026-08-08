---
title: "FontSettings"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Configuraciones de fuente del renderizador de formatos vectoriales de imágenes generales."
type: docs
weight: 47
url: /es/java/com.aspose.psd/fontsettings/
---

**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

Configuraciones de fuente del renderizador de formatos vectoriales de imágenes generales.
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeFontName(String fontFamilyName)](#getAdobeFontName-java.lang.String-) | Obtiene el nombre de fuente Adobe por nombre de familia de fuente. |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | Obtiene el nombre de fuente predeterminado. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | Obtiene las carpetas de fuentes predeterminadas. |
| [getFontReplacements(String fontName)](#getFontReplacements-java.lang.String-) | Obtiene la matriz de reemplazos de fuentes por el nombre de la fuente |
| [getFontsFolders()](#getFontsFolders--) | Obtiene una copia de la matriz que contiene la lista de carpetas donde Aspose.Imaging busca fuentes TrueType. |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | Obtiene o establece un valor que indica si [obtener fuente alternativa]. |
| [getReplacementFont(String fontName)](#getReplacementFont-java.lang.String-) | Obtiene la fuente de reemplazo más adecuada. |
| [hashCode()](#hashCode--) |  |
| [isFontAllowed(String fontName)](#isFontAllowed-java.lang.String-) | Determina si [se permite la fuente] [el nombre de fuente especificado]. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFontCacheFile()](#removeFontCacheFile--) | Elimina el archivo de caché de fuentes. |
| [reset()](#reset--) | Restablece la carpeta de fuentes y el nombre de fuente predeterminado al valor predeterminado del sistema. |
| [setAllowedFonts(String[] fontList)](#setAllowedFonts-java.lang.String---) | Restringe el uso de fuentes mediante una lista de fuentes. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | Establece el nombre de fuente predeterminado. |
| [setFontReplacements(String fontToReplace, String[] fontNames)](#setFontReplacements-java.lang.String-java.lang.String---) | Establece la lista de reemplazo de fuentes. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | Sobrescribir la lista de carpetas de fuentes para  carpeta |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | Sobrescribir la lista de carpetas de fuentes para  carpetas |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | Establece las carpetas desde donde se cargan las fuentes TrueType y elimina todas las fuentes cargadas. |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | Obtiene o establece un valor que indica si [obtener fuente alternativa]. |
| [toString()](#toString--) |  |
| [updateFonts()](#updateFonts--) | Actualiza la caché de fuentes para archivos PSD que contienen capas de texto. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAdobeFontName(String fontFamilyName) {#getAdobeFontName-java.lang.String-}
```
public static String getAdobeFontName(String fontFamilyName)
```


Obtiene el nombre de fuente Adobe por nombre de familia de fuente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontFamilyName | java.lang.String | El nombre de la familia de fuentes. |

**Returns:**
java.lang.String - El nombre de fuente Adobe por nombre de familia de fuente.
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


Obtiene el nombre de fuente predeterminado.

**Returns:**
java.lang.String - nombre de la fuente predeterminada
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


Obtiene las carpetas de fuentes predeterminadas.

**Returns:**
java.lang.String[] - Devuelve la carpeta del sistema
### getFontReplacements(String fontName) {#getFontReplacements-java.lang.String-}
```
public static String[] getFontReplacements(String fontName)
```


Obtiene la matriz de reemplazos de fuentes por el nombre de la fuente

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | Nombre de la fuente. |

**Returns:**
java.lang.String[] - Matriz de nombres de reemplazos para las fuentes proporcionadas
### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


Obtiene una copia de la matriz que contiene la lista de carpetas donde Aspose.Imaging busca fuentes TrueType.

El valor devuelto es una copia de los datos que utiliza Aspose.Imaging. Si cambias las entradas en la matriz devuelta, no tendrá ningún efecto en la renderización del documento. Para especificar nuevas ubicaciones de fuentes usa el método  setFontsFolders .

**Returns:**
java.lang.String[] - Una copia de las ubicaciones actuales de fuentes.
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


Obtiene o establece un valor que indica si [obtener fuente alternativa].

Valor:  true  si [get alternative font]; de lo contrario,  false .

**Returns:**
boolean
### getReplacementFont(String fontName) {#getReplacementFont-java.lang.String-}
```
public static String getReplacementFont(String fontName)
```


Obtiene la fuente de reemplazo más adecuada. Si todos los reemplazos no están permitidos, se devolverá la primera fuente permitida y disponible. Si no hay fuentes disponibles, se devolverá la fuente del argumento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | Nombre de la fuente. |

**Returns:**
java.lang.String - El nombre de la fuente reemplazada
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


Determina si [se permite la fuente] [el nombre de fuente especificado].

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | Nombre de la fuente. |

**Returns:**
boolean -  true  si [is font allowed] [el nombre de fuente especificado]; de lo contrario,  false .
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


Elimina el archivo de caché de fuentes.

### reset() {#reset--}
```
public static void reset()
```


Restablece la carpeta de fuentes y el nombre de fuente predeterminado al valor predeterminado del sistema.

### setAllowedFonts(String[] fontList) {#setAllowedFonts-java.lang.String---}
```
public static void setAllowedFonts(String[] fontList)
```


Restringe el uso de fuentes mediante una lista de fuentes. Por favor, verifica los nombres reales de las fuentes antes de la restricción. Establece la lista de fuentes permitidas a Null para eliminar las restricciones.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontList | java.lang.String[] | La lista de fuentes. |

### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


Establece el nombre de fuente predeterminado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontName | java.lang.String | El nombre predeterminado de la fuente. |

### setFontReplacements(String fontToReplace, String[] fontNames) {#setFontReplacements-java.lang.String-java.lang.String---}
```
public static void setFontReplacements(String fontToReplace, String[] fontNames)
```


Establece la lista de reemplazo de fuentes. Si una fuente no está permitida, se buscará un reemplazo. La primera fuente de la lista se usará primero. Si también está restringida, se seleccionará la siguiente fuente de la lista. Si la fuente no tiene reemplazos o todos los reemplazos no están permitidos, se usará la primera fuente permitida de la lista de fuentes permitidas. Si no hay fuentes permitidas y disponibles, la biblioteca intentará usar la fuente predeterminada del sistema aunque no esté permitida.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontToReplace | java.lang.String | La fuente a reemplazar. |
| fontNames | java.lang.String[] | Los nombres de fuentes de reemplazo en orden de similitud. |

### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


Sobrescribir la lista de carpetas de fuentes para  carpeta

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| folder | java.lang.String | Carpeta con fuentes TrueType. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


Sobrescribir la lista de carpetas de fuentes para  carpetas

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| folders | java.lang.String[] | Matriz de carpetas |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


Establece las carpetas desde donde se cargan las fuentes TrueType y borra todas las fuentes cargadas. No se realizan verificaciones en las carpetas de fuentes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| folders | java.lang.String[] | Las carpetas de fuentes. |
| recursive | boolean | si se establece a  true  [recursive]. |

### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


Obtiene o establece un valor que indica si [obtener fuente alternativa].

Valor:  true  si [get alternative font]; de lo contrario,  false .

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

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


Actualiza la caché de fuentes para archivos PSD que contienen capas de texto. Este método garantiza que las fuentes de la carpeta fontsFolder usando el método FontSettings.setFontsFolder(fontsFolder) o después de restablecer fuentes usando FontSettings.reset() serán tenidas en cuenta al procesar archivos PSD. Por favor, use este método cada vez que se llame a FontSettings.setFontsFolder(fontsFolder) o FontSettings.reset() para imágenes PSD. Sin llamar a este método no hay garantía de que las fuentes se actualicen.

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

