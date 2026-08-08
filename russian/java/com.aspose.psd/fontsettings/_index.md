---
title: "FontSettings"
second_title: "Aspose.PSD for Java API Справочник"
description: "Настройки шрифтов рендерера общих векторных форматов изображений."
type: docs
weight: 47
url: /ru/java/com.aspose.psd/fontsettings/
---

**Inheritance:**
java.lang.Object
```
public final class FontSettings
```

Настройки шрифтов рендерера общих векторных форматов изображений.
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdobeFontName(String fontFamilyName)](#getAdobeFontName-java.lang.String-) | Получает имя шрифта Adobe по имени семейства шрифта. |
| [getClass()](#getClass--) |  |
| [getDefaultFontName()](#getDefaultFontName--) | Получает имя шрифта по умолчанию. |
| [getDefaultFontsFolders()](#getDefaultFontsFolders--) | Получает папки шрифтов по умолчанию. |
| [getFontReplacements(String fontName)](#getFontReplacements-java.lang.String-) | Получает массив замен шрифтов по имени шрифта |
| [getFontsFolders()](#getFontsFolders--) | Получает копию массива, содержащего список папок, где Aspose.Imaging ищет TrueType‑шрифты. |
| [getGetSystemAlternativeFont()](#getGetSystemAlternativeFont--) | Получает или задает значение, указывающее, следует ли [get alternative font]. |
| [getReplacementFont(String fontName)](#getReplacementFont-java.lang.String-) | Получает наиболее подходящий заменяющий шрифт. |
| [hashCode()](#hashCode--) |  |
| [isFontAllowed(String fontName)](#isFontAllowed-java.lang.String-) | Определяет, [is font allowed] [the specified font name]. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeFontCacheFile()](#removeFontCacheFile--) | Удаляет файл кэша шрифтов. |
| [reset()](#reset--) | Сбрасывает папку шрифтов и имя шрифта по умолчанию к системным настройкам. |
| [setAllowedFonts(String[] fontList)](#setAllowedFonts-java.lang.String---) | Ограничивает использование шрифтов списком шрифтов. |
| [setDefaultFontName(String fontName)](#setDefaultFontName-java.lang.String-) | Устанавливает имя шрифта по умолчанию. |
| [setFontReplacements(String fontToReplace, String[] fontNames)](#setFontReplacements-java.lang.String-java.lang.String---) | Устанавливает список замен шрифтов. |
| [setFontsFolder(String folder)](#setFontsFolder-java.lang.String-) | Переопределить список папок шрифтов для папки |
| [setFontsFolders(String[] folders)](#setFontsFolders-java.lang.String---) | Переопределить список папок шрифтов для папок |
| [setFontsFolders(String[] folders, boolean recursive)](#setFontsFolders-java.lang.String---boolean-) | Устанавливает папки, из которых загружаются TrueType‑шрифты, и очищает все загруженные шрифты. |
| [setGetSystemAlternativeFont(boolean value)](#setGetSystemAlternativeFont-boolean-) | Получает или задает значение, указывающее, следует ли [get alternative font]. |
| [toString()](#toString--) |  |
| [updateFonts()](#updateFonts--) | Обновляет кэш шрифтов для PSD‑файлов, содержащих текстовые слои. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAdobeFontName(String fontFamilyName) {#getAdobeFontName-java.lang.String-}
```
public static String getAdobeFontName(String fontFamilyName)
```


Получает имя шрифта Adobe по имени семейства шрифта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFamilyName | java.lang.String | Имя семейства шрифта. |

**Returns:**
java.lang.String - Имя шрифта Adobe по имени семейства шрифта.
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


Получает имя шрифта по умолчанию.

**Returns:**
java.lang.String - имя шрифта по умолчанию
### getDefaultFontsFolders() {#getDefaultFontsFolders--}
```
public static String[] getDefaultFontsFolders()
```


Получает папки шрифтов по умолчанию.

**Returns:**
java.lang.String[] - Возвращает системную папку
### getFontReplacements(String fontName) {#getFontReplacements-java.lang.String-}
```
public static String[] getFontReplacements(String fontName)
```


Получает массив замен шрифтов по имени шрифта

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Имя шрифта. |

**Returns:**
java.lang.String[] - Массив имён замен для предоставленных шрифтов
### getFontsFolders() {#getFontsFolders--}
```
public static String[] getFontsFolders()
```


Получает копию массива, содержащего список папок, где Aspose.Imaging ищет TrueType‑шрифты.

Возвращаемое значение является копией данных, используемых Aspose.Imaging. Если изменить элементы в возвращённом массиве, это не повлияет на отрисовку документа. Чтобы указать новые расположения шрифтов, используйте метод  setFontsFolders .

**Returns:**
java.lang.String[] - Копия текущих расположений шрифтов.
### getGetSystemAlternativeFont() {#getGetSystemAlternativeFont--}
```
public static boolean getGetSystemAlternativeFont()
```


Получает или задает значение, указывающее, следует ли [get alternative font].

Значение:  true  если [get alternative font]; иначе,  false .

**Returns:**
boolean
### getReplacementFont(String fontName) {#getReplacementFont-java.lang.String-}
```
public static String getReplacementFont(String fontName)
```


Получает наиболее подходящий заменяющий шрифт. Если все замены не разрешены, будет возвращён первый разрешённый и доступный шрифт. Если доступных шрифтов нет, будет возвращён шрифт из аргумента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Имя шрифта. |

**Returns:**
java.lang.String - Имя заменённого шрифта
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


Определяет, [is font allowed] [the specified font name].

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Имя шрифта. |

**Returns:**
boolean -  true  если [is font allowed] [указанное имя шрифта]; иначе,  false .
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


Удаляет файл кэша шрифтов.

### reset() {#reset--}
```
public static void reset()
```


Сбрасывает папку шрифтов и имя шрифта по умолчанию к системным настройкам.

### setAllowedFonts(String[] fontList) {#setAllowedFonts-java.lang.String---}
```
public static void setAllowedFonts(String[] fontList)
```


Ограничивает использование шрифтов списком шрифтов. Пожалуйста, проверьте реальные имена шрифтов перед ограничением. Установите список разрешённых шрифтов в Null, чтобы снять ограничения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontList | java.lang.String[] | Список шрифтов. |

### setDefaultFontName(String fontName) {#setDefaultFontName-java.lang.String-}
```
public static void setDefaultFontName(String fontName)
```


Устанавливает имя шрифта по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Имя шрифта по умолчанию. |

### setFontReplacements(String fontToReplace, String[] fontNames) {#setFontReplacements-java.lang.String-java.lang.String---}
```
public static void setFontReplacements(String fontToReplace, String[] fontNames)
```


Устанавливает список замен шрифтов. Если шрифт не разрешён, будет найдено заменяющее значение. Первый шрифт в списке будет использован первым. Если он также ограничен, будет выбран следующий шрифт из списка. Если у шрифта нет замен или все замены не разрешены, будет использован первый разрешённый шрифт из списка разрешённых шрифтов. Если нет разрешённых и доступных шрифтов, библиотека попытается использовать системный шрифт по умолчанию, даже если он не разрешён.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontToReplace | java.lang.String | Шрифт для замены. |
| fontNames | java.lang.String[] | Имена заменяющих шрифтов в порядке схожести. |

### setFontsFolder(String folder) {#setFontsFolder-java.lang.String-}
```
public static void setFontsFolder(String folder)
```


Переопределить список папок шрифтов для папки

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | java.lang.String | Папка с TrueType‑шрифтами. |

### setFontsFolders(String[] folders) {#setFontsFolders-java.lang.String---}
```
public static void setFontsFolders(String[] folders)
```


Переопределить список папок шрифтов для папок

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| folders | java.lang.String[] | Массив папок |

### setFontsFolders(String[] folders, boolean recursive) {#setFontsFolders-java.lang.String---boolean-}
```
public static void setFontsFolders(String[] folders, boolean recursive)
```


Устанавливает папки, из которых загружаются TrueType‑шрифты, и очищает все загруженные шрифты. Проверки папок шрифтов не выполняются.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| folders | java.lang.String[] | Папки шрифтов. |
| recursive | boolean | если установлено в  true  [recursive]. |

### setGetSystemAlternativeFont(boolean value) {#setGetSystemAlternativeFont-boolean-}
```
public static void setGetSystemAlternativeFont(boolean value)
```


Получает или задает значение, указывающее, следует ли [get alternative font].

Значение:  true  если [get alternative font]; иначе,  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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


Обновляет кэш шрифтов для PSD‑файлов, содержащих текстовые слои. Этот метод гарантирует, что шрифты из папки fontsFolder, указанные методом FontSettings.setFontsFolder(fontsFolder) или после сброса шрифтов с помощью FontSettings.reset(), будут учитываться при обработке PSD‑файлов. Пожалуйста, используйте этот метод каждый раз, когда вызывается FontSettings.setFontsFolder(fontsFolder) или FontSettings.reset() для PSD‑изображений. Без вызова этого метода нет гарантии, что шрифты будут обновлены.

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

