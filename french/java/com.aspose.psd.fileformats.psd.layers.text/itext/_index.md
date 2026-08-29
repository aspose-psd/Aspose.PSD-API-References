---
title: "IText"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "Interface pour l'édition de texte pour les calques de texte"
type: docs
weight: 11
url: /fr/java/com.aspose.psd.fileformats.psd.layers.text/itext/
---
```
public interface IText
```

Interface pour l'édition de texte pour les calques de texte
## Méthodes

| Méthode | Description |
| --- | --- |
| [addPortion(ITextPortion portion)](#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-) | Ajoute la portion de texte à la fin |
| [getItems()](#getItems--) | Obtient les éléments. |
| [getText()](#getText--) | Obtient le texte. |
| [getTextOrientation()](#getTextOrientation--) | Obtient ou définit l'orientation du texte. |
| [insertPortion(ITextPortion portion, int index)](#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-) | Insère le [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) à la position spécifiée |
| [producePortion()](#producePortion--) | Produit la nouvelle portion avec les paramètres par défaut |
| [producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)](#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-) | Produit les nouvelles portions avec les paramètres d'entrée ou par défaut. |
| [removePortion(int index)](#removePortion-int-) | Supprime la portion à l'index spécifié |
| [setTextOrientation(int value)](#setTextOrientation-int-) | Obtient ou définit l'orientation du texte. |
| [updateLayerData()](#updateLayerData--) | Met à jour les données du calque. |
### addPortion(ITextPortion portion) {#addPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-}
```
public abstract void addPortion(ITextPortion portion)
```


Ajoute la portion de texte à la fin

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | La portion. |

### getItems() {#getItems--}
```
public abstract ITextPortion[] getItems()
```


Obtient les éléments.

Valeur: les éléments.

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[]
### getText() {#getText--}
```
public abstract String getText()
```


Obtient le texte.

Valeur : le texte.

**Returns:**
java.lang.String
### getTextOrientation() {#getTextOrientation--}
```
public abstract int getTextOrientation()
```


Obtient ou définit l'orientation du texte.

Valeur: l'orientation du texte.

**Returns:**
int
### insertPortion(ITextPortion portion, int index) {#insertPortion-com.aspose.psd.fileformats.psd.layers.text.ITextPortion-int-}
```
public abstract void insertPortion(ITextPortion portion, int index)
```


Insère le [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) à la position spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| portion | [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) | La portion. |
| index | int | L'index. |

### producePortion() {#producePortion--}
```
public abstract ITextPortion producePortion()
```


Produit la nouvelle portion avec les paramètres par défaut

**Returns:**
[ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion) - Reference to newly created [ITextPortion](../../com.aspose.psd.fileformats.psd.layers.text/itextportion).
### producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype) {#producePortions-java.lang.String---com.aspose.psd.fileformats.psd.layers.text.ITextStyle-com.aspose.psd.fileformats.psd.layers.text.ITextParagraph-}
```
public abstract ITextPortion[] producePortions(String[] portionsOfText, ITextStyle stylePrototype, ITextParagraph paragraphPrototype)
```


Produit les nouvelles portions avec les paramètres d'entrée ou par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| portionsOfText | java.lang.String[] | Les portions de texte pour créer un nouveau ITextPortion. |
| stylePrototype | [ITextStyle](../../com.aspose.psd.fileformats.psd.layers.text/itextstyle) | Un style qui, s'il n'est pas nul, sera appliqué dans le nouveau   , sinon sera par défaut. |
| paragraphPrototype | [ITextParagraph](../../com.aspose.psd.fileformats.psd.layers.text/itextparagraph) | Un paragraphe qui, s'il n'est pas nul, sera appliqué dans le nouveau   , sinon sera par défaut. |

**Returns:**
com.aspose.psd.fileformats.psd.layers.text.ITextPortion[] - Retourne les nouvelles portions ITextPortion basées sur les paramètres d'entrée.
### removePortion(int index) {#removePortion-int-}
```
public abstract void removePortion(int index)
```


Supprime la portion à l'index spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | L'index. |

### setTextOrientation(int value) {#setTextOrientation-int-}
```
public abstract void setTextOrientation(int value)
```


Obtient ou définit l'orientation du texte.

Valeur: l'orientation du texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### updateLayerData() {#updateLayerData--}
```
public abstract void updateLayerData()
```


Met à jour les données du calque.

