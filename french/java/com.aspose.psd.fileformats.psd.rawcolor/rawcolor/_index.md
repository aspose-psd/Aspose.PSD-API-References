---
title: "RawColor"
second_title: "Référence de l'API Aspose.PSD pour Java"
description: "La classe Raw Color aide à stocker les couleurs avec n'importe quel nombre de canaux, n'importe quel mode couleur et n'importe quelle profondeur de bits. Veuillez noter que certaines classes internes peuvent rencontrer des problèmes lors de la conversion de RawColor vers son format natif, donc si l'API vous fournit une couleur CMYK, il est plus fiable d'utiliser le format fourni."
type: docs
weight: 11
url: /fr/java/com.aspose.psd.fileformats.psd.rawcolor/rawcolor/
---

**Inheritance:**
java.lang.Object
```
public final class RawColor
```

La classe Raw Color aide à stocker les couleurs avec n'importe quel nombre de canaux, n'importe quel mode couleur et n'importe quelle profondeur de bits. Veuillez noter que certaines classes internes peuvent rencontrer des problèmes lors de la conversion de RawColor vers son format natif, donc si l'API vous fournit une couleur CMYK, il est plus fiable d'utiliser le format fourni. De plus, il peut y avoir certains cas où Raw Color peut être converti.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RawColor(ColorComponent[] components)](#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---) | Initialise une nouvelle instance de la classe [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor). |
| [RawColor(PixelDataFormat pixelDataFormat)](#RawColor-com.aspose.psd.PixelDataFormat-) |  |
| [RawColor(PixelDataFormat pixelDataFormat, short colorMode)](#RawColor-com.aspose.psd.PixelDataFormat-short-) | Initialise une nouvelle instance de la classe [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) à partir du format de données de pixel en utilisant des modes couleur prédéfinis. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Détermine si l'Objet spécifié est égal à cette instance. |
| [getAsInt()](#getAsInt--) | Obtient la couleur en tant qu'int si cela est possible. |
| [getAsLong()](#getAsLong--) | Obtient la couleur en tant que long si cela est possible. |
| [getBitDepth()](#getBitDepth--) | Obtient la profondeur de bits de Raw Color. |
| [getClass()](#getClass--) |  |
| [getColorMode()](#getColorMode--) | Mode que la couleur doit suivre. |
| [getColorModeName()](#getColorModeName--) | Obtient le nom du mode couleur. |
| [getComponents()](#getComponents--) | Obtient les composants de la couleur. |
| [hashCode()](#hashCode--) | Obtient le code de hachage de l'objet actuel. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(RawColor left, RawColor right)](#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Implémente l'opérateur ==. |
| [op_Inequality(RawColor left, RawColor right)](#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-) | Implémente l'opérateur !=. |
| [setAsInt(int value)](#setAsInt-int-) | Définit les données de tous les canaux à partir d'un argument int si possible. |
| [setAsLong(long value)](#setAsLong-long-) | Définit les données de tous les canaux à partir d'un argument int si possible. |
| [setColorMode(short value)](#setColorMode-short-) | Mode que la couleur doit suivre. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RawColor(ColorComponent[] components) {#RawColor-com.aspose.psd.fileformats.psd.rawcolor.ColorComponent---}
```
public RawColor(ColorComponent[] components)
```


Initialise une nouvelle instance de la classe [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| components | [ColorComponent\[\]](../../com.aspose.psd.fileformats.psd.rawcolor/colorcomponent) | Les composants de couleur personnalisés. |

### RawColor(PixelDataFormat pixelDataFormat) {#RawColor-com.aspose.psd.PixelDataFormat-}
```
public RawColor(PixelDataFormat pixelDataFormat)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) |  |

### RawColor(PixelDataFormat pixelDataFormat, short colorMode) {#RawColor-com.aspose.psd.PixelDataFormat-short-}
```
public RawColor(PixelDataFormat pixelDataFormat, short colorMode)
```


Initialise une nouvelle instance de la classe [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) à partir du format de données de pixel en utilisant des modes couleur prédéfinis.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixelDataFormat | [PixelDataFormat](../../com.aspose.psd/pixeldataformat) | Le format des données pixel. |
| colorMode | short |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si l'Objet spécifié est égal à cette instance.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | L'objet à comparer avec cette instance. |

**Returns:**
booléen -  true  si l'objet spécifié est égal à cette instance ; sinon,  false .
### getAsInt() {#getAsInt--}
```
public final int getAsInt()
```


Obtient la couleur en tant qu'int si cela est possible.

**Returns:**
int - Données des canaux stockées en Int
### getAsLong() {#getAsLong--}
```
public final long getAsLong()
```


Obtient la couleur en tant que long si cela est possible.

**Returns:**
long - Données des canaux stockées en Int
### getBitDepth() {#getBitDepth--}
```
public final int getBitDepth()
```


Obtient la profondeur de bits de Raw Color. Par exemple, pour une couleur ARGB avec 8 bits par canal/composant, la profondeur de bits est de 32. La profondeur de bits d'une couleur ARGB complète avec 16 bits par canal/composant est de 64. La profondeur de bits est accumulée à partir de la somme des profondeurs de bits des canaux. C'est possible si différents canaux ont des profondeurs de bits différentes.

**Returns:**
int - La somme des profondeurs de bits de tous les canaux
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorMode() {#getColorMode--}
```
public final short getColorMode()
```


Mode que la couleur doit suivre.

**Returns:**
short
### getColorModeName() {#getColorModeName--}
```
public final String getColorModeName()
```


Obtient le nom du mode couleur. Le nom du mode couleur est accumulé à partir des noms des canaux/composants.

**Returns:**
java.lang.String - Chaîne avec le nom du mode couleur
### getComponents() {#getComponents--}
```
public final ColorComponent[] getComponents()
```


Obtient les composants de couleur. Chaque composant est un canal séparé, et si vous utilisez un schéma de couleur peu répandu, il vaut mieux travailler avec chaque canal séparément

Valeur : Les composants de couleur

**Returns:**
com.aspose.psd.fileformats.psd.rawcolor.ColorComponent[]
### hashCode() {#hashCode--}
```
public int hashCode()
```


Obtient le code de hachage de l'objet actuel.

**Returns:**
int - Le code de hachage.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(RawColor left, RawColor right) {#op-Equality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Equality(RawColor left, RawColor right)
```


Implémente l'opérateur ==.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Le premier RawColor. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Le deuxième RawColor. |

**Returns:**
boolean - Le résultat de l'opérateur.
### op_Inequality(RawColor left, RawColor right) {#op-Inequality-com.aspose.psd.fileformats.psd.rawcolor.RawColor-com.aspose.psd.fileformats.psd.rawcolor.RawColor-}
```
public static boolean op_Inequality(RawColor left, RawColor right)
```


Implémente l'opérateur !=.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| left | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Le premier RawColor. |
| right | [RawColor](../../com.aspose.psd.fileformats.psd.rawcolor/rawcolor) | Le deuxième RawColor. |

**Returns:**
boolean - Le résultat de l'opérateur.
### setAsInt(int value) {#setAsInt-int-}
```
public final void setAsInt(int value)
```


Définit les données de tous les canaux à partir d'un argument int si possible.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | La valeur int qui contient les données du composant |

### setAsLong(long value) {#setAsLong-long-}
```
public final void setAsLong(long value)
```


Définit les données de tous les canaux à partir d'un argument int si possible.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | long | La valeur int qui contient les données du composant |

### setColorMode(short value) {#setColorMode-short-}
```
public final void setColorMode(short value)
```


Mode que la couleur doit suivre.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | short |  |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

