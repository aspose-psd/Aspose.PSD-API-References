---
title: "PdfCoreOptions"
second_title: "Aspose.PSD for Java API Справочник"
description: "Общие параметры конвертации в PDF."
type: docs
weight: 10
url: /ru/java/com.aspose.psd.fileformats.pdf/pdfcoreoptions/
---

**Inheritance:**
java.lang.Object
```
public class PdfCoreOptions
```

Общие параметры конвертации в PDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfCoreOptions()](#PdfCoreOptions--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | Указывает, на каком уровне в структуре документа отображать объекты закладок. |
| [getClass()](#getClass--) |  |
| [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | Указывает, сколько уровней в структуре документа показывать развернутыми при просмотре PDF‑файла. |
| [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | Указывает, сколько уровней элементов структуры включать в структуру документа. |
| [getJpegQuality()](#getJpegQuality--) | Указывает качество JPEG‑сжатия для изображений (если используется JPEG‑сжатие). |
| [getPdfCompliance()](#getPdfCompliance--) | Получает соответствие PDF. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | Указывает, на каком уровне в структуре документа отображать объекты закладок. |
| [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | Указывает, сколько уровней в структуре документа показывать развернутыми при просмотре PDF‑файла. |
| [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | Указывает, сколько уровней элементов структуры включать в структуру документа. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Указывает качество JPEG‑сжатия для изображений (если используется JPEG‑сжатие). |
| [setPdfCompliance(int value)](#setPdfCompliance-int-) | Устанавливает соответствие PDF. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PdfCoreOptions() {#PdfCoreOptions--}
```
public PdfCoreOptions()
```


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
### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public int getBookmarksOutlineLevel()
```


Указывает, на каком уровне в структуре документа отображать объекты закладок. 0 — не отображается. 1 — на первом уровне и так далее. По умолчанию 0.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public int getExpandedOutlineLevels()
```


Указывает, сколько уровней в структуре документа показывать развернутыми при просмотре PDF‑файла. 0 — структура документа не развернута. 1 — элементы первого уровня развернуты и так далее. По умолчанию 0.

**Returns:**
int
### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public int getHeadingsOutlineLevels()
```


Указывает, сколько уровней элементов структуры включать в структуру документа. 0 — без структуры, 1 — один уровень структуры и так далее. По умолчанию 0.

**Returns:**
int
### getJpegQuality() {#getJpegQuality--}
```
public int getJpegQuality()
```


Указывает качество JPEG‑сжатия для изображений (если используется JPEG‑сжатие). По умолчанию 95.

**Returns:**
int
### getPdfCompliance() {#getPdfCompliance--}
```
public final int getPdfCompliance()
```


Получает соответствие PDF.

**Returns:**
int - соответствие PDF.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public void setBookmarksOutlineLevel(int value)
```


Указывает, на каком уровне в структуре документа отображать объекты закладок. 0 — не отображается. 1 — на первом уровне и так далее. По умолчанию 0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public void setExpandedOutlineLevels(int value)
```


Указывает, сколько уровней в структуре документа показывать развернутыми при просмотре PDF‑файла. 0 — структура документа не развернута. 1 — элементы первого уровня развернуты и так далее. По умолчанию 0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public void setHeadingsOutlineLevels(int value)
```


Указывает, сколько уровней элементов структуры включать в структуру документа. 0 — без структуры, 1 — один уровень структуры и так далее. По умолчанию 0.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public void setJpegQuality(int value)
```


Указывает качество JPEG‑сжатия для изображений (если используется JPEG‑сжатие). По умолчанию 95.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### setPdfCompliance(int value) {#setPdfCompliance-int-}
```
public final void setPdfCompliance(int value)
```


Устанавливает соответствие PDF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int | соответствие PDF. |

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

