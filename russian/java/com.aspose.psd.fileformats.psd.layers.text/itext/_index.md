---
title: "IText"
second_title: "Aspose.PSD for Java API Справочник"
description: "Интерфейс для редактирования текста в текстовых слоях."
type: docs
weight: 11
url: /ru/java/com.aspose.psd.fileformats.psd.layers.text/itext/
---
```
public interface IText
```

Интерфейс для редактирования текста в текстовых слоях.
## Методы

| Метод | Описание |
| --- | --- |
| [addPortion(ITextPortion portion)](#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-) | Добавляет часть текста в конец |
| [getItems()](#getItems--) | Получает элементы. |
| [getText()](#getText--) | Получает текст. |
| [getTextOrientation()](#getTextOrientation--) | Получает или задает ориентацию текста. |
| [insertPortion(ITextPortion portion, int index)](#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-) | Вставляет [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) в указанную позицию |
| [producePortion()](#producePortion--) | Создаёт новую часть с параметрами по умолчанию |
| [producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)](#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Создаёт новые части с заданными или параметрами по умолчанию. |
| [removePortion(int index)](#removePortion-int-) | Удаляет часть по указанному индексу |
| [setTextOrientation(int value)](#setTextOrientation-int-) | Получает или задает ориентацию текста. |
| [updateLayerData()](#updateLayerData--) | Обновляет данные слоя. |
### addPortion(ITextPortion portion) {#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-}
```
public abstract void addPortion(ITextPortion portion)
```


Добавляет часть текста в конец

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | Часть. |

### getItems() {#getItems--}
```
public abstract ITextPortion[] getItems()
```


Получает элементы.

Значение: элементы.

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[]
### getText() {#getText--}
```
public abstract String getText()
```


Получает текст.

Value: Текст.

**Returns:**
java.lang.String
### getTextOrientation() {#getTextOrientation--}
```
public abstract int getTextOrientation()
```


Получает или задает ориентацию текста.

Значение: ориентация текста.

**Returns:**
int
### insertPortion(ITextPortion portion, int index) {#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-}
```
public abstract void insertPortion(ITextPortion portion, int index)
```


Вставляет [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) в указанную позицию

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | Часть. |
| индекс | int | Индекс. |

### producePortion() {#producePortion--}
```
public abstract ITextPortion producePortion()
```


Создаёт новую часть с параметрами по умолчанию

**Returns:**
[ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) - Reference to newly created [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion).
### producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype) {#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract ITextPortion[] producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)
```


Создаёт новые части с заданными или параметрами по умолчанию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| portionsOfText | java.lang.String[] | Части текста для создания нового  ITextPortion . |
| stylePrototype | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Стиль, который, если не null, будет применён в новом   , иначе будет использоваться по умолчанию. |
| paragraphPrototype | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | Абзац, который, если не null, будет применён в новом   , иначе будет использоваться по умолчанию. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[] - Возвращает новые части  ITextPortion  на основе входных параметров.
### removePortion(int index) {#removePortion-int-}
```
public abstract void removePortion(int index)
```


Удаляет часть по указанному индексу

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int | Индекс. |

### setTextOrientation(int value) {#setTextOrientation-int-}
```
public abstract void setTextOrientation(int value)
```


Получает или задает ориентацию текста.

Значение: ориентация текста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### updateLayerData() {#updateLayerData--}
```
public abstract void updateLayerData()
```


Обновляет данные слоя.

