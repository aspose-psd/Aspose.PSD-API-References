---
title: "XmpPacketWrapper"
second_title: "Aspose.PSD for Java API Справочник"
description: "Содержит сериализованный пакет xmp, включающий заголовок и трейлер."
type: docs
weight: 20
url: /ru/java/com.aspose.psd.xmp/xmppacketwrapper/
---

**Inheritance:**
java.lang.Object
```
public class XmpPacketWrapper
```

Содержит сериализованный пакет xmp, включающий заголовок и трейлер.

Обёртка, состоящая из пары инструкций обработки XML (PI), может быть размещена вокруг элемента rdf:RDF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)](#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-) | Инициализирует новый экземпляр класса  XmpPacketWrapper  . |
| [XmpPacketWrapper()](#XmpPacketWrapper--) | Инициализирует новый экземпляр класса  XmpPacketWrapper  . |
## Методы

| Метод | Описание |
| --- | --- |
| [addPackage(XmpPackage package_)](#addPackage-com.aspose.psd.xmp.XmpPackage-) | Добавляет пакет. |
| [clearPackages()](#clearPackages--) | Удаляет все  XmpPackage  внутри XMP. |
| [containsPackage(String namespaceUri)](#containsPackage-java.lang.String-) | Определяет, существует ли пакет в обёртке XMP. |
| [deepClone_internalized()](#deepClone-internalized--) | Клонирует этот экземпляр. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getHeaderPi()](#getHeaderPi--) | Получает инструкцию обработки заголовка. |
| [getMeta()](#getMeta--) | Получает метаданные XMP. |
| [getPackage(String namespaceUri)](#getPackage-java.lang.String-) | Получает пакет по URI пространства имён. |
| [getPackages()](#getPackages--) | Получает массив  XmpPackage  внутри XMP. |
| [getPackagesCount()](#getPackagesCount--) | Получает количество пакетов внутри структуры XMP. |
| [getRdfRoot_internalized()](#getRdfRoot-internalized--) | Получает корневой элемент RDF. |
| [getTrailerPi()](#getTrailerPi--) | Получает инструкцию обработки трейлера. |
| [getXmlValue_internalized()](#getXmlValue-internalized--) | Преобразует значение XMP в представление XML. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removePackage(XmpPackage package_)](#removePackage-com.aspose.psd.xmp.XmpPackage-) | Удаляет пакет XMP. |
| [setHeaderPi(XmpHeaderPi value)](#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-) | Устанавливает инструкцию обработки заголовка. |
| [setMeta(XmpMeta value)](#setMeta-com.aspose.psd.xmp.XmpMeta-) | Устанавливает метаданные XMP. |
| [setRdfRoot_internalized(XmpRdfRoot value)](#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-) | Устанавливает корневой элемент RDF. |
| [setTrailerPi(XmpTrailerPi value)](#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-) | Устанавливает инструкцию обработки трейлера. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta) {#XmpPacketWrapper-com.aspose.psd.xmp.XmpHeaderPi-com.aspose.psd.xmp.XmpTrailerPi-com.aspose.psd.xmp.XmpMeta-}
```
public XmpPacketWrapper(XmpHeaderPi header, XmpTrailerPi trailer, XmpMeta xmpMeta)
```


Инициализирует новый экземпляр класса  XmpPacketWrapper  .

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| header | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | Заголовок XMP инструкции обработки. |
| trailer | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | Трейлер XMP инструкции обработки. |
| xmpMeta | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | Метаданные XMP. |

### XmpPacketWrapper() {#XmpPacketWrapper--}
```
public XmpPacketWrapper()
```


Инициализирует новый экземпляр класса  XmpPacketWrapper  .

### addPackage(XmpPackage package_) {#addPackage-com.aspose.psd.xmp.XmpPackage-}
```
public void addPackage(XmpPackage package_)
```


Добавляет пакет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Пакет. |

### clearPackages() {#clearPackages--}
```
public void clearPackages()
```


Удаляет все  XmpPackage  внутри XMP.

### containsPackage(String namespaceUri) {#containsPackage-java.lang.String-}
```
public boolean containsPackage(String namespaceUri)
```


Определяет, существует ли пакет в обёртке XMP.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| namespaceUri | java.lang.String | URI схемы пакета. |

**Returns:**
boolean - Возвращает true, если пакет с указанным URI пространства имен существует в обёртке XMP.
### deepClone_internalized() {#deepClone-internalized--}
```
public final XmpPacketWrapper deepClone_internalized()
```


Клонирует этот экземпляр.

**Returns:**
[XmpPacketWrapper](../../com.aspose.psd.xmp/xmppacketwrapper) - The cloned object
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getHeaderPi() {#getHeaderPi--}
```
public XmpHeaderPi getHeaderPi()
```


Получает инструкцию обработки заголовка.

**Returns:**
[XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) - The Header processing instruction.
### getMeta() {#getMeta--}
```
public XmpMeta getMeta()
```


Получает метаданные XMP. Необязательно.

**Returns:**
[XmpMeta](../../com.aspose.psd.xmp/xmpmeta) - The XMP meta. Optional.
### getPackage(String namespaceUri) {#getPackage-java.lang.String-}
```
public XmpPackage getPackage(String namespaceUri)
```


Получает пакет по URI пространства имён.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| namespaceUri | java.lang.String | URI схемы пакета. |

**Returns:**
[XmpPackage](../../com.aspose.psd.xmp/xmppackage) - Returns the XMP package for specified namespace URI.
### getPackages() {#getPackages--}
```
public XmpPackage[] getPackages()
```


Получает массив  XmpPackage  внутри XMP.

**Returns:**
com.aspose.psd.xmp.XmpPackage[] - Массив XmpPackage внутри XMP.
### getPackagesCount() {#getPackagesCount--}
```
public int getPackagesCount()
```


Получает количество пакетов внутри структуры XMP.

**Returns:**
int - Количество пакетов внутри структуры XMP.
### getRdfRoot_internalized() {#getRdfRoot-internalized--}
```
public XmpRdfRoot getRdfRoot_internalized()
```


Получает корневой элемент RDF.

**Returns:**
[XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) - The RDF root element.
### getTrailerPi() {#getTrailerPi--}
```
public XmpTrailerPi getTrailerPi()
```


Получает инструкцию обработки трейлера.

**Returns:**
[XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) - Trailer processing instruction.
### getXmlValue_internalized() {#getXmlValue-internalized--}
```
public String getXmlValue_internalized()
```


Преобразует значение XMP в представление XML.

**Returns:**
java.lang.String - Возвращает преобразованное значение XMP в XML.
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




### removePackage(XmpPackage package_) {#removePackage-com.aspose.psd.xmp.XmpPackage-}
```
public void removePackage(XmpPackage package_)
```


Удаляет пакет XMP.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| package_ | [XmpPackage](../../com.aspose.psd.xmp/xmppackage) | Пакет. |

### setHeaderPi(XmpHeaderPi value) {#setHeaderPi-com.aspose.psd.xmp.XmpHeaderPi-}
```
public void setHeaderPi(XmpHeaderPi value)
```


Устанавливает инструкцию обработки заголовка.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XmpHeaderPi](../../com.aspose.psd.xmp/xmpheaderpi) | Инструкция обработки Header. |

### setMeta(XmpMeta value) {#setMeta-com.aspose.psd.xmp.XmpMeta-}
```
public void setMeta(XmpMeta value)
```


Устанавливает метаданные XMP. Необязательно.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XmpMeta](../../com.aspose.psd.xmp/xmpmeta) | Метаданные XMP. Необязательно. |

### setRdfRoot_internalized(XmpRdfRoot value) {#setRdfRoot-internalized-com.aspose.psd.xmp.XmpRdfRoot-}
```
public void setRdfRoot_internalized(XmpRdfRoot value)
```


Устанавливает корневой элемент RDF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XmpRdfRoot](../../com.aspose.psd.xmp/xmprdfroot) | Корневой элемент RDF. |

### setTrailerPi(XmpTrailerPi value) {#setTrailerPi-com.aspose.psd.xmp.XmpTrailerPi-}
```
public void setTrailerPi(XmpTrailerPi value)
```


Устанавливает инструкцию обработки трейлера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [XmpTrailerPi](../../com.aspose.psd.xmp/xmptrailerpi) | Инструкция обработки трейлера. |

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

