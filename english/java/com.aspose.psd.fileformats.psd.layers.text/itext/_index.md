---
title: IText
second_title: Aspose.PSD for Java API Reference
description: Interface for Text Editing for Text Layers
type: docs
weight: 11
url: /java/com.aspose.psd.fileformats.psd.layers.text/itext/
---
```
public interface IText
```

Interface for Text Editing for Text Layers
## Methods

| Method | Description |
| --- | --- |
| [addPortion(ITextPortion portion)](#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-) | Adds the portion of text to the end |
| [getItems()](#getItems--) | Gets the items. |
| [getText()](#getText--) | Gets the text. |
| [getTextOrientation()](#getTextOrientation--) | Gets or sets the text orientation. |
| [insertPortion(ITextPortion portion, int index)](#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-) | Inserts the [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) to specified position |
| [producePortion()](#producePortion--) | Produces the new portion with default parameters |
| [producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)](#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Produces the new portions with input or default parameters. |
| [removePortion(int index)](#removePortion-int-) | Removes the portion in specified index |
| [setTextOrientation(int value)](#setTextOrientation-int-) | Gets or sets the text orientation. |
| [updateLayerData()](#updateLayerData--) | Updates the layer data. |
### addPortion(ITextPortion portion) {#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-}
```
public abstract void addPortion(ITextPortion portion)
```


Adds the portion of text to the end

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | The portion. |

### getItems() {#getItems--}
```
public abstract ITextPortion[] getItems()
```


Gets the items.

Value: The items.

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[]
### getText() {#getText--}
```
public abstract String getText()
```


Gets the text.

Value: The text.

**Returns:**
java.lang.String
### getTextOrientation() {#getTextOrientation--}
```
public abstract int getTextOrientation()
```


Gets or sets the text orientation.

Value: The text orientation.

**Returns:**
int
### insertPortion(ITextPortion portion, int index) {#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-}
```
public abstract void insertPortion(ITextPortion portion, int index)
```


Inserts the [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) to specified position

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | The portion. |
| index | int | The index. |

### producePortion() {#producePortion--}
```
public abstract ITextPortion producePortion()
```


Produces the new portion with default parameters

**Returns:**
[ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) - Reference to newly created [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion).
### producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype) {#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract ITextPortion[] producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)
```


Produces the new portions with input or default parameters.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| portionsOfText | java.lang.String[] | The portions of text to create new  ITextPortion . |
| stylePrototype | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | A style that, if not null, will be applied in the new   , otherwise will be default. |
| paragraphPrototype | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | A paragraph that, if not null, will be applied in the new   , otherwise will be default. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[] - Returns the new portions  ITextPortion  based on input parameters.
### removePortion(int index) {#removePortion-int-}
```
public abstract void removePortion(int index)
```


Removes the portion in specified index

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index. |

### setTextOrientation(int value) {#setTextOrientation-int-}
```
public abstract void setTextOrientation(int value)
```


Gets or sets the text orientation.

Value: The text orientation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### updateLayerData() {#updateLayerData--}
```
public abstract void updateLayerData()
```


Updates the layer data.

