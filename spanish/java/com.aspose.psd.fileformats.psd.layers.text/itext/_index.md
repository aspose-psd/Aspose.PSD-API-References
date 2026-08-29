---
title: "IText"
second_title: "Referencia de API de Aspose.PSD para Java"
description: "Interfaz para la edición de texto de capas de texto"
type: docs
weight: 11
url: /es/java/com.aspose.psd.fileformats.psd.layers.text/itext/
---
```
public interface IText
```

Interfaz para la edición de texto de capas de texto
## Métodos

| Método | Descripción |
| --- | --- |
| [addPortion(ITextPortion portion)](#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-) | Agrega la porción de texto al final |
| [getItems()](#getItems--) | Obtiene los elementos. |
| [getText()](#getText--) | Obtiene el texto. |
| [getTextOrientation()](#getTextOrientation--) | Obtiene o establece la orientación del texto. |
| [insertPortion(ITextPortion portion, int index)](#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-) | Inserta el [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) en la posición especificada |
| [producePortion()](#producePortion--) | Produce la nueva porción con parámetros predeterminados |
| [producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)](#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Produce las nuevas porciones con parámetros de entrada o predeterminados. |
| [removePortion(int index)](#removePortion-int-) | Elimina la porción en el índice especificado |
| [setTextOrientation(int value)](#setTextOrientation-int-) | Obtiene o establece la orientación del texto. |
| [updateLayerData()](#updateLayerData--) | Actualiza los datos de la capa. |
### addPortion(ITextPortion portion) {#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-}
```
public abstract void addPortion(ITextPortion portion)
```


Agrega la porción de texto al final

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | La porción. |

### getItems() {#getItems--}
```
public abstract ITextPortion[] getItems()
```


Obtiene los elementos.

Valor: los elementos.

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[]
### getText() {#getText--}
```
public abstract String getText()
```


Obtiene el texto.

Valor: El texto.

**Returns:**
java.lang.String
### getTextOrientation() {#getTextOrientation--}
```
public abstract int getTextOrientation()
```


Obtiene o establece la orientación del texto.

Valor: la orientación del texto.

**Returns:**
int
### insertPortion(ITextPortion portion, int index) {#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-}
```
public abstract void insertPortion(ITextPortion portion, int index)
```


Inserta el [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) en la posición especificada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | La porción. |
| índice | int | El índice. |

### producePortion() {#producePortion--}
```
public abstract ITextPortion producePortion()
```


Produce la nueva porción con parámetros predeterminados

**Returns:**
[ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) - Reference to newly created [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion).
### producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype) {#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract ITextPortion[] producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)
```


Produce las nuevas porciones con parámetros de entrada o predeterminados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| portionsOfText | java.lang.String[] | Las porciones de texto para crear una nueva ITextPortion. |
| stylePrototype | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Un estilo que, si no es nulo, se aplicará en el nuevo   , de lo contrario será predeterminado. |
| paragraphPrototype | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | Un párrafo que, si no es nulo, se aplicará en el nuevo   , de lo contrario será predeterminado. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[] - Devuelve las nuevas porciones ITextPortion basadas en los parámetros de entrada.
### removePortion(int index) {#removePortion-int-}
```
public abstract void removePortion(int index)
```


Elimina la porción en el índice especificado

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índice | int | El índice. |

### setTextOrientation(int value) {#setTextOrientation-int-}
```
public abstract void setTextOrientation(int value)
```


Obtiene o establece la orientación del texto.

Valor: la orientación del texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### updateLayerData() {#updateLayerData--}
```
public abstract void updateLayerData()
```


Actualiza los datos de la capa.

