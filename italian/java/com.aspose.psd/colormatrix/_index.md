---
title: "ColorMatrix"
second_title: "Riferimento API Aspose.PSD per Java"
description: "Definisce una matrice 5 x 5 che contiene le coordinate per lo spazio RGBA."
type: docs
weight: 25
url: /it/java/com.aspose.psd/colormatrix/
---

**Inheritance:**
java.lang.Object
```
public final class ColorMatrix
```

Definisce una matrice 5 x 5 che contiene le coordinate per lo spazio RGBA. Diversi metodi della classe com.aspose.psd.ImageAttributes regolano i colori dell'immagine usando una matrice di colori. Questa classe non può essere ereditata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ColorMatrix()](#ColorMatrix--) | Inizializza una nuova istanza della classe Aspose.Imaging.ColorMatrix. |
| [ColorMatrix(float[][] newColorMatrix)](#ColorMatrix-float-----) | Inizializza una nuova istanza della classe Aspose.Imaging.ColorMatrix usando gli elementi nella matrice specificata newColorMatrix. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [MatrixDimensionElementsCount](#MatrixDimensionElementsCount) | Il numero di elementi nella dimensione della matrice. |
| [MatrixDimensionsCount](#MatrixDimensionsCount) | Il numero di dimensioni della matrice. |
| [MatrixTotalElementsCount](#MatrixTotalElementsCount) | Il numero totale di elementi nella matrice. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMatrix()](#getMatrix--) | Ottiene i valori della matrice. |
| [getMatrix00()](#getMatrix00--) | Ottiene l'elemento alla riga 0 (zero) e colonna 0 di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix01()](#getMatrix01--) | Ottiene l'elemento alla riga 0 (zero) e prima colonna di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix02()](#getMatrix02--) | Ottiene l'elemento alla riga 0 (zero) e seconda colonna di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix03()](#getMatrix03--) | Ottiene l'elemento alla riga 0 (zero) e terza colonna di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix04()](#getMatrix04--) | Ottiene l'elemento alla riga 0 (zero) e quarta colonna di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix10()](#getMatrix10--) | Ottiene l'elemento alla prima riga e colonna 0 (zero) di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix11()](#getMatrix11--) | Ottiene l'elemento alla prima riga e prima colonna di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix12()](#getMatrix12--) | Ottiene l'elemento alla prima riga e seconda colonna di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix13()](#getMatrix13--) | Ottiene l'elemento alla prima riga e terza colonna di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix14()](#getMatrix14--) | Ottiene l'elemento alla prima riga e quarta colonna di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix20()](#getMatrix20--) | Ottiene l'elemento alla seconda riga e colonna 0 (zero) di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix21()](#getMatrix21--) | Ottiene l'elemento alla seconda riga e prima colonna di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix22()](#getMatrix22--) | Ottiene l'elemento alla seconda riga e seconda colonna di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix23()](#getMatrix23--) | Ottiene l'elemento alla seconda riga e terza colonna di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix24()](#getMatrix24--) | Ottiene l'elemento alla seconda riga e quarta colonna di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix30()](#getMatrix30--) | Ottiene l'elemento alla terza riga e colonna 0 (zero) di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix31()](#getMatrix31--) | Ottiene l'elemento alla terza riga e prima colonna di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix32()](#getMatrix32--) | Ottiene l'elemento alla terza riga e seconda colonna di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix33()](#getMatrix33--) | Ottiene l'elemento alla terza riga e terza colonna di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix34()](#getMatrix34--) | Ottiene l'elemento alla terza riga e quarta colonna di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix40()](#getMatrix40--) | Ottiene l'elemento alla quarta riga e colonna 0 (zero) di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix41()](#getMatrix41--) | Ottiene l'elemento alla quarta riga e prima colonna di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix42()](#getMatrix42--) | Ottiene l'elemento alla quarta riga e seconda colonna di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix43()](#getMatrix43--) | Ottiene l'elemento alla quarta riga e terza colonna di questo Aspose.Imaging.ColorMatrix. |
| [getMatrix44()](#getMatrix44--) | Ottiene l'elemento alla quarta riga e quarta colonna di questo Aspose.Imaging.ColorMatrix. |
| [get_Item(int row, int column)](#get-Item-int-int-) | Ottiene l'elemento alla riga e colonna specificate nella Aspose.Imaging.ColorMatrix. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMatrix00(float value)](#setMatrix00-float-) | Imposta l'elemento alla riga 0 (zero) e colonna 0 di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix01(float value)](#setMatrix01-float-) | Imposta l'elemento alla riga 0 (zero) e prima colonna di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix02(float value)](#setMatrix02-float-) | Imposta l'elemento alla riga 0 (zero) e seconda colonna di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix03(float value)](#setMatrix03-float-) | Imposta l'elemento alla riga 0 (zero) e terza colonna di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix04(float value)](#setMatrix04-float-) | Imposta l'elemento alla riga 0 (zero) e quarta colonna di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix10(float value)](#setMatrix10-float-) | Imposta l'elemento alla prima riga e colonna 0 (zero) di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix11(float value)](#setMatrix11-float-) | Imposta l'elemento alla prima riga e prima colonna di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix12(float value)](#setMatrix12-float-) | Imposta l'elemento alla prima riga e seconda colonna di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix13(float value)](#setMatrix13-float-) | Imposta l'elemento alla prima riga e terza colonna di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix14(float value)](#setMatrix14-float-) | Imposta l'elemento alla prima riga e quarta colonna di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix20(float value)](#setMatrix20-float-) | Imposta l'elemento alla seconda riga e colonna 0 (zero) di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix21(float value)](#setMatrix21-float-) | Imposta l'elemento alla seconda riga e prima colonna di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix22(float value)](#setMatrix22-float-) | Imposta l'elemento alla seconda riga e seconda colonna di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix23(float value)](#setMatrix23-float-) | Imposta l'elemento alla seconda riga e terza colonna di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix24(float value)](#setMatrix24-float-) | Imposta l'elemento alla seconda riga e quarta colonna di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix30(float value)](#setMatrix30-float-) | Imposta l'elemento alla terza riga e colonna 0 (zero) di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix31(float value)](#setMatrix31-float-) | Imposta l'elemento alla terza riga e prima colonna di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix32(float value)](#setMatrix32-float-) | Imposta l'elemento alla terza riga e seconda colonna di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix33(float value)](#setMatrix33-float-) | Imposta l'elemento alla terza riga e terza colonna di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix34(float value)](#setMatrix34-float-) | Imposta l'elemento alla terza riga e quarta colonna di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix40(float value)](#setMatrix40-float-) | Imposta l'elemento alla quarta riga e colonna 0 (zero) di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix41(float value)](#setMatrix41-float-) | Imposta l'elemento alla quarta riga e prima colonna di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix42(float value)](#setMatrix42-float-) | Imposta l'elemento alla quarta riga e seconda colonna di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix43(float value)](#setMatrix43-float-) | Imposta l'elemento alla quarta riga e terza colonna di questo Aspose.Imaging.ColorMatrix. |
| [setMatrix44(float value)](#setMatrix44-float-) | Imposta l'elemento alla quarta riga e quarta colonna di questo Aspose.Imaging.ColorMatrix. |
| [set_Item(int row, int column, float value)](#set-Item-int-int-float-) | Imposta l'elemento alla riga e colonna specificate in questo Aspose.Imaging.ColorMatrix. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ColorMatrix() {#ColorMatrix--}
```
public ColorMatrix()
```


Inizializza una nuova istanza della classe Aspose.Imaging.ColorMatrix.

### ColorMatrix(float[][] newColorMatrix) {#ColorMatrix-float-----}
```
public ColorMatrix(float[][] newColorMatrix)
```


Inizializza una nuova istanza della classe Aspose.Imaging.ColorMatrix usando gli elementi nella matrice specificata newColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newColorMatrix | float[][] | I valori degli elementi per il nuovo Aspose.Imaging.ColorMatrix. |

### MatrixDimensionElementsCount {#MatrixDimensionElementsCount}
```
public static final int MatrixDimensionElementsCount
```


Il numero di elementi nella dimensione della matrice.

### MatrixDimensionsCount {#MatrixDimensionsCount}
```
public static final int MatrixDimensionsCount
```


Il numero di dimensioni della matrice.

### MatrixTotalElementsCount {#MatrixTotalElementsCount}
```
public static final int MatrixTotalElementsCount
```


Il numero totale di elementi nella matrice.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
### getMatrix() {#getMatrix--}
```
public float[][] getMatrix()
```


Ottiene i valori della matrice.

**Returns:**
float[][] - L'array dei valori della matrice.
### getMatrix00() {#getMatrix00--}
```
public float getMatrix00()
```


Ottiene l'elemento alla riga 0 (zero) e colonna 0 di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla riga 0 e colonna 0 di questo Aspose.Imaging.ColorMatrix.
### getMatrix01() {#getMatrix01--}
```
public float getMatrix01()
```


Ottiene l'elemento alla riga 0 (zero) e prima colonna di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla riga 0 e prima colonna di questo Aspose.Imaging.ColorMatrix.
### getMatrix02() {#getMatrix02--}
```
public float getMatrix02()
```


Ottiene l'elemento alla riga 0 (zero) e seconda colonna di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla riga 0 e seconda colonna di questo Aspose.Imaging.ColorMatrix.
### getMatrix03() {#getMatrix03--}
```
public float getMatrix03()
```


Ottiene l'elemento alla riga 0 (zero) e terza colonna di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla riga 0 e terza colonna di questo Aspose.Imaging.ColorMatrix.
### getMatrix04() {#getMatrix04--}
```
public float getMatrix04()
```


Ottiene l'elemento alla riga 0 (zero) e quarta colonna di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla riga 0 e quarta colonna di questo Aspose.Imaging.ColorMatrix.
### getMatrix10() {#getMatrix10--}
```
public float getMatrix10()
```


Ottiene l'elemento alla prima riga e colonna 0 (zero) di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla prima riga e colonna 0 di questo Aspose.Imaging.ColorMatrix.
### getMatrix11() {#getMatrix11--}
```
public float getMatrix11()
```


Ottiene l'elemento alla prima riga e prima colonna di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla prima riga e prima colonna di questo Aspose.Imaging.ColorMatrix.
### getMatrix12() {#getMatrix12--}
```
public float getMatrix12()
```


Ottiene l'elemento alla prima riga e seconda colonna di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla prima riga e seconda colonna di questo Aspose.Imaging.ColorMatrix.
### getMatrix13() {#getMatrix13--}
```
public float getMatrix13()
```


Ottiene l'elemento alla prima riga e terza colonna di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla prima riga e terza colonna di questo Aspose.Imaging.ColorMatrix.
### getMatrix14() {#getMatrix14--}
```
public float getMatrix14()
```


Ottiene l'elemento alla prima riga e quarta colonna di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla prima riga e quarta colonna di questo Aspose.Imaging.ColorMatrix.
### getMatrix20() {#getMatrix20--}
```
public float getMatrix20()
```


Ottiene l'elemento alla seconda riga e colonna 0 (zero) di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla seconda riga e colonna 0 di questo Aspose.Imaging.ColorMatrix.
### getMatrix21() {#getMatrix21--}
```
public float getMatrix21()
```


Ottiene l'elemento alla seconda riga e prima colonna di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla seconda riga e prima colonna di questo Aspose.Imaging.ColorMatrix.
### getMatrix22() {#getMatrix22--}
```
public float getMatrix22()
```


Ottiene l'elemento alla seconda riga e seconda colonna di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla seconda riga e seconda colonna di questo Aspose.Imaging.ColorMatrix.
### getMatrix23() {#getMatrix23--}
```
public float getMatrix23()
```


Ottiene l'elemento alla seconda riga e terza colonna di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla seconda riga e terza colonna di questo Aspose.Imaging.ColorMatrix.
### getMatrix24() {#getMatrix24--}
```
public float getMatrix24()
```


Ottiene l'elemento alla seconda riga e quarta colonna di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla seconda riga e quarta colonna di questo Aspose.Imaging.ColorMatrix.
### getMatrix30() {#getMatrix30--}
```
public float getMatrix30()
```


Ottiene l'elemento alla terza riga e colonna 0 (zero) di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla terza riga e colonna 0 di questo Aspose.Imaging.ColorMatrix.
### getMatrix31() {#getMatrix31--}
```
public float getMatrix31()
```


Ottiene l'elemento alla terza riga e prima colonna di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla terza riga e prima colonna di questo **Aspose.Imaging.ColorMatrix**.
### getMatrix32() {#getMatrix32--}
```
public float getMatrix32()
```


Ottiene l'elemento alla terza riga e seconda colonna di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla terza riga e seconda colonna di questo **Aspose.Imaging.ColorMatrix**.
### getMatrix33() {#getMatrix33--}
```
public float getMatrix33()
```


Ottiene l'elemento alla terza riga e terza colonna di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla terza riga e terza colonna di questo **Aspose.Imaging.ColorMatrix**.
### getMatrix34() {#getMatrix34--}
```
public float getMatrix34()
```


Ottiene l'elemento alla terza riga e quarta colonna di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla terza riga e quarta colonna di questo **Aspose.Imaging.ColorMatrix**.
### getMatrix40() {#getMatrix40--}
```
public float getMatrix40()
```


Ottiene l'elemento alla quarta riga e colonna 0 (zero) di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla quarta riga e colonna 0 di questo **Aspose.Imaging.ColorMatrix**.
### getMatrix41() {#getMatrix41--}
```
public float getMatrix41()
```


Ottiene l'elemento alla quarta riga e prima colonna di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla quarta riga e prima colonna di questo **Aspose.Imaging.ColorMatrix**.
### getMatrix42() {#getMatrix42--}
```
public float getMatrix42()
```


Ottiene l'elemento alla quarta riga e seconda colonna di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla quarta riga e seconda colonna di questo **Aspose.Imaging.ColorMatrix**.
### getMatrix43() {#getMatrix43--}
```
public float getMatrix43()
```


Ottiene l'elemento alla quarta riga e terza colonna di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla quarta riga e terza colonna di questo **Aspose.Imaging.ColorMatrix**.
### getMatrix44() {#getMatrix44--}
```
public float getMatrix44()
```


Ottiene l'elemento alla quarta riga e quarta colonna di questo Aspose.Imaging.ColorMatrix.

**Returns:**
float - L'elemento alla quarta riga e quarta colonna di questo **Aspose.Imaging.ColorMatrix**.
### get_Item(int row, int column) {#get-Item-int-int-}
```
public float get_Item(int row, int column)
```


Ottiene l'elemento alla riga e colonna specificate nella Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| riga | int | Il numero della riga. |
| colonna | int | Il numero della colonna. |

**Returns:**
float - L'elemento alla riga e colonna specificate.
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




### setMatrix00(float value) {#setMatrix00-float-}
```
public void setMatrix00(float value)
```


Imposta l'elemento alla riga 0 (zero) e colonna 0 di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla riga 0 e colonna 0 di questo **Aspose.Imaging.ColorMatrix**. |

### setMatrix01(float value) {#setMatrix01-float-}
```
public void setMatrix01(float value)
```


Imposta l'elemento alla riga 0 (zero) e prima colonna di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla riga 0 e prima colonna di questo **Aspose.Imaging.ColorMatrix**. |

### setMatrix02(float value) {#setMatrix02-float-}
```
public void setMatrix02(float value)
```


Imposta l'elemento alla riga 0 (zero) e seconda colonna di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla riga 0 e seconda colonna di questo **Aspose.Imaging.ColorMatrix**. |

### setMatrix03(float value) {#setMatrix03-float-}
```
public void setMatrix03(float value)
```


Imposta l'elemento alla riga 0 (zero) e terza colonna di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla riga 0 e terza colonna di questo **Aspose.Imaging.ColorMatrix**. |

### setMatrix04(float value) {#setMatrix04-float-}
```
public void setMatrix04(float value)
```


Imposta l'elemento alla riga 0 (zero) e quarta colonna di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla riga 0 e quarta colonna di questo **Aspose.Imaging.ColorMatrix**. |

### setMatrix10(float value) {#setMatrix10-float-}
```
public void setMatrix10(float value)
```


Imposta l'elemento alla prima riga e colonna 0 (zero) di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla prima riga e colonna 0 di questo **Aspose.Imaging.ColorMatrix**. |

### setMatrix11(float value) {#setMatrix11-float-}
```
public void setMatrix11(float value)
```


Imposta l'elemento alla prima riga e prima colonna di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla prima riga e prima colonna di questo **Aspose.Imaging.ColorMatrix**. |

### setMatrix12(float value) {#setMatrix12-float-}
```
public void setMatrix12(float value)
```


Imposta l'elemento alla prima riga e seconda colonna di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla prima riga e seconda colonna di questo **Aspose.Imaging.ColorMatrix**. |

### setMatrix13(float value) {#setMatrix13-float-}
```
public void setMatrix13(float value)
```


Imposta l'elemento alla prima riga e terza colonna di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla prima riga e terza colonna di questo **Aspose.Imaging.ColorMatrix**. |

### setMatrix14(float value) {#setMatrix14-float-}
```
public void setMatrix14(float value)
```


Imposta l'elemento alla prima riga e quarta colonna di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla prima riga e quarta colonna di questo **Aspose.Imaging.ColorMatrix**. |

### setMatrix20(float value) {#setMatrix20-float-}
```
public void setMatrix20(float value)
```


Imposta l'elemento alla seconda riga e colonna 0 (zero) di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla seconda riga e colonna 0 di questo **Aspose.Imaging.ColorMatrix**. |

### setMatrix21(float value) {#setMatrix21-float-}
```
public void setMatrix21(float value)
```


Imposta l'elemento alla seconda riga e prima colonna di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla seconda riga e prima colonna di questa  Aspose.Imaging.ColorMatrix . |

### setMatrix22(float value) {#setMatrix22-float-}
```
public void setMatrix22(float value)
```


Imposta l'elemento alla seconda riga e seconda colonna di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla seconda riga e seconda colonna di questa  Aspose.Imaging.ColorMatrix . |

### setMatrix23(float value) {#setMatrix23-float-}
```
public void setMatrix23(float value)
```


Imposta l'elemento alla seconda riga e terza colonna di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla seconda riga e terza colonna di questa  Aspose.Imaging.ColorMatrix . |

### setMatrix24(float value) {#setMatrix24-float-}
```
public void setMatrix24(float value)
```


Imposta l'elemento alla seconda riga e quarta colonna di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla seconda riga e quarta colonna di questa  Aspose.Imaging.ColorMatrix . |

### setMatrix30(float value) {#setMatrix30-float-}
```
public void setMatrix30(float value)
```


Imposta l'elemento alla terza riga e colonna 0 (zero) di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla terza riga e colonna 0 di questa  Aspose.Imaging.ColorMatrix . |

### setMatrix31(float value) {#setMatrix31-float-}
```
public void setMatrix31(float value)
```


Imposta l'elemento alla terza riga e prima colonna di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla terza riga e prima colonna di questa  Aspose.Imaging.ColorMatrix . |

### setMatrix32(float value) {#setMatrix32-float-}
```
public void setMatrix32(float value)
```


Imposta l'elemento alla terza riga e seconda colonna di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla terza riga e seconda colonna di questa  Aspose.Imaging.ColorMatrix . |

### setMatrix33(float value) {#setMatrix33-float-}
```
public void setMatrix33(float value)
```


Imposta l'elemento alla terza riga e terza colonna di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla terza riga e terza colonna di questa  Aspose.Imaging.ColorMatrix . |

### setMatrix34(float value) {#setMatrix34-float-}
```
public void setMatrix34(float value)
```


Imposta l'elemento alla terza riga e quarta colonna di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla terza riga e quarta colonna di questa  Aspose.Imaging.ColorMatrix . |

### setMatrix40(float value) {#setMatrix40-float-}
```
public void setMatrix40(float value)
```


Imposta l'elemento alla quarta riga e colonna 0 (zero) di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla quarta riga e colonna 0 di questa  Aspose.Imaging.ColorMatrix . |

### setMatrix41(float value) {#setMatrix41-float-}
```
public void setMatrix41(float value)
```


Imposta l'elemento alla quarta riga e prima colonna di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla quarta riga e prima colonna di questa  Aspose.Imaging.ColorMatrix . |

### setMatrix42(float value) {#setMatrix42-float-}
```
public void setMatrix42(float value)
```


Imposta l'elemento alla quarta riga e seconda colonna di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla quarta riga e seconda colonna di questa  Aspose.Imaging.ColorMatrix . |

### setMatrix43(float value) {#setMatrix43-float-}
```
public void setMatrix43(float value)
```


Imposta l'elemento alla quarta riga e terza colonna di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla quarta riga e terza colonna di questa  Aspose.Imaging.ColorMatrix . |

### setMatrix44(float value) {#setMatrix44-float-}
```
public void setMatrix44(float value)
```


Imposta l'elemento alla quarta riga e quarta colonna di questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | L'elemento alla quarta riga e quarta colonna di questa  Aspose.Imaging.ColorMatrix . |

### set_Item(int row, int column, float value) {#set-Item-int-int-float-}
```
public void set_Item(int row, int column, float value)
```


Imposta l'elemento alla riga e colonna specificate in questo Aspose.Imaging.ColorMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| riga | int | Il numero della riga. |
| colonna | int | Il numero della colonna. |
| valore | float | Il valore |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

