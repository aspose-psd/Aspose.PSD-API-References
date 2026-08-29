---
title: "Шрифт"
second_title: "Aspose.PSD for Java API Справочник"
description: "Представляет шрифт XMP."
type: docs
weight: 10
url: /ru/java/com.aspose.psd.xmp.types.complex.font/font/
---

**Inheritance:**
java.lang.Object, [com.aspose.psd.xmp.types.XmpTypeBase](../../com.aspose.psd.xmp.types/xmptypebase), [com.aspose.psd.xmp.types.complex.ComplexTypeBase](../../com.aspose.psd.xmp.types.complex/complextypebase)
```
public final class Font extends ComplexTypeBase
```

Представляет шрифт XMP.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Font()](#Font--) | Инициализирует новый экземпляр класса  Font  . |
| [Font(String fontFamily)](#Font-java.lang.String-) | Инициализирует новый экземпляр класса  Font  . |
## Методы

| Метод | Описание |
| --- | --- |
| [add(String key, Object value)](#add-java.lang.String-java.lang.Object-) | Добавляет указанный ключ. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChildFontFiles()](#getChildFontFiles--) | Получает или задает массив имен файлов шрифтов, составляющих составной шрифт. |
| [getClass()](#getClass--) |  |
| [getFontFace()](#getFontFace--) | Получает или задает начертание шрифта. |
| [getFontFamily()](#getFontFamily--) | Получает или задает семейство шрифта. |
| [getFontFileName()](#getFontFileName--) | Получает или задает имя файла шрифта без полного пути. |
| [getFontName()](#getFontName--) | Получает или задает имя шрифта PostScript. |
| [getFontType()](#getFontType--) | Получает или задает тип шрифта. |
| [getNamespaceUri()](#getNamespaceUri--) | Получает URI пространства имён по умолчанию. |
| [getPrefix()](#getPrefix--) | Получает префикс. |
| [getVersion()](#getVersion--) | Получает или задает версию шрифта. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Получает строковое значение в формате XMP. |
| [hashCode()](#hashCode--) |  |
| [isComposite()](#isComposite--) | Получает или задает значение, указывающее, является ли этот шрифт составным. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setChildFontFiles(String[] value)](#setChildFontFiles-java.lang.String---) | Получает или задает массив имен файлов шрифтов, составляющих составной шрифт. |
| [setComposite(boolean value)](#setComposite-boolean-) | Получает или задает значение, указывающее, является ли этот шрифт составным. |
| [setFontFace(String value)](#setFontFace-java.lang.String-) | Получает или задает начертание шрифта. |
| [setFontFamily(String value)](#setFontFamily-java.lang.String-) | Получает или задает семейство шрифта. |
| [setFontFileName(String value)](#setFontFileName-java.lang.String-) | Получает или задает имя файла шрифта без полного пути. |
| [setFontName(String value)](#setFontName-java.lang.String-) | Получает или задает имя шрифта PostScript. |
| [setFontType(String value)](#setFontType-java.lang.String-) | Получает или задает тип шрифта. |
| [setVersion(String value)](#setVersion-java.lang.String-) | Получает или задает версию шрифта. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Font() {#Font--}
```
public Font()
```


Инициализирует новый экземпляр класса  Font  .

### Font(String fontFamily) {#Font-java.lang.String-}
```
public Font(String fontFamily)
```


Инициализирует новый экземпляр класса  Font  .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontFamily | java.lang.String | Семейство шрифта. |

### add(String key, Object value) {#add-java.lang.String-java.lang.Object-}
```
public void add(String key, Object value)
```


Добавляет указанный ключ.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Строковое представление ключа, идентифицированного с добавленным значением. |
| значение | java.lang.Object | Значение для добавления. |

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
### getChildFontFiles() {#getChildFontFiles--}
```
public String[] getChildFontFiles()
```


Получает или задает массив имен файлов шрифтов, составляющих составной шрифт.

Значение: массив имён файлов шрифтов, составляющих составной шрифт.

**Returns:**
java.lang.String[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFontFace() {#getFontFace--}
```
public String getFontFace()
```


Получает или задает начертание шрифта.

Значение: начертание шрифта.

**Returns:**
java.lang.String
### getFontFamily() {#getFontFamily--}
```
public String getFontFamily()
```


Получает или задает семейство шрифта.

Значение: семейство шрифта.

**Returns:**
java.lang.String
### getFontFileName() {#getFontFileName--}
```
public String getFontFileName()
```


Получает или задает имя файла шрифта без полного пути.

Значение: имя файла шрифта без полного пути.

**Returns:**
java.lang.String
### getFontName() {#getFontName--}
```
public String getFontName()
```


Получает или задает имя шрифта PostScript.

Значение: имя шрифта PostScript.

**Returns:**
java.lang.String
### getFontType() {#getFontType--}
```
public String getFontType()
```


Получает или задает тип шрифта.

TrueType, Type 1, Open Type и т.д. Значение: тип шрифта.

**Returns:**
java.lang.String
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


Получает URI пространства имён по умолчанию.

**Returns:**
java.lang.String - Значение URI пространства имён по умолчанию.
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


Получает префикс.

**Returns:**
java.lang.String - Префикс.
### getVersion() {#getVersion--}
```
public String getVersion()
```


Получает или задает версию шрифта.

/version для шрифтов Type1, nameId 5 для Apple True Type и OpenType, /CIDFontVersion для CID‑шрифтов. Пустая строка для растровых шрифтов. Значение: версия шрифта.

**Returns:**
java.lang.String
### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Получает строковое значение в формате XMP.

**Returns:**
java.lang.String - Возвращает строковое значение в формате XMP.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isComposite() {#isComposite--}
```
public boolean isComposite()
```


Получает или задает значение, указывающее, является ли этот шрифт составным.

Значение:  true  если этот шрифт составной; в противном случае  false .

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setChildFontFiles(String[] value) {#setChildFontFiles-java.lang.String---}
```
public void setChildFontFiles(String[] value)
```


Получает или задает массив имен файлов шрифтов, составляющих составной шрифт.

Значение: массив имён файлов шрифтов, составляющих составной шрифт.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String[] |  |

### setComposite(boolean value) {#setComposite-boolean-}
```
public void setComposite(boolean value)
```


Получает или задает значение, указывающее, является ли этот шрифт составным.

Значение:  true  если этот шрифт составной; в противном случае  false .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### setFontFace(String value) {#setFontFace-java.lang.String-}
```
public void setFontFace(String value)
```


Получает или задает начертание шрифта.

Значение: начертание шрифта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setFontFamily(String value) {#setFontFamily-java.lang.String-}
```
public void setFontFamily(String value)
```


Получает или задает семейство шрифта.

Значение: семейство шрифта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setFontFileName(String value) {#setFontFileName-java.lang.String-}
```
public void setFontFileName(String value)
```


Получает или задает имя файла шрифта без полного пути.

Значение: имя файла шрифта без полного пути.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setFontName(String value) {#setFontName-java.lang.String-}
```
public void setFontName(String value)
```


Получает или задает имя шрифта PostScript.

Значение: имя шрифта PostScript.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setFontType(String value) {#setFontType-java.lang.String-}
```
public void setFontType(String value)
```


Получает или задает тип шрифта.

TrueType, Type 1, Open Type и т.д. Значение: тип шрифта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### setVersion(String value) {#setVersion-java.lang.String-}
```
public void setVersion(String value)
```


Получает или задает версию шрифта.

/version для шрифтов Type1, nameId 5 для Apple True Type и OpenType, /CIDFontVersion для CID‑шрифтов. Пустая строка для растровых шрифтов. Значение: версия шрифта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

